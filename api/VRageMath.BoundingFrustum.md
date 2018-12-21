← [Index](index)
# BoundingFrustum Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a frustum and helps determine whether forms intersect with it.
### Fields
<table style="width:100%;display:table">
<tr><td>static _<a href="VRageMath.CornerCount"><code>int CornerCount</code></a>_</td><td>Specifies the total number of corners (8) in the BoundingFrustum.</td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Planes"><code>Plane[] Planes</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Item"><code>Plane Item</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Near"><code>Plane Near</code></a>_</td><td>Gets the near plane of the BoundingFrustum.</td></tr>
<tr><td>_<a href="VRageMath.Far"><code>Plane Far</code></a>_</td><td>Gets the far plane of the BoundingFrustum.</td></tr>
<tr><td>_<a href="VRageMath.Left"><code>Plane Left</code></a>_</td><td>Gets the left plane of the BoundingFrustum.</td></tr>
<tr><td>_<a href="VRageMath.Right"><code>Plane Right</code></a>_</td><td>Gets the right plane of the BoundingFrustum.</td></tr>
<tr><td>_<a href="VRageMath.Top"><code>Plane Top</code></a>_</td><td>Gets the top plane of the BoundingFrustum.</td></tr>
<tr><td>_<a href="VRageMath.Bottom"><code>Plane Bottom</code></a>_</td><td>Gets the bottom plane of the BoundingFrustum.</td></tr>
<tr><td>_<a href="VRageMath.Matrix"><code>Matrix Matrix</code></a>_</td><td>Gets or sets the Matrix that describes this bounding frustum.</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.GetCorners"><code>Vector3[] GetCorners()</code></a>_</td><td>Gets an array of points that make up the corners of the BoundingFrustum. ALLOCATION!</td></tr>
<tr><td>_<a href="VRageMath.GetCorners"><code>void GetCorners(Vector3[] corners)</code></a>_</td><td>Gets an array of points that make up the corners of the BoundingFrustum.</td></tr>
<tr><td>_<a href="VRageMath.GetCornersUnsafe"><code>void GetCornersUnsafe(*Vector3 corners)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(BoundingFrustum other)</code></a>_</td><td>Determines whether the specified BoundingFrustum is equal to the current BoundingFrustum.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Object obj)</code></a>_</td><td>Determines whether the specified Object is equal to the BoundingFrustum.</td></tr>
<tr><td>_<a href="VRageMath.GetHashCode"><code>int GetHashCode()</code></a>_</td><td>Gets the hash code for this instance.</td></tr>
<tr><td>_<a href="VRageMath.ToString"><code>string ToString()</code></a>_</td><td>Returns a String that represents the current BoundingFrustum.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(BoundingBox box)</code></a>_</td><td>Checks whether the current BoundingFrustum intersects the specified BoundingBox.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref BoundingBox box, ref bool result)</code></a>_</td><td>Checks whether the current BoundingFrustum intersects a BoundingBox.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(BoundingFrustum frustum)</code></a>_</td><td>Checks whether the current BoundingFrustum intersects the specified BoundingFrustum.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>PlaneIntersectionType Intersects(Plane plane)</code></a>_</td><td>Checks whether the current BoundingFrustum intersects the specified Plane.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref Plane plane, ref PlaneIntersectionType result)</code></a>_</td><td>Checks whether the current BoundingFrustum intersects a Plane.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>Nullable<float> Intersects(Ray ray)</code></a>_</td><td>Checks whether the current BoundingFrustum intersects the specified Ray.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref Ray ray, ref Nullable<float> result)</code></a>_</td><td>Checks whether the current BoundingFrustum intersects a Ray.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(BoundingSphere sphere)</code></a>_</td><td>Checks whether the current BoundingFrustum intersects the specified BoundingSphere.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref BoundingSphere sphere, ref bool result)</code></a>_</td><td>Checks whether the current BoundingFrustum intersects a BoundingSphere.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(ref BoundingBox box)</code></a>_</td><td>Checks whether the current BoundingFrustum contains the specified BoundingBox.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref BoundingBox box, ref ContainmentType result)</code></a>_</td><td>Checks whether the current BoundingFrustum contains the specified BoundingBox.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(BoundingFrustum frustum)</code></a>_</td><td>Checks whether the current BoundingFrustum contains the specified BoundingFrustum.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(Vector3 point)</code></a>_</td><td>Checks whether the current BoundingFrustum contains the specified point.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref Vector3 point, ref ContainmentType result)</code></a>_</td><td>Checks whether the current BoundingFrustum contains the specified point.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(BoundingSphere sphere)</code></a>_</td><td>Checks whether the current BoundingFrustum contains the specified BoundingSphere.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref BoundingSphere sphere, ref ContainmentType result)</code></a>_</td><td>Checks whether the current BoundingFrustum contains the specified BoundingSphere.</td></tr>
</table>
