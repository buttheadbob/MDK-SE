← [Index](index)
# BoundingSphere Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a sphere.
### Fields
|Member|Description|
|---|---|
|[`VRageMath.Vector3 Center`](VRageMath.Center)|The center point of the sphere.|
|[`float Radius`](VRageMath.Radius)|The radius of the sphere.|
### Methods
|Member|Description|
|---|---|
|[`bool Equals(VRageMath.BoundingSphere)`](VRageMath.Equals)|Determines whether the specified BoundingSphere is equal to the current BoundingSphere.|
|[`bool Equals(System.Object)`](VRageMath.Equals)|Determines whether the specified Object is equal to the BoundingSphere.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingSphere.|
|static [`VRageMath.BoundingSphere CreateMerged(VRageMath.BoundingSphere, VRageMath.BoundingSphere)`](VRageMath.CreateMerged)|Creates a BoundingSphere that contains the two specified BoundingSphere instances.|
|static [`void CreateMerged(ref VRageMath.BoundingSphere, ref VRageMath.BoundingSphere, ref VRageMath.BoundingSphere)`](VRageMath.CreateMerged)|Creates a BoundingSphere that contains the two specified BoundingSphere instances.|
|static [`VRageMath.BoundingSphere CreateFromBoundingBox(VRageMath.BoundingBox)`](VRageMath.CreateFromBoundingBox)|Creates the smallest BoundingSphere that can contain a specified BoundingBox.|
|static [`void CreateFromBoundingBox(ref VRageMath.BoundingBox, ref VRageMath.BoundingSphere)`](VRageMath.CreateFromBoundingBox)|Creates the smallest BoundingSphere that can contain a specified BoundingBox.|
|static [`VRageMath.BoundingSphere CreateFromPoints(IEnumerable<VRageMath.Vector3>)`](VRageMath.CreateFromPoints)|Creates a BoundingSphere that can contain a specified list of points.|
|static [`VRageMath.BoundingSphere CreateFromFrustum(VRageMath.BoundingFrustum)`](VRageMath.CreateFromFrustum)|Creates the smallest BoundingSphere that can contain a specified BoundingFrustum.|
|[`bool Intersects(VRageMath.BoundingBox)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects with a specified BoundingBox.|
|[`void Intersects(ref VRageMath.BoundingBox, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects a BoundingBox.|
|[`bool Intersects(VRageMath.BoundingFrustum)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects with a specified BoundingFrustum.|
|[`VRageMath.PlaneIntersectionType Intersects(VRageMath.Plane)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects with a specified Plane.|
|[`void Intersects(ref VRageMath.Plane, ref VRageMath.PlaneIntersectionType)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects a Plane.|
|[`Nullable<System.Single> Intersects(VRageMath.Ray)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects with a specified Ray.|
|[`void Intersects(ref VRageMath.Ray, ref Nullable<System.Single>)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects a Ray.|
|[`bool Intersects(VRageMath.BoundingSphere)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects with a specified BoundingSphere.|
|[`void Intersects(ref VRageMath.BoundingSphere, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects another BoundingSphere.|
|[`VRageMath.ContainmentType Contains(VRageMath.BoundingBox)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified BoundingBox.|
|[`void Contains(ref VRageMath.BoundingBox, ref VRageMath.ContainmentType)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified BoundingBox.|
|[`VRageMath.ContainmentType Contains(VRageMath.BoundingFrustum)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified BoundingFrustum.|
|[`VRageMath.ContainmentType Contains(VRageMath.Vector3)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified point.|
|[`void Contains(ref VRageMath.Vector3, ref VRageMath.ContainmentType)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified point.|
|[`VRageMath.ContainmentType Contains(VRageMath.BoundingSphere)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified BoundingSphere.|
|[`void Contains(ref VRageMath.BoundingSphere, ref VRageMath.ContainmentType)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified BoundingSphere.|
|[`VRageMath.BoundingSphere Transform(VRageMath.Matrix)`](VRageMath.Transform)|Translates and scales the BoundingSphere using a given Matrix.|
|[`void Transform(ref VRageMath.Matrix, ref VRageMath.BoundingSphere)`](VRageMath.Transform)|Translates and scales the BoundingSphere using a given Matrix.|
|[`VRageMath.BoundingSphere Translate(ref VRageMath.Vector3)`](VRageMath.Translate)||
|[`bool IntersectRaySphere(VRageMath.Ray, ref float, ref float)`](VRageMath.IntersectRaySphere)||
|[`VRageMath.BoundingSphere Include(VRageMath.BoundingSphere)`](VRageMath.Include)||
|static [`void Include(ref VRageMath.BoundingSphere, ref VRageMath.BoundingSphere)`](VRageMath.Include)||
|static [`VRageMath.BoundingSphere CreateInvalid()`](VRageMath.CreateInvalid)||
