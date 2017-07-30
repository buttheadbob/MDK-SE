
This is a simplistic attempt to explain the various parts of an ingame script and how it works. It is by no means a complete explanation. To get further help, I recommend connecting to [Keen's official Discord](https://discord.gg/0hIE7GirODUqhfIg) and asking in the #programming-in-game channel. There's usually plenty of people there to help you. I will be assuming that you're familiar with the game itself, and how to _use_ scripts, and how to load a script into a programmable block via the workshop button.

### The Language

First of all: The programmable block uses the programming language C# in order to provide high-performance automation for your builds. Before continuing you should get a basic grasp of the language itself. There are several tutorials on the web dealing with this, including [Microsoft's own](https://docs.microsoft.com/en-us/dotnet/csharp/csharp). You might be able to find some tutorials which are better at explaining than them though, they tend to be rather obtuse.

### The Anatomy of a Script

Ok, so you've dealt with that, and you've opened your brand new project and is looking at this (comments and `using` removed for brevity):

```csharp
namespace IngameScript
{
    partial class Program : MyGridProgram
    {
        public Program()
        {
        }

        public void Save()
        {
        }

        public void Main(string argument)
        {
        }
    }
}
```
The first you need to be aware of, is that the namespace and the `partial class Program : MyGridProgram` parts is _not_ a part of the programmable block script. Only the parts _inside_ the Program class is actually used when this script project is deployed to Space Engineers. The reason is that Space Engineers need strict control of what a script class _is_. A script class is _always_ named `Program`, and it's _always_ inherited from `MyGridProgram`. So the important part of this code file, then, is this:
```csharp
public Program()
{
}

public void Save()
{
}

public void Main(string argument)
{
}
```
The rest of the code should be left as it is. Let me then explain the individual parts:

#### The Constructor
```csharp
public Program() 
{

}
```
It is used for one-time initialization of your script, and is run once every time your script is instantiated. This means it's run once after your game is loaded, or after you recompile your script. Recompiling happens when you have edited your script or when you press the `Recompile` button.
The constructor is optional, you don't need it to have a working script.

#### The Save Method
```csharp
public void Save() 
{
}
```
The Save method is called whenever the game is saved. Here you can store any data you need to persist between play sessions. This is a bit out of scope right now, but it's nice to know.

This save method is also optional.

#### The Main Method
```csharp
public void Main(string argument) 
{
}
```
or simply
```csharp
public void Main() 
{
}
```
The Main method is the main entry point of your script. It might be called many times during a script's lifetime, depending on what your script is and how it is set up.
This method is required, obviously.
The argument is passed from the game (depending on your toolbar setup) to your script, enabling a single script to do a bunch of different things. This is beyond the scope of this tutorial.

### Your First Script
Let's start simple. Let's say you have a light, and you want to turn it off and on. Yes, I know, you can just add that to any old toolbar. But it's one of the easiest things you can script, so I say we start there. In fact, let me provide you with [a finished blueprint with the script in place and ready to go](http://steamcommunity.com/sharedfiles/filedetails/?id=1094911307).

Since it's somewhat... cumbersome... to read scripts in the game's internal editor, let me provide the script here. Again I have removed the comments for brevity.

```cs
public void Main() 
{
    IMyInteriorLight light;

    light = GridTerminalSystem.GetBlockWithName("That Important Light") as IMyInteriorLight;
    if (light == null) 
    {
        Echo("Oh my! I couldn't find that block...");
        return;
    }

    light.Enabled = !light.Enabled;
    Echo("I have toggled the button!");
}
```

So let's explain what is happening here. 

First I need to define a variable to contain a reference to the light I want to change.
```csharp
IMyInteriorLight light;
```

Then I must query the grid terminal system for the specific block I'm after. I do this by requesting it by name. Be aware that this name must be _exact_. Even if your query differs by a space, the system will not find your block.
```csharp
light = GridTerminalSystem.GetBlockWithName("That Important Light") as IMyInteriorLight;
```
The first part, `GridTerminalSystem.GetBlockWithName("That Important Light")` will find the first block on the build that has the name That Important Light. It does not care what type of block that is. If you rename the light to something else, and rename, let's say the reactor, to That Important Light, the method will return _that_ block instead. So to remedy that, we add a conditional cast `as IMyInteriorLight` which will test if the block is of that particular type, and return it only if it is. If the type does not match, it will return `null`. So in practice that means that there are two scenarios where the query above will _not_ return a block: Either because there is no block with that name on your build, or because the block with that name does not have this particular type. This means that we should check if the block has been retrieved:
```csharp
if (light == null) 
{
    // Output some text to the programmable block's details section:
    Echo("Oh my! I couldn't find that block...");
    // Just quit, we can't do anything else here.
    return;
}
```
Ok, so we have a block, and we know it's a light. So all we have to do now, is to toggle it.   
```csharp
light.Enabled = !light.Enabled;
Echo("I have toggled the button!");
```

What we are doing here is to set the light's Enabled state (it's on/off button, essentially) to _the opposite_ (as defined by the !) as its current value. This will effectively toggle the button on and off. We're done! Press Check code, then Remember & Exit, and then the Run button, to see what happens (you may need to wait a second or so for the light to catch up to the change).

That will conclude the first introduction. I have hopes that I - or some contributors - will be able to add further tutorials to help you along the way. In the mean time, again, I point towards [Keen's official Discord](https://discord.gg/0hIE7GirODUqhfIg) and the #programming-in-game channel.