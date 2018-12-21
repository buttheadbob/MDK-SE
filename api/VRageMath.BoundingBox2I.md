← [Index](index)
# BoundingBox2I Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
<table style="width:100%;display:table">
<tr><td>[`Vector2I Min`](VRageMath.Min)</td><td>The minimum point the BoundingBox2I contains.</td></tr>
<tr><td>[`Vector2I Max`](VRageMath.Max)</td><td>The maximum point the BoundingBox2I contains.</td></tr>
<tr><td>static [`int CornerCount`](VRageMath.CornerCount)</td><td>Specifies the total number of corners (8) in the BoundingBox2I.</td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>[`Vector2I Center`](VRageMath.Center)</td><td>Calculates center</td></tr>
<tr><td>[`Vector2I HalfExtents`](VRageMath.HalfExtents)</td><td></td></tr>
<tr><td>[`Vector2I Extents`](VRageMath.Extents)</td><td></td></tr>
<tr><td>[`float Width`](VRageMath.Width)</td><td></td></tr>
<tr><td>[`float Height`](VRageMath.Height)</td><td></td></tr>
<tr><td>[`Vector2I Size`](VRageMath.Size)</td><td>Size</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>[`Vector2I[] GetCorners()`](VRageMath.GetCorners)</td><td>Gets an array of points that make up the corners of the BoundingBox2I.</td></tr>
<tr><td>[`void GetCorners(Vector2I[] corners)`](VRageMath.GetCorners)</td><td>Gets the array of points that make up the corners of the BoundingBox2I.</td></tr>
<tr><td>[`void GetCornersUnsafe(*Vector2I corners)`](VRageMath.GetCornersUnsafe)</td><td></td></tr>
<tr><td>[`bool Equals(BoundingBox2I other)`](VRageMath.Equals)</td><td>Determines whether two instances of BoundingBox2I are equal.</td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td>Determines whether two instances of BoundingBox2I are equal.</td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td>Gets the hash code for this instance.</td></tr>
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td>Returns a String that represents the current BoundingBox2I.</td></tr>
<tr><td>static [`BoundingBox2I CreateMerged(BoundingBox2I original, BoundingBox2I additional)`](VRageMath.CreateMerged)</td><td>Creates the smallest BoundingBox2I that contains the two specified BoundingBox2I instances.</td></tr>
<tr><td>static [`void CreateMerged(ref BoundingBox2I original, ref BoundingBox2I additional, ref BoundingBox2I result)`](VRageMath.CreateMerged)</td><td>Creates the smallest BoundingBox2I that contains the two specified BoundingBox2I instances.</td></tr>
<tr><td>static [`BoundingBox2I CreateFromPoints(IEnumerable<Vector2I> points)`](VRageMath.CreateFromPoints)</td><td>Creates the smallest BoundingBox2I that will contain a group of points.</td></tr>
<tr><td>static [`BoundingBox2I CreateFromHalfExtent(Vector2I center, int halfExtent)`](VRageMath.CreateFromHalfExtent)</td><td></td></tr>
<tr><td>static [`BoundingBox2I CreateFromHalfExtent(Vector2I center, Vector2I halfExtent)`](VRageMath.CreateFromHalfExtent)</td><td></td></tr>
<tr><td>[`BoundingBox2I Intersect(BoundingBox2I box)`](VRageMath.Intersect)</td><td>Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)</td></tr>
<tr><td>[`bool Intersects(BoundingBox2I box)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBox2I intersects another BoundingBox2I.</td></tr>
<tr><td>[`bool Intersects(ref BoundingBox2I box)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`void Intersects(ref BoundingBox2I box, ref bool result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBox2I intersects another BoundingBox2I.</td></tr>
<tr><td>[`ContainmentType Contains(BoundingBox2I box)`](VRageMath.Contains)</td><td>Tests whether the BoundingBox2I contains another BoundingBox2I.</td></tr>
<tr><td>[`void Contains(ref BoundingBox2I box, ref ContainmentType result)`](VRageMath.Contains)</td><td>Tests whether the BoundingBox2I contains a BoundingBox2I.</td></tr>
<tr><td>[`ContainmentType Contains(Vector2I point)`](VRageMath.Contains)</td><td>Tests whether the BoundingBox2I contains a point.</td></tr>
<tr><td>[`void Contains(ref Vector2I point, ref ContainmentType result)`](VRageMath.Contains)</td><td>Tests whether the BoundingBox2I contains a point.</td></tr>
<tr><td>[`BoundingBox2I Translate(Vector2I vctTranlsation)`](VRageMath.Translate)</td><td>Translate</td></tr>
<tr><td>[`BoundingBox2I Include(ref Vector2I point)`](VRageMath.Include)</td><td>return expanded aabb (abb include point)</td></tr>
<tr><td>[`BoundingBox2I GetIncluded(Vector2I point)`](VRageMath.GetIncluded)</td><td></td></tr>
<tr><td>[`BoundingBox2I Include(Vector2I point)`](VRageMath.Include)</td><td></td></tr>
<tr><td>[`BoundingBox2I Include(Vector2I p0, Vector2I p1, Vector2I p2)`](VRageMath.Include)</td><td></td></tr>
<tr><td>[`BoundingBox2I Include(ref Vector2I p0, ref Vector2I p1, ref Vector2I p2)`](VRageMath.Include)</td><td></td></tr>
<tr><td>[`BoundingBox2I Include(ref BoundingBox2I box)`](VRageMath.Include)</td><td>return expanded aabb (abb include point)</td></tr>
<tr><td>[`BoundingBox2I Include(BoundingBox2I box)`](VRageMath.Include)</td><td></td></tr>
<tr><td>static [`BoundingBox2I CreateInvalid()`](VRageMath.CreateInvalid)</td><td></td></tr>
<tr><td>[`float Perimeter()`](VRageMath.Perimeter)</td><td></td></tr>
<tr><td>[`float Area()`](VRageMath.Area)</td><td></td></tr>
<tr><td>[`void Inflate(int size)`](VRageMath.Inflate)</td><td></td></tr>
<tr><td>[`void InflateToMinimum(Vector2I minimumSize)`](VRageMath.InflateToMinimum)</td><td></td></tr>
<tr><td>[`void Scale(Vector2I scale)`](VRageMath.Scale)</td><td></td></tr>
</table>
