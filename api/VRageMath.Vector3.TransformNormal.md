← [Index](Api-Index) ← [Vector3](VRageMath.Vector3)

```csharp[Vector3](VRageMath.Vector3) TransformNormal([Vector3](VRageMath.Vector3) normal, [Matrix](VRageMath.Matrix) matrix)```##### Summary

Transforms a 3D vector normal by a matrix.

```csharp[Vector3](VRageMath.Vector3) TransformNormal([Vector3](VRageMath.Vector3) normal, [MatrixD](VRageMath.MatrixD) matrix)```##### Summary

Transforms a 3D vector normal by a matrix.

```csharp[Vector3](VRageMath.Vector3) TransformNormal([Vector3D](VRageMath.Vector3D) normal, [Matrix](VRageMath.Matrix) matrix)```##### Summary

Transforms a 3D vector normal by a matrix.

```csharpvoid TransformNormal(ref [Vector3](VRageMath.Vector3) normal, ref [Matrix](VRageMath.Matrix) matrix, ref [Vector3](VRageMath.Vector3) result)```##### Summary

Transforms a vector normal by a matrix.

```csharpvoid TransformNormal(ref [Vector3](VRageMath.Vector3) normal, ref [MatrixD](VRageMath.MatrixD) matrix, ref [Vector3](VRageMath.Vector3) result)``````csharpvoid TransformNormal(ref [Vector3](VRageMath.Vector3) normal, ref [MatrixI](VRageMath.MatrixI) matrix, ref [Vector3](VRageMath.Vector3) result)``````csharp[Vector3](VRageMath.Vector3) TransformNormal([Vector3](VRageMath.Vector3) normal, [MyBlockOrientation](VRageMath.MyBlockOrientation) orientation)``````csharpvoid TransformNormal(ref [Vector3](VRageMath.Vector3) normal, [MyBlockOrientation](VRageMath.MyBlockOrientation) orientation, ref [Vector3](VRageMath.Vector3) result)``````csharp[Vector3](VRageMath.Vector3) TransformNormal([Vector3](VRageMath.Vector3) normal, ref [Matrix](VRageMath.Matrix) matrix)``````csharpvoid TransformNormal([Vector3[]](VRageMath.Vector3[]) sourceArray, ref [Matrix](VRageMath.Matrix) matrix, [Vector3[]](VRageMath.Vector3[]) destinationArray)```##### Summary

Transforms an array of 3D vector normals by a specified Matrix.

```csharpvoid TransformNormal([Vector3[]](VRageMath.Vector3[]) sourceArray, [int](System.Int32) sourceIndex, ref [Matrix](VRageMath.Matrix) matrix, [Vector3[]](VRageMath.Vector3[]) destinationArray, [int](System.Int32) destinationIndex, [int](System.Int32) length)```##### Summary

Transforms a specified range in an array of 3D vector normals by a specified Matrix and writes the results to a specified range in a destination array.

