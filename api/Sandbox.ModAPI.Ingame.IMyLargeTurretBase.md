← [Index](index)
# IMyLargeTurretBase Interface
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
**Implements:**
* [`Sandbox.ModAPI.Ingame.IMyUserControllableGun`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)
* [`Sandbox.ModAPI.Ingame.IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyFunctionalBlock)
* [`Sandbox.ModAPI.Ingame.IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTerminalBlock)
* [`VRage.Game.ModAPI.Ingame.IMyCubeBlock`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)
* [`VRage.Game.ModAPI.Ingame.IMyEntity`](VRage.Game.ModAPI.Ingame.IMyEntity)

**Inheritors:**
* [`SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)

### Properties
|Member|Description|
|---|---|
|[`IsUnderControl`](Sandbox.ModAPI.Ingame.IsUnderControl)|Indicates whether a block is locally or remotely controlled.|
|[`CanControl`](Sandbox.ModAPI.Ingame.CanControl)||
|[`Range`](Sandbox.ModAPI.Ingame.Range)||
|[`IsAimed`](Sandbox.ModAPI.Ingame.IsAimed)||
|[`HasTarget`](Sandbox.ModAPI.Ingame.HasTarget)|Checks if the turret is locked onto a target|
|[`Elevation`](Sandbox.ModAPI.Ingame.Elevation)|Sets/gets elevation of turret, this method is not synced, you need to sync elevation manually|
|[`Azimuth`](Sandbox.ModAPI.Ingame.Azimuth)|Sets/gets azimuth of turret, this method is not synced, you need to sync azimuth manually|
|[`EnableIdleRotation`](Sandbox.ModAPI.Ingame.EnableIdleRotation)|enable/disable idle rotation for turret, this method is not synced, you need to sync manually|
|[`AIEnabled`](Sandbox.ModAPI.Ingame.AIEnabled)|Checks is AI is enabled for turret|
|[`Components`](VRage.Game.ModAPI.Ingame.Components)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`EntityId`](VRage.Game.ModAPI.Ingame.EntityId)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`Name`](VRage.Game.ModAPI.Ingame.Name)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)|Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)|Returns the count of the number of inventories this entity has.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`CheckConnectionAllowed`](VRage.Game.ModAPI.Ingame.CheckConnectionAllowed)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid)|Grid in which the block is placed<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`DefinitionDisplayNameText`](VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText)|Definition name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`DisassembleRatio`](VRage.Game.ModAPI.Ingame.DisassembleRatio)|Is set in definition Ratio at which is the block disassembled (grinding)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`DisplayNameText`](VRage.Game.ModAPI.Ingame.DisplayNameText)|Translated block name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`IsBeingHacked`](VRage.Game.ModAPI.Ingame.IsBeingHacked)|Hacking of the block is in progress<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`IsFunctional`](VRage.Game.ModAPI.Ingame.IsFunctional)|True if integrity is above breaking threshold<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`IsWorking`](VRage.Game.ModAPI.Ingame.IsWorking)|True if block is able to do its work depening on block type (is functional, powered, enabled, etc...)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`Max`](VRage.Game.ModAPI.Ingame.Max)|Maximum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`Mass`](VRage.Game.ModAPI.Ingame.Mass)|Block mass<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`Min`](VRage.Game.ModAPI.Ingame.Min)|Minimum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`NumberInGrid`](VRage.Game.ModAPI.Ingame.NumberInGrid)|Order in which were the blocks of same type added to grid Used in default display name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`Orientation`](VRage.Game.ModAPI.Ingame.Orientation)|Returns block orientation in base 6 directions<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId)|Id of player owning block (not steam Id)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`Position`](VRage.Game.ModAPI.Ingame.Position)|Position in grid coordinates<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`CustomName`](Sandbox.ModAPI.Ingame.CustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`CustomNameWithFaction`](Sandbox.ModAPI.Ingame.CustomNameWithFaction)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`DetailedInfo`](Sandbox.ModAPI.Ingame.DetailedInfo)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`CustomInfo`](Sandbox.ModAPI.Ingame.CustomInfo)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`CustomData`](Sandbox.ModAPI.Ingame.CustomData)|Gets or sets the Custom Data string. NOTE: Only use this for user input. For storing large mod configs, create your own MyModStorageComponent<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`ShowOnHUD`](Sandbox.ModAPI.Ingame.ShowOnHUD)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`ShowInTerminal`](Sandbox.ModAPI.Ingame.ShowInTerminal)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`ShowInToolbarConfig`](Sandbox.ModAPI.Ingame.ShowInToolbarConfig)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`ShowInInventory`](Sandbox.ModAPI.Ingame.ShowInInventory)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`Enabled`](Sandbox.ModAPI.Ingame.Enabled)|_Inherited from [`IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`IsShooting`](Sandbox.ModAPI.Ingame.IsShooting)|_Inherited from [`IMyUserControllableGun`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
### Methods
|Member|Description|
|---|---|
|[`TrackTarget(Vector3D, Vector3)`](Sandbox.ModAPI.Ingame.TrackTarget)|Tracks given target with enabled position prediction|
|[`SetTarget(Vector3D)`](Sandbox.ModAPI.Ingame.SetTarget)|Targets given position|
|[`SyncElevation()`](Sandbox.ModAPI.Ingame.SyncElevation)|method used to sync elevation of turret , you need to call it to sync elevation for other clients/server|
|[`SyncAzimuth()`](Sandbox.ModAPI.Ingame.SyncAzimuth)|method used to sync azimuth, you need to call it to sync azimuth for other clients/server|
|[`SyncEnableIdleRotation()`](Sandbox.ModAPI.Ingame.SyncEnableIdleRotation)|method used to sync idle rotation and elevation, you need to call it to sync rotation and elevation for other clients/server|
|[`ResetTargetingToDefault()`](Sandbox.ModAPI.Ingame.ResetTargetingToDefault)|resert targeting to default values|
|[`GetTargetedEntity()`](Sandbox.ModAPI.Ingame.GetTargetedEntity)|Gets the turret's current detected entity, if any|
|[`GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)|Simply get the MyInventoryBase component stored in this entity.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`GetInventory(int)`](VRage.Game.ModAPI.Ingame.GetInventory)|Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`GetOwnerFactionTag()`](VRage.Game.ModAPI.Ingame.GetOwnerFactionTag)|Tag of faction owning block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`GetPlayerRelationToOwner()`](VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`GetUserRelationToOwner(long)`](VRage.Game.ModAPI.Ingame.GetUserRelationToOwner)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`UpdateIsWorking()`](VRage.Game.ModAPI.Ingame.UpdateIsWorking)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`UpdateVisual()`](VRage.Game.ModAPI.Ingame.UpdateVisual)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`HasLocalPlayerAccess()`](Sandbox.ModAPI.Ingame.HasLocalPlayerAccess)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`HasPlayerAccess(long)`](Sandbox.ModAPI.Ingame.HasPlayerAccess)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`SetCustomName(string)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`SetCustomName(StringBuilder)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`GetActions(List<ITerminalAction>, Func<ITerminalAction, bool>)`](Sandbox.ModAPI.Ingame.GetActions)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`SearchActionsOfName(string, List<ITerminalAction>, Func<ITerminalAction, bool>)`](Sandbox.ModAPI.Ingame.SearchActionsOfName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`GetActionWithName(string)`](Sandbox.ModAPI.Ingame.GetActionWithName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`GetProperty(string)`](Sandbox.ModAPI.Ingame.GetProperty)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`GetProperties(List<ITerminalProperty>, Func<ITerminalProperty, bool>)`](Sandbox.ModAPI.Ingame.GetProperties)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`IsSameConstructAs(IMyTerminalBlock)`](Sandbox.ModAPI.Ingame.IsSameConstructAs)|Determines whether this block is mechanically connected to the other. This is any block connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
|[`RequestEnable(bool)`](Sandbox.ModAPI.Ingame.RequestEnable)|_Inherited from [`IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)_|
