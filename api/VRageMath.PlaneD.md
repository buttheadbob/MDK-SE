← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### PlaneD Struct

```csharp
public struct PlaneD: IEquatable<PlaneD\>
```

Defines a PlaneD.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<PlaneD\>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\$1double D](VRageMath.PlaneD.D)|The distance of the PlaneD along its normal from the origin. Note: Be careful! The distance is signed and is the opposite of what people usually expect. If you look closely at the plane equation: (n dot P) + D = 0, you'll realize that D = - (n dot P) (that is, negative instead of positive)|
|\$1Vector3D Normal](VRageMath.PlaneD.Normal)|The normal vector of the PlaneD.|

#### Constructors

|Member|Description|
|---|---|
|\$1PlaneD(double, double, double, double)](VRageMath.PlaneD..ctor)||
|\$1PlaneD(Vector3D, double)](VRageMath.PlaneD..ctor)||
|\$1PlaneD(Vector3D, Vector3D)](VRageMath.PlaneD..ctor)||
|\$1PlaneD(Vector3D, Vector3)](VRageMath.PlaneD..ctor)||
|\$1PlaneD(Vector4)](VRageMath.PlaneD..ctor)||
|\$1PlaneD(Vector3D, Vector3D, Vector3D)](VRageMath.PlaneD..ctor)||

#### Methods

|Member|Description|
|---|---|
|\$1static PlaneD Normalize(PlaneD)](VRageMath.PlaneD.Normalize)|Changes the coefficients of the Normal vector of a PlaneD to make it of unit length.|
|\$1static void Normalize(ref PlaneD, out PlaneD)](VRageMath.PlaneD.Normalize)|Changes the coefficients of the Normal vector of a PlaneD to make it of unit length.|
|\$1static PlaneD Transform(PlaneD, MatrixD)](VRageMath.PlaneD.Transform)|Transforms a normalized plane by a Matrix.|
|\$1static void Transform(ref PlaneD, ref MatrixD, out PlaneD)](VRageMath.PlaneD.Transform)|Transforms a normalized plane by a Matrix.|
|\$1double DistanceToPoint(Vector3D)](VRageMath.PlaneD.DistanceToPoint)||
|\$1double DistanceToPoint(ref Vector3D)](VRageMath.PlaneD.DistanceToPoint)||
|\$1double Dot(Vector4)](VRageMath.PlaneD.Dot)|Calculates the dot product of a specified Vector4 and this PlaneD.|
|\$1void Dot(ref Vector4, out double)](VRageMath.PlaneD.Dot)|Calculates the dot product of a specified Vector4 and this PlaneD.|
|\$1double DotCoordinate(Vector3D)](VRageMath.PlaneD.DotCoordinate)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD plus the distance (D) value of the PlaneD.|
|\$1void DotCoordinate(ref Vector3D, out double)](VRageMath.PlaneD.DotCoordinate)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD plus the distance (D) value of the PlaneD.|
|\$1double DotNormal(Vector3D)](VRageMath.PlaneD.DotNormal)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD.|
|\$1void DotNormal(ref Vector3D, out double)](VRageMath.PlaneD.DotNormal)|Returns the dot product of a specified Vector3D and the Normal vector of this PlaneD.|
|\$1bool Equals(PlaneD)](VRageMath.PlaneD.Equals)|Determines whether the specified PlaneD is equal to the PlaneD.|
|\$1bool Equals(object)](VRageMath.PlaneD.Equals)|Determines whether the specified Object is equal to the PlaneD.|
|\$1int GetHashCode()](VRageMath.PlaneD.GetHashCode)|Gets the hash code for this object.|
|\$1Vector3D Intersection(ref Vector3D, ref Vector3D)](VRageMath.PlaneD.Intersection)|Gets intersection point in Plane.|
|\$1PlaneIntersectionType Intersects(BoundingBoxD)](VRageMath.PlaneD.Intersects)|Checks whether the current PlaneD intersects a specified BoundingBox.|
|\$1void Intersects(ref BoundingBoxD, out PlaneIntersectionType)](VRageMath.PlaneD.Intersects)|Checks whether the current PlaneD intersects a BoundingBox.|
|\$1PlaneIntersectionType Intersects(BoundingFrustumD)](VRageMath.PlaneD.Intersects)|Checks whether the current PlaneD intersects a specified BoundingFrustum.|
|\$1PlaneIntersectionType Intersects(BoundingSphereD)](VRageMath.PlaneD.Intersects)|Checks whether the current PlaneD intersects a specified BoundingSphere.|
|\$1void Intersects(ref BoundingSphere, out PlaneIntersectionType)](VRageMath.PlaneD.Intersects)|Checks whether the current PlaneD intersects a BoundingSphere.|
|\$1void Normalize()](VRageMath.PlaneD.Normalize)|Changes the coefficients of the Normal vector of this PlaneD to make it of unit length.|
|\$1Vector3D ProjectPoint(ref Vector3D)](VRageMath.PlaneD.ProjectPoint)||
|\$1Vector3D RandomPoint()](VRageMath.PlaneD.RandomPoint)||
|\$1string ToString()](VRageMath.PlaneD.ToString)|Returns a String that represents the current PlaneD.|

