← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### BoundingBox Struct

```csharp
public struct BoundingBox: IEquatable<BoundingBox>
```

Defines an axis-aligned box-shaped 3D volume.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable&lt;BoundingBox&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[static ComparerType Comparer](VRageMath.BoundingBox.Comparer)||
|[static int CornerCount](VRageMath.BoundingBox.CornerCount)|Specifies the total number of corners (8) in the BoundingBox.|
|[static BoundingBox Invalid](VRageMath.BoundingBox.Invalid)||
|[Vector3 Max](VRageMath.BoundingBox.Max)|The maximum point the BoundingBox contains.|
|[Vector3 Min](VRageMath.BoundingBox.Min)|The minimum point the BoundingBox contains.|

#### Properties

|Member|Description|
|---|---|
|[Vector3 Center { get; }](VRageMath.BoundingBox.Center)|Calculates center|
|[BoxCornerEnumerator Corners { get; set; }](VRageMath.BoundingBox.Corners)||
|[float Depth { get; }](VRageMath.BoundingBox.Depth)||
|[Vector3 Extents { get; }](VRageMath.BoundingBox.Extents)||
|[Vector3 HalfExtents { get; }](VRageMath.BoundingBox.HalfExtents)||
|[float Height { get; }](VRageMath.BoundingBox.Height)||
|[Matrix Matrix { get; }](VRageMath.BoundingBox.Matrix)|Matrix of AABB, respecting center and size|
|[float Perimeter { get; }](VRageMath.BoundingBox.Perimeter)|return perimeter of edges|
|[Vector3 Size { get; }](VRageMath.BoundingBox.Size)|Size|
|[float Width { get; }](VRageMath.BoundingBox.Width)||

#### Constructors

|Member|Description|
|---|---|
|[BoundingBox(Vector3, Vector3)](VRageMath.BoundingBox..ctor)||
|[BoundingBox(BoundingBoxD)](VRageMath.BoundingBox..ctor)||
|[BoundingBox(BoundingBoxI)](VRageMath.BoundingBox..ctor)||

#### Methods

