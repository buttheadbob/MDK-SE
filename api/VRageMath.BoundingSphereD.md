← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### BoundingSphereD Struct

```csharp
public struct BoundingSphereD: IEquatable<BoundingSphereD>
```

Defines a sphere.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<BoundingSphereD>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\\%1Vector3D Center](VRageMath.BoundingSphereD.Center)|The center point of the sphere.|
|\\%1double Radius](VRageMath.BoundingSphereD.Radius)|The radius of the sphere.|

#### Constructors

|Member|Description|
|---|---|
|\\%1BoundingSphereD(Vector3D, double)](VRageMath.BoundingSphereD..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\%1static BoundingSphereD CreateFromBoundingBox(BoundingBoxD)](VRageMath.BoundingSphereD.CreateFromBoundingBox)|Creates the smallest BoundingSphereD that can contain a specified BoundingBoxD.|
|\\%1static void CreateFromBoundingBox(ref BoundingBoxD, out BoundingSphereD)](VRageMath.BoundingSphereD.CreateFromBoundingBox)|Creates the smallest BoundingSphereD that can contain a specified BoundingBoxD.|
|\\%1static BoundingSphereD CreateFromFrustum(BoundingFrustumD)](VRageMath.BoundingSphereD.CreateFromFrustum)|Creates the smallest BoundingSphereD that can contain a specified BoundingFrustum.|
|\\%1static BoundingSphereD CreateFromPoints(Vector3D\\%1])](VRageMath.BoundingSphereD.CreateFromPoints)|Creates a BoundingSphereD that can contain a specified list of points.|
|\\%1static BoundingSphereD CreateInvalid()](VRageMath.BoundingSphereD.CreateInvalid)||
|\\%1static BoundingSphereD CreateMerged(BoundingSphereD, BoundingSphereD)](VRageMath.BoundingSphereD.CreateMerged)|Creates a BoundingSphereD that contains the two specified BoundingSphereD instances.|
|\\%1static void CreateMerged(ref BoundingSphereD, ref BoundingSphereD, out BoundingSphereD)](VRageMath.BoundingSphereD.CreateMerged)|Creates a BoundingSphereD that contains the two specified BoundingSphereD instances.|
|\\%1static void Include(ref BoundingSphereD, ref BoundingSphereD)](VRageMath.BoundingSphereD.Include)||
|\\%1ContainmentType Contains(BoundingBoxD)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingBoxD.|
|\\%1void Contains(ref BoundingBoxD, out ContainmentType)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingBoxD.|
|\\%1ContainmentType Contains(BoundingFrustumD)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingFrustum.|
|\\%1ContainmentType Contains(Vector3D)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified point.|
|\\%1void Contains(ref Vector3D, out ContainmentType)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified point.|
|\\%1ContainmentType Contains(BoundingSphereD)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingSphereD.|
|\\%1void Contains(ref BoundingSphereD, out ContainmentType)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingSphereD.|
|\\%1bool Equals(BoundingSphereD)](VRageMath.BoundingSphereD.Equals)|Determines whether the specified BoundingSphereD is equal to the current BoundingSphereD.|
|\\%1bool Equals(object)](VRageMath.BoundingSphereD.Equals)|Determines whether the specified Object is equal to the BoundingSphereD.|
|\\%1BoundingBoxD GetBoundingBox()](VRageMath.BoundingSphereD.GetBoundingBox)||
|\\%1int GetHashCode()](VRageMath.BoundingSphereD.GetHashCode)|Gets the hash code for this instance.|
|\\%1BoundingSphereD Include(BoundingSphereD)](VRageMath.BoundingSphereD.Include)||
|\\%1bool IntersectRaySphere(RayD, out double, out double)](VRageMath.BoundingSphereD.IntersectRaySphere)|NOTE: This function doesn't calculate the normal because it's easily derived for a sphere (p - center).|
|\\%1bool Intersects(BoundingBoxD)](VRageMath.BoundingSphereD.Intersects)|Checks whether the current BoundingSphereD intersects with a specified BoundingBoxD.|
|\\%1void Intersects(ref BoundingBoxD, out bool)](VRageMath.BoundingSphereD.Intersects)|Checks whether the current BoundingSphereD intersects a BoundingBoxD.|
|\\%1double? Intersects(RayD)](VRageMath.BoundingSphereD.Intersects)||
|\\%1bool Intersects(BoundingFrustumD)](VRageMath.BoundingSphereD.Intersects)|Checks whether the current BoundingSphereD intersects with a specified BoundingFrustum.|
|\\%1bool Intersects(BoundingSphereD)](VRageMath.BoundingSphereD.Intersects)|Checks whether the current BoundingSphereD intersects with a specified BoundingSphereD.|
|\\%1void Intersects(ref BoundingSphereD, out bool)](VRageMath.BoundingSphereD.Intersects)|Checks whether the current BoundingSphereD intersects another BoundingSphereD.|
|\\%1Vector3D RandomToUniformPointInSphere(double, double, double)](VRageMath.BoundingSphereD.RandomToUniformPointInSphere)|If ranX, ranY, ranZ are uniformly distributed across ranges <0,1>, Resulting point will be uniformly distributed inside sphere|
|\\%1Vector3D? RandomToUniformPointInSphereWithInnerCutout(double, double, double, double)](VRageMath.BoundingSphereD.RandomToUniformPointInSphereWithInnerCutout)|Similar to RandomToUniformPointInSphere(...) but excludes points within distance of cutoutRadius from center. (Results are randomly distributed in the shape that remains from sphere that had another sphere cut out from center. )|
|\\%1Vector3D RandomToUniformPointOnSphere(double, double)](VRageMath.BoundingSphereD.RandomToUniformPointOnSphere)||
|\\%1string ToString()](VRageMath.BoundingSphereD.ToString)|Returns a String that represents the current BoundingSphereD.|
|\\%1BoundingSphereD Transform(MatrixD)](VRageMath.BoundingSphereD.Transform)|Translates and scales the BoundingSphereD using a given Matrix.|
|\\%1void Transform(ref MatrixD, out BoundingSphereD)](VRageMath.BoundingSphereD.Transform)|Translates and scales the BoundingSphereD using a given Matrix.|

