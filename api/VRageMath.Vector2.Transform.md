← [Index](Api-Index) ← [Vector2](VRageMath.Vector2)

### Summary

```csharp
public Vector2 Transform(Vector2 position, Matrix matrix)
```

Transforms the vector (x, y, 0, 1) by the specified matrix.

### Returns

[Vector2](VRageMath.Vector2)

### Summary

```csharp
public void Transform(ref Vector2 position, ref Matrix matrix, ref Vector2 result)
```

Transforms a Vector2 by the given Matrix.

### Summary

```csharp
public Vector2 Transform(Vector2 value, Quaternion rotation)
```

Transforms a single Vector2, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.

### Returns

[Vector2](VRageMath.Vector2)

### Summary

```csharp
public void Transform(ref Vector2 value, ref Quaternion rotation, ref Vector2 result)
```

Transforms a Vector2, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.

### Summary

```csharp
public void Transform(Vector2[] sourceArray, ref Matrix matrix, Vector2[] destinationArray)
```

Transforms an array of Vector2s by a specified Matrix.

### Summary

```csharp
public void Transform(Vector2[] sourceArray, int sourceIndex, ref Matrix matrix, Vector2[] destinationArray, int destinationIndex, int length)
```

Transforms a specified range in an array of Vector2s by a specified Matrix and places the results in a specified range in a destination array.

### Summary

```csharp
public void Transform(Vector2[] sourceArray, ref Quaternion rotation, Vector2[] destinationArray)
```

Transforms an array of Vector2s by a specified Quaternion.

### Summary

```csharp
public void Transform(Vector2[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector2[] destinationArray, int destinationIndex, int length)
```

Transforms a specified range in an array of Vector2s by a specified Quaternion and places the results in a specified range in a destination array.

