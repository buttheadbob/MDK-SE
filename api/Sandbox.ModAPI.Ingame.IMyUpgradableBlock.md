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
<table style="width: 100%">
<tr><td>[`uint UpgradeCount`](Sandbox.ModAPI.Ingame.UpgradeCount)</td><td>number of upgrades applied</td></tr>
<tr><td>[`MyEntityComponentContainer Components`](VRage.Game.ModAPI.Ingame.Components)</td><td>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`long EntityId`](VRage.Game.ModAPI.Ingame.EntityId)</td><td>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`string Name`](VRage.Game.ModAPI.Ingame.Name)</td><td>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`string DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)</td><td>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`bool HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)</td><td>Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`int InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)</td><td>Returns the count of the number of inventories this entity has.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`BoundingBoxD WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)</td><td>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`BoundingBoxD WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)</td><td>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`MatrixD WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)</td><td>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`BoundingSphereD WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)</td><td>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`BoundingSphereD WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)</td><td>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`SerializableDefinitionId BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition)</td><td>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`bool CheckConnectionAllowed`](VRage.Game.ModAPI.Ingame.CheckConnectionAllowed)</td><td>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`IMyCubeGrid CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid)</td><td>Grid in which the block is placed<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`string DefinitionDisplayNameText`](VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText)</td><td>Definition name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`float DisassembleRatio`](VRage.Game.ModAPI.Ingame.DisassembleRatio)</td><td>Is set in definition Ratio at which is the block disassembled (grinding)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`string DisplayNameText`](VRage.Game.ModAPI.Ingame.DisplayNameText)</td><td>Translated block name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`bool IsBeingHacked`](VRage.Game.ModAPI.Ingame.IsBeingHacked)</td><td>Hacking of the block is in progress<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`bool IsFunctional`](VRage.Game.ModAPI.Ingame.IsFunctional)</td><td>True if integrity is above breaking threshold<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`bool IsWorking`](VRage.Game.ModAPI.Ingame.IsWorking)</td><td>True if block is able to do its work depening on block type (is functional, powered, enabled, etc...)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`Vector3I Max`](VRage.Game.ModAPI.Ingame.Max)</td><td>Maximum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`float Mass`](VRage.Game.ModAPI.Ingame.Mass)</td><td>Block mass<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`Vector3I Min`](VRage.Game.ModAPI.Ingame.Min)</td><td>Minimum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`int NumberInGrid`](VRage.Game.ModAPI.Ingame.NumberInGrid)</td><td>Order in which were the blocks of same type added to grid Used in default display name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`MyBlockOrientation Orientation`](VRage.Game.ModAPI.Ingame.Orientation)</td><td>Returns block orientation in base 6 directions<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`long OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId)</td><td>Id of player owning block (not steam Id)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`Vector3I Position`](VRage.Game.ModAPI.Ingame.Position)</td><td>Position in grid coordinates<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
</table>
### Methods
<table style="width: 100%">
<tr><td>[`void GetUpgrades(ref Dictionary<string, float> upgrades)`](Sandbox.ModAPI.Ingame.GetUpgrades)</td><td>get list of upgrades (r/o); string - upgrade type, float - effect value as float (1 = 100%)</td></tr>
<tr><td>[`IMyInventory GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)</td><td>Simply get the MyInventoryBase component stored in this entity.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`IMyInventory GetInventory(int index)`](VRage.Game.ModAPI.Ingame.GetInventory)</td><td>Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`Vector3D GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)</td><td>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`string GetOwnerFactionTag()`](VRage.Game.ModAPI.Ingame.GetOwnerFactionTag)</td><td>Tag of faction owning block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`MyRelationsBetweenPlayerAndBlock GetPlayerRelationToOwner()`](VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner)</td><td>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`MyRelationsBetweenPlayerAndBlock GetUserRelationToOwner(long playerId)`](VRage.Game.ModAPI.Ingame.GetUserRelationToOwner)</td><td>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`void UpdateIsWorking()`](VRage.Game.ModAPI.Ingame.UpdateIsWorking)</td><td>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
<tr><td>[`void UpdateVisual()`](VRage.Game.ModAPI.Ingame.UpdateVisual)</td><td>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)_</td></tr>
</table>
