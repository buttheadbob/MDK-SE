← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### IMyBlockGroup Interface

```csharp
public interface IMyBlockGroup
```

Describes terminal block group (PB scripting interface)

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

#### Properties

[string Name { get; }](Sandbox.ModAPI.Ingame.IMyBlockGroup.Name)

> Gets name of terminal blocks group

#### Methods

[void GetBlocks(List&lt;IMyTerminalBlock&gt; blocks, Func&lt;IMyTerminalBlock, bool&gt; collect = null)](Sandbox.ModAPI.Ingame.IMyBlockGroup.GetBlocks)

> Get terminal blocks which assigned to this group

[void GetBlocksOfType&lt;T&gt;(List&lt;IMyTerminalBlock&gt; blocks, Func&lt;IMyTerminalBlock, bool&gt; collect = null)](Sandbox.ModAPI.Ingame.IMyBlockGroup.GetBlocksOfType)

> 

[void GetBlocksOfType&lt;T&gt;(List&lt;T&gt; blocks, Func&lt;T, bool&gt; collect = null)](Sandbox.ModAPI.Ingame.IMyBlockGroup.GetBlocksOfType)

> 

