← [Index](index)
# BoundingBox2I Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Min"><code>Vector2I Min</code></a>_</td><td>The minimum point the BoundingBox2I contains.</td></tr>
<tr><td>_<a href="VRageMath.Max"><code>Vector2I Max</code></a>_</td><td>The maximum point the BoundingBox2I contains.</td></tr>
<tr><td>static _<a href="VRageMath.CornerCount"><code>int CornerCount</code></a>_</td><td>Specifies the total number of corners (8) in the BoundingBox2I.</td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Center"><code>Vector2I Center</code></a>_</td><td>Calculates center</td></tr>
<tr><td>_<a href="VRageMath.HalfExtents"><code>Vector2I HalfExtents</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Extents"><code>Vector2I Extents</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Width"><code>float Width</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Height"><code>float Height</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Size"><code>Vector2I Size</code></a>_</td><td>Size</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.GetCorners"><code>Vector2I[] GetCorners()</code></a>_</td><td>Gets an array of points that make up the corners of the BoundingBox2I.</td></tr>
<tr><td>_<a href="VRageMath.GetCorners"><code>void GetCorners(Vector2I[] corners)</code></a>_</td><td>Gets the array of points that make up the corners of the BoundingBox2I.</td></tr>
<tr><td>_<a href="VRageMath.GetCornersUnsafe"><code>void GetCornersUnsafe(*Vector2I corners)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(BoundingBox2I other)</code></a>_</td><td>Determines whether two instances of BoundingBox2I are equal.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Object obj)</code></a>_</td><td>Determines whether two instances of BoundingBox2I are equal.</td></tr>
<tr><td>_<a href="VRageMath.GetHashCode"><code>int GetHashCode()</code></a>_</td><td>Gets the hash code for this instance.</td></tr>
<tr><td>_<a href="VRageMath.ToString"><code>string ToString()</code></a>_</td><td>Returns a String that represents the current BoundingBox2I.</td></tr>
<tr><td>static _<a href="VRageMath.CreateMerged"><code>BoundingBox2I CreateMerged(BoundingBox2I original, BoundingBox2I additional)</code></a>_</td><td>Creates the smallest BoundingBox2I that contains the two specified BoundingBox2I instances.</td></tr>
<tr><td>static _<a href="VRageMath.CreateMerged"><code>void CreateMerged(ref BoundingBox2I original, ref BoundingBox2I additional, ref BoundingBox2I result)</code></a>_</td><td>Creates the smallest BoundingBox2I that contains the two specified BoundingBox2I instances.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromPoints"><code>BoundingBox2I CreateFromPoints(IEnumerable<Vector2I> points)</code></a>_</td><td>Creates the smallest BoundingBox2I that will contain a group of points.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromHalfExtent"><code>BoundingBox2I CreateFromHalfExtent(Vector2I center, int halfExtent)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CreateFromHalfExtent"><code>BoundingBox2I CreateFromHalfExtent(Vector2I center, Vector2I halfExtent)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersect"><code>BoundingBox2I Intersect(BoundingBox2I box)</code></a>_</td><td>Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(BoundingBox2I box)</code></a>_</td><td>Checks whether the current BoundingBox2I intersects another BoundingBox2I.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(ref BoundingBox2I box)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref BoundingBox2I box, ref bool result)</code></a>_</td><td>Checks whether the current BoundingBox2I intersects another BoundingBox2I.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(BoundingBox2I box)</code></a>_</td><td>Tests whether the BoundingBox2I contains another BoundingBox2I.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref BoundingBox2I box, ref ContainmentType result)</code></a>_</td><td>Tests whether the BoundingBox2I contains a BoundingBox2I.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(Vector2I point)</code></a>_</td><td>Tests whether the BoundingBox2I contains a point.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref Vector2I point, ref ContainmentType result)</code></a>_</td><td>Tests whether the BoundingBox2I contains a point.</td></tr>
<tr><td>_<a href="VRageMath.Translate"><code>BoundingBox2I Translate(Vector2I vctTranlsation)</code></a>_</td><td>Translate</td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox2I Include(ref Vector2I point)</code></a>_</td><td>return expanded aabb (abb include point)</td></tr>
<tr><td>_<a href="VRageMath.GetIncluded"><code>BoundingBox2I GetIncluded(Vector2I point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox2I Include(Vector2I point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox2I Include(Vector2I p0, Vector2I p1, Vector2I p2)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox2I Include(ref Vector2I p0, ref Vector2I p1, ref Vector2I p2)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox2I Include(ref BoundingBox2I box)</code></a>_</td><td>return expanded aabb (abb include point)</td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox2I Include(BoundingBox2I box)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CreateInvalid"><code>BoundingBox2I CreateInvalid()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Perimeter"><code>float Perimeter()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Area"><code>float Area()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Inflate"><code>void Inflate(int size)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.InflateToMinimum"><code>void InflateToMinimum(Vector2I minimumSize)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Scale"><code>void Scale(Vector2I scale)</code></a>_</td><td></td></tr>
</table>
