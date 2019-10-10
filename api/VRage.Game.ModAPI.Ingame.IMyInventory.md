← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### IMyInventory Interface

```csharp
public interface IMyInventory
```

**Namespace:** [VRage.Game.ModAPI.Ingame](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll

#### Properties

|Member|Description|
|---|---|
|[Owner](VRage.Game.ModAPI.Ingame.IMyInventory.Owner)|Returns entity this inventory belongs to.|
|[IsFull](VRage.Game.ModAPI.Ingame.IMyInventory.IsFull)|Determines if inventory is absolutely full.|
|[CurrentMass](VRage.Game.ModAPI.Ingame.IMyInventory.CurrentMass)|Returns total mass of items inside this inventory in Kg.|
|[MaxVolume](VRage.Game.ModAPI.Ingame.IMyInventory.MaxVolume)|Returns maximum volume of items this inventory can contain in m^3.|
|[CurrentVolume](VRage.Game.ModAPI.Ingame.IMyInventory.CurrentVolume)|Returns total volume of items inside this inventory in m^3.|
|[ItemCount](VRage.Game.ModAPI.Ingame.IMyInventory.ItemCount)|Returns number of occupied inventory slots.|

#### Methods

|Member|Description|
|---|---|
|[IsItemAt(int)](VRage.Game.ModAPI.Ingame.IMyInventory.IsItemAt)|Determines if there is any item on given inventory slot.|
|[GetItemAmount(MyItemType)](VRage.Game.ModAPI.Ingame.IMyInventory.GetItemAmount)|Sums up total amount of items of given type contained inside this inventory.|
|[ContainItems(MyFixedPoint, MyItemType)](VRage.Game.ModAPI.Ingame.IMyInventory.ContainItems)|Determines if there is at least given amount of items of given type contained inside this inventory.|
|[GetItemAt(int)](VRage.Game.ModAPI.Ingame.IMyInventory.GetItemAt)|Returns info about item at give position.|
|[GetItemByID(uint)](VRage.Game.ModAPI.Ingame.IMyInventory.GetItemByID)|Returns info about item contained inside this inventory.|
|[FindItem(MyItemType)](VRage.Game.ModAPI.Ingame.IMyInventory.FindItem)|Tries to find an item of given type inside this inventory.|
|[CanItemsBeAdded(MyFixedPoint, MyItemType)](VRage.Game.ModAPI.Ingame.IMyInventory.CanItemsBeAdded)|Determines if given amount of items fits into this inventory on top of existing items.|
|[GetItems(List, Func)](VRage.Game.ModAPI.Ingame.IMyInventory.GetItems)|Collects all items present inside this inventory and returns snapshot of the current inventory state.|
|[TransferItemTo(IMyInventory, MyInventoryItem, MyFixedPoint?)](VRage.Game.ModAPI.Ingame.IMyInventory.TransferItemTo)|Attempts to transfer item from one inventory to another.|
|[TransferItemFrom(IMyInventory, MyInventoryItem, MyFixedPoint?)](VRage.Game.ModAPI.Ingame.IMyInventory.TransferItemFrom)|Attempts to transfer item from one inventory to another.|
|[TransferItemTo(IMyInventory, int, int?, bool?, MyFixedPoint?)](VRage.Game.ModAPI.Ingame.IMyInventory.TransferItemTo)|Attempts to transfer item from one inventory to another.|
|[TransferItemFrom(IMyInventory, int, int?, bool?, MyFixedPoint?)](VRage.Game.ModAPI.Ingame.IMyInventory.TransferItemFrom)|Attempts to transfer item from one inventory to another.|
|[IsConnectedTo(IMyInventory)](VRage.Game.ModAPI.Ingame.IMyInventory.IsConnectedTo)|Checks if two inventories are connected.|
|[CanTransferItemTo(IMyInventory, MyItemType)](VRage.Game.ModAPI.Ingame.IMyInventory.CanTransferItemTo)|Determines if there is working conveyor connection for item of give type to be transferred to other inventory.|
|[GetAcceptedItems(List, Func)](VRage.Game.ModAPI.Ingame.IMyInventory.GetAcceptedItems)|Returns all items this inventory accepts.|

