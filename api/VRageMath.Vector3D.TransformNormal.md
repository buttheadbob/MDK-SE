← [Index](Api-Index) ← [Vector3D](VRageMath.Vector3D)

```csharpvoid TransformNormal(ref [Vector3D](VRageMath.Vector3D) normal, ref [MatrixI](VRageMath.MatrixI) matrix, ref [Vector3D](VRageMath.Vector3D) result)``````csharp[Vector3D](VRageMath.Vector3D) TransformNormal([Vector3D](VRageMath.Vector3D) normal, [MyBlockOrientation](VRageMath.MyBlockOrientation) orientation)``````csharpvoid TransformNormal(ref [Vector3D](VRageMath.Vector3D) normal, [MyBlockOrientation](VRageMath.MyBlockOrientation) orientation, ref [Vector3D](VRageMath.Vector3D) result)``````csharp[Vector3D](VRageMath.Vector3D) TransformNormal([Vector3D](VRageMath.Vector3D) normal, ref [MatrixD](VRageMath.MatrixD) matrix)``````csharpvoid TransformNormal([Vector3D[]](VRageMath.Vector3D[]) sourceArray, ref [Matrix](VRageMath.Matrix) matrix, [Vector3D[]](VRageMath.Vector3D[]) destinationArray)```##### Summary

Transforms an array of 3D vector normals by a specified Matrix.

```csharpvoid TransformNormal([Vector3D[]](VRageMath.Vector3D[]) sourceArray, ref [Matrix](VRageMath.Matrix) matrix, *[Vector3D](VRageMath.Vector3D) destinationArray)``````csharpvoid TransformNormal([Vector3D[]](VRageMath.Vector3D[]) sourceArray, [int](System.Int32) sourceIndex, ref [Matrix](VRageMath.Matrix) matrix, [Vector3D[]](VRageMath.Vector3D[]) destinationArray, [int](System.Int32) destinationIndex, [int](System.Int32) length)```##### Summary

Transforms a specified range in an array of 3D vector normals by a specified Matrix and writes the results to a specified range in a destination array.

```csharp[Vector3D](VRageMath.Vector3D) TransformNormal([Vector3D](VRageMath.Vector3D) normal, [Matrix](VRageMath.Matrix) matrix)```##### Summary

Transforms a 3D vector normal by a matrix.

```csharp[Vector3D](VRageMath.Vector3D) TransformNormal([Vector3](VRageMath.Vector3) normal, [MatrixD](VRageMath.MatrixD) matrix)```##### Summary

Transforms a 3D vector normal by a matrix.

```csharp[Vector3D](VRageMath.Vector3D) TransformNormal([Vector3D](VRageMath.Vector3D) normal, [MatrixD](VRageMath.MatrixD) matrix)```##### Summary

Transforms a 3D vector normal by a matrix.

```csharpvoid TransformNormal(ref [Vector3D](VRageMath.Vector3D) normal, ref [MatrixD](VRageMath.MatrixD) matrix, ref [Vector3D](VRageMath.Vector3D) result)```##### Summary

Transforms a vector normal by a matrix.

```csharpvoid TransformNormal(ref [Vector3](VRageMath.Vector3) normal, ref [MatrixD](VRageMath.MatrixD) matrix, ref [Vector3D](VRageMath.Vector3D) result)```