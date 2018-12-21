← [Index](index)
# MyIniKey Struct
**Namespace:** [`VRage.Game.ModAPI.Ingame.Utilities`](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll  
## Summary
Represents the combination of a section and a key in a [MyIni](VRage.Game.ModAPI.Ingame.Utilities.MyIni) structure.
### Fields
<table style="width:100%;display:table">
<tr><td>static _<a href="VRage.Game.ModAPI.Ingame.Utilities.EMPTY"><code>MyIniKey EMPTY</code></a>_</td><td></td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Section"><code>string Section</code></a>_</td><td>Gets the Section part of this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey)</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Name"><code>string Name</code></a>_</td><td>Gets the Key part of this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey)</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.IsEmpty"><code>bool IsEmpty</code></a>_</td><td>Determines whether this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) is empty.</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>static _<a href="VRage.Game.ModAPI.Ingame.Utilities.TryParse"><code>bool TryParse(string input, ref MyIniKey key)</code></a>_</td><td>Parses a string in the form of`section/key`into a [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) object.</td></tr>
<tr><td>static _<a href="VRage.Game.ModAPI.Ingame.Utilities.Parse"><code>MyIniKey Parse(string input)</code></a>_</td><td>Parses a string in the form of`section/key`into a [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) object.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Equals"><code>bool Equals(MyIniKey other)</code></a>_</td><td>Compares this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) with another. Note that this is equality in the sense of a configuration key, which means the comparison is implicitly case insensitive.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Equals"><code>bool Equals(Object obj)</code></a>_</td><td>Compares this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) with another. Note that this is equality in the sense of a configuration key, which means the comparison is implicitly case insensitive.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.GetHashCode"><code>int GetHashCode()</code></a>_</td><td>Gets the hash code representing this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey)</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.ToString"><code>string ToString()</code></a>_</td><td>Generates a string representing this [MyIniKey](VRage.Game.ModAPI.Ingame.Utilities.MyIniKey) in the form of`section/key`.</td></tr>
</table>
