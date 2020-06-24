← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### BoundingSphereD Struct

```csharp
public struct BoundingSphereD: IEquatable<VRageMath.BoundingSphereD>
```

Defines a sphere.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<VRageMath.BoundingSphereD>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[Center](VRageMath.BoundingSphereD.Center)|The center point of the sphere.|
|[Radius](VRageMath.BoundingSphereD.Radius)|The radius of the sphere.|

#### Constructors

|Member|Description|
|---|---|
|[BoundingSphereD(Vector3D, double)](VRageMath.BoundingSphereD..ctor)||

#### Methods

|Member|Description|
|---|---|
|[Equals(BoundingSphereD)](VRageMath.BoundingSphereD.Equals)|Determines whether the specified BoundingSphereD is equal to the current BoundingSphereD.|
|[Equals(object)](VRageMath.BoundingSphereD.Equals)|Determines whether the specified Object is equal to the BoundingSphereD.|
|[GetHashCode()](VRageMath.BoundingSphereD.GetHashCode)|Gets the hash code for this instance.|
|[ToString()](VRageMath.BoundingSphereD.ToString)|Returns a String that represents the current BoundingSphereD.|
|[CreateMerged(BoundingSphereD, BoundingSphereD)](VRageMath.BoundingSphereD.CreateMerged)|Creates a BoundingSphereD that contains the two specified BoundingSphereD instances.|
|[CreateMerged(ref BoundingSphereD, ref BoundingSphereD, out BoundingSphereD)](VRageMath.BoundingSphereD.CreateMerged)|Creates a BoundingSphereD that contains the two specified BoundingSphereD instances.|
|[CreateFromBoundingBox(BoundingBoxD)](VRageMath.BoundingSphereD.CreateFromBoundingBox)|Creates the smallest BoundingSphereD that can contain a specified BoundingBoxD.|
|[CreateFromBoundingBox(ref BoundingBoxD, out BoundingSphereD)](VRageMath.BoundingSphereD.CreateFromBoundingBox)|Creates the smallest BoundingSphereD that can contain a specified BoundingBoxD.|
|[CreateFromPoints(Vector3D[])](VRageMath.BoundingSphereD.CreateFromPoints)|Creates a BoundingSphereD that can contain a specified list of points.|
|[CreateFromFrustum(BoundingFrustumD)](VRageMath.BoundingSphereD.CreateFromFrustum)|Creates the smallest BoundingSphereD that can contain a specified BoundingFrustum.|
|[Intersects(BoundingBoxD)](VRageMath.BoundingSphereD.Intersects)|Checks whether the current BoundingSphereD intersects with a specified BoundingBoxD.|
|[Intersects(ref BoundingBoxD, out bool)](VRageMath.BoundingSphereD.Intersects)|Checks whether the current BoundingSphereD intersects a BoundingBoxD.|
|[Intersects(RayD)](VRageMath.BoundingSphereD.Intersects)||
|[Intersects(BoundingFrustumD)](VRageMath.BoundingSphereD.Intersects)|Checks whether the current BoundingSphereD intersects with a specified BoundingFrustum.|
|[Intersects(BoundingSphereD)](VRageMath.BoundingSphereD.Intersects)|Checks whether the current BoundingSphereD intersects with a specified BoundingSphereD.|
|[Intersects(ref BoundingSphereD, out bool)](VRageMath.BoundingSphereD.Intersects)|Checks whether the current BoundingSphereD intersects another BoundingSphereD.|
|[Contains(BoundingBoxD)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingBoxD.|
|[Contains(ref BoundingBoxD, out ContainmentType)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingBoxD.|
|[Contains(BoundingFrustumD)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingFrustum.|
|[Contains(Vector3D)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified point.|
|[Contains(ref Vector3D, out ContainmentType)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified point.|
|[Contains(BoundingSphereD)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingSphereD.|
|[Contains(ref BoundingSphereD, out ContainmentType)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingSphereD.|
|[Transform(MatrixD)](VRageMath.BoundingSphereD.Transform)|Translates and scales the BoundingSphereD using a given Matrix.|
|[Transform(ref MatrixD, out BoundingSphereD)](VRageMath.BoundingSphereD.Transform)|Translates and scales the BoundingSphereD using a given Matrix.|
|[IntersectRaySphere(RayD, out double, out double)](VRageMath.BoundingSphereD.IntersectRaySphere)||
|[Include(BoundingSphereD)](VRageMath.BoundingSphereD.Include)||
|[Include(ref BoundingSphereD, ref BoundingSphereD)](VRageMath.BoundingSphereD.Include)||
|[CreateInvalid()](VRageMath.BoundingSphereD.CreateInvalid)||
|[RandomToUniformPointInSphere(double, double, double)](VRageMath.BoundingSphereD.RandomToUniformPointInSphere)||
|[RandomToUniformPointInSphereWithInnerCutout(double, double, double, double)](VRageMath.BoundingSphereD.RandomToUniformPointInSphereWithInnerCutout)|Similar to RandomToUniformPointInSphere(...) but excludes points within distance of cutoutRadius from center. (Results are randomly distributed in the shape that remains from sphere that had another sphere cut out from center. )|
|[RandomToUniformPointOnSphere(double, double)](VRageMath.BoundingSphereD.RandomToUniformPointOnSphere)||
|[GetBoundingBox()](VRageMath.BoundingSphereD.GetBoundingBox)||

