← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### BoundingSphere Struct

```csharp
public struct BoundingSphere: IEquatable<VRageMath.BoundingSphere>
```

Defines a sphere.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<VRageMath.BoundingSphere>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[Center](VRageMath.BoundingSphere.Center)|The center point of the sphere.|
|[Radius](VRageMath.BoundingSphere.Radius)|The radius of the sphere.|

#### Constructors

|Member|Description|
|---|---|
|[BoundingSphere(Vector3, float)](VRageMath.BoundingSphere..ctor)||

#### Methods

|Member|Description|
|---|---|
|[Equals(BoundingSphere)](VRageMath.BoundingSphere.Equals)|Determines whether the specified BoundingSphere is equal to the current BoundingSphere.|
|[Equals(object)](VRageMath.BoundingSphere.Equals)|Determines whether the specified Object is equal to the BoundingSphere.|
|[GetHashCode()](VRageMath.BoundingSphere.GetHashCode)|Gets the hash code for this instance.|
|[ToString()](VRageMath.BoundingSphere.ToString)|Returns a String that represents the current BoundingSphere.|
|[CreateMerged(BoundingSphere, BoundingSphere)](VRageMath.BoundingSphere.CreateMerged)|Creates a BoundingSphere that contains the two specified BoundingSphere instances.|
|[CreateMerged(ref BoundingSphere, ref BoundingSphere, out BoundingSphere)](VRageMath.BoundingSphere.CreateMerged)|Creates a BoundingSphere that contains the two specified BoundingSphere instances.|
|[CreateFromBoundingBox(BoundingBox)](VRageMath.BoundingSphere.CreateFromBoundingBox)|Creates the smallest BoundingSphere that can contain a specified BoundingBox.|
|[CreateFromBoundingBox(ref BoundingBox, out BoundingSphere)](VRageMath.BoundingSphere.CreateFromBoundingBox)|Creates the smallest BoundingSphere that can contain a specified BoundingBox.|
|[CreateFromPoints(IEnumerable)](VRageMath.BoundingSphere.CreateFromPoints)|Creates a BoundingSphere that can contain a specified list of points.|
|[CreateFromFrustum(BoundingFrustum)](VRageMath.BoundingSphere.CreateFromFrustum)|Creates the smallest BoundingSphere that can contain a specified BoundingFrustum.|
|[Intersects(BoundingBox)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects with a specified BoundingBox.|
|[Intersects(ref BoundingBox, out bool)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects a BoundingBox.|
|[Intersects(BoundingFrustum)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects with a specified BoundingFrustum.|
|[Intersects(Plane)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects with a specified Plane.|
|[Intersects(ref Plane, out PlaneIntersectionType)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects a Plane.|
|[Intersects(Ray)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects with a specified Ray.|
|[Intersects(ref Ray, out float?)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects a Ray.|
|[Intersects(BoundingSphere)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects with a specified BoundingSphere.|
|[Intersects(ref BoundingSphere, out bool)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects another BoundingSphere.|
|[Contains(BoundingBox)](VRageMath.BoundingSphere.Contains)|Checks whether the current BoundingSphere contains the specified BoundingBox.|
|[Contains(ref BoundingBox, out ContainmentType)](VRageMath.BoundingSphere.Contains)|Checks whether the current BoundingSphere contains the specified BoundingBox.|
|[Contains(BoundingFrustum)](VRageMath.BoundingSphere.Contains)|Checks whether the current BoundingSphere contains the specified BoundingFrustum.|
|[Contains(Vector3)](VRageMath.BoundingSphere.Contains)|Checks whether the current BoundingSphere contains the specified point.|
|[Contains(ref Vector3, out ContainmentType)](VRageMath.BoundingSphere.Contains)|Checks whether the current BoundingSphere contains the specified point.|
|[Contains(BoundingSphere)](VRageMath.BoundingSphere.Contains)|Checks whether the current BoundingSphere contains the specified BoundingSphere.|
|[Contains(ref BoundingSphere, out ContainmentType)](VRageMath.BoundingSphere.Contains)|Checks whether the current BoundingSphere contains the specified BoundingSphere.|
|[Transform(Matrix)](VRageMath.BoundingSphere.Transform)|Translates and scales the BoundingSphere using a given Matrix.|
|[Transform(ref Matrix, out BoundingSphere)](VRageMath.BoundingSphere.Transform)|Translates and scales the BoundingSphere using a given Matrix.|
|[Translate(ref Vector3)](VRageMath.BoundingSphere.Translate)||
|[IntersectRaySphere(Ray, out float, out float)](VRageMath.BoundingSphere.IntersectRaySphere)||
|[Include(BoundingSphere)](VRageMath.BoundingSphere.Include)||
|[Include(ref BoundingSphere, ref BoundingSphere)](VRageMath.BoundingSphere.Include)||
|[CreateInvalid()](VRageMath.BoundingSphere.CreateInvalid)||

