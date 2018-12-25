← [Index](Api-Index) ← [Vector2](VRageMath.Vector2)

### Summary

```csharp
public public sealed struct Vector2 Transform(public sealed struct Vector2 position, public sealed struct Matrix matrix)
```

Transforms the vector (x, y, 0, 1) by the specified matrix.

### Returns

### Example

### Remarks

### Summary

```csharp
public void Transform(ref public sealed struct Vector2 position, ref public sealed struct Matrix matrix, ref public sealed struct Vector2 result)
```

Transforms a Vector2 by the given Matrix.

### Returns

### Example

### Remarks

### Summary

```csharp
public public sealed struct Vector2 Transform(public sealed struct Vector2 value, public sealed struct Quaternion rotation)
```

Transforms a single Vector2, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.

### Returns

### Example

### Remarks

### Summary

```csharp
public void Transform(ref public sealed struct Vector2 value, ref public sealed struct Quaternion rotation, ref public sealed struct Vector2 result)
```

Transforms a Vector2, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.

### Returns

### Example

### Remarks

### Summary

```csharp
public void Transform(public sealed class Vector2[] sourceArray, ref public sealed struct Matrix matrix, public sealed class Vector2[] destinationArray)
```

Transforms an array of Vector2s by a specified Matrix.

### Returns

### Example

### Remarks

### Summary

```csharp
public void Transform(public sealed class Vector2[] sourceArray, int sourceIndex, ref public sealed struct Matrix matrix, public sealed class Vector2[] destinationArray, int destinationIndex, int length)
```

Transforms a specified range in an array of Vector2s by a specified Matrix and places the results in a specified range in a destination array.

### Returns

### Example

### Remarks

### Summary

```csharp
public void Transform(public sealed class Vector2[] sourceArray, ref public sealed struct Quaternion rotation, public sealed class Vector2[] destinationArray)
```

Transforms an array of Vector2s by a specified Quaternion.

### Returns

### Example

### Remarks

### Summary

```csharp
public void Transform(public sealed class Vector2[] sourceArray, int sourceIndex, ref public sealed struct Quaternion rotation, public sealed class Vector2[] destinationArray, int destinationIndex, int length)
```

Transforms a specified range in an array of Vector2s by a specified Quaternion and places the results in a specified range in a destination array.

### Returns

### Example

### Remarks

