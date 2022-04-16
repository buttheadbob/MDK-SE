← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### BoundingSphere Struct

```csharp
public struct BoundingSphere: IEquatable<BoundingSphere>
```

Defines a sphere.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable&lt;BoundingSphere&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[Vector3 Center](VRageMath.BoundingSphere.Center)|The center point of the sphere.|
|[float Radius](VRageMath.BoundingSphere.Radius)|The radius of the sphere.|

#### Constructors

|Member|Description|
|---|---|
|[BoundingSphere(Vector3, float)](VRageMath.BoundingSphere..ctor)||

#### Methods

|Member|Description|
|---|---|
|[static BoundingSphere CreateFromBoundingBox(BoundingBox)](VRageMath.BoundingSphere.CreateFromBoundingBox)|Creates the smallest BoundingSphere that can contain a specified BoundingBox.|
|[static void CreateFromBoundingBox(ref BoundingBox, out BoundingSphere)](VRageMath.BoundingSphere.CreateFromBoundingBox)|Creates the smallest BoundingSphere that can contain a specified BoundingBox.|
|[static BoundingSphere CreateFromFrustum(BoundingFrustum)](VRageMath.BoundingSphere.CreateFromFrustum)|Creates the smallest BoundingSphere that can contain a specified BoundingFrustum.|
|[static BoundingSphere CreateFromPoints(IEnumerable&lt;Vector3&gt;)](VRageMath.BoundingSphere.CreateFromPoints)|Creates a BoundingSphere that can contain a specified list of points.|
|[static BoundingSphere CreateInvalid()](VRageMath.BoundingSphere.CreateInvalid)||
|[static BoundingSphere CreateMerged(BoundingSphere, BoundingSphere)](VRageMath.BoundingSphere.CreateMerged)|Creates a BoundingSphere that contains the two specified BoundingSphere instances.|
|[static void CreateMerged(ref BoundingSphere, ref BoundingSphere, out BoundingSphere)](VRageMath.BoundingSphere.CreateMerged)|Creates a BoundingSphere that contains the two specified BoundingSphere instances.|
|[static void Include(ref BoundingSphere, ref BoundingSphere)](VRageMath.BoundingSphere.Include)||
|[ContainmentType Contains(BoundingBox)](VRageMath.BoundingSphere.Contains)|Checks whether the current BoundingSphere contains the specified BoundingBox.|
|[void Contains(ref BoundingBox, out ContainmentType)](VRageMath.BoundingSphere.Contains)|Checks whether the current BoundingSphere contains the specified BoundingBox.|
|[ContainmentType Contains(BoundingFrustum)](VRageMath.BoundingSphere.Contains)|Checks whether the current BoundingSphere contains the specified BoundingFrustum.|
|[ContainmentType Contains(Vector3)](VRageMath.BoundingSphere.Contains)|Checks whether the current BoundingSphere contains the specified point.|
|[void Contains(ref Vector3, out ContainmentType)](VRageMath.BoundingSphere.Contains)|Checks whether the current BoundingSphere contains the specified point.|
|[ContainmentType Contains(BoundingSphere)](VRageMath.BoundingSphere.Contains)|Checks whether the current BoundingSphere contains the specified BoundingSphere.|
|[void Contains(ref BoundingSphere, out ContainmentType)](VRageMath.BoundingSphere.Contains)|Checks whether the current BoundingSphere contains the specified BoundingSphere.|
|[bool Equals(BoundingSphere)](VRageMath.BoundingSphere.Equals)|Determines whether the specified BoundingSphere is equal to the current BoundingSphere.|
|[bool Equals(object)](VRageMath.BoundingSphere.Equals)|Determines whether the specified Object is equal to the BoundingSphere.|
|[BoundingBox GetBoundingBox()](VRageMath.BoundingSphere.GetBoundingBox)||
|[int GetHashCode()](VRageMath.BoundingSphere.GetHashCode)|Gets the hash code for this instance.|
|[BoundingSphere Include(BoundingSphere)](VRageMath.BoundingSphere.Include)||
|[bool IntersectRaySphere(Ray, out float, out float)](VRageMath.BoundingSphere.IntersectRaySphere)||
|[bool Intersects(BoundingBox)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects with a specified BoundingBox.|
|[void Intersects(ref BoundingBox, out bool)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects a BoundingBox.|
|[bool Intersects(BoundingFrustum)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects with a specified BoundingFrustum.|
|[PlaneIntersectionType Intersects(Plane)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects with a specified Plane.|
|[void Intersects(ref Plane, out PlaneIntersectionType)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects a Plane.|
|[float? Intersects(Ray)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects with a specified Ray.|
|[void Intersects(ref Ray, out float?)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects a Ray.|
|[bool Intersects(BoundingSphere)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects with a specified BoundingSphere.|
|[void Intersects(ref BoundingSphere, out bool)](VRageMath.BoundingSphere.Intersects)|Checks whether the current BoundingSphere intersects another BoundingSphere.|
|[string ToString()](VRageMath.BoundingSphere.ToString)|Returns a String that represents the current BoundingSphere.|
|[BoundingSphere Transform(Matrix)](VRageMath.BoundingSphere.Transform)|Translates and scales the BoundingSphere using a given Matrix.|
|[void Transform(ref Matrix, out BoundingSphere)](VRageMath.BoundingSphere.Transform)|Translates and scales the BoundingSphere using a given Matrix.|
|[BoundingSphere Translate(ref Vector3)](VRageMath.BoundingSphere.Translate)||

