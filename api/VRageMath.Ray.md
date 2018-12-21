← [Index](index)
# Ray Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a ray.
### Fields
|Member|Description|
|---|---|
|[`Vector3&nbsp;Position`](VRageMath.Position)|Specifies the starting point of the Ray.|
|[`Vector3&nbsp;Direction`](VRageMath.Direction)|Unit vector specifying the direction the Ray is pointing.|
### Methods
|Member|Description|
|---|---|
|[`bool&nbsp;Equals(Ray&nbsp;other)`](VRageMath.Equals)|Determines whether the specified Ray is equal to the current Ray.|
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Determines whether two instances of Ray are equal.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string&nbsp;ToString()`](VRageMath.ToString)|Returns a String that represents the current Ray.|
|[`Nullable<float>&nbsp;Intersects(BoundingBox&nbsp;box)`](VRageMath.Intersects)|Checks whether the Ray intersects a specified BoundingBox.|
|[`void&nbsp;Intersects(ref&nbsp;BoundingBox&nbsp;box,&nbsp;ref&nbsp;Nullable<float>&nbsp;result)`](VRageMath.Intersects)|Checks whether the current Ray intersects a BoundingBox.|
|[`Nullable<float>&nbsp;Intersects(BoundingFrustum&nbsp;frustum)`](VRageMath.Intersects)|Checks whether the Ray intersects a specified BoundingFrustum.|
|[`Nullable<float>&nbsp;Intersects(Plane&nbsp;plane)`](VRageMath.Intersects)|Determines whether this Ray intersects a specified Plane.|
|[`void&nbsp;Intersects(ref&nbsp;Plane&nbsp;plane,&nbsp;ref&nbsp;Nullable<float>&nbsp;result)`](VRageMath.Intersects)|Determines whether this Ray intersects a specified Plane.|
|[`Nullable<float>&nbsp;Intersects(BoundingSphere&nbsp;sphere)`](VRageMath.Intersects)|Checks whether the Ray intersects a specified BoundingSphere.|
|[`void&nbsp;Intersects(ref&nbsp;BoundingSphere&nbsp;sphere,&nbsp;ref&nbsp;Nullable<float>&nbsp;result)`](VRageMath.Intersects)|Checks whether the current Ray intersects a BoundingSphere.|
