← [Index](index)
# BoundingFrustum Class
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
|[`Plane[] Planes`](VRageMath.Planes)||
|[`Plane Item`](VRageMath.Item)||
|[`Plane Near`](VRageMath.Near)||
|[`Plane Far`](VRageMath.Far)||
|[`Plane Left`](VRageMath.Left)||
|[`Plane Right`](VRageMath.Right)||
|[`Plane Top`](VRageMath.Top)||
|[`Plane Bottom`](VRageMath.Bottom)||
|[`Matrix Matrix`](VRageMath.Matrix)||
### Methods
|Member|Description|
|---|---|
|[`Vector3[] GetCorners()`](VRageMath.GetCorners)||
|[`void GetCorners(Vector3[] corners)`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustum.|
|[`void GetCornersUnsafe(*Vector3 corners)`](VRageMath.GetCornersUnsafe)||
|[`bool Equals(BoundingFrustum other)`](VRageMath.Equals)|Determines whether the specified BoundingFrustum is equal to the current BoundingFrustum.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Determines whether the specified Object is equal to the BoundingFrustum.|
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`string ToString()`](VRageMath.ToString)||
|[`bool Intersects(BoundingBox box)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects the specified BoundingBox.|
|[`void Intersects(ref BoundingBox box, ref bool result)`](VRageMath.Intersects)||
|[`bool Intersects(BoundingFrustum frustum)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects the specified BoundingFrustum.|
|[`PlaneIntersectionType Intersects(Plane plane)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects the specified Plane.|
|[`void Intersects(ref Plane plane, ref PlaneIntersectionType result)`](VRageMath.Intersects)||
|[`Nullable<float> Intersects(Ray ray)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects the specified Ray.|
|[`void Intersects(ref Ray ray, ref Nullable<float> result)`](VRageMath.Intersects)||
|[`bool Intersects(BoundingSphere sphere)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects the specified BoundingSphere.|
|[`void Intersects(ref BoundingSphere sphere, ref bool result)`](VRageMath.Intersects)||
|[`ContainmentType Contains(ref BoundingBox box)`](VRageMath.Contains)||
|[`void Contains(ref BoundingBox box, ref ContainmentType result)`](VRageMath.Contains)||
|[`ContainmentType Contains(BoundingFrustum frustum)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingFrustum.|
|[`ContainmentType Contains(Vector3 point)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified point.|
|[`void Contains(ref Vector3 point, ref ContainmentType result)`](VRageMath.Contains)||
|[`ContainmentType Contains(BoundingSphere sphere)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingSphere.|
|[`void Contains(ref BoundingSphere sphere, ref ContainmentType result)`](VRageMath.Contains)||
