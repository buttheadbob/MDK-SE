← [Index](index)
# BoundingSphere Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a sphere.
### Fields
|Member|Description|
|---|---|
|[`Vector3 Center`](VRageMath.Center)|The center point of the sphere.|
|[`float Radius`](VRageMath.Radius)|The radius of the sphere.|
### Methods
|Member|Description|
|---|---|
|[`bool Equals(BoundingSphere other)`](VRageMath.Equals)|Determines whether the specified BoundingSphere is equal to the current BoundingSphere.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Determines whether the specified Object is equal to the BoundingSphere.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingSphere.|
|static [`BoundingSphere CreateMerged(BoundingSphere original, BoundingSphere additional)`](VRageMath.CreateMerged)|Creates a BoundingSphere that contains the two specified BoundingSphere instances.|
|static [`void CreateMerged(ref BoundingSphere original, ref BoundingSphere additional, ref BoundingSphere result)`](VRageMath.CreateMerged)|Creates a BoundingSphere that contains the two specified BoundingSphere instances.|
|static [`BoundingSphere CreateFromBoundingBox(BoundingBox box)`](VRageMath.CreateFromBoundingBox)|Creates the smallest BoundingSphere that can contain a specified BoundingBox.|
|static [`void CreateFromBoundingBox(ref BoundingBox box, ref BoundingSphere result)`](VRageMath.CreateFromBoundingBox)|Creates the smallest BoundingSphere that can contain a specified BoundingBox.|
|static [`BoundingSphere CreateFromPoints(IEnumerable<Vector3> points)`](VRageMath.CreateFromPoints)|Creates a BoundingSphere that can contain a specified list of points.|
|static [`BoundingSphere CreateFromFrustum(BoundingFrustum frustum)`](VRageMath.CreateFromFrustum)|Creates the smallest BoundingSphere that can contain a specified BoundingFrustum.|
|[`bool Intersects(BoundingBox box)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects with a specified BoundingBox.|
|[`void Intersects(ref BoundingBox box, ref bool result)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects a BoundingBox.|
|[`bool Intersects(BoundingFrustum frustum)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects with a specified BoundingFrustum.|
|[`PlaneIntersectionType Intersects(Plane plane)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects with a specified Plane.|
|[`void Intersects(ref Plane plane, ref PlaneIntersectionType result)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects a Plane.|
|[`Nullable<float> Intersects(Ray ray)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects with a specified Ray.|
|[`void Intersects(ref Ray ray, ref Nullable<float> result)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects a Ray.|
|[`bool Intersects(BoundingSphere sphere)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects with a specified BoundingSphere.|
|[`void Intersects(ref BoundingSphere sphere, ref bool result)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects another BoundingSphere.|
|[`ContainmentType Contains(BoundingBox box)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified BoundingBox.|
|[`void Contains(ref BoundingBox box, ref ContainmentType result)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified BoundingBox.|
|[`ContainmentType Contains(BoundingFrustum frustum)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified BoundingFrustum.|
|[`ContainmentType Contains(Vector3 point)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified point.|
|[`void Contains(ref Vector3 point, ref ContainmentType result)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified point.|
|[`ContainmentType Contains(BoundingSphere sphere)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified BoundingSphere.|
|[`void Contains(ref BoundingSphere sphere, ref ContainmentType result)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified BoundingSphere.|
|[`BoundingSphere Transform(Matrix matrix)`](VRageMath.Transform)|Translates and scales the BoundingSphere using a given Matrix.|
|[`void Transform(ref Matrix matrix, ref BoundingSphere result)`](VRageMath.Transform)|Translates and scales the BoundingSphere using a given Matrix.|
|[`BoundingSphere Translate(ref Vector3 translation)`](VRageMath.Translate)||
|[`bool IntersectRaySphere(Ray ray, ref float tmin, ref float tmax)`](VRageMath.IntersectRaySphere)||
|[`BoundingSphere Include(BoundingSphere sphere)`](VRageMath.Include)||
|static [`void Include(ref BoundingSphere sphere, ref BoundingSphere otherSphere)`](VRageMath.Include)||
|static [`BoundingSphere CreateInvalid()`](VRageMath.CreateInvalid)||
