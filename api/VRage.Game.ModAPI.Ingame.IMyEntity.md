← [Index](index)
# IMyEntity Interface
**Namespace:** [`VRage.Game.ModAPI.Ingame`](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll  
## Summary
Ingame (Programmable Block) interface for all entities.
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Components"><code>MyEntityComponentContainer Components</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.EntityId"><code>long EntityId</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Name"><code>string Name</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.DisplayName"><code>string DisplayName</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.HasInventory"><code>bool HasInventory</code></a>_</td><td>Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.InventoryCount"><code>int InventoryCount</code></a>_</td><td>Returns the count of the number of inventories this entity has.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.WorldAABB"><code>BoundingBoxD WorldAABB</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.WorldAABBHr"><code>BoundingBoxD WorldAABBHr</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.WorldMatrix"><code>MatrixD WorldMatrix</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.WorldVolume"><code>BoundingSphereD WorldVolume</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.WorldVolumeHr"><code>BoundingSphereD WorldVolumeHr</code></a>_</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetInventory"><code>IMyInventory GetInventory()</code></a>_</td><td>Simply get the MyInventoryBase component stored in this entity.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetInventory"><code>IMyInventory GetInventory(int index)</code></a>_</td><td>Search for inventory component with maching index.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetPosition"><code>Vector3D GetPosition()</code></a>_</td><td></td></tr>
</table>
