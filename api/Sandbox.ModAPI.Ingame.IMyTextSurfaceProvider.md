← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### IMyTextSurfaceProvider Interface

```csharp
public interface IMyTextSurfaceProvider
```

Describes block, that has at least 1 text surface (PB scripting interface)

**Namespace:** [Sandbox.ModAPI.Ingame](Sandbox.ModAPI.Ingame)  
**Assembly:** Sandbox.Common.dll

**Inheritors:**  
* [IMyCockpit](Sandbox.ModAPI.Ingame.IMyCockpit)  
* [IMyCryoChamber](Sandbox.ModAPI.Ingame.IMyCryoChamber)  
* [IMyProgrammableBlock](Sandbox.ModAPI.Ingame.IMyProgrammableBlock)  
* [IMyProjector](Sandbox.ModAPI.Ingame.IMyProjector)

#### Properties

|Member|Description|
|---|---|
|\\$1int SurfaceCount { get; }](Sandbox.ModAPI.Ingame.IMyTextSurfaceProvider.SurfaceCount)|Get surfaces count|
|\\$1bool UseGenericLcd { get; }](Sandbox.ModAPI.Ingame.IMyTextSurfaceProvider.UseGenericLcd)|Whether generic LCD terminal controls should be created|

#### Methods

|Member|Description|
|---|---|
|\\$1IMyTextSurface GetSurface(int)](Sandbox.ModAPI.Ingame.IMyTextSurfaceProvider.GetSurface)|Get surface by index|

