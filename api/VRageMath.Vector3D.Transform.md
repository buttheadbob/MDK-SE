← [Index](Api-Index) ← [Vector3D](VRageMath.Vector3D)

```csharp[Vector3D](VRageMath.Vector3D) Transform([Vector3D](VRageMath.Vector3D) value, [Quaternion](VRageMath.Quaternion) rotation)```##### Summary

Transforms a Vector3 by a specified Quaternion rotation.

```csharpvoid Transform(ref [Vector3D](VRageMath.Vector3D) value, ref [Quaternion](VRageMath.Quaternion) rotation, ref [Vector3D](VRageMath.Vector3D) result)```##### Summary

Transforms a Vector3 by a specified Quaternion rotation.

```csharpvoid Transform([Vector3D[]](VRageMath.Vector3D[]) sourceArray, ref [MatrixD](VRageMath.MatrixD) matrix, [Vector3D[]](VRageMath.Vector3D[]) destinationArray)```##### Summary

Transforms a source array of Vector3s by a specified Matrix and writes the results to an existing destination array.

```csharpvoid Transform([Vector3D[]](VRageMath.Vector3D[]) sourceArray, ref [MatrixD](VRageMath.MatrixD) matrix, *[Vector3D](VRageMath.Vector3D) destinationArray)``````csharpvoid Transform([Vector3D[]](VRageMath.Vector3D[]) sourceArray, [int](System.Int32) sourceIndex, ref [Matrix](VRageMath.Matrix) matrix, [Vector3D[]](VRageMath.Vector3D[]) destinationArray, [int](System.Int32) destinationIndex, [int](System.Int32) length)```##### Summary

Applies a specified transform Matrix to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.

```csharpvoid Transform([Vector3D[]](VRageMath.Vector3D[]) sourceArray, ref [Quaternion](VRageMath.Quaternion) rotation, [Vector3D[]](VRageMath.Vector3D[]) destinationArray)```##### Summary

Transforms a source array of Vector3s by a specified Quaternion rotation and writes the results to an existing destination array.

```csharpvoid Transform([Vector3D[]](VRageMath.Vector3D[]) sourceArray, [int](System.Int32) sourceIndex, ref [Quaternion](VRageMath.Quaternion) rotation, [Vector3D[]](VRageMath.Vector3D[]) destinationArray, [int](System.Int32) destinationIndex, [int](System.Int32) length)```##### Summary

Applies a specified Quaternion rotation to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.

```csharp[Vector3D](VRageMath.Vector3D) Transform([Vector3D](VRageMath.Vector3D) position, [MatrixD](VRageMath.MatrixD) matrix)```##### Summary

Transforms a 3D vector by the given matrix.

```csharp[Vector3D](VRageMath.Vector3D) Transform([Vector3](VRageMath.Vector3) position, [MatrixD](VRageMath.MatrixD) matrix)``````csharp[Vector3D](VRageMath.Vector3D) Transform([Vector3D](VRageMath.Vector3D) position, [Matrix](VRageMath.Matrix) matrix)```##### Summary

Transforms a 3D vector by the given matrix.

```csharp[Vector3D](VRageMath.Vector3D) Transform([Vector3D](VRageMath.Vector3D) position, ref [MatrixD](VRageMath.MatrixD) matrix)``````csharpvoid Transform(ref [Vector3D](VRageMath.Vector3D) position, ref [MatrixD](VRageMath.MatrixD) matrix, ref [Vector3D](VRageMath.Vector3D) result)```##### Summary

Transforms a Vector3 by the given Matrix.

```csharpvoid Transform(ref [Vector3](VRageMath.Vector3) position, ref [MatrixD](VRageMath.MatrixD) matrix, ref [Vector3D](VRageMath.Vector3D) result)``````csharpvoid Transform(ref [Vector3D](VRageMath.Vector3D) position, ref [MatrixI](VRageMath.MatrixI) matrix, ref [Vector3D](VRageMath.Vector3D) result)```