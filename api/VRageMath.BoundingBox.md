← [Index](index)
# BoundingBox Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
<table style="width: 100%">
<tr><td>[`Vector3 Min`](VRageMath.Min)</td><td>The minimum point the BoundingBox contains.</td></tr>
<tr><td>[`Vector3 Max`](VRageMath.Max)</td><td>The maximum point the BoundingBox contains.</td></tr>
<tr><td>static [`ComparerType Comparer`](VRageMath.Comparer)</td><td></td></tr>
<tr><td>static [`int CornerCount`](VRageMath.CornerCount)</td><td>Specifies the total number of corners (8) in the BoundingBox.</td></tr>
</table>
### Properties
<table style="width: 100%">
<tr><td>[`BoxCornerEnumerator Corners`](VRageMath.Corners)</td><td></td></tr>
<tr><td>[`Vector3 Center`](VRageMath.Center)</td><td>Calculates center</td></tr>
<tr><td>[`Vector3 HalfExtents`](VRageMath.HalfExtents)</td><td></td></tr>
<tr><td>[`Vector3 Extents`](VRageMath.Extents)</td><td></td></tr>
<tr><td>[`float Width`](VRageMath.Width)</td><td></td></tr>
<tr><td>[`float Height`](VRageMath.Height)</td><td></td></tr>
<tr><td>[`float Depth`](VRageMath.Depth)</td><td></td></tr>
<tr><td>[`Vector3 Size`](VRageMath.Size)</td><td>Size</td></tr>
<tr><td>[`Matrix Matrix`](VRageMath.Matrix)</td><td>Matrix of AABB, respection center and size</td></tr>
<tr><td>[`float Perimeter`](VRageMath.Perimeter)</td><td>return perimeter of edges</td></tr>
</table>
### Methods
<table style="width: 100%">
<tr><td>[`Vector3[] GetCorners()`](VRageMath.GetCorners)</td><td>Gets an array of points that make up the corners of the BoundingBox. ALLOCATION!</td></tr>
<tr><td>[`void GetCorners(Vector3[] corners)`](VRageMath.GetCorners)</td><td>Gets the array of points that make up the corners of the BoundingBox.</td></tr>
<tr><td>[`void GetCornersUnsafe(*Vector3 corners)`](VRageMath.GetCornersUnsafe)</td><td></td></tr>
<tr><td>[`bool Equals(BoundingBox other)`](VRageMath.Equals)</td><td>Determines whether two instances of BoundingBox are equal.</td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td>Determines whether two instances of BoundingBox are equal.</td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td>Gets the hash code for this instance.</td></tr>
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td>Returns a String that represents the current BoundingBox.</td></tr>
<tr><td>static [`BoundingBox CreateMerged(BoundingBox original, BoundingBox additional)`](VRageMath.CreateMerged)</td><td>Creates the smallest BoundingBox that contains the two specified BoundingBox instances.</td></tr>
<tr><td>static [`void CreateMerged(ref BoundingBox original, ref BoundingBox additional, ref BoundingBox result)`](VRageMath.CreateMerged)</td><td>Creates the smallest BoundingBox that contains the two specified BoundingBox instances.</td></tr>
<tr><td>static [`BoundingBox CreateFromSphere(BoundingSphere sphere)`](VRageMath.CreateFromSphere)</td><td>Creates the smallest BoundingBox that will contain the specified BoundingSphere.</td></tr>
<tr><td>static [`void CreateFromSphere(ref BoundingSphere sphere, ref BoundingBox result)`](VRageMath.CreateFromSphere)</td><td>Creates the smallest BoundingBox that will contain the specified BoundingSphere.</td></tr>
<tr><td>static [`BoundingBox CreateFromPoints(IEnumerable<Vector3> points)`](VRageMath.CreateFromPoints)</td><td>Creates the smallest BoundingBox that will contain a group of points.</td></tr>
<tr><td>static [`BoundingBox CreateFromHalfExtent(Vector3 center, float halfExtent)`](VRageMath.CreateFromHalfExtent)</td><td></td></tr>
<tr><td>static [`BoundingBox CreateFromHalfExtent(Vector3 center, Vector3 halfExtent)`](VRageMath.CreateFromHalfExtent)</td><td></td></tr>
<tr><td>[`BoundingBox Intersect(BoundingBox box)`](VRageMath.Intersect)</td><td>Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)</td></tr>
<tr><td>[`bool Intersects(BoundingBox box)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBox intersects another BoundingBox.</td></tr>
<tr><td>[`bool Intersects(ref BoundingBox box)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`void Intersects(ref BoundingBox box, ref bool result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBox intersects another BoundingBox.</td></tr>
<tr><td>[`bool IntersectsTriangle(Vector3 v0, Vector3 v1, Vector3 v2)`](VRageMath.IntersectsTriangle)</td><td></td></tr>
<tr><td>[`bool IntersectsTriangle(ref Vector3 v0, ref Vector3 v1, ref Vector3 v2)`](VRageMath.IntersectsTriangle)</td><td></td></tr>
<tr><td>[`bool Intersects(BoundingFrustum frustum)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBox intersects a BoundingFrustum.</td></tr>
<tr><td>[`PlaneIntersectionType Intersects(Plane plane)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBox intersects a Plane.</td></tr>
<tr><td>[`void Intersects(ref Plane plane, ref PlaneIntersectionType result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBox intersects a Plane.</td></tr>
<tr><td>[`bool Intersects(Line line, ref float distance)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`Nullable<float> Intersects(Ray ray)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBox intersects a Ray.</td></tr>
<tr><td>[`void Intersects(ref Ray ray, ref Nullable<float> result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBox intersects a Ray.</td></tr>
<tr><td>[`bool Intersects(BoundingSphere sphere)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBox intersects a BoundingSphere.</td></tr>
<tr><td>[`void Intersects(ref BoundingSphere sphere, ref bool result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBox intersects a BoundingSphere.</td></tr>
<tr><td>[`bool Intersects(ref BoundingSphere sphere)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`bool Intersects(ref BoundingSphereD sphere)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`float Distance(Vector3 point)`](VRageMath.Distance)</td><td></td></tr>
<tr><td>[`float DistanceSquared(Vector3 point)`](VRageMath.DistanceSquared)</td><td></td></tr>
<tr><td>[`ContainmentType Contains(BoundingBox box)`](VRageMath.Contains)</td><td>Tests whether the BoundingBox contains another BoundingBox.</td></tr>
<tr><td>[`void Contains(ref BoundingBox box, ref ContainmentType result)`](VRageMath.Contains)</td><td>Tests whether the BoundingBox contains a BoundingBox.</td></tr>
<tr><td>[`ContainmentType Contains(BoundingFrustum frustum)`](VRageMath.Contains)</td><td>Tests whether the BoundingBox contains a BoundingFrustum.</td></tr>
<tr><td>[`ContainmentType Contains(Vector3 point)`](VRageMath.Contains)</td><td>Tests whether the BoundingBox contains a point.</td></tr>
<tr><td>[`ContainmentType Contains(Vector3D point)`](VRageMath.Contains)</td><td></td></tr>
<tr><td>[`void Contains(ref Vector3 point, ref ContainmentType result)`](VRageMath.Contains)</td><td>Tests whether the BoundingBox contains a point.</td></tr>
<tr><td>[`ContainmentType Contains(BoundingSphere sphere)`](VRageMath.Contains)</td><td>Tests whether the BoundingBox contains a BoundingSphere.</td></tr>
<tr><td>[`void Contains(ref BoundingSphere sphere, ref ContainmentType result)`](VRageMath.Contains)</td><td>Tests whether the BoundingBox contains a BoundingSphere.</td></tr>
<tr><td>[`BoundingBox Translate(Matrix worldMatrix)`](VRageMath.Translate)</td><td>Translate</td></tr>
<tr><td>[`BoundingBox Translate(Vector3 vctTranlsation)`](VRageMath.Translate)</td><td>Translate</td></tr>
<tr><td>[`BoundingBox Transform(Matrix worldMatrix)`](VRageMath.Transform)</td><td></td></tr>
<tr><td>[`BoundingBoxD Transform(MatrixD worldMatrix)`](VRageMath.Transform)</td><td></td></tr>
<tr><td>[`BoundingBox Transform(ref Matrix m)`](VRageMath.Transform)</td><td></td></tr>
<tr><td>[`void Transform(ref Matrix m, ref BoundingBox bb)`](VRageMath.Transform)</td><td></td></tr>
<tr><td>[`BoundingBoxD Transform(ref MatrixD m)`](VRageMath.Transform)</td><td></td></tr>
<tr><td>[`void Transform(ref MatrixD m, ref BoundingBoxD bb)`](VRageMath.Transform)</td><td></td></tr>
<tr><td>[`BoundingBox Include(ref Vector3 point)`](VRageMath.Include)</td><td>return expanded aabb (aabb include point)</td></tr>
<tr><td>[`BoundingBox GetIncluded(Vector3 point)`](VRageMath.GetIncluded)</td><td></td></tr>
<tr><td>[`BoundingBox Include(Vector3 point)`](VRageMath.Include)</td><td></td></tr>
<tr><td>[`BoundingBox Include(Vector3 p0, Vector3 p1, Vector3 p2)`](VRageMath.Include)</td><td></td></tr>
<tr><td>[`BoundingBox Include(ref Vector3 p0, ref Vector3 p1, ref Vector3 p2)`](VRageMath.Include)</td><td></td></tr>
<tr><td>[`BoundingBox Include(ref BoundingBox box)`](VRageMath.Include)</td><td>return expanded aabb (aabb include aabb)</td></tr>
<tr><td>[`BoundingBox Include(BoundingBox box)`](VRageMath.Include)</td><td></td></tr>
<tr><td>[`void Include(ref Line line)`](VRageMath.Include)</td><td></td></tr>
<tr><td>[`BoundingBox Include(BoundingSphere sphere)`](VRageMath.Include)</td><td></td></tr>
<tr><td>[`BoundingBox Include(ref BoundingSphere sphere)`](VRageMath.Include)</td><td></td></tr>
<tr><td>[`BoundingBox Include(ref BoundingFrustum frustum)`](VRageMath.Include)</td><td></td></tr>
<tr><td>static [`BoundingBox CreateInvalid()`](VRageMath.CreateInvalid)</td><td></td></tr>
<tr><td>[`float SurfaceArea()`](VRageMath.SurfaceArea)</td><td></td></tr>
<tr><td>[`float Volume()`](VRageMath.Volume)</td><td></td></tr>
<tr><td>[`float ProjectedArea(Vector3 viewDir)`](VRageMath.ProjectedArea)</td><td></td></tr>
<tr><td>[`void Inflate(float size)`](VRageMath.Inflate)</td><td></td></tr>
<tr><td>[`void Inflate(Vector3 size)`](VRageMath.Inflate)</td><td></td></tr>
<tr><td>[`void InflateToMinimum(Vector3 minimumSize)`](VRageMath.InflateToMinimum)</td><td></td></tr>
<tr><td>[`void Scale(Vector3 scale)`](VRageMath.Scale)</td><td></td></tr>
</table>
