← [Index](index)
# ITerminalProperty Interface
**Namespace:** [`Sandbox.ModAPI.Interfaces`](Sandbox.ModAPI.Interfaces)  
**Assembly:** Sandbox.Common.dll  
**Implements:**
* [`Sandbox.ModAPI.Interfaces.ITerminalProperty`](Sandbox.ModAPI.Interfaces.ITerminalProperty)
### Properties
|Member|Description|
|---|---|
|[`string Id`](Sandbox.ModAPI.Interfaces.Id)|Property Id (value name)<br/><br/>_Inherited from [`ITerminalProperty`](Sandbox.ModAPI.Interfaces.ITerminalProperty)_|
|[`string TypeName`](Sandbox.ModAPI.Interfaces.TypeName)|Property type (bool - [System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/system.boolean?view=netframework-4.6) , float - [System.Single](https://docs.microsoft.com/en-us/dotnet/api/system.single?view=netframework-4.6) , color - [Color](VRageMath.Color) )<br/><br/>_Inherited from [`ITerminalProperty`](Sandbox.ModAPI.Interfaces.ITerminalProperty)_|
### Methods
|Member|Description|
|---|---|
|[`TValue GetValue(IMyCubeBlock block)`](Sandbox.ModAPI.Interfaces.GetValue)||
|[`void SetValue(IMyCubeBlock block, TValue value)`](Sandbox.ModAPI.Interfaces.SetValue)||
|[`TValue GetDefaultValue(IMyCubeBlock block)`](Sandbox.ModAPI.Interfaces.GetDefaultValue)||
|[`TValue GetMininum(IMyCubeBlock block)`](Sandbox.ModAPI.Interfaces.GetMininum)||
|[`TValue GetMinimum(IMyCubeBlock block)`](Sandbox.ModAPI.Interfaces.GetMinimum)||
|[`TValue GetMaximum(IMyCubeBlock block)`](Sandbox.ModAPI.Interfaces.GetMaximum)||
