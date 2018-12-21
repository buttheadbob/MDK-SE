← [Index](index)
# BoundingSphere Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a sphere.
### Fields
<table style="width: 100%">
<tr><td>[`Vector3 Center`](VRageMath.Center)</td><td>The center point of the sphere.</td></tr>
<tr><td>[`float Radius`](VRageMath.Radius)</td><td>The radius of the sphere.</td></tr>
</table>
### Methods
<table style="width: 100%">
<tr><td>[`bool Equals(BoundingSphere other)`](VRageMath.Equals)</td><td>Determines whether the specified BoundingSphere is equal to the current BoundingSphere.</td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td>Determines whether the specified Object is equal to the BoundingSphere.</td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td>Gets the hash code for this instance.</td></tr>
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td>Returns a String that represents the current BoundingSphere.</td></tr>
<tr><td>static [`BoundingSphere CreateMerged(BoundingSphere original, BoundingSphere additional)`](VRageMath.CreateMerged)</td><td>Creates a BoundingSphere that contains the two specified BoundingSphere instances.</td></tr>
<tr><td>static [`void CreateMerged(ref BoundingSphere original, ref BoundingSphere additional, ref BoundingSphere result)`](VRageMath.CreateMerged)</td><td>Creates a BoundingSphere that contains the two specified BoundingSphere instances.</td></tr>
<tr><td>static [`BoundingSphere CreateFromBoundingBox(BoundingBox box)`](VRageMath.CreateFromBoundingBox)</td><td>Creates the smallest BoundingSphere that can contain a specified BoundingBox.</td></tr>
<tr><td>static [`void CreateFromBoundingBox(ref BoundingBox box, ref BoundingSphere result)`](VRageMath.CreateFromBoundingBox)</td><td>Creates the smallest BoundingSphere that can contain a specified BoundingBox.</td></tr>
<tr><td>static [`BoundingSphere CreateFromPoints(IEnumerable<Vector3> points)`](VRageMath.CreateFromPoints)</td><td>Creates a BoundingSphere that can contain a specified list of points.</td></tr>
<tr><td>static [`BoundingSphere CreateFromFrustum(BoundingFrustum frustum)`](VRageMath.CreateFromFrustum)</td><td>Creates the smallest BoundingSphere that can contain a specified BoundingFrustum.</td></tr>
<tr><td>[`bool Intersects(BoundingBox box)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingSphere intersects with a specified BoundingBox.</td></tr>
<tr><td>[`void Intersects(ref BoundingBox box, ref bool result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingSphere intersects a BoundingBox.</td></tr>
<tr><td>[`bool Intersects(BoundingFrustum frustum)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingSphere intersects with a specified BoundingFrustum.</td></tr>
<tr><td>[`PlaneIntersectionType Intersects(Plane plane)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingSphere intersects with a specified Plane.</td></tr>
<tr><td>[`void Intersects(ref Plane plane, ref PlaneIntersectionType result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingSphere intersects a Plane.</td></tr>
<tr><td>[`Nullable<float> Intersects(Ray ray)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingSphere intersects with a specified Ray.</td></tr>
<tr><td>[`void Intersects(ref Ray ray, ref Nullable<float> result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingSphere intersects a Ray.</td></tr>
<tr><td>[`bool Intersects(BoundingSphere sphere)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingSphere intersects with a specified BoundingSphere.</td></tr>
<tr><td>[`void Intersects(ref BoundingSphere sphere, ref bool result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingSphere intersects another BoundingSphere.</td></tr>
<tr><td>[`ContainmentType Contains(BoundingBox box)`](VRageMath.Contains)</td><td>Checks whether the current BoundingSphere contains the specified BoundingBox.</td></tr>
<tr><td>[`void Contains(ref BoundingBox box, ref ContainmentType result)`](VRageMath.Contains)</td><td>Checks whether the current BoundingSphere contains the specified BoundingBox.</td></tr>
<tr><td>[`ContainmentType Contains(BoundingFrustum frustum)`](VRageMath.Contains)</td><td>Checks whether the current BoundingSphere contains the specified BoundingFrustum.</td></tr>
<tr><td>[`ContainmentType Contains(Vector3 point)`](VRageMath.Contains)</td><td>Checks whether the current BoundingSphere contains the specified point.</td></tr>
<tr><td>[`void Contains(ref Vector3 point, ref ContainmentType result)`](VRageMath.Contains)</td><td>Checks whether the current BoundingSphere contains the specified point.</td></tr>
<tr><td>[`ContainmentType Contains(BoundingSphere sphere)`](VRageMath.Contains)</td><td>Checks whether the current BoundingSphere contains the specified BoundingSphere.</td></tr>
<tr><td>[`void Contains(ref BoundingSphere sphere, ref ContainmentType result)`](VRageMath.Contains)</td><td>Checks whether the current BoundingSphere contains the specified BoundingSphere.</td></tr>
<tr><td>[`BoundingSphere Transform(Matrix matrix)`](VRageMath.Transform)</td><td>Translates and scales the BoundingSphere using a given Matrix.</td></tr>
<tr><td>[`void Transform(ref Matrix matrix, ref BoundingSphere result)`](VRageMath.Transform)</td><td>Translates and scales the BoundingSphere using a given Matrix.</td></tr>
<tr><td>[`BoundingSphere Translate(ref Vector3 translation)`](VRageMath.Translate)</td><td></td></tr>
<tr><td>[`bool IntersectRaySphere(Ray ray, ref float tmin, ref float tmax)`](VRageMath.IntersectRaySphere)</td><td></td></tr>
<tr><td>[`BoundingSphere Include(BoundingSphere sphere)`](VRageMath.Include)</td><td></td></tr>
<tr><td>static [`void Include(ref BoundingSphere sphere, ref BoundingSphere otherSphere)`](VRageMath.Include)</td><td></td></tr>
<tr><td>static [`BoundingSphere CreateInvalid()`](VRageMath.CreateInvalid)</td><td></td></tr>
</table>
