← [Index](index.md)
# BoundingBoxI Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`Vector3I Min`](VRageMath.Min.md)||
|[`Vector3I Max`](VRageMath.Max.md)||
|[`int CornerCount`](VRageMath.CornerCount.md)||
### Properties
|Member|Description|
|---|---|
|[`Vector3I Center`](VRageMath.Center.md)||
|[`Vector3I HalfExtents`](VRageMath.HalfExtents.md)||
|[`Vector3I Size`](VRageMath.Size.md)||
|[`float Perimeter`](VRageMath.Perimeter.md)||
|[`bool IsValid`](VRageMath.IsValid.md)||
### Methods
|Member|Description|
|---|---|
|[`Vector3I[] GetCorners()`](VRageMath.GetCorners.md)||
|[`void GetCorners(Vector3I[] corners)`](VRageMath.GetCorners.md)|Gets the array of points that make up the corners of the BoundingBoxI.|
|[`void GetCornersUnsafe(*Vector3I corners)`](VRageMath.GetCornersUnsafe.md)||
|[`bool Equals(BoundingBoxI other)`](VRageMath.Equals.md)|Determines whether two instances of BoundingBoxI are equal.|
|[`bool Equals(Object obj)`](VRageMath.Equals.md)|Determines whether two instances of BoundingBoxI are equal.|
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`string ToString()`](VRageMath.ToString.md)||
|[`BoundingBoxI CreateMerged(BoundingBoxI original, BoundingBoxI additional)`](VRageMath.CreateMerged.md)||
|[`void CreateMerged(ref BoundingBoxI original, ref BoundingBoxI additional, ref BoundingBoxI result)`](VRageMath.CreateMerged.md)||
|[`BoundingBoxI CreateFromSphere(BoundingSphere sphere)`](VRageMath.CreateFromSphere.md)|Creates the smallest BoundingBoxI that will contain the specified BoundingSphere.|
|[`void CreateFromSphere(ref BoundingSphere sphere, ref BoundingBoxI result)`](VRageMath.CreateFromSphere.md)||
|[`BoundingBoxI CreateFromPoints(IEnumerable<Vector3I> points)`](VRageMath.CreateFromPoints.md)|Creates the smallest BoundingBoxI that will contain a group of points.|
|[`void IntersectWith(ref BoundingBoxI box)`](VRageMath.IntersectWith.md)||
|[`BoundingBoxI Intersect(BoundingBoxI box)`](VRageMath.Intersect.md)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`bool Intersects(BoundingBoxI box)`](VRageMath.Intersects.md)|Checks whether the current BoundingBoxI intersects another BoundingBoxI.|
|[`bool Intersects(ref BoundingBoxI box)`](VRageMath.Intersects.md)||
|[`void Intersects(ref BoundingBoxI box, ref bool result)`](VRageMath.Intersects.md)||
|[`bool IntersectsTriangle(Vector3I v0, Vector3I v1, Vector3I v2)`](VRageMath.IntersectsTriangle.md)||
|[`bool IntersectsTriangle(ref Vector3I v0, ref Vector3I v1, ref Vector3I v2)`](VRageMath.IntersectsTriangle.md)||
|[`PlaneIntersectionType Intersects(Plane plane)`](VRageMath.Intersects.md)|Checks whether the current BoundingBoxI intersects a Plane.|
|[`void Intersects(ref Plane plane, ref PlaneIntersectionType result)`](VRageMath.Intersects.md)||
|[`bool Intersects(Line line, ref float distance)`](VRageMath.Intersects.md)||
|[`Nullable<float> Intersects(Ray ray)`](VRageMath.Intersects.md)|Checks whether the current BoundingBoxI intersects a Ray.|
|[`void Intersects(ref Ray ray, ref Nullable<float> result)`](VRageMath.Intersects.md)||
|[`float Distance(Vector3I point)`](VRageMath.Distance.md)|Checks whether the current BoundingBoxI intersects a BoundingSphere.|
|[`ContainmentType Contains(BoundingBoxI box)`](VRageMath.Contains.md)|Tests whether the BoundingBoxI contains another BoundingBoxI.|
|[`void Contains(ref BoundingBoxI box, ref ContainmentType result)`](VRageMath.Contains.md)||
|[`ContainmentType Contains(Vector3I point)`](VRageMath.Contains.md)|Tests whether the BoundingBoxI contains a point.|
|[`ContainmentType Contains(Vector3 point)`](VRageMath.Contains.md)||
|[`void Contains(ref Vector3I point, ref ContainmentType result)`](VRageMath.Contains.md)||
|[`BoundingBoxI Translate(Vector3I vctTranlsation)`](VRageMath.Translate.md)|Translate|
|[`BoundingBoxI Include(ref Vector3I point)`](VRageMath.Include.md)||
|[`BoundingBoxI GetIncluded(Vector3I point)`](VRageMath.GetIncluded.md)||
|[`BoundingBoxI Include(Vector3I point)`](VRageMath.Include.md)||
|[`BoundingBoxI Include(Vector3I p0, Vector3I p1, Vector3I p2)`](VRageMath.Include.md)||
|[`BoundingBoxI Include(ref Vector3I p0, ref Vector3I p1, ref Vector3I p2)`](VRageMath.Include.md)||
|[`BoundingBoxI Include(ref BoundingBoxI box)`](VRageMath.Include.md)||
|[`BoundingBoxI Include(BoundingBoxI box)`](VRageMath.Include.md)||
|[`BoundingBoxI CreateInvalid()`](VRageMath.CreateInvalid.md)||
|[`float SurfaceArea()`](VRageMath.SurfaceArea.md)||
|[`float Volume()`](VRageMath.Volume.md)||
|[`void Inflate(int size)`](VRageMath.Inflate.md)||
|[`void InflateToMinimum(Vector3I minimumSize)`](VRageMath.InflateToMinimum.md)||
|[`IEnumerable<Vector3I> IterateDifference(BoundingBoxI left, BoundingBoxI right)`](VRageMath.IterateDifference.md)||
|[`IEnumerable<Vector3I> EnumeratePoints(BoundingBoxI rangeInclusive)`](VRageMath.EnumeratePoints.md)|Enumerate all values in a integer interval (a cuboid). This method is an allocating version of the Vector3I_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.|
