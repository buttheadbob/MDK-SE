← [Index](index)
# BoundingBox2D Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
<table style="width: 100%">
<tr><td>[`Vector2D Min`](VRageMath.Min)</td><td>The minimum point the BoundingBox2D contains.</td></tr>
<tr><td>[`Vector2D Max`](VRageMath.Max)</td><td>The maximum point the BoundingBox2D contains.</td></tr>
<tr><td>static [`int CornerCount`](VRageMath.CornerCount)</td><td>Specifies the total number of corners (8) in the BoundingBox2D.</td></tr>
</table>
### Properties
<table style="width: 100%">
<tr><td>[`Vector2D Center`](VRageMath.Center)</td><td>Calculates center</td></tr>
<tr><td>[`Vector2D HalfExtents`](VRageMath.HalfExtents)</td><td></td></tr>
<tr><td>[`Vector2D Extents`](VRageMath.Extents)</td><td></td></tr>
<tr><td>[`double Width`](VRageMath.Width)</td><td></td></tr>
<tr><td>[`double Height`](VRageMath.Height)</td><td></td></tr>
<tr><td>[`Vector2D Size`](VRageMath.Size)</td><td>Size</td></tr>
</table>
### Methods
<table style="width: 100%">
<tr><td>[`Vector2D[] GetCorners()`](VRageMath.GetCorners)</td><td>Gets an array of points that make up the corners of the BoundingBox2D.</td></tr>
<tr><td>[`void GetCorners(Vector2D[] corners)`](VRageMath.GetCorners)</td><td>Gets the array of points that make up the corners of the BoundingBox2D.</td></tr>
<tr><td>[`void GetCornersUnsafe(*Vector2D corners)`](VRageMath.GetCornersUnsafe)</td><td></td></tr>
<tr><td>[`bool Equals(BoundingBox2D other)`](VRageMath.Equals)</td><td>Determines whether two instances of BoundingBox2D are equal.</td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td>Determines whether two instances of BoundingBox2D are equal.</td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td>Gets the hash code for this instance.</td></tr>
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td>Returns a String that represents the current BoundingBox2D.</td></tr>
<tr><td>static [`BoundingBox2D CreateMerged(BoundingBox2D original, BoundingBox2D additional)`](VRageMath.CreateMerged)</td><td>Creates the smallest BoundingBox2D that contains the two specified BoundingBox2D instances.</td></tr>
<tr><td>static [`void CreateMerged(ref BoundingBox2D original, ref BoundingBox2D additional, ref BoundingBox2D result)`](VRageMath.CreateMerged)</td><td>Creates the smallest BoundingBox2D that contains the two specified BoundingBox2D instances.</td></tr>
<tr><td>static [`BoundingBox2D CreateFromPoints(IEnumerable<Vector2D> points)`](VRageMath.CreateFromPoints)</td><td>Creates the smallest BoundingBox2D that will contain a group of points.</td></tr>
<tr><td>static [`BoundingBox2D CreateFromHalfExtent(Vector2D center, double halfExtent)`](VRageMath.CreateFromHalfExtent)</td><td></td></tr>
<tr><td>static [`BoundingBox2D CreateFromHalfExtent(Vector2D center, Vector2D halfExtent)`](VRageMath.CreateFromHalfExtent)</td><td></td></tr>
<tr><td>[`BoundingBox2D Intersect(BoundingBox2D box)`](VRageMath.Intersect)</td><td>Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)</td></tr>
<tr><td>[`bool Intersects(BoundingBox2D box)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBox2D intersects another BoundingBox2D.</td></tr>
<tr><td>[`bool Intersects(ref BoundingBox2D box)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`void Intersects(ref BoundingBox2D box, ref bool result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBox2D intersects another BoundingBox2D.</td></tr>
<tr><td>[`double Distance(Vector2D point)`](VRageMath.Distance)</td><td></td></tr>
<tr><td>[`ContainmentType Contains(BoundingBox2D box)`](VRageMath.Contains)</td><td>Tests whether the BoundingBox2D contains another BoundingBox2D.</td></tr>
<tr><td>[`void Contains(ref BoundingBox2D box, ref ContainmentType result)`](VRageMath.Contains)</td><td>Tests whether the BoundingBox2D contains a BoundingBox2D.</td></tr>
<tr><td>[`ContainmentType Contains(Vector2D point)`](VRageMath.Contains)</td><td>Tests whether the BoundingBox2D contains a point.</td></tr>
<tr><td>[`void Contains(ref Vector2D point, ref ContainmentType result)`](VRageMath.Contains)</td><td>Tests whether the BoundingBox2D contains a point.</td></tr>
<tr><td>[`BoundingBox2D Translate(Vector2D vctTranlsation)`](VRageMath.Translate)</td><td>Translate</td></tr>
<tr><td>[`BoundingBox2D Include(ref Vector2D point)`](VRageMath.Include)</td><td>return expanded aabb (abb include point)</td></tr>
<tr><td>[`BoundingBox2D GetIncluded(Vector2D point)`](VRageMath.GetIncluded)</td><td></td></tr>
<tr><td>[`BoundingBox2D Include(Vector2D point)`](VRageMath.Include)</td><td></td></tr>
<tr><td>[`BoundingBox2D Include(Vector2D p0, Vector2D p1, Vector2D p2)`](VRageMath.Include)</td><td></td></tr>
<tr><td>[`BoundingBox2D Include(ref Vector2D p0, ref Vector2D p1, ref Vector2D p2)`](VRageMath.Include)</td><td></td></tr>
<tr><td>[`BoundingBox2D Include(ref BoundingBox2D box)`](VRageMath.Include)</td><td>return expanded aabb (abb include point)</td></tr>
<tr><td>[`BoundingBox2D Include(BoundingBox2D box)`](VRageMath.Include)</td><td></td></tr>
<tr><td>static [`BoundingBox2D CreateInvalid()`](VRageMath.CreateInvalid)</td><td></td></tr>
<tr><td>[`double Perimeter()`](VRageMath.Perimeter)</td><td></td></tr>
<tr><td>[`double Area()`](VRageMath.Area)</td><td></td></tr>
<tr><td>[`void Inflate(double size)`](VRageMath.Inflate)</td><td></td></tr>
<tr><td>[`void InflateToMinimum(Vector2D minimumSize)`](VRageMath.InflateToMinimum)</td><td></td></tr>
<tr><td>[`void Scale(Vector2D scale)`](VRageMath.Scale)</td><td></td></tr>
</table>
