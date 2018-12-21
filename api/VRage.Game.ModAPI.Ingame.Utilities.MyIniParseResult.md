← [Index](index)
# MyIniParseResult Struct
**Namespace:** [`VRage.Game.ModAPI.Ingame.Utilities`](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll  
## Summary
Represents the results of a configuration parsing.
### Fields
|Member|Description|
|---|---|
|[`string Error`](VRage.Game.ModAPI.Ingame.Utilities.Error)|Gets a description of the error that occurred during parsing. Will be`null`if no error occurred.|
### Properties
|Member|Description|
|---|---|
|[`int LineNo`](VRage.Game.ModAPI.Ingame.Utilities.LineNo)|Gets the line number where an error occured.|
|[`bool Success`](VRage.Game.ModAPI.Ingame.Utilities.Success)|Determines the success of the configuration parsing.|
|[`bool IsDefined`](VRage.Game.ModAPI.Ingame.Utilities.IsDefined)|Determines if the value of this result is defined, meaning whether the [bool Success](VRage.Game.ModAPI.Ingame.Utilities.Success) actually holds any meaning.|
### Methods
|Member|Description|
|---|---|
|[`bool Equals(MyIniParseResult other)`](VRage.Game.ModAPI.Ingame.Utilities.Equals)|Compares this [MyIniParseResult](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult) with another.|
|[`bool Equals(Object obj)`](VRage.Game.ModAPI.Ingame.Utilities.Equals)|Compares this [MyIniParseResult](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult) with another.|
|[`int GetHashCode()`](VRage.Game.ModAPI.Ingame.Utilities.GetHashCode)|Gets the hash code for this [MyIniParseResult](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult) .|
|[`string ToString()`](VRage.Game.ModAPI.Ingame.Utilities.ToString)|Generates a generic error message in the form of`Line N: Error`|
