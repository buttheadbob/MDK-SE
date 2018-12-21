← [Index](index)
# RayD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a ray.
### Fields
|Member|Description|
|---|---|
|[`Vector3D Position`](VRageMath.Position)||
|[`Vector3D Direction`](VRageMath.Direction)||
### Methods
|Member|Description|
|---|---|
|[`bool Equals(RayD other)`](VRageMath.Equals)|Determines whether the specified Ray is equal to the current Ray.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Determines whether two instances of Ray are equal.|
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`string ToString()`](VRageMath.ToString)||
|[`Nullable<double> Intersects(BoundingBoxD box)`](VRageMath.Intersects)|Checks whether the Ray intersects a specified BoundingBox.|
|[`void Intersects(ref BoundingBoxD box, ref Nullable<double> result)`](VRageMath.Intersects)||
|[`Nullable<double> Intersects(BoundingFrustumD frustum)`](VRageMath.Intersects)|Checks whether the Ray intersects a specified BoundingFrustum.|
|[`Nullable<double> Intersects(PlaneD plane)`](VRageMath.Intersects)|Determines whether this Ray intersects a specified Plane.|
|[`void Intersects(ref PlaneD plane, ref Nullable<double> result)`](VRageMath.Intersects)||
|[`Nullable<double> Intersects(BoundingSphereD sphere)`](VRageMath.Intersects)|Checks whether the Ray intersects a specified BoundingSphere.|
|[`void Intersects(ref BoundingSphere sphere, ref Nullable<double> result)`](VRageMath.Intersects)||
