← [Index](index)
# BoundingBoxD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Min"><code>Vector3D Min</code></a>_</td><td>The minimum point the BoundingBox contains.</td></tr>
<tr><td>_<a href="VRageMath.Max"><code>Vector3D Max</code></a>_</td><td>The maximum point the BoundingBox contains.</td></tr>
<tr><td>static _<a href="VRageMath.Comparer"><code>ComparerType Comparer</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CornerCount"><code>int CornerCount</code></a>_</td><td>Specifies the total number of corners (8) in the BoundingBox.</td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Center"><code>Vector3D Center</code></a>_</td><td>Calculates center</td></tr>
<tr><td>_<a href="VRageMath.HalfExtents"><code>Vector3D HalfExtents</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Extents"><code>Vector3D Extents</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Size"><code>Vector3D Size</code></a>_</td><td>Size</td></tr>
<tr><td>_<a href="VRageMath.Matrix"><code>MatrixD Matrix</code></a>_</td><td>Matrix of AABB, respection center and size</td></tr>
<tr><td>_<a href="VRageMath.SurfaceArea"><code>double SurfaceArea</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Volume"><code>double Volume</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Perimeter"><code>double Perimeter</code></a>_</td><td>return perimeter of edges</td></tr>
<tr><td>_<a href="VRageMath.Valid"><code>bool Valid</code></a>_</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.GetCorners"><code>Vector3D[] GetCorners()</code></a>_</td><td>Gets an array of points that make up the corners of the BoundingBox. ALLOCATION!</td></tr>
<tr><td>_<a href="VRageMath.GetCorners"><code>void GetCorners(Vector3D[] corners)</code></a>_</td><td>Gets the array of points that make up the corners of the BoundingBox.</td></tr>
<tr><td>_<a href="VRageMath.GetCornersUnsafe"><code>void GetCornersUnsafe(*Vector3D corners)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(BoundingBoxD other)</code></a>_</td><td>Determines whether two instances of BoundingBox are equal.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Object obj)</code></a>_</td><td>Determines whether two instances of BoundingBox are equal.</td></tr>
<tr><td>_<a href="VRageMath.GetHashCode"><code>int GetHashCode()</code></a>_</td><td>Gets the hash code for this instance.</td></tr>
<tr><td>_<a href="VRageMath.ToString"><code>string ToString()</code></a>_</td><td>Returns a String that represents the current BoundingBox.</td></tr>
<tr><td>static _<a href="VRageMath.CreateMerged"><code>BoundingBoxD CreateMerged(BoundingBoxD original, BoundingBoxD additional)</code></a>_</td><td>Creates the smallest BoundingBox that contains the two specified BoundingBox instances.</td></tr>
<tr><td>static _<a href="VRageMath.CreateMerged"><code>void CreateMerged(ref BoundingBoxD original, ref BoundingBoxD additional, ref BoundingBoxD result)</code></a>_</td><td>Creates the smallest BoundingBox that contains the two specified BoundingBox instances.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromSphere"><code>BoundingBoxD CreateFromSphere(BoundingSphereD sphere)</code></a>_</td><td>Creates the smallest BoundingBox that will contain the specified BoundingSphere.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromSphere"><code>void CreateFromSphere(ref BoundingSphereD sphere, ref BoundingBoxD result)</code></a>_</td><td>Creates the smallest BoundingBox that will contain the specified BoundingSphere.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromPoints"><code>BoundingBoxD CreateFromPoints(IEnumerable<Vector3D> points)</code></a>_</td><td>Creates the smallest BoundingBox that will contain a group of points.</td></tr>
<tr><td>_<a href="VRageMath.Intersect"><code>BoundingBoxD Intersect(BoundingBoxD box)</code></a>_</td><td>Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(BoundingBoxD box)</code></a>_</td><td>Checks whether the current BoundingBox intersects another BoundingBox.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(ref BoundingBoxD box)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref BoundingBoxD box, ref bool result)</code></a>_</td><td>Checks whether the current BoundingBox intersects another BoundingBox.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref BoundingBox box, ref bool result)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.IntersectsTriangle"><code>bool IntersectsTriangle(Vector3D v0, Vector3D v1, Vector3D v2)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.IntersectsTriangle"><code>bool IntersectsTriangle(ref Vector3D v0, ref Vector3D v1, ref Vector3D v2)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(BoundingFrustumD frustum)</code></a>_</td><td>Checks whether the current BoundingBox intersects a BoundingFrustum.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>PlaneIntersectionType Intersects(PlaneD plane)</code></a>_</td><td>Checks whether the current BoundingBox intersects a Plane.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref PlaneD plane, ref PlaneIntersectionType result)</code></a>_</td><td>Checks whether the current BoundingBox intersects a Plane.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(ref LineD line)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(ref LineD line, ref double distance)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>Nullable<double> Intersects(Ray ray)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>Nullable<double> Intersects(RayD ray)</code></a>_</td><td>Checks whether the current BoundingBox intersects a Ray.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref RayD ray, ref Nullable<double> result)</code></a>_</td><td>Checks whether the current BoundingBox intersects a Ray.</td></tr>
<tr><td>_<a href="VRageMath.Intersect"><code>bool Intersect(ref LineD line, ref LineD intersectedLine)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersect"><code>bool Intersect(ref LineD line, ref double t1, ref double t2)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersect"><code>bool Intersect(ref RayD ray, ref double tmin, ref double tmax)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(BoundingSphereD sphere)</code></a>_</td><td>Checks whether the current BoundingBox intersects a BoundingSphere.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>void Intersects(ref BoundingSphereD sphere, ref bool result)</code></a>_</td><td>Checks whether the current BoundingBox intersects a BoundingSphere.</td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(ref BoundingSphereD sphere)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Distance"><code>double Distance(Vector3D point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.DistanceSquared"><code>double DistanceSquared(Vector3D point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.DistanceSquared"><code>double DistanceSquared(ref Vector3D point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(BoundingBoxD box)</code></a>_</td><td>Tests whether the BoundingBox contains another BoundingBox.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref BoundingBoxD box, ref ContainmentType result)</code></a>_</td><td>Tests whether the BoundingBox contains a BoundingBox.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(BoundingFrustumD frustum)</code></a>_</td><td>Tests whether the BoundingBox contains a BoundingFrustum.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(Vector3D point)</code></a>_</td><td>Tests whether the BoundingBox contains a point.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref Vector3D point, ref ContainmentType result)</code></a>_</td><td>Tests whether the BoundingBox contains a point.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(BoundingSphereD sphere)</code></a>_</td><td>Tests whether the BoundingBox contains a BoundingSphere.</td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>void Contains(ref BoundingSphereD sphere, ref ContainmentType result)</code></a>_</td><td>Tests whether the BoundingBox contains a BoundingSphere.</td></tr>
<tr><td>_<a href="VRageMath.Translate"><code>BoundingBoxD Translate(MatrixD worldMatrix)</code></a>_</td><td>Translate</td></tr>
<tr><td>_<a href="VRageMath.Translate"><code>BoundingBoxD Translate(Vector3D vctTranlsation)</code></a>_</td><td>Translate</td></tr>
<tr><td>_<a href="VRageMath.TransformSlow"><code>BoundingBoxD TransformSlow(MatrixD m)</code></a>_</td><td>Transform this AABB by matrix.</td></tr>
<tr><td>_<a href="VRageMath.TransformSlow"><code>BoundingBoxD TransformSlow(ref MatrixD worldMatrix)</code></a>_</td><td>Transform this AABB by matrix.</td></tr>
<tr><td>_<a href="VRageMath.TransformFast"><code>BoundingBoxD TransformFast(MatrixD m)</code></a>_</td><td>Transform this AABB by matrix. Matrix has to be only rotation and translation.</td></tr>
<tr><td>_<a href="VRageMath.TransformFast"><code>BoundingBoxD TransformFast(ref MatrixD m)</code></a>_</td><td>Transform this AABB by matrix. Matrix has to be only rotation and translation.</td></tr>
<tr><td>_<a href="VRageMath.TransformFast"><code>void TransformFast(ref MatrixD m, ref BoundingBoxD bb)</code></a>_</td><td>Transform this AABB by matrix. Matrix has to be only rotation and translation.</td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBoxD Include(ref Vector3D point)</code></a>_</td><td>return expanded aabb (aabb include point)</td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBoxD Include(Vector3D point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBoxD Include(Vector3D p0, Vector3D p1, Vector3D p2)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBoxD Include(ref Vector3D p0, ref Vector3D p1, ref Vector3D p2)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBoxD Include(ref BoundingBoxD box)</code></a>_</td><td>return expanded aabb (aabb include aabb)</td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBoxD Include(BoundingBoxD box)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>void Include(ref LineD line)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBoxD Include(BoundingSphereD sphere)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBoxD Include(ref BoundingSphereD sphere)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Include"><code>BoundingBoxD Include(ref BoundingFrustumD frustum)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CreateInvalid"><code>BoundingBoxD CreateInvalid()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.ProjectedArea"><code>double ProjectedArea(Vector3D viewDir)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Inflate"><code>BoundingBoxD Inflate(double size)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Inflate"><code>BoundingBoxD Inflate(Vector3 size)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.GetInflated"><code>BoundingBoxD GetInflated(double size)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.GetInflated"><code>BoundingBoxD GetInflated(Vector3 size)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.InflateToMinimum"><code>void InflateToMinimum(Vector3D minimumSize)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.InflateToMinimum"><code>void InflateToMinimum(double minimumSize)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.AssertIsValid"><code>void AssertIsValid()</code></a>_</td><td></td></tr>
</table>
