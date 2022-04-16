← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### BoundingBox Struct

```csharp
public struct BoundingBox: IEquatable<BoundingBox\>
```

Defines an axis-aligned box-shaped 3D volume.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<BoundingBox\>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\$1static ComparerType Comparer](VRageMath.BoundingBox.Comparer)||
|\$1static int CornerCount](VRageMath.BoundingBox.CornerCount)|Specifies the total number of corners (8) in the BoundingBox.|
|\$1static BoundingBox Invalid](VRageMath.BoundingBox.Invalid)||
|\$1Vector3 Max](VRageMath.BoundingBox.Max)|The maximum point the BoundingBox contains.|
|\$1Vector3 Min](VRageMath.BoundingBox.Min)|The minimum point the BoundingBox contains.|

#### Properties

|Member|Description|
|---|---|
|\$1Vector3 Center { get; }](VRageMath.BoundingBox.Center)|Calculates center|
|\$1BoxCornerEnumerator Corners { get; set; }](VRageMath.BoundingBox.Corners)||
|\$1float Depth { get; }](VRageMath.BoundingBox.Depth)||
|\$1Vector3 Extents { get; }](VRageMath.BoundingBox.Extents)||
|\$1Vector3 HalfExtents { get; }](VRageMath.BoundingBox.HalfExtents)||
|\$1float Height { get; }](VRageMath.BoundingBox.Height)||
|\$1Matrix Matrix { get; }](VRageMath.BoundingBox.Matrix)|Matrix of AABB, respecting center and size|
|\$1float Perimeter { get; }](VRageMath.BoundingBox.Perimeter)|return perimeter of edges|
|\$1Vector3 Size { get; }](VRageMath.BoundingBox.Size)|Size|
|\$1float Width { get; }](VRageMath.BoundingBox.Width)||

#### Constructors

|Member|Description|
|---|---|
|\$1BoundingBox(Vector3, Vector3)](VRageMath.BoundingBox..ctor)||
|\$1BoundingBox(BoundingBoxD)](VRageMath.BoundingBox..ctor)||
|\$1BoundingBox(BoundingBoxI)](VRageMath.BoundingBox..ctor)||

#### Methods

