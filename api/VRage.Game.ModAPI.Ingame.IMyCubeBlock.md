← [Index](index)
# IMyCubeBlock Interface
**Namespace:** [`VRage.Game.ModAPI.Ingame`](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll  
**Implements:**
* [`VRage.Game.ModAPI.Ingame.IMyEntity`](VRage.Game.ModAPI.Ingame.IMyEntity)
## Summary
Basic cube interface
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.BlockDefinition"><code>SerializableDefinitionId BlockDefinition</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.CheckConnectionAllowed"><code>bool CheckConnectionAllowed</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.CubeGrid"><code>IMyCubeGrid CubeGrid</code></a>_</td><td>Grid in which the block is placed</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText"><code>string DefinitionDisplayNameText</code></a>_</td><td>Definition name</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.DisassembleRatio"><code>float DisassembleRatio</code></a>_</td><td>Is set in definition Ratio at which is the block disassembled (grinding)</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.DisplayNameText"><code>string DisplayNameText</code></a>_</td><td>Translated block name</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.IsBeingHacked"><code>bool IsBeingHacked</code></a>_</td><td>Hacking of the block is in progress</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.IsFunctional"><code>bool IsFunctional</code></a>_</td><td>True if integrity is above breaking threshold</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.IsWorking"><code>bool IsWorking</code></a>_</td><td>True if block is able to do its work depening on block type (is functional, powered, enabled, etc...)</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Max"><code>Vector3I Max</code></a>_</td><td>Maximum coordinates of grid cells occupied by this block</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Mass"><code>float Mass</code></a>_</td><td>Block mass</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Min"><code>Vector3I Min</code></a>_</td><td>Minimum coordinates of grid cells occupied by this block</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.NumberInGrid"><code>int NumberInGrid</code></a>_</td><td>Order in which were the blocks of same type added to grid Used in default display name</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Orientation"><code>MyBlockOrientation Orientation</code></a>_</td><td>Returns block orientation in base 6 directions</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.OwnerId"><code>long OwnerId</code></a>_</td><td>Id of player owning block (not steam Id)</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Position"><code>Vector3I Position</code></a>_</td><td>Position in grid coordinates</td></tr>
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
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetOwnerFactionTag"><code>string GetOwnerFactionTag()</code></a>_</td><td>Tag of faction owning block</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner"><code>MyRelationsBetweenPlayerAndBlock GetPlayerRelationToOwner()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetUserRelationToOwner"><code>MyRelationsBetweenPlayerAndBlock GetUserRelationToOwner(long playerId)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.UpdateIsWorking"><code>void UpdateIsWorking()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.UpdateVisual"><code>void UpdateVisual()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetInventory"><code>IMyInventory GetInventory()</code></a>_</td><td>Simply get the MyInventoryBase component stored in this entity.<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetInventory"><code>IMyInventory GetInventory(int index)</code></a>_</td><td>Search for inventory component with maching index.<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetPosition"><code>Vector3D GetPosition()</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
</table>
