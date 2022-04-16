← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### BoundingBoxI Struct

```csharp
public struct BoundingBoxI: IEquatable<BoundingBoxI\>
```

Defines an axis-aligned box-shaped 3D volume.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<BoundingBoxI\>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\$1Vector3I Max](VRageMath.BoundingBoxI.Max)|The maximum point the BoundingBoxI contains.|
|\$1Vector3I Min](VRageMath.BoundingBoxI.Min)|The minimum point the BoundingBoxI contains.|

#### Properties

|Member|Description|
|---|---|
|\$1Vector3I Center { get; }](VRageMath.BoundingBoxI.Center)|Calculates center|
|\$1Vector3I HalfExtents { get; }](VRageMath.BoundingBoxI.HalfExtents)||
|\$1bool IsValid { get; }](VRageMath.BoundingBoxI.IsValid)||
|\$1float Perimeter { get; }](VRageMath.BoundingBoxI.Perimeter)|return perimeter of edges|
|\$1Vector3I Size { get; }](VRageMath.BoundingBoxI.Size)|Size|

#### Constructors

|Member|Description|
|---|---|
|\$1BoundingBoxI(BoundingBox)](VRageMath.BoundingBoxI..ctor)||
|\$1BoundingBoxI(Vector3I, Vector3I)](VRageMath.BoundingBoxI..ctor)||
|\$1BoundingBoxI(int, int)](VRageMath.BoundingBoxI..ctor)||

#### Methods

