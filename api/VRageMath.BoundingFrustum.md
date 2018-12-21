← [Index](index.md)
# BoundingFrustum Class
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
|[`Plane[] Planes`](VRageMath.Planes.md)||
|[`Plane Item`](VRageMath.Item.md)||
|[`Plane Near`](VRageMath.Near.md)||
|[`Plane Far`](VRageMath.Far.md)||
|[`Plane Left`](VRageMath.Left.md)||
|[`Plane Right`](VRageMath.Right.md)||
|[`Plane Top`](VRageMath.Top.md)||
|[`Plane Bottom`](VRageMath.Bottom.md)||
|[`Matrix Matrix`](VRageMath.Matrix.md)||
### Methods
|Member|Description|
|---|---|
|[`Vector3[] GetCorners()`](VRageMath.GetCorners.md)||
|[`void GetCorners(Vector3[] corners)`](VRageMath.GetCorners.md)|Gets an array of points that make up the corners of the BoundingFrustum.|
|[`void GetCornersUnsafe(*Vector3 corners)`](VRageMath.GetCornersUnsafe.md)||
|[`bool Equals(BoundingFrustum other)`](VRageMath.Equals.md)|Determines whether the specified BoundingFrustum is equal to the current BoundingFrustum.|
|[`bool Equals(Object obj)`](VRageMath.Equals.md)|Determines whether the specified Object is equal to the BoundingFrustum.|
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`string ToString()`](VRageMath.ToString.md)||
|[`bool Intersects(BoundingBox box)`](VRageMath.Intersects.md)|Checks whether the current BoundingFrustum intersects the specified BoundingBox.|
|[`void Intersects(ref BoundingBox box, ref bool result)`](VRageMath.Intersects.md)||
|[`bool Intersects(BoundingFrustum frustum)`](VRageMath.Intersects.md)|Checks whether the current BoundingFrustum intersects the specified BoundingFrustum.|
|[`PlaneIntersectionType Intersects(Plane plane)`](VRageMath.Intersects.md)|Checks whether the current BoundingFrustum intersects the specified Plane.|
|[`void Intersects(ref Plane plane, ref PlaneIntersectionType result)`](VRageMath.Intersects.md)||
|[`Nullable<float> Intersects(Ray ray)`](VRageMath.Intersects.md)|Checks whether the current BoundingFrustum intersects the specified Ray.|
|[`void Intersects(ref Ray ray, ref Nullable<float> result)`](VRageMath.Intersects.md)||
|[`bool Intersects(BoundingSphere sphere)`](VRageMath.Intersects.md)|Checks whether the current BoundingFrustum intersects the specified BoundingSphere.|
|[`void Intersects(ref BoundingSphere sphere, ref bool result)`](VRageMath.Intersects.md)||
|[`ContainmentType Contains(ref BoundingBox box)`](VRageMath.Contains.md)||
|[`void Contains(ref BoundingBox box, ref ContainmentType result)`](VRageMath.Contains.md)||
|[`ContainmentType Contains(BoundingFrustum frustum)`](VRageMath.Contains.md)|Checks whether the current BoundingFrustum contains the specified BoundingFrustum.|
|[`ContainmentType Contains(Vector3 point)`](VRageMath.Contains.md)|Checks whether the current BoundingFrustum contains the specified point.|
|[`void Contains(ref Vector3 point, ref ContainmentType result)`](VRageMath.Contains.md)||
|[`ContainmentType Contains(BoundingSphere sphere)`](VRageMath.Contains.md)|Checks whether the current BoundingFrustum contains the specified BoundingSphere.|
|[`void Contains(ref BoundingSphere sphere, ref ContainmentType result)`](VRageMath.Contains.md)||
