← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### BoundingBox2 Struct

```csharp
public struct BoundingBox2: IEquatable<VRageMath.BoundingBox2>
```

Defines an axis-aligned box-shaped 3D volume.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<VRageMath.BoundingBox2>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[Vector2 Max](VRageMath.BoundingBox2.Max)|The maximum point the BoundingBox2 contains.|
|[Vector2 Min](VRageMath.BoundingBox2.Min)|The minimum point the BoundingBox2 contains.|

#### Properties

|Member|Description|
|---|---|
|[Vector2 Center { get; }](VRageMath.BoundingBox2.Center)|Calculates center|
|[Vector2 Extents { get; }](VRageMath.BoundingBox2.Extents)||
|[Vector2 HalfExtents { get; }](VRageMath.BoundingBox2.HalfExtents)||
|[float Height { get; }](VRageMath.BoundingBox2.Height)||
|[Vector2 Size { get; }](VRageMath.BoundingBox2.Size)|Size|
|[float Width { get; }](VRageMath.BoundingBox2.Width)||

#### Constructors

|Member|Description|
|---|---|
|[BoundingBox2(Vector2, Vector2)](VRageMath.BoundingBox2..ctor)||

#### Methods

|Member|Description|
|---|---|
|[static BoundingBox2 CreateFromHalfExtent(Vector2, float)](VRageMath.BoundingBox2.CreateFromHalfExtent)||
|[static BoundingBox2 CreateFromHalfExtent(Vector2, Vector2)](VRageMath.BoundingBox2.CreateFromHalfExtent)||
|[static BoundingBox2 CreateFromPoints(IEnumerable<VRageMath.Vector2>)](VRageMath.BoundingBox2.CreateFromPoints)|Creates the smallest BoundingBox2 that will contain a group of points.|
|[static BoundingBox2 CreateInvalid()](VRageMath.BoundingBox2.CreateInvalid)||
|[static BoundingBox2 CreateMerged(BoundingBox2, BoundingBox2)](VRageMath.BoundingBox2.CreateMerged)|Creates the smallest BoundingBox2 that contains the two specified BoundingBox2 instances.|
|[static void CreateMerged(ref BoundingBox2, ref BoundingBox2, out BoundingBox2)](VRageMath.BoundingBox2.CreateMerged)|Creates the smallest BoundingBox2 that contains the two specified BoundingBox2 instances.|
|[float Area()](VRageMath.BoundingBox2.Area)||
|[ContainmentType Contains(BoundingBox2)](VRageMath.BoundingBox2.Contains)|Tests whether the BoundingBox2 contains another BoundingBox2.|
|[void Contains(ref BoundingBox2, out ContainmentType)](VRageMath.BoundingBox2.Contains)|Tests whether the BoundingBox2 contains a BoundingBox2.|
|[ContainmentType Contains(Vector2)](VRageMath.BoundingBox2.Contains)|Tests whether the BoundingBox2 contains a point.|
|[void Contains(ref Vector2, out ContainmentType)](VRageMath.BoundingBox2.Contains)|Tests whether the BoundingBox2 contains a point.|
|[float Distance(Vector2)](VRageMath.BoundingBox2.Distance)||
|[bool Equals(BoundingBox2)](VRageMath.BoundingBox2.Equals)|Determines whether two instances of BoundingBox2 are equal.|
|[bool Equals(object)](VRageMath.BoundingBox2.Equals)|Determines whether two instances of BoundingBox2 are equal.|
|[Vector2[] GetCorners()](VRageMath.BoundingBox2.GetCorners)|Gets an array of points that make up the corners of the BoundingBox2.|
|[void GetCorners(Vector2[])](VRageMath.BoundingBox2.GetCorners)|Gets the array of points that make up the corners of the BoundingBox2.|
|[void GetCornersUnsafe(*Vector2)](VRageMath.BoundingBox2.GetCornersUnsafe)||
|[int GetHashCode()](VRageMath.BoundingBox2.GetHashCode)|Gets the hash code for this instance.|
|[BoundingBox2 GetIncluded(Vector2)](VRageMath.BoundingBox2.GetIncluded)||
|[BoundingBox2 Include(ref Vector2)](VRageMath.BoundingBox2.Include)|return expanded aabb (abb include point)|
|[BoundingBox2 Include(Vector2)](VRageMath.BoundingBox2.Include)||
|[BoundingBox2 Include(Vector2, Vector2, Vector2)](VRageMath.BoundingBox2.Include)||
|[BoundingBox2 Include(ref Vector2, ref Vector2, ref Vector2)](VRageMath.BoundingBox2.Include)||
|[BoundingBox2 Include(ref BoundingBox2)](VRageMath.BoundingBox2.Include)|return expanded aabb (abb include point)|
|[BoundingBox2 Include(BoundingBox2)](VRageMath.BoundingBox2.Include)||
|[void Inflate(float)](VRageMath.BoundingBox2.Inflate)||
|[void InflateToMinimum(Vector2)](VRageMath.BoundingBox2.InflateToMinimum)||
|[BoundingBox2 Intersect(BoundingBox2)](VRageMath.BoundingBox2.Intersect)|Returns bounding box which is intersection of this and box Result is invalid box when there's no intersection (Min > Max)|
|[bool Intersects(BoundingBox2)](VRageMath.BoundingBox2.Intersects)|Checks whether the current BoundingBox2 intersects another BoundingBox2.|
|[bool Intersects(ref BoundingBox2)](VRageMath.BoundingBox2.Intersects)||
|[void Intersects(ref BoundingBox2, out bool)](VRageMath.BoundingBox2.Intersects)|Checks whether the current BoundingBox2 intersects another BoundingBox2.|
|[float Perimeter()](VRageMath.BoundingBox2.Perimeter)||
|[void Scale(Vector2)](VRageMath.BoundingBox2.Scale)||
|[string ToString()](VRageMath.BoundingBox2.ToString)|Returns a String that represents the current BoundingBox2.|
|[BoundingBox2 Translate(Vector2)](VRageMath.BoundingBox2.Translate)|Translate|

