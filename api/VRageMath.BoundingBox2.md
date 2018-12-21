← [Index](index)
# BoundingBox2 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Min"><code>Vector2 Min</code></a>_</td><td>The minimum point the BoundingBox2 contains.</td></tr>
<tr><td>_<a href="VRageMath.Max"><code>Vector2 Max</code></a>_</td><td>The maximum point the BoundingBox2 contains.</td></tr>
<tr><td>static _<a href="VRageMath.CornerCount"><code>int CornerCount</code></a>_</td><td>Specifies the total number of corners (8) in the BoundingBox2.</td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Center"><code>Vector2 Center</code></a>_</td><td>Calculates center</td></tr>
<tr><td>_<a href="VRageMath.HalfExtents"><code>Vector2 HalfExtents</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Extents"><code>Vector2 Extents</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Width"><code>float Width</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Height"><code>float Height</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Size"><code>Vector2 Size</code></a>_</td><td>Size</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.GetCorners"><code>Vector2[] GetCorners()</code></a>_</td><td>Gets an array of points that make up the corners of the BoundingBox2.</td></tr>
<tr><td>_<a href="VRageMath.GetCorners"><code>void GetCorners(Vector2[] corners)</code></a>_</td><td>Gets the array of points that make up the corners of the BoundingBox2.</td></tr>
<tr><td>_<a href="VRageMath.GetCornersUnsafe"><code>void GetCornersUnsafe(*Vector2 corners)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(BoundingBox2 other)</code></a>_</td><td>Determines whether two instances of BoundingBox2 are equal.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Object obj)</code></a>_</td><td>Determines whether two instances of BoundingBox2 are equal.</td></tr>
<tr><td>_<a href="VRageMath.GetHashCode"><code>int GetHashCode()</code></a>_</td><td>Gets the hash code for this instance.</td></tr>
<tr><td>_<a href="VRageMath.ToString"><code>string ToString()</code></a>_</td><td>Returns a String that represents the current BoundingBox2.</td></tr>
<tr><td>static _<a href="VRageMath.CreateMerged"><code>BoundingBox2 CreateMerged(BoundingBox2 original, BoundingBox2 additional)</code></a>_</td><td>Creates the smallest BoundingBox2 that contains the two specified BoundingBox2 instances.</td></tr>
<tr><td>static _<a href="VRageMath.CreateMerged"><code>void CreateMerged(ref BoundingBox2 original, ref BoundingBox2 additional, ref BoundingBox2 result)</code></a>_</td><td>Creates the smallest BoundingBox2 that contains the two specified BoundingBox2 instances.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromPoints"><code>BoundingBox2 CreateFromPoints(IEnumerable<Vector2> points)</code></a>_</td><td>Creates the smallest BoundingBox2 that will contain a group of points.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromHalfExtent"><code>BoundingBox2 CreateFromHalfExtent(Vector2 center, float halfExtent)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CreateFromHalfExtent"><code>BoundingBox2 CreateFromHalfExtent(Vector2 center, Vector2 halfExtent)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersect"><code>BoundingBox2 Intersect(BoundingBox2 box)</code></a>_</td><td>Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(BoundingBox2 box)</code></a>_</td><td>Checks whether the current BoundingBox2 intersects another BoundingBox2.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(ref BoundingBox2 box)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref BoundingBox2 box, ref bool result)</code></a>_</td><td>Checks whether the current BoundingBox2 intersects another BoundingBox2.</td></tr>
<tr><td>_<a href="VRageMath.Distance"><code>float Distance(Vector2 point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(BoundingBox2 box)</code></a>_</td><td>Tests whether the BoundingBox2 contains another BoundingBox2.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref BoundingBox2 box, ref ContainmentType result)</code></a>_</td><td>Tests whether the BoundingBox2 contains a BoundingBox2.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(Vector2 point)</code></a>_</td><td>Tests whether the BoundingBox2 contains a point.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref Vector2 point, ref ContainmentType result)</code></a>_</td><td>Tests whether the BoundingBox2 contains a point.</td></tr>
<tr><td>_<a href="VRageMath.Translate"><code>BoundingBox2 Translate(Vector2 vctTranlsation)</code></a>_</td><td>Translate</td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox2 Include(ref Vector2 point)</code></a>_</td><td>return expanded aabb (abb include point)</td></tr>
<tr><td>_<a href="VRageMath.GetIncluded"><code>BoundingBox2 GetIncluded(Vector2 point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox2 Include(Vector2 point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox2 Include(Vector2 p0, Vector2 p1, Vector2 p2)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox2 Include(ref Vector2 p0, ref Vector2 p1, ref Vector2 p2)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox2 Include(ref BoundingBox2 box)</code></a>_</td><td>return expanded aabb (abb include point)</td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox2 Include(BoundingBox2 box)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CreateInvalid"><code>BoundingBox2 CreateInvalid()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Perimeter"><code>float Perimeter()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Area"><code>float Area()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Inflate"><code>void Inflate(float size)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.InflateToMinimum"><code>void InflateToMinimum(Vector2 minimumSize)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Scale"><code>void Scale(Vector2 scale)</code></a>_</td><td></td></tr>
</table>
