← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MyInventoryItem Struct

```csharp
public struct MyInventoryItem: IComparable, IEquatable
```

Snapshot of inventory item at the moment of query. Not updated afterwards!

**Namespace:** [VRage.Game.ModAPI.Ingame](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll

**Implements:**  
* [IComparable<VRage.Game.ModAPI.Ingame.MyInventoryItem>](https://docs.microsoft.com/en-us/dotnet/api/System.IComparable-1?view=netframework-4.6)  
* [IEquatable<VRage.Game.ModAPI.Ingame.MyInventoryItem>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[MyFixedPoint Amount](VRage.Game.ModAPI.Ingame.MyInventoryItem.Amount)|Amount of stacked items. Kg or count, based on item type.|
|[uint ItemId](VRage.Game.ModAPI.Ingame.MyInventoryItem.ItemId)|Id of item, unique within a single inventory.|
|[MyItemType Type](VRage.Game.ModAPI.Ingame.MyInventoryItem.Type)|Type of inventory item.|

#### Constructors

|Member|Description|
|---|---|
|[MyInventoryItem(MyItemType, uint, MyFixedPoint)](VRage.Game.ModAPI.Ingame.MyInventoryItem..ctor)||

#### Methods

|Member|Description|
|---|---|
|[int CompareTo(MyInventoryItem)](VRage.Game.ModAPI.Ingame.MyInventoryItem.CompareTo)||
|[bool Equals(MyInventoryItem)](VRage.Game.ModAPI.Ingame.MyInventoryItem.Equals)||
|[bool Equals(object)](VRage.Game.ModAPI.Ingame.MyInventoryItem.Equals)||
|[int GetHashCode()](VRage.Game.ModAPI.Ingame.MyInventoryItem.GetHashCode)||
|[string ToString()](VRage.Game.ModAPI.Ingame.MyInventoryItem.ToString)||

