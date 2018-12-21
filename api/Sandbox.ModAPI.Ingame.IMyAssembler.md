← [Index](ApiIndex)
# IMyAssembler Interface
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
**Implements:**
* [`Sandbox.ModAPI.Ingame.IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)
* [`Sandbox.ModAPI.Ingame.IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyFunctionalBlock)
* [`Sandbox.ModAPI.Ingame.IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTerminalBlock)
* [`VRage.Game.ModAPI.Ingame.IMyCubeBlock`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)
* [`VRage.Game.ModAPI.Ingame.IMyEntity`](VRage.Game.ModAPI.Ingame.IMyEntity)

### Properties
|Member|Description|
|---|---|
|[`DisassembleEnabled`](Sandbox.ModAPI.Ingame.DisassembleEnabled)||
|[`CurrentProgress`](Sandbox.ModAPI.Ingame.CurrentProgress)|Gets the progress for the item currently in production.|
|[`Mode`](Sandbox.ModAPI.Ingame.Mode)|Gets or sets the current work mode of this assembly, whether it's assembling or disassembling.|
|[`CooperativeMode`](Sandbox.ModAPI.Ingame.CooperativeMode)|Gets or sets whether this assembler should cooperate with other assemblers by adopting parts of their work queue.|
|[`Repeating`](Sandbox.ModAPI.Ingame.Repeating)|Gets or sets whether this assembler should be perpetually repeating its work queue.|
|[`Components`](VRage.Game.ModAPI.Ingame.Components)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`EntityId`](VRage.Game.ModAPI.Ingame.EntityId)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`Name`](VRage.Game.ModAPI.Ingame.Name)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)|Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)|Returns the count of the number of inventories this entity has.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`CheckConnectionAllowed`](VRage.Game.ModAPI.Ingame.CheckConnectionAllowed)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid)|Grid in which the block is placed<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`DefinitionDisplayNameText`](VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText)|Definition name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`DisassembleRatio`](VRage.Game.ModAPI.Ingame.DisassembleRatio)|Is set in definition Ratio at which is the block disassembled (grinding)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`DisplayNameText`](VRage.Game.ModAPI.Ingame.DisplayNameText)|Translated block name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`IsBeingHacked`](VRage.Game.ModAPI.Ingame.IsBeingHacked)|Hacking of the block is in progress<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`IsFunctional`](VRage.Game.ModAPI.Ingame.IsFunctional)|True if integrity is above breaking threshold<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`IsWorking`](VRage.Game.ModAPI.Ingame.IsWorking)|True if block is able to do its work depening on block type (is functional, powered, enabled, etc...)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`Max`](VRage.Game.ModAPI.Ingame.Max)|Maximum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`Mass`](VRage.Game.ModAPI.Ingame.Mass)|Block mass<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`Min`](VRage.Game.ModAPI.Ingame.Min)|Minimum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`NumberInGrid`](VRage.Game.ModAPI.Ingame.NumberInGrid)|Order in which were the blocks of same type added to grid Used in default display name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`Orientation`](VRage.Game.ModAPI.Ingame.Orientation)|Returns block orientation in base 6 directions<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId)|Id of player owning block (not steam Id)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`Position`](VRage.Game.ModAPI.Ingame.Position)|Position in grid coordinates<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`CustomName`](Sandbox.ModAPI.Ingame.CustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`CustomNameWithFaction`](Sandbox.ModAPI.Ingame.CustomNameWithFaction)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`DetailedInfo`](Sandbox.ModAPI.Ingame.DetailedInfo)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`CustomInfo`](Sandbox.ModAPI.Ingame.CustomInfo)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`CustomData`](Sandbox.ModAPI.Ingame.CustomData)|Gets or sets the Custom Data string. NOTE: Only use this for user input. For storing large mod configs, create your own MyModStorageComponent<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`ShowOnHUD`](Sandbox.ModAPI.Ingame.ShowOnHUD)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`ShowInTerminal`](Sandbox.ModAPI.Ingame.ShowInTerminal)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`ShowInToolbarConfig`](Sandbox.ModAPI.Ingame.ShowInToolbarConfig)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`ShowInInventory`](Sandbox.ModAPI.Ingame.ShowInInventory)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`Enabled`](Sandbox.ModAPI.Ingame.Enabled)|_Inherited from [`IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`InputInventory`](Sandbox.ModAPI.Ingame.InputInventory)|Gets the input inventory.<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`OutputInventory`](Sandbox.ModAPI.Ingame.OutputInventory)|Gets the output inventory.<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`IsProducing`](Sandbox.ModAPI.Ingame.IsProducing)|The device is currently producing.<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`IsQueueEmpty`](Sandbox.ModAPI.Ingame.IsQueueEmpty)|The production queue is empty.<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`NextItemId`](Sandbox.ModAPI.Ingame.NextItemId)|Gets the queue item ID of the next item to be produced.<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`UseConveyorSystem`](Sandbox.ModAPI.Ingame.UseConveyorSystem)|Gets or sets whether this device should use the conveyor system to retrieve and store items.<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
### Methods
|Member|Description|
|---|---|
|[`GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)|Simply get the MyInventoryBase component stored in this entity.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`GetInventory(int)`](VRage.Game.ModAPI.Ingame.GetInventory)|Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`GetOwnerFactionTag()`](VRage.Game.ModAPI.Ingame.GetOwnerFactionTag)|Tag of faction owning block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`GetPlayerRelationToOwner()`](VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`GetUserRelationToOwner(long)`](VRage.Game.ModAPI.Ingame.GetUserRelationToOwner)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`UpdateIsWorking()`](VRage.Game.ModAPI.Ingame.UpdateIsWorking)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`UpdateVisual()`](VRage.Game.ModAPI.Ingame.UpdateVisual)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`HasLocalPlayerAccess()`](Sandbox.ModAPI.Ingame.HasLocalPlayerAccess)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`HasPlayerAccess(long)`](Sandbox.ModAPI.Ingame.HasPlayerAccess)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`SetCustomName(string)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`SetCustomName(StringBuilder)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`GetActions(List<ITerminalAction>, Func<ITerminalAction, bool>)`](Sandbox.ModAPI.Ingame.GetActions)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`SearchActionsOfName(string, List<ITerminalAction>, Func<ITerminalAction, bool>)`](Sandbox.ModAPI.Ingame.SearchActionsOfName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`GetActionWithName(string)`](Sandbox.ModAPI.Ingame.GetActionWithName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`GetProperty(string)`](Sandbox.ModAPI.Ingame.GetProperty)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`GetProperties(List<ITerminalProperty>, Func<ITerminalProperty, bool>)`](Sandbox.ModAPI.Ingame.GetProperties)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`IsSameConstructAs(IMyTerminalBlock)`](Sandbox.ModAPI.Ingame.IsSameConstructAs)|Determines whether this block is mechanically connected to the other. This is any block connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`RequestEnable(bool)`](Sandbox.ModAPI.Ingame.RequestEnable)|_Inherited from [`IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`MoveQueueItemRequest(uint, int)`](Sandbox.ModAPI.Ingame.MoveQueueItemRequest)|Moves an item in the queue to a target position in the queue.<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`CanUseBlueprint(MyDefinitionId)`](Sandbox.ModAPI.Ingame.CanUseBlueprint)|Can this production block produce this blueprint?<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`AddQueueItem(MyDefinitionId, MyFixedPoint)`](Sandbox.ModAPI.Ingame.AddQueueItem)|Adds a blueprint to the production queue<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`AddQueueItem(MyDefinitionId, decimal)`](Sandbox.ModAPI.Ingame.AddQueueItem)|Adds a blueprint to the production queue<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`AddQueueItem(MyDefinitionId, double)`](Sandbox.ModAPI.Ingame.AddQueueItem)|Adds a blueprint to the production queue<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`InsertQueueItem(int, MyDefinitionId, MyFixedPoint)`](Sandbox.ModAPI.Ingame.InsertQueueItem)|Inserts a blueprint into the production queue<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`InsertQueueItem(int, MyDefinitionId, decimal)`](Sandbox.ModAPI.Ingame.InsertQueueItem)|Inserts a blueprint into the production queue<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`InsertQueueItem(int, MyDefinitionId, double)`](Sandbox.ModAPI.Ingame.InsertQueueItem)|Inserts a blueprint into the production queue<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`RemoveQueueItem(int, MyFixedPoint)`](Sandbox.ModAPI.Ingame.RemoveQueueItem)|Removes an item from the queue<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`RemoveQueueItem(int, decimal)`](Sandbox.ModAPI.Ingame.RemoveQueueItem)|Removes an item from the queue<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`RemoveQueueItem(int, double)`](Sandbox.ModAPI.Ingame.RemoveQueueItem)|Removes an item from the queue<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`ClearQueue()`](Sandbox.ModAPI.Ingame.ClearQueue)|Clears the Queue<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`GetQueue(List<MyProductionItem>)`](Sandbox.ModAPI.Ingame.GetQueue)|Gets the current production queue<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
