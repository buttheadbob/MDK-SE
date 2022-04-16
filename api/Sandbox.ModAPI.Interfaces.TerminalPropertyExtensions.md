← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### TerminalPropertyExtensions Class

```csharp
public abstract sealed class TerminalPropertyExtensions
```

Terminal block extension for property access

**Namespace:** [Sandbox.ModAPI.Interfaces](Sandbox.ModAPI.Interfaces)  
**Assembly:** Sandbox.Common.dll

#### Methods

|Member|Description|
|---|---|
|[static ITerminalProperty&lt;TValue&gt; As&lt;TValue&gt;(this ITerminalProperty)](Sandbox.ModAPI.Interfaces.TerminalPropertyExtensions.As)||
|[static ITerminalProperty&lt;bool&gt; AsBool(this ITerminalProperty)](Sandbox.ModAPI.Interfaces.TerminalPropertyExtensions.AsBool)|Property type cast|
|[static ITerminalProperty&lt;Color&gt; AsColor(this ITerminalProperty)](Sandbox.ModAPI.Interfaces.TerminalPropertyExtensions.AsColor)|Property type cast|
|[static ITerminalProperty&lt;float&gt; AsFloat(this ITerminalProperty)](Sandbox.ModAPI.Interfaces.TerminalPropertyExtensions.AsFloat)|Property type cast|
|[static ITerminalProperty&lt;TValue&gt; Cast&lt;TValue&gt;(this ITerminalProperty)](Sandbox.ModAPI.Interfaces.TerminalPropertyExtensions.Cast)||
|[static T GetDefaultValue&lt;T&gt;(this IMyTerminalBlock, string)](Sandbox.ModAPI.Interfaces.TerminalPropertyExtensions.GetDefaultValue)||
|[static T GetMaximum&lt;T&gt;(this IMyTerminalBlock, string)](Sandbox.ModAPI.Interfaces.TerminalPropertyExtensions.GetMaximum)||
|[static T GetMinimum&lt;T&gt;(this IMyTerminalBlock, string)](Sandbox.ModAPI.Interfaces.TerminalPropertyExtensions.GetMinimum)||
|[static T GetMininum&lt;T&gt;(this IMyTerminalBlock, string)](Sandbox.ModAPI.Interfaces.TerminalPropertyExtensions.GetMininum)|_**Obsolete:** Use GetMinimum instead_|
|[static T GetValue&lt;T&gt;(this IMyTerminalBlock, string)](Sandbox.ModAPI.Interfaces.TerminalPropertyExtensions.GetValue)||
|[static bool GetValueBool(this IMyTerminalBlock, string)](Sandbox.ModAPI.Interfaces.TerminalPropertyExtensions.GetValueBool)|Returns value of specified property|
|[static Color GetValueColor(this IMyTerminalBlock, string)](Sandbox.ModAPI.Interfaces.TerminalPropertyExtensions.GetValueColor)|Returns value of specified property|
|[static float GetValueFloat(this IMyTerminalBlock, string)](Sandbox.ModAPI.Interfaces.TerminalPropertyExtensions.GetValueFloat)|Returns value of specified property|
|[static bool Is&lt;TValue&gt;(this ITerminalProperty)](Sandbox.ModAPI.Interfaces.TerminalPropertyExtensions.Is)||
|[static void SetValue&lt;T&gt;(this IMyTerminalBlock, string, T)](Sandbox.ModAPI.Interfaces.TerminalPropertyExtensions.SetValue)||
|[static void SetValueBool(this IMyTerminalBlock, string, bool)](Sandbox.ModAPI.Interfaces.TerminalPropertyExtensions.SetValueBool)|Set bool value of property|
|[static void SetValueColor(this IMyTerminalBlock, string, Color)](Sandbox.ModAPI.Interfaces.TerminalPropertyExtensions.SetValueColor)|Set bool value of property|
|[static void SetValueFloat(this IMyTerminalBlock, string, float)](Sandbox.ModAPI.Interfaces.TerminalPropertyExtensions.SetValueFloat)|Set float value of property|

