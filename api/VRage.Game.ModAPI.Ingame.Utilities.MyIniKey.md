← [Index](index)
# MyIniKey Struct
**Namespace:** [`VRage.Game.ModAPI.Ingame.Utilities`](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll  
## Summary
Represents the combination of a section and a key in a [MyIni](VRage.Game.ModAPI.Ingame.Utilities.MyIni) structure.
### Fields
<table style="width:100%;display:table">
<tr><td>static [`MyIniKey EMPTY`](VRage.Game.ModAPI.Ingame.Utilities.EMPTY)</td><td></td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>[`string Section`](VRage.Game.ModAPI.Ingame.Utilities.Section)</td><td>Gets the Section part of this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey)</td></tr>
<tr><td>[`string Name`](VRage.Game.ModAPI.Ingame.Utilities.Name)</td><td>Gets the Key part of this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey)</td></tr>
<tr><td>[`bool IsEmpty`](VRage.Game.ModAPI.Ingame.Utilities.IsEmpty)</td><td>Determines whether this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) is empty.</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>static [`bool TryParse(string input, ref MyIniKey key)`](VRage.Game.ModAPI.Ingame.Utilities.TryParse)</td><td>Parses a string in the form of`section/key`into a [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) object.</td></tr>
<tr><td>static [`MyIniKey Parse(string input)`](VRage.Game.ModAPI.Ingame.Utilities.Parse)</td><td>Parses a string in the form of`section/key`into a [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) object.</td></tr>
<tr><td>[`bool Equals(MyIniKey other)`](VRage.Game.ModAPI.Ingame.Utilities.Equals)</td><td>Compares this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) with another. Note that this is equality in the sense of a configuration key, which means the comparison is implicitly case insensitive.</td></tr>
<tr><td>[`bool Equals(Object obj)`](VRage.Game.ModAPI.Ingame.Utilities.Equals)</td><td>Compares this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) with another. Note that this is equality in the sense of a configuration key, which means the comparison is implicitly case insensitive.</td></tr>
<tr><td>[`int GetHashCode()`](VRage.Game.ModAPI.Ingame.Utilities.GetHashCode)</td><td>Gets the hash code representing this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey)</td></tr>
<tr><td>[`string ToString()`](VRage.Game.ModAPI.Ingame.Utilities.ToString)</td><td>Generates a string representing this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) in the form of`section/key`.</td></tr>
</table>
