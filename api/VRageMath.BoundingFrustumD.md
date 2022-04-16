← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### BoundingFrustumD Class

```csharp
public class BoundingFrustumD: IEquatable<BoundingFrustumD>
```

Defines a frustum and helps determine whether forms intersect with it.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable&lt;BoundingFrustumD&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

[static int CornerCount](VRageMath.BoundingFrustumD.CornerCount)

> Specifies the total number of corners (8) in the BoundingFrustumD.

#### Properties

[PlaneD Bottom { get; }](VRageMath.BoundingFrustumD.Bottom)

> Gets the bottom plane of the BoundingFrustumD.

[PlaneD Far { get; }](VRageMath.BoundingFrustumD.Far)

> Gets the far plane of the BoundingFrustumD.

[PlaneD Item { get; }](VRageMath.BoundingFrustumD.Item)

> 

[PlaneD Left { get; }](VRageMath.BoundingFrustumD.Left)

> Gets the left plane of the BoundingFrustumD.

[MatrixD Matrix { get; set; }](VRageMath.BoundingFrustumD.Matrix)

> Gets or sets the Matrix that describes this bounding frustum.

[PlaneD Near { get; }](VRageMath.BoundingFrustumD.Near)

> Gets the near plane of the BoundingFrustumD.

[PlaneD Right { get; }](VRageMath.BoundingFrustumD.Right)

> Gets the right plane of the BoundingFrustumD.

[PlaneD Top { get; }](VRageMath.BoundingFrustumD.Top)

> Gets the top plane of the BoundingFrustumD.

#### Constructors

[BoundingFrustumD()](VRageMath.BoundingFrustumD..ctor)

> 

[BoundingFrustumD(MatrixD)](VRageMath.BoundingFrustumD..ctor)

> 

#### Methods

[ContainmentType Contains(BoundingBoxD)](VRageMath.BoundingFrustumD.Contains)

> Checks whether the current BoundingFrustumD contains the specified BoundingBoxD.

[void Contains(ref BoundingBoxD, out ContainmentType)](VRageMath.BoundingFrustumD.Contains)

> Checks whether the current BoundingFrustumD contains the specified BoundingBoxD.

[ContainmentType Contains(BoundingFrustumD)](VRageMath.BoundingFrustumD.Contains)

> Checks whether the current BoundingFrustumD contains the specified BoundingFrustumD.

[ContainmentType Contains(Vector3D)](VRageMath.BoundingFrustumD.Contains)

> Checks whether the current BoundingFrustumD contains the specified point.

[void Contains(ref Vector3D, out ContainmentType)](VRageMath.BoundingFrustumD.Contains)

> Checks whether the current BoundingFrustumD contains the specified point.

[ContainmentType Contains(BoundingSphereD)](VRageMath.BoundingFrustumD.Contains)

> Checks whether the current BoundingFrustumD contains the specified BoundingSphere.

[void Contains(ref BoundingSphereD, out ContainmentType)](VRageMath.BoundingFrustumD.Contains)

> Checks whether the current BoundingFrustumD contains the specified BoundingSphere.

[bool Equals(BoundingFrustumD)](VRageMath.BoundingFrustumD.Equals)

> Determines whether the specified BoundingFrustumD is equal to the current BoundingFrustumD.

[bool Equals(object)](VRageMath.BoundingFrustumD.Equals)

> Determines whether the specified Object is equal to the BoundingFrustumD.

[Vector3D&#91&#93; GetCorners()](VRageMath.BoundingFrustumD.GetCorners)

> Gets an array of points that make up the corners of the BoundingFrustumD. ALLOCATION!

[void GetCorners(Vector3D&#91&#93;)](VRageMath.BoundingFrustumD.GetCorners)

> Gets an array of points that make up the corners of the BoundingFrustumD.

[void GetCornersUnsafe(*Vector3D)](VRageMath.BoundingFrustumD.GetCornersUnsafe)

> 

[int GetHashCode()](VRageMath.BoundingFrustumD.GetHashCode)

> Gets the hash code for this instance.

[bool Intersects(BoundingBoxD)](VRageMath.BoundingFrustumD.Intersects)

> Checks whether the current BoundingFrustumD intersects the specified BoundingBoxD.

[void Intersects(ref BoundingBoxD, out bool)](VRageMath.BoundingFrustumD.Intersects)

> Checks whether the current BoundingFrustumD intersects a BoundingBoxD.

[bool Intersects(BoundingFrustumD)](VRageMath.BoundingFrustumD.Intersects)

> Checks whether the current BoundingFrustumD intersects the specified BoundingFrustumD.

[PlaneIntersectionType Intersects(PlaneD)](VRageMath.BoundingFrustumD.Intersects)

> Checks whether the current BoundingFrustumD intersects the specified Plane.

[void Intersects(ref PlaneD, out PlaneIntersectionType)](VRageMath.BoundingFrustumD.Intersects)

> Checks whether the current BoundingFrustumD intersects a Plane.

[double? Intersects(RayD)](VRageMath.BoundingFrustumD.Intersects)

> Checks whether the current BoundingFrustumD intersects the specified Ray.

[void Intersects(ref RayD, out double?)](VRageMath.BoundingFrustumD.Intersects)

> Checks whether the current BoundingFrustumD intersects a Ray.

[bool Intersects(BoundingSphereD)](VRageMath.BoundingFrustumD.Intersects)

> Checks whether the current BoundingFrustumD intersects the specified BoundingSphere.

[void Intersects(ref BoundingSphereD, out bool)](VRageMath.BoundingFrustumD.Intersects)

> Checks whether the current BoundingFrustumD intersects a BoundingSphere.

[string ToString()](VRageMath.BoundingFrustumD.ToString)

> Returns a String that represents the current BoundingFrustumD.

