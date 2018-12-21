← [Index](index)
# BoundingBox Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`Vector3 Min`](VRageMath.Min)||
|[`Vector3 Max`](VRageMath.Max)||
|[`ComparerType Comparer`](VRageMath.Comparer)||
|[`int CornerCount`](VRageMath.CornerCount)||
### Properties
|Member|Description|
|---|---|
|[`BoxCornerEnumerator Corners`](VRageMath.Corners)||
|[`Vector3 Center`](VRageMath.Center)||
|[`Vector3 HalfExtents`](VRageMath.HalfExtents)||
|[`Vector3 Extents`](VRageMath.Extents)||
|[`float Width`](VRageMath.Width)||
|[`float Height`](VRageMath.Height)||
|[`float Depth`](VRageMath.Depth)||
|[`Vector3 Size`](VRageMath.Size)||
|[`Matrix Matrix`](VRageMath.Matrix)||
|[`float Perimeter`](VRageMath.Perimeter)||
### Methods
|Member|Description|
|---|---|
|[`Vector3[] GetCorners()`](VRageMath.GetCorners)||
|[`void GetCorners(Vector3[] corners)`](VRageMath.GetCorners)|Gets the array of points that make up the corners of the BoundingBox.|
|[`void GetCornersUnsafe(*Vector3 corners)`](VRageMath.GetCornersUnsafe)||
|[`bool Equals(BoundingBox other)`](VRageMath.Equals)|Determines whether two instances of BoundingBox are equal.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Determines whether two instances of BoundingBox are equal.|
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`string ToString()`](VRageMath.ToString)||
|[`BoundingBox CreateMerged(BoundingBox original, BoundingBox additional)`](VRageMath.CreateMerged)||
|[`void CreateMerged(ref BoundingBox original, ref BoundingBox additional, ref BoundingBox result)`](VRageMath.CreateMerged)||
|[`BoundingBox CreateFromSphere(BoundingSphere sphere)`](VRageMath.CreateFromSphere)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|[`void CreateFromSphere(ref BoundingSphere sphere, ref BoundingBox result)`](VRageMath.CreateFromSphere)||
|[`BoundingBox CreateFromPoints(IEnumerable<Vector3> points)`](VRageMath.CreateFromPoints)|Creates the smallest BoundingBox that will contain a group of points.|
|[`BoundingBox CreateFromHalfExtent(Vector3 center, float halfExtent)`](VRageMath.CreateFromHalfExtent)||
|[`BoundingBox CreateFromHalfExtent(Vector3 center, Vector3 halfExtent)`](VRageMath.CreateFromHalfExtent)||
|[`BoundingBox Intersect(BoundingBox box)`](VRageMath.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`bool Intersects(BoundingBox box)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects another BoundingBox.|
|[`bool Intersects(ref BoundingBox box)`](VRageMath.Intersects)||
|[`void Intersects(ref BoundingBox box, ref bool result)`](VRageMath.Intersects)||
|[`bool IntersectsTriangle(Vector3 v0, Vector3 v1, Vector3 v2)`](VRageMath.IntersectsTriangle)||
|[`bool IntersectsTriangle(ref Vector3 v0, ref Vector3 v1, ref Vector3 v2)`](VRageMath.IntersectsTriangle)||
|[`bool Intersects(BoundingFrustum frustum)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a BoundingFrustum.|
|[`PlaneIntersectionType Intersects(Plane plane)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Plane.|
|[`void Intersects(ref Plane plane, ref PlaneIntersectionType result)`](VRageMath.Intersects)||
|[`bool Intersects(Line line, ref float distance)`](VRageMath.Intersects)||
|[`Nullable<float> Intersects(Ray ray)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Ray.|
|[`void Intersects(ref Ray ray, ref Nullable<float> result)`](VRageMath.Intersects)||
|[`bool Intersects(BoundingSphere sphere)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|[`void Intersects(ref BoundingSphere sphere, ref bool result)`](VRageMath.Intersects)||
|[`bool Intersects(ref BoundingSphere sphere)`](VRageMath.Intersects)||
|[`bool Intersects(ref BoundingSphereD sphere)`](VRageMath.Intersects)||
|[`float Distance(Vector3 point)`](VRageMath.Distance)||
|[`float DistanceSquared(Vector3 point)`](VRageMath.DistanceSquared)||
|[`ContainmentType Contains(BoundingBox box)`](VRageMath.Contains)|Tests whether the BoundingBox contains another BoundingBox.|
|[`void Contains(ref BoundingBox box, ref ContainmentType result)`](VRageMath.Contains)||
|[`ContainmentType Contains(BoundingFrustum frustum)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingFrustum.|
|[`ContainmentType Contains(Vector3 point)`](VRageMath.Contains)|Tests whether the BoundingBox contains a point.|
|[`ContainmentType Contains(Vector3D point)`](VRageMath.Contains)||
|[`void Contains(ref Vector3 point, ref ContainmentType result)`](VRageMath.Contains)||
|[`ContainmentType Contains(BoundingSphere sphere)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingSphere.|
|[`void Contains(ref BoundingSphere sphere, ref ContainmentType result)`](VRageMath.Contains)||
|[`BoundingBox Translate(Matrix worldMatrix)`](VRageMath.Translate)|Translate|
|[`BoundingBox Translate(Vector3 vctTranlsation)`](VRageMath.Translate)|Translate|
|[`BoundingBox Transform(Matrix worldMatrix)`](VRageMath.Transform)||
|[`BoundingBoxD Transform(MatrixD worldMatrix)`](VRageMath.Transform)||
|[`BoundingBox Transform(ref Matrix m)`](VRageMath.Transform)||
|[`void Transform(ref Matrix m, ref BoundingBox bb)`](VRageMath.Transform)||
|[`BoundingBoxD Transform(ref MatrixD m)`](VRageMath.Transform)||
|[`void Transform(ref MatrixD m, ref BoundingBoxD bb)`](VRageMath.Transform)||
|[`BoundingBox Include(ref Vector3 point)`](VRageMath.Include)||
|[`BoundingBox GetIncluded(Vector3 point)`](VRageMath.GetIncluded)||
|[`BoundingBox Include(Vector3 point)`](VRageMath.Include)||
|[`BoundingBox Include(Vector3 p0, Vector3 p1, Vector3 p2)`](VRageMath.Include)||
|[`BoundingBox Include(ref Vector3 p0, ref Vector3 p1, ref Vector3 p2)`](VRageMath.Include)||
|[`BoundingBox Include(ref BoundingBox box)`](VRageMath.Include)||
|[`BoundingBox Include(BoundingBox box)`](VRageMath.Include)||
|[`void Include(ref Line line)`](VRageMath.Include)||
|[`BoundingBox Include(BoundingSphere sphere)`](VRageMath.Include)||
|[`BoundingBox Include(ref BoundingSphere sphere)`](VRageMath.Include)||
|[`BoundingBox Include(ref BoundingFrustum frustum)`](VRageMath.Include)||
|[`BoundingBox CreateInvalid()`](VRageMath.CreateInvalid)||
|[`float SurfaceArea()`](VRageMath.SurfaceArea)||
|[`float Volume()`](VRageMath.Volume)||
|[`float ProjectedArea(Vector3 viewDir)`](VRageMath.ProjectedArea)||
|[`void Inflate(float size)`](VRageMath.Inflate)||
|[`void Inflate(Vector3 size)`](VRageMath.Inflate)||
|[`void InflateToMinimum(Vector3 minimumSize)`](VRageMath.InflateToMinimum)||
|[`void Scale(Vector3 scale)`](VRageMath.Scale)||
