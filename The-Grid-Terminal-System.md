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

This is called ["intellisense"](https://msdn.microsoft.com/en-us/library/hcw1s69b.aspx). It shows you what is available to you at the current location. In this case, it is showing you GridTerminalSystem, which is the property we want. Press `tab` or `enter` and the IDE will fill in the rest for you. This method is available to you for _any_ accessible type, variable, field or property, not just the GridTerminalSystem. This means that if you for instance define a variable with the type of a block you want, you can use this technique to see what this block can do and what it can provide in terms of information - to a certain degree. There's also (unfortunately) something called [Terminal Properties and Terminal Actions](https://github.com/malware-dev/MDK-SE/wiki/Terminal-Properties-And-Actions) which makes this more complicated than it has to be.

Now continue by adding a `.` at the end. This is what is important. Now it should show you this:
![Select the Ingame Script template](https://github.com/malware-dev/MDK-SE/blob/master/images/wiki-intellisense-2.jpg)

These are the methods available to you in the grid terminal system. All of them are ways to retrieve blocks from your grids in various ways.

* `GetBlocks`  
    Gets _all_ the available blocks the Grid Terminal System has access to. Requires a target list of the base `IMyTerminalBlock` type.
    ```csharp
    List<IMyTerminalBlock> blocks = new List<IMyTerminalBlock>();
    void Main()
    {
        // Fill a list with all blocks in the system
        GridTerminalSystem.GetBlocks(blocks);
    }
    ````

* `GetBlocksOfType`  
    Allows you to retrieve a list of blocks of a specific type, optionally filtered by a given collect predicate.
    ```csharp
    List<IMyInteriorLight> lights = new List<IMyInteriorLight>();
    void Main()
    {
        // Fill a list with all interior lights in the system
        GridTerminalSystem.GetBlocksOfType(lights);
    }
    ```
    ```csharp
    // Create a list containing all interior lights in the system, but store them
    // in a generic list containing blocks of the IMyTerminalBlock type
    List<IMyTerminalBlock> lights = new List<IMyTerminalBlock>();
    GridTerminalSystem.GetBlocksOfType<IMyInteriorLight>(lights);
    ```
    ```csharp
    List<IMyInteriorLight> lights = new List<IMyInteriorLight>();
    void Main()
    {
        // Fill a list with all interior lights that are currently on
        GridTerminalSystem.GetBlocksOfType(lights, light => light.Enabled);
    }
    ```

* `SearchBlocksOfName`  
    Searches through all the blocks, returning those whose name _contains_ the entered name. Meaning, a block named "Mynoch" would be returned if you search for "no". Also provides the ability to use a collect predicate, just like `GetBlocksOfType`. Unfortunately, this method can _only_ accept a target list of the base `IMyTerminalBlock` type.
    ```csharp
    List<IMyTerminalBlock> lights = new List<IMyTerminalBlock>();
    void Main()
    {
        // Fill a list with all lights in the system whose name contains the text "no"
        GridTerminalSystem.SearchBlocksOfName("no", lights, light => light is IMyInteriorLight);
    }
    ```

* `GetBlockWithName`  
    Allows you to retrieve a single block having a specific name. Note that the name must be _exact_, case sensitive and including any spacing.
    ```csharp
    // Find a block of a specific name, then check if it's a timer block. If it is, store it in the
    // timer variable, otherwise store null there.
    IMyTimerBlock timer = GridTerminalSystem.GetBlockWithName("Timer Block") as IMyTimerBlock;
    ```

* `GetBlockWithId`  
    Allows you to retrieve a block by its `EntityId`. This is [a unique id](https://github.com/malware-dev/MDK-SE/wiki/The-Entity-Id) given to a block by the game, and will remain the same even if you rename the block.

* `GetBlockGroups`  
    Fetches a list of [block groups](https://github.com/malware-dev/MDK-SE/wiki/Block-Groups), optionally filtered by a given collect predicate.
    ```csharp
    List<IMyBlockGroup> groups = new List<IMyBlockGroup>();
    void Main()
    {
        // Fill a list with all the block groups in the system
        GridTerminalSystem.GetBlockGroups(groups);
    }
    ```
    ```csharp
    List<IMyBlockGroup> groups = new List<IMyBlockGroup>();
    void Main()
    {
        // Fill a list with all the block groups whose name contains the text "no"
        GridTerminalSystem.GetBlockGroups(groups, group => group.Name.Contains("no"));
    }
    ```

* `GetBlockGroupWithName`  
    Returns a [block group](https://github.com/malware-dev/MDK-SE/wiki/Block-Groups) by its name. Note that the name must be _exact_, case sensitive and including any spacing.
    ```csharp
    // Retrieve the block group named "Interesting Blocks"
    IMyBlockGroup group;
    group = GridTerminalSystem.GetBlockGroupWithName("Interesting Blocks");
    ```
#### The Grid Terminal System, Docking, and Multiple Constructs
By default, the grid terminal system just grabs everything it has access to, whether it's a part of your ship or not. **From version 1.188** you will have access to a new block method called `IsSameConstructAs`. This method will check if the two compared blocks belong to the same _mechanical group_, which means any set of grids connected by rotors and pistons. This mechanical group is called a _construct_ and is usually what your ship, vehicle or station is made out from.

Be aware that you _cannot_ distinguish between grids that are merged with a merge block, since the very purpose of that block is to permanently merge two grids into one.
```csharp
List<IMyTerminalBlock> blocks = new List<IMyTerminalBlock>();
void Main()
{
    // Fill a list with all blocks in the current construct (ship, vehicle or station),
    // ignoring anything that might be docked to it. "Me" is the Program's reference to
    // the programmable block this script is running in.
    GridTerminalSystem.GetBlocksOfType(blocks, block => block.IsSameConstructAs(Me));
}
```

#### The Grid Terminal System and Subclasses
As your scripts increase in complexity, it's inevitable that you'll want to split your code into classes. Once you do this you will quickly realize that you lose access to the content of your program inside these classes. This is because the program _itself_ is just another class. This very fact, however, provides you with a solution to this problem.

```csharp
public class SomeUsefulSubclass
{
    Program _program;

    public SomeUsefulSubclass(Program program) 
    {
        _program = program;
    }

    public SomeUsefulMethod() 
    {
        var block = _program.GridTerminalSystem.GetBlockWithName("That Block I Want");
        // Do useful stuff with that block
    }
}

SomeUsefulSubclass _subclass;

public Program() 
{
    _subclass = new SomeUsefulSubclass(this);
}

public void Main() {
    _subclass.SomeUsefulMethod();
}
```

In this example we are leveraging the very fact that your script is just a class like any other, a class which is _always_ named `Program`. We are passing the main Program instance (`this` in any of the methods or properties in your main script - _not_ in your subclasses) into our subclass via its constructor. We choose to pass the program itself rather than just the `GridTerminalSystem` because it will provide access to the other scripting facilities like the [Echo](https://github.com/malware-dev/MDK-SE/wiki/Debugging-Your-Scripts), [Storage](https://github.com/malware-dev/MDK-SE/wiki/The-Storage-String) and the [Runtime](https://github.com/malware-dev/MDK-SE/wiki/The-Runtime) _as well_ as the GridTerminalSystem.