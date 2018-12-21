← [Index](index)
# MyOrientedBoundingBox Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`Vector3 Center`](VRageMath.Center)||
|[`Vector3 HalfExtent`](VRageMath.HalfExtent)||
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
|static [`MyOrientedBoundingBox CreateFromBoundingBox(BoundingBox box)`](VRageMath.CreateFromBoundingBox)||
|[`MyOrientedBoundingBox Transform(Quaternion rotation, Vector3 translation)`](VRageMath.Transform)||
|[`MyOrientedBoundingBox Transform(float scale, Quaternion rotation, Vector3 translation)`](VRageMath.Transform)||
|[`void Transform(Matrix matrix)`](VRageMath.Transform)||
|[`bool Equals(MyOrientedBoundingBox other)`](VRageMath.Equals)||
|[`bool Equals(Object obj)`](VRageMath.Equals)||
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`string ToString()`](VRageMath.ToString)||
|[`bool Intersects(ref BoundingBox box)`](VRageMath.Intersects)||
|[`ContainmentType Contains(ref BoundingBox box)`](VRageMath.Contains)||
|static [`ContainmentType Contains(ref BoundingBox boxA, ref MyOrientedBoundingBox oboxB)`](VRageMath.Contains)||
|[`bool Intersects(ref MyOrientedBoundingBox other)`](VRageMath.Intersects)||
|[`ContainmentType Contains(ref MyOrientedBoundingBox other)`](VRageMath.Contains)||
|[`ContainmentType Contains(BoundingFrustum frustum)`](VRageMath.Contains)||
|[`bool Intersects(BoundingFrustum frustum)`](VRageMath.Intersects)||
|static [`ContainmentType Contains(BoundingFrustum frustum, ref MyOrientedBoundingBox obox)`](VRageMath.Contains)||
|[`ContainmentType Contains(ref BoundingSphere sphere)`](VRageMath.Contains)||
|[`bool Intersects(ref BoundingSphere sphere)`](VRageMath.Intersects)||
|static [`ContainmentType Contains(ref BoundingSphere sphere, ref MyOrientedBoundingBox box)`](VRageMath.Contains)||
|[`bool Contains(ref Vector3 point)`](VRageMath.Contains)||
|[`Nullable<float> Intersects(ref Ray ray)`](VRageMath.Intersects)||
|[`Nullable<float> Intersects(ref Line line)`](VRageMath.Intersects)||
|[`PlaneIntersectionType Intersects(ref Plane plane)`](VRageMath.Intersects)||
|[`void GetCorners(Vector3[] corners, int startIndex)`](VRageMath.GetCorners)||
|static [`ContainmentType ContainsRelativeBox(ref Vector3 hA, ref Vector3 hB, ref Matrix mB)`](VRageMath.ContainsRelativeBox)||
|[`BoundingFrustum ConvertToFrustum()`](VRageMath.ConvertToFrustum)||
|[`BoundingBox GetAABB()`](VRageMath.GetAABB)||
|static [`MyOrientedBoundingBox Create(BoundingBox boundingBox, Matrix matrix)`](VRageMath.Create)||
