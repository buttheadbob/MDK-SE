← [Index](index.md)
# PlaneD Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Defines a PlaneD.
### Fields
|Member|Description|
|---|---|
|[`Vector3D Normal`](VRageMath.Normal)||
|[`double D`](VRageMath.D)||
### Methods
|Member|Description|
|---|---|
|[`bool Equals(PlaneD other)`](VRageMath.Equals)|Determines whether the specified PlaneD is equal to the PlaneD.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Determines whether the specified Object is equal to the PlaneD.|
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`string ToString()`](VRageMath.ToString)||
|[`void Normalize()`](VRageMath.Normalize)||
|[`PlaneD Normalize(PlaneD value)`](VRageMath.Normalize)|Changes the coefficients of the Normal vector of a PlaneD to make it of unit length.|
|[`void Normalize(ref PlaneD value, ref PlaneD result)`](VRageMath.Normalize)||
|[`PlaneD Transform(PlaneD plane, MatrixD matrix)`](VRageMath.Transform)||
|[`void Transform(ref PlaneD plane, ref MatrixD matrix, ref PlaneD result)`](VRageMath.Transform)||
|[`double Dot(Vector4 value)`](VRageMath.Dot)|Calculates the dot product of a specified Vector4 and this PlaneD.|
|[`void Dot(ref Vector4 value, ref double result)`](VRageMath.Dot)||
|[`double DotCoordinate(Vector3D value)`](VRageMath.DotCoordinate)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD plus the distance (D) value of the PlaneD.|
|[`void DotCoordinate(ref Vector3D value, ref double result)`](VRageMath.DotCoordinate)||
|[`double DotNormal(Vector3D value)`](VRageMath.DotNormal)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD.|
|[`void DotNormal(ref Vector3D value, ref double result)`](VRageMath.DotNormal)||
|[`PlaneIntersectionType Intersects(BoundingBoxD box)`](VRageMath.Intersects)|Checks whether the current PlaneD intersects a specified BoundingBox.|
|[`void Intersects(ref BoundingBoxD box, ref PlaneIntersectionType result)`](VRageMath.Intersects)||
|[`PlaneIntersectionType Intersects(BoundingFrustumD frustum)`](VRageMath.Intersects)|Checks whether the current PlaneD intersects a specified BoundingFrustum.|
|[`PlaneIntersectionType Intersects(BoundingSphereD sphere)`](VRageMath.Intersects)|Checks whether the current PlaneD intersects a specified BoundingSphere.|
|[`void Intersects(ref BoundingSphere sphere, ref PlaneIntersectionType result)`](VRageMath.Intersects)||
|[`Vector3D RandomPoint()`](VRageMath.RandomPoint)||
|[`double DistanceToPoint(Vector3D point)`](VRageMath.DistanceToPoint)||
|[`double DistanceToPoint(ref Vector3D point)`](VRageMath.DistanceToPoint)||
|[`Vector3D ProjectPoint(ref Vector3D point)`](VRageMath.ProjectPoint)||
|[`Vector3D Intersection(ref Vector3D from, ref Vector3D direction)`](VRageMath.Intersection)||
