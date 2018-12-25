← [Index](Api-Index)

#### MyLaserAntennaStatus Enum

```csharp
public enum MyLaserAntennaStatus: IComparable, IFormattable, IConvertible
```

Describes the current status of a laser antenna.

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

**Implements:**  
* [IComparable](https://docs.microsoft.com/en-us/dotnet/api/system.icomparable?view=netframework-4.6)  
* [IFormattable](https://docs.microsoft.com/en-us/dotnet/api/system.iformattable?view=netframework-4.6)  
* [IConvertible](https://docs.microsoft.com/en-us/dotnet/api/system.iconvertible?view=netframework-4.6)

#### Example

#### Remarks

#### Fields

|Member|Description|
|---|---|
|Idle|Not doing anything and not connected.|
|RotatingToTarget|Currently rotating towards the currently selected target.|
|SearchingTargetForAntenna|Currently searching for a laser antenna at the target.|
|Connecting|Currently connecting to a laser antenna.|
|Connected|Currently connected to a laser antenna.|
|OutOfRange|The target antenna is out of range.|

