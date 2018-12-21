← [Index](index)
# TerminalPropertyExtensions Class
**Namespace:** [`Sandbox.ModAPI.Interfaces`](Sandbox.ModAPI.Interfaces)  
**Assembly:** Sandbox.Common.dll  
## Summary
Terminal block extension for property access
### Methods
|Member|Description|
|---|---|
|[`ITerminalProperty<TValue> As<TValue>(ITerminalProperty property)`](Sandbox.ModAPI.Interfaces.As)||
|[`ITerminalProperty<TValue> Cast<TValue>(ITerminalProperty property)`](Sandbox.ModAPI.Interfaces.Cast)||
|[`bool Is<TValue>(ITerminalProperty property)`](Sandbox.ModAPI.Interfaces.Is)||
|[`ITerminalProperty<float> AsFloat(ITerminalProperty property)`](Sandbox.ModAPI.Interfaces.AsFloat)|Property type cast|
|[`ITerminalProperty<Color> AsColor(ITerminalProperty property)`](Sandbox.ModAPI.Interfaces.AsColor)|Property type cast|
|[`ITerminalProperty<bool> AsBool(ITerminalProperty property)`](Sandbox.ModAPI.Interfaces.AsBool)|Property type cast|
|[`float GetValueFloat(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetValueFloat)||
|[`void SetValueFloat(IMyTerminalBlock block, string propertyId, float value)`](Sandbox.ModAPI.Interfaces.SetValueFloat)||
|[`bool GetValueBool(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetValueBool)||
|[`void SetValueBool(IMyTerminalBlock block, string propertyId, bool value)`](Sandbox.ModAPI.Interfaces.SetValueBool)||
|[`Color GetValueColor(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetValueColor)||
|[`void SetValueColor(IMyTerminalBlock block, string propertyId, Color value)`](Sandbox.ModAPI.Interfaces.SetValueColor)||
|[`T GetValue<T>(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetValue)||
|[`T GetDefaultValue<T>(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetDefaultValue)||
|[`T GetMininum<T>(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetMininum)||
|[`T GetMinimum<T>(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetMinimum)||
|[`T GetMaximum<T>(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetMaximum)||
|[`void SetValue<T>(IMyTerminalBlock block, string propertyId, T value)`](Sandbox.ModAPI.Interfaces.SetValue)||
