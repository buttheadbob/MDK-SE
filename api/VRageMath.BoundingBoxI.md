← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### BoundingBoxI Struct

```csharp
public struct BoundingBoxI: IEquatable<T>
```

Defines an axis-aligned box-shaped 3D volume.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<T>](https://docs.microsoft.com/en-us/dotnet/api/system.iequatable?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[Min](VRageMath.BoundingBoxI.Min)|The minimum point the BoundingBoxI contains.|
|[Max](VRageMath.BoundingBoxI.Max)|The maximum point the BoundingBoxI contains.|
|[CornerCount](VRageMath.BoundingBoxI.CornerCount)|Specifies the total number of corners (8) in the BoundingBoxI.|

#### Properties

|Member|Description|
|---|---|
|[Center](VRageMath.BoundingBoxI.Center)|Calculates center|
|[HalfExtents](VRageMath.BoundingBoxI.HalfExtents)||
|[Size](VRageMath.BoundingBoxI.Size)|Size|
|[Perimeter](VRageMath.BoundingBoxI.Perimeter)|return perimeter of edges|
|[IsValid](VRageMath.BoundingBoxI.IsValid)||

#### Methods

|Member|Description|
|---|---|
|[GetCorners()](VRageMath.BoundingBoxI.GetCorners)|Gets an array of points that make up the corners of the BoundingBoxI.|
|[GetCorners(Vector3I[])](VRageMath.BoundingBoxI.GetCorners)|Gets the array of points that make up the corners of the BoundingBoxI.|
|[GetCornersUnsafe(*Vector3I)](VRageMath.BoundingBoxI.GetCornersUnsafe)||
|[Equals(BoundingBoxI)](VRageMath.BoundingBoxI.Equals)|Determines whether two instances of BoundingBoxI are equal.|
|[Equals(object)](VRageMath.BoundingBoxI.Equals)|Determines whether two instances of BoundingBoxI are equal.|
|[GetHashCode()](VRageMath.BoundingBoxI.GetHashCode)|Gets the hash code for this instance.|
|[ToString()](VRageMath.BoundingBoxI.ToString)|Returns a String that represents the current BoundingBoxI.|
|[CreateMerged(BoundingBoxI, BoundingBoxI)](VRageMath.BoundingBoxI.CreateMerged)|Creates the smallest BoundingBoxI that contains the two specified BoundingBoxI instances.|
|[CreateMerged(ref BoundingBoxI, ref BoundingBoxI, ref BoundingBoxI)](VRageMath.BoundingBoxI.CreateMerged)|Creates the smallest BoundingBoxI that contains the two specified BoundingBoxI instances.|
|[CreateFromSphere(BoundingSphere)](VRageMath.BoundingBoxI.CreateFromSphere)|Creates the smallest BoundingBoxI that will contain the specified BoundingSphere.|
|[CreateFromSphere(ref BoundingSphere, ref BoundingBoxI)](VRageMath.BoundingBoxI.CreateFromSphere)|Creates the smallest BoundingBoxI that will contain the specified BoundingSphere.|
|[CreateFromPoints(IEnumerable)](VRageMath.BoundingBoxI.CreateFromPoints)||
|[IntersectWith(ref BoundingBoxI)](VRageMath.BoundingBoxI.IntersectWith)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[Intersect(BoundingBoxI)](VRageMath.BoundingBoxI.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[Intersects(BoundingBoxI)](VRageMath.BoundingBoxI.Intersects)|Checks whether the current BoundingBoxI intersects another BoundingBoxI.|
|[Intersects(ref BoundingBoxI)](VRageMath.BoundingBoxI.Intersects)||
|[Intersects(ref BoundingBoxI, ref bool)](VRageMath.BoundingBoxI.Intersects)|Checks whether the current BoundingBoxI intersects another BoundingBoxI.|
|[IntersectsTriangle(Vector3I, Vector3I, Vector3I)](VRageMath.BoundingBoxI.IntersectsTriangle)||
|[IntersectsTriangle(ref Vector3I, ref Vector3I, ref Vector3I)](VRageMath.BoundingBoxI.IntersectsTriangle)||
|[Intersects(Plane)](VRageMath.BoundingBoxI.Intersects)|Checks whether the current BoundingBoxI intersects a Plane.|
|[Intersects(ref Plane, ref PlaneIntersectionType)](VRageMath.BoundingBoxI.Intersects)|Checks whether the current BoundingBoxI intersects a Plane.|
|[Intersects(Line, ref float)](VRageMath.BoundingBoxI.Intersects)||
|[Intersects(Ray)](VRageMath.BoundingBoxI.Intersects)|Checks whether the current BoundingBoxI intersects a Ray.|
|[Intersects(ref Ray, ref Nullable)](VRageMath.BoundingBoxI.Intersects)||
|[Distance(Vector3I)](VRageMath.BoundingBoxI.Distance)|Checks whether the current BoundingBoxI intersects a BoundingSphere.|
|[Contains(BoundingBoxI)](VRageMath.BoundingBoxI.Contains)|Tests whether the BoundingBoxI contains another BoundingBoxI.|
|[Contains(ref BoundingBoxI, ref ContainmentType)](VRageMath.BoundingBoxI.Contains)|Tests whether the BoundingBoxI contains a BoundingBoxI.|
|[Contains(Vector3I)](VRageMath.BoundingBoxI.Contains)|Tests whether the BoundingBoxI contains a point.|
|[Contains(Vector3)](VRageMath.BoundingBoxI.Contains)||
|[Contains(ref Vector3I, ref ContainmentType)](VRageMath.BoundingBoxI.Contains)|Tests whether the BoundingBoxI contains a point.|
|[Translate(Vector3I)](VRageMath.BoundingBoxI.Translate)|Translate|
|[Include(ref Vector3I)](VRageMath.BoundingBoxI.Include)|return expanded aabb (abb include point)|
|[GetIncluded(Vector3I)](VRageMath.BoundingBoxI.GetIncluded)||
|[Include(Vector3I)](VRageMath.BoundingBoxI.Include)||
|[Include(Vector3I, Vector3I, Vector3I)](VRageMath.BoundingBoxI.Include)||
|[Include(ref Vector3I, ref Vector3I, ref Vector3I)](VRageMath.BoundingBoxI.Include)||
|[Include(ref BoundingBoxI)](VRageMath.BoundingBoxI.Include)|return expanded aabb (abb include point)|
|[Include(BoundingBoxI)](VRageMath.BoundingBoxI.Include)||
|[CreateInvalid()](VRageMath.BoundingBoxI.CreateInvalid)||
|[SurfaceArea()](VRageMath.BoundingBoxI.SurfaceArea)||
|[Volume()](VRageMath.BoundingBoxI.Volume)||
|[Inflate(int)](VRageMath.BoundingBoxI.Inflate)||
|[InflateToMinimum(Vector3I)](VRageMath.BoundingBoxI.InflateToMinimum)||
|[IterateDifference(BoundingBoxI, BoundingBoxI)](VRageMath.BoundingBoxI.IterateDifference)|Iterate every cell contained in {left} - {right}, where we interpret {box} as the set of all distinct Vector3I points inside a 'box'. Containment is taken in a typical inclusive start, exclusive end fashion.|
|[EnumeratePoints(BoundingBoxI)](VRageMath.BoundingBoxI.EnumeratePoints)|Enumerate all values in a integer interval (a cuboid). This method is an allocating version of the Vector3I_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.|

