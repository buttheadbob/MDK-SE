← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### Plane Struct

```csharp
public struct Plane: IEquatable<Plane\>
```

Defines a plane.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<Plane\>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\$1float D](VRageMath.Plane.D)|The distance of the Plane along its normal from the origin. Note: Be careful! The distance is signed and is the opposite of what people usually expect. If you look closely at the plane equation: (n dot P) - D = 0, you'll realize that D = - (n dot P) (that is, negative instead of positive)|
|\$1Vector3 Normal](VRageMath.Plane.Normal)|The normal vector of the Plane.|

#### Constructors

|Member|Description|
|---|---|
|\$1Plane(float, float, float, float)](VRageMath.Plane..ctor)||
|\$1Plane(Vector3, float)](VRageMath.Plane..ctor)||
|\$1Plane(Vector3, Vector3)](VRageMath.Plane..ctor)||
|\$1Plane(Vector4)](VRageMath.Plane..ctor)||
|\$1Plane(Vector3, Vector3, Vector3)](VRageMath.Plane..ctor)||
|\$1Plane(ref Vector3, ref Vector3, ref Vector3)](VRageMath.Plane..ctor)||

#### Methods

|Member|Description|
|---|---|
|\$1static Plane Normalize(Plane)](VRageMath.Plane.Normalize)|Changes the coefficients of the Normal vector of a Plane to make it of unit length.|
|\$1static void Normalize(ref Plane, out Plane)](VRageMath.Plane.Normalize)|Changes the coefficients of the Normal vector of a Plane to make it of unit length.|
|\$1static Plane Transform(Plane, Matrix)](VRageMath.Plane.Transform)|Transforms a normalized Plane by a Matrix.|
|\$1static void Transform(ref Plane, ref Matrix, out Plane)](VRageMath.Plane.Transform)|Transforms a normalized Plane by a Matrix.|
|\$1float Dot(Vector4)](VRageMath.Plane.Dot)|Calculates the dot product of a specified Vector4 and this Plane.|
|\$1void Dot(ref Vector4, out float)](VRageMath.Plane.Dot)|Calculates the dot product of a specified Vector4 and this Plane.|
|\$1float DotCoordinate(Vector3)](VRageMath.Plane.DotCoordinate)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane plus the distance (D) value of the Plane.|
|\$1void DotCoordinate(ref Vector3, out float)](VRageMath.Plane.DotCoordinate)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane plus the distance (D) value of the Plane.|
|\$1double DotNormal(Vector3D)](VRageMath.Plane.DotNormal)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane.|
|\$1void DotNormal(ref Vector3, out float)](VRageMath.Plane.DotNormal)|Returns the dot product of a specified Vector3 and the Normal vector of this Plane.|
|\$1bool Equals(Plane)](VRageMath.Plane.Equals)|Determines whether the specified Plane is equal to the Plane.|
|\$1bool Equals(object)](VRageMath.Plane.Equals)|Determines whether the specified Object is equal to the Plane.|
|\$1int GetHashCode()](VRageMath.Plane.GetHashCode)|Gets the hash code for this object.|
|\$1Vector3D Intersection(ref Vector3D, ref Vector3D)](VRageMath.Plane.Intersection)|Gets intersection point in Plane.|
|\$1PlaneIntersectionType Intersects(BoundingBox)](VRageMath.Plane.Intersects)|Checks whether the current Plane intersects a specified BoundingBox.|
|\$1void Intersects(ref BoundingBox, out PlaneIntersectionType)](VRageMath.Plane.Intersects)|Checks whether the current Plane intersects a BoundingBox.|
|\$1PlaneIntersectionType Intersects(BoundingFrustum)](VRageMath.Plane.Intersects)|Checks whether the current Plane intersects a specified BoundingFrustum.|
|\$1PlaneIntersectionType Intersects(BoundingSphere)](VRageMath.Plane.Intersects)|Checks whether the current Plane intersects a specified BoundingSphere.|
|\$1void Intersects(ref BoundingSphere, out PlaneIntersectionType)](VRageMath.Plane.Intersects)|Checks whether the current Plane intersects a BoundingSphere.|
|\$1void Normalize()](VRageMath.Plane.Normalize)|Changes the coefficients of the Normal vector of this Plane to make it of unit length.|
|\$1Vector3 RandomPoint()](VRageMath.Plane.RandomPoint)||
|\$1string ToString()](VRageMath.Plane.ToString)|Returns a String that represents the current Plane.|

