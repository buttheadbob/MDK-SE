← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### IMyGridTerminalSystem Interface

```csharp
public interface IMyGridTerminalSystem
```

Describes terminal system (PB scripting interface)

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

#### Methods

|Member|Description|
|---|---|
|[bool CanAccess(IMyTerminalBlock, [MyTerminalAccessScope])](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.CanAccess)|Checks if the grid terminal system can still access the given [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock) . A block is no longer accessible if it's destroyed, detached, it's ownership has changed or is otherwise disconnected from this grid terminal system.|
|[bool CanAccess(IMyCubeGrid, [MyTerminalAccessScope])](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.CanAccess)|Checks if the grid terminal system can still access the given [IMyCubeGrid](VRage.Game.ModAPI.Ingame.IMyCubeGrid) . A grid is no longer accessible if it's destroyed, detached, it's ownership has changed or is otherwise disconnected from this grid terminal system.|
|[void GetBlockGroups(List<Sandbox.ModAPI.Ingame.IMyBlockGroup>, [Func<Sandbox.ModAPI.Ingame.IMyBlockGroup, System.Boolean>])](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.GetBlockGroups)|Fills the provided list with the block groups reachable by this grid terminal system.|
|[IMyBlockGroup GetBlockGroupWithName(string)](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.GetBlockGroupWithName)|Returns the first block group found with the given name. Will return`null`if no block group with that name can be found.|
|[void GetBlocks(List<Sandbox.ModAPI.Ingame.IMyTerminalBlock>)](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.GetBlocks)|Fills the provided list with all the blocks reachable by this grid terminal system. This means all blocks on the same grid, or connected via rotors, pistons or connectors.|
|[void GetBlocksOfType(List<Sandbox.ModAPI.Ingame.IMyTerminalBlock>, [Func<Sandbox.ModAPI.Ingame.IMyTerminalBlock, System.Boolean>])](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.GetBlocksOfType)||
|[void GetBlocksOfType(List<T>, [Func<T, System.Boolean>])](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.GetBlocksOfType)||
|[IMyTerminalBlock GetBlockWithId(long)](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.GetBlockWithId)|Attempts to retrieve the block with the given entity ID.|
|[IMyTerminalBlock GetBlockWithName(string)](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.GetBlockWithName)|Returns the first block found with the given name.|
|[void SearchBlocksOfName(string, List<Sandbox.ModAPI.Ingame.IMyTerminalBlock>, [Func<Sandbox.ModAPI.Ingame.IMyTerminalBlock, System.Boolean>])](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.SearchBlocksOfName)|Fills the provided list with the blocks reachable by this grid terminal system. This means all blocks on the same grid, or connected via rotors, pistons or connectors.|

