← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### ITerminalAction Interface

```csharp
public interface ITerminalAction
```

**Namespace:** [Sandbox.ModAPI.Interfaces](Sandbox.ModAPI.Interfaces)  
**Assembly:** Sandbox.Common.dll

#### Properties

[string Icon { get; }](Sandbox.ModAPI.Interfaces.ITerminalAction.Icon)

> 

[string Id { get; }](Sandbox.ModAPI.Interfaces.ITerminalAction.Id)

> 

[StringBuilder Name { get; }](Sandbox.ModAPI.Interfaces.ITerminalAction.Name)

> 

#### Methods

[void Apply(IMyCubeBlock block)](Sandbox.ModAPI.Interfaces.ITerminalAction.Apply)

> 

[void Apply(IMyCubeBlock block, ListReader&lt;TerminalActionParameter&gt; terminalActionParameters)](Sandbox.ModAPI.Interfaces.ITerminalAction.Apply)

> 

[bool IsEnabled(IMyCubeBlock block)](Sandbox.ModAPI.Interfaces.ITerminalAction.IsEnabled)

> 

[void WriteValue(IMyCubeBlock block, StringBuilder appendTo)](Sandbox.ModAPI.Interfaces.ITerminalAction.WriteValue)

> 

