← [Index](Api-Index)

#### UpdateType Enum

```csharp
public enum UpdateType: IComparable, IFormattable, IConvertible
```

Enum describes what source triggered the script to run.

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
|None||
|Terminal|Script run by user in the terminal.|
|Trigger|Script run by a block such as timer, sensor.|
|Antenna|Script run by antenna receiving a message.|
|Mod|Script run by a mod.|
|Script|Script run by another programmable block.|
|Update1|Script is updating every tick.|
|Update10|Script is updating every 10th tick.|
|Update100|Script is updating every 100th tick.|
|Once|Script is updating once before the tick.|

