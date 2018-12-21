← [Index](index)
# BoundingBoxD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`VRageMath.Vector3D Min`](VRageMath.Min)|The minimum point the BoundingBox contains.|
|[`VRageMath.Vector3D Max`](VRageMath.Max)|The maximum point the BoundingBox contains.|
|static [`VRageMath.ComparerType Comparer`](VRageMath.Comparer)||
|static [`int CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingBox.|
### Properties
|Member|Description|
|---|---|
|[`VRageMath.Vector3D Center`](VRageMath.Center)|Calculates center|
|[`VRageMath.Vector3D HalfExtents`](VRageMath.HalfExtents)||
|[`VRageMath.Vector3D Extents`](VRageMath.Extents)||
|[`VRageMath.Vector3D Size`](VRageMath.Size)|Size|
|[`VRageMath.MatrixD Matrix`](VRageMath.Matrix)|Matrix of AABB, respection center and size|
|[`double SurfaceArea`](VRageMath.SurfaceArea)||
|[`double Volume`](VRageMath.Volume)||
|[`double Perimeter`](VRageMath.Perimeter)|return perimeter of edges|
|[`bool Valid`](VRageMath.Valid)||
### Methods
|Member|Description|
|---|---|
|[`VRageMath.Vector3D[] GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingBox. ALLOCATION!|
|[`void GetCorners(VRageMath.Vector3D[])`](VRageMath.GetCorners)|Gets the array of points that make up the corners of the BoundingBox.|
|[`void GetCornersUnsafe(*VRageMath.Vector3D)`](VRageMath.GetCornersUnsafe)||
|[`bool Equals(VRageMath.BoundingBoxD)`](VRageMath.Equals)|Determines whether two instances of BoundingBox are equal.|
|[`bool Equals(System.Object)`](VRageMath.Equals)|Determines whether two instances of BoundingBox are equal.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingBox.|
|static [`VRageMath.BoundingBoxD CreateMerged(VRageMath.BoundingBoxD, VRageMath.BoundingBoxD)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox that contains the two specified BoundingBox instances.|
|static [`void CreateMerged(ref VRageMath.BoundingBoxD, ref VRageMath.BoundingBoxD, ref VRageMath.BoundingBoxD)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox that contains the two specified BoundingBox instances.|
|static [`VRageMath.BoundingBoxD CreateFromSphere(VRageMath.BoundingSphereD)`](VRageMath.CreateFromSphere)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|static [`void CreateFromSphere(ref VRageMath.BoundingSphereD, ref VRageMath.BoundingBoxD)`](VRageMath.CreateFromSphere)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|static [`VRageMath.BoundingBoxD CreateFromPoints(IEnumerable<VRageMath.Vector3D>)`](VRageMath.CreateFromPoints)|Creates the smallest BoundingBox that will contain a group of points.|
|[`VRageMath.BoundingBoxD Intersect(VRageMath.BoundingBoxD)`](VRageMath.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`bool Intersects(VRageMath.BoundingBoxD)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects another BoundingBox.|
|[`bool Intersects(ref VRageMath.BoundingBoxD)`](VRageMath.Intersects)||
|[`void Intersects(ref VRageMath.BoundingBoxD, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects another BoundingBox.|
|[`void Intersects(ref VRageMath.BoundingBox, ref bool)`](VRageMath.Intersects)||
|[`bool IntersectsTriangle(VRageMath.Vector3D, VRageMath.Vector3D, VRageMath.Vector3D)`](VRageMath.IntersectsTriangle)||
|[`bool IntersectsTriangle(ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref VRageMath.Vector3D)`](VRageMath.IntersectsTriangle)||
|[`bool Intersects(VRageMath.BoundingFrustumD)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a BoundingFrustum.|
|[`VRageMath.PlaneIntersectionType Intersects(VRageMath.PlaneD)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Plane.|
|[`void Intersects(ref VRageMath.PlaneD, ref VRageMath.PlaneIntersectionType)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Plane.|
|[`bool Intersects(ref VRageMath.LineD)`](VRageMath.Intersects)||
|[`bool Intersects(ref VRageMath.LineD, ref double)`](VRageMath.Intersects)||
|[`Nullable<System.Double> Intersects(VRageMath.Ray)`](VRageMath.Intersects)||
|[`Nullable<System.Double> Intersects(VRageMath.RayD)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Ray.|
|[`void Intersects(ref VRageMath.RayD, ref Nullable<System.Double>)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Ray.|
|[`bool Intersect(ref VRageMath.LineD, ref VRageMath.LineD)`](VRageMath.Intersect)||
|[`bool Intersect(ref VRageMath.LineD, ref double, ref double)`](VRageMath.Intersect)||
|[`bool Intersect(ref VRageMath.RayD, ref double, ref double)`](VRageMath.Intersect)||
|[`bool Intersects(VRageMath.BoundingSphereD)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|[`void Intersects(ref VRageMath.BoundingSphereD, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|[`bool Intersects(ref VRageMath.BoundingSphereD)`](VRageMath.Intersects)||
|[`double Distance(VRageMath.Vector3D)`](VRageMath.Distance)||
|[`double DistanceSquared(VRageMath.Vector3D)`](VRageMath.DistanceSquared)||
|[`double DistanceSquared(ref VRageMath.Vector3D)`](VRageMath.DistanceSquared)||
|[`VRageMath.ContainmentType Contains(VRageMath.BoundingBoxD)`](VRageMath.Contains)|Tests whether the BoundingBox contains another BoundingBox.|
|[`void Contains(ref VRageMath.BoundingBoxD, ref VRageMath.ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingBox.|
|[`VRageMath.ContainmentType Contains(VRageMath.BoundingFrustumD)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingFrustum.|
|[`VRageMath.ContainmentType Contains(VRageMath.Vector3D)`](VRageMath.Contains)|Tests whether the BoundingBox contains a point.|
|[`void Contains(ref VRageMath.Vector3D, ref VRageMath.ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBox contains a point.|
|[`VRageMath.ContainmentType Contains(VRageMath.BoundingSphereD)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingSphere.|
|[`void Contains(ref VRageMath.BoundingSphereD, ref VRageMath.ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingSphere.|
|[`VRageMath.BoundingBoxD Translate(VRageMath.MatrixD)`](VRageMath.Translate)|Translate|
|[`VRageMath.BoundingBoxD Translate(VRageMath.Vector3D)`](VRageMath.Translate)|Translate|
|[`VRageMath.BoundingBoxD TransformSlow(VRageMath.MatrixD)`](VRageMath.TransformSlow)|Transform this AABB by matrix.|
|[`VRageMath.BoundingBoxD TransformSlow(ref VRageMath.MatrixD)`](VRageMath.TransformSlow)|Transform this AABB by matrix.|
|[`VRageMath.BoundingBoxD TransformFast(VRageMath.MatrixD)`](VRageMath.TransformFast)|Transform this AABB by matrix. Matrix has to be only rotation and translation.|
|[`VRageMath.BoundingBoxD TransformFast(ref VRageMath.MatrixD)`](VRageMath.TransformFast)|Transform this AABB by matrix. Matrix has to be only rotation and translation.|
|[`void TransformFast(ref VRageMath.MatrixD, ref VRageMath.BoundingBoxD)`](VRageMath.TransformFast)|Transform this AABB by matrix. Matrix has to be only rotation and translation.|
|[`VRageMath.BoundingBoxD Include(ref VRageMath.Vector3D)`](VRageMath.Include)|return expanded aabb (aabb include point)|
|[`VRageMath.BoundingBoxD Include(VRageMath.Vector3D)`](VRageMath.Include)||
|[`VRageMath.BoundingBoxD Include(VRageMath.Vector3D, VRageMath.Vector3D, VRageMath.Vector3D)`](VRageMath.Include)||
|[`VRageMath.BoundingBoxD Include(ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref VRageMath.Vector3D)`](VRageMath.Include)||
|[`VRageMath.BoundingBoxD Include(ref VRageMath.BoundingBoxD)`](VRageMath.Include)|return expanded aabb (aabb include aabb)|
|[`VRageMath.BoundingBoxD Include(VRageMath.BoundingBoxD)`](VRageMath.Include)||
|[`void Include(ref VRageMath.LineD)`](VRageMath.Include)||
|[`VRageMath.BoundingBoxD Include(VRageMath.BoundingSphereD)`](VRageMath.Include)||
|[`VRageMath.BoundingBoxD Include(ref VRageMath.BoundingSphereD)`](VRageMath.Include)||
|[`VRageMath.BoundingBoxD Include(ref VRageMath.BoundingFrustumD)`](VRageMath.Include)||
|static [`VRageMath.BoundingBoxD CreateInvalid()`](VRageMath.CreateInvalid)||
|[`double ProjectedArea(VRageMath.Vector3D)`](VRageMath.ProjectedArea)||
|[`VRageMath.BoundingBoxD Inflate(double)`](VRageMath.Inflate)||
|[`VRageMath.BoundingBoxD Inflate(VRageMath.Vector3)`](VRageMath.Inflate)||
|[`VRageMath.BoundingBoxD GetInflated(double)`](VRageMath.GetInflated)||
|[`VRageMath.BoundingBoxD GetInflated(VRageMath.Vector3)`](VRageMath.GetInflated)||
|[`void InflateToMinimum(VRageMath.Vector3D)`](VRageMath.InflateToMinimum)||
|[`void InflateToMinimum(double)`](VRageMath.InflateToMinimum)||
|[`void AssertIsValid()`](VRageMath.AssertIsValid)||
