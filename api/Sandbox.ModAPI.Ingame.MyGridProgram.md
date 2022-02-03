← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MyGridProgram Class

```csharp
public abstract class MyGridProgram: IMyGridProgram
```

All programmable block scripts derive from this class, meaning that all properties in this class are directly available for use in your scripts. If you use Visual Studio or other external editors to write your scripts, you can derive directly from this class and have a compatible script template.

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

**Implements:**  
* [IMyGridProgram](Sandbox.ModAPI.IMyGridProgram)

#### Example

```csharp  
public void Main()  
{  
    // Print out the time elapsed since the currently running programmable block was run  
    // the last time.  
    Echo(Me.CustomName + " was last run " + Runtime.TimeSinceLastRun.TotalSeconds + " seconds ago.");  
}  
  
```

#### Properties

|Member|Description|
|---|---|
|[GridTerminalSystem { get; protected set; }](Sandbox.ModAPI.Ingame.MyGridProgram.GridTerminalSystem)|Provides access to the grid terminal system as viewed from this programmable block.|
|[Me { get; protected set; }](Sandbox.ModAPI.Ingame.MyGridProgram.Me)|Gets a reference to the currently running programmable block.|
|[Runtime { get; protected set; }](Sandbox.ModAPI.Ingame.MyGridProgram.Runtime)|Gets runtime information for the running grid program.|
|[Storage { get; protected set; }](Sandbox.ModAPI.Ingame.MyGridProgram.Storage)|Allows you to store data between game sessions.|
|[Echo { get; protected set; }](Sandbox.ModAPI.Ingame.MyGridProgram.Echo)|Prints out text onto the currently running programmable block's detail info area.|
|[IGC { get; }](Sandbox.ModAPI.Ingame.MyGridProgram.IGC)||

