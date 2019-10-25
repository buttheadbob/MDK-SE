← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### IMyFunctionalBlock Interface

```csharp
public interface IMyFunctionalBlock: IMyTerminalBlock, IMyCubeBlock, IMyEntity
```

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

**Implements:**  
* [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)  
* [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)  
* [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)

**Inheritors:**  
* [IMyAdvancedDoor](Sandbox.ModAPI.Ingame.IMyAdvancedDoor)  
* [IMyAirtightDoorBase](Sandbox.ModAPI.Ingame.IMyAirtightDoorBase)  
* [IMyAirtightHangarDoor](Sandbox.ModAPI.Ingame.IMyAirtightHangarDoor)  
* [IMyAirtightSlideDoor](Sandbox.ModAPI.Ingame.IMyAirtightSlideDoor)  
* [IMyAssembler](Sandbox.ModAPI.Ingame.IMyAssembler)  
* [IMyBatteryBlock](Sandbox.ModAPI.Ingame.IMyBatteryBlock)  
* [IMyBeacon](Sandbox.ModAPI.Ingame.IMyBeacon)  
* [IMyCameraBlock](Sandbox.ModAPI.Ingame.IMyCameraBlock)  
* [IMyCollector](Sandbox.ModAPI.Ingame.IMyCollector)  
* [IMyConveyorSorter](Sandbox.ModAPI.Ingame.IMyConveyorSorter)  
* [IMyDecoy](Sandbox.ModAPI.Ingame.IMyDecoy)  
* [IMyDoor](Sandbox.ModAPI.Ingame.IMyDoor)  
* [IMyExtendedPistonBase](Sandbox.ModAPI.Ingame.IMyExtendedPistonBase)  
* [IMyGyro](Sandbox.ModAPI.Ingame.IMyGyro)  
* [IMyJumpDrive](Sandbox.ModAPI.Ingame.IMyJumpDrive)  
* [IMyLargeTurretBase](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)  
* [IMyLaserAntenna](Sandbox.ModAPI.Ingame.IMyLaserAntenna)  
* [IMyLightingBlock](Sandbox.ModAPI.Ingame.IMyLightingBlock)  
* [IMyMechanicalConnectionBlock](Sandbox.ModAPI.Ingame.IMyMechanicalConnectionBlock)  
* [IMyMotorAdvancedStator](Sandbox.ModAPI.Ingame.IMyMotorAdvancedStator)  
* [IMyMotorBase](Sandbox.ModAPI.Ingame.IMyMotorBase)  
* [IMyMotorStator](Sandbox.ModAPI.Ingame.IMyMotorStator)  
* [IMyMotorSuspension](Sandbox.ModAPI.Ingame.IMyMotorSuspension)  
* [IMyOreDetector](Sandbox.ModAPI.Ingame.IMyOreDetector)  
* [IMyGasGenerator](Sandbox.ModAPI.Ingame.IMyGasGenerator)  
* [IMyOxygenGenerator](Sandbox.ModAPI.Ingame.IMyOxygenGenerator)  
* [IMyGasTank](Sandbox.ModAPI.Ingame.IMyGasTank)  
* [IMyOxygenTank](Sandbox.ModAPI.Ingame.IMyOxygenTank)  
* [IMyPistonBase](Sandbox.ModAPI.Ingame.IMyPistonBase)  
* [IMyPowerProducer](Sandbox.ModAPI.Ingame.IMyPowerProducer)  
* [IMyProductionBlock](Sandbox.ModAPI.Ingame.IMyProductionBlock)  
* [IMyProgrammableBlock](Sandbox.ModAPI.Ingame.IMyProgrammableBlock)  
* [IMyProjector](Sandbox.ModAPI.Ingame.IMyProjector)  
* [IMyRadioAntenna](Sandbox.ModAPI.Ingame.IMyRadioAntenna)  
* [IMyReactor](Sandbox.ModAPI.Ingame.IMyReactor)  
* [IMyRefinery](Sandbox.ModAPI.Ingame.IMyRefinery)  
* [IMyReflectorLight](Sandbox.ModAPI.Ingame.IMyReflectorLight)  
* [IMySensorBlock](Sandbox.ModAPI.Ingame.IMySensorBlock)  
* [IMyShipConnector](Sandbox.ModAPI.Ingame.IMyShipConnector)  
* [IMyShipDrill](Sandbox.ModAPI.Ingame.IMyShipDrill)  
* [IMyShipGrinder](Sandbox.ModAPI.Ingame.IMyShipGrinder)  
* [IMyShipToolBase](Sandbox.ModAPI.Ingame.IMyShipToolBase)  
* [IMyShipWelder](Sandbox.ModAPI.Ingame.IMyShipWelder)  
* [IMySmallGatlingGun](Sandbox.ModAPI.Ingame.IMySmallGatlingGun)  
* [IMySmallMissileLauncher](Sandbox.ModAPI.Ingame.IMySmallMissileLauncher)  
* [IMySmallMissileLauncherReload](Sandbox.ModAPI.Ingame.IMySmallMissileLauncherReload)  
* [IMyStoreBlock](Sandbox.ModAPI.Ingame.IMyStoreBlock)  
* [IMyTextPanel](Sandbox.ModAPI.Ingame.IMyTextPanel)  
* [IMyThrust](Sandbox.ModAPI.Ingame.IMyThrust)  
* [IMyUpgradeModule](Sandbox.ModAPI.Ingame.IMyUpgradeModule)  
* [IMyUserControllableGun](Sandbox.ModAPI.Ingame.IMyUserControllableGun)  
* [IMyAirVent](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)  
* [IMyArtificialMassBlock](SpaceEngineers.Game.ModAPI.Ingame.IMyArtificialMassBlock)  
* [IMyGravityGenerator](SpaceEngineers.Game.ModAPI.Ingame.IMyGravityGenerator)  
* [IMyGravityGeneratorBase](SpaceEngineers.Game.ModAPI.Ingame.IMyGravityGeneratorBase)  
* [IMyGravityGeneratorSphere](SpaceEngineers.Game.ModAPI.Ingame.IMyGravityGeneratorSphere)  
* [IMyInteriorLight](SpaceEngineers.Game.ModAPI.Ingame.IMyInteriorLight)  
* [IMyLandingGear](SpaceEngineers.Game.ModAPI.Ingame.IMyLandingGear)  
* [IMyLargeConveyorTurretBase](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)  
* [IMyLargeGatlingTurret](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeGatlingTurret)  
* [IMyLargeInteriorTurret](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeInteriorTurret)  
* [IMyLargeMissileTurret](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeMissileTurret)  
* [IMyMedicalRoom](SpaceEngineers.Game.ModAPI.Ingame.IMyMedicalRoom)  
* [IMyParachute](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)  
* [IMySafeZoneBlock](SpaceEngineers.Game.ModAPI.Ingame.IMySafeZoneBlock)  
* [IMyShipMergeBlock](SpaceEngineers.Game.ModAPI.Ingame.IMyShipMergeBlock)  
* [IMySolarPanel](SpaceEngineers.Game.ModAPI.Ingame.IMySolarPanel)  
* [IMySoundBlock](SpaceEngineers.Game.ModAPI.Ingame.IMySoundBlock)  
* [IMySpaceBall](SpaceEngineers.Game.ModAPI.Ingame.IMySpaceBall)  
* [IMyTimerBlock](SpaceEngineers.Game.ModAPI.Ingame.IMyTimerBlock)  
* [IMyVirtualMass](SpaceEngineers.Game.ModAPI.Ingame.IMyVirtualMass)

