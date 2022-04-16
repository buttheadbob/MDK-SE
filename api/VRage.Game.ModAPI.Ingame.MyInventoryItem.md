← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MyInventoryItem Struct

```csharp
public struct MyInventoryItem: IComparable<MyInventoryItem>, IEquatable<MyInventoryItem>
```

Snapshot of inventory item at the moment of query. Not updated afterwards!

**Namespace:** [VRage.Game.ModAPI.Ingame](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll

**Implements:**  
* [IComparable<MyInventoryItem>](https://docs.microsoft.com/en-us/dotnet/api/System.IComparable-1?view=netframework-4.6)  
* [IEquatable<MyInventoryItem>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\\%1MyFixedPoint Amount](VRage.Game.ModAPI.Ingame.MyInventoryItem.Amount)|Amount of stacked items. Kg or count, based on item type.|
|\\%1uint ItemId](VRage.Game.ModAPI.Ingame.MyInventoryItem.ItemId)|Id of item, unique within a single inventory.|
|\\%1MyItemType Type](VRage.Game.ModAPI.Ingame.MyInventoryItem.Type)|Type of inventory item.|

#### Constructors

|Member|Description|
|---|---|
|\\%1MyInventoryItem(MyItemType, uint, MyFixedPoint)](VRage.Game.ModAPI.Ingame.MyInventoryItem..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\%1int CompareTo(MyInventoryItem)](VRage.Game.ModAPI.Ingame.MyInventoryItem.CompareTo)||
|\\%1bool Equals(MyInventoryItem)](VRage.Game.ModAPI.Ingame.MyInventoryItem.Equals)||
|\\%1bool Equals(object)](VRage.Game.ModAPI.Ingame.MyInventoryItem.Equals)||
|\\%1int GetHashCode()](VRage.Game.ModAPI.Ingame.MyInventoryItem.GetHashCode)||
|\\%1string ToString()](VRage.Game.ModAPI.Ingame.MyInventoryItem.ToString)||

