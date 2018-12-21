← [Index](index)
# IMySensorBlock Interface
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
|[`MaxRange`](Sandbox.ModAPI.Ingame.MaxRange)|Gets the maximum range of the sensor in any direction.|
|[`LeftExtend`](Sandbox.ModAPI.Ingame.LeftExtend)|Gets or sets the left range of the sensor.|
|[`RightExtend`](Sandbox.ModAPI.Ingame.RightExtend)|Gets or sets the right range of the sensor.|
|[`TopExtend`](Sandbox.ModAPI.Ingame.TopExtend)|Gets or sets the top range of the sensor.|
|[`BottomExtend`](Sandbox.ModAPI.Ingame.BottomExtend)|Gets or sets the bottom range of the sensor.|
|[`FrontExtend`](Sandbox.ModAPI.Ingame.FrontExtend)|Gets or sets the front range of the sensor.|
|[`BackExtend`](Sandbox.ModAPI.Ingame.BackExtend)|Gets or sets the back range of the sensor.|
|[`PlayProximitySound`](Sandbox.ModAPI.Ingame.PlayProximitySound)|Gets or sets if the proximity sound plays when an entity is detected.|
|[`DetectPlayers`](Sandbox.ModAPI.Ingame.DetectPlayers)|Gets or sets if the sensor should detect players.|
|[`DetectFloatingObjects`](Sandbox.ModAPI.Ingame.DetectFloatingObjects)|Gets or sets if the sensor should detect floating objects (components, rocks).|
|[`DetectSmallShips`](Sandbox.ModAPI.Ingame.DetectSmallShips)|Gets or sets if the sensor should detect small ships.|
|[`DetectLargeShips`](Sandbox.ModAPI.Ingame.DetectLargeShips)|Gets or sets if the sensor should detect large ships.|
|[`DetectStations`](Sandbox.ModAPI.Ingame.DetectStations)|Gets or sets if the sensor should detect large stations.|
|[`DetectSubgrids`](Sandbox.ModAPI.Ingame.DetectSubgrids)|Gets or sets if the sensor should detect subgrids (eg. connected by connector).|
|[`DetectAsteroids`](Sandbox.ModAPI.Ingame.DetectAsteroids)|Gets or sets if the sensor should detect asteroids or planets.|
|[`DetectOwner`](Sandbox.ModAPI.Ingame.DetectOwner)|Gets or sets if the sensor should detect the block owner.|
|[`DetectFriendly`](Sandbox.ModAPI.Ingame.DetectFriendly)|Gets or sets if the sensor should detect friendly players.|
|[`DetectNeutral`](Sandbox.ModAPI.Ingame.DetectNeutral)|Gets or sets if the sensor should detect neutral players.|
|[`DetectEnemy`](Sandbox.ModAPI.Ingame.DetectEnemy)|Gets or sets if the sensor should detect enemy players.|
|[`IsActive`](Sandbox.ModAPI.Ingame.IsActive)|Gets if there is any entity currently being detected.|
|[`LastDetectedEntity`](Sandbox.ModAPI.Ingame.LastDetectedEntity)||
|[`Components`](VRage.Game.ModAPI.Ingame.Components)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`EntityId`](VRage.Game.ModAPI.Ingame.EntityId)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`Name`](VRage.Game.ModAPI.Ingame.Name)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)|Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)|Returns the count of the number of inventories this entity has.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`CheckConnectionAllowed`](VRage.Game.ModAPI.Ingame.CheckConnectionAllowed)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid)|Grid in which the block is placed<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`DefinitionDisplayNameText`](VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText)|Definition name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`DisassembleRatio`](VRage.Game.ModAPI.Ingame.DisassembleRatio)|Is set in definition Ratio at which is the block disassembled (grinding)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`DisplayNameText`](VRage.Game.ModAPI.Ingame.DisplayNameText)|Translated block name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`IsBeingHacked`](VRage.Game.ModAPI.Ingame.IsBeingHacked)|Hacking of the block is in progress<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`IsFunctional`](VRage.Game.ModAPI.Ingame.IsFunctional)|True if integrity is above breaking threshold<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`IsWorking`](VRage.Game.ModAPI.Ingame.IsWorking)|True if block is able to do its work depening on block type (is functional, powered, enabled, etc...)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`Max`](VRage.Game.ModAPI.Ingame.Max)|Maximum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`Mass`](VRage.Game.ModAPI.Ingame.Mass)|Block mass<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`Min`](VRage.Game.ModAPI.Ingame.Min)|Minimum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`NumberInGrid`](VRage.Game.ModAPI.Ingame.NumberInGrid)|Order in which were the blocks of same type added to grid Used in default display name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`Orientation`](VRage.Game.ModAPI.Ingame.Orientation)|Returns block orientation in base 6 directions<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId)|Id of player owning block (not steam Id)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`Position`](VRage.Game.ModAPI.Ingame.Position)|Position in grid coordinates<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`CustomName`](Sandbox.ModAPI.Ingame.CustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`CustomNameWithFaction`](Sandbox.ModAPI.Ingame.CustomNameWithFaction)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`DetailedInfo`](Sandbox.ModAPI.Ingame.DetailedInfo)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`CustomInfo`](Sandbox.ModAPI.Ingame.CustomInfo)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`CustomData`](Sandbox.ModAPI.Ingame.CustomData)|Gets or sets the Custom Data string. NOTE: Only use this for user input. For storing large mod configs, create your own MyModStorageComponent<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`ShowOnHUD`](Sandbox.ModAPI.Ingame.ShowOnHUD)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`ShowInTerminal`](Sandbox.ModAPI.Ingame.ShowInTerminal)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`ShowInToolbarConfig`](Sandbox.ModAPI.Ingame.ShowInToolbarConfig)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`ShowInInventory`](Sandbox.ModAPI.Ingame.ShowInInventory)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`Enabled`](Sandbox.ModAPI.Ingame.Enabled)|_Inherited from [`IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
### Methods
|Member|Description|
|---|---|
|[`DetectedEntities(List<MyDetectedEntityInfo>)`](Sandbox.ModAPI.Ingame.DetectedEntities)||
|[`GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)|Simply get the MyInventoryBase component stored in this entity.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`GetInventory(int)`](VRage.Game.ModAPI.Ingame.GetInventory)|Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`GetOwnerFactionTag()`](VRage.Game.ModAPI.Ingame.GetOwnerFactionTag)|Tag of faction owning block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`GetPlayerRelationToOwner()`](VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`GetUserRelationToOwner(long)`](VRage.Game.ModAPI.Ingame.GetUserRelationToOwner)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`UpdateIsWorking()`](VRage.Game.ModAPI.Ingame.UpdateIsWorking)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`UpdateVisual()`](VRage.Game.ModAPI.Ingame.UpdateVisual)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`HasLocalPlayerAccess()`](Sandbox.ModAPI.Ingame.HasLocalPlayerAccess)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`HasPlayerAccess(long)`](Sandbox.ModAPI.Ingame.HasPlayerAccess)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`SetCustomName(string)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`SetCustomName(StringBuilder)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`GetActions(List<ITerminalAction>, Func<ITerminalAction, bool>)`](Sandbox.ModAPI.Ingame.GetActions)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`SearchActionsOfName(string, List<ITerminalAction>, Func<ITerminalAction, bool>)`](Sandbox.ModAPI.Ingame.SearchActionsOfName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`GetActionWithName(string)`](Sandbox.ModAPI.Ingame.GetActionWithName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`GetProperty(string)`](Sandbox.ModAPI.Ingame.GetProperty)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`GetProperties(List<ITerminalProperty>, Func<ITerminalProperty, bool>)`](Sandbox.ModAPI.Ingame.GetProperties)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`IsSameConstructAs(IMyTerminalBlock)`](Sandbox.ModAPI.Ingame.IsSameConstructAs)|Determines whether this block is mechanically connected to the other. This is any block connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
|[`RequestEnable(bool)`](Sandbox.ModAPI.Ingame.RequestEnable)|_Inherited from [`IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMySensorBlock)_|
