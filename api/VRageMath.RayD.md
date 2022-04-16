← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### RayD Struct

```csharp
public struct RayD: IEquatable<RayD>
```

Defines a ray.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<RayD>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\\%1Vector3D Direction](VRageMath.RayD.Direction)|Unit vector specifying the direction the Ray is pointing.|
|\\%1Vector3D Position](VRageMath.RayD.Position)|Specifies the starting point of the Ray.|

#### Constructors

|Member|Description|
|---|---|
|\\%1RayD(Vector3D, Vector3D)](VRageMath.RayD..ctor)||
|\\%1RayD(ref Vector3D, ref Vector3D)](VRageMath.RayD..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\%1bool Equals(RayD)](VRageMath.RayD.Equals)|Determines whether the specified Ray is equal to the current Ray.|
|\\%1bool Equals(object)](VRageMath.RayD.Equals)|Determines whether two instances of Ray are equal.|
|\\%1int GetHashCode()](VRageMath.RayD.GetHashCode)|Gets the hash code for this instance.|
|\\%1double? Intersects(BoundingBoxD)](VRageMath.RayD.Intersects)|Checks whether the Ray intersects a specified BoundingBox.|
|\\%1void Intersects(ref BoundingBoxD, out double?)](VRageMath.RayD.Intersects)|Checks whether the current Ray intersects a BoundingBox.|
|\\%1double? Intersects(BoundingFrustumD)](VRageMath.RayD.Intersects)|Checks whether the Ray intersects a specified BoundingFrustum.|
|\\%1double? Intersects(PlaneD)](VRageMath.RayD.Intersects)|Determines whether this Ray intersects a specified Plane.|
|\\%1void Intersects(ref PlaneD, out double?)](VRageMath.RayD.Intersects)|Determines whether this Ray intersects a specified Plane.|
|\\%1double? Intersects(BoundingSphereD)](VRageMath.RayD.Intersects)|Checks whether the Ray intersects a specified BoundingSphere.|
|\\%1void Intersects(ref BoundingSphere, out double?)](VRageMath.RayD.Intersects)|Checks whether the current Ray intersects a BoundingSphere.|
|\\%1string ToString()](VRageMath.RayD.ToString)|Returns a String that represents the current Ray.|

