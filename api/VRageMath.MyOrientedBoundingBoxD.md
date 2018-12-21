← [Index](index)
# MyOrientedBoundingBoxD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`VRageMath.Vector3D Center`](VRageMath.Center)||
|[`VRageMath.Vector3D HalfExtent`](VRageMath.HalfExtent)||
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
|static [`VRageMath.MyOrientedBoundingBoxD CreateFromBoundingBox(VRageMath.BoundingBoxD)`](VRageMath.CreateFromBoundingBox)||
|[`VRageMath.MyOrientedBoundingBoxD Transform(VRageMath.Quaternion, VRageMath.Vector3D)`](VRageMath.Transform)||
|[`VRageMath.MyOrientedBoundingBoxD Transform(float, VRageMath.Quaternion, VRageMath.Vector3D)`](VRageMath.Transform)||
|[`void Transform(VRageMath.MatrixD)`](VRageMath.Transform)||
|[`bool Equals(VRageMath.MyOrientedBoundingBox)`](VRageMath.Equals)||
|[`bool Equals(System.Object)`](VRageMath.Equals)||
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`string ToString()`](VRageMath.ToString)||
|[`bool Intersects(ref VRageMath.BoundingBox)`](VRageMath.Intersects)||
|[`bool Intersects(ref VRageMath.BoundingBoxD)`](VRageMath.Intersects)||
|[`VRageMath.ContainmentType Contains(ref VRageMath.BoundingBox)`](VRageMath.Contains)||
|[`VRageMath.ContainmentType Contains(ref VRageMath.BoundingBoxD)`](VRageMath.Contains)||
|static [`VRageMath.ContainmentType Contains(ref VRageMath.BoundingBox, ref VRageMath.MyOrientedBoundingBox)`](VRageMath.Contains)||
|[`bool Intersects(ref VRageMath.MyOrientedBoundingBoxD)`](VRageMath.Intersects)||
|[`VRageMath.ContainmentType Contains(ref VRageMath.MyOrientedBoundingBoxD)`](VRageMath.Contains)||
|[`VRageMath.ContainmentType Contains(VRageMath.BoundingFrustumD)`](VRageMath.Contains)||
|[`bool Intersects(VRageMath.BoundingFrustumD)`](VRageMath.Intersects)||
|static [`VRageMath.ContainmentType Contains(VRageMath.BoundingFrustumD, ref VRageMath.MyOrientedBoundingBoxD)`](VRageMath.Contains)||
|[`VRageMath.ContainmentType Contains(ref VRageMath.BoundingSphereD)`](VRageMath.Contains)||
|[`bool Intersects(ref VRageMath.BoundingSphereD)`](VRageMath.Intersects)||
|static [`VRageMath.ContainmentType Contains(ref VRageMath.BoundingSphere, ref VRageMath.MyOrientedBoundingBox)`](VRageMath.Contains)||
|[`bool Contains(ref VRageMath.Vector3)`](VRageMath.Contains)||
|[`bool Contains(ref VRageMath.Vector3D)`](VRageMath.Contains)||
|[`Nullable<System.Double> Intersects(ref VRageMath.RayD)`](VRageMath.Intersects)||
|[`Nullable<System.Double> Intersects(ref VRageMath.LineD)`](VRageMath.Intersects)||
|[`VRageMath.PlaneIntersectionType Intersects(ref VRageMath.PlaneD)`](VRageMath.Intersects)||
|[`void GetCorners(VRageMath.Vector3D[], int)`](VRageMath.GetCorners)||
|static [`VRageMath.ContainmentType ContainsRelativeBox(ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref VRageMath.MatrixD)`](VRageMath.ContainsRelativeBox)||
|[`VRageMath.BoundingFrustumD ConvertToFrustum()`](VRageMath.ConvertToFrustum)||
|[`VRageMath.BoundingBoxD GetAABB()`](VRageMath.GetAABB)||
|static [`VRageMath.MyOrientedBoundingBoxD Create(VRageMath.BoundingBoxD, VRageMath.MatrixD)`](VRageMath.Create)||
