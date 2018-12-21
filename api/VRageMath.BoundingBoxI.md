← [Index](index)
# BoundingBoxI Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`Vector3I Min`](VRageMath.Min)||
|[`Vector3I Max`](VRageMath.Max)||
|[`int CornerCount`](VRageMath.CornerCount)||
### Properties
|Member|Description|
|---|---|
|[`Vector3I Center`](VRageMath.Center)||
|[`Vector3I HalfExtents`](VRageMath.HalfExtents)||
|[`Vector3I Size`](VRageMath.Size)||
|[`float Perimeter`](VRageMath.Perimeter)||
|[`bool IsValid`](VRageMath.IsValid)||
### Methods
|Member|Description|
|---|---|
|[`Vector3I[] GetCorners()`](VRageMath.GetCorners)||
|[`void GetCorners(Vector3I[] corners)`](VRageMath.GetCorners)|Gets the array of points that make up the corners of the BoundingBoxI.|
|[`void GetCornersUnsafe(*Vector3I corners)`](VRageMath.GetCornersUnsafe)||
|[`bool Equals(BoundingBoxI other)`](VRageMath.Equals)|Determines whether two instances of BoundingBoxI are equal.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Determines whether two instances of BoundingBoxI are equal.|
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`string ToString()`](VRageMath.ToString)||
|[`BoundingBoxI CreateMerged(BoundingBoxI original, BoundingBoxI additional)`](VRageMath.CreateMerged)||
|[`void CreateMerged(ref BoundingBoxI original, ref BoundingBoxI additional, ref BoundingBoxI result)`](VRageMath.CreateMerged)||
|[`BoundingBoxI CreateFromSphere(BoundingSphere sphere)`](VRageMath.CreateFromSphere)|Creates the smallest BoundingBoxI that will contain the specified BoundingSphere.|
|[`void CreateFromSphere(ref BoundingSphere sphere, ref BoundingBoxI result)`](VRageMath.CreateFromSphere)||
|[`BoundingBoxI CreateFromPoints(IEnumerable<Vector3I> points)`](VRageMath.CreateFromPoints)|Creates the smallest BoundingBoxI that will contain a group of points.|
|[`void IntersectWith(ref BoundingBoxI box)`](VRageMath.IntersectWith)||
|[`BoundingBoxI Intersect(BoundingBoxI box)`](VRageMath.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`bool Intersects(BoundingBoxI box)`](VRageMath.Intersects)|Checks whether the current BoundingBoxI intersects another BoundingBoxI.|
|[`bool Intersects(ref BoundingBoxI box)`](VRageMath.Intersects)||
|[`void Intersects(ref BoundingBoxI box, ref bool result)`](VRageMath.Intersects)||
|[`bool IntersectsTriangle(Vector3I v0, Vector3I v1, Vector3I v2)`](VRageMath.IntersectsTriangle)||
|[`bool IntersectsTriangle(ref Vector3I v0, ref Vector3I v1, ref Vector3I v2)`](VRageMath.IntersectsTriangle)||
|[`PlaneIntersectionType Intersects(Plane plane)`](VRageMath.Intersects)|Checks whether the current BoundingBoxI intersects a Plane.|
|[`void Intersects(ref Plane plane, ref PlaneIntersectionType result)`](VRageMath.Intersects)||
|[`bool Intersects(Line line, ref float distance)`](VRageMath.Intersects)||
|[`Nullable<float> Intersects(Ray ray)`](VRageMath.Intersects)|Checks whether the current BoundingBoxI intersects a Ray.|
|[`void Intersects(ref Ray ray, ref Nullable<float> result)`](VRageMath.Intersects)||
|[`float Distance(Vector3I point)`](VRageMath.Distance)|Checks whether the current BoundingBoxI intersects a BoundingSphere.|
|[`ContainmentType Contains(BoundingBoxI box)`](VRageMath.Contains)|Tests whether the BoundingBoxI contains another BoundingBoxI.|
|[`void Contains(ref BoundingBoxI box, ref ContainmentType result)`](VRageMath.Contains)||
|[`ContainmentType Contains(Vector3I point)`](VRageMath.Contains)|Tests whether the BoundingBoxI contains a point.|
|[`ContainmentType Contains(Vector3 point)`](VRageMath.Contains)||
|[`void Contains(ref Vector3I point, ref ContainmentType result)`](VRageMath.Contains)||
|[`BoundingBoxI Translate(Vector3I vctTranlsation)`](VRageMath.Translate)|Translate|
|[`BoundingBoxI Include(ref Vector3I point)`](VRageMath.Include)||
|[`BoundingBoxI GetIncluded(Vector3I point)`](VRageMath.GetIncluded)||
|[`BoundingBoxI Include(Vector3I point)`](VRageMath.Include)||
|[`BoundingBoxI Include(Vector3I p0, Vector3I p1, Vector3I p2)`](VRageMath.Include)||
|[`BoundingBoxI Include(ref Vector3I p0, ref Vector3I p1, ref Vector3I p2)`](VRageMath.Include)||
|[`BoundingBoxI Include(ref BoundingBoxI box)`](VRageMath.Include)||
|[`BoundingBoxI Include(BoundingBoxI box)`](VRageMath.Include)||
|[`BoundingBoxI CreateInvalid()`](VRageMath.CreateInvalid)||
|[`float SurfaceArea()`](VRageMath.SurfaceArea)||
|[`float Volume()`](VRageMath.Volume)||
|[`void Inflate(int size)`](VRageMath.Inflate)||
|[`void InflateToMinimum(Vector3I minimumSize)`](VRageMath.InflateToMinimum)||
|[`IEnumerable<Vector3I> IterateDifference(BoundingBoxI left, BoundingBoxI right)`](VRageMath.IterateDifference)||
|[`IEnumerable<Vector3I> EnumeratePoints(BoundingBoxI rangeInclusive)`](VRageMath.EnumeratePoints)|Enumerate all values in a integer interval (a cuboid). This method is an allocating version of the Vector3I_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.|
