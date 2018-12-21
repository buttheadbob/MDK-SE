← [Index](index)
# BoundingSphereD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a sphere.
### Fields
|Member|Description|
|---|---|
|[`VRageMath.Vector3D Center`](VRageMath.Center)|The center point of the sphere.|
|[`double Radius`](VRageMath.Radius)|The radius of the sphere.|
### Methods
|Member|Description|
|---|---|
|[`bool Equals(VRageMath.BoundingSphereD)`](VRageMath.Equals)|Determines whether the specified BoundingSphereD is equal to the current BoundingSphereD.|
|[`bool Equals(System.Object)`](VRageMath.Equals)|Determines whether the specified Object is equal to the BoundingSphereD.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingSphereD.|
|static [`VRageMath.BoundingSphereD CreateMerged(VRageMath.BoundingSphereD, VRageMath.BoundingSphereD)`](VRageMath.CreateMerged)|Creates a BoundingSphereD that contains the two specified BoundingSphereD instances.|
|static [`void CreateMerged(ref VRageMath.BoundingSphereD, ref VRageMath.BoundingSphereD, ref VRageMath.BoundingSphereD)`](VRageMath.CreateMerged)|Creates a BoundingSphereD that contains the two specified BoundingSphereD instances.|
|static [`VRageMath.BoundingSphereD CreateFromBoundingBox(VRageMath.BoundingBoxD)`](VRageMath.CreateFromBoundingBox)|Creates the smallest BoundingSphereD that can contain a specified BoundingBoxD.|
|static [`void CreateFromBoundingBox(ref VRageMath.BoundingBoxD, ref VRageMath.BoundingSphereD)`](VRageMath.CreateFromBoundingBox)|Creates the smallest BoundingSphereD that can contain a specified BoundingBoxD.|
|static [`VRageMath.BoundingSphereD CreateFromPoints(VRageMath.Vector3D[])`](VRageMath.CreateFromPoints)|Creates a BoundingSphereD that can contain a specified list of points.|
|static [`VRageMath.BoundingSphereD CreateFromFrustum(VRageMath.BoundingFrustumD)`](VRageMath.CreateFromFrustum)|Creates the smallest BoundingSphereD that can contain a specified BoundingFrustum.|
|[`bool Intersects(VRageMath.BoundingBoxD)`](VRageMath.Intersects)|Checks whether the current BoundingSphereD intersects with a specified BoundingBoxD.|
|[`void Intersects(ref VRageMath.BoundingBoxD, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingSphereD intersects a BoundingBoxD.|
|[`Nullable<System.Double> Intersects(VRageMath.RayD)`](VRageMath.Intersects)||
|[`bool Intersects(VRageMath.BoundingFrustumD)`](VRageMath.Intersects)|Checks whether the current BoundingSphereD intersects with a specified BoundingFrustum.|
|[`bool Intersects(VRageMath.BoundingSphereD)`](VRageMath.Intersects)|Checks whether the current BoundingSphereD intersects with a specified BoundingSphereD.|
|[`void Intersects(ref VRageMath.BoundingSphereD, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingSphereD intersects another BoundingSphereD.|
|[`VRageMath.ContainmentType Contains(VRageMath.BoundingBoxD)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingBoxD.|
|[`void Contains(ref VRageMath.BoundingBoxD, ref VRageMath.ContainmentType)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingBoxD.|
|[`VRageMath.ContainmentType Contains(VRageMath.BoundingFrustumD)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingFrustum.|
|[`VRageMath.ContainmentType Contains(VRageMath.Vector3D)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified point.|
|[`void Contains(ref VRageMath.Vector3D, ref VRageMath.ContainmentType)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified point.|
|[`VRageMath.ContainmentType Contains(VRageMath.BoundingSphereD)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingSphereD.|
|[`void Contains(ref VRageMath.BoundingSphereD, ref VRageMath.ContainmentType)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingSphereD.|
|[`VRageMath.BoundingSphereD Transform(VRageMath.MatrixD)`](VRageMath.Transform)|Translates and scales the BoundingSphereD using a given Matrix.|
|[`void Transform(ref VRageMath.MatrixD, ref VRageMath.BoundingSphereD)`](VRageMath.Transform)|Translates and scales the BoundingSphereD using a given Matrix.|
|[`bool IntersectRaySphere(VRageMath.RayD, ref double, ref double)`](VRageMath.IntersectRaySphere)||
|[`VRageMath.BoundingSphereD Include(VRageMath.BoundingSphereD)`](VRageMath.Include)||
|static [`void Include(ref VRageMath.BoundingSphereD, ref VRageMath.BoundingSphereD)`](VRageMath.Include)||
|static [`VRageMath.BoundingSphereD CreateInvalid()`](VRageMath.CreateInvalid)||
