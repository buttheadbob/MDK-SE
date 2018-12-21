← [Index](index.md)
# IMyCubeBlock Interface
**Namespace:** VRage.Game.ModAPI.Ingame  
**Assembly:** VRage.Game.dll  
**Implements:**
* [`VRage.Game.ModAPI.Ingame.IMyEntity`](VRage.Game.ModAPI.Ingame.IMyEntity.md)
## Summary
Basic cube interface
### Properties
|Member|Description|
|---|---|
|[`SerializableDefinitionId BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition.md)||
|[`bool CheckConnectionAllowed`](VRage.Game.ModAPI.Ingame.CheckConnectionAllowed.md)||
|[`IMyCubeGrid CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid.md)||
|[`string DefinitionDisplayNameText`](VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText.md)||
|[`float DisassembleRatio`](VRage.Game.ModAPI.Ingame.DisassembleRatio.md)||
|[`string DisplayNameText`](VRage.Game.ModAPI.Ingame.DisplayNameText.md)||
|[`bool IsBeingHacked`](VRage.Game.ModAPI.Ingame.IsBeingHacked.md)||
|[`bool IsFunctional`](VRage.Game.ModAPI.Ingame.IsFunctional.md)||
|[`bool IsWorking`](VRage.Game.ModAPI.Ingame.IsWorking.md)||
|[`Vector3I Max`](VRage.Game.ModAPI.Ingame.Max.md)||
|[`float Mass`](VRage.Game.ModAPI.Ingame.Mass.md)||
|[`Vector3I Min`](VRage.Game.ModAPI.Ingame.Min.md)||
|[`int NumberInGrid`](VRage.Game.ModAPI.Ingame.NumberInGrid.md)||
|[`MyBlockOrientation Orientation`](VRage.Game.ModAPI.Ingame.Orientation.md)||
|[`long OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId.md)||
|[`Vector3I Position`](VRage.Game.ModAPI.Ingame.Position.md)||
|[`MyEntityComponentContainer Components`](VRage.Game.ModAPI.Ingame.Components.md)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock.md)_|
|[`long EntityId`](VRage.Game.ModAPI.Ingame.EntityId.md)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock.md)_|
|[`string Name`](VRage.Game.ModAPI.Ingame.Name.md)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock.md)_|
|[`string DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName.md)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock.md)_|
|[`bool HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory.md)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock.md)_|
|[`int InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount.md)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock.md)_|
|[`BoundingBoxD WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB.md)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock.md)_|
|[`BoundingBoxD WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr.md)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock.md)_|
|[`MatrixD WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix.md)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock.md)_|
|[`BoundingSphereD WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume.md)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock.md)_|
|[`BoundingSphereD WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr.md)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock.md)_|
### Methods
|Member|Description|
|---|---|
|[`string GetOwnerFactionTag()`](VRage.Game.ModAPI.Ingame.GetOwnerFactionTag.md)||
|[`MyRelationsBetweenPlayerAndBlock GetPlayerRelationToOwner()`](VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner.md)||
|[`MyRelationsBetweenPlayerAndBlock GetUserRelationToOwner(long playerId)`](VRage.Game.ModAPI.Ingame.GetUserRelationToOwner.md)||
|[`void UpdateIsWorking()`](VRage.Game.ModAPI.Ingame.UpdateIsWorking.md)||
|[`void UpdateVisual()`](VRage.Game.ModAPI.Ingame.UpdateVisual.md)||
|[`IMyInventory GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory.md)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock.md)_|
|[`IMyInventory GetInventory(int index)`](VRage.Game.ModAPI.Ingame.GetInventory.md)|Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock.md)_|
|[`Vector3D GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition.md)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeBlock.md)_|
