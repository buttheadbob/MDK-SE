← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MyIniKey Struct

```csharp
public struct MyIniKey: IEquatable<MyIniKey>
```

Represents the combination of a section and a key in a [MyIni](VRage.Game.ModAPI.Ingame.Utilities.MyIni) structure.

**Namespace:** [VRage.Game.ModAPI.Ingame.Utilities](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll

**Implements:**  
* [IEquatable&lt;MyIniKey&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[static MyIniKey EMPTY](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey.EMPTY)||

#### Properties

|Member|Description|
|---|---|
|[bool IsEmpty { get; }](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey.IsEmpty)|Determines whether this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) is empty.|
|[string Name { get; }](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey.Name)|Gets the Key part of this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) |
|[string Section { get; }](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey.Section)|Gets the Section part of this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) |

#### Constructors

|Member|Description|
|---|---|
|[MyIniKey(string, string)](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey..ctor)||

#### Methods

|Member|Description|
|---|---|
|[static MyIniKey Parse(string)](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey.Parse)|Parses a string in the form of`section/key`into a [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) object.|
|[static bool TryParse(string, out MyIniKey)](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey.TryParse)|Parses a string in the form of`section/key`into a [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) object.|
|[bool Equals(MyIniKey)](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey.Equals)|Compares this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) with another. Note that this is equality in the sense of a configuration key, which means the comparison is implicitly case insensitive.|
|[bool Equals(object)](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey.Equals)|Compares this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) with another. Note that this is equality in the sense of a configuration key, which means the comparison is implicitly case insensitive.|
|[int GetHashCode()](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey.GetHashCode)|Gets the hash code representing this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) |
|[string ToString()](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey.ToString)|Generates a string representing this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) in the form of`section/key`.|

