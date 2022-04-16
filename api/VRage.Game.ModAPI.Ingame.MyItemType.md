← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MyItemType Struct

```csharp
public struct MyItemType: IComparable<MyItemType>, IEquatable<MyItemType>
```

Use by [MyInventoryItem](VRage.Game.ModAPI.Ingame.MyInventoryItem) 

**Namespace:** [VRage.Game.ModAPI.Ingame](VRage.Game.ModAPI.Ingame)  
**Assembly:** VRage.Game.dll

**Implements:**  
* [IComparable<MyItemType>](https://docs.microsoft.com/en-us/dotnet/api/System.IComparable-1?view=netframework-4.6)  
* [IEquatable<MyItemType>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Properties

|Member|Description|
|---|---|
|\[string SubtypeId { get; }](VRage.Game.ModAPI.Ingame.MyItemType.SubtypeId)|Gets Subtype of Item|
|\[string TypeId { get; }](VRage.Game.ModAPI.Ingame.MyItemType.TypeId)|Gets TypeId of Item|

#### Constructors

|Member|Description|
|---|---|
|\[MyItemType(string, string)](VRage.Game.ModAPI.Ingame.MyItemType..ctor)||
|\[MyItemType(MyObjectBuilderType, MyStringHash)](VRage.Game.ModAPI.Ingame.MyItemType..ctor)||

#### Methods

|Member|Description|
|---|---|
|\[static MyItemType MakeAmmo(string)](VRage.Game.ModAPI.Ingame.MyItemType.MakeAmmo)||
|\[static MyItemType MakeComponent(string)](VRage.Game.ModAPI.Ingame.MyItemType.MakeComponent)||
|\[static MyItemType MakeIngot(string)](VRage.Game.ModAPI.Ingame.MyItemType.MakeIngot)||
|\[static MyItemType MakeOre(string)](VRage.Game.ModAPI.Ingame.MyItemType.MakeOre)||
|\[static MyItemType MakeTool(string)](VRage.Game.ModAPI.Ingame.MyItemType.MakeTool)||
|\[static MyItemType Parse(string)](VRage.Game.ModAPI.Ingame.MyItemType.Parse)||
|\[int CompareTo(MyItemType)](VRage.Game.ModAPI.Ingame.MyItemType.CompareTo)||
|\[bool Equals(MyItemType)](VRage.Game.ModAPI.Ingame.MyItemType.Equals)||
|\[bool Equals(object)](VRage.Game.ModAPI.Ingame.MyItemType.Equals)||
|\[int GetHashCode()](VRage.Game.ModAPI.Ingame.MyItemType.GetHashCode)||
|\[string ToString()](VRage.Game.ModAPI.Ingame.MyItemType.ToString)||

