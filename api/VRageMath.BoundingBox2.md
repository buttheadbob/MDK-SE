← [Index](index)
# BoundingBox2 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`VRageMath.Vector2 Min`](VRageMath.Min)|The minimum point the BoundingBox2 contains.|
|[`VRageMath.Vector2 Max`](VRageMath.Max)|The maximum point the BoundingBox2 contains.|
|static [`int CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingBox2.|
### Properties
|Member|Description|
|---|---|
|[`VRageMath.Vector2 Center`](VRageMath.Center)|Calculates center|
|[`VRageMath.Vector2 HalfExtents`](VRageMath.HalfExtents)||
|[`VRageMath.Vector2 Extents`](VRageMath.Extents)||
|[`float Width`](VRageMath.Width)||
|[`float Height`](VRageMath.Height)||
|[`VRageMath.Vector2 Size`](VRageMath.Size)|Size|
### Methods
|Member|Description|
|---|---|
|[`VRageMath.Vector2[] GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingBox2.|
|[`void GetCorners(VRageMath.Vector2[])`](VRageMath.GetCorners)|Gets the array of points that make up the corners of the BoundingBox2.|
|[`void GetCornersUnsafe(*VRageMath.Vector2)`](VRageMath.GetCornersUnsafe)||
|[`bool Equals(VRageMath.BoundingBox2)`](VRageMath.Equals)|Determines whether two instances of BoundingBox2 are equal.|
|[`bool Equals(System.Object)`](VRageMath.Equals)|Determines whether two instances of BoundingBox2 are equal.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingBox2.|
|static [`VRageMath.BoundingBox2 CreateMerged(VRageMath.BoundingBox2, VRageMath.BoundingBox2)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox2 that contains the two specified BoundingBox2 instances.|
|static [`void CreateMerged(ref VRageMath.BoundingBox2, ref VRageMath.BoundingBox2, ref VRageMath.BoundingBox2)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox2 that contains the two specified BoundingBox2 instances.|
|static [`VRageMath.BoundingBox2 CreateFromPoints(IEnumerable<VRageMath.Vector2>)`](VRageMath.CreateFromPoints)|Creates the smallest BoundingBox2 that will contain a group of points.|
|static [`VRageMath.BoundingBox2 CreateFromHalfExtent(VRageMath.Vector2, float)`](VRageMath.CreateFromHalfExtent)||
|static [`VRageMath.BoundingBox2 CreateFromHalfExtent(VRageMath.Vector2, VRageMath.Vector2)`](VRageMath.CreateFromHalfExtent)||
|[`VRageMath.BoundingBox2 Intersect(VRageMath.BoundingBox2)`](VRageMath.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`bool Intersects(VRageMath.BoundingBox2)`](VRageMath.Intersects)|Checks whether the current BoundingBox2 intersects another BoundingBox2.|
|[`bool Intersects(ref VRageMath.BoundingBox2)`](VRageMath.Intersects)||
|[`void Intersects(ref VRageMath.BoundingBox2, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingBox2 intersects another BoundingBox2.|
|[`float Distance(VRageMath.Vector2)`](VRageMath.Distance)||
|[`VRageMath.ContainmentType Contains(VRageMath.BoundingBox2)`](VRageMath.Contains)|Tests whether the BoundingBox2 contains another BoundingBox2.|
|[`void Contains(ref VRageMath.BoundingBox2, ref VRageMath.ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBox2 contains a BoundingBox2.|
|[`VRageMath.ContainmentType Contains(VRageMath.Vector2)`](VRageMath.Contains)|Tests whether the BoundingBox2 contains a point.|
|[`void Contains(ref VRageMath.Vector2, ref VRageMath.ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBox2 contains a point.|
|[`VRageMath.BoundingBox2 Translate(VRageMath.Vector2)`](VRageMath.Translate)|Translate|
|[`VRageMath.BoundingBox2 Include(ref VRageMath.Vector2)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`VRageMath.BoundingBox2 GetIncluded(VRageMath.Vector2)`](VRageMath.GetIncluded)||
|[`VRageMath.BoundingBox2 Include(VRageMath.Vector2)`](VRageMath.Include)||
|[`VRageMath.BoundingBox2 Include(VRageMath.Vector2, VRageMath.Vector2, VRageMath.Vector2)`](VRageMath.Include)||
|[`VRageMath.BoundingBox2 Include(ref VRageMath.Vector2, ref VRageMath.Vector2, ref VRageMath.Vector2)`](VRageMath.Include)||
|[`VRageMath.BoundingBox2 Include(ref VRageMath.BoundingBox2)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`VRageMath.BoundingBox2 Include(VRageMath.BoundingBox2)`](VRageMath.Include)||
|static [`VRageMath.BoundingBox2 CreateInvalid()`](VRageMath.CreateInvalid)||
|[`float Perimeter()`](VRageMath.Perimeter)||
|[`float Area()`](VRageMath.Area)||
|[`void Inflate(float)`](VRageMath.Inflate)||
|[`void InflateToMinimum(VRageMath.Vector2)`](VRageMath.InflateToMinimum)||
|[`void Scale(VRageMath.Vector2)`](VRageMath.Scale)||
