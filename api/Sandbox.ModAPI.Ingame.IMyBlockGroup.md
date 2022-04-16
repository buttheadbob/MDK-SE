← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### IMyBlockGroup Interface

```csharp
public interface IMyBlockGroup
```

Describes terminal block group (PB scripting interface)

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

#### Properties

|Member|Description|
|---|---|
|[string Name { get; }](Sandbox.ModAPI.Ingame.IMyBlockGroup.Name)|Gets name of terminal blocks group|

#### Methods

|Member|Description|
|---|---|
|[void GetBlocks(List&lt;IMyTerminalBlock&gt;, Func&lt;IMyTerminalBlock, bool&gt; = null)](Sandbox.ModAPI.Ingame.IMyBlockGroup.GetBlocks)|Get terminal blocks which assigned to this group|
|[void GetBlocksOfType&lt;T&gt;(List&lt;IMyTerminalBlock&gt;, Func&lt;IMyTerminalBlock, bool&gt; = null)](Sandbox.ModAPI.Ingame.IMyBlockGroup.GetBlocksOfType)||
|[void GetBlocksOfType&lt;T&gt;(List&lt;T&gt;, Func&lt;T, bool&gt; = null)](Sandbox.ModAPI.Ingame.IMyBlockGroup.GetBlocksOfType)||

