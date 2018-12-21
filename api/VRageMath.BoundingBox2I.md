← [Index](index)
# BoundingBox2I Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`Vector2I Min`](VRageMath.Min)|The minimum point the BoundingBox2I contains.|
|[`Vector2I Max`](VRageMath.Max)|The maximum point the BoundingBox2I contains.|
|static [`int CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingBox2I.|
### Properties
|Member|Description|
|---|---|
|[`Vector2I Center`](VRageMath.Center)|Calculates center|
|[`Vector2I HalfExtents`](VRageMath.HalfExtents)||
|[`Vector2I Extents`](VRageMath.Extents)||
|[`float Width`](VRageMath.Width)||
|[`float Height`](VRageMath.Height)||
|[`Vector2I Size`](VRageMath.Size)|Size|
### Methods
|Member|Description|
|---|---|
|[`Vector2I[] GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingBox2I.|
|[`void GetCorners(Vector2I[] corners)`](VRageMath.GetCorners)|Gets the array of points that make up the corners of the BoundingBox2I.|
|[`void GetCornersUnsafe(*Vector2I corners)`](VRageMath.GetCornersUnsafe)||
|[`bool Equals(BoundingBox2I other)`](VRageMath.Equals)|Determines whether two instances of BoundingBox2I are equal.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Determines whether two instances of BoundingBox2I are equal.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingBox2I.|
|static [`BoundingBox2I CreateMerged(BoundingBox2I original, BoundingBox2I additional)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox2I that contains the two specified BoundingBox2I instances.|
|static [`void CreateMerged(ref BoundingBox2I original, ref BoundingBox2I additional, ref BoundingBox2I result)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox2I that contains the two specified BoundingBox2I instances.|
|static [`BoundingBox2I CreateFromPoints(IEnumerable<Vector2I> points)`](VRageMath.CreateFromPoints)|Creates the smallest BoundingBox2I that will contain a group of points.|
|static [`BoundingBox2I CreateFromHalfExtent(Vector2I center, int halfExtent)`](VRageMath.CreateFromHalfExtent)||
|static [`BoundingBox2I CreateFromHalfExtent(Vector2I center, Vector2I halfExtent)`](VRageMath.CreateFromHalfExtent)||
|[`BoundingBox2I Intersect(BoundingBox2I box)`](VRageMath.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`bool Intersects(BoundingBox2I box)`](VRageMath.Intersects)|Checks whether the current BoundingBox2I intersects another BoundingBox2I.|
|[`bool Intersects(ref BoundingBox2I box)`](VRageMath.Intersects)||
|[`void Intersects(ref BoundingBox2I box, ref bool result)`](VRageMath.Intersects)|Checks whether the current BoundingBox2I intersects another BoundingBox2I.|
|[`ContainmentType Contains(BoundingBox2I box)`](VRageMath.Contains)|Tests whether the BoundingBox2I contains another BoundingBox2I.|
|[`void Contains(ref BoundingBox2I box, ref ContainmentType result)`](VRageMath.Contains)|Tests whether the BoundingBox2I contains a BoundingBox2I.|
|[`ContainmentType Contains(Vector2I point)`](VRageMath.Contains)|Tests whether the BoundingBox2I contains a point.|
|[`void Contains(ref Vector2I point, ref ContainmentType result)`](VRageMath.Contains)|Tests whether the BoundingBox2I contains a point.|
|[`BoundingBox2I Translate(Vector2I vctTranlsation)`](VRageMath.Translate)|Translate|
|[`BoundingBox2I Include(ref Vector2I point)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`BoundingBox2I GetIncluded(Vector2I point)`](VRageMath.GetIncluded)||
|[`BoundingBox2I Include(Vector2I point)`](VRageMath.Include)||
|[`BoundingBox2I Include(Vector2I p0, Vector2I p1, Vector2I p2)`](VRageMath.Include)||
|[`BoundingBox2I Include(ref Vector2I p0, ref Vector2I p1, ref Vector2I p2)`](VRageMath.Include)||
|[`BoundingBox2I Include(ref BoundingBox2I box)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`BoundingBox2I Include(BoundingBox2I box)`](VRageMath.Include)||
|static [`BoundingBox2I CreateInvalid()`](VRageMath.CreateInvalid)||
|[`float Perimeter()`](VRageMath.Perimeter)||
|[`float Area()`](VRageMath.Area)||
|[`void Inflate(int size)`](VRageMath.Inflate)||
|[`void InflateToMinimum(Vector2I minimumSize)`](VRageMath.InflateToMinimum)||
|[`void Scale(Vector2I scale)`](VRageMath.Scale)||
