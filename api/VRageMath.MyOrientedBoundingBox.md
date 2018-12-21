← [Index](index)
# MyOrientedBoundingBox Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`VRageMath.Vector3 Center`](VRageMath.Center)||
|[`VRageMath.Vector3 HalfExtent`](VRageMath.HalfExtent)||
|[`VRageMath.Quaternion Orientation`](VRageMath.Orientation)||
|static [`System.Int32[] StartVertices`](VRageMath.StartVertices)||
|static [`System.Int32[] EndVertices`](VRageMath.EndVertices)||
|static [`System.Int32[] StartXVertices`](VRageMath.StartXVertices)||
|static [`System.Int32[] EndXVertices`](VRageMath.EndXVertices)||
|static [`System.Int32[] StartYVertices`](VRageMath.StartYVertices)||
|static [`System.Int32[] EndYVertices`](VRageMath.EndYVertices)||
|static [`System.Int32[] StartZVertices`](VRageMath.StartZVertices)||
|static [`System.Int32[] EndZVertices`](VRageMath.EndZVertices)||
|static [`VRageMath.Vector3[] XNeighbourVectorsBack`](VRageMath.XNeighbourVectorsBack)||
|static [`VRageMath.Vector3[] XNeighbourVectorsForw`](VRageMath.XNeighbourVectorsForw)||
|static [`VRageMath.Vector3[] YNeighbourVectorsBack`](VRageMath.YNeighbourVectorsBack)||
|static [`VRageMath.Vector3[] YNeighbourVectorsForw`](VRageMath.YNeighbourVectorsForw)||
|static [`VRageMath.Vector3[] ZNeighbourVectorsBack`](VRageMath.ZNeighbourVectorsBack)||
|static [`VRageMath.Vector3[] ZNeighbourVectorsForw`](VRageMath.ZNeighbourVectorsForw)||
|static [`int CornerCount`](VRageMath.CornerCount)||
### Methods
|Member|Description|
|---|---|
|static [`bool GetNormalBetweenEdges(int, int, int, ref VRageMath.Vector3)`](VRageMath.GetNormalBetweenEdges)|Returns normal between two cube edge of same direction|
|static [`VRageMath.MyOrientedBoundingBox CreateFromBoundingBox(VRageMath.BoundingBox)`](VRageMath.CreateFromBoundingBox)||
|[`VRageMath.MyOrientedBoundingBox Transform(VRageMath.Quaternion, VRageMath.Vector3)`](VRageMath.Transform)||
|[`VRageMath.MyOrientedBoundingBox Transform(float, VRageMath.Quaternion, VRageMath.Vector3)`](VRageMath.Transform)||
|[`void Transform(VRageMath.Matrix)`](VRageMath.Transform)||
|[`bool Equals(VRageMath.MyOrientedBoundingBox)`](VRageMath.Equals)||
|[`bool Equals(System.Object)`](VRageMath.Equals)||
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`string ToString()`](VRageMath.ToString)||
|[`bool Intersects(ref VRageMath.BoundingBox)`](VRageMath.Intersects)||
|[`VRageMath.ContainmentType Contains(ref VRageMath.BoundingBox)`](VRageMath.Contains)||
|static [`VRageMath.ContainmentType Contains(ref VRageMath.BoundingBox, ref VRageMath.MyOrientedBoundingBox)`](VRageMath.Contains)||
|[`bool Intersects(ref VRageMath.MyOrientedBoundingBox)`](VRageMath.Intersects)||
|[`VRageMath.ContainmentType Contains(ref VRageMath.MyOrientedBoundingBox)`](VRageMath.Contains)||
|[`VRageMath.ContainmentType Contains(VRageMath.BoundingFrustum)`](VRageMath.Contains)||
|[`bool Intersects(VRageMath.BoundingFrustum)`](VRageMath.Intersects)||
|static [`VRageMath.ContainmentType Contains(VRageMath.BoundingFrustum, ref VRageMath.MyOrientedBoundingBox)`](VRageMath.Contains)||
|[`VRageMath.ContainmentType Contains(ref VRageMath.BoundingSphere)`](VRageMath.Contains)||
|[`bool Intersects(ref VRageMath.BoundingSphere)`](VRageMath.Intersects)||
|static [`VRageMath.ContainmentType Contains(ref VRageMath.BoundingSphere, ref VRageMath.MyOrientedBoundingBox)`](VRageMath.Contains)||
|[`bool Contains(ref VRageMath.Vector3)`](VRageMath.Contains)||
|[`Nullable<System.Single> Intersects(ref VRageMath.Ray)`](VRageMath.Intersects)||
|[`Nullable<System.Single> Intersects(ref VRageMath.Line)`](VRageMath.Intersects)||
|[`VRageMath.PlaneIntersectionType Intersects(ref VRageMath.Plane)`](VRageMath.Intersects)||
|[`void GetCorners(VRageMath.Vector3[], int)`](VRageMath.GetCorners)||
|static [`VRageMath.ContainmentType ContainsRelativeBox(ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Matrix)`](VRageMath.ContainsRelativeBox)||
|[`VRageMath.BoundingFrustum ConvertToFrustum()`](VRageMath.ConvertToFrustum)||
|[`VRageMath.BoundingBox GetAABB()`](VRageMath.GetAABB)||
|static [`VRageMath.MyOrientedBoundingBox Create(VRageMath.BoundingBox, VRageMath.Matrix)`](VRageMath.Create)||
