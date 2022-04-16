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
|\\%1Direction Backward](VRageMath.MatrixI.Backward)||
|\\%1Direction Right](VRageMath.MatrixI.Right)||
|\\%1Vector3I Translation](VRageMath.MatrixI.Translation)||
|\\%1Direction Up](VRageMath.MatrixI.Up)||

#### Properties

|Member|Description|
|---|---|
|\\%1Vector3I BackwardVector { get; set; }](VRageMath.MatrixI.BackwardVector)||
|\\%1Direction Down { get; set; }](VRageMath.MatrixI.Down)||
|\\%1Vector3I DownVector { get; set; }](VRageMath.MatrixI.DownVector)||
|\\%1Direction Forward { get; set; }](VRageMath.MatrixI.Forward)||
|\\%1Vector3I ForwardVector { get; set; }](VRageMath.MatrixI.ForwardVector)||
|\\%1Direction Left { get; set; }](VRageMath.MatrixI.Left)||
|\\%1Vector3I LeftVector { get; set; }](VRageMath.MatrixI.LeftVector)||
|\\%1Vector3I RightVector { get; set; }](VRageMath.MatrixI.RightVector)||
|\\%1Vector3I UpVector { get; set; }](VRageMath.MatrixI.UpVector)||

#### Constructors

|Member|Description|
|---|---|
|\\%1MatrixI(ref Vector3I, Direction, Direction)](VRageMath.MatrixI..ctor)||
|\\%1MatrixI(Vector3I, Direction, Direction)](VRageMath.MatrixI..ctor)||
|\\%1MatrixI(Direction, Direction)](VRageMath.MatrixI..ctor)||
|\\%1MatrixI(ref Vector3I, ref Vector3I, ref Vector3I)](VRageMath.MatrixI..ctor)||
|\\%1MatrixI(ref Vector3I, ref Vector3, ref Vector3)](VRageMath.MatrixI..ctor)||
|\\%1MatrixI(MyBlockOrientation)](VRageMath.MatrixI..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\%1static MatrixI CreateRotation(Direction, Direction, Direction, Direction)](VRageMath.MatrixI.CreateRotation)||
|\\%1static void Invert(ref MatrixI, out MatrixI)](VRageMath.MatrixI.Invert)||
|\\%1static void Multiply(ref MatrixI, ref MatrixI, out MatrixI)](VRageMath.MatrixI.Multiply)||
|\\%1static MyBlockOrientation Transform(ref MyBlockOrientation, ref MatrixI)](VRageMath.MatrixI.Transform)||
|\\%1MyBlockOrientation GetBlockOrientation()](VRageMath.MatrixI.GetBlockOrientation)||
|\\%1Direction GetDirection(Direction)](VRageMath.MatrixI.GetDirection)||
|\\%1Matrix GetFloatMatrix()](VRageMath.MatrixI.GetFloatMatrix)||
|\\%1void SetDirection(Direction, Direction)](VRageMath.MatrixI.SetDirection)||

