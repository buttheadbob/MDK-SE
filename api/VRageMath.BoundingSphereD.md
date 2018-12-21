← [Index](Api-Index)
# BoundingSphereD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a sphere.
### Fields
|Member|Description|
|---|---|
|[`Center`](VRageMath.Center)|The center point of the sphere.|
|[`Radius`](VRageMath.Radius)|The radius of the sphere.|
### Methods
|Member|Description|
|---|---|
|[`Equals(BoundingSphereD)`](VRageMath.Equals)|Determines whether the specified BoundingSphereD is equal to the current BoundingSphereD.|
|[`Equals(Object)`](VRageMath.Equals)|Determines whether the specified Object is equal to the BoundingSphereD.|
|[`GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingSphereD.|
|[`CreateMerged(BoundingSphereD, BoundingSphereD)`](VRageMath.CreateMerged)|Creates a BoundingSphereD that contains the two specified BoundingSphereD instances.|
|[`CreateMerged(ref BoundingSphereD, ref BoundingSphereD, ref BoundingSphereD)`](VRageMath.CreateMerged)|Creates a BoundingSphereD that contains the two specified BoundingSphereD instances.|
|[`CreateFromBoundingBox(BoundingBoxD)`](VRageMath.CreateFromBoundingBox)|Creates the smallest BoundingSphereD that can contain a specified BoundingBoxD.|
|[`CreateFromBoundingBox(ref BoundingBoxD, ref BoundingSphereD)`](VRageMath.CreateFromBoundingBox)|Creates the smallest BoundingSphereD that can contain a specified BoundingBoxD.|
|[`CreateFromPoints(Vector3D[])`](VRageMath.CreateFromPoints)|Creates a BoundingSphereD that can contain a specified list of points.|
|[`CreateFromFrustum(BoundingFrustumD)`](VRageMath.CreateFromFrustum)|Creates the smallest BoundingSphereD that can contain a specified BoundingFrustum.|
|[`Intersects(BoundingBoxD)`](VRageMath.Intersects)|Checks whether the current BoundingSphereD intersects with a specified BoundingBoxD.|
|[`Intersects(ref BoundingBoxD, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingSphereD intersects a BoundingBoxD.|
|[`Intersects(RayD)`](VRageMath.Intersects)||
|[`Intersects(BoundingFrustumD)`](VRageMath.Intersects)|Checks whether the current BoundingSphereD intersects with a specified BoundingFrustum.|
|[`Intersects(BoundingSphereD)`](VRageMath.Intersects)|Checks whether the current BoundingSphereD intersects with a specified BoundingSphereD.|
|[`Intersects(ref BoundingSphereD, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingSphereD intersects another BoundingSphereD.|
|[`Contains(BoundingBoxD)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingBoxD.|
|[`Contains(ref BoundingBoxD, ref ContainmentType)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingBoxD.|
|[`Contains(BoundingFrustumD)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingFrustum.|
|[`Contains(Vector3D)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified point.|
|[`Contains(ref Vector3D, ref ContainmentType)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified point.|
|[`Contains(BoundingSphereD)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingSphereD.|
|[`Contains(ref BoundingSphereD, ref ContainmentType)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingSphereD.|
|[`Transform(MatrixD)`](VRageMath.Transform)|Translates and scales the BoundingSphereD using a given Matrix.|
|[`Transform(ref MatrixD, ref BoundingSphereD)`](VRageMath.Transform)|Translates and scales the BoundingSphereD using a given Matrix.|
|[`IntersectRaySphere(RayD, ref double, ref double)`](VRageMath.IntersectRaySphere)||
|[`Include(BoundingSphereD)`](VRageMath.Include)||
|[`Include(ref BoundingSphereD, ref BoundingSphereD)`](VRageMath.Include)||
|[`CreateInvalid()`](VRageMath.CreateInvalid)||
