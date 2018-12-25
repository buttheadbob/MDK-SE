← [Index](Api-Index)

### MyIniKey Struct

```csharp
private public sealed MyIniKey
```csharp

**Namespace:** [VRage.Game.ModAPI.Ingame.Utilities](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll

### Example

### Remarks

###### Fields

|Member|Description|
|---|---|
|[EMPTY](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey.EMPTY)||

###### Properties

|Member|Description|
|---|---|
|[Section](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey.Section)|Gets the Section part of this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) |
|[Name](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey.Name)|Gets the Key part of this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) |
|[IsEmpty](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey.IsEmpty)|Determines whether this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) is empty.|

###### Methods

|Member|Description|
|---|---|
|[TryParse(string, ref MyIniKey)](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey.TryParse)|Parses a string in the form of`section/key`into a [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) object.|
|[Parse(string)](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey.Parse)|Parses a string in the form of`section/key`into a [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) object.|
|[Equals(MyIniKey)](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey.Equals)|Compares this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) with another. Note that this is equality in the sense of a configuration key, which means the comparison is implicitly case insensitive.|
|[Equals(object)](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey.Equals)|Compares this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) with another. Note that this is equality in the sense of a configuration key, which means the comparison is implicitly case insensitive.|
|[GetHashCode()](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey.GetHashCode)|Gets the hash code representing this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) |
|[ToString()](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey.ToString)|Generates a string representing this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) in the form of`section/key`.|

