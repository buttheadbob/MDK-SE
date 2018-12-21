← [Index](index)
# BoundingBox2D Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Min"><code>Vector2D Min</code></a>_</td><td>The minimum point the BoundingBox2D contains.</td></tr>
<tr><td>_<a href="VRageMath.Max"><code>Vector2D Max</code></a>_</td><td>The maximum point the BoundingBox2D contains.</td></tr>
<tr><td>static _<a href="VRageMath.CornerCount"><code>int CornerCount</code></a>_</td><td>Specifies the total number of corners (8) in the BoundingBox2D.</td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Center"><code>Vector2D Center</code></a>_</td><td>Calculates center</td></tr>
<tr><td>_<a href="VRageMath.HalfExtents"><code>Vector2D HalfExtents</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Extents"><code>Vector2D Extents</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Width"><code>double Width</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Height"><code>double Height</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Size"><code>Vector2D Size</code></a>_</td><td>Size</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.GetCorners"><code>Vector2D[] GetCorners()</code></a>_</td><td>Gets an array of points that make up the corners of the BoundingBox2D.</td></tr>
<tr><td>_<a href="VRageMath.GetCorners"><code>void GetCorners(Vector2D[] corners)</code></a>_</td><td>Gets the array of points that make up the corners of the BoundingBox2D.</td></tr>
<tr><td>_<a href="VRageMath.GetCornersUnsafe"><code>void GetCornersUnsafe(*Vector2D corners)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(BoundingBox2D other)</code></a>_</td><td>Determines whether two instances of BoundingBox2D are equal.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Object obj)</code></a>_</td><td>Determines whether two instances of BoundingBox2D are equal.</td></tr>
<tr><td>_<a href="VRageMath.GetHashCode"><code>int GetHashCode()</code></a>_</td><td>Gets the hash code for this instance.</td></tr>
<tr><td>_<a href="VRageMath.ToString"><code>string ToString()</code></a>_</td><td>Returns a String that represents the current BoundingBox2D.</td></tr>
<tr><td>static _<a href="VRageMath.CreateMerged"><code>BoundingBox2D CreateMerged(BoundingBox2D original, BoundingBox2D additional)</code></a>_</td><td>Creates the smallest BoundingBox2D that contains the two specified BoundingBox2D instances.</td></tr>
<tr><td>static _<a href="VRageMath.CreateMerged"><code>void CreateMerged(ref BoundingBox2D original, ref BoundingBox2D additional, ref BoundingBox2D result)</code></a>_</td><td>Creates the smallest BoundingBox2D that contains the two specified BoundingBox2D instances.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromPoints"><code>BoundingBox2D CreateFromPoints(IEnumerable<Vector2D> points)</code></a>_</td><td>Creates the smallest BoundingBox2D that will contain a group of points.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromHalfExtent"><code>BoundingBox2D CreateFromHalfExtent(Vector2D center, double halfExtent)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CreateFromHalfExtent"><code>BoundingBox2D CreateFromHalfExtent(Vector2D center, Vector2D halfExtent)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersect"><code>BoundingBox2D Intersect(BoundingBox2D box)</code></a>_</td><td>Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(BoundingBox2D box)</code></a>_</td><td>Checks whether the current BoundingBox2D intersects another BoundingBox2D.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(ref BoundingBox2D box)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref BoundingBox2D box, ref bool result)</code></a>_</td><td>Checks whether the current BoundingBox2D intersects another BoundingBox2D.</td></tr>
<tr><td>_<a href="VRageMath.Distance"><code>double Distance(Vector2D point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(BoundingBox2D box)</code></a>_</td><td>Tests whether the BoundingBox2D contains another BoundingBox2D.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref BoundingBox2D box, ref ContainmentType result)</code></a>_</td><td>Tests whether the BoundingBox2D contains a BoundingBox2D.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(Vector2D point)</code></a>_</td><td>Tests whether the BoundingBox2D contains a point.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref Vector2D point, ref ContainmentType result)</code></a>_</td><td>Tests whether the BoundingBox2D contains a point.</td></tr>
<tr><td>_<a href="VRageMath.Translate"><code>BoundingBox2D Translate(Vector2D vctTranlsation)</code></a>_</td><td>Translate</td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox2D Include(ref Vector2D point)</code></a>_</td><td>return expanded aabb (abb include point)</td></tr>
<tr><td>_<a href="VRageMath.GetIncluded"><code>BoundingBox2D GetIncluded(Vector2D point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox2D Include(Vector2D point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox2D Include(Vector2D p0, Vector2D p1, Vector2D p2)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox2D Include(ref Vector2D p0, ref Vector2D p1, ref Vector2D p2)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox2D Include(ref BoundingBox2D box)</code></a>_</td><td>return expanded aabb (abb include point)</td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox2D Include(BoundingBox2D box)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CreateInvalid"><code>BoundingBox2D CreateInvalid()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Perimeter"><code>double Perimeter()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Area"><code>double Area()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Inflate"><code>void Inflate(double size)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.InflateToMinimum"><code>void InflateToMinimum(Vector2D minimumSize)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Scale"><code>void Scale(Vector2D scale)</code></a>_</td><td></td></tr>
</table>
