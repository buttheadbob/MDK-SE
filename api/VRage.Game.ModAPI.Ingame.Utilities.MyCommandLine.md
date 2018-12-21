← [Index](index)
# MyCommandLine Class
**Namespace:** [`VRage.Game.ModAPI.Ingame.Utilities`](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll  
## Summary
A utility class to parse arguments from a command line string. Switches are defined with hyphen (-switch). Quotes can be placed around an argument to parse verbatim.
### Properties
|Member|Description|
|---|---|
|[`ItemCollection&nbsp;Items`](VRage.Game.ModAPI.Ingame.Utilities.Items)|Contains all items, both arguments and switches|
|[`SwitchCollection&nbsp;Switches`](VRage.Game.ModAPI.Ingame.Utilities.Switches)|Contains a list of all detected switches|
|[`int&nbsp;ArgumentCount`](VRage.Game.ModAPI.Ingame.Utilities.ArgumentCount)|Returns the number of non-switch arguments|
### Methods
|Member|Description|
|---|---|
|[`bool&nbsp;TryParse(string&nbsp;argument)`](VRage.Game.ModAPI.Ingame.Utilities.TryParse)|Attempts to parse the given string as a command line|
|[`string&nbsp;Argument(int&nbsp;index)`](VRage.Game.ModAPI.Ingame.Utilities.Argument)|Returns the argument at the given index. Switches are not counted.|
|[`bool&nbsp;Switch(string&nbsp;name)`](VRage.Game.ModAPI.Ingame.Utilities.Switch)|Determines whether the given switch is set. Switches are specified without their prefixed hyphen.|
|[`string&nbsp;Switch(string&nbsp;name,&nbsp;int&nbsp;relativeArgument)`](VRage.Game.ModAPI.Ingame.Utilities.Switch)|Gets an argument of a switch. For example, using`Switch("key", 0)`on the command line`someOtherArgument -key value`will return`value`.|
|[`void&nbsp;Clear()`](VRage.Game.ModAPI.Ingame.Utilities.Clear)|Clears all arguments|
