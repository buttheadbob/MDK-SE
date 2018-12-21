← [Index](index)
# MyIniParseResult Struct
**Namespace:** [`VRage.Game.ModAPI.Ingame.Utilities`](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll  
## Summary
Represents the results of a configuration parsing.
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Error"><code>string Error</code></a>_</td><td>Gets a description of the error that occurred during parsing. Will be`null`if no error occurred.</td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.LineNo"><code>int LineNo</code></a>_</td><td>Gets the line number where an error occured.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Success"><code>bool Success</code></a>_</td><td>Determines the success of the configuration parsing.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.IsDefined"><code>bool IsDefined</code></a>_</td><td>Determines if the value of this result is defined, meaning whether the [bool Success](VRage.Game.ModAPI.Ingame.Utilities.Success) actually holds any meaning.</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Equals"><code>bool Equals(MyIniParseResult other)</code></a>_</td><td>Compares this [MyIniParseResult](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult) with another.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Equals"><code>bool Equals(Object obj)</code></a>_</td><td>Compares this [MyIniParseResult](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult) with another.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.GetHashCode"><code>int GetHashCode()</code></a>_</td><td>Gets the hash code for this [MyIniParseResult](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult) .</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.ToString"><code>string ToString()</code></a>_</td><td>Generates a generic error message in the form of`Line N: Error`</td></tr>
</table>
