← [Index](Api-Index)

#### Plane Struct

```csharp
private public sealed Plane
```

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

#### Example

#### Remarks

#### Fields

|Member|Description|
|---|---|
|[Normal](VRageMath.Plane.Normal)|The normal vector of the Plane.|
|[D](VRageMath.Plane.D)|The distance of the Plane along its normal from the origin. Note: Be careful! The distance is signed and is the opposite of what people usually expect. If you look closely at the plane equation: (n dot P) - D = 0, you'll realize that D = - (n dot P) (that is, negative instead of positive)|

#### Methods

|Member|Description|
|---|---|
|[Equals(Plane)](VRageMath.Plane.Equals)|Determines whether the specified Plane is equal to the Plane.|
|[Equals(object)](VRageMath.Plane.Equals)|Determines whether the specified Object is equal to the Plane.|
|[GetHashCode()](VRageMath.Plane.GetHashCode)|Gets the hash code for this object.|
|[ToString()](VRageMath.Plane.ToString)|Returns a String that represents the current Plane.|
|[Normalize()](VRageMath.Plane.Normalize)|Changes the coefficients of the Normal vector of this Plane to make it of unit length.|
|[Normalize(Plane)](VRageMath.Plane.Normalize)|Changes the coefficients of the Normal vector of a Plane to make it of unit length.|
|[Normalize(ref Plane, ref Plane)](VRageMath.Plane.Normalize)|Changes the coefficients of the Normal vector of a Plane to make it of unit length.|
|[Transform(Plane, Matrix)](VRageMath.Plane.Transform)|Transforms a normalized Plane by a Matrix.|
|[Transform(ref Plane, ref Matrix, ref Plane)](VRageMath.Plane.Transform)|Transforms a normalized Plane by a Matrix.|
|[Dot(Vector4)](VRageMath.Plane.Dot)|Calculates the dot product of a specified Vector4 and this Plane.|
|[Dot(ref Vector4, ref float)](VRageMath.Plane.Dot)|Calculates the dot product of a specified Vector4 and this Plane.|
|[DotCoordinate(Vector3)](VRageMath.Plane.DotCoordinate)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane plus the distance (D) value of the Plane.|
|[DotCoordinate(ref Vector3, ref float)](VRageMath.Plane.DotCoordinate)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane plus the distance (D) value of the Plane.|
|[DotNormal(Vector3)](VRageMath.Plane.DotNormal)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane.|
|[DotNormal(ref Vector3, ref float)](VRageMath.Plane.DotNormal)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane.|
|[Intersects(BoundingBox)](VRageMath.Plane.Intersects)|Checks whether the current Plane intersects a specified BoundingBox.|
|[Intersects(ref BoundingBox, ref PlaneIntersectionType)](VRageMath.Plane.Intersects)|Checks whether the current Plane intersects a BoundingBox.|
|[Intersects(BoundingFrustum)](VRageMath.Plane.Intersects)|Checks whether the current Plane intersects a specified BoundingFrustum.|
|[Intersects(BoundingSphere)](VRageMath.Plane.Intersects)|Checks whether the current Plane intersects a specified BoundingSphere.|
|[Intersects(ref BoundingSphere, ref PlaneIntersectionType)](VRageMath.Plane.Intersects)|Checks whether the current Plane intersects a BoundingSphere.|
|[RandomPoint()](VRageMath.Plane.RandomPoint)||

