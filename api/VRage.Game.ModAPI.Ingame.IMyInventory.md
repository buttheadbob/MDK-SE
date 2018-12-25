← [Index](Api-Index)

### IMyInventory Interface

```csharp
private public abstract IMyInventory
```csharp

**Namespace:** [VRage.Game.ModAPI.Ingame](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll

### Example

### Remarks

###### Properties

|Member|Description|
|---|---|
|[IsFull](VRage.Game.ModAPI.Ingame.IMyInventory.IsFull)||
|[Size](VRage.Game.ModAPI.Ingame.IMyInventory.Size)||
|[CurrentMass](VRage.Game.ModAPI.Ingame.IMyInventory.CurrentMass)||
|[MaxVolume](VRage.Game.ModAPI.Ingame.IMyInventory.MaxVolume)||
|[CurrentVolume](VRage.Game.ModAPI.Ingame.IMyInventory.CurrentVolume)||
|[Owner](VRage.Game.ModAPI.Ingame.IMyInventory.Owner)||

###### Methods

|Member|Description|
|---|---|
|[IsItemAt(int)](VRage.Game.ModAPI.Ingame.IMyInventory.IsItemAt)||
|[CanAddItemAmount(IMyInventoryItem, MyFixedPoint)](VRage.Game.ModAPI.Ingame.IMyInventory.CanAddItemAmount)||
|[CanItemsBeAdded(MyFixedPoint, SerializableDefinitionId)](VRage.Game.ModAPI.Ingame.IMyInventory.CanItemsBeAdded)||
|[ContainItems(MyFixedPoint, MyObjectBuilder_PhysicalObject)](VRage.Game.ModAPI.Ingame.IMyInventory.ContainItems)||
|[GetItemAmount(SerializableDefinitionId, MyItemFlags)](VRage.Game.ModAPI.Ingame.IMyInventory.GetItemAmount)||
|[TransferItemTo(IMyInventory, int, Nullable, Nullable, Nullable)](VRage.Game.ModAPI.Ingame.IMyInventory.TransferItemTo)||
|[TransferItemFrom(IMyInventory, int, Nullable, Nullable, Nullable)](VRage.Game.ModAPI.Ingame.IMyInventory.TransferItemFrom)||
|[TransferItemFrom(IMyInventory, IMyInventoryItem, MyFixedPoint)](VRage.Game.ModAPI.Ingame.IMyInventory.TransferItemFrom)||
|[GetItems()](VRage.Game.ModAPI.Ingame.IMyInventory.GetItems)||
|[GetItemByID(uint)](VRage.Game.ModAPI.Ingame.IMyInventory.GetItemByID)||
|[FindItem(SerializableDefinitionId)](VRage.Game.ModAPI.Ingame.IMyInventory.FindItem)||
|[IsConnectedTo(IMyInventory)](VRage.Game.ModAPI.Ingame.IMyInventory.IsConnectedTo)||

