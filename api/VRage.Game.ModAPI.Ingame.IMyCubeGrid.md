← [Index](index)
# IMyCubeGrid Interface
**Namespace:** [`VRage.Game.ModAPI.Ingame`](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll  
**Implements:**
* [`VRage.Game.ModAPI.Ingame.IMyEntity`](VRage.Game.ModAPI.Ingame.IMyEntity)
## Summary
Grid interface
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.CustomName"><code>string CustomName</code></a>_</td><td>Display name of the grid (as seen in Info terminal tab)</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GridSize"><code>float GridSize</code></a>_</td><td>Grid size in meters</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GridSizeEnum"><code>MyCubeSize GridSizeEnum</code></a>_</td><td>Grid size enum</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.IsStatic"><code>bool IsStatic</code></a>_</td><td>Determines if the grid is static (unmoveable)</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Max"><code>Vector3I Max</code></a>_</td><td>Maximum coordinates of blocks in grid</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Min"><code>Vector3I Min</code></a>_</td><td>Minimum coordinates of blocks in grid</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Components"><code>MyEntityComponentContainer Components</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.EntityId"><code>long EntityId</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Name"><code>string Name</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.DisplayName"><code>string DisplayName</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.HasInventory"><code>bool HasInventory</code></a>_</td><td>Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.InventoryCount"><code>int InventoryCount</code></a>_</td><td>Returns the count of the number of inventories this entity has.<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.WorldAABB"><code>BoundingBoxD WorldAABB</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.WorldAABBHr"><code>BoundingBoxD WorldAABBHr</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.WorldMatrix"><code>MatrixD WorldMatrix</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.WorldVolume"><code>BoundingSphereD WorldVolume</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.WorldVolumeHr"><code>BoundingSphereD WorldVolumeHr</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.CubeExists"><code>bool CubeExists(Vector3I pos)</code></a>_</td><td>Returns true if there is any block occupying given position</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetCubeBlock"><code>IMySlimBlock GetCubeBlock(Vector3I pos)</code></a>_</td><td>Get cube block at given position</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GridIntegerToWorld"><code>Vector3D GridIntegerToWorld(Vector3I gridCoords)</code></a>_</td><td>Converts grid coordinates to world space</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.WorldToGridInteger"><code>Vector3I WorldToGridInteger(Vector3D coords)</code></a>_</td><td>Converts world coordinates to grid space cell coordinates</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.IsSameConstructAs"><code>bool IsSameConstructAs(IMyCubeGrid other)</code></a>_</td><td>Determines whether this grid is mechanically connected to the other. This is any grid connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetInventory"><code>IMyInventory GetInventory()</code></a>_</td><td>Simply get the MyInventoryBase component stored in this entity.<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetInventory"><code>IMyInventory GetInventory(int index)</code></a>_</td><td>Search for inventory component with maching index.<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetPosition"><code>Vector3D GetPosition()</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
</table>
