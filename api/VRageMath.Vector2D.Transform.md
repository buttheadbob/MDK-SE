← [Index](Api-Index) ← [Vector2D](VRageMath.Vector2D)

```csharp[Vector2D](VRageMath.Vector2D) Transform([Vector2D](VRageMath.Vector2D) position, [Matrix](VRageMath.Matrix) matrix)```##### Summary

Transforms the vector (x, y, 0, 1) by the specified matrix.

```csharpvoid Transform(ref [Vector2D](VRageMath.Vector2D) position, ref [Matrix](VRageMath.Matrix) matrix, ref [Vector2D](VRageMath.Vector2D) result)```##### Summary

Transforms a Vector2D by the given Matrix.

```csharp[Vector2D](VRageMath.Vector2D) Transform([Vector2D](VRageMath.Vector2D) value, [Quaternion](VRageMath.Quaternion) rotation)```##### Summary

Transforms a single Vector2D, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.

```csharpvoid Transform(ref [Vector2D](VRageMath.Vector2D) value, ref [Quaternion](VRageMath.Quaternion) rotation, ref [Vector2D](VRageMath.Vector2D) result)```##### Summary

Transforms a Vector2D, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.

```csharpvoid Transform([Vector2D[]](VRageMath.Vector2D[]) sourceArray, ref [Matrix](VRageMath.Matrix) matrix, [Vector2D[]](VRageMath.Vector2D[]) destinationArray)```##### Summary

Transforms an array of Vector2s by a specified Matrix.

```csharpvoid Transform([Vector2D[]](VRageMath.Vector2D[]) sourceArray, [int](System.Int32) sourceIndex, ref [Matrix](VRageMath.Matrix) matrix, [Vector2D[]](VRageMath.Vector2D[]) destinationArray, [int](System.Int32) destinationIndex, [int](System.Int32) length)```##### Summary

Transforms a specified range in an array of Vector2s by a specified Matrix and places the results in a specified range in a destination array.

```csharpvoid Transform([Vector2D[]](VRageMath.Vector2D[]) sourceArray, ref [Quaternion](VRageMath.Quaternion) rotation, [Vector2D[]](VRageMath.Vector2D[]) destinationArray)```##### Summary

Transforms an array of Vector2s by a specified Quaternion.

```csharpvoid Transform([Vector2D[]](VRageMath.Vector2D[]) sourceArray, [int](System.Int32) sourceIndex, ref [Quaternion](VRageMath.Quaternion) rotation, [Vector2D[]](VRageMath.Vector2D[]) destinationArray, [int](System.Int32) destinationIndex, [int](System.Int32) length)```##### Summary

Transforms a specified range in an array of Vector2s by a specified Quaternion and places the results in a specified range in a destination array.