|Member|Description|
|---|---|
|[static BoundingBox CreateFromHalfExtent(Vector3, float)](VRageMath.BoundingBox.CreateFromHalfExtent)||
|[static BoundingBox CreateFromHalfExtent(Vector3, Vector3)](VRageMath.BoundingBox.CreateFromHalfExtent)||
|[static BoundingBox CreateFromPoints(IEnumerable&lt;Vector3&gt;)](VRageMath.BoundingBox.CreateFromPoints)|Creates the smallest BoundingBox that will contain a group of points.|
|[static BoundingBox CreateFromSphere(BoundingSphere)](VRageMath.BoundingBox.CreateFromSphere)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|[static void CreateFromSphere(ref BoundingSphere, out BoundingBox)](VRageMath.BoundingBox.CreateFromSphere)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|[static BoundingBox CreateInvalid()](VRageMath.BoundingBox.CreateInvalid)||
|[static BoundingBox CreateMerged(BoundingBox, BoundingBox)](VRageMath.BoundingBox.CreateMerged)|Creates the smallest BoundingBox that contains the two specified BoundingBox instances.|
|[static void CreateMerged(ref BoundingBox, ref BoundingBox, out BoundingBox)](VRageMath.BoundingBox.CreateMerged)|Creates the smallest BoundingBox that contains the two specified BoundingBox instances.|
|[ContainmentType Contains(BoundingBox)](VRageMath.BoundingBox.Contains)|Tests whether the BoundingBox contains another BoundingBox.|
|[void Contains(ref BoundingBox, out ContainmentType)](VRageMath.BoundingBox.Contains)|Tests whether the BoundingBox contains a BoundingBox.|
|[ContainmentType Contains(BoundingFrustum)](VRageMath.BoundingBox.Contains)|Tests whether the BoundingBox contains a BoundingFrustum.|
|[ContainmentType Contains(Vector3)](VRageMath.BoundingBox.Contains)|Tests whether the BoundingBox contains a point.|
|[ContainmentType Contains(Vector3D)](VRageMath.BoundingBox.Contains)||
|[void Contains(ref Vector3, out ContainmentType)](VRageMath.BoundingBox.Contains)|Tests whether the BoundingBox contains a point.|
|[ContainmentType Contains(BoundingSphere)](VRageMath.BoundingBox.Contains)|Tests whether the BoundingBox contains a BoundingSphere.|
|[void Contains(ref BoundingSphere, out ContainmentType)](VRageMath.BoundingBox.Contains)|Tests whether the BoundingBox contains a BoundingSphere.|
|[float Distance(Vector3)](VRageMath.BoundingBox.Distance)||
|[float DistanceSquared(Vector3)](VRageMath.BoundingBox.DistanceSquared)||
|[bool Equals(BoundingBox)](VRageMath.BoundingBox.Equals)|Determines whether two instances of BoundingBox are equal.|
|[bool Equals(object)](VRageMath.BoundingBox.Equals)|Determines whether two instances of BoundingBox are equal.|
|[bool Equals(BoundingBox, float)](VRageMath.BoundingBox.Equals)||
|[Vector3&#91&#93; GetCorners()](VRageMath.BoundingBox.GetCorners)|Gets an array of points that make up the corners of the BoundingBox. ALLOCATION!|
|[void GetCorners(Vector3&#91&#93;)](VRageMath.BoundingBox.GetCorners)|Gets the array of points that make up the corners of the BoundingBox.|
|[void GetCornersUnsafe(*Vector3)](VRageMath.BoundingBox.GetCornersUnsafe)||
|[int GetHashCode()](VRageMath.BoundingBox.GetHashCode)|Gets the hash code for this instance.|
|[BoundingBox GetIncluded(Vector3)](VRageMath.BoundingBox.GetIncluded)||
|[BoundingBox Include(ref Vector3)](VRageMath.BoundingBox.Include)|return expanded aabb (aabb include point)|
|[BoundingBox Include(Vector3)](VRageMath.BoundingBox.Include)||
|[BoundingBox Include(Vector3, Vector3, Vector3)](VRageMath.BoundingBox.Include)||
|[BoundingBox Include(ref Vector3, ref Vector3, ref Vector3)](VRageMath.BoundingBox.Include)||
|[BoundingBox Include(ref BoundingBox)](VRageMath.BoundingBox.Include)|return expanded aabb (aabb include aabb)|
|[BoundingBox Include(BoundingBox)](VRageMath.BoundingBox.Include)||
|[void Include(ref Line)](VRageMath.BoundingBox.Include)||
|[BoundingBox Include(BoundingSphere)](VRageMath.BoundingBox.Include)||
|[BoundingBox Include(ref BoundingSphere)](VRageMath.BoundingBox.Include)||
|[BoundingBox Include(ref BoundingFrustum)](VRageMath.BoundingBox.Include)||
|[void Inflate(float)](VRageMath.BoundingBox.Inflate)||
|[void Inflate(Vector3)](VRageMath.BoundingBox.Inflate)||
|[void InflateToMinimum(Vector3)](VRageMath.BoundingBox.InflateToMinimum)||
|[BoundingBox Intersect(BoundingBox)](VRageMath.BoundingBox.Intersect)|Returns bounding box which is intersection of this and box Result is invalid box when there's no intersection (Min > Max)|
|[bool Intersects(BoundingBox)](VRageMath.BoundingBox.Intersects)|Checks whether the current BoundingBox intersects another BoundingBox.|
|[bool Intersects(ref BoundingBox)](VRageMath.BoundingBox.Intersects)||
|[void Intersects(ref BoundingBox, out bool)](VRageMath.BoundingBox.Intersects)|Checks whether the current BoundingBox intersects another BoundingBox.|
|[bool Intersects(BoundingFrustum)](VRageMath.BoundingBox.Intersects)|Checks whether the current BoundingBox intersects a BoundingFrustum.|
|[PlaneIntersectionType Intersects(Plane)](VRageMath.BoundingBox.Intersects)|Checks whether the current BoundingBox intersects a Plane.|
|[void Intersects(ref Plane, out PlaneIntersectionType)](VRageMath.BoundingBox.Intersects)|Checks whether the current BoundingBox intersects a Plane.|
|[bool Intersects(Line, out float)](VRageMath.BoundingBox.Intersects)||
|[float? Intersects(Ray)](VRageMath.BoundingBox.Intersects)|Checks whether the current BoundingBox intersects a Ray.|
|[void Intersects(ref Ray, out float?)](VRageMath.BoundingBox.Intersects)|Checks whether the current BoundingBox intersects a Ray.|
|[bool Intersects(BoundingSphere)](VRageMath.BoundingBox.Intersects)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|[void Intersects(ref BoundingSphere, out bool)](VRageMath.BoundingBox.Intersects)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|[bool Intersects(ref BoundingSphere)](VRageMath.BoundingBox.Intersects)||
|[bool Intersects(ref BoundingSphereD)](VRageMath.BoundingBox.Intersects)||
|[bool IntersectsTriangle(Vector3, Vector3, Vector3)](VRageMath.BoundingBox.IntersectsTriangle)||
|[bool IntersectsTriangle(ref Vector3, ref Vector3, ref Vector3)](VRageMath.BoundingBox.IntersectsTriangle)||
|[float ProjectedArea(Vector3)](VRageMath.BoundingBox.ProjectedArea)||
|[BoundingBox Round(int)](VRageMath.BoundingBox.Round)||
|[BoundingBoxI Round()](VRageMath.BoundingBox.Round)||
|[void Scale(Vector3)](VRageMath.BoundingBox.Scale)||
|[float SurfaceArea()](VRageMath.BoundingBox.SurfaceArea)||
|[string ToString()](VRageMath.BoundingBox.ToString)|Returns a String that represents the current BoundingBox.|
|[BoundingBox Transform(Matrix)](VRageMath.BoundingBox.Transform)||
|[BoundingBoxD Transform(MatrixD)](VRageMath.BoundingBox.Transform)||
|[BoundingBox Transform(ref Matrix)](VRageMath.BoundingBox.Transform)||
|[void Transform(ref Matrix, ref BoundingBox)](VRageMath.BoundingBox.Transform)||
|[BoundingBoxD Transform(ref MatrixD)](VRageMath.BoundingBox.Transform)||
|[void Transform(ref MatrixD, ref BoundingBoxD)](VRageMath.BoundingBox.Transform)||
|[BoundingBox Translate(Matrix)](VRageMath.BoundingBox.Translate)|Translate|
|[BoundingBox Translate(Vector3)](VRageMath.BoundingBox.Translate)|Translate|
|[float Volume()](VRageMath.BoundingBox.Volume)||

