← [Index](index)
# BoundingBoxI Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`Vector3I&nbsp;Min`](VRageMath.Min)|The minimum point the BoundingBoxI contains.|
|[`Vector3I&nbsp;Max`](VRageMath.Max)|The maximum point the BoundingBoxI contains.|
|static&nbsp;[`int&nbsp;CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingBoxI.|
### Properties
|Member|Description|
|---|---|
|[`Vector3I&nbsp;Center`](VRageMath.Center)|Calculates center|
|[`Vector3I&nbsp;HalfExtents`](VRageMath.HalfExtents)||
|[`Vector3I&nbsp;Size`](VRageMath.Size)|Size|
|[`float&nbsp;Perimeter`](VRageMath.Perimeter)|return perimeter of edges|
|[`bool&nbsp;IsValid`](VRageMath.IsValid)||
### Methods
|Member|Description|
|---|---|
|[`Vector3I[]&nbsp;GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingBoxI.|
|[`void&nbsp;GetCorners(Vector3I[]&nbsp;corners)`](VRageMath.GetCorners)|Gets the array of points that make up the corners of the BoundingBoxI.|
|[`void&nbsp;GetCornersUnsafe(*Vector3I&nbsp;corners)`](VRageMath.GetCornersUnsafe)||
|[`bool&nbsp;Equals(BoundingBoxI&nbsp;other)`](VRageMath.Equals)|Determines whether two instances of BoundingBoxI are equal.|
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Determines whether two instances of BoundingBoxI are equal.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string&nbsp;ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingBoxI.|
|static&nbsp;[`BoundingBoxI&nbsp;CreateMerged(BoundingBoxI&nbsp;original,&nbsp;BoundingBoxI&nbsp;additional)`](VRageMath.CreateMerged)|Creates the smallest BoundingBoxI that contains the two specified BoundingBoxI instances.|
|static&nbsp;[`void&nbsp;CreateMerged(ref&nbsp;BoundingBoxI&nbsp;original,&nbsp;ref&nbsp;BoundingBoxI&nbsp;additional,&nbsp;ref&nbsp;BoundingBoxI&nbsp;result)`](VRageMath.CreateMerged)|Creates the smallest BoundingBoxI that contains the two specified BoundingBoxI instances.|
|static&nbsp;[`BoundingBoxI&nbsp;CreateFromSphere(BoundingSphere&nbsp;sphere)`](VRageMath.CreateFromSphere)|Creates the smallest BoundingBoxI that will contain the specified BoundingSphere.|
|static&nbsp;[`void&nbsp;CreateFromSphere(ref&nbsp;BoundingSphere&nbsp;sphere,&nbsp;ref&nbsp;BoundingBoxI&nbsp;result)`](VRageMath.CreateFromSphere)|Creates the smallest BoundingBoxI that will contain the specified BoundingSphere.|
|static&nbsp;[`BoundingBoxI&nbsp;CreateFromPoints(IEnumerable<Vector3I>&nbsp;points)`](VRageMath.CreateFromPoints)|Creates the smallest BoundingBoxI that will contain a group of points.|
|[`void&nbsp;IntersectWith(ref&nbsp;BoundingBoxI&nbsp;box)`](VRageMath.IntersectWith)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`BoundingBoxI&nbsp;Intersect(BoundingBoxI&nbsp;box)`](VRageMath.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`bool&nbsp;Intersects(BoundingBoxI&nbsp;box)`](VRageMath.Intersects)|Checks whether the current BoundingBoxI intersects another BoundingBoxI.|
|[`bool&nbsp;Intersects(ref&nbsp;BoundingBoxI&nbsp;box)`](VRageMath.Intersects)||
|[`void&nbsp;Intersects(ref&nbsp;BoundingBoxI&nbsp;box,&nbsp;ref&nbsp;bool&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingBoxI intersects another BoundingBoxI.|
|[`bool&nbsp;IntersectsTriangle(Vector3I&nbsp;v0,&nbsp;Vector3I&nbsp;v1,&nbsp;Vector3I&nbsp;v2)`](VRageMath.IntersectsTriangle)||
|[`bool&nbsp;IntersectsTriangle(ref&nbsp;Vector3I&nbsp;v0,&nbsp;ref&nbsp;Vector3I&nbsp;v1,&nbsp;ref&nbsp;Vector3I&nbsp;v2)`](VRageMath.IntersectsTriangle)||
|[`PlaneIntersectionType&nbsp;Intersects(Plane&nbsp;plane)`](VRageMath.Intersects)|Checks whether the current BoundingBoxI intersects a Plane.|
|[`void&nbsp;Intersects(ref&nbsp;Plane&nbsp;plane,&nbsp;ref&nbsp;PlaneIntersectionType&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingBoxI intersects a Plane.|
|[`bool&nbsp;Intersects(Line&nbsp;line,&nbsp;ref&nbsp;float&nbsp;distance)`](VRageMath.Intersects)||
|[`Nullable<float>&nbsp;Intersects(Ray&nbsp;ray)`](VRageMath.Intersects)|Checks whether the current BoundingBoxI intersects a Ray.|
|[`void&nbsp;Intersects(ref&nbsp;Ray&nbsp;ray,&nbsp;ref&nbsp;Nullable<float>&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingBoxI intersects a Ray.|
|[`float&nbsp;Distance(Vector3I&nbsp;point)`](VRageMath.Distance)|Checks whether the current BoundingBoxI intersects a BoundingSphere.|
|[`ContainmentType&nbsp;Contains(BoundingBoxI&nbsp;box)`](VRageMath.Contains)|Tests whether the BoundingBoxI contains another BoundingBoxI.|
|[`void&nbsp;Contains(ref&nbsp;BoundingBoxI&nbsp;box,&nbsp;ref&nbsp;ContainmentType&nbsp;result)`](VRageMath.Contains)|Tests whether the BoundingBoxI contains a BoundingBoxI.|
|[`ContainmentType&nbsp;Contains(Vector3I&nbsp;point)`](VRageMath.Contains)|Tests whether the BoundingBoxI contains a point.|
|[`ContainmentType&nbsp;Contains(Vector3&nbsp;point)`](VRageMath.Contains)||
|[`void&nbsp;Contains(ref&nbsp;Vector3I&nbsp;point,&nbsp;ref&nbsp;ContainmentType&nbsp;result)`](VRageMath.Contains)|Tests whether the BoundingBoxI contains a point.|
|[`BoundingBoxI&nbsp;Translate(Vector3I&nbsp;vctTranlsation)`](VRageMath.Translate)|Translate|
|[`BoundingBoxI&nbsp;Include(ref&nbsp;Vector3I&nbsp;point)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`BoundingBoxI&nbsp;GetIncluded(Vector3I&nbsp;point)`](VRageMath.GetIncluded)||
|[`BoundingBoxI&nbsp;Include(Vector3I&nbsp;point)`](VRageMath.Include)||
|[`BoundingBoxI&nbsp;Include(Vector3I&nbsp;p0,&nbsp;Vector3I&nbsp;p1,&nbsp;Vector3I&nbsp;p2)`](VRageMath.Include)||
|[`BoundingBoxI&nbsp;Include(ref&nbsp;Vector3I&nbsp;p0,&nbsp;ref&nbsp;Vector3I&nbsp;p1,&nbsp;ref&nbsp;Vector3I&nbsp;p2)`](VRageMath.Include)||
|[`BoundingBoxI&nbsp;Include(ref&nbsp;BoundingBoxI&nbsp;box)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`BoundingBoxI&nbsp;Include(BoundingBoxI&nbsp;box)`](VRageMath.Include)||
|static&nbsp;[`BoundingBoxI&nbsp;CreateInvalid()`](VRageMath.CreateInvalid)||
|[`float&nbsp;SurfaceArea()`](VRageMath.SurfaceArea)||
|[`float&nbsp;Volume()`](VRageMath.Volume)||
|[`void&nbsp;Inflate(int&nbsp;size)`](VRageMath.Inflate)||
|[`void&nbsp;InflateToMinimum(Vector3I&nbsp;minimumSize)`](VRageMath.InflateToMinimum)||
|static&nbsp;[`IEnumerable<Vector3I>&nbsp;IterateDifference(BoundingBoxI&nbsp;left,&nbsp;BoundingBoxI&nbsp;right)`](VRageMath.IterateDifference)|Iterate every cell contained in {left} - {right}, where we interpret {box} as the set of all distinct Vector3I points inside a 'box'. Containment is taken in a typical inclusive start, exclusive end fashion.|
|static&nbsp;[`IEnumerable<Vector3I>&nbsp;EnumeratePoints(BoundingBoxI&nbsp;rangeInclusive)`](VRageMath.EnumeratePoints)|Enumerate all values in a integer interval (a cuboid). This method is an allocating version of the Vector3I_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.|
