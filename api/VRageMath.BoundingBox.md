← [Index](index.md)
# BoundingBox Struct
** Namespace: ** VRageMath  
** Assembly: ** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`Vector3 Min`](VRageMath.Min.md)||
|[`Vector3 Max`](VRageMath.Max.md)||
|[`ComparerType Comparer`](VRageMath.Comparer.md)||
|[`int CornerCount`](VRageMath.CornerCount.md)||
### Properties
|Member|Description|
|---|---|
|[`BoxCornerEnumerator Corners`](VRageMath.Corners.md)||
|[`Vector3 Center`](VRageMath.Center.md)||
|[`Vector3 HalfExtents`](VRageMath.HalfExtents.md)||
|[`Vector3 Extents`](VRageMath.Extents.md)||
|[`float Width`](VRageMath.Width.md)||
|[`float Height`](VRageMath.Height.md)||
|[`float Depth`](VRageMath.Depth.md)||
|[`Vector3 Size`](VRageMath.Size.md)||
|[`Matrix Matrix`](VRageMath.Matrix.md)||
|[`float Perimeter`](VRageMath.Perimeter.md)||
### Methods
|Member|Description|
|---|---|
|[`Vector3[] GetCorners()`](VRageMath.GetCorners.md)||
|[`void GetCorners(Vector3[] corners)`](VRageMath.GetCorners.md)|Gets the array of points that make up the corners of the BoundingBox.|
|[`void GetCornersUnsafe(*Vector3 corners)`](VRageMath.GetCornersUnsafe.md)||
|[`bool Equals(BoundingBox other)`](VRageMath.Equals.md)|Determines whether two instances of BoundingBox are equal.|
|[`bool Equals(Object obj)`](VRageMath.Equals.md)|Determines whether two instances of BoundingBox are equal.|
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`string ToString()`](VRageMath.ToString.md)||
|[`BoundingBox CreateMerged(BoundingBox original, BoundingBox additional)`](VRageMath.CreateMerged.md)||
|[`void CreateMerged(ref BoundingBox original, ref BoundingBox additional, ref BoundingBox result)`](VRageMath.CreateMerged.md)||
|[`BoundingBox CreateFromSphere(BoundingSphere sphere)`](VRageMath.CreateFromSphere.md)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|[`void CreateFromSphere(ref BoundingSphere sphere, ref BoundingBox result)`](VRageMath.CreateFromSphere.md)||
|[`BoundingBox CreateFromPoints(IEnumerable<Vector3> points)`](VRageMath.CreateFromPoints.md)|Creates the smallest BoundingBox that will contain a group of points.|
|[`BoundingBox CreateFromHalfExtent(Vector3 center, float halfExtent)`](VRageMath.CreateFromHalfExtent.md)||
|[`BoundingBox CreateFromHalfExtent(Vector3 center, Vector3 halfExtent)`](VRageMath.CreateFromHalfExtent.md)||
|[`BoundingBox Intersect(BoundingBox box)`](VRageMath.Intersect.md)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`bool Intersects(BoundingBox box)`](VRageMath.Intersects.md)|Checks whether the current BoundingBox intersects another BoundingBox.|
|[`bool Intersects(ref BoundingBox box)`](VRageMath.Intersects.md)||
|[`void Intersects(ref BoundingBox box, ref bool result)`](VRageMath.Intersects.md)||
|[`bool IntersectsTriangle(Vector3 v0, Vector3 v1, Vector3 v2)`](VRageMath.IntersectsTriangle.md)||
|[`bool IntersectsTriangle(ref Vector3 v0, ref Vector3 v1, ref Vector3 v2)`](VRageMath.IntersectsTriangle.md)||
|[`bool Intersects(BoundingFrustum frustum)`](VRageMath.Intersects.md)|Checks whether the current BoundingBox intersects a BoundingFrustum.|
|[`PlaneIntersectionType Intersects(Plane plane)`](VRageMath.Intersects.md)|Checks whether the current BoundingBox intersects a Plane.|
|[`void Intersects(ref Plane plane, ref PlaneIntersectionType result)`](VRageMath.Intersects.md)||
|[`bool Intersects(Line line, ref float distance)`](VRageMath.Intersects.md)||
|[`Nullable<float> Intersects(Ray ray)`](VRageMath.Intersects.md)|Checks whether the current BoundingBox intersects a Ray.|
|[`void Intersects(ref Ray ray, ref Nullable<float> result)`](VRageMath.Intersects.md)||
|[`bool Intersects(BoundingSphere sphere)`](VRageMath.Intersects.md)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|[`void Intersects(ref BoundingSphere sphere, ref bool result)`](VRageMath.Intersects.md)||
|[`bool Intersects(ref BoundingSphere sphere)`](VRageMath.Intersects.md)||
|[`bool Intersects(ref BoundingSphereD sphere)`](VRageMath.Intersects.md)||
|[`float Distance(Vector3 point)`](VRageMath.Distance.md)||
|[`float DistanceSquared(Vector3 point)`](VRageMath.DistanceSquared.md)||
|[`ContainmentType Contains(BoundingBox box)`](VRageMath.Contains.md)|Tests whether the BoundingBox contains another BoundingBox.|
|[`void Contains(ref BoundingBox box, ref ContainmentType result)`](VRageMath.Contains.md)||
|[`ContainmentType Contains(BoundingFrustum frustum)`](VRageMath.Contains.md)|Tests whether the BoundingBox contains a BoundingFrustum.|
|[`ContainmentType Contains(Vector3 point)`](VRageMath.Contains.md)|Tests whether the BoundingBox contains a point.|
|[`ContainmentType Contains(Vector3D point)`](VRageMath.Contains.md)||
|[`void Contains(ref Vector3 point, ref ContainmentType result)`](VRageMath.Contains.md)||
|[`ContainmentType Contains(BoundingSphere sphere)`](VRageMath.Contains.md)|Tests whether the BoundingBox contains a BoundingSphere.|
|[`void Contains(ref BoundingSphere sphere, ref ContainmentType result)`](VRageMath.Contains.md)||
|[`BoundingBox Translate(Matrix worldMatrix)`](VRageMath.Translate.md)|Translate|
|[`BoundingBox Translate(Vector3 vctTranlsation)`](VRageMath.Translate.md)|Translate|
|[`BoundingBox Transform(Matrix worldMatrix)`](VRageMath.Transform.md)||
|[`BoundingBoxD Transform(MatrixD worldMatrix)`](VRageMath.Transform.md)||
|[`BoundingBox Transform(ref Matrix m)`](VRageMath.Transform.md)||
|[`void Transform(ref Matrix m, ref BoundingBox bb)`](VRageMath.Transform.md)||
|[`BoundingBoxD Transform(ref MatrixD m)`](VRageMath.Transform.md)||
|[`void Transform(ref MatrixD m, ref BoundingBoxD bb)`](VRageMath.Transform.md)||
|[`BoundingBox Include(ref Vector3 point)`](VRageMath.Include.md)||
|[`BoundingBox GetIncluded(Vector3 point)`](VRageMath.GetIncluded.md)||
|[`BoundingBox Include(Vector3 point)`](VRageMath.Include.md)||
|[`BoundingBox Include(Vector3 p0, Vector3 p1, Vector3 p2)`](VRageMath.Include.md)||
|[`BoundingBox Include(ref Vector3 p0, ref Vector3 p1, ref Vector3 p2)`](VRageMath.Include.md)||
|[`BoundingBox Include(ref BoundingBox box)`](VRageMath.Include.md)||
|[`BoundingBox Include(BoundingBox box)`](VRageMath.Include.md)||
|[`void Include(ref Line line)`](VRageMath.Include.md)||
|[`BoundingBox Include(BoundingSphere sphere)`](VRageMath.Include.md)||
|[`BoundingBox Include(ref BoundingSphere sphere)`](VRageMath.Include.md)||
|[`BoundingBox Include(ref BoundingFrustum frustum)`](VRageMath.Include.md)||
|[`BoundingBox CreateInvalid()`](VRageMath.CreateInvalid.md)||
|[`float SurfaceArea()`](VRageMath.SurfaceArea.md)||
|[`float Volume()`](VRageMath.Volume.md)||
|[`float ProjectedArea(Vector3 viewDir)`](VRageMath.ProjectedArea.md)||
|[`void Inflate(float size)`](VRageMath.Inflate.md)||
|[`void Inflate(Vector3 size)`](VRageMath.Inflate.md)||
|[`void InflateToMinimum(Vector3 minimumSize)`](VRageMath.InflateToMinimum.md)||
|[`void Scale(Vector3 scale)`](VRageMath.Scale.md)||
