← [Index](index)
# RayD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a ray.
### Fields
|Member|Description|
|---|---|
|[`Vector3D&nbsp;Position`](VRageMath.Position)|Specifies the starting point of the Ray.|
|[`Vector3D&nbsp;Direction`](VRageMath.Direction)|Unit vector specifying the direction the Ray is pointing.|
### Methods
|Member|Description|
|---|---|
|[`bool&nbsp;Equals(RayD&nbsp;other)`](VRageMath.Equals)|Determines whether the specified Ray is equal to the current Ray.|
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Determines whether two instances of Ray are equal.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string&nbsp;ToString()`](VRageMath.ToString)|Returns a String that represents the current Ray.|
|[`Nullable<double>&nbsp;Intersects(BoundingBoxD&nbsp;box)`](VRageMath.Intersects)|Checks whether the Ray intersects a specified BoundingBox.|
|[`void&nbsp;Intersects(ref&nbsp;BoundingBoxD&nbsp;box,&nbsp;ref&nbsp;Nullable<double>&nbsp;result)`](VRageMath.Intersects)|Checks whether the current Ray intersects a BoundingBox.|
|[`Nullable<double>&nbsp;Intersects(BoundingFrustumD&nbsp;frustum)`](VRageMath.Intersects)|Checks whether the Ray intersects a specified BoundingFrustum.|
|[`Nullable<double>&nbsp;Intersects(PlaneD&nbsp;plane)`](VRageMath.Intersects)|Determines whether this Ray intersects a specified Plane.|
|[`void&nbsp;Intersects(ref&nbsp;PlaneD&nbsp;plane,&nbsp;ref&nbsp;Nullable<double>&nbsp;result)`](VRageMath.Intersects)|Determines whether this Ray intersects a specified Plane.|
|[`Nullable<double>&nbsp;Intersects(BoundingSphereD&nbsp;sphere)`](VRageMath.Intersects)|Checks whether the Ray intersects a specified BoundingSphere.|
|[`void&nbsp;Intersects(ref&nbsp;BoundingSphere&nbsp;sphere,&nbsp;ref&nbsp;Nullable<double>&nbsp;result)`](VRageMath.Intersects)|Checks whether the current Ray intersects a BoundingSphere.|
