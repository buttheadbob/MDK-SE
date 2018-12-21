← [Index](Api-Index)
# MyIniParseResult Struct
**Namespace:** [`VRage.Game.ModAPI.Ingame.Utilities`](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll  
## Summary
Represents the results of a configuration parsing.
### Fields
|Member|Description|
|---|---|
|[`Error`](VRage.Game.ModAPI.Ingame.Utilities.Error)|Gets a description of the error that occurred during parsing. Will be`null`if no error occurred.|
### Properties
|Member|Description|
|---|---|
|[`LineNo`](VRage.Game.ModAPI.Ingame.Utilities.LineNo)|Gets the line number where an error occured.|
|[`Success`](VRage.Game.ModAPI.Ingame.Utilities.Success)|Determines the success of the configuration parsing.|
|[`IsDefined`](VRage.Game.ModAPI.Ingame.Utilities.IsDefined)|Determines if the value of this result is defined, meaning whether the [bool Success](VRage.Game.ModAPI.Ingame.Utilities.Success) actually holds any meaning.|
### Methods
|Member|Description|
|---|---|
|[`Equals(MyIniParseResult)`](VRage.Game.ModAPI.Ingame.Utilities.Equals)|Compares this [MyIniParseResult](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult) with another.|
|[`Equals(Object)`](VRage.Game.ModAPI.Ingame.Utilities.Equals)|Compares this [MyIniParseResult](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult) with another.|
|[`GetHashCode()`](VRage.Game.ModAPI.Ingame.Utilities.GetHashCode)|Gets the hash code for this [MyIniParseResult](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult) .|
|[`ToString()`](VRage.Game.ModAPI.Ingame.Utilities.ToString)|Generates a generic error message in the form of`Line N: Error`|
