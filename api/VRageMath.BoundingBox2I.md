← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### BoundingBox2I Struct

```csharp
public struct BoundingBox2I: IEquatable<VRageMath.BoundingBox2I>
```

Defines an axis-aligned box-shaped 3D volume.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<VRageMath.BoundingBox2I>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[Vector2I Max](VRageMath.BoundingBox2I.Max)|The maximum point the BoundingBox2I contains.|
|[Vector2I Min](VRageMath.BoundingBox2I.Min)|The minimum point the BoundingBox2I contains.|

#### Properties

|Member|Description|
|---|---|
|[Vector2I Center { get; }](VRageMath.BoundingBox2I.Center)|Calculates center|
|[Vector2I Extents { get; }](VRageMath.BoundingBox2I.Extents)||
|[Vector2I HalfExtents { get; }](VRageMath.BoundingBox2I.HalfExtents)||
|[float Height { get; }](VRageMath.BoundingBox2I.Height)||
|[Vector2I Size { get; }](VRageMath.BoundingBox2I.Size)|Size|
|[float Width { get; }](VRageMath.BoundingBox2I.Width)||

#### Constructors

|Member|Description|
|---|---|
|[BoundingBox2I(Vector2I, Vector2I)](VRageMath.BoundingBox2I..ctor)||

#### Methods

|Member|Description|
|---|---|
|[static BoundingBox2I CreateFromHalfExtent(Vector2I, int)](VRageMath.BoundingBox2I.CreateFromHalfExtent)||
|[static BoundingBox2I CreateFromHalfExtent(Vector2I, Vector2I)](VRageMath.BoundingBox2I.CreateFromHalfExtent)||
|[static BoundingBox2I CreateFromPoints(IEnumerable<VRageMath.Vector2I>)](VRageMath.BoundingBox2I.CreateFromPoints)|Creates the smallest BoundingBox2I that will contain a group of points.|
|[static BoundingBox2I CreateInvalid()](VRageMath.BoundingBox2I.CreateInvalid)||
|[static BoundingBox2I CreateMerged(BoundingBox2I, BoundingBox2I)](VRageMath.BoundingBox2I.CreateMerged)|Creates the smallest BoundingBox2I that contains the two specified BoundingBox2I instances.|
|[static void CreateMerged(ref BoundingBox2I, ref BoundingBox2I, out BoundingBox2I)](VRageMath.BoundingBox2I.CreateMerged)|Creates the smallest BoundingBox2I that contains the two specified BoundingBox2I instances.|
|[float Area()](VRageMath.BoundingBox2I.Area)||
|[ContainmentType Contains(BoundingBox2I)](VRageMath.BoundingBox2I.Contains)|Tests whether the BoundingBox2I contains another BoundingBox2I.|
|[void Contains(ref BoundingBox2I, out ContainmentType)](VRageMath.BoundingBox2I.Contains)|Tests whether the BoundingBox2I contains a BoundingBox2I.|
|[ContainmentType Contains(Vector2I)](VRageMath.BoundingBox2I.Contains)|Tests whether the BoundingBox2I contains a point.|
|[void Contains(ref Vector2I, out ContainmentType)](VRageMath.BoundingBox2I.Contains)|Tests whether the BoundingBox2I contains a point.|
|[bool Equals(BoundingBox2I)](VRageMath.BoundingBox2I.Equals)|Determines whether two instances of BoundingBox2I are equal.|
|[bool Equals(object)](VRageMath.BoundingBox2I.Equals)|Determines whether two instances of BoundingBox2I are equal.|
|[Vector2I[] GetCorners()](VRageMath.BoundingBox2I.GetCorners)|Gets an array of points that make up the corners of the BoundingBox2I.|
|[void GetCorners(Vector2I[])](VRageMath.BoundingBox2I.GetCorners)|Gets the array of points that make up the corners of the BoundingBox2I.|
|[void GetCornersUnsafe(*Vector2I)](VRageMath.BoundingBox2I.GetCornersUnsafe)||
|[int GetHashCode()](VRageMath.BoundingBox2I.GetHashCode)|Gets the hash code for this instance.|
|[BoundingBox2I GetIncluded(Vector2I)](VRageMath.BoundingBox2I.GetIncluded)||
|[BoundingBox2I Include(ref Vector2I)](VRageMath.BoundingBox2I.Include)|return expanded aabb (abb include point)|
|[BoundingBox2I Include(Vector2I)](VRageMath.BoundingBox2I.Include)||
|[BoundingBox2I Include(Vector2I, Vector2I, Vector2I)](VRageMath.BoundingBox2I.Include)||
|[BoundingBox2I Include(ref Vector2I, ref Vector2I, ref Vector2I)](VRageMath.BoundingBox2I.Include)||
|[BoundingBox2I Include(ref BoundingBox2I)](VRageMath.BoundingBox2I.Include)|return expanded aabb (abb include point)|
|[BoundingBox2I Include(BoundingBox2I)](VRageMath.BoundingBox2I.Include)||
|[void Inflate(int)](VRageMath.BoundingBox2I.Inflate)||
|[void InflateToMinimum(Vector2I)](VRageMath.BoundingBox2I.InflateToMinimum)||
|[BoundingBox2I Intersect(BoundingBox2I)](VRageMath.BoundingBox2I.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[bool Intersects(BoundingBox2I)](VRageMath.BoundingBox2I.Intersects)|Checks whether the current BoundingBox2I intersects another BoundingBox2I.|
|[bool Intersects(ref BoundingBox2I)](VRageMath.BoundingBox2I.Intersects)||
|[void Intersects(ref BoundingBox2I, out bool)](VRageMath.BoundingBox2I.Intersects)|Checks whether the current BoundingBox2I intersects another BoundingBox2I.|
|[float Perimeter()](VRageMath.BoundingBox2I.Perimeter)||
|[void Scale(Vector2I)](VRageMath.BoundingBox2I.Scale)||
|[string ToString()](VRageMath.BoundingBox2I.ToString)|Returns a String that represents the current BoundingBox2I.|
|[BoundingBox2I Translate(Vector2I)](VRageMath.BoundingBox2I.Translate)|Translate|

