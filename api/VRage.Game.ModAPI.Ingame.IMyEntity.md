← [Index](index.md)
# IMyEntity Interface
** Namespace: ** VRage.Game.ModAPI.Ingame  
** Assembly: ** VRage.Game.dll  
## Summary
Ingame (Programmable Block) interface for all entities.
### Properties
|Member|Description|
|---|---|
|[`MyEntityComponentContainer Components`](VRage.Game.ModAPI.Ingame.Components.md)||
|[`long EntityId`](VRage.Game.ModAPI.Ingame.EntityId.md)||
|[`string Name`](VRage.Game.ModAPI.Ingame.Name.md)||
|[`string DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName.md)||
|[`bool HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory.md)||
|[`int InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount.md)||
|[`BoundingBoxD WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB.md)||
|[`BoundingBoxD WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr.md)||
|[`MatrixD WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix.md)||
|[`BoundingSphereD WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume.md)||
|[`BoundingSphereD WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr.md)||
### Methods
|Member|Description|
|---|---|
|[`IMyInventory GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory.md)||
|[`IMyInventory GetInventory(int index)`](VRage.Game.ModAPI.Ingame.GetInventory.md)|Search for inventory component with maching index.|
|[`Vector3D GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition.md)||
