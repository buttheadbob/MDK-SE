← [Index](index)
# PlaneD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a PlaneD.
### Fields
|Member|Description|
|---|---|
|[`Vector3D Normal`](VRageMath.Normal)|The normal vector of the PlaneD.|
|[`double D`](VRageMath.D)|The distance of the PlaneD along its normal from the origin. Note: Be careful! The distance is signed and is the opposite of what people usually expect. If you look closely at the plane equation: (n dot P) + D = 0, you'll realize that D = - (n dot P) (that is, negative instead of positive)|
### Methods
|Member|Description|
|---|---|
|[`bool Equals(PlaneD other)`](VRageMath.Equals)|Determines whether the specified PlaneD is equal to the PlaneD.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Determines whether the specified Object is equal to the PlaneD.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this object.|
|[`string ToString()`](VRageMath.ToString)|Returns a String that represents the current PlaneD.|
|[`void Normalize()`](VRageMath.Normalize)|Changes the coefficients of the Normal vector of this PlaneD to make it of unit length.|
|static [`PlaneD Normalize(PlaneD value)`](VRageMath.Normalize)|Changes the coefficients of the Normal vector of a PlaneD to make it of unit length.|
|static [`void Normalize(ref PlaneD value, ref PlaneD result)`](VRageMath.Normalize)|Changes the coefficients of the Normal vector of a PlaneD to make it of unit length.|
|static [`PlaneD Transform(PlaneD plane, MatrixD matrix)`](VRageMath.Transform)|Transforms a normalized PlaneD by a Matrix.|
|static [`void Transform(ref PlaneD plane, ref MatrixD matrix, ref PlaneD result)`](VRageMath.Transform)|Transforms a normalized PlaneD by a Matrix.|
|[`double Dot(Vector4 value)`](VRageMath.Dot)|Calculates the dot product of a specified Vector4 and this PlaneD.|
|[`void Dot(ref Vector4 value, ref double result)`](VRageMath.Dot)|Calculates the dot product of a specified Vector4 and this PlaneD.|
|[`double DotCoordinate(Vector3D value)`](VRageMath.DotCoordinate)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD plus the distance (D) value of the PlaneD.|
|[`void DotCoordinate(ref Vector3D value, ref double result)`](VRageMath.DotCoordinate)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD plus the distance (D) value of the PlaneD.|
|[`double DotNormal(Vector3D value)`](VRageMath.DotNormal)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD.|
|[`void DotNormal(ref Vector3D value, ref double result)`](VRageMath.DotNormal)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD.|
|[`PlaneIntersectionType Intersects(BoundingBoxD box)`](VRageMath.Intersects)|Checks whether the current PlaneD intersects a specified BoundingBox.|
|[`void Intersects(ref BoundingBoxD box, ref PlaneIntersectionType result)`](VRageMath.Intersects)|Checks whether the current PlaneD intersects a BoundingBox.|
|[`PlaneIntersectionType Intersects(BoundingFrustumD frustum)`](VRageMath.Intersects)|Checks whether the current PlaneD intersects a specified BoundingFrustum.|
|[`PlaneIntersectionType Intersects(BoundingSphereD sphere)`](VRageMath.Intersects)|Checks whether the current PlaneD intersects a specified BoundingSphere.|
|[`void Intersects(ref BoundingSphere sphere, ref PlaneIntersectionType result)`](VRageMath.Intersects)|Checks whether the current PlaneD intersects a BoundingSphere.|
|[`Vector3D RandomPoint()`](VRageMath.RandomPoint)||
|[`double DistanceToPoint(Vector3D point)`](VRageMath.DistanceToPoint)||
|[`double DistanceToPoint(ref Vector3D point)`](VRageMath.DistanceToPoint)||
|[`Vector3D ProjectPoint(ref Vector3D point)`](VRageMath.ProjectPoint)||
|[`Vector3D Intersection(ref Vector3D from, ref Vector3D direction)`](VRageMath.Intersection)|Gets intersection point in Plane.|
