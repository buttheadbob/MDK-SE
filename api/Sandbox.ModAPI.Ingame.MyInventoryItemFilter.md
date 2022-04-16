← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MyInventoryItemFilter Struct

```csharp
public struct MyInventoryItemFilter
```

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

#### Fields

|Member|Description|
|---|---|
|\\[bool AllSubTypes](Sandbox.ModAPI.Ingame.MyInventoryItemFilter.AllSubTypes)|Determines whether all subtypes of the given item ID should pass this filter check.|
|\\[MyDefinitionId ItemId](Sandbox.ModAPI.Ingame.MyInventoryItemFilter.ItemId)|Specifies an item to filter. Set [AllSubTypes](Sandbox.ModAPI.Ingame.MyInventoryItemFilter.AllSubTypes) to true to only check the main type part of this ID.|

#### Properties

|Member|Description|
|---|---|
|\\[MyItemType ItemType { get; }](Sandbox.ModAPI.Ingame.MyInventoryItemFilter.ItemType)||

#### Constructors

|Member|Description|
|---|---|
|\\[MyInventoryItemFilter(string, \\[bool])](Sandbox.ModAPI.Ingame.MyInventoryItemFilter..ctor)||
|\\[MyInventoryItemFilter(MyDefinitionId, \\[bool])](Sandbox.ModAPI.Ingame.MyInventoryItemFilter..ctor)||

