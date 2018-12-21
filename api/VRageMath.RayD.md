← [Index](index)
# RayD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a ray.
### Fields
<table style="width: 100%">
<tr><td>[`Vector3D Position`](VRageMath.Position)</td><td>Specifies the starting point of the Ray.</td></tr>
<tr><td>[`Vector3D Direction`](VRageMath.Direction)</td><td>Unit vector specifying the direction the Ray is pointing.</td></tr>
</table>
### Methods
<table style="width: 100%">
<tr><td>[`bool Equals(RayD other)`](VRageMath.Equals)</td><td>Determines whether the specified Ray is equal to the current Ray.</td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td>Determines whether two instances of Ray are equal.</td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td>Gets the hash code for this instance.</td></tr>
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td>Returns a String that represents the current Ray.</td></tr>
<tr><td>[`Nullable<double> Intersects(BoundingBoxD box)`](VRageMath.Intersects)</td><td>Checks whether the Ray intersects a specified BoundingBox.</td></tr>
<tr><td>[`void Intersects(ref BoundingBoxD box, ref Nullable<double> result)`](VRageMath.Intersects)</td><td>Checks whether the current Ray intersects a BoundingBox.</td></tr>
<tr><td>[`Nullable<double> Intersects(BoundingFrustumD frustum)`](VRageMath.Intersects)</td><td>Checks whether the Ray intersects a specified BoundingFrustum.</td></tr>
<tr><td>[`Nullable<double> Intersects(PlaneD plane)`](VRageMath.Intersects)</td><td>Determines whether this Ray intersects a specified Plane.</td></tr>
<tr><td>[`void Intersects(ref PlaneD plane, ref Nullable<double> result)`](VRageMath.Intersects)</td><td>Determines whether this Ray intersects a specified Plane.</td></tr>
<tr><td>[`Nullable<double> Intersects(BoundingSphereD sphere)`](VRageMath.Intersects)</td><td>Checks whether the Ray intersects a specified BoundingSphere.</td></tr>
<tr><td>[`void Intersects(ref BoundingSphere sphere, ref Nullable<double> result)`](VRageMath.Intersects)</td><td>Checks whether the current Ray intersects a BoundingSphere.</td></tr>
</table>
