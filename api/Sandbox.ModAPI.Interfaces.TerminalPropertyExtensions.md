← [Index](index)
# TerminalPropertyExtensions Class
**Namespace:** [`Sandbox.ModAPI.Interfaces`](Sandbox.ModAPI.Interfaces)  
**Assembly:** Sandbox.Common.dll  
## Summary
Terminal block extension for property access
### Methods
|Member|Description|
|---|---|
|static [`ITerminalProperty<TValue> As<TValue>(Sandbox.ModAPI.Interfaces.ITerminalProperty)`](Sandbox.ModAPI.Interfaces.As)||
|static [`ITerminalProperty<TValue> Cast<TValue>(Sandbox.ModAPI.Interfaces.ITerminalProperty)`](Sandbox.ModAPI.Interfaces.Cast)||
|static [`bool Is<TValue>(Sandbox.ModAPI.Interfaces.ITerminalProperty)`](Sandbox.ModAPI.Interfaces.Is)||
|static [`ITerminalProperty<System.Single> AsFloat(Sandbox.ModAPI.Interfaces.ITerminalProperty)`](Sandbox.ModAPI.Interfaces.AsFloat)|Property type cast|
|static [`ITerminalProperty<VRageMath.Color> AsColor(Sandbox.ModAPI.Interfaces.ITerminalProperty)`](Sandbox.ModAPI.Interfaces.AsColor)|Property type cast|
|static [`ITerminalProperty<System.Boolean> AsBool(Sandbox.ModAPI.Interfaces.ITerminalProperty)`](Sandbox.ModAPI.Interfaces.AsBool)|Property type cast|
|static [`float GetValueFloat(Sandbox.ModAPI.Ingame.IMyTerminalBlock, string)`](Sandbox.ModAPI.Interfaces.GetValueFloat)|Returns value of specified property|
|static [`void SetValueFloat(Sandbox.ModAPI.Ingame.IMyTerminalBlock, string, float)`](Sandbox.ModAPI.Interfaces.SetValueFloat)|Set float value of property|
|static [`bool GetValueBool(Sandbox.ModAPI.Ingame.IMyTerminalBlock, string)`](Sandbox.ModAPI.Interfaces.GetValueBool)|Returns value of specified property|
|static [`void SetValueBool(Sandbox.ModAPI.Ingame.IMyTerminalBlock, string, bool)`](Sandbox.ModAPI.Interfaces.SetValueBool)|Set bool value of property|
|static [`VRageMath.Color GetValueColor(Sandbox.ModAPI.Ingame.IMyTerminalBlock, string)`](Sandbox.ModAPI.Interfaces.GetValueColor)|Returns value of specified property|
|static [`void SetValueColor(Sandbox.ModAPI.Ingame.IMyTerminalBlock, string, VRageMath.Color)`](Sandbox.ModAPI.Interfaces.SetValueColor)|Set bool value of property|
|static [`Sandbox.ModAPI.Interfaces.T GetValue<T>(Sandbox.ModAPI.Ingame.IMyTerminalBlock, string)`](Sandbox.ModAPI.Interfaces.GetValue)||
|static [`Sandbox.ModAPI.Interfaces.T GetDefaultValue<T>(Sandbox.ModAPI.Ingame.IMyTerminalBlock, string)`](Sandbox.ModAPI.Interfaces.GetDefaultValue)||
|static [`Sandbox.ModAPI.Interfaces.T GetMininum<T>(Sandbox.ModAPI.Ingame.IMyTerminalBlock, string)`](Sandbox.ModAPI.Interfaces.GetMininum)||
|static [`Sandbox.ModAPI.Interfaces.T GetMinimum<T>(Sandbox.ModAPI.Ingame.IMyTerminalBlock, string)`](Sandbox.ModAPI.Interfaces.GetMinimum)||
|static [`Sandbox.ModAPI.Interfaces.T GetMaximum<T>(Sandbox.ModAPI.Ingame.IMyTerminalBlock, string)`](Sandbox.ModAPI.Interfaces.GetMaximum)||
|static [`void SetValue<T>(Sandbox.ModAPI.Ingame.IMyTerminalBlock, string, Sandbox.ModAPI.Interfaces.T)`](Sandbox.ModAPI.Interfaces.SetValue)||
