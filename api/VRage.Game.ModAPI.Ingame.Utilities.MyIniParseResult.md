← [Index](index)
# MyIniParseResult Struct
**Namespace:** [`VRage.Game.ModAPI.Ingame.Utilities`](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll  
## Summary
Represents the results of a configuration parsing.
### Fields
<table style="width:100%;display:table">
<tr><td>[`string Error`](VRage.Game.ModAPI.Ingame.Utilities.Error)</td><td>Gets a description of the error that occurred during parsing. Will be`null`if no error occurred.</td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>[`int LineNo`](VRage.Game.ModAPI.Ingame.Utilities.LineNo)</td><td>Gets the line number where an error occured.</td></tr>
<tr><td>[`bool Success`](VRage.Game.ModAPI.Ingame.Utilities.Success)</td><td>Determines the success of the configuration parsing.</td></tr>
<tr><td>[`bool IsDefined`](VRage.Game.ModAPI.Ingame.Utilities.IsDefined)</td><td>Determines if the value of this result is defined, meaning whether the [bool Success](VRage.Game.ModAPI.Ingame.Utilities.Success) actually holds any meaning.</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>[`bool Equals(MyIniParseResult other)`](VRage.Game.ModAPI.Ingame.Utilities.Equals)</td><td>Compares this [MyIniParseResult](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult) with another.</td></tr>
<tr><td>[`bool Equals(Object obj)`](VRage.Game.ModAPI.Ingame.Utilities.Equals)</td><td>Compares this [MyIniParseResult](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult) with another.</td></tr>
<tr><td>[`int GetHashCode()`](VRage.Game.ModAPI.Ingame.Utilities.GetHashCode)</td><td>Gets the hash code for this [MyIniParseResult](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult) .</td></tr>
<tr><td>[`string ToString()`](VRage.Game.ModAPI.Ingame.Utilities.ToString)</td><td>Generates a generic error message in the form of`Line N: Error`</td></tr>
</table>
