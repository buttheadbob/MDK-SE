← [Index](index)
# BoundingBox Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`Vector3&nbsp;Min`](VRageMath.Min)|The minimum point the BoundingBox contains.|
|[`Vector3&nbsp;Max`](VRageMath.Max)|The maximum point the BoundingBox contains.|
|static&nbsp;[`ComparerType&nbsp;Comparer`](VRageMath.Comparer)||
|static&nbsp;[`int&nbsp;CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingBox.|
### Properties
|Member|Description|
|---|---|
|[`BoxCornerEnumerator&nbsp;Corners`](VRageMath.Corners)||
|[`Vector3&nbsp;Center`](VRageMath.Center)|Calculates center|
|[`Vector3&nbsp;HalfExtents`](VRageMath.HalfExtents)||
|[`Vector3&nbsp;Extents`](VRageMath.Extents)||
|[`float&nbsp;Width`](VRageMath.Width)||
|[`float&nbsp;Height`](VRageMath.Height)||
|[`float&nbsp;Depth`](VRageMath.Depth)||
|[`Vector3&nbsp;Size`](VRageMath.Size)|Size|
|[`Matrix&nbsp;Matrix`](VRageMath.Matrix)|Matrix of AABB, respection center and size|
|[`float&nbsp;Perimeter`](VRageMath.Perimeter)|return perimeter of edges|
### Methods
|Member|Description|
|---|---|
|[`Vector3[]&nbsp;GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingBox. ALLOCATION!|
|[`void&nbsp;GetCorners(Vector3[]&nbsp;corners)`](VRageMath.GetCorners)|Gets the array of points that make up the corners of the BoundingBox.|
|[`void&nbsp;GetCornersUnsafe(*Vector3&nbsp;corners)`](VRageMath.GetCornersUnsafe)||
|[`bool&nbsp;Equals(BoundingBox&nbsp;other)`](VRageMath.Equals)|Determines whether two instances of BoundingBox are equal.|
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Determines whether two instances of BoundingBox are equal.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string&nbsp;ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingBox.|
|static&nbsp;[`BoundingBox&nbsp;CreateMerged(BoundingBox&nbsp;original,&nbsp;BoundingBox&nbsp;additional)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox that contains the two specified BoundingBox instances.|
|static&nbsp;[`void&nbsp;CreateMerged(ref&nbsp;BoundingBox&nbsp;original,&nbsp;ref&nbsp;BoundingBox&nbsp;additional,&nbsp;ref&nbsp;BoundingBox&nbsp;result)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox that contains the two specified BoundingBox instances.|
|static&nbsp;[`BoundingBox&nbsp;CreateFromSphere(BoundingSphere&nbsp;sphere)`](VRageMath.CreateFromSphere)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|static&nbsp;[`void&nbsp;CreateFromSphere(ref&nbsp;BoundingSphere&nbsp;sphere,&nbsp;ref&nbsp;BoundingBox&nbsp;result)`](VRageMath.CreateFromSphere)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|static&nbsp;[`BoundingBox&nbsp;CreateFromPoints(IEnumerable<Vector3>&nbsp;points)`](VRageMath.CreateFromPoints)|Creates the smallest BoundingBox that will contain a group of points.|
|static&nbsp;[`BoundingBox&nbsp;CreateFromHalfExtent(Vector3&nbsp;center,&nbsp;float&nbsp;halfExtent)`](VRageMath.CreateFromHalfExtent)||
|static&nbsp;[`BoundingBox&nbsp;CreateFromHalfExtent(Vector3&nbsp;center,&nbsp;Vector3&nbsp;halfExtent)`](VRageMath.CreateFromHalfExtent)||
|[`BoundingBox&nbsp;Intersect(BoundingBox&nbsp;box)`](VRageMath.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`bool&nbsp;Intersects(BoundingBox&nbsp;box)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects another BoundingBox.|
|[`bool&nbsp;Intersects(ref&nbsp;BoundingBox&nbsp;box)`](VRageMath.Intersects)||
|[`void&nbsp;Intersects(ref&nbsp;BoundingBox&nbsp;box,&nbsp;ref&nbsp;bool&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects another BoundingBox.|
|[`bool&nbsp;IntersectsTriangle(Vector3&nbsp;v0,&nbsp;Vector3&nbsp;v1,&nbsp;Vector3&nbsp;v2)`](VRageMath.IntersectsTriangle)||
|[`bool&nbsp;IntersectsTriangle(ref&nbsp;Vector3&nbsp;v0,&nbsp;ref&nbsp;Vector3&nbsp;v1,&nbsp;ref&nbsp;Vector3&nbsp;v2)`](VRageMath.IntersectsTriangle)||
|[`bool&nbsp;Intersects(BoundingFrustum&nbsp;frustum)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a BoundingFrustum.|
|[`PlaneIntersectionType&nbsp;Intersects(Plane&nbsp;plane)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Plane.|
|[`void&nbsp;Intersects(ref&nbsp;Plane&nbsp;plane,&nbsp;ref&nbsp;PlaneIntersectionType&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Plane.|
|[`bool&nbsp;Intersects(Line&nbsp;line,&nbsp;ref&nbsp;float&nbsp;distance)`](VRageMath.Intersects)||
|[`Nullable<float>&nbsp;Intersects(Ray&nbsp;ray)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Ray.|
|[`void&nbsp;Intersects(ref&nbsp;Ray&nbsp;ray,&nbsp;ref&nbsp;Nullable<float>&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Ray.|
|[`bool&nbsp;Intersects(BoundingSphere&nbsp;sphere)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|[`void&nbsp;Intersects(ref&nbsp;BoundingSphere&nbsp;sphere,&nbsp;ref&nbsp;bool&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|[`bool&nbsp;Intersects(ref&nbsp;BoundingSphere&nbsp;sphere)`](VRageMath.Intersects)||
|[`bool&nbsp;Intersects(ref&nbsp;BoundingSphereD&nbsp;sphere)`](VRageMath.Intersects)||
|[`float&nbsp;Distance(Vector3&nbsp;point)`](VRageMath.Distance)||
|[`float&nbsp;DistanceSquared(Vector3&nbsp;point)`](VRageMath.DistanceSquared)||
|[`ContainmentType&nbsp;Contains(BoundingBox&nbsp;box)`](VRageMath.Contains)|Tests whether the BoundingBox contains another BoundingBox.|
|[`void&nbsp;Contains(ref&nbsp;BoundingBox&nbsp;box,&nbsp;ref&nbsp;ContainmentType&nbsp;result)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingBox.|
|[`ContainmentType&nbsp;Contains(BoundingFrustum&nbsp;frustum)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingFrustum.|
|[`ContainmentType&nbsp;Contains(Vector3&nbsp;point)`](VRageMath.Contains)|Tests whether the BoundingBox contains a point.|
|[`ContainmentType&nbsp;Contains(Vector3D&nbsp;point)`](VRageMath.Contains)||
|[`void&nbsp;Contains(ref&nbsp;Vector3&nbsp;point,&nbsp;ref&nbsp;ContainmentType&nbsp;result)`](VRageMath.Contains)|Tests whether the BoundingBox contains a point.|
|[`ContainmentType&nbsp;Contains(BoundingSphere&nbsp;sphere)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingSphere.|
|[`void&nbsp;Contains(ref&nbsp;BoundingSphere&nbsp;sphere,&nbsp;ref&nbsp;ContainmentType&nbsp;result)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingSphere.|
|[`BoundingBox&nbsp;Translate(Matrix&nbsp;worldMatrix)`](VRageMath.Translate)|Translate|
|[`BoundingBox&nbsp;Translate(Vector3&nbsp;vctTranlsation)`](VRageMath.Translate)|Translate|
|[`BoundingBox&nbsp;Transform(Matrix&nbsp;worldMatrix)`](VRageMath.Transform)||
|[`BoundingBoxD&nbsp;Transform(MatrixD&nbsp;worldMatrix)`](VRageMath.Transform)||
|[`BoundingBox&nbsp;Transform(ref&nbsp;Matrix&nbsp;m)`](VRageMath.Transform)||
|[`void&nbsp;Transform(ref&nbsp;Matrix&nbsp;m,&nbsp;ref&nbsp;BoundingBox&nbsp;bb)`](VRageMath.Transform)||
|[`BoundingBoxD&nbsp;Transform(ref&nbsp;MatrixD&nbsp;m)`](VRageMath.Transform)||
|[`void&nbsp;Transform(ref&nbsp;MatrixD&nbsp;m,&nbsp;ref&nbsp;BoundingBoxD&nbsp;bb)`](VRageMath.Transform)||
|[`BoundingBox&nbsp;Include(ref&nbsp;Vector3&nbsp;point)`](VRageMath.Include)|return expanded aabb (aabb include point)|
|[`BoundingBox&nbsp;GetIncluded(Vector3&nbsp;point)`](VRageMath.GetIncluded)||
|[`BoundingBox&nbsp;Include(Vector3&nbsp;point)`](VRageMath.Include)||
|[`BoundingBox&nbsp;Include(Vector3&nbsp;p0,&nbsp;Vector3&nbsp;p1,&nbsp;Vector3&nbsp;p2)`](VRageMath.Include)||
|[`BoundingBox&nbsp;Include(ref&nbsp;Vector3&nbsp;p0,&nbsp;ref&nbsp;Vector3&nbsp;p1,&nbsp;ref&nbsp;Vector3&nbsp;p2)`](VRageMath.Include)||
|[`BoundingBox&nbsp;Include(ref&nbsp;BoundingBox&nbsp;box)`](VRageMath.Include)|return expanded aabb (aabb include aabb)|
|[`BoundingBox&nbsp;Include(BoundingBox&nbsp;box)`](VRageMath.Include)||
|[`void&nbsp;Include(ref&nbsp;Line&nbsp;line)`](VRageMath.Include)||
|[`BoundingBox&nbsp;Include(BoundingSphere&nbsp;sphere)`](VRageMath.Include)||
|[`BoundingBox&nbsp;Include(ref&nbsp;BoundingSphere&nbsp;sphere)`](VRageMath.Include)||
|[`BoundingBox&nbsp;Include(ref&nbsp;BoundingFrustum&nbsp;frustum)`](VRageMath.Include)||
|static&nbsp;[`BoundingBox&nbsp;CreateInvalid()`](VRageMath.CreateInvalid)||
|[`float&nbsp;SurfaceArea()`](VRageMath.SurfaceArea)||
|[`float&nbsp;Volume()`](VRageMath.Volume)||
|[`float&nbsp;ProjectedArea(Vector3&nbsp;viewDir)`](VRageMath.ProjectedArea)||
|[`void&nbsp;Inflate(float&nbsp;size)`](VRageMath.Inflate)||
|[`void&nbsp;Inflate(Vector3&nbsp;size)`](VRageMath.Inflate)||
|[`void&nbsp;InflateToMinimum(Vector3&nbsp;minimumSize)`](VRageMath.InflateToMinimum)||
|[`void&nbsp;Scale(Vector3&nbsp;scale)`](VRageMath.Scale)||
