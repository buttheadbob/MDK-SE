← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### BoundingSphere Struct

```csharp
public struct BoundingSphere: IEquatable<BoundingSphere>
```

Defines a sphere.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<BoundingSphere>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\\%1Vector3 Center](VRageMath.BoundingSphere.Center)|The center point of the sphere.|
|\\%1float Radius](VRageMath.BoundingSphere.Radius)|The radius of the sphere.|

#### Constructors

|Member|Description|
|---|---|
|\\%1BoundingSphere(Vector3, float)](VRageMath.BoundingSphere..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\%1static BoundingSphere CreateFromBoundingBox(BoundingBox)](VRageMath.BoundingSphere.CreateFromBoundingBox)|Creates the smallest BoundingSphere that can contain a specified BoundingBox.|
|\\%1static void CreateFromBoundingBox(ref BoundingBox, out BoundingSphere)](VRageMath.BoundingSphere.CreateFromBoundingBox)|Creates the smallest BoundingSphere that can contain a specified BoundingBox.|
|\\%1static BoundingSphere CreateFromFrustum(BoundingFrustum)](VRageMath.BoundingSphere.CreateFromFrustum)|Creates the smallest BoundingSphere that can contain a specified BoundingFrustum.|
|\\%1static BoundingSphere CreateFromPoints(IEnumerable\\%1Vector3>)](VRageMath.BoundingSphere.CreateFromPoints)|Creates a BoundingSphere that can contain a specified list of points.|
|\\%1static BoundingSphere CreateInvalid()](VRageMath.BoundingSphere.CreateInvalid)||
|\\%1static BoundingSphere CreateMerged(BoundingSphere, BoundingSphere)](VRageMath.BoundingSphere.CreateMerged)|Creates a BoundingSphere that contains the two specified BoundingSphere instances.|
|\\%1static void CreateMerged(ref BoundingSphere, ref BoundingSphere, out BoundingSphere)](VRageMath.BoundingSphere.CreateMerged)|Creates a BoundingSphere that contains the two specified BoundingSphere instances.|
|\\%1static void Include(ref BoundingSphere, ref BoundingSphere)](VRageMath.BoundingSphere.Include)||
|\\%1ContainmentType Contains(BoundingBox)](VRageMath.BoundingSphere.Contains)|Checks whether the current BoundingSphere contains the specified BoundingBox.|
|\\%1void Contains(ref BoundingBox, out ContainmentType)](VRageMath.BoundingSphere.Contains)|Checks whether the current BoundingSphere contains the specified BoundingBox.|
|\\%1ContainmentType Contains(BoundingFrustum)](VRageMath.BoundingSphere.Contains)|Checks whether the current BoundingSphere contains the specified BoundingFrustum.|
|\\%1ContainmentType Contains(Vector3)](VRageMath.BoundingSphere.Contains)|Checks whether the current BoundingSphere contains the specified point.|
|\\%1void Contains(ref Vector3, out ContainmentType)](VRageMath.BoundingSphere.Contains)|Checks whether the current BoundingSphere contains the specified point.|
|\\%1ContainmentType Contains(BoundingSphere)](VRageMath.BoundingSphere.Contains)|Checks whether the current BoundingSphere contains the specified BoundingSphere.|
|\\%1void Contains(ref BoundingSphere, out ContainmentType)](VRageMath.BoundingSphere.Contains)|Checks whether the current BoundingSphere contains the specified BoundingSphere.|
|\\%1bool Equals(BoundingSphere)](VRageMath.BoundingSphere.Equals)|Determines whether the specified BoundingSphere is equal to the current BoundingSphere.|
|\\%1bool Equals(object)](VRageMath.BoundingSphere.Equals)|Determines whether the specified Object is equal to the BoundingSphere.|
|\\%1BoundingBox GetBoundingBox()](VRageMath.BoundingSphere.GetBoundingBox)||
|\\%1int GetHashCode()](VRageMath.BoundingSphere.GetHashCode)|Gets the hash code for this instance.|
|\\%1BoundingSphere Include(BoundingSphere)](VRageMath.BoundingSphere.Include)||
|\\%1bool IntersectRaySphere(Ray, out float, out float)](VRageMath.BoundingSphere.IntersectRaySphere)||
|\\%1bool Intersects(BoundingBox)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects with a specified BoundingBox.|
|\\%1void Intersects(ref BoundingBox, out bool)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects a BoundingBox.|
|\\%1bool Intersects(BoundingFrustum)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects with a specified BoundingFrustum.|
|\\%1PlaneIntersectionType Intersects(Plane)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects with a specified Plane.|
|\\%1void Intersects(ref Plane, out PlaneIntersectionType)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects a Plane.|
|\\%1float? Intersects(Ray)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects with a specified Ray.|
|\\%1void Intersects(ref Ray, out float?)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects a Ray.|
|\\%1bool Intersects(BoundingSphere)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects with a specified BoundingSphere.|
|\\%1void Intersects(ref BoundingSphere, out bool)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects another BoundingSphere.|
|\\%1string ToString()](VRageMath.BoundingSphere.ToString)|Returns a String that represents the current BoundingSphere.|
|\\%1BoundingSphere Transform(Matrix)](VRageMath.BoundingSphere.Transform)|Translates and scales the BoundingSphere using a given Matrix.|
|\\%1void Transform(ref Matrix, out BoundingSphere)](VRageMath.BoundingSphere.Transform)|Translates and scales the BoundingSphere using a given Matrix.|
|\\%1BoundingSphere Translate(ref Vector3)](VRageMath.BoundingSphere.Translate)||

