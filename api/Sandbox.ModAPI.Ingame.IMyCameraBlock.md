← [Index](index)
# IMyCameraBlock Interface
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
**Implements:**
* [`Sandbox.ModAPI.Ingame.IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyFunctionalBlock)
* [`Sandbox.ModAPI.Ingame.IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTerminalBlock)
* [`VRage.Game.ModAPI.Ingame.IMyCubeBlock`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)
* [`VRage.Game.ModAPI.Ingame.IMyEntity`](VRage.Game.ModAPI.Ingame.IMyEntity)

### Properties
|Member|Description|
|---|---|
|[`IsActive`](Sandbox.ModAPI.Ingame.IsActive)|Determines whether this camera is currently in use.|
|[`AvailableScanRange`](Sandbox.ModAPI.Ingame.AvailableScanRange)|The maximum distance that this camera can scan, based on the time since the last scan.|
|[`EnableRaycast`](Sandbox.ModAPI.Ingame.EnableRaycast)|When this is true, the available raycast distance will count up, and power usage is increased.|
|[`RaycastConeLimit`](Sandbox.ModAPI.Ingame.RaycastConeLimit)|Returns the maximum positive angle you can apply for pitch and yaw.|
|[`RaycastDistanceLimit`](Sandbox.ModAPI.Ingame.RaycastDistanceLimit)|Returns the maximum distance you can request a raycast. -1 means infinite.|
|[`Components`](VRage.Game.ModAPI.Ingame.Components)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`EntityId`](VRage.Game.ModAPI.Ingame.EntityId)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`Name`](VRage.Game.ModAPI.Ingame.Name)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)|Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)|Returns the count of the number of inventories this entity has.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`CheckConnectionAllowed`](VRage.Game.ModAPI.Ingame.CheckConnectionAllowed)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid)|Grid in which the block is placed<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`DefinitionDisplayNameText`](VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText)|Definition name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`DisassembleRatio`](VRage.Game.ModAPI.Ingame.DisassembleRatio)|Is set in definition Ratio at which is the block disassembled (grinding)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`DisplayNameText`](VRage.Game.ModAPI.Ingame.DisplayNameText)|Translated block name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`IsBeingHacked`](VRage.Game.ModAPI.Ingame.IsBeingHacked)|Hacking of the block is in progress<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`IsFunctional`](VRage.Game.ModAPI.Ingame.IsFunctional)|True if integrity is above breaking threshold<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`IsWorking`](VRage.Game.ModAPI.Ingame.IsWorking)|True if block is able to do its work depening on block type (is functional, powered, enabled, etc...)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`Max`](VRage.Game.ModAPI.Ingame.Max)|Maximum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`Mass`](VRage.Game.ModAPI.Ingame.Mass)|Block mass<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`Min`](VRage.Game.ModAPI.Ingame.Min)|Minimum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`NumberInGrid`](VRage.Game.ModAPI.Ingame.NumberInGrid)|Order in which were the blocks of same type added to grid Used in default display name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`Orientation`](VRage.Game.ModAPI.Ingame.Orientation)|Returns block orientation in base 6 directions<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId)|Id of player owning block (not steam Id)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`Position`](VRage.Game.ModAPI.Ingame.Position)|Position in grid coordinates<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`CustomName`](Sandbox.ModAPI.Ingame.CustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`CustomNameWithFaction`](Sandbox.ModAPI.Ingame.CustomNameWithFaction)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`DetailedInfo`](Sandbox.ModAPI.Ingame.DetailedInfo)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`CustomInfo`](Sandbox.ModAPI.Ingame.CustomInfo)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`CustomData`](Sandbox.ModAPI.Ingame.CustomData)|Gets or sets the Custom Data string. NOTE: Only use this for user input. For storing large mod configs, create your own MyModStorageComponent<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`ShowOnHUD`](Sandbox.ModAPI.Ingame.ShowOnHUD)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`ShowInTerminal`](Sandbox.ModAPI.Ingame.ShowInTerminal)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`ShowInToolbarConfig`](Sandbox.ModAPI.Ingame.ShowInToolbarConfig)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`ShowInInventory`](Sandbox.ModAPI.Ingame.ShowInInventory)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`Enabled`](Sandbox.ModAPI.Ingame.Enabled)|_Inherited from [`IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
### Methods
|Member|Description|
|---|---|
|[`Raycast(double, float, float)`](Sandbox.ModAPI.Ingame.Raycast)|Does a raycast in the direction the camera is facing. Pitch and Yaw are in degrees. Will return an empty struct if distance or angle are out of bounds.|
|[`Raycast(Vector3D)`](Sandbox.ModAPI.Ingame.Raycast)|Does a raycast to the given point. Will return an empty struct if distance or angle are out of bounds.|
|[`Raycast(double, Vector3D)`](Sandbox.ModAPI.Ingame.Raycast)|Does a raycast in the given direction. Will return an empty struct if distance or angle are out of bounds.|
|[`CanScan(double)`](Sandbox.ModAPI.Ingame.CanScan)|Checks if the camera can scan the given distance.|
|[`CanScan(double, Vector3D)`](Sandbox.ModAPI.Ingame.CanScan)|Checks if the camera can scan to the given direction and distance.|
|[`CanScan(Vector3D)`](Sandbox.ModAPI.Ingame.CanScan)|Checks if the camera can scan to the given target|
|[`TimeUntilScan(double)`](Sandbox.ModAPI.Ingame.TimeUntilScan)|Returns the number of milliseconds until the camera can do a raycast of the given distance.|
|[`GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)|Simply get the MyInventoryBase component stored in this entity.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`GetInventory(int)`](VRage.Game.ModAPI.Ingame.GetInventory)|Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`GetOwnerFactionTag()`](VRage.Game.ModAPI.Ingame.GetOwnerFactionTag)|Tag of faction owning block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`GetPlayerRelationToOwner()`](VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`GetUserRelationToOwner(long)`](VRage.Game.ModAPI.Ingame.GetUserRelationToOwner)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`UpdateIsWorking()`](VRage.Game.ModAPI.Ingame.UpdateIsWorking)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`UpdateVisual()`](VRage.Game.ModAPI.Ingame.UpdateVisual)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`HasLocalPlayerAccess()`](Sandbox.ModAPI.Ingame.HasLocalPlayerAccess)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`HasPlayerAccess(long)`](Sandbox.ModAPI.Ingame.HasPlayerAccess)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`SetCustomName(string)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`SetCustomName(StringBuilder)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`GetActions(List<ITerminalAction>, Func<ITerminalAction, bool>)`](Sandbox.ModAPI.Ingame.GetActions)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`SearchActionsOfName(string, List<ITerminalAction>, Func<ITerminalAction, bool>)`](Sandbox.ModAPI.Ingame.SearchActionsOfName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`GetActionWithName(string)`](Sandbox.ModAPI.Ingame.GetActionWithName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`GetProperty(string)`](Sandbox.ModAPI.Ingame.GetProperty)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`GetProperties(List<ITerminalProperty>, Func<ITerminalProperty, bool>)`](Sandbox.ModAPI.Ingame.GetProperties)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`IsSameConstructAs(IMyTerminalBlock)`](Sandbox.ModAPI.Ingame.IsSameConstructAs)|Determines whether this block is mechanically connected to the other. This is any block connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
|[`RequestEnable(bool)`](Sandbox.ModAPI.Ingame.RequestEnable)|_Inherited from [`IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyCameraBlock)_|
