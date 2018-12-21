← [Index](index)
# BoundingFrustumD Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a frustum and helps determine whether forms intersect with it.
### Fields
<table style="width:100%;display:table">
<tr><td>static [`int CornerCount`](VRageMath.CornerCount)</td><td>Specifies the total number of corners (8) in the BoundingFrustumD.</td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>[`PlaneD Item`](VRageMath.Item)</td><td></td></tr>
<tr><td>[`PlaneD Near`](VRageMath.Near)</td><td>Gets the near plane of the BoundingFrustumD.</td></tr>
<tr><td>[`PlaneD Far`](VRageMath.Far)</td><td>Gets the far plane of the BoundingFrustumD.</td></tr>
<tr><td>[`PlaneD Left`](VRageMath.Left)</td><td>Gets the left plane of the BoundingFrustumD.</td></tr>
<tr><td>[`PlaneD Right`](VRageMath.Right)</td><td>Gets the right plane of the BoundingFrustumD.</td></tr>
<tr><td>[`PlaneD Top`](VRageMath.Top)</td><td>Gets the top plane of the BoundingFrustumD.</td></tr>
<tr><td>[`PlaneD Bottom`](VRageMath.Bottom)</td><td>Gets the bottom plane of the BoundingFrustumD.</td></tr>
<tr><td>[`MatrixD Matrix`](VRageMath.Matrix)</td><td>Gets or sets the Matrix that describes this bounding frustum.</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>[`Vector3D[] GetCorners()`](VRageMath.GetCorners)</td><td>Gets an array of points that make up the corners of the BoundingFrustumD. ALLOCATION!</td></tr>
<tr><td>[`void GetCorners(Vector3D[] corners)`](VRageMath.GetCorners)</td><td>Gets an array of points that make up the corners of the BoundingFrustumD.</td></tr>
<tr><td>[`void GetCornersUnsafe(*Vector3D corners)`](VRageMath.GetCornersUnsafe)</td><td></td></tr>
<tr><td>[`bool Equals(BoundingFrustumD other)`](VRageMath.Equals)</td><td>Determines whether the specified BoundingFrustumD is equal to the current BoundingFrustumD.</td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td>Determines whether the specified Object is equal to the BoundingFrustumD.</td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td>Gets the hash code for this instance.</td></tr>
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td>Returns a String that represents the current BoundingFrustumD.</td></tr>
<tr><td>[`bool Intersects(BoundingBoxD box)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingFrustumD intersects the specified BoundingBoxD.</td></tr>
<tr><td>[`void Intersects(ref BoundingBoxD box, ref bool result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingFrustumD intersects a BoundingBoxD.</td></tr>
<tr><td>[`bool Intersects(BoundingFrustumD frustum)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingFrustumD intersects the specified BoundingFrustumD.</td></tr>
<tr><td>[`PlaneIntersectionType Intersects(PlaneD plane)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingFrustumD intersects the specified Plane.</td></tr>
<tr><td>[`void Intersects(ref PlaneD plane, ref PlaneIntersectionType result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingFrustumD intersects a Plane.</td></tr>
<tr><td>[`Nullable<double> Intersects(RayD ray)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingFrustumD intersects the specified Ray.</td></tr>
<tr><td>[`void Intersects(ref RayD ray, ref Nullable<double> result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingFrustumD intersects a Ray.</td></tr>
<tr><td>[`bool Intersects(BoundingSphereD sphere)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingFrustumD intersects the specified BoundingSphere.</td></tr>
<tr><td>[`void Intersects(ref BoundingSphereD sphere, ref bool result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingFrustumD intersects a BoundingSphere.</td></tr>
<tr><td>[`ContainmentType Contains(BoundingBoxD box)`](VRageMath.Contains)</td><td>Checks whether the current BoundingFrustumD contains the specified BoundingBoxD.</td></tr>
<tr><td>[`void Contains(ref BoundingBoxD box, ref ContainmentType result)`](VRageMath.Contains)</td><td>Checks whether the current BoundingFrustumD contains the specified BoundingBoxD.</td></tr>
<tr><td>[`ContainmentType Contains(BoundingFrustumD frustum)`](VRageMath.Contains)</td><td>Checks whether the current BoundingFrustumD contains the specified BoundingFrustumD.</td></tr>
<tr><td>[`ContainmentType Contains(Vector3D point)`](VRageMath.Contains)</td><td>Checks whether the current BoundingFrustumD contains the specified point.</td></tr>
<tr><td>[`void Contains(ref Vector3D point, ref ContainmentType result)`](VRageMath.Contains)</td><td>Checks whether the current BoundingFrustumD contains the specified point.</td></tr>
<tr><td>[`ContainmentType Contains(BoundingSphereD sphere)`](VRageMath.Contains)</td><td>Checks whether the current BoundingFrustumD contains the specified BoundingSphere.</td></tr>
<tr><td>[`void Contains(ref BoundingSphereD sphere, ref ContainmentType result)`](VRageMath.Contains)</td><td>Checks whether the current BoundingFrustumD contains the specified BoundingSphere.</td></tr>
</table>
