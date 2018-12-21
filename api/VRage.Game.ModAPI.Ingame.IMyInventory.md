← [Index](index)
# IMyInventory Interface
**Namespace:** [`VRage.Game.ModAPI.Ingame`](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll  
### Properties
<table style="width: 100%">
<tr><td>[`bool IsFull`](VRage.Game.ModAPI.Ingame.IsFull)</td><td></td></tr>
<tr><td>[`Vector3 Size`](VRage.Game.ModAPI.Ingame.Size)</td><td></td></tr>
<tr><td>[`MyFixedPoint CurrentMass`](VRage.Game.ModAPI.Ingame.CurrentMass)</td><td></td></tr>
<tr><td>[`MyFixedPoint MaxVolume`](VRage.Game.ModAPI.Ingame.MaxVolume)</td><td></td></tr>
<tr><td>[`MyFixedPoint CurrentVolume`](VRage.Game.ModAPI.Ingame.CurrentVolume)</td><td></td></tr>
<tr><td>[`IMyInventoryOwner Owner`](VRage.Game.ModAPI.Ingame.Owner)</td><td></td></tr>
</table>
### Methods
<table style="width: 100%">
<tr><td>[`bool IsItemAt(int position)`](VRage.Game.ModAPI.Ingame.IsItemAt)</td><td></td></tr>
<tr><td>[`bool CanAddItemAmount(IMyInventoryItem item, MyFixedPoint amount)`](VRage.Game.ModAPI.Ingame.CanAddItemAmount)</td><td></td></tr>
<tr><td>[`bool CanItemsBeAdded(MyFixedPoint amount, SerializableDefinitionId contentId)`](VRage.Game.ModAPI.Ingame.CanItemsBeAdded)</td><td></td></tr>
<tr><td>[`bool ContainItems(MyFixedPoint amount, MyObjectBuilder_PhysicalObject ob)`](VRage.Game.ModAPI.Ingame.ContainItems)</td><td></td></tr>
<tr><td>[`MyFixedPoint GetItemAmount(SerializableDefinitionId contentId, MyItemFlags flags)`](VRage.Game.ModAPI.Ingame.GetItemAmount)</td><td></td></tr>
<tr><td>[`bool TransferItemTo(IMyInventory dst, int sourceItemIndex, Nullable<int> targetItemIndex, Nullable<bool> stackIfPossible, Nullable<MyFixedPoint> amount)`](VRage.Game.ModAPI.Ingame.TransferItemTo)</td><td></td></tr>
<tr><td>[`bool TransferItemFrom(IMyInventory sourceInventory, int sourceItemIndex, Nullable<int> targetItemIndex, Nullable<bool> stackIfPossible, Nullable<MyFixedPoint> amount)`](VRage.Game.ModAPI.Ingame.TransferItemFrom)</td><td></td></tr>
<tr><td>[`bool TransferItemFrom(IMyInventory sourceInventory, IMyInventoryItem item, MyFixedPoint amount)`](VRage.Game.ModAPI.Ingame.TransferItemFrom)</td><td></td></tr>
<tr><td>[`List<IMyInventoryItem> GetItems()`](VRage.Game.ModAPI.Ingame.GetItems)</td><td></td></tr>
<tr><td>[`IMyInventoryItem GetItemByID(uint id)`](VRage.Game.ModAPI.Ingame.GetItemByID)</td><td></td></tr>
<tr><td>[`IMyInventoryItem FindItem(SerializableDefinitionId contentId)`](VRage.Game.ModAPI.Ingame.FindItem)</td><td></td></tr>
<tr><td>[`bool IsConnectedTo(IMyInventory dst)`](VRage.Game.ModAPI.Ingame.IsConnectedTo)</td><td></td></tr>
</table>
