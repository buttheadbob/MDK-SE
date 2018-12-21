← [Index](index)
# BoundingBoxD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`Vector3D&nbsp;Min`](VRageMath.Min)|The minimum point the BoundingBox contains.|
|[`Vector3D&nbsp;Max`](VRageMath.Max)|The maximum point the BoundingBox contains.|
|static&nbsp;[`ComparerType&nbsp;Comparer`](VRageMath.Comparer)||
|static&nbsp;[`int&nbsp;CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingBox.|
### Properties
|Member|Description|
|---|---|
|[`Vector3D&nbsp;Center`](VRageMath.Center)|Calculates center|
|[`Vector3D&nbsp;HalfExtents`](VRageMath.HalfExtents)||
|[`Vector3D&nbsp;Extents`](VRageMath.Extents)||
|[`Vector3D&nbsp;Size`](VRageMath.Size)|Size|
|[`MatrixD&nbsp;Matrix`](VRageMath.Matrix)|Matrix of AABB, respection center and size|
|[`double&nbsp;SurfaceArea`](VRageMath.SurfaceArea)||
|[`double&nbsp;Volume`](VRageMath.Volume)||
|[`double&nbsp;Perimeter`](VRageMath.Perimeter)|return perimeter of edges|
|[`bool&nbsp;Valid`](VRageMath.Valid)||
### Methods
|Member|Description|
|---|---|
|[`Vector3D[]&nbsp;GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingBox. ALLOCATION!|
|[`void&nbsp;GetCorners(Vector3D[]&nbsp;corners)`](VRageMath.GetCorners)|Gets the array of points that make up the corners of the BoundingBox.|
|[`void&nbsp;GetCornersUnsafe(*Vector3D&nbsp;corners)`](VRageMath.GetCornersUnsafe)||
|[`bool&nbsp;Equals(BoundingBoxD&nbsp;other)`](VRageMath.Equals)|Determines whether two instances of BoundingBox are equal.|
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Determines whether two instances of BoundingBox are equal.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string&nbsp;ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingBox.|
|static&nbsp;[`BoundingBoxD&nbsp;CreateMerged(BoundingBoxD&nbsp;original,&nbsp;BoundingBoxD&nbsp;additional)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox that contains the two specified BoundingBox instances.|
|static&nbsp;[`void&nbsp;CreateMerged(ref&nbsp;BoundingBoxD&nbsp;original,&nbsp;ref&nbsp;BoundingBoxD&nbsp;additional,&nbsp;ref&nbsp;BoundingBoxD&nbsp;result)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox that contains the two specified BoundingBox instances.|
|static&nbsp;[`BoundingBoxD&nbsp;CreateFromSphere(BoundingSphereD&nbsp;sphere)`](VRageMath.CreateFromSphere)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|static&nbsp;[`void&nbsp;CreateFromSphere(ref&nbsp;BoundingSphereD&nbsp;sphere,&nbsp;ref&nbsp;BoundingBoxD&nbsp;result)`](VRageMath.CreateFromSphere)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|static&nbsp;[`BoundingBoxD&nbsp;CreateFromPoints(IEnumerable<Vector3D>&nbsp;points)`](VRageMath.CreateFromPoints)|Creates the smallest BoundingBox that will contain a group of points.|
|[`BoundingBoxD&nbsp;Intersect(BoundingBoxD&nbsp;box)`](VRageMath.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`bool&nbsp;Intersects(BoundingBoxD&nbsp;box)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects another BoundingBox.|
|[`bool&nbsp;Intersects(ref&nbsp;BoundingBoxD&nbsp;box)`](VRageMath.Intersects)||
|[`void&nbsp;Intersects(ref&nbsp;BoundingBoxD&nbsp;box,&nbsp;ref&nbsp;bool&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects another BoundingBox.|
|[`void&nbsp;Intersects(ref&nbsp;BoundingBox&nbsp;box,&nbsp;ref&nbsp;bool&nbsp;result)`](VRageMath.Intersects)||
|[`bool&nbsp;IntersectsTriangle(Vector3D&nbsp;v0,&nbsp;Vector3D&nbsp;v1,&nbsp;Vector3D&nbsp;v2)`](VRageMath.IntersectsTriangle)||
|[`bool&nbsp;IntersectsTriangle(ref&nbsp;Vector3D&nbsp;v0,&nbsp;ref&nbsp;Vector3D&nbsp;v1,&nbsp;ref&nbsp;Vector3D&nbsp;v2)`](VRageMath.IntersectsTriangle)||
|[`bool&nbsp;Intersects(BoundingFrustumD&nbsp;frustum)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a BoundingFrustum.|
|[`PlaneIntersectionType&nbsp;Intersects(PlaneD&nbsp;plane)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Plane.|
|[`void&nbsp;Intersects(ref&nbsp;PlaneD&nbsp;plane,&nbsp;ref&nbsp;PlaneIntersectionType&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Plane.|
|[`bool&nbsp;Intersects(ref&nbsp;LineD&nbsp;line)`](VRageMath.Intersects)||
|[`bool&nbsp;Intersects(ref&nbsp;LineD&nbsp;line,&nbsp;ref&nbsp;double&nbsp;distance)`](VRageMath.Intersects)||
|[`Nullable<double>&nbsp;Intersects(Ray&nbsp;ray)`](VRageMath.Intersects)||
|[`Nullable<double>&nbsp;Intersects(RayD&nbsp;ray)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Ray.|
|[`void&nbsp;Intersects(ref&nbsp;RayD&nbsp;ray,&nbsp;ref&nbsp;Nullable<double>&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Ray.|
|[`bool&nbsp;Intersect(ref&nbsp;LineD&nbsp;line,&nbsp;ref&nbsp;LineD&nbsp;intersectedLine)`](VRageMath.Intersect)||
|[`bool&nbsp;Intersect(ref&nbsp;LineD&nbsp;line,&nbsp;ref&nbsp;double&nbsp;t1,&nbsp;ref&nbsp;double&nbsp;t2)`](VRageMath.Intersect)||
|[`bool&nbsp;Intersect(ref&nbsp;RayD&nbsp;ray,&nbsp;ref&nbsp;double&nbsp;tmin,&nbsp;ref&nbsp;double&nbsp;tmax)`](VRageMath.Intersect)||
|[`bool&nbsp;Intersects(BoundingSphereD&nbsp;sphere)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|[`void&nbsp;Intersects(ref&nbsp;BoundingSphereD&nbsp;sphere,&nbsp;ref&nbsp;bool&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|[`bool&nbsp;Intersects(ref&nbsp;BoundingSphereD&nbsp;sphere)`](VRageMath.Intersects)||
|[`double&nbsp;Distance(Vector3D&nbsp;point)`](VRageMath.Distance)||
|[`double&nbsp;DistanceSquared(Vector3D&nbsp;point)`](VRageMath.DistanceSquared)||
|[`double&nbsp;DistanceSquared(ref&nbsp;Vector3D&nbsp;point)`](VRageMath.DistanceSquared)||
|[`ContainmentType&nbsp;Contains(BoundingBoxD&nbsp;box)`](VRageMath.Contains)|Tests whether the BoundingBox contains another BoundingBox.|
|[`void&nbsp;Contains(ref&nbsp;BoundingBoxD&nbsp;box,&nbsp;ref&nbsp;ContainmentType&nbsp;result)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingBox.|
|[`ContainmentType&nbsp;Contains(BoundingFrustumD&nbsp;frustum)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingFrustum.|
|[`ContainmentType&nbsp;Contains(Vector3D&nbsp;point)`](VRageMath.Contains)|Tests whether the BoundingBox contains a point.|
|[`void&nbsp;Contains(ref&nbsp;Vector3D&nbsp;point,&nbsp;ref&nbsp;ContainmentType&nbsp;result)`](VRageMath.Contains)|Tests whether the BoundingBox contains a point.|
|[`ContainmentType&nbsp;Contains(BoundingSphereD&nbsp;sphere)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingSphere.|
|[`void&nbsp;Contains(ref&nbsp;BoundingSphereD&nbsp;sphere,&nbsp;ref&nbsp;ContainmentType&nbsp;result)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingSphere.|
|[`BoundingBoxD&nbsp;Translate(MatrixD&nbsp;worldMatrix)`](VRageMath.Translate)|Translate|
|[`BoundingBoxD&nbsp;Translate(Vector3D&nbsp;vctTranlsation)`](VRageMath.Translate)|Translate|
|[`BoundingBoxD&nbsp;TransformSlow(MatrixD&nbsp;m)`](VRageMath.TransformSlow)|Transform this AABB by matrix.|
|[`BoundingBoxD&nbsp;TransformSlow(ref&nbsp;MatrixD&nbsp;worldMatrix)`](VRageMath.TransformSlow)|Transform this AABB by matrix.|
|[`BoundingBoxD&nbsp;TransformFast(MatrixD&nbsp;m)`](VRageMath.TransformFast)|Transform this AABB by matrix. Matrix has to be only rotation and translation.|
|[`BoundingBoxD&nbsp;TransformFast(ref&nbsp;MatrixD&nbsp;m)`](VRageMath.TransformFast)|Transform this AABB by matrix. Matrix has to be only rotation and translation.|
|[`void&nbsp;TransformFast(ref&nbsp;MatrixD&nbsp;m,&nbsp;ref&nbsp;BoundingBoxD&nbsp;bb)`](VRageMath.TransformFast)|Transform this AABB by matrix. Matrix has to be only rotation and translation.|
|[`BoundingBoxD&nbsp;Include(ref&nbsp;Vector3D&nbsp;point)`](VRageMath.Include)|return expanded aabb (aabb include point)|
|[`BoundingBoxD&nbsp;Include(Vector3D&nbsp;point)`](VRageMath.Include)||
|[`BoundingBoxD&nbsp;Include(Vector3D&nbsp;p0,&nbsp;Vector3D&nbsp;p1,&nbsp;Vector3D&nbsp;p2)`](VRageMath.Include)||
|[`BoundingBoxD&nbsp;Include(ref&nbsp;Vector3D&nbsp;p0,&nbsp;ref&nbsp;Vector3D&nbsp;p1,&nbsp;ref&nbsp;Vector3D&nbsp;p2)`](VRageMath.Include)||
|[`BoundingBoxD&nbsp;Include(ref&nbsp;BoundingBoxD&nbsp;box)`](VRageMath.Include)|return expanded aabb (aabb include aabb)|
|[`BoundingBoxD&nbsp;Include(BoundingBoxD&nbsp;box)`](VRageMath.Include)||
|[`void&nbsp;Include(ref&nbsp;LineD&nbsp;line)`](VRageMath.Include)||
|[`BoundingBoxD&nbsp;Include(BoundingSphereD&nbsp;sphere)`](VRageMath.Include)||
|[`BoundingBoxD&nbsp;Include(ref&nbsp;BoundingSphereD&nbsp;sphere)`](VRageMath.Include)||
|[`BoundingBoxD&nbsp;Include(ref&nbsp;BoundingFrustumD&nbsp;frustum)`](VRageMath.Include)||
|static&nbsp;[`BoundingBoxD&nbsp;CreateInvalid()`](VRageMath.CreateInvalid)||
|[`double&nbsp;ProjectedArea(Vector3D&nbsp;viewDir)`](VRageMath.ProjectedArea)||
|[`BoundingBoxD&nbsp;Inflate(double&nbsp;size)`](VRageMath.Inflate)||
|[`BoundingBoxD&nbsp;Inflate(Vector3&nbsp;size)`](VRageMath.Inflate)||
|[`BoundingBoxD&nbsp;GetInflated(double&nbsp;size)`](VRageMath.GetInflated)||
|[`BoundingBoxD&nbsp;GetInflated(Vector3&nbsp;size)`](VRageMath.GetInflated)||
|[`void&nbsp;InflateToMinimum(Vector3D&nbsp;minimumSize)`](VRageMath.InflateToMinimum)||
|[`void&nbsp;InflateToMinimum(double&nbsp;minimumSize)`](VRageMath.InflateToMinimum)||
|[`void&nbsp;AssertIsValid()`](VRageMath.AssertIsValid)||
