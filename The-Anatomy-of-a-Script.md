## The MDK / Visual Studio Specific Section
_If you're not using MDK, you can skip to the next section_

Ok, [so you've learned the basics of C# and know where to get help](https://github.com/malware-dev/MDK-SE/wiki/Quick-Introduction-to-Space-Engineers-Ingame-Scripts), and you've [opened your brand new project](https://github.com/malware-dev/MDK-SE/wiki/Getting-Started) and you are looking at this (comments and using removed for brevity):

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
The first you need to be aware of, is that the namespace and the `partial class Program : MyGridProgram` parts is _not_ a part of the programmable block script. Only the parts _inside_ the Program class is actually used when this script project is deployed to Space Engineers. The reason is that Space Engineers need strict control of what a script class _is_. A script class is _always_ named `Program`, and it's _always_ inherited from `MyGridProgram`. Space Engineers will add these parts to your script behind the scene. If you're just using the ingame editor, a normal text editor or something like that, you won't need these additions.

## The General Section (even if you don't use MDK)

This is what you'll see the first time you open a newly placed programmable block (comments removed for brevity):
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
The Save method is called whenever the game is saved, or right before you recompile your script. Here you can store any data you need to persist between play sessions. See [The Storage String](https://github.com/malware-dev/MDK-SE/wiki/The-Storage-String) for more details on how to do this.

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
The argument is passed from the game (depending on your toolbar setup) to your script, enabling a single script to do a bunch of different things. You can set this argument by dragging your programmable block onto a button panel, sensor or timer toolbar (or any other device toolbar except your suit) and selecting "Run". You will be presented with an input box where you can type in what you want to be passed to your script. It will be passed verbatim, Keep that in mind.

#### The limitations
This is a game, obviously, so there needs to be limitations. There are three distinct limitations in place for a programmable block script.

The first is the the size of the script itself. No scripts can have any more than 100 000 characters.

The second is what is called the "instruction counter". You may only have a maximum of 50000 code junctions per single run in your script. A code junction includes things like method calls, switches, conditional, loops and similar. Simple statements like 1+1 does not increase this count. **note that this is only a tool**. You should always strive to execute as little as possible code per run as possible. Remember, the game has only about 16 milliseconds per frame to do _everything_, including game logic, physics, rendering and _all_ scripts in your world. Every nanosecond counts!

The third limitation is how much of the .NET framework you have access to. Obviously giving full access to the framework is dangerous, because then people could do bad things to others' computers. This is why Space Engineers uses a whitelist to restrict which parts of the framework you have access to. 

If you use [MDK](https://github.com/malware-dev/MDK-SE/wiki/Getting-Started), it will tell you if you try to reference a type or member that is not allowed. You can try this now by creating a new MDK project, and add this:

```csharp
public void Main()
{
    System.Threading.Thread thread;
}
```

With the help of the MDK extension, Visual Studio will mark this with an error telling you that the type `System.Threading.Thread` is prohibited.

