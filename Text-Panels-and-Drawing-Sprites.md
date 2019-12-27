Some time ago we finally got a way to make more advanced and pretty screens using the programmable block. These **sprites** are really designed for use with the new LCD Script system (the script menu you get for each LCD panel) but we were also given the ability to draw these sprites using the programmable block.


### Configuring Text Surfaces

Every block with modifiable text surfaces will slow a list of text surfaces in the control panel.  
![Text Surface List](images/textsurface-list.jpg)  
For the programmable block, there's two. The number and names will vary across different blocks.

To manually set up a text surface for sprite drawing, select the text surface you wish to draw on, then select `Script` in the Content drop box below the surface list. A new set of controls will show up below the Content drop box.  
![Text Surface Content](images/textsurface-content.jpg)  
The scripts listed in this list are _not_ programmable block scripts. They are special built-in (or modded) scripts that we cannot directly modify in-game. So, for our purposes, we want to make sure that we select `None`.
This will allow the programmable block to control the output of this text panel.

The sliders below control the background and foreground colors of the sprites. We will talk more about those later.

## Fetching Text Surfaces And Preparing The Script

In order to draw on a text surface, we need to retrieve it first. For the sake of this example, we will simply be working on the large text panel of the running programmable block, but the principle applies for all
blocks with scriptable text panels.

Every block with scriptable text panels implements the interface [`IMyTextSurfaceProvider`](Sandbox.ModAPI.Ingame.IMyTextSurfaceProvider). This interface contains the members we need to retrieve the text surface we 
want to draw on. We want to use the `GetSurface` method. It takes a single parameter, the index of the text surface to retrieve. These text surfaces are ordered the same way as we see in the list above, so in our
example we will want to retrieve the _first_ text panel, since that is the Large Display. Most indices in C# are 0-based, so we will want to retrieve surface 0.

The sprite system is designed to be continually updated. If you don't periodically update your display in sprite mode, it will fall back to the default image for that particular text surface. For this reason we need to set up [continuous execution of our script](Continuous-Running-No-Timers-Needed). For the sake of our simple demo script, we'll just update every 100 ticks. Update rates are maxed out at every 10 ticks for sprites, so updating _every_ tick is a waste of processing power.

```csharp
IMyTextSurface _drawingSurface;

// Script constructor
public Program()
{
    // Me is the programmable block which is running this script.
    // Retrieve the Large Display, which is the first surface
    _drawingSurface = Me.GetSurface(0);

    // Set the continuous update frequency of this script
    Runtime.UpdateFrequency = UpdateFrequency.Update100;
}
```

### Drawing A Frame

The drawing API is for all intents and purposes quite low level. You tell the surface that you wish to start a new frame, then you create and add a bunch of sprites, then you tell the surface that you're done. 

```csharp
// Main Entry Point
public void Main(string argument, UpdateType updateType)
{
    // Begin a new frame
    var frame = _drawingSurface.DrawFrame();

    // All sprites must be added to the frame here
    DrawSprites(ref frame);

    // We are done with the frame, send all the sprites to the text panel
    frame.Dispose();
}
```

Note that every `DrawFrame` will overwrite the previous. You cannot have multiple `DrawFrame` calls within a single Main call.

### Drawing Sprites

Our first example will be drawing two lines of text in two different colors. To do this we will create and add two text sprites.

```csharp
// Drawing Sprites
public void DrawSprites(ref MySpriteDrawFrame frame)
{
    var line1Sprite = new MySprite()
    {
        Type = SpriteType.TEXT,           // Designate a text sprite
        Data = "Line 1",                  // for a text sprite, this is the text to display
        Position = new Vector2(256, 100), // where we want this sprite to show up
        RotationOrScale = 0.8f,           // for a text sprite, this is a scale value - 80 % size in this case
        Color = Color.Red,                // The color of the text
        Alignment = TextAlignment.CENTER, // how the text is aligned horizontally on the Position
        FontId = "White"                  // What font to use. You'll likely want to use either "White" or
                                          // "Monospace", all others are just variant of "White".
    };
}
```