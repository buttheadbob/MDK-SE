← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### IMyInventoryItem Interface

```csharp
public interface IMyInventoryItem
```

**Namespace:** [VRage.Game.ModAPI.Ingame](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll

#### Properties

|Member|Description|
|---|---|
|[MyFixedPoint Amount { get; set; }](VRage.Game.ModAPI.Ingame.IMyInventoryItem.Amount)|Gets or sets amount of items|
|[MyObjectBuilder_Base Content { get; set; }](VRage.Game.ModAPI.Ingame.IMyInventoryItem.Content)|Gets or sets content of inventory item. Cast it to [VRage.Game.MyObjectBuilder_PhysicalObject](https://docs.microsoft.com/en-us/dotnet/api/vrage.game.myobjectbuilder_physicalobject?view=netframework-4.6) |
|[uint ItemId { get; set; }](VRage.Game.ModAPI.Ingame.IMyInventoryItem.ItemId)|Item Id. Used to determine exact stack|
|[float Scale { get; set; }](VRage.Game.ModAPI.Ingame.IMyInventoryItem.Scale)|Gets or sets scale of Floating object|

