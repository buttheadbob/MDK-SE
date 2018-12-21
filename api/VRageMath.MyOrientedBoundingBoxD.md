← [Index](index)
# MyOrientedBoundingBoxD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Center"><code>Vector3D Center</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.HalfExtent"><code>Vector3D HalfExtent</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Orientation"><code>Quaternion Orientation</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.StartVertices"><code>Int32[] StartVertices</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.EndVertices"><code>Int32[] EndVertices</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.StartXVertices"><code>Int32[] StartXVertices</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.EndXVertices"><code>Int32[] EndXVertices</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.StartYVertices"><code>Int32[] StartYVertices</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.EndYVertices"><code>Int32[] EndYVertices</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.StartZVertices"><code>Int32[] StartZVertices</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.EndZVertices"><code>Int32[] EndZVertices</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.XNeighbourVectorsBack"><code>Vector3[] XNeighbourVectorsBack</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.XNeighbourVectorsForw"><code>Vector3[] XNeighbourVectorsForw</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.YNeighbourVectorsBack"><code>Vector3[] YNeighbourVectorsBack</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.YNeighbourVectorsForw"><code>Vector3[] YNeighbourVectorsForw</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.ZNeighbourVectorsBack"><code>Vector3[] ZNeighbourVectorsBack</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.ZNeighbourVectorsForw"><code>Vector3[] ZNeighbourVectorsForw</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CornerCount"><code>int CornerCount</code></a>_</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>static _<a href="VRageMath.GetNormalBetweenEdges"><code>bool GetNormalBetweenEdges(int axis, int edge0, int edge1, ref Vector3 normal)</code></a>_</td><td>Returns normal between two cube edge of same direction</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromBoundingBox"><code>MyOrientedBoundingBoxD CreateFromBoundingBox(BoundingBoxD box)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Transform"><code>MyOrientedBoundingBoxD Transform(Quaternion rotation, Vector3D translation)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Transform"><code>MyOrientedBoundingBoxD Transform(float scale, Quaternion rotation, Vector3D translation)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Transform"><code>void Transform(MatrixD matrix)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(MyOrientedBoundingBox other)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Object obj)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.GetHashCode"><code>int GetHashCode()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.ToString"><code>string ToString()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(ref BoundingBox box)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(ref BoundingBoxD box)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(ref BoundingBox box)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(ref BoundingBoxD box)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Contains"><code>ContainmentType Contains(ref BoundingBox boxA, ref MyOrientedBoundingBox oboxB)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(ref MyOrientedBoundingBoxD other)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(ref MyOrientedBoundingBoxD other)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(BoundingFrustumD frustum)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(BoundingFrustumD frustum)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Contains"><code>ContainmentType Contains(BoundingFrustumD frustum, ref MyOrientedBoundingBoxD obox)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(ref BoundingSphereD sphere)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(ref BoundingSphereD sphere)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Contains"><code>ContainmentType Contains(ref BoundingSphere sphere, ref MyOrientedBoundingBox box)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>bool Contains(ref Vector3 point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>bool Contains(ref Vector3D point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>Nullable<double> Intersects(ref RayD ray)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>Nullable<double> Intersects(ref LineD line)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>PlaneIntersectionType Intersects(ref PlaneD plane)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.GetCorners"><code>void GetCorners(Vector3D[] corners, int startIndex)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.ContainsRelativeBox"><code>ContainmentType ContainsRelativeBox(ref Vector3D hA, ref Vector3D hB, ref MatrixD mB)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.ConvertToFrustum"><code>BoundingFrustumD ConvertToFrustum()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.GetAABB"><code>BoundingBoxD GetAABB()</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Create"><code>MyOrientedBoundingBoxD Create(BoundingBoxD boundingBox, MatrixD matrix)</code></a>_</td><td></td></tr>
</table>
