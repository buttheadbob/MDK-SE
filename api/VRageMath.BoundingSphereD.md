← [Index](index)
# BoundingSphereD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a sphere.
### Fields
|Member|Description|
|---|---|
|[`Vector3D Center`](VRageMath.Center)|The center point of the sphere.|
|[`double Radius`](VRageMath.Radius)|The radius of the sphere.|
### Methods
|Member|Description|
|---|---|
|[`bool Equals(BoundingSphereD other)`](VRageMath.Equals)|Determines whether the specified BoundingSphereD is equal to the current BoundingSphereD.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Determines whether the specified Object is equal to the BoundingSphereD.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingSphereD.|
|static [`BoundingSphereD CreateMerged(BoundingSphereD original, BoundingSphereD additional)`](VRageMath.CreateMerged)|Creates a BoundingSphereD that contains the two specified BoundingSphereD instances.|
|static [`void CreateMerged(ref BoundingSphereD original, ref BoundingSphereD additional, ref BoundingSphereD result)`](VRageMath.CreateMerged)|Creates a BoundingSphereD that contains the two specified BoundingSphereD instances.|
|static [`BoundingSphereD CreateFromBoundingBox(BoundingBoxD box)`](VRageMath.CreateFromBoundingBox)|Creates the smallest BoundingSphereD that can contain a specified BoundingBoxD.|
|static [`void CreateFromBoundingBox(ref BoundingBoxD box, ref BoundingSphereD result)`](VRageMath.CreateFromBoundingBox)|Creates the smallest BoundingSphereD that can contain a specified BoundingBoxD.|
|static [`BoundingSphereD CreateFromPoints(Vector3D[] points)`](VRageMath.CreateFromPoints)|Creates a BoundingSphereD that can contain a specified list of points.|
|static [`BoundingSphereD CreateFromFrustum(BoundingFrustumD frustum)`](VRageMath.CreateFromFrustum)|Creates the smallest BoundingSphereD that can contain a specified BoundingFrustum.|
|[`bool Intersects(BoundingBoxD box)`](VRageMath.Intersects)|Checks whether the current BoundingSphereD intersects with a specified BoundingBoxD.|
|[`void Intersects(ref BoundingBoxD box, ref bool result)`](VRageMath.Intersects)|Checks whether the current BoundingSphereD intersects a BoundingBoxD.|
|[`Nullable<double> Intersects(RayD ray)`](VRageMath.Intersects)||
|[`bool Intersects(BoundingFrustumD frustum)`](VRageMath.Intersects)|Checks whether the current BoundingSphereD intersects with a specified BoundingFrustum.|
|[`bool Intersects(BoundingSphereD sphere)`](VRageMath.Intersects)|Checks whether the current BoundingSphereD intersects with a specified BoundingSphereD.|
|[`void Intersects(ref BoundingSphereD sphere, ref bool result)`](VRageMath.Intersects)|Checks whether the current BoundingSphereD intersects another BoundingSphereD.|
|[`ContainmentType Contains(BoundingBoxD box)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingBoxD.|
|[`void Contains(ref BoundingBoxD box, ref ContainmentType result)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingBoxD.|
|[`ContainmentType Contains(BoundingFrustumD frustum)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingFrustum.|
|[`ContainmentType Contains(Vector3D point)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified point.|
|[`void Contains(ref Vector3D point, ref ContainmentType result)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified point.|
|[`ContainmentType Contains(BoundingSphereD sphere)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingSphereD.|
|[`void Contains(ref BoundingSphereD sphere, ref ContainmentType result)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingSphereD.|
|[`BoundingSphereD Transform(MatrixD matrix)`](VRageMath.Transform)|Translates and scales the BoundingSphereD using a given Matrix.|
|[`void Transform(ref MatrixD matrix, ref BoundingSphereD result)`](VRageMath.Transform)|Translates and scales the BoundingSphereD using a given Matrix.|
|[`bool IntersectRaySphere(RayD ray, ref double tmin, ref double tmax)`](VRageMath.IntersectRaySphere)||
|[`BoundingSphereD Include(BoundingSphereD sphere)`](VRageMath.Include)||
|static [`void Include(ref BoundingSphereD sphere, ref BoundingSphereD otherSphere)`](VRageMath.Include)||
|static [`BoundingSphereD CreateInvalid()`](VRageMath.CreateInvalid)||
