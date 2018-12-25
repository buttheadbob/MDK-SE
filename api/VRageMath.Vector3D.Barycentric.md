← [Index](Api-Index) ← [Vector3D](VRageMath.Vector3D)

### Summary

```csharp
public public sealed struct Vector3D Barycentric(public sealed struct Vector3D value1, public sealed struct Vector3D value2, public sealed struct Vector3D value3, double amount1, double amount2)
```

Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in Barycentric coordinates relative to a 3D triangle.

### Returns

### Example

### Remarks

### Summary

```csharp
public void Barycentric(ref public sealed struct Vector3D value1, ref public sealed struct Vector3D value2, ref public sealed struct Vector3D value3, double amount1, double amount2, ref public sealed struct Vector3D result)
```

Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 3D triangle.

### Returns

### Example

### Remarks

### Summary

```csharp
public void Barycentric(public sealed struct Vector3D p, public sealed struct Vector3D a, public sealed struct Vector3D b, public sealed struct Vector3D c, ref double u, ref double v, ref double w)
```

Compute barycentric coordinates (u, v, w) for point p with respect to triangle (a, b, c) From : Real-Time Collision Detection, Christer Ericson, CRC Press 3.4 Barycentric Coordinates

### Returns

### Example

### Remarks

