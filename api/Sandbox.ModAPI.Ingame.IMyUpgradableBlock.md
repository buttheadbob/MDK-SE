← [Index](index)
# IMyUpgradableBlock Interface
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
**Implements:**
* [`VRage.Game.ModAPI.Ingame.IMyCubeBlock`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)
* [`VRage.Game.ModAPI.Ingame.IMyEntity`](VRage.Game.ModAPI.Ingame.IMyEntity)
## Summary
interface to retrieve upgrade effects on block
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="Sandbox.ModAPI.Ingame.UpgradeCount"><code>uint UpgradeCount</code></a>_</td><td>number of upgrades applied</td></tr>
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
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.BlockDefinition"><code>SerializableDefinitionId BlockDefinition</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.CheckConnectionAllowed"><code>bool CheckConnectionAllowed</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.CubeGrid"><code>IMyCubeGrid CubeGrid</code></a>_</td><td>Grid in which the block is placed<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText"><code>string DefinitionDisplayNameText</code></a>_</td><td>Definition name<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.DisassembleRatio"><code>float DisassembleRatio</code></a>_</td><td>Is set in definition Ratio at which is the block disassembled (grinding)<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.DisplayNameText"><code>string DisplayNameText</code></a>_</td><td>Translated block name<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.IsBeingHacked"><code>bool IsBeingHacked</code></a>_</td><td>Hacking of the block is in progress<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.IsFunctional"><code>bool IsFunctional</code></a>_</td><td>True if integrity is above breaking threshold<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.IsWorking"><code>bool IsWorking</code></a>_</td><td>True if block is able to do its work depening on block type (is functional, powered, enabled, etc...)<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Max"><code>Vector3I Max</code></a>_</td><td>Maximum coordinates of grid cells occupied by this block<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Mass"><code>float Mass</code></a>_</td><td>Block mass<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Min"><code>Vector3I Min</code></a>_</td><td>Minimum coordinates of grid cells occupied by this block<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.NumberInGrid"><code>int NumberInGrid</code></a>_</td><td>Order in which were the blocks of same type added to grid Used in default display name<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Orientation"><code>MyBlockOrientation Orientation</code></a>_</td><td>Returns block orientation in base 6 directions<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.OwnerId"><code>long OwnerId</code></a>_</td><td>Id of player owning block (not steam Id)<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Position"><code>Vector3I Position</code></a>_</td><td>Position in grid coordinates<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="Sandbox.ModAPI.Ingame.GetUpgrades"><code>void GetUpgrades(ref Dictionary<string, float> upgrades)</code></a>_</td><td>get list of upgrades (r/o); string - upgrade type, float - effect value as float (1 = 100%)</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetInventory"><code>IMyInventory GetInventory()</code></a>_</td><td>Simply get the MyInventoryBase component stored in this entity.<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetInventory"><code>IMyInventory GetInventory(int index)</code></a>_</td><td>Search for inventory component with maching index.<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetPosition"><code>Vector3D GetPosition()</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyEntity"><code>IMyEntity</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetOwnerFactionTag"><code>string GetOwnerFactionTag()</code></a>_</td><td>Tag of faction owning block<br/><br/>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner"><code>MyRelationsBetweenPlayerAndBlock GetPlayerRelationToOwner()</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetUserRelationToOwner"><code>MyRelationsBetweenPlayerAndBlock GetUserRelationToOwner(long playerId)</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.UpdateIsWorking"><code>void UpdateIsWorking()</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.UpdateVisual"><code>void UpdateVisual()</code></a>_</td><td>_Inherited from <a href="VRage.Game.ModAPI.Ingame.IMyCubeBlock"><code>IMyCubeBlock</code></a>_</td></tr>
</table>
