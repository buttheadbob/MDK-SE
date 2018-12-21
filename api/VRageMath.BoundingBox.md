← [Index](index)
# BoundingBox Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`Min`](VRageMath.Min)|The minimum point the BoundingBox contains.|
|[`Max`](VRageMath.Max)|The maximum point the BoundingBox contains.|
|[`Comparer`](VRageMath.Comparer)||
|[`CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingBox.|
### Properties
|Member|Description|
|---|---|
|[`Corners`](VRageMath.Corners)||
|[`Center`](VRageMath.Center)|Calculates center|
|[`HalfExtents`](VRageMath.HalfExtents)||
|[`Extents`](VRageMath.Extents)||
|[`Width`](VRageMath.Width)||
|[`Height`](VRageMath.Height)||
|[`Depth`](VRageMath.Depth)||
|[`Size`](VRageMath.Size)|Size|
|[`Matrix`](VRageMath.Matrix)|Matrix of AABB, respection center and size|
|[`Perimeter`](VRageMath.Perimeter)|return perimeter of edges|
### Methods
|Member|Description|
|---|---|
|[`GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingBox. ALLOCATION!|
|[`GetCorners(Vector3[])`](VRageMath.GetCorners)|Gets the array of points that make up the corners of the BoundingBox.|
|[`GetCornersUnsafe(*Vector3)`](VRageMath.GetCornersUnsafe)||
|[`Equals(BoundingBox)`](VRageMath.Equals)|Determines whether two instances of BoundingBox are equal.|
|[`Equals(Object)`](VRageMath.Equals)|Determines whether two instances of BoundingBox are equal.|
|[`GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingBox.|
|[`CreateMerged(BoundingBox, BoundingBox)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox that contains the two specified BoundingBox instances.|
|[`CreateMerged(ref BoundingBox, ref BoundingBox, ref BoundingBox)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox that contains the two specified BoundingBox instances.|
|[`CreateFromSphere(BoundingSphere)`](VRageMath.CreateFromSphere)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|[`CreateFromSphere(ref BoundingSphere, ref BoundingBox)`](VRageMath.CreateFromSphere)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|[`CreateFromPoints(IEnumerable<Vector3>)`](VRageMath.CreateFromPoints)|Creates the smallest BoundingBox that will contain a group of points.|
|[`CreateFromHalfExtent(Vector3, float)`](VRageMath.CreateFromHalfExtent)||
|[`CreateFromHalfExtent(Vector3, Vector3)`](VRageMath.CreateFromHalfExtent)||
|[`Intersect(BoundingBox)`](VRageMath.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`Intersects(BoundingBox)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects another BoundingBox.|
|[`Intersects(ref BoundingBox)`](VRageMath.Intersects)||
|[`Intersects(ref BoundingBox, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects another BoundingBox.|
|[`IntersectsTriangle(Vector3, Vector3, Vector3)`](VRageMath.IntersectsTriangle)||
|[`IntersectsTriangle(ref Vector3, ref Vector3, ref Vector3)`](VRageMath.IntersectsTriangle)||
|[`Intersects(BoundingFrustum)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a BoundingFrustum.|
|[`Intersects(Plane)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Plane.|
|[`Intersects(ref Plane, ref PlaneIntersectionType)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Plane.|
|[`Intersects(Line, ref float)`](VRageMath.Intersects)||
|[`Intersects(Ray)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Ray.|
|[`Intersects(ref Ray, ref Nullable<float>)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Ray.|
|[`Intersects(BoundingSphere)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|[`Intersects(ref BoundingSphere, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|[`Intersects(ref BoundingSphere)`](VRageMath.Intersects)||
|[`Intersects(ref BoundingSphereD)`](VRageMath.Intersects)||
|[`Distance(Vector3)`](VRageMath.Distance)||
|[`DistanceSquared(Vector3)`](VRageMath.DistanceSquared)||
|[`Contains(BoundingBox)`](VRageMath.Contains)|Tests whether the BoundingBox contains another BoundingBox.|
|[`Contains(ref BoundingBox, ref ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingBox.|
|[`Contains(BoundingFrustum)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingFrustum.|
|[`Contains(Vector3)`](VRageMath.Contains)|Tests whether the BoundingBox contains a point.|
|[`Contains(Vector3D)`](VRageMath.Contains)||
|[`Contains(ref Vector3, ref ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBox contains a point.|
|[`Contains(BoundingSphere)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingSphere.|
|[`Contains(ref BoundingSphere, ref ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingSphere.|
|[`Translate(Matrix)`](VRageMath.Translate)|Translate|
|[`Translate(Vector3)`](VRageMath.Translate)|Translate|
|[`Transform(Matrix)`](VRageMath.Transform)||
|[`Transform(MatrixD)`](VRageMath.Transform)||
|[`Transform(ref Matrix)`](VRageMath.Transform)||
|[`Transform(ref Matrix, ref BoundingBox)`](VRageMath.Transform)||
|[`Transform(ref MatrixD)`](VRageMath.Transform)||
|[`Transform(ref MatrixD, ref BoundingBoxD)`](VRageMath.Transform)||
|[`Include(ref Vector3)`](VRageMath.Include)|return expanded aabb (aabb include point)|
|[`GetIncluded(Vector3)`](VRageMath.GetIncluded)||
|[`Include(Vector3)`](VRageMath.Include)||
|[`Include(Vector3, Vector3, Vector3)`](VRageMath.Include)||
|[`Include(ref Vector3, ref Vector3, ref Vector3)`](VRageMath.Include)||
|[`Include(ref BoundingBox)`](VRageMath.Include)|return expanded aabb (aabb include aabb)|
|[`Include(BoundingBox)`](VRageMath.Include)||
|[`Include(ref Line)`](VRageMath.Include)||
|[`Include(BoundingSphere)`](VRageMath.Include)||
|[`Include(ref BoundingSphere)`](VRageMath.Include)||
|[`Include(ref BoundingFrustum)`](VRageMath.Include)||
|[`CreateInvalid()`](VRageMath.CreateInvalid)||
|[`SurfaceArea()`](VRageMath.SurfaceArea)||
|[`Volume()`](VRageMath.Volume)||
|[`ProjectedArea(Vector3)`](VRageMath.ProjectedArea)||
|[`Inflate(float)`](VRageMath.Inflate)||
|[`Inflate(Vector3)`](VRageMath.Inflate)||
|[`InflateToMinimum(Vector3)`](VRageMath.InflateToMinimum)||
|[`Scale(Vector3)`](VRageMath.Scale)||
