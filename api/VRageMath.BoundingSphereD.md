← [Index](Api-Index)

#### BoundingSphereD Struct

```csharp
public sealed struct BoundingSphereD
```

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

#### Example

#### Remarks

#### Fields

|Member|Description|
|---|---|
|[Center](VRageMath.BoundingSphereD.Center)|The center point of the sphere.|
|[Radius](VRageMath.BoundingSphereD.Radius)|The radius of the sphere.|

#### Methods

|Member|Description|
|---|---|
|[Equals(BoundingSphereD)](VRageMath.BoundingSphereD.Equals)|Determines whether the specified BoundingSphereD is equal to the current BoundingSphereD.|
|[Equals(object)](VRageMath.BoundingSphereD.Equals)|Determines whether the specified Object is equal to the BoundingSphereD.|
|[GetHashCode()](VRageMath.BoundingSphereD.GetHashCode)|Gets the hash code for this instance.|
|[ToString()](VRageMath.BoundingSphereD.ToString)|Returns a String that represents the current BoundingSphereD.|
|[CreateMerged(BoundingSphereD, BoundingSphereD)](VRageMath.BoundingSphereD.CreateMerged)|Creates a BoundingSphereD that contains the two specified BoundingSphereD instances.|
|[CreateMerged(ref BoundingSphereD, ref BoundingSphereD, ref BoundingSphereD)](VRageMath.BoundingSphereD.CreateMerged)|Creates a BoundingSphereD that contains the two specified BoundingSphereD instances.|
|[CreateFromBoundingBox(BoundingBoxD)](VRageMath.BoundingSphereD.CreateFromBoundingBox)|Creates the smallest BoundingSphereD that can contain a specified BoundingBoxD.|
|[CreateFromBoundingBox(ref BoundingBoxD, ref BoundingSphereD)](VRageMath.BoundingSphereD.CreateFromBoundingBox)|Creates the smallest BoundingSphereD that can contain a specified BoundingBoxD.|
|[CreateFromPoints(Vector3D[])](VRageMath.BoundingSphereD.CreateFromPoints)|Creates a BoundingSphereD that can contain a specified list of points.|
|[CreateFromFrustum(BoundingFrustumD)](VRageMath.BoundingSphereD.CreateFromFrustum)|Creates the smallest BoundingSphereD that can contain a specified BoundingFrustum.|
|[Intersects(BoundingBoxD)](VRageMath.BoundingSphereD.Intersects)|Checks whether the current BoundingSphereD intersects with a specified BoundingBoxD.|
|[Intersects(ref BoundingBoxD, ref bool)](VRageMath.BoundingSphereD.Intersects)|Checks whether the current BoundingSphereD intersects a BoundingBoxD.|
|[Intersects(RayD)](VRageMath.BoundingSphereD.Intersects)||
|[Intersects(BoundingFrustumD)](VRageMath.BoundingSphereD.Intersects)|Checks whether the current BoundingSphereD intersects with a specified BoundingFrustum.|
|[Intersects(BoundingSphereD)](VRageMath.BoundingSphereD.Intersects)|Checks whether the current BoundingSphereD intersects with a specified BoundingSphereD.|
|[Intersects(ref BoundingSphereD, ref bool)](VRageMath.BoundingSphereD.Intersects)|Checks whether the current BoundingSphereD intersects another BoundingSphereD.|
|[Contains(BoundingBoxD)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingBoxD.|
|[Contains(ref BoundingBoxD, ref ContainmentType)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingBoxD.|
|[Contains(BoundingFrustumD)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingFrustum.|
|[Contains(Vector3D)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified point.|
|[Contains(ref Vector3D, ref ContainmentType)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified point.|
|[Contains(BoundingSphereD)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingSphereD.|
|[Contains(ref BoundingSphereD, ref ContainmentType)](VRageMath.BoundingSphereD.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingSphereD.|
|[Transform(MatrixD)](VRageMath.BoundingSphereD.Transform)|Translates and scales the BoundingSphereD using a given Matrix.|
|[Transform(ref MatrixD, ref BoundingSphereD)](VRageMath.BoundingSphereD.Transform)|Translates and scales the BoundingSphereD using a given Matrix.|
|[IntersectRaySphere(RayD, ref double, ref double)](VRageMath.BoundingSphereD.IntersectRaySphere)||
|[Include(BoundingSphereD)](VRageMath.BoundingSphereD.Include)||
|[Include(ref BoundingSphereD, ref BoundingSphereD)](VRageMath.BoundingSphereD.Include)||
|[CreateInvalid()](VRageMath.BoundingSphereD.CreateInvalid)||

