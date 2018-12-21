← [Index](index)
# BoundingFrustum Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a frustum and helps determine whether forms intersect with it.
### Fields
|Member|Description|
|---|---|
|static [`int CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingFrustum.|
### Properties
|Member|Description|
|---|---|
|[`Plane[] Planes`](VRageMath.Planes)||
|[`Plane Item`](VRageMath.Item)||
|[`Plane Near`](VRageMath.Near)|Gets the near plane of the BoundingFrustum.|
|[`Plane Far`](VRageMath.Far)|Gets the far plane of the BoundingFrustum.|
|[`Plane Left`](VRageMath.Left)|Gets the left plane of the BoundingFrustum.|
|[`Plane Right`](VRageMath.Right)|Gets the right plane of the BoundingFrustum.|
|[`Plane Top`](VRageMath.Top)|Gets the top plane of the BoundingFrustum.|
|[`Plane Bottom`](VRageMath.Bottom)|Gets the bottom plane of the BoundingFrustum.|
|[`Matrix Matrix`](VRageMath.Matrix)|Gets or sets the Matrix that describes this bounding frustum.|
### Methods
|Member|Description|
|---|---|
|[`Vector3[] GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustum. ALLOCATION!|
|[`void GetCorners(Vector3[] corners)`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustum.|
|[`void GetCornersUnsafe(*Vector3 corners)`](VRageMath.GetCornersUnsafe)||
|[`bool Equals(BoundingFrustum other)`](VRageMath.Equals)|Determines whether the specified BoundingFrustum is equal to the current BoundingFrustum.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Determines whether the specified Object is equal to the BoundingFrustum.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingFrustum.|
|[`bool Intersects(BoundingBox box)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects the specified BoundingBox.|
|[`void Intersects(ref BoundingBox box, ref bool result)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects a BoundingBox.|
|[`bool Intersects(BoundingFrustum frustum)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects the specified BoundingFrustum.|
|[`PlaneIntersectionType Intersects(Plane plane)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects the specified Plane.|
|[`void Intersects(ref Plane plane, ref PlaneIntersectionType result)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects a Plane.|
|[`Nullable<float> Intersects(Ray ray)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects the specified Ray.|
|[`void Intersects(ref Ray ray, ref Nullable<float> result)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects a Ray.|
|[`bool Intersects(BoundingSphere sphere)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects the specified BoundingSphere.|
|[`void Intersects(ref BoundingSphere sphere, ref bool result)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects a BoundingSphere.|
|[`ContainmentType Contains(ref BoundingBox box)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingBox.|
|[`void Contains(ref BoundingBox box, ref ContainmentType result)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingBox.|
|[`ContainmentType Contains(BoundingFrustum frustum)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingFrustum.|
|[`ContainmentType Contains(Vector3 point)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified point.|
|[`void Contains(ref Vector3 point, ref ContainmentType result)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified point.|
|[`ContainmentType Contains(BoundingSphere sphere)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingSphere.|
|[`void Contains(ref BoundingSphere sphere, ref ContainmentType result)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingSphere.|
