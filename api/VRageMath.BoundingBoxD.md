← [Index](index)
# BoundingBoxD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
<table style="width:100%;display:table">
<tr><td>[`Vector3D Min`](VRageMath.Min)</td><td>The minimum point the BoundingBox contains.</td></tr>
<tr><td>[`Vector3D Max`](VRageMath.Max)</td><td>The maximum point the BoundingBox contains.</td></tr>
<tr><td>static [`ComparerType Comparer`](VRageMath.Comparer)</td><td></td></tr>
<tr><td>static [`int CornerCount`](VRageMath.CornerCount)</td><td>Specifies the total number of corners (8) in the BoundingBox.</td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>[`Vector3D Center`](VRageMath.Center)</td><td>Calculates center</td></tr>
<tr><td>[`Vector3D HalfExtents`](VRageMath.HalfExtents)</td><td></td></tr>
<tr><td>[`Vector3D Extents`](VRageMath.Extents)</td><td></td></tr>
<tr><td>[`Vector3D Size`](VRageMath.Size)</td><td>Size</td></tr>
<tr><td>[`MatrixD Matrix`](VRageMath.Matrix)</td><td>Matrix of AABB, respection center and size</td></tr>
<tr><td>[`double SurfaceArea`](VRageMath.SurfaceArea)</td><td></td></tr>
<tr><td>[`double Volume`](VRageMath.Volume)</td><td></td></tr>
<tr><td>[`double Perimeter`](VRageMath.Perimeter)</td><td>return perimeter of edges</td></tr>
<tr><td>[`bool Valid`](VRageMath.Valid)</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>[`Vector3D[] GetCorners()`](VRageMath.GetCorners)</td><td>Gets an array of points that make up the corners of the BoundingBox. ALLOCATION!</td></tr>
<tr><td>[`void GetCorners(Vector3D[] corners)`](VRageMath.GetCorners)</td><td>Gets the array of points that make up the corners of the BoundingBox.</td></tr>
<tr><td>[`void GetCornersUnsafe(*Vector3D corners)`](VRageMath.GetCornersUnsafe)</td><td></td></tr>
<tr><td>[`bool Equals(BoundingBoxD other)`](VRageMath.Equals)</td><td>Determines whether two instances of BoundingBox are equal.</td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td>Determines whether two instances of BoundingBox are equal.</td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td>Gets the hash code for this instance.</td></tr>
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td>Returns a String that represents the current BoundingBox.</td></tr>
<tr><td>static [`BoundingBoxD CreateMerged(BoundingBoxD original, BoundingBoxD additional)`](VRageMath.CreateMerged)</td><td>Creates the smallest BoundingBox that contains the two specified BoundingBox instances.</td></tr>
<tr><td>static [`void CreateMerged(ref BoundingBoxD original, ref BoundingBoxD additional, ref BoundingBoxD result)`](VRageMath.CreateMerged)</td><td>Creates the smallest BoundingBox that contains the two specified BoundingBox instances.</td></tr>
<tr><td>static [`BoundingBoxD CreateFromSphere(BoundingSphereD sphere)`](VRageMath.CreateFromSphere)</td><td>Creates the smallest BoundingBox that will contain the specified BoundingSphere.</td></tr>
<tr><td>static [`void CreateFromSphere(ref BoundingSphereD sphere, ref BoundingBoxD result)`](VRageMath.CreateFromSphere)</td><td>Creates the smallest BoundingBox that will contain the specified BoundingSphere.</td></tr>
<tr><td>static [`BoundingBoxD CreateFromPoints(IEnumerable<Vector3D> points)`](VRageMath.CreateFromPoints)</td><td>Creates the smallest BoundingBox that will contain a group of points.</td></tr>
<tr><td>[`BoundingBoxD Intersect(BoundingBoxD box)`](VRageMath.Intersect)</td><td>Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)</td></tr>
<tr><td>[`bool Intersects(BoundingBoxD box)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBox intersects another BoundingBox.</td></tr>
<tr><td>[`bool Intersects(ref BoundingBoxD box)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`void Intersects(ref BoundingBoxD box, ref bool result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBox intersects another BoundingBox.</td></tr>
<tr><td>[`void Intersects(ref BoundingBox box, ref bool result)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`bool IntersectsTriangle(Vector3D v0, Vector3D v1, Vector3D v2)`](VRageMath.IntersectsTriangle)</td><td></td></tr>
<tr><td>[`bool IntersectsTriangle(ref Vector3D v0, ref Vector3D v1, ref Vector3D v2)`](VRageMath.IntersectsTriangle)</td><td></td></tr>
<tr><td>[`bool Intersects(BoundingFrustumD frustum)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBox intersects a BoundingFrustum.</td></tr>
<tr><td>[`PlaneIntersectionType Intersects(PlaneD plane)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBox intersects a Plane.</td></tr>
<tr><td>[`void Intersects(ref PlaneD plane, ref PlaneIntersectionType result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBox intersects a Plane.</td></tr>
<tr><td>[`bool Intersects(ref LineD line)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`bool Intersects(ref LineD line, ref double distance)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`Nullable<double> Intersects(Ray ray)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`Nullable<double> Intersects(RayD ray)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBox intersects a Ray.</td></tr>
<tr><td>[`void Intersects(ref RayD ray, ref Nullable<double> result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBox intersects a Ray.</td></tr>
<tr><td>[`bool Intersect(ref LineD line, ref LineD intersectedLine)`](VRageMath.Intersect)</td><td></td></tr>
<tr><td>[`bool Intersect(ref LineD line, ref double t1, ref double t2)`](VRageMath.Intersect)</td><td></td></tr>
<tr><td>[`bool Intersect(ref RayD ray, ref double tmin, ref double tmax)`](VRageMath.Intersect)</td><td></td></tr>
<tr><td>[`bool Intersects(BoundingSphereD sphere)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBox intersects a BoundingSphere.</td></tr>
<tr><td>[`void Intersects(ref BoundingSphereD sphere, ref bool result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBox intersects a BoundingSphere.</td></tr>
<tr><td>[`bool Intersects(ref BoundingSphereD sphere)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`double Distance(Vector3D point)`](VRageMath.Distance)</td><td></td></tr>
<tr><td>[`double DistanceSquared(Vector3D point)`](VRageMath.DistanceSquared)</td><td></td></tr>
<tr><td>[`double DistanceSquared(ref Vector3D point)`](VRageMath.DistanceSquared)</td><td></td></tr>
<tr><td>[`ContainmentType Contains(BoundingBoxD box)`](VRageMath.Contains)</td><td>Tests whether the BoundingBox contains another BoundingBox.</td></tr>
<tr><td>[`void Contains(ref BoundingBoxD box, ref ContainmentType result)`](VRageMath.Contains)</td><td>Tests whether the BoundingBox contains a BoundingBox.</td></tr>
<tr><td>[`ContainmentType Contains(BoundingFrustumD frustum)`](VRageMath.Contains)</td><td>Tests whether the BoundingBox contains a BoundingFrustum.</td></tr>
<tr><td>[`ContainmentType Contains(Vector3D point)`](VRageMath.Contains)</td><td>Tests whether the BoundingBox contains a point.</td></tr>
<tr><td>[`void Contains(ref Vector3D point, ref ContainmentType result)`](VRageMath.Contains)</td><td>Tests whether the BoundingBox contains a point.</td></tr>
<tr><td>[`ContainmentType Contains(BoundingSphereD sphere)`](VRageMath.Contains)</td><td>Tests whether the BoundingBox contains a BoundingSphere.</td></tr>
<tr><td>[`void Contains(ref BoundingSphereD sphere, ref ContainmentType result)`](VRageMath.Contains)</td><td>Tests whether the BoundingBox contains a BoundingSphere.</td></tr>
<tr><td>[`BoundingBoxD Translate(MatrixD worldMatrix)`](VRageMath.Translate)</td><td>Translate</td></tr>
<tr><td>[`BoundingBoxD Translate(Vector3D vctTranlsation)`](VRageMath.Translate)</td><td>Translate</td></tr>
<tr><td>[`BoundingBoxD TransformSlow(MatrixD m)`](VRageMath.TransformSlow)</td><td>Transform this AABB by matrix.</td></tr>
<tr><td>[`BoundingBoxD TransformSlow(ref MatrixD worldMatrix)`](VRageMath.TransformSlow)</td><td>Transform this AABB by matrix.</td></tr>
<tr><td>[`BoundingBoxD TransformFast(MatrixD m)`](VRageMath.TransformFast)</td><td>Transform this AABB by matrix. Matrix has to be only rotation and translation.</td></tr>
<tr><td>[`BoundingBoxD TransformFast(ref MatrixD m)`](VRageMath.TransformFast)</td><td>Transform this AABB by matrix. Matrix has to be only rotation and translation.</td></tr>
<tr><td>[`void TransformFast(ref MatrixD m, ref BoundingBoxD bb)`](VRageMath.TransformFast)</td><td>Transform this AABB by matrix. Matrix has to be only rotation and translation.</td></tr>
<tr><td>[`BoundingBoxD Include(ref Vector3D point)`](VRageMath.Include)</td><td>return expanded aabb (aabb include point)</td></tr>
<tr><td>[`BoundingBoxD Include(Vector3D point)`](VRageMath.Include)</td><td></td></tr>
<tr><td>[`BoundingBoxD Include(Vector3D p0, Vector3D p1, Vector3D p2)`](VRageMath.Include)</td><td></td></tr>
<tr><td>[`BoundingBoxD Include(ref Vector3D p0, ref Vector3D p1, ref Vector3D p2)`](VRageMath.Include)</td><td></td></tr>
<tr><td>[`BoundingBoxD Include(ref BoundingBoxD box)`](VRageMath.Include)</td><td>return expanded aabb (aabb include aabb)</td></tr>
<tr><td>[`BoundingBoxD Include(BoundingBoxD box)`](VRageMath.Include)</td><td></td></tr>
<tr><td>[`void Include(ref LineD line)`](VRageMath.Include)</td><td></td></tr>
<tr><td>[`BoundingBoxD Include(BoundingSphereD sphere)`](VRageMath.Include)</td><td></td></tr>
<tr><td>[`BoundingBoxD Include(ref BoundingSphereD sphere)`](VRageMath.Include)</td><td></td></tr>
<tr><td>[`BoundingBoxD Include(ref BoundingFrustumD frustum)`](VRageMath.Include)</td><td></td></tr>
<tr><td>static [`BoundingBoxD CreateInvalid()`](VRageMath.CreateInvalid)</td><td></td></tr>
<tr><td>[`double ProjectedArea(Vector3D viewDir)`](VRageMath.ProjectedArea)</td><td></td></tr>
<tr><td>[`BoundingBoxD Inflate(double size)`](VRageMath.Inflate)</td><td></td></tr>
<tr><td>[`BoundingBoxD Inflate(Vector3 size)`](VRageMath.Inflate)</td><td></td></tr>
<tr><td>[`BoundingBoxD GetInflated(double size)`](VRageMath.GetInflated)</td><td></td></tr>
<tr><td>[`BoundingBoxD GetInflated(Vector3 size)`](VRageMath.GetInflated)</td><td></td></tr>
<tr><td>[`void InflateToMinimum(Vector3D minimumSize)`](VRageMath.InflateToMinimum)</td><td></td></tr>
<tr><td>[`void InflateToMinimum(double minimumSize)`](VRageMath.InflateToMinimum)</td><td></td></tr>
<tr><td>[`void AssertIsValid()`](VRageMath.AssertIsValid)</td><td></td></tr>
</table>
