← [Index](index)
# RayD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a ray.
### Fields
|Member|Description|
|---|---|
|[`Vector3D Position`](VRageMath.Position)|Specifies the starting point of the Ray.|
|[`Vector3D Direction`](VRageMath.Direction)|Unit vector specifying the direction the Ray is pointing.|
### Methods
|Member|Description|
|---|---|
|[`bool Equals(RayD other)`](VRageMath.Equals)|Determines whether the specified Ray is equal to the current Ray.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Determines whether two instances of Ray are equal.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string ToString()`](VRageMath.ToString)|Returns a String that represents the current Ray.|
|[`Nullable<double> Intersects(BoundingBoxD box)`](VRageMath.Intersects)|Checks whether the Ray intersects a specified BoundingBox.|
|[`void Intersects(ref BoundingBoxD box, ref Nullable<double> result)`](VRageMath.Intersects)|Checks whether the current Ray intersects a BoundingBox.|
|[`Nullable<double> Intersects(BoundingFrustumD frustum)`](VRageMath.Intersects)|Checks whether the Ray intersects a specified BoundingFrustum.|
|[`Nullable<double> Intersects(PlaneD plane)`](VRageMath.Intersects)|Determines whether this Ray intersects a specified Plane.|
|[`void Intersects(ref PlaneD plane, ref Nullable<double> result)`](VRageMath.Intersects)|Determines whether this Ray intersects a specified Plane.|
|[`Nullable<double> Intersects(BoundingSphereD sphere)`](VRageMath.Intersects)|Checks whether the Ray intersects a specified BoundingSphere.|
|[`void Intersects(ref BoundingSphere sphere, ref Nullable<double> result)`](VRageMath.Intersects)|Checks whether the current Ray intersects a BoundingSphere.|
