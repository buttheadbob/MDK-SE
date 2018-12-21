← [Index](index)
# IMyParachute Interface
**Namespace:** [`SpaceEngineers.Game.ModAPI.Ingame`](SpaceEngineers.Game.ModAPI.Ingame)  
**Assembly:** SpaceEngineers.Game.dll  
**Implements:**
* [`Sandbox.ModAPI.Ingame.IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyFunctionalBlock)
* [`Sandbox.ModAPI.Ingame.IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTerminalBlock)
* [`VRage.Game.ModAPI.Ingame.IMyCubeBlock`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)
* [`VRage.Game.ModAPI.Ingame.IMyEntity`](VRage.Game.ModAPI.Ingame.IMyEntity)
### Properties
|Member|Description|
|---|---|
|[`float&nbsp;Atmosphere`](SpaceEngineers.Game.ModAPI.Ingame.Atmosphere)|Atmospheric Density at the block. Returns 0.0f if not near a planet.|
|[`DoorStatus&nbsp;Status`](SpaceEngineers.Game.ModAPI.Ingame.Status)|Determines the current general status of the door.|
|[`float&nbsp;OpenRatio`](SpaceEngineers.Game.ModAPI.Ingame.OpenRatio)|The current, accurate ratio of the door's current state where 0 is fully closed and 1 is fully open.|
|[`MyEntityComponentContainer&nbsp;Components`](VRage.Game.ModAPI.Ingame.Components)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`long&nbsp;EntityId`](VRage.Game.ModAPI.Ingame.EntityId)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`string&nbsp;Name`](VRage.Game.ModAPI.Ingame.Name)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`string&nbsp;DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`bool&nbsp;HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)|Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.<br/><br/>_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`int&nbsp;InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)|Returns the count of the number of inventories this entity has.<br/><br/>_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`BoundingBoxD&nbsp;WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`BoundingBoxD&nbsp;WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`MatrixD&nbsp;WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`BoundingSphereD&nbsp;WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`BoundingSphereD&nbsp;WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`SerializableDefinitionId&nbsp;BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`bool&nbsp;CheckConnectionAllowed`](VRage.Game.ModAPI.Ingame.CheckConnectionAllowed)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`IMyCubeGrid&nbsp;CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid)|Grid in which the block is placed<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`string&nbsp;DefinitionDisplayNameText`](VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText)|Definition name<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`float&nbsp;DisassembleRatio`](VRage.Game.ModAPI.Ingame.DisassembleRatio)|Is set in definition Ratio at which is the block disassembled (grinding)<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`string&nbsp;DisplayNameText`](VRage.Game.ModAPI.Ingame.DisplayNameText)|Translated block name<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`bool&nbsp;IsBeingHacked`](VRage.Game.ModAPI.Ingame.IsBeingHacked)|Hacking of the block is in progress<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`bool&nbsp;IsFunctional`](VRage.Game.ModAPI.Ingame.IsFunctional)|True if integrity is above breaking threshold<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`bool&nbsp;IsWorking`](VRage.Game.ModAPI.Ingame.IsWorking)|True if block is able to do its work depening on block type (is functional, powered, enabled, etc...)<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`Vector3I&nbsp;Max`](VRage.Game.ModAPI.Ingame.Max)|Maximum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`float&nbsp;Mass`](VRage.Game.ModAPI.Ingame.Mass)|Block mass<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`Vector3I&nbsp;Min`](VRage.Game.ModAPI.Ingame.Min)|Minimum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`int&nbsp;NumberInGrid`](VRage.Game.ModAPI.Ingame.NumberInGrid)|Order in which were the blocks of same type added to grid Used in default display name<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`MyBlockOrientation&nbsp;Orientation`](VRage.Game.ModAPI.Ingame.Orientation)|Returns block orientation in base 6 directions<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`long&nbsp;OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId)|Id of player owning block (not steam Id)<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`Vector3I&nbsp;Position`](VRage.Game.ModAPI.Ingame.Position)|Position in grid coordinates<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`string&nbsp;CustomName`](Sandbox.ModAPI.Ingame.CustomName)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`string&nbsp;CustomNameWithFaction`](Sandbox.ModAPI.Ingame.CustomNameWithFaction)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`string&nbsp;DetailedInfo`](Sandbox.ModAPI.Ingame.DetailedInfo)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`string&nbsp;CustomInfo`](Sandbox.ModAPI.Ingame.CustomInfo)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`string&nbsp;CustomData`](Sandbox.ModAPI.Ingame.CustomData)|Gets or sets the Custom Data string. NOTE: Only use this for user input. For storing large mod configs, create your own MyModStorageComponent<br/><br/>_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`bool&nbsp;ShowOnHUD`](Sandbox.ModAPI.Ingame.ShowOnHUD)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`bool&nbsp;ShowInTerminal`](Sandbox.ModAPI.Ingame.ShowInTerminal)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`bool&nbsp;ShowInToolbarConfig`](Sandbox.ModAPI.Ingame.ShowInToolbarConfig)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`bool&nbsp;ShowInInventory`](Sandbox.ModAPI.Ingame.ShowInInventory)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`bool&nbsp;Enabled`](Sandbox.ModAPI.Ingame.Enabled)|_Inherited from [`IMyFunctionalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
### Methods
|Member|Description|
|---|---|
|[`bool&nbsp;TryGetClosestPoint(ref&nbsp;Nullable<Vector3D>&nbsp;closestPoint)`](SpaceEngineers.Game.ModAPI.Ingame.TryGetClosestPoint)|Gets Elevation, elevation will equal positive infinity if method returns false|
|[`Vector3D&nbsp;GetVelocity()`](SpaceEngineers.Game.ModAPI.Ingame.GetVelocity)|Determines the linear velocities in meters per second at the block position|
|[`Vector3D&nbsp;GetNaturalGravity()`](SpaceEngineers.Game.ModAPI.Ingame.GetNaturalGravity)|Gets the detected natural gravity vector and power at the current location.|
|[`Vector3D&nbsp;GetArtificialGravity()`](SpaceEngineers.Game.ModAPI.Ingame.GetArtificialGravity)|Gets the detected artificial gravity vector and power at the current location.|
|[`Vector3D&nbsp;GetTotalGravity()`](SpaceEngineers.Game.ModAPI.Ingame.GetTotalGravity)|Gets the total accumulated gravity vector and power at the current location, taking both natural and artificial gravity into account.|
|[`void&nbsp;OpenDoor()`](SpaceEngineers.Game.ModAPI.Ingame.OpenDoor)|Opens the door. See [DoorStatus Status](SpaceEngineers.Game.ModAPI.Ingame.Status) to get the current status.|
|[`void&nbsp;CloseDoor()`](SpaceEngineers.Game.ModAPI.Ingame.CloseDoor)|Closes the door. See [DoorStatus Status](SpaceEngineers.Game.ModAPI.Ingame.Status) to get the current status.|
|[`void&nbsp;ToggleDoor()`](SpaceEngineers.Game.ModAPI.Ingame.ToggleDoor)|Toggles the open state of this door. See [DoorStatus Status](SpaceEngineers.Game.ModAPI.Ingame.Status) to get the current status.|
|[`IMyInventory&nbsp;GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)|Simply get the MyInventoryBase component stored in this entity.<br/><br/>_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`IMyInventory&nbsp;GetInventory(int&nbsp;index)`](VRage.Game.ModAPI.Ingame.GetInventory)|Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`Vector3D&nbsp;GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`string&nbsp;GetOwnerFactionTag()`](VRage.Game.ModAPI.Ingame.GetOwnerFactionTag)|Tag of faction owning block<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`MyRelationsBetweenPlayerAndBlock&nbsp;GetPlayerRelationToOwner()`](VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`MyRelationsBetweenPlayerAndBlock&nbsp;GetUserRelationToOwner(long&nbsp;playerId)`](VRage.Game.ModAPI.Ingame.GetUserRelationToOwner)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`void&nbsp;UpdateIsWorking()`](VRage.Game.ModAPI.Ingame.UpdateIsWorking)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`void&nbsp;UpdateVisual()`](VRage.Game.ModAPI.Ingame.UpdateVisual)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`bool&nbsp;HasLocalPlayerAccess()`](Sandbox.ModAPI.Ingame.HasLocalPlayerAccess)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`bool&nbsp;HasPlayerAccess(long&nbsp;playerId)`](Sandbox.ModAPI.Ingame.HasPlayerAccess)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`void&nbsp;SetCustomName(string&nbsp;text)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`void&nbsp;SetCustomName(StringBuilder&nbsp;text)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`void&nbsp;GetActions(List<ITerminalAction>&nbsp;resultList,&nbsp;Func<ITerminalAction,&nbsp;bool>&nbsp;collect)`](Sandbox.ModAPI.Ingame.GetActions)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`void&nbsp;SearchActionsOfName(string&nbsp;name,&nbsp;List<ITerminalAction>&nbsp;resultList,&nbsp;Func<ITerminalAction,&nbsp;bool>&nbsp;collect)`](Sandbox.ModAPI.Ingame.SearchActionsOfName)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`ITerminalAction&nbsp;GetActionWithName(string&nbsp;name)`](Sandbox.ModAPI.Ingame.GetActionWithName)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`ITerminalProperty&nbsp;GetProperty(string&nbsp;id)`](Sandbox.ModAPI.Ingame.GetProperty)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`void&nbsp;GetProperties(List<ITerminalProperty>&nbsp;resultList,&nbsp;Func<ITerminalProperty,&nbsp;bool>&nbsp;collect)`](Sandbox.ModAPI.Ingame.GetProperties)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`bool&nbsp;IsSameConstructAs(IMyTerminalBlock&nbsp;other)`](Sandbox.ModAPI.Ingame.IsSameConstructAs)|Determines whether this block is mechanically connected to the other. This is any block connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.<br/><br/>_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
|[`void&nbsp;RequestEnable(bool&nbsp;enable)`](Sandbox.ModAPI.Ingame.RequestEnable)|_Inherited from [`IMyFunctionalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyParachute)_|
