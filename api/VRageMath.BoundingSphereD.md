← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### BoundingSphereD Struct

```csharp
public struct BoundingSphereD: IEquatable
```

Defines a sphere.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<VRageMath.BoundingSphereD>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[Vector3D Center](VRageMath.BoundingSphereD.Center)|The center point of the sphere.|
|[double Radius](VRageMath.BoundingSphereD.Radius)|The radius of the sphere.|

#### Constructors

|Member|Description|
|---|---|
|[BoundingSphereD(Vector3D, double)](VRageMath.BoundingSphereD..ctor)||

#### Methods

|Member|Description|
|---|---|
|[static BoundingSphereD CreateFromBoundingBox(BoundingBoxD)](VRageMath.BoundingSphereD.CreateFromBoundingBox)|Creates the smallest BoundingSphereD that can contain a specified BoundingBoxD.|
|[static void CreateFromBoundingBox(ref BoundingBoxD, out BoundingSphereD)](VRageMath.BoundingSphereD.CreateFromBoundingBox)|Creates the smallest BoundingSphereD that can contain a specified BoundingBoxD.|
|[static BoundingSphereD CreateFromFrustum(BoundingFrustumD)](VRageMath.BoundingSphereD.CreateFromFrustum)|Creates the smallest BoundingSphereD that can contain a specified BoundingFrustum.|
|[static BoundingSphereD CreateFromPoints(Vector3D[])](VRageMath.BoundingSphereD.CreateFromPoints)|Creates a BoundingSphereD that can contain a specified list of points.|
|[static BoundingSphereD CreateInvalid()](VRageMath.BoundingSphereD.CreateInvalid)||
|[static BoundingSphereD CreateMerged(BoundingSphereD, BoundingSphereD)](VRageMath.BoundingSphereD.CreateMerged)|Creates a BoundingSphereD that contains the two specified BoundingSphereD instances.|
|[static void CreateMerged(ref BoundingSphereD, ref BoundingSphereD, out BoundingSphereD)](VRageMath.BoundingSphereD.CreateMerged)|Creates a BoundingSphereD that contains the two specified BoundingSphereD instances.|
|[static void Include(ref BoundingSphereD, ref BoundingSphereD)](VRageMath.BoundingSphereD.Include)||
|[ContainmentType Contains(BoundingBoxD)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingBoxD.|
|[void Contains(ref BoundingBoxD, out ContainmentType)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingBoxD.|
|[ContainmentType Contains(BoundingFrustumD)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingFrustum.|
|[ContainmentType Contains(Vector3D)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified point.|
|[void Contains(ref Vector3D, out ContainmentType)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified point.|
|[ContainmentType Contains(BoundingSphereD)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingSphereD.|
|[void Contains(ref BoundingSphereD, out ContainmentType)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingSphereD.|
|[bool Equals(BoundingSphereD)](VRageMath.BoundingSphereD.Equals)|Determines whether the specified BoundingSphereD is equal to the current BoundingSphereD.|
|[bool Equals(object)](VRageMath.BoundingSphereD.Equals)|Determines whether the specified Object is equal to the BoundingSphereD.|
|[BoundingBoxD GetBoundingBox()](VRageMath.BoundingSphereD.GetBoundingBox)||
|[int GetHashCode()](VRageMath.BoundingSphereD.GetHashCode)|Gets the hash code for this instance.|
|[BoundingSphereD Include(BoundingSphereD)](VRageMath.BoundingSphereD.Include)||
|[bool IntersectRaySphere(RayD, out double, out double)](VRageMath.BoundingSphereD.IntersectRaySphere)|NOTE: This function doesn't calculate the normal because it's easily derived for a sphere (p - center).|
|[bool Intersects(BoundingBoxD)](VRageMath.BoundingSphereD.Intersects)|Checks whether the current BoundingSphereD intersects with a specified BoundingBoxD.|
|[void Intersects(ref BoundingBoxD, out bool)](VRageMath.BoundingSphereD.Intersects)|Checks whether the current BoundingSphereD intersects a BoundingBoxD.|
|[double? Intersects(RayD)](VRageMath.BoundingSphereD.Intersects)||
|[bool Intersects(BoundingFrustumD)](VRageMath.BoundingSphereD.Intersects)|Checks whether the current BoundingSphereD intersects with a specified BoundingFrustum.|
|[bool Intersects(BoundingSphereD)](VRageMath.BoundingSphereD.Intersects)|Checks whether the current BoundingSphereD intersects with a specified BoundingSphereD.|
|[void Intersects(ref BoundingSphereD, out bool)](VRageMath.BoundingSphereD.Intersects)|Checks whether the current BoundingSphereD intersects another BoundingSphereD.|
|[Vector3D RandomToUniformPointInSphere(double, double, double)](VRageMath.BoundingSphereD.RandomToUniformPointInSphere)|If ranX, ranY, ranZ are uniformly distributed across ranges <0,1>, Resulting point will be uniformly distributed inside sphere|
|[Vector3D? RandomToUniformPointInSphereWithInnerCutout(double, double, double, double)](VRageMath.BoundingSphereD.RandomToUniformPointInSphereWithInnerCutout)|Similar to RandomToUniformPointInSphere(...) but excludes points within distance of cutoutRadius from center. (Results are randomly distributed in the shape that remains from sphere that had another sphere cut out from center. )|
|[Vector3D RandomToUniformPointOnSphere(double, double)](VRageMath.BoundingSphereD.RandomToUniformPointOnSphere)||
|[string ToString()](VRageMath.BoundingSphereD.ToString)|Returns a String that represents the current BoundingSphereD.|
|[BoundingSphereD Transform(MatrixD)](VRageMath.BoundingSphereD.Transform)|Translates and scales the BoundingSphereD using a given Matrix.|
|[void Transform(ref MatrixD, out BoundingSphereD)](VRageMath.BoundingSphereD.Transform)|Translates and scales the BoundingSphereD using a given Matrix.|

