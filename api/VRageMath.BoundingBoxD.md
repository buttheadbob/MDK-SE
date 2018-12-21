← [Index](index)
# BoundingBoxD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`Min`](VRageMath.Min)|The minimum point the BoundingBox contains.|
|[`Max`](VRageMath.Max)|The maximum point the BoundingBox contains.|
|static [`Comparer`](VRageMath.Comparer)||
|static [`CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingBox.|
### Properties
|Member|Description|
|---|---|
|[`Center`](VRageMath.Center)|Calculates center|
|[`HalfExtents`](VRageMath.HalfExtents)||
|[`Extents`](VRageMath.Extents)||
|[`Size`](VRageMath.Size)|Size|
|[`Matrix`](VRageMath.Matrix)|Matrix of AABB, respection center and size|
|[`SurfaceArea`](VRageMath.SurfaceArea)||
|[`Volume`](VRageMath.Volume)||
|[`Perimeter`](VRageMath.Perimeter)|return perimeter of edges|
|[`Valid`](VRageMath.Valid)||
### Methods
|Member|Description|
|---|---|
|[`GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingBox. ALLOCATION!|
|[`GetCorners(Vector3D[])`](VRageMath.GetCorners)|Gets the array of points that make up the corners of the BoundingBox.|
|[`GetCornersUnsafe(*Vector3D)`](VRageMath.GetCornersUnsafe)||
|[`Equals(BoundingBoxD)`](VRageMath.Equals)|Determines whether two instances of BoundingBox are equal.|
|[`Equals(Object)`](VRageMath.Equals)|Determines whether two instances of BoundingBox are equal.|
|[`GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingBox.|
|static [`CreateMerged(BoundingBoxD, BoundingBoxD)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox that contains the two specified BoundingBox instances.|
|static [`CreateMerged(ref BoundingBoxD, ref BoundingBoxD, ref BoundingBoxD)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox that contains the two specified BoundingBox instances.|
|static [`CreateFromSphere(BoundingSphereD)`](VRageMath.CreateFromSphere)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|static [`CreateFromSphere(ref BoundingSphereD, ref BoundingBoxD)`](VRageMath.CreateFromSphere)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|static [`CreateFromPoints(IEnumerable<Vector3D>)`](VRageMath.CreateFromPoints)|Creates the smallest BoundingBox that will contain a group of points.|
|[`Intersect(BoundingBoxD)`](VRageMath.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`Intersects(BoundingBoxD)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects another BoundingBox.|
|[`Intersects(ref BoundingBoxD)`](VRageMath.Intersects)||
|[`Intersects(ref BoundingBoxD, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects another BoundingBox.|
|[`Intersects(ref BoundingBox, ref bool)`](VRageMath.Intersects)||
|[`IntersectsTriangle(Vector3D, Vector3D, Vector3D)`](VRageMath.IntersectsTriangle)||
|[`IntersectsTriangle(ref Vector3D, ref Vector3D, ref Vector3D)`](VRageMath.IntersectsTriangle)||
|[`Intersects(BoundingFrustumD)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a BoundingFrustum.|
|[`Intersects(PlaneD)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Plane.|
|[`Intersects(ref PlaneD, ref PlaneIntersectionType)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Plane.|
|[`Intersects(ref LineD)`](VRageMath.Intersects)||
|[`Intersects(ref LineD, ref double)`](VRageMath.Intersects)||
|[`Intersects(Ray)`](VRageMath.Intersects)||
|[`Intersects(RayD)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Ray.|
|[`Intersects(ref RayD, ref Nullable<double>)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Ray.|
|[`Intersect(ref LineD, ref LineD)`](VRageMath.Intersect)||
|[`Intersect(ref LineD, ref double, ref double)`](VRageMath.Intersect)||
|[`Intersect(ref RayD, ref double, ref double)`](VRageMath.Intersect)||
|[`Intersects(BoundingSphereD)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|[`Intersects(ref BoundingSphereD, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|[`Intersects(ref BoundingSphereD)`](VRageMath.Intersects)||
|[`Distance(Vector3D)`](VRageMath.Distance)||
|[`DistanceSquared(Vector3D)`](VRageMath.DistanceSquared)||
|[`DistanceSquared(ref Vector3D)`](VRageMath.DistanceSquared)||
|[`Contains(BoundingBoxD)`](VRageMath.Contains)|Tests whether the BoundingBox contains another BoundingBox.|
|[`Contains(ref BoundingBoxD, ref ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingBox.|
|[`Contains(BoundingFrustumD)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingFrustum.|
|[`Contains(Vector3D)`](VRageMath.Contains)|Tests whether the BoundingBox contains a point.|
|[`Contains(ref Vector3D, ref ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBox contains a point.|
|[`Contains(BoundingSphereD)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingSphere.|
|[`Contains(ref BoundingSphereD, ref ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingSphere.|
|[`Translate(MatrixD)`](VRageMath.Translate)|Translate|
|[`Translate(Vector3D)`](VRageMath.Translate)|Translate|
|[`TransformSlow(MatrixD)`](VRageMath.TransformSlow)|Transform this AABB by matrix.|
|[`TransformSlow(ref MatrixD)`](VRageMath.TransformSlow)|Transform this AABB by matrix.|
|[`TransformFast(MatrixD)`](VRageMath.TransformFast)|Transform this AABB by matrix. Matrix has to be only rotation and translation.|
|[`TransformFast(ref MatrixD)`](VRageMath.TransformFast)|Transform this AABB by matrix. Matrix has to be only rotation and translation.|
|[`TransformFast(ref MatrixD, ref BoundingBoxD)`](VRageMath.TransformFast)|Transform this AABB by matrix. Matrix has to be only rotation and translation.|
|[`Include(ref Vector3D)`](VRageMath.Include)|return expanded aabb (aabb include point)|
|[`Include(Vector3D)`](VRageMath.Include)||
|[`Include(Vector3D, Vector3D, Vector3D)`](VRageMath.Include)||
|[`Include(ref Vector3D, ref Vector3D, ref Vector3D)`](VRageMath.Include)||
|[`Include(ref BoundingBoxD)`](VRageMath.Include)|return expanded aabb (aabb include aabb)|
|[`Include(BoundingBoxD)`](VRageMath.Include)||
|[`Include(ref LineD)`](VRageMath.Include)||
|[`Include(BoundingSphereD)`](VRageMath.Include)||
|[`Include(ref BoundingSphereD)`](VRageMath.Include)||
|[`Include(ref BoundingFrustumD)`](VRageMath.Include)||
|static [`CreateInvalid()`](VRageMath.CreateInvalid)||
|[`ProjectedArea(Vector3D)`](VRageMath.ProjectedArea)||
|[`Inflate(double)`](VRageMath.Inflate)||
|[`Inflate(Vector3)`](VRageMath.Inflate)||
|[`GetInflated(double)`](VRageMath.GetInflated)||
|[`GetInflated(Vector3)`](VRageMath.GetInflated)||
|[`InflateToMinimum(Vector3D)`](VRageMath.InflateToMinimum)||
|[`InflateToMinimum(double)`](VRageMath.InflateToMinimum)||
|[`AssertIsValid()`](VRageMath.AssertIsValid)||
