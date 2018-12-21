← [Index](Api-Index)
# BoundingBox2I Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`Min`](VRageMath.Min)|The minimum point the BoundingBox2I contains.|
|[`Max`](VRageMath.Max)|The maximum point the BoundingBox2I contains.|
|[`CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingBox2I.|
### Properties
|Member|Description|
|---|---|
|[`Center`](VRageMath.Center)|Calculates center|
|[`HalfExtents`](VRageMath.HalfExtents)||
|[`Extents`](VRageMath.Extents)||
|[`Width`](VRageMath.Width)||
|[`Height`](VRageMath.Height)||
|[`Size`](VRageMath.Size)|Size|
### Methods
|Member|Description|
|---|---|
|[`GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingBox2I.|
|[`GetCorners(Vector2I[])`](VRageMath.GetCorners)|Gets the array of points that make up the corners of the BoundingBox2I.|
|[`GetCornersUnsafe(*Vector2I)`](VRageMath.GetCornersUnsafe)||
|[`Equals(BoundingBox2I)`](VRageMath.Equals)|Determines whether two instances of BoundingBox2I are equal.|
|[`Equals(Object)`](VRageMath.Equals)|Determines whether two instances of BoundingBox2I are equal.|
|[`GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingBox2I.|
|[`CreateMerged(BoundingBox2I, BoundingBox2I)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox2I that contains the two specified BoundingBox2I instances.|
|[`CreateMerged(ref BoundingBox2I, ref BoundingBox2I, ref BoundingBox2I)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox2I that contains the two specified BoundingBox2I instances.|
|[`CreateFromPoints(IEnumerable<Vector2I>)`](VRageMath.CreateFromPoints)|Creates the smallest BoundingBox2I that will contain a group of points.|
|[`CreateFromHalfExtent(Vector2I, int)`](VRageMath.CreateFromHalfExtent)||
|[`CreateFromHalfExtent(Vector2I, Vector2I)`](VRageMath.CreateFromHalfExtent)||
|[`Intersect(BoundingBox2I)`](VRageMath.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`Intersects(BoundingBox2I)`](VRageMath.Intersects)|Checks whether the current BoundingBox2I intersects another BoundingBox2I.|
|[`Intersects(ref BoundingBox2I)`](VRageMath.Intersects)||
|[`Intersects(ref BoundingBox2I, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingBox2I intersects another BoundingBox2I.|
|[`Contains(BoundingBox2I)`](VRageMath.Contains)|Tests whether the BoundingBox2I contains another BoundingBox2I.|
|[`Contains(ref BoundingBox2I, ref ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBox2I contains a BoundingBox2I.|
|[`Contains(Vector2I)`](VRageMath.Contains)|Tests whether the BoundingBox2I contains a point.|
|[`Contains(ref Vector2I, ref ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBox2I contains a point.|
|[`Translate(Vector2I)`](VRageMath.Translate)|Translate|
|[`Include(ref Vector2I)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`GetIncluded(Vector2I)`](VRageMath.GetIncluded)||
|[`Include(Vector2I)`](VRageMath.Include)||
|[`Include(Vector2I, Vector2I, Vector2I)`](VRageMath.Include)||
|[`Include(ref Vector2I, ref Vector2I, ref Vector2I)`](VRageMath.Include)||
|[`Include(ref BoundingBox2I)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`Include(BoundingBox2I)`](VRageMath.Include)||
|[`CreateInvalid()`](VRageMath.CreateInvalid)||
|[`Perimeter()`](VRageMath.Perimeter)||
|[`Area()`](VRageMath.Area)||
|[`Inflate(int)`](VRageMath.Inflate)||
|[`InflateToMinimum(Vector2I)`](VRageMath.InflateToMinimum)||
|[`Scale(Vector2I)`](VRageMath.Scale)||
