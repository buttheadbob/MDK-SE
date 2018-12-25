← [Index](Api-Index) ← [Namespace Index](Namespace-Index) ← [IMyProgrammableBlock](Sandbox.ModAPI.Ingame.IMyProgrammableBlock)

### Summary

```csharp
public bool TryRun(string argument)
```

Attempts to run this programmable block using the given argument. An already running programmable block cannot be run again. This is equivalent to running`block.ApplyAction("Run", argumentsList);`This should be called from an ingame script. Do not use in mods.

### Returns

[bool](https://docs.microsoft.com/en-us/dotnet/api/system.boolean?view=netframework-4.6)

`true`if the action was applied,`false`otherwise

### Parameters

* [string](https://docs.microsoft.com/en-us/dotnet/api/system.string?view=netframework-4.6) argument
