← [Index](index.md)
#Ray Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
##Summary
Defines a ray.
###Fields
|Member|Description|
|---|---|
|[`Vector3 Position`](VRageMath.Position.md)||
|[`Vector3 Direction`](VRageMath.Direction.md)||
###Methods
|Member|Description|
|---|---|
|[`bool Equals(Ray other)`](VRageMath.Equals.md)|Determines whether the specified Ray is equal to the current Ray.|
|[`bool Equals(Object obj)`](VRageMath.Equals.md)|Determines whether two instances of Ray are equal.|
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`string ToString()`](VRageMath.ToString.md)||
|[`Nullable<float> Intersects(BoundingBox box)`](VRageMath.Intersects.md)|Checks whether the Ray intersects a specified BoundingBox.|
|[`void Intersects(ref BoundingBox box, ref Nullable<float> result)`](VRageMath.Intersects.md)||
|[`Nullable<float> Intersects(BoundingFrustum frustum)`](VRageMath.Intersects.md)|Checks whether the Ray intersects a specified BoundingFrustum.|
|[`Nullable<float> Intersects(Plane plane)`](VRageMath.Intersects.md)|Determines whether this Ray intersects a specified Plane.|
|[`void Intersects(ref Plane plane, ref Nullable<float> result)`](VRageMath.Intersects.md)||
|[`Nullable<float> Intersects(BoundingSphere sphere)`](VRageMath.Intersects.md)|Checks whether the Ray intersects a specified BoundingSphere.|
|[`void Intersects(ref BoundingSphere sphere, ref Nullable<float> result)`](VRageMath.Intersects.md)||
