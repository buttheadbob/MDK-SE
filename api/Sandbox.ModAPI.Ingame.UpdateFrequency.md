← [Index](index)
# UpdateFrequency Enum
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
## Summary
Flags set how often the script will run itself.
### Fields
<table style="width: 100%">
<tr><td>static [`UpdateFrequency None`](Sandbox.ModAPI.Ingame.None)</td><td>Does not run autonomously.</td></tr>
<tr><td>static [`UpdateFrequency Update1`](Sandbox.ModAPI.Ingame.Update1)</td><td>Run every game tick.</td></tr>
<tr><td>static [`UpdateFrequency Update10`](Sandbox.ModAPI.Ingame.Update10)</td><td>Run every 10th game tick.</td></tr>
<tr><td>static [`UpdateFrequency Update100`](Sandbox.ModAPI.Ingame.Update100)</td><td>Run every 100th game tick.</td></tr>
<tr><td>static [`UpdateFrequency Once`](Sandbox.ModAPI.Ingame.Once)</td><td>Run once before the next tick. Flag is un-set automatically after the update</td></tr>
</table>
