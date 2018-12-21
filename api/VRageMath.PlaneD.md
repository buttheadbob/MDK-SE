← [Index](index)
# PlaneD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a PlaneD.
### Fields
|Member|Description|
|---|---|
|[`Vector3D&nbsp;Normal`](VRageMath.Normal)|The normal vector of the PlaneD.|
|[`double&nbsp;D`](VRageMath.D)|The distance of the PlaneD along its normal from the origin. Note: Be careful! The distance is signed and is the opposite of what people usually expect. If you look closely at the plane equation: (n dot P) + D = 0, you'll realize that D = - (n dot P) (that is, negative instead of positive)|
### Methods
|Member|Description|
|---|---|
|[`bool&nbsp;Equals(PlaneD&nbsp;other)`](VRageMath.Equals)|Determines whether the specified PlaneD is equal to the PlaneD.|
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Determines whether the specified Object is equal to the PlaneD.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this object.|
|[`string&nbsp;ToString()`](VRageMath.ToString)|Returns a String that represents the current PlaneD.|
|[`void&nbsp;Normalize()`](VRageMath.Normalize)|Changes the coefficients of the Normal vector of this PlaneD to make it of unit length.|
|static&nbsp;[`PlaneD&nbsp;Normalize(PlaneD&nbsp;value)`](VRageMath.Normalize)|Changes the coefficients of the Normal vector of a PlaneD to make it of unit length.|
|static&nbsp;[`void&nbsp;Normalize(ref&nbsp;PlaneD&nbsp;value,&nbsp;ref&nbsp;PlaneD&nbsp;result)`](VRageMath.Normalize)|Changes the coefficients of the Normal vector of a PlaneD to make it of unit length.|
|static&nbsp;[`PlaneD&nbsp;Transform(PlaneD&nbsp;plane,&nbsp;MatrixD&nbsp;matrix)`](VRageMath.Transform)|Transforms a normalized PlaneD by a Matrix.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;PlaneD&nbsp;plane,&nbsp;ref&nbsp;MatrixD&nbsp;matrix,&nbsp;ref&nbsp;PlaneD&nbsp;result)`](VRageMath.Transform)|Transforms a normalized PlaneD by a Matrix.|
|[`double&nbsp;Dot(Vector4&nbsp;value)`](VRageMath.Dot)|Calculates the dot product of a specified Vector4 and this PlaneD.|
|[`void&nbsp;Dot(ref&nbsp;Vector4&nbsp;value,&nbsp;ref&nbsp;double&nbsp;result)`](VRageMath.Dot)|Calculates the dot product of a specified Vector4 and this PlaneD.|
|[`double&nbsp;DotCoordinate(Vector3D&nbsp;value)`](VRageMath.DotCoordinate)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD plus the distance (D) value of the PlaneD.|
|[`void&nbsp;DotCoordinate(ref&nbsp;Vector3D&nbsp;value,&nbsp;ref&nbsp;double&nbsp;result)`](VRageMath.DotCoordinate)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD plus the distance (D) value of the PlaneD.|
|[`double&nbsp;DotNormal(Vector3D&nbsp;value)`](VRageMath.DotNormal)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD.|
|[`void&nbsp;DotNormal(ref&nbsp;Vector3D&nbsp;value,&nbsp;ref&nbsp;double&nbsp;result)`](VRageMath.DotNormal)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD.|
|[`PlaneIntersectionType&nbsp;Intersects(BoundingBoxD&nbsp;box)`](VRageMath.Intersects)|Checks whether the current PlaneD intersects a specified BoundingBox.|
|[`void&nbsp;Intersects(ref&nbsp;BoundingBoxD&nbsp;box,&nbsp;ref&nbsp;PlaneIntersectionType&nbsp;result)`](VRageMath.Intersects)|Checks whether the current PlaneD intersects a BoundingBox.|
|[`PlaneIntersectionType&nbsp;Intersects(BoundingFrustumD&nbsp;frustum)`](VRageMath.Intersects)|Checks whether the current PlaneD intersects a specified BoundingFrustum.|
|[`PlaneIntersectionType&nbsp;Intersects(BoundingSphereD&nbsp;sphere)`](VRageMath.Intersects)|Checks whether the current PlaneD intersects a specified BoundingSphere.|
|[`void&nbsp;Intersects(ref&nbsp;BoundingSphere&nbsp;sphere,&nbsp;ref&nbsp;PlaneIntersectionType&nbsp;result)`](VRageMath.Intersects)|Checks whether the current PlaneD intersects a BoundingSphere.|
|[`Vector3D&nbsp;RandomPoint()`](VRageMath.RandomPoint)||
|[`double&nbsp;DistanceToPoint(Vector3D&nbsp;point)`](VRageMath.DistanceToPoint)||
|[`double&nbsp;DistanceToPoint(ref&nbsp;Vector3D&nbsp;point)`](VRageMath.DistanceToPoint)||
|[`Vector3D&nbsp;ProjectPoint(ref&nbsp;Vector3D&nbsp;point)`](VRageMath.ProjectPoint)||
|[`Vector3D&nbsp;Intersection(ref&nbsp;Vector3D&nbsp;from,&nbsp;ref&nbsp;Vector3D&nbsp;direction)`](VRageMath.Intersection)|Gets intersection point in Plane.|
