← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### IMyLargeTurretBase Interface

```csharp
public interface IMyLargeTurretBase: IMyUserControllableGun, IMyFunctionalBlock, IMyTerminalBlock, IMyCubeBlock, IMyEntity
```

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

**Implements:**  
* [IMyUserControllableGun](Sandbox.ModAPI.Ingame.IMyUserControllableGun)  
* [IMyFunctionalBlock](Sandbox.ModAPI.Ingame.IMyFunctionalBlock)  
* [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)  
* [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)  
* [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)

**Inheritors:**  
* [IMyLargeConveyorTurretBase](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)

#### Properties

|Member|Description|
|---|---|
|[IsUnderControl](Sandbox.ModAPI.Ingame.IMyLargeTurretBase.IsUnderControl)|Indicates whether a block is locally or remotely controlled.|
|[CanControl](Sandbox.ModAPI.Ingame.IMyLargeTurretBase.CanControl)||
|[Range](Sandbox.ModAPI.Ingame.IMyLargeTurretBase.Range)||
|[IsAimed](Sandbox.ModAPI.Ingame.IMyLargeTurretBase.IsAimed)||
|[HasTarget](Sandbox.ModAPI.Ingame.IMyLargeTurretBase.HasTarget)|Checks if the turret is locked onto a target|
|[Elevation](Sandbox.ModAPI.Ingame.IMyLargeTurretBase.Elevation)|Sets/gets elevation of turret, this method is not synced, you need to sync elevation manually|
|[Azimuth](Sandbox.ModAPI.Ingame.IMyLargeTurretBase.Azimuth)|Sets/gets azimuth of turret, this method is not synced, you need to sync azimuth manually|
|[EnableIdleRotation](Sandbox.ModAPI.Ingame.IMyLargeTurretBase.EnableIdleRotation)|enable/disable idle rotation for turret, this method is not synced, you need to sync manually|
|[AIEnabled](Sandbox.ModAPI.Ingame.IMyLargeTurretBase.AIEnabled)|Checks is AI is enabled for turret|
|[Components](VRage.Game.ModAPI.Ingame.IMyEntity.Components)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[EntityId](VRage.Game.ModAPI.Ingame.IMyEntity.EntityId)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[Name](VRage.Game.ModAPI.Ingame.IMyEntity.Name)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[DisplayName](VRage.Game.ModAPI.Ingame.IMyEntity.DisplayName)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[HasInventory](VRage.Game.ModAPI.Ingame.IMyEntity.HasInventory)|Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[InventoryCount](VRage.Game.ModAPI.Ingame.IMyEntity.InventoryCount)|Returns the count of the number of inventories this entity has.<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[WorldAABB](VRage.Game.ModAPI.Ingame.IMyEntity.WorldAABB)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[WorldAABBHr](VRage.Game.ModAPI.Ingame.IMyEntity.WorldAABBHr)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[WorldMatrix](VRage.Game.ModAPI.Ingame.IMyEntity.WorldMatrix)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[WorldVolume](VRage.Game.ModAPI.Ingame.IMyEntity.WorldVolume)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[WorldVolumeHr](VRage.Game.ModAPI.Ingame.IMyEntity.WorldVolumeHr)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[BlockDefinition](VRage.Game.ModAPI.Ingame.IMyCubeBlock.BlockDefinition)|_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[CheckConnectionAllowed](VRage.Game.ModAPI.Ingame.IMyCubeBlock.CheckConnectionAllowed)|_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[CubeGrid](VRage.Game.ModAPI.Ingame.IMyCubeBlock.CubeGrid)|Grid in which the block is placed<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[DefinitionDisplayNameText](VRage.Game.ModAPI.Ingame.IMyCubeBlock.DefinitionDisplayNameText)|Definition name<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[DisassembleRatio](VRage.Game.ModAPI.Ingame.IMyCubeBlock.DisassembleRatio)|Is set in definition Ratio at which is the block disassembled (grinding)<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[DisplayNameText](VRage.Game.ModAPI.Ingame.IMyCubeBlock.DisplayNameText)|Translated block name<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[IsBeingHacked](VRage.Game.ModAPI.Ingame.IMyCubeBlock.IsBeingHacked)|Hacking of the block is in progress<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[IsFunctional](VRage.Game.ModAPI.Ingame.IMyCubeBlock.IsFunctional)|True if integrity is above breaking threshold<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[IsWorking](VRage.Game.ModAPI.Ingame.IMyCubeBlock.IsWorking)|True if block is able to do its work depening on block type (is functional, powered, enabled, etc...)<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[Max](VRage.Game.ModAPI.Ingame.IMyCubeBlock.Max)|Maximum coordinates of grid cells occupied by this block<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[Mass](VRage.Game.ModAPI.Ingame.IMyCubeBlock.Mass)|Block mass<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[Min](VRage.Game.ModAPI.Ingame.IMyCubeBlock.Min)|Minimum coordinates of grid cells occupied by this block<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[NumberInGrid](VRage.Game.ModAPI.Ingame.IMyCubeBlock.NumberInGrid)|Order in which were the blocks of same type added to grid Used in default display name<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[Orientation](VRage.Game.ModAPI.Ingame.IMyCubeBlock.Orientation)|Returns block orientation in base 6 directions<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[OwnerId](VRage.Game.ModAPI.Ingame.IMyCubeBlock.OwnerId)|Id of player owning block (not steam Id)<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[Position](VRage.Game.ModAPI.Ingame.IMyCubeBlock.Position)|Position in grid coordinates<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[CustomName](Sandbox.ModAPI.Ingame.IMyTerminalBlock.CustomName)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[CustomNameWithFaction](Sandbox.ModAPI.Ingame.IMyTerminalBlock.CustomNameWithFaction)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[DetailedInfo](Sandbox.ModAPI.Ingame.IMyTerminalBlock.DetailedInfo)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[CustomInfo](Sandbox.ModAPI.Ingame.IMyTerminalBlock.CustomInfo)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[CustomData](Sandbox.ModAPI.Ingame.IMyTerminalBlock.CustomData)|Gets or sets the Custom Data string. NOTE: Only use this for user input. For storing large mod configs, create your own MyModStorageComponent<br /><br />_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[ShowOnHUD](Sandbox.ModAPI.Ingame.IMyTerminalBlock.ShowOnHUD)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[ShowInTerminal](Sandbox.ModAPI.Ingame.IMyTerminalBlock.ShowInTerminal)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[ShowInToolbarConfig](Sandbox.ModAPI.Ingame.IMyTerminalBlock.ShowInToolbarConfig)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[ShowInInventory](Sandbox.ModAPI.Ingame.IMyTerminalBlock.ShowInInventory)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[Enabled](Sandbox.ModAPI.Ingame.IMyFunctionalBlock.Enabled)|_Inherited from [IMyFunctionalBlock](Sandbox.ModAPI.Ingame.IMyFunctionalBlock)_|
|[IsShooting](Sandbox.ModAPI.Ingame.IMyUserControllableGun.IsShooting)|_Inherited from [IMyUserControllableGun](Sandbox.ModAPI.Ingame.IMyUserControllableGun)_|

