← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### ITerminalProperty&lt;TValue&gt; Interface

```csharp
public interface ITerminalProperty<TValue>: ITerminalProperty
```

**Namespace:** [Sandbox.ModAPI.Interfaces](Sandbox.ModAPI.Interfaces)  
**Assembly:** Sandbox.Common.dll

**Implements:**  
* [ITerminalProperty](Sandbox.ModAPI.Interfaces.ITerminalProperty)

#### Properties

|Member|Description|
|---|---|
|\\%1string Id { get; }](Sandbox.ModAPI.Interfaces.ITerminalProperty.Id)|Property Id (value name)<br /><br />_Inherited from [ITerminalProperty](Sandbox.ModAPI.Interfaces.ITerminalProperty)_|
|\\%1string TypeName { get; }](Sandbox.ModAPI.Interfaces.ITerminalProperty.TypeName)|Property type (bool - [System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/system.boolean?view=netframework-4.6) , float - [System.Single](https://docs.microsoft.com/en-us/dotnet/api/system.single?view=netframework-4.6) , color - [Color](VRageMath.Color) )<br /><br />_Inherited from [ITerminalProperty](Sandbox.ModAPI.Interfaces.ITerminalProperty)_|

#### Methods

|Member|Description|
|---|---|
|\\%1TValue GetDefaultValue(IMyCubeBlock)](Sandbox.ModAPI.Interfaces.ITerminalProperty`1.GetDefaultValue)||
|\\%1TValue GetMaximum(IMyCubeBlock)](Sandbox.ModAPI.Interfaces.ITerminalProperty`1.GetMaximum)||
|\\%1TValue GetMinimum(IMyCubeBlock)](Sandbox.ModAPI.Interfaces.ITerminalProperty`1.GetMinimum)||
|\\%1TValue GetMininum(IMyCubeBlock)](Sandbox.ModAPI.Interfaces.ITerminalProperty`1.GetMininum)|_**Obsolete:** Use GetMinimum instead_|
|\\%1TValue GetValue(IMyCubeBlock)](Sandbox.ModAPI.Interfaces.ITerminalProperty`1.GetValue)||
|\\%1void SetValue(IMyCubeBlock, TValue)](Sandbox.ModAPI.Interfaces.ITerminalProperty`1.SetValue)||

