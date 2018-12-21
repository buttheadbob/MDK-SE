← [Index](index)
# BoundingSphereD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a sphere.
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Center"><code>Vector3D Center</code></a>_</td><td>The center point of the sphere.</td></tr>
<tr><td>_<a href="VRageMath.Radius"><code>double Radius</code></a>_</td><td>The radius of the sphere.</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(BoundingSphereD other)</code></a>_</td><td>Determines whether the specified BoundingSphereD is equal to the current BoundingSphereD.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Object obj)</code></a>_</td><td>Determines whether the specified Object is equal to the BoundingSphereD.</td></tr>
<tr><td>_<a href="VRageMath.GetHashCode"><code>int GetHashCode()</code></a>_</td><td>Gets the hash code for this instance.</td></tr>
<tr><td>_<a href="VRageMath.ToString"><code>string ToString()</code></a>_</td><td>Returns a String that represents the current BoundingSphereD.</td></tr>
<tr><td>static _<a href="VRageMath.CreateMerged"><code>BoundingSphereD CreateMerged(BoundingSphereD original, BoundingSphereD additional)</code></a>_</td><td>Creates a BoundingSphereD that contains the two specified BoundingSphereD instances.</td></tr>
<tr><td>static _<a href="VRageMath.CreateMerged"><code>void CreateMerged(ref BoundingSphereD original, ref BoundingSphereD additional, ref BoundingSphereD result)</code></a>_</td><td>Creates a BoundingSphereD that contains the two specified BoundingSphereD instances.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromBoundingBox"><code>BoundingSphereD CreateFromBoundingBox(BoundingBoxD box)</code></a>_</td><td>Creates the smallest BoundingSphereD that can contain a specified BoundingBoxD.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromBoundingBox"><code>void CreateFromBoundingBox(ref BoundingBoxD box, ref BoundingSphereD result)</code></a>_</td><td>Creates the smallest BoundingSphereD that can contain a specified BoundingBoxD.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromPoints"><code>BoundingSphereD CreateFromPoints(Vector3D[] points)</code></a>_</td><td>Creates a BoundingSphereD that can contain a specified list of points.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromFrustum"><code>BoundingSphereD CreateFromFrustum(BoundingFrustumD frustum)</code></a>_</td><td>Creates the smallest BoundingSphereD that can contain a specified BoundingFrustum.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(BoundingBoxD box)</code></a>_</td><td>Checks whether the current BoundingSphereD intersects with a specified BoundingBoxD.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref BoundingBoxD box, ref bool result)</code></a>_</td><td>Checks whether the current BoundingSphereD intersects a BoundingBoxD.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>Nullable<double> Intersects(RayD ray)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(BoundingFrustumD frustum)</code></a>_</td><td>Checks whether the current BoundingSphereD intersects with a specified BoundingFrustum.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(BoundingSphereD sphere)</code></a>_</td><td>Checks whether the current BoundingSphereD intersects with a specified BoundingSphereD.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref BoundingSphereD sphere, ref bool result)</code></a>_</td><td>Checks whether the current BoundingSphereD intersects another BoundingSphereD.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(BoundingBoxD box)</code></a>_</td><td>Checks whether the current BoundingSphereD contains the specified BoundingBoxD.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref BoundingBoxD box, ref ContainmentType result)</code></a>_</td><td>Checks whether the current BoundingSphereD contains the specified BoundingBoxD.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(BoundingFrustumD frustum)</code></a>_</td><td>Checks whether the current BoundingSphereD contains the specified BoundingFrustum.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(Vector3D point)</code></a>_</td><td>Checks whether the current BoundingSphereD contains the specified point.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref Vector3D point, ref ContainmentType result)</code></a>_</td><td>Checks whether the current BoundingSphereD contains the specified point.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(BoundingSphereD sphere)</code></a>_</td><td>Checks whether the current BoundingSphereD contains the specified BoundingSphereD.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref BoundingSphereD sphere, ref ContainmentType result)</code></a>_</td><td>Checks whether the current BoundingSphereD contains the specified BoundingSphereD.</td></tr>
<tr><td>_<a href="VRageMath.Transform"><code>BoundingSphereD Transform(MatrixD matrix)</code></a>_</td><td>Translates and scales the BoundingSphereD using a given Matrix.</td></tr>
<tr><td>_<a href="VRageMath.Transform"><code>void Transform(ref MatrixD matrix, ref BoundingSphereD result)</code></a>_</td><td>Translates and scales the BoundingSphereD using a given Matrix.</td></tr>
<tr><td>_<a href="VRageMath.IntersectRaySphere"><code>bool IntersectRaySphere(RayD ray, ref double tmin, ref double tmax)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingSphereD Include(BoundingSphereD sphere)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Include"><code>void Include(ref BoundingSphereD sphere, ref BoundingSphereD otherSphere)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CreateInvalid"><code>BoundingSphereD CreateInvalid()</code></a>_</td><td></td></tr>
</table>
