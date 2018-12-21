← [Index](index)
# MyOrientedBoundingBoxD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`Vector3D&nbsp;Center`](VRageMath.Center)||
|[`Vector3D&nbsp;HalfExtent`](VRageMath.HalfExtent)||
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
|static&nbsp;[`MyOrientedBoundingBoxD&nbsp;CreateFromBoundingBox(BoundingBoxD&nbsp;box)`](VRageMath.CreateFromBoundingBox)||
|[`MyOrientedBoundingBoxD&nbsp;Transform(Quaternion&nbsp;rotation,&nbsp;Vector3D&nbsp;translation)`](VRageMath.Transform)||
|[`MyOrientedBoundingBoxD&nbsp;Transform(float&nbsp;scale,&nbsp;Quaternion&nbsp;rotation,&nbsp;Vector3D&nbsp;translation)`](VRageMath.Transform)||
|[`void&nbsp;Transform(MatrixD&nbsp;matrix)`](VRageMath.Transform)||
|[`bool&nbsp;Equals(MyOrientedBoundingBox&nbsp;other)`](VRageMath.Equals)||
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)||
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)||
|[`string&nbsp;ToString()`](VRageMath.ToString)||
|[`bool&nbsp;Intersects(ref&nbsp;BoundingBox&nbsp;box)`](VRageMath.Intersects)||
|[`bool&nbsp;Intersects(ref&nbsp;BoundingBoxD&nbsp;box)`](VRageMath.Intersects)||
|[`ContainmentType&nbsp;Contains(ref&nbsp;BoundingBox&nbsp;box)`](VRageMath.Contains)||
|[`ContainmentType&nbsp;Contains(ref&nbsp;BoundingBoxD&nbsp;box)`](VRageMath.Contains)||
|static&nbsp;[`ContainmentType&nbsp;Contains(ref&nbsp;BoundingBox&nbsp;boxA,&nbsp;ref&nbsp;MyOrientedBoundingBox&nbsp;oboxB)`](VRageMath.Contains)||
|[`bool&nbsp;Intersects(ref&nbsp;MyOrientedBoundingBoxD&nbsp;other)`](VRageMath.Intersects)||
|[`ContainmentType&nbsp;Contains(ref&nbsp;MyOrientedBoundingBoxD&nbsp;other)`](VRageMath.Contains)||
|[`ContainmentType&nbsp;Contains(BoundingFrustumD&nbsp;frustum)`](VRageMath.Contains)||
|[`bool&nbsp;Intersects(BoundingFrustumD&nbsp;frustum)`](VRageMath.Intersects)||
|static&nbsp;[`ContainmentType&nbsp;Contains(BoundingFrustumD&nbsp;frustum,&nbsp;ref&nbsp;MyOrientedBoundingBoxD&nbsp;obox)`](VRageMath.Contains)||
|[`ContainmentType&nbsp;Contains(ref&nbsp;BoundingSphereD&nbsp;sphere)`](VRageMath.Contains)||
|[`bool&nbsp;Intersects(ref&nbsp;BoundingSphereD&nbsp;sphere)`](VRageMath.Intersects)||
|static&nbsp;[`ContainmentType&nbsp;Contains(ref&nbsp;BoundingSphere&nbsp;sphere,&nbsp;ref&nbsp;MyOrientedBoundingBox&nbsp;box)`](VRageMath.Contains)||
|[`bool&nbsp;Contains(ref&nbsp;Vector3&nbsp;point)`](VRageMath.Contains)||
|[`bool&nbsp;Contains(ref&nbsp;Vector3D&nbsp;point)`](VRageMath.Contains)||
|[`Nullable<double>&nbsp;Intersects(ref&nbsp;RayD&nbsp;ray)`](VRageMath.Intersects)||
|[`Nullable<double>&nbsp;Intersects(ref&nbsp;LineD&nbsp;line)`](VRageMath.Intersects)||
|[`PlaneIntersectionType&nbsp;Intersects(ref&nbsp;PlaneD&nbsp;plane)`](VRageMath.Intersects)||
|[`void&nbsp;GetCorners(Vector3D[]&nbsp;corners,&nbsp;int&nbsp;startIndex)`](VRageMath.GetCorners)||
|static&nbsp;[`ContainmentType&nbsp;ContainsRelativeBox(ref&nbsp;Vector3D&nbsp;hA,&nbsp;ref&nbsp;Vector3D&nbsp;hB,&nbsp;ref&nbsp;MatrixD&nbsp;mB)`](VRageMath.ContainsRelativeBox)||
|[`BoundingFrustumD&nbsp;ConvertToFrustum()`](VRageMath.ConvertToFrustum)||
|[`BoundingBoxD&nbsp;GetAABB()`](VRageMath.GetAABB)||
|static&nbsp;[`MyOrientedBoundingBoxD&nbsp;Create(BoundingBoxD&nbsp;boundingBox,&nbsp;MatrixD&nbsp;matrix)`](VRageMath.Create)||
