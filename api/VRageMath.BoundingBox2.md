← [Index](index)
# BoundingBox2 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`Vector2 Min`](VRageMath.Min)|The minimum point the BoundingBox2 contains.|
|[`Vector2 Max`](VRageMath.Max)|The maximum point the BoundingBox2 contains.|
|static [`int CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingBox2.|
### Properties
|Member|Description|
|---|---|
|[`Vector2 Center`](VRageMath.Center)|Calculates center|
|[`Vector2 HalfExtents`](VRageMath.HalfExtents)||
|[`Vector2 Extents`](VRageMath.Extents)||
|[`float Width`](VRageMath.Width)||
|[`float Height`](VRageMath.Height)||
|[`Vector2 Size`](VRageMath.Size)|Size|
### Methods
|Member|Description|
|---|---|
|[`Vector2[] GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingBox2.|
|[`void GetCorners(Vector2[] corners)`](VRageMath.GetCorners)|Gets the array of points that make up the corners of the BoundingBox2.|
|[`void GetCornersUnsafe(*Vector2 corners)`](VRageMath.GetCornersUnsafe)||
|[`bool Equals(BoundingBox2 other)`](VRageMath.Equals)|Determines whether two instances of BoundingBox2 are equal.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Determines whether two instances of BoundingBox2 are equal.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingBox2.|
|static [`BoundingBox2 CreateMerged(BoundingBox2 original, BoundingBox2 additional)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox2 that contains the two specified BoundingBox2 instances.|
|static [`void CreateMerged(ref BoundingBox2 original, ref BoundingBox2 additional, ref BoundingBox2 result)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox2 that contains the two specified BoundingBox2 instances.|
|static [`BoundingBox2 CreateFromPoints(IEnumerable<Vector2> points)`](VRageMath.CreateFromPoints)|Creates the smallest BoundingBox2 that will contain a group of points.|
|static [`BoundingBox2 CreateFromHalfExtent(Vector2 center, float halfExtent)`](VRageMath.CreateFromHalfExtent)||
|static [`BoundingBox2 CreateFromHalfExtent(Vector2 center, Vector2 halfExtent)`](VRageMath.CreateFromHalfExtent)||
|[`BoundingBox2 Intersect(BoundingBox2 box)`](VRageMath.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`bool Intersects(BoundingBox2 box)`](VRageMath.Intersects)|Checks whether the current BoundingBox2 intersects another BoundingBox2.|
|[`bool Intersects(ref BoundingBox2 box)`](VRageMath.Intersects)||
|[`void Intersects(ref BoundingBox2 box, ref bool result)`](VRageMath.Intersects)|Checks whether the current BoundingBox2 intersects another BoundingBox2.|
|[`float Distance(Vector2 point)`](VRageMath.Distance)||
|[`ContainmentType Contains(BoundingBox2 box)`](VRageMath.Contains)|Tests whether the BoundingBox2 contains another BoundingBox2.|
|[`void Contains(ref BoundingBox2 box, ref ContainmentType result)`](VRageMath.Contains)|Tests whether the BoundingBox2 contains a BoundingBox2.|
|[`ContainmentType Contains(Vector2 point)`](VRageMath.Contains)|Tests whether the BoundingBox2 contains a point.|
|[`void Contains(ref Vector2 point, ref ContainmentType result)`](VRageMath.Contains)|Tests whether the BoundingBox2 contains a point.|
|[`BoundingBox2 Translate(Vector2 vctTranlsation)`](VRageMath.Translate)|Translate|
|[`BoundingBox2 Include(ref Vector2 point)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`BoundingBox2 GetIncluded(Vector2 point)`](VRageMath.GetIncluded)||
|[`BoundingBox2 Include(Vector2 point)`](VRageMath.Include)||
|[`BoundingBox2 Include(Vector2 p0, Vector2 p1, Vector2 p2)`](VRageMath.Include)||
|[`BoundingBox2 Include(ref Vector2 p0, ref Vector2 p1, ref Vector2 p2)`](VRageMath.Include)||
|[`BoundingBox2 Include(ref BoundingBox2 box)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`BoundingBox2 Include(BoundingBox2 box)`](VRageMath.Include)||
|static [`BoundingBox2 CreateInvalid()`](VRageMath.CreateInvalid)||
|[`float Perimeter()`](VRageMath.Perimeter)||
|[`float Area()`](VRageMath.Area)||
|[`void Inflate(float size)`](VRageMath.Inflate)||
|[`void InflateToMinimum(Vector2 minimumSize)`](VRageMath.InflateToMinimum)||
|[`void Scale(Vector2 scale)`](VRageMath.Scale)||
