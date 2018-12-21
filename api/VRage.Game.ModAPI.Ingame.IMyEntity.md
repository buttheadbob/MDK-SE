← [Index](index)
# IMyEntity Interface
**Namespace:** [`VRage.Game.ModAPI.Ingame`](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll  
## Summary
Ingame (Programmable Block) interface for all entities.
### Properties
|Member|Description|
|---|---|
|[`Components`](VRage.Game.ModAPI.Ingame.Components)||
|[`EntityId`](VRage.Game.ModAPI.Ingame.EntityId)||
|[`Name`](VRage.Game.ModAPI.Ingame.Name)||
|[`DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)||
|[`HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)|Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.|
|[`InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)|Returns the count of the number of inventories this entity has.|
|[`WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)||
|[`WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)||
|[`WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)||
|[`WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)||
|[`WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)||
### Methods
|Member|Description|
|---|---|
|[`GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)|Simply get the MyInventoryBase component stored in this entity.|
|[`GetInventory(int)`](VRage.Game.ModAPI.Ingame.GetInventory)|Search for inventory component with maching index.|
|[`GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)||
