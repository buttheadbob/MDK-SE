← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MyIniParseResult Struct

```csharp
public struct MyIniParseResult
```

Represents the results of a configuration parsing.

**Namespace:** [VRage.Game.ModAPI.Ingame.Utilities](VRage.Game.ModAPI.Ingame.Utilities)  
**Assembly:** VRage.Game.dll

#### Fields

|Member|Description|
|---|---|
|\\%1string Error](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult.Error)|Gets a description of the error that occurred during parsing. Will be`null`if no error occurred.|

#### Properties

|Member|Description|
|---|---|
|\\%1bool IsDefined { get; }](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult.IsDefined)|Determines if the value of this result is defined, meaning whether the [Success](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult.Success) actually holds any meaning.|
|\\%1int LineNo { get; }](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult.LineNo)|Gets the line number where an error occured.|
|\\%1bool Success { get; }](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult.Success)|Determines the success of the configuration parsing.|

#### Methods

|Member|Description|
|---|---|
|\\%1bool Equals(MyIniParseResult)](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult.Equals)|Compares this [MyIniParseResult](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult) with another.|
|\\%1bool Equals(object)](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult.Equals)|Compares this [MyIniParseResult](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult) with another.|
|\\%1int GetHashCode()](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult.GetHashCode)|Gets the hash code for this [MyIniParseResult](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult) .|
|\\%1string ToString()](VRage.Game.ModAPI.Ingame.Utilities.MyIniParseResult.ToString)|Generates a generic error message in the form of`Line N: Error`|

