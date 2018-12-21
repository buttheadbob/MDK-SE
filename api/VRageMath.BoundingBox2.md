← [Index](index)
# BoundingBox2 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
<table style="width: 100%">
<tr><td>[`Vector2 Min`](VRageMath.Min)</td><td>The minimum point the BoundingBox2 contains.</td></tr>
<tr><td>[`Vector2 Max`](VRageMath.Max)</td><td>The maximum point the BoundingBox2 contains.</td></tr>
<tr><td>static [`int CornerCount`](VRageMath.CornerCount)</td><td>Specifies the total number of corners (8) in the BoundingBox2.</td></tr>
</table>
### Properties
<table style="width: 100%">
<tr><td>[`Vector2 Center`](VRageMath.Center)</td><td>Calculates center</td></tr>
<tr><td>[`Vector2 HalfExtents`](VRageMath.HalfExtents)</td><td></td></tr>
<tr><td>[`Vector2 Extents`](VRageMath.Extents)</td><td></td></tr>
<tr><td>[`float Width`](VRageMath.Width)</td><td></td></tr>
<tr><td>[`float Height`](VRageMath.Height)</td><td></td></tr>
<tr><td>[`Vector2 Size`](VRageMath.Size)</td><td>Size</td></tr>
</table>
### Methods
<table style="width: 100%">
<tr><td>[`Vector2[] GetCorners()`](VRageMath.GetCorners)</td><td>Gets an array of points that make up the corners of the BoundingBox2.</td></tr>
<tr><td>[`void GetCorners(Vector2[] corners)`](VRageMath.GetCorners)</td><td>Gets the array of points that make up the corners of the BoundingBox2.</td></tr>
<tr><td>[`void GetCornersUnsafe(*Vector2 corners)`](VRageMath.GetCornersUnsafe)</td><td></td></tr>
<tr><td>[`bool Equals(BoundingBox2 other)`](VRageMath.Equals)</td><td>Determines whether two instances of BoundingBox2 are equal.</td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td>Determines whether two instances of BoundingBox2 are equal.</td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td>Gets the hash code for this instance.</td></tr>
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td>Returns a String that represents the current BoundingBox2.</td></tr>
<tr><td>static [`BoundingBox2 CreateMerged(BoundingBox2 original, BoundingBox2 additional)`](VRageMath.CreateMerged)</td><td>Creates the smallest BoundingBox2 that contains the two specified BoundingBox2 instances.</td></tr>
<tr><td>static [`void CreateMerged(ref BoundingBox2 original, ref BoundingBox2 additional, ref BoundingBox2 result)`](VRageMath.CreateMerged)</td><td>Creates the smallest BoundingBox2 that contains the two specified BoundingBox2 instances.</td></tr>
<tr><td>static [`BoundingBox2 CreateFromPoints(IEnumerable<Vector2> points)`](VRageMath.CreateFromPoints)</td><td>Creates the smallest BoundingBox2 that will contain a group of points.</td></tr>
<tr><td>static [`BoundingBox2 CreateFromHalfExtent(Vector2 center, float halfExtent)`](VRageMath.CreateFromHalfExtent)</td><td></td></tr>
<tr><td>static [`BoundingBox2 CreateFromHalfExtent(Vector2 center, Vector2 halfExtent)`](VRageMath.CreateFromHalfExtent)</td><td></td></tr>
<tr><td>[`BoundingBox2 Intersect(BoundingBox2 box)`](VRageMath.Intersect)</td><td>Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)</td></tr>
<tr><td>[`bool Intersects(BoundingBox2 box)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBox2 intersects another BoundingBox2.</td></tr>
<tr><td>[`bool Intersects(ref BoundingBox2 box)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`void Intersects(ref BoundingBox2 box, ref bool result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBox2 intersects another BoundingBox2.</td></tr>
<tr><td>[`float Distance(Vector2 point)`](VRageMath.Distance)</td><td></td></tr>
<tr><td>[`ContainmentType Contains(BoundingBox2 box)`](VRageMath.Contains)</td><td>Tests whether the BoundingBox2 contains another BoundingBox2.</td></tr>
<tr><td>[`void Contains(ref BoundingBox2 box, ref ContainmentType result)`](VRageMath.Contains)</td><td>Tests whether the BoundingBox2 contains a BoundingBox2.</td></tr>
<tr><td>[`ContainmentType Contains(Vector2 point)`](VRageMath.Contains)</td><td>Tests whether the BoundingBox2 contains a point.</td></tr>
<tr><td>[`void Contains(ref Vector2 point, ref ContainmentType result)`](VRageMath.Contains)</td><td>Tests whether the BoundingBox2 contains a point.</td></tr>
<tr><td>[`BoundingBox2 Translate(Vector2 vctTranlsation)`](VRageMath.Translate)</td><td>Translate</td></tr>
<tr><td>[`BoundingBox2 Include(ref Vector2 point)`](VRageMath.Include)</td><td>return expanded aabb (abb include point)</td></tr>
<tr><td>[`BoundingBox2 GetIncluded(Vector2 point)`](VRageMath.GetIncluded)</td><td></td></tr>
<tr><td>[`BoundingBox2 Include(Vector2 point)`](VRageMath.Include)</td><td></td></tr>
<tr><td>[`BoundingBox2 Include(Vector2 p0, Vector2 p1, Vector2 p2)`](VRageMath.Include)</td><td></td></tr>
<tr><td>[`BoundingBox2 Include(ref Vector2 p0, ref Vector2 p1, ref Vector2 p2)`](VRageMath.Include)</td><td></td></tr>
<tr><td>[`BoundingBox2 Include(ref BoundingBox2 box)`](VRageMath.Include)</td><td>return expanded aabb (abb include point)</td></tr>
<tr><td>[`BoundingBox2 Include(BoundingBox2 box)`](VRageMath.Include)</td><td></td></tr>
<tr><td>static [`BoundingBox2 CreateInvalid()`](VRageMath.CreateInvalid)</td><td></td></tr>
<tr><td>[`float Perimeter()`](VRageMath.Perimeter)</td><td></td></tr>
<tr><td>[`float Area()`](VRageMath.Area)</td><td></td></tr>
<tr><td>[`void Inflate(float size)`](VRageMath.Inflate)</td><td></td></tr>
<tr><td>[`void InflateToMinimum(Vector2 minimumSize)`](VRageMath.InflateToMinimum)</td><td></td></tr>
<tr><td>[`void Scale(Vector2 scale)`](VRageMath.Scale)</td><td></td></tr>
</table>
