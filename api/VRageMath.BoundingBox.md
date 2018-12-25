← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### BoundingBox Struct

```csharp
public struct BoundingBox: IEquatable<T>
```

Defines an axis-aligned box-shaped 3D volume.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<T>](https://docs.microsoft.com/en-us/dotnet/api/system.iequatable?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[Min](VRageMath.BoundingBox.Min)|The minimum point the BoundingBox contains.|
|[Max](VRageMath.BoundingBox.Max)|The maximum point the BoundingBox contains.|
|[Comparer](VRageMath.BoundingBox.Comparer)||
|[CornerCount](VRageMath.BoundingBox.CornerCount)|Specifies the total number of corners (8) in the BoundingBox.|

#### Properties

|Member|Description|
|---|---|
|[Corners](VRageMath.BoundingBox.Corners)||
|[Center](VRageMath.BoundingBox.Center)|Calculates center|
|[HalfExtents](VRageMath.BoundingBox.HalfExtents)||
|[Extents](VRageMath.BoundingBox.Extents)||
|[Width](VRageMath.BoundingBox.Width)||
|[Height](VRageMath.BoundingBox.Height)||
|[Depth](VRageMath.BoundingBox.Depth)||
|[Size](VRageMath.BoundingBox.Size)|Size|
|[Matrix](VRageMath.BoundingBox.Matrix)|Matrix of AABB, respection center and size|
|[Perimeter](VRageMath.BoundingBox.Perimeter)|return perimeter of edges|

#### Methods

|Member|Description|
|---|---|
|[GetCorners()](VRageMath.BoundingBox.GetCorners)|Gets an array of points that make up the corners of the BoundingBox. ALLOCATION!|
|[GetCorners(Vector3[])](VRageMath.BoundingBox.GetCorners)|Gets the array of points that make up the corners of the BoundingBox.|
|[GetCornersUnsafe(*Vector3)](VRageMath.BoundingBox.GetCornersUnsafe)||
|[Equals(BoundingBox)](VRageMath.BoundingBox.Equals)|Determines whether two instances of BoundingBox are equal.|
|[Equals(object)](VRageMath.BoundingBox.Equals)|Determines whether two instances of BoundingBox are equal.|
|[GetHashCode()](VRageMath.BoundingBox.GetHashCode)|Gets the hash code for this instance.|
|[ToString()](VRageMath.BoundingBox.ToString)|Returns a String that represents the current BoundingBox.|
|[CreateMerged(BoundingBox, BoundingBox)](VRageMath.BoundingBox.CreateMerged)|Creates the smallest BoundingBox that contains the two specified BoundingBox instances.|
|[CreateMerged(ref BoundingBox, ref BoundingBox, ref BoundingBox)](VRageMath.BoundingBox.CreateMerged)|Creates the smallest BoundingBox that contains the two specified BoundingBox instances.|
|[CreateFromSphere(BoundingSphere)](VRageMath.BoundingBox.CreateFromSphere)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|[CreateFromSphere(ref BoundingSphere, ref BoundingBox)](VRageMath.BoundingBox.CreateFromSphere)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|[CreateFromPoints(IEnumerable)](VRageMath.BoundingBox.CreateFromPoints)||
|[CreateFromHalfExtent(Vector3, float)](VRageMath.BoundingBox.CreateFromHalfExtent)||
|[CreateFromHalfExtent(Vector3, Vector3)](VRageMath.BoundingBox.CreateFromHalfExtent)||
|[Intersect(BoundingBox)](VRageMath.BoundingBox.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[Intersects(BoundingBox)](VRageMath.BoundingBox.Intersects)|Checks whether the current BoundingBox intersects another BoundingBox.|
|[Intersects(ref BoundingBox)](VRageMath.BoundingBox.Intersects)||
|[Intersects(ref BoundingBox, ref bool)](VRageMath.BoundingBox.Intersects)|Checks whether the current BoundingBox intersects another BoundingBox.|
|[IntersectsTriangle(Vector3, Vector3, Vector3)](VRageMath.BoundingBox.IntersectsTriangle)||
|[IntersectsTriangle(ref Vector3, ref Vector3, ref Vector3)](VRageMath.BoundingBox.IntersectsTriangle)||
|[Intersects(BoundingFrustum)](VRageMath.BoundingBox.Intersects)|Checks whether the current BoundingBox intersects a BoundingFrustum.|
|[Intersects(Plane)](VRageMath.BoundingBox.Intersects)|Checks whether the current BoundingBox intersects a Plane.|
|[Intersects(ref Plane, ref PlaneIntersectionType)](VRageMath.BoundingBox.Intersects)|Checks whether the current BoundingBox intersects a Plane.|
|[Intersects(Line, ref float)](VRageMath.BoundingBox.Intersects)||
|[Intersects(Ray)](VRageMath.BoundingBox.Intersects)|Checks whether the current BoundingBox intersects a Ray.|
|[Intersects(ref Ray, ref Nullable)](VRageMath.BoundingBox.Intersects)||
|[Intersects(BoundingSphere)](VRageMath.BoundingBox.Intersects)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|[Intersects(ref BoundingSphere, ref bool)](VRageMath.BoundingBox.Intersects)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|[Intersects(ref BoundingSphere)](VRageMath.BoundingBox.Intersects)||
|[Intersects(ref BoundingSphereD)](VRageMath.BoundingBox.Intersects)||
|[Distance(Vector3)](VRageMath.BoundingBox.Distance)||
|[DistanceSquared(Vector3)](VRageMath.BoundingBox.DistanceSquared)||
|[Contains(BoundingBox)](VRageMath.BoundingBox.Contains)|Tests whether the BoundingBox contains another BoundingBox.|
|[Contains(ref BoundingBox, ref ContainmentType)](VRageMath.BoundingBox.Contains)|Tests whether the BoundingBox contains a BoundingBox.|
|[Contains(BoundingFrustum)](VRageMath.BoundingBox.Contains)|Tests whether the BoundingBox contains a BoundingFrustum.|
|[Contains(Vector3)](VRageMath.BoundingBox.Contains)|Tests whether the BoundingBox contains a point.|
|[Contains(Vector3D)](VRageMath.BoundingBox.Contains)||
|[Contains(ref Vector3, ref ContainmentType)](VRageMath.BoundingBox.Contains)|Tests whether the BoundingBox contains a point.|
|[Contains(BoundingSphere)](VRageMath.BoundingBox.Contains)|Tests whether the BoundingBox contains a BoundingSphere.|
|[Contains(ref BoundingSphere, ref ContainmentType)](VRageMath.BoundingBox.Contains)|Tests whether the BoundingBox contains a BoundingSphere.|
|[Translate(Matrix)](VRageMath.BoundingBox.Translate)|Translate|
|[Translate(Vector3)](VRageMath.BoundingBox.Translate)|Translate|
|[Transform(Matrix)](VRageMath.BoundingBox.Transform)||
|[Transform(MatrixD)](VRageMath.BoundingBox.Transform)||
|[Transform(ref Matrix)](VRageMath.BoundingBox.Transform)||
|[Transform(ref Matrix, ref BoundingBox)](VRageMath.BoundingBox.Transform)||
|[Transform(ref MatrixD)](VRageMath.BoundingBox.Transform)||
|[Transform(ref MatrixD, ref BoundingBoxD)](VRageMath.BoundingBox.Transform)||
|[Include(ref Vector3)](VRageMath.BoundingBox.Include)|return expanded aabb (aabb include point)|
|[GetIncluded(Vector3)](VRageMath.BoundingBox.GetIncluded)||
|[Include(Vector3)](VRageMath.BoundingBox.Include)||
|[Include(Vector3, Vector3, Vector3)](VRageMath.BoundingBox.Include)||
|[Include(ref Vector3, ref Vector3, ref Vector3)](VRageMath.BoundingBox.Include)||
|[Include(ref BoundingBox)](VRageMath.BoundingBox.Include)|return expanded aabb (aabb include aabb)|
|[Include(BoundingBox)](VRageMath.BoundingBox.Include)||
|[Include(ref Line)](VRageMath.BoundingBox.Include)||
|[Include(BoundingSphere)](VRageMath.BoundingBox.Include)||
|[Include(ref BoundingSphere)](VRageMath.BoundingBox.Include)||
|[Include(ref BoundingFrustum)](VRageMath.BoundingBox.Include)||
|[CreateInvalid()](VRageMath.BoundingBox.CreateInvalid)||
|[SurfaceArea()](VRageMath.BoundingBox.SurfaceArea)||
|[Volume()](VRageMath.BoundingBox.Volume)||
|[ProjectedArea(Vector3)](VRageMath.BoundingBox.ProjectedArea)||
|[Inflate(float)](VRageMath.BoundingBox.Inflate)||
|[Inflate(Vector3)](VRageMath.BoundingBox.Inflate)||
|[InflateToMinimum(Vector3)](VRageMath.BoundingBox.InflateToMinimum)||
|[Scale(Vector3)](VRageMath.BoundingBox.Scale)||

