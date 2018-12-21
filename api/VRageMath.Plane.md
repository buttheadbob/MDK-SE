← [Index](index.md)
# Plane Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Defines a plane.
### Fields
|Member|Description|
|---|---|
|[`Vector3 Normal`](VRageMath.Normal.md)||
|[`float D`](VRageMath.D.md)||
### Methods
|Member|Description|
|---|---|
|[`bool Equals(Plane other)`](VRageMath.Equals.md)|Determines whether the specified Plane is equal to the Plane.|
|[`bool Equals(Object obj)`](VRageMath.Equals.md)|Determines whether the specified Object is equal to the Plane.|
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`string ToString()`](VRageMath.ToString.md)||
|[`void Normalize()`](VRageMath.Normalize.md)||
|[`Plane Normalize(Plane value)`](VRageMath.Normalize.md)|Changes the coefficients of the Normal vector of a Plane to make it of unit length.|
|[`void Normalize(ref Plane value, ref Plane result)`](VRageMath.Normalize.md)||
|[`Plane Transform(Plane plane, Matrix matrix)`](VRageMath.Transform.md)||
|[`void Transform(ref Plane plane, ref Matrix matrix, ref Plane result)`](VRageMath.Transform.md)||
|[`float Dot(Vector4 value)`](VRageMath.Dot.md)|Calculates the dot product of a specified Vector4 and this Plane.|
|[`void Dot(ref Vector4 value, ref float result)`](VRageMath.Dot.md)||
|[`float DotCoordinate(Vector3 value)`](VRageMath.DotCoordinate.md)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane plus the distance (D) value of the Plane.|
|[`void DotCoordinate(ref Vector3 value, ref float result)`](VRageMath.DotCoordinate.md)||
|[`float DotNormal(Vector3 value)`](VRageMath.DotNormal.md)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane.|
|[`void DotNormal(ref Vector3 value, ref float result)`](VRageMath.DotNormal.md)||
|[`PlaneIntersectionType Intersects(BoundingBox box)`](VRageMath.Intersects.md)|Checks whether the current Plane intersects a specified BoundingBox.|
|[`void Intersects(ref BoundingBox box, ref PlaneIntersectionType result)`](VRageMath.Intersects.md)||
|[`PlaneIntersectionType Intersects(BoundingFrustum frustum)`](VRageMath.Intersects.md)|Checks whether the current Plane intersects a specified BoundingFrustum.|
|[`PlaneIntersectionType Intersects(BoundingSphere sphere)`](VRageMath.Intersects.md)|Checks whether the current Plane intersects a specified BoundingSphere.|
|[`void Intersects(ref BoundingSphere sphere, ref PlaneIntersectionType result)`](VRageMath.Intersects.md)||
|[`Vector3 RandomPoint()`](VRageMath.RandomPoint.md)||
