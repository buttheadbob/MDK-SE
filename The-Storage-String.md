Sometimes you need to store information that must survive reloading or shutting down the game, or recompiling your script. The grid program currently provides only one way to do this: The `Storage` property. This property resides in your script's base class `MyGridProgram` and as such can be accessed by any method or property in your script - but not directly by any subclass (see [the bottom of this page](https://github.com/malware-dev/MDK-SE/wiki/The-Grid-Terminal-System#the-grid-terminal-system-and-subclasses) - "The Grid Terminal System and Subclasses" - for a way to get around that problem).

The `Storage` property is simply a string property:
```csharp
public void Save()
{
    Storage = "My String"
}
```
As you can see, nothing special about its use. The difference between this property and any other is the fact that its content is saved to your disk when the game is saved.

Changing it to just any old string, that's not very useful, is it. What if you need to save something more complicated? Well, I'm afraid you're gonna have to do the hard work yourself. Let me help you on your way by providing a very simple
helper class: The `StorageDictionary`. While it may not suffice for the more complicated scenarios, it should be good enough for most smaller purposes.

_storage dictionary pending_

_tutorial pending_