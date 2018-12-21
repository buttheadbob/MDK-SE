← [Index](index)
# UpdateType Enum
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
## Summary
Enum describes what source triggered the script to run.
### Fields
|Member|Description|
|---|---|
|static [`None`](Sandbox.ModAPI.Ingame.None)||
|static [`Terminal`](Sandbox.ModAPI.Ingame.Terminal)|Script run by user in the terminal.|
|static [`Trigger`](Sandbox.ModAPI.Ingame.Trigger)|Script run by a block such as timer, sensor.|
|static [`Antenna`](Sandbox.ModAPI.Ingame.Antenna)|Script run by antenna receiving a message.|
|static [`Mod`](Sandbox.ModAPI.Ingame.Mod)|Script run by a mod.|
|static [`Script`](Sandbox.ModAPI.Ingame.Script)|Script run by another programmable block.|
|static [`Update1`](Sandbox.ModAPI.Ingame.Update1)|Script is updating every tick.|
|static [`Update10`](Sandbox.ModAPI.Ingame.Update10)|Script is updating every 10th tick.|
|static [`Update100`](Sandbox.ModAPI.Ingame.Update100)|Script is updating every 100th tick.|
|static [`Once`](Sandbox.ModAPI.Ingame.Once)|Script is updating once before the tick.|
