← [Index](index)
# BoundingBoxI Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`Min`](VRageMath.Min)|The minimum point the BoundingBoxI contains.|
|[`Max`](VRageMath.Max)|The maximum point the BoundingBoxI contains.|
|static [`CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingBoxI.|
### Properties
|Member|Description|
|---|---|
|[`Center`](VRageMath.Center)|Calculates center|
|[`HalfExtents`](VRageMath.HalfExtents)||
|[`Size`](VRageMath.Size)|Size|
|[`Perimeter`](VRageMath.Perimeter)|return perimeter of edges|
|[`IsValid`](VRageMath.IsValid)||
### Methods
|Member|Description|
|---|---|
|[`GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingBoxI.|
|[`GetCorners(Vector3I[])`](VRageMath.GetCorners)|Gets the array of points that make up the corners of the BoundingBoxI.|
|[`GetCornersUnsafe(*Vector3I)`](VRageMath.GetCornersUnsafe)||
|[`Equals(BoundingBoxI)`](VRageMath.Equals)|Determines whether two instances of BoundingBoxI are equal.|
|[`Equals(Object)`](VRageMath.Equals)|Determines whether two instances of BoundingBoxI are equal.|
|[`GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingBoxI.|
|static [`CreateMerged(BoundingBoxI, BoundingBoxI)`](VRageMath.CreateMerged)|Creates the smallest BoundingBoxI that contains the two specified BoundingBoxI instances.|
|static [`CreateMerged(ref BoundingBoxI, ref BoundingBoxI, ref BoundingBoxI)`](VRageMath.CreateMerged)|Creates the smallest BoundingBoxI that contains the two specified BoundingBoxI instances.|
|static [`CreateFromSphere(BoundingSphere)`](VRageMath.CreateFromSphere)|Creates the smallest BoundingBoxI that will contain the specified BoundingSphere.|
|static [`CreateFromSphere(ref BoundingSphere, ref BoundingBoxI)`](VRageMath.CreateFromSphere)|Creates the smallest BoundingBoxI that will contain the specified BoundingSphere.|
|static [`CreateFromPoints(IEnumerable<Vector3I>)`](VRageMath.CreateFromPoints)|Creates the smallest BoundingBoxI that will contain a group of points.|
|[`IntersectWith(ref BoundingBoxI)`](VRageMath.IntersectWith)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`Intersect(BoundingBoxI)`](VRageMath.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`Intersects(BoundingBoxI)`](VRageMath.Intersects)|Checks whether the current BoundingBoxI intersects another BoundingBoxI.|
|[`Intersects(ref BoundingBoxI)`](VRageMath.Intersects)||
|[`Intersects(ref BoundingBoxI, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingBoxI intersects another BoundingBoxI.|
|[`IntersectsTriangle(Vector3I, Vector3I, Vector3I)`](VRageMath.IntersectsTriangle)||
|[`IntersectsTriangle(ref Vector3I, ref Vector3I, ref Vector3I)`](VRageMath.IntersectsTriangle)||
|[`Intersects(Plane)`](VRageMath.Intersects)|Checks whether the current BoundingBoxI intersects a Plane.|
|[`Intersects(ref Plane, ref PlaneIntersectionType)`](VRageMath.Intersects)|Checks whether the current BoundingBoxI intersects a Plane.|
|[`Intersects(Line, ref float)`](VRageMath.Intersects)||
|[`Intersects(Ray)`](VRageMath.Intersects)|Checks whether the current BoundingBoxI intersects a Ray.|
|[`Intersects(ref Ray, ref Nullable<float>)`](VRageMath.Intersects)|Checks whether the current BoundingBoxI intersects a Ray.|
|[`Distance(Vector3I)`](VRageMath.Distance)|Checks whether the current BoundingBoxI intersects a BoundingSphere.|
|[`Contains(BoundingBoxI)`](VRageMath.Contains)|Tests whether the BoundingBoxI contains another BoundingBoxI.|
|[`Contains(ref BoundingBoxI, ref ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBoxI contains a BoundingBoxI.|
|[`Contains(Vector3I)`](VRageMath.Contains)|Tests whether the BoundingBoxI contains a point.|
|[`Contains(Vector3)`](VRageMath.Contains)||
|[`Contains(ref Vector3I, ref ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBoxI contains a point.|
|[`Translate(Vector3I)`](VRageMath.Translate)|Translate|
|[`Include(ref Vector3I)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`GetIncluded(Vector3I)`](VRageMath.GetIncluded)||
|[`Include(Vector3I)`](VRageMath.Include)||
|[`Include(Vector3I, Vector3I, Vector3I)`](VRageMath.Include)||
|[`Include(ref Vector3I, ref Vector3I, ref Vector3I)`](VRageMath.Include)||
|[`Include(ref BoundingBoxI)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`Include(BoundingBoxI)`](VRageMath.Include)||
|static [`CreateInvalid()`](VRageMath.CreateInvalid)||
|[`SurfaceArea()`](VRageMath.SurfaceArea)||
|[`Volume()`](VRageMath.Volume)||
|[`Inflate(int)`](VRageMath.Inflate)||
|[`InflateToMinimum(Vector3I)`](VRageMath.InflateToMinimum)||
|static [`IterateDifference(BoundingBoxI, BoundingBoxI)`](VRageMath.IterateDifference)|Iterate every cell contained in {left} - {right}, where we interpret {box} as the set of all distinct Vector3I points inside a 'box'. Containment is taken in a typical inclusive start, exclusive end fashion.|
|static [`EnumeratePoints(BoundingBoxI)`](VRageMath.EnumeratePoints)|Enumerate all values in a integer interval (a cuboid). This method is an allocating version of the Vector3I_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.|
