← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### TerminalBlockExtentions Class

```csharp
public abstract sealed class TerminalBlockExtentions
```

Class having some sugar extensions. Written by Kalvin Osborne, AKA Night Lone.

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

#### Methods

|Member|Description|
|---|---|
|[static void ApplyAction(this IMyTerminalBlock, string)](Sandbox.ModAPI.Ingame.TerminalBlockExtentions.ApplyAction)|Finds action by [GetActionWithName(string)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.GetActionWithName) and calls [Apply(IMyCubeBlock)](Sandbox.ModAPI.Interfaces.ITerminalAction.Apply) |
|[static void ApplyAction(this IMyTerminalBlock, string, List)](Sandbox.ModAPI.Ingame.TerminalBlockExtentions.ApplyAction)|Finds action by [GetActionWithName(string)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.GetActionWithName) and calls [Apply(IMyCubeBlock, ListReader<Sandbox.ModAPI.Ingame.TerminalActionParameter>)](Sandbox.ModAPI.Interfaces.ITerminalAction.Apply) |
|[static long GetId(this IMyTerminalBlock)](Sandbox.ModAPI.Ingame.TerminalBlockExtentions.GetId)|Get EntityId of block|
|[static IMyInventory GetInventory(this IMyTerminalBlock, int)](Sandbox.ModAPI.Ingame.TerminalBlockExtentions.GetInventory)|_**Obsolete:** Use the GetInventoryBase method._|
|[static int GetInventoryCount(this IMyTerminalBlock)](Sandbox.ModAPI.Ingame.TerminalBlockExtentions.GetInventoryCount)|_**Obsolete:** Use the InventoryCount property._|
|[static bool GetUseConveyorSystem(this IMyTerminalBlock)](Sandbox.ModAPI.Ingame.TerminalBlockExtentions.GetUseConveyorSystem)|_**Obsolete:** Use the blocks themselves, this method is no longer reliable_|
|[static bool HasAction(this IMyTerminalBlock, string)](Sandbox.ModAPI.Ingame.TerminalBlockExtentions.HasAction)|Searches for terminal action with name|
|[static bool HasInventory(this IMyTerminalBlock)](Sandbox.ModAPI.Ingame.TerminalBlockExtentions.HasInventory)|_**Obsolete:** Use the HasInventory property._|
|[static void SetUseConveyorSystem(this IMyTerminalBlock, bool)](Sandbox.ModAPI.Ingame.TerminalBlockExtentions.SetUseConveyorSystem)|_**Obsolete:** Use the blocks themselves, this method is no longer reliable_|

