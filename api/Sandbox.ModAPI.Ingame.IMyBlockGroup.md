← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### IMyBlockGroup Interface

```csharp
public interface IMyBlockGroup
```

Describes terminal block group (PB scripting interface)

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

#### Properties

|Member|Description|
|---|---|
|[string Name { get; }](Sandbox.ModAPI.Ingame.IMyBlockGroup.Name)|Gets name of terminal blocks group|

#### Methods

|Member|Description|
|---|---|
|[void GetBlocks(List<Sandbox.ModAPI.Ingame.IMyTerminalBlock>, [Func<Sandbox.ModAPI.Ingame.IMyTerminalBlock, System.Boolean>])](Sandbox.ModAPI.Ingame.IMyBlockGroup.GetBlocks)|Get terminal blocks which assigned to this group|
|[void GetBlocksOfType(List<Sandbox.ModAPI.Ingame.IMyTerminalBlock>, [Func<Sandbox.ModAPI.Ingame.IMyTerminalBlock, System.Boolean>])](Sandbox.ModAPI.Ingame.IMyBlockGroup.GetBlocksOfType)||
|[void GetBlocksOfType(List<T>, [Func<T, System.Boolean>])](Sandbox.ModAPI.Ingame.IMyBlockGroup.GetBlocksOfType)||

