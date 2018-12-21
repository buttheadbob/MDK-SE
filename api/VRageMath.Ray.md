← [Index](index)
# Ray Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a ray.
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Position"><code>Vector3 Position</code></a>_</td><td>Specifies the starting point of the Ray.</td></tr>
<tr><td>_<a href="VRageMath.Direction"><code>Vector3 Direction</code></a>_</td><td>Unit vector specifying the direction the Ray is pointing.</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Ray other)</code></a>_</td><td>Determines whether the specified Ray is equal to the current Ray.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Object obj)</code></a>_</td><td>Determines whether two instances of Ray are equal.</td></tr>
<tr><td>_<a href="VRageMath.GetHashCode"><code>int GetHashCode()</code></a>_</td><td>Gets the hash code for this instance.</td></tr>
<tr><td>_<a href="VRageMath.ToString"><code>string ToString()</code></a>_</td><td>Returns a String that represents the current Ray.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>Nullable<float> Intersects(BoundingBox box)</code></a>_</td><td>Checks whether the Ray intersects a specified BoundingBox.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref BoundingBox box, ref Nullable<float> result)</code></a>_</td><td>Checks whether the current Ray intersects a BoundingBox.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>Nullable<float> Intersects(BoundingFrustum frustum)</code></a>_</td><td>Checks whether the Ray intersects a specified BoundingFrustum.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>Nullable<float> Intersects(Plane plane)</code></a>_</td><td>Determines whether this Ray intersects a specified Plane.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref Plane plane, ref Nullable<float> result)</code></a>_</td><td>Determines whether this Ray intersects a specified Plane.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>Nullable<float> Intersects(BoundingSphere sphere)</code></a>_</td><td>Checks whether the Ray intersects a specified BoundingSphere.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref BoundingSphere sphere, ref Nullable<float> result)</code></a>_</td><td>Checks whether the current Ray intersects a BoundingSphere.</td></tr>
</table>
