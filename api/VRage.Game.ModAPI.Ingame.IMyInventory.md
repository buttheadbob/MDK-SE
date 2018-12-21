← [Index](index)
# IMyInventory Interface
**Namespace:** [`VRage.Game.ModAPI.Ingame`](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll  
### Properties
|Member|Description|
|---|---|
|[`bool IsFull`](VRage.Game.ModAPI.Ingame.IsFull)||
|[`VRageMath.Vector3 Size`](VRage.Game.ModAPI.Ingame.Size)||
|[`VRage.MyFixedPoint CurrentMass`](VRage.Game.ModAPI.Ingame.CurrentMass)||
|[`VRage.MyFixedPoint MaxVolume`](VRage.Game.ModAPI.Ingame.MaxVolume)||
|[`VRage.MyFixedPoint CurrentVolume`](VRage.Game.ModAPI.Ingame.CurrentVolume)||
|[`VRage.Game.ModAPI.Ingame.IMyInventoryOwner Owner`](VRage.Game.ModAPI.Ingame.Owner)||
### Methods
|Member|Description|
|---|---|
|[`bool IsItemAt(int)`](VRage.Game.ModAPI.Ingame.IsItemAt)||
|[`bool CanAddItemAmount(VRage.Game.ModAPI.Ingame.IMyInventoryItem, VRage.MyFixedPoint)`](VRage.Game.ModAPI.Ingame.CanAddItemAmount)||
|[`bool CanItemsBeAdded(VRage.MyFixedPoint, VRage.ObjectBuilders.SerializableDefinitionId)`](VRage.Game.ModAPI.Ingame.CanItemsBeAdded)||
|[`bool ContainItems(VRage.MyFixedPoint, VRage.Game.MyObjectBuilder_PhysicalObject)`](VRage.Game.ModAPI.Ingame.ContainItems)||
|[`VRage.MyFixedPoint GetItemAmount(VRage.ObjectBuilders.SerializableDefinitionId, VRage.Game.MyItemFlags)`](VRage.Game.ModAPI.Ingame.GetItemAmount)||
|[`bool TransferItemTo(VRage.Game.ModAPI.Ingame.IMyInventory, int, Nullable<System.Int32>, Nullable<System.Boolean>, Nullable<VRage.MyFixedPoint>)`](VRage.Game.ModAPI.Ingame.TransferItemTo)||
|[`bool TransferItemFrom(VRage.Game.ModAPI.Ingame.IMyInventory, int, Nullable<System.Int32>, Nullable<System.Boolean>, Nullable<VRage.MyFixedPoint>)`](VRage.Game.ModAPI.Ingame.TransferItemFrom)||
|[`bool TransferItemFrom(VRage.Game.ModAPI.Ingame.IMyInventory, VRage.Game.ModAPI.Ingame.IMyInventoryItem, VRage.MyFixedPoint)`](VRage.Game.ModAPI.Ingame.TransferItemFrom)||
|[`List<VRage.Game.ModAPI.Ingame.IMyInventoryItem> GetItems()`](VRage.Game.ModAPI.Ingame.GetItems)||
|[`VRage.Game.ModAPI.Ingame.IMyInventoryItem GetItemByID(uint)`](VRage.Game.ModAPI.Ingame.GetItemByID)||
|[`VRage.Game.ModAPI.Ingame.IMyInventoryItem FindItem(VRage.ObjectBuilders.SerializableDefinitionId)`](VRage.Game.ModAPI.Ingame.FindItem)||
|[`bool IsConnectedTo(VRage.Game.ModAPI.Ingame.IMyInventory)`](VRage.Game.ModAPI.Ingame.IsConnectedTo)||
