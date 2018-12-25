← [Index](Api-Index) ← [MyCommandLine](VRage.Game.ModAPI.Ingame.Utilities.MyCommandLine)

### Summary

```csharp
public bool Switch(string name)
```

Determines whether the given switch is set. Switches are specified without their prefixed hyphen.

### Returns

[bool](System.Boolean)



### Summary

```csharp
public string Switch(string name, int relativeArgument)
```

Gets an argument of a switch. For example, using`Switch("key", 0)`on the command line`someOtherArgument -key value`will return`value`.

### Returns

[string](System.String)



