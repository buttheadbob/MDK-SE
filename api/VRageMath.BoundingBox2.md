← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### BoundingBox2 Struct

```csharp
public struct BoundingBox2: IEquatable<BoundingBox2\>
```

Defines an axis-aligned box-shaped 3D volume.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<BoundingBox2\>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\$1Vector2 Max](VRageMath.BoundingBox2.Max)|The maximum point the BoundingBox2 contains.|
|\$1Vector2 Min](VRageMath.BoundingBox2.Min)|The minimum point the BoundingBox2 contains.|

#### Properties

|Member|Description|
|---|---|
|\$1Vector2 Center { get; }](VRageMath.BoundingBox2.Center)|Calculates center|
|\$1Vector2 Extents { get; }](VRageMath.BoundingBox2.Extents)||
|\$1Vector2 HalfExtents { get; }](VRageMath.BoundingBox2.HalfExtents)||
|\$1float Height { get; }](VRageMath.BoundingBox2.Height)||
|\$1Vector2 Size { get; }](VRageMath.BoundingBox2.Size)|Size|
|\$1float Width { get; }](VRageMath.BoundingBox2.Width)||

#### Constructors

|Member|Description|
|---|---|
|\$1BoundingBox2(Vector2, Vector2)](VRageMath.BoundingBox2..ctor)||

#### Methods

|Member|Description|
|---|---|
|\$1static BoundingBox2 CreateFromHalfExtent(Vector2, float)](VRageMath.BoundingBox2.CreateFromHalfExtent)||
|\$1static BoundingBox2 CreateFromHalfExtent(Vector2, Vector2)](VRageMath.BoundingBox2.CreateFromHalfExtent)||
|\$1static BoundingBox2 CreateFromPoints(IEnumerable\$1Vector2\>)](VRageMath.BoundingBox2.CreateFromPoints)|Creates the smallest BoundingBox2 that will contain a group of points.|
|\$1static BoundingBox2 CreateInvalid()](VRageMath.BoundingBox2.CreateInvalid)||
|\$1static BoundingBox2 CreateMerged(BoundingBox2, BoundingBox2)](VRageMath.BoundingBox2.CreateMerged)|Creates the smallest BoundingBox2 that contains the two specified BoundingBox2 instances.|
|\$1static void CreateMerged(ref BoundingBox2, ref BoundingBox2, out BoundingBox2)](VRageMath.BoundingBox2.CreateMerged)|Creates the smallest BoundingBox2 that contains the two specified BoundingBox2 instances.|
|\$1float Area()](VRageMath.BoundingBox2.Area)||
|\$1ContainmentType Contains(BoundingBox2)](VRageMath.BoundingBox2.Contains)|Tests whether the BoundingBox2 contains another BoundingBox2.|
|\$1void Contains(ref BoundingBox2, out ContainmentType)](VRageMath.BoundingBox2.Contains)|Tests whether the BoundingBox2 contains a BoundingBox2.|
|\$1ContainmentType Contains(Vector2)](VRageMath.BoundingBox2.Contains)|Tests whether the BoundingBox2 contains a point.|
|\$1void Contains(ref Vector2, out ContainmentType)](VRageMath.BoundingBox2.Contains)|Tests whether the BoundingBox2 contains a point.|
|\$1float Distance(Vector2)](VRageMath.BoundingBox2.Distance)||
|\$1bool Equals(BoundingBox2)](VRageMath.BoundingBox2.Equals)|Determines whether two instances of BoundingBox2 are equal.|
|\$1bool Equals(object)](VRageMath.BoundingBox2.Equals)|Determines whether two instances of BoundingBox2 are equal.|
|\$1Vector2\$1] GetCorners()](VRageMath.BoundingBox2.GetCorners)|Gets an array of points that make up the corners of the BoundingBox2.|
|\$1void GetCorners(Vector2\$1])](VRageMath.BoundingBox2.GetCorners)|Gets the array of points that make up the corners of the BoundingBox2.|
|\$1void GetCornersUnsafe(*Vector2)](VRageMath.BoundingBox2.GetCornersUnsafe)||
|\$1int GetHashCode()](VRageMath.BoundingBox2.GetHashCode)|Gets the hash code for this instance.|
|\$1BoundingBox2 GetIncluded(Vector2)](VRageMath.BoundingBox2.GetIncluded)||
|\$1BoundingBox2 Include(ref Vector2)](VRageMath.BoundingBox2.Include)|return expanded aabb (abb include point)|
|\$1BoundingBox2 Include(Vector2)](VRageMath.BoundingBox2.Include)||
|\$1BoundingBox2 Include(Vector2, Vector2, Vector2)](VRageMath.BoundingBox2.Include)||
|\$1BoundingBox2 Include(ref Vector2, ref Vector2, ref Vector2)](VRageMath.BoundingBox2.Include)||
|\$1BoundingBox2 Include(ref BoundingBox2)](VRageMath.BoundingBox2.Include)|return expanded aabb (abb include point)|
|\$1BoundingBox2 Include(BoundingBox2)](VRageMath.BoundingBox2.Include)||
|\$1void Inflate(float)](VRageMath.BoundingBox2.Inflate)||
|\$1void InflateToMinimum(Vector2)](VRageMath.BoundingBox2.InflateToMinimum)||
|\$1BoundingBox2 Intersect(BoundingBox2)](VRageMath.BoundingBox2.Intersect)|Returns bounding box which is intersection of this and box Result is invalid box when there's no intersection (Min > Max)|
|\$1bool Intersects(BoundingBox2)](VRageMath.BoundingBox2.Intersects)|Checks whether the current BoundingBox2 intersects another BoundingBox2.|
|\$1bool Intersects(ref BoundingBox2)](VRageMath.BoundingBox2.Intersects)||
|\$1void Intersects(ref BoundingBox2, out bool)](VRageMath.BoundingBox2.Intersects)|Checks whether the current BoundingBox2 intersects another BoundingBox2.|
|\$1float Perimeter()](VRageMath.BoundingBox2.Perimeter)||
|\$1void Scale(Vector2)](VRageMath.BoundingBox2.Scale)||
|\$1string ToString()](VRageMath.BoundingBox2.ToString)|Returns a String that represents the current BoundingBox2.|
|\$1BoundingBox2 Translate(Vector2)](VRageMath.BoundingBox2.Translate)|Translate|

