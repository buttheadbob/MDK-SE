← [Index](Api-Index) ← [Vector3](VRageMath.Vector3)

### Summary

```csharp
public public sealed struct Vector3 Barycentric(public sealed struct Vector3 value1, public sealed struct Vector3 value2, public sealed struct Vector3 value3, float amount1, float amount2)
```

Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in Barycentric coordinates relative to a 3D triangle.

### Returns

### Example

### Remarks

### Summary

```csharp
public void Barycentric(ref public sealed struct Vector3 value1, ref public sealed struct Vector3 value2, ref public sealed struct Vector3 value3, float amount1, float amount2, ref public sealed struct Vector3 result)
```

Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 3D triangle.

### Returns

### Example

### Remarks

### Summary

```csharp
public void Barycentric(public sealed struct Vector3 p, public sealed struct Vector3 a, public sealed struct Vector3 b, public sealed struct Vector3 c, ref float u, ref float v, ref float w)
```

Compute barycentric coordinates (u, v, w) for point p with respect to triangle (a, b, c) From : Real-Time Collision Detection, Christer Ericson, CRC Press 3.4 Barycentric Coordinates

### Returns

### Example

### Remarks

