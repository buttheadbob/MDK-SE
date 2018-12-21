← [Index](index)
# MyIniKey Struct
**Namespace:** [`VRage.Game.ModAPI.Ingame.Utilities`](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll  
## Summary
Represents the combination of a section and a key in a [MyIni](VRage.Game.ModAPI.Ingame.Utilities.MyIni) structure.
### Fields
|Member|Description|
|---|---|
|static [`MyIniKey EMPTY`](VRage.Game.ModAPI.Ingame.Utilities.EMPTY)||
### Properties
|Member|Description|
|---|---|
|[`string Section`](VRage.Game.ModAPI.Ingame.Utilities.Section)|Gets the Section part of this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey)|
|[`string Name`](VRage.Game.ModAPI.Ingame.Utilities.Name)|Gets the Key part of this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey)|
|[`bool IsEmpty`](VRage.Game.ModAPI.Ingame.Utilities.IsEmpty)|Determines whether this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) is empty.|
### Methods
|Member|Description|
|---|---|
|static [`bool TryParse(string input, ref MyIniKey key)`](VRage.Game.ModAPI.Ingame.Utilities.TryParse)|Parses a string in the form of`section/key`into a [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) object.|
|static [`MyIniKey Parse(string input)`](VRage.Game.ModAPI.Ingame.Utilities.Parse)|Parses a string in the form of`section/key`into a [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) object.|
|[`bool Equals(MyIniKey other)`](VRage.Game.ModAPI.Ingame.Utilities.Equals)|Compares this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) with another. Note that this is equality in the sense of a configuration key, which means the comparison is implicitly case insensitive.|
|[`bool Equals(Object obj)`](VRage.Game.ModAPI.Ingame.Utilities.Equals)|Compares this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) with another. Note that this is equality in the sense of a configuration key, which means the comparison is implicitly case insensitive.|
|[`int GetHashCode()`](VRage.Game.ModAPI.Ingame.Utilities.GetHashCode)|Gets the hash code representing this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey)|
|[`string ToString()`](VRage.Game.ModAPI.Ingame.Utilities.ToString)|Generates a string representing this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) in the form of`section/key`.|
