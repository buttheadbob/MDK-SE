← [Index](index)
# MyOrientedBoundingBoxD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`Center`](VRageMath.Center)||
|[`HalfExtent`](VRageMath.HalfExtent)||
|[`Orientation`](VRageMath.Orientation)||
|static [`StartVertices`](VRageMath.StartVertices)||
|static [`EndVertices`](VRageMath.EndVertices)||
|static [`StartXVertices`](VRageMath.StartXVertices)||
|static [`EndXVertices`](VRageMath.EndXVertices)||
|static [`StartYVertices`](VRageMath.StartYVertices)||
|static [`EndYVertices`](VRageMath.EndYVertices)||
|static [`StartZVertices`](VRageMath.StartZVertices)||
|static [`EndZVertices`](VRageMath.EndZVertices)||
|static [`XNeighbourVectorsBack`](VRageMath.XNeighbourVectorsBack)||
|static [`XNeighbourVectorsForw`](VRageMath.XNeighbourVectorsForw)||
|static [`YNeighbourVectorsBack`](VRageMath.YNeighbourVectorsBack)||
|static [`YNeighbourVectorsForw`](VRageMath.YNeighbourVectorsForw)||
|static [`ZNeighbourVectorsBack`](VRageMath.ZNeighbourVectorsBack)||
|static [`ZNeighbourVectorsForw`](VRageMath.ZNeighbourVectorsForw)||
|static [`CornerCount`](VRageMath.CornerCount)||
### Methods
|Member|Description|
|---|---|
|static [`GetNormalBetweenEdges(int, int, int, ref Vector3)`](VRageMath.GetNormalBetweenEdges)|Returns normal between two cube edge of same direction|
|static [`CreateFromBoundingBox(BoundingBoxD)`](VRageMath.CreateFromBoundingBox)||
|[`Transform(Quaternion, Vector3D)`](VRageMath.Transform)||
|[`Transform(float, Quaternion, Vector3D)`](VRageMath.Transform)||
|[`Transform(MatrixD)`](VRageMath.Transform)||
|[`Equals(MyOrientedBoundingBox)`](VRageMath.Equals)||
|[`Equals(Object)`](VRageMath.Equals)||
|[`GetHashCode()`](VRageMath.GetHashCode)||
|[`ToString()`](VRageMath.ToString)||
|[`Intersects(ref BoundingBox)`](VRageMath.Intersects)||
|[`Intersects(ref BoundingBoxD)`](VRageMath.Intersects)||
|[`Contains(ref BoundingBox)`](VRageMath.Contains)||
|[`Contains(ref BoundingBoxD)`](VRageMath.Contains)||
|static [`Contains(ref BoundingBox, ref MyOrientedBoundingBox)`](VRageMath.Contains)||
|[`Intersects(ref MyOrientedBoundingBoxD)`](VRageMath.Intersects)||
|[`Contains(ref MyOrientedBoundingBoxD)`](VRageMath.Contains)||
|[`Contains(BoundingFrustumD)`](VRageMath.Contains)||
|[`Intersects(BoundingFrustumD)`](VRageMath.Intersects)||
|static [`Contains(BoundingFrustumD, ref MyOrientedBoundingBoxD)`](VRageMath.Contains)||
|[`Contains(ref BoundingSphereD)`](VRageMath.Contains)||
|[`Intersects(ref BoundingSphereD)`](VRageMath.Intersects)||
|static [`Contains(ref BoundingSphere, ref MyOrientedBoundingBox)`](VRageMath.Contains)||
|[`Contains(ref Vector3)`](VRageMath.Contains)||
|[`Contains(ref Vector3D)`](VRageMath.Contains)||
|[`Intersects(ref RayD)`](VRageMath.Intersects)||
|[`Intersects(ref LineD)`](VRageMath.Intersects)||
|[`Intersects(ref PlaneD)`](VRageMath.Intersects)||
|[`GetCorners(Vector3D[], int)`](VRageMath.GetCorners)||
|static [`ContainsRelativeBox(ref Vector3D, ref Vector3D, ref MatrixD)`](VRageMath.ContainsRelativeBox)||
|[`ConvertToFrustum()`](VRageMath.ConvertToFrustum)||
|[`GetAABB()`](VRageMath.GetAABB)||
|static [`Create(BoundingBoxD, MatrixD)`](VRageMath.Create)||
