← [Index](index)
# BoundingBox2D Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`Vector2D&nbsp;Min`](VRageMath.Min)|The minimum point the BoundingBox2D contains.|
|[`Vector2D&nbsp;Max`](VRageMath.Max)|The maximum point the BoundingBox2D contains.|
|static&nbsp;[`int&nbsp;CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingBox2D.|
### Properties
|Member|Description|
|---|---|
|[`Vector2D&nbsp;Center`](VRageMath.Center)|Calculates center|
|[`Vector2D&nbsp;HalfExtents`](VRageMath.HalfExtents)||
|[`Vector2D&nbsp;Extents`](VRageMath.Extents)||
|[`double&nbsp;Width`](VRageMath.Width)||
|[`double&nbsp;Height`](VRageMath.Height)||
|[`Vector2D&nbsp;Size`](VRageMath.Size)|Size|
### Methods
|Member|Description|
|---|---|
|[`Vector2D[]&nbsp;GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingBox2D.|
|[`void&nbsp;GetCorners(Vector2D[]&nbsp;corners)`](VRageMath.GetCorners)|Gets the array of points that make up the corners of the BoundingBox2D.|
|[`void&nbsp;GetCornersUnsafe(*Vector2D&nbsp;corners)`](VRageMath.GetCornersUnsafe)||
|[`bool&nbsp;Equals(BoundingBox2D&nbsp;other)`](VRageMath.Equals)|Determines whether two instances of BoundingBox2D are equal.|
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Determines whether two instances of BoundingBox2D are equal.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string&nbsp;ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingBox2D.|
|static&nbsp;[`BoundingBox2D&nbsp;CreateMerged(BoundingBox2D&nbsp;original,&nbsp;BoundingBox2D&nbsp;additional)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox2D that contains the two specified BoundingBox2D instances.|
|static&nbsp;[`void&nbsp;CreateMerged(ref&nbsp;BoundingBox2D&nbsp;original,&nbsp;ref&nbsp;BoundingBox2D&nbsp;additional,&nbsp;ref&nbsp;BoundingBox2D&nbsp;result)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox2D that contains the two specified BoundingBox2D instances.|
|static&nbsp;[`BoundingBox2D&nbsp;CreateFromPoints(IEnumerable<Vector2D>&nbsp;points)`](VRageMath.CreateFromPoints)|Creates the smallest BoundingBox2D that will contain a group of points.|
|static&nbsp;[`BoundingBox2D&nbsp;CreateFromHalfExtent(Vector2D&nbsp;center,&nbsp;double&nbsp;halfExtent)`](VRageMath.CreateFromHalfExtent)||
|static&nbsp;[`BoundingBox2D&nbsp;CreateFromHalfExtent(Vector2D&nbsp;center,&nbsp;Vector2D&nbsp;halfExtent)`](VRageMath.CreateFromHalfExtent)||
|[`BoundingBox2D&nbsp;Intersect(BoundingBox2D&nbsp;box)`](VRageMath.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`bool&nbsp;Intersects(BoundingBox2D&nbsp;box)`](VRageMath.Intersects)|Checks whether the current BoundingBox2D intersects another BoundingBox2D.|
|[`bool&nbsp;Intersects(ref&nbsp;BoundingBox2D&nbsp;box)`](VRageMath.Intersects)||
|[`void&nbsp;Intersects(ref&nbsp;BoundingBox2D&nbsp;box,&nbsp;ref&nbsp;bool&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingBox2D intersects another BoundingBox2D.|
|[`double&nbsp;Distance(Vector2D&nbsp;point)`](VRageMath.Distance)||
|[`ContainmentType&nbsp;Contains(BoundingBox2D&nbsp;box)`](VRageMath.Contains)|Tests whether the BoundingBox2D contains another BoundingBox2D.|
|[`void&nbsp;Contains(ref&nbsp;BoundingBox2D&nbsp;box,&nbsp;ref&nbsp;ContainmentType&nbsp;result)`](VRageMath.Contains)|Tests whether the BoundingBox2D contains a BoundingBox2D.|
|[`ContainmentType&nbsp;Contains(Vector2D&nbsp;point)`](VRageMath.Contains)|Tests whether the BoundingBox2D contains a point.|
|[`void&nbsp;Contains(ref&nbsp;Vector2D&nbsp;point,&nbsp;ref&nbsp;ContainmentType&nbsp;result)`](VRageMath.Contains)|Tests whether the BoundingBox2D contains a point.|
|[`BoundingBox2D&nbsp;Translate(Vector2D&nbsp;vctTranlsation)`](VRageMath.Translate)|Translate|
|[`BoundingBox2D&nbsp;Include(ref&nbsp;Vector2D&nbsp;point)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`BoundingBox2D&nbsp;GetIncluded(Vector2D&nbsp;point)`](VRageMath.GetIncluded)||
|[`BoundingBox2D&nbsp;Include(Vector2D&nbsp;point)`](VRageMath.Include)||
|[`BoundingBox2D&nbsp;Include(Vector2D&nbsp;p0,&nbsp;Vector2D&nbsp;p1,&nbsp;Vector2D&nbsp;p2)`](VRageMath.Include)||
|[`BoundingBox2D&nbsp;Include(ref&nbsp;Vector2D&nbsp;p0,&nbsp;ref&nbsp;Vector2D&nbsp;p1,&nbsp;ref&nbsp;Vector2D&nbsp;p2)`](VRageMath.Include)||
|[`BoundingBox2D&nbsp;Include(ref&nbsp;BoundingBox2D&nbsp;box)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`BoundingBox2D&nbsp;Include(BoundingBox2D&nbsp;box)`](VRageMath.Include)||
|static&nbsp;[`BoundingBox2D&nbsp;CreateInvalid()`](VRageMath.CreateInvalid)||
|[`double&nbsp;Perimeter()`](VRageMath.Perimeter)||
|[`double&nbsp;Area()`](VRageMath.Area)||
|[`void&nbsp;Inflate(double&nbsp;size)`](VRageMath.Inflate)||
|[`void&nbsp;InflateToMinimum(Vector2D&nbsp;minimumSize)`](VRageMath.InflateToMinimum)||
|[`void&nbsp;Scale(Vector2D&nbsp;scale)`](VRageMath.Scale)||
