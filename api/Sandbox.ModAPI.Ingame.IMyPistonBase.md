← [Index](index)
# IMyPistonBase Interface
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
**Implements:**
* [`Sandbox.ModAPI.Ingame.IMyMechanicalConnectionBlock`](Sandbox.ModAPI.Ingame.IMyMechanicalConnectionBlock)
* [`Sandbox.ModAPI.Ingame.IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyFunctionalBlock)
* [`Sandbox.ModAPI.Ingame.IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTerminalBlock)
* [`VRage.Game.ModAPI.Ingame.IMyCubeBlock`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)
* [`VRage.Game.ModAPI.Ingame.IMyEntity`](VRage.Game.ModAPI.Ingame.IMyEntity)
### Properties
|Member|Description|
|---|---|
|[`Velocity`](Sandbox.ModAPI.Ingame.Velocity)|Gets or sets the velocity of the piston as it extends or retracts. This value can be between negative and positive [float MaxVelocity](Sandbox.ModAPI.Ingame.MaxVelocity) .|
|[`MaxVelocity`](Sandbox.ModAPI.Ingame.MaxVelocity)|Gets the maximum velocity this piston is capable of moving at.|
|[`MinLimit`](Sandbox.ModAPI.Ingame.MinLimit)|Gets or sets the minimum position the piston can retract to. See [float LowestPosition](Sandbox.ModAPI.Ingame.LowestPosition) and [float HighestPosition](Sandbox.ModAPI.Ingame.HighestPosition) for the limits of this value.|
|[`MaxLimit`](Sandbox.ModAPI.Ingame.MaxLimit)|Gets or sets the maximum position the piston can extend to. See [float LowestPosition](Sandbox.ModAPI.Ingame.LowestPosition) and [float HighestPosition](Sandbox.ModAPI.Ingame.HighestPosition) for the limits of this value.|
|[`LowestPosition`](Sandbox.ModAPI.Ingame.LowestPosition)|Gets the lowest position the piston is capable of moving to.|
|[`HighestPosition`](Sandbox.ModAPI.Ingame.HighestPosition)|Gets the highest position the piston is capable of moving to.|
|[`CurrentPosition`](Sandbox.ModAPI.Ingame.CurrentPosition)|Gets the current position of the piston head relative to the base.|
|[`Status`](Sandbox.ModAPI.Ingame.Status)|Gets the current status.|
|[`Components`](VRage.Game.ModAPI.Ingame.Components)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`EntityId`](VRage.Game.ModAPI.Ingame.EntityId)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`Name`](VRage.Game.ModAPI.Ingame.Name)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)|Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)|Returns the count of the number of inventories this entity has.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`CheckConnectionAllowed`](VRage.Game.ModAPI.Ingame.CheckConnectionAllowed)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid)|Grid in which the block is placed<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`DefinitionDisplayNameText`](VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText)|Definition name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`DisassembleRatio`](VRage.Game.ModAPI.Ingame.DisassembleRatio)|Is set in definition Ratio at which is the block disassembled (grinding)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`DisplayNameText`](VRage.Game.ModAPI.Ingame.DisplayNameText)|Translated block name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`IsBeingHacked`](VRage.Game.ModAPI.Ingame.IsBeingHacked)|Hacking of the block is in progress<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`IsFunctional`](VRage.Game.ModAPI.Ingame.IsFunctional)|True if integrity is above breaking threshold<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`IsWorking`](VRage.Game.ModAPI.Ingame.IsWorking)|True if block is able to do its work depening on block type (is functional, powered, enabled, etc...)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`Max`](VRage.Game.ModAPI.Ingame.Max)|Maximum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`Mass`](VRage.Game.ModAPI.Ingame.Mass)|Block mass<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`Min`](VRage.Game.ModAPI.Ingame.Min)|Minimum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`NumberInGrid`](VRage.Game.ModAPI.Ingame.NumberInGrid)|Order in which were the blocks of same type added to grid Used in default display name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`Orientation`](VRage.Game.ModAPI.Ingame.Orientation)|Returns block orientation in base 6 directions<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId)|Id of player owning block (not steam Id)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`Position`](VRage.Game.ModAPI.Ingame.Position)|Position in grid coordinates<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`CustomName`](Sandbox.ModAPI.Ingame.CustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`CustomNameWithFaction`](Sandbox.ModAPI.Ingame.CustomNameWithFaction)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`DetailedInfo`](Sandbox.ModAPI.Ingame.DetailedInfo)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`CustomInfo`](Sandbox.ModAPI.Ingame.CustomInfo)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`CustomData`](Sandbox.ModAPI.Ingame.CustomData)|Gets or sets the Custom Data string. NOTE: Only use this for user input. For storing large mod configs, create your own MyModStorageComponent<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`ShowOnHUD`](Sandbox.ModAPI.Ingame.ShowOnHUD)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`ShowInTerminal`](Sandbox.ModAPI.Ingame.ShowInTerminal)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`ShowInToolbarConfig`](Sandbox.ModAPI.Ingame.ShowInToolbarConfig)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`ShowInInventory`](Sandbox.ModAPI.Ingame.ShowInInventory)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`Enabled`](Sandbox.ModAPI.Ingame.Enabled)|_Inherited from [`IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`TopGrid`](Sandbox.ModAPI.Ingame.TopGrid)|Gets the grid of the attached top part<br/><br/>_Inherited from [`IMyMechanicalConnectionBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`Top`](Sandbox.ModAPI.Ingame.Top)|Gets the attached top part entity<br/><br/>_Inherited from [`IMyMechanicalConnectionBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`SafetyLockSpeed`](Sandbox.ModAPI.Ingame.SafetyLockSpeed)|Gets or sets the speed at which this device will engage it's safety lock ( [bool IsLocked](Sandbox.ModAPI.Ingame.IsLocked) ).<br/><br/>_Inherited from [`IMyMechanicalConnectionBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`SafetyLock`](Sandbox.ModAPI.Ingame.SafetyLock)|Gets if the block is safety locked (welded)<br/><br/>_Inherited from [`IMyMechanicalConnectionBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`IsAttached`](Sandbox.ModAPI.Ingame.IsAttached)|Gets if the block base is attached to something<br/><br/>_Inherited from [`IMyMechanicalConnectionBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`IsLocked`](Sandbox.ModAPI.Ingame.IsLocked)|Gets if the block is safety locked (welded)<br/><br/>_Inherited from [`IMyMechanicalConnectionBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`PendingAttachment`](Sandbox.ModAPI.Ingame.PendingAttachment)|Gets if the block is looking for a top part<br/><br/>_Inherited from [`IMyMechanicalConnectionBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
### Methods
|Member|Description|
|---|---|
|[`Extend()`](Sandbox.ModAPI.Ingame.Extend)|Extends the piston.|
|[`Retract()`](Sandbox.ModAPI.Ingame.Retract)|Retracts the piston.|
|[`Reverse()`](Sandbox.ModAPI.Ingame.Reverse)|Reverses the direction of the piston.|
|[`GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)|Simply get the MyInventoryBase component stored in this entity.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`GetInventory(int)`](VRage.Game.ModAPI.Ingame.GetInventory)|Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`GetOwnerFactionTag()`](VRage.Game.ModAPI.Ingame.GetOwnerFactionTag)|Tag of faction owning block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`GetPlayerRelationToOwner()`](VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`GetUserRelationToOwner(long)`](VRage.Game.ModAPI.Ingame.GetUserRelationToOwner)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`UpdateIsWorking()`](VRage.Game.ModAPI.Ingame.UpdateIsWorking)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`UpdateVisual()`](VRage.Game.ModAPI.Ingame.UpdateVisual)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`HasLocalPlayerAccess()`](Sandbox.ModAPI.Ingame.HasLocalPlayerAccess)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`HasPlayerAccess(long)`](Sandbox.ModAPI.Ingame.HasPlayerAccess)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`SetCustomName(string)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`SetCustomName(StringBuilder)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`GetActions(List<ITerminalAction>, Func<ITerminalAction, bool>)`](Sandbox.ModAPI.Ingame.GetActions)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`SearchActionsOfName(string, List<ITerminalAction>, Func<ITerminalAction, bool>)`](Sandbox.ModAPI.Ingame.SearchActionsOfName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`GetActionWithName(string)`](Sandbox.ModAPI.Ingame.GetActionWithName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`GetProperty(string)`](Sandbox.ModAPI.Ingame.GetProperty)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`GetProperties(List<ITerminalProperty>, Func<ITerminalProperty, bool>)`](Sandbox.ModAPI.Ingame.GetProperties)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`IsSameConstructAs(IMyTerminalBlock)`](Sandbox.ModAPI.Ingame.IsSameConstructAs)|Determines whether this block is mechanically connected to the other. This is any block connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`RequestEnable(bool)`](Sandbox.ModAPI.Ingame.RequestEnable)|_Inherited from [`IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`Attach()`](Sandbox.ModAPI.Ingame.Attach)|Attaches a nearby top part to the block<br/><br/>_Inherited from [`IMyMechanicalConnectionBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`Detach()`](Sandbox.ModAPI.Ingame.Detach)|Detaches the top from the base<br/><br/>_Inherited from [`IMyMechanicalConnectionBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
