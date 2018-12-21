← [Index](index)
# ITerminalProperty Interface
**Namespace:** [`Sandbox.ModAPI.Interfaces`](Sandbox.ModAPI.Interfaces)  
**Assembly:** Sandbox.Common.dll  
**Implements:**
* [`Sandbox.ModAPI.Interfaces.ITerminalProperty`](Sandbox.ModAPI.Interfaces.ITerminalProperty)
### Properties
<table style="width: 100%">
<tr><td>[`string Id`](Sandbox.ModAPI.Interfaces.Id)</td><td>Property Id (value name)<br/><br/>_Inherited from [`ITerminalProperty`](Sandbox.ModAPI.Interfaces.ITerminalProperty)_</td></tr>
<tr><td>[`string TypeName`](Sandbox.ModAPI.Interfaces.TypeName)</td><td>Property type (bool - [System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/system.boolean?view=netframework-4.6) , float - [System.Single](https://docs.microsoft.com/en-us/dotnet/api/system.single?view=netframework-4.6) , color - [Color](VRageMath.Color) )<br/><br/>_Inherited from [`ITerminalProperty`](Sandbox.ModAPI.Interfaces.ITerminalProperty)_</td></tr>
</table>
### Methods
<table style="width: 100%">
<tr><td>[`TValue GetValue(IMyCubeBlock block)`](Sandbox.ModAPI.Interfaces.GetValue)</td><td></td></tr>
<tr><td>[`void SetValue(IMyCubeBlock block, TValue value)`](Sandbox.ModAPI.Interfaces.SetValue)</td><td></td></tr>
<tr><td>[`TValue GetDefaultValue(IMyCubeBlock block)`](Sandbox.ModAPI.Interfaces.GetDefaultValue)</td><td></td></tr>
<tr><td>[`TValue GetMininum(IMyCubeBlock block)`](Sandbox.ModAPI.Interfaces.GetMininum)</td><td></td></tr>
<tr><td>[`TValue GetMinimum(IMyCubeBlock block)`](Sandbox.ModAPI.Interfaces.GetMinimum)</td><td></td></tr>
<tr><td>[`TValue GetMaximum(IMyCubeBlock block)`](Sandbox.ModAPI.Interfaces.GetMaximum)</td><td></td></tr>
</table>
