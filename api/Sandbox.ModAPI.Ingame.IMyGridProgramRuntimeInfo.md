← [Index](index)
# IMyGridProgramRuntimeInfo Interface
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
## Summary
Provides runtime info for a running grid program.
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="Sandbox.ModAPI.Ingame.TimeSinceLastRun"><code>TimeSpan TimeSinceLastRun</code></a>_</td><td>Gets the time elapsed since the last time the Main method of this program was run. This property returns no valid data neither in the constructor nor the Save method.</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.LastRunTimeMs"><code>double LastRunTimeMs</code></a>_</td><td>Gets the number of milliseconds it took to execute the Main method the last time it was run. This property returns no valid data neither in the constructor nor the Save method.</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.MaxInstructionCount"><code>int MaxInstructionCount</code></a>_</td><td>Gets the maximum number of significant instructions that can be executing during a single run, including any other programmable blocks invoked immediately.</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.CurrentInstructionCount"><code>int CurrentInstructionCount</code></a>_</td><td>Gets the current number of significant instructions executed.</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.MaxCallChainDepth"><code>int MaxCallChainDepth</code></a>_</td><td>Gets the maximum number of method calls that can be nested into each other.</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.CurrentCallChainDepth"><code>int CurrentCallChainDepth</code></a>_</td><td>Gets the current number of nested method calls.</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.UpdateFrequency"><code>UpdateFrequency UpdateFrequency</code></a>_</td><td>Gets or sets how frequently this script will run itself</td></tr>
</table>
