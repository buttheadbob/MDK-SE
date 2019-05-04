← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### BoundingBox2D Struct

```csharp
public struct BoundingBox2D: IEquatable<VRageMath.BoundingBox2D>
```

Defines an axis-aligned box-shaped 3D volume.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<VRageMath.BoundingBox2D>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[Min](VRageMath.BoundingBox2D.Min)|The minimum point the BoundingBox2D contains.|
|[Max](VRageMath.BoundingBox2D.Max)|The maximum point the BoundingBox2D contains.|
|[CornerCount](VRageMath.BoundingBox2D.CornerCount)|Specifies the total number of corners (8) in the BoundingBox2D.|

#### Properties

|Member|Description|
|---|---|
|[Center](VRageMath.BoundingBox2D.Center)|Calculates center|
|[HalfExtents](VRageMath.BoundingBox2D.HalfExtents)||
|[Extents](VRageMath.BoundingBox2D.Extents)||
|[Width](VRageMath.BoundingBox2D.Width)||
|[Height](VRageMath.BoundingBox2D.Height)||
|[Size](VRageMath.BoundingBox2D.Size)|Size|

#### Constructors

|Member|Description|
|---|---|
|[BoundingBox2D(Vector2D, Vector2D)](VRageMath.BoundingBox2D..ctor)||

#### Methods

|Member|Description|
|---|---|
|[GetCorners()](VRageMath.BoundingBox2D.GetCorners)|Gets an array of points that make up the corners of the BoundingBox2D.|
|[GetCorners(Vector2D[])](VRageMath.BoundingBox2D.GetCorners)|Gets the array of points that make up the corners of the BoundingBox2D.|
|[GetCornersUnsafe(*Vector2D)](VRageMath.BoundingBox2D.GetCornersUnsafe)||
|[Equals(BoundingBox2D)](VRageMath.BoundingBox2D.Equals)|Determines whether two instances of BoundingBox2D are equal.|
|[Equals(object)](VRageMath.BoundingBox2D.Equals)|Determines whether two instances of BoundingBox2D are equal.|
|[GetHashCode()](VRageMath.BoundingBox2D.GetHashCode)|Gets the hash code for this instance.|
|[ToString()](VRageMath.BoundingBox2D.ToString)|Returns a String that represents the current BoundingBox2D.|
|[CreateMerged(BoundingBox2D, BoundingBox2D)](VRageMath.BoundingBox2D.CreateMerged)|Creates the smallest BoundingBox2D that contains the two specified BoundingBox2D instances.|
|[CreateMerged(ref BoundingBox2D, ref BoundingBox2D, ref BoundingBox2D)](VRageMath.BoundingBox2D.CreateMerged)|Creates the smallest BoundingBox2D that contains the two specified BoundingBox2D instances.|
|[CreateFromPoints(IEnumerable)](VRageMath.BoundingBox2D.CreateFromPoints)||
|[CreateFromHalfExtent(Vector2D, double)](VRageMath.BoundingBox2D.CreateFromHalfExtent)||
|[CreateFromHalfExtent(Vector2D, Vector2D)](VRageMath.BoundingBox2D.CreateFromHalfExtent)||
|[Intersect(BoundingBox2D)](VRageMath.BoundingBox2D.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[Intersects(BoundingBox2D)](VRageMath.BoundingBox2D.Intersects)|Checks whether the current BoundingBox2D intersects another BoundingBox2D.|
|[Intersects(ref BoundingBox2D)](VRageMath.BoundingBox2D.Intersects)||
|[Intersects(ref BoundingBox2D, ref bool)](VRageMath.BoundingBox2D.Intersects)|Checks whether the current BoundingBox2D intersects another BoundingBox2D.|
|[Distance(Vector2D)](VRageMath.BoundingBox2D.Distance)||
|[Contains(BoundingBox2D)](VRageMath.BoundingBox2D.Contains)|Tests whether the BoundingBox2D contains another BoundingBox2D.|
|[Contains(ref BoundingBox2D, ref ContainmentType)](VRageMath.BoundingBox2D.Contains)|Tests whether the BoundingBox2D contains a BoundingBox2D.|
|[Contains(Vector2D)](VRageMath.BoundingBox2D.Contains)|Tests whether the BoundingBox2D contains a point.|
|[Contains(ref Vector2D, ref ContainmentType)](VRageMath.BoundingBox2D.Contains)|Tests whether the BoundingBox2D contains a point.|
|[Translate(Vector2D)](VRageMath.BoundingBox2D.Translate)|Translate|
|[Include(ref Vector2D)](VRageMath.BoundingBox2D.Include)|return expanded aabb (abb include point)|
|[GetIncluded(Vector2D)](VRageMath.BoundingBox2D.GetIncluded)||
|[Include(Vector2D)](VRageMath.BoundingBox2D.Include)||
|[Include(Vector2D, Vector2D, Vector2D)](VRageMath.BoundingBox2D.Include)||
|[Include(ref Vector2D, ref Vector2D, ref Vector2D)](VRageMath.BoundingBox2D.Include)||
|[Include(ref BoundingBox2D)](VRageMath.BoundingBox2D.Include)|return expanded aabb (abb include point)|
|[Include(BoundingBox2D)](VRageMath.BoundingBox2D.Include)||
|[CreateInvalid()](VRageMath.BoundingBox2D.CreateInvalid)||
|[Perimeter()](VRageMath.BoundingBox2D.Perimeter)||
|[Area()](VRageMath.BoundingBox2D.Area)||
|[Inflate(double)](VRageMath.BoundingBox2D.Inflate)||
|[InflateToMinimum(Vector2D)](VRageMath.BoundingBox2D.InflateToMinimum)||
|[Scale(Vector2D)](VRageMath.BoundingBox2D.Scale)||

