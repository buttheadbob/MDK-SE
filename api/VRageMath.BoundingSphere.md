← [Index](index)
# BoundingSphere Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Defines a sphere.
### Fields
|Member|Description|
|---|---|
|[`Vector3 Center`](VRageMath.Center)||
|[`float Radius`](VRageMath.Radius)||
### Methods
|Member|Description|
|---|---|
|[`bool Equals(BoundingSphere other)`](VRageMath.Equals)|Determines whether the specified BoundingSphere is equal to the current BoundingSphere.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Determines whether the specified Object is equal to the BoundingSphere.|
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`string ToString()`](VRageMath.ToString)||
|[`BoundingSphere CreateMerged(BoundingSphere original, BoundingSphere additional)`](VRageMath.CreateMerged)||
|[`void CreateMerged(ref BoundingSphere original, ref BoundingSphere additional, ref BoundingSphere result)`](VRageMath.CreateMerged)||
|[`BoundingSphere CreateFromBoundingBox(BoundingBox box)`](VRageMath.CreateFromBoundingBox)|Creates the smallest BoundingSphere that can contain a specified BoundingBox.|
|[`void CreateFromBoundingBox(ref BoundingBox box, ref BoundingSphere result)`](VRageMath.CreateFromBoundingBox)||
|[`BoundingSphere CreateFromPoints(IEnumerable<Vector3> points)`](VRageMath.CreateFromPoints)|Creates a BoundingSphere that can contain a specified list of points.|
|[`BoundingSphere CreateFromFrustum(BoundingFrustum frustum)`](VRageMath.CreateFromFrustum)|Creates the smallest BoundingSphere that can contain a specified BoundingFrustum.|
|[`bool Intersects(BoundingBox box)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects with a specified BoundingBox.|
|[`void Intersects(ref BoundingBox box, ref bool result)`](VRageMath.Intersects)||
|[`bool Intersects(BoundingFrustum frustum)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects with a specified BoundingFrustum.|
|[`PlaneIntersectionType Intersects(Plane plane)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects with a specified Plane.|
|[`void Intersects(ref Plane plane, ref PlaneIntersectionType result)`](VRageMath.Intersects)||
|[`Nullable<float> Intersects(Ray ray)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects with a specified Ray.|
|[`void Intersects(ref Ray ray, ref Nullable<float> result)`](VRageMath.Intersects)||
|[`bool Intersects(BoundingSphere sphere)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects with a specified BoundingSphere.|
|[`void Intersects(ref BoundingSphere sphere, ref bool result)`](VRageMath.Intersects)||
|[`ContainmentType Contains(BoundingBox box)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified BoundingBox.|
|[`void Contains(ref BoundingBox box, ref ContainmentType result)`](VRageMath.Contains)||
|[`ContainmentType Contains(BoundingFrustum frustum)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified BoundingFrustum.|
|[`ContainmentType Contains(Vector3 point)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified point.|
|[`void Contains(ref Vector3 point, ref ContainmentType result)`](VRageMath.Contains)||
|[`ContainmentType Contains(BoundingSphere sphere)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified BoundingSphere.|
|[`void Contains(ref BoundingSphere sphere, ref ContainmentType result)`](VRageMath.Contains)||
|[`BoundingSphere Transform(Matrix matrix)`](VRageMath.Transform)|Translates and scales the BoundingSphere using a given Matrix.|
|[`void Transform(ref Matrix matrix, ref BoundingSphere result)`](VRageMath.Transform)||
|[`BoundingSphere Translate(ref Vector3 translation)`](VRageMath.Translate)||
|[`bool IntersectRaySphere(Ray ray, ref float tmin, ref float tmax)`](VRageMath.IntersectRaySphere)||
|[`BoundingSphere Include(BoundingSphere sphere)`](VRageMath.Include)||
|[`void Include(ref BoundingSphere sphere, ref BoundingSphere otherSphere)`](VRageMath.Include)||
|[`BoundingSphere CreateInvalid()`](VRageMath.CreateInvalid)||
