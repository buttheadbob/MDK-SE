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
|[`string CustomName`](VRage.Game.ModAPI.Ingame.CustomName)|Display name of the grid (as seen in Info terminal tab)|
|[`float GridSize`](VRage.Game.ModAPI.Ingame.GridSize)|Grid size in meters|
|[`VRage.Game.MyCubeSize GridSizeEnum`](VRage.Game.ModAPI.Ingame.GridSizeEnum)|Grid size enum|
|[`bool IsStatic`](VRage.Game.ModAPI.Ingame.IsStatic)|Determines if the grid is static (unmoveable)|
|[`VRageMath.Vector3I Max`](VRage.Game.ModAPI.Ingame.Max)|Maximum coordinates of blocks in grid|
|[`VRageMath.Vector3I Min`](VRage.Game.ModAPI.Ingame.Min)|Minimum coordinates of blocks in grid|
|[`VRage.Game.Components.MyEntityComponentContainer Components`](VRage.Game.ModAPI.Ingame.Components)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`long EntityId`](VRage.Game.ModAPI.Ingame.EntityId)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`string Name`](VRage.Game.ModAPI.Ingame.Name)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`string DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`bool HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)|Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.<br/><br/>_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`int InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)|Returns the count of the number of inventories this entity has.<br/><br/>_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`VRageMath.BoundingBoxD WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`VRageMath.BoundingBoxD WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`VRageMath.MatrixD WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`VRageMath.BoundingSphereD WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`VRageMath.BoundingSphereD WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
### Methods
|Member|Description|
|---|---|
|[`bool CubeExists(VRageMath.Vector3I)`](VRage.Game.ModAPI.Ingame.CubeExists)|Returns true if there is any block occupying given position|
|[`VRage.Game.ModAPI.Ingame.IMySlimBlock GetCubeBlock(VRageMath.Vector3I)`](VRage.Game.ModAPI.Ingame.GetCubeBlock)|Get cube block at given position|
|[`VRageMath.Vector3D GridIntegerToWorld(VRageMath.Vector3I)`](VRage.Game.ModAPI.Ingame.GridIntegerToWorld)|Converts grid coordinates to world space|
|[`VRageMath.Vector3I WorldToGridInteger(VRageMath.Vector3D)`](VRage.Game.ModAPI.Ingame.WorldToGridInteger)|Converts world coordinates to grid space cell coordinates|
|[`bool IsSameConstructAs(VRage.Game.ModAPI.Ingame.IMyCubeGrid)`](VRage.Game.ModAPI.Ingame.IsSameConstructAs)|Determines whether this grid is mechanically connected to the other. This is any grid connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.|
|[`VRage.Game.ModAPI.Ingame.IMyInventory GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)|Simply get the MyInventoryBase component stored in this entity.<br/><br/>_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`VRage.Game.ModAPI.Ingame.IMyInventory GetInventory(int)`](VRage.Game.ModAPI.Ingame.GetInventory)|Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`VRageMath.Vector3D GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
