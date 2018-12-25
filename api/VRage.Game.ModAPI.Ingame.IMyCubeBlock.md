← [Index](Api-Index)

#### IMyCubeBlock Interface

```csharp
public interface IMyCubeBlock
```

**Namespace:** [VRage.Game.ModAPI.Ingame](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll

**Implements:**  
* [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)

**Inheritors:**  
* [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)  
* [IMyFunctionalBlock](Sandbox.ModAPI.Ingame.IMyFunctionalBlock)  
* [IMyDoor](Sandbox.ModAPI.Ingame.IMyDoor)  
* [IMyProductionBlock](Sandbox.ModAPI.Ingame.IMyProductionBlock)  
* [IMyAssembler](Sandbox.ModAPI.Ingame.IMyAssembler)  
* [IMyAttachableTopBlock](Sandbox.ModAPI.Ingame.IMyAttachableTopBlock)  
* [IMyBatteryBlock](Sandbox.ModAPI.Ingame.IMyBatteryBlock)  
* [IMyBeacon](Sandbox.ModAPI.Ingame.IMyBeacon)  
* [IMyCameraBlock](Sandbox.ModAPI.Ingame.IMyCameraBlock)  
* [IMyShipController](Sandbox.ModAPI.Ingame.IMyShipController)  
* [IMyCockpit](Sandbox.ModAPI.Ingame.IMyCockpit)  
* [IMyCollector](Sandbox.ModAPI.Ingame.IMyCollector)  
* [IMyConveyorSorter](Sandbox.ModAPI.Ingame.IMyConveyorSorter)  
* [IMyGyro](Sandbox.ModAPI.Ingame.IMyGyro)  
* [IMyJumpDrive](Sandbox.ModAPI.Ingame.IMyJumpDrive)  
* [IMyUserControllableGun](Sandbox.ModAPI.Ingame.IMyUserControllableGun)  
* [IMyLargeTurretBase](Sandbox.ModAPI.Ingame.IMyLargeTurretBase)  
* [IMyLaserAntenna](Sandbox.ModAPI.Ingame.IMyLaserAntenna)  
* [IMyLightingBlock](Sandbox.ModAPI.Ingame.IMyLightingBlock)  
* [IMyMechanicalConnectionBlock](Sandbox.ModAPI.Ingame.IMyMechanicalConnectionBlock)  
* [IMyMotorStator](Sandbox.ModAPI.Ingame.IMyMotorStator)  
* [IMyOreDetector](Sandbox.ModAPI.Ingame.IMyOreDetector)  
* [IMyGasGenerator](Sandbox.ModAPI.Ingame.IMyGasGenerator)  
* [IMyGasTank](Sandbox.ModAPI.Ingame.IMyGasTank)  
* [IMyOxygenTank](Sandbox.ModAPI.Ingame.IMyOxygenTank)  
* [IMyPistonBase](Sandbox.ModAPI.Ingame.IMyPistonBase)  
* [IMyProgrammableBlock](Sandbox.ModAPI.Ingame.IMyProgrammableBlock)  
* [IMyProjector](Sandbox.ModAPI.Ingame.IMyProjector)  
* [IMyRadioAntenna](Sandbox.ModAPI.Ingame.IMyRadioAntenna)  
* [IMyReactor](Sandbox.ModAPI.Ingame.IMyReactor)  
* [IMyRemoteControl](Sandbox.ModAPI.Ingame.IMyRemoteControl)  
* [IMySensorBlock](Sandbox.ModAPI.Ingame.IMySensorBlock)  
* [IMyShipConnector](Sandbox.ModAPI.Ingame.IMyShipConnector)  
* [IMyShipDrill](Sandbox.ModAPI.Ingame.IMyShipDrill)  
* [IMyShipToolBase](Sandbox.ModAPI.Ingame.IMyShipToolBase)  
* [IMyShipWelder](Sandbox.ModAPI.Ingame.IMyShipWelder)  
* [IMySmallGatlingGun](Sandbox.ModAPI.Ingame.IMySmallGatlingGun)  
* [IMySmallMissileLauncher](Sandbox.ModAPI.Ingame.IMySmallMissileLauncher)  
* [IMyThrust](Sandbox.ModAPI.Ingame.IMyThrust)  
* [IMyUpgradableBlock](Sandbox.ModAPI.Ingame.IMyUpgradableBlock)  
* [IMyUpgradeModule](Sandbox.ModAPI.Ingame.IMyUpgradeModule)  
* [IMyWarhead](Sandbox.ModAPI.Ingame.IMyWarhead)  
* [IMyMotorSuspension](Sandbox.ModAPI.Ingame.IMyMotorSuspension)  
* [IMyTextPanel](Sandbox.ModAPI.Ingame.IMyTextPanel)  
* [IMyParachute](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)  
* [IMyAirVent](SpaceEngineers.Game.ModAPI.Ingame.IMyAirVent)  
* [IMyButtonPanel](SpaceEngineers.Game.ModAPI.Ingame.IMyButtonPanel)  
* [IMyGravityGeneratorBase](SpaceEngineers.Game.ModAPI.Ingame.IMyGravityGeneratorBase)  
* [IMyGravityGenerator](SpaceEngineers.Game.ModAPI.Ingame.IMyGravityGenerator)  
* [IMyGravityGeneratorSphere](SpaceEngineers.Game.ModAPI.Ingame.IMyGravityGeneratorSphere)  
* [IMyLandingGear](SpaceEngineers.Game.ModAPI.Ingame.IMyLandingGear)  
* [IMyOxygenFarm](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)  
* [IMyShipMergeBlock](SpaceEngineers.Game.ModAPI.Ingame.IMyShipMergeBlock)  
* [IMySolarPanel](SpaceEngineers.Game.ModAPI.Ingame.IMySolarPanel)  
* [IMySoundBlock](SpaceEngineers.Game.ModAPI.Ingame.IMySoundBlock)  
* [IMyVirtualMass](SpaceEngineers.Game.ModAPI.Ingame.IMyVirtualMass)  
* [IMySpaceBall](SpaceEngineers.Game.ModAPI.Ingame.IMySpaceBall)  
* [IMyTimerBlock](SpaceEngineers.Game.ModAPI.Ingame.IMyTimerBlock)  
* [IMyLargeConveyorTurretBase](SpaceEngineers.Game.ModAPI.Ingame.IMyLargeConveyorTurretBase)

#### Example

#### Remarks

#### Properties

|Member|Description|
|---|---|
|[BlockDefinition](VRage.Game.ModAPI.Ingame.IMyCubeBlock.BlockDefinition)||
|[CheckConnectionAllowed](VRage.Game.ModAPI.Ingame.IMyCubeBlock.CheckConnectionAllowed)||
|[CubeGrid](VRage.Game.ModAPI.Ingame.IMyCubeBlock.CubeGrid)|Grid in which the block is placed|
|[DefinitionDisplayNameText](VRage.Game.ModAPI.Ingame.IMyCubeBlock.DefinitionDisplayNameText)|Definition name|
|[DisassembleRatio](VRage.Game.ModAPI.Ingame.IMyCubeBlock.DisassembleRatio)|Is set in definition Ratio at which is the block disassembled (grinding)|
|[DisplayNameText](VRage.Game.ModAPI.Ingame.IMyCubeBlock.DisplayNameText)|Translated block name|
|[IsBeingHacked](VRage.Game.ModAPI.Ingame.IMyCubeBlock.IsBeingHacked)|Hacking of the block is in progress|
|[IsFunctional](VRage.Game.ModAPI.Ingame.IMyCubeBlock.IsFunctional)|True if integrity is above breaking threshold|
|[IsWorking](VRage.Game.ModAPI.Ingame.IMyCubeBlock.IsWorking)|True if block is able to do its work depening on block type (is functional, powered, enabled, etc...)|
|[Max](VRage.Game.ModAPI.Ingame.IMyCubeBlock.Max)|Maximum coordinates of grid cells occupied by this block|
|[Mass](VRage.Game.ModAPI.Ingame.IMyCubeBlock.Mass)|Block mass|
|[Min](VRage.Game.ModAPI.Ingame.IMyCubeBlock.Min)|Minimum coordinates of grid cells occupied by this block|
|[NumberInGrid](VRage.Game.ModAPI.Ingame.IMyCubeBlock.NumberInGrid)|Order in which were the blocks of same type added to grid Used in default display name|
|[Orientation](VRage.Game.ModAPI.Ingame.IMyCubeBlock.Orientation)|Returns block orientation in base 6 directions|
|[OwnerId](VRage.Game.ModAPI.Ingame.IMyCubeBlock.OwnerId)|Id of player owning block (not steam Id)|
|[Position](VRage.Game.ModAPI.Ingame.IMyCubeBlock.Position)|Position in grid coordinates|
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

#### Methods

|Member|Description|
|---|---|
|[GetOwnerFactionTag()](VRage.Game.ModAPI.Ingame.IMyCubeBlock.GetOwnerFactionTag)|Tag of faction owning block|
|[GetPlayerRelationToOwner()](VRage.Game.ModAPI.Ingame.IMyCubeBlock.GetPlayerRelationToOwner)|_**Obsolete:** GetPlayerRelationToOwner() is useless ingame. Mods should use the one in ModAPI.IMyCubeBlock_|
|[GetUserRelationToOwner(long)](VRage.Game.ModAPI.Ingame.IMyCubeBlock.GetUserRelationToOwner)||
|[UpdateIsWorking()](VRage.Game.ModAPI.Ingame.IMyCubeBlock.UpdateIsWorking)|_**Obsolete:** _|
|[UpdateVisual()](VRage.Game.ModAPI.Ingame.IMyCubeBlock.UpdateVisual)|_**Obsolete:** _|
|[GetInventory()](VRage.Game.ModAPI.Ingame.IMyEntity.GetInventory)|Simply get the MyInventoryBase component stored in this entity.<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[GetInventory(int)](VRage.Game.ModAPI.Ingame.IMyEntity.GetInventory)|Search for inventory component with maching index.<br /><br />_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|
|[GetPosition()](VRage.Game.ModAPI.Ingame.IMyEntity.GetPosition)|_Inherited from [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)_|

