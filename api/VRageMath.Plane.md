← [Index](index)
# Plane Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a plane.
### Fields
<table style="width:100%;display:table">
<tr><td>[`Vector3 Normal`](VRageMath.Normal)</td><td>The normal vector of the Plane.</td></tr>
<tr><td>[`float D`](VRageMath.D)</td><td>The distance of the Plane along its normal from the origin. Note: Be careful! The distance is signed and is the opposite of what people usually expect. If you look closely at the plane equation: (n dot P) - D = 0, you'll realize that D = - (n dot P) (that is, negative instead of positive)</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>[`bool Equals(Plane other)`](VRageMath.Equals)</td><td>Determines whether the specified Plane is equal to the Plane.</td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td>Determines whether the specified Object is equal to the Plane.</td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td>Gets the hash code for this object.</td></tr>
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td>Returns a String that represents the current Plane.</td></tr>
<tr><td>[`void Normalize()`](VRageMath.Normalize)</td><td>Changes the coefficients of the Normal vector of this Plane to make it of unit length.</td></tr>
<tr><td>static [`Plane Normalize(Plane value)`](VRageMath.Normalize)</td><td>Changes the coefficients of the Normal vector of a Plane to make it of unit length.</td></tr>
<tr><td>static [`void Normalize(ref Plane value, ref Plane result)`](VRageMath.Normalize)</td><td>Changes the coefficients of the Normal vector of a Plane to make it of unit length.</td></tr>
<tr><td>static [`Plane Transform(Plane plane, Matrix matrix)`](VRageMath.Transform)</td><td>Transforms a normalized Plane by a Matrix.</td></tr>
<tr><td>static [`void Transform(ref Plane plane, ref Matrix matrix, ref Plane result)`](VRageMath.Transform)</td><td>Transforms a normalized Plane by a Matrix.</td></tr>
<tr><td>[`float Dot(Vector4 value)`](VRageMath.Dot)</td><td>Calculates the dot product of a specified Vector4 and this Plane.</td></tr>
<tr><td>[`void Dot(ref Vector4 value, ref float result)`](VRageMath.Dot)</td><td>Calculates the dot product of a specified Vector4 and this Plane.</td></tr>
<tr><td>[`float DotCoordinate(Vector3 value)`](VRageMath.DotCoordinate)</td><td>Returns the dot product of a specified Vector3 and the Normal vector of this Plane plus the distance (D) value of the Plane.</td></tr>
<tr><td>[`void DotCoordinate(ref Vector3 value, ref float result)`](VRageMath.DotCoordinate)</td><td>Returns the dot product of a specified Vector3 and the Normal vector of this Plane plus the distance (D) value of the Plane.</td></tr>
<tr><td>[`float DotNormal(Vector3 value)`](VRageMath.DotNormal)</td><td>Returns the dot product of a specified Vector3 and the Normal vector of this Plane.</td></tr>
<tr><td>[`void DotNormal(ref Vector3 value, ref float result)`](VRageMath.DotNormal)</td><td>Returns the dot product of a specified Vector3 and the Normal vector of this Plane.</td></tr>
<tr><td>[`PlaneIntersectionType Intersects(BoundingBox box)`](VRageMath.Intersects)</td><td>Checks whether the current Plane intersects a specified BoundingBox.</td></tr>
<tr><td>[`void Intersects(ref BoundingBox box, ref PlaneIntersectionType result)`](VRageMath.Intersects)</td><td>Checks whether the current Plane intersects a BoundingBox.</td></tr>
<tr><td>[`PlaneIntersectionType Intersects(BoundingFrustum frustum)`](VRageMath.Intersects)</td><td>Checks whether the current Plane intersects a specified BoundingFrustum.</td></tr>
<tr><td>[`PlaneIntersectionType Intersects(BoundingSphere sphere)`](VRageMath.Intersects)</td><td>Checks whether the current Plane intersects a specified BoundingSphere.</td></tr>
<tr><td>[`void Intersects(ref BoundingSphere sphere, ref PlaneIntersectionType result)`](VRageMath.Intersects)</td><td>Checks whether the current Plane intersects a BoundingSphere.</td></tr>
<tr><td>[`Vector3 RandomPoint()`](VRageMath.RandomPoint)</td><td></td></tr>
</table>
