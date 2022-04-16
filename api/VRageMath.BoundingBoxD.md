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
|\\%1static ComparerType Comparer](VRageMath.BoundingBoxD.Comparer)||
|\\%1Vector3D Max](VRageMath.BoundingBoxD.Max)|The maximum point the BoundingBox contains.|
|\\%1Vector3D Min](VRageMath.BoundingBoxD.Min)|The minimum point the BoundingBox contains.|

#### Properties

|Member|Description|
|---|---|
|\\%1Vector3D Center { get; }](VRageMath.BoundingBoxD.Center)|Calculates center|
|\\%1Vector3D Extents { get; }](VRageMath.BoundingBoxD.Extents)||
|\\%1Vector3D HalfExtents { get; }](VRageMath.BoundingBoxD.HalfExtents)||
|\\%1MatrixD Matrix { get; }](VRageMath.BoundingBoxD.Matrix)|Matrix of AABB, respecting center and size|
|\\%1double Perimeter { get; }](VRageMath.BoundingBoxD.Perimeter)|return perimeter of edges|
|\\%1Vector3D Size { get; }](VRageMath.BoundingBoxD.Size)|Size|
|\\%1double SurfaceArea { get; }](VRageMath.BoundingBoxD.SurfaceArea)||
|\\%1bool Valid { get; }](VRageMath.BoundingBoxD.Valid)||
|\\%1double Volume { get; }](VRageMath.BoundingBoxD.Volume)||

#### Constructors

