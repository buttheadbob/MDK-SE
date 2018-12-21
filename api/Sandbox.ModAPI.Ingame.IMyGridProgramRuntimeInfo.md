← [Index](ApiIndex)
# IMyGridProgramRuntimeInfo Interface
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
## Summary
Provides runtime info for a running grid program.
### Properties
|Member|Description|
|---|---|
|[`TimeSinceLastRun`](Sandbox.ModAPI.Ingame.TimeSinceLastRun)|Gets the time elapsed since the last time the Main method of this program was run. This property returns no valid data neither in the constructor nor the Save method.|
|[`LastRunTimeMs`](Sandbox.ModAPI.Ingame.LastRunTimeMs)|Gets the number of milliseconds it took to execute the Main method the last time it was run. This property returns no valid data neither in the constructor nor the Save method.|
|[`MaxInstructionCount`](Sandbox.ModAPI.Ingame.MaxInstructionCount)|Gets the maximum number of significant instructions that can be executing during a single run, including any other programmable blocks invoked immediately.|
|[`CurrentInstructionCount`](Sandbox.ModAPI.Ingame.CurrentInstructionCount)|Gets the current number of significant instructions executed.|
|[`MaxCallChainDepth`](Sandbox.ModAPI.Ingame.MaxCallChainDepth)|Gets the maximum number of method calls that can be nested into each other.|
|[`CurrentCallChainDepth`](Sandbox.ModAPI.Ingame.CurrentCallChainDepth)|Gets the current number of nested method calls.|
|[`UpdateFrequency`](Sandbox.ModAPI.Ingame.UpdateFrequency)|Gets or sets how frequently this script will run itself|
