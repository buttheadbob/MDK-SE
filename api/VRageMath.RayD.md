← [Index](index.md)
# RayD Struct
** Namespace: ** VRageMath  
** Assembly: ** VRage.Math.dll  
## Summary
Defines a ray.
### Fields
|Member|Description|
|---|---|
|[`Vector3D Position`](VRageMath.Position.md)||
|[`Vector3D Direction`](VRageMath.Direction.md)||
### Methods
|Member|Description|
|---|---|
|[`bool Equals(RayD other)`](VRageMath.Equals.md)|Determines whether the specified Ray is equal to the current Ray.|
|[`bool Equals(Object obj)`](VRageMath.Equals.md)|Determines whether two instances of Ray are equal.|
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`string ToString()`](VRageMath.ToString.md)||
|[`Nullable<double> Intersects(BoundingBoxD box)`](VRageMath.Intersects.md)|Checks whether the Ray intersects a specified BoundingBox.|
|[`void Intersects(ref BoundingBoxD box, ref Nullable<double> result)`](VRageMath.Intersects.md)||
|[`Nullable<double> Intersects(BoundingFrustumD frustum)`](VRageMath.Intersects.md)|Checks whether the Ray intersects a specified BoundingFrustum.|
|[`Nullable<double> Intersects(PlaneD plane)`](VRageMath.Intersects.md)|Determines whether this Ray intersects a specified Plane.|
|[`void Intersects(ref PlaneD plane, ref Nullable<double> result)`](VRageMath.Intersects.md)||
|[`Nullable<double> Intersects(BoundingSphereD sphere)`](VRageMath.Intersects.md)|Checks whether the Ray intersects a specified BoundingSphere.|
|[`void Intersects(ref BoundingSphere sphere, ref Nullable<double> result)`](VRageMath.Intersects.md)||
