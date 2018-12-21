← [Index](ApiIndex)
# MyOrientedBoundingBoxD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`Center`](VRageMath.Center)||
|[`HalfExtent`](VRageMath.HalfExtent)||
|[`Orientation`](VRageMath.Orientation)||
|[`StartVertices`](VRageMath.StartVertices)||
|[`EndVertices`](VRageMath.EndVertices)||
|[`StartXVertices`](VRageMath.StartXVertices)||
|[`EndXVertices`](VRageMath.EndXVertices)||
|[`StartYVertices`](VRageMath.StartYVertices)||
|[`EndYVertices`](VRageMath.EndYVertices)||
|[`StartZVertices`](VRageMath.StartZVertices)||
|[`EndZVertices`](VRageMath.EndZVertices)||
|[`XNeighbourVectorsBack`](VRageMath.XNeighbourVectorsBack)||
|[`XNeighbourVectorsForw`](VRageMath.XNeighbourVectorsForw)||
|[`YNeighbourVectorsBack`](VRageMath.YNeighbourVectorsBack)||
|[`YNeighbourVectorsForw`](VRageMath.YNeighbourVectorsForw)||
|[`ZNeighbourVectorsBack`](VRageMath.ZNeighbourVectorsBack)||
|[`ZNeighbourVectorsForw`](VRageMath.ZNeighbourVectorsForw)||
|[`CornerCount`](VRageMath.CornerCount)||
### Methods
|Member|Description|
|---|---|
|[`GetNormalBetweenEdges(int, int, int, ref Vector3)`](VRageMath.GetNormalBetweenEdges)|Returns normal between two cube edge of same direction|
|[`CreateFromBoundingBox(BoundingBoxD)`](VRageMath.CreateFromBoundingBox)||
|[`Transform(Quaternion, Vector3D)`](VRageMath.Transform)||
|[`Transform(float, Quaternion, Vector3D)`](VRageMath.Transform)||
|[`Transform(MatrixD)`](VRageMath.Transform)||
|[`Equals(MyOrientedBoundingBox)`](VRageMath.Equals)||
|[`Equals(Object)`](VRageMath.Equals)||
|[`GetHashCode()`](VRageMath.GetHashCode)||
|[`ToString()`](VRageMath.ToString)||
|[`Intersects(ref BoundingBox)`](VRageMath.Intersects)||
|[`Intersects(ref BoundingBoxD)`](VRageMath.Intersects)||
|[`Contains(ref BoundingBox)`](VRageMath.Contains)||
|[`Contains(ref BoundingBoxD)`](VRageMath.Contains)||
|[`Contains(ref BoundingBox, ref MyOrientedBoundingBox)`](VRageMath.Contains)||
|[`Intersects(ref MyOrientedBoundingBoxD)`](VRageMath.Intersects)||
|[`Contains(ref MyOrientedBoundingBoxD)`](VRageMath.Contains)||
|[`Contains(BoundingFrustumD)`](VRageMath.Contains)||
|[`Intersects(BoundingFrustumD)`](VRageMath.Intersects)||
|[`Contains(BoundingFrustumD, ref MyOrientedBoundingBoxD)`](VRageMath.Contains)||
|[`Contains(ref BoundingSphereD)`](VRageMath.Contains)||
|[`Intersects(ref BoundingSphereD)`](VRageMath.Intersects)||
|[`Contains(ref BoundingSphere, ref MyOrientedBoundingBox)`](VRageMath.Contains)||
|[`Contains(ref Vector3)`](VRageMath.Contains)||
|[`Contains(ref Vector3D)`](VRageMath.Contains)||
|[`Intersects(ref RayD)`](VRageMath.Intersects)||
|[`Intersects(ref LineD)`](VRageMath.Intersects)||
|[`Intersects(ref PlaneD)`](VRageMath.Intersects)||
|[`GetCorners(Vector3D[], int)`](VRageMath.GetCorners)||
|[`ContainsRelativeBox(ref Vector3D, ref Vector3D, ref MatrixD)`](VRageMath.ContainsRelativeBox)||
|[`ConvertToFrustum()`](VRageMath.ConvertToFrustum)||
|[`GetAABB()`](VRageMath.GetAABB)||
|[`Create(BoundingBoxD, MatrixD)`](VRageMath.Create)||
