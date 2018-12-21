← [Index](index)
# BoundingBox2D Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`Min`](VRageMath.Min)|The minimum point the BoundingBox2D contains.|
|[`Max`](VRageMath.Max)|The maximum point the BoundingBox2D contains.|
|static [`CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingBox2D.|
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
|[`GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingBox2D.|
|[`GetCorners(Vector2D[])`](VRageMath.GetCorners)|Gets the array of points that make up the corners of the BoundingBox2D.|
|[`GetCornersUnsafe(*Vector2D)`](VRageMath.GetCornersUnsafe)||
|[`Equals(BoundingBox2D)`](VRageMath.Equals)|Determines whether two instances of BoundingBox2D are equal.|
|[`Equals(Object)`](VRageMath.Equals)|Determines whether two instances of BoundingBox2D are equal.|
|[`GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingBox2D.|
|static [`CreateMerged(BoundingBox2D, BoundingBox2D)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox2D that contains the two specified BoundingBox2D instances.|
|static [`CreateMerged(ref BoundingBox2D, ref BoundingBox2D, ref BoundingBox2D)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox2D that contains the two specified BoundingBox2D instances.|
|static [`CreateFromPoints(IEnumerable<Vector2D>)`](VRageMath.CreateFromPoints)|Creates the smallest BoundingBox2D that will contain a group of points.|
|static [`CreateFromHalfExtent(Vector2D, double)`](VRageMath.CreateFromHalfExtent)||
|static [`CreateFromHalfExtent(Vector2D, Vector2D)`](VRageMath.CreateFromHalfExtent)||
|[`Intersect(BoundingBox2D)`](VRageMath.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`Intersects(BoundingBox2D)`](VRageMath.Intersects)|Checks whether the current BoundingBox2D intersects another BoundingBox2D.|
|[`Intersects(ref BoundingBox2D)`](VRageMath.Intersects)||
|[`Intersects(ref BoundingBox2D, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingBox2D intersects another BoundingBox2D.|
|[`Distance(Vector2D)`](VRageMath.Distance)||
|[`Contains(BoundingBox2D)`](VRageMath.Contains)|Tests whether the BoundingBox2D contains another BoundingBox2D.|
|[`Contains(ref BoundingBox2D, ref ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBox2D contains a BoundingBox2D.|
|[`Contains(Vector2D)`](VRageMath.Contains)|Tests whether the BoundingBox2D contains a point.|
|[`Contains(ref Vector2D, ref ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBox2D contains a point.|
|[`Translate(Vector2D)`](VRageMath.Translate)|Translate|
|[`Include(ref Vector2D)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`GetIncluded(Vector2D)`](VRageMath.GetIncluded)||
|[`Include(Vector2D)`](VRageMath.Include)||
|[`Include(Vector2D, Vector2D, Vector2D)`](VRageMath.Include)||
|[`Include(ref Vector2D, ref Vector2D, ref Vector2D)`](VRageMath.Include)||
|[`Include(ref BoundingBox2D)`](VRageMath.Include)|return expanded aabb (abb include point)|
|[`Include(BoundingBox2D)`](VRageMath.Include)||
|static [`CreateInvalid()`](VRageMath.CreateInvalid)||
|[`Perimeter()`](VRageMath.Perimeter)||
|[`Area()`](VRageMath.Area)||
|[`Inflate(double)`](VRageMath.Inflate)||
|[`InflateToMinimum(Vector2D)`](VRageMath.InflateToMinimum)||
|[`Scale(Vector2D)`](VRageMath.Scale)||
