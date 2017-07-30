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
The Save method is called whenever the game is saved, or right before you recompile your script. Here you can store any data you need to persist between play sessions. This is a bit out of scope right now, but it's nice to know.

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
