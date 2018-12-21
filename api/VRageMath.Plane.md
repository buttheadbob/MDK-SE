← [Index](index)
# Plane Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a plane.
### Fields
|Member|Description|
|---|---|
|[`VRageMath.Vector3 Normal`](VRageMath.Normal)|The normal vector of the Plane.|
|[`float D`](VRageMath.D)|The distance of the Plane along its normal from the origin. Note: Be careful! The distance is signed and is the opposite of what people usually expect. If you look closely at the plane equation: (n dot P) - D = 0, you'll realize that D = - (n dot P) (that is, negative instead of positive)|
### Methods
|Member|Description|
|---|---|
|[`bool Equals(VRageMath.Plane)`](VRageMath.Equals)|Determines whether the specified Plane is equal to the Plane.|
|[`bool Equals(System.Object)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Plane.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this object.|
|[`string ToString()`](VRageMath.ToString)|Returns a String that represents the current Plane.|
|[`void Normalize()`](VRageMath.Normalize)|Changes the coefficients of the Normal vector of this Plane to make it of unit length.|
|static [`VRageMath.Plane Normalize(VRageMath.Plane)`](VRageMath.Normalize)|Changes the coefficients of the Normal vector of a Plane to make it of unit length.|
|static [`void Normalize(ref VRageMath.Plane, ref VRageMath.Plane)`](VRageMath.Normalize)|Changes the coefficients of the Normal vector of a Plane to make it of unit length.|
|static [`VRageMath.Plane Transform(VRageMath.Plane, VRageMath.Matrix)`](VRageMath.Transform)|Transforms a normalized Plane by a Matrix.|
|static [`void Transform(ref VRageMath.Plane, ref VRageMath.Matrix, ref VRageMath.Plane)`](VRageMath.Transform)|Transforms a normalized Plane by a Matrix.|
|[`float Dot(VRageMath.Vector4)`](VRageMath.Dot)|Calculates the dot product of a specified Vector4 and this Plane.|
|[`void Dot(ref VRageMath.Vector4, ref float)`](VRageMath.Dot)|Calculates the dot product of a specified Vector4 and this Plane.|
|[`float DotCoordinate(VRageMath.Vector3)`](VRageMath.DotCoordinate)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane plus the distance (D) value of the Plane.|
|[`void DotCoordinate(ref VRageMath.Vector3, ref float)`](VRageMath.DotCoordinate)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane plus the distance (D) value of the Plane.|
|[`float DotNormal(VRageMath.Vector3)`](VRageMath.DotNormal)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane.|
|[`void DotNormal(ref VRageMath.Vector3, ref float)`](VRageMath.DotNormal)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane.|
|[`VRageMath.PlaneIntersectionType Intersects(VRageMath.BoundingBox)`](VRageMath.Intersects)|Checks whether the current Plane intersects a specified BoundingBox.|
|[`void Intersects(ref VRageMath.BoundingBox, ref VRageMath.PlaneIntersectionType)`](VRageMath.Intersects)|Checks whether the current Plane intersects a BoundingBox.|
|[`VRageMath.PlaneIntersectionType Intersects(VRageMath.BoundingFrustum)`](VRageMath.Intersects)|Checks whether the current Plane intersects a specified BoundingFrustum.|
|[`VRageMath.PlaneIntersectionType Intersects(VRageMath.BoundingSphere)`](VRageMath.Intersects)|Checks whether the current Plane intersects a specified BoundingSphere.|
|[`void Intersects(ref VRageMath.BoundingSphere, ref VRageMath.PlaneIntersectionType)`](VRageMath.Intersects)|Checks whether the current Plane intersects a BoundingSphere.|
|[`VRageMath.Vector3 RandomPoint()`](VRageMath.RandomPoint)||
