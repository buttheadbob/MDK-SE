← [Index](index)
# BoundingFrustumD Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a frustum and helps determine whether forms intersect with it.
### Fields
<table style="width:100%;display:table">
<tr><td>static _<a href="VRageMath.CornerCount"><code>int CornerCount</code></a>_</td><td>Specifies the total number of corners (8) in the BoundingFrustumD.</td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Item"><code>PlaneD Item</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Near"><code>PlaneD Near</code></a>_</td><td>Gets the near plane of the BoundingFrustumD.</td></tr>
<tr><td>_<a href="VRageMath.Far"><code>PlaneD Far</code></a>_</td><td>Gets the far plane of the BoundingFrustumD.</td></tr>
<tr><td>_<a href="VRageMath.Left"><code>PlaneD Left</code></a>_</td><td>Gets the left plane of the BoundingFrustumD.</td></tr>
<tr><td>_<a href="VRageMath.Right"><code>PlaneD Right</code></a>_</td><td>Gets the right plane of the BoundingFrustumD.</td></tr>
<tr><td>_<a href="VRageMath.Top"><code>PlaneD Top</code></a>_</td><td>Gets the top plane of the BoundingFrustumD.</td></tr>
<tr><td>_<a href="VRageMath.Bottom"><code>PlaneD Bottom</code></a>_</td><td>Gets the bottom plane of the BoundingFrustumD.</td></tr>
<tr><td>_<a href="VRageMath.Matrix"><code>MatrixD Matrix</code></a>_</td><td>Gets or sets the Matrix that describes this bounding frustum.</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.GetCorners"><code>Vector3D[] GetCorners()</code></a>_</td><td>Gets an array of points that make up the corners of the BoundingFrustumD. ALLOCATION!</td></tr>
<tr><td>_<a href="VRageMath.GetCorners"><code>void GetCorners(Vector3D[] corners)</code></a>_</td><td>Gets an array of points that make up the corners of the BoundingFrustumD.</td></tr>
<tr><td>_<a href="VRageMath.GetCornersUnsafe"><code>void GetCornersUnsafe(*Vector3D corners)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(BoundingFrustumD other)</code></a>_</td><td>Determines whether the specified BoundingFrustumD is equal to the current BoundingFrustumD.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Object obj)</code></a>_</td><td>Determines whether the specified Object is equal to the BoundingFrustumD.</td></tr>
<tr><td>_<a href="VRageMath.GetHashCode"><code>int GetHashCode()</code></a>_</td><td>Gets the hash code for this instance.</td></tr>
<tr><td>_<a href="VRageMath.ToString"><code>string ToString()</code></a>_</td><td>Returns a String that represents the current BoundingFrustumD.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(BoundingBoxD box)</code></a>_</td><td>Checks whether the current BoundingFrustumD intersects the specified BoundingBoxD.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref BoundingBoxD box, ref bool result)</code></a>_</td><td>Checks whether the current BoundingFrustumD intersects a BoundingBoxD.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(BoundingFrustumD frustum)</code></a>_</td><td>Checks whether the current BoundingFrustumD intersects the specified BoundingFrustumD.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>PlaneIntersectionType Intersects(PlaneD plane)</code></a>_</td><td>Checks whether the current BoundingFrustumD intersects the specified Plane.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref PlaneD plane, ref PlaneIntersectionType result)</code></a>_</td><td>Checks whether the current BoundingFrustumD intersects a Plane.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>Nullable<double> Intersects(RayD ray)</code></a>_</td><td>Checks whether the current BoundingFrustumD intersects the specified Ray.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref RayD ray, ref Nullable<double> result)</code></a>_</td><td>Checks whether the current BoundingFrustumD intersects a Ray.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(BoundingSphereD sphere)</code></a>_</td><td>Checks whether the current BoundingFrustumD intersects the specified BoundingSphere.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref BoundingSphereD sphere, ref bool result)</code></a>_</td><td>Checks whether the current BoundingFrustumD intersects a BoundingSphere.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(BoundingBoxD box)</code></a>_</td><td>Checks whether the current BoundingFrustumD contains the specified BoundingBoxD.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref BoundingBoxD box, ref ContainmentType result)</code></a>_</td><td>Checks whether the current BoundingFrustumD contains the specified BoundingBoxD.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(BoundingFrustumD frustum)</code></a>_</td><td>Checks whether the current BoundingFrustumD contains the specified BoundingFrustumD.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(Vector3D point)</code></a>_</td><td>Checks whether the current BoundingFrustumD contains the specified point.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref Vector3D point, ref ContainmentType result)</code></a>_</td><td>Checks whether the current BoundingFrustumD contains the specified point.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(BoundingSphereD sphere)</code></a>_</td><td>Checks whether the current BoundingFrustumD contains the specified BoundingSphere.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref BoundingSphereD sphere, ref ContainmentType result)</code></a>_</td><td>Checks whether the current BoundingFrustumD contains the specified BoundingSphere.</td></tr>
</table>
