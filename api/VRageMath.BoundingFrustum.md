← [Index](index)
# BoundingFrustum Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a frustum and helps determine whether forms intersect with it.
### Fields
|Member|Description|
|---|---|
|static [`int CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingFrustum.|
### Properties
|Member|Description|
|---|---|
|[`VRageMath.Plane[] Planes`](VRageMath.Planes)||
|[`VRageMath.Plane Item`](VRageMath.Item)||
|[`VRageMath.Plane Near`](VRageMath.Near)|Gets the near plane of the BoundingFrustum.|
|[`VRageMath.Plane Far`](VRageMath.Far)|Gets the far plane of the BoundingFrustum.|
|[`VRageMath.Plane Left`](VRageMath.Left)|Gets the left plane of the BoundingFrustum.|
|[`VRageMath.Plane Right`](VRageMath.Right)|Gets the right plane of the BoundingFrustum.|
|[`VRageMath.Plane Top`](VRageMath.Top)|Gets the top plane of the BoundingFrustum.|
|[`VRageMath.Plane Bottom`](VRageMath.Bottom)|Gets the bottom plane of the BoundingFrustum.|
|[`VRageMath.Matrix Matrix`](VRageMath.Matrix)|Gets or sets the Matrix that describes this bounding frustum.|
### Methods
|Member|Description|
|---|---|
|[`VRageMath.Vector3[] GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustum. ALLOCATION!|
|[`void GetCorners(VRageMath.Vector3[])`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustum.|
|[`void GetCornersUnsafe(*VRageMath.Vector3)`](VRageMath.GetCornersUnsafe)||
|[`bool Equals(VRageMath.BoundingFrustum)`](VRageMath.Equals)|Determines whether the specified BoundingFrustum is equal to the current BoundingFrustum.|
|[`bool Equals(System.Object)`](VRageMath.Equals)|Determines whether the specified Object is equal to the BoundingFrustum.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingFrustum.|
|[`bool Intersects(VRageMath.BoundingBox)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects the specified BoundingBox.|
|[`void Intersects(ref VRageMath.BoundingBox, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects a BoundingBox.|
|[`bool Intersects(VRageMath.BoundingFrustum)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects the specified BoundingFrustum.|
|[`VRageMath.PlaneIntersectionType Intersects(VRageMath.Plane)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects the specified Plane.|
|[`void Intersects(ref VRageMath.Plane, ref VRageMath.PlaneIntersectionType)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects a Plane.|
|[`Nullable<System.Single> Intersects(VRageMath.Ray)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects the specified Ray.|
|[`void Intersects(ref VRageMath.Ray, ref Nullable<System.Single>)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects a Ray.|
|[`bool Intersects(VRageMath.BoundingSphere)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects the specified BoundingSphere.|
|[`void Intersects(ref VRageMath.BoundingSphere, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects a BoundingSphere.|
|[`VRageMath.ContainmentType Contains(ref VRageMath.BoundingBox)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingBox.|
|[`void Contains(ref VRageMath.BoundingBox, ref VRageMath.ContainmentType)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingBox.|
|[`VRageMath.ContainmentType Contains(VRageMath.BoundingFrustum)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingFrustum.|
|[`VRageMath.ContainmentType Contains(VRageMath.Vector3)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified point.|
|[`void Contains(ref VRageMath.Vector3, ref VRageMath.ContainmentType)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified point.|
|[`VRageMath.ContainmentType Contains(VRageMath.BoundingSphere)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingSphere.|
|[`void Contains(ref VRageMath.BoundingSphere, ref VRageMath.ContainmentType)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingSphere.|
