← [Index](Api-Index) ← [Vector2D](VRageMath.Vector2D)

### Summary

```csharp
public public sealed struct Vector2D Transform(public sealed struct Vector2D position, public sealed struct Matrix matrix)
```

Transforms the vector (x, y, 0, 1) by the specified matrix.

### Returns

### Example

### Remarks

### Summary

```csharp
public void Transform(ref public sealed struct Vector2D position, ref public sealed struct Matrix matrix, ref public sealed struct Vector2D result)
```

Transforms a Vector2D by the given Matrix.

### Returns

### Example

### Remarks

### Summary

```csharp
public public sealed struct Vector2D Transform(public sealed struct Vector2D value, public sealed struct Quaternion rotation)
```

Transforms a single Vector2D, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.

### Returns

### Example

### Remarks

### Summary

```csharp
public void Transform(ref public sealed struct Vector2D value, ref public sealed struct Quaternion rotation, ref public sealed struct Vector2D result)
```

Transforms a Vector2D, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.

### Returns

### Example

### Remarks

### Summary

```csharp
public void Transform(public sealed class Vector2D[] sourceArray, ref public sealed struct Matrix matrix, public sealed class Vector2D[] destinationArray)
```

Transforms an array of Vector2s by a specified Matrix.

### Returns

### Example

### Remarks

### Summary

```csharp
public void Transform(public sealed class Vector2D[] sourceArray, int sourceIndex, ref public sealed struct Matrix matrix, public sealed class Vector2D[] destinationArray, int destinationIndex, int length)
```

Transforms a specified range in an array of Vector2s by a specified Matrix and places the results in a specified range in a destination array.

### Returns

### Example

### Remarks

### Summary

```csharp
public void Transform(public sealed class Vector2D[] sourceArray, ref public sealed struct Quaternion rotation, public sealed class Vector2D[] destinationArray)
```

Transforms an array of Vector2s by a specified Quaternion.

### Returns

### Example

### Remarks

### Summary

```csharp
public void Transform(public sealed class Vector2D[] sourceArray, int sourceIndex, ref public sealed struct Quaternion rotation, public sealed class Vector2D[] destinationArray, int destinationIndex, int length)
```

Transforms a specified range in an array of Vector2s by a specified Quaternion and places the results in a specified range in a destination array.

### Returns

### Example

### Remarks

