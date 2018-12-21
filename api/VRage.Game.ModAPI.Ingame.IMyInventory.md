← [Index](index)
# IMyInventory Interface
**Namespace:** [`VRage.Game.ModAPI.Ingame`](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll  
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.IsFull"><code>bool IsFull</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Size"><code>Vector3 Size</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.CurrentMass"><code>MyFixedPoint CurrentMass</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.MaxVolume"><code>MyFixedPoint MaxVolume</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.CurrentVolume"><code>MyFixedPoint CurrentVolume</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Owner"><code>IMyInventoryOwner Owner</code></a>_</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.IsItemAt"><code>bool IsItemAt(int position)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.CanAddItemAmount"><code>bool CanAddItemAmount(IMyInventoryItem item, MyFixedPoint amount)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.CanItemsBeAdded"><code>bool CanItemsBeAdded(MyFixedPoint amount, SerializableDefinitionId contentId)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.ContainItems"><code>bool ContainItems(MyFixedPoint amount, MyObjectBuilder_PhysicalObject ob)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetItemAmount"><code>MyFixedPoint GetItemAmount(SerializableDefinitionId contentId, MyItemFlags flags)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.TransferItemTo"><code>bool TransferItemTo(IMyInventory dst, int sourceItemIndex, Nullable<int> targetItemIndex, Nullable<bool> stackIfPossible, Nullable<MyFixedPoint> amount)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.TransferItemFrom"><code>bool TransferItemFrom(IMyInventory sourceInventory, int sourceItemIndex, Nullable<int> targetItemIndex, Nullable<bool> stackIfPossible, Nullable<MyFixedPoint> amount)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.TransferItemFrom"><code>bool TransferItemFrom(IMyInventory sourceInventory, IMyInventoryItem item, MyFixedPoint amount)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetItems"><code>List<IMyInventoryItem> GetItems()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.GetItemByID"><code>IMyInventoryItem GetItemByID(uint id)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.FindItem"><code>IMyInventoryItem FindItem(SerializableDefinitionId contentId)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.IsConnectedTo"><code>bool IsConnectedTo(IMyInventory dst)</code></a>_</td><td></td></tr>
</table>
