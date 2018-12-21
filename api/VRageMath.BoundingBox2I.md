← [Index](index.md)
#BoundingBox2I Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
##Summary
Defines an axis-aligned box-shaped 3D volume.
###Fields
|Member|Description|
|---|---|
|[`Vector2I Min`](VRageMath.Min.md)||
|[`Vector2I Max`](VRageMath.Max.md)||
|[`int CornerCount`](VRageMath.CornerCount.md)||
###Properties
|Member|Description|
|---|---|
|[`Vector2I Center`](VRageMath.Center.md)||
|[`Vector2I HalfExtents`](VRageMath.HalfExtents.md)||
|[`Vector2I Extents`](VRageMath.Extents.md)||
|[`float Width`](VRageMath.Width.md)||
|[`float Height`](VRageMath.Height.md)||
|[`Vector2I Size`](VRageMath.Size.md)||
###Methods
|Member|Description|
|---|---|
|[`Vector2I[] GetCorners()`](VRageMath.GetCorners.md)||
|[`void GetCorners(Vector2I[] corners)`](VRageMath.GetCorners.md)|Gets the array of points that make up the corners of the BoundingBox2I.|
|[`void GetCornersUnsafe(*Vector2I corners)`](VRageMath.GetCornersUnsafe.md)||
|[`bool Equals(BoundingBox2I other)`](VRageMath.Equals.md)|Determines whether two instances of BoundingBox2I are equal.|
|[`bool Equals(Object obj)`](VRageMath.Equals.md)|Determines whether two instances of BoundingBox2I are equal.|
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`string ToString()`](VRageMath.ToString.md)||
|[`BoundingBox2I CreateMerged(BoundingBox2I original, BoundingBox2I additional)`](VRageMath.CreateMerged.md)||
|[`void CreateMerged(ref BoundingBox2I original, ref BoundingBox2I additional, ref BoundingBox2I result)`](VRageMath.CreateMerged.md)||
|[`BoundingBox2I CreateFromPoints(IEnumerable<Vector2I> points)`](VRageMath.CreateFromPoints.md)|Creates the smallest BoundingBox2I that will contain a group of points.|
|[`BoundingBox2I CreateFromHalfExtent(Vector2I center, int halfExtent)`](VRageMath.CreateFromHalfExtent.md)||
|[`BoundingBox2I CreateFromHalfExtent(Vector2I center, Vector2I halfExtent)`](VRageMath.CreateFromHalfExtent.md)||
|[`BoundingBox2I Intersect(BoundingBox2I box)`](VRageMath.Intersect.md)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`bool Intersects(BoundingBox2I box)`](VRageMath.Intersects.md)|Checks whether the current BoundingBox2I intersects another BoundingBox2I.|
|[`bool Intersects(ref BoundingBox2I box)`](VRageMath.Intersects.md)||
|[`void Intersects(ref BoundingBox2I box, ref bool result)`](VRageMath.Intersects.md)||
|[`ContainmentType Contains(BoundingBox2I box)`](VRageMath.Contains.md)|Tests whether the BoundingBox2I contains another BoundingBox2I.|
|[`void Contains(ref BoundingBox2I box, ref ContainmentType result)`](VRageMath.Contains.md)||
|[`ContainmentType Contains(Vector2I point)`](VRageMath.Contains.md)|Tests whether the BoundingBox2I contains a point.|
|[`void Contains(ref Vector2I point, ref ContainmentType result)`](VRageMath.Contains.md)||
|[`BoundingBox2I Translate(Vector2I vctTranlsation)`](VRageMath.Translate.md)|Translate|
|[`BoundingBox2I Include(ref Vector2I point)`](VRageMath.Include.md)||
|[`BoundingBox2I GetIncluded(Vector2I point)`](VRageMath.GetIncluded.md)||
|[`BoundingBox2I Include(Vector2I point)`](VRageMath.Include.md)||
|[`BoundingBox2I Include(Vector2I p0, Vector2I p1, Vector2I p2)`](VRageMath.Include.md)||
|[`BoundingBox2I Include(ref Vector2I p0, ref Vector2I p1, ref Vector2I p2)`](VRageMath.Include.md)||
|[`BoundingBox2I Include(ref BoundingBox2I box)`](VRageMath.Include.md)||
|[`BoundingBox2I Include(BoundingBox2I box)`](VRageMath.Include.md)||
|[`BoundingBox2I CreateInvalid()`](VRageMath.CreateInvalid.md)||
|[`float Perimeter()`](VRageMath.Perimeter.md)||
|[`float Area()`](VRageMath.Area.md)||
|[`void Inflate(int size)`](VRageMath.Inflate.md)||
|[`void InflateToMinimum(Vector2I minimumSize)`](VRageMath.InflateToMinimum.md)||
|[`void Scale(Vector2I scale)`](VRageMath.Scale.md)||
