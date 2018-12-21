← [Index](index)
# IMyRemoteControl Interface
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
|[`bool&nbsp;IsAutoPilotEnabled`](Sandbox.ModAPI.Ingame.IsAutoPilotEnabled)|Determines whether the autopilot is currently enabled.|
|[`float&nbsp;SpeedLimit`](Sandbox.ModAPI.Ingame.SpeedLimit)|Gets or sets the autopilot speed limit|
|[`FlightMode&nbsp;FlightMode`](Sandbox.ModAPI.Ingame.FlightMode)|Gets or sets the current flight mode|
|[`Direction&nbsp;Direction`](Sandbox.ModAPI.Ingame.Direction)|Gets or sets the current flight direction|
|[`MyWaypointInfo&nbsp;CurrentWaypoint`](Sandbox.ModAPI.Ingame.CurrentWaypoint)|Gets the current target waypoint|
|[`MyEntityComponentContainer&nbsp;Components`](VRage.Game.ModAPI.Ingame.Components)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`long&nbsp;EntityId`](VRage.Game.ModAPI.Ingame.EntityId)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`string&nbsp;Name`](VRage.Game.ModAPI.Ingame.Name)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`string&nbsp;DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`bool&nbsp;HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)|Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`int&nbsp;InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)|Returns the count of the number of inventories this entity has.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`BoundingBoxD&nbsp;WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`BoundingBoxD&nbsp;WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`MatrixD&nbsp;WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`BoundingSphereD&nbsp;WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`BoundingSphereD&nbsp;WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`SerializableDefinitionId&nbsp;BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`bool&nbsp;CheckConnectionAllowed`](VRage.Game.ModAPI.Ingame.CheckConnectionAllowed)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`IMyCubeGrid&nbsp;CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid)|Grid in which the block is placed<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`string&nbsp;DefinitionDisplayNameText`](VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText)|Definition name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`float&nbsp;DisassembleRatio`](VRage.Game.ModAPI.Ingame.DisassembleRatio)|Is set in definition Ratio at which is the block disassembled (grinding)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`string&nbsp;DisplayNameText`](VRage.Game.ModAPI.Ingame.DisplayNameText)|Translated block name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`bool&nbsp;IsBeingHacked`](VRage.Game.ModAPI.Ingame.IsBeingHacked)|Hacking of the block is in progress<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`bool&nbsp;IsFunctional`](VRage.Game.ModAPI.Ingame.IsFunctional)|True if integrity is above breaking threshold<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`bool&nbsp;IsWorking`](VRage.Game.ModAPI.Ingame.IsWorking)|True if block is able to do its work depening on block type (is functional, powered, enabled, etc...)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`Vector3I&nbsp;Max`](VRage.Game.ModAPI.Ingame.Max)|Maximum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`float&nbsp;Mass`](VRage.Game.ModAPI.Ingame.Mass)|Block mass<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`Vector3I&nbsp;Min`](VRage.Game.ModAPI.Ingame.Min)|Minimum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`int&nbsp;NumberInGrid`](VRage.Game.ModAPI.Ingame.NumberInGrid)|Order in which were the blocks of same type added to grid Used in default display name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`MyBlockOrientation&nbsp;Orientation`](VRage.Game.ModAPI.Ingame.Orientation)|Returns block orientation in base 6 directions<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`long&nbsp;OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId)|Id of player owning block (not steam Id)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`Vector3I&nbsp;Position`](VRage.Game.ModAPI.Ingame.Position)|Position in grid coordinates<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`string&nbsp;CustomName`](Sandbox.ModAPI.Ingame.CustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`string&nbsp;CustomNameWithFaction`](Sandbox.ModAPI.Ingame.CustomNameWithFaction)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`string&nbsp;DetailedInfo`](Sandbox.ModAPI.Ingame.DetailedInfo)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`string&nbsp;CustomInfo`](Sandbox.ModAPI.Ingame.CustomInfo)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`string&nbsp;CustomData`](Sandbox.ModAPI.Ingame.CustomData)|Gets or sets the Custom Data string. NOTE: Only use this for user input. For storing large mod configs, create your own MyModStorageComponent<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`bool&nbsp;ShowOnHUD`](Sandbox.ModAPI.Ingame.ShowOnHUD)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`bool&nbsp;ShowInTerminal`](Sandbox.ModAPI.Ingame.ShowInTerminal)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`bool&nbsp;ShowInToolbarConfig`](Sandbox.ModAPI.Ingame.ShowInToolbarConfig)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`bool&nbsp;ShowInInventory`](Sandbox.ModAPI.Ingame.ShowInInventory)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`bool&nbsp;CanControlShip`](Sandbox.ModAPI.Ingame.CanControlShip)|Determines whether this specific ship controller is capable of controlling the ship it's installed on.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`bool&nbsp;IsUnderControl`](Sandbox.ModAPI.Ingame.IsUnderControl)|Indicates whether a block is locally or remotely controlled.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`bool&nbsp;HasWheels`](Sandbox.ModAPI.Ingame.HasWheels)|Determines whether there are any wheels on this ship.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`bool&nbsp;ControlWheels`](Sandbox.ModAPI.Ingame.ControlWheels)|Gets or sets whether wheels are being controlled by this controller.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`bool&nbsp;ControlThrusters`](Sandbox.ModAPI.Ingame.ControlThrusters)|Gets or sets whether thrusters are being controlled by this controller.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`bool&nbsp;HandBrake`](Sandbox.ModAPI.Ingame.HandBrake)|Gets or sets the current state of the handbrake.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`bool&nbsp;DampenersOverride`](Sandbox.ModAPI.Ingame.DampenersOverride)|Gets or sets whether dampeners are currently enabled.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`bool&nbsp;ShowHorizonIndicator`](Sandbox.ModAPI.Ingame.ShowHorizonIndicator)|Gets or sets whether the horizon indicator should be displayed for this block.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`Vector3&nbsp;MoveIndicator`](Sandbox.ModAPI.Ingame.MoveIndicator)|Directional input from user/autopilot. Values can be very large with high controller sensitivity<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`Vector2&nbsp;RotationIndicator`](Sandbox.ModAPI.Ingame.RotationIndicator)|Pitch, yaw input from user/autopilot. Values can be very large with high controller sensitivity<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`float&nbsp;RollIndicator`](Sandbox.ModAPI.Ingame.RollIndicator)|Roll input from user/autopilot. Values can be very large with high controller sensitivity<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`Vector3D&nbsp;CenterOfMass`](Sandbox.ModAPI.Ingame.CenterOfMass)|Center of mass in world coordinates<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`bool&nbsp;IsMainCockpit`](Sandbox.ModAPI.Ingame.IsMainCockpit)|Gets or sets if this controller is the main one.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
### Methods
|Member|Description|
|---|---|
|[`bool&nbsp;GetNearestPlayer(ref&nbsp;Vector3D&nbsp;playerPosition)`](Sandbox.ModAPI.Ingame.GetNearestPlayer)|Gets the nearest player's position. Will only work if the remote control belongs to an NPC|
|[`void&nbsp;ClearWaypoints()`](Sandbox.ModAPI.Ingame.ClearWaypoints)|Removes all existing waypoints.|
|[`void&nbsp;GetWaypointInfo(List<MyWaypointInfo>&nbsp;waypoints)`](Sandbox.ModAPI.Ingame.GetWaypointInfo)|Gets basic information about the currently configured waypoints.|
|[`void&nbsp;AddWaypoint(Vector3D&nbsp;coords,&nbsp;string&nbsp;name)`](Sandbox.ModAPI.Ingame.AddWaypoint)|Adds a new waypoint.|
|[`void&nbsp;AddWaypoint(MyWaypointInfo&nbsp;coords)`](Sandbox.ModAPI.Ingame.AddWaypoint)|Adds a new waypoint.|
|[`void&nbsp;SetAutoPilotEnabled(bool&nbsp;enabled)`](Sandbox.ModAPI.Ingame.SetAutoPilotEnabled)|Enables or disables the autopilot.|
|[`void&nbsp;SetCollisionAvoidance(bool&nbsp;enabled)`](Sandbox.ModAPI.Ingame.SetCollisionAvoidance)|Enables or disables collision avoidance.|
|[`void&nbsp;SetDockingMode(bool&nbsp;enabled)`](Sandbox.ModAPI.Ingame.SetDockingMode)|Enables or disables docking mode.|
|[`IMyInventory&nbsp;GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)|Simply get the MyInventoryBase component stored in this entity.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`IMyInventory&nbsp;GetInventory(int&nbsp;index)`](VRage.Game.ModAPI.Ingame.GetInventory)|Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`Vector3D&nbsp;GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`string&nbsp;GetOwnerFactionTag()`](VRage.Game.ModAPI.Ingame.GetOwnerFactionTag)|Tag of faction owning block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`MyRelationsBetweenPlayerAndBlock&nbsp;GetPlayerRelationToOwner()`](VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`MyRelationsBetweenPlayerAndBlock&nbsp;GetUserRelationToOwner(long&nbsp;playerId)`](VRage.Game.ModAPI.Ingame.GetUserRelationToOwner)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`void&nbsp;UpdateIsWorking()`](VRage.Game.ModAPI.Ingame.UpdateIsWorking)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`void&nbsp;UpdateVisual()`](VRage.Game.ModAPI.Ingame.UpdateVisual)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`bool&nbsp;HasLocalPlayerAccess()`](Sandbox.ModAPI.Ingame.HasLocalPlayerAccess)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`bool&nbsp;HasPlayerAccess(long&nbsp;playerId)`](Sandbox.ModAPI.Ingame.HasPlayerAccess)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`void&nbsp;SetCustomName(string&nbsp;text)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`void&nbsp;SetCustomName(StringBuilder&nbsp;text)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`void&nbsp;GetActions(List<ITerminalAction>&nbsp;resultList,&nbsp;Func<ITerminalAction,&nbsp;bool>&nbsp;collect)`](Sandbox.ModAPI.Ingame.GetActions)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`void&nbsp;SearchActionsOfName(string&nbsp;name,&nbsp;List<ITerminalAction>&nbsp;resultList,&nbsp;Func<ITerminalAction,&nbsp;bool>&nbsp;collect)`](Sandbox.ModAPI.Ingame.SearchActionsOfName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`ITerminalAction&nbsp;GetActionWithName(string&nbsp;name)`](Sandbox.ModAPI.Ingame.GetActionWithName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`ITerminalProperty&nbsp;GetProperty(string&nbsp;id)`](Sandbox.ModAPI.Ingame.GetProperty)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`void&nbsp;GetProperties(List<ITerminalProperty>&nbsp;resultList,&nbsp;Func<ITerminalProperty,&nbsp;bool>&nbsp;collect)`](Sandbox.ModAPI.Ingame.GetProperties)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`bool&nbsp;IsSameConstructAs(IMyTerminalBlock&nbsp;other)`](Sandbox.ModAPI.Ingame.IsSameConstructAs)|Determines whether this block is mechanically connected to the other. This is any block connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`Vector3D&nbsp;GetNaturalGravity()`](Sandbox.ModAPI.Ingame.GetNaturalGravity)|Gets the detected natural gravity vector and power at the current location.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`Vector3D&nbsp;GetArtificialGravity()`](Sandbox.ModAPI.Ingame.GetArtificialGravity)|Gets the detected artificial gravity vector and power at the current location.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`Vector3D&nbsp;GetTotalGravity()`](Sandbox.ModAPI.Ingame.GetTotalGravity)|Gets the total accumulated gravity vector and power at the current location, taking both natural and artificial gravity into account.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`double&nbsp;GetShipSpeed()`](Sandbox.ModAPI.Ingame.GetShipSpeed)|Gets the basic ship speed in meters per second, for when you just need to know how fast you're going.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`MyShipVelocities&nbsp;GetShipVelocities()`](Sandbox.ModAPI.Ingame.GetShipVelocities)|Determines the linear velocities in meters per second and angular velocities in radians per second. Provides a more accurate representation of the directions and axis speeds.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`MyShipMass&nbsp;CalculateShipMass()`](Sandbox.ModAPI.Ingame.CalculateShipMass)|Gets information about the current mass of the ship.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`bool&nbsp;TryGetPlanetPosition(ref&nbsp;Vector3D&nbsp;position)`](Sandbox.ModAPI.Ingame.TryGetPlanetPosition)|Attempts to get the world position of the nearest planet. This method is only available when a ship is within the gravity well of a planet.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
|[`bool&nbsp;TryGetPlanetElevation(MyPlanetElevation&nbsp;detail,&nbsp;ref&nbsp;double&nbsp;elevation)`](Sandbox.ModAPI.Ingame.TryGetPlanetElevation)|Attempts to get the elevation of the ship in relation to the nearest planet. This method is only available when a ship is within the gravity well of a planet.<br/><br/>_Inherited from [`IMyShipController`](Sandbox.ModAPI.Ingame.IMyRemoteControl)_|
