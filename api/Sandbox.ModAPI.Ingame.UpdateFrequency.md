← [Index](Api-Index)

#### UpdateFrequency Enum

```csharp
public enum UpdateFrequency: Enum, IComparable, IFormattable, IConvertible
```

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

**Inheritance:** [Enum](https://docs.microsoft.com/en-us/dotnet/api/system.enum?view=netframework-4.6)

**Implements:**  
* [IComparable](https://docs.microsoft.com/en-us/dotnet/api/system.icomparable?view=netframework-4.6)  
* [IFormattable](https://docs.microsoft.com/en-us/dotnet/api/system.iformattable?view=netframework-4.6)  
* [IConvertible](https://docs.microsoft.com/en-us/dotnet/api/system.iconvertible?view=netframework-4.6)

#### Example

#### Remarks

#### Fields

|Member|Description|
|---|---|
|None|Does not run autonomously.|
|Update1|Run every game tick.|
|Update10|Run every 10th game tick.|
|Update100|Run every 100th game tick.|
|Once|Run once before the next tick. Flag is un-set automatically after the update|

