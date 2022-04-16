← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### BoundingBoxD Struct

```csharp
public struct BoundingBoxD: IEquatable<BoundingBoxD>
```

Defines an axis-aligned box-shaped 3D volume.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<BoundingBoxD>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[static ComparerType Comparer](VRageMath.BoundingBoxD.Comparer)||
|[Vector3D Max](VRageMath.BoundingBoxD.Max)|The maximum point the BoundingBox contains.|
|[Vector3D Min](VRageMath.BoundingBoxD.Min)|The minimum point the BoundingBox contains.|

#### Properties

|Member|Description|
|---|---|
|[Vector3D Center { get; }](VRageMath.BoundingBoxD.Center)|Calculates center|
|[Vector3D Extents { get; }](VRageMath.BoundingBoxD.Extents)||
|[Vector3D HalfExtents { get; }](VRageMath.BoundingBoxD.HalfExtents)||
|[MatrixD Matrix { get; }](VRageMath.BoundingBoxD.Matrix)|Matrix of AABB, respecting center and size|
|[double Perimeter { get; }](VRageMath.BoundingBoxD.Perimeter)|return perimeter of edges|
|[Vector3D Size { get; }](VRageMath.BoundingBoxD.Size)|Size|
|[double SurfaceArea { get; }](VRageMath.BoundingBoxD.SurfaceArea)||
|[bool Valid { get; }](VRageMath.BoundingBoxD.Valid)||
|[double Volume { get; }](VRageMath.BoundingBoxD.Volume)||

#### Constructors

|Member|Description|
|---|---|
|[BoundingBoxD(Vector3D, Vector3D)](VRageMath.BoundingBoxD..ctor)||

#### Methods

