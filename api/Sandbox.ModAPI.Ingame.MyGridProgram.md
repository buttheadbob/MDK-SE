← [Index](index)
# MyGridProgram Class
**Namespace:** [`Sandbox.ModAPI.Ingame`](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll  
## Summary
All programmable block scripts derive from this class, meaning that all properties in this class are directly available for use in your scripts. If you use Visual Studio or other external editors to write your scripts, you can derive directly from this class and have a compatible script template.
## Example
```csharp
public void Main()
{
    // Print out the time elapsed since the currently running programmable block was run
    // the last time.
    Echo(Me.CustomName + " was last run " + Runtime.TimeSinceLastRun.TotalSeconds + " seconds ago.");
}
```

### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="Sandbox.ModAPI.Ingame.GridTerminalSystem"><code>IMyGridTerminalSystem GridTerminalSystem</code></a>_</td><td>Provides access to the grid terminal system as viewed from this programmable block.</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.Me"><code>IMyProgrammableBlock Me</code></a>_</td><td>Gets a reference to the currently running programmable block.</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.ElapsedTime"><code>TimeSpan ElapsedTime</code></a>_</td><td>Gets the amount of in-game time elapsed from the previous run.</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.Runtime"><code>IMyGridProgramRuntimeInfo Runtime</code></a>_</td><td>Gets runtime information for the running grid program.</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.Storage"><code>string Storage</code></a>_</td><td>Allows you to store data between game sessions.</td></tr>
<tr><td>_<a href="Sandbox.ModAPI.Ingame.Echo"><code>Action<string> Echo</code></a>_</td><td>Prints out text onto the currently running programmable block's detail info area.</td></tr>
</table>
