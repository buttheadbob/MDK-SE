← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### BoundingFrustumD Class

```csharp
public class BoundingFrustumD: IEquatable<BoundingFrustumD\>
```

Defines a frustum and helps determine whether forms intersect with it.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<BoundingFrustumD\>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\$1static int CornerCount](VRageMath.BoundingFrustumD.CornerCount)|Specifies the total number of corners (8) in the BoundingFrustumD.|

#### Properties

|Member|Description|
|---|---|
|\$1PlaneD Bottom { get; }](VRageMath.BoundingFrustumD.Bottom)|Gets the bottom plane of the BoundingFrustumD.|
|\$1PlaneD Far { get; }](VRageMath.BoundingFrustumD.Far)|Gets the far plane of the BoundingFrustumD.|
|\$1PlaneD Item { get; }](VRageMath.BoundingFrustumD.Item)||
|\$1PlaneD Left { get; }](VRageMath.BoundingFrustumD.Left)|Gets the left plane of the BoundingFrustumD.|
|\$1MatrixD Matrix { get; set; }](VRageMath.BoundingFrustumD.Matrix)|Gets or sets the Matrix that describes this bounding frustum.|
|\$1PlaneD Near { get; }](VRageMath.BoundingFrustumD.Near)|Gets the near plane of the BoundingFrustumD.|
|\$1PlaneD Right { get; }](VRageMath.BoundingFrustumD.Right)|Gets the right plane of the BoundingFrustumD.|
|\$1PlaneD Top { get; }](VRageMath.BoundingFrustumD.Top)|Gets the top plane of the BoundingFrustumD.|

#### Constructors

|Member|Description|
|---|---|
|\$1BoundingFrustumD()](VRageMath.BoundingFrustumD..ctor)||
|\$1BoundingFrustumD(MatrixD)](VRageMath.BoundingFrustumD..ctor)||

#### Methods

|Member|Description|
|---|---|
|\$1ContainmentType Contains(BoundingBoxD)](VRageMath.BoundingFrustumD.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingBoxD.|
|\$1void Contains(ref BoundingBoxD, out ContainmentType)](VRageMath.BoundingFrustumD.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingBoxD.|
|\$1ContainmentType Contains(BoundingFrustumD)](VRageMath.BoundingFrustumD.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingFrustumD.|
|\$1ContainmentType Contains(Vector3D)](VRageMath.BoundingFrustumD.Contains)|Checks whether the current BoundingFrustumD contains the specified point.|
|\$1void Contains(ref Vector3D, out ContainmentType)](VRageMath.BoundingFrustumD.Contains)|Checks whether the current BoundingFrustumD contains the specified point.|
|\$1ContainmentType Contains(BoundingSphereD)](VRageMath.BoundingFrustumD.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingSphere.|
|\$1void Contains(ref BoundingSphereD, out ContainmentType)](VRageMath.BoundingFrustumD.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingSphere.|
|\$1bool Equals(BoundingFrustumD)](VRageMath.BoundingFrustumD.Equals)|Determines whether the specified BoundingFrustumD is equal to the current BoundingFrustumD.|
|\$1bool Equals(object)](VRageMath.BoundingFrustumD.Equals)|Determines whether the specified Object is equal to the BoundingFrustumD.|
|\$1Vector3D\$1] GetCorners()](VRageMath.BoundingFrustumD.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustumD. ALLOCATION!|
|\$1void GetCorners(Vector3D\$1])](VRageMath.BoundingFrustumD.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustumD.|
|\$1void GetCornersUnsafe(*Vector3D)](VRageMath.BoundingFrustumD.GetCornersUnsafe)||
|\$1int GetHashCode()](VRageMath.BoundingFrustumD.GetHashCode)|Gets the hash code for this instance.|
|\$1bool Intersects(BoundingBoxD)](VRageMath.BoundingFrustumD.Intersects)|Checks whether the current BoundingFrustumD intersects the specified BoundingBoxD.|
|\$1void Intersects(ref BoundingBoxD, out bool)](VRageMath.BoundingFrustumD.Intersects)|Checks whether the current BoundingFrustumD intersects a BoundingBoxD.|
|\$1bool Intersects(BoundingFrustumD)](VRageMath.BoundingFrustumD.Intersects)|Checks whether the current BoundingFrustumD intersects the specified BoundingFrustumD.|
|\$1PlaneIntersectionType Intersects(PlaneD)](VRageMath.BoundingFrustumD.Intersects)|Checks whether the current BoundingFrustumD intersects the specified Plane.|
|\$1void Intersects(ref PlaneD, out PlaneIntersectionType)](VRageMath.BoundingFrustumD.Intersects)|Checks whether the current BoundingFrustumD intersects a Plane.|
|\$1double? Intersects(RayD)](VRageMath.BoundingFrustumD.Intersects)|Checks whether the current BoundingFrustumD intersects the specified Ray.|
|\$1void Intersects(ref RayD, out double?)](VRageMath.BoundingFrustumD.Intersects)|Checks whether the current BoundingFrustumD intersects a Ray.|
|\$1bool Intersects(BoundingSphereD)](VRageMath.BoundingFrustumD.Intersects)|Checks whether the current BoundingFrustumD intersects the specified BoundingSphere.|
|\$1void Intersects(ref BoundingSphereD, out bool)](VRageMath.BoundingFrustumD.Intersects)|Checks whether the current BoundingFrustumD intersects a BoundingSphere.|
|\$1string ToString()](VRageMath.BoundingFrustumD.ToString)|Returns a String that represents the current BoundingFrustumD.|

