← [Index](index)
# BoundingBox2I Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`Vector2I&nbsp;Min`](VRageMath.Min)|The minimum point the BoundingBox2I contains.|
|[`Vector2I&nbsp;Max`](VRageMath.Max)|The maximum point the BoundingBox2I contains.|
|static&nbsp;[`int&nbsp;CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingBox2I.|
### Properties
|Member|Description|
|---|---|
|[`Vector2I&nbsp;Center`](VRageMath.Center)|Calculates center|
|[`Vector2I&nbsp;HalfExtents`](VRageMath.HalfExtents)||
|[`Vector2I&nbsp;Extents`](VRageMath.Extents)||
|[`float&nbsp;Width`](VRageMath.Width)||
|[`float&nbsp;Height`](VRageMath.Height)||
|[`Vector2I&nbsp;Size`](VRageMath.Size)|Size|
### Methods
|Member|Description|
|---|---|
|[`Vector2I[]&nbsp;GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingBox2I.|
|[`void&nbsp;GetCorners(Vector2I[]&nbsp;corners)`](VRageMath.GetCorners)|Gets the array of points that make up the corners of the BoundingBox2I.|
|[`void&nbsp;GetCornersUnsafe(*Vector2I&nbsp;corners)`](VRageMath.GetCornersUnsafe)||
|[`bool&nbsp;Equals(BoundingBox2I&nbsp;other)`](VRageMath.Equals)|Determines whether two instances of BoundingBox2I are equal.|
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Determines whether two instances of BoundingBox2I are equal.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string&nbsp;ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingBox2I.|
|static&nbsp;[`BoundingBox2I&nbsp;CreateMerged(BoundingBox2I&nbsp;original,&nbsp;BoundingBox2I&nbsp;additional)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox2I that contains the two specified BoundingBox2I instances.|
|static&nbsp;[`void&nbsp;CreateMerged(ref&nbsp;BoundingBox2I&nbsp;original,&nbsp;ref&nbsp;BoundingBox2I&nbsp;additional,&nbsp;ref&nbsp;BoundingBox2I&nbsp;result)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox2I that contains the two specified BoundingBox2I instances.|
|static&nbsp;[`BoundingBox2I&nbsp;CreateFromPoints(IEnumerable<Vector2I>&nbsp;points)`](VRageMath.CreateFromPoints)|Creates the smallest BoundingBox2I that will contain a group of points.|
|static&nbsp;[`BoundingBox2I&nbsp;CreateFromHalfExtent(Vector2I&nbsp;center,&nbsp;int&nbsp;halfExtent)`](VRageMath.CreateFromHalfExtent)||
|static&nbsp;[`BoundingBox2I&nbsp;CreateFromHalfExtent(Vector2I&nbsp;center,&nbsp;Vector2I&nbsp;halfExtent)`](VRageMath.CreateFromHalfExtent)||
|[`BoundingBox2I&nbsp;Intersect(BoundingBox2I&nbsp;box)`](VRageMath.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`bool&nbsp;Intersects(BoundingBox2I&nbsp;box)`](VRageMath.Intersects)|Checks whether the current BoundingBox2I intersects another BoundingBox2I.|
|[`bool&nbsp;Intersects(ref&nbsp;BoundingBox2I&nbsp;box)`](VRageMath.Intersects)||
|[`void&nbsp;Intersects(ref&nbsp;BoundingBox2I&nbsp;box,&nbsp;ref&nbsp;bool&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingBox2I intersects another BoundingBox2I.|
|[`ContainmentType&nbsp;Contains(BoundingBox2I&nbsp;box)`](VRageMath.Contains)|Tests whether the BoundingBox2I contains another BoundingBox2I.|
|[`void&nbsp;Contains(ref&nbsp;BoundingBox2I&nbsp;box,&nbsp;ref&nbsp;ContainmentType&nbsp;result)`](VRageMath.Contains)|Tests whether the BoundingBox2I contains a BoundingBox2I.|
|[`ContainmentType&nbsp;Contains(Vector2I&nbsp;point)`](VRageMath.Contains)|Tests whether the BoundingBox2I contains a point.|
|[`void&nbsp;Contains(ref&nbsp;Vector2I&nbsp;point,&nbsp;ref&nbsp;ContainmentType&nbsp;result)`](VRageMath.Contains)|Tests whether the BoundingBox2I contains a point.|
|[`BoundingBox2I&nbsp;Translate(Vector2I&nbsp;vctTranlsation)`](VRageMath.Translate)|Translate|
|[`BoundingBox2I&nbsp;Include(ref&nbsp;Vector2I&nbsp;point)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`BoundingBox2I&nbsp;GetIncluded(Vector2I&nbsp;point)`](VRageMath.GetIncluded)||
|[`BoundingBox2I&nbsp;Include(Vector2I&nbsp;point)`](VRageMath.Include)||
|[`BoundingBox2I&nbsp;Include(Vector2I&nbsp;p0,&nbsp;Vector2I&nbsp;p1,&nbsp;Vector2I&nbsp;p2)`](VRageMath.Include)||
|[`BoundingBox2I&nbsp;Include(ref&nbsp;Vector2I&nbsp;p0,&nbsp;ref&nbsp;Vector2I&nbsp;p1,&nbsp;ref&nbsp;Vector2I&nbsp;p2)`](VRageMath.Include)||
|[`BoundingBox2I&nbsp;Include(ref&nbsp;BoundingBox2I&nbsp;box)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`BoundingBox2I&nbsp;Include(BoundingBox2I&nbsp;box)`](VRageMath.Include)||
|static&nbsp;[`BoundingBox2I&nbsp;CreateInvalid()`](VRageMath.CreateInvalid)||
|[`float&nbsp;Perimeter()`](VRageMath.Perimeter)||
|[`float&nbsp;Area()`](VRageMath.Area)||
|[`void&nbsp;Inflate(int&nbsp;size)`](VRageMath.Inflate)||
|[`void&nbsp;InflateToMinimum(Vector2I&nbsp;minimumSize)`](VRageMath.InflateToMinimum)||
|[`void&nbsp;Scale(Vector2I&nbsp;scale)`](VRageMath.Scale)||
