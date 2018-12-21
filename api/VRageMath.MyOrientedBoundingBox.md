← [Index](Api-Index)
# MyOrientedBoundingBox Struct
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
|[`CreateFromBoundingBox(BoundingBox)`](VRageMath.CreateFromBoundingBox)||
|[`Transform(Quaternion, Vector3)`](VRageMath.Transform)||
|[`Transform(float, Quaternion, Vector3)`](VRageMath.Transform)||
|[`Transform(Matrix)`](VRageMath.Transform)||
|[`Equals(MyOrientedBoundingBox)`](VRageMath.Equals)||
|[`Equals(Object)`](VRageMath.Equals)||
|[`GetHashCode()`](VRageMath.GetHashCode)||
|[`ToString()`](VRageMath.ToString)||
|[`Intersects(ref BoundingBox)`](VRageMath.Intersects)||
|[`Contains(ref BoundingBox)`](VRageMath.Contains)||
|[`Contains(ref BoundingBox, ref MyOrientedBoundingBox)`](VRageMath.Contains)||
|[`Intersects(ref MyOrientedBoundingBox)`](VRageMath.Intersects)||
|[`Contains(ref MyOrientedBoundingBox)`](VRageMath.Contains)||
|[`Contains(BoundingFrustum)`](VRageMath.Contains)||
|[`Intersects(BoundingFrustum)`](VRageMath.Intersects)||
|[`Contains(BoundingFrustum, ref MyOrientedBoundingBox)`](VRageMath.Contains)||
|[`Contains(ref BoundingSphere)`](VRageMath.Contains)||
|[`Intersects(ref BoundingSphere)`](VRageMath.Intersects)||
|[`Contains(ref BoundingSphere, ref MyOrientedBoundingBox)`](VRageMath.Contains)||
|[`Contains(ref Vector3)`](VRageMath.Contains)||
|[`Intersects(ref Ray)`](VRageMath.Intersects)||
|[`Intersects(ref Line)`](VRageMath.Intersects)||
|[`Intersects(ref Plane)`](VRageMath.Intersects)||
|[`GetCorners(Vector3[], int)`](VRageMath.GetCorners)||
|[`ContainsRelativeBox(ref Vector3, ref Vector3, ref Matrix)`](VRageMath.ContainsRelativeBox)||
|[`ConvertToFrustum()`](VRageMath.ConvertToFrustum)||
|[`GetAABB()`](VRageMath.GetAABB)||
|[`Create(BoundingBox, Matrix)`](VRageMath.Create)||
