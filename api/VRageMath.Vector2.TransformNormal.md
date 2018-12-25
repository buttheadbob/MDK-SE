← [Index](Api-Index) ← [Vector2](VRageMath.Vector2)

```csharp[Vector2](VRageMath.Vector2) TransformNormal([Vector2](VRageMath.Vector2) normal, [Matrix](VRageMath.Matrix) matrix)```##### Summary

Transforms a 2D vector normal by a matrix.

```csharpvoid TransformNormal(ref [Vector2](VRageMath.Vector2) normal, ref [Matrix](VRageMath.Matrix) matrix, ref [Vector2](VRageMath.Vector2) result)```##### Summary

Transforms a vector normal by a matrix.

```csharpvoid TransformNormal([Vector2[]](VRageMath.Vector2[]) sourceArray, ref [Matrix](VRageMath.Matrix) matrix, [Vector2[]](VRageMath.Vector2[]) destinationArray)```##### Summary

Transforms an array of Vector2 vector normals by a specified Matrix.

```csharpvoid TransformNormal([Vector2[]](VRageMath.Vector2[]) sourceArray, [int](System.Int32) sourceIndex, ref [Matrix](VRageMath.Matrix) matrix, [Vector2[]](VRageMath.Vector2[]) destinationArray, [int](System.Int32) destinationIndex, [int](System.Int32) length)```##### Summary

Transforms a specified range in an array of Vector2 vector normals by a specified Matrix and places the results in a specified range in a destination array.

