← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### IMyGridTerminalSystem Interface

```csharp
public interface IMyGridTerminalSystem
```

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

#### Methods

|Member|Description|
|---|---|
|[GetBlocks(List)](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.GetBlocks)|Fills the provided list with all the blocks reachable by this grid terminal system. This means all blocks on the same grid, or connected via rotors, pistons or connectors.|
|[GetBlockGroups(List, Func)](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.GetBlockGroups)|Fills the provided list with the block groups reachable by this grid terminal system.|
|[GetBlocksOfType(List, Func)](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.GetBlocksOfType)||
|[GetBlocksOfType(List, Func)](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.GetBlocksOfType)||
|[SearchBlocksOfName(string, List, Func)](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.SearchBlocksOfName)|Fills the provided list with the blocks reachable by this grid terminal system. This means all blocks on the same grid, or connected via rotors, pistons or connectors. The blocks must contain the given name in their name.|
|[GetBlockWithName(string)](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.GetBlockWithName)|Returns the first block found with the given name. Will return`null`if no block with that name can be found.|
|[GetBlockGroupWithName(string)](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.GetBlockGroupWithName)|Returns the first block group found with the given name. Will return`null`if no block group with that name can be found.|
|[GetBlockWithId(long)](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.GetBlockWithId)|Attempts to retrieve the block with the given entity ID. Will return`null`if no block can be found.|
|[CanAccess(IMyTerminalBlock, MyTerminalAccessScope)](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.CanAccess)|Checks if the grid terminal system can still access the given [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock) . A block is no longer accessible if it's destroyed, detached, it's ownership has changed or is otherwise disconnected from this grid terminal system.|
|[CanAccess(IMyCubeGrid, MyTerminalAccessScope)](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.CanAccess)|Checks if the grid terminal system can still access the given [IMyCubeGrid](VRage.Game.ModAPI.Ingame.IMyCubeGrid) . A grid is no longer accessible if it's destroyed, detached, it's ownership has changed or is otherwise disconnected from this grid terminal system.|

