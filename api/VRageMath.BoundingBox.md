← [Index](index)
# BoundingBox Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Min"><code>Vector3 Min</code></a>_</td><td>The minimum point the BoundingBox contains.</td></tr>
<tr><td>_<a href="VRageMath.Max"><code>Vector3 Max</code></a>_</td><td>The maximum point the BoundingBox contains.</td></tr>
<tr><td>static _<a href="VRageMath.Comparer"><code>ComparerType Comparer</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CornerCount"><code>int CornerCount</code></a>_</td><td>Specifies the total number of corners (8) in the BoundingBox.</td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Corners"><code>BoxCornerEnumerator Corners</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Center"><code>Vector3 Center</code></a>_</td><td>Calculates center</td></tr>
<tr><td>_<a href="VRageMath.HalfExtents"><code>Vector3 HalfExtents</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Extents"><code>Vector3 Extents</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Width"><code>float Width</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Height"><code>float Height</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Depth"><code>float Depth</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Size"><code>Vector3 Size</code></a>_</td><td>Size</td></tr>
<tr><td>_<a href="VRageMath.Matrix"><code>Matrix Matrix</code></a>_</td><td>Matrix of AABB, respection center and size</td></tr>
<tr><td>_<a href="VRageMath.Perimeter"><code>float Perimeter</code></a>_</td><td>return perimeter of edges</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.GetCorners"><code>Vector3[] GetCorners()</code></a>_</td><td>Gets an array of points that make up the corners of the BoundingBox. ALLOCATION!</td></tr>
<tr><td>_<a href="VRageMath.GetCorners"><code>void GetCorners(Vector3[] corners)</code></a>_</td><td>Gets the array of points that make up the corners of the BoundingBox.</td></tr>
<tr><td>_<a href="VRageMath.GetCornersUnsafe"><code>void GetCornersUnsafe(*Vector3 corners)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(BoundingBox other)</code></a>_</td><td>Determines whether two instances of BoundingBox are equal.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Object obj)</code></a>_</td><td>Determines whether two instances of BoundingBox are equal.</td></tr>
<tr><td>_<a href="VRageMath.GetHashCode"><code>int GetHashCode()</code></a>_</td><td>Gets the hash code for this instance.</td></tr>
<tr><td>_<a href="VRageMath.ToString"><code>string ToString()</code></a>_</td><td>Returns a String that represents the current BoundingBox.</td></tr>
<tr><td>static _<a href="VRageMath.CreateMerged"><code>BoundingBox CreateMerged(BoundingBox original, BoundingBox additional)</code></a>_</td><td>Creates the smallest BoundingBox that contains the two specified BoundingBox instances.</td></tr>
<tr><td>static _<a href="VRageMath.CreateMerged"><code>void CreateMerged(ref BoundingBox original, ref BoundingBox additional, ref BoundingBox result)</code></a>_</td><td>Creates the smallest BoundingBox that contains the two specified BoundingBox instances.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromSphere"><code>BoundingBox CreateFromSphere(BoundingSphere sphere)</code></a>_</td><td>Creates the smallest BoundingBox that will contain the specified BoundingSphere.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromSphere"><code>void CreateFromSphere(ref BoundingSphere sphere, ref BoundingBox result)</code></a>_</td><td>Creates the smallest BoundingBox that will contain the specified BoundingSphere.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromPoints"><code>BoundingBox CreateFromPoints(IEnumerable<Vector3> points)</code></a>_</td><td>Creates the smallest BoundingBox that will contain a group of points.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromHalfExtent"><code>BoundingBox CreateFromHalfExtent(Vector3 center, float halfExtent)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CreateFromHalfExtent"><code>BoundingBox CreateFromHalfExtent(Vector3 center, Vector3 halfExtent)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersect"><code>BoundingBox Intersect(BoundingBox box)</code></a>_</td><td>Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(BoundingBox box)</code></a>_</td><td>Checks whether the current BoundingBox intersects another BoundingBox.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(ref BoundingBox box)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref BoundingBox box, ref bool result)</code></a>_</td><td>Checks whether the current BoundingBox intersects another BoundingBox.</td></tr>
<tr><td>_<a href="VRageMath.IntersectsTriangle"><code>bool IntersectsTriangle(Vector3 v0, Vector3 v1, Vector3 v2)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.IntersectsTriangle"><code>bool IntersectsTriangle(ref Vector3 v0, ref Vector3 v1, ref Vector3 v2)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(BoundingFrustum frustum)</code></a>_</td><td>Checks whether the current BoundingBox intersects a BoundingFrustum.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>PlaneIntersectionType Intersects(Plane plane)</code></a>_</td><td>Checks whether the current BoundingBox intersects a Plane.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref Plane plane, ref PlaneIntersectionType result)</code></a>_</td><td>Checks whether the current BoundingBox intersects a Plane.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(Line line, ref float distance)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>Nullable<float> Intersects(Ray ray)</code></a>_</td><td>Checks whether the current BoundingBox intersects a Ray.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref Ray ray, ref Nullable<float> result)</code></a>_</td><td>Checks whether the current BoundingBox intersects a Ray.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(BoundingSphere sphere)</code></a>_</td><td>Checks whether the current BoundingBox intersects a BoundingSphere.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref BoundingSphere sphere, ref bool result)</code></a>_</td><td>Checks whether the current BoundingBox intersects a BoundingSphere.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(ref BoundingSphere sphere)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(ref BoundingSphereD sphere)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Distance"><code>float Distance(Vector3 point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.DistanceSquared"><code>float DistanceSquared(Vector3 point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(BoundingBox box)</code></a>_</td><td>Tests whether the BoundingBox contains another BoundingBox.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref BoundingBox box, ref ContainmentType result)</code></a>_</td><td>Tests whether the BoundingBox contains a BoundingBox.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(BoundingFrustum frustum)</code></a>_</td><td>Tests whether the BoundingBox contains a BoundingFrustum.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(Vector3 point)</code></a>_</td><td>Tests whether the BoundingBox contains a point.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(Vector3D point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref Vector3 point, ref ContainmentType result)</code></a>_</td><td>Tests whether the BoundingBox contains a point.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(BoundingSphere sphere)</code></a>_</td><td>Tests whether the BoundingBox contains a BoundingSphere.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref BoundingSphere sphere, ref ContainmentType result)</code></a>_</td><td>Tests whether the BoundingBox contains a BoundingSphere.</td></tr>
<tr><td>_<a href="VRageMath.Translate"><code>BoundingBox Translate(Matrix worldMatrix)</code></a>_</td><td>Translate</td></tr>
<tr><td>_<a href="VRageMath.Translate"><code>BoundingBox Translate(Vector3 vctTranlsation)</code></a>_</td><td>Translate</td></tr>
<tr><td>_<a href="VRageMath.Transform"><code>BoundingBox Transform(Matrix worldMatrix)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Transform"><code>BoundingBoxD Transform(MatrixD worldMatrix)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Transform"><code>BoundingBox Transform(ref Matrix m)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Transform"><code>void Transform(ref Matrix m, ref BoundingBox bb)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Transform"><code>BoundingBoxD Transform(ref MatrixD m)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Transform"><code>void Transform(ref MatrixD m, ref BoundingBoxD bb)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox Include(ref Vector3 point)</code></a>_</td><td>return expanded aabb (aabb include point)</td></tr>
<tr><td>_<a href="VRageMath.GetIncluded"><code>BoundingBox GetIncluded(Vector3 point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox Include(Vector3 point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox Include(Vector3 p0, Vector3 p1, Vector3 p2)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox Include(ref Vector3 p0, ref Vector3 p1, ref Vector3 p2)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox Include(ref BoundingBox box)</code></a>_</td><td>return expanded aabb (aabb include aabb)</td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox Include(BoundingBox box)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>void Include(ref Line line)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox Include(BoundingSphere sphere)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox Include(ref BoundingSphere sphere)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBox Include(ref BoundingFrustum frustum)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CreateInvalid"><code>BoundingBox CreateInvalid()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.SurfaceArea"><code>float SurfaceArea()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Volume"><code>float Volume()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.ProjectedArea"><code>float ProjectedArea(Vector3 viewDir)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Inflate"><code>void Inflate(float size)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Inflate"><code>void Inflate(Vector3 size)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.InflateToMinimum"><code>void InflateToMinimum(Vector3 minimumSize)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Scale"><code>void Scale(Vector3 scale)</code></a>_</td><td></td></tr>
</table>
