← [Index](index)
# Ray Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a ray.
### Fields
|Member|Description|
|---|---|
|[`VRageMath.Vector3 Position`](VRageMath.Position)|Specifies the starting point of the Ray.|
|[`VRageMath.Vector3 Direction`](VRageMath.Direction)|Unit vector specifying the direction the Ray is pointing.|
### Methods
|Member|Description|
|---|---|
|[`bool Equals(VRageMath.Ray)`](VRageMath.Equals)|Determines whether the specified Ray is equal to the current Ray.|
|[`bool Equals(System.Object)`](VRageMath.Equals)|Determines whether two instances of Ray are equal.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string ToString()`](VRageMath.ToString)|Returns a String that represents the current Ray.|
|[`Nullable<System.Single> Intersects(VRageMath.BoundingBox)`](VRageMath.Intersects)|Checks whether the Ray intersects a specified BoundingBox.|
|[`void Intersects(ref VRageMath.BoundingBox, ref Nullable<System.Single>)`](VRageMath.Intersects)|Checks whether the current Ray intersects a BoundingBox.|
|[`Nullable<System.Single> Intersects(VRageMath.BoundingFrustum)`](VRageMath.Intersects)|Checks whether the Ray intersects a specified BoundingFrustum.|
|[`Nullable<System.Single> Intersects(VRageMath.Plane)`](VRageMath.Intersects)|Determines whether this Ray intersects a specified Plane.|
|[`void Intersects(ref VRageMath.Plane, ref Nullable<System.Single>)`](VRageMath.Intersects)|Determines whether this Ray intersects a specified Plane.|
|[`Nullable<System.Single> Intersects(VRageMath.BoundingSphere)`](VRageMath.Intersects)|Checks whether the Ray intersects a specified BoundingSphere.|
|[`void Intersects(ref VRageMath.BoundingSphere, ref Nullable<System.Single>)`](VRageMath.Intersects)|Checks whether the current Ray intersects a BoundingSphere.|
