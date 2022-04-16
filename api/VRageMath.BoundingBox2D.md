← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### BoundingBox2D Struct

```csharp
public struct BoundingBox2D: IEquatable<BoundingBox2D>
```

Defines an axis-aligned box-shaped 2D volume.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<BoundingBox2D>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\\$1static int CornerCount](VRageMath.BoundingBox2D.CornerCount)|Specifies the total number of corners (8) in the BoundingBox2D.|
|\\$1Vector2D Max](VRageMath.BoundingBox2D.Max)|The maximum point the BoundingBox2D contains.|
|\\$1Vector2D Min](VRageMath.BoundingBox2D.Min)|The minimum point the BoundingBox2D contains.|

#### Properties

|Member|Description|
|---|---|
|\\$1Vector2D Center { get; }](VRageMath.BoundingBox2D.Center)|Calculates center|
|\\$1Vector2D Extents { get; }](VRageMath.BoundingBox2D.Extents)||
|\\$1Vector2D HalfExtents { get; }](VRageMath.BoundingBox2D.HalfExtents)||
|\\$1double Height { get; }](VRageMath.BoundingBox2D.Height)||
|\\$1Vector2D Size { get; }](VRageMath.BoundingBox2D.Size)|Size|
|\\$1double Width { get; }](VRageMath.BoundingBox2D.Width)||

#### Constructors

|Member|Description|
|---|---|
|\\$1BoundingBox2D(Vector2D, Vector2D)](VRageMath.BoundingBox2D..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\$1static BoundingBox2D CreateFromHalfExtent(Vector2D, double)](VRageMath.BoundingBox2D.CreateFromHalfExtent)||
|\\$1static BoundingBox2D CreateFromHalfExtent(Vector2D, Vector2D)](VRageMath.BoundingBox2D.CreateFromHalfExtent)||
|\\$1static BoundingBox2D CreateFromPoints(IEnumerable\\$1Vector2D>)](VRageMath.BoundingBox2D.CreateFromPoints)|Creates the smallest BoundingBox2D that will contain a group of points.|
|\\$1static BoundingBox2D CreateInvalid()](VRageMath.BoundingBox2D.CreateInvalid)||
|\\$1static BoundingBox2D CreateMerged(BoundingBox2D, BoundingBox2D)](VRageMath.BoundingBox2D.CreateMerged)|Creates the smallest BoundingBox2D that contains the two specified BoundingBox2D instances.|
|\\$1static void CreateMerged(ref BoundingBox2D, ref BoundingBox2D, out BoundingBox2D)](VRageMath.BoundingBox2D.CreateMerged)|Creates the smallest BoundingBox2D that contains the two specified BoundingBox2D instances.|
|\\$1double Area()](VRageMath.BoundingBox2D.Area)||
|\\$1ContainmentType Contains(BoundingBox2D)](VRageMath.BoundingBox2D.Contains)|Tests whether the BoundingBox2D contains another BoundingBox2D.|
|\\$1void Contains(ref BoundingBox2D, out ContainmentType)](VRageMath.BoundingBox2D.Contains)|Tests whether the BoundingBox2D contains a BoundingBox2D.|
|\\$1ContainmentType Contains(Vector2D)](VRageMath.BoundingBox2D.Contains)|Tests whether the BoundingBox2D contains a point.|
|\\$1void Contains(ref Vector2D, out ContainmentType)](VRageMath.BoundingBox2D.Contains)|Tests whether the BoundingBox2D contains a point.|
|\\$1double Distance(Vector2D)](VRageMath.BoundingBox2D.Distance)||
|\\$1bool Equals(BoundingBox2D)](VRageMath.BoundingBox2D.Equals)|Determines whether two instances of BoundingBox2D are equal.|
|\\$1bool Equals(object)](VRageMath.BoundingBox2D.Equals)|Determines whether two instances of BoundingBox2D are equal.|
|\\$1Vector2D\\$1] GetCorners()](VRageMath.BoundingBox2D.GetCorners)|Gets an array of points that make up the corners of the BoundingBox2D.|
|\\$1void GetCorners(Vector2D\\$1])](VRageMath.BoundingBox2D.GetCorners)|Gets the array of points that make up the corners of the BoundingBox2D.|
|\\$1void GetCornersUnsafe(*Vector2D)](VRageMath.BoundingBox2D.GetCornersUnsafe)||
|\\$1int GetHashCode()](VRageMath.BoundingBox2D.GetHashCode)|Gets the hash code for this instance.|
|\\$1BoundingBox2D GetIncluded(Vector2D)](VRageMath.BoundingBox2D.GetIncluded)||
|\\$1BoundingBox2D Include(ref Vector2D)](VRageMath.BoundingBox2D.Include)|return expanded aabb (abb include point)|
|\\$1BoundingBox2D Include(Vector2D)](VRageMath.BoundingBox2D.Include)||
|\\$1BoundingBox2D Include(Vector2D, Vector2D, Vector2D)](VRageMath.BoundingBox2D.Include)||
|\\$1BoundingBox2D Include(ref Vector2D, ref Vector2D, ref Vector2D)](VRageMath.BoundingBox2D.Include)||
|\\$1BoundingBox2D Include(ref BoundingBox2D)](VRageMath.BoundingBox2D.Include)|return expanded aabb (abb include point)|
|\\$1BoundingBox2D Include(BoundingBox2D)](VRageMath.BoundingBox2D.Include)||
|\\$1void Inflate(double)](VRageMath.BoundingBox2D.Inflate)||
|\\$1void InflateToMinimum(Vector2D)](VRageMath.BoundingBox2D.InflateToMinimum)||
|\\$1BoundingBox2D Intersect(BoundingBox2D)](VRageMath.BoundingBox2D.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|\\$1bool Intersects(BoundingBox2D)](VRageMath.BoundingBox2D.Intersects)|Checks whether the current BoundingBox2D intersects another BoundingBox2D.|
|\\$1bool Intersects(ref BoundingBox2D)](VRageMath.BoundingBox2D.Intersects)||
|\\$1void Intersects(ref BoundingBox2D, out bool)](VRageMath.BoundingBox2D.Intersects)|Checks whether the current BoundingBox2D intersects another BoundingBox2D.|
|\\$1double Perimeter()](VRageMath.BoundingBox2D.Perimeter)||
|\\$1void Scale(Vector2D)](VRageMath.BoundingBox2D.Scale)||
|\\$1string ToString()](VRageMath.BoundingBox2D.ToString)|Returns a String that represents the current BoundingBox2D.|
|\\$1BoundingBox2D Translate(Vector2D)](VRageMath.BoundingBox2D.Translate)|Translate|

