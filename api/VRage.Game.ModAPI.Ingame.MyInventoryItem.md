← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MyInventoryItem Struct

```csharp
public struct MyInventoryItem: IComparable<T>, IEquatable<T>
```

Snapshot of inventory item at the moment of query. Not updated afterwards!

**Namespace:** [VRage.Game.ModAPI.Ingame](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll

**Implements:**  
* [IComparable<T>](https://docs.microsoft.com/en-us/dotnet/api/system.icomparable?view=netframework-4.6)  
* [IEquatable<T>](https://docs.microsoft.com/en-us/dotnet/api/system.iequatable?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[ItemId](VRage.Game.ModAPI.Ingame.MyInventoryItem.ItemId)|Id of item, unique within a single inventory.|
|[Amount](VRage.Game.ModAPI.Ingame.MyInventoryItem.Amount)|Amount of stacked items. Kg or count, based on item type.|
|[Type](VRage.Game.ModAPI.Ingame.MyInventoryItem.Type)|Type of inventory item.|

#### Constructors

|Member|Description|
|---|---|
|[MyInventoryItem(MyItemType, uint, MyFixedPoint)](VRage.Game.ModAPI.Ingame.MyInventoryItem..ctor)||

#### Methods

|Member|Description|
|---|---|
|[Equals(MyInventoryItem)](VRage.Game.ModAPI.Ingame.MyInventoryItem.Equals)||
|[Equals(object)](VRage.Game.ModAPI.Ingame.MyInventoryItem.Equals)||
|[GetHashCode()](VRage.Game.ModAPI.Ingame.MyInventoryItem.GetHashCode)||
|[CompareTo(MyInventoryItem)](VRage.Game.ModAPI.Ingame.MyInventoryItem.CompareTo)||
|[ToString()](VRage.Game.ModAPI.Ingame.MyInventoryItem.ToString)||

