← [Index](Api-Index) ← [Namespace Index](Namespace-Index) ← [Vector3D](VRageMath.Vector3D)

### Summary

```csharp
public static Vector3D Barycentric(Vector3D value1, Vector3D value2, Vector3D value3, double amount1, double amount2)
```

Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in Barycentric coordinates relative to a 3D triangle.

### Returns

[Vector3D](VRageMath.Vector3D)

### Parameters

* [Vector3D](VRageMath.Vector3D) value1
* [Vector3D](VRageMath.Vector3D) value2
* [Vector3D](VRageMath.Vector3D) value3
* [double](https://docs.microsoft.com/en-us/dotnet/api/system.double?view=netframework-4.6) amount1
* [double](https://docs.microsoft.com/en-us/dotnet/api/system.double?view=netframework-4.6) amount2
### Summary

```csharp
public static void Barycentric(ref Vector3D value1, ref Vector3D value2, ref Vector3D value3, double amount1, double amount2, ref Vector3D result)
```

Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 3D triangle.

### Parameters

* [Vector3D](VRageMath.Vector3D) value1
* [Vector3D](VRageMath.Vector3D) value2
* [Vector3D](VRageMath.Vector3D) value3
* [double](https://docs.microsoft.com/en-us/dotnet/api/system.double?view=netframework-4.6) amount1
* [double](https://docs.microsoft.com/en-us/dotnet/api/system.double?view=netframework-4.6) amount2
* [Vector3D](VRageMath.Vector3D) result
### Summary

```csharp
public static void Barycentric(Vector3D p, Vector3D a, Vector3D b, Vector3D c, ref double u, ref double v, ref double w)
```

Compute barycentric coordinates (u, v, w) for point p with respect to triangle (a, b, c) From : Real-Time Collision Detection, Christer Ericson, CRC Press 3.4 Barycentric Coordinates

### Parameters

* [Vector3D](VRageMath.Vector3D) p
* [Vector3D](VRageMath.Vector3D) a
* [Vector3D](VRageMath.Vector3D) b
* [Vector3D](VRageMath.Vector3D) c
* [double](https://docs.microsoft.com/en-us/dotnet/api/system.double?view=netframework-4.6) u
* [double](https://docs.microsoft.com/en-us/dotnet/api/system.double?view=netframework-4.6) v
* [double](https://docs.microsoft.com/en-us/dotnet/api/system.double?view=netframework-4.6) w
