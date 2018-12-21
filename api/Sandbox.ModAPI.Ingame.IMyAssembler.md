← [Index](index)
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
|[`bool&nbsp;DisassembleEnabled`](Sandbox.ModAPI.Ingame.DisassembleEnabled)||
|[`float&nbsp;CurrentProgress`](Sandbox.ModAPI.Ingame.CurrentProgress)|Gets the progress for the item currently in production.|
|[`MyAssemblerMode&nbsp;Mode`](Sandbox.ModAPI.Ingame.Mode)|Gets or sets the current work mode of this assembly, whether it's assembling or disassembling.|
|[`bool&nbsp;CooperativeMode`](Sandbox.ModAPI.Ingame.CooperativeMode)|Gets or sets whether this assembler should cooperate with other assemblers by adopting parts of their work queue.|
|[`bool&nbsp;Repeating`](Sandbox.ModAPI.Ingame.Repeating)|Gets or sets whether this assembler should be perpetually repeating its work queue.|
|[`MyEntityComponentContainer&nbsp;Components`](VRage.Game.ModAPI.Ingame.Components)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`long&nbsp;EntityId`](VRage.Game.ModAPI.Ingame.EntityId)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`string&nbsp;Name`](VRage.Game.ModAPI.Ingame.Name)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`string&nbsp;DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`bool&nbsp;HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)|Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`int&nbsp;InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)|Returns the count of the number of inventories this entity has.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`BoundingBoxD&nbsp;WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`BoundingBoxD&nbsp;WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`MatrixD&nbsp;WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`BoundingSphereD&nbsp;WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`BoundingSphereD&nbsp;WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`SerializableDefinitionId&nbsp;BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`bool&nbsp;CheckConnectionAllowed`](VRage.Game.ModAPI.Ingame.CheckConnectionAllowed)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`IMyCubeGrid&nbsp;CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid)|Grid in which the block is placed<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`string&nbsp;DefinitionDisplayNameText`](VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText)|Definition name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`float&nbsp;DisassembleRatio`](VRage.Game.ModAPI.Ingame.DisassembleRatio)|Is set in definition Ratio at which is the block disassembled (grinding)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`string&nbsp;DisplayNameText`](VRage.Game.ModAPI.Ingame.DisplayNameText)|Translated block name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`bool&nbsp;IsBeingHacked`](VRage.Game.ModAPI.Ingame.IsBeingHacked)|Hacking of the block is in progress<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`bool&nbsp;IsFunctional`](VRage.Game.ModAPI.Ingame.IsFunctional)|True if integrity is above breaking threshold<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`bool&nbsp;IsWorking`](VRage.Game.ModAPI.Ingame.IsWorking)|True if block is able to do its work depening on block type (is functional, powered, enabled, etc...)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`Vector3I&nbsp;Max`](VRage.Game.ModAPI.Ingame.Max)|Maximum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`float&nbsp;Mass`](VRage.Game.ModAPI.Ingame.Mass)|Block mass<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`Vector3I&nbsp;Min`](VRage.Game.ModAPI.Ingame.Min)|Minimum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`int&nbsp;NumberInGrid`](VRage.Game.ModAPI.Ingame.NumberInGrid)|Order in which were the blocks of same type added to grid Used in default display name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`MyBlockOrientation&nbsp;Orientation`](VRage.Game.ModAPI.Ingame.Orientation)|Returns block orientation in base 6 directions<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`long&nbsp;OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId)|Id of player owning block (not steam Id)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`Vector3I&nbsp;Position`](VRage.Game.ModAPI.Ingame.Position)|Position in grid coordinates<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`string&nbsp;CustomName`](Sandbox.ModAPI.Ingame.CustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`string&nbsp;CustomNameWithFaction`](Sandbox.ModAPI.Ingame.CustomNameWithFaction)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`string&nbsp;DetailedInfo`](Sandbox.ModAPI.Ingame.DetailedInfo)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`string&nbsp;CustomInfo`](Sandbox.ModAPI.Ingame.CustomInfo)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`string&nbsp;CustomData`](Sandbox.ModAPI.Ingame.CustomData)|Gets or sets the Custom Data string. NOTE: Only use this for user input. For storing large mod configs, create your own MyModStorageComponent<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`bool&nbsp;ShowOnHUD`](Sandbox.ModAPI.Ingame.ShowOnHUD)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`bool&nbsp;ShowInTerminal`](Sandbox.ModAPI.Ingame.ShowInTerminal)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`bool&nbsp;ShowInToolbarConfig`](Sandbox.ModAPI.Ingame.ShowInToolbarConfig)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`bool&nbsp;ShowInInventory`](Sandbox.ModAPI.Ingame.ShowInInventory)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`bool&nbsp;Enabled`](Sandbox.ModAPI.Ingame.Enabled)|_Inherited from [`IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`IMyInventory&nbsp;InputInventory`](Sandbox.ModAPI.Ingame.InputInventory)|Gets the input inventory.<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`IMyInventory&nbsp;OutputInventory`](Sandbox.ModAPI.Ingame.OutputInventory)|Gets the output inventory.<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`bool&nbsp;IsProducing`](Sandbox.ModAPI.Ingame.IsProducing)|The device is currently producing.<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`bool&nbsp;IsQueueEmpty`](Sandbox.ModAPI.Ingame.IsQueueEmpty)|The production queue is empty.<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`uint&nbsp;NextItemId`](Sandbox.ModAPI.Ingame.NextItemId)|Gets the queue item ID of the next item to be produced.<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`bool&nbsp;UseConveyorSystem`](Sandbox.ModAPI.Ingame.UseConveyorSystem)|Gets or sets whether this device should use the conveyor system to retrieve and store items.<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
### Methods
|Member|Description|
|---|---|
|[`IMyInventory&nbsp;GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)|Simply get the MyInventoryBase component stored in this entity.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`IMyInventory&nbsp;GetInventory(int&nbsp;index)`](VRage.Game.ModAPI.Ingame.GetInventory)|Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`Vector3D&nbsp;GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`string&nbsp;GetOwnerFactionTag()`](VRage.Game.ModAPI.Ingame.GetOwnerFactionTag)|Tag of faction owning block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`MyRelationsBetweenPlayerAndBlock&nbsp;GetPlayerRelationToOwner()`](VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`MyRelationsBetweenPlayerAndBlock&nbsp;GetUserRelationToOwner(long&nbsp;playerId)`](VRage.Game.ModAPI.Ingame.GetUserRelationToOwner)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`void&nbsp;UpdateIsWorking()`](VRage.Game.ModAPI.Ingame.UpdateIsWorking)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`void&nbsp;UpdateVisual()`](VRage.Game.ModAPI.Ingame.UpdateVisual)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`bool&nbsp;HasLocalPlayerAccess()`](Sandbox.ModAPI.Ingame.HasLocalPlayerAccess)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`bool&nbsp;HasPlayerAccess(long&nbsp;playerId)`](Sandbox.ModAPI.Ingame.HasPlayerAccess)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`void&nbsp;SetCustomName(string&nbsp;text)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`void&nbsp;SetCustomName(StringBuilder&nbsp;text)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`void&nbsp;GetActions(List<ITerminalAction>&nbsp;resultList,&nbsp;Func<ITerminalAction,&nbsp;bool>&nbsp;collect)`](Sandbox.ModAPI.Ingame.GetActions)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`void&nbsp;SearchActionsOfName(string&nbsp;name,&nbsp;List<ITerminalAction>&nbsp;resultList,&nbsp;Func<ITerminalAction,&nbsp;bool>&nbsp;collect)`](Sandbox.ModAPI.Ingame.SearchActionsOfName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`ITerminalAction&nbsp;GetActionWithName(string&nbsp;name)`](Sandbox.ModAPI.Ingame.GetActionWithName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`ITerminalProperty&nbsp;GetProperty(string&nbsp;id)`](Sandbox.ModAPI.Ingame.GetProperty)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`void&nbsp;GetProperties(List<ITerminalProperty>&nbsp;resultList,&nbsp;Func<ITerminalProperty,&nbsp;bool>&nbsp;collect)`](Sandbox.ModAPI.Ingame.GetProperties)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`bool&nbsp;IsSameConstructAs(IMyTerminalBlock&nbsp;other)`](Sandbox.ModAPI.Ingame.IsSameConstructAs)|Determines whether this block is mechanically connected to the other. This is any block connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`void&nbsp;RequestEnable(bool&nbsp;enable)`](Sandbox.ModAPI.Ingame.RequestEnable)|_Inherited from [`IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`void&nbsp;MoveQueueItemRequest(uint&nbsp;queueItemId,&nbsp;int&nbsp;targetIdx)`](Sandbox.ModAPI.Ingame.MoveQueueItemRequest)|Moves an item in the queue to a target position in the queue.<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`bool&nbsp;CanUseBlueprint(MyDefinitionId&nbsp;blueprint)`](Sandbox.ModAPI.Ingame.CanUseBlueprint)|Can this production block produce this blueprint?<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`void&nbsp;AddQueueItem(MyDefinitionId&nbsp;blueprint,&nbsp;MyFixedPoint&nbsp;amount)`](Sandbox.ModAPI.Ingame.AddQueueItem)|Adds a blueprint to the production queue<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`void&nbsp;AddQueueItem(MyDefinitionId&nbsp;blueprint,&nbsp;decimal&nbsp;amount)`](Sandbox.ModAPI.Ingame.AddQueueItem)|Adds a blueprint to the production queue<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`void&nbsp;AddQueueItem(MyDefinitionId&nbsp;blueprint,&nbsp;double&nbsp;amount)`](Sandbox.ModAPI.Ingame.AddQueueItem)|Adds a blueprint to the production queue<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`void&nbsp;InsertQueueItem(int&nbsp;idx,&nbsp;MyDefinitionId&nbsp;blueprint,&nbsp;MyFixedPoint&nbsp;amount)`](Sandbox.ModAPI.Ingame.InsertQueueItem)|Inserts a blueprint into the production queue<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`void&nbsp;InsertQueueItem(int&nbsp;idx,&nbsp;MyDefinitionId&nbsp;blueprint,&nbsp;decimal&nbsp;amount)`](Sandbox.ModAPI.Ingame.InsertQueueItem)|Inserts a blueprint into the production queue<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`void&nbsp;InsertQueueItem(int&nbsp;idx,&nbsp;MyDefinitionId&nbsp;blueprint,&nbsp;double&nbsp;amount)`](Sandbox.ModAPI.Ingame.InsertQueueItem)|Inserts a blueprint into the production queue<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`void&nbsp;RemoveQueueItem(int&nbsp;idx,&nbsp;MyFixedPoint&nbsp;amount)`](Sandbox.ModAPI.Ingame.RemoveQueueItem)|Removes an item from the queue<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`void&nbsp;RemoveQueueItem(int&nbsp;idx,&nbsp;decimal&nbsp;amount)`](Sandbox.ModAPI.Ingame.RemoveQueueItem)|Removes an item from the queue<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`void&nbsp;RemoveQueueItem(int&nbsp;idx,&nbsp;double&nbsp;amount)`](Sandbox.ModAPI.Ingame.RemoveQueueItem)|Removes an item from the queue<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`void&nbsp;ClearQueue()`](Sandbox.ModAPI.Ingame.ClearQueue)|Clears the Queue<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
|[`void&nbsp;GetQueue(List<MyProductionItem>&nbsp;items)`](Sandbox.ModAPI.Ingame.GetQueue)|Gets the current production queue<br/><br/>_Inherited from [`IMyProductionBlock`](Sandbox.ModAPI.Ingame.IMyAssembler)_|
