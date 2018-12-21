← [Index](index)
# BoundingBox2D Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`VRageMath.Vector2D Min`](VRageMath.Min)|The minimum point the BoundingBox2D contains.|
|[`VRageMath.Vector2D Max`](VRageMath.Max)|The maximum point the BoundingBox2D contains.|
|static [`int CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingBox2D.|
### Properties
|Member|Description|
|---|---|
|[`VRageMath.Vector2D Center`](VRageMath.Center)|Calculates center|
|[`VRageMath.Vector2D HalfExtents`](VRageMath.HalfExtents)||
|[`VRageMath.Vector2D Extents`](VRageMath.Extents)||
|[`double Width`](VRageMath.Width)||
|[`double Height`](VRageMath.Height)||
|[`VRageMath.Vector2D Size`](VRageMath.Size)|Size|
### Methods
|Member|Description|
|---|---|
|[`VRageMath.Vector2D[] GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingBox2D.|
|[`void GetCorners(VRageMath.Vector2D[])`](VRageMath.GetCorners)|Gets the array of points that make up the corners of the BoundingBox2D.|
|[`void GetCornersUnsafe(*VRageMath.Vector2D)`](VRageMath.GetCornersUnsafe)||
|[`bool Equals(VRageMath.BoundingBox2D)`](VRageMath.Equals)|Determines whether two instances of BoundingBox2D are equal.|
|[`bool Equals(System.Object)`](VRageMath.Equals)|Determines whether two instances of BoundingBox2D are equal.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingBox2D.|
|static [`VRageMath.BoundingBox2D CreateMerged(VRageMath.BoundingBox2D, VRageMath.BoundingBox2D)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox2D that contains the two specified BoundingBox2D instances.|
|static [`void CreateMerged(ref VRageMath.BoundingBox2D, ref VRageMath.BoundingBox2D, ref VRageMath.BoundingBox2D)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox2D that contains the two specified BoundingBox2D instances.|
|static [`VRageMath.BoundingBox2D CreateFromPoints(IEnumerable<VRageMath.Vector2D>)`](VRageMath.CreateFromPoints)|Creates the smallest BoundingBox2D that will contain a group of points.|
|static [`VRageMath.BoundingBox2D CreateFromHalfExtent(VRageMath.Vector2D, double)`](VRageMath.CreateFromHalfExtent)||
|static [`VRageMath.BoundingBox2D CreateFromHalfExtent(VRageMath.Vector2D, VRageMath.Vector2D)`](VRageMath.CreateFromHalfExtent)||
|[`VRageMath.BoundingBox2D Intersect(VRageMath.BoundingBox2D)`](VRageMath.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`bool Intersects(VRageMath.BoundingBox2D)`](VRageMath.Intersects)|Checks whether the current BoundingBox2D intersects another BoundingBox2D.|
|[`bool Intersects(ref VRageMath.BoundingBox2D)`](VRageMath.Intersects)||
|[`void Intersects(ref VRageMath.BoundingBox2D, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingBox2D intersects another BoundingBox2D.|
|[`double Distance(VRageMath.Vector2D)`](VRageMath.Distance)||
|[`VRageMath.ContainmentType Contains(VRageMath.BoundingBox2D)`](VRageMath.Contains)|Tests whether the BoundingBox2D contains another BoundingBox2D.|
|[`void Contains(ref VRageMath.BoundingBox2D, ref VRageMath.ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBox2D contains a BoundingBox2D.|
|[`VRageMath.ContainmentType Contains(VRageMath.Vector2D)`](VRageMath.Contains)|Tests whether the BoundingBox2D contains a point.|
|[`void Contains(ref VRageMath.Vector2D, ref VRageMath.ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBox2D contains a point.|
|[`VRageMath.BoundingBox2D Translate(VRageMath.Vector2D)`](VRageMath.Translate)|Translate|
|[`VRageMath.BoundingBox2D Include(ref VRageMath.Vector2D)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`VRageMath.BoundingBox2D GetIncluded(VRageMath.Vector2D)`](VRageMath.GetIncluded)||
|[`VRageMath.BoundingBox2D Include(VRageMath.Vector2D)`](VRageMath.Include)||
|[`VRageMath.BoundingBox2D Include(VRageMath.Vector2D, VRageMath.Vector2D, VRageMath.Vector2D)`](VRageMath.Include)||
|[`VRageMath.BoundingBox2D Include(ref VRageMath.Vector2D, ref VRageMath.Vector2D, ref VRageMath.Vector2D)`](VRageMath.Include)||
|[`VRageMath.BoundingBox2D Include(ref VRageMath.BoundingBox2D)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`VRageMath.BoundingBox2D Include(VRageMath.BoundingBox2D)`](VRageMath.Include)||
|static [`VRageMath.BoundingBox2D CreateInvalid()`](VRageMath.CreateInvalid)||
|[`double Perimeter()`](VRageMath.Perimeter)||
|[`double Area()`](VRageMath.Area)||
|[`void Inflate(double)`](VRageMath.Inflate)||
|[`void InflateToMinimum(VRageMath.Vector2D)`](VRageMath.InflateToMinimum)||
|[`void Scale(VRageMath.Vector2D)`](VRageMath.Scale)||
