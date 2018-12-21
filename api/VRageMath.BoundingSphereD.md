← [Index](index.md)
# BoundingSphereD Struct
** Namespace: ** VRageMath  
** Assembly: ** VRage.Math.dll  
## Summary
Defines a sphere.
### Fields
|Member|Description|
|---|---|
|[`Vector3D Center`](VRageMath.Center.md)||
|[`double Radius`](VRageMath.Radius.md)||
### Methods
|Member|Description|
|---|---|
|[`bool Equals(BoundingSphereD other)`](VRageMath.Equals.md)|Determines whether the specified BoundingSphereD is equal to the current BoundingSphereD.|
|[`bool Equals(Object obj)`](VRageMath.Equals.md)|Determines whether the specified Object is equal to the BoundingSphereD.|
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`string ToString()`](VRageMath.ToString.md)||
|[`BoundingSphereD CreateMerged(BoundingSphereD original, BoundingSphereD additional)`](VRageMath.CreateMerged.md)||
|[`void CreateMerged(ref BoundingSphereD original, ref BoundingSphereD additional, ref BoundingSphereD result)`](VRageMath.CreateMerged.md)||
|[`BoundingSphereD CreateFromBoundingBox(BoundingBoxD box)`](VRageMath.CreateFromBoundingBox.md)|Creates the smallest BoundingSphereD that can contain a specified BoundingBoxD.|
|[`void CreateFromBoundingBox(ref BoundingBoxD box, ref BoundingSphereD result)`](VRageMath.CreateFromBoundingBox.md)||
|[`BoundingSphereD CreateFromPoints(Vector3D[] points)`](VRageMath.CreateFromPoints.md)|Creates a BoundingSphereD that can contain a specified list of points.|
|[`BoundingSphereD CreateFromFrustum(BoundingFrustumD frustum)`](VRageMath.CreateFromFrustum.md)|Creates the smallest BoundingSphereD that can contain a specified BoundingFrustum.|
|[`bool Intersects(BoundingBoxD box)`](VRageMath.Intersects.md)|Checks whether the current BoundingSphereD intersects with a specified BoundingBoxD.|
|[`void Intersects(ref BoundingBoxD box, ref bool result)`](VRageMath.Intersects.md)||
|[`Nullable<double> Intersects(RayD ray)`](VRageMath.Intersects.md)||
|[`bool Intersects(BoundingFrustumD frustum)`](VRageMath.Intersects.md)|Checks whether the current BoundingSphereD intersects with a specified BoundingFrustum.|
|[`bool Intersects(BoundingSphereD sphere)`](VRageMath.Intersects.md)|Checks whether the current BoundingSphereD intersects with a specified BoundingSphereD.|
|[`void Intersects(ref BoundingSphereD sphere, ref bool result)`](VRageMath.Intersects.md)||
|[`ContainmentType Contains(BoundingBoxD box)`](VRageMath.Contains.md)|Checks whether the current BoundingSphereD contains the specified BoundingBoxD.|
|[`void Contains(ref BoundingBoxD box, ref ContainmentType result)`](VRageMath.Contains.md)||
|[`ContainmentType Contains(BoundingFrustumD frustum)`](VRageMath.Contains.md)|Checks whether the current BoundingSphereD contains the specified BoundingFrustum.|
|[`ContainmentType Contains(Vector3D point)`](VRageMath.Contains.md)|Checks whether the current BoundingSphereD contains the specified point.|
|[`void Contains(ref Vector3D point, ref ContainmentType result)`](VRageMath.Contains.md)||
|[`ContainmentType Contains(BoundingSphereD sphere)`](VRageMath.Contains.md)|Checks whether the current BoundingSphereD contains the specified BoundingSphereD.|
|[`void Contains(ref BoundingSphereD sphere, ref ContainmentType result)`](VRageMath.Contains.md)||
|[`BoundingSphereD Transform(MatrixD matrix)`](VRageMath.Transform.md)|Translates and scales the BoundingSphereD using a given Matrix.|
|[`void Transform(ref MatrixD matrix, ref BoundingSphereD result)`](VRageMath.Transform.md)||
|[`bool IntersectRaySphere(RayD ray, ref double tmin, ref double tmax)`](VRageMath.IntersectRaySphere.md)||
|[`BoundingSphereD Include(BoundingSphereD sphere)`](VRageMath.Include.md)||
|[`void Include(ref BoundingSphereD sphere, ref BoundingSphereD otherSphere)`](VRageMath.Include.md)||
|[`BoundingSphereD CreateInvalid()`](VRageMath.CreateInvalid.md)||
