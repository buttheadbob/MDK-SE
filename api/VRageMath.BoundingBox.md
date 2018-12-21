← [Index](index)
# BoundingBox Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines an axis-aligned box-shaped 3D volume.
### Fields
|Member|Description|
|---|---|
|[`VRageMath.Vector3 Min`](VRageMath.Min)|The minimum point the BoundingBox contains.|
|[`VRageMath.Vector3 Max`](VRageMath.Max)|The maximum point the BoundingBox contains.|
|static [`VRageMath.ComparerType Comparer`](VRageMath.Comparer)||
|static [`int CornerCount`](VRageMath.CornerCount)|Specifies the total number of corners (8) in the BoundingBox.|
### Properties
|Member|Description|
|---|---|
|[`VRageMath.BoxCornerEnumerator Corners`](VRageMath.Corners)||
|[`VRageMath.Vector3 Center`](VRageMath.Center)|Calculates center|
|[`VRageMath.Vector3 HalfExtents`](VRageMath.HalfExtents)||
|[`VRageMath.Vector3 Extents`](VRageMath.Extents)||
|[`float Width`](VRageMath.Width)||
|[`float Height`](VRageMath.Height)||
|[`float Depth`](VRageMath.Depth)||
|[`VRageMath.Vector3 Size`](VRageMath.Size)|Size|
|[`VRageMath.Matrix Matrix`](VRageMath.Matrix)|Matrix of AABB, respection center and size|
|[`float Perimeter`](VRageMath.Perimeter)|return perimeter of edges|
### Methods
|Member|Description|
|---|---|
|[`VRageMath.Vector3[] GetCorners()`](VRageMath.GetCorners)|Gets an array of points that make up the corners of the BoundingBox. ALLOCATION!|
|[`void GetCorners(VRageMath.Vector3[])`](VRageMath.GetCorners)|Gets the array of points that make up the corners of the BoundingBox.|
|[`void GetCornersUnsafe(*VRageMath.Vector3)`](VRageMath.GetCornersUnsafe)||
|[`bool Equals(VRageMath.BoundingBox)`](VRageMath.Equals)|Determines whether two instances of BoundingBox are equal.|
|[`bool Equals(System.Object)`](VRageMath.Equals)|Determines whether two instances of BoundingBox are equal.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code for this instance.|
|[`string ToString()`](VRageMath.ToString)|Returns a String that represents the current BoundingBox.|
|static [`VRageMath.BoundingBox CreateMerged(VRageMath.BoundingBox, VRageMath.BoundingBox)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox that contains the two specified BoundingBox instances.|
|static [`void CreateMerged(ref VRageMath.BoundingBox, ref VRageMath.BoundingBox, ref VRageMath.BoundingBox)`](VRageMath.CreateMerged)|Creates the smallest BoundingBox that contains the two specified BoundingBox instances.|
|static [`VRageMath.BoundingBox CreateFromSphere(VRageMath.BoundingSphere)`](VRageMath.CreateFromSphere)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|static [`void CreateFromSphere(ref VRageMath.BoundingSphere, ref VRageMath.BoundingBox)`](VRageMath.CreateFromSphere)|Creates the smallest BoundingBox that will contain the specified BoundingSphere.|
|static [`VRageMath.BoundingBox CreateFromPoints(IEnumerable<VRageMath.Vector3>)`](VRageMath.CreateFromPoints)|Creates the smallest BoundingBox that will contain a group of points.|
|static [`VRageMath.BoundingBox CreateFromHalfExtent(VRageMath.Vector3, float)`](VRageMath.CreateFromHalfExtent)||
|static [`VRageMath.BoundingBox CreateFromHalfExtent(VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.CreateFromHalfExtent)||
|[`VRageMath.BoundingBox Intersect(VRageMath.BoundingBox)`](VRageMath.Intersect)|Returns bounding box which is intersection of this and box It's called 'Prunik' Result is invalid box when there's no intersection (Min > Max)|
|[`bool Intersects(VRageMath.BoundingBox)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects another BoundingBox.|
|[`bool Intersects(ref VRageMath.BoundingBox)`](VRageMath.Intersects)||
|[`void Intersects(ref VRageMath.BoundingBox, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects another BoundingBox.|
|[`bool IntersectsTriangle(VRageMath.Vector3, VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.IntersectsTriangle)||
|[`bool IntersectsTriangle(ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Vector3)`](VRageMath.IntersectsTriangle)||
|[`bool Intersects(VRageMath.BoundingFrustum)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a BoundingFrustum.|
|[`VRageMath.PlaneIntersectionType Intersects(VRageMath.Plane)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Plane.|
|[`void Intersects(ref VRageMath.Plane, ref VRageMath.PlaneIntersectionType)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Plane.|
|[`bool Intersects(VRageMath.Line, ref float)`](VRageMath.Intersects)||
|[`Nullable<System.Single> Intersects(VRageMath.Ray)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Ray.|
|[`void Intersects(ref VRageMath.Ray, ref Nullable<System.Single>)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a Ray.|
|[`bool Intersects(VRageMath.BoundingSphere)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|[`void Intersects(ref VRageMath.BoundingSphere, ref bool)`](VRageMath.Intersects)|Checks whether the current BoundingBox intersects a BoundingSphere.|
|[`bool Intersects(ref VRageMath.BoundingSphere)`](VRageMath.Intersects)||
|[`bool Intersects(ref VRageMath.BoundingSphereD)`](VRageMath.Intersects)||
|[`float Distance(VRageMath.Vector3)`](VRageMath.Distance)||
|[`float DistanceSquared(VRageMath.Vector3)`](VRageMath.DistanceSquared)||
|[`VRageMath.ContainmentType Contains(VRageMath.BoundingBox)`](VRageMath.Contains)|Tests whether the BoundingBox contains another BoundingBox.|
|[`void Contains(ref VRageMath.BoundingBox, ref VRageMath.ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingBox.|
|[`VRageMath.ContainmentType Contains(VRageMath.BoundingFrustum)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingFrustum.|
|[`VRageMath.ContainmentType Contains(VRageMath.Vector3)`](VRageMath.Contains)|Tests whether the BoundingBox contains a point.|
|[`VRageMath.ContainmentType Contains(VRageMath.Vector3D)`](VRageMath.Contains)||
|[`void Contains(ref VRageMath.Vector3, ref VRageMath.ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBox contains a point.|
|[`VRageMath.ContainmentType Contains(VRageMath.BoundingSphere)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingSphere.|
|[`void Contains(ref VRageMath.BoundingSphere, ref VRageMath.ContainmentType)`](VRageMath.Contains)|Tests whether the BoundingBox contains a BoundingSphere.|
|[`VRageMath.BoundingBox Translate(VRageMath.Matrix)`](VRageMath.Translate)|Translate|
|[`VRageMath.BoundingBox Translate(VRageMath.Vector3)`](VRageMath.Translate)|Translate|
|[`VRageMath.BoundingBox Transform(VRageMath.Matrix)`](VRageMath.Transform)||
|[`VRageMath.BoundingBoxD Transform(VRageMath.MatrixD)`](VRageMath.Transform)||
|[`VRageMath.BoundingBox Transform(ref VRageMath.Matrix)`](VRageMath.Transform)||
|[`void Transform(ref VRageMath.Matrix, ref VRageMath.BoundingBox)`](VRageMath.Transform)||
|[`VRageMath.BoundingBoxD Transform(ref VRageMath.MatrixD)`](VRageMath.Transform)||
|[`void Transform(ref VRageMath.MatrixD, ref VRageMath.BoundingBoxD)`](VRageMath.Transform)||
|[`VRageMath.BoundingBox Include(ref VRageMath.Vector3)`](VRageMath.Include)|return expanded aabb (aabb include point)|
|[`VRageMath.BoundingBox GetIncluded(VRageMath.Vector3)`](VRageMath.GetIncluded)||
|[`VRageMath.BoundingBox Include(VRageMath.Vector3)`](VRageMath.Include)||
|[`VRageMath.BoundingBox Include(VRageMath.Vector3, VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.Include)||
|[`VRageMath.BoundingBox Include(ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Vector3)`](VRageMath.Include)||
|[`VRageMath.BoundingBox Include(ref VRageMath.BoundingBox)`](VRageMath.Include)|return expanded aabb (aabb include aabb)|
|[`VRageMath.BoundingBox Include(VRageMath.BoundingBox)`](VRageMath.Include)||
|[`void Include(ref VRageMath.Line)`](VRageMath.Include)||
|[`VRageMath.BoundingBox Include(VRageMath.BoundingSphere)`](VRageMath.Include)||
|[`VRageMath.BoundingBox Include(ref VRageMath.BoundingSphere)`](VRageMath.Include)||
|[`VRageMath.BoundingBox Include(ref VRageMath.BoundingFrustum)`](VRageMath.Include)||
|static [`VRageMath.BoundingBox CreateInvalid()`](VRageMath.CreateInvalid)||
|[`float SurfaceArea()`](VRageMath.SurfaceArea)||
|[`float Volume()`](VRageMath.Volume)||
|[`float ProjectedArea(VRageMath.Vector3)`](VRageMath.ProjectedArea)||
|[`void Inflate(float)`](VRageMath.Inflate)||
|[`void Inflate(VRageMath.Vector3)`](VRageMath.Inflate)||
|[`void InflateToMinimum(VRageMath.Vector3)`](VRageMath.InflateToMinimum)||
|[`void Scale(VRageMath.Vector3)`](VRageMath.Scale)||
