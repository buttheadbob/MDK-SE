← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### UpdateType Enum

```csharp
public enum UpdateType
```

Enum describes what source triggered the script to run.

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

#### Fields

|Member|Description|
|---|---|
|UpdateType IGC|Script run by intergrid communication system.|
|UpdateType Mod|Script run by a mod.|
|UpdateType None||
|UpdateType Once|Script is updating once before the tick.|
|UpdateType Script|Script run by another programmable block.|
|UpdateType Terminal|Script run by user in the terminal.|
|UpdateType Trigger|Script run by a block such as timer, sensor.|
|UpdateType Update1|Script is updating every tick.|
|UpdateType Update10|Script is updating every 10th tick.|
|UpdateType Update100|Script is updating every 100th tick.|