#### Properties

|Member|Description|
|---|---|
|[Enabled](Sandbox.ModAPI.Ingame.IMyFunctionalBlock.Enabled)||
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

#### Methods

|Member|Description|
|---|---|
|[RequestEnable(bool)](Sandbox.ModAPI.Ingame.IMyFunctionalBlock.RequestEnable)|_**Obsolete:** Use the setter of Enabled_|
|[GetInventory()](VRage.Game.ModAPI.Ingame.IMyEntity.GetInventory)|Simply get the MyInventoryBase component stored in this entity.<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[GetInventory(int)](VRage.Game.ModAPI.Ingame.IMyEntity.GetInventory)|Search for inventory component with maching index.<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[GetPosition()](VRage.Game.ModAPI.Ingame.IMyEntity.GetPosition)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[GetOwnerFactionTag()](VRage.Game.ModAPI.Ingame.IMyCubeBlock.GetOwnerFactionTag)|Tag of faction owning block<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[GetPlayerRelationToOwner()](VRage.Game.ModAPI.Ingame.IMyCubeBlock.GetPlayerRelationToOwner)|_**Obsolete:** GetPlayerRelationToOwner() is useless ingame. Mods should use the one in ModAPI.IMyCubeBlock_<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[GetUserRelationToOwner(long)](VRage.Game.ModAPI.Ingame.IMyCubeBlock.GetUserRelationToOwner)|_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[UpdateIsWorking()](VRage.Game.ModAPI.Ingame.IMyCubeBlock.UpdateIsWorking)|_**Obsolete**_<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
|[UpdateVisual()](VRage.Game.ModAPI.Ingame.IMyCubeBlock.UpdateVisual)|_**Obsolete**_<br /><br />_Inherited from [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)_|
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