#### Methods

|Member|Description|
|---|---|
|[TrackTarget(Vector3D, Vector3)](Sandbox.ModAPI.Ingame.IMyLargeTurretBase.TrackTarget)|Tracks given target with enabled position prediction|
|[SetTarget(Vector3D)](Sandbox.ModAPI.Ingame.IMyLargeTurretBase.SetTarget)|Targets given position|
|[SyncElevation()](Sandbox.ModAPI.Ingame.IMyLargeTurretBase.SyncElevation)|method used to sync elevation of turret , you need to call it to sync elevation for other clients/server|
|[SyncAzimuth()](Sandbox.ModAPI.Ingame.IMyLargeTurretBase.SyncAzimuth)|method used to sync azimuth, you need to call it to sync azimuth for other clients/server|
|[SyncEnableIdleRotation()](Sandbox.ModAPI.Ingame.IMyLargeTurretBase.SyncEnableIdleRotation)|method used to sync idle rotation and elevation, you need to call it to sync rotation and elevation for other clients/server|
|[ResetTargetingToDefault()](Sandbox.ModAPI.Ingame.IMyLargeTurretBase.ResetTargetingToDefault)|resert targeting to default values|
|[GetTargetedEntity()](Sandbox.ModAPI.Ingame.IMyLargeTurretBase.GetTargetedEntity)|Gets the turret's current detected entity, if any|
|[GetInventory()](VRage.Game.ModAPI.Ingame.IMyEntity.GetInventory)|Simply get the MyInventoryBase component stored in this entity.<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[GetInventory(int)](VRage.Game.ModAPI.Ingame.IMyEntity.GetInventory)|Search for inventory component with maching index.<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[GetPosition()](VRage.Game.ModAPI.Ingame.IMyEntity.GetPosition)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[GetOwnerFactionTag()](VRage.Game.ModAPI.Ingame.IMyCubeBlock.GetOwnerFactionTag)|Tag of faction owning block<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[GetPlayerRelationToOwner()](VRage.Game.ModAPI.Ingame.IMyCubeBlock.GetPlayerRelationToOwner)|_**Obsolete:** GetPlayerRelationToOwner() is useless ingame. Mods should use the one in ModAPI.IMyCubeBlock_<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[GetUserRelationToOwner(long)](VRage.Game.ModAPI.Ingame.IMyCubeBlock.GetUserRelationToOwner)|_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[UpdateIsWorking()](VRage.Game.ModAPI.Ingame.IMyCubeBlock.UpdateIsWorking)|_**Obsolete:** _<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[UpdateVisual()](VRage.Game.ModAPI.Ingame.IMyCubeBlock.UpdateVisual)|_**Obsolete:** _<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[HasLocalPlayerAccess()](Sandbox.ModAPI.Ingame.IMyTerminalBlock.HasLocalPlayerAccess)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[HasPlayerAccess(long)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.HasPlayerAccess)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[SetCustomName(string)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.SetCustomName)|_**Obsolete:** Use the setter of Customname_<br /><br />_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[SetCustomName(StringBuilder)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.SetCustomName)|_**Obsolete:** Use the setter of Customname_<br /><br />_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[GetActions(List, Func)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.GetActions)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[SearchActionsOfName(string, List, Func)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.SearchActionsOfName)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[GetActionWithName(string)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.GetActionWithName)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[GetProperty(string)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.GetProperty)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[GetProperties(List, Func)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.GetProperties)|_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[IsSameConstructAs(IMyTerminalBlock)](Sandbox.ModAPI.Ingame.IMyTerminalBlock.IsSameConstructAs)|Determines whether this block is mechanically connected to the other. This is any block connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br /><br />Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.<br /><br />_Inherited from [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)_|
|[RequestEnable(bool)](Sandbox.ModAPI.Ingame.IMyFunctionalBlock.RequestEnable)|_**Obsolete:** Use the setter of Enabled_<br /><br />_Inherited from [IMyFunctionalBlock](Sandbox.ModAPI.Ingame.IMyFunctionalBlock)_|

