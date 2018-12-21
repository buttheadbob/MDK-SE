← [Index](index)
# MyCommandLine Class
**Namespace:** [`VRage.Game.ModAPI.Ingame.Utilities`](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll  
## Summary
A utility class to parse arguments from a command line string. Switches are defined with hyphen (-switch). Quotes can be placed around an argument to parse verbatim.
### Properties
|Member|Description|
|---|---|
|[`ItemCollection Items`](VRage.Game.ModAPI.Ingame.Utilities.Items)||
|[`SwitchCollection Switches`](VRage.Game.ModAPI.Ingame.Utilities.Switches)||
|[`int ArgumentCount`](VRage.Game.ModAPI.Ingame.Utilities.ArgumentCount)||
### Methods
|Member|Description|
|---|---|
|[`bool TryParse(string argument)`](VRage.Game.ModAPI.Ingame.Utilities.TryParse)|Attempts to parse the given string as a command line|
|[`string Argument(int index)`](VRage.Game.ModAPI.Ingame.Utilities.Argument)|Returns the argument at the given index. Switches are not counted.|
|[`bool Switch(string name)`](VRage.Game.ModAPI.Ingame.Utilities.Switch)|Determines whether the given switch is set. Switches are specified without their prefixed hyphen.|
|[`string Switch(string name, int relativeArgument)`](VRage.Game.ModAPI.Ingame.Utilities.Switch)||
|[`void Clear()`](VRage.Game.ModAPI.Ingame.Utilities.Clear)||
