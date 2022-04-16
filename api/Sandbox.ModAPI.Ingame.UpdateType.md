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
|UpdateType IGC <sub>prohibited</sub>|Script run by intergrid communication system.|
|UpdateType Mod <sub>prohibited</sub>|Script run by a mod.|
|UpdateType None <sub>prohibited</sub>||
|UpdateType Once <sub>prohibited</sub>|Script is updating once before the tick.|
|UpdateType Script <sub>prohibited</sub>|Script run by another programmable block.|
|UpdateType Terminal <sub>prohibited</sub>|Script run by user in the terminal.|
|UpdateType Trigger <sub>prohibited</sub>|Script run by a block such as timer, sensor.|
|UpdateType Update1 <sub>prohibited</sub>|Script is updating every tick.|
|UpdateType Update10 <sub>prohibited</sub>|Script is updating every 10th tick.|
|UpdateType Update100 <sub>prohibited</sub>|Script is updating every 100th tick.|

