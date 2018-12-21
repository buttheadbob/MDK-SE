← [Index](index)
# MyOrientedBoundingBox Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
<table style="width:100%;display:table">
<tr><td>[`Vector3 Center`](VRageMath.Center)</td><td></td></tr>
<tr><td>[`Vector3 HalfExtent`](VRageMath.HalfExtent)</td><td></td></tr>
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
<tr><td>static [`MyOrientedBoundingBox CreateFromBoundingBox(BoundingBox box)`](VRageMath.CreateFromBoundingBox)</td><td></td></tr>
<tr><td>[`MyOrientedBoundingBox Transform(Quaternion rotation, Vector3 translation)`](VRageMath.Transform)</td><td></td></tr>
<tr><td>[`MyOrientedBoundingBox Transform(float scale, Quaternion rotation, Vector3 translation)`](VRageMath.Transform)</td><td></td></tr>
<tr><td>[`void Transform(Matrix matrix)`](VRageMath.Transform)</td><td></td></tr>
<tr><td>[`bool Equals(MyOrientedBoundingBox other)`](VRageMath.Equals)</td><td></td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td></td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td></td></tr>
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td></td></tr>
<tr><td>[`bool Intersects(ref BoundingBox box)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`ContainmentType Contains(ref BoundingBox box)`](VRageMath.Contains)</td><td></td></tr>
<tr><td>static [`ContainmentType Contains(ref BoundingBox boxA, ref MyOrientedBoundingBox oboxB)`](VRageMath.Contains)</td><td></td></tr>
<tr><td>[`bool Intersects(ref MyOrientedBoundingBox other)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`ContainmentType Contains(ref MyOrientedBoundingBox other)`](VRageMath.Contains)</td><td></td></tr>
<tr><td>[`ContainmentType Contains(BoundingFrustum frustum)`](VRageMath.Contains)</td><td></td></tr>
<tr><td>[`bool Intersects(BoundingFrustum frustum)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>static [`ContainmentType Contains(BoundingFrustum frustum, ref MyOrientedBoundingBox obox)`](VRageMath.Contains)</td><td></td></tr>
<tr><td>[`ContainmentType Contains(ref BoundingSphere sphere)`](VRageMath.Contains)</td><td></td></tr>
<tr><td>[`bool Intersects(ref BoundingSphere sphere)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>static [`ContainmentType Contains(ref BoundingSphere sphere, ref MyOrientedBoundingBox box)`](VRageMath.Contains)</td><td></td></tr>
<tr><td>[`bool Contains(ref Vector3 point)`](VRageMath.Contains)</td><td></td></tr>
<tr><td>[`Nullable<float> Intersects(ref Ray ray)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`Nullable<float> Intersects(ref Line line)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`PlaneIntersectionType Intersects(ref Plane plane)`](VRageMath.Intersects)</td><td></td></tr>
<tr><td>[`void GetCorners(Vector3[] corners, int startIndex)`](VRageMath.GetCorners)</td><td></td></tr>
<tr><td>static [`ContainmentType ContainsRelativeBox(ref Vector3 hA, ref Vector3 hB, ref Matrix mB)`](VRageMath.ContainsRelativeBox)</td><td></td></tr>
<tr><td>[`BoundingFrustum ConvertToFrustum()`](VRageMath.ConvertToFrustum)</td><td></td></tr>
<tr><td>[`BoundingBox GetAABB()`](VRageMath.GetAABB)</td><td></td></tr>
<tr><td>static [`MyOrientedBoundingBox Create(BoundingBox boundingBox, Matrix matrix)`](VRageMath.Create)</td><td></td></tr>
</table>
