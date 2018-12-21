← [Index](index)
# UpdateFrequency Enum
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
## Summary
Flags set how often the script will run itself.
### Fields
<table style="width:100%;display:table">
<tr><td>static _<a href="Sandbox.ModAPI.Ingame.None"><code>UpdateFrequency None</code></a>_</td><td>Does not run autonomously.</td></tr>
<tr><td>static _<a href="Sandbox.ModAPI.Ingame.Update1"><code>UpdateFrequency Update1</code></a>_</td><td>Run every game tick.</td></tr>
<tr><td>static _<a href="Sandbox.ModAPI.Ingame.Update10"><code>UpdateFrequency Update10</code></a>_</td><td>Run every 10th game tick.</td></tr>
<tr><td>static _<a href="Sandbox.ModAPI.Ingame.Update100"><code>UpdateFrequency Update100</code></a>_</td><td>Run every 100th game tick.</td></tr>
<tr><td>static _<a href="Sandbox.ModAPI.Ingame.Once"><code>UpdateFrequency Once</code></a>_</td><td>Run once before the next tick. Flag is un-set automatically after the update</td></tr>
</table>
