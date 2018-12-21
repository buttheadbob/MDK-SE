← [Index](index)
# BoundingBoxI Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Min"><code>Vector3I Min</code></a>_</td><td>The minimum point the BoundingBoxI contains.</td></tr>
<tr><td>_<a href="VRageMath.Max"><code>Vector3I Max</code></a>_</td><td>The maximum point the BoundingBoxI contains.</td></tr>
<tr><td>static _<a href="VRageMath.CornerCount"><code>int CornerCount</code></a>_</td><td>Specifies the total number of corners (8) in the BoundingBoxI.</td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Center"><code>Vector3I Center</code></a>_</td><td>Calculates center</td></tr>
<tr><td>_<a href="VRageMath.HalfExtents"><code>Vector3I HalfExtents</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Size"><code>Vector3I Size</code></a>_</td><td>Size</td></tr>
<tr><td>_<a href="VRageMath.Perimeter"><code>float Perimeter</code></a>_</td><td>return perimeter of edges</td></tr>
<tr><td>_<a href="VRageMath.IsValid"><code>bool IsValid</code></a>_</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.GetCorners"><code>Vector3I[] GetCorners()</code></a>_</td><td>Gets an array of points that make up the corners of the BoundingBoxI.</td></tr>
<tr><td>_<a href="VRageMath.GetCorners"><code>void GetCorners(Vector3I[] corners)</code></a>_</td><td>Gets the array of points that make up the corners of the BoundingBoxI.</td></tr>
<tr><td>_<a href="VRageMath.GetCornersUnsafe"><code>void GetCornersUnsafe(*Vector3I corners)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(BoundingBoxI other)</code></a>_</td><td>Determines whether two instances of BoundingBoxI are equal.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Object obj)</code></a>_</td><td>Determines whether two instances of BoundingBoxI are equal.</td></tr>
<tr><td>_<a href="VRageMath.GetHashCode"><code>int GetHashCode()</code></a>_</td><td>Gets the hash code for this instance.</td></tr>
<tr><td>_<a href="VRageMath.ToString"><code>string ToString()</code></a>_</td><td>Returns a String that represents the current BoundingBoxI.</td></tr>
<tr><td>static _<a href="VRageMath.CreateMerged"><code>BoundingBoxI CreateMerged(BoundingBoxI original, BoundingBoxI additional)</code></a>_</td><td>Creates the smallest BoundingBoxI that contains the two specified BoundingBoxI instances.</td></tr>
<tr><td>static _<a href="VRageMath.CreateMerged"><code>void CreateMerged(ref BoundingBoxI original, ref BoundingBoxI additional, ref BoundingBoxI result)</code></a>_</td><td>Creates the smallest BoundingBoxI that contains the two specified BoundingBoxI instances.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromSphere"><code>BoundingBoxI CreateFromSphere(BoundingSphere sphere)</code></a>_</td><td>Creates the smallest BoundingBoxI that will contain the specified BoundingSphere.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromSphere"><code>void CreateFromSphere(ref BoundingSphere sphere, ref BoundingBoxI result)</code></a>_</td><td>Creates the smallest BoundingBoxI that will contain the specified BoundingSphere.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromPoints"><code>BoundingBoxI CreateFromPoints(IEnumerable<Vector3I> points)</code></a>_</td><td>Creates the smallest BoundingBoxI that will contain a group of points.</td></tr>
<tr><td>_<a href="VRageMath.IntersectWith"><code>void IntersectWith(ref BoundingBoxI box)</code></a>_</td><td>Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)</td></tr>
<tr><td>_<a href="VRageMath.Intersect"><code>BoundingBoxI Intersect(BoundingBoxI box)</code></a>_</td><td>Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(BoundingBoxI box)</code></a>_</td><td>Checks whether the current BoundingBoxI intersects another BoundingBoxI.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(ref BoundingBoxI box)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref BoundingBoxI box, ref bool result)</code></a>_</td><td>Checks whether the current BoundingBoxI intersects another BoundingBoxI.</td></tr>
<tr><td>_<a href="VRageMath.IntersectsTriangle"><code>bool IntersectsTriangle(Vector3I v0, Vector3I v1, Vector3I v2)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.IntersectsTriangle"><code>bool IntersectsTriangle(ref Vector3I v0, ref Vector3I v1, ref Vector3I v2)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>PlaneIntersectionType Intersects(Plane plane)</code></a>_</td><td>Checks whether the current BoundingBoxI intersects a Plane.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref Plane plane, ref PlaneIntersectionType result)</code></a>_</td><td>Checks whether the current BoundingBoxI intersects a Plane.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(Line line, ref float distance)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>Nullable<float> Intersects(Ray ray)</code></a>_</td><td>Checks whether the current BoundingBoxI intersects a Ray.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref Ray ray, ref Nullable<float> result)</code></a>_</td><td>Checks whether the current BoundingBoxI intersects a Ray.</td></tr>
<tr><td>_<a href="VRageMath.Distance"><code>float Distance(Vector3I point)</code></a>_</td><td>Checks whether the current BoundingBoxI intersects a BoundingSphere.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(BoundingBoxI box)</code></a>_</td><td>Tests whether the BoundingBoxI contains another BoundingBoxI.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref BoundingBoxI box, ref ContainmentType result)</code></a>_</td><td>Tests whether the BoundingBoxI contains a BoundingBoxI.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(Vector3I point)</code></a>_</td><td>Tests whether the BoundingBoxI contains a point.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(Vector3 point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref Vector3I point, ref ContainmentType result)</code></a>_</td><td>Tests whether the BoundingBoxI contains a point.</td></tr>
<tr><td>_<a href="VRageMath.Translate"><code>BoundingBoxI Translate(Vector3I vctTranlsation)</code></a>_</td><td>Translate</td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBoxI Include(ref Vector3I point)</code></a>_</td><td>return expanded aabb (abb include point)</td></tr>
<tr><td>_<a href="VRageMath.GetIncluded"><code>BoundingBoxI GetIncluded(Vector3I point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBoxI Include(Vector3I point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBoxI Include(Vector3I p0, Vector3I p1, Vector3I p2)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBoxI Include(ref Vector3I p0, ref Vector3I p1, ref Vector3I p2)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBoxI Include(ref BoundingBoxI box)</code></a>_</td><td>return expanded aabb (abb include point)</td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBoxI Include(BoundingBoxI box)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CreateInvalid"><code>BoundingBoxI CreateInvalid()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.SurfaceArea"><code>float SurfaceArea()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Volume"><code>float Volume()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Inflate"><code>void Inflate(int size)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.InflateToMinimum"><code>void InflateToMinimum(Vector3I minimumSize)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IterateDifference"><code>IEnumerable<Vector3I> IterateDifference(BoundingBoxI left, BoundingBoxI right)</code></a>_</td><td>Iterate every cell contained in {left} - {right}, where we interpret {box} as the set of all distinct Vector3I points inside a 'box'. Containment is taken in a typical inclusive start, exclusive end fashion.</td></tr>
<tr><td>static _<a href="VRageMath.EnumeratePoints"><code>IEnumerable<Vector3I> EnumeratePoints(BoundingBoxI rangeInclusive)</code></a>_</td><td>Enumerate all values in a integer interval (a cuboid). This method is an allocating version of the Vector3I_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.</td></tr>
</table>
