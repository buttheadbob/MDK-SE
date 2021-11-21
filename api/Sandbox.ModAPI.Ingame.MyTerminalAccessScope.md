← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MyTerminalAccessScope Enum

```csharp
public enum MyTerminalAccessScope
```

Determines how [CanAccess(IMyTerminalBlock, MyTerminalAccessScope)](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.CanAccess) limits its access check.

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

#### Fields

|Member|Description|
|---|---|
|All|Checks for access over the entire grid terminal system, no matter how the block is connected.|
|Construct|Checks for access only within the current construct. This is any block connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct. Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way.|
|Grid|Checks for access only for blocks on the same grid as the programmable block.|
