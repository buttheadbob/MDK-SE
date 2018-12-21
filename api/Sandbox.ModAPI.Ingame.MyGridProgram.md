← [Index](index)
# MyGridProgram Class
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
## Summary
All programmable block scripts derive from this class, meaning that all properties in this class are directly available for use in your scripts. If you use Visual Studio or other external editors to write your scripts, you can derive directly from this class and have a compatible script template.
## Example
```csharp
public void Main() { // Print out the time elapsed since the currently running programmable block was run // the last time. Echo(Me.CustomName + " was last run " + Runtime.TimeSinceLastRun.TotalSeconds + " seconds ago."); }
```

### Properties
|Member|Description|
|---|---|
|[`IMyGridTerminalSystem GridTerminalSystem`](Sandbox.ModAPI.Ingame.GridTerminalSystem)||
|[`IMyProgrammableBlock Me`](Sandbox.ModAPI.Ingame.Me)||
|[`TimeSpan ElapsedTime`](Sandbox.ModAPI.Ingame.ElapsedTime)||
|[`IMyGridProgramRuntimeInfo Runtime`](Sandbox.ModAPI.Ingame.Runtime)||
|[`string Storage`](Sandbox.ModAPI.Ingame.Storage)||
|[`Action<string> Echo`](Sandbox.ModAPI.Ingame.Echo)||
