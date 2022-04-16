← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### IMyInventory Interface

```csharp
public interface IMyInventory
```

Describes inventory interface (PB scripting interface)

**Namespace:** [VRage.Game.ModAPI.Ingame](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll

#### Properties

|Member|Description|
|---|---|
|\\%1MyFixedPoint CurrentMass { get; }](VRage.Game.ModAPI.Ingame.IMyInventory.CurrentMass)|Returns total mass of items inside this inventory in Kg.|
|\\%1MyFixedPoint CurrentVolume { get; }](VRage.Game.ModAPI.Ingame.IMyInventory.CurrentVolume)|Returns total volume of items inside this inventory in m^3.|
|\\%1bool IsFull { get; }](VRage.Game.ModAPI.Ingame.IMyInventory.IsFull)|Determines if inventory is absolutely full.|
|\\%1int ItemCount { get; }](VRage.Game.ModAPI.Ingame.IMyInventory.ItemCount)|Returns number of occupied inventory slots.|
|\\%1MyFixedPoint MaxVolume { get; }](VRage.Game.ModAPI.Ingame.IMyInventory.MaxVolume)|Returns maximum volume of items this inventory can contain in m^3.|
|\\%1IMyEntity Owner { get; }](VRage.Game.ModAPI.Ingame.IMyInventory.Owner)|Returns entity this inventory belongs to.|

#### Methods

|Member|Description|
|---|---|
|\\%1bool CanItemsBeAdded(MyFixedPoint, MyItemType)](VRage.Game.ModAPI.Ingame.IMyInventory.CanItemsBeAdded)|Determines if given amount of items fits into this inventory on top of existing items.|
|\\%1bool CanTransferItemTo(IMyInventory, MyItemType)](VRage.Game.ModAPI.Ingame.IMyInventory.CanTransferItemTo)|Determines if there is working conveyor connection for item of give type to be transferred to other inventory.|
|\\%1bool ContainItems(MyFixedPoint, MyItemType)](VRage.Game.ModAPI.Ingame.IMyInventory.ContainItems)|Determines if there is at least given amount of items of given type contained inside this inventory.|
|\\%1MyInventoryItem? FindItem(MyItemType)](VRage.Game.ModAPI.Ingame.IMyInventory.FindItem)|Tries to find an item of given type inside this inventory.|
|\\%1void GetAcceptedItems(List\\%1MyItemType>, \\%1Func\\%1MyItemType, bool>])](VRage.Game.ModAPI.Ingame.IMyInventory.GetAcceptedItems)|Returns all items this inventory accepts.|
|\\%1MyFixedPoint GetItemAmount(MyItemType)](VRage.Game.ModAPI.Ingame.IMyInventory.GetItemAmount)|Sums up total amount of items of given type contained inside this inventory.|
|\\%1MyInventoryItem? GetItemAt(int)](VRage.Game.ModAPI.Ingame.IMyInventory.GetItemAt)|Returns info about item at give position.|
|\\%1MyInventoryItem? GetItemByID(uint)](VRage.Game.ModAPI.Ingame.IMyInventory.GetItemByID)|Returns info about item contained inside this inventory.|
|\\%1void GetItems(List\\%1MyInventoryItem>, \\%1Func\\%1MyInventoryItem, bool>])](VRage.Game.ModAPI.Ingame.IMyInventory.GetItems)|Collects all items present inside this inventory and returns snapshot of the current inventory state.|
|\\%1bool IsConnectedTo(IMyInventory)](VRage.Game.ModAPI.Ingame.IMyInventory.IsConnectedTo)|Checks if two inventories are connected.|
|\\%1bool IsItemAt(int)](VRage.Game.ModAPI.Ingame.IMyInventory.IsItemAt)|Determines if there is any item on given inventory slot.|
|\\%1bool TransferItemFrom(IMyInventory, MyInventoryItem, \\%1MyFixedPoint?])](VRage.Game.ModAPI.Ingame.IMyInventory.TransferItemFrom)|Attempts to transfer item from one inventory to another.|
|\\%1bool TransferItemFrom(IMyInventory, int, \\%1int?], \\%1bool?], \\%1MyFixedPoint?])](VRage.Game.ModAPI.Ingame.IMyInventory.TransferItemFrom)|Attempts to transfer item from one inventory to another.|
|\\%1bool TransferItemTo(IMyInventory, MyInventoryItem, \\%1MyFixedPoint?])](VRage.Game.ModAPI.Ingame.IMyInventory.TransferItemTo)|Attempts to transfer item from one inventory to another.|
|\\%1bool TransferItemTo(IMyInventory, int, \\%1int?], \\%1bool?], \\%1MyFixedPoint?])](VRage.Game.ModAPI.Ingame.IMyInventory.TransferItemTo)|Attempts to transfer item from one inventory to another.|

