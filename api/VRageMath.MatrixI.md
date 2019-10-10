← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MatrixI Struct

```csharp
public struct MatrixI
```

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

#### Fields

|Member|Description|
|---|---|
|[Right](VRageMath.MatrixI.Right)||
|[Up](VRageMath.MatrixI.Up)||
|[Backward](VRageMath.MatrixI.Backward)||
|[Translation](VRageMath.MatrixI.Translation)||

#### Properties

|Member|Description|
|---|---|
|[Left](VRageMath.MatrixI.Left)||
|[Down](VRageMath.MatrixI.Down)||
|[Forward](VRageMath.MatrixI.Forward)||
|[RightVector](VRageMath.MatrixI.RightVector)||
|[LeftVector](VRageMath.MatrixI.LeftVector)||
|[UpVector](VRageMath.MatrixI.UpVector)||
|[DownVector](VRageMath.MatrixI.DownVector)||
|[BackwardVector](VRageMath.MatrixI.BackwardVector)||
|[ForwardVector](VRageMath.MatrixI.ForwardVector)||

#### Constructors

|Member|Description|
|---|---|
|[MatrixI(ref Vector3I, Direction, Direction)](VRageMath.MatrixI..ctor)||
|[MatrixI(Vector3I, Direction, Direction)](VRageMath.MatrixI..ctor)||
|[MatrixI(Direction, Direction)](VRageMath.MatrixI..ctor)||
|[MatrixI(ref Vector3I, ref Vector3I, ref Vector3I)](VRageMath.MatrixI..ctor)||
|[MatrixI(ref Vector3I, ref Vector3, ref Vector3)](VRageMath.MatrixI..ctor)||
|[MatrixI(MyBlockOrientation)](VRageMath.MatrixI..ctor)||

#### Methods

|Member|Description|
|---|---|
|[GetDirection(Direction)](VRageMath.MatrixI.GetDirection)||
|[SetDirection(Direction, Direction)](VRageMath.MatrixI.SetDirection)||
|[GetBlockOrientation()](VRageMath.MatrixI.GetBlockOrientation)||
|[GetFloatMatrix()](VRageMath.MatrixI.GetFloatMatrix)||
|[CreateRotation(Direction, Direction, Direction, Direction)](VRageMath.MatrixI.CreateRotation)||
|[Invert(ref MatrixI, out MatrixI)](VRageMath.MatrixI.Invert)||
|[Multiply(ref MatrixI, ref MatrixI, out MatrixI)](VRageMath.MatrixI.Multiply)||
|[Transform(ref MyBlockOrientation, ref MatrixI)](VRageMath.MatrixI.Transform)||

