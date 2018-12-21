← [Index](index)
# BoundingSphere Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a sphere.
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Center"><code>Vector3 Center</code></a>_</td><td>The center point of the sphere.</td></tr>
<tr><td>_<a href="VRageMath.Radius"><code>float Radius</code></a>_</td><td>The radius of the sphere.</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(BoundingSphere other)</code></a>_</td><td>Determines whether the specified BoundingSphere is equal to the current BoundingSphere.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Object obj)</code></a>_</td><td>Determines whether the specified Object is equal to the BoundingSphere.</td></tr>
<tr><td>_<a href="VRageMath.GetHashCode"><code>int GetHashCode()</code></a>_</td><td>Gets the hash code for this instance.</td></tr>
<tr><td>_<a href="VRageMath.ToString"><code>string ToString()</code></a>_</td><td>Returns a String that represents the current BoundingSphere.</td></tr>
<tr><td>static _<a href="VRageMath.CreateMerged"><code>BoundingSphere CreateMerged(BoundingSphere original, BoundingSphere additional)</code></a>_</td><td>Creates a BoundingSphere that contains the two specified BoundingSphere instances.</td></tr>
<tr><td>static _<a href="VRageMath.CreateMerged"><code>void CreateMerged(ref BoundingSphere original, ref BoundingSphere additional, ref BoundingSphere result)</code></a>_</td><td>Creates a BoundingSphere that contains the two specified BoundingSphere instances.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromBoundingBox"><code>BoundingSphere CreateFromBoundingBox(BoundingBox box)</code></a>_</td><td>Creates the smallest BoundingSphere that can contain a specified BoundingBox.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromBoundingBox"><code>void CreateFromBoundingBox(ref BoundingBox box, ref BoundingSphere result)</code></a>_</td><td>Creates the smallest BoundingSphere that can contain a specified BoundingBox.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromPoints"><code>BoundingSphere CreateFromPoints(IEnumerable<Vector3> points)</code></a>_</td><td>Creates a BoundingSphere that can contain a specified list of points.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromFrustum"><code>BoundingSphere CreateFromFrustum(BoundingFrustum frustum)</code></a>_</td><td>Creates the smallest BoundingSphere that can contain a specified BoundingFrustum.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(BoundingBox box)</code></a>_</td><td>Checks whether the current BoundingSphere intersects with a specified BoundingBox.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref BoundingBox box, ref bool result)</code></a>_</td><td>Checks whether the current BoundingSphere intersects a BoundingBox.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(BoundingFrustum frustum)</code></a>_</td><td>Checks whether the current BoundingSphere intersects with a specified BoundingFrustum.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>PlaneIntersectionType Intersects(Plane plane)</code></a>_</td><td>Checks whether the current BoundingSphere intersects with a specified Plane.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref Plane plane, ref PlaneIntersectionType result)</code></a>_</td><td>Checks whether the current BoundingSphere intersects a Plane.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>Nullable<float> Intersects(Ray ray)</code></a>_</td><td>Checks whether the current BoundingSphere intersects with a specified Ray.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref Ray ray, ref Nullable<float> result)</code></a>_</td><td>Checks whether the current BoundingSphere intersects a Ray.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(BoundingSphere sphere)</code></a>_</td><td>Checks whether the current BoundingSphere intersects with a specified BoundingSphere.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref BoundingSphere sphere, ref bool result)</code></a>_</td><td>Checks whether the current BoundingSphere intersects another BoundingSphere.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(BoundingBox box)</code></a>_</td><td>Checks whether the current BoundingSphere contains the specified BoundingBox.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref BoundingBox box, ref ContainmentType result)</code></a>_</td><td>Checks whether the current BoundingSphere contains the specified BoundingBox.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(BoundingFrustum frustum)</code></a>_</td><td>Checks whether the current BoundingSphere contains the specified BoundingFrustum.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(Vector3 point)</code></a>_</td><td>Checks whether the current BoundingSphere contains the specified point.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref Vector3 point, ref ContainmentType result)</code></a>_</td><td>Checks whether the current BoundingSphere contains the specified point.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(BoundingSphere sphere)</code></a>_</td><td>Checks whether the current BoundingSphere contains the specified BoundingSphere.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref BoundingSphere sphere, ref ContainmentType result)</code></a>_</td><td>Checks whether the current BoundingSphere contains the specified BoundingSphere.</td></tr>
<tr><td>_<a href="VRageMath.Transform"><code>BoundingSphere Transform(Matrix matrix)</code></a>_</td><td>Translates and scales the BoundingSphere using a given Matrix.</td></tr>
<tr><td>_<a href="VRageMath.Transform"><code>void Transform(ref Matrix matrix, ref BoundingSphere result)</code></a>_</td><td>Translates and scales the BoundingSphere using a given Matrix.</td></tr>
<tr><td>_<a href="VRageMath.Translate"><code>BoundingSphere Translate(ref Vector3 translation)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.IntersectRaySphere"><code>bool IntersectRaySphere(Ray ray, ref float tmin, ref float tmax)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingSphere Include(BoundingSphere sphere)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Include"><code>void Include(ref BoundingSphere sphere, ref BoundingSphere otherSphere)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CreateInvalid"><code>BoundingSphere CreateInvalid()</code></a>_</td><td></td></tr>
</table>
