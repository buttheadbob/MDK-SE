← [Index](index.md)
#PlaneD Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
##Summary
Defines a PlaneD.
###Fields
|Member|Description|
|---|---|
|[`Vector3D Normal`](VRageMath.Normal.md)||
|[`double D`](VRageMath.D.md)||
###Methods
|Member|Description|
|---|---|
|[`bool Equals(PlaneD other)`](VRageMath.Equals.md)|Determines whether the specified PlaneD is equal to the PlaneD.|
|[`bool Equals(Object obj)`](VRageMath.Equals.md)|Determines whether the specified Object is equal to the PlaneD.|
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`string ToString()`](VRageMath.ToString.md)||
|[`void Normalize()`](VRageMath.Normalize.md)||
|[`PlaneD Normalize(PlaneD value)`](VRageMath.Normalize.md)|Changes the coefficients of the Normal vector of a PlaneD to make it of unit length.|
|[`void Normalize(ref PlaneD value, ref PlaneD result)`](VRageMath.Normalize.md)||
|[`PlaneD Transform(PlaneD plane, MatrixD matrix)`](VRageMath.Transform.md)||
|[`void Transform(ref PlaneD plane, ref MatrixD matrix, ref PlaneD result)`](VRageMath.Transform.md)||
|[`double Dot(Vector4 value)`](VRageMath.Dot.md)|Calculates the dot product of a specified Vector4 and this PlaneD.|
|[`void Dot(ref Vector4 value, ref double result)`](VRageMath.Dot.md)||
|[`double DotCoordinate(Vector3D value)`](VRageMath.DotCoordinate.md)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD plus the distance (D) value of the PlaneD.|
|[`void DotCoordinate(ref Vector3D value, ref double result)`](VRageMath.DotCoordinate.md)||
|[`double DotNormal(Vector3D value)`](VRageMath.DotNormal.md)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD.|
|[`void DotNormal(ref Vector3D value, ref double result)`](VRageMath.DotNormal.md)||
|[`PlaneIntersectionType Intersects(BoundingBoxD box)`](VRageMath.Intersects.md)|Checks whether the current PlaneD intersects a specified BoundingBox.|
|[`void Intersects(ref BoundingBoxD box, ref PlaneIntersectionType result)`](VRageMath.Intersects.md)||
|[`PlaneIntersectionType Intersects(BoundingFrustumD frustum)`](VRageMath.Intersects.md)|Checks whether the current PlaneD intersects a specified BoundingFrustum.|
|[`PlaneIntersectionType Intersects(BoundingSphereD sphere)`](VRageMath.Intersects.md)|Checks whether the current PlaneD intersects a specified BoundingSphere.|
|[`void Intersects(ref BoundingSphere sphere, ref PlaneIntersectionType result)`](VRageMath.Intersects.md)||
|[`Vector3D RandomPoint()`](VRageMath.RandomPoint.md)||
|[`double DistanceToPoint(Vector3D point)`](VRageMath.DistanceToPoint.md)||
|[`double DistanceToPoint(ref Vector3D point)`](VRageMath.DistanceToPoint.md)||
|[`Vector3D ProjectPoint(ref Vector3D point)`](VRageMath.ProjectPoint.md)||
|[`Vector3D Intersection(ref Vector3D from, ref Vector3D direction)`](VRageMath.Intersection.md)||
