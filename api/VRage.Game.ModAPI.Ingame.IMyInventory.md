← [Index](index.md)
#IMyInventory Interface
**Namespace:** VRage.Game.ModAPI.Ingame  
**Assembly:** VRage.Game.dll  
###Properties
|Member|Description|
|---|---|
|[`bool IsFull`](VRage.Game.ModAPI.Ingame.IsFull.md)||
|[`Vector3 Size`](VRage.Game.ModAPI.Ingame.Size.md)||
|[`MyFixedPoint CurrentMass`](VRage.Game.ModAPI.Ingame.CurrentMass.md)||
|[`MyFixedPoint MaxVolume`](VRage.Game.ModAPI.Ingame.MaxVolume.md)||
|[`MyFixedPoint CurrentVolume`](VRage.Game.ModAPI.Ingame.CurrentVolume.md)||
|[`IMyInventoryOwner Owner`](VRage.Game.ModAPI.Ingame.Owner.md)||
###Methods
|Member|Description|
|---|---|
|[`bool IsItemAt(int position)`](VRage.Game.ModAPI.Ingame.IsItemAt.md)||
|[`bool CanAddItemAmount(IMyInventoryItem item, MyFixedPoint amount)`](VRage.Game.ModAPI.Ingame.CanAddItemAmount.md)||
|[`bool CanItemsBeAdded(MyFixedPoint amount, SerializableDefinitionId contentId)`](VRage.Game.ModAPI.Ingame.CanItemsBeAdded.md)||
|[`bool ContainItems(MyFixedPoint amount, MyObjectBuilder_PhysicalObject ob)`](VRage.Game.ModAPI.Ingame.ContainItems.md)||
|[`MyFixedPoint GetItemAmount(SerializableDefinitionId contentId, MyItemFlags flags)`](VRage.Game.ModAPI.Ingame.GetItemAmount.md)||
|[`bool TransferItemTo(IMyInventory dst, int sourceItemIndex, Nullable<int> targetItemIndex, Nullable<bool> stackIfPossible, Nullable<MyFixedPoint> amount)`](VRage.Game.ModAPI.Ingame.TransferItemTo.md)||
|[`bool TransferItemFrom(IMyInventory sourceInventory, int sourceItemIndex, Nullable<int> targetItemIndex, Nullable<bool> stackIfPossible, Nullable<MyFixedPoint> amount)`](VRage.Game.ModAPI.Ingame.TransferItemFrom.md)||
|[`bool TransferItemFrom(IMyInventory sourceInventory, IMyInventoryItem item, MyFixedPoint amount)`](VRage.Game.ModAPI.Ingame.TransferItemFrom.md)||
|[`List<IMyInventoryItem> GetItems()`](VRage.Game.ModAPI.Ingame.GetItems.md)||
|[`IMyInventoryItem GetItemByID(uint id)`](VRage.Game.ModAPI.Ingame.GetItemByID.md)||
|[`IMyInventoryItem FindItem(SerializableDefinitionId contentId)`](VRage.Game.ModAPI.Ingame.FindItem.md)||
|[`bool IsConnectedTo(IMyInventory dst)`](VRage.Game.ModAPI.Ingame.IsConnectedTo.md)||
