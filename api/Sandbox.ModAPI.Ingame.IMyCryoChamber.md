← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### IMyCryoChamber Interface

```csharp
public interface IMyCryoChamber: IMyCockpit, IMyShipController, IMyTerminalBlock, IMyCubeBlock, IMyEntity
```

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

**Implements:**  
* [IMyCockpit](Sandbox.ModAPI.Ingame.IMyCockpit)  
* [IMyShipController](Sandbox.ModAPI.Ingame.IMyShipController)  
* [IMyTerminalBlock](Sandbox.ModAPI.Ingame.IMyTerminalBlock)  
* [IMyCubeBlock](VRage.Game.ModAPI.Ingame.IMyCubeBlock)  
* [IMyEntity](VRage.Game.ModAPI.Ingame.IMyEntity)

#### Properties

|Member|Description|
|---|---|
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
|[CanControlShip](Sandbox.ModAPI.Ingame.IMyShipController.CanControlShip)|Determines whether this specific ship controller is capable of controlling the ship it's installed on.<br /><br />_Inherited from [IMyShipController](Sandbox.ModAPI.Ingame.IMyShipController)_|
|[IsUnderControl](Sandbox.ModAPI.Ingame.IMyShipController.IsUnderControl)|Indicates whether a block is locally or remotely controlled.<br /><br />_Inherited from [IMyShipController](Sandbox.ModAPI.Ingame.IMyShipController)_|
|[HasWheels](Sandbox.ModAPI.Ingame.IMyShipController.HasWheels)|Determines whether there are any wheels on this ship.<br /><br />_Inherited from [IMyShipController](Sandbox.ModAPI.Ingame.IMyShipController)_|
|[ControlWheels](Sandbox.ModAPI.Ingame.IMyShipController.ControlWheels)|Gets or sets whether wheels are being controlled by this controller.<br /><br />_Inherited from [IMyShipController](Sandbox.ModAPI.Ingame.IMyShipController)_|
|[ControlThrusters](Sandbox.ModAPI.Ingame.IMyShipController.ControlThrusters)|Gets or sets whether thrusters are being controlled by this controller.<br /><br />_Inherited from [IMyShipController](Sandbox.ModAPI.Ingame.IMyShipController)_|
|[HandBrake](Sandbox.ModAPI.Ingame.IMyShipController.HandBrake)|Gets or sets the current state of the handbrake.<br /><br />_Inherited from [IMyShipController](Sandbox.ModAPI.Ingame.IMyShipController)_|
|[DampenersOverride](Sandbox.ModAPI.Ingame.IMyShipController.DampenersOverride)|Gets or sets whether dampeners are currently enabled.<br /><br />_Inherited from [IMyShipController](Sandbox.ModAPI.Ingame.IMyShipController)_|
|[ShowHorizonIndicator](Sandbox.ModAPI.Ingame.IMyShipController.ShowHorizonIndicator)|Gets or sets whether the horizon indicator should be displayed for this block.<br /><br />_Inherited from [IMyShipController](Sandbox.ModAPI.Ingame.IMyShipController)_|
|[MoveIndicator](Sandbox.ModAPI.Ingame.IMyShipController.MoveIndicator)|Directional input from user/autopilot. Values can be very large with high controller sensitivity<br /><br />_Inherited from [IMyShipController](Sandbox.ModAPI.Ingame.IMyShipController)_|
|[RotationIndicator](Sandbox.ModAPI.Ingame.IMyShipController.RotationIndicator)|Pitch, yaw input from user/autopilot. Values can be very large with high controller sensitivity<br /><br />_Inherited from [IMyShipController](Sandbox.ModAPI.Ingame.IMyShipController)_|
|[RollIndicator](Sandbox.ModAPI.Ingame.IMyShipController.RollIndicator)|Roll input from user/autopilot. Values can be very large with high controller sensitivity<br /><br />_Inherited from [IMyShipController](Sandbox.ModAPI.Ingame.IMyShipController)_|
|[CenterOfMass](Sandbox.ModAPI.Ingame.IMyShipController.CenterOfMass)|Center of mass in world coordinates<br /><br />_Inherited from [IMyShipController](Sandbox.ModAPI.Ingame.IMyShipController)_|
|[IsMainCockpit](Sandbox.ModAPI.Ingame.IMyShipController.IsMainCockpit)|Gets or sets if this controller is the main one.<br /><br />_Inherited from [IMyShipController](Sandbox.ModAPI.Ingame.IMyShipController)_|
|[IsMainCockpit](Sandbox.ModAPI.Ingame.IMyCockpit.IsMainCockpit)|Determines whether this controller is the main cockpit of the shit this doesn't belong here.<br /><br />_Inherited from [IMyCockpit](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[OxygenCapacity](Sandbox.ModAPI.Ingame.IMyCockpit.OxygenCapacity)|Gets the maximum oxygen capacity of this cockpit.<br /><br />_Inherited from [IMyCockpit](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[OxygenFilledRatio](Sandbox.ModAPI.Ingame.IMyCockpit.OxygenFilledRatio)|Gets the current oxygen level of this cockpit, as a value between 0 (empty) and 1 (full).<br /><br />_Inherited from [IMyCockpit](Sandbox.ModAPI.Ingame.IMyCockpit)_|

