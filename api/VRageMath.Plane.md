← [Index](index)
# Plane Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a plane.
### Fields
|Member|Description|
|---|---|
|[`Vector3 Normal`](VRageMath.Normal)||
|[`float D`](VRageMath.D)||
### Methods
|Member|Description|
|---|---|
|[`bool Equals(Plane other)`](VRageMath.Equals)|Determines whether the specified Plane is equal to the Plane.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Plane.|
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`string ToString()`](VRageMath.ToString)||
|[`void Normalize()`](VRageMath.Normalize)||
|[`Plane Normalize(Plane value)`](VRageMath.Normalize)|Changes the coefficients of the Normal vector of a Plane to make it of unit length.|
|[`void Normalize(ref Plane value, ref Plane result)`](VRageMath.Normalize)||
|[`Plane Transform(Plane plane, Matrix matrix)`](VRageMath.Transform)||
|[`void Transform(ref Plane plane, ref Matrix matrix, ref Plane result)`](VRageMath.Transform)||
|[`float Dot(Vector4 value)`](VRageMath.Dot)|Calculates the dot product of a specified Vector4 and this Plane.|
|[`void Dot(ref Vector4 value, ref float result)`](VRageMath.Dot)||
|[`float DotCoordinate(Vector3 value)`](VRageMath.DotCoordinate)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane plus the distance (D) value of the Plane.|
|[`void DotCoordinate(ref Vector3 value, ref float result)`](VRageMath.DotCoordinate)||
|[`float DotNormal(Vector3 value)`](VRageMath.DotNormal)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane.|
|[`void DotNormal(ref Vector3 value, ref float result)`](VRageMath.DotNormal)||
|[`PlaneIntersectionType Intersects(BoundingBox box)`](VRageMath.Intersects)|Checks whether the current Plane intersects a specified BoundingBox.|
|[`void Intersects(ref BoundingBox box, ref PlaneIntersectionType result)`](VRageMath.Intersects)||
|[`PlaneIntersectionType Intersects(BoundingFrustum frustum)`](VRageMath.Intersects)|Checks whether the current Plane intersects a specified BoundingFrustum.|
|[`PlaneIntersectionType Intersects(BoundingSphere sphere)`](VRageMath.Intersects)|Checks whether the current Plane intersects a specified BoundingSphere.|
|[`void Intersects(ref BoundingSphere sphere, ref PlaneIntersectionType result)`](VRageMath.Intersects)||
|[`Vector3 RandomPoint()`](VRageMath.RandomPoint)||
