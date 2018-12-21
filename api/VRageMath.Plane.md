← [Index](ApiIndex)
# Plane Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a plane.
### Fields
|Member|Description|
|---|---|
|[`Normal`](VRageMath.Normal)|The normal vector of the Plane.|
|[`D`](VRageMath.D)|The distance of the Plane along its normal from the origin. Note: Be careful! The distance is signed and is the opposite of what people usually expect. If you look closely at the plane equation: (n dot P) - D = 0, you'll realize that D = - (n dot P) (that is, negative instead of positive)|
### Methods
|Member|Description|
|---|---|
|[`Equals(Plane)`](VRageMath.Equals)|Determines whether the specified Plane is equal to the Plane.|
|[`Equals(Object)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Plane.|
|[`GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this object.|
|[`ToString()`](VRageMath.ToString)|Returns a String that represents the current Plane.|
|[`Normalize()`](VRageMath.Normalize)|Changes the coefficients of the Normal vector of this Plane to make it of unit length.|
|[`Normalize(Plane)`](VRageMath.Normalize)|Changes the coefficients of the Normal vector of a Plane to make it of unit length.|
|[`Normalize(ref Plane, ref Plane)`](VRageMath.Normalize)|Changes the coefficients of the Normal vector of a Plane to make it of unit length.|
|[`Transform(Plane, Matrix)`](VRageMath.Transform)|Transforms a normalized Plane by a Matrix.|
|[`Transform(ref Plane, ref Matrix, ref Plane)`](VRageMath.Transform)|Transforms a normalized Plane by a Matrix.|
|[`Dot(Vector4)`](VRageMath.Dot)|Calculates the dot product of a specified Vector4 and this Plane.|
|[`Dot(ref Vector4, ref float)`](VRageMath.Dot)|Calculates the dot product of a specified Vector4 and this Plane.|
|[`DotCoordinate(Vector3)`](VRageMath.DotCoordinate)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane plus the distance (D) value of the Plane.|
|[`DotCoordinate(ref Vector3, ref float)`](VRageMath.DotCoordinate)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane plus the distance (D) value of the Plane.|
|[`DotNormal(Vector3)`](VRageMath.DotNormal)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane.|
|[`DotNormal(ref Vector3, ref float)`](VRageMath.DotNormal)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane.|
|[`Intersects(BoundingBox)`](VRageMath.Intersects)|Checks whether the current Plane intersects a specified BoundingBox.|
|[`Intersects(ref BoundingBox, ref PlaneIntersectionType)`](VRageMath.Intersects)|Checks whether the current Plane intersects a BoundingBox.|
|[`Intersects(BoundingFrustum)`](VRageMath.Intersects)|Checks whether the current Plane intersects a specified BoundingFrustum.|
|[`Intersects(BoundingSphere)`](VRageMath.Intersects)|Checks whether the current Plane intersects a specified BoundingSphere.|
|[`Intersects(ref BoundingSphere, ref PlaneIntersectionType)`](VRageMath.Intersects)|Checks whether the current Plane intersects a BoundingSphere.|
|[`RandomPoint()`](VRageMath.RandomPoint)||
