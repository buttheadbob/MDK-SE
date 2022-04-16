← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### BoundingFrustum Class

```csharp
public class BoundingFrustum: IEquatable<BoundingFrustum\>
```

Defines a frustum and helps determine whether forms intersect with it.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<BoundingFrustum\>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\$1static int CornerCount](VRageMath.BoundingFrustum.CornerCount)|Specifies the total number of corners (8) in the BoundingFrustum.|

#### Properties

|Member|Description|
|---|---|
|\$1Plane Bottom { get; }](VRageMath.BoundingFrustum.Bottom)|Gets the bottom plane of the BoundingFrustum.|
|\$1Plane Far { get; }](VRageMath.BoundingFrustum.Far)|Gets the far plane of the BoundingFrustum.|
|\$1Plane Item { get; }](VRageMath.BoundingFrustum.Item)||
|\$1Plane Left { get; }](VRageMath.BoundingFrustum.Left)|Gets the left plane of the BoundingFrustum.|
|\$1Matrix Matrix { get; set; }](VRageMath.BoundingFrustum.Matrix)|Gets or sets the Matrix that describes this bounding frustum.|
|\$1Plane Near { get; }](VRageMath.BoundingFrustum.Near)|Gets the near plane of the BoundingFrustum.|
|\$1Plane\$1] Planes { get; }](VRageMath.BoundingFrustum.Planes)||
|\$1Plane Right { get; }](VRageMath.BoundingFrustum.Right)|Gets the right plane of the BoundingFrustum.|
|\$1Plane Top { get; }](VRageMath.BoundingFrustum.Top)|Gets the top plane of the BoundingFrustum.|

#### Constructors

|Member|Description|
|---|---|
|\$1BoundingFrustum()](VRageMath.BoundingFrustum..ctor)||
|\$1BoundingFrustum(Matrix)](VRageMath.BoundingFrustum..ctor)||

#### Methods

|Member|Description|
|---|---|
|\$1ContainmentType Contains(ref BoundingBox)](VRageMath.BoundingFrustum.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingBox.|
|\$1void Contains(ref BoundingBox, out ContainmentType)](VRageMath.BoundingFrustum.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingBox.|
|\$1ContainmentType Contains(BoundingFrustum)](VRageMath.BoundingFrustum.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingFrustum.|
|\$1ContainmentType Contains(Vector3)](VRageMath.BoundingFrustum.Contains)|Checks whether the current BoundingFrustum contains the specified point.|
|\$1void Contains(ref Vector3, out ContainmentType)](VRageMath.BoundingFrustum.Contains)|Checks whether the current BoundingFrustum contains the specified point.|
|\$1ContainmentType Contains(BoundingSphere)](VRageMath.BoundingFrustum.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingSphere.|
|\$1void Contains(ref BoundingSphere, out ContainmentType)](VRageMath.BoundingFrustum.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingSphere.|
|\$1bool Equals(BoundingFrustum)](VRageMath.BoundingFrustum.Equals)|Determines whether the specified BoundingFrustum is equal to the current BoundingFrustum.|
|\$1bool Equals(object)](VRageMath.BoundingFrustum.Equals)|Determines whether the specified Object is equal to the BoundingFrustum.|
|\$1Vector3\$1] GetCorners()](VRageMath.BoundingFrustum.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustum. ALLOCATION!|
|\$1void GetCorners(Vector3\$1])](VRageMath.BoundingFrustum.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustum.|
|\$1void GetCornersUnsafe(*Vector3)](VRageMath.BoundingFrustum.GetCornersUnsafe)||
|\$1int GetHashCode()](VRageMath.BoundingFrustum.GetHashCode)|Gets the hash code for this instance.|
|\$1bool Intersects(BoundingBox)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects the specified BoundingBox.|
|\$1void Intersects(ref BoundingBox, out bool)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects a BoundingBox.|
|\$1bool Intersects(BoundingFrustum)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects the specified BoundingFrustum.|
|\$1PlaneIntersectionType Intersects(Plane)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects the specified Plane.|
|\$1void Intersects(ref Plane, out PlaneIntersectionType)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects a Plane.|
|\$1float? Intersects(Ray)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects the specified Ray.|
|\$1void Intersects(ref Ray, out float?)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects a Ray.|
|\$1bool Intersects(BoundingSphere)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects the specified BoundingSphere.|
|\$1void Intersects(ref BoundingSphere, out bool)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects a BoundingSphere.|
|\$1string ToString()](VRageMath.BoundingFrustum.ToString)|Returns a String that represents the current BoundingFrustum.|

