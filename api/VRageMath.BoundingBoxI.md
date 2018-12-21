← [Index](index)
# BoundingBoxI Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`VRageMath.Vector3I Min`](VRageMath.Min)|The minimum point the BoundingBoxI contains.|
|[`VRageMath.Vector3I Max`](VRageMath.Max)|The maximum point the BoundingBoxI contains.|
|static [`int CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingBoxI.|
### Properties
|Member|Description|
|---|---|
|[`VRageMath.Vector3I Center`](VRageMath.Center)|Calculates center|
|[`VRageMath.Vector3I HalfExtents`](VRageMath.HalfExtents)||
|[`VRageMath.Vector3I Size`](VRageMath.Size)|Size|
|[`float Perimeter`](VRageMath.Perimeter)|return perimeter of edges|
|[`bool IsValid`](VRageMath.IsValid)||
### Methods
|Member|Description|
|---|---|
|[`VRageMath.Vector3I[] GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingBoxI.|
|[`void GetCorners(VRageMath.Vector3I[])`](VRageMath.GetCorners)|Gets the array of points that make up the corners of the BoundingBoxI.|
|[`void GetCornersUnsafe(*VRageMath.Vector3I)`](VRageMath.GetCornersUnsafe)||
|[`bool Equals(VRageMath.BoundingBoxI)`](VRageMath.Equals)|Determines whether two instances of BoundingBoxI are equal.|
|[`bool Equals(System.Object)`](VRageMath.Equals)|Determines whether two instances of BoundingBoxI are equal.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingBoxI.|
|static [`VRageMath.BoundingBoxI CreateMerged(VRageMath.BoundingBoxI, VRageMath.BoundingBoxI)`](VRageMath.CreateMerged)|Creates the smallest BoundingBoxI that contains the two specified BoundingBoxI instances.|
|static [`void CreateMerged(ref VRageMath.BoundingBoxI, ref VRageMath.BoundingBoxI, ref VRageMath.BoundingBoxI)`](VRageMath.CreateMerged)|Creates the smallest BoundingBoxI that contains the two specified BoundingBoxI instances.|
|static [`VRageMath.BoundingBoxI CreateFromSphere(VRageMath.BoundingSphere)`](VRageMath.CreateFromSphere)|Creates the smallest BoundingBoxI that will contain the specified BoundingSphere.|
|static [`void CreateFromSphere(ref VRageMath.BoundingSphere, ref VRageMath.BoundingBoxI)`](VRageMath.CreateFromSphere)|Creates the smallest BoundingBoxI that will contain the specified BoundingSphere.|
|static [`VRageMath.BoundingBoxI CreateFromPoints(IEnumerable<VRageMath.Vector3I>)`](VRageMath.CreateFromPoints)|Creates the smallest BoundingBoxI that will contain a group of points.|
|[`void IntersectWith(ref VRageMath.BoundingBoxI)`](VRageMath.IntersectWith)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`VRageMath.BoundingBoxI Intersect(VRageMath.BoundingBoxI)`](VRageMath.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`bool Intersects(VRageMath.BoundingBoxI)`](VRageMath.Intersects)|Checks whether the current BoundingBoxI intersects another BoundingBoxI.|
|[`bool Intersects(ref VRageMath.BoundingBoxI)`](VRageMath.Intersects)||
|[`void Intersects(ref VRageMath.BoundingBoxI, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingBoxI intersects another BoundingBoxI.|
|[`bool IntersectsTriangle(VRageMath.Vector3I, VRageMath.Vector3I, VRageMath.Vector3I)`](VRageMath.IntersectsTriangle)||
|[`bool IntersectsTriangle(ref VRageMath.Vector3I, ref VRageMath.Vector3I, ref VRageMath.Vector3I)`](VRageMath.IntersectsTriangle)||
|[`VRageMath.PlaneIntersectionType Intersects(VRageMath.Plane)`](VRageMath.Intersects)|Checks whether the current BoundingBoxI intersects a Plane.|
|[`void Intersects(ref VRageMath.Plane, ref VRageMath.PlaneIntersectionType)`](VRageMath.Intersects)|Checks whether the current BoundingBoxI intersects a Plane.|
|[`bool Intersects(VRageMath.Line, ref float)`](VRageMath.Intersects)||
|[`Nullable<System.Single> Intersects(VRageMath.Ray)`](VRageMath.Intersects)|Checks whether the current BoundingBoxI intersects a Ray.|
|[`void Intersects(ref VRageMath.Ray, ref Nullable<System.Single>)`](VRageMath.Intersects)|Checks whether the current BoundingBoxI intersects a Ray.|
|[`float Distance(VRageMath.Vector3I)`](VRageMath.Distance)|Checks whether the current BoundingBoxI intersects a BoundingSphere.|
|[`VRageMath.ContainmentType Contains(VRageMath.BoundingBoxI)`](VRageMath.Contains)|Tests whether the BoundingBoxI contains another BoundingBoxI.|
|[`void Contains(ref VRageMath.BoundingBoxI, ref VRageMath.ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBoxI contains a BoundingBoxI.|
|[`VRageMath.ContainmentType Contains(VRageMath.Vector3I)`](VRageMath.Contains)|Tests whether the BoundingBoxI contains a point.|
|[`VRageMath.ContainmentType Contains(VRageMath.Vector3)`](VRageMath.Contains)||
|[`void Contains(ref VRageMath.Vector3I, ref VRageMath.ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBoxI contains a point.|
|[`VRageMath.BoundingBoxI Translate(VRageMath.Vector3I)`](VRageMath.Translate)|Translate|
|[`VRageMath.BoundingBoxI Include(ref VRageMath.Vector3I)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`VRageMath.BoundingBoxI GetIncluded(VRageMath.Vector3I)`](VRageMath.GetIncluded)||
|[`VRageMath.BoundingBoxI Include(VRageMath.Vector3I)`](VRageMath.Include)||
|[`VRageMath.BoundingBoxI Include(VRageMath.Vector3I, VRageMath.Vector3I, VRageMath.Vector3I)`](VRageMath.Include)||
|[`VRageMath.BoundingBoxI Include(ref VRageMath.Vector3I, ref VRageMath.Vector3I, ref VRageMath.Vector3I)`](VRageMath.Include)||
|[`VRageMath.BoundingBoxI Include(ref VRageMath.BoundingBoxI)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`VRageMath.BoundingBoxI Include(VRageMath.BoundingBoxI)`](VRageMath.Include)||
|static [`VRageMath.BoundingBoxI CreateInvalid()`](VRageMath.CreateInvalid)||
|[`float SurfaceArea()`](VRageMath.SurfaceArea)||
|[`float Volume()`](VRageMath.Volume)||
|[`void Inflate(int)`](VRageMath.Inflate)||
|[`void InflateToMinimum(VRageMath.Vector3I)`](VRageMath.InflateToMinimum)||
|static [`IEnumerable<VRageMath.Vector3I> IterateDifference(VRageMath.BoundingBoxI, VRageMath.BoundingBoxI)`](VRageMath.IterateDifference)|Iterate every cell contained in {left} - {right}, where we interpret {box} as the set of all distinct Vector3I points inside a 'box'. Containment is taken in a typical inclusive start, exclusive end fashion.|
|static [`IEnumerable<VRageMath.Vector3I> EnumeratePoints(VRageMath.BoundingBoxI)`](VRageMath.EnumeratePoints)|Enumerate all values in a integer interval (a cuboid). This method is an allocating version of the Vector3I_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.|
