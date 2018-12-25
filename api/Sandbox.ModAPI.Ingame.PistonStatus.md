← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### PistonStatus Enum

```csharp
public enum PistonStatus: IComparable, IFormattable, IConvertible
```

Describes the current status of the piston.

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

**Implements:**  
* [IComparable](https://docs.microsoft.com/en-us/dotnet/api/system.icomparable?view=netframework-4.6)  
* [IFormattable](https://docs.microsoft.com/en-us/dotnet/api/system.iformattable?view=netframework-4.6)  
* [IConvertible](https://docs.microsoft.com/en-us/dotnet/api/system.iconvertible?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|Stopped|The piston velocity is 0 (stationary).|
|Extending|The piston is being extended (moving).|
|Extended|The piston is in its extended position (stationary).|
|Retracting|The piston is being retracted (moving).|
|Retracted|The piston is in its retracted position (stationary).|