|Member|Description|
|---|---|
|[static BoundingBoxD CreateFromPoints(IEnumerable<Vector3D>)](VRageMath.BoundingBoxD.CreateFromPoints)|Creates the smallest BoundingBox that will contain a group of points.|
|[static BoundingBoxD CreateFromSphere(BoundingSphereD)](VRageMath.BoundingBoxD.CreateFromSphere)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|[static void CreateFromSphere(ref BoundingSphereD, out BoundingBoxD)](VRageMath.BoundingBoxD.CreateFromSphere)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|[static BoundingBoxD CreateInvalid()](VRageMath.BoundingBoxD.CreateInvalid)||
|[static BoundingBoxD CreateMerged(BoundingBoxD, BoundingBoxD)](VRageMath.BoundingBoxD.CreateMerged)|Creates the smallest BoundingBox that contains the two specified BoundingBox instances.|
|[static void CreateMerged(ref BoundingBoxD, ref BoundingBoxD, out BoundingBoxD)](VRageMath.BoundingBoxD.CreateMerged)|Creates the smallest BoundingBox that contains the two specified BoundingBox instances.|
|[void AssertIsValid()](VRageMath.BoundingBoxD.AssertIsValid)||
|[void Centerize(Vector3D)](VRageMath.BoundingBoxD.Centerize)||
|[ContainmentType Contains(BoundingBoxD)](VRageMath.BoundingBoxD.Contains)|Tests whether the BoundingBox contains another BoundingBox.|
|[void Contains(ref BoundingBoxD, out ContainmentType)](VRageMath.BoundingBoxD.Contains)|Tests whether the BoundingBox contains a BoundingBox.|
|[ContainmentType Contains(BoundingFrustumD)](VRageMath.BoundingBoxD.Contains)|Tests whether the BoundingBox contains a BoundingFrustum.|
|[ContainmentType Contains(Vector3D)](VRageMath.BoundingBoxD.Contains)|Tests whether the BoundingBox contains a point.|
|[void Contains(ref Vector3D, out ContainmentType)](VRageMath.BoundingBoxD.Contains)|Tests whether the BoundingBox contains a point.|
|[ContainmentType Contains(BoundingSphereD)](VRageMath.BoundingBoxD.Contains)|Tests whether the BoundingBox contains a BoundingSphere.|
|[void Contains(ref BoundingSphereD, out ContainmentType)](VRageMath.BoundingBoxD.Contains)|Tests whether the BoundingBox contains a BoundingSphere.|
|[double Distance(Vector3D)](VRageMath.BoundingBoxD.Distance)||
|[double Distance(ref BoundingBoxD)](VRageMath.BoundingBoxD.Distance)||
|[double DistanceSquared(Vector3D)](VRageMath.BoundingBoxD.DistanceSquared)||
|[double DistanceSquared(ref Vector3D)](VRageMath.BoundingBoxD.DistanceSquared)||
|[double DistanceSquared(ref BoundingBoxD)](VRageMath.BoundingBoxD.DistanceSquared)||
|[bool Equals(BoundingBoxD)](VRageMath.BoundingBoxD.Equals)|Determines whether two instances of BoundingBox are equal.|
|[bool Equals(object)](VRageMath.BoundingBoxD.Equals)|Determines whether two instances of BoundingBox are equal.|
|[bool Equals(BoundingBoxD, double)](VRageMath.BoundingBoxD.Equals)||
|[Vector3D[] GetCorners()](VRageMath.BoundingBoxD.GetCorners)|Gets an array of points that make up the corners of the BoundingBox. ALLOCATION!|
|[void GetCorners(Vector3D[])](VRageMath.BoundingBoxD.GetCorners)|Gets the array of points that make up the corners of the BoundingBox.|
|[void GetCornersUnsafe(*Vector3D)](VRageMath.BoundingBoxD.GetCornersUnsafe)||
|[int GetHashCode()](VRageMath.BoundingBoxD.GetHashCode)|Gets the hash code for this instance.|
|[BoundingBoxD GetInflated(double)](VRageMath.BoundingBoxD.GetInflated)||
|[BoundingBoxD GetInflated(Vector3)](VRageMath.BoundingBoxD.GetInflated)||
|[BoundingBoxD GetInflated(Vector3D)](VRageMath.BoundingBoxD.GetInflated)||
|[BoundingBoxD Include(ref Vector3D)](VRageMath.BoundingBoxD.Include)|return expanded aabb (aabb include point)|
|[BoundingBoxD Include(Vector3D)](VRageMath.BoundingBoxD.Include)||
|[BoundingBoxD Include(Vector3D, Vector3D, Vector3D)](VRageMath.BoundingBoxD.Include)||
|[BoundingBoxD Include(ref Vector3D, ref Vector3D, ref Vector3D)](VRageMath.BoundingBoxD.Include)||
|[BoundingBoxD Include(ref BoundingBoxD)](VRageMath.BoundingBoxD.Include)|return expanded aabb (aabb include aabb)|
|[BoundingBoxD Include(BoundingBoxD)](VRageMath.BoundingBoxD.Include)||
|[void Include(ref LineD)](VRageMath.BoundingBoxD.Include)||
|[BoundingBoxD Include(BoundingSphereD)](VRageMath.BoundingBoxD.Include)||
|[BoundingBoxD Include(ref BoundingSphereD)](VRageMath.BoundingBoxD.Include)||
|[BoundingBoxD Include(ref BoundingFrustumD)](VRageMath.BoundingBoxD.Include)||
|[BoundingBoxD Inflate(double)](VRageMath.BoundingBoxD.Inflate)||
|[BoundingBoxD Inflate(Vector3D)](VRageMath.BoundingBoxD.Inflate)||
|[void InflateToMinimum(Vector3D)](VRageMath.BoundingBoxD.InflateToMinimum)||
|[void InflateToMinimum(double)](VRageMath.BoundingBoxD.InflateToMinimum)||
|[BoundingBoxD Intersect(BoundingBoxD)](VRageMath.BoundingBoxD.Intersect)|Returns bounding box which is intersection of this and box Result is invalid box when there's no intersection (Min > Max)|
|[bool Intersect(ref LineD, out LineD)](VRageMath.BoundingBoxD.Intersect)||
|[bool Intersect(ref LineD, out double, out double)](VRageMath.BoundingBoxD.Intersect)||
|[bool Intersect(ref RayD, out double, out double)](VRageMath.BoundingBoxD.Intersect)||
|[bool Intersects(BoundingBoxD)](VRageMath.BoundingBoxD.Intersects)|Checks whether the current BoundingBox intersects another BoundingBox.|
|[bool Intersects(ref BoundingBoxD)](VRageMath.BoundingBoxD.Intersects)||
|[void Intersects(ref BoundingBoxD, out bool)](VRageMath.BoundingBoxD.Intersects)|Checks whether the current BoundingBox intersects another BoundingBox.|
|[void Intersects(ref BoundingBox, out bool)](VRageMath.BoundingBoxD.Intersects)||
|[bool Intersects(BoundingFrustumD)](VRageMath.BoundingBoxD.Intersects)|Checks whether the current BoundingBox intersects a BoundingFrustum.|
|[PlaneIntersectionType Intersects(PlaneD)](VRageMath.BoundingBoxD.Intersects)|Checks whether the current BoundingBox intersects a Plane.|
|[void Intersects(ref PlaneD, out PlaneIntersectionType)](VRageMath.BoundingBoxD.Intersects)|Checks whether the current BoundingBox intersects a Plane.|
|[bool Intersects(ref LineD)](VRageMath.BoundingBoxD.Intersects)||
|[bool Intersects(ref LineD, out double)](VRageMath.BoundingBoxD.Intersects)||
|[double? Intersects(Ray)](VRageMath.BoundingBoxD.Intersects)||
|[double? Intersects(RayD)](VRageMath.BoundingBoxD.Intersects)|Checks whether the current BoundingBox intersects a Ray.|
|[void Intersects(ref RayD, out double?)](VRageMath.BoundingBoxD.Intersects)|Checks whether the current BoundingBox intersects a Ray.|
|[bool Intersects(BoundingSphereD)](VRageMath.BoundingBoxD.Intersects)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|[void Intersects(ref BoundingSphereD, out bool)](VRageMath.BoundingBoxD.Intersects)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|[bool Intersects(ref BoundingSphereD)](VRageMath.BoundingBoxD.Intersects)||
|[bool IntersectsTriangle(Vector3D, Vector3D, Vector3D)](VRageMath.BoundingBoxD.IntersectsTriangle)||
|[bool IntersectsTriangle(ref Vector3D, ref Vector3D, ref Vector3D)](VRageMath.BoundingBoxD.IntersectsTriangle)||
|[double ProjectedArea(Vector3D)](VRageMath.BoundingBoxD.ProjectedArea)||
|[BoundingBoxD Round(int)](VRageMath.BoundingBoxD.Round)||
|[BoundingBoxI Round()](VRageMath.BoundingBoxD.Round)||
|[string ToString()](VRageMath.BoundingBoxD.ToString)|Returns a String that represents the current BoundingBox.|
|[BoundingBoxD TransformFast(MatrixD)](VRageMath.BoundingBoxD.TransformFast)|Transform this AABB by matrix. Matrix has to be only rotation and translation.|
|[BoundingBoxD TransformFast(ref MatrixD)](VRageMath.BoundingBoxD.TransformFast)|Transform this AABB by matrix. Matrix has to be only rotation and translation.|
|[void TransformFast(ref MatrixD, ref BoundingBoxD)](VRageMath.BoundingBoxD.TransformFast)|Transform this AABB by matrix. Matrix has to be only rotation and translation.|
|[BoundingBoxD TransformSlow(MatrixD)](VRageMath.BoundingBoxD.TransformSlow)|Transform this AABB by matrix.|
|[BoundingBoxD TransformSlow(ref MatrixD)](VRageMath.BoundingBoxD.TransformSlow)|Transform this AABB by matrix.|
|[BoundingBoxD Translate(MatrixD)](VRageMath.BoundingBoxD.Translate)|Translate|
|[BoundingBoxD Translate(Vector3D)](VRageMath.BoundingBoxD.Translate)|Translate|

