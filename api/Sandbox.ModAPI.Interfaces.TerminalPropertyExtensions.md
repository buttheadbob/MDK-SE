← [Index](index)
# TerminalPropertyExtensions Class
**Namespace:** [`Sandbox.ModAPI.Interfaces`](Sandbox.ModAPI.Interfaces)  
**Assembly:** Sandbox.Common.dll  
## Summary
Terminal block extension for property access
### Methods
<table style="width:100%;display:table">
<tr><td>static [`ITerminalProperty<TValue> As<TValue>(ITerminalProperty property)`](Sandbox.ModAPI.Interfaces.As)</td><td></td></tr>
<tr><td>static [`ITerminalProperty<TValue> Cast<TValue>(ITerminalProperty property)`](Sandbox.ModAPI.Interfaces.Cast)</td><td></td></tr>
<tr><td>static [`bool Is<TValue>(ITerminalProperty property)`](Sandbox.ModAPI.Interfaces.Is)</td><td></td></tr>
<tr><td>static [`ITerminalProperty<float> AsFloat(ITerminalProperty property)`](Sandbox.ModAPI.Interfaces.AsFloat)</td><td>Property type cast</td></tr>
<tr><td>static [`ITerminalProperty<Color> AsColor(ITerminalProperty property)`](Sandbox.ModAPI.Interfaces.AsColor)</td><td>Property type cast</td></tr>
<tr><td>static [`ITerminalProperty<bool> AsBool(ITerminalProperty property)`](Sandbox.ModAPI.Interfaces.AsBool)</td><td>Property type cast</td></tr>
<tr><td>static [`float GetValueFloat(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetValueFloat)</td><td>Returns value of specified property</td></tr>
<tr><td>static [`void SetValueFloat(IMyTerminalBlock block, string propertyId, float value)`](Sandbox.ModAPI.Interfaces.SetValueFloat)</td><td>Set float value of property</td></tr>
<tr><td>static [`bool GetValueBool(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetValueBool)</td><td>Returns value of specified property</td></tr>
<tr><td>static [`void SetValueBool(IMyTerminalBlock block, string propertyId, bool value)`](Sandbox.ModAPI.Interfaces.SetValueBool)</td><td>Set bool value of property</td></tr>
<tr><td>static [`Color GetValueColor(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetValueColor)</td><td>Returns value of specified property</td></tr>
<tr><td>static [`void SetValueColor(IMyTerminalBlock block, string propertyId, Color value)`](Sandbox.ModAPI.Interfaces.SetValueColor)</td><td>Set bool value of property</td></tr>
<tr><td>static [`T GetValue<T>(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetValue)</td><td></td></tr>
<tr><td>static [`T GetDefaultValue<T>(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetDefaultValue)</td><td></td></tr>
<tr><td>static [`T GetMininum<T>(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetMininum)</td><td></td></tr>
<tr><td>static [`T GetMinimum<T>(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetMinimum)</td><td></td></tr>
<tr><td>static [`T GetMaximum<T>(IMyTerminalBlock block, string propertyId)`](Sandbox.ModAPI.Interfaces.GetMaximum)</td><td></td></tr>
<tr><td>static [`void SetValue<T>(IMyTerminalBlock block, string propertyId, T value)`](Sandbox.ModAPI.Interfaces.SetValue)</td><td></td></tr>
</table>
