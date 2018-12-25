← [Index](Api-Index)

### PlaneD Struct

```csharp
private public sealed PlaneD
```csharp

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

### Example

### Remarks

###### Fields

|Member|Description|
|---|---|
|[Normal](VRageMath.PlaneD.Normal)|The normal vector of the PlaneD.|
|[D](VRageMath.PlaneD.D)|The distance of the PlaneD along its normal from the origin. Note: Be careful! The distance is signed and is the opposite of what people usually expect. If you look closely at the plane equation: (n dot P) + D = 0, you'll realize that D = - (n dot P) (that is, negative instead of positive)|

###### Methods

|Member|Description|
|---|---|
|[Equals(PlaneD)](VRageMath.PlaneD.Equals)|Determines whether the specified PlaneD is equal to the PlaneD.|
|[Equals(object)](VRageMath.PlaneD.Equals)|Determines whether the specified Object is equal to the PlaneD.|
|[GetHashCode()](VRageMath.PlaneD.GetHashCode)|Gets the hash code for this object.|
|[ToString()](VRageMath.PlaneD.ToString)|Returns a String that represents the current PlaneD.|
|[Normalize()](VRageMath.PlaneD.Normalize)|Changes the coefficients of the Normal vector of this PlaneD to make it of unit length.|
|[Normalize(PlaneD)](VRageMath.PlaneD.Normalize)|Changes the coefficients of the Normal vector of a PlaneD to make it of unit length.|
|[Normalize(ref PlaneD, ref PlaneD)](VRageMath.PlaneD.Normalize)|Changes the coefficients of the Normal vector of a PlaneD to make it of unit length.|
|[Transform(PlaneD, MatrixD)](VRageMath.PlaneD.Transform)|Transforms a normalized PlaneD by a Matrix.|
|[Transform(ref PlaneD, ref MatrixD, ref PlaneD)](VRageMath.PlaneD.Transform)|Transforms a normalized PlaneD by a Matrix.|
|[Dot(Vector4)](VRageMath.PlaneD.Dot)|Calculates the dot product of a specified Vector4 and this PlaneD.|
|[Dot(ref Vector4, ref double)](VRageMath.PlaneD.Dot)|Calculates the dot product of a specified Vector4 and this PlaneD.|
|[DotCoordinate(Vector3D)](VRageMath.PlaneD.DotCoordinate)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD plus the distance (D) value of the PlaneD.|
|[DotCoordinate(ref Vector3D, ref double)](VRageMath.PlaneD.DotCoordinate)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD plus the distance (D) value of the PlaneD.|
|[DotNormal(Vector3D)](VRageMath.PlaneD.DotNormal)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD.|
|[DotNormal(ref Vector3D, ref double)](VRageMath.PlaneD.DotNormal)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD.|
|[Intersects(BoundingBoxD)](VRageMath.PlaneD.Intersects)|Checks whether the current PlaneD intersects a specified BoundingBox.|
|[Intersects(ref BoundingBoxD, ref PlaneIntersectionType)](VRageMath.PlaneD.Intersects)|Checks whether the current PlaneD intersects a BoundingBox.|
|[Intersects(BoundingFrustumD)](VRageMath.PlaneD.Intersects)|Checks whether the current PlaneD intersects a specified BoundingFrustum.|
|[Intersects(BoundingSphereD)](VRageMath.PlaneD.Intersects)|Checks whether the current PlaneD intersects a specified BoundingSphere.|
|[Intersects(ref BoundingSphere, ref PlaneIntersectionType)](VRageMath.PlaneD.Intersects)|Checks whether the current PlaneD intersects a BoundingSphere.|
|[RandomPoint()](VRageMath.PlaneD.RandomPoint)||
|[DistanceToPoint(Vector3D)](VRageMath.PlaneD.DistanceToPoint)||
|[DistanceToPoint(ref Vector3D)](VRageMath.PlaneD.DistanceToPoint)||
|[ProjectPoint(ref Vector3D)](VRageMath.PlaneD.ProjectPoint)||
|[Intersection(ref Vector3D, ref Vector3D)](VRageMath.PlaneD.Intersection)|Gets intersection point in Plane.|

