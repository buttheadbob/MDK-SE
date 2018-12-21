← [Index](index)
# MyCommandLine Class
**Namespace:** [`VRage.Game.ModAPI.Ingame.Utilities`](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll  
## Summary
A utility class to parse arguments from a command line string. Switches are defined with hyphen (-switch). Quotes can be placed around an argument to parse verbatim.
### Properties
|Member|Description|
|---|---|
|[`VRage.Game.ModAPI.Ingame.Utilities.ItemCollection Items`](VRage.Game.ModAPI.Ingame.Utilities.Items)|Contains all items, both arguments and switches|
|[`VRage.Game.ModAPI.Ingame.Utilities.SwitchCollection Switches`](VRage.Game.ModAPI.Ingame.Utilities.Switches)|Contains a list of all detected switches|
|[`int ArgumentCount`](VRage.Game.ModAPI.Ingame.Utilities.ArgumentCount)|Returns the number of non-switch arguments|
### Methods
|Member|Description|
|---|---|
|[`bool TryParse(string)`](VRage.Game.ModAPI.Ingame.Utilities.TryParse)|Attempts to parse the given string as a command line|
|[`string Argument(int)`](VRage.Game.ModAPI.Ingame.Utilities.Argument)|Returns the argument at the given index. Switches are not counted.|
|[`bool Switch(string)`](VRage.Game.ModAPI.Ingame.Utilities.Switch)|Determines whether the given switch is set. Switches are specified without their prefixed hyphen.|
|[`string Switch(string, int)`](VRage.Game.ModAPI.Ingame.Utilities.Switch)|Gets an argument of a switch. For example, using`Switch("key", 0)`on the command line`someOtherArgument -key value`will return`value`.|
|[`void Clear()`](VRage.Game.ModAPI.Ingame.Utilities.Clear)|Clears all arguments|
