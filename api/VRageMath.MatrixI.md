← [Index](index)
# MatrixI Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
<table style="width: 100%">
<tr><td>[`Direction Right`](VRageMath.Right)</td><td></td></tr>
<tr><td>[`Direction Up`](VRageMath.Up)</td><td></td></tr>
<tr><td>[`Direction Backward`](VRageMath.Backward)</td><td></td></tr>
<tr><td>[`Vector3I Translation`](VRageMath.Translation)</td><td></td></tr>
</table>
### Properties
<table style="width: 100%">
<tr><td>[`Direction Left`](VRageMath.Left)</td><td></td></tr>
<tr><td>[`Direction Down`](VRageMath.Down)</td><td></td></tr>
<tr><td>[`Direction Forward`](VRageMath.Forward)</td><td></td></tr>
<tr><td>[`Vector3I RightVector`](VRageMath.RightVector)</td><td></td></tr>
<tr><td>[`Vector3I LeftVector`](VRageMath.LeftVector)</td><td></td></tr>
<tr><td>[`Vector3I UpVector`](VRageMath.UpVector)</td><td></td></tr>
<tr><td>[`Vector3I DownVector`](VRageMath.DownVector)</td><td></td></tr>
<tr><td>[`Vector3I BackwardVector`](VRageMath.BackwardVector)</td><td></td></tr>
<tr><td>[`Vector3I ForwardVector`](VRageMath.ForwardVector)</td><td></td></tr>
</table>
### Methods
<table style="width: 100%">
<tr><td>[`Direction GetDirection(Direction direction)`](VRageMath.GetDirection)</td><td></td></tr>
<tr><td>[`void SetDirection(Direction dirToSet, Direction newDirection)`](VRageMath.SetDirection)</td><td></td></tr>
<tr><td>[`MyBlockOrientation GetBlockOrientation()`](VRageMath.GetBlockOrientation)</td><td></td></tr>
<tr><td>[`Matrix GetFloatMatrix()`](VRageMath.GetFloatMatrix)</td><td></td></tr>
<tr><td>static [`MatrixI CreateRotation(Direction oldA, Direction oldB, Direction newA, Direction newB)`](VRageMath.CreateRotation)</td><td></td></tr>
<tr><td>static [`void Invert(ref MatrixI matrix, ref MatrixI result)`](VRageMath.Invert)</td><td></td></tr>
<tr><td>static [`void Multiply(ref MatrixI leftMatrix, ref MatrixI rightMatrix, ref MatrixI result)`](VRageMath.Multiply)</td><td></td></tr>
<tr><td>static [`MyBlockOrientation Transform(ref MyBlockOrientation orientation, ref MatrixI transform)`](VRageMath.Transform)</td><td></td></tr>
</table>
