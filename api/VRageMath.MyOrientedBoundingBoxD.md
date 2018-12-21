← [Index](index)
# MyOrientedBoundingBoxD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
<table style="width:100%;display:table">
<tr><td>[`Vector3D Center`](VRageMath.Center)</td><td></td></tr>
<tr><td>[`Vector3D HalfExtent`](VRageMath.HalfExtent)</td><td></td></tr>
<tr><td>[`Quaternion Orientation`](VRageMath.Orientation)</td><td></td></tr>
<tr><td>static [`Int32[] StartVertices`](VRageMath.StartVertices)</td><td></td></tr>
<tr><td>static [`Int32[] EndVertices`](VRageMath.EndVertices)</td><td></td></tr>
<tr><td>static [`Int32[] StartXVertices`](VRageMath.StartXVertices)</td><td></td></tr>
<tr><td>static [`Int32[] EndXVertices`](VRageMath.EndXVertices)</td><td></td></tr>
<tr><td>static [`Int32[] StartYVertices`](VRageMath.StartYVertices)</td><td></td></tr>
<tr><td>static [`Int32[] EndYVertices`](VRageMath.EndYVertices)</td><td></td></tr>
<tr><td>static [`Int32[] StartZVertices`](VRageMath.StartZVertices)</td><td></td></tr>
<tr><td>static [`Int32[] EndZVertices`](VRageMath.EndZVertices)</td><td></td></tr>
<tr><td>static [`Vector3[] XNeighbourVectorsBack`](VRageMath.XNeighbourVectorsBack)</td><td></td></tr>
<tr><td>static [`Vector3[] XNeighbourVectorsForw`](VRageMath.XNeighbourVectorsForw)</td><td></td></tr>
<tr><td>static [`Vector3[] YNeighbourVectorsBack`](VRageMath.YNeighbourVectorsBack)</td><td></td></tr>
<tr><td>static [`Vector3[] YNeighbourVectorsForw`](VRageMath.YNeighbourVectorsForw)</td><td></td></tr>
<tr><td>static [`Vector3[] ZNeighbourVectorsBack`](VRageMath.ZNeighbourVectorsBack)</td><td></td></tr>
<tr><td>static [`Vector3[] ZNeighbourVectorsForw`](VRageMath.ZNeighbourVectorsForw)</td><td></td></tr>
<tr><td>static [`int CornerCount`](VRageMath.CornerCount)</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>static [`bool GetNormalBetweenEdges(int axis, int edge0, int edge1, ref Vector3 normal)`](VRageMath.GetNormalBetweenEdges)</td><td>Returns normal between two cube edge of same direction</td></tr>
<tr><td>static [`MyOrientedBoundingBoxD CreateFromBoundingBox(BoundingBoxD box)`](VRageMath.CreateFromBoundingBox)</td><td></td></tr>
<tr><td>[`MyOrientedBoundingBoxD Transform(Quaternion rotation, Vector3D translation)`](VRageMath.Transform)</td><td></td></tr>
<tr><td>[`MyOrientedBoundingBoxD Transform(float scale, Quaternion rotation, Vector3D translation)`](VRageMath.Transform)</td><td></td></tr>
<tr><td>[`void Transform(MatrixD matrix)`](VRageMath.Transform)</td><td></td></tr>
<tr><td>[`bool Equals(MyOrientedBoundingBox other)`](VRageMath.Equals)</td><td></td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td></td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td></td></tr>
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td></td></tr>
<tr><td>[`bool Intersects(ref BoundingBox box)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`bool Intersects(ref BoundingBoxD box)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`ContainmentType Contains(ref BoundingBox box)`](VRageMath.Contains)</td><td></td></tr>
<tr><td>[`ContainmentType Contains(ref BoundingBoxD box)`](VRageMath.Contains)</td><td></td></tr>
<tr><td>static [`ContainmentType Contains(ref BoundingBox boxA, ref MyOrientedBoundingBox oboxB)`](VRageMath.Contains)</td><td></td></tr>
<tr><td>[`bool Intersects(ref MyOrientedBoundingBoxD other)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`ContainmentType Contains(ref MyOrientedBoundingBoxD other)`](VRageMath.Contains)</td><td></td></tr>
<tr><td>[`ContainmentType Contains(BoundingFrustumD frustum)`](VRageMath.Contains)</td><td></td></tr>
<tr><td>[`bool Intersects(BoundingFrustumD frustum)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>static [`ContainmentType Contains(BoundingFrustumD frustum, ref MyOrientedBoundingBoxD obox)`](VRageMath.Contains)</td><td></td></tr>
<tr><td>[`ContainmentType Contains(ref BoundingSphereD sphere)`](VRageMath.Contains)</td><td></td></tr>
<tr><td>[`bool Intersects(ref BoundingSphereD sphere)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>static [`ContainmentType Contains(ref BoundingSphere sphere, ref MyOrientedBoundingBox box)`](VRageMath.Contains)</td><td></td></tr>
<tr><td>[`bool Contains(ref Vector3 point)`](VRageMath.Contains)</td><td></td></tr>
<tr><td>[`bool Contains(ref Vector3D point)`](VRageMath.Contains)</td><td></td></tr>
<tr><td>[`Nullable<double> Intersects(ref RayD ray)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`Nullable<double> Intersects(ref LineD line)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`PlaneIntersectionType Intersects(ref PlaneD plane)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`void GetCorners(Vector3D[] corners, int startIndex)`](VRageMath.GetCorners)</td><td></td></tr>
<tr><td>static [`ContainmentType ContainsRelativeBox(ref Vector3D hA, ref Vector3D hB, ref MatrixD mB)`](VRageMath.ContainsRelativeBox)</td><td></td></tr>
<tr><td>[`BoundingFrustumD ConvertToFrustum()`](VRageMath.ConvertToFrustum)</td><td></td></tr>
<tr><td>[`BoundingBoxD GetAABB()`](VRageMath.GetAABB)</td><td></td></tr>
<tr><td>static [`MyOrientedBoundingBoxD Create(BoundingBoxD boundingBox, MatrixD matrix)`](VRageMath.Create)</td><td></td></tr>
</table>
