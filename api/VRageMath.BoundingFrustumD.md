← [Index](index)
# BoundingFrustumD Class
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Defines a frustum and helps determine whether forms intersect with it.
### Fields
|Member|Description|
|---|---|
|[`int CornerCount`](VRageMath.CornerCount)||
### Properties
|Member|Description|
|---|---|
|[`PlaneD Item`](VRageMath.Item)||
|[`PlaneD Near`](VRageMath.Near)||
|[`PlaneD Far`](VRageMath.Far)||
|[`PlaneD Left`](VRageMath.Left)||
|[`PlaneD Right`](VRageMath.Right)||
|[`PlaneD Top`](VRageMath.Top)||
|[`PlaneD Bottom`](VRageMath.Bottom)||
|[`MatrixD Matrix`](VRageMath.Matrix)||
### Methods
|Member|Description|
|---|---|
|[`Vector3D[] GetCorners()`](VRageMath.GetCorners)||
|[`void GetCorners(Vector3D[] corners)`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustumD.|
|[`void GetCornersUnsafe(*Vector3D corners)`](VRageMath.GetCornersUnsafe)||
|[`bool Equals(BoundingFrustumD other)`](VRageMath.Equals)|Determines whether the specified BoundingFrustumD is equal to the current BoundingFrustumD.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Determines whether the specified Object is equal to the BoundingFrustumD.|
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`string ToString()`](VRageMath.ToString)||
|[`bool Intersects(BoundingBoxD box)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects the specified BoundingBoxD.|
|[`void Intersects(ref BoundingBoxD box, ref bool result)`](VRageMath.Intersects)||
|[`bool Intersects(BoundingFrustumD frustum)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects the specified BoundingFrustumD.|
|[`PlaneIntersectionType Intersects(PlaneD plane)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects the specified Plane.|
|[`void Intersects(ref PlaneD plane, ref PlaneIntersectionType result)`](VRageMath.Intersects)||
|[`Nullable<double> Intersects(RayD ray)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects the specified Ray.|
|[`void Intersects(ref RayD ray, ref Nullable<double> result)`](VRageMath.Intersects)||
|[`bool Intersects(BoundingSphereD sphere)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects the specified BoundingSphere.|
|[`void Intersects(ref BoundingSphereD sphere, ref bool result)`](VRageMath.Intersects)||
|[`ContainmentType Contains(BoundingBoxD box)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingBoxD.|
|[`void Contains(ref BoundingBoxD box, ref ContainmentType result)`](VRageMath.Contains)||
|[`ContainmentType Contains(BoundingFrustumD frustum)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingFrustumD.|
|[`ContainmentType Contains(Vector3D point)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified point.|
|[`void Contains(ref Vector3D point, ref ContainmentType result)`](VRageMath.Contains)||
|[`ContainmentType Contains(BoundingSphereD sphere)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingSphere.|
|[`void Contains(ref BoundingSphereD sphere, ref ContainmentType result)`](VRageMath.Contains)||
