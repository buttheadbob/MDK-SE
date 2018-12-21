← [Index](index)
# PlaneD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a PlaneD.
### Fields
|Member|Description|
|---|---|
|[`VRageMath.Vector3D Normal`](VRageMath.Normal)|The normal vector of the PlaneD.|
|[`double D`](VRageMath.D)|The distance of the PlaneD along its normal from the origin. Note: Be careful! The distance is signed and is the opposite of what people usually expect. If you look closely at the plane equation: (n dot P) + D = 0, you'll realize that D = - (n dot P) (that is, negative instead of positive)|
### Methods
|Member|Description|
|---|---|
|[`bool Equals(VRageMath.PlaneD)`](VRageMath.Equals)|Determines whether the specified PlaneD is equal to the PlaneD.|
|[`bool Equals(System.Object)`](VRageMath.Equals)|Determines whether the specified Object is equal to the PlaneD.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this object.|
|[`string ToString()`](VRageMath.ToString)|Returns a String that represents the current PlaneD.|
|[`void Normalize()`](VRageMath.Normalize)|Changes the coefficients of the Normal vector of this PlaneD to make it of unit length.|
|static [`VRageMath.PlaneD Normalize(VRageMath.PlaneD)`](VRageMath.Normalize)|Changes the coefficients of the Normal vector of a PlaneD to make it of unit length.|
|static [`void Normalize(ref VRageMath.PlaneD, ref VRageMath.PlaneD)`](VRageMath.Normalize)|Changes the coefficients of the Normal vector of a PlaneD to make it of unit length.|
|static [`VRageMath.PlaneD Transform(VRageMath.PlaneD, VRageMath.MatrixD)`](VRageMath.Transform)|Transforms a normalized PlaneD by a Matrix.|
|static [`void Transform(ref VRageMath.PlaneD, ref VRageMath.MatrixD, ref VRageMath.PlaneD)`](VRageMath.Transform)|Transforms a normalized PlaneD by a Matrix.|
|[`double Dot(VRageMath.Vector4)`](VRageMath.Dot)|Calculates the dot product of a specified Vector4 and this PlaneD.|
|[`void Dot(ref VRageMath.Vector4, ref double)`](VRageMath.Dot)|Calculates the dot product of a specified Vector4 and this PlaneD.|
|[`double DotCoordinate(VRageMath.Vector3D)`](VRageMath.DotCoordinate)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD plus the distance (D) value of the PlaneD.|
|[`void DotCoordinate(ref VRageMath.Vector3D, ref double)`](VRageMath.DotCoordinate)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD plus the distance (D) value of the PlaneD.|
|[`double DotNormal(VRageMath.Vector3D)`](VRageMath.DotNormal)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD.|
|[`void DotNormal(ref VRageMath.Vector3D, ref double)`](VRageMath.DotNormal)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD.|
|[`VRageMath.PlaneIntersectionType Intersects(VRageMath.BoundingBoxD)`](VRageMath.Intersects)|Checks whether the current PlaneD intersects a specified BoundingBox.|
|[`void Intersects(ref VRageMath.BoundingBoxD, ref VRageMath.PlaneIntersectionType)`](VRageMath.Intersects)|Checks whether the current PlaneD intersects a BoundingBox.|
|[`VRageMath.PlaneIntersectionType Intersects(VRageMath.BoundingFrustumD)`](VRageMath.Intersects)|Checks whether the current PlaneD intersects a specified BoundingFrustum.|
|[`VRageMath.PlaneIntersectionType Intersects(VRageMath.BoundingSphereD)`](VRageMath.Intersects)|Checks whether the current PlaneD intersects a specified BoundingSphere.|
|[`void Intersects(ref VRageMath.BoundingSphere, ref VRageMath.PlaneIntersectionType)`](VRageMath.Intersects)|Checks whether the current PlaneD intersects a BoundingSphere.|
|[`VRageMath.Vector3D RandomPoint()`](VRageMath.RandomPoint)||
|[`double DistanceToPoint(VRageMath.Vector3D)`](VRageMath.DistanceToPoint)||
|[`double DistanceToPoint(ref VRageMath.Vector3D)`](VRageMath.DistanceToPoint)||
|[`VRageMath.Vector3D ProjectPoint(ref VRageMath.Vector3D)`](VRageMath.ProjectPoint)||
|[`VRageMath.Vector3D Intersection(ref VRageMath.Vector3D, ref VRageMath.Vector3D)`](VRageMath.Intersection)|Gets intersection point in Plane.|
