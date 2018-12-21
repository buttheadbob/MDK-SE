← [Index](index)
# BoundingBox2I Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`VRageMath.Vector2I Min`](VRageMath.Min)|The minimum point the BoundingBox2I contains.|
|[`VRageMath.Vector2I Max`](VRageMath.Max)|The maximum point the BoundingBox2I contains.|
|static [`int CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingBox2I.|
### Properties
|Member|Description|
|---|---|
|[`VRageMath.Vector2I Center`](VRageMath.Center)|Calculates center|
|[`VRageMath.Vector2I HalfExtents`](VRageMath.HalfExtents)||
|[`VRageMath.Vector2I Extents`](VRageMath.Extents)||
|[`float Width`](VRageMath.Width)||
|[`float Height`](VRageMath.Height)||
|[`VRageMath.Vector2I Size`](VRageMath.Size)|Size|
### Methods
|Member|Description|
|---|---|
|[`VRageMath.Vector2I[] GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingBox2I.|
|[`void GetCorners(VRageMath.Vector2I[])`](VRageMath.GetCorners)|Gets the array of points that make up the corners of the BoundingBox2I.|
|[`void GetCornersUnsafe(*VRageMath.Vector2I)`](VRageMath.GetCornersUnsafe)||
|[`bool Equals(VRageMath.BoundingBox2I)`](VRageMath.Equals)|Determines whether two instances of BoundingBox2I are equal.|
|[`bool Equals(System.Object)`](VRageMath.Equals)|Determines whether two instances of BoundingBox2I are equal.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingBox2I.|
|static [`VRageMath.BoundingBox2I CreateMerged(VRageMath.BoundingBox2I, VRageMath.BoundingBox2I)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox2I that contains the two specified BoundingBox2I instances.|
|static [`void CreateMerged(ref VRageMath.BoundingBox2I, ref VRageMath.BoundingBox2I, ref VRageMath.BoundingBox2I)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox2I that contains the two specified BoundingBox2I instances.|
|static [`VRageMath.BoundingBox2I CreateFromPoints(IEnumerable<VRageMath.Vector2I>)`](VRageMath.CreateFromPoints)|Creates the smallest BoundingBox2I that will contain a group of points.|
|static [`VRageMath.BoundingBox2I CreateFromHalfExtent(VRageMath.Vector2I, int)`](VRageMath.CreateFromHalfExtent)||
|static [`VRageMath.BoundingBox2I CreateFromHalfExtent(VRageMath.Vector2I, VRageMath.Vector2I)`](VRageMath.CreateFromHalfExtent)||
|[`VRageMath.BoundingBox2I Intersect(VRageMath.BoundingBox2I)`](VRageMath.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`bool Intersects(VRageMath.BoundingBox2I)`](VRageMath.Intersects)|Checks whether the current BoundingBox2I intersects another BoundingBox2I.|
|[`bool Intersects(ref VRageMath.BoundingBox2I)`](VRageMath.Intersects)||
|[`void Intersects(ref VRageMath.BoundingBox2I, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingBox2I intersects another BoundingBox2I.|
|[`VRageMath.ContainmentType Contains(VRageMath.BoundingBox2I)`](VRageMath.Contains)|Tests whether the BoundingBox2I contains another BoundingBox2I.|
|[`void Contains(ref VRageMath.BoundingBox2I, ref VRageMath.ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBox2I contains a BoundingBox2I.|
|[`VRageMath.ContainmentType Contains(VRageMath.Vector2I)`](VRageMath.Contains)|Tests whether the BoundingBox2I contains a point.|
|[`void Contains(ref VRageMath.Vector2I, ref VRageMath.ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBox2I contains a point.|
|[`VRageMath.BoundingBox2I Translate(VRageMath.Vector2I)`](VRageMath.Translate)|Translate|
|[`VRageMath.BoundingBox2I Include(ref VRageMath.Vector2I)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`VRageMath.BoundingBox2I GetIncluded(VRageMath.Vector2I)`](VRageMath.GetIncluded)||
|[`VRageMath.BoundingBox2I Include(VRageMath.Vector2I)`](VRageMath.Include)||
|[`VRageMath.BoundingBox2I Include(VRageMath.Vector2I, VRageMath.Vector2I, VRageMath.Vector2I)`](VRageMath.Include)||
|[`VRageMath.BoundingBox2I Include(ref VRageMath.Vector2I, ref VRageMath.Vector2I, ref VRageMath.Vector2I)`](VRageMath.Include)||
|[`VRageMath.BoundingBox2I Include(ref VRageMath.BoundingBox2I)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`VRageMath.BoundingBox2I Include(VRageMath.BoundingBox2I)`](VRageMath.Include)||
|static [`VRageMath.BoundingBox2I CreateInvalid()`](VRageMath.CreateInvalid)||
|[`float Perimeter()`](VRageMath.Perimeter)||
|[`float Area()`](VRageMath.Area)||
|[`void Inflate(int)`](VRageMath.Inflate)||
|[`void InflateToMinimum(VRageMath.Vector2I)`](VRageMath.InflateToMinimum)||
|[`void Scale(VRageMath.Vector2I)`](VRageMath.Scale)||