#### Methods

|Member|Description|
|---|---|
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
|[GetNaturalGravity()](Sandbox.ModAPI.Ingame.IMyShipController.GetNaturalGravity)|Gets the detected natural gravity vector and power at the current location.<br /><br />_Inherited from [IMyShipController](Sandbox.ModAPI.Ingame.IMyShipController)_|
|[GetArtificialGravity()](Sandbox.ModAPI.Ingame.IMyShipController.GetArtificialGravity)|Gets the detected artificial gravity vector and power at the current location.<br /><br />_Inherited from [IMyShipController](Sandbox.ModAPI.Ingame.IMyShipController)_|
|[GetTotalGravity()](Sandbox.ModAPI.Ingame.IMyShipController.GetTotalGravity)|Gets the total accumulated gravity vector and power at the current location, taking both natural and artificial gravity into account.<br /><br />_Inherited from [IMyShipController](Sandbox.ModAPI.Ingame.IMyShipController)_|
|[GetShipSpeed()](Sandbox.ModAPI.Ingame.IMyShipController.GetShipSpeed)|Gets the basic ship speed in meters per second, for when you just need to know how fast you're going.<br /><br />_Inherited from [IMyShipController](Sandbox.ModAPI.Ingame.IMyShipController)_|
|[GetShipVelocities()](Sandbox.ModAPI.Ingame.IMyShipController.GetShipVelocities)|Determines the linear velocities in meters per second and angular velocities in radians per second. Provides a more accurate representation of the directions and axis speeds.<br /><br />_Inherited from [IMyShipController](Sandbox.ModAPI.Ingame.IMyShipController)_|
|[CalculateShipMass()](Sandbox.ModAPI.Ingame.IMyShipController.CalculateShipMass)|Gets information about the current mass of the ship.<br /><br />_Inherited from [IMyShipController](Sandbox.ModAPI.Ingame.IMyShipController)_|
|[TryGetPlanetPosition(out Vector3D)](Sandbox.ModAPI.Ingame.IMyShipController.TryGetPlanetPosition)|Attempts to get the world position of the nearest planet. This method is only available when a ship is within the gravity well of a planet.<br /><br />_Inherited from [IMyShipController](Sandbox.ModAPI.Ingame.IMyShipController)_|
|[TryGetPlanetElevation(MyPlanetElevation, out double)](Sandbox.ModAPI.Ingame.IMyShipController.TryGetPlanetElevation)|Attempts to get the elevation of the ship in relation to the nearest planet. This method is only available when a ship is within the gravity well of a planet.<br /><br />_Inherited from [IMyShipController](Sandbox.ModAPI.Ingame.IMyShipController)_|
