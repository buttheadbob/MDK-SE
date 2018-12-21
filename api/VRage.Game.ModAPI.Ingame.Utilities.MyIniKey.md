← [Index](index)
# MyIniKey Struct
**Namespace:** [`VRage.Game.ModAPI.Ingame.Utilities`](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll  
## Summary
Represents the combination of a section and a key in a [MyIni](VRage.Game.ModAPI.Ingame.Utilities.MyIni) structure.
### Fields
|Member|Description|
|---|---|
|static&nbsp;[`MyIniKey&nbsp;EMPTY`](VRage.Game.ModAPI.Ingame.Utilities.EMPTY)||
### Properties
|Member|Description|
|---|---|
|[`string&nbsp;Section`](VRage.Game.ModAPI.Ingame.Utilities.Section)|Gets the Section part of this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey)|
|[`string&nbsp;Name`](VRage.Game.ModAPI.Ingame.Utilities.Name)|Gets the Key part of this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey)|
|[`bool&nbsp;IsEmpty`](VRage.Game.ModAPI.Ingame.Utilities.IsEmpty)|Determines whether this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) is empty.|
### Methods
|Member|Description|
|---|---|
|static&nbsp;[`bool&nbsp;TryParse(string&nbsp;input,&nbsp;ref&nbsp;MyIniKey&nbsp;key)`](VRage.Game.ModAPI.Ingame.Utilities.TryParse)|Parses a string in the form of`section/key`into a [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) object.|
|static&nbsp;[`MyIniKey&nbsp;Parse(string&nbsp;input)`](VRage.Game.ModAPI.Ingame.Utilities.Parse)|Parses a string in the form of`section/key`into a [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) object.|
|[`bool&nbsp;Equals(MyIniKey&nbsp;other)`](VRage.Game.ModAPI.Ingame.Utilities.Equals)|Compares this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) with another. Note that this is equality in the sense of a configuration key, which means the comparison is implicitly case insensitive.|
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRage.Game.ModAPI.Ingame.Utilities.Equals)|Compares this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) with another. Note that this is equality in the sense of a configuration key, which means the comparison is implicitly case insensitive.|
|[`int&nbsp;GetHashCode()`](VRage.Game.ModAPI.Ingame.Utilities.GetHashCode)|Gets the hash code representing this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey)|
|[`string&nbsp;ToString()`](VRage.Game.ModAPI.Ingame.Utilities.ToString)|Generates a string representing this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) in the form of`section/key`.|
