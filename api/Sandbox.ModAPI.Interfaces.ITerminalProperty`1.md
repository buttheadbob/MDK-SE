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

[string Id { get; }](Sandbox.ModAPI.Interfaces.ITerminalProperty.Id)

> Property Id (value name)  
>   
> _Inherited from [ITerminalProperty](Sandbox.ModAPI.Interfaces.ITerminalProperty)_

[string TypeName { get; }](Sandbox.ModAPI.Interfaces.ITerminalProperty.TypeName)

> Property type (bool - [System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/system.boolean?view=netframework-4.6) , float - [System.Single](https://docs.microsoft.com/en-us/dotnet/api/system.single?view=netframework-4.6) , color - [Color](VRageMath.Color) )  
>   
> _Inherited from [ITerminalProperty](Sandbox.ModAPI.Interfaces.ITerminalProperty)_

#### Methods

[TValue GetDefaultValue(IMyCubeBlock)](Sandbox.ModAPI.Interfaces.ITerminalProperty`1.GetDefaultValue)

> 

[TValue GetMaximum(IMyCubeBlock)](Sandbox.ModAPI.Interfaces.ITerminalProperty`1.GetMaximum)

> 

[TValue GetMinimum(IMyCubeBlock)](Sandbox.ModAPI.Interfaces.ITerminalProperty`1.GetMinimum)

> 

[TValue GetMininum(IMyCubeBlock)](Sandbox.ModAPI.Interfaces.ITerminalProperty`1.GetMininum)

> _**Obsolete:** Use GetMinimum instead_

[TValue GetValue(IMyCubeBlock)](Sandbox.ModAPI.Interfaces.ITerminalProperty`1.GetValue)

> 

[void SetValue(IMyCubeBlock, TValue)](Sandbox.ModAPI.Interfaces.ITerminalProperty`1.SetValue)

> 

