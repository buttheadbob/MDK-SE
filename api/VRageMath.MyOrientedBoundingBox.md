← [Index](index)
# MyOrientedBoundingBox Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`Vector3&nbsp;Center`](VRageMath.Center)||
|[`Vector3&nbsp;HalfExtent`](VRageMath.HalfExtent)||
|[`Quaternion&nbsp;Orientation`](VRageMath.Orientation)||
|static&nbsp;[`Int32[]&nbsp;StartVertices`](VRageMath.StartVertices)||
|static&nbsp;[`Int32[]&nbsp;EndVertices`](VRageMath.EndVertices)||
|static&nbsp;[`Int32[]&nbsp;StartXVertices`](VRageMath.StartXVertices)||
|static&nbsp;[`Int32[]&nbsp;EndXVertices`](VRageMath.EndXVertices)||
|static&nbsp;[`Int32[]&nbsp;StartYVertices`](VRageMath.StartYVertices)||
|static&nbsp;[`Int32[]&nbsp;EndYVertices`](VRageMath.EndYVertices)||
|static&nbsp;[`Int32[]&nbsp;StartZVertices`](VRageMath.StartZVertices)||
|static&nbsp;[`Int32[]&nbsp;EndZVertices`](VRageMath.EndZVertices)||
|static&nbsp;[`Vector3[]&nbsp;XNeighbourVectorsBack`](VRageMath.XNeighbourVectorsBack)||
|static&nbsp;[`Vector3[]&nbsp;XNeighbourVectorsForw`](VRageMath.XNeighbourVectorsForw)||
|static&nbsp;[`Vector3[]&nbsp;YNeighbourVectorsBack`](VRageMath.YNeighbourVectorsBack)||
|static&nbsp;[`Vector3[]&nbsp;YNeighbourVectorsForw`](VRageMath.YNeighbourVectorsForw)||
|static&nbsp;[`Vector3[]&nbsp;ZNeighbourVectorsBack`](VRageMath.ZNeighbourVectorsBack)||
|static&nbsp;[`Vector3[]&nbsp;ZNeighbourVectorsForw`](VRageMath.ZNeighbourVectorsForw)||
|static&nbsp;[`int&nbsp;CornerCount`](VRageMath.CornerCount)||
### Methods
|Member|Description|
|---|---|
|static&nbsp;[`bool&nbsp;GetNormalBetweenEdges(int&nbsp;axis,&nbsp;int&nbsp;edge0,&nbsp;int&nbsp;edge1,&nbsp;ref&nbsp;Vector3&nbsp;normal)`](VRageMath.GetNormalBetweenEdges)|Returns normal between two cube edge of same direction|
|static&nbsp;[`MyOrientedBoundingBox&nbsp;CreateFromBoundingBox(BoundingBox&nbsp;box)`](VRageMath.CreateFromBoundingBox)||
|[`MyOrientedBoundingBox&nbsp;Transform(Quaternion&nbsp;rotation,&nbsp;Vector3&nbsp;translation)`](VRageMath.Transform)||
|[`MyOrientedBoundingBox&nbsp;Transform(float&nbsp;scale,&nbsp;Quaternion&nbsp;rotation,&nbsp;Vector3&nbsp;translation)`](VRageMath.Transform)||
|[`void&nbsp;Transform(Matrix&nbsp;matrix)`](VRageMath.Transform)||
|[`bool&nbsp;Equals(MyOrientedBoundingBox&nbsp;other)`](VRageMath.Equals)||
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)||
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)||
|[`string&nbsp;ToString()`](VRageMath.ToString)||
|[`bool&nbsp;Intersects(ref&nbsp;BoundingBox&nbsp;box)`](VRageMath.Intersects)||
|[`ContainmentType&nbsp;Contains(ref&nbsp;BoundingBox&nbsp;box)`](VRageMath.Contains)||
|static&nbsp;[`ContainmentType&nbsp;Contains(ref&nbsp;BoundingBox&nbsp;boxA,&nbsp;ref&nbsp;MyOrientedBoundingBox&nbsp;oboxB)`](VRageMath.Contains)||
|[`bool&nbsp;Intersects(ref&nbsp;MyOrientedBoundingBox&nbsp;other)`](VRageMath.Intersects)||
|[`ContainmentType&nbsp;Contains(ref&nbsp;MyOrientedBoundingBox&nbsp;other)`](VRageMath.Contains)||
|[`ContainmentType&nbsp;Contains(BoundingFrustum&nbsp;frustum)`](VRageMath.Contains)||
|[`bool&nbsp;Intersects(BoundingFrustum&nbsp;frustum)`](VRageMath.Intersects)||
|static&nbsp;[`ContainmentType&nbsp;Contains(BoundingFrustum&nbsp;frustum,&nbsp;ref&nbsp;MyOrientedBoundingBox&nbsp;obox)`](VRageMath.Contains)||
|[`ContainmentType&nbsp;Contains(ref&nbsp;BoundingSphere&nbsp;sphere)`](VRageMath.Contains)||
|[`bool&nbsp;Intersects(ref&nbsp;BoundingSphere&nbsp;sphere)`](VRageMath.Intersects)||
|static&nbsp;[`ContainmentType&nbsp;Contains(ref&nbsp;BoundingSphere&nbsp;sphere,&nbsp;ref&nbsp;MyOrientedBoundingBox&nbsp;box)`](VRageMath.Contains)||
|[`bool&nbsp;Contains(ref&nbsp;Vector3&nbsp;point)`](VRageMath.Contains)||
|[`Nullable<float>&nbsp;Intersects(ref&nbsp;Ray&nbsp;ray)`](VRageMath.Intersects)||
|[`Nullable<float>&nbsp;Intersects(ref&nbsp;Line&nbsp;line)`](VRageMath.Intersects)||
|[`PlaneIntersectionType&nbsp;Intersects(ref&nbsp;Plane&nbsp;plane)`](VRageMath.Intersects)||
|[`void&nbsp;GetCorners(Vector3[]&nbsp;corners,&nbsp;int&nbsp;startIndex)`](VRageMath.GetCorners)||
|static&nbsp;[`ContainmentType&nbsp;ContainsRelativeBox(ref&nbsp;Vector3&nbsp;hA,&nbsp;ref&nbsp;Vector3&nbsp;hB,&nbsp;ref&nbsp;Matrix&nbsp;mB)`](VRageMath.ContainsRelativeBox)||
|[`BoundingFrustum&nbsp;ConvertToFrustum()`](VRageMath.ConvertToFrustum)||
|[`BoundingBox&nbsp;GetAABB()`](VRageMath.GetAABB)||
|static&nbsp;[`MyOrientedBoundingBox&nbsp;Create(BoundingBox&nbsp;boundingBox,&nbsp;Matrix&nbsp;matrix)`](VRageMath.Create)||
