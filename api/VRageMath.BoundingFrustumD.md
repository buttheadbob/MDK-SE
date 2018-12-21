← [Index](ApiIndex)
# BoundingFrustumD Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a frustum and helps determine whether forms intersect with it.
### Fields
|Member|Description|
|---|---|
|[`CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingFrustumD.|
### Properties
|Member|Description|
|---|---|
|[`Item`](VRageMath.Item)||
|[`Near`](VRageMath.Near)|Gets the near plane of the BoundingFrustumD.|
|[`Far`](VRageMath.Far)|Gets the far plane of the BoundingFrustumD.|
|[`Left`](VRageMath.Left)|Gets the left plane of the BoundingFrustumD.|
|[`Right`](VRageMath.Right)|Gets the right plane of the BoundingFrustumD.|
|[`Top`](VRageMath.Top)|Gets the top plane of the BoundingFrustumD.|
|[`Bottom`](VRageMath.Bottom)|Gets the bottom plane of the BoundingFrustumD.|
|[`Matrix`](VRageMath.Matrix)|Gets or sets the Matrix that describes this bounding frustum.|
### Methods
|Member|Description|
|---|---|
|[`GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustumD. ALLOCATION!|
|[`GetCorners(Vector3D[])`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustumD.|
|[`GetCornersUnsafe(*Vector3D)`](VRageMath.GetCornersUnsafe)||
|[`Equals(BoundingFrustumD)`](VRageMath.Equals)|Determines whether the specified BoundingFrustumD is equal to the current BoundingFrustumD.|
|[`Equals(Object)`](VRageMath.Equals)|Determines whether the specified Object is equal to the BoundingFrustumD.|
|[`GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingFrustumD.|
|[`Intersects(BoundingBoxD)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects the specified BoundingBoxD.|
|[`Intersects(ref BoundingBoxD, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects a BoundingBoxD.|
|[`Intersects(BoundingFrustumD)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects the specified BoundingFrustumD.|
|[`Intersects(PlaneD)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects the specified Plane.|
|[`Intersects(ref PlaneD, ref PlaneIntersectionType)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects a Plane.|
|[`Intersects(RayD)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects the specified Ray.|
|[`Intersects(ref RayD, ref Nullable<double>)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects a Ray.|
|[`Intersects(BoundingSphereD)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects the specified BoundingSphere.|
|[`Intersects(ref BoundingSphereD, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects a BoundingSphere.|
|[`Contains(BoundingBoxD)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingBoxD.|
|[`Contains(ref BoundingBoxD, ref ContainmentType)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingBoxD.|
|[`Contains(BoundingFrustumD)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingFrustumD.|
|[`Contains(Vector3D)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified point.|
|[`Contains(ref Vector3D, ref ContainmentType)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified point.|
|[`Contains(BoundingSphereD)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingSphere.|
|[`Contains(ref BoundingSphereD, ref ContainmentType)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingSphere.|
