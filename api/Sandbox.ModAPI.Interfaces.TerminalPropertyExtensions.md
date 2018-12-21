← [Index](index)
# TerminalPropertyExtensions Class
**Namespace:** [`Sandbox.ModAPI.Interfaces`](Sandbox.ModAPI.Interfaces)  
**Assembly:** Sandbox.Common.dll  
## Summary
Terminal block extension for property access
### Methods
|Member|Description|
|---|---|
|static&nbsp;[`ITerminalProperty<TValue>&nbsp;As<TValue>(ITerminalProperty&nbsp;property)`](Sandbox.ModAPI.Interfaces.As)||
|static&nbsp;[`ITerminalProperty<TValue>&nbsp;Cast<TValue>(ITerminalProperty&nbsp;property)`](Sandbox.ModAPI.Interfaces.Cast)||
|static&nbsp;[`bool&nbsp;Is<TValue>(ITerminalProperty&nbsp;property)`](Sandbox.ModAPI.Interfaces.Is)||
|static&nbsp;[`ITerminalProperty<float>&nbsp;AsFloat(ITerminalProperty&nbsp;property)`](Sandbox.ModAPI.Interfaces.AsFloat)|Property type cast|
|static&nbsp;[`ITerminalProperty<Color>&nbsp;AsColor(ITerminalProperty&nbsp;property)`](Sandbox.ModAPI.Interfaces.AsColor)|Property type cast|
|static&nbsp;[`ITerminalProperty<bool>&nbsp;AsBool(ITerminalProperty&nbsp;property)`](Sandbox.ModAPI.Interfaces.AsBool)|Property type cast|
|static&nbsp;[`float&nbsp;GetValueFloat(IMyTerminalBlock&nbsp;block,&nbsp;string&nbsp;propertyId)`](Sandbox.ModAPI.Interfaces.GetValueFloat)|Returns value of specified property|
|static&nbsp;[`void&nbsp;SetValueFloat(IMyTerminalBlock&nbsp;block,&nbsp;string&nbsp;propertyId,&nbsp;float&nbsp;value)`](Sandbox.ModAPI.Interfaces.SetValueFloat)|Set float value of property|
|static&nbsp;[`bool&nbsp;GetValueBool(IMyTerminalBlock&nbsp;block,&nbsp;string&nbsp;propertyId)`](Sandbox.ModAPI.Interfaces.GetValueBool)|Returns value of specified property|
|static&nbsp;[`void&nbsp;SetValueBool(IMyTerminalBlock&nbsp;block,&nbsp;string&nbsp;propertyId,&nbsp;bool&nbsp;value)`](Sandbox.ModAPI.Interfaces.SetValueBool)|Set bool value of property|
|static&nbsp;[`Color&nbsp;GetValueColor(IMyTerminalBlock&nbsp;block,&nbsp;string&nbsp;propertyId)`](Sandbox.ModAPI.Interfaces.GetValueColor)|Returns value of specified property|
|static&nbsp;[`void&nbsp;SetValueColor(IMyTerminalBlock&nbsp;block,&nbsp;string&nbsp;propertyId,&nbsp;Color&nbsp;value)`](Sandbox.ModAPI.Interfaces.SetValueColor)|Set bool value of property|
|static&nbsp;[`T&nbsp;GetValue<T>(IMyTerminalBlock&nbsp;block,&nbsp;string&nbsp;propertyId)`](Sandbox.ModAPI.Interfaces.GetValue)||
|static&nbsp;[`T&nbsp;GetDefaultValue<T>(IMyTerminalBlock&nbsp;block,&nbsp;string&nbsp;propertyId)`](Sandbox.ModAPI.Interfaces.GetDefaultValue)||
|static&nbsp;[`T&nbsp;GetMininum<T>(IMyTerminalBlock&nbsp;block,&nbsp;string&nbsp;propertyId)`](Sandbox.ModAPI.Interfaces.GetMininum)||
|static&nbsp;[`T&nbsp;GetMinimum<T>(IMyTerminalBlock&nbsp;block,&nbsp;string&nbsp;propertyId)`](Sandbox.ModAPI.Interfaces.GetMinimum)||
|static&nbsp;[`T&nbsp;GetMaximum<T>(IMyTerminalBlock&nbsp;block,&nbsp;string&nbsp;propertyId)`](Sandbox.ModAPI.Interfaces.GetMaximum)||
|static&nbsp;[`void&nbsp;SetValue<T>(IMyTerminalBlock&nbsp;block,&nbsp;string&nbsp;propertyId,&nbsp;T&nbsp;value)`](Sandbox.ModAPI.Interfaces.SetValue)||
