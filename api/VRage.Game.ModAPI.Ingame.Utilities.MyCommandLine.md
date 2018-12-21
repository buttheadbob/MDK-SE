← [Index](index)
# MyCommandLine Class
**Namespace:** [`VRage.Game.ModAPI.Ingame.Utilities`](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll  
## Summary
A utility class to parse arguments from a command line string. Switches are defined with hyphen (-switch). Quotes can be placed around an argument to parse verbatim.
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Items"><code>ItemCollection Items</code></a>_</td><td>Contains all items, both arguments and switches</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Switches"><code>SwitchCollection Switches</code></a>_</td><td>Contains a list of all detected switches</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.ArgumentCount"><code>int ArgumentCount</code></a>_</td><td>Returns the number of non-switch arguments</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.TryParse"><code>bool TryParse(string argument)</code></a>_</td><td>Attempts to parse the given string as a command line</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Argument"><code>string Argument(int index)</code></a>_</td><td>Returns the argument at the given index. Switches are not counted.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Switch"><code>bool Switch(string name)</code></a>_</td><td>Determines whether the given switch is set. Switches are specified without their prefixed hyphen.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Switch"><code>string Switch(string name, int relativeArgument)</code></a>_</td><td>Gets an argument of a switch. For example, using`Switch("key", 0)`on the command line`someOtherArgument -key value`will return`value`.</td></tr>
<tr><td>_<a href="VRage.Game.ModAPI.Ingame.Utilities.Clear"><code>void Clear()</code></a>_</td><td>Clears all arguments</td></tr>
</table>