|Member|Description|
|---|---|
|\$1static BoundingBoxI CreateFromPoints(IEnumerable\$1Vector3I\>)](VRageMath.BoundingBoxI.CreateFromPoints)|Creates the smallest BoundingBoxI that will contain a group of points.|
|\$1static BoundingBoxI CreateFromSphere(BoundingSphere)](VRageMath.BoundingBoxI.CreateFromSphere)|Creates the smallest BoundingBoxI that will contain the specified BoundingSphere.|
|\$1static void CreateFromSphere(ref BoundingSphere, out BoundingBoxI)](VRageMath.BoundingBoxI.CreateFromSphere)|Creates the smallest BoundingBoxI that will contain the specified BoundingSphere.|
|\$1static BoundingBoxI CreateInvalid()](VRageMath.BoundingBoxI.CreateInvalid)||
|\$1static BoundingBoxI CreateMerged(BoundingBoxI, BoundingBoxI)](VRageMath.BoundingBoxI.CreateMerged)|Creates the smallest BoundingBoxI that contains the two specified BoundingBoxI instances.|
|\$1static void CreateMerged(ref BoundingBoxI, ref BoundingBoxI, out BoundingBoxI)](VRageMath.BoundingBoxI.CreateMerged)|Creates the smallest BoundingBoxI that contains the two specified BoundingBoxI instances.|
|\$1static IEnumerable\$1Vector3I\> EnumeratePoints(BoundingBoxI)](VRageMath.BoundingBoxI.EnumeratePoints)|Enumerate all values in a integer interval (a cuboid). This method is an allocating version of the Vector3I_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.|
|\$1static IEnumerable\$1Vector3I\> IterateDifference(BoundingBoxI, BoundingBoxI)](VRageMath.BoundingBoxI.IterateDifference)|Iterate every cell contained in {left} - {right}, where we interpret {box} as the set of all distinct Vector3I points inside a 'box'. Containment is taken in a typical inclusive start, exclusive end fashion.|
|\$1ContainmentType Contains(BoundingBoxI)](VRageMath.BoundingBoxI.Contains)|Tests whether the BoundingBoxI contains another BoundingBoxI.|
|\$1void Contains(ref BoundingBoxI, out ContainmentType)](VRageMath.BoundingBoxI.Contains)|Tests whether the BoundingBoxI contains a BoundingBoxI.|
|\$1ContainmentType Contains(Vector3I)](VRageMath.BoundingBoxI.Contains)|Tests whether the BoundingBoxI contains a point.|
|\$1ContainmentType Contains(Vector3)](VRageMath.BoundingBoxI.Contains)||
|\$1void Contains(ref Vector3I, out ContainmentType)](VRageMath.BoundingBoxI.Contains)|Tests whether the BoundingBoxI contains a point.|
|\$1float Distance(Vector3I)](VRageMath.BoundingBoxI.Distance)||
|\$1bool Equals(BoundingBoxI)](VRageMath.BoundingBoxI.Equals)|Determines whether two instances of BoundingBoxI are equal.|
|\$1bool Equals(object)](VRageMath.BoundingBoxI.Equals)|Determines whether two instances of BoundingBoxI are equal.|
|\$1Vector3I\$1] GetCorners()](VRageMath.BoundingBoxI.GetCorners)|Gets an array of points that make up the corners of the BoundingBoxI.|
|\$1void GetCorners(Vector3I\$1])](VRageMath.BoundingBoxI.GetCorners)|Gets the array of points that make up the corners of the BoundingBoxI.|
|\$1void GetCornersUnsafe(*Vector3I)](VRageMath.BoundingBoxI.GetCornersUnsafe)||
|\$1int GetHashCode()](VRageMath.BoundingBoxI.GetHashCode)|Gets the hash code for this instance.|
|\$1BoundingBoxI GetIncluded(Vector3I)](VRageMath.BoundingBoxI.GetIncluded)||
|\$1BoundingBoxI Include(ref Vector3I)](VRageMath.BoundingBoxI.Include)|return expanded aabb (abb include point)|
|\$1BoundingBoxI Include(Vector3I)](VRageMath.BoundingBoxI.Include)||
|\$1BoundingBoxI Include(Vector3I, Vector3I, Vector3I)](VRageMath.BoundingBoxI.Include)||
|\$1BoundingBoxI Include(ref Vector3I, ref Vector3I, ref Vector3I)](VRageMath.BoundingBoxI.Include)||
|\$1BoundingBoxI Include(ref BoundingBoxI)](VRageMath.BoundingBoxI.Include)|return expanded aabb (abb include point)|
|\$1BoundingBoxI Include(BoundingBoxI)](VRageMath.BoundingBoxI.Include)||
|\$1void Inflate(int)](VRageMath.BoundingBoxI.Inflate)||
|\$1void InflateToMinimum(Vector3I)](VRageMath.BoundingBoxI.InflateToMinimum)||
|\$1BoundingBoxI Intersect(BoundingBoxI)](VRageMath.BoundingBoxI.Intersect)|Returns bounding box which is intersection of this and box Result is invalid box when there's no intersection (Min > Max)|
|\$1bool Intersects(BoundingBoxI)](VRageMath.BoundingBoxI.Intersects)|Checks whether the current BoundingBoxI intersects another BoundingBoxI.|
|\$1bool Intersects(ref BoundingBoxI)](VRageMath.BoundingBoxI.Intersects)||
|\$1void Intersects(ref BoundingBoxI, out bool)](VRageMath.BoundingBoxI.Intersects)|Checks whether the current BoundingBoxI intersects another BoundingBoxI.|
|\$1PlaneIntersectionType Intersects(Plane)](VRageMath.BoundingBoxI.Intersects)|Checks whether the current BoundingBoxI intersects a Plane.|
|\$1void Intersects(ref Plane, out PlaneIntersectionType)](VRageMath.BoundingBoxI.Intersects)|Checks whether the current BoundingBoxI intersects a Plane.|
|\$1bool Intersects(Line, out float)](VRageMath.BoundingBoxI.Intersects)||
|\$1float? Intersects(Ray)](VRageMath.BoundingBoxI.Intersects)|Checks whether the current BoundingBoxI intersects a Ray.|
|\$1void Intersects(ref Ray, out float?)](VRageMath.BoundingBoxI.Intersects)|Checks whether the current BoundingBoxI intersects a Ray.|
|\$1bool IntersectsTriangle(Vector3I, Vector3I, Vector3I)](VRageMath.BoundingBoxI.IntersectsTriangle)||
|\$1bool IntersectsTriangle(ref Vector3I, ref Vector3I, ref Vector3I)](VRageMath.BoundingBoxI.IntersectsTriangle)||
|\$1void IntersectWith(ref BoundingBoxI)](VRageMath.BoundingBoxI.IntersectWith)|Returns bounding box which is intersection of this and box Result is invalid box when there's no intersection (Min > Max)|
|\$1float SurfaceArea()](VRageMath.BoundingBoxI.SurfaceArea)||
|\$1string ToString()](VRageMath.BoundingBoxI.ToString)|Returns a String that represents the current BoundingBoxI.|
|\$1BoundingBoxI Translate(Vector3I)](VRageMath.BoundingBoxI.Translate)|Translate|
|\$1float Volume()](VRageMath.BoundingBoxI.Volume)||

