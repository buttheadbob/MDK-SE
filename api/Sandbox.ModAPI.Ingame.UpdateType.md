← [Index](index)
# UpdateType Enum
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
## Summary
Enum describes what source triggered the script to run.
### Fields
|Member|Description|
|---|---|
|static [`UpdateType None`](Sandbox.ModAPI.Ingame.None)||
|static [`UpdateType Terminal`](Sandbox.ModAPI.Ingame.Terminal)|Script run by user in the terminal.|
|static [`UpdateType Trigger`](Sandbox.ModAPI.Ingame.Trigger)|Script run by a block such as timer, sensor.|
|static [`UpdateType Antenna`](Sandbox.ModAPI.Ingame.Antenna)|Script run by antenna receiving a message.|
|static [`UpdateType Mod`](Sandbox.ModAPI.Ingame.Mod)|Script run by a mod.|
|static [`UpdateType Script`](Sandbox.ModAPI.Ingame.Script)|Script run by another programmable block.|
|static [`UpdateType Update1`](Sandbox.ModAPI.Ingame.Update1)|Script is updating every tick.|
|static [`UpdateType Update10`](Sandbox.ModAPI.Ingame.Update10)|Script is updating every 10th tick.|
|static [`UpdateType Update100`](Sandbox.ModAPI.Ingame.Update100)|Script is updating every 100th tick.|
|static [`UpdateType Once`](Sandbox.ModAPI.Ingame.Once)|Script is updating once before the tick.|
