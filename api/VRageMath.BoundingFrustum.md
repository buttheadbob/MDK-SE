← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### BoundingFrustum Class

```csharp
public class BoundingFrustum: IEquatable<BoundingFrustum>
```

Defines a frustum and helps determine whether forms intersect with it.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<BoundingFrustum>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\[static int CornerCount](VRageMath.BoundingFrustum.CornerCount)|Specifies the total number of corners (8) in the BoundingFrustum.|

#### Properties

|Member|Description|
|---|---|
|\[Plane Bottom { get; }](VRageMath.BoundingFrustum.Bottom)|Gets the bottom plane of the BoundingFrustum.|
|\[Plane Far { get; }](VRageMath.BoundingFrustum.Far)|Gets the far plane of the BoundingFrustum.|
|\[Plane Item { get; }](VRageMath.BoundingFrustum.Item)||
|\[Plane Left { get; }](VRageMath.BoundingFrustum.Left)|Gets the left plane of the BoundingFrustum.|
|\[Matrix Matrix { get; set; }](VRageMath.BoundingFrustum.Matrix)|Gets or sets the Matrix that describes this bounding frustum.|
|\[Plane Near { get; }](VRageMath.BoundingFrustum.Near)|Gets the near plane of the BoundingFrustum.|
|\[Plane\[] Planes { get; }](VRageMath.BoundingFrustum.Planes)||
|\[Plane Right { get; }](VRageMath.BoundingFrustum.Right)|Gets the right plane of the BoundingFrustum.|
|\[Plane Top { get; }](VRageMath.BoundingFrustum.Top)|Gets the top plane of the BoundingFrustum.|

#### Constructors

|Member|Description|
|---|---|
|\[BoundingFrustum()](VRageMath.BoundingFrustum..ctor)||
|\[BoundingFrustum(Matrix)](VRageMath.BoundingFrustum..ctor)||

#### Methods

|Member|Description|
|---|---|
|\[ContainmentType Contains(ref BoundingBox)](VRageMath.BoundingFrustum.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingBox.|
|\[void Contains(ref BoundingBox, out ContainmentType)](VRageMath.BoundingFrustum.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingBox.|
|\[ContainmentType Contains(BoundingFrustum)](VRageMath.BoundingFrustum.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingFrustum.|
|\[ContainmentType Contains(Vector3)](VRageMath.BoundingFrustum.Contains)|Checks whether the current BoundingFrustum contains the specified point.|
|\[void Contains(ref Vector3, out ContainmentType)](VRageMath.BoundingFrustum.Contains)|Checks whether the current BoundingFrustum contains the specified point.|
|\[ContainmentType Contains(BoundingSphere)](VRageMath.BoundingFrustum.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingSphere.|
|\[void Contains(ref BoundingSphere, out ContainmentType)](VRageMath.BoundingFrustum.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingSphere.|
|\[bool Equals(BoundingFrustum)](VRageMath.BoundingFrustum.Equals)|Determines whether the specified BoundingFrustum is equal to the current BoundingFrustum.|
|\[bool Equals(object)](VRageMath.BoundingFrustum.Equals)|Determines whether the specified Object is equal to the BoundingFrustum.|
|\[Vector3\[] GetCorners()](VRageMath.BoundingFrustum.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustum. ALLOCATION!|
|\[void GetCorners(Vector3\[])](VRageMath.BoundingFrustum.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustum.|
|\[void GetCornersUnsafe(*Vector3)](VRageMath.BoundingFrustum.GetCornersUnsafe)||
|\[int GetHashCode()](VRageMath.BoundingFrustum.GetHashCode)|Gets the hash code for this instance.|
|\[bool Intersects(BoundingBox)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects the specified BoundingBox.|
|\[void Intersects(ref BoundingBox, out bool)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects a BoundingBox.|
|\[bool Intersects(BoundingFrustum)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects the specified BoundingFrustum.|
|\[PlaneIntersectionType Intersects(Plane)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects the specified Plane.|
|\[void Intersects(ref Plane, out PlaneIntersectionType)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects a Plane.|
|\[float? Intersects(Ray)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects the specified Ray.|
|\[void Intersects(ref Ray, out float?)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects a Ray.|
|\[bool Intersects(BoundingSphere)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects the specified BoundingSphere.|
|\[void Intersects(ref BoundingSphere, out bool)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects a BoundingSphere.|
|\[string ToString()](VRageMath.BoundingFrustum.ToString)|Returns a String that represents the current BoundingFrustum.|

