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
|[`string&nbsp;CustomName`](VRage.Game.ModAPI.Ingame.CustomName)|Display name of the grid (as seen in Info terminal tab)|
|[`float&nbsp;GridSize`](VRage.Game.ModAPI.Ingame.GridSize)|Grid size in meters|
|[`MyCubeSize&nbsp;GridSizeEnum`](VRage.Game.ModAPI.Ingame.GridSizeEnum)|Grid size enum|
|[`bool&nbsp;IsStatic`](VRage.Game.ModAPI.Ingame.IsStatic)|Determines if the grid is static (unmoveable)|
|[`Vector3I&nbsp;Max`](VRage.Game.ModAPI.Ingame.Max)|Maximum coordinates of blocks in grid|
|[`Vector3I&nbsp;Min`](VRage.Game.ModAPI.Ingame.Min)|Minimum coordinates of blocks in grid|
|[`MyEntityComponentContainer&nbsp;Components`](VRage.Game.ModAPI.Ingame.Components)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`long&nbsp;EntityId`](VRage.Game.ModAPI.Ingame.EntityId)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`string&nbsp;Name`](VRage.Game.ModAPI.Ingame.Name)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`string&nbsp;DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`bool&nbsp;HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)|Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.<br/><br/>_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`int&nbsp;InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)|Returns the count of the number of inventories this entity has.<br/><br/>_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`BoundingBoxD&nbsp;WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`BoundingBoxD&nbsp;WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`MatrixD&nbsp;WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`BoundingSphereD&nbsp;WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`BoundingSphereD&nbsp;WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
### Methods
|Member|Description|
|---|---|
|[`bool&nbsp;CubeExists(Vector3I&nbsp;pos)`](VRage.Game.ModAPI.Ingame.CubeExists)|Returns true if there is any block occupying given position|
|[`IMySlimBlock&nbsp;GetCubeBlock(Vector3I&nbsp;pos)`](VRage.Game.ModAPI.Ingame.GetCubeBlock)|Get cube block at given position|
|[`Vector3D&nbsp;GridIntegerToWorld(Vector3I&nbsp;gridCoords)`](VRage.Game.ModAPI.Ingame.GridIntegerToWorld)|Converts grid coordinates to world space|
|[`Vector3I&nbsp;WorldToGridInteger(Vector3D&nbsp;coords)`](VRage.Game.ModAPI.Ingame.WorldToGridInteger)|Converts world coordinates to grid space cell coordinates|
|[`bool&nbsp;IsSameConstructAs(IMyCubeGrid&nbsp;other)`](VRage.Game.ModAPI.Ingame.IsSameConstructAs)|Determines whether this grid is mechanically connected to the other. This is any grid connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.|
|[`IMyInventory&nbsp;GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)|Simply get the MyInventoryBase component stored in this entity.<br/><br/>_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`IMyInventory&nbsp;GetInventory(int&nbsp;index)`](VRage.Game.ModAPI.Ingame.GetInventory)|Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
|[`Vector3D&nbsp;GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)|_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_|
