← [Index](index)
# MyOrientedBoundingBox Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`Center`](VRageMath.Center)||
|[`HalfExtent`](VRageMath.HalfExtent)||
|[`Orientation`](VRageMath.Orientation)||
|static [`StartVertices`](VRageMath.StartVertices)||
|static [`EndVertices`](VRageMath.EndVertices)||
|static [`StartXVertices`](VRageMath.StartXVertices)||
|static [`EndXVertices`](VRageMath.EndXVertices)||
|static [`StartYVertices`](VRageMath.StartYVertices)||
|static [`EndYVertices`](VRageMath.EndYVertices)||
|static [`StartZVertices`](VRageMath.StartZVertices)||
|static [`EndZVertices`](VRageMath.EndZVertices)||
|static [`XNeighbourVectorsBack`](VRageMath.XNeighbourVectorsBack)||
|static [`XNeighbourVectorsForw`](VRageMath.XNeighbourVectorsForw)||
|static [`YNeighbourVectorsBack`](VRageMath.YNeighbourVectorsBack)||
|static [`YNeighbourVectorsForw`](VRageMath.YNeighbourVectorsForw)||
|static [`ZNeighbourVectorsBack`](VRageMath.ZNeighbourVectorsBack)||
|static [`ZNeighbourVectorsForw`](VRageMath.ZNeighbourVectorsForw)||
|static [`CornerCount`](VRageMath.CornerCount)||
### Methods
|Member|Description|
|---|---|
|static [`GetNormalBetweenEdges(int, int, int, ref Vector3)`](VRageMath.GetNormalBetweenEdges)|Returns normal between two cube edge of same direction|
|static [`CreateFromBoundingBox(BoundingBox)`](VRageMath.CreateFromBoundingBox)||
|[`Transform(Quaternion, Vector3)`](VRageMath.Transform)||
|[`Transform(float, Quaternion, Vector3)`](VRageMath.Transform)||
|[`Transform(Matrix)`](VRageMath.Transform)||
|[`Equals(MyOrientedBoundingBox)`](VRageMath.Equals)||
|[`Equals(Object)`](VRageMath.Equals)||
|[`GetHashCode()`](VRageMath.GetHashCode)||
|[`ToString()`](VRageMath.ToString)||
|[`Intersects(ref BoundingBox)`](VRageMath.Intersects)||
|[`Contains(ref BoundingBox)`](VRageMath.Contains)||
|static [`Contains(ref BoundingBox, ref MyOrientedBoundingBox)`](VRageMath.Contains)||
|[`Intersects(ref MyOrientedBoundingBox)`](VRageMath.Intersects)||
|[`Contains(ref MyOrientedBoundingBox)`](VRageMath.Contains)||
|[`Contains(BoundingFrustum)`](VRageMath.Contains)||
|[`Intersects(BoundingFrustum)`](VRageMath.Intersects)||
|static [`Contains(BoundingFrustum, ref MyOrientedBoundingBox)`](VRageMath.Contains)||
|[`Contains(ref BoundingSphere)`](VRageMath.Contains)||
|[`Intersects(ref BoundingSphere)`](VRageMath.Intersects)||
|static [`Contains(ref BoundingSphere, ref MyOrientedBoundingBox)`](VRageMath.Contains)||
|[`Contains(ref Vector3)`](VRageMath.Contains)||
|[`Intersects(ref Ray)`](VRageMath.Intersects)||
|[`Intersects(ref Line)`](VRageMath.Intersects)||
|[`Intersects(ref Plane)`](VRageMath.Intersects)||
|[`GetCorners(Vector3[], int)`](VRageMath.GetCorners)||
|static [`ContainsRelativeBox(ref Vector3, ref Vector3, ref Matrix)`](VRageMath.ContainsRelativeBox)||
|[`ConvertToFrustum()`](VRageMath.ConvertToFrustum)||
|[`GetAABB()`](VRageMath.GetAABB)||
|static [`Create(BoundingBox, Matrix)`](VRageMath.Create)||
