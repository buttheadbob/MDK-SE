← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### UpdateFrequency Enum

```csharp
public enum UpdateFrequency
```

Flags set how often the script will run itself.

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

#### Fields

|Member|Description|
|---|---|
|UpdateFrequency None <sub>prohibited</sub>|Does not run autonomously.|
|UpdateFrequency Once <sub>prohibited</sub>|Run once before the next tick. Flag is un-set automatically after the update|
|UpdateFrequency Update1 <sub>prohibited</sub>|Run every game tick.|
|UpdateFrequency Update10 <sub>prohibited</sub>|Run every 10th game tick.|
|UpdateFrequency Update100 <sub>prohibited</sub>|Run every 100th game tick.|

