← [Index](index)
# IMyLargeConveyorTurretBase Interface
**Namespace:** [`SpaceEngineers.Game.ModAPI.Ingame`](SpaceEngineers.Game.ModAPI.Ingame)  
**Assembly:** SpaceEngineers.Game.dll  
**Implements:**
* [`Sandbox.ModAPI.Ingame.IMyLargeTurretBase`](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)
* [`Sandbox.ModAPI.Ingame.IMyUserControllableGun`](Sandbox.ModAPI.Ingame.IMyUserControllableGun)
* [`Sandbox.ModAPI.Ingame.IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyFunctionalBlock)
* [`Sandbox.ModAPI.Ingame.IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTerminalBlock)
* [`VRage.Game.ModAPI.Ingame.IMyCubeBlock`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)
* [`VRage.Game.ModAPI.Ingame.IMyEntity`](VRage.Game.ModAPI.Ingame.IMyEntity)
### Properties
|Member|Description|
|---|---|
|[`bool UseConveyorSystem`](SpaceEngineers.Game.ModAPI.Ingame.UseConveyorSystem)||
|[`MyEntityComponentContainer Components`](VRage.Game.ModAPI.Ingame.Components)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`long EntityId`](VRage.Game.ModAPI.Ingame.EntityId)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`string Name`](VRage.Game.ModAPI.Ingame.Name)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`string DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`bool HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)|Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.<br/><br/>_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`int InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)|Returns the count of the number of inventories this entity has.<br/><br/>_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`BoundingBoxD WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`BoundingBoxD WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`MatrixD WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`BoundingSphereD WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`BoundingSphereD WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`SerializableDefinitionId BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`bool CheckConnectionAllowed`](VRage.Game.ModAPI.Ingame.CheckConnectionAllowed)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`IMyCubeGrid CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid)|Grid in which the block is placed<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`string DefinitionDisplayNameText`](VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText)|Definition name<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`float DisassembleRatio`](VRage.Game.ModAPI.Ingame.DisassembleRatio)|Is set in definition Ratio at which is the block disassembled (grinding)<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`string DisplayNameText`](VRage.Game.ModAPI.Ingame.DisplayNameText)|Translated block name<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`bool IsBeingHacked`](VRage.Game.ModAPI.Ingame.IsBeingHacked)|Hacking of the block is in progress<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`bool IsFunctional`](VRage.Game.ModAPI.Ingame.IsFunctional)|True if integrity is above breaking threshold<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`bool IsWorking`](VRage.Game.ModAPI.Ingame.IsWorking)|True if block is able to do its work depening on block type (is functional, powered, enabled, etc...)<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`Vector3I Max`](VRage.Game.ModAPI.Ingame.Max)|Maximum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`float Mass`](VRage.Game.ModAPI.Ingame.Mass)|Block mass<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`Vector3I Min`](VRage.Game.ModAPI.Ingame.Min)|Minimum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`int NumberInGrid`](VRage.Game.ModAPI.Ingame.NumberInGrid)|Order in which were the blocks of same type added to grid Used in default display name<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`MyBlockOrientation Orientation`](VRage.Game.ModAPI.Ingame.Orientation)|Returns block orientation in base 6 directions<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`long OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId)|Id of player owning block (not steam Id)<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`Vector3I Position`](VRage.Game.ModAPI.Ingame.Position)|Position in grid coordinates<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`string CustomName`](Sandbox.ModAPI.Ingame.CustomName)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`string CustomNameWithFaction`](Sandbox.ModAPI.Ingame.CustomNameWithFaction)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`string DetailedInfo`](Sandbox.ModAPI.Ingame.DetailedInfo)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`string CustomInfo`](Sandbox.ModAPI.Ingame.CustomInfo)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`string CustomData`](Sandbox.ModAPI.Ingame.CustomData)|Gets or sets the Custom Data string. NOTE: Only use this for user input. For storing large mod configs, create your own MyModStorageComponent<br/><br/>_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`bool ShowOnHUD`](Sandbox.ModAPI.Ingame.ShowOnHUD)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`bool ShowInTerminal`](Sandbox.ModAPI.Ingame.ShowInTerminal)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`bool ShowInToolbarConfig`](Sandbox.ModAPI.Ingame.ShowInToolbarConfig)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`bool ShowInInventory`](Sandbox.ModAPI.Ingame.ShowInInventory)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`bool Enabled`](Sandbox.ModAPI.Ingame.Enabled)|_Inherited from [`IMyFunctionalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`bool IsShooting`](Sandbox.ModAPI.Ingame.IsShooting)|_Inherited from [`IMyUserControllableGun`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`bool IsUnderControl`](Sandbox.ModAPI.Ingame.IsUnderControl)|Indicates whether a block is locally or remotely controlled.<br/><br/>_Inherited from [`IMyLargeTurretBase`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`bool CanControl`](Sandbox.ModAPI.Ingame.CanControl)|_Inherited from [`IMyLargeTurretBase`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`float Range`](Sandbox.ModAPI.Ingame.Range)|_Inherited from [`IMyLargeTurretBase`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`bool IsAimed`](Sandbox.ModAPI.Ingame.IsAimed)|_Inherited from [`IMyLargeTurretBase`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`bool HasTarget`](Sandbox.ModAPI.Ingame.HasTarget)|Checks if the turret is locked onto a target<br/><br/>_Inherited from [`IMyLargeTurretBase`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`float Elevation`](Sandbox.ModAPI.Ingame.Elevation)|Sets/gets elevation of turret, this method is not synced, you need to sync elevation manually<br/><br/>_Inherited from [`IMyLargeTurretBase`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`float Azimuth`](Sandbox.ModAPI.Ingame.Azimuth)|Sets/gets azimuth of turret, this method is not synced, you need to sync azimuth manually<br/><br/>_Inherited from [`IMyLargeTurretBase`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`bool EnableIdleRotation`](Sandbox.ModAPI.Ingame.EnableIdleRotation)|enable/disable idle rotation for turret, this method is not synced, you need to sync manually<br/><br/>_Inherited from [`IMyLargeTurretBase`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`bool AIEnabled`](Sandbox.ModAPI.Ingame.AIEnabled)|Checks is AI is enabled for turret<br/><br/>_Inherited from [`IMyLargeTurretBase`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
### Methods
|Member|Description|
|---|---|
|[`IMyInventory GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)|Simply get the MyInventoryBase component stored in this entity.<br/><br/>_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`IMyInventory GetInventory(int index)`](VRage.Game.ModAPI.Ingame.GetInventory)|Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`Vector3D GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`string GetOwnerFactionTag()`](VRage.Game.ModAPI.Ingame.GetOwnerFactionTag)|Tag of faction owning block<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`MyRelationsBetweenPlayerAndBlock GetPlayerRelationToOwner()`](VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`MyRelationsBetweenPlayerAndBlock GetUserRelationToOwner(long playerId)`](VRage.Game.ModAPI.Ingame.GetUserRelationToOwner)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`void UpdateIsWorking()`](VRage.Game.ModAPI.Ingame.UpdateIsWorking)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`void UpdateVisual()`](VRage.Game.ModAPI.Ingame.UpdateVisual)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`bool HasLocalPlayerAccess()`](Sandbox.ModAPI.Ingame.HasLocalPlayerAccess)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`bool HasPlayerAccess(long playerId)`](Sandbox.ModAPI.Ingame.HasPlayerAccess)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`void SetCustomName(string text)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`void SetCustomName(StringBuilder text)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`void GetActions(List<ITerminalAction> resultList, Func<ITerminalAction, bool> collect)`](Sandbox.ModAPI.Ingame.GetActions)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`void SearchActionsOfName(string name, List<ITerminalAction> resultList, Func<ITerminalAction, bool> collect)`](Sandbox.ModAPI.Ingame.SearchActionsOfName)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`ITerminalAction GetActionWithName(string name)`](Sandbox.ModAPI.Ingame.GetActionWithName)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`ITerminalProperty GetProperty(string id)`](Sandbox.ModAPI.Ingame.GetProperty)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`void GetProperties(List<ITerminalProperty> resultList, Func<ITerminalProperty, bool> collect)`](Sandbox.ModAPI.Ingame.GetProperties)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`bool IsSameConstructAs(IMyTerminalBlock other)`](Sandbox.ModAPI.Ingame.IsSameConstructAs)|Determines whether this block is mechanically connected to the other. This is any block connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.<br/><br/>_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`void RequestEnable(bool enable)`](Sandbox.ModAPI.Ingame.RequestEnable)|_Inherited from [`IMyFunctionalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`void TrackTarget(Vector3D pos, Vector3 velocity)`](Sandbox.ModAPI.Ingame.TrackTarget)|Tracks given target with enabled position prediction<br/><br/>_Inherited from [`IMyLargeTurretBase`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`void SetTarget(Vector3D pos)`](Sandbox.ModAPI.Ingame.SetTarget)|Targets given position<br/><br/>_Inherited from [`IMyLargeTurretBase`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`void SyncElevation()`](Sandbox.ModAPI.Ingame.SyncElevation)|method used to sync elevation of turret , you need to call it to sync elevation for other clients/server<br/><br/>_Inherited from [`IMyLargeTurretBase`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`void SyncAzimuth()`](Sandbox.ModAPI.Ingame.SyncAzimuth)|method used to sync azimuth, you need to call it to sync azimuth for other clients/server<br/><br/>_Inherited from [`IMyLargeTurretBase`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`void SyncEnableIdleRotation()`](Sandbox.ModAPI.Ingame.SyncEnableIdleRotation)|method used to sync idle rotation and elevation, you need to call it to sync rotation and elevation for other clients/server<br/><br/>_Inherited from [`IMyLargeTurretBase`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`void ResetTargetingToDefault()`](Sandbox.ModAPI.Ingame.ResetTargetingToDefault)|resert targeting to default values<br/><br/>_Inherited from [`IMyLargeTurretBase`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
|[`MyDetectedEntityInfo GetTargetedEntity()`](Sandbox.ModAPI.Ingame.GetTargetedEntity)|Gets the turret's current detected entity, if any<br/><br/>_Inherited from [`IMyLargeTurretBase`](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)_|
