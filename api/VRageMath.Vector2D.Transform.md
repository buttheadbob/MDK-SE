← [Index](Api-Index) ← [Vector2D](VRageMath.Vector2D)

### Summary

```csharp
public Vector2D Transform(Vector2D position, Matrix matrix)
```

Transforms the vector (x, y, 0, 1) by the specified matrix.

### Returns

[Vector2D](VRageMath.Vector2D)

### Summary

```csharp
public void Transform(ref Vector2D position, ref Matrix matrix, ref Vector2D result)
```

Transforms a Vector2D by the given Matrix.

### Summary

```csharp
public Vector2D Transform(Vector2D value, Quaternion rotation)
```

Transforms a single Vector2D, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.

### Returns

[Vector2D](VRageMath.Vector2D)

### Summary

```csharp
public void Transform(ref Vector2D value, ref Quaternion rotation, ref Vector2D result)
```

Transforms a Vector2D, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.

### Summary

```csharp
public void Transform(Vector2D[] sourceArray, ref Matrix matrix, Vector2D[] destinationArray)
```

Transforms an array of Vector2s by a specified Matrix.

### Summary

```csharp
public void Transform(Vector2D[] sourceArray, int sourceIndex, ref Matrix matrix, Vector2D[] destinationArray, int destinationIndex, int length)
```

Transforms a specified range in an array of Vector2s by a specified Matrix and places the results in a specified range in a destination array.

### Summary

```csharp
public void Transform(Vector2D[] sourceArray, ref Quaternion rotation, Vector2D[] destinationArray)
```

Transforms an array of Vector2s by a specified Quaternion.

### Summary

```csharp
public void Transform(Vector2D[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector2D[] destinationArray, int destinationIndex, int length)
```

Transforms a specified range in an array of Vector2s by a specified Quaternion and places the results in a specified range in a destination array.

