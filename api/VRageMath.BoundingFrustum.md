← [Index](index)
# BoundingFrustum Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a frustum and helps determine whether forms intersect with it.
### Fields
|Member|Description|
|---|---|
|static [`CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingFrustum.|
### Properties
|Member|Description|
|---|---|
|[`Planes`](VRageMath.Planes)||
|[`Item`](VRageMath.Item)||
|[`Near`](VRageMath.Near)|Gets the near plane of the BoundingFrustum.|
|[`Far`](VRageMath.Far)|Gets the far plane of the BoundingFrustum.|
|[`Left`](VRageMath.Left)|Gets the left plane of the BoundingFrustum.|
|[`Right`](VRageMath.Right)|Gets the right plane of the BoundingFrustum.|
|[`Top`](VRageMath.Top)|Gets the top plane of the BoundingFrustum.|
|[`Bottom`](VRageMath.Bottom)|Gets the bottom plane of the BoundingFrustum.|
|[`Matrix`](VRageMath.Matrix)|Gets or sets the Matrix that describes this bounding frustum.|
### Methods
|Member|Description|
|---|---|
|[`GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustum. ALLOCATION!|
|[`GetCorners(Vector3[])`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustum.|
|[`GetCornersUnsafe(*Vector3)`](VRageMath.GetCornersUnsafe)||
|[`Equals(BoundingFrustum)`](VRageMath.Equals)|Determines whether the specified BoundingFrustum is equal to the current BoundingFrustum.|
|[`Equals(Object)`](VRageMath.Equals)|Determines whether the specified Object is equal to the BoundingFrustum.|
|[`GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingFrustum.|
|[`Intersects(BoundingBox)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects the specified BoundingBox.|
|[`Intersects(ref BoundingBox, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects a BoundingBox.|
|[`Intersects(BoundingFrustum)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects the specified BoundingFrustum.|
|[`Intersects(Plane)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects the specified Plane.|
|[`Intersects(ref Plane, ref PlaneIntersectionType)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects a Plane.|
|[`Intersects(Ray)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects the specified Ray.|
|[`Intersects(ref Ray, ref Nullable<float>)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects a Ray.|
|[`Intersects(BoundingSphere)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects the specified BoundingSphere.|
|[`Intersects(ref BoundingSphere, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects a BoundingSphere.|
|[`Contains(ref BoundingBox)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingBox.|
|[`Contains(ref BoundingBox, ref ContainmentType)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingBox.|
|[`Contains(BoundingFrustum)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingFrustum.|
|[`Contains(Vector3)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified point.|
|[`Contains(ref Vector3, ref ContainmentType)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified point.|
|[`Contains(BoundingSphere)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingSphere.|
|[`Contains(ref BoundingSphere, ref ContainmentType)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingSphere.|
