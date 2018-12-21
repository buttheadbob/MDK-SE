← [Index](index)
# MyCommandLine Class
**Namespace:** [`VRage.Game.ModAPI.Ingame.Utilities`](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll  
## Summary
A utility class to parse arguments from a command line string. Switches are defined with hyphen (-switch). Quotes can be placed around an argument to parse verbatim.
### Properties
<table style="width:100%;display:table">
<tr><td>[`ItemCollection Items`](VRage.Game.ModAPI.Ingame.Utilities.Items)</td><td>Contains all items, both arguments and switches</td></tr>
<tr><td>[`SwitchCollection Switches`](VRage.Game.ModAPI.Ingame.Utilities.Switches)</td><td>Contains a list of all detected switches</td></tr>
<tr><td>[`int ArgumentCount`](VRage.Game.ModAPI.Ingame.Utilities.ArgumentCount)</td><td>Returns the number of non-switch arguments</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>[`bool TryParse(string argument)`](VRage.Game.ModAPI.Ingame.Utilities.TryParse)</td><td>Attempts to parse the given string as a command line</td></tr>
<tr><td>[`string Argument(int index)`](VRage.Game.ModAPI.Ingame.Utilities.Argument)</td><td>Returns the argument at the given index. Switches are not counted.</td></tr>
<tr><td>[`bool Switch(string name)`](VRage.Game.ModAPI.Ingame.Utilities.Switch)</td><td>Determines whether the given switch is set. Switches are specified without their prefixed hyphen.</td></tr>
<tr><td>[`string Switch(string name, int relativeArgument)`](VRage.Game.ModAPI.Ingame.Utilities.Switch)</td><td>Gets an argument of a switch. For example, using`Switch("key", 0)`on the command line`someOtherArgument -key value`will return`value`.</td></tr>
<tr><td>[`void Clear()`](VRage.Game.ModAPI.Ingame.Utilities.Clear)</td><td>Clears all arguments</td></tr>
</table>
