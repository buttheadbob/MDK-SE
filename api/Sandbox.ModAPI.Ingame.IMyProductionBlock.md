← [Index](index)
# IMyProductionBlock Interface
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
**Implements:**
* [`Sandbox.ModAPI.Ingame.IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyFunctionalBlock)
* [`Sandbox.ModAPI.Ingame.IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyTerminalBlock)
* [`VRage.Game.ModAPI.Ingame.IMyCubeBlock`](VRage.Game.ModAPI.Ingame.IMyCubeBlock)
* [`VRage.Game.ModAPI.Ingame.IMyEntity`](VRage.Game.ModAPI.Ingame.IMyEntity)
### Properties
<table style="width: 100%">
<tr><td>[`IMyInventory InputInventory`](Sandbox.ModAPI.Ingame.InputInventory)</td><td>Gets the input inventory.</td></tr>
<tr><td>[`IMyInventory OutputInventory`](Sandbox.ModAPI.Ingame.OutputInventory)</td><td>Gets the output inventory.</td></tr>
<tr><td>[`bool IsProducing`](Sandbox.ModAPI.Ingame.IsProducing)</td><td>The device is currently producing.</td></tr>
<tr><td>[`bool IsQueueEmpty`](Sandbox.ModAPI.Ingame.IsQueueEmpty)</td><td>The production queue is empty.</td></tr>
<tr><td>[`uint NextItemId`](Sandbox.ModAPI.Ingame.NextItemId)</td><td>Gets the queue item ID of the next item to be produced.</td></tr>
<tr><td>[`bool UseConveyorSystem`](Sandbox.ModAPI.Ingame.UseConveyorSystem)</td><td>Gets or sets whether this device should use the conveyor system to retrieve and store items.</td></tr>
<tr><td>[`MyEntityComponentContainer Components`](VRage.Game.ModAPI.Ingame.Components)</td><td>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`long EntityId`](VRage.Game.ModAPI.Ingame.EntityId)</td><td>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`string Name`](VRage.Game.ModAPI.Ingame.Name)</td><td>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`string DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)</td><td>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`bool HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)</td><td>Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`int InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)</td><td>Returns the count of the number of inventories this entity has.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`BoundingBoxD WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)</td><td>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`BoundingBoxD WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)</td><td>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`MatrixD WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)</td><td>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`BoundingSphereD WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)</td><td>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`BoundingSphereD WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)</td><td>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`SerializableDefinitionId BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition)</td><td>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`bool CheckConnectionAllowed`](VRage.Game.ModAPI.Ingame.CheckConnectionAllowed)</td><td>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`IMyCubeGrid CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid)</td><td>Grid in which the block is placed<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`string DefinitionDisplayNameText`](VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText)</td><td>Definition name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`float DisassembleRatio`](VRage.Game.ModAPI.Ingame.DisassembleRatio)</td><td>Is set in definition Ratio at which is the block disassembled (grinding)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`string DisplayNameText`](VRage.Game.ModAPI.Ingame.DisplayNameText)</td><td>Translated block name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`bool IsBeingHacked`](VRage.Game.ModAPI.Ingame.IsBeingHacked)</td><td>Hacking of the block is in progress<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`bool IsFunctional`](VRage.Game.ModAPI.Ingame.IsFunctional)</td><td>True if integrity is above breaking threshold<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`bool IsWorking`](VRage.Game.ModAPI.Ingame.IsWorking)</td><td>True if block is able to do its work depening on block type (is functional, powered, enabled, etc...)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`Vector3I Max`](VRage.Game.ModAPI.Ingame.Max)</td><td>Maximum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`float Mass`](VRage.Game.ModAPI.Ingame.Mass)</td><td>Block mass<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`Vector3I Min`](VRage.Game.ModAPI.Ingame.Min)</td><td>Minimum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`int NumberInGrid`](VRage.Game.ModAPI.Ingame.NumberInGrid)</td><td>Order in which were the blocks of same type added to grid Used in default display name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`MyBlockOrientation Orientation`](VRage.Game.ModAPI.Ingame.Orientation)</td><td>Returns block orientation in base 6 directions<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`long OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId)</td><td>Id of player owning block (not steam Id)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`Vector3I Position`](VRage.Game.ModAPI.Ingame.Position)</td><td>Position in grid coordinates<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`string CustomName`](Sandbox.ModAPI.Ingame.CustomName)</td><td>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`string CustomNameWithFaction`](Sandbox.ModAPI.Ingame.CustomNameWithFaction)</td><td>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`string DetailedInfo`](Sandbox.ModAPI.Ingame.DetailedInfo)</td><td>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`string CustomInfo`](Sandbox.ModAPI.Ingame.CustomInfo)</td><td>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`string CustomData`](Sandbox.ModAPI.Ingame.CustomData)</td><td>Gets or sets the Custom Data string. NOTE: Only use this for user input. For storing large mod configs, create your own MyModStorageComponent<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`bool ShowOnHUD`](Sandbox.ModAPI.Ingame.ShowOnHUD)</td><td>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`bool ShowInTerminal`](Sandbox.ModAPI.Ingame.ShowInTerminal)</td><td>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`bool ShowInToolbarConfig`](Sandbox.ModAPI.Ingame.ShowInToolbarConfig)</td><td>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`bool ShowInInventory`](Sandbox.ModAPI.Ingame.ShowInInventory)</td><td>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`bool Enabled`](Sandbox.ModAPI.Ingame.Enabled)</td><td>_Inherited from [`IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
</table>
### Methods
<table style="width: 100%">
<tr><td>[`void MoveQueueItemRequest(uint queueItemId, int targetIdx)`](Sandbox.ModAPI.Ingame.MoveQueueItemRequest)</td><td>Moves an item in the queue to a target position in the queue.</td></tr>
<tr><td>[`bool CanUseBlueprint(MyDefinitionId blueprint)`](Sandbox.ModAPI.Ingame.CanUseBlueprint)</td><td>Can this production block produce this blueprint?</td></tr>
<tr><td>[`void AddQueueItem(MyDefinitionId blueprint, MyFixedPoint amount)`](Sandbox.ModAPI.Ingame.AddQueueItem)</td><td>Adds a blueprint to the production queue</td></tr>
<tr><td>[`void AddQueueItem(MyDefinitionId blueprint, decimal amount)`](Sandbox.ModAPI.Ingame.AddQueueItem)</td><td>Adds a blueprint to the production queue</td></tr>
<tr><td>[`void AddQueueItem(MyDefinitionId blueprint, double amount)`](Sandbox.ModAPI.Ingame.AddQueueItem)</td><td>Adds a blueprint to the production queue</td></tr>
<tr><td>[`void InsertQueueItem(int idx, MyDefinitionId blueprint, MyFixedPoint amount)`](Sandbox.ModAPI.Ingame.InsertQueueItem)</td><td>Inserts a blueprint into the production queue</td></tr>
<tr><td>[`void InsertQueueItem(int idx, MyDefinitionId blueprint, decimal amount)`](Sandbox.ModAPI.Ingame.InsertQueueItem)</td><td>Inserts a blueprint into the production queue</td></tr>
<tr><td>[`void InsertQueueItem(int idx, MyDefinitionId blueprint, double amount)`](Sandbox.ModAPI.Ingame.InsertQueueItem)</td><td>Inserts a blueprint into the production queue</td></tr>
<tr><td>[`void RemoveQueueItem(int idx, MyFixedPoint amount)`](Sandbox.ModAPI.Ingame.RemoveQueueItem)</td><td>Removes an item from the queue</td></tr>
<tr><td>[`void RemoveQueueItem(int idx, decimal amount)`](Sandbox.ModAPI.Ingame.RemoveQueueItem)</td><td>Removes an item from the queue</td></tr>
<tr><td>[`void RemoveQueueItem(int idx, double amount)`](Sandbox.ModAPI.Ingame.RemoveQueueItem)</td><td>Removes an item from the queue</td></tr>
<tr><td>[`void ClearQueue()`](Sandbox.ModAPI.Ingame.ClearQueue)</td><td>Clears the Queue</td></tr>
<tr><td>[`void GetQueue(List<MyProductionItem> items)`](Sandbox.ModAPI.Ingame.GetQueue)</td><td>Gets the current production queue</td></tr>
<tr><td>[`IMyInventory GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)</td><td>Simply get the MyInventoryBase component stored in this entity.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`IMyInventory GetInventory(int index)`](VRage.Game.ModAPI.Ingame.GetInventory)</td><td>Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`Vector3D GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)</td><td>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`string GetOwnerFactionTag()`](VRage.Game.ModAPI.Ingame.GetOwnerFactionTag)</td><td>Tag of faction owning block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`MyRelationsBetweenPlayerAndBlock GetPlayerRelationToOwner()`](VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner)</td><td>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`MyRelationsBetweenPlayerAndBlock GetUserRelationToOwner(long playerId)`](VRage.Game.ModAPI.Ingame.GetUserRelationToOwner)</td><td>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`void UpdateIsWorking()`](VRage.Game.ModAPI.Ingame.UpdateIsWorking)</td><td>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`void UpdateVisual()`](VRage.Game.ModAPI.Ingame.UpdateVisual)</td><td>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`bool HasLocalPlayerAccess()`](Sandbox.ModAPI.Ingame.HasLocalPlayerAccess)</td><td>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`bool HasPlayerAccess(long playerId)`](Sandbox.ModAPI.Ingame.HasPlayerAccess)</td><td>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`void SetCustomName(string text)`](Sandbox.ModAPI.Ingame.SetCustomName)</td><td>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`void SetCustomName(StringBuilder text)`](Sandbox.ModAPI.Ingame.SetCustomName)</td><td>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`void GetActions(List<ITerminalAction> resultList, Func<ITerminalAction, bool> collect)`](Sandbox.ModAPI.Ingame.GetActions)</td><td>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`void SearchActionsOfName(string name, List<ITerminalAction> resultList, Func<ITerminalAction, bool> collect)`](Sandbox.ModAPI.Ingame.SearchActionsOfName)</td><td>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`ITerminalAction GetActionWithName(string name)`](Sandbox.ModAPI.Ingame.GetActionWithName)</td><td>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`ITerminalProperty GetProperty(string id)`](Sandbox.ModAPI.Ingame.GetProperty)</td><td>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`void GetProperties(List<ITerminalProperty> resultList, Func<ITerminalProperty, bool> collect)`](Sandbox.ModAPI.Ingame.GetProperties)</td><td>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`bool IsSameConstructAs(IMyTerminalBlock other)`](Sandbox.ModAPI.Ingame.IsSameConstructAs)</td><td>Determines whether this block is mechanically connected to the other. This is any block connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
<tr><td>[`void RequestEnable(bool enable)`](Sandbox.ModAPI.Ingame.RequestEnable)</td><td>_Inherited from [`IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyProductionBlock)_</td></tr>
</table>
