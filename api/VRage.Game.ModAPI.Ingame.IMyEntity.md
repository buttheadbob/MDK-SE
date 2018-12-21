← [Index](index)
# IMyEntity Interface
**Namespace:** [`VRage.Game.ModAPI.Ingame`](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll  
## Summary
Ingame (Programmable Block) interface for all entities.
### Properties
|Member|Description|
|---|---|
|[`VRage.Game.Components.MyEntityComponentContainer Components`](VRage.Game.ModAPI.Ingame.Components)||
|[`long EntityId`](VRage.Game.ModAPI.Ingame.EntityId)||
|[`string Name`](VRage.Game.ModAPI.Ingame.Name)||
|[`string DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)||
|[`bool HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)|Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.|
|[`int InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)|Returns the count of the number of inventories this entity has.|
|[`VRageMath.BoundingBoxD WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)||
|[`VRageMath.BoundingBoxD WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)||
|[`VRageMath.MatrixD WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)||
|[`VRageMath.BoundingSphereD WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)||
|[`VRageMath.BoundingSphereD WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)||
### Methods
|Member|Description|
|---|---|
|[`VRage.Game.ModAPI.Ingame.IMyInventory GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)|Simply get the MyInventoryBase component stored in this entity.|
|[`VRage.Game.ModAPI.Ingame.IMyInventory GetInventory(int)`](VRage.Game.ModAPI.Ingame.GetInventory)|Search for inventory component with maching index.|
|[`VRageMath.Vector3D GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)||
