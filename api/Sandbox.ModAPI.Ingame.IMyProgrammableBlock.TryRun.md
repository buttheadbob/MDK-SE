← [Index](Api-Index) ← [IMyProgrammableBlock](Sandbox.ModAPI.Ingame.IMyProgrammableBlock)

### Summary

```csharp
private public virtual bool TryRun(string argument)
```

Attempts to run this programmable block using the given argument. An already running programmable block cannot be run again. This is equivalent to running`block.ApplyAction("Run", argumentsList);`This should be called from an ingame script. Do not use in mods.

### Returns

`true`if the action was applied,`false`otherwise

### Example

### Remarks

