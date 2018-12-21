← [Index](index.md)
# IMyGasGenerator Interface
** Namespace: ** Sandbox.ModAPI.Ingame  
** Assembly: ** Sandbox.Common.dll  
** Implements: **
* [`Sandbox.ModAPI.Ingame.IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyFunctionalBlock.md)
* [`Sandbox.ModAPI.Ingame.IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTerminalBlock.md)
* [`VRage.Game.ModAPI.Ingame.IMyCubeBlock`](VRage.Game.ModAPI.Ingame.IMyCubeBlock.md)
* [`VRage.Game.ModAPI.Ingame.IMyEntity`](VRage.Game.ModAPI.Ingame.IMyEntity.md)
## Summary
Gas generator interface
### Properties
|Member|Description|
|---|---|
|[`bool AutoRefill`](Sandbox.ModAPI.Ingame.AutoRefill.md)||
|[`bool UseConveyorSystem`](Sandbox.ModAPI.Ingame.UseConveyorSystem.md)||
|[`MyEntityComponentContainer Components`](VRage.Game.ModAPI.Ingame.Components.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`long EntityId`](VRage.Game.ModAPI.Ingame.EntityId.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`string Name`](VRage.Game.ModAPI.Ingame.Name.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`string DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`bool HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`int InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`BoundingBoxD WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`BoundingBoxD WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`MatrixD WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`BoundingSphereD WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`BoundingSphereD WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`SerializableDefinitionId BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`bool CheckConnectionAllowed`](VRage.Game.ModAPI.Ingame.CheckConnectionAllowed.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`IMyCubeGrid CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`string DefinitionDisplayNameText`](VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`float DisassembleRatio`](VRage.Game.ModAPI.Ingame.DisassembleRatio.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`string DisplayNameText`](VRage.Game.ModAPI.Ingame.DisplayNameText.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`bool IsBeingHacked`](VRage.Game.ModAPI.Ingame.IsBeingHacked.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`bool IsFunctional`](VRage.Game.ModAPI.Ingame.IsFunctional.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`bool IsWorking`](VRage.Game.ModAPI.Ingame.IsWorking.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`Vector3I Max`](VRage.Game.ModAPI.Ingame.Max.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`float Mass`](VRage.Game.ModAPI.Ingame.Mass.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`Vector3I Min`](VRage.Game.ModAPI.Ingame.Min.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`int NumberInGrid`](VRage.Game.ModAPI.Ingame.NumberInGrid.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`MyBlockOrientation Orientation`](VRage.Game.ModAPI.Ingame.Orientation.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`long OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`Vector3I Position`](VRage.Game.ModAPI.Ingame.Position.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`string CustomName`](Sandbox.ModAPI.Ingame.CustomName.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`string CustomNameWithFaction`](Sandbox.ModAPI.Ingame.CustomNameWithFaction.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`string DetailedInfo`](Sandbox.ModAPI.Ingame.DetailedInfo.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`string CustomInfo`](Sandbox.ModAPI.Ingame.CustomInfo.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`string CustomData`](Sandbox.ModAPI.Ingame.CustomData.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`bool ShowOnHUD`](Sandbox.ModAPI.Ingame.ShowOnHUD.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`bool ShowInTerminal`](Sandbox.ModAPI.Ingame.ShowInTerminal.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`bool ShowInToolbarConfig`](Sandbox.ModAPI.Ingame.ShowInToolbarConfig.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`bool ShowInInventory`](Sandbox.ModAPI.Ingame.ShowInInventory.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`bool Enabled`](Sandbox.ModAPI.Ingame.Enabled.md)|_Inherited from [`IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
### Methods
|Member|Description|
|---|---|
|[`IMyInventory GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`IMyInventory GetInventory(int index)`](VRage.Game.ModAPI.Ingame.GetInventory.md)|Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`Vector3D GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition.md)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`string GetOwnerFactionTag()`](VRage.Game.ModAPI.Ingame.GetOwnerFactionTag.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`MyRelationsBetweenPlayerAndBlock GetPlayerRelationToOwner()`](VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`MyRelationsBetweenPlayerAndBlock GetUserRelationToOwner(long playerId)`](VRage.Game.ModAPI.Ingame.GetUserRelationToOwner.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`void UpdateIsWorking()`](VRage.Game.ModAPI.Ingame.UpdateIsWorking.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`void UpdateVisual()`](VRage.Game.ModAPI.Ingame.UpdateVisual.md)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`bool HasLocalPlayerAccess()`](Sandbox.ModAPI.Ingame.HasLocalPlayerAccess.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`bool HasPlayerAccess(long playerId)`](Sandbox.ModAPI.Ingame.HasPlayerAccess.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`void SetCustomName(string text)`](Sandbox.ModAPI.Ingame.SetCustomName.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`void SetCustomName(StringBuilder text)`](Sandbox.ModAPI.Ingame.SetCustomName.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`void GetActions(List<ITerminalAction> resultList, Func<ITerminalAction, bool> collect)`](Sandbox.ModAPI.Ingame.GetActions.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`void SearchActionsOfName(string name, List<ITerminalAction> resultList, Func<ITerminalAction, bool> collect)`](Sandbox.ModAPI.Ingame.SearchActionsOfName.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`ITerminalAction GetActionWithName(string name)`](Sandbox.ModAPI.Ingame.GetActionWithName.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`ITerminalProperty GetProperty(string id)`](Sandbox.ModAPI.Ingame.GetProperty.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`void GetProperties(List<ITerminalProperty> resultList, Func<ITerminalProperty, bool> collect)`](Sandbox.ModAPI.Ingame.GetProperties.md)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`bool IsSameConstructAs(IMyTerminalBlock other)`](Sandbox.ModAPI.Ingame.IsSameConstructAs.md)|Determines whether this block is mechanically connected to the other. This is any block connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
|[`void RequestEnable(bool enable)`](Sandbox.ModAPI.Ingame.RequestEnable.md)|_Inherited from [`IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyGasGenerator.md)_|
