← [Index](index.md)
# BoundingBox2D Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`Vector2D Min`](VRageMath.Min)||
|[`Vector2D Max`](VRageMath.Max)||
|[`int CornerCount`](VRageMath.CornerCount)||
### Properties
|Member|Description|
|---|---|
|[`Vector2D Center`](VRageMath.Center)||
|[`Vector2D HalfExtents`](VRageMath.HalfExtents)||
|[`Vector2D Extents`](VRageMath.Extents)||
|[`double Width`](VRageMath.Width)||
|[`double Height`](VRageMath.Height)||
|[`Vector2D Size`](VRageMath.Size)||
### Methods
|Member|Description|
|---|---|
|[`Vector2D[] GetCorners()`](VRageMath.GetCorners)||
|[`void GetCorners(Vector2D[] corners)`](VRageMath.GetCorners)|Gets the array of points that make up the corners of the BoundingBox2D.|
|[`void GetCornersUnsafe(*Vector2D corners)`](VRageMath.GetCornersUnsafe)||
|[`bool Equals(BoundingBox2D other)`](VRageMath.Equals)|Determines whether two instances of BoundingBox2D are equal.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Determines whether two instances of BoundingBox2D are equal.|
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`string ToString()`](VRageMath.ToString)||
|[`BoundingBox2D CreateMerged(BoundingBox2D original, BoundingBox2D additional)`](VRageMath.CreateMerged)||
|[`void CreateMerged(ref BoundingBox2D original, ref BoundingBox2D additional, ref BoundingBox2D result)`](VRageMath.CreateMerged)||
|[`BoundingBox2D CreateFromPoints(IEnumerable<Vector2D> points)`](VRageMath.CreateFromPoints)|Creates the smallest BoundingBox2D that will contain a group of points.|
|[`BoundingBox2D CreateFromHalfExtent(Vector2D center, double halfExtent)`](VRageMath.CreateFromHalfExtent)||
|[`BoundingBox2D CreateFromHalfExtent(Vector2D center, Vector2D halfExtent)`](VRageMath.CreateFromHalfExtent)||
|[`BoundingBox2D Intersect(BoundingBox2D box)`](VRageMath.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`bool Intersects(BoundingBox2D box)`](VRageMath.Intersects)|Checks whether the current BoundingBox2D intersects another BoundingBox2D.|
|[`bool Intersects(ref BoundingBox2D box)`](VRageMath.Intersects)||
|[`void Intersects(ref BoundingBox2D box, ref bool result)`](VRageMath.Intersects)||
|[`double Distance(Vector2D point)`](VRageMath.Distance)||
|[`ContainmentType Contains(BoundingBox2D box)`](VRageMath.Contains)|Tests whether the BoundingBox2D contains another BoundingBox2D.|
|[`void Contains(ref BoundingBox2D box, ref ContainmentType result)`](VRageMath.Contains)||
|[`ContainmentType Contains(Vector2D point)`](VRageMath.Contains)|Tests whether the BoundingBox2D contains a point.|
|[`void Contains(ref Vector2D point, ref ContainmentType result)`](VRageMath.Contains)||
|[`BoundingBox2D Translate(Vector2D vctTranlsation)`](VRageMath.Translate)|Translate|
|[`BoundingBox2D Include(ref Vector2D point)`](VRageMath.Include)||
|[`BoundingBox2D GetIncluded(Vector2D point)`](VRageMath.GetIncluded)||
|[`BoundingBox2D Include(Vector2D point)`](VRageMath.Include)||
|[`BoundingBox2D Include(Vector2D p0, Vector2D p1, Vector2D p2)`](VRageMath.Include)||
|[`BoundingBox2D Include(ref Vector2D p0, ref Vector2D p1, ref Vector2D p2)`](VRageMath.Include)||
|[`BoundingBox2D Include(ref BoundingBox2D box)`](VRageMath.Include)||
|[`BoundingBox2D Include(BoundingBox2D box)`](VRageMath.Include)||
|[`BoundingBox2D CreateInvalid()`](VRageMath.CreateInvalid)||
|[`double Perimeter()`](VRageMath.Perimeter)||
|[`double Area()`](VRageMath.Area)||
|[`void Inflate(double size)`](VRageMath.Inflate)||
|[`void InflateToMinimum(Vector2D minimumSize)`](VRageMath.InflateToMinimum)||
|[`void Scale(Vector2D scale)`](VRageMath.Scale)||
