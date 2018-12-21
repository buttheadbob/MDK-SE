← [Index](index)
# PlaneD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a PlaneD.
### Fields
<table style="width:100%;display:table">
<tr><td>[`Vector3D Normal`](VRageMath.Normal)</td><td>The normal vector of the PlaneD.</td></tr>
<tr><td>[`double D`](VRageMath.D)</td><td>The distance of the PlaneD along its normal from the origin. Note: Be careful! The distance is signed and is the opposite of what people usually expect. If you look closely at the plane equation: (n dot P) + D = 0, you'll realize that D = - (n dot P) (that is, negative instead of positive)</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>[`bool Equals(PlaneD other)`](VRageMath.Equals)</td><td>Determines whether the specified PlaneD is equal to the PlaneD.</td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td>Determines whether the specified Object is equal to the PlaneD.</td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td>Gets the hash code for this object.</td></tr>
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td>Returns a String that represents the current PlaneD.</td></tr>
<tr><td>[`void Normalize()`](VRageMath.Normalize)</td><td>Changes the coefficients of the Normal vector of this PlaneD to make it of unit length.</td></tr>
<tr><td>static [`PlaneD Normalize(PlaneD value)`](VRageMath.Normalize)</td><td>Changes the coefficients of the Normal vector of a PlaneD to make it of unit length.</td></tr>
<tr><td>static [`void Normalize(ref PlaneD value, ref PlaneD result)`](VRageMath.Normalize)</td><td>Changes the coefficients of the Normal vector of a PlaneD to make it of unit length.</td></tr>
<tr><td>static [`PlaneD Transform(PlaneD plane, MatrixD matrix)`](VRageMath.Transform)</td><td>Transforms a normalized PlaneD by a Matrix.</td></tr>
<tr><td>static [`void Transform(ref PlaneD plane, ref MatrixD matrix, ref PlaneD result)`](VRageMath.Transform)</td><td>Transforms a normalized PlaneD by a Matrix.</td></tr>
<tr><td>[`double Dot(Vector4 value)`](VRageMath.Dot)</td><td>Calculates the dot product of a specified Vector4 and this PlaneD.</td></tr>
<tr><td>[`void Dot(ref Vector4 value, ref double result)`](VRageMath.Dot)</td><td>Calculates the dot product of a specified Vector4 and this PlaneD.</td></tr>
<tr><td>[`double DotCoordinate(Vector3D value)`](VRageMath.DotCoordinate)</td><td>Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD plus the distance (D) value of the PlaneD.</td></tr>
<tr><td>[`void DotCoordinate(ref Vector3D value, ref double result)`](VRageMath.DotCoordinate)</td><td>Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD plus the distance (D) value of the PlaneD.</td></tr>
<tr><td>[`double DotNormal(Vector3D value)`](VRageMath.DotNormal)</td><td>Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD.</td></tr>
<tr><td>[`void DotNormal(ref Vector3D value, ref double result)`](VRageMath.DotNormal)</td><td>Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD.</td></tr>
<tr><td>[`PlaneIntersectionType Intersects(BoundingBoxD box)`](VRageMath.Intersects)</td><td>Checks whether the current PlaneD intersects a specified BoundingBox.</td></tr>
<tr><td>[`void Intersects(ref BoundingBoxD box, ref PlaneIntersectionType result)`](VRageMath.Intersects)</td><td>Checks whether the current PlaneD intersects a BoundingBox.</td></tr>
<tr><td>[`PlaneIntersectionType Intersects(BoundingFrustumD frustum)`](VRageMath.Intersects)</td><td>Checks whether the current PlaneD intersects a specified BoundingFrustum.</td></tr>
<tr><td>[`PlaneIntersectionType Intersects(BoundingSphereD sphere)`](VRageMath.Intersects)</td><td>Checks whether the current PlaneD intersects a specified BoundingSphere.</td></tr>
<tr><td>[`void Intersects(ref BoundingSphere sphere, ref PlaneIntersectionType result)`](VRageMath.Intersects)</td><td>Checks whether the current PlaneD intersects a BoundingSphere.</td></tr>
<tr><td>[`Vector3D RandomPoint()`](VRageMath.RandomPoint)</td><td></td></tr>
<tr><td>[`double DistanceToPoint(Vector3D point)`](VRageMath.DistanceToPoint)</td><td></td></tr>
<tr><td>[`double DistanceToPoint(ref Vector3D point)`](VRageMath.DistanceToPoint)</td><td></td></tr>
<tr><td>[`Vector3D ProjectPoint(ref Vector3D point)`](VRageMath.ProjectPoint)</td><td></td></tr>
<tr><td>[`Vector3D Intersection(ref Vector3D from, ref Vector3D direction)`](VRageMath.Intersection)</td><td>Gets intersection point in Plane.</td></tr>
</table>
