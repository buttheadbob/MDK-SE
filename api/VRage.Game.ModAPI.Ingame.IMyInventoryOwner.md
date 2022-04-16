← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### IMyInventoryOwner Interface

```csharp
public interface IMyInventoryOwner
```

Describes interface of object that has inventory (PB scripting interface)

**Namespace:** [VRage.Game.ModAPI.Ingame](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll

#### Properties

|Member|Description|
|---|---|
|\$1long EntityId { get; }](VRage.Game.ModAPI.Ingame.IMyInventoryOwner.EntityId)|Gets EntityId, which it belongs to|
|\$1bool HasInventory { get; }](VRage.Game.ModAPI.Ingame.IMyInventoryOwner.HasInventory)|Gets whether has inventory|
|\$1int InventoryCount { get; }](VRage.Game.ModAPI.Ingame.IMyInventoryOwner.InventoryCount)|Gets amount of inventories|
|\$1bool UseConveyorSystem { get; set; }](VRage.Game.ModAPI.Ingame.IMyInventoryOwner.UseConveyorSystem)|Gets or sets if that inventory can interact with|

#### Methods

|Member|Description|
|---|---|
|\$1IMyInventory GetInventory(int)](VRage.Game.ModAPI.Ingame.IMyInventoryOwner.GetInventory)|Gets inventory by index|

