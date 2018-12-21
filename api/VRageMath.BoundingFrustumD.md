← [Index](index)
# BoundingFrustumD Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a frustum and helps determine whether forms intersect with it.
### Fields
|Member|Description|
|---|---|
|static [`int CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingFrustumD.|
### Properties
|Member|Description|
|---|---|
|[`VRageMath.PlaneD Item`](VRageMath.Item)||
|[`VRageMath.PlaneD Near`](VRageMath.Near)|Gets the near plane of the BoundingFrustumD.|
|[`VRageMath.PlaneD Far`](VRageMath.Far)|Gets the far plane of the BoundingFrustumD.|
|[`VRageMath.PlaneD Left`](VRageMath.Left)|Gets the left plane of the BoundingFrustumD.|
|[`VRageMath.PlaneD Right`](VRageMath.Right)|Gets the right plane of the BoundingFrustumD.|
|[`VRageMath.PlaneD Top`](VRageMath.Top)|Gets the top plane of the BoundingFrustumD.|
|[`VRageMath.PlaneD Bottom`](VRageMath.Bottom)|Gets the bottom plane of the BoundingFrustumD.|
|[`VRageMath.MatrixD Matrix`](VRageMath.Matrix)|Gets or sets the Matrix that describes this bounding frustum.|
### Methods
|Member|Description|
|---|---|
|[`VRageMath.Vector3D[] GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustumD. ALLOCATION!|
|[`void GetCorners(VRageMath.Vector3D[])`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingFrustumD.|
|[`void GetCornersUnsafe(*VRageMath.Vector3D)`](VRageMath.GetCornersUnsafe)||
|[`bool Equals(VRageMath.BoundingFrustumD)`](VRageMath.Equals)|Determines whether the specified BoundingFrustumD is equal to the current BoundingFrustumD.|
|[`bool Equals(System.Object)`](VRageMath.Equals)|Determines whether the specified Object is equal to the BoundingFrustumD.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingFrustumD.|
|[`bool Intersects(VRageMath.BoundingBoxD)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects the specified BoundingBoxD.|
|[`void Intersects(ref VRageMath.BoundingBoxD, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects a BoundingBoxD.|
|[`bool Intersects(VRageMath.BoundingFrustumD)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects the specified BoundingFrustumD.|
|[`VRageMath.PlaneIntersectionType Intersects(VRageMath.PlaneD)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects the specified Plane.|
|[`void Intersects(ref VRageMath.PlaneD, ref VRageMath.PlaneIntersectionType)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects a Plane.|
|[`Nullable<System.Double> Intersects(VRageMath.RayD)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects the specified Ray.|
|[`void Intersects(ref VRageMath.RayD, ref Nullable<System.Double>)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects a Ray.|
|[`bool Intersects(VRageMath.BoundingSphereD)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects the specified BoundingSphere.|
|[`void Intersects(ref VRageMath.BoundingSphereD, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingFrustumD intersects a BoundingSphere.|
|[`VRageMath.ContainmentType Contains(VRageMath.BoundingBoxD)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingBoxD.|
|[`void Contains(ref VRageMath.BoundingBoxD, ref VRageMath.ContainmentType)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingBoxD.|
|[`VRageMath.ContainmentType Contains(VRageMath.BoundingFrustumD)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingFrustumD.|
|[`VRageMath.ContainmentType Contains(VRageMath.Vector3D)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified point.|
|[`void Contains(ref VRageMath.Vector3D, ref VRageMath.ContainmentType)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified point.|
|[`VRageMath.ContainmentType Contains(VRageMath.BoundingSphereD)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingSphere.|
|[`void Contains(ref VRageMath.BoundingSphereD, ref VRageMath.ContainmentType)`](VRageMath.Contains)|Checks whether the current BoundingFrustumD contains the specified BoundingSphere.|
