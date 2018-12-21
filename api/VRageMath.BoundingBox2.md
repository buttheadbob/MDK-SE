← [Index](index.md)
#BoundingBox2 Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
##Summary
Defines an axis-aligned box-shaped 3D volume.
###Fields
|Member|Description|
|---|---|
|[`Vector2 Min`](VRageMath.Min.md)||
|[`Vector2 Max`](VRageMath.Max.md)||
|[`int CornerCount`](VRageMath.CornerCount.md)||
###Properties
|Member|Description|
|---|---|
|[`Vector2 Center`](VRageMath.Center.md)||
|[`Vector2 HalfExtents`](VRageMath.HalfExtents.md)||
|[`Vector2 Extents`](VRageMath.Extents.md)||
|[`float Width`](VRageMath.Width.md)||
|[`float Height`](VRageMath.Height.md)||
|[`Vector2 Size`](VRageMath.Size.md)||
###Methods
|Member|Description|
|---|---|
|[`Vector2[] GetCorners()`](VRageMath.GetCorners.md)||
|[`void GetCorners(Vector2[] corners)`](VRageMath.GetCorners.md)|Gets the array of points that make up the corners of the BoundingBox2.|
|[`void GetCornersUnsafe(*Vector2 corners)`](VRageMath.GetCornersUnsafe.md)||
|[`bool Equals(BoundingBox2 other)`](VRageMath.Equals.md)|Determines whether two instances of BoundingBox2 are equal.|
|[`bool Equals(Object obj)`](VRageMath.Equals.md)|Determines whether two instances of BoundingBox2 are equal.|
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`string ToString()`](VRageMath.ToString.md)||
|[`BoundingBox2 CreateMerged(BoundingBox2 original, BoundingBox2 additional)`](VRageMath.CreateMerged.md)||
|[`void CreateMerged(ref BoundingBox2 original, ref BoundingBox2 additional, ref BoundingBox2 result)`](VRageMath.CreateMerged.md)||
|[`BoundingBox2 CreateFromPoints(IEnumerable<Vector2> points)`](VRageMath.CreateFromPoints.md)|Creates the smallest BoundingBox2 that will contain a group of points.|
|[`BoundingBox2 CreateFromHalfExtent(Vector2 center, float halfExtent)`](VRageMath.CreateFromHalfExtent.md)||
|[`BoundingBox2 CreateFromHalfExtent(Vector2 center, Vector2 halfExtent)`](VRageMath.CreateFromHalfExtent.md)||
|[`BoundingBox2 Intersect(BoundingBox2 box)`](VRageMath.Intersect.md)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`bool Intersects(BoundingBox2 box)`](VRageMath.Intersects.md)|Checks whether the current BoundingBox2 intersects another BoundingBox2.|
|[`bool Intersects(ref BoundingBox2 box)`](VRageMath.Intersects.md)||
|[`void Intersects(ref BoundingBox2 box, ref bool result)`](VRageMath.Intersects.md)||
|[`float Distance(Vector2 point)`](VRageMath.Distance.md)||
|[`ContainmentType Contains(BoundingBox2 box)`](VRageMath.Contains.md)|Tests whether the BoundingBox2 contains another BoundingBox2.|
|[`void Contains(ref BoundingBox2 box, ref ContainmentType result)`](VRageMath.Contains.md)||
|[`ContainmentType Contains(Vector2 point)`](VRageMath.Contains.md)|Tests whether the BoundingBox2 contains a point.|
|[`void Contains(ref Vector2 point, ref ContainmentType result)`](VRageMath.Contains.md)||
|[`BoundingBox2 Translate(Vector2 vctTranlsation)`](VRageMath.Translate.md)|Translate|
|[`BoundingBox2 Include(ref Vector2 point)`](VRageMath.Include.md)||
|[`BoundingBox2 GetIncluded(Vector2 point)`](VRageMath.GetIncluded.md)||
|[`BoundingBox2 Include(Vector2 point)`](VRageMath.Include.md)||
|[`BoundingBox2 Include(Vector2 p0, Vector2 p1, Vector2 p2)`](VRageMath.Include.md)||
|[`BoundingBox2 Include(ref Vector2 p0, ref Vector2 p1, ref Vector2 p2)`](VRageMath.Include.md)||
|[`BoundingBox2 Include(ref BoundingBox2 box)`](VRageMath.Include.md)||
|[`BoundingBox2 Include(BoundingBox2 box)`](VRageMath.Include.md)||
|[`BoundingBox2 CreateInvalid()`](VRageMath.CreateInvalid.md)||
|[`float Perimeter()`](VRageMath.Perimeter.md)||
|[`float Area()`](VRageMath.Area.md)||
|[`void Inflate(float size)`](VRageMath.Inflate.md)||
|[`void InflateToMinimum(Vector2 minimumSize)`](VRageMath.InflateToMinimum.md)||
|[`void Scale(Vector2 scale)`](VRageMath.Scale.md)||
