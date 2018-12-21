← [Index](index.md)
# BoundingBox2D Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`Vector2D Min`](VRageMath.Min.md)||
|[`Vector2D Max`](VRageMath.Max.md)||
|[`int CornerCount`](VRageMath.CornerCount.md)||
### Properties
|Member|Description|
|---|---|
|[`Vector2D Center`](VRageMath.Center.md)||
|[`Vector2D HalfExtents`](VRageMath.HalfExtents.md)||
|[`Vector2D Extents`](VRageMath.Extents.md)||
|[`double Width`](VRageMath.Width.md)||
|[`double Height`](VRageMath.Height.md)||
|[`Vector2D Size`](VRageMath.Size.md)||
### Methods
|Member|Description|
|---|---|
|[`Vector2D[] GetCorners()`](VRageMath.GetCorners.md)||
|[`void GetCorners(Vector2D[] corners)`](VRageMath.GetCorners.md)|Gets the array of points that make up the corners of the BoundingBox2D.|
|[`void GetCornersUnsafe(*Vector2D corners)`](VRageMath.GetCornersUnsafe.md)||
|[`bool Equals(BoundingBox2D other)`](VRageMath.Equals.md)|Determines whether two instances of BoundingBox2D are equal.|
|[`bool Equals(Object obj)`](VRageMath.Equals.md)|Determines whether two instances of BoundingBox2D are equal.|
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`string ToString()`](VRageMath.ToString.md)||
|[`BoundingBox2D CreateMerged(BoundingBox2D original, BoundingBox2D additional)`](VRageMath.CreateMerged.md)||
|[`void CreateMerged(ref BoundingBox2D original, ref BoundingBox2D additional, ref BoundingBox2D result)`](VRageMath.CreateMerged.md)||
|[`BoundingBox2D CreateFromPoints(IEnumerable<Vector2D> points)`](VRageMath.CreateFromPoints.md)|Creates the smallest BoundingBox2D that will contain a group of points.|
|[`BoundingBox2D CreateFromHalfExtent(Vector2D center, double halfExtent)`](VRageMath.CreateFromHalfExtent.md)||
|[`BoundingBox2D CreateFromHalfExtent(Vector2D center, Vector2D halfExtent)`](VRageMath.CreateFromHalfExtent.md)||
|[`BoundingBox2D Intersect(BoundingBox2D box)`](VRageMath.Intersect.md)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`bool Intersects(BoundingBox2D box)`](VRageMath.Intersects.md)|Checks whether the current BoundingBox2D intersects another BoundingBox2D.|
|[`bool Intersects(ref BoundingBox2D box)`](VRageMath.Intersects.md)||
|[`void Intersects(ref BoundingBox2D box, ref bool result)`](VRageMath.Intersects.md)||
|[`double Distance(Vector2D point)`](VRageMath.Distance.md)||
|[`ContainmentType Contains(BoundingBox2D box)`](VRageMath.Contains.md)|Tests whether the BoundingBox2D contains another BoundingBox2D.|
|[`void Contains(ref BoundingBox2D box, ref ContainmentType result)`](VRageMath.Contains.md)||
|[`ContainmentType Contains(Vector2D point)`](VRageMath.Contains.md)|Tests whether the BoundingBox2D contains a point.|
|[`void Contains(ref Vector2D point, ref ContainmentType result)`](VRageMath.Contains.md)||
|[`BoundingBox2D Translate(Vector2D vctTranlsation)`](VRageMath.Translate.md)|Translate|
|[`BoundingBox2D Include(ref Vector2D point)`](VRageMath.Include.md)||
|[`BoundingBox2D GetIncluded(Vector2D point)`](VRageMath.GetIncluded.md)||
|[`BoundingBox2D Include(Vector2D point)`](VRageMath.Include.md)||
|[`BoundingBox2D Include(Vector2D p0, Vector2D p1, Vector2D p2)`](VRageMath.Include.md)||
|[`BoundingBox2D Include(ref Vector2D p0, ref Vector2D p1, ref Vector2D p2)`](VRageMath.Include.md)||
|[`BoundingBox2D Include(ref BoundingBox2D box)`](VRageMath.Include.md)||
|[`BoundingBox2D Include(BoundingBox2D box)`](VRageMath.Include.md)||
|[`BoundingBox2D CreateInvalid()`](VRageMath.CreateInvalid.md)||
|[`double Perimeter()`](VRageMath.Perimeter.md)||
|[`double Area()`](VRageMath.Area.md)||
|[`void Inflate(double size)`](VRageMath.Inflate.md)||
|[`void InflateToMinimum(Vector2D minimumSize)`](VRageMath.InflateToMinimum.md)||
|[`void Scale(Vector2D scale)`](VRageMath.Scale.md)||