|Member|Description|
|---|---|
|\$1static BoundingBox CreateFromHalfExtent(Vector3, float)](VRageMath.BoundingBox.CreateFromHalfExtent)||
|\$1static BoundingBox CreateFromHalfExtent(Vector3, Vector3)](VRageMath.BoundingBox.CreateFromHalfExtent)||
|\$1static BoundingBox CreateFromPoints(IEnumerable\$1Vector3\>)](VRageMath.BoundingBox.CreateFromPoints)|Creates the smallest BoundingBox that will contain a group of points.|
|\$1static BoundingBox CreateFromSphere(BoundingSphere)](VRageMath.BoundingBox.CreateFromSphere)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|\$1static void CreateFromSphere(ref BoundingSphere, out BoundingBox)](VRageMath.BoundingBox.CreateFromSphere)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|\$1static BoundingBox CreateInvalid()](VRageMath.BoundingBox.CreateInvalid)||
|\$1static BoundingBox CreateMerged(BoundingBox, BoundingBox)](VRageMath.BoundingBox.CreateMerged)|Creates the smallest BoundingBox that contains the two specified BoundingBox instances.|
|\$1static void CreateMerged(ref BoundingBox, ref BoundingBox, out BoundingBox)](VRageMath.BoundingBox.CreateMerged)|Creates the smallest BoundingBox that contains the two specified BoundingBox instances.|
|\$1ContainmentType Contains(BoundingBox)](VRageMath.BoundingBox.Contains)|Tests whether the BoundingBox contains another BoundingBox.|
|\$1void Contains(ref BoundingBox, out ContainmentType)](VRageMath.BoundingBox.Contains)|Tests whether the BoundingBox contains a BoundingBox.|
|\$1ContainmentType Contains(BoundingFrustum)](VRageMath.BoundingBox.Contains)|Tests whether the BoundingBox contains a BoundingFrustum.|
|\$1ContainmentType Contains(Vector3)](VRageMath.BoundingBox.Contains)|Tests whether the BoundingBox contains a point.|
|\$1ContainmentType Contains(Vector3D)](VRageMath.BoundingBox.Contains)||
|\$1void Contains(ref Vector3, out ContainmentType)](VRageMath.BoundingBox.Contains)|Tests whether the BoundingBox contains a point.|
|\$1ContainmentType Contains(BoundingSphere)](VRageMath.BoundingBox.Contains)|Tests whether the BoundingBox contains a BoundingSphere.|
|\$1void Contains(ref BoundingSphere, out ContainmentType)](VRageMath.BoundingBox.Contains)|Tests whether the BoundingBox contains a BoundingSphere.|
|\$1float Distance(Vector3)](VRageMath.BoundingBox.Distance)||
|\$1float DistanceSquared(Vector3)](VRageMath.BoundingBox.DistanceSquared)||
|\$1bool Equals(BoundingBox)](VRageMath.BoundingBox.Equals)|Determines whether two instances of BoundingBox are equal.|
|\$1bool Equals(object)](VRageMath.BoundingBox.Equals)|Determines whether two instances of BoundingBox are equal.|
|\$1bool Equals(BoundingBox, float)](VRageMath.BoundingBox.Equals)||
|\$1Vector3\$1] GetCorners()](VRageMath.BoundingBox.GetCorners)|Gets an array of points that make up the corners of the BoundingBox. ALLOCATION!|
|\$1void GetCorners(Vector3\$1])](VRageMath.BoundingBox.GetCorners)|Gets the array of points that make up the corners of the BoundingBox.|
|\$1void GetCornersUnsafe(*Vector3)](VRageMath.BoundingBox.GetCornersUnsafe)||
|\$1int GetHashCode()](VRageMath.BoundingBox.GetHashCode)|Gets the hash code for this instance.|
|\$1BoundingBox GetIncluded(Vector3)](VRageMath.BoundingBox.GetIncluded)||
|\$1BoundingBox Include(ref Vector3)](VRageMath.BoundingBox.Include)|return expanded aabb (aabb include point)|
|\$1BoundingBox Include(Vector3)](VRageMath.BoundingBox.Include)||
|\$1BoundingBox Include(Vector3, Vector3, Vector3)](VRageMath.BoundingBox.Include)||
|\$1BoundingBox Include(ref Vector3, ref Vector3, ref Vector3)](VRageMath.BoundingBox.Include)||
|\$1BoundingBox Include(ref BoundingBox)](VRageMath.BoundingBox.Include)|return expanded aabb (aabb include aabb)|
|\$1BoundingBox Include(BoundingBox)](VRageMath.BoundingBox.Include)||
|\$1void Include(ref Line)](VRageMath.BoundingBox.Include)||
|\$1BoundingBox Include(BoundingSphere)](VRageMath.BoundingBox.Include)||
|\$1BoundingBox Include(ref BoundingSphere)](VRageMath.BoundingBox.Include)||
|\$1BoundingBox Include(ref BoundingFrustum)](VRageMath.BoundingBox.Include)||
|\$1void Inflate(float)](VRageMath.BoundingBox.Inflate)||
|\$1void Inflate(Vector3)](VRageMath.BoundingBox.Inflate)||
|\$1void InflateToMinimum(Vector3)](VRageMath.BoundingBox.InflateToMinimum)||
|\$1BoundingBox Intersect(BoundingBox)](VRageMath.BoundingBox.Intersect)|Returns bounding box which is intersection of this and box Result is invalid box when there's no intersection (Min > Max)|
|\$1bool Intersects(BoundingBox)](VRageMath.BoundingBox.Intersects)|Checks whether the current BoundingBox intersects another BoundingBox.|
|\$1bool Intersects(ref BoundingBox)](VRageMath.BoundingBox.Intersects)||
|\$1void Intersects(ref BoundingBox, out bool)](VRageMath.BoundingBox.Intersects)|Checks whether the current BoundingBox intersects another BoundingBox.|
|\$1bool Intersects(BoundingFrustum)](VRageMath.BoundingBox.Intersects)|Checks whether the current BoundingBox intersects a BoundingFrustum.|
|\$1PlaneIntersectionType Intersects(Plane)](VRageMath.BoundingBox.Intersects)|Checks whether the current BoundingBox intersects a Plane.|
|\$1void Intersects(ref Plane, out PlaneIntersectionType)](VRageMath.BoundingBox.Intersects)|Checks whether the current BoundingBox intersects a Plane.|
|\$1bool Intersects(Line, out float)](VRageMath.BoundingBox.Intersects)||
|\$1float? Intersects(Ray)](VRageMath.BoundingBox.Intersects)|Checks whether the current BoundingBox intersects a Ray.|
|\$1void Intersects(ref Ray, out float?)](VRageMath.BoundingBox.Intersects)|Checks whether the current BoundingBox intersects a Ray.|
|\$1bool Intersects(BoundingSphere)](VRageMath.BoundingBox.Intersects)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|\$1void Intersects(ref BoundingSphere, out bool)](VRageMath.BoundingBox.Intersects)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|\$1bool Intersects(ref BoundingSphere)](VRageMath.BoundingBox.Intersects)||
|\$1bool Intersects(ref BoundingSphereD)](VRageMath.BoundingBox.Intersects)||
|\$1bool IntersectsTriangle(Vector3, Vector3, Vector3)](VRageMath.BoundingBox.IntersectsTriangle)||
|\$1bool IntersectsTriangle(ref Vector3, ref Vector3, ref Vector3)](VRageMath.BoundingBox.IntersectsTriangle)||
|\$1float ProjectedArea(Vector3)](VRageMath.BoundingBox.ProjectedArea)||
|\$1BoundingBox Round(int)](VRageMath.BoundingBox.Round)||
|\$1BoundingBoxI Round()](VRageMath.BoundingBox.Round)||
|\$1void Scale(Vector3)](VRageMath.BoundingBox.Scale)||
|\$1float SurfaceArea()](VRageMath.BoundingBox.SurfaceArea)||
|\$1string ToString()](VRageMath.BoundingBox.ToString)|Returns a String that represents the current BoundingBox.|
|\$1BoundingBox Transform(Matrix)](VRageMath.BoundingBox.Transform)||
|\$1BoundingBoxD Transform(MatrixD)](VRageMath.BoundingBox.Transform)||
|\$1BoundingBox Transform(ref Matrix)](VRageMath.BoundingBox.Transform)||
|\$1void Transform(ref Matrix, ref BoundingBox)](VRageMath.BoundingBox.Transform)||
|\$1BoundingBoxD Transform(ref MatrixD)](VRageMath.BoundingBox.Transform)||
|\$1void Transform(ref MatrixD, ref BoundingBoxD)](VRageMath.BoundingBox.Transform)||
|\$1BoundingBox Translate(Matrix)](VRageMath.BoundingBox.Translate)|Translate|
|\$1BoundingBox Translate(Vector3)](VRageMath.BoundingBox.Translate)|Translate|
|\$1float Volume()](VRageMath.BoundingBox.Volume)||

