← [Index](index)
# IMyCockpit Interface
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
**Implements:**
* [`Sandbox.ModAPI.Ingame.IMyShipController`](Sandbox.ModAPI.Ingame.IMyShipController)
* [`Sandbox.ModAPI.Ingame.IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTerminalBlock)
* [`VRage.Game.ModAPI.Ingame.IMyCubeBlock`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)
* [`VRage.Game.ModAPI.Ingame.IMyEntity`](VRage.Game.ModAPI.Ingame.IMyEntity)
### Properties
|Member|Description|
|---|---|
|[`bool IsMainCockpit`](Sandbox.ModAPI.Ingame.IsMainCockpit)|Determines whether this controller is the main cockpit of the shit this doesn't belong here.|
|[`float OxygenCapacity`](Sandbox.ModAPI.Ingame.OxygenCapacity)|Gets the maximum oxygen capacity of this cockpit.|
|[`float OxygenFilledRatio`](Sandbox.ModAPI.Ingame.OxygenFilledRatio)|Gets the current oxygen level of this cockpit, as a value between 0 (empty) and 1 (full).|
|[`MyEntityComponentContainer Components`](VRage.Game.ModAPI.Ingame.Components)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`long EntityId`](VRage.Game.ModAPI.Ingame.EntityId)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`string Name`](VRage.Game.ModAPI.Ingame.Name)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`string DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)|Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`int InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)|Returns the count of the number of inventories this entity has.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`BoundingBoxD WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`BoundingBoxD WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`MatrixD WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`BoundingSphereD WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`BoundingSphereD WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`SerializableDefinitionId BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool CheckConnectionAllowed`](VRage.Game.ModAPI.Ingame.CheckConnectionAllowed)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`IMyCubeGrid CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid)|Grid in which the block is placed<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`string DefinitionDisplayNameText`](VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText)|Definition name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`float DisassembleRatio`](VRage.Game.ModAPI.Ingame.DisassembleRatio)|Is set in definition Ratio at which is the block disassembled (grinding)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`string DisplayNameText`](VRage.Game.ModAPI.Ingame.DisplayNameText)|Translated block name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool IsBeingHacked`](VRage.Game.ModAPI.Ingame.IsBeingHacked)|Hacking of the block is in progress<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool IsFunctional`](VRage.Game.ModAPI.Ingame.IsFunctional)|True if integrity is above breaking threshold<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool IsWorking`](VRage.Game.ModAPI.Ingame.IsWorking)|True if block is able to do its work depening on block type (is functional, powered, enabled, etc...)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`Vector3I Max`](VRage.Game.ModAPI.Ingame.Max)|Maximum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`float Mass`](VRage.Game.ModAPI.Ingame.Mass)|Block mass<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`Vector3I Min`](VRage.Game.ModAPI.Ingame.Min)|Minimum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`int NumberInGrid`](VRage.Game.ModAPI.Ingame.NumberInGrid)|Order in which were the blocks of same type added to grid Used in default display name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`MyBlockOrientation Orientation`](VRage.Game.ModAPI.Ingame.Orientation)|Returns block orientation in base 6 directions<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`long OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId)|Id of player owning block (not steam Id)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`Vector3I Position`](VRage.Game.ModAPI.Ingame.Position)|Position in grid coordinates<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`string CustomName`](Sandbox.ModAPI.Ingame.CustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`string CustomNameWithFaction`](Sandbox.ModAPI.Ingame.CustomNameWithFaction)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`string DetailedInfo`](Sandbox.ModAPI.Ingame.DetailedInfo)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`string CustomInfo`](Sandbox.ModAPI.Ingame.CustomInfo)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`string CustomData`](Sandbox.ModAPI.Ingame.CustomData)|Gets or sets the Custom Data string. NOTE: Only use this for user input. For storing large mod configs, create your own MyModStorageComponent<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool ShowOnHUD`](Sandbox.ModAPI.Ingame.ShowOnHUD)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool ShowInTerminal`](Sandbox.ModAPI.Ingame.ShowInTerminal)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool ShowInToolbarConfig`](Sandbox.ModAPI.Ingame.ShowInToolbarConfig)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool ShowInInventory`](Sandbox.ModAPI.Ingame.ShowInInventory)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool CanControlShip`](Sandbox.ModAPI.Ingame.CanControlShip)|Determines whether this specific ship controller is capable of controlling the ship it's installed on.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool IsUnderControl`](Sandbox.ModAPI.Ingame.IsUnderControl)|Indicates whether a block is locally or remotely controlled.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool HasWheels`](Sandbox.ModAPI.Ingame.HasWheels)|Determines whether there are any wheels on this ship.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool ControlWheels`](Sandbox.ModAPI.Ingame.ControlWheels)|Gets or sets whether wheels are being controlled by this controller.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool ControlThrusters`](Sandbox.ModAPI.Ingame.ControlThrusters)|Gets or sets whether thrusters are being controlled by this controller.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool HandBrake`](Sandbox.ModAPI.Ingame.HandBrake)|Gets or sets the current state of the handbrake.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool DampenersOverride`](Sandbox.ModAPI.Ingame.DampenersOverride)|Gets or sets whether dampeners are currently enabled.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool ShowHorizonIndicator`](Sandbox.ModAPI.Ingame.ShowHorizonIndicator)|Gets or sets whether the horizon indicator should be displayed for this block.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`Vector3 MoveIndicator`](Sandbox.ModAPI.Ingame.MoveIndicator)|Directional input from user/autopilot. Values can be very large with high controller sensitivity<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`Vector2 RotationIndicator`](Sandbox.ModAPI.Ingame.RotationIndicator)|Pitch, yaw input from user/autopilot. Values can be very large with high controller sensitivity<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`float RollIndicator`](Sandbox.ModAPI.Ingame.RollIndicator)|Roll input from user/autopilot. Values can be very large with high controller sensitivity<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`Vector3D CenterOfMass`](Sandbox.ModAPI.Ingame.CenterOfMass)|Center of mass in world coordinates<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool IsMainCockpit`](Sandbox.ModAPI.Ingame.IsMainCockpit)|Gets or sets if this controller is the main one.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
### Methods
|Member|Description|
|---|---|
|[`IMyInventory GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)|Simply get the MyInventoryBase component stored in this entity.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`IMyInventory GetInventory(int index)`](VRage.Game.ModAPI.Ingame.GetInventory)|Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`Vector3D GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`string GetOwnerFactionTag()`](VRage.Game.ModAPI.Ingame.GetOwnerFactionTag)|Tag of faction owning block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`MyRelationsBetweenPlayerAndBlock GetPlayerRelationToOwner()`](VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`MyRelationsBetweenPlayerAndBlock GetUserRelationToOwner(long playerId)`](VRage.Game.ModAPI.Ingame.GetUserRelationToOwner)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`void UpdateIsWorking()`](VRage.Game.ModAPI.Ingame.UpdateIsWorking)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`void UpdateVisual()`](VRage.Game.ModAPI.Ingame.UpdateVisual)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool HasLocalPlayerAccess()`](Sandbox.ModAPI.Ingame.HasLocalPlayerAccess)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool HasPlayerAccess(long playerId)`](Sandbox.ModAPI.Ingame.HasPlayerAccess)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`void SetCustomName(string text)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`void SetCustomName(StringBuilder text)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`void GetActions(List<ITerminalAction> resultList, Func<ITerminalAction, bool> collect)`](Sandbox.ModAPI.Ingame.GetActions)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`void SearchActionsOfName(string name, List<ITerminalAction> resultList, Func<ITerminalAction, bool> collect)`](Sandbox.ModAPI.Ingame.SearchActionsOfName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`ITerminalAction GetActionWithName(string name)`](Sandbox.ModAPI.Ingame.GetActionWithName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`ITerminalProperty GetProperty(string id)`](Sandbox.ModAPI.Ingame.GetProperty)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`void GetProperties(List<ITerminalProperty> resultList, Func<ITerminalProperty, bool> collect)`](Sandbox.ModAPI.Ingame.GetProperties)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool IsSameConstructAs(IMyTerminalBlock other)`](Sandbox.ModAPI.Ingame.IsSameConstructAs)|Determines whether this block is mechanically connected to the other. This is any block connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`Vector3D GetNaturalGravity()`](Sandbox.ModAPI.Ingame.GetNaturalGravity)|Gets the detected natural gravity vector and power at the current location.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`Vector3D GetArtificialGravity()`](Sandbox.ModAPI.Ingame.GetArtificialGravity)|Gets the detected artificial gravity vector and power at the current location.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`Vector3D GetTotalGravity()`](Sandbox.ModAPI.Ingame.GetTotalGravity)|Gets the total accumulated gravity vector and power at the current location, taking both natural and artificial gravity into account.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`double GetShipSpeed()`](Sandbox.ModAPI.Ingame.GetShipSpeed)|Gets the basic ship speed in meters per second, for when you just need to know how fast you're going.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`MyShipVelocities GetShipVelocities()`](Sandbox.ModAPI.Ingame.GetShipVelocities)|Determines the linear velocities in meters per second and angular velocities in radians per second. Provides a more accurate representation of the directions and axis speeds.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`MyShipMass CalculateShipMass()`](Sandbox.ModAPI.Ingame.CalculateShipMass)|Gets information about the current mass of the ship.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool TryGetPlanetPosition(ref Vector3D position)`](Sandbox.ModAPI.Ingame.TryGetPlanetPosition)|Attempts to get the world position of the nearest planet. This method is only available when a ship is within the gravity well of a planet.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
|[`bool TryGetPlanetElevation(MyPlanetElevation detail, ref double elevation)`](Sandbox.ModAPI.Ingame.TryGetPlanetElevation)|Attempts to get the elevation of the ship in relation to the nearest planet. This method is only available when a ship is within the gravity well of a planet.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyCockpit)_|
