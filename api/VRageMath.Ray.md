← [Index](index)
# Ray Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a ray.
### Fields
|Member|Description|
|---|---|
|[`Vector3 Position`](VRageMath.Position)||
|[`Vector3 Direction`](VRageMath.Direction)||
### Methods
|Member|Description|
|---|---|
|[`bool Equals(Ray other)`](VRageMath.Equals)|Determines whether the specified Ray is equal to the current Ray.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Determines whether two instances of Ray are equal.|
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`string ToString()`](VRageMath.ToString)||
|[`Nullable<float> Intersects(BoundingBox box)`](VRageMath.Intersects)|Checks whether the Ray intersects a specified BoundingBox.|
|[`void Intersects(ref BoundingBox box, ref Nullable<float> result)`](VRageMath.Intersects)||
|[`Nullable<float> Intersects(BoundingFrustum frustum)`](VRageMath.Intersects)|Checks whether the Ray intersects a specified BoundingFrustum.|
|[`Nullable<float> Intersects(Plane plane)`](VRageMath.Intersects)|Determines whether this Ray intersects a specified Plane.|
|[`void Intersects(ref Plane plane, ref Nullable<float> result)`](VRageMath.Intersects)||
|[`Nullable<float> Intersects(BoundingSphere sphere)`](VRageMath.Intersects)|Checks whether the Ray intersects a specified BoundingSphere.|
|[`void Intersects(ref BoundingSphere sphere, ref Nullable<float> result)`](VRageMath.Intersects)||
