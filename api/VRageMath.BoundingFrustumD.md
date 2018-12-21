← [Index](index)
# BoundingFrustumD Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a frustum and helps determine whether forms intersect with it.
### Fields
|Member|Description|
|---|---|
|static [`int CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingFrustumD.|
### Properties
|Member|Description|
|---|---|
|[`PlaneD Item`](VRageMath.Item)||
|[`PlaneD Near`](VRageMath.Near)|Gets the near plane of the BoundingFrustumD.|
|[`PlaneD Far`](VRageMath.Far)|Gets the far plane of the BoundingFrustumD.|
|[`PlaneD Left`](VRageMath.Left)|Gets the left plane of the BoundingFrustumD.|
|[`PlaneD Right`](VRageMath.Right)|Gets the right plane of the BoundingFrustumD.|
|[`PlaneD Top`](VRageMath.Top)|Gets the top plane of the BoundingFrustumD.|
|[`PlaneD Bottom`](VRageMath.Bottom)|Gets the bottom plane of the BoundingFrustumD.|
|[`MatrixD Matrix`](VRageMath.Matrix)|Gets or sets the Matrix that describes this bounding frustum.|
### Methods
|Member|Description|
|---|---|
|[`Vector3D[] GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustumD. ALLOCATION!|
|[`void GetCorners(Vector3D[] corners)`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustumD.|
|[`void GetCornersUnsafe(*Vector3D corners)`](VRageMath.GetCornersUnsafe)||
|[`bool Equals(BoundingFrustumD other)`](VRageMath.Equals)|Determines whether the specified BoundingFrustumD is equal to the current BoundingFrustumD.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Determines whether the specified Object is equal to the BoundingFrustumD.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingFrustumD.|
|[`bool Intersects(BoundingBoxD box)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects the specified BoundingBoxD.|
|[`void Intersects(ref BoundingBoxD box, ref bool result)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects a BoundingBoxD.|
|[`bool Intersects(BoundingFrustumD frustum)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects the specified BoundingFrustumD.|
|[`PlaneIntersectionType Intersects(PlaneD plane)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects the specified Plane.|
|[`void Intersects(ref PlaneD plane, ref PlaneIntersectionType result)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects a Plane.|
|[`Nullable<double> Intersects(RayD ray)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects the specified Ray.|
|[`void Intersects(ref RayD ray, ref Nullable<double> result)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects a Ray.|
|[`bool Intersects(BoundingSphereD sphere)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects the specified BoundingSphere.|
|[`void Intersects(ref BoundingSphereD sphere, ref bool result)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects a BoundingSphere.|
|[`ContainmentType Contains(BoundingBoxD box)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingBoxD.|
|[`void Contains(ref BoundingBoxD box, ref ContainmentType result)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingBoxD.|
|[`ContainmentType Contains(BoundingFrustumD frustum)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingFrustumD.|
|[`ContainmentType Contains(Vector3D point)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified point.|
|[`void Contains(ref Vector3D point, ref ContainmentType result)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified point.|
|[`ContainmentType Contains(BoundingSphereD sphere)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingSphere.|
|[`void Contains(ref BoundingSphereD sphere, ref ContainmentType result)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingSphere.|
