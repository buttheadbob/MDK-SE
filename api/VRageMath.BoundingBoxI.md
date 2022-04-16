← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### BoundingBoxI Struct

```csharp
public struct BoundingBoxI: IEquatable<BoundingBoxI>
```

Defines an axis-aligned box-shaped 3D volume.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable\<BoundingBoxI>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[Vector3I Max](VRageMath.BoundingBoxI.Max)|The maximum point the BoundingBoxI contains.|
|[Vector3I Min](VRageMath.BoundingBoxI.Min)|The minimum point the BoundingBoxI contains.|

#### Properties

|Member|Description|
|---|---|
|[Vector3I Center { get; }](VRageMath.BoundingBoxI.Center)|Calculates center|
|[Vector3I HalfExtents { get; }](VRageMath.BoundingBoxI.HalfExtents)||
|[bool IsValid { get; }](VRageMath.BoundingBoxI.IsValid)||
|[float Perimeter { get; }](VRageMath.BoundingBoxI.Perimeter)|return perimeter of edges|
|[Vector3I Size { get; }](VRageMath.BoundingBoxI.Size)|Size|

#### Constructors

|Member|Description|
|---|---|
|[BoundingBoxI(BoundingBox)](VRageMath.BoundingBoxI..ctor)||
|[BoundingBoxI(Vector3I, Vector3I)](VRageMath.BoundingBoxI..ctor)||
|[BoundingBoxI(int, int)](VRageMath.BoundingBoxI..ctor)||

#### Methods

