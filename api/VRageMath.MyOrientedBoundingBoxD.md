← [Index](index)
# MyOrientedBoundingBoxD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`Vector3D Center`](VRageMath.Center)||
|[`Vector3D HalfExtent`](VRageMath.HalfExtent)||
|[`Quaternion Orientation`](VRageMath.Orientation)||
|static [`Int32[] StartVertices`](VRageMath.StartVertices)||
|static [`Int32[] EndVertices`](VRageMath.EndVertices)||
|static [`Int32[] StartXVertices`](VRageMath.StartXVertices)||
|static [`Int32[] EndXVertices`](VRageMath.EndXVertices)||
|static [`Int32[] StartYVertices`](VRageMath.StartYVertices)||
|static [`Int32[] EndYVertices`](VRageMath.EndYVertices)||
|static [`Int32[] StartZVertices`](VRageMath.StartZVertices)||
|static [`Int32[] EndZVertices`](VRageMath.EndZVertices)||
|static [`Vector3[] XNeighbourVectorsBack`](VRageMath.XNeighbourVectorsBack)||
|static [`Vector3[] XNeighbourVectorsForw`](VRageMath.XNeighbourVectorsForw)||
|static [`Vector3[] YNeighbourVectorsBack`](VRageMath.YNeighbourVectorsBack)||
|static [`Vector3[] YNeighbourVectorsForw`](VRageMath.YNeighbourVectorsForw)||
|static [`Vector3[] ZNeighbourVectorsBack`](VRageMath.ZNeighbourVectorsBack)||
|static [`Vector3[] ZNeighbourVectorsForw`](VRageMath.ZNeighbourVectorsForw)||
|static [`int CornerCount`](VRageMath.CornerCount)||
### Methods
|Member|Description|
|---|---|
|static [`bool GetNormalBetweenEdges(int axis, int edge0, int edge1, ref Vector3 normal)`](VRageMath.GetNormalBetweenEdges)|Returns normal between two cube edge of same direction|
|static [`MyOrientedBoundingBoxD CreateFromBoundingBox(BoundingBoxD box)`](VRageMath.CreateFromBoundingBox)||
|[`MyOrientedBoundingBoxD Transform(Quaternion rotation, Vector3D translation)`](VRageMath.Transform)||
|[`MyOrientedBoundingBoxD Transform(float scale, Quaternion rotation, Vector3D translation)`](VRageMath.Transform)||
|[`void Transform(MatrixD matrix)`](VRageMath.Transform)||
|[`bool Equals(MyOrientedBoundingBox other)`](VRageMath.Equals)||
|[`bool Equals(Object obj)`](VRageMath.Equals)||
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`string ToString()`](VRageMath.ToString)||
|[`bool Intersects(ref BoundingBox box)`](VRageMath.Intersects)||
|[`bool Intersects(ref BoundingBoxD box)`](VRageMath.Intersects)||
|[`ContainmentType Contains(ref BoundingBox box)`](VRageMath.Contains)||
|[`ContainmentType Contains(ref BoundingBoxD box)`](VRageMath.Contains)||
|static [`ContainmentType Contains(ref BoundingBox boxA, ref MyOrientedBoundingBox oboxB)`](VRageMath.Contains)||
|[`bool Intersects(ref MyOrientedBoundingBoxD other)`](VRageMath.Intersects)||
|[`ContainmentType Contains(ref MyOrientedBoundingBoxD other)`](VRageMath.Contains)||
|[`ContainmentType Contains(BoundingFrustumD frustum)`](VRageMath.Contains)||
|[`bool Intersects(BoundingFrustumD frustum)`](VRageMath.Intersects)||
|static [`ContainmentType Contains(BoundingFrustumD frustum, ref MyOrientedBoundingBoxD obox)`](VRageMath.Contains)||
|[`ContainmentType Contains(ref BoundingSphereD sphere)`](VRageMath.Contains)||
|[`bool Intersects(ref BoundingSphereD sphere)`](VRageMath.Intersects)||
|static [`ContainmentType Contains(ref BoundingSphere sphere, ref MyOrientedBoundingBox box)`](VRageMath.Contains)||
|[`bool Contains(ref Vector3 point)`](VRageMath.Contains)||
|[`bool Contains(ref Vector3D point)`](VRageMath.Contains)||
|[`Nullable<double> Intersects(ref RayD ray)`](VRageMath.Intersects)||
|[`Nullable<double> Intersects(ref LineD line)`](VRageMath.Intersects)||
|[`PlaneIntersectionType Intersects(ref PlaneD plane)`](VRageMath.Intersects)||
|[`void GetCorners(Vector3D[] corners, int startIndex)`](VRageMath.GetCorners)||
|static [`ContainmentType ContainsRelativeBox(ref Vector3D hA, ref Vector3D hB, ref MatrixD mB)`](VRageMath.ContainsRelativeBox)||
|[`BoundingFrustumD ConvertToFrustum()`](VRageMath.ConvertToFrustum)||
|[`BoundingBoxD GetAABB()`](VRageMath.GetAABB)||
|static [`MyOrientedBoundingBoxD Create(BoundingBoxD boundingBox, MatrixD matrix)`](VRageMath.Create)||
