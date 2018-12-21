← [Index](index)
# BoundingFrustum Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a frustum and helps determine whether forms intersect with it.
### Fields
<table style="width: 100%">
<tr><td>static [`int CornerCount`](VRageMath.CornerCount)</td><td>Specifies the total number of corners (8) in the BoundingFrustum.</td></tr>
</table>
### Properties
<table style="width: 100%">
<tr><td>[`Plane[] Planes`](VRageMath.Planes)</td><td></td></tr>
<tr><td>[`Plane Item`](VRageMath.Item)</td><td></td></tr>
<tr><td>[`Plane Near`](VRageMath.Near)</td><td>Gets the near plane of the BoundingFrustum.</td></tr>
<tr><td>[`Plane Far`](VRageMath.Far)</td><td>Gets the far plane of the BoundingFrustum.</td></tr>
<tr><td>[`Plane Left`](VRageMath.Left)</td><td>Gets the left plane of the BoundingFrustum.</td></tr>
<tr><td>[`Plane Right`](VRageMath.Right)</td><td>Gets the right plane of the BoundingFrustum.</td></tr>
<tr><td>[`Plane Top`](VRageMath.Top)</td><td>Gets the top plane of the BoundingFrustum.</td></tr>
<tr><td>[`Plane Bottom`](VRageMath.Bottom)</td><td>Gets the bottom plane of the BoundingFrustum.</td></tr>
<tr><td>[`Matrix Matrix`](VRageMath.Matrix)</td><td>Gets or sets the Matrix that describes this bounding frustum.</td></tr>
</table>
### Methods
<table style="width: 100%">
<tr><td>[`Vector3[] GetCorners()`](VRageMath.GetCorners)</td><td>Gets an array of points that make up the corners of the BoundingFrustum. ALLOCATION!</td></tr>
<tr><td>[`void GetCorners(Vector3[] corners)`](VRageMath.GetCorners)</td><td>Gets an array of points that make up the corners of the BoundingFrustum.</td></tr>
<tr><td>[`void GetCornersUnsafe(*Vector3 corners)`](VRageMath.GetCornersUnsafe)</td><td></td></tr>
<tr><td>[`bool Equals(BoundingFrustum other)`](VRageMath.Equals)</td><td>Determines whether the specified BoundingFrustum is equal to the current BoundingFrustum.</td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td>Determines whether the specified Object is equal to the BoundingFrustum.</td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td>Gets the hash code for this instance.</td></tr>
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td>Returns a String that represents the current BoundingFrustum.</td></tr>
<tr><td>[`bool Intersects(BoundingBox box)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingFrustum intersects the specified BoundingBox.</td></tr>
<tr><td>[`void Intersects(ref BoundingBox box, ref bool result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingFrustum intersects a BoundingBox.</td></tr>
<tr><td>[`bool Intersects(BoundingFrustum frustum)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingFrustum intersects the specified BoundingFrustum.</td></tr>
<tr><td>[`PlaneIntersectionType Intersects(Plane plane)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingFrustum intersects the specified Plane.</td></tr>
<tr><td>[`void Intersects(ref Plane plane, ref PlaneIntersectionType result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingFrustum intersects a Plane.</td></tr>
<tr><td>[`Nullable<float> Intersects(Ray ray)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingFrustum intersects the specified Ray.</td></tr>
<tr><td>[`void Intersects(ref Ray ray, ref Nullable<float> result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingFrustum intersects a Ray.</td></tr>
<tr><td>[`bool Intersects(BoundingSphere sphere)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingFrustum intersects the specified BoundingSphere.</td></tr>
<tr><td>[`void Intersects(ref BoundingSphere sphere, ref bool result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingFrustum intersects a BoundingSphere.</td></tr>
<tr><td>[`ContainmentType Contains(ref BoundingBox box)`](VRageMath.Contains)</td><td>Checks whether the current BoundingFrustum contains the specified BoundingBox.</td></tr>
<tr><td>[`void Contains(ref BoundingBox box, ref ContainmentType result)`](VRageMath.Contains)</td><td>Checks whether the current BoundingFrustum contains the specified BoundingBox.</td></tr>
<tr><td>[`ContainmentType Contains(BoundingFrustum frustum)`](VRageMath.Contains)</td><td>Checks whether the current BoundingFrustum contains the specified BoundingFrustum.</td></tr>
<tr><td>[`ContainmentType Contains(Vector3 point)`](VRageMath.Contains)</td><td>Checks whether the current BoundingFrustum contains the specified point.</td></tr>
<tr><td>[`void Contains(ref Vector3 point, ref ContainmentType result)`](VRageMath.Contains)</td><td>Checks whether the current BoundingFrustum contains the specified point.</td></tr>
<tr><td>[`ContainmentType Contains(BoundingSphere sphere)`](VRageMath.Contains)</td><td>Checks whether the current BoundingFrustum contains the specified BoundingSphere.</td></tr>
<tr><td>[`void Contains(ref BoundingSphere sphere, ref ContainmentType result)`](VRageMath.Contains)</td><td>Checks whether the current BoundingFrustum contains the specified BoundingSphere.</td></tr>
</table>
