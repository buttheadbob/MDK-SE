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
|\\$1bool CanAccess(IMyTerminalBlock, \\$1MyTerminalAccessScope])](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.CanAccess)|Checks if the grid terminal system can still access the given [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock) . A block is no longer accessible if it's destroyed, detached, it's ownership has changed or is otherwise disconnected from this grid terminal system.|
|\\$1bool CanAccess(IMyCubeGrid, \\$1MyTerminalAccessScope])](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.CanAccess)|Checks if the grid terminal system can still access the given [IMyCubeGrid](VRage.Game.ModAPI.Ingame.IMyCubeGrid) . A grid is no longer accessible if it's destroyed, detached, it's ownership has changed or is otherwise disconnected from this grid terminal system.|
|\\$1void GetBlockGroups(List\\$1IMyBlockGroup>, \\$1Func\\$1IMyBlockGroup, bool>])](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.GetBlockGroups)|Fills the provided list with the block groups reachable by this grid terminal system.|
|\\$1IMyBlockGroup GetBlockGroupWithName(string)](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.GetBlockGroupWithName)|Returns the first block group found with the given name. Will return`null`if no block group with that name can be found.|
|\\$1void GetBlocks(List\\$1IMyTerminalBlock>)](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.GetBlocks)|Fills the provided list with all the blocks reachable by this grid terminal system. This means all blocks on the same grid, or connected via rotors, pistons or connectors.|
|\\$1void GetBlocksOfType\\$1T>(List\\$1IMyTerminalBlock>, \\$1Func\\$1IMyTerminalBlock, bool>])](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.GetBlocksOfType)||
|\\$1void GetBlocksOfType\\$1T>(List\\$1T>, \\$1Func\\$1T, bool>])](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.GetBlocksOfType)||
|\\$1IMyTerminalBlock GetBlockWithId(long)](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.GetBlockWithId)|Attempts to retrieve the block with the given entity ID.|
|\\$1IMyTerminalBlock GetBlockWithName(string)](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.GetBlockWithName)|Returns the first block found with the given name.|
|\\$1void SearchBlocksOfName(string, List\\$1IMyTerminalBlock>, \\$1Func\\$1IMyTerminalBlock, bool>])](Sandbox.ModAPI.Ingame.IMyGridTerminalSystem.SearchBlocksOfName)|Fills the provided list with the blocks reachable by this grid terminal system. This means all blocks on the same grid, or connected via rotors, pistons or connectors.|

