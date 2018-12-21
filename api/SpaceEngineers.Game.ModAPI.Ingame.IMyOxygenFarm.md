← [Index](ApiIndex)
# IMyOxygenFarm Interface
**Namespace:** [`SpaceEngineers.Game.ModAPI.Ingame`](SpaceEngineers.Game.ModAPI.Ingame)  
**Assembly:** SpaceEngineers.Game.dll  
**Implements:**
* [`Sandbox.ModAPI.Ingame.IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTerminalBlock)
* [`VRage.Game.ModAPI.Ingame.IMyCubeBlock`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)
* [`VRage.Game.ModAPI.Ingame.IMyEntity`](VRage.Game.ModAPI.Ingame.IMyEntity)

### Properties
|Member|Description|
|---|---|
|[`CanProduce`](SpaceEngineers.Game.ModAPI.Ingame.CanProduce)|Gets if the block can produce gas.|
|[`Components`](VRage.Game.ModAPI.Ingame.Components)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`EntityId`](VRage.Game.ModAPI.Ingame.EntityId)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`Name`](VRage.Game.ModAPI.Ingame.Name)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)|Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.<br/><br/>_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)|Returns the count of the number of inventories this entity has.<br/><br/>_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`CheckConnectionAllowed`](VRage.Game.ModAPI.Ingame.CheckConnectionAllowed)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid)|Grid in which the block is placed<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`DefinitionDisplayNameText`](VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText)|Definition name<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`DisassembleRatio`](VRage.Game.ModAPI.Ingame.DisassembleRatio)|Is set in definition Ratio at which is the block disassembled (grinding)<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`DisplayNameText`](VRage.Game.ModAPI.Ingame.DisplayNameText)|Translated block name<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`IsBeingHacked`](VRage.Game.ModAPI.Ingame.IsBeingHacked)|Hacking of the block is in progress<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`IsFunctional`](VRage.Game.ModAPI.Ingame.IsFunctional)|True if integrity is above breaking threshold<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`IsWorking`](VRage.Game.ModAPI.Ingame.IsWorking)|True if block is able to do its work depening on block type (is functional, powered, enabled, etc...)<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`Max`](VRage.Game.ModAPI.Ingame.Max)|Maximum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`Mass`](VRage.Game.ModAPI.Ingame.Mass)|Block mass<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`Min`](VRage.Game.ModAPI.Ingame.Min)|Minimum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`NumberInGrid`](VRage.Game.ModAPI.Ingame.NumberInGrid)|Order in which were the blocks of same type added to grid Used in default display name<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`Orientation`](VRage.Game.ModAPI.Ingame.Orientation)|Returns block orientation in base 6 directions<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId)|Id of player owning block (not steam Id)<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`Position`](VRage.Game.ModAPI.Ingame.Position)|Position in grid coordinates<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`CustomName`](Sandbox.ModAPI.Ingame.CustomName)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`CustomNameWithFaction`](Sandbox.ModAPI.Ingame.CustomNameWithFaction)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`DetailedInfo`](Sandbox.ModAPI.Ingame.DetailedInfo)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`CustomInfo`](Sandbox.ModAPI.Ingame.CustomInfo)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`CustomData`](Sandbox.ModAPI.Ingame.CustomData)|Gets or sets the Custom Data string. NOTE: Only use this for user input. For storing large mod configs, create your own MyModStorageComponent<br/><br/>_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`ShowOnHUD`](Sandbox.ModAPI.Ingame.ShowOnHUD)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`ShowInTerminal`](Sandbox.ModAPI.Ingame.ShowInTerminal)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`ShowInToolbarConfig`](Sandbox.ModAPI.Ingame.ShowInToolbarConfig)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`ShowInInventory`](Sandbox.ModAPI.Ingame.ShowInInventory)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
### Methods
|Member|Description|
|---|---|
|[`GetOutput()`](SpaceEngineers.Game.ModAPI.Ingame.GetOutput)||
|[`GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)|Simply get the MyInventoryBase component stored in this entity.<br/><br/>_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`GetInventory(int)`](VRage.Game.ModAPI.Ingame.GetInventory)|Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)|_Inherited from [`IMyEntity`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`GetOwnerFactionTag()`](VRage.Game.ModAPI.Ingame.GetOwnerFactionTag)|Tag of faction owning block<br/><br/>_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`GetPlayerRelationToOwner()`](VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`GetUserRelationToOwner(long)`](VRage.Game.ModAPI.Ingame.GetUserRelationToOwner)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`UpdateIsWorking()`](VRage.Game.ModAPI.Ingame.UpdateIsWorking)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`UpdateVisual()`](VRage.Game.ModAPI.Ingame.UpdateVisual)|_Inherited from [`IMyCubeBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`HasLocalPlayerAccess()`](Sandbox.ModAPI.Ingame.HasLocalPlayerAccess)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`HasPlayerAccess(long)`](Sandbox.ModAPI.Ingame.HasPlayerAccess)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`SetCustomName(string)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`SetCustomName(StringBuilder)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`GetActions(List<ITerminalAction>, Func<ITerminalAction, bool>)`](Sandbox.ModAPI.Ingame.GetActions)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`SearchActionsOfName(string, List<ITerminalAction>, Func<ITerminalAction, bool>)`](Sandbox.ModAPI.Ingame.SearchActionsOfName)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`GetActionWithName(string)`](Sandbox.ModAPI.Ingame.GetActionWithName)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`GetProperty(string)`](Sandbox.ModAPI.Ingame.GetProperty)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`GetProperties(List<ITerminalProperty>, Func<ITerminalProperty, bool>)`](Sandbox.ModAPI.Ingame.GetProperties)|_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
|[`IsSameConstructAs(IMyTerminalBlock)`](Sandbox.ModAPI.Ingame.IsSameConstructAs)|Determines whether this block is mechanically connected to the other. This is any block connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.<br/><br/>_Inherited from [`IMyTerminalBlock`](SpaceEngineers.Game.ModAPI.Ingame.IMyOxygenFarm)_|
