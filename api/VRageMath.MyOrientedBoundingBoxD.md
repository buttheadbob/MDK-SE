← [Index](index.md)
# MyOrientedBoundingBoxD Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`Vector3D Center`](VRageMath.Center.md)||
|[`Vector3D HalfExtent`](VRageMath.HalfExtent.md)||
|[`Quaternion Orientation`](VRageMath.Orientation.md)||
|[`Int32[] StartVertices`](VRageMath.StartVertices.md)||
|[`Int32[] EndVertices`](VRageMath.EndVertices.md)||
|[`Int32[] StartXVertices`](VRageMath.StartXVertices.md)||
|[`Int32[] EndXVertices`](VRageMath.EndXVertices.md)||
|[`Int32[] StartYVertices`](VRageMath.StartYVertices.md)||
|[`Int32[] EndYVertices`](VRageMath.EndYVertices.md)||
|[`Int32[] StartZVertices`](VRageMath.StartZVertices.md)||
|[`Int32[] EndZVertices`](VRageMath.EndZVertices.md)||
|[`Vector3[] XNeighbourVectorsBack`](VRageMath.XNeighbourVectorsBack.md)||
|[`Vector3[] XNeighbourVectorsForw`](VRageMath.XNeighbourVectorsForw.md)||
|[`Vector3[] YNeighbourVectorsBack`](VRageMath.YNeighbourVectorsBack.md)||
|[`Vector3[] YNeighbourVectorsForw`](VRageMath.YNeighbourVectorsForw.md)||
|[`Vector3[] ZNeighbourVectorsBack`](VRageMath.ZNeighbourVectorsBack.md)||
|[`Vector3[] ZNeighbourVectorsForw`](VRageMath.ZNeighbourVectorsForw.md)||
|[`int CornerCount`](VRageMath.CornerCount.md)||
### Methods
|Member|Description|
|---|---|
|[`bool GetNormalBetweenEdges(int axis, int edge0, int edge1, ref Vector3 normal)`](VRageMath.GetNormalBetweenEdges.md)||
|[`MyOrientedBoundingBoxD CreateFromBoundingBox(BoundingBoxD box)`](VRageMath.CreateFromBoundingBox.md)||
|[`MyOrientedBoundingBoxD Transform(Quaternion rotation, Vector3D translation)`](VRageMath.Transform.md)||
|[`MyOrientedBoundingBoxD Transform(float scale, Quaternion rotation, Vector3D translation)`](VRageMath.Transform.md)||
|[`void Transform(MatrixD matrix)`](VRageMath.Transform.md)||
|[`bool Equals(MyOrientedBoundingBox other)`](VRageMath.Equals.md)||
|[`bool Equals(Object obj)`](VRageMath.Equals.md)||
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`string ToString()`](VRageMath.ToString.md)||
|[`bool Intersects(ref BoundingBox box)`](VRageMath.Intersects.md)||
|[`bool Intersects(ref BoundingBoxD box)`](VRageMath.Intersects.md)||
|[`ContainmentType Contains(ref BoundingBox box)`](VRageMath.Contains.md)||
|[`ContainmentType Contains(ref BoundingBoxD box)`](VRageMath.Contains.md)||
|[`ContainmentType Contains(ref BoundingBox boxA, ref MyOrientedBoundingBox oboxB)`](VRageMath.Contains.md)||
|[`bool Intersects(ref MyOrientedBoundingBoxD other)`](VRageMath.Intersects.md)||
|[`ContainmentType Contains(ref MyOrientedBoundingBoxD other)`](VRageMath.Contains.md)||
|[`ContainmentType Contains(BoundingFrustumD frustum)`](VRageMath.Contains.md)||
|[`bool Intersects(BoundingFrustumD frustum)`](VRageMath.Intersects.md)||
|[`ContainmentType Contains(BoundingFrustumD frustum, ref MyOrientedBoundingBoxD obox)`](VRageMath.Contains.md)||
|[`ContainmentType Contains(ref BoundingSphereD sphere)`](VRageMath.Contains.md)||
|[`bool Intersects(ref BoundingSphereD sphere)`](VRageMath.Intersects.md)||
|[`ContainmentType Contains(ref BoundingSphere sphere, ref MyOrientedBoundingBox box)`](VRageMath.Contains.md)||
|[`bool Contains(ref Vector3 point)`](VRageMath.Contains.md)||
|[`bool Contains(ref Vector3D point)`](VRageMath.Contains.md)||
|[`Nullable<double> Intersects(ref RayD ray)`](VRageMath.Intersects.md)||
|[`Nullable<double> Intersects(ref LineD line)`](VRageMath.Intersects.md)||
|[`PlaneIntersectionType Intersects(ref PlaneD plane)`](VRageMath.Intersects.md)||
|[`void GetCorners(Vector3D[] corners, int startIndex)`](VRageMath.GetCorners.md)||
|[`ContainmentType ContainsRelativeBox(ref Vector3D hA, ref Vector3D hB, ref MatrixD mB)`](VRageMath.ContainsRelativeBox.md)||
|[`BoundingFrustumD ConvertToFrustum()`](VRageMath.ConvertToFrustum.md)||
|[`BoundingBoxD GetAABB()`](VRageMath.GetAABB.md)||
|[`MyOrientedBoundingBoxD Create(BoundingBoxD boundingBox, MatrixD matrix)`](VRageMath.Create.md)||
