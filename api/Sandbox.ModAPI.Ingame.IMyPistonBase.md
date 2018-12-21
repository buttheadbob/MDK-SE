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
|[`float Velocity`](Sandbox.ModAPI.Ingame.Velocity)|Gets or sets the velocity of the piston as it extends or retracts. This value can be between negative and positive [float MaxVelocity](Sandbox.ModAPI.Ingame.MaxVelocity) .|
|[`float MaxVelocity`](Sandbox.ModAPI.Ingame.MaxVelocity)|Gets the maximum velocity this piston is capable of moving at.|
|[`float MinLimit`](Sandbox.ModAPI.Ingame.MinLimit)|Gets or sets the minimum position the piston can retract to. See [float LowestPosition](Sandbox.ModAPI.Ingame.LowestPosition) and [float HighestPosition](Sandbox.ModAPI.Ingame.HighestPosition) for the limits of this value.|
|[`float MaxLimit`](Sandbox.ModAPI.Ingame.MaxLimit)|Gets or sets the maximum position the piston can extend to. See [float LowestPosition](Sandbox.ModAPI.Ingame.LowestPosition) and [float HighestPosition](Sandbox.ModAPI.Ingame.HighestPosition) for the limits of this value.|
|[`float LowestPosition`](Sandbox.ModAPI.Ingame.LowestPosition)|Gets the lowest position the piston is capable of moving to.|
|[`float HighestPosition`](Sandbox.ModAPI.Ingame.HighestPosition)|Gets the highest position the piston is capable of moving to.|
|[`float CurrentPosition`](Sandbox.ModAPI.Ingame.CurrentPosition)|Gets the current position of the piston head relative to the base.|
|[`Sandbox.ModAPI.Ingame.PistonStatus Status`](Sandbox.ModAPI.Ingame.Status)|Gets the current status.|
|[`VRage.Game.Components.MyEntityComponentContainer Components`](VRage.Game.ModAPI.Ingame.Components)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`long EntityId`](VRage.Game.ModAPI.Ingame.EntityId)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`string Name`](VRage.Game.ModAPI.Ingame.Name)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`string DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`bool HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)|Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`int InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)|Returns the count of the number of inventories this entity has.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`VRageMath.BoundingBoxD WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`VRageMath.BoundingBoxD WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`VRageMath.MatrixD WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`VRageMath.BoundingSphereD WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`VRageMath.BoundingSphereD WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`VRage.ObjectBuilders.SerializableDefinitionId BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`bool CheckConnectionAllowed`](VRage.Game.ModAPI.Ingame.CheckConnectionAllowed)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`VRage.Game.ModAPI.Ingame.IMyCubeGrid CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid)|Grid in which the block is placed<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`string DefinitionDisplayNameText`](VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText)|Definition name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`float DisassembleRatio`](VRage.Game.ModAPI.Ingame.DisassembleRatio)|Is set in definition Ratio at which is the block disassembled (grinding)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`string DisplayNameText`](VRage.Game.ModAPI.Ingame.DisplayNameText)|Translated block name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`bool IsBeingHacked`](VRage.Game.ModAPI.Ingame.IsBeingHacked)|Hacking of the block is in progress<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`bool IsFunctional`](VRage.Game.ModAPI.Ingame.IsFunctional)|True if integrity is above breaking threshold<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`bool IsWorking`](VRage.Game.ModAPI.Ingame.IsWorking)|True if block is able to do its work depening on block type (is functional, powered, enabled, etc...)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`VRageMath.Vector3I Max`](VRage.Game.ModAPI.Ingame.Max)|Maximum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`float Mass`](VRage.Game.ModAPI.Ingame.Mass)|Block mass<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`VRageMath.Vector3I Min`](VRage.Game.ModAPI.Ingame.Min)|Minimum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`int NumberInGrid`](VRage.Game.ModAPI.Ingame.NumberInGrid)|Order in which were the blocks of same type added to grid Used in default display name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`VRageMath.MyBlockOrientation Orientation`](VRage.Game.ModAPI.Ingame.Orientation)|Returns block orientation in base 6 directions<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`long OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId)|Id of player owning block (not steam Id)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`VRageMath.Vector3I Position`](VRage.Game.ModAPI.Ingame.Position)|Position in grid coordinates<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`string CustomName`](Sandbox.ModAPI.Ingame.CustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`string CustomNameWithFaction`](Sandbox.ModAPI.Ingame.CustomNameWithFaction)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`string DetailedInfo`](Sandbox.ModAPI.Ingame.DetailedInfo)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`string CustomInfo`](Sandbox.ModAPI.Ingame.CustomInfo)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`string CustomData`](Sandbox.ModAPI.Ingame.CustomData)|Gets or sets the Custom Data string. NOTE: Only use this for user input. For storing large mod configs, create your own MyModStorageComponent<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`bool ShowOnHUD`](Sandbox.ModAPI.Ingame.ShowOnHUD)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`bool ShowInTerminal`](Sandbox.ModAPI.Ingame.ShowInTerminal)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`bool ShowInToolbarConfig`](Sandbox.ModAPI.Ingame.ShowInToolbarConfig)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`bool ShowInInventory`](Sandbox.ModAPI.Ingame.ShowInInventory)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`bool Enabled`](Sandbox.ModAPI.Ingame.Enabled)|_Inherited from [`IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`VRage.Game.ModAPI.Ingame.IMyCubeGrid TopGrid`](Sandbox.ModAPI.Ingame.TopGrid)|Gets the grid of the attached top part<br/><br/>_Inherited from [`IMyMechanicalConnectionBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`Sandbox.ModAPI.Ingame.IMyAttachableTopBlock Top`](Sandbox.ModAPI.Ingame.Top)|Gets the attached top part entity<br/><br/>_Inherited from [`IMyMechanicalConnectionBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`float SafetyLockSpeed`](Sandbox.ModAPI.Ingame.SafetyLockSpeed)|Gets or sets the speed at which this device will engage it's safety lock ( [bool IsLocked](Sandbox.ModAPI.Ingame.IsLocked) ).<br/><br/>_Inherited from [`IMyMechanicalConnectionBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`bool SafetyLock`](Sandbox.ModAPI.Ingame.SafetyLock)|Gets if the block is safety locked (welded)<br/><br/>_Inherited from [`IMyMechanicalConnectionBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`bool IsAttached`](Sandbox.ModAPI.Ingame.IsAttached)|Gets if the block base is attached to something<br/><br/>_Inherited from [`IMyMechanicalConnectionBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`bool IsLocked`](Sandbox.ModAPI.Ingame.IsLocked)|Gets if the block is safety locked (welded)<br/><br/>_Inherited from [`IMyMechanicalConnectionBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`bool PendingAttachment`](Sandbox.ModAPI.Ingame.PendingAttachment)|Gets if the block is looking for a top part<br/><br/>_Inherited from [`IMyMechanicalConnectionBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
### Methods
|Member|Description|
|---|---|
|[`void Extend()`](Sandbox.ModAPI.Ingame.Extend)|Extends the piston.|
|[`void Retract()`](Sandbox.ModAPI.Ingame.Retract)|Retracts the piston.|
|[`void Reverse()`](Sandbox.ModAPI.Ingame.Reverse)|Reverses the direction of the piston.|
|[`VRage.Game.ModAPI.Ingame.IMyInventory GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)|Simply get the MyInventoryBase component stored in this entity.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`VRage.Game.ModAPI.Ingame.IMyInventory GetInventory(int)`](VRage.Game.ModAPI.Ingame.GetInventory)|Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`VRageMath.Vector3D GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`string GetOwnerFactionTag()`](VRage.Game.ModAPI.Ingame.GetOwnerFactionTag)|Tag of faction owning block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`VRage.Game.MyRelationsBetweenPlayerAndBlock GetPlayerRelationToOwner()`](VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`VRage.Game.MyRelationsBetweenPlayerAndBlock GetUserRelationToOwner(long)`](VRage.Game.ModAPI.Ingame.GetUserRelationToOwner)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`void UpdateIsWorking()`](VRage.Game.ModAPI.Ingame.UpdateIsWorking)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`void UpdateVisual()`](VRage.Game.ModAPI.Ingame.UpdateVisual)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`bool HasLocalPlayerAccess()`](Sandbox.ModAPI.Ingame.HasLocalPlayerAccess)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`bool HasPlayerAccess(long)`](Sandbox.ModAPI.Ingame.HasPlayerAccess)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`void SetCustomName(string)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`void SetCustomName(System.Text.StringBuilder)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`void GetActions(List<Sandbox.ModAPI.Interfaces.ITerminalAction>, Func<Sandbox.ModAPI.Interfaces.ITerminalAction, System.Boolean>)`](Sandbox.ModAPI.Ingame.GetActions)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`void SearchActionsOfName(string, List<Sandbox.ModAPI.Interfaces.ITerminalAction>, Func<Sandbox.ModAPI.Interfaces.ITerminalAction, System.Boolean>)`](Sandbox.ModAPI.Ingame.SearchActionsOfName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`Sandbox.ModAPI.Interfaces.ITerminalAction GetActionWithName(string)`](Sandbox.ModAPI.Ingame.GetActionWithName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`Sandbox.ModAPI.Interfaces.ITerminalProperty GetProperty(string)`](Sandbox.ModAPI.Ingame.GetProperty)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`void GetProperties(List<Sandbox.ModAPI.Interfaces.ITerminalProperty>, Func<Sandbox.ModAPI.Interfaces.ITerminalProperty, System.Boolean>)`](Sandbox.ModAPI.Ingame.GetProperties)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`bool IsSameConstructAs(Sandbox.ModAPI.Ingame.IMyTerminalBlock)`](Sandbox.ModAPI.Ingame.IsSameConstructAs)|Determines whether this block is mechanically connected to the other. This is any block connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`void RequestEnable(bool)`](Sandbox.ModAPI.Ingame.RequestEnable)|_Inherited from [`IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`void Attach()`](Sandbox.ModAPI.Ingame.Attach)|Attaches a nearby top part to the block<br/><br/>_Inherited from [`IMyMechanicalConnectionBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
|[`void Detach()`](Sandbox.ModAPI.Ingame.Detach)|Detaches the top from the base<br/><br/>_Inherited from [`IMyMechanicalConnectionBlock`](Sandbox.ModAPI.Ingame.IMyPistonBase)_|
