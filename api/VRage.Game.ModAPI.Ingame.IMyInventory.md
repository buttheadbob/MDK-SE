← [Index](index.md)
# IMyInventory Interface
**Namespace:** VRage.Game.ModAPI.Ingame  
**Assembly:** VRage.Game.dll  
### Properties
|Member|Description|
|---|---|
|[`bool IsFull`](VRage.Game.ModAPI.Ingame.IsFull)||
|[`Vector3 Size`](VRage.Game.ModAPI.Ingame.Size)||
|[`MyFixedPoint CurrentMass`](VRage.Game.ModAPI.Ingame.CurrentMass)||
|[`MyFixedPoint MaxVolume`](VRage.Game.ModAPI.Ingame.MaxVolume)||
|[`MyFixedPoint CurrentVolume`](VRage.Game.ModAPI.Ingame.CurrentVolume)||
|[`IMyInventoryOwner Owner`](VRage.Game.ModAPI.Ingame.Owner)||
### Methods
|Member|Description|
|---|---|
|[`bool IsItemAt(int position)`](VRage.Game.ModAPI.Ingame.IsItemAt)||
|[`bool CanAddItemAmount(IMyInventoryItem item, MyFixedPoint amount)`](VRage.Game.ModAPI.Ingame.CanAddItemAmount)||
|[`bool CanItemsBeAdded(MyFixedPoint amount, SerializableDefinitionId contentId)`](VRage.Game.ModAPI.Ingame.CanItemsBeAdded)||
|[`bool ContainItems(MyFixedPoint amount, MyObjectBuilder_PhysicalObject ob)`](VRage.Game.ModAPI.Ingame.ContainItems)||
|[`MyFixedPoint GetItemAmount(SerializableDefinitionId contentId, MyItemFlags flags)`](VRage.Game.ModAPI.Ingame.GetItemAmount)||
|[`bool TransferItemTo(IMyInventory dst, int sourceItemIndex, Nullable<int> targetItemIndex, Nullable<bool> stackIfPossible, Nullable<MyFixedPoint> amount)`](VRage.Game.ModAPI.Ingame.TransferItemTo)||
|[`bool TransferItemFrom(IMyInventory sourceInventory, int sourceItemIndex, Nullable<int> targetItemIndex, Nullable<bool> stackIfPossible, Nullable<MyFixedPoint> amount)`](VRage.Game.ModAPI.Ingame.TransferItemFrom)||
|[`bool TransferItemFrom(IMyInventory sourceInventory, IMyInventoryItem item, MyFixedPoint amount)`](VRage.Game.ModAPI.Ingame.TransferItemFrom)||
|[`List<IMyInventoryItem> GetItems()`](VRage.Game.ModAPI.Ingame.GetItems)||
|[`IMyInventoryItem GetItemByID(uint id)`](VRage.Game.ModAPI.Ingame.GetItemByID)||
|[`IMyInventoryItem FindItem(SerializableDefinitionId contentId)`](VRage.Game.ModAPI.Ingame.FindItem)||
|[`bool IsConnectedTo(IMyInventory dst)`](VRage.Game.ModAPI.Ingame.IsConnectedTo)||
