← [Index](index)
# Plane Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a plane.
### Fields
|Member|Description|
|---|---|
|[`Vector3 Normal`](VRageMath.Normal)|The normal vector of the Plane.|
|[`float D`](VRageMath.D)|The distance of the Plane along its normal from the origin. Note: Be careful! The distance is signed and is the opposite of what people usually expect. If you look closely at the plane equation: (n dot P) - D = 0, you'll realize that D = - (n dot P) (that is, negative instead of positive)|
### Methods
|Member|Description|
|---|---|
|[`bool Equals(Plane other)`](VRageMath.Equals)|Determines whether the specified Plane is equal to the Plane.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Plane.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this object.|
|[`string ToString()`](VRageMath.ToString)|Returns a String that represents the current Plane.|
|[`void Normalize()`](VRageMath.Normalize)|Changes the coefficients of the Normal vector of this Plane to make it of unit length.|
|static [`Plane Normalize(Plane value)`](VRageMath.Normalize)|Changes the coefficients of the Normal vector of a Plane to make it of unit length.|
|static [`void Normalize(ref Plane value, ref Plane result)`](VRageMath.Normalize)|Changes the coefficients of the Normal vector of a Plane to make it of unit length.|
|static [`Plane Transform(Plane plane, Matrix matrix)`](VRageMath.Transform)|Transforms a normalized Plane by a Matrix.|
|static [`void Transform(ref Plane plane, ref Matrix matrix, ref Plane result)`](VRageMath.Transform)|Transforms a normalized Plane by a Matrix.|
|[`float Dot(Vector4 value)`](VRageMath.Dot)|Calculates the dot product of a specified Vector4 and this Plane.|
|[`void Dot(ref Vector4 value, ref float result)`](VRageMath.Dot)|Calculates the dot product of a specified Vector4 and this Plane.|
|[`float DotCoordinate(Vector3 value)`](VRageMath.DotCoordinate)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane plus the distance (D) value of the Plane.|
|[`void DotCoordinate(ref Vector3 value, ref float result)`](VRageMath.DotCoordinate)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane plus the distance (D) value of the Plane.|
|[`float DotNormal(Vector3 value)`](VRageMath.DotNormal)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane.|
|[`void DotNormal(ref Vector3 value, ref float result)`](VRageMath.DotNormal)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane.|
|[`PlaneIntersectionType Intersects(BoundingBox box)`](VRageMath.Intersects)|Checks whether the current Plane intersects a specified BoundingBox.|
|[`void Intersects(ref BoundingBox box, ref PlaneIntersectionType result)`](VRageMath.Intersects)|Checks whether the current Plane intersects a BoundingBox.|
|[`PlaneIntersectionType Intersects(BoundingFrustum frustum)`](VRageMath.Intersects)|Checks whether the current Plane intersects a specified BoundingFrustum.|
|[`PlaneIntersectionType Intersects(BoundingSphere sphere)`](VRageMath.Intersects)|Checks whether the current Plane intersects a specified BoundingSphere.|
|[`void Intersects(ref BoundingSphere sphere, ref PlaneIntersectionType result)`](VRageMath.Intersects)|Checks whether the current Plane intersects a BoundingSphere.|
|[`Vector3 RandomPoint()`](VRageMath.RandomPoint)||
