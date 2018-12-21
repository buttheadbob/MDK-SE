← [Index](index)
# Plane Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a plane.
### Fields
|Member|Description|
|---|---|
|[`Vector3&nbsp;Normal`](VRageMath.Normal)|The normal vector of the Plane.|
|[`float&nbsp;D`](VRageMath.D)|The distance of the Plane along its normal from the origin. Note: Be careful! The distance is signed and is the opposite of what people usually expect. If you look closely at the plane equation: (n dot P) - D = 0, you'll realize that D = - (n dot P) (that is, negative instead of positive)|
### Methods
|Member|Description|
|---|---|
|[`bool&nbsp;Equals(Plane&nbsp;other)`](VRageMath.Equals)|Determines whether the specified Plane is equal to the Plane.|
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Plane.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this object.|
|[`string&nbsp;ToString()`](VRageMath.ToString)|Returns a String that represents the current Plane.|
|[`void&nbsp;Normalize()`](VRageMath.Normalize)|Changes the coefficients of the Normal vector of this Plane to make it of unit length.|
|static&nbsp;[`Plane&nbsp;Normalize(Plane&nbsp;value)`](VRageMath.Normalize)|Changes the coefficients of the Normal vector of a Plane to make it of unit length.|
|static&nbsp;[`void&nbsp;Normalize(ref&nbsp;Plane&nbsp;value,&nbsp;ref&nbsp;Plane&nbsp;result)`](VRageMath.Normalize)|Changes the coefficients of the Normal vector of a Plane to make it of unit length.|
|static&nbsp;[`Plane&nbsp;Transform(Plane&nbsp;plane,&nbsp;Matrix&nbsp;matrix)`](VRageMath.Transform)|Transforms a normalized Plane by a Matrix.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Plane&nbsp;plane,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;ref&nbsp;Plane&nbsp;result)`](VRageMath.Transform)|Transforms a normalized Plane by a Matrix.|
|[`float&nbsp;Dot(Vector4&nbsp;value)`](VRageMath.Dot)|Calculates the dot product of a specified Vector4 and this Plane.|
|[`void&nbsp;Dot(ref&nbsp;Vector4&nbsp;value,&nbsp;ref&nbsp;float&nbsp;result)`](VRageMath.Dot)|Calculates the dot product of a specified Vector4 and this Plane.|
|[`float&nbsp;DotCoordinate(Vector3&nbsp;value)`](VRageMath.DotCoordinate)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane plus the distance (D) value of the Plane.|
|[`void&nbsp;DotCoordinate(ref&nbsp;Vector3&nbsp;value,&nbsp;ref&nbsp;float&nbsp;result)`](VRageMath.DotCoordinate)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane plus the distance (D) value of the Plane.|
|[`float&nbsp;DotNormal(Vector3&nbsp;value)`](VRageMath.DotNormal)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane.|
|[`void&nbsp;DotNormal(ref&nbsp;Vector3&nbsp;value,&nbsp;ref&nbsp;float&nbsp;result)`](VRageMath.DotNormal)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane.|
|[`PlaneIntersectionType&nbsp;Intersects(BoundingBox&nbsp;box)`](VRageMath.Intersects)|Checks whether the current Plane intersects a specified BoundingBox.|
|[`void&nbsp;Intersects(ref&nbsp;BoundingBox&nbsp;box,&nbsp;ref&nbsp;PlaneIntersectionType&nbsp;result)`](VRageMath.Intersects)|Checks whether the current Plane intersects a BoundingBox.|
|[`PlaneIntersectionType&nbsp;Intersects(BoundingFrustum&nbsp;frustum)`](VRageMath.Intersects)|Checks whether the current Plane intersects a specified BoundingFrustum.|
|[`PlaneIntersectionType&nbsp;Intersects(BoundingSphere&nbsp;sphere)`](VRageMath.Intersects)|Checks whether the current Plane intersects a specified BoundingSphere.|
|[`void&nbsp;Intersects(ref&nbsp;BoundingSphere&nbsp;sphere,&nbsp;ref&nbsp;PlaneIntersectionType&nbsp;result)`](VRageMath.Intersects)|Checks whether the current Plane intersects a BoundingSphere.|
|[`Vector3&nbsp;RandomPoint()`](VRageMath.RandomPoint)||
