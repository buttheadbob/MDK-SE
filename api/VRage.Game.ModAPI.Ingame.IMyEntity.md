← [Index](index)
# IMyEntity Interface
**Namespace:** [`VRage.Game.ModAPI.Ingame`](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll  
## Summary
Ingame (Programmable Block) interface for all entities.
### Properties
|Member|Description|
|---|---|
|[`MyEntityComponentContainer Components`](VRage.Game.ModAPI.Ingame.Components)||
|[`long EntityId`](VRage.Game.ModAPI.Ingame.EntityId)||
|[`string Name`](VRage.Game.ModAPI.Ingame.Name)||
|[`string DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)||
|[`bool HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)||
|[`int InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)||
|[`BoundingBoxD WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)||
|[`BoundingBoxD WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)||
|[`MatrixD WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)||
|[`BoundingSphereD WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)||
|[`BoundingSphereD WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)||
### Methods
|Member|Description|
|---|---|
|[`IMyInventory GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)||
|[`IMyInventory GetInventory(int index)`](VRage.Game.ModAPI.Ingame.GetInventory)|Search for inventory component with maching index.|
|[`Vector3D GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)||