|Member|Description|
|---|---|
|[static BoundingBoxI CreateFromPoints(IEnumerable\<Vector3I>)](VRageMath.BoundingBoxI.CreateFromPoints)|Creates the smallest BoundingBoxI that will contain a group of points.|
|[static BoundingBoxI CreateFromSphere(BoundingSphere)](VRageMath.BoundingBoxI.CreateFromSphere)|Creates the smallest BoundingBoxI that will contain the specified BoundingSphere.|
|[static void CreateFromSphere(ref BoundingSphere, out BoundingBoxI)](VRageMath.BoundingBoxI.CreateFromSphere)|Creates the smallest BoundingBoxI that will contain the specified BoundingSphere.|
|[static BoundingBoxI CreateInvalid()](VRageMath.BoundingBoxI.CreateInvalid)||
|[static BoundingBoxI CreateMerged(BoundingBoxI, BoundingBoxI)](VRageMath.BoundingBoxI.CreateMerged)|Creates the smallest BoundingBoxI that contains the two specified BoundingBoxI instances.|
|[static void CreateMerged(ref BoundingBoxI, ref BoundingBoxI, out BoundingBoxI)](VRageMath.BoundingBoxI.CreateMerged)|Creates the smallest BoundingBoxI that contains the two specified BoundingBoxI instances.|
|[static IEnumerable\<Vector3I> EnumeratePoints(BoundingBoxI)](VRageMath.BoundingBoxI.EnumeratePoints)|Enumerate all values in a integer interval (a cuboid). This method is an allocating version of the Vector3I_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.|
|[static IEnumerable\<Vector3I> IterateDifference(BoundingBoxI, BoundingBoxI)](VRageMath.BoundingBoxI.IterateDifference)|Iterate every cell contained in {left} - {right}, where we interpret {box} as the set of all distinct Vector3I points inside a 'box'. Containment is taken in a typical inclusive start, exclusive end fashion.|
|[ContainmentType Contains(BoundingBoxI)](VRageMath.BoundingBoxI.Contains)|Tests whether the BoundingBoxI contains another BoundingBoxI.|
|[void Contains(ref BoundingBoxI, out ContainmentType)](VRageMath.BoundingBoxI.Contains)|Tests whether the BoundingBoxI contains a BoundingBoxI.|
|[ContainmentType Contains(Vector3I)](VRageMath.BoundingBoxI.Contains)|Tests whether the BoundingBoxI contains a point.|
|[ContainmentType Contains(Vector3)](VRageMath.BoundingBoxI.Contains)||
|[void Contains(ref Vector3I, out ContainmentType)](VRageMath.BoundingBoxI.Contains)|Tests whether the BoundingBoxI contains a point.|
|[float Distance(Vector3I)](VRageMath.BoundingBoxI.Distance)||
|[bool Equals(BoundingBoxI)](VRageMath.BoundingBoxI.Equals)|Determines whether two instances of BoundingBoxI are equal.|
|[bool Equals(object)](VRageMath.BoundingBoxI.Equals)|Determines whether two instances of BoundingBoxI are equal.|
|[Vector3I\[\] GetCorners()](VRageMath.BoundingBoxI.GetCorners)|Gets an array of points that make up the corners of the BoundingBoxI.|
|[void GetCorners(Vector3I\[\])](VRageMath.BoundingBoxI.GetCorners)|Gets the array of points that make up the corners of the BoundingBoxI.|
|[void GetCornersUnsafe(*Vector3I)](VRageMath.BoundingBoxI.GetCornersUnsafe)||
|[int GetHashCode()](VRageMath.BoundingBoxI.GetHashCode)|Gets the hash code for this instance.|
|[BoundingBoxI GetIncluded(Vector3I)](VRageMath.BoundingBoxI.GetIncluded)||
|[BoundingBoxI Include(ref Vector3I)](VRageMath.BoundingBoxI.Include)|return expanded aabb (abb include point)|
|[BoundingBoxI Include(Vector3I)](VRageMath.BoundingBoxI.Include)||
|[BoundingBoxI Include(Vector3I, Vector3I, Vector3I)](VRageMath.BoundingBoxI.Include)||
|[BoundingBoxI Include(ref Vector3I, ref Vector3I, ref Vector3I)](VRageMath.BoundingBoxI.Include)||
|[BoundingBoxI Include(ref BoundingBoxI)](VRageMath.BoundingBoxI.Include)|return expanded aabb (abb include point)|
|[BoundingBoxI Include(BoundingBoxI)](VRageMath.BoundingBoxI.Include)||
|[void Inflate(int)](VRageMath.BoundingBoxI.Inflate)||
|[void InflateToMinimum(Vector3I)](VRageMath.BoundingBoxI.InflateToMinimum)||
|[BoundingBoxI Intersect(BoundingBoxI)](VRageMath.BoundingBoxI.Intersect)|Returns bounding box which is intersection of this and box Result is invalid box when there's no intersection (Min > Max)|
|[bool Intersects(BoundingBoxI)](VRageMath.BoundingBoxI.Intersects)|Checks whether the current BoundingBoxI intersects another BoundingBoxI.|
|[bool Intersects(ref BoundingBoxI)](VRageMath.BoundingBoxI.Intersects)||
|[void Intersects(ref BoundingBoxI, out bool)](VRageMath.BoundingBoxI.Intersects)|Checks whether the current BoundingBoxI intersects another BoundingBoxI.|
|[PlaneIntersectionType Intersects(Plane)](VRageMath.BoundingBoxI.Intersects)|Checks whether the current BoundingBoxI intersects a Plane.|
|[void Intersects(ref Plane, out PlaneIntersectionType)](VRageMath.BoundingBoxI.Intersects)|Checks whether the current BoundingBoxI intersects a Plane.|
|[bool Intersects(Line, out float)](VRageMath.BoundingBoxI.Intersects)||
|[float? Intersects(Ray)](VRageMath.BoundingBoxI.Intersects)|Checks whether the current BoundingBoxI intersects a Ray.|
|[void Intersects(ref Ray, out float?)](VRageMath.BoundingBoxI.Intersects)|Checks whether the current BoundingBoxI intersects a Ray.|
|[bool IntersectsTriangle(Vector3I, Vector3I, Vector3I)](VRageMath.BoundingBoxI.IntersectsTriangle)||
|[bool IntersectsTriangle(ref Vector3I, ref Vector3I, ref Vector3I)](VRageMath.BoundingBoxI.IntersectsTriangle)||
|[void IntersectWith(ref BoundingBoxI)](VRageMath.BoundingBoxI.IntersectWith)|Returns bounding box which is intersection of this and box Result is invalid box when there's no intersection (Min > Max)|
|[float SurfaceArea()](VRageMath.BoundingBoxI.SurfaceArea)||
|[string ToString()](VRageMath.BoundingBoxI.ToString)|Returns a String that represents the current BoundingBoxI.|
|[BoundingBoxI Translate(Vector3I)](VRageMath.BoundingBoxI.Translate)|Translate|
|[float Volume()](VRageMath.BoundingBoxI.Volume)||

