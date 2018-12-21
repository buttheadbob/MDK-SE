← [Index](index.md)
# IMyCubeGrid Interface
** Namespace: ** VRage.Game.ModAPI.Ingame  
** Assembly: ** VRage.Game.dll  
** Implements: **
* [`VRage.Game.ModAPI.Ingame.IMyEntity`](VRage.Game.ModAPI.Ingame.IMyEntity.md)
## Summary
Grid interface
### Properties
|Member|Description|
|---|---|
|[`string CustomName`](VRage.Game.ModAPI.Ingame.CustomName.md)||
|[`float GridSize`](VRage.Game.ModAPI.Ingame.GridSize.md)||
|[`MyCubeSize GridSizeEnum`](VRage.Game.ModAPI.Ingame.GridSizeEnum.md)||
|[`bool IsStatic`](VRage.Game.ModAPI.Ingame.IsStatic.md)||
|[`Vector3I Max`](VRage.Game.ModAPI.Ingame.Max.md)||
|[`Vector3I Min`](VRage.Game.ModAPI.Ingame.Min.md)||
|[`MyEntityComponentContainer Components`](VRage.Game.ModAPI.Ingame.Components.md)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid.md)_|
|[`long EntityId`](VRage.Game.ModAPI.Ingame.EntityId.md)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid.md)_|
|[`string Name`](VRage.Game.ModAPI.Ingame.Name.md)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid.md)_|
|[`string DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName.md)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid.md)_|
|[`bool HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory.md)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid.md)_|
|[`int InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount.md)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid.md)_|
|[`BoundingBoxD WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB.md)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid.md)_|
|[`BoundingBoxD WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr.md)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid.md)_|
|[`MatrixD WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix.md)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid.md)_|
|[`BoundingSphereD WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume.md)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid.md)_|
|[`BoundingSphereD WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr.md)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid.md)_|
### Methods
|Member|Description|
|---|---|
|[`bool CubeExists(Vector3I pos)`](VRage.Game.ModAPI.Ingame.CubeExists.md)|Returns true if there is any block occupying given position|
|[`IMySlimBlock GetCubeBlock(Vector3I pos)`](VRage.Game.ModAPI.Ingame.GetCubeBlock.md)|Get cube block at given position|
|[`Vector3D GridIntegerToWorld(Vector3I gridCoords)`](VRage.Game.ModAPI.Ingame.GridIntegerToWorld.md)|Converts grid coordinates to world space|
|[`Vector3I WorldToGridInteger(Vector3D coords)`](VRage.Game.ModAPI.Ingame.WorldToGridInteger.md)|Converts world coordinates to grid space cell coordinates|
|[`bool IsSameConstructAs(IMyCubeGrid other)`](VRage.Game.ModAPI.Ingame.IsSameConstructAs.md)|Determines whether this grid is mechanically connected to the other. This is any grid connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.|
|[`IMyInventory GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory.md)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid.md)_|
|[`IMyInventory GetInventory(int index)`](VRage.Game.ModAPI.Ingame.GetInventory.md)|Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid.md)_|
|[`Vector3D GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition.md)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid.md)_|
