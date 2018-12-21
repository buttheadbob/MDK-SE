← [Index](index)
# BoundingSphereD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a sphere.
### Fields
|Member|Description|
|---|---|
|[`Vector3D&nbsp;Center`](VRageMath.Center)|The center point of the sphere.|
|[`double&nbsp;Radius`](VRageMath.Radius)|The radius of the sphere.|
### Methods
|Member|Description|
|---|---|
|[`bool&nbsp;Equals(BoundingSphereD&nbsp;other)`](VRageMath.Equals)|Determines whether the specified BoundingSphereD is equal to the current BoundingSphereD.|
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Determines whether the specified Object is equal to the BoundingSphereD.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string&nbsp;ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingSphereD.|
|static&nbsp;[`BoundingSphereD&nbsp;CreateMerged(BoundingSphereD&nbsp;original,&nbsp;BoundingSphereD&nbsp;additional)`](VRageMath.CreateMerged)|Creates a BoundingSphereD that contains the two specified BoundingSphereD instances.|
|static&nbsp;[`void&nbsp;CreateMerged(ref&nbsp;BoundingSphereD&nbsp;original,&nbsp;ref&nbsp;BoundingSphereD&nbsp;additional,&nbsp;ref&nbsp;BoundingSphereD&nbsp;result)`](VRageMath.CreateMerged)|Creates a BoundingSphereD that contains the two specified BoundingSphereD instances.|
|static&nbsp;[`BoundingSphereD&nbsp;CreateFromBoundingBox(BoundingBoxD&nbsp;box)`](VRageMath.CreateFromBoundingBox)|Creates the smallest BoundingSphereD that can contain a specified BoundingBoxD.|
|static&nbsp;[`void&nbsp;CreateFromBoundingBox(ref&nbsp;BoundingBoxD&nbsp;box,&nbsp;ref&nbsp;BoundingSphereD&nbsp;result)`](VRageMath.CreateFromBoundingBox)|Creates the smallest BoundingSphereD that can contain a specified BoundingBoxD.|
|static&nbsp;[`BoundingSphereD&nbsp;CreateFromPoints(Vector3D[]&nbsp;points)`](VRageMath.CreateFromPoints)|Creates a BoundingSphereD that can contain a specified list of points.|
|static&nbsp;[`BoundingSphereD&nbsp;CreateFromFrustum(BoundingFrustumD&nbsp;frustum)`](VRageMath.CreateFromFrustum)|Creates the smallest BoundingSphereD that can contain a specified BoundingFrustum.|
|[`bool&nbsp;Intersects(BoundingBoxD&nbsp;box)`](VRageMath.Intersects)|Checks whether the current BoundingSphereD intersects with a specified BoundingBoxD.|
|[`void&nbsp;Intersects(ref&nbsp;BoundingBoxD&nbsp;box,&nbsp;ref&nbsp;bool&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingSphereD intersects a BoundingBoxD.|
|[`Nullable<double>&nbsp;Intersects(RayD&nbsp;ray)`](VRageMath.Intersects)||
|[`bool&nbsp;Intersects(BoundingFrustumD&nbsp;frustum)`](VRageMath.Intersects)|Checks whether the current BoundingSphereD intersects with a specified BoundingFrustum.|
|[`bool&nbsp;Intersects(BoundingSphereD&nbsp;sphere)`](VRageMath.Intersects)|Checks whether the current BoundingSphereD intersects with a specified BoundingSphereD.|
|[`void&nbsp;Intersects(ref&nbsp;BoundingSphereD&nbsp;sphere,&nbsp;ref&nbsp;bool&nbsp;result)`](VRageMath.Intersects)|Checks whether the current BoundingSphereD intersects another BoundingSphereD.|
|[`ContainmentType&nbsp;Contains(BoundingBoxD&nbsp;box)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingBoxD.|
|[`void&nbsp;Contains(ref&nbsp;BoundingBoxD&nbsp;box,&nbsp;ref&nbsp;ContainmentType&nbsp;result)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingBoxD.|
|[`ContainmentType&nbsp;Contains(BoundingFrustumD&nbsp;frustum)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingFrustum.|
|[`ContainmentType&nbsp;Contains(Vector3D&nbsp;point)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified point.|
|[`void&nbsp;Contains(ref&nbsp;Vector3D&nbsp;point,&nbsp;ref&nbsp;ContainmentType&nbsp;result)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified point.|
|[`ContainmentType&nbsp;Contains(BoundingSphereD&nbsp;sphere)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingSphereD.|
|[`void&nbsp;Contains(ref&nbsp;BoundingSphereD&nbsp;sphere,&nbsp;ref&nbsp;ContainmentType&nbsp;result)`](VRageMath.Contains)|Checks whether the current BoundingSphereD contains the specified BoundingSphereD.|
|[`BoundingSphereD&nbsp;Transform(MatrixD&nbsp;matrix)`](VRageMath.Transform)|Translates and scales the BoundingSphereD using a given Matrix.|
|[`void&nbsp;Transform(ref&nbsp;MatrixD&nbsp;matrix,&nbsp;ref&nbsp;BoundingSphereD&nbsp;result)`](VRageMath.Transform)|Translates and scales the BoundingSphereD using a given Matrix.|
|[`bool&nbsp;IntersectRaySphere(RayD&nbsp;ray,&nbsp;ref&nbsp;double&nbsp;tmin,&nbsp;ref&nbsp;double&nbsp;tmax)`](VRageMath.IntersectRaySphere)||
|[`BoundingSphereD&nbsp;Include(BoundingSphereD&nbsp;sphere)`](VRageMath.Include)||
|static&nbsp;[`void&nbsp;Include(ref&nbsp;BoundingSphereD&nbsp;sphere,&nbsp;ref&nbsp;BoundingSphereD&nbsp;otherSphere)`](VRageMath.Include)||
|static&nbsp;[`BoundingSphereD&nbsp;CreateInvalid()`](VRageMath.CreateInvalid)||
