← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### BoundingFrustum Class

```csharp
public class BoundingFrustum: IEquatable<VRageMath.BoundingFrustum>
```

Defines a frustum and helps determine whether forms intersect with it.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<VRageMath.BoundingFrustum>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[CornerCount](VRageMath.BoundingFrustum.CornerCount)|Specifies the total number of corners (8) in the BoundingFrustum.|

#### Properties

|Member|Description|
|---|---|
|[Planes](VRageMath.BoundingFrustum.Planes)||
|[Item](VRageMath.BoundingFrustum.Item)||
|[Near](VRageMath.BoundingFrustum.Near)|Gets the near plane of the BoundingFrustum.|
|[Far](VRageMath.BoundingFrustum.Far)|Gets the far plane of the BoundingFrustum.|
|[Left](VRageMath.BoundingFrustum.Left)|Gets the left plane of the BoundingFrustum.|
|[Right](VRageMath.BoundingFrustum.Right)|Gets the right plane of the BoundingFrustum.|
|[Top](VRageMath.BoundingFrustum.Top)|Gets the top plane of the BoundingFrustum.|
|[Bottom](VRageMath.BoundingFrustum.Bottom)|Gets the bottom plane of the BoundingFrustum.|
|[Matrix](VRageMath.BoundingFrustum.Matrix)|Gets or sets the Matrix that describes this bounding frustum.|

#### Constructors

|Member|Description|
|---|---|
|[BoundingFrustum()](VRageMath.BoundingFrustum..ctor)||
|[BoundingFrustum(Matrix)](VRageMath.BoundingFrustum..ctor)||

#### Methods

|Member|Description|
|---|---|
|[GetCorners()](VRageMath.BoundingFrustum.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustum. ALLOCATION!|
|[GetCorners(Vector3[])](VRageMath.BoundingFrustum.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustum.|
|[GetCornersUnsafe(*Vector3)](VRageMath.BoundingFrustum.GetCornersUnsafe)||
|[Equals(BoundingFrustum)](VRageMath.BoundingFrustum.Equals)|Determines whether the specified BoundingFrustum is equal to the current BoundingFrustum.|
|[Equals(object)](VRageMath.BoundingFrustum.Equals)|Determines whether the specified Object is equal to the BoundingFrustum.|
|[GetHashCode()](VRageMath.BoundingFrustum.GetHashCode)|Gets the hash code for this instance.|
|[ToString()](VRageMath.BoundingFrustum.ToString)|Returns a String that represents the current BoundingFrustum.|
|[Intersects(BoundingBox)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects the specified BoundingBox.|
|[Intersects(ref BoundingBox, out bool)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects a BoundingBox.|
|[Intersects(BoundingFrustum)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects the specified BoundingFrustum.|
|[Intersects(Plane)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects the specified Plane.|
|[Intersects(ref Plane, out PlaneIntersectionType)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects a Plane.|
|[Intersects(Ray)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects the specified Ray.|
|[Intersects(ref Ray, out float?)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects a Ray.|
|[Intersects(BoundingSphere)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects the specified BoundingSphere.|
|[Intersects(ref BoundingSphere, out bool)](VRageMath.BoundingFrustum.Intersects)|Checks whether the current BoundingFrustum intersects a BoundingSphere.|
|[Contains(ref BoundingBox)](VRageMath.BoundingFrustum.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingBox.|
|[Contains(ref BoundingBox, out ContainmentType)](VRageMath.BoundingFrustum.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingBox.|
|[Contains(BoundingFrustum)](VRageMath.BoundingFrustum.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingFrustum.|
|[Contains(Vector3)](VRageMath.BoundingFrustum.Contains)|Checks whether the current BoundingFrustum contains the specified point.|
|[Contains(ref Vector3, out ContainmentType)](VRageMath.BoundingFrustum.Contains)|Checks whether the current BoundingFrustum contains the specified point.|
|[Contains(BoundingSphere)](VRageMath.BoundingFrustum.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingSphere.|
|[Contains(ref BoundingSphere, out ContainmentType)](VRageMath.BoundingFrustum.Contains)|Checks whether the current BoundingFrustum contains the specified BoundingSphere.|

