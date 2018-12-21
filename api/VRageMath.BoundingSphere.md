← [Index](index.md)
# BoundingSphere Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Defines a sphere.
### Fields
|Member|Description|
|---|---|
|[`Vector3 Center`](VRageMath.Center.md)||
|[`float Radius`](VRageMath.Radius.md)||
### Methods
|Member|Description|
|---|---|
|[`bool Equals(BoundingSphere other)`](VRageMath.Equals.md)|Determines whether the specified BoundingSphere is equal to the current BoundingSphere.|
|[`bool Equals(Object obj)`](VRageMath.Equals.md)|Determines whether the specified Object is equal to the BoundingSphere.|
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`string ToString()`](VRageMath.ToString.md)||
|[`BoundingSphere CreateMerged(BoundingSphere original, BoundingSphere additional)`](VRageMath.CreateMerged.md)||
|[`void CreateMerged(ref BoundingSphere original, ref BoundingSphere additional, ref BoundingSphere result)`](VRageMath.CreateMerged.md)||
|[`BoundingSphere CreateFromBoundingBox(BoundingBox box)`](VRageMath.CreateFromBoundingBox.md)|Creates the smallest BoundingSphere that can contain a specified BoundingBox.|
|[`void CreateFromBoundingBox(ref BoundingBox box, ref BoundingSphere result)`](VRageMath.CreateFromBoundingBox.md)||
|[`BoundingSphere CreateFromPoints(IEnumerable<Vector3> points)`](VRageMath.CreateFromPoints.md)|Creates a BoundingSphere that can contain a specified list of points.|
|[`BoundingSphere CreateFromFrustum(BoundingFrustum frustum)`](VRageMath.CreateFromFrustum.md)|Creates the smallest BoundingSphere that can contain a specified BoundingFrustum.|
|[`bool Intersects(BoundingBox box)`](VRageMath.Intersects.md)|Checks whether the current BoundingSphere intersects with a specified BoundingBox.|
|[`void Intersects(ref BoundingBox box, ref bool result)`](VRageMath.Intersects.md)||
|[`bool Intersects(BoundingFrustum frustum)`](VRageMath.Intersects.md)|Checks whether the current BoundingSphere intersects with a specified BoundingFrustum.|
|[`PlaneIntersectionType Intersects(Plane plane)`](VRageMath.Intersects.md)|Checks whether the current BoundingSphere intersects with a specified Plane.|
|[`void Intersects(ref Plane plane, ref PlaneIntersectionType result)`](VRageMath.Intersects.md)||
|[`Nullable<float> Intersects(Ray ray)`](VRageMath.Intersects.md)|Checks whether the current BoundingSphere intersects with a specified Ray.|
|[`void Intersects(ref Ray ray, ref Nullable<float> result)`](VRageMath.Intersects.md)||
|[`bool Intersects(BoundingSphere sphere)`](VRageMath.Intersects.md)|Checks whether the current BoundingSphere intersects with a specified BoundingSphere.|
|[`void Intersects(ref BoundingSphere sphere, ref bool result)`](VRageMath.Intersects.md)||
|[`ContainmentType Contains(BoundingBox box)`](VRageMath.Contains.md)|Checks whether the current BoundingSphere contains the specified BoundingBox.|
|[`void Contains(ref BoundingBox box, ref ContainmentType result)`](VRageMath.Contains.md)||
|[`ContainmentType Contains(BoundingFrustum frustum)`](VRageMath.Contains.md)|Checks whether the current BoundingSphere contains the specified BoundingFrustum.|
|[`ContainmentType Contains(Vector3 point)`](VRageMath.Contains.md)|Checks whether the current BoundingSphere contains the specified point.|
|[`void Contains(ref Vector3 point, ref ContainmentType result)`](VRageMath.Contains.md)||
|[`ContainmentType Contains(BoundingSphere sphere)`](VRageMath.Contains.md)|Checks whether the current BoundingSphere contains the specified BoundingSphere.|
|[`void Contains(ref BoundingSphere sphere, ref ContainmentType result)`](VRageMath.Contains.md)||
|[`BoundingSphere Transform(Matrix matrix)`](VRageMath.Transform.md)|Translates and scales the BoundingSphere using a given Matrix.|
|[`void Transform(ref Matrix matrix, ref BoundingSphere result)`](VRageMath.Transform.md)||
|[`BoundingSphere Translate(ref Vector3 translation)`](VRageMath.Translate.md)||
|[`bool IntersectRaySphere(Ray ray, ref float tmin, ref float tmax)`](VRageMath.IntersectRaySphere.md)||
|[`BoundingSphere Include(BoundingSphere sphere)`](VRageMath.Include.md)||
|[`void Include(ref BoundingSphere sphere, ref BoundingSphere otherSphere)`](VRageMath.Include.md)||
|[`BoundingSphere CreateInvalid()`](VRageMath.CreateInvalid.md)||
