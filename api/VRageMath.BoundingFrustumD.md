← [Index](index)
# BoundingFrustumD Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a frustum and helps determine whether forms intersect with it.
### Fields
|Member|Description|
|---|---|
|static&nbsp;[`int&nbsp;CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingFrustumD.|
### Properties
|Member|Description|
|---|---|
|[`PlaneD&nbsp;Item`](VRageMath.Item)||
|[`PlaneD&nbsp;Near`](VRageMath.Near)|Gets the near plane of the BoundingFrustumD.|
|[`PlaneD&nbsp;Far`](VRageMath.Far)|Gets the far plane of the BoundingFrustumD.|
|[`PlaneD&nbsp;Left`](VRageMath.Left)|Gets the left plane of the BoundingFrustumD.|
|[`PlaneD&nbsp;Right`](VRageMath.Right)|Gets the right plane of the BoundingFrustumD.|
|[`PlaneD&nbsp;Top`](VRageMath.Top)|Gets the top plane of the BoundingFrustumD.|
|[`PlaneD&nbsp;Bottom`](VRageMath.Bottom)|Gets the bottom plane of the BoundingFrustumD.|
|[`MatrixD&nbsp;Matrix`](VRageMath.Matrix)|Gets or sets the Matrix that describes this bounding frustum.|
### Methods
|Member|Description|
|---|---|
|[`Vector3D[]&nbsp;GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustumD. ALLOCATION!|
|[`void&nbsp;GetCorners(Vector3D[]&nbsp;corners)`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustumD.|
|[`void&nbsp;GetCornersUnsafe(*Vector3D&nbsp;corners)`](VRageMath.GetCornersUnsafe)||
|[`bool&nbsp;Equals(BoundingFrustumD&nbsp;other)`](VRageMath.Equals)|Determines whether the specified BoundingFrustumD is equal to the current BoundingFrustumD.|
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Determines whether the specified Object is equal to the BoundingFrustumD.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string&nbsp;ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingFrustumD.|
|[`bool&nbsp;Intersects(BoundingBoxD&nbsp;box)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects the specified BoundingBoxD.|
|[`void&nbsp;Intersects(ref&nbsp;BoundingBoxD&nbsp;box,&nbsp;ref&nbsp;bool&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects a BoundingBoxD.|
|[`bool&nbsp;Intersects(BoundingFrustumD&nbsp;frustum)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects the specified BoundingFrustumD.|
|[`PlaneIntersectionType&nbsp;Intersects(PlaneD&nbsp;plane)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects the specified Plane.|
|[`void&nbsp;Intersects(ref&nbsp;PlaneD&nbsp;plane,&nbsp;ref&nbsp;PlaneIntersectionType&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects a Plane.|
|[`Nullable<double>&nbsp;Intersects(RayD&nbsp;ray)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects the specified Ray.|
|[`void&nbsp;Intersects(ref&nbsp;RayD&nbsp;ray,&nbsp;ref&nbsp;Nullable<double>&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects a Ray.|
|[`bool&nbsp;Intersects(BoundingSphereD&nbsp;sphere)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects the specified BoundingSphere.|
|[`void&nbsp;Intersects(ref&nbsp;BoundingSphereD&nbsp;sphere,&nbsp;ref&nbsp;bool&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects a BoundingSphere.|
|[`ContainmentType&nbsp;Contains(BoundingBoxD&nbsp;box)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingBoxD.|
|[`void&nbsp;Contains(ref&nbsp;BoundingBoxD&nbsp;box,&nbsp;ref&nbsp;ContainmentType&nbsp;result)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingBoxD.|
|[`ContainmentType&nbsp;Contains(BoundingFrustumD&nbsp;frustum)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingFrustumD.|
|[`ContainmentType&nbsp;Contains(Vector3D&nbsp;point)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified point.|
|[`void&nbsp;Contains(ref&nbsp;Vector3D&nbsp;point,&nbsp;ref&nbsp;ContainmentType&nbsp;result)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified point.|
|[`ContainmentType&nbsp;Contains(BoundingSphereD&nbsp;sphere)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingSphere.|
|[`void&nbsp;Contains(ref&nbsp;BoundingSphereD&nbsp;sphere,&nbsp;ref&nbsp;ContainmentType&nbsp;result)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingSphere.|
