← [Index](index.md)
# BoundingBoxD Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`Vector3D Min`](VRageMath.Min.md)||
|[`Vector3D Max`](VRageMath.Max.md)||
|[`ComparerType Comparer`](VRageMath.Comparer.md)||
|[`int CornerCount`](VRageMath.CornerCount.md)||
### Properties
|Member|Description|
|---|---|
|[`Vector3D Center`](VRageMath.Center.md)||
|[`Vector3D HalfExtents`](VRageMath.HalfExtents.md)||
|[`Vector3D Extents`](VRageMath.Extents.md)||
|[`Vector3D Size`](VRageMath.Size.md)||
|[`MatrixD Matrix`](VRageMath.Matrix.md)||
|[`double SurfaceArea`](VRageMath.SurfaceArea.md)||
|[`double Volume`](VRageMath.Volume.md)||
|[`double Perimeter`](VRageMath.Perimeter.md)||
|[`bool Valid`](VRageMath.Valid.md)||
### Methods
|Member|Description|
|---|---|
|[`Vector3D[] GetCorners()`](VRageMath.GetCorners.md)||
|[`void GetCorners(Vector3D[] corners)`](VRageMath.GetCorners.md)|Gets the array of points that make up the corners of the BoundingBox.|
|[`void GetCornersUnsafe(*Vector3D corners)`](VRageMath.GetCornersUnsafe.md)||
|[`bool Equals(BoundingBoxD other)`](VRageMath.Equals.md)|Determines whether two instances of BoundingBox are equal.|
|[`bool Equals(Object obj)`](VRageMath.Equals.md)|Determines whether two instances of BoundingBox are equal.|
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`string ToString()`](VRageMath.ToString.md)||
|[`BoundingBoxD CreateMerged(BoundingBoxD original, BoundingBoxD additional)`](VRageMath.CreateMerged.md)||
|[`void CreateMerged(ref BoundingBoxD original, ref BoundingBoxD additional, ref BoundingBoxD result)`](VRageMath.CreateMerged.md)||
|[`BoundingBoxD CreateFromSphere(BoundingSphereD sphere)`](VRageMath.CreateFromSphere.md)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|[`void CreateFromSphere(ref BoundingSphereD sphere, ref BoundingBoxD result)`](VRageMath.CreateFromSphere.md)||
|[`BoundingBoxD CreateFromPoints(IEnumerable<Vector3D> points)`](VRageMath.CreateFromPoints.md)|Creates the smallest BoundingBox that will contain a group of points.|
|[`BoundingBoxD Intersect(BoundingBoxD box)`](VRageMath.Intersect.md)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`bool Intersects(BoundingBoxD box)`](VRageMath.Intersects.md)|Checks whether the current BoundingBox intersects another BoundingBox.|
|[`bool Intersects(ref BoundingBoxD box)`](VRageMath.Intersects.md)||
|[`void Intersects(ref BoundingBoxD box, ref bool result)`](VRageMath.Intersects.md)||
|[`void Intersects(ref BoundingBox box, ref bool result)`](VRageMath.Intersects.md)||
|[`bool IntersectsTriangle(Vector3D v0, Vector3D v1, Vector3D v2)`](VRageMath.IntersectsTriangle.md)||
|[`bool IntersectsTriangle(ref Vector3D v0, ref Vector3D v1, ref Vector3D v2)`](VRageMath.IntersectsTriangle.md)||
|[`bool Intersects(BoundingFrustumD frustum)`](VRageMath.Intersects.md)|Checks whether the current BoundingBox intersects a BoundingFrustum.|
|[`PlaneIntersectionType Intersects(PlaneD plane)`](VRageMath.Intersects.md)|Checks whether the current BoundingBox intersects a Plane.|
|[`void Intersects(ref PlaneD plane, ref PlaneIntersectionType result)`](VRageMath.Intersects.md)||
|[`bool Intersects(ref LineD line)`](VRageMath.Intersects.md)||
|[`bool Intersects(ref LineD line, ref double distance)`](VRageMath.Intersects.md)||
|[`Nullable<double> Intersects(Ray ray)`](VRageMath.Intersects.md)||
|[`Nullable<double> Intersects(RayD ray)`](VRageMath.Intersects.md)|Checks whether the current BoundingBox intersects a Ray.|
|[`void Intersects(ref RayD ray, ref Nullable<double> result)`](VRageMath.Intersects.md)||
|[`bool Intersect(ref LineD line, ref LineD intersectedLine)`](VRageMath.Intersect.md)||
|[`bool Intersect(ref LineD line, ref double t1, ref double t2)`](VRageMath.Intersect.md)||
|[`bool Intersect(ref RayD ray, ref double tmin, ref double tmax)`](VRageMath.Intersect.md)||
|[`bool Intersects(BoundingSphereD sphere)`](VRageMath.Intersects.md)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|[`void Intersects(ref BoundingSphereD sphere, ref bool result)`](VRageMath.Intersects.md)||
|[`bool Intersects(ref BoundingSphereD sphere)`](VRageMath.Intersects.md)||
|[`double Distance(Vector3D point)`](VRageMath.Distance.md)||
|[`double DistanceSquared(Vector3D point)`](VRageMath.DistanceSquared.md)||
|[`double DistanceSquared(ref Vector3D point)`](VRageMath.DistanceSquared.md)||
|[`ContainmentType Contains(BoundingBoxD box)`](VRageMath.Contains.md)|Tests whether the BoundingBox contains another BoundingBox.|
|[`void Contains(ref BoundingBoxD box, ref ContainmentType result)`](VRageMath.Contains.md)||
|[`ContainmentType Contains(BoundingFrustumD frustum)`](VRageMath.Contains.md)|Tests whether the BoundingBox contains a BoundingFrustum.|
|[`ContainmentType Contains(Vector3D point)`](VRageMath.Contains.md)|Tests whether the BoundingBox contains a point.|
|[`void Contains(ref Vector3D point, ref ContainmentType result)`](VRageMath.Contains.md)||
|[`ContainmentType Contains(BoundingSphereD sphere)`](VRageMath.Contains.md)|Tests whether the BoundingBox contains a BoundingSphere.|
|[`void Contains(ref BoundingSphereD sphere, ref ContainmentType result)`](VRageMath.Contains.md)||
|[`BoundingBoxD Translate(MatrixD worldMatrix)`](VRageMath.Translate.md)|Translate|
|[`BoundingBoxD Translate(Vector3D vctTranlsation)`](VRageMath.Translate.md)|Translate|
|[`BoundingBoxD TransformSlow(MatrixD m)`](VRageMath.TransformSlow.md)|Transform this AABB by matrix.|
|[`BoundingBoxD TransformSlow(ref MatrixD worldMatrix)`](VRageMath.TransformSlow.md)||
|[`BoundingBoxD TransformFast(MatrixD m)`](VRageMath.TransformFast.md)|Transform this AABB by matrix. Matrix has to be only rotation and translation.|
|[`BoundingBoxD TransformFast(ref MatrixD m)`](VRageMath.TransformFast.md)||
|[`void TransformFast(ref MatrixD m, ref BoundingBoxD bb)`](VRageMath.TransformFast.md)||
|[`BoundingBoxD Include(ref Vector3D point)`](VRageMath.Include.md)||
|[`BoundingBoxD Include(Vector3D point)`](VRageMath.Include.md)||
|[`BoundingBoxD Include(Vector3D p0, Vector3D p1, Vector3D p2)`](VRageMath.Include.md)||
|[`BoundingBoxD Include(ref Vector3D p0, ref Vector3D p1, ref Vector3D p2)`](VRageMath.Include.md)||
|[`BoundingBoxD Include(ref BoundingBoxD box)`](VRageMath.Include.md)||
|[`BoundingBoxD Include(BoundingBoxD box)`](VRageMath.Include.md)||
|[`void Include(ref LineD line)`](VRageMath.Include.md)||
|[`BoundingBoxD Include(BoundingSphereD sphere)`](VRageMath.Include.md)||
|[`BoundingBoxD Include(ref BoundingSphereD sphere)`](VRageMath.Include.md)||
|[`BoundingBoxD Include(ref BoundingFrustumD frustum)`](VRageMath.Include.md)||
|[`BoundingBoxD CreateInvalid()`](VRageMath.CreateInvalid.md)||
|[`double ProjectedArea(Vector3D viewDir)`](VRageMath.ProjectedArea.md)||
|[`BoundingBoxD Inflate(double size)`](VRageMath.Inflate.md)||
|[`BoundingBoxD Inflate(Vector3 size)`](VRageMath.Inflate.md)||
|[`BoundingBoxD GetInflated(double size)`](VRageMath.GetInflated.md)||
|[`BoundingBoxD GetInflated(Vector3 size)`](VRageMath.GetInflated.md)||
|[`void InflateToMinimum(Vector3D minimumSize)`](VRageMath.InflateToMinimum.md)||
|[`void InflateToMinimum(double minimumSize)`](VRageMath.InflateToMinimum.md)||
|[`void AssertIsValid()`](VRageMath.AssertIsValid.md)||
