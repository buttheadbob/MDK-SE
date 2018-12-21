← [Index](index.md)
# BoundingFrustumD Class
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Defines a frustum and helps determine whether forms intersect with it.
### Fields
|Member|Description|
|---|---|
|[`int CornerCount`](VRageMath.CornerCount.md)||
### Properties
|Member|Description|
|---|---|
|[`PlaneD Item`](VRageMath.Item.md)||
|[`PlaneD Near`](VRageMath.Near.md)||
|[`PlaneD Far`](VRageMath.Far.md)||
|[`PlaneD Left`](VRageMath.Left.md)||
|[`PlaneD Right`](VRageMath.Right.md)||
|[`PlaneD Top`](VRageMath.Top.md)||
|[`PlaneD Bottom`](VRageMath.Bottom.md)||
|[`MatrixD Matrix`](VRageMath.Matrix.md)||
### Methods
|Member|Description|
|---|---|
|[`Vector3D[] GetCorners()`](VRageMath.GetCorners.md)||
|[`void GetCorners(Vector3D[] corners)`](VRageMath.GetCorners.md)|Gets an array of points that make up the corners of the BoundingFrustumD.|
|[`void GetCornersUnsafe(*Vector3D corners)`](VRageMath.GetCornersUnsafe.md)||
|[`bool Equals(BoundingFrustumD other)`](VRageMath.Equals.md)|Determines whether the specified BoundingFrustumD is equal to the current BoundingFrustumD.|
|[`bool Equals(Object obj)`](VRageMath.Equals.md)|Determines whether the specified Object is equal to the BoundingFrustumD.|
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`string ToString()`](VRageMath.ToString.md)||
|[`bool Intersects(BoundingBoxD box)`](VRageMath.Intersects.md)|Checks whether the current BoundingFrustumD intersects the specified BoundingBoxD.|
|[`void Intersects(ref BoundingBoxD box, ref bool result)`](VRageMath.Intersects.md)||
|[`bool Intersects(BoundingFrustumD frustum)`](VRageMath.Intersects.md)|Checks whether the current BoundingFrustumD intersects the specified BoundingFrustumD.|
|[`PlaneIntersectionType Intersects(PlaneD plane)`](VRageMath.Intersects.md)|Checks whether the current BoundingFrustumD intersects the specified Plane.|
|[`void Intersects(ref PlaneD plane, ref PlaneIntersectionType result)`](VRageMath.Intersects.md)||
|[`Nullable<double> Intersects(RayD ray)`](VRageMath.Intersects.md)|Checks whether the current BoundingFrustumD intersects the specified Ray.|
|[`void Intersects(ref RayD ray, ref Nullable<double> result)`](VRageMath.Intersects.md)||
|[`bool Intersects(BoundingSphereD sphere)`](VRageMath.Intersects.md)|Checks whether the current BoundingFrustumD intersects the specified BoundingSphere.|
|[`void Intersects(ref BoundingSphereD sphere, ref bool result)`](VRageMath.Intersects.md)||
|[`ContainmentType Contains(BoundingBoxD box)`](VRageMath.Contains.md)|Checks whether the current BoundingFrustumD contains the specified BoundingBoxD.|
|[`void Contains(ref BoundingBoxD box, ref ContainmentType result)`](VRageMath.Contains.md)||
|[`ContainmentType Contains(BoundingFrustumD frustum)`](VRageMath.Contains.md)|Checks whether the current BoundingFrustumD contains the specified BoundingFrustumD.|
|[`ContainmentType Contains(Vector3D point)`](VRageMath.Contains.md)|Checks whether the current BoundingFrustumD contains the specified point.|
|[`void Contains(ref Vector3D point, ref ContainmentType result)`](VRageMath.Contains.md)||
|[`ContainmentType Contains(BoundingSphereD sphere)`](VRageMath.Contains.md)|Checks whether the current BoundingFrustumD contains the specified BoundingSphere.|
|[`void Contains(ref BoundingSphereD sphere, ref ContainmentType result)`](VRageMath.Contains.md)||
