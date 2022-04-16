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
|UpdateFrequency None|Does not run autonomously.|
|UpdateFrequency Once|Run once before the next tick. Flag is un-set automatically after the update|
|UpdateFrequency Update1|Run every game tick.|
|UpdateFrequency Update10|Run every 10th game tick.|
|UpdateFrequency Update100|Run every 100th game tick.|

