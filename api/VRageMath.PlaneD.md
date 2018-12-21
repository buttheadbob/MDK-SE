← [Index](index)
# PlaneD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a PlaneD.
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Normal"><code>Vector3D Normal</code></a>_</td><td>The normal vector of the PlaneD.</td></tr>
<tr><td>_<a href="VRageMath.D"><code>double D</code></a>_</td><td>The distance of the PlaneD along its normal from the origin. Note: Be careful! The distance is signed and is the opposite of what people usually expect. If you look closely at the plane equation: (n dot P) + D = 0, you'll realize that D = - (n dot P) (that is, negative instead of positive)</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(PlaneD other)</code></a>_</td><td>Determines whether the specified PlaneD is equal to the PlaneD.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Object obj)</code></a>_</td><td>Determines whether the specified Object is equal to the PlaneD.</td></tr>
<tr><td>_<a href="VRageMath.GetHashCode"><code>int GetHashCode()</code></a>_</td><td>Gets the hash code for this object.</td></tr>
<tr><td>_<a href="VRageMath.ToString"><code>string ToString()</code></a>_</td><td>Returns a String that represents the current PlaneD.</td></tr>
<tr><td>_<a href="VRageMath.Normalize"><code>void Normalize()</code></a>_</td><td>Changes the coefficients of the Normal vector of this PlaneD to make it of unit length.</td></tr>
<tr><td>static _<a href="VRageMath.Normalize"><code>PlaneD Normalize(PlaneD value)</code></a>_</td><td>Changes the coefficients of the Normal vector of a PlaneD to make it of unit length.</td></tr>
<tr><td>static _<a href="VRageMath.Normalize"><code>void Normalize(ref PlaneD value, ref PlaneD result)</code></a>_</td><td>Changes the coefficients of the Normal vector of a PlaneD to make it of unit length.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>PlaneD Transform(PlaneD plane, MatrixD matrix)</code></a>_</td><td>Transforms a normalized PlaneD by a Matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(ref PlaneD plane, ref MatrixD matrix, ref PlaneD result)</code></a>_</td><td>Transforms a normalized PlaneD by a Matrix.</td></tr>
<tr><td>_<a href="VRageMath.Dot"><code>double Dot(Vector4 value)</code></a>_</td><td>Calculates the dot product of a specified Vector4 and this PlaneD.</td></tr>
<tr><td>_<a href="VRageMath.Dot"><code>void Dot(ref Vector4 value, ref double result)</code></a>_</td><td>Calculates the dot product of a specified Vector4 and this PlaneD.</td></tr>
<tr><td>_<a href="VRageMath.DotCoordinate"><code>double DotCoordinate(Vector3D value)</code></a>_</td><td>Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD plus the distance (D) value of the PlaneD.</td></tr>
<tr><td>_<a href="VRageMath.DotCoordinate"><code>void DotCoordinate(ref Vector3D value, ref double result)</code></a>_</td><td>Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD plus the distance (D) value of the PlaneD.</td></tr>
<tr><td>_<a href="VRageMath.DotNormal"><code>double DotNormal(Vector3D value)</code></a>_</td><td>Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD.</td></tr>
<tr><td>_<a href="VRageMath.DotNormal"><code>void DotNormal(ref Vector3D value, ref double result)</code></a>_</td><td>Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>PlaneIntersectionType Intersects(BoundingBoxD box)</code></a>_</td><td>Checks whether the current PlaneD intersects a specified BoundingBox.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref BoundingBoxD box, ref PlaneIntersectionType result)</code></a>_</td><td>Checks whether the current PlaneD intersects a BoundingBox.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>PlaneIntersectionType Intersects(BoundingFrustumD frustum)</code></a>_</td><td>Checks whether the current PlaneD intersects a specified BoundingFrustum.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>PlaneIntersectionType Intersects(BoundingSphereD sphere)</code></a>_</td><td>Checks whether the current PlaneD intersects a specified BoundingSphere.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref BoundingSphere sphere, ref PlaneIntersectionType result)</code></a>_</td><td>Checks whether the current PlaneD intersects a BoundingSphere.</td></tr>
<tr><td>_<a href="VRageMath.RandomPoint"><code>Vector3D RandomPoint()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.DistanceToPoint"><code>double DistanceToPoint(Vector3D point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.DistanceToPoint"><code>double DistanceToPoint(ref Vector3D point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.ProjectPoint"><code>Vector3D ProjectPoint(ref Vector3D point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersection"><code>Vector3D Intersection(ref Vector3D from, ref Vector3D direction)</code></a>_</td><td>Gets intersection point in Plane.</td></tr>
</table>
