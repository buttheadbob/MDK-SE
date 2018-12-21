← [Index](index)
# IMyGridProgramRuntimeInfo Interface
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
## Summary
Provides runtime info for a running grid program.
### Properties
<table style="width: 100%">
<tr><td>[`TimeSpan TimeSinceLastRun`](Sandbox.ModAPI.Ingame.TimeSinceLastRun)</td><td>Gets the time elapsed since the last time the Main method of this program was run. This property returns no valid data neither in the constructor nor the Save method.</td></tr>
<tr><td>[`double LastRunTimeMs`](Sandbox.ModAPI.Ingame.LastRunTimeMs)</td><td>Gets the number of milliseconds it took to execute the Main method the last time it was run. This property returns no valid data neither in the constructor nor the Save method.</td></tr>
<tr><td>[`int MaxInstructionCount`](Sandbox.ModAPI.Ingame.MaxInstructionCount)</td><td>Gets the maximum number of significant instructions that can be executing during a single run, including any other programmable blocks invoked immediately.</td></tr>
<tr><td>[`int CurrentInstructionCount`](Sandbox.ModAPI.Ingame.CurrentInstructionCount)</td><td>Gets the current number of significant instructions executed.</td></tr>
<tr><td>[`int MaxCallChainDepth`](Sandbox.ModAPI.Ingame.MaxCallChainDepth)</td><td>Gets the maximum number of method calls that can be nested into each other.</td></tr>
<tr><td>[`int CurrentCallChainDepth`](Sandbox.ModAPI.Ingame.CurrentCallChainDepth)</td><td>Gets the current number of nested method calls.</td></tr>
<tr><td>[`UpdateFrequency UpdateFrequency`](Sandbox.ModAPI.Ingame.UpdateFrequency)</td><td>Gets or sets how frequently this script will run itself</td></tr>
</table>
