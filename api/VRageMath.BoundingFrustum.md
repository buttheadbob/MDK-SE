← [Index](index)
# BoundingFrustum Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a frustum and helps determine whether forms intersect with it.
### Fields
|Member|Description|
|---|---|
|static&nbsp;[`int&nbsp;CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingFrustum.|
### Properties
|Member|Description|
|---|---|
|[`Plane[]&nbsp;Planes`](VRageMath.Planes)||
|[`Plane&nbsp;Item`](VRageMath.Item)||
|[`Plane&nbsp;Near`](VRageMath.Near)|Gets the near plane of the BoundingFrustum.|
|[`Plane&nbsp;Far`](VRageMath.Far)|Gets the far plane of the BoundingFrustum.|
|[`Plane&nbsp;Left`](VRageMath.Left)|Gets the left plane of the BoundingFrustum.|
|[`Plane&nbsp;Right`](VRageMath.Right)|Gets the right plane of the BoundingFrustum.|
|[`Plane&nbsp;Top`](VRageMath.Top)|Gets the top plane of the BoundingFrustum.|
|[`Plane&nbsp;Bottom`](VRageMath.Bottom)|Gets the bottom plane of the BoundingFrustum.|
|[`Matrix&nbsp;Matrix`](VRageMath.Matrix)|Gets or sets the Matrix that describes this bounding frustum.|
### Methods
|Member|Description|
|---|---|
|[`Vector3[]&nbsp;GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustum. ALLOCATION!|
|[`void&nbsp;GetCorners(Vector3[]&nbsp;corners)`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustum.|
|[`void&nbsp;GetCornersUnsafe(*Vector3&nbsp;corners)`](VRageMath.GetCornersUnsafe)||
|[`bool&nbsp;Equals(BoundingFrustum&nbsp;other)`](VRageMath.Equals)|Determines whether the specified BoundingFrustum is equal to the current BoundingFrustum.|
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Determines whether the specified Object is equal to the BoundingFrustum.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string&nbsp;ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingFrustum.|
|[`bool&nbsp;Intersects(BoundingBox&nbsp;box)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects the specified BoundingBox.|
|[`void&nbsp;Intersects(ref&nbsp;BoundingBox&nbsp;box,&nbsp;ref&nbsp;bool&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects a BoundingBox.|
|[`bool&nbsp;Intersects(BoundingFrustum&nbsp;frustum)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects the specified BoundingFrustum.|
|[`PlaneIntersectionType&nbsp;Intersects(Plane&nbsp;plane)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects the specified Plane.|
|[`void&nbsp;Intersects(ref&nbsp;Plane&nbsp;plane,&nbsp;ref&nbsp;PlaneIntersectionType&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects a Plane.|
|[`Nullable<float>&nbsp;Intersects(Ray&nbsp;ray)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects the specified Ray.|
|[`void&nbsp;Intersects(ref&nbsp;Ray&nbsp;ray,&nbsp;ref&nbsp;Nullable<float>&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects a Ray.|
|[`bool&nbsp;Intersects(BoundingSphere&nbsp;sphere)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects the specified BoundingSphere.|
|[`void&nbsp;Intersects(ref&nbsp;BoundingSphere&nbsp;sphere,&nbsp;ref&nbsp;bool&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingFrustum intersects a BoundingSphere.|
|[`ContainmentType&nbsp;Contains(ref&nbsp;BoundingBox&nbsp;box)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingBox.|
|[`void&nbsp;Contains(ref&nbsp;BoundingBox&nbsp;box,&nbsp;ref&nbsp;ContainmentType&nbsp;result)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingBox.|
|[`ContainmentType&nbsp;Contains(BoundingFrustum&nbsp;frustum)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingFrustum.|
|[`ContainmentType&nbsp;Contains(Vector3&nbsp;point)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified point.|
|[`void&nbsp;Contains(ref&nbsp;Vector3&nbsp;point,&nbsp;ref&nbsp;ContainmentType&nbsp;result)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified point.|
|[`ContainmentType&nbsp;Contains(BoundingSphere&nbsp;sphere)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingSphere.|
|[`void&nbsp;Contains(ref&nbsp;BoundingSphere&nbsp;sphere,&nbsp;ref&nbsp;ContainmentType&nbsp;result)`](VRageMath.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingSphere.|
