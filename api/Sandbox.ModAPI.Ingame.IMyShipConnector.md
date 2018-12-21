← [Index](index)
# IMyShipConnector Interface
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
|[`bool&nbsp;ThrowOut`](Sandbox.ModAPI.Ingame.ThrowOut)|Gets or sets whether this connector should throw out anything placed in its inventory.|
|[`bool&nbsp;CollectAll`](Sandbox.ModAPI.Ingame.CollectAll)|Gets or sets whether this connector should be pulling items into its inventory.|
|[`float&nbsp;PullStrength`](Sandbox.ModAPI.Ingame.PullStrength)|Gets or sets the currently configured strength of the pull when the connector is within range of another.|
|[`bool&nbsp;IsLocked`](Sandbox.ModAPI.Ingame.IsLocked)||
|[`bool&nbsp;IsConnected`](Sandbox.ModAPI.Ingame.IsConnected)||
|[`MyShipConnectorStatus&nbsp;Status`](Sandbox.ModAPI.Ingame.Status)|Determines the current status of the connector.|
|[`IMyShipConnector&nbsp;OtherConnector`](Sandbox.ModAPI.Ingame.OtherConnector)|Gets the connector this one is connected to when [MyShipConnectorStatus Status](Sandbox.ModAPI.Ingame.Status) is `ConnectorStatus.Connected` .|
|[`MyEntityComponentContainer&nbsp;Components`](VRage.Game.ModAPI.Ingame.Components)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`long&nbsp;EntityId`](VRage.Game.ModAPI.Ingame.EntityId)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`string&nbsp;Name`](VRage.Game.ModAPI.Ingame.Name)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`string&nbsp;DisplayName`](VRage.Game.ModAPI.Ingame.DisplayName)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`bool&nbsp;HasInventory`](VRage.Game.ModAPI.Ingame.HasInventory)|Returns true if this entity has got at least one inventory. Note that one aggregate inventory can contain zero simple inventories => zero will be returned even if GetInventory() != null.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`int&nbsp;InventoryCount`](VRage.Game.ModAPI.Ingame.InventoryCount)|Returns the count of the number of inventories this entity has.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`BoundingBoxD&nbsp;WorldAABB`](VRage.Game.ModAPI.Ingame.WorldAABB)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`BoundingBoxD&nbsp;WorldAABBHr`](VRage.Game.ModAPI.Ingame.WorldAABBHr)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`MatrixD&nbsp;WorldMatrix`](VRage.Game.ModAPI.Ingame.WorldMatrix)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`BoundingSphereD&nbsp;WorldVolume`](VRage.Game.ModAPI.Ingame.WorldVolume)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`BoundingSphereD&nbsp;WorldVolumeHr`](VRage.Game.ModAPI.Ingame.WorldVolumeHr)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`SerializableDefinitionId&nbsp;BlockDefinition`](VRage.Game.ModAPI.Ingame.BlockDefinition)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`bool&nbsp;CheckConnectionAllowed`](VRage.Game.ModAPI.Ingame.CheckConnectionAllowed)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`IMyCubeGrid&nbsp;CubeGrid`](VRage.Game.ModAPI.Ingame.CubeGrid)|Grid in which the block is placed<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`string&nbsp;DefinitionDisplayNameText`](VRage.Game.ModAPI.Ingame.DefinitionDisplayNameText)|Definition name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`float&nbsp;DisassembleRatio`](VRage.Game.ModAPI.Ingame.DisassembleRatio)|Is set in definition Ratio at which is the block disassembled (grinding)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`string&nbsp;DisplayNameText`](VRage.Game.ModAPI.Ingame.DisplayNameText)|Translated block name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`bool&nbsp;IsBeingHacked`](VRage.Game.ModAPI.Ingame.IsBeingHacked)|Hacking of the block is in progress<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`bool&nbsp;IsFunctional`](VRage.Game.ModAPI.Ingame.IsFunctional)|True if integrity is above breaking threshold<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`bool&nbsp;IsWorking`](VRage.Game.ModAPI.Ingame.IsWorking)|True if block is able to do its work depening on block type (is functional, powered, enabled, etc...)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`Vector3I&nbsp;Max`](VRage.Game.ModAPI.Ingame.Max)|Maximum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`float&nbsp;Mass`](VRage.Game.ModAPI.Ingame.Mass)|Block mass<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`Vector3I&nbsp;Min`](VRage.Game.ModAPI.Ingame.Min)|Minimum coordinates of grid cells occupied by this block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`int&nbsp;NumberInGrid`](VRage.Game.ModAPI.Ingame.NumberInGrid)|Order in which were the blocks of same type added to grid Used in default display name<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`MyBlockOrientation&nbsp;Orientation`](VRage.Game.ModAPI.Ingame.Orientation)|Returns block orientation in base 6 directions<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`long&nbsp;OwnerId`](VRage.Game.ModAPI.Ingame.OwnerId)|Id of player owning block (not steam Id)<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`Vector3I&nbsp;Position`](VRage.Game.ModAPI.Ingame.Position)|Position in grid coordinates<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`string&nbsp;CustomName`](Sandbox.ModAPI.Ingame.CustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`string&nbsp;CustomNameWithFaction`](Sandbox.ModAPI.Ingame.CustomNameWithFaction)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`string&nbsp;DetailedInfo`](Sandbox.ModAPI.Ingame.DetailedInfo)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`string&nbsp;CustomInfo`](Sandbox.ModAPI.Ingame.CustomInfo)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`string&nbsp;CustomData`](Sandbox.ModAPI.Ingame.CustomData)|Gets or sets the Custom Data string. NOTE: Only use this for user input. For storing large mod configs, create your own MyModStorageComponent<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`bool&nbsp;ShowOnHUD`](Sandbox.ModAPI.Ingame.ShowOnHUD)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`bool&nbsp;ShowInTerminal`](Sandbox.ModAPI.Ingame.ShowInTerminal)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`bool&nbsp;ShowInToolbarConfig`](Sandbox.ModAPI.Ingame.ShowInToolbarConfig)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`bool&nbsp;ShowInInventory`](Sandbox.ModAPI.Ingame.ShowInInventory)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`bool&nbsp;Enabled`](Sandbox.ModAPI.Ingame.Enabled)|_Inherited from [`IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
### Methods
|Member|Description|
|---|---|
|[`void&nbsp;Connect()`](Sandbox.ModAPI.Ingame.Connect)|Attempts to connect. If [MyShipConnectorStatus Status](Sandbox.ModAPI.Ingame.Status) is anything else but `ConnectorStatus.Connectable` , this method does nothing.|
|[`void&nbsp;Disconnect()`](Sandbox.ModAPI.Ingame.Disconnect)|Disconnects this connector.|
|[`void&nbsp;ToggleConnect()`](Sandbox.ModAPI.Ingame.ToggleConnect)|Toggles between `ConnectorStatus.Connected` and `ConnectorStatus.Unconnected` , depending on the current status. Another connector must be in range for this method to have any effect.|
|[`IMyInventory&nbsp;GetInventory()`](VRage.Game.ModAPI.Ingame.GetInventory)|Simply get the MyInventoryBase component stored in this entity.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`IMyInventory&nbsp;GetInventory(int&nbsp;index)`](VRage.Game.ModAPI.Ingame.GetInventory)|Search for inventory component with maching index.<br/><br/>_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`Vector3D&nbsp;GetPosition()`](VRage.Game.ModAPI.Ingame.GetPosition)|_Inherited from [`IMyEntity`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`string&nbsp;GetOwnerFactionTag()`](VRage.Game.ModAPI.Ingame.GetOwnerFactionTag)|Tag of faction owning block<br/><br/>_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`MyRelationsBetweenPlayerAndBlock&nbsp;GetPlayerRelationToOwner()`](VRage.Game.ModAPI.Ingame.GetPlayerRelationToOwner)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`MyRelationsBetweenPlayerAndBlock&nbsp;GetUserRelationToOwner(long&nbsp;playerId)`](VRage.Game.ModAPI.Ingame.GetUserRelationToOwner)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`void&nbsp;UpdateIsWorking()`](VRage.Game.ModAPI.Ingame.UpdateIsWorking)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`void&nbsp;UpdateVisual()`](VRage.Game.ModAPI.Ingame.UpdateVisual)|_Inherited from [`IMyCubeBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`bool&nbsp;HasLocalPlayerAccess()`](Sandbox.ModAPI.Ingame.HasLocalPlayerAccess)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`bool&nbsp;HasPlayerAccess(long&nbsp;playerId)`](Sandbox.ModAPI.Ingame.HasPlayerAccess)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`void&nbsp;SetCustomName(string&nbsp;text)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`void&nbsp;SetCustomName(StringBuilder&nbsp;text)`](Sandbox.ModAPI.Ingame.SetCustomName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`void&nbsp;GetActions(List<ITerminalAction>&nbsp;resultList,&nbsp;Func<ITerminalAction,&nbsp;bool>&nbsp;collect)`](Sandbox.ModAPI.Ingame.GetActions)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`void&nbsp;SearchActionsOfName(string&nbsp;name,&nbsp;List<ITerminalAction>&nbsp;resultList,&nbsp;Func<ITerminalAction,&nbsp;bool>&nbsp;collect)`](Sandbox.ModAPI.Ingame.SearchActionsOfName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`ITerminalAction&nbsp;GetActionWithName(string&nbsp;name)`](Sandbox.ModAPI.Ingame.GetActionWithName)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`ITerminalProperty&nbsp;GetProperty(string&nbsp;id)`](Sandbox.ModAPI.Ingame.GetProperty)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`void&nbsp;GetProperties(List<ITerminalProperty>&nbsp;resultList,&nbsp;Func<ITerminalProperty,&nbsp;bool>&nbsp;collect)`](Sandbox.ModAPI.Ingame.GetProperties)|_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`bool&nbsp;IsSameConstructAs(IMyTerminalBlock&nbsp;other)`](Sandbox.ModAPI.Ingame.IsSameConstructAs)|Determines whether this block is mechanically connected to the other. This is any block connected with rotors or pistons or other mechanical devices, but not things like connectors. This will in most cases constitute your complete construct.<br/>Be aware that using merge blocks combines grids into one, so this function will not filter out grids connected that way. Also be aware that detaching the heads of pistons and rotors will cause this connection to change.<br/><br/>_Inherited from [`IMyTerminalBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
|[`void&nbsp;RequestEnable(bool&nbsp;enable)`](Sandbox.ModAPI.Ingame.RequestEnable)|_Inherited from [`IMyFunctionalBlock`](Sandbox.ModAPI.Ingame.IMyShipConnector)_|
