← [Index](index)
# IMyCubeGrid Interface
**Namespace:** [`VRage.Game.ModAPI.Ingame`](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll  
**Implements:**
* [`VRage.Game.ModAPI.Ingame.IMyEntity`](VRage.Game.ModAPI.Ingame.IMyEntity)
## Summary
Grid interface
### Properties
<table style="width: 100%">
<tr><td>[`string CustomName`](VRage.Game.ModAPI.Ingame.CustomName)</td><td>Display name of the grid (as seen in Info terminal tab)</td></tr>
<tr><td>[`float GridSize`](VRage.Game.ModAPI.Ingame.GridSize)</td><td>Grid size in meters</td></tr>
<tr><td>[`MyCubeSize GridSizeEnum`](VRage.Game.ModAPI.Ingame.GridSizeEnum)</td><td>Grid size enum</td></tr>
<tr><td>[`bool IsStatic`](VRage.Game.ModAPI.Ingame.IsStatic)</td><td>Determines if the grid is static (unmoveable)</td></tr>
<tr><td>[`Vector3I Max`](VRage.Game.ModAPI.Ingame.Max)</td><td>Maximum coordinates of blocks in grid</td></tr>
<tr><td>[`Vector3I Min`](VRage.Game.ModAPI.Ingame.Min)</td><td>Minimum coordinates of blocks in grid</td></tr>
<tr><td>[`MyEntityComponentContainer Components`](VRage.Game.ModAPI.Ingame.Components)</td><td>_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_</td></tr>
<tr><td>[`long EntityId`](VRage.Game.ModAPI.Ingame.EntityId)</td><td>_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_</td></tr>
<tr><td>[`string Name`](VRage.Game.ModAPI.Ingame.Name)</td><td>_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_</td></tr>
<tr><td>[`string DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)</td><td>_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_</td></tr>
<tr><td>[`bool HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)</td><td>Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.<br/><br/>_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_</td></tr>
<tr><td>[`int InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)</td><td>Returns the count of the number of inventories this entity has.<br/><br/>_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_</td></tr>
<tr><td>[`BoundingBoxD WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)</td><td>_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_</td></tr>
<tr><td>[`BoundingBoxD WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)</td><td>_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_</td></tr>
<tr><td>[`MatrixD WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)</td><td>_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_</td></tr>
<tr><td>[`BoundingSphereD WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)</td><td>_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_</td></tr>
<tr><td>[`BoundingSphereD WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)</td><td>_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_</td></tr>
</table>
### Methods
<table style="width: 100%">
<tr><td>[`bool CubeExists(Vector3I pos)`](VRage.Game.ModAPI.Ingame.CubeExists)</td><td>Returns true if there is any block occupying given position</td></tr>
<tr><td>[`IMySlimBlock GetCubeBlock(Vector3I pos)`](VRage.Game.ModAPI.Ingame.GetCubeBlock)</td><td>Get cube block at given position</td></tr>
<tr><td>[`Vector3D GridIntegerToWorld(Vector3I gridCoords)`](VRage.Game.ModAPI.Ingame.GridIntegerToWorld)</td><td>Converts grid coordinates to world space</td></tr>
<tr><td>[`Vector3I WorldToGridInteger(Vector3D coords)`](VRage.Game.ModAPI.Ingame.WorldToGridInteger)</td><td>Converts world coordinates to grid space cell coordinates</td></tr>
<tr><td>[`bool IsSameConstructAs(IMyCubeGrid other)`](VRage.Game.ModAPI.Ingame.IsSameConstructAs)</td><td>Determines whether this grid is mechanically connected to the other. This is any grid connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.</td></tr>
<tr><td>[`IMyInventory GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)</td><td>Simply get the MyInventoryBase component stored in this entity.<br/><br/>_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_</td></tr>
<tr><td>[`IMyInventory GetInventory(int index)`](VRage.Game.ModAPI.Ingame.GetInventory)</td><td>Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_</td></tr>
<tr><td>[`Vector3D GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)</td><td>_Inherited from [`IMyEntity`](VRage.Game.ModAPI.Ingame.IMyCubeGrid)_</td></tr>
</table>
