← [Index](index)
# BoundingBox2 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`Min`](VRageMath.Min)|The minimum point the BoundingBox2 contains.|
|[`Max`](VRageMath.Max)|The maximum point the BoundingBox2 contains.|
|static [`CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingBox2.|
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
|[`GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingBox2.|
|[`GetCorners(Vector2[])`](VRageMath.GetCorners)|Gets the array of points that make up the corners of the BoundingBox2.|
|[`GetCornersUnsafe(*Vector2)`](VRageMath.GetCornersUnsafe)||
|[`Equals(BoundingBox2)`](VRageMath.Equals)|Determines whether two instances of BoundingBox2 are equal.|
|[`Equals(Object)`](VRageMath.Equals)|Determines whether two instances of BoundingBox2 are equal.|
|[`GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingBox2.|
|static [`CreateMerged(BoundingBox2, BoundingBox2)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox2 that contains the two specified BoundingBox2 instances.|
|static [`CreateMerged(ref BoundingBox2, ref BoundingBox2, ref BoundingBox2)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox2 that contains the two specified BoundingBox2 instances.|
|static [`CreateFromPoints(IEnumerable<Vector2>)`](VRageMath.CreateFromPoints)|Creates the smallest BoundingBox2 that will contain a group of points.|
|static [`CreateFromHalfExtent(Vector2, float)`](VRageMath.CreateFromHalfExtent)||
|static [`CreateFromHalfExtent(Vector2, Vector2)`](VRageMath.CreateFromHalfExtent)||
|[`Intersect(BoundingBox2)`](VRageMath.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`Intersects(BoundingBox2)`](VRageMath.Intersects)|Checks whether the current BoundingBox2 intersects another BoundingBox2.|
|[`Intersects(ref BoundingBox2)`](VRageMath.Intersects)||
|[`Intersects(ref BoundingBox2, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingBox2 intersects another BoundingBox2.|
|[`Distance(Vector2)`](VRageMath.Distance)||
|[`Contains(BoundingBox2)`](VRageMath.Contains)|Tests whether the BoundingBox2 contains another BoundingBox2.|
|[`Contains(ref BoundingBox2, ref ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBox2 contains a BoundingBox2.|
|[`Contains(Vector2)`](VRageMath.Contains)|Tests whether the BoundingBox2 contains a point.|
|[`Contains(ref Vector2, ref ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBox2 contains a point.|
|[`Translate(Vector2)`](VRageMath.Translate)|Translate|
|[`Include(ref Vector2)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`GetIncluded(Vector2)`](VRageMath.GetIncluded)||
|[`Include(Vector2)`](VRageMath.Include)||
|[`Include(Vector2, Vector2, Vector2)`](VRageMath.Include)||
|[`Include(ref Vector2, ref Vector2, ref Vector2)`](VRageMath.Include)||
|[`Include(ref BoundingBox2)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`Include(BoundingBox2)`](VRageMath.Include)||
|static [`CreateInvalid()`](VRageMath.CreateInvalid)||
|[`Perimeter()`](VRageMath.Perimeter)||
|[`Area()`](VRageMath.Area)||
|[`Inflate(float)`](VRageMath.Inflate)||
|[`InflateToMinimum(Vector2)`](VRageMath.InflateToMinimum)||
|[`Scale(Vector2)`](VRageMath.Scale)||
