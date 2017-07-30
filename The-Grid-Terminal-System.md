The Grid Terminal System is where you will be able to access your ship's devices. It provides access to all blocks on the same grid the programmable block is on, as well as any grids connected via rotors, pistons or connectors (_not_ landing gears) - as long as the blocks have the same ownership as the running programmable block.

You access it via the property `GridTerminalSystem`, which belongs to the script's base class, `MyGridProgram`. This means that it will be available to all methods and properties in your script - but it is _not_ directly available in any subclasses. More on this later.

The easiest way to see what the Grid Terminal System has to offer, is to [create your script project](https://github.com/malware-dev/MDK-SE/wiki/Getting-Started) in Visual Studio. Find your Main method

```csharp
public void Main() 
{
    // Start typing in here
}
```

and where the comment indicates above, start typing Grid (mind the casing). Visual Studio will respond by showing you this:
![Select the Ingame Script template](https://github.com/malware-dev/MDK-SE/blob/master/images/wiki-intellisense-1.jpg)

This is called "intellisense". It shows you what is available to you at the current location. In this case, it is showing you GridTerminalSystem, which is the property we want. Press `tab` or `enter` and the IDE will fill in the rest for you.

Now continue by adding a `.` at the end. This is what is important. Now it should show you this:
![Select the Ingame Script template](https://github.com/malware-dev/MDK-SE/blob/master/images/wiki-intellisense-2.jpg)

These are the methods available to you in the grid terminal system. All of them are ways to retrieve blocks from your grids in various ways.

* `GetBlocks`
    Gets _all_ the available blocks the Grid Terminal System has access to. Requires a target list of the base `IMyTerminalBlock` type.
    ```csharp
    // Create a list containing _all_ blocks in the system
    List<IMyTerminalBlock> blocks = new List<IMyTerminalBlock>();
    GridTerminalSystem.GetBlocks(blocks);
    ````

* `GetBlocksOfType`
    Allows you to retrieve a list of blocks of a specific type, optionally filtered by a given collect predicate.
    ```csharp
    // Create a list containing all interior lights in the system
    List<IMyInteriorLight> lights = new List<IMyInteriorLight>();
    GridTerminalSystem.GetBlocksOfType(lights);
    ```
    ```csharp
    // Create a list containing all interior lights in the system, but store them
    // in a generic list containing blocks of the IMyTerminalBlock type
    List<IMyTerminalBlock> lights = new List<IMyTerminalBlock>();
    GridTerminalSystem.GetBlocksOfType<IMyInteriorLight>(lights);
    ```
    ```csharp
    // Create a list containing all interior lights that are currently on
    List<IMyInteriorLight> lights = new List<IMyInteriorLight>();
    GridTerminalSystem.GetBlocksOfType(lights, light => light.Enabled);
    ```

* `SearchBlocksOfName`
    Searches through all the blocks, returning those whose name _contains_ the entered name. Meaning, a block named "Mynoch" would be returned if you search for "no". Also provides the ability to use a collect predicate, just like `GetBlocksOfType`. Unfortunately, this method can _only_ accept a target list of the base `IMyTerminalBlock` type.
    ```csharp
    // Returns all lights in the system whose name contains the text "no"
    List<IMyTerminalBlock> lights = new List<IMyTerminalBlock>();
    GridTerminalSystem.SearchBlocksOfName("no", lights, light => light is IMyInteriorLight);
    ```

* `GetBlockWithName`
    Allows you to retrieve a single block having a specific name. Note that the name must be _exact_, case sensitive and including any spacing.
    ```csharp
    // Find a block of a specific name, then check if it's a timer block. If it is, store it in the
    // timer variable, otherwise store null there.
    IMyTimerBlock timer = GridTerminalSystem.GetBlockWithName("Timer Block") as IMyTimerBlock;
    ```

* `GetBlockWithId`
    Allows you to retrieve a block by its `EntityId`. This is an unique id given to a block by the game, and will remain the same even if you rename the block.

* `GetBlockGroups`
    Fetches a list of block groups, optionally filtered by a given collect predicate.
    ```csharp
    ```

* `GetBlockGroupWithName`
    Returns a block group by its name. Note that the name must be _exact_, case sensitive and including any spacing.
    ```csharp
    ```