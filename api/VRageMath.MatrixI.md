← [Index](index)
# MatrixI Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`Direction&nbsp;Right`](VRageMath.Right)||
|[`Direction&nbsp;Up`](VRageMath.Up)||
|[`Direction&nbsp;Backward`](VRageMath.Backward)||
|[`Vector3I&nbsp;Translation`](VRageMath.Translation)||
### Properties
|Member|Description|
|---|---|
|[`Direction&nbsp;Left`](VRageMath.Left)||
|[`Direction&nbsp;Down`](VRageMath.Down)||
|[`Direction&nbsp;Forward`](VRageMath.Forward)||
|[`Vector3I&nbsp;RightVector`](VRageMath.RightVector)||
|[`Vector3I&nbsp;LeftVector`](VRageMath.LeftVector)||
|[`Vector3I&nbsp;UpVector`](VRageMath.UpVector)||
|[`Vector3I&nbsp;DownVector`](VRageMath.DownVector)||
|[`Vector3I&nbsp;BackwardVector`](VRageMath.BackwardVector)||
|[`Vector3I&nbsp;ForwardVector`](VRageMath.ForwardVector)||
### Methods
|Member|Description|
|---|---|
|[`Direction&nbsp;GetDirection(Direction&nbsp;direction)`](VRageMath.GetDirection)||
|[`void&nbsp;SetDirection(Direction&nbsp;dirToSet,&nbsp;Direction&nbsp;newDirection)`](VRageMath.SetDirection)||
|[`MyBlockOrientation&nbsp;GetBlockOrientation()`](VRageMath.GetBlockOrientation)||
|[`Matrix&nbsp;GetFloatMatrix()`](VRageMath.GetFloatMatrix)||
|static&nbsp;[`MatrixI&nbsp;CreateRotation(Direction&nbsp;oldA,&nbsp;Direction&nbsp;oldB,&nbsp;Direction&nbsp;newA,&nbsp;Direction&nbsp;newB)`](VRageMath.CreateRotation)||
|static&nbsp;[`void&nbsp;Invert(ref&nbsp;MatrixI&nbsp;matrix,&nbsp;ref&nbsp;MatrixI&nbsp;result)`](VRageMath.Invert)||
|static&nbsp;[`void&nbsp;Multiply(ref&nbsp;MatrixI&nbsp;leftMatrix,&nbsp;ref&nbsp;MatrixI&nbsp;rightMatrix,&nbsp;ref&nbsp;MatrixI&nbsp;result)`](VRageMath.Multiply)||
|static&nbsp;[`MyBlockOrientation&nbsp;Transform(ref&nbsp;MyBlockOrientation&nbsp;orientation,&nbsp;ref&nbsp;MatrixI&nbsp;transform)`](VRageMath.Transform)||
