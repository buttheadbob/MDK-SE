← [Index](index)
# BoundingSphere Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a sphere.
### Fields
|Member|Description|
|---|---|
|[`Vector3&nbsp;Center`](VRageMath.Center)|The center point of the sphere.|
|[`float&nbsp;Radius`](VRageMath.Radius)|The radius of the sphere.|
### Methods
|Member|Description|
|---|---|
|[`bool&nbsp;Equals(BoundingSphere&nbsp;other)`](VRageMath.Equals)|Determines whether the specified BoundingSphere is equal to the current BoundingSphere.|
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Determines whether the specified Object is equal to the BoundingSphere.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string&nbsp;ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingSphere.|
|static&nbsp;[`BoundingSphere&nbsp;CreateMerged(BoundingSphere&nbsp;original,&nbsp;BoundingSphere&nbsp;additional)`](VRageMath.CreateMerged)|Creates a BoundingSphere that contains the two specified BoundingSphere instances.|
|static&nbsp;[`void&nbsp;CreateMerged(ref&nbsp;BoundingSphere&nbsp;original,&nbsp;ref&nbsp;BoundingSphere&nbsp;additional,&nbsp;ref&nbsp;BoundingSphere&nbsp;result)`](VRageMath.CreateMerged)|Creates a BoundingSphere that contains the two specified BoundingSphere instances.|
|static&nbsp;[`BoundingSphere&nbsp;CreateFromBoundingBox(BoundingBox&nbsp;box)`](VRageMath.CreateFromBoundingBox)|Creates the smallest BoundingSphere that can contain a specified BoundingBox.|
|static&nbsp;[`void&nbsp;CreateFromBoundingBox(ref&nbsp;BoundingBox&nbsp;box,&nbsp;ref&nbsp;BoundingSphere&nbsp;result)`](VRageMath.CreateFromBoundingBox)|Creates the smallest BoundingSphere that can contain a specified BoundingBox.|
|static&nbsp;[`BoundingSphere&nbsp;CreateFromPoints(IEnumerable<Vector3>&nbsp;points)`](VRageMath.CreateFromPoints)|Creates a BoundingSphere that can contain a specified list of points.|
|static&nbsp;[`BoundingSphere&nbsp;CreateFromFrustum(BoundingFrustum&nbsp;frustum)`](VRageMath.CreateFromFrustum)|Creates the smallest BoundingSphere that can contain a specified BoundingFrustum.|
|[`bool&nbsp;Intersects(BoundingBox&nbsp;box)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects with a specified BoundingBox.|
|[`void&nbsp;Intersects(ref&nbsp;BoundingBox&nbsp;box,&nbsp;ref&nbsp;bool&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects a BoundingBox.|
|[`bool&nbsp;Intersects(BoundingFrustum&nbsp;frustum)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects with a specified BoundingFrustum.|
|[`PlaneIntersectionType&nbsp;Intersects(Plane&nbsp;plane)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects with a specified Plane.|
|[`void&nbsp;Intersects(ref&nbsp;Plane&nbsp;plane,&nbsp;ref&nbsp;PlaneIntersectionType&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects a Plane.|
|[`Nullable<float>&nbsp;Intersects(Ray&nbsp;ray)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects with a specified Ray.|
|[`void&nbsp;Intersects(ref&nbsp;Ray&nbsp;ray,&nbsp;ref&nbsp;Nullable<float>&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects a Ray.|
|[`bool&nbsp;Intersects(BoundingSphere&nbsp;sphere)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects with a specified BoundingSphere.|
|[`void&nbsp;Intersects(ref&nbsp;BoundingSphere&nbsp;sphere,&nbsp;ref&nbsp;bool&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingSphere intersects another BoundingSphere.|
|[`ContainmentType&nbsp;Contains(BoundingBox&nbsp;box)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified BoundingBox.|
|[`void&nbsp;Contains(ref&nbsp;BoundingBox&nbsp;box,&nbsp;ref&nbsp;ContainmentType&nbsp;result)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified BoundingBox.|
|[`ContainmentType&nbsp;Contains(BoundingFrustum&nbsp;frustum)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified BoundingFrustum.|
|[`ContainmentType&nbsp;Contains(Vector3&nbsp;point)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified point.|
|[`void&nbsp;Contains(ref&nbsp;Vector3&nbsp;point,&nbsp;ref&nbsp;ContainmentType&nbsp;result)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified point.|
|[`ContainmentType&nbsp;Contains(BoundingSphere&nbsp;sphere)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified BoundingSphere.|
|[`void&nbsp;Contains(ref&nbsp;BoundingSphere&nbsp;sphere,&nbsp;ref&nbsp;ContainmentType&nbsp;result)`](VRageMath.Contains)|Checks whether the current BoundingSphere contains the specified BoundingSphere.|
|[`BoundingSphere&nbsp;Transform(Matrix&nbsp;matrix)`](VRageMath.Transform)|Translates and scales the BoundingSphere using a given Matrix.|
|[`void&nbsp;Transform(ref&nbsp;Matrix&nbsp;matrix,&nbsp;ref&nbsp;BoundingSphere&nbsp;result)`](VRageMath.Transform)|Translates and scales the BoundingSphere using a given Matrix.|
|[`BoundingSphere&nbsp;Translate(ref&nbsp;Vector3&nbsp;translation)`](VRageMath.Translate)||
|[`bool&nbsp;IntersectRaySphere(Ray&nbsp;ray,&nbsp;ref&nbsp;float&nbsp;tmin,&nbsp;ref&nbsp;float&nbsp;tmax)`](VRageMath.IntersectRaySphere)||
|[`BoundingSphere&nbsp;Include(BoundingSphere&nbsp;sphere)`](VRageMath.Include)||
|static&nbsp;[`void&nbsp;Include(ref&nbsp;BoundingSphere&nbsp;sphere,&nbsp;ref&nbsp;BoundingSphere&nbsp;otherSphere)`](VRageMath.Include)||
|static&nbsp;[`BoundingSphere&nbsp;CreateInvalid()`](VRageMath.CreateInvalid)||
