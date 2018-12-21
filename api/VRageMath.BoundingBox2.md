← [Index](index)
# BoundingBox2 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`Vector2&nbsp;Min`](VRageMath.Min)|The minimum point the BoundingBox2 contains.|
|[`Vector2&nbsp;Max`](VRageMath.Max)|The maximum point the BoundingBox2 contains.|
|static&nbsp;[`int&nbsp;CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingBox2.|
### Properties
|Member|Description|
|---|---|
|[`Vector2&nbsp;Center`](VRageMath.Center)|Calculates center|
|[`Vector2&nbsp;HalfExtents`](VRageMath.HalfExtents)||
|[`Vector2&nbsp;Extents`](VRageMath.Extents)||
|[`float&nbsp;Width`](VRageMath.Width)||
|[`float&nbsp;Height`](VRageMath.Height)||
|[`Vector2&nbsp;Size`](VRageMath.Size)|Size|
### Methods
|Member|Description|
|---|---|
|[`Vector2[]&nbsp;GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingBox2.|
|[`void&nbsp;GetCorners(Vector2[]&nbsp;corners)`](VRageMath.GetCorners)|Gets the array of points that make up the corners of the BoundingBox2.|
|[`void&nbsp;GetCornersUnsafe(*Vector2&nbsp;corners)`](VRageMath.GetCornersUnsafe)||
|[`bool&nbsp;Equals(BoundingBox2&nbsp;other)`](VRageMath.Equals)|Determines whether two instances of BoundingBox2 are equal.|
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Determines whether two instances of BoundingBox2 are equal.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string&nbsp;ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingBox2.|
|static&nbsp;[`BoundingBox2&nbsp;CreateMerged(BoundingBox2&nbsp;original,&nbsp;BoundingBox2&nbsp;additional)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox2 that contains the two specified BoundingBox2 instances.|
|static&nbsp;[`void&nbsp;CreateMerged(ref&nbsp;BoundingBox2&nbsp;original,&nbsp;ref&nbsp;BoundingBox2&nbsp;additional,&nbsp;ref&nbsp;BoundingBox2&nbsp;result)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox2 that contains the two specified BoundingBox2 instances.|
|static&nbsp;[`BoundingBox2&nbsp;CreateFromPoints(IEnumerable<Vector2>&nbsp;points)`](VRageMath.CreateFromPoints)|Creates the smallest BoundingBox2 that will contain a group of points.|
|static&nbsp;[`BoundingBox2&nbsp;CreateFromHalfExtent(Vector2&nbsp;center,&nbsp;float&nbsp;halfExtent)`](VRageMath.CreateFromHalfExtent)||
|static&nbsp;[`BoundingBox2&nbsp;CreateFromHalfExtent(Vector2&nbsp;center,&nbsp;Vector2&nbsp;halfExtent)`](VRageMath.CreateFromHalfExtent)||
|[`BoundingBox2&nbsp;Intersect(BoundingBox2&nbsp;box)`](VRageMath.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`bool&nbsp;Intersects(BoundingBox2&nbsp;box)`](VRageMath.Intersects)|Checks whether the current BoundingBox2 intersects another BoundingBox2.|
|[`bool&nbsp;Intersects(ref&nbsp;BoundingBox2&nbsp;box)`](VRageMath.Intersects)||
|[`void&nbsp;Intersects(ref&nbsp;BoundingBox2&nbsp;box,&nbsp;ref&nbsp;bool&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingBox2 intersects another BoundingBox2.|
|[`float&nbsp;Distance(Vector2&nbsp;point)`](VRageMath.Distance)||
|[`ContainmentType&nbsp;Contains(BoundingBox2&nbsp;box)`](VRageMath.Contains)|Tests whether the BoundingBox2 contains another BoundingBox2.|
|[`void&nbsp;Contains(ref&nbsp;BoundingBox2&nbsp;box,&nbsp;ref&nbsp;ContainmentType&nbsp;result)`](VRageMath.Contains)|Tests whether the BoundingBox2 contains a BoundingBox2.|
|[`ContainmentType&nbsp;Contains(Vector2&nbsp;point)`](VRageMath.Contains)|Tests whether the BoundingBox2 contains a point.|
|[`void&nbsp;Contains(ref&nbsp;Vector2&nbsp;point,&nbsp;ref&nbsp;ContainmentType&nbsp;result)`](VRageMath.Contains)|Tests whether the BoundingBox2 contains a point.|
|[`BoundingBox2&nbsp;Translate(Vector2&nbsp;vctTranlsation)`](VRageMath.Translate)|Translate|
|[`BoundingBox2&nbsp;Include(ref&nbsp;Vector2&nbsp;point)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`BoundingBox2&nbsp;GetIncluded(Vector2&nbsp;point)`](VRageMath.GetIncluded)||
|[`BoundingBox2&nbsp;Include(Vector2&nbsp;point)`](VRageMath.Include)||
|[`BoundingBox2&nbsp;Include(Vector2&nbsp;p0,&nbsp;Vector2&nbsp;p1,&nbsp;Vector2&nbsp;p2)`](VRageMath.Include)||
|[`BoundingBox2&nbsp;Include(ref&nbsp;Vector2&nbsp;p0,&nbsp;ref&nbsp;Vector2&nbsp;p1,&nbsp;ref&nbsp;Vector2&nbsp;p2)`](VRageMath.Include)||
|[`BoundingBox2&nbsp;Include(ref&nbsp;BoundingBox2&nbsp;box)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`BoundingBox2&nbsp;Include(BoundingBox2&nbsp;box)`](VRageMath.Include)||
|static&nbsp;[`BoundingBox2&nbsp;CreateInvalid()`](VRageMath.CreateInvalid)||
|[`float&nbsp;Perimeter()`](VRageMath.Perimeter)||
|[`float&nbsp;Area()`](VRageMath.Area)||
|[`void&nbsp;Inflate(float&nbsp;size)`](VRageMath.Inflate)||
|[`void&nbsp;InflateToMinimum(Vector2&nbsp;minimumSize)`](VRageMath.InflateToMinimum)||
|[`void&nbsp;Scale(Vector2&nbsp;scale)`](VRageMath.Scale)||
