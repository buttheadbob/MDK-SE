← [Index](index)
# BoundingBoxI Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
<table style="width:100%;display:table">
<tr><td>[`Vector3I Min`](VRageMath.Min)</td><td>The minimum point the BoundingBoxI contains.</td></tr>
<tr><td>[`Vector3I Max`](VRageMath.Max)</td><td>The maximum point the BoundingBoxI contains.</td></tr>
<tr><td>static [`int CornerCount`](VRageMath.CornerCount)</td><td>Specifies the total number of corners (8) in the BoundingBoxI.</td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>[`Vector3I Center`](VRageMath.Center)</td><td>Calculates center</td></tr>
<tr><td>[`Vector3I HalfExtents`](VRageMath.HalfExtents)</td><td></td></tr>
<tr><td>[`Vector3I Size`](VRageMath.Size)</td><td>Size</td></tr>
<tr><td>[`float Perimeter`](VRageMath.Perimeter)</td><td>return perimeter of edges</td></tr>
<tr><td>[`bool IsValid`](VRageMath.IsValid)</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>[`Vector3I[] GetCorners()`](VRageMath.GetCorners)</td><td>Gets an array of points that make up the corners of the BoundingBoxI.</td></tr>
<tr><td>[`void GetCorners(Vector3I[] corners)`](VRageMath.GetCorners)</td><td>Gets the array of points that make up the corners of the BoundingBoxI.</td></tr>
<tr><td>[`void GetCornersUnsafe(*Vector3I corners)`](VRageMath.GetCornersUnsafe)</td><td></td></tr>
<tr><td>[`bool Equals(BoundingBoxI other)`](VRageMath.Equals)</td><td>Determines whether two instances of BoundingBoxI are equal.</td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td>Determines whether two instances of BoundingBoxI are equal.</td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td>Gets the hash code for this instance.</td></tr>
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td>Returns a String that represents the current BoundingBoxI.</td></tr>
<tr><td>static [`BoundingBoxI CreateMerged(BoundingBoxI original, BoundingBoxI additional)`](VRageMath.CreateMerged)</td><td>Creates the smallest BoundingBoxI that contains the two specified BoundingBoxI instances.</td></tr>
<tr><td>static [`void CreateMerged(ref BoundingBoxI original, ref BoundingBoxI additional, ref BoundingBoxI result)`](VRageMath.CreateMerged)</td><td>Creates the smallest BoundingBoxI that contains the two specified BoundingBoxI instances.</td></tr>
<tr><td>static [`BoundingBoxI CreateFromSphere(BoundingSphere sphere)`](VRageMath.CreateFromSphere)</td><td>Creates the smallest BoundingBoxI that will contain the specified BoundingSphere.</td></tr>
<tr><td>static [`void CreateFromSphere(ref BoundingSphere sphere, ref BoundingBoxI result)`](VRageMath.CreateFromSphere)</td><td>Creates the smallest BoundingBoxI that will contain the specified BoundingSphere.</td></tr>
<tr><td>static [`BoundingBoxI CreateFromPoints(IEnumerable<Vector3I> points)`](VRageMath.CreateFromPoints)</td><td>Creates the smallest BoundingBoxI that will contain a group of points.</td></tr>
<tr><td>[`void IntersectWith(ref BoundingBoxI box)`](VRageMath.IntersectWith)</td><td>Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)</td></tr>
<tr><td>[`BoundingBoxI Intersect(BoundingBoxI box)`](VRageMath.Intersect)</td><td>Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)</td></tr>
<tr><td>[`bool Intersects(BoundingBoxI box)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBoxI intersects another BoundingBoxI.</td></tr>
<tr><td>[`bool Intersects(ref BoundingBoxI box)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`void Intersects(ref BoundingBoxI box, ref bool result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBoxI intersects another BoundingBoxI.</td></tr>
<tr><td>[`bool IntersectsTriangle(Vector3I v0, Vector3I v1, Vector3I v2)`](VRageMath.IntersectsTriangle)</td><td></td></tr>
<tr><td>[`bool IntersectsTriangle(ref Vector3I v0, ref Vector3I v1, ref Vector3I v2)`](VRageMath.IntersectsTriangle)</td><td></td></tr>
<tr><td>[`PlaneIntersectionType Intersects(Plane plane)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBoxI intersects a Plane.</td></tr>
<tr><td>[`void Intersects(ref Plane plane, ref PlaneIntersectionType result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBoxI intersects a Plane.</td></tr>
<tr><td>[`bool Intersects(Line line, ref float distance)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`Nullable<float> Intersects(Ray ray)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBoxI intersects a Ray.</td></tr>
<tr><td>[`void Intersects(ref Ray ray, ref Nullable<float> result)`](VRageMath.Intersects)</td><td>Checks whether the current BoundingBoxI intersects a Ray.</td></tr>
<tr><td>[`float Distance(Vector3I point)`](VRageMath.Distance)</td><td>Checks whether the current BoundingBoxI intersects a BoundingSphere.</td></tr>
<tr><td>[`ContainmentType Contains(BoundingBoxI box)`](VRageMath.Contains)</td><td>Tests whether the BoundingBoxI contains another BoundingBoxI.</td></tr>
<tr><td>[`void Contains(ref BoundingBoxI box, ref ContainmentType result)`](VRageMath.Contains)</td><td>Tests whether the BoundingBoxI contains a BoundingBoxI.</td></tr>
<tr><td>[`ContainmentType Contains(Vector3I point)`](VRageMath.Contains)</td><td>Tests whether the BoundingBoxI contains a point.</td></tr>
<tr><td>[`ContainmentType Contains(Vector3 point)`](VRageMath.Contains)</td><td></td></tr>
<tr><td>[`void Contains(ref Vector3I point, ref ContainmentType result)`](VRageMath.Contains)</td><td>Tests whether the BoundingBoxI contains a point.</td></tr>
<tr><td>[`BoundingBoxI Translate(Vector3I vctTranlsation)`](VRageMath.Translate)</td><td>Translate</td></tr>
<tr><td>[`BoundingBoxI Include(ref Vector3I point)`](VRageMath.Include)</td><td>return expanded aabb (abb include point)</td></tr>
<tr><td>[`BoundingBoxI GetIncluded(Vector3I point)`](VRageMath.GetIncluded)</td><td></td></tr>
<tr><td>[`BoundingBoxI Include(Vector3I point)`](VRageMath.Include)</td><td></td></tr>
<tr><td>[`BoundingBoxI Include(Vector3I p0, Vector3I p1, Vector3I p2)`](VRageMath.Include)</td><td></td></tr>
<tr><td>[`BoundingBoxI Include(ref Vector3I p0, ref Vector3I p1, ref Vector3I p2)`](VRageMath.Include)</td><td></td></tr>
<tr><td>[`BoundingBoxI Include(ref BoundingBoxI box)`](VRageMath.Include)</td><td>return expanded aabb (abb include point)</td></tr>
<tr><td>[`BoundingBoxI Include(BoundingBoxI box)`](VRageMath.Include)</td><td></td></tr>
<tr><td>static [`BoundingBoxI CreateInvalid()`](VRageMath.CreateInvalid)</td><td></td></tr>
<tr><td>[`float SurfaceArea()`](VRageMath.SurfaceArea)</td><td></td></tr>
<tr><td>[`float Volume()`](VRageMath.Volume)</td><td></td></tr>
<tr><td>[`void Inflate(int size)`](VRageMath.Inflate)</td><td></td></tr>
<tr><td>[`void InflateToMinimum(Vector3I minimumSize)`](VRageMath.InflateToMinimum)</td><td></td></tr>
<tr><td>static [`IEnumerable<Vector3I> IterateDifference(BoundingBoxI left, BoundingBoxI right)`](VRageMath.IterateDifference)</td><td>Iterate every cell contained in {left} - {right}, where we interpret {box} as the set of all distinct Vector3I points inside a 'box'. Containment is taken in a typical inclusive start, exclusive end fashion.</td></tr>
<tr><td>static [`IEnumerable<Vector3I> EnumeratePoints(BoundingBoxI rangeInclusive)`](VRageMath.EnumeratePoints)</td><td>Enumerate all values in a integer interval (a cuboid). This method is an allocating version of the Vector3I_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.</td></tr>
</table>
