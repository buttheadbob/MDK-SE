← [Index](index)
# PlaneD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a PlaneD.
### Fields
|Member|Description|
|---|---|
|[`Normal`](VRageMath.Normal)|The normal vector of the PlaneD.|
|[`D`](VRageMath.D)|The distance of the PlaneD along its normal from the origin. Note: Be careful! The distance is signed and is the opposite of what people usually expect. If you look closely at the plane equation: (n dot P) + D = 0, you'll realize that D = - (n dot P) (that is, negative instead of positive)|
### Methods
|Member|Description|
|---|---|
|[`Equals(PlaneD)`](VRageMath.Equals)|Determines whether the specified PlaneD is equal to the PlaneD.|
|[`Equals(Object)`](VRageMath.Equals)|Determines whether the specified Object is equal to the PlaneD.|
|[`GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this object.|
|[`ToString()`](VRageMath.ToString)|Returns a String that represents the current PlaneD.|
|[`Normalize()`](VRageMath.Normalize)|Changes the coefficients of the Normal vector of this PlaneD to make it of unit length.|
|[`Normalize(PlaneD)`](VRageMath.Normalize)|Changes the coefficients of the Normal vector of a PlaneD to make it of unit length.|
|[`Normalize(ref PlaneD, ref PlaneD)`](VRageMath.Normalize)|Changes the coefficients of the Normal vector of a PlaneD to make it of unit length.|
|[`Transform(PlaneD, MatrixD)`](VRageMath.Transform)|Transforms a normalized PlaneD by a Matrix.|
|[`Transform(ref PlaneD, ref MatrixD, ref PlaneD)`](VRageMath.Transform)|Transforms a normalized PlaneD by a Matrix.|
|[`Dot(Vector4)`](VRageMath.Dot)|Calculates the dot product of a specified Vector4 and this PlaneD.|
|[`Dot(ref Vector4, ref double)`](VRageMath.Dot)|Calculates the dot product of a specified Vector4 and this PlaneD.|
|[`DotCoordinate(Vector3D)`](VRageMath.DotCoordinate)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD plus the distance (D) value of the PlaneD.|
|[`DotCoordinate(ref Vector3D, ref double)`](VRageMath.DotCoordinate)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD plus the distance (D) value of the PlaneD.|
|[`DotNormal(Vector3D)`](VRageMath.DotNormal)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD.|
|[`DotNormal(ref Vector3D, ref double)`](VRageMath.DotNormal)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD.|
|[`Intersects(BoundingBoxD)`](VRageMath.Intersects)|Checks whether the current PlaneD intersects a specified BoundingBox.|
|[`Intersects(ref BoundingBoxD, ref PlaneIntersectionType)`](VRageMath.Intersects)|Checks whether the current PlaneD intersects a BoundingBox.|
|[`Intersects(BoundingFrustumD)`](VRageMath.Intersects)|Checks whether the current PlaneD intersects a specified BoundingFrustum.|
|[`Intersects(BoundingSphereD)`](VRageMath.Intersects)|Checks whether the current PlaneD intersects a specified BoundingSphere.|
|[`Intersects(ref BoundingSphere, ref PlaneIntersectionType)`](VRageMath.Intersects)|Checks whether the current PlaneD intersects a BoundingSphere.|
|[`RandomPoint()`](VRageMath.RandomPoint)||
|[`DistanceToPoint(Vector3D)`](VRageMath.DistanceToPoint)||
|[`DistanceToPoint(ref Vector3D)`](VRageMath.DistanceToPoint)||
|[`ProjectPoint(ref Vector3D)`](VRageMath.ProjectPoint)||
|[`Intersection(ref Vector3D, ref Vector3D)`](VRageMath.Intersection)|Gets intersection point in Plane.|
