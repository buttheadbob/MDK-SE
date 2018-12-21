← [Index](index)
# Plane Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a plane.
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Normal"><code>Vector3 Normal</code></a>_</td><td>The normal vector of the Plane.</td></tr>
<tr><td>_<a href="VRageMath.D"><code>float D</code></a>_</td><td>The distance of the Plane along its normal from the origin. Note: Be careful! The distance is signed and is the opposite of what people usually expect. If you look closely at the plane equation: (n dot P) - D = 0, you'll realize that D = - (n dot P) (that is, negative instead of positive)</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Plane other)</code></a>_</td><td>Determines whether the specified Plane is equal to the Plane.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Object obj)</code></a>_</td><td>Determines whether the specified Object is equal to the Plane.</td></tr>
<tr><td>_<a href="VRageMath.GetHashCode"><code>int GetHashCode()</code></a>_</td><td>Gets the hash code for this object.</td></tr>
<tr><td>_<a href="VRageMath.ToString"><code>string ToString()</code></a>_</td><td>Returns a String that represents the current Plane.</td></tr>
<tr><td>_<a href="VRageMath.Normalize"><code>void Normalize()</code></a>_</td><td>Changes the coefficients of the Normal vector of this Plane to make it of unit length.</td></tr>
<tr><td>static _<a href="VRageMath.Normalize"><code>Plane Normalize(Plane value)</code></a>_</td><td>Changes the coefficients of the Normal vector of a Plane to make it of unit length.</td></tr>
<tr><td>static _<a href="VRageMath.Normalize"><code>void Normalize(ref Plane value, ref Plane result)</code></a>_</td><td>Changes the coefficients of the Normal vector of a Plane to make it of unit length.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>Plane Transform(Plane plane, Matrix matrix)</code></a>_</td><td>Transforms a normalized Plane by a Matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(ref Plane plane, ref Matrix matrix, ref Plane result)</code></a>_</td><td>Transforms a normalized Plane by a Matrix.</td></tr>
<tr><td>_<a href="VRageMath.Dot"><code>float Dot(Vector4 value)</code></a>_</td><td>Calculates the dot product of a specified Vector4 and this Plane.</td></tr>
<tr><td>_<a href="VRageMath.Dot"><code>void Dot(ref Vector4 value, ref float result)</code></a>_</td><td>Calculates the dot product of a specified Vector4 and this Plane.</td></tr>
<tr><td>_<a href="VRageMath.DotCoordinate"><code>float DotCoordinate(Vector3 value)</code></a>_</td><td>Returns the dot product of a specified Vector3 and the Normal vector of this Plane plus the distance (D) value of the Plane.</td></tr>
<tr><td>_<a href="VRageMath.DotCoordinate"><code>void DotCoordinate(ref Vector3 value, ref float result)</code></a>_</td><td>Returns the dot product of a specified Vector3 and the Normal vector of this Plane plus the distance (D) value of the Plane.</td></tr>
<tr><td>_<a href="VRageMath.DotNormal"><code>float DotNormal(Vector3 value)</code></a>_</td><td>Returns the dot product of a specified Vector3 and the Normal vector of this Plane.</td></tr>
<tr><td>_<a href="VRageMath.DotNormal"><code>void DotNormal(ref Vector3 value, ref float result)</code></a>_</td><td>Returns the dot product of a specified Vector3 and the Normal vector of this Plane.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>PlaneIntersectionType Intersects(BoundingBox box)</code></a>_</td><td>Checks whether the current Plane intersects a specified BoundingBox.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref BoundingBox box, ref PlaneIntersectionType result)</code></a>_</td><td>Checks whether the current Plane intersects a BoundingBox.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>PlaneIntersectionType Intersects(BoundingFrustum frustum)</code></a>_</td><td>Checks whether the current Plane intersects a specified BoundingFrustum.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>PlaneIntersectionType Intersects(BoundingSphere sphere)</code></a>_</td><td>Checks whether the current Plane intersects a specified BoundingSphere.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref BoundingSphere sphere, ref PlaneIntersectionType result)</code></a>_</td><td>Checks whether the current Plane intersects a BoundingSphere.</td></tr>
<tr><td>_<a href="VRageMath.RandomPoint"><code>Vector3 RandomPoint()</code></a>_</td><td></td></tr>
</table>
