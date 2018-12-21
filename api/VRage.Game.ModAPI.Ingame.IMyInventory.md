← [Index](index)
# IMyInventory Interface
**Namespace:** [`VRage.Game.ModAPI.Ingame`](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll  
### Properties
|Member|Description|
|---|---|
|[`bool&nbsp;IsFull`](VRage.Game.ModAPI.Ingame.IsFull)||
|[`Vector3&nbsp;Size`](VRage.Game.ModAPI.Ingame.Size)||
|[`MyFixedPoint&nbsp;CurrentMass`](VRage.Game.ModAPI.Ingame.CurrentMass)||
|[`MyFixedPoint&nbsp;MaxVolume`](VRage.Game.ModAPI.Ingame.MaxVolume)||
|[`MyFixedPoint&nbsp;CurrentVolume`](VRage.Game.ModAPI.Ingame.CurrentVolume)||
|[`IMyInventoryOwner&nbsp;Owner`](VRage.Game.ModAPI.Ingame.Owner)||
### Methods
|Member|Description|
|---|---|
|[`bool&nbsp;IsItemAt(int&nbsp;position)`](VRage.Game.ModAPI.Ingame.IsItemAt)||
|[`bool&nbsp;CanAddItemAmount(IMyInventoryItem&nbsp;item,&nbsp;MyFixedPoint&nbsp;amount)`](VRage.Game.ModAPI.Ingame.CanAddItemAmount)||
|[`bool&nbsp;CanItemsBeAdded(MyFixedPoint&nbsp;amount,&nbsp;SerializableDefinitionId&nbsp;contentId)`](VRage.Game.ModAPI.Ingame.CanItemsBeAdded)||
|[`bool&nbsp;ContainItems(MyFixedPoint&nbsp;amount,&nbsp;MyObjectBuilder_PhysicalObject&nbsp;ob)`](VRage.Game.ModAPI.Ingame.ContainItems)||
|[`MyFixedPoint&nbsp;GetItemAmount(SerializableDefinitionId&nbsp;contentId,&nbsp;MyItemFlags&nbsp;flags)`](VRage.Game.ModAPI.Ingame.GetItemAmount)||
|[`bool&nbsp;TransferItemTo(IMyInventory&nbsp;dst,&nbsp;int&nbsp;sourceItemIndex,&nbsp;Nullable<int>&nbsp;targetItemIndex,&nbsp;Nullable<bool>&nbsp;stackIfPossible,&nbsp;Nullable<MyFixedPoint>&nbsp;amount)`](VRage.Game.ModAPI.Ingame.TransferItemTo)||
|[`bool&nbsp;TransferItemFrom(IMyInventory&nbsp;sourceInventory,&nbsp;int&nbsp;sourceItemIndex,&nbsp;Nullable<int>&nbsp;targetItemIndex,&nbsp;Nullable<bool>&nbsp;stackIfPossible,&nbsp;Nullable<MyFixedPoint>&nbsp;amount)`](VRage.Game.ModAPI.Ingame.TransferItemFrom)||
|[`bool&nbsp;TransferItemFrom(IMyInventory&nbsp;sourceInventory,&nbsp;IMyInventoryItem&nbsp;item,&nbsp;MyFixedPoint&nbsp;amount)`](VRage.Game.ModAPI.Ingame.TransferItemFrom)||
|[`List<IMyInventoryItem>&nbsp;GetItems()`](VRage.Game.ModAPI.Ingame.GetItems)||
|[`IMyInventoryItem&nbsp;GetItemByID(uint&nbsp;id)`](VRage.Game.ModAPI.Ingame.GetItemByID)||
|[`IMyInventoryItem&nbsp;FindItem(SerializableDefinitionId&nbsp;contentId)`](VRage.Game.ModAPI.Ingame.FindItem)||
|[`bool&nbsp;IsConnectedTo(IMyInventory&nbsp;dst)`](VRage.Game.ModAPI.Ingame.IsConnectedTo)||
