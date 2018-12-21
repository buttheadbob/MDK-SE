← [Index](index)
# BoundingBoxD Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`Vector3D Min`](VRageMath.Min)||
|[`Vector3D Max`](VRageMath.Max)||
|[`ComparerType Comparer`](VRageMath.Comparer)||
|[`int CornerCount`](VRageMath.CornerCount)||
### Properties
|Member|Description|
|---|---|
|[`Vector3D Center`](VRageMath.Center)||
|[`Vector3D HalfExtents`](VRageMath.HalfExtents)||
|[`Vector3D Extents`](VRageMath.Extents)||
|[`Vector3D Size`](VRageMath.Size)||
|[`MatrixD Matrix`](VRageMath.Matrix)||
|[`double SurfaceArea`](VRageMath.SurfaceArea)||
|[`double Volume`](VRageMath.Volume)||
|[`double Perimeter`](VRageMath.Perimeter)||
|[`bool Valid`](VRageMath.Valid)||
### Methods
|Member|Description|
|---|---|
|[`Vector3D[] GetCorners()`](VRageMath.GetCorners)||
|[`void GetCorners(Vector3D[] corners)`](VRageMath.GetCorners)|Gets the array of points that make up the corners of the BoundingBox.|
|[`void GetCornersUnsafe(*Vector3D corners)`](VRageMath.GetCornersUnsafe)||
|[`bool Equals(BoundingBoxD other)`](VRageMath.Equals)|Determines whether two instances of BoundingBox are equal.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Determines whether two instances of BoundingBox are equal.|
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`string ToString()`](VRageMath.ToString)||
|[`BoundingBoxD CreateMerged(BoundingBoxD original, BoundingBoxD additional)`](VRageMath.CreateMerged)||
|[`void CreateMerged(ref BoundingBoxD original, ref BoundingBoxD additional, ref BoundingBoxD result)`](VRageMath.CreateMerged)||
|[`BoundingBoxD CreateFromSphere(BoundingSphereD sphere)`](VRageMath.CreateFromSphere)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|[`void CreateFromSphere(ref BoundingSphereD sphere, ref BoundingBoxD result)`](VRageMath.CreateFromSphere)||
|[`BoundingBoxD CreateFromPoints(IEnumerable<Vector3D> points)`](VRageMath.CreateFromPoints)|Creates the smallest BoundingBox that will contain a group of points.|
|[`BoundingBoxD Intersect(BoundingBoxD box)`](VRageMath.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`bool Intersects(BoundingBoxD box)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects another BoundingBox.|
|[`bool Intersects(ref BoundingBoxD box)`](VRageMath.Intersects)||
|[`void Intersects(ref BoundingBoxD box, ref bool result)`](VRageMath.Intersects)||
|[`void Intersects(ref BoundingBox box, ref bool result)`](VRageMath.Intersects)||
|[`bool IntersectsTriangle(Vector3D v0, Vector3D v1, Vector3D v2)`](VRageMath.IntersectsTriangle)||
|[`bool IntersectsTriangle(ref Vector3D v0, ref Vector3D v1, ref Vector3D v2)`](VRageMath.IntersectsTriangle)||
|[`bool Intersects(BoundingFrustumD frustum)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a BoundingFrustum.|
|[`PlaneIntersectionType Intersects(PlaneD plane)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Plane.|
|[`void Intersects(ref PlaneD plane, ref PlaneIntersectionType result)`](VRageMath.Intersects)||
|[`bool Intersects(ref LineD line)`](VRageMath.Intersects)||
|[`bool Intersects(ref LineD line, ref double distance)`](VRageMath.Intersects)||
|[`Nullable<double> Intersects(Ray ray)`](VRageMath.Intersects)||
|[`Nullable<double> Intersects(RayD ray)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Ray.|
|[`void Intersects(ref RayD ray, ref Nullable<double> result)`](VRageMath.Intersects)||
|[`bool Intersect(ref LineD line, ref LineD intersectedLine)`](VRageMath.Intersect)||
|[`bool Intersect(ref LineD line, ref double t1, ref double t2)`](VRageMath.Intersect)||
|[`bool Intersect(ref RayD ray, ref double tmin, ref double tmax)`](VRageMath.Intersect)||
|[`bool Intersects(BoundingSphereD sphere)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|[`void Intersects(ref BoundingSphereD sphere, ref bool result)`](VRageMath.Intersects)||
|[`bool Intersects(ref BoundingSphereD sphere)`](VRageMath.Intersects)||
|[`double Distance(Vector3D point)`](VRageMath.Distance)||
|[`double DistanceSquared(Vector3D point)`](VRageMath.DistanceSquared)||
|[`double DistanceSquared(ref Vector3D point)`](VRageMath.DistanceSquared)||
|[`ContainmentType Contains(BoundingBoxD box)`](VRageMath.Contains)|Tests whether the BoundingBox contains another BoundingBox.|
|[`void Contains(ref BoundingBoxD box, ref ContainmentType result)`](VRageMath.Contains)||
|[`ContainmentType Contains(BoundingFrustumD frustum)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingFrustum.|
|[`ContainmentType Contains(Vector3D point)`](VRageMath.Contains)|Tests whether the BoundingBox contains a point.|
|[`void Contains(ref Vector3D point, ref ContainmentType result)`](VRageMath.Contains)||
|[`ContainmentType Contains(BoundingSphereD sphere)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingSphere.|
|[`void Contains(ref BoundingSphereD sphere, ref ContainmentType result)`](VRageMath.Contains)||
|[`BoundingBoxD Translate(MatrixD worldMatrix)`](VRageMath.Translate)|Translate|
|[`BoundingBoxD Translate(Vector3D vctTranlsation)`](VRageMath.Translate)|Translate|
|[`BoundingBoxD TransformSlow(MatrixD m)`](VRageMath.TransformSlow)|Transform this AABB by matrix.|
|[`BoundingBoxD TransformSlow(ref MatrixD worldMatrix)`](VRageMath.TransformSlow)||
|[`BoundingBoxD TransformFast(MatrixD m)`](VRageMath.TransformFast)|Transform this AABB by matrix. Matrix has to be only rotation and translation.|
|[`BoundingBoxD TransformFast(ref MatrixD m)`](VRageMath.TransformFast)||
|[`void TransformFast(ref MatrixD m, ref BoundingBoxD bb)`](VRageMath.TransformFast)||
|[`BoundingBoxD Include(ref Vector3D point)`](VRageMath.Include)||
|[`BoundingBoxD Include(Vector3D point)`](VRageMath.Include)||
|[`BoundingBoxD Include(Vector3D p0, Vector3D p1, Vector3D p2)`](VRageMath.Include)||
|[`BoundingBoxD Include(ref Vector3D p0, ref Vector3D p1, ref Vector3D p2)`](VRageMath.Include)||
|[`BoundingBoxD Include(ref BoundingBoxD box)`](VRageMath.Include)||
|[`BoundingBoxD Include(BoundingBoxD box)`](VRageMath.Include)||
|[`void Include(ref LineD line)`](VRageMath.Include)||
|[`BoundingBoxD Include(BoundingSphereD sphere)`](VRageMath.Include)||
|[`BoundingBoxD Include(ref BoundingSphereD sphere)`](VRageMath.Include)||
|[`BoundingBoxD Include(ref BoundingFrustumD frustum)`](VRageMath.Include)||
|[`BoundingBoxD CreateInvalid()`](VRageMath.CreateInvalid)||
|[`double ProjectedArea(Vector3D viewDir)`](VRageMath.ProjectedArea)||
|[`BoundingBoxD Inflate(double size)`](VRageMath.Inflate)||
|[`BoundingBoxD Inflate(Vector3 size)`](VRageMath.Inflate)||
|[`BoundingBoxD GetInflated(double size)`](VRageMath.GetInflated)||
|[`BoundingBoxD GetInflated(Vector3 size)`](VRageMath.GetInflated)||
|[`void InflateToMinimum(Vector3D minimumSize)`](VRageMath.InflateToMinimum)||
|[`void InflateToMinimum(double minimumSize)`](VRageMath.InflateToMinimum)||
|[`void AssertIsValid()`](VRageMath.AssertIsValid)||
