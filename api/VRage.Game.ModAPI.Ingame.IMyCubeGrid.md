← [Index](index)
# IMyCubeGrid Interface
**Namespace:** [`VRage.Game.ModAPI.Ingame`](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll  
**Implements:**
* [`VRage.Game.ModAPI.Ingame.IMyEntity`](VRage.Game.ModAPI.Ingame.IMyEntity)
## Summary
Grid interface
### Properties
|Member|Description|
|---|---|
|[`string CustomName`](VRage.Game.ModAPI.Ingame.CustomName)||
|[`float GridSize`](VRage.Game.ModAPI.Ingame.GridSize)||
|[`MyCubeSize GridSizeEnum`](VRage.Game.ModAPI.Ingame.GridSizeEnum)||
|[`bool IsStatic`](VRage.Game.ModAPI.Ingame.IsStatic)||
|[`Vector3I Max`](VRage.Game.ModAPI.Ingame.Max)||
|[`Vector3I Min`](VRage.Game.ModAPI.Ingame.Min)||
|[`MyEntityComponentContainer Components`](VRage.Game.ModAPI.Ingame.Components)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`long EntityId`](VRage.Game.ModAPI.Ingame.EntityId)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`string Name`](VRage.Game.ModAPI.Ingame.Name)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`string DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`bool HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`int InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`BoundingBoxD WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`BoundingBoxD WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`MatrixD WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`BoundingSphereD WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`BoundingSphereD WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
### Methods
|Member|Description|
|---|---|
|[`bool CubeExists(Vector3I pos)`](VRage.Game.ModAPI.Ingame.CubeExists)|Returns true if there is any block occupying given position|
|[`IMySlimBlock GetCubeBlock(Vector3I pos)`](VRage.Game.ModAPI.Ingame.GetCubeBlock)|Get cube block at given position|
|[`Vector3D GridIntegerToWorld(Vector3I gridCoords)`](VRage.Game.ModAPI.Ingame.GridIntegerToWorld)|Converts grid coordinates to world space|
|[`Vector3I WorldToGridInteger(Vector3D coords)`](VRage.Game.ModAPI.Ingame.WorldToGridInteger)|Converts world coordinates to grid space cell coordinates|
|[`bool IsSameConstructAs(IMyCubeGrid other)`](VRage.Game.ModAPI.Ingame.IsSameConstructAs)|Determines whether this grid is mechanically connected to the other. This is any grid connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.|
|[`IMyInventory GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`IMyInventory GetInventory(int index)`](VRage.Game.ModAPI.Ingame.GetInventory)|Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`Vector3D GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
