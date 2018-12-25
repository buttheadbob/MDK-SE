← [Index](Api-Index) ← [Vector3](VRageMath.Vector3)

```csharp[Vector3](VRageMath.Vector3) Barycentric([Vector3](VRageMath.Vector3) value1, [Vector3](VRageMath.Vector3) value2, [Vector3](VRageMath.Vector3) value3, [float](System.Single) amount1, [float](System.Single) amount2)```##### Summary

Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in Barycentric coordinates relative to a 3D triangle.

```csharpvoid Barycentric(ref [Vector3](VRageMath.Vector3) value1, ref [Vector3](VRageMath.Vector3) value2, ref [Vector3](VRageMath.Vector3) value3, [float](System.Single) amount1, [float](System.Single) amount2, ref [Vector3](VRageMath.Vector3) result)```##### Summary

Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 3D triangle.

```csharpvoid Barycentric([Vector3](VRageMath.Vector3) p, [Vector3](VRageMath.Vector3) a, [Vector3](VRageMath.Vector3) b, [Vector3](VRageMath.Vector3) c, ref [float](System.Single) u, ref [float](System.Single) v, ref [float](System.Single) w)```##### Summary

Compute barycentric coordinates (u, v, w) for point p with respect to triangle (a, b, c) From : Real-Time Collision Detection, Christer Ericson, CRC Press 3.4 Barycentric Coordinates

