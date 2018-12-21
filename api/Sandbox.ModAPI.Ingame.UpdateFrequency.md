← [Index](index)
# UpdateFrequency Enum
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
## Summary
Flags set how often the script will run itself.
### Fields
|Member|Description|
|---|---|
|static [`UpdateFrequency None`](Sandbox.ModAPI.Ingame.None)|Does not run autonomously.|
|static [`UpdateFrequency Update1`](Sandbox.ModAPI.Ingame.Update1)|Run every game tick.|
|static [`UpdateFrequency Update10`](Sandbox.ModAPI.Ingame.Update10)|Run every 10th game tick.|
|static [`UpdateFrequency Update100`](Sandbox.ModAPI.Ingame.Update100)|Run every 100th game tick.|
|static [`UpdateFrequency Once`](Sandbox.ModAPI.Ingame.Once)|Run once before the next tick. Flag is un-set automatically after the update|
