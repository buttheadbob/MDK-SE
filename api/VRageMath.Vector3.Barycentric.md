← [Index](Api-Index) ← [Vector3](VRageMath.Vector3)

### Summary

```csharp
public Vector3 Barycentric(Vector3 value1, Vector3 value2, Vector3 value3, float amount1, float amount2)
```

Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in Barycentric coordinates relative to a 3D triangle.

### Returns

[Vector3](VRageMath.Vector3)

### Parameters

* [Vector3](VRageMath.Vector3) value1
* [Vector3](VRageMath.Vector3) value2
* [Vector3](VRageMath.Vector3) value3
* [float](System.Single) amount1
* [float](System.Single) amount2
### Summary

```csharp
public void Barycentric(ref Vector3 value1, ref Vector3 value2, ref Vector3 value3, float amount1, float amount2, ref Vector3 result)
```

Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 3D triangle.

### Parameters

* [Vector3](VRageMath.Vector3) value1
* [Vector3](VRageMath.Vector3) value2
* [Vector3](VRageMath.Vector3) value3
* [float](System.Single) amount1
* [float](System.Single) amount2
* [Vector3](VRageMath.Vector3) result
### Summary

```csharp
public void Barycentric(Vector3 p, Vector3 a, Vector3 b, Vector3 c, ref float u, ref float v, ref float w)
```

Compute barycentric coordinates (u, v, w) for point p with respect to triangle (a, b, c) From : Real-Time Collision Detection, Christer Ericson, CRC Press 3.4 Barycentric Coordinates

### Parameters

* [Vector3](VRageMath.Vector3) p
* [Vector3](VRageMath.Vector3) a
* [Vector3](VRageMath.Vector3) b
* [Vector3](VRageMath.Vector3) c
* [float](System.Single) u
* [float](System.Single) v
* [float](System.Single) w
