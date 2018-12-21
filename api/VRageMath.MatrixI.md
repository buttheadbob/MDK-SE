← [Index](index)
# MatrixI Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`Direction Right`](VRageMath.Right)||
|[`Direction Up`](VRageMath.Up)||
|[`Direction Backward`](VRageMath.Backward)||
|[`Vector3I Translation`](VRageMath.Translation)||
### Properties
|Member|Description|
|---|---|
|[`Direction Left`](VRageMath.Left)||
|[`Direction Down`](VRageMath.Down)||
|[`Direction Forward`](VRageMath.Forward)||
|[`Vector3I RightVector`](VRageMath.RightVector)||
|[`Vector3I LeftVector`](VRageMath.LeftVector)||
|[`Vector3I UpVector`](VRageMath.UpVector)||
|[`Vector3I DownVector`](VRageMath.DownVector)||
|[`Vector3I BackwardVector`](VRageMath.BackwardVector)||
|[`Vector3I ForwardVector`](VRageMath.ForwardVector)||
### Methods
|Member|Description|
|---|---|
|[`Direction GetDirection(Direction direction)`](VRageMath.GetDirection)||
|[`void SetDirection(Direction dirToSet, Direction newDirection)`](VRageMath.SetDirection)||
|[`MyBlockOrientation GetBlockOrientation()`](VRageMath.GetBlockOrientation)||
|[`Matrix GetFloatMatrix()`](VRageMath.GetFloatMatrix)||
|static [`MatrixI CreateRotation(Direction oldA, Direction oldB, Direction newA, Direction newB)`](VRageMath.CreateRotation)||
|static [`void Invert(ref MatrixI matrix, ref MatrixI result)`](VRageMath.Invert)||
|static [`void Multiply(ref MatrixI leftMatrix, ref MatrixI rightMatrix, ref MatrixI result)`](VRageMath.Multiply)||
|static [`MyBlockOrientation Transform(ref MyBlockOrientation orientation, ref MatrixI transform)`](VRageMath.Transform)||
