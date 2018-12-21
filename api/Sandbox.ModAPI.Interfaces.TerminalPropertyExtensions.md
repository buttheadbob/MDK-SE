← [Index](index.md)
#TerminalPropertyExtensions Class
**Namespace:** Sandbox.ModAPI.Interfaces  
**Assembly:** Sandbox.Common.dll  
##Summary
Terminal block extension for property access
###Methods
|Member|Description|
|---|---|
|[`ITerminalProperty<TValue> As<TValue>(ITerminalProperty property)`](Sandbox.ModAPI.Interfaces.As.md)||
|[`ITerminalProperty<TValue> Cast<TValue>(ITerminalProperty property)`](Sandbox.ModAPI.Interfaces.Cast.md)||
|[`bool Is<TValue>(ITerminalProperty property)`](Sandbox.ModAPI.Interfaces.Is.md)||
|[`ITerminalProperty<float> AsFloat(ITerminalProperty property)`](Sandbox.ModAPI.Interfaces.AsFloat.md)|Property type cast|
|[`ITerminalProperty<Color> AsColor(ITerminalProperty property)`](Sandbox.ModAPI.Interfaces.AsColor.md)|Property type cast|
|[`ITerminalProperty<bool> AsBool(ITerminalProperty property)`](Sandbox.ModAPI.Interfaces.AsBool.md)|Property type cast|
|[`float GetValueFloat(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetValueFloat.md)||
|[`void SetValueFloat(IMyTerminalBlock block, string propertyId, float value)`](Sandbox.ModAPI.Interfaces.SetValueFloat.md)||
|[`bool GetValueBool(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetValueBool.md)||
|[`void SetValueBool(IMyTerminalBlock block, string propertyId, bool value)`](Sandbox.ModAPI.Interfaces.SetValueBool.md)||
|[`Color GetValueColor(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetValueColor.md)||
|[`void SetValueColor(IMyTerminalBlock block, string propertyId, Color value)`](Sandbox.ModAPI.Interfaces.SetValueColor.md)||
|[`T GetValue<T>(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetValue.md)||
|[`T GetDefaultValue<T>(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetDefaultValue.md)||
|[`T GetMininum<T>(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetMininum.md)||
|[`T GetMinimum<T>(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetMinimum.md)||
|[`T GetMaximum<T>(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetMaximum.md)||
|[`void SetValue<T>(IMyTerminalBlock block, string propertyId, T value)`](Sandbox.ModAPI.Interfaces.SetValue.md)||
