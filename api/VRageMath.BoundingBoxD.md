← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### BoundingBoxD Struct

```csharp
public struct BoundingBoxD: IEquatable<T>
```

Defines an axis-aligned box-shaped 3D volume.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<T>](https://docs.microsoft.com/en-us/dotnet/api/system.iequatable?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[Min](VRageMath.BoundingBoxD.Min)|The minimum point the BoundingBox contains.|
|[Max](VRageMath.BoundingBoxD.Max)|The maximum point the BoundingBox contains.|
|[Comparer](VRageMath.BoundingBoxD.Comparer)||
|[CornerCount](VRageMath.BoundingBoxD.CornerCount)|Specifies the total number of corners (8) in the BoundingBox.|

#### Properties

|Member|Description|
|---|---|
|[Center](VRageMath.BoundingBoxD.Center)|Calculates center|
|[HalfExtents](VRageMath.BoundingBoxD.HalfExtents)||
|[Extents](VRageMath.BoundingBoxD.Extents)||
|[Size](VRageMath.BoundingBoxD.Size)|Size|
|[Matrix](VRageMath.BoundingBoxD.Matrix)|Matrix of AABB, respection center and size|
|[SurfaceArea](VRageMath.BoundingBoxD.SurfaceArea)||
|[Volume](VRageMath.BoundingBoxD.Volume)||
|[Perimeter](VRageMath.BoundingBoxD.Perimeter)|return perimeter of edges|
|[Valid](VRageMath.BoundingBoxD.Valid)||

#### Methods

|Member|Description|
|---|---|
|[GetCorners()](VRageMath.BoundingBoxD.GetCorners)|Gets an array of points that make up the corners of the BoundingBox. ALLOCATION!|
|[GetCorners(Vector3D[])](VRageMath.BoundingBoxD.GetCorners)|Gets the array of points that make up the corners of the BoundingBox.|
|[GetCornersUnsafe(*Vector3D)](VRageMath.BoundingBoxD.GetCornersUnsafe)||
|[Equals(BoundingBoxD)](VRageMath.BoundingBoxD.Equals)|Determines whether two instances of BoundingBox are equal.|
|[Equals(object)](VRageMath.BoundingBoxD.Equals)|Determines whether two instances of BoundingBox are equal.|
|[GetHashCode()](VRageMath.BoundingBoxD.GetHashCode)|Gets the hash code for this instance.|
|[ToString()](VRageMath.BoundingBoxD.ToString)|Returns a String that represents the current BoundingBox.|
|[CreateMerged(BoundingBoxD, BoundingBoxD)](VRageMath.BoundingBoxD.CreateMerged)|Creates the smallest BoundingBox that contains the two specified BoundingBox instances.|
|[CreateMerged(ref BoundingBoxD, ref BoundingBoxD, ref BoundingBoxD)](VRageMath.BoundingBoxD.CreateMerged)|Creates the smallest BoundingBox that contains the two specified BoundingBox instances.|
|[CreateFromSphere(BoundingSphereD)](VRageMath.BoundingBoxD.CreateFromSphere)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|[CreateFromSphere(ref BoundingSphereD, ref BoundingBoxD)](VRageMath.BoundingBoxD.CreateFromSphere)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|[CreateFromPoints(IEnumerable)](VRageMath.BoundingBoxD.CreateFromPoints)||
|[Intersect(BoundingBoxD)](VRageMath.BoundingBoxD.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[Intersects(BoundingBoxD)](VRageMath.BoundingBoxD.Intersects)|Checks whether the current BoundingBox intersects another BoundingBox.|
|[Intersects(ref BoundingBoxD)](VRageMath.BoundingBoxD.Intersects)||
|[Intersects(ref BoundingBoxD, ref bool)](VRageMath.BoundingBoxD.Intersects)|Checks whether the current BoundingBox intersects another BoundingBox.|
|[Intersects(ref BoundingBox, ref bool)](VRageMath.BoundingBoxD.Intersects)||
|[IntersectsTriangle(Vector3D, Vector3D, Vector3D)](VRageMath.BoundingBoxD.IntersectsTriangle)||
|[IntersectsTriangle(ref Vector3D, ref Vector3D, ref Vector3D)](VRageMath.BoundingBoxD.IntersectsTriangle)||
|[Intersects(BoundingFrustumD)](VRageMath.BoundingBoxD.Intersects)|Checks whether the current BoundingBox intersects a BoundingFrustum.|
|[Intersects(PlaneD)](VRageMath.BoundingBoxD.Intersects)|Checks whether the current BoundingBox intersects a Plane.|
|[Intersects(ref PlaneD, ref PlaneIntersectionType)](VRageMath.BoundingBoxD.Intersects)|Checks whether the current BoundingBox intersects a Plane.|
|[Intersects(ref LineD)](VRageMath.BoundingBoxD.Intersects)||
|[Intersects(ref LineD, ref double)](VRageMath.BoundingBoxD.Intersects)||
|[Intersects(Ray)](VRageMath.BoundingBoxD.Intersects)||
|[Intersects(RayD)](VRageMath.BoundingBoxD.Intersects)|Checks whether the current BoundingBox intersects a Ray.|
|[Intersects(ref RayD, ref Nullable)](VRageMath.BoundingBoxD.Intersects)||
|[Intersect(ref LineD, ref LineD)](VRageMath.BoundingBoxD.Intersect)||
|[Intersect(ref LineD, ref double, ref double)](VRageMath.BoundingBoxD.Intersect)||
|[Intersect(ref RayD, ref double, ref double)](VRageMath.BoundingBoxD.Intersect)||
|[Intersects(BoundingSphereD)](VRageMath.BoundingBoxD.Intersects)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|[Intersects(ref BoundingSphereD, ref bool)](VRageMath.BoundingBoxD.Intersects)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|[Intersects(ref BoundingSphereD)](VRageMath.BoundingBoxD.Intersects)||
|[Distance(Vector3D)](VRageMath.BoundingBoxD.Distance)||
|[DistanceSquared(Vector3D)](VRageMath.BoundingBoxD.DistanceSquared)||
|[DistanceSquared(ref Vector3D)](VRageMath.BoundingBoxD.DistanceSquared)||
|[Contains(BoundingBoxD)](VRageMath.BoundingBoxD.Contains)|Tests whether the BoundingBox contains another BoundingBox.|
|[Contains(ref BoundingBoxD, ref ContainmentType)](VRageMath.BoundingBoxD.Contains)|Tests whether the BoundingBox contains a BoundingBox.|
|[Contains(BoundingFrustumD)](VRageMath.BoundingBoxD.Contains)|Tests whether the BoundingBox contains a BoundingFrustum.|
|[Contains(Vector3D)](VRageMath.BoundingBoxD.Contains)|Tests whether the BoundingBox contains a point.|
|[Contains(ref Vector3D, ref ContainmentType)](VRageMath.BoundingBoxD.Contains)|Tests whether the BoundingBox contains a point.|
|[Contains(BoundingSphereD)](VRageMath.BoundingBoxD.Contains)|Tests whether the BoundingBox contains a BoundingSphere.|
|[Contains(ref BoundingSphereD, ref ContainmentType)](VRageMath.BoundingBoxD.Contains)|Tests whether the BoundingBox contains a BoundingSphere.|
|[Translate(MatrixD)](VRageMath.BoundingBoxD.Translate)|Translate|
|[Translate(Vector3D)](VRageMath.BoundingBoxD.Translate)|Translate|
|[TransformSlow(MatrixD)](VRageMath.BoundingBoxD.TransformSlow)|Transform this AABB by matrix.|
|[TransformSlow(ref MatrixD)](VRageMath.BoundingBoxD.TransformSlow)|Transform this AABB by matrix.|
|[TransformFast(MatrixD)](VRageMath.BoundingBoxD.TransformFast)|Transform this AABB by matrix. Matrix has to be only rotation and translation.|
|[TransformFast(ref MatrixD)](VRageMath.BoundingBoxD.TransformFast)|Transform this AABB by matrix. Matrix has to be only rotation and translation.|
|[TransformFast(ref MatrixD, ref BoundingBoxD)](VRageMath.BoundingBoxD.TransformFast)|Transform this AABB by matrix. Matrix has to be only rotation and translation.|
|[Include(ref Vector3D)](VRageMath.BoundingBoxD.Include)|return expanded aabb (aabb include point)|
|[Include(Vector3D)](VRageMath.BoundingBoxD.Include)||
|[Include(Vector3D, Vector3D, Vector3D)](VRageMath.BoundingBoxD.Include)||
|[Include(ref Vector3D, ref Vector3D, ref Vector3D)](VRageMath.BoundingBoxD.Include)||
|[Include(ref BoundingBoxD)](VRageMath.BoundingBoxD.Include)|return expanded aabb (aabb include aabb)|
|[Include(BoundingBoxD)](VRageMath.BoundingBoxD.Include)||
|[Include(ref LineD)](VRageMath.BoundingBoxD.Include)||
|[Include(BoundingSphereD)](VRageMath.BoundingBoxD.Include)||
|[Include(ref BoundingSphereD)](VRageMath.BoundingBoxD.Include)||
|[Include(ref BoundingFrustumD)](VRageMath.BoundingBoxD.Include)||
|[CreateInvalid()](VRageMath.BoundingBoxD.CreateInvalid)||
|[ProjectedArea(Vector3D)](VRageMath.BoundingBoxD.ProjectedArea)||
|[Inflate(double)](VRageMath.BoundingBoxD.Inflate)||
|[Inflate(Vector3)](VRageMath.BoundingBoxD.Inflate)||
|[GetInflated(double)](VRageMath.BoundingBoxD.GetInflated)||
|[GetInflated(Vector3)](VRageMath.BoundingBoxD.GetInflated)||
|[InflateToMinimum(Vector3D)](VRageMath.BoundingBoxD.InflateToMinimum)||
|[InflateToMinimum(double)](VRageMath.BoundingBoxD.InflateToMinimum)||
|[AssertIsValid()](VRageMath.BoundingBoxD.AssertIsValid)||

