← [Index](Api-Index) ← [Vector2](VRageMath.Vector2)

```csharp[Vector2](VRageMath.Vector2) Transform([Vector2](VRageMath.Vector2) position, [Matrix](VRageMath.Matrix) matrix)```##### Summary

Transforms the vector (x, y, 0, 1) by the specified matrix.

```csharpvoid Transform(ref [Vector2](VRageMath.Vector2) position, ref [Matrix](VRageMath.Matrix) matrix, ref [Vector2](VRageMath.Vector2) result)```##### Summary

Transforms a Vector2 by the given Matrix.

```csharp[Vector2](VRageMath.Vector2) Transform([Vector2](VRageMath.Vector2) value, [Quaternion](VRageMath.Quaternion) rotation)```##### Summary

Transforms a single Vector2, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.

```csharpvoid Transform(ref [Vector2](VRageMath.Vector2) value, ref [Quaternion](VRageMath.Quaternion) rotation, ref [Vector2](VRageMath.Vector2) result)```##### Summary

Transforms a Vector2, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.

```csharpvoid Transform([Vector2[]](VRageMath.Vector2[]) sourceArray, ref [Matrix](VRageMath.Matrix) matrix, [Vector2[]](VRageMath.Vector2[]) destinationArray)```##### Summary

Transforms an array of Vector2s by a specified Matrix.

```csharpvoid Transform([Vector2[]](VRageMath.Vector2[]) sourceArray, [int](System.Int32) sourceIndex, ref [Matrix](VRageMath.Matrix) matrix, [Vector2[]](VRageMath.Vector2[]) destinationArray, [int](System.Int32) destinationIndex, [int](System.Int32) length)```##### Summary

Transforms a specified range in an array of Vector2s by a specified Matrix and places the results in a specified range in a destination array.

```csharpvoid Transform([Vector2[]](VRageMath.Vector2[]) sourceArray, ref [Quaternion](VRageMath.Quaternion) rotation, [Vector2[]](VRageMath.Vector2[]) destinationArray)```##### Summary

Transforms an array of Vector2s by a specified Quaternion.

```csharpvoid Transform([Vector2[]](VRageMath.Vector2[]) sourceArray, [int](System.Int32) sourceIndex, ref [Quaternion](VRageMath.Quaternion) rotation, [Vector2[]](VRageMath.Vector2[]) destinationArray, [int](System.Int32) destinationIndex, [int](System.Int32) length)```##### Summary

Transforms a specified range in an array of Vector2s by a specified Quaternion and places the results in a specified range in a destination array.

