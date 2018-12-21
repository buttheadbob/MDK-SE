← [Index](index)
# MyIniKey Struct
**Namespace:** [`VRage.Game.ModAPI.Ingame.Utilities`](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll  
## Summary
Represents the combination of a section and a key in aT:VRage.Game.ModAPI.Ingame.Utilities.MyInistructure.
### Fields
|Member|Description|
|---|---|
|[`MyIniKey EMPTY`](VRage.Game.ModAPI.Ingame.Utilities.EMPTY)||
### Properties
|Member|Description|
|---|---|
|[`string Section`](VRage.Game.ModAPI.Ingame.Utilities.Section)||
|[`string Name`](VRage.Game.ModAPI.Ingame.Utilities.Name)||
|[`bool IsEmpty`](VRage.Game.ModAPI.Ingame.Utilities.IsEmpty)||
### Methods
|Member|Description|
|---|---|
|[`bool TryParse(string input, ref MyIniKey key)`](VRage.Game.ModAPI.Ingame.Utilities.TryParse)||
|[`MyIniKey Parse(string input)`](VRage.Game.ModAPI.Ingame.Utilities.Parse)|Parses a string in the form ofsection/keyinto aT:VRage.Game.ModAPI.Ingame.Utilities.MyIniKeyobject.|
|[`bool Equals(MyIniKey other)`](VRage.Game.ModAPI.Ingame.Utilities.Equals)|Compares thisT:VRage.Game.ModAPI.Ingame.Utilities.MyIniKeywith another. Note that this is equality in the sense of a configuration key, which means the comparison is implicitly case insensitive.|
|[`bool Equals(Object obj)`](VRage.Game.ModAPI.Ingame.Utilities.Equals)|Compares thisT:VRage.Game.ModAPI.Ingame.Utilities.MyIniKeywith another. Note that this is equality in the sense of a configuration key, which means the comparison is implicitly case insensitive.|
|[`int GetHashCode()`](VRage.Game.ModAPI.Ingame.Utilities.GetHashCode)||
|[`string ToString()`](VRage.Game.ModAPI.Ingame.Utilities.ToString)||
