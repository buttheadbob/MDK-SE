← [Index](Api-Index)

#### BoundingBox2I Struct

```csharp
public struct BoundingBox2I: ValueType, IEquatable<T>
```

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Inheritance: **[ValueType](System.ValueType)

**Implements:**  
* [IEquatable<T>](System.IEquatable`1)

#### Example

#### Remarks

#### Fields

|Member|Description|
|---|---|
|[Min](VRageMath.BoundingBox2I.Min)|The minimum point the BoundingBox2I contains.|
|[Max](VRageMath.BoundingBox2I.Max)|The maximum point the BoundingBox2I contains.|
|[CornerCount](VRageMath.BoundingBox2I.CornerCount)|Specifies the total number of corners (8) in the BoundingBox2I.|

#### Properties

|Member|Description|
|---|---|
|[Center](VRageMath.BoundingBox2I.Center)|Calculates center|
|[HalfExtents](VRageMath.BoundingBox2I.HalfExtents)||
|[Extents](VRageMath.BoundingBox2I.Extents)||
|[Width](VRageMath.BoundingBox2I.Width)||
|[Height](VRageMath.BoundingBox2I.Height)||
|[Size](VRageMath.BoundingBox2I.Size)|Size|

#### Methods

|Member|Description|
|---|---|
|[GetCorners()](VRageMath.BoundingBox2I.GetCorners)|Gets an array of points that make up the corners of the BoundingBox2I.|
|[GetCorners(Vector2I[])](VRageMath.BoundingBox2I.GetCorners)|Gets the array of points that make up the corners of the BoundingBox2I.|
|[GetCornersUnsafe(*Vector2I)](VRageMath.BoundingBox2I.GetCornersUnsafe)||
|[Equals(BoundingBox2I)](VRageMath.BoundingBox2I.Equals)|Determines whether two instances of BoundingBox2I are equal.|
|[Equals(object)](VRageMath.BoundingBox2I.Equals)|Determines whether two instances of BoundingBox2I are equal.|
|[GetHashCode()](VRageMath.BoundingBox2I.GetHashCode)|Gets the hash code for this instance.|
|[ToString()](VRageMath.BoundingBox2I.ToString)|Returns a String that represents the current BoundingBox2I.|
|[CreateMerged(BoundingBox2I, BoundingBox2I)](VRageMath.BoundingBox2I.CreateMerged)|Creates the smallest BoundingBox2I that contains the two specified BoundingBox2I instances.|
|[CreateMerged(ref BoundingBox2I, ref BoundingBox2I, ref BoundingBox2I)](VRageMath.BoundingBox2I.CreateMerged)|Creates the smallest BoundingBox2I that contains the two specified BoundingBox2I instances.|
|[CreateFromPoints(IEnumerable)](VRageMath.BoundingBox2I.CreateFromPoints)||
|[CreateFromHalfExtent(Vector2I, int)](VRageMath.BoundingBox2I.CreateFromHalfExtent)||
|[CreateFromHalfExtent(Vector2I, Vector2I)](VRageMath.BoundingBox2I.CreateFromHalfExtent)||
|[Intersect(BoundingBox2I)](VRageMath.BoundingBox2I.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[Intersects(BoundingBox2I)](VRageMath.BoundingBox2I.Intersects)|Checks whether the current BoundingBox2I intersects another BoundingBox2I.|
|[Intersects(ref BoundingBox2I)](VRageMath.BoundingBox2I.Intersects)||
|[Intersects(ref BoundingBox2I, ref bool)](VRageMath.BoundingBox2I.Intersects)|Checks whether the current BoundingBox2I intersects another BoundingBox2I.|
|[Contains(BoundingBox2I)](VRageMath.BoundingBox2I.Contains)|Tests whether the BoundingBox2I contains another BoundingBox2I.|
|[Contains(ref BoundingBox2I, ref ContainmentType)](VRageMath.BoundingBox2I.Contains)|Tests whether the BoundingBox2I contains a BoundingBox2I.|
|[Contains(Vector2I)](VRageMath.BoundingBox2I.Contains)|Tests whether the BoundingBox2I contains a point.|
|[Contains(ref Vector2I, ref ContainmentType)](VRageMath.BoundingBox2I.Contains)|Tests whether the BoundingBox2I contains a point.|
|[Translate(Vector2I)](VRageMath.BoundingBox2I.Translate)|Translate|
|[Include(ref Vector2I)](VRageMath.BoundingBox2I.Include)|return expanded aabb (abb include point)|
|[GetIncluded(Vector2I)](VRageMath.BoundingBox2I.GetIncluded)||
|[Include(Vector2I)](VRageMath.BoundingBox2I.Include)||
|[Include(Vector2I, Vector2I, Vector2I)](VRageMath.BoundingBox2I.Include)||
|[Include(ref Vector2I, ref Vector2I, ref Vector2I)](VRageMath.BoundingBox2I.Include)||
|[Include(ref BoundingBox2I)](VRageMath.BoundingBox2I.Include)|return expanded aabb (abb include point)|
|[Include(BoundingBox2I)](VRageMath.BoundingBox2I.Include)||
|[CreateInvalid()](VRageMath.BoundingBox2I.CreateInvalid)||
|[Perimeter()](VRageMath.BoundingBox2I.Perimeter)||
|[Area()](VRageMath.BoundingBox2I.Area)||
|[Inflate(int)](VRageMath.BoundingBox2I.Inflate)||
|[InflateToMinimum(Vector2I)](VRageMath.BoundingBox2I.InflateToMinimum)||
|[Scale(Vector2I)](VRageMath.BoundingBox2I.Scale)||

