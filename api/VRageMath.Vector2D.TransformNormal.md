← [Index](Api-Index) ← [Vector2D](VRageMath.Vector2D)

### Summary

```csharp
public Vector2D TransformNormal(Vector2D normal, Matrix matrix)
```

Transforms a 2D vector normal by a matrix.

### Returns

[Vector2D](VRageMath.Vector2D)

### Parameters

* [Vector2D](VRageMath.Vector2D) normal
* [Matrix](VRageMath.Matrix) matrix
### Summary

```csharp
public void TransformNormal(ref Vector2D normal, ref Matrix matrix, ref Vector2D result)
```

Transforms a vector normal by a matrix.

### Parameters

* [Vector2D](VRageMath.Vector2D) normal
* [Matrix](VRageMath.Matrix) matrix
* [Vector2D](VRageMath.Vector2D) result
### Summary

```csharp
public void TransformNormal(Vector2D[] sourceArray, ref Matrix matrix, Vector2D[] destinationArray)
```

Transforms an array of Vector2D vector normals by a specified Matrix.

### Parameters

* [Vector2D[]](VRageMath.Vector2D[]) sourceArray
* [Matrix](VRageMath.Matrix) matrix
* [Vector2D[]](VRageMath.Vector2D[]) destinationArray
### Summary

```csharp
public void TransformNormal(Vector2D[] sourceArray, int sourceIndex, ref Matrix matrix, Vector2D[] destinationArray, int destinationIndex, int length)
```

Transforms a specified range in an array of Vector2D vector normals by a specified Matrix and places the results in a specified range in a destination array.

### Parameters

* [Vector2D[]](VRageMath.Vector2D[]) sourceArray
* [int](System.Int32) sourceIndex
* [Matrix](VRageMath.Matrix) matrix
* [Vector2D[]](VRageMath.Vector2D[]) destinationArray
* [int](System.Int32) destinationIndex
* [int](System.Int32) length