|Member|Description|
|---|---|
|\\%1BoundingBoxD(Vector3D, Vector3D)](VRageMath.BoundingBoxD..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\%1static BoundingBoxD CreateFromPoints(IEnumerable\\%1Vector3D>)](VRageMath.BoundingBoxD.CreateFromPoints)|Creates the smallest BoundingBox that will contain a group of points.|
|\\%1static BoundingBoxD CreateFromSphere(BoundingSphereD)](VRageMath.BoundingBoxD.CreateFromSphere)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|\\%1static void CreateFromSphere(ref BoundingSphereD, out BoundingBoxD)](VRageMath.BoundingBoxD.CreateFromSphere)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|\\%1static BoundingBoxD CreateInvalid()](VRageMath.BoundingBoxD.CreateInvalid)||
|\\%1static BoundingBoxD CreateMerged(BoundingBoxD, BoundingBoxD)](VRageMath.BoundingBoxD.CreateMerged)|Creates the smallest BoundingBox that contains the two specified BoundingBox instances.|
|\\%1static void CreateMerged(ref BoundingBoxD, ref BoundingBoxD, out BoundingBoxD)](VRageMath.BoundingBoxD.CreateMerged)|Creates the smallest BoundingBox that contains the two specified BoundingBox instances.|
|\\%1void AssertIsValid()](VRageMath.BoundingBoxD.AssertIsValid)||
|\\%1void Centerize(Vector3D)](VRageMath.BoundingBoxD.Centerize)||
|\\%1ContainmentType Contains(BoundingBoxD)](VRageMath.BoundingBoxD.Contains)|Tests whether the BoundingBox contains another BoundingBox.|
|\\%1void Contains(ref BoundingBoxD, out ContainmentType)](VRageMath.BoundingBoxD.Contains)|Tests whether the BoundingBox contains a BoundingBox.|
|\\%1ContainmentType Contains(BoundingFrustumD)](VRageMath.BoundingBoxD.Contains)|Tests whether the BoundingBox contains a BoundingFrustum.|
|\\%1ContainmentType Contains(Vector3D)](VRageMath.BoundingBoxD.Contains)|Tests whether the BoundingBox contains a point.|
|\\%1void Contains(ref Vector3D, out ContainmentType)](VRageMath.BoundingBoxD.Contains)|Tests whether the BoundingBox contains a point.|
|\\%1ContainmentType Contains(BoundingSphereD)](VRageMath.BoundingBoxD.Contains)|Tests whether the BoundingBox contains a BoundingSphere.|
|\\%1void Contains(ref BoundingSphereD, out ContainmentType)](VRageMath.BoundingBoxD.Contains)|Tests whether the BoundingBox contains a BoundingSphere.|
|\\%1double Distance(Vector3D)](VRageMath.BoundingBoxD.Distance)||
|\\%1double Distance(ref BoundingBoxD)](VRageMath.BoundingBoxD.Distance)||
|\\%1double DistanceSquared(Vector3D)](VRageMath.BoundingBoxD.DistanceSquared)||
|\\%1double DistanceSquared(ref Vector3D)](VRageMath.BoundingBoxD.DistanceSquared)||
|\\%1double DistanceSquared(ref BoundingBoxD)](VRageMath.BoundingBoxD.DistanceSquared)||
|\\%1bool Equals(BoundingBoxD)](VRageMath.BoundingBoxD.Equals)|Determines whether two instances of BoundingBox are equal.|
|\\%1bool Equals(object)](VRageMath.BoundingBoxD.Equals)|Determines whether two instances of BoundingBox are equal.|
|\\%1bool Equals(BoundingBoxD, double)](VRageMath.BoundingBoxD.Equals)||
|\\%1Vector3D\\%1] GetCorners()](VRageMath.BoundingBoxD.GetCorners)|Gets an array of points that make up the corners of the BoundingBox. ALLOCATION!|
|\\%1void GetCorners(Vector3D\\%1])](VRageMath.BoundingBoxD.GetCorners)|Gets the array of points that make up the corners of the BoundingBox.|
|\\%1void GetCornersUnsafe(*Vector3D)](VRageMath.BoundingBoxD.GetCornersUnsafe)||
|\\%1int GetHashCode()](VRageMath.BoundingBoxD.GetHashCode)|Gets the hash code for this instance.|
|\\%1BoundingBoxD GetInflated(double)](VRageMath.BoundingBoxD.GetInflated)||
|\\%1BoundingBoxD GetInflated(Vector3)](VRageMath.BoundingBoxD.GetInflated)||
|\\%1BoundingBoxD GetInflated(Vector3D)](VRageMath.BoundingBoxD.GetInflated)||
|\\%1BoundingBoxD Include(ref Vector3D)](VRageMath.BoundingBoxD.Include)|return expanded aabb (aabb include point)|
|\\%1BoundingBoxD Include(Vector3D)](VRageMath.BoundingBoxD.Include)||
|\\%1BoundingBoxD Include(Vector3D, Vector3D, Vector3D)](VRageMath.BoundingBoxD.Include)||
|\\%1BoundingBoxD Include(ref Vector3D, ref Vector3D, ref Vector3D)](VRageMath.BoundingBoxD.Include)||
|\\%1BoundingBoxD Include(ref BoundingBoxD)](VRageMath.BoundingBoxD.Include)|return expanded aabb (aabb include aabb)|
|\\%1BoundingBoxD Include(BoundingBoxD)](VRageMath.BoundingBoxD.Include)||
|\\%1void Include(ref LineD)](VRageMath.BoundingBoxD.Include)||
|\\%1BoundingBoxD Include(BoundingSphereD)](VRageMath.BoundingBoxD.Include)||
|\\%1BoundingBoxD Include(ref BoundingSphereD)](VRageMath.BoundingBoxD.Include)||
|\\%1BoundingBoxD Include(ref BoundingFrustumD)](VRageMath.BoundingBoxD.Include)||
|\\%1BoundingBoxD Inflate(double)](VRageMath.BoundingBoxD.Inflate)||
|\\%1BoundingBoxD Inflate(Vector3D)](VRageMath.BoundingBoxD.Inflate)||
|\\%1void InflateToMinimum(Vector3D)](VRageMath.BoundingBoxD.InflateToMinimum)||
|\\%1void InflateToMinimum(double)](VRageMath.BoundingBoxD.InflateToMinimum)||
|\\%1BoundingBoxD Intersect(BoundingBoxD)](VRageMath.BoundingBoxD.Intersect)|Returns bounding box which is intersection of this and box Result is invalid box when there's no intersection (Min > Max)|
|\\%1bool Intersect(ref LineD, out LineD)](VRageMath.BoundingBoxD.Intersect)||
|\\%1bool Intersect(ref LineD, out double, out double)](VRageMath.BoundingBoxD.Intersect)||
|\\%1bool Intersect(ref RayD, out double, out double)](VRageMath.BoundingBoxD.Intersect)||
|\\%1bool Intersects(BoundingBoxD)](VRageMath.BoundingBoxD.Intersects)|Checks whether the current BoundingBox intersects another BoundingBox.|
|\\%1bool Intersects(ref BoundingBoxD)](VRageMath.BoundingBoxD.Intersects)||
|\\%1void Intersects(ref BoundingBoxD, out bool)](VRageMath.BoundingBoxD.Intersects)|Checks whether the current BoundingBox intersects another BoundingBox.|
|\\%1void Intersects(ref BoundingBox, out bool)](VRageMath.BoundingBoxD.Intersects)||
|\\%1bool Intersects(BoundingFrustumD)](VRageMath.BoundingBoxD.Intersects)|Checks whether the current BoundingBox intersects a BoundingFrustum.|
|\\%1PlaneIntersectionType Intersects(PlaneD)](VRageMath.BoundingBoxD.Intersects)|Checks whether the current BoundingBox intersects a Plane.|
|\\%1void Intersects(ref PlaneD, out PlaneIntersectionType)](VRageMath.BoundingBoxD.Intersects)|Checks whether the current BoundingBox intersects a Plane.|
|\\%1bool Intersects(ref LineD)](VRageMath.BoundingBoxD.Intersects)||
|\\%1bool Intersects(ref LineD, out double)](VRageMath.BoundingBoxD.Intersects)||
|\\%1double? Intersects(Ray)](VRageMath.BoundingBoxD.Intersects)||
|\\%1double? Intersects(RayD)](VRageMath.BoundingBoxD.Intersects)|Checks whether the current BoundingBox intersects a Ray.|
|\\%1void Intersects(ref RayD, out double?)](VRageMath.BoundingBoxD.Intersects)|Checks whether the current BoundingBox intersects a Ray.|
|\\%1bool Intersects(BoundingSphereD)](VRageMath.BoundingBoxD.Intersects)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|\\%1void Intersects(ref BoundingSphereD, out bool)](VRageMath.BoundingBoxD.Intersects)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|\\%1bool Intersects(ref BoundingSphereD)](VRageMath.BoundingBoxD.Intersects)||
|\\%1bool IntersectsTriangle(Vector3D, Vector3D, Vector3D)](VRageMath.BoundingBoxD.IntersectsTriangle)||
|\\%1bool IntersectsTriangle(ref Vector3D, ref Vector3D, ref Vector3D)](VRageMath.BoundingBoxD.IntersectsTriangle)||
|\\%1double ProjectedArea(Vector3D)](VRageMath.BoundingBoxD.ProjectedArea)||
|\\%1BoundingBoxD Round(int)](VRageMath.BoundingBoxD.Round)||
|\\%1BoundingBoxI Round()](VRageMath.BoundingBoxD.Round)||
|\\%1string ToString()](VRageMath.BoundingBoxD.ToString)|Returns a String that represents the current BoundingBox.|
|\\%1BoundingBoxD TransformFast(MatrixD)](VRageMath.BoundingBoxD.TransformFast)|Transform this AABB by matrix. Matrix has to be only rotation and translation.|
|\\%1BoundingBoxD TransformFast(ref MatrixD)](VRageMath.BoundingBoxD.TransformFast)|Transform this AABB by matrix. Matrix has to be only rotation and translation.|
|\\%1void TransformFast(ref MatrixD, ref BoundingBoxD)](VRageMath.BoundingBoxD.TransformFast)|Transform this AABB by matrix. Matrix has to be only rotation and translation.|
|\\%1BoundingBoxD TransformSlow(MatrixD)](VRageMath.BoundingBoxD.TransformSlow)|Transform this AABB by matrix.|
|\\%1BoundingBoxD TransformSlow(ref MatrixD)](VRageMath.BoundingBoxD.TransformSlow)|Transform this AABB by matrix.|
|\\%1BoundingBoxD Translate(MatrixD)](VRageMath.BoundingBoxD.Translate)|Translate|
|\\%1BoundingBoxD Translate(Vector3D)](VRageMath.BoundingBoxD.Translate)|Translate|

