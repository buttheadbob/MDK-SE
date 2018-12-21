← [Index](index)
# BoundingSphere Struct
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
|[`Equals(BoundingSphere)`](VRageMath.Equals)|Determines whether the specified BoundingSphere is equal to the current BoundingSphere.|
|[`Equals(Object)`](VRageMath.Equals)|Determines whether the specified Object is equal to the BoundingSphere.|
|[`GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingSphere.|
|static [`CreateMerged(BoundingSphere, BoundingSphere)`](VRageMath.CreateMerged)|Creates a BoundingSphere that contains the two specified BoundingSphere instances.|
|static [`CreateMerged(ref BoundingSphere, ref BoundingSphere, ref BoundingSphere)`](VRageMath.CreateMerged)|Creates a BoundingSphere that contains the two specified BoundingSphere instances.|
|static [`CreateFromBoundingBox(BoundingBox)`](VRageMath.CreateFromBoundingBox)|Creates the smallest BoundingSphere that can contain a specified BoundingBox.|
|static [`CreateFromBoundingBox(ref BoundingBox, ref BoundingSphere)`](VRageMath.CreateFromBoundingBox)|Creates the smallest BoundingSphere that can contain a specified BoundingBox.|
|static [`CreateFromPoints(IEnumerable<Vector3>)`](VRageMath.CreateFromPoints)|Creates a BoundingSphere that can contain a specified list of points.|
|static [`CreateFromFrustum(BoundingFrustum)`](VRageMath.CreateFromFrustum)|Creates the smallest BoundingSphere that can contain a specified BoundingFrustum.|
|[`Intersects(BoundingBox)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects with a specified BoundingBox.|
|[`Intersects(ref BoundingBox, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects a BoundingBox.|
|[`Intersects(BoundingFrustum)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects with a specified BoundingFrustum.|
|[`Intersects(Plane)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects with a specified Plane.|
|[`Intersects(ref Plane, ref PlaneIntersectionType)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects a Plane.|
|[`Intersects(Ray)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects with a specified Ray.|
|[`Intersects(ref Ray, ref Nullable<float>)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects a Ray.|
|[`Intersects(BoundingSphere)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects with a specified BoundingSphere.|
|[`Intersects(ref BoundingSphere, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects another BoundingSphere.|
|[`Contains(BoundingBox)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified BoundingBox.|
|[`Contains(ref BoundingBox, ref ContainmentType)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified BoundingBox.|
|[`Contains(BoundingFrustum)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified BoundingFrustum.|
|[`Contains(Vector3)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified point.|
|[`Contains(ref Vector3, ref ContainmentType)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified point.|
|[`Contains(BoundingSphere)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified BoundingSphere.|
|[`Contains(ref BoundingSphere, ref ContainmentType)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified BoundingSphere.|
|[`Transform(Matrix)`](VRageMath.Transform)|Translates and scales the BoundingSphere using a given Matrix.|
|[`Transform(ref Matrix, ref BoundingSphere)`](VRageMath.Transform)|Translates and scales the BoundingSphere using a given Matrix.|
|[`Translate(ref Vector3)`](VRageMath.Translate)||
|[`IntersectRaySphere(Ray, ref float, ref float)`](VRageMath.IntersectRaySphere)||
|[`Include(BoundingSphere)`](VRageMath.Include)||
|static [`Include(ref BoundingSphere, ref BoundingSphere)`](VRageMath.Include)||
|static [`CreateInvalid()`](VRageMath.CreateInvalid)||
