← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### IMyGridProgramRuntimeInfo Interface

```csharp
public interface IMyGridProgramRuntimeInfo
```

Provides runtime info for a running grid program.

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

#### Properties

|Member|Description|
|---|---|
|\$1int CurrentCallChainDepth { get; }](Sandbox.ModAPI.Ingame.IMyGridProgramRuntimeInfo.CurrentCallChainDepth)|Gets the current number of nested method calls.|
|\$1int CurrentInstructionCount { get; }](Sandbox.ModAPI.Ingame.IMyGridProgramRuntimeInfo.CurrentInstructionCount)|Gets the current number of significant instructions executed.|
|\$1double LastRunTimeMs { get; }](Sandbox.ModAPI.Ingame.IMyGridProgramRuntimeInfo.LastRunTimeMs)|Gets the number of milliseconds it took to execute the Main method the last time it was run. This property returns no valid data neither in the constructor nor the Save method.|
|\$1int MaxCallChainDepth { get; }](Sandbox.ModAPI.Ingame.IMyGridProgramRuntimeInfo.MaxCallChainDepth)|Gets the maximum number of method calls that can be nested into each other.|
|\$1int MaxInstructionCount { get; }](Sandbox.ModAPI.Ingame.IMyGridProgramRuntimeInfo.MaxInstructionCount)|Gets the maximum number of significant instructions that can be executing during a single run, including any other programmable blocks invoked immediately.|
|\$1TimeSpan TimeSinceLastRun { get; }](Sandbox.ModAPI.Ingame.IMyGridProgramRuntimeInfo.TimeSinceLastRun)|Gets the time elapsed since the last time the Main method of this program was run. This property returns no valid data neither in the constructor nor the Save method.|
|\$1UpdateFrequency UpdateFrequency { get; set; }](Sandbox.ModAPI.Ingame.IMyGridProgramRuntimeInfo.UpdateFrequency)|Gets or sets how frequently this script will run itself|

