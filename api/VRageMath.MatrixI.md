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
|[Direction Backward](VRageMath.MatrixI.Backward)||
|[Direction Right](VRageMath.MatrixI.Right)||
|[Vector3I Translation](VRageMath.MatrixI.Translation)||
|[Direction Up](VRageMath.MatrixI.Up)||

#### Properties

|Member|Description|
|---|---|
|[Vector3I BackwardVector { get; set; }](VRageMath.MatrixI.BackwardVector)||
|[Direction Down { get; set; }](VRageMath.MatrixI.Down)||
|[Vector3I DownVector { get; set; }](VRageMath.MatrixI.DownVector)||
|[Direction Forward { get; set; }](VRageMath.MatrixI.Forward)||
|[Vector3I ForwardVector { get; set; }](VRageMath.MatrixI.ForwardVector)||
|[Direction Left { get; set; }](VRageMath.MatrixI.Left)||
|[Vector3I LeftVector { get; set; }](VRageMath.MatrixI.LeftVector)||
|[Vector3I RightVector { get; set; }](VRageMath.MatrixI.RightVector)||
|[Vector3I UpVector { get; set; }](VRageMath.MatrixI.UpVector)||

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
|[static MatrixI CreateRotation(Direction, Direction, Direction, Direction)](VRageMath.MatrixI.CreateRotation)||
|[static void Invert(ref MatrixI, out MatrixI)](VRageMath.MatrixI.Invert)||
|[static void Multiply(ref MatrixI, ref MatrixI, out MatrixI)](VRageMath.MatrixI.Multiply)||
|[static MyBlockOrientation Transform(ref MyBlockOrientation, ref MatrixI)](VRageMath.MatrixI.Transform)||
|[MyBlockOrientation GetBlockOrientation()](VRageMath.MatrixI.GetBlockOrientation)||
|[Direction GetDirection(Direction)](VRageMath.MatrixI.GetDirection)||
|[Matrix GetFloatMatrix()](VRageMath.MatrixI.GetFloatMatrix)||
|[void SetDirection(Direction, Direction)](VRageMath.MatrixI.SetDirection)||

