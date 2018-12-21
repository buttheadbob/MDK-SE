← [Index](index)
# TerminalPropertyExtensions Class
**Namespace:** [`Sandbox.ModAPI.Interfaces`](Sandbox.ModAPI.Interfaces)  
**Assembly:** Sandbox.Common.dll  
## Summary
Terminal block extension for property access
### Methods
|Member|Description|
|---|---|
|static [`ITerminalProperty<TValue> As<TValue>(ITerminalProperty property)`](Sandbox.ModAPI.Interfaces.As)||
|static [`ITerminalProperty<TValue> Cast<TValue>(ITerminalProperty property)`](Sandbox.ModAPI.Interfaces.Cast)||
|static [`bool Is<TValue>(ITerminalProperty property)`](Sandbox.ModAPI.Interfaces.Is)||
|static [`ITerminalProperty<float> AsFloat(ITerminalProperty property)`](Sandbox.ModAPI.Interfaces.AsFloat)|Property type cast|
|static [`ITerminalProperty<Color> AsColor(ITerminalProperty property)`](Sandbox.ModAPI.Interfaces.AsColor)|Property type cast|
|static [`ITerminalProperty<bool> AsBool(ITerminalProperty property)`](Sandbox.ModAPI.Interfaces.AsBool)|Property type cast|
|static [`float GetValueFloat(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetValueFloat)|Returns value of specified property|
|static [`void SetValueFloat(IMyTerminalBlock block, string propertyId, float value)`](Sandbox.ModAPI.Interfaces.SetValueFloat)|Set float value of property|
|static [`bool GetValueBool(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetValueBool)|Returns value of specified property|
|static [`void SetValueBool(IMyTerminalBlock block, string propertyId, bool value)`](Sandbox.ModAPI.Interfaces.SetValueBool)|Set bool value of property|
|static [`Color GetValueColor(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetValueColor)|Returns value of specified property|
|static [`void SetValueColor(IMyTerminalBlock block, string propertyId, Color value)`](Sandbox.ModAPI.Interfaces.SetValueColor)|Set bool value of property|
|static [`T GetValue<T>(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetValue)||
|static [`T GetDefaultValue<T>(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetDefaultValue)||
|static [`T GetMininum<T>(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetMininum)||
|static [`T GetMinimum<T>(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetMinimum)||
|static [`T GetMaximum<T>(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetMaximum)||
|static [`void SetValue<T>(IMyTerminalBlock block, string propertyId, T value)`](Sandbox.ModAPI.Interfaces.SetValue)||
