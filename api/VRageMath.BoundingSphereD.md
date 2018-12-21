← [Index](index)
# BoundingSphereD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a sphere.
### Fields
<table style="width:100%;display:table">
<tr><td>[`Vector3D Center`](VRageMath.Center)</td><td>The center point of the sphere.</td></tr>
<tr><td>[`double Radius`](VRageMath.Radius)</td><td>The radius of the sphere.</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>[`bool Equals(BoundingSphereD other)`](VRageMath.Equals)</td><td>Determines whether the specified BoundingSphereD is equal to the current BoundingSphereD.</td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td>Determines whether the specified Object is equal to the BoundingSphereD.</td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td>Gets the hash code for this instance.</td></tr>
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td>Returns a String that represents the current BoundingSphereD.</td></tr>
<tr><td>static [`BoundingSphereD CreateMerged(BoundingSphereD original, BoundingSphereD additional)`](VRageMath.CreateMerged)</td><td>Creates a BoundingSphereD that contains the two specified BoundingSphereD instances.</td></tr>
<tr><td>static [`void CreateMerged(ref BoundingSphereD original, ref BoundingSphereD additional, ref BoundingSphereD result)`](VRageMath.CreateMerged)</td><td>Creates a BoundingSphereD that contains the two specified BoundingSphereD instances.</td></tr>
<tr><td>static [`BoundingSphereD CreateFromBoundingBox(BoundingBoxD box)`](VRageMath.CreateFromBoundingBox)</td><td>Creates the smallest BoundingSphereD that can contain a specified BoundingBoxD.</td></tr>
<tr><td>static [`void CreateFromBoundingBox(ref BoundingBoxD box, ref BoundingSphereD result)`](VRageMath.CreateFromBoundingBox)</td><td>Creates the smallest BoundingSphereD that can contain a specified BoundingBoxD.</td></tr>
<tr><td>static [`BoundingSphereD CreateFromPoints(Vector3D[] points)`](VRageMath.CreateFromPoints)</td><td>Creates a BoundingSphereD that can contain a specified list of points.</td></tr>
<tr><td>static [`BoundingSphereD CreateFromFrustum(BoundingFrustumD frustum)`](VRageMath.CreateFromFrustum)</td><td>Creates the smallest BoundingSphereD that can contain a specified BoundingFrustum.</td></tr>
<tr><td>[`bool Intersects(BoundingBoxD box)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingSphereD intersects with a specified BoundingBoxD.</td></tr>
<tr><td>[`void Intersects(ref BoundingBoxD box, ref bool result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingSphereD intersects a BoundingBoxD.</td></tr>
<tr><td>[`Nullable<double> Intersects(RayD ray)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`bool Intersects(BoundingFrustumD frustum)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingSphereD intersects with a specified BoundingFrustum.</td></tr>
<tr><td>[`bool Intersects(BoundingSphereD sphere)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingSphereD intersects with a specified BoundingSphereD.</td></tr>
<tr><td>[`void Intersects(ref BoundingSphereD sphere, ref bool result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingSphereD intersects another BoundingSphereD.</td></tr>
<tr><td>[`ContainmentType Contains(BoundingBoxD box)`](VRageMath.Contains)</td><td>Checks whether the current BoundingSphereD contains the specified BoundingBoxD.</td></tr>
<tr><td>[`void Contains(ref BoundingBoxD box, ref ContainmentType result)`](VRageMath.Contains)</td><td>Checks whether the current BoundingSphereD contains the specified BoundingBoxD.</td></tr>
<tr><td>[`ContainmentType Contains(BoundingFrustumD frustum)`](VRageMath.Contains)</td><td>Checks whether the current BoundingSphereD contains the specified BoundingFrustum.</td></tr>
<tr><td>[`ContainmentType Contains(Vector3D point)`](VRageMath.Contains)</td><td>Checks whether the current BoundingSphereD contains the specified point.</td></tr>
<tr><td>[`void Contains(ref Vector3D point, ref ContainmentType result)`](VRageMath.Contains)</td><td>Checks whether the current BoundingSphereD contains the specified point.</td></tr>
<tr><td>[`ContainmentType Contains(BoundingSphereD sphere)`](VRageMath.Contains)</td><td>Checks whether the current BoundingSphereD contains the specified BoundingSphereD.</td></tr>
<tr><td>[`void Contains(ref BoundingSphereD sphere, ref ContainmentType result)`](VRageMath.Contains)</td><td>Checks whether the current BoundingSphereD contains the specified BoundingSphereD.</td></tr>
<tr><td>[`BoundingSphereD Transform(MatrixD matrix)`](VRageMath.Transform)</td><td>Translates and scales the BoundingSphereD using a given Matrix.</td></tr>
<tr><td>[`void Transform(ref MatrixD matrix, ref BoundingSphereD result)`](VRageMath.Transform)</td><td>Translates and scales the BoundingSphereD using a given Matrix.</td></tr>
<tr><td>[`bool IntersectRaySphere(RayD ray, ref double tmin, ref double tmax)`](VRageMath.IntersectRaySphere)</td><td></td></tr>
<tr><td>[`BoundingSphereD Include(BoundingSphereD sphere)`](VRageMath.Include)</td><td></td></tr>
<tr><td>static [`void Include(ref BoundingSphereD sphere, ref BoundingSphereD otherSphere)`](VRageMath.Include)</td><td></td></tr>
<tr><td>static [`BoundingSphereD CreateInvalid()`](VRageMath.CreateInvalid)</td><td></td></tr>
</table>
