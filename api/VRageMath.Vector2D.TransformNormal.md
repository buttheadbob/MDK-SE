← [Index](Api-Index) ← [Vector2D](VRageMath.Vector2D)

```csharp[Vector2D](VRageMath.Vector2D) TransformNormal([Vector2D](VRageMath.Vector2D) normal, [Matrix](VRageMath.Matrix) matrix)```##### Summary

Transforms a 2D vector normal by a matrix.

```csharpvoid TransformNormal(ref [Vector2D](VRageMath.Vector2D) normal, ref [Matrix](VRageMath.Matrix) matrix, ref [Vector2D](VRageMath.Vector2D) result)```##### Summary

Transforms a vector normal by a matrix.

```csharpvoid TransformNormal([Vector2D[]](VRageMath.Vector2D[]) sourceArray, ref [Matrix](VRageMath.Matrix) matrix, [Vector2D[]](VRageMath.Vector2D[]) destinationArray)```##### Summary

Transforms an array of Vector2D vector normals by a specified Matrix.

```csharpvoid TransformNormal([Vector2D[]](VRageMath.Vector2D[]) sourceArray, [int](System.Int32) sourceIndex, ref [Matrix](VRageMath.Matrix) matrix, [Vector2D[]](VRageMath.Vector2D[]) destinationArray, [int](System.Int32) destinationIndex, [int](System.Int32) length)```##### Summary

Transforms a specified range in an array of Vector2D vector normals by a specified Matrix and places the results in a specified range in a destination array.

