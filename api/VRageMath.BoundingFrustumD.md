← [Index](Api-Index)

#### BoundingFrustumD Class

```csharp
public class BoundingFrustumD: object, IEquatable<T>
```

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Inheritance: **[object](System.Object)

**Implements:**  
* [IEquatable<T>](System.IEquatable`1)

#### Example

#### Remarks

#### Fields

|Member|Description|
|---|---|
|[CornerCount](VRageMath.BoundingFrustumD.CornerCount)|Specifies the total number of corners (8) in the BoundingFrustumD.|

#### Properties

|Member|Description|
|---|---|
|[Item](VRageMath.BoundingFrustumD.Item)||
|[Near](VRageMath.BoundingFrustumD.Near)|Gets the near plane of the BoundingFrustumD.|
|[Far](VRageMath.BoundingFrustumD.Far)|Gets the far plane of the BoundingFrustumD.|
|[Left](VRageMath.BoundingFrustumD.Left)|Gets the left plane of the BoundingFrustumD.|
|[Right](VRageMath.BoundingFrustumD.Right)|Gets the right plane of the BoundingFrustumD.|
|[Top](VRageMath.BoundingFrustumD.Top)|Gets the top plane of the BoundingFrustumD.|
|[Bottom](VRageMath.BoundingFrustumD.Bottom)|Gets the bottom plane of the BoundingFrustumD.|
|[Matrix](VRageMath.BoundingFrustumD.Matrix)|Gets or sets the Matrix that describes this bounding frustum.|

#### Methods

|Member|Description|
|---|---|
|[GetCorners()](VRageMath.BoundingFrustumD.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustumD. ALLOCATION!|
|[GetCorners(Vector3D[])](VRageMath.BoundingFrustumD.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustumD.|
|[GetCornersUnsafe(*Vector3D)](VRageMath.BoundingFrustumD.GetCornersUnsafe)||
|[Equals(BoundingFrustumD)](VRageMath.BoundingFrustumD.Equals)|Determines whether the specified BoundingFrustumD is equal to the current BoundingFrustumD.|
|[Equals(object)](VRageMath.BoundingFrustumD.Equals)|Determines whether the specified Object is equal to the BoundingFrustumD.|
|[GetHashCode()](VRageMath.BoundingFrustumD.GetHashCode)|Gets the hash code for this instance.|
|[ToString()](VRageMath.BoundingFrustumD.ToString)|Returns a String that represents the current BoundingFrustumD.|
|[Intersects(BoundingBoxD)](VRageMath.BoundingFrustumD.Intersects)|Checks whether the current BoundingFrustumD intersects the specified BoundingBoxD.|
|[Intersects(ref BoundingBoxD, ref bool)](VRageMath.BoundingFrustumD.Intersects)|Checks whether the current BoundingFrustumD intersects a BoundingBoxD.|
|[Intersects(BoundingFrustumD)](VRageMath.BoundingFrustumD.Intersects)|Checks whether the current BoundingFrustumD intersects the specified BoundingFrustumD.|
|[Intersects(PlaneD)](VRageMath.BoundingFrustumD.Intersects)|Checks whether the current BoundingFrustumD intersects the specified Plane.|
|[Intersects(ref PlaneD, ref PlaneIntersectionType)](VRageMath.BoundingFrustumD.Intersects)|Checks whether the current BoundingFrustumD intersects a Plane.|
|[Intersects(RayD)](VRageMath.BoundingFrustumD.Intersects)|Checks whether the current BoundingFrustumD intersects the specified Ray.|
|[Intersects(ref RayD, ref Nullable)](VRageMath.BoundingFrustumD.Intersects)||
|[Intersects(BoundingSphereD)](VRageMath.BoundingFrustumD.Intersects)|Checks whether the current BoundingFrustumD intersects the specified BoundingSphere.|
|[Intersects(ref BoundingSphereD, ref bool)](VRageMath.BoundingFrustumD.Intersects)|Checks whether the current BoundingFrustumD intersects a BoundingSphere.|
|[Contains(BoundingBoxD)](VRageMath.BoundingFrustumD.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingBoxD.|
|[Contains(ref BoundingBoxD, ref ContainmentType)](VRageMath.BoundingFrustumD.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingBoxD.|
|[Contains(BoundingFrustumD)](VRageMath.BoundingFrustumD.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingFrustumD.|
|[Contains(Vector3D)](VRageMath.BoundingFrustumD.Contains)|Checks whether the current BoundingFrustumD contains the specified point.|
|[Contains(ref Vector3D, ref ContainmentType)](VRageMath.BoundingFrustumD.Contains)|Checks whether the current BoundingFrustumD contains the specified point.|
|[Contains(BoundingSphereD)](VRageMath.BoundingFrustumD.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingSphere.|
|[Contains(ref BoundingSphereD, ref ContainmentType)](VRageMath.BoundingFrustumD.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingSphere.|

