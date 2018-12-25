← [Index](Api-Index) ← [IMyInventory](VRage.Game.ModAPI.Ingame.IMyInventory)

### Summary

```csharp
public bool TransferItemFrom(IMyInventory sourceInventory, int sourceItemIndex, Nullable<T> targetItemIndex, Nullable<T> stackIfPossible, Nullable<T> amount)
```

### Returns

[bool](https://docs.microsoft.com/en-us/dotnet/api/system.boolean?view=netframework-4.6)

### Parameters

* [IMyInventory](VRage.Game.ModAPI.Ingame.IMyInventory) sourceInventory
* [int](https://docs.microsoft.com/en-us/dotnet/api/system.int32?view=netframework-4.6) sourceItemIndex
* [Nullable<T>](https://docs.microsoft.com/en-us/dotnet/api/system.nullable?view=netframework-4.6) targetItemIndex
* [Nullable<T>](https://docs.microsoft.com/en-us/dotnet/api/system.nullable?view=netframework-4.6) stackIfPossible
* [Nullable<T>](https://docs.microsoft.com/en-us/dotnet/api/system.nullable?view=netframework-4.6) amount
### Summary

```csharp
public bool TransferItemFrom(IMyInventory sourceInventory, IMyInventoryItem item, MyFixedPoint amount)
```

### Returns

[bool](https://docs.microsoft.com/en-us/dotnet/api/system.boolean?view=netframework-4.6)

### Parameters

* [IMyInventory](VRage.Game.ModAPI.Ingame.IMyInventory) sourceInventory
* [IMyInventoryItem](VRage.Game.ModAPI.Ingame.IMyInventoryItem) item
* [MyFixedPoint](VRage.MyFixedPoint) amount
