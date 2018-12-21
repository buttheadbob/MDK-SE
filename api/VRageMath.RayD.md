← [Index](index)
# RayD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a ray.
### Fields
|Member|Description|
|---|---|
|[`VRageMath.Vector3D Position`](VRageMath.Position)|Specifies the starting point of the Ray.|
|[`VRageMath.Vector3D Direction`](VRageMath.Direction)|Unit vector specifying the direction the Ray is pointing.|
### Methods
|Member|Description|
|---|---|
|[`bool Equals(VRageMath.RayD)`](VRageMath.Equals)|Determines whether the specified Ray is equal to the current Ray.|
|[`bool Equals(System.Object)`](VRageMath.Equals)|Determines whether two instances of Ray are equal.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string ToString()`](VRageMath.ToString)|Returns a String that represents the current Ray.|
|[`Nullable<System.Double> Intersects(VRageMath.BoundingBoxD)`](VRageMath.Intersects)|Checks whether the Ray intersects a specified BoundingBox.|
|[`void Intersects(ref VRageMath.BoundingBoxD, ref Nullable<System.Double>)`](VRageMath.Intersects)|Checks whether the current Ray intersects a BoundingBox.|
|[`Nullable<System.Double> Intersects(VRageMath.BoundingFrustumD)`](VRageMath.Intersects)|Checks whether the Ray intersects a specified BoundingFrustum.|
|[`Nullable<System.Double> Intersects(VRageMath.PlaneD)`](VRageMath.Intersects)|Determines whether this Ray intersects a specified Plane.|
|[`void Intersects(ref VRageMath.PlaneD, ref Nullable<System.Double>)`](VRageMath.Intersects)|Determines whether this Ray intersects a specified Plane.|
|[`Nullable<System.Double> Intersects(VRageMath.BoundingSphereD)`](VRageMath.Intersects)|Checks whether the Ray intersects a specified BoundingSphere.|
|[`void Intersects(ref VRageMath.BoundingSphere, ref Nullable<System.Double>)`](VRageMath.Intersects)|Checks whether the current Ray intersects a BoundingSphere.|
