← [Index](Api-Index) ← [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)

### Summary

```csharp
private public abstract virtual bool IsSameConstructAs
```

Determines whether this block is mechanically connected to the other. This is any block connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.  
  
Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.

### Returns



### Example

### Remarks

