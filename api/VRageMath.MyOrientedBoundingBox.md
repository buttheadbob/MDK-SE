← [Index](index)
# MyOrientedBoundingBox Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Center"><code>Vector3 Center</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.HalfExtent"><code>Vector3 HalfExtent</code></a>_</td><td></td></tr>
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
<tr><td>static _<a href="VRageMath.CreateFromBoundingBox"><code>MyOrientedBoundingBox CreateFromBoundingBox(BoundingBox box)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Transform"><code>MyOrientedBoundingBox Transform(Quaternion rotation, Vector3 translation)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Transform"><code>MyOrientedBoundingBox Transform(float scale, Quaternion rotation, Vector3 translation)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Transform"><code>void Transform(Matrix matrix)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(MyOrientedBoundingBox other)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Object obj)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.GetHashCode"><code>int GetHashCode()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.ToString"><code>string ToString()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(ref BoundingBox box)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(ref BoundingBox box)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Contains"><code>ContainmentType Contains(ref BoundingBox boxA, ref MyOrientedBoundingBox oboxB)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(ref MyOrientedBoundingBox other)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(ref MyOrientedBoundingBox other)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(BoundingFrustum frustum)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(BoundingFrustum frustum)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Contains"><code>ContainmentType Contains(BoundingFrustum frustum, ref MyOrientedBoundingBox obox)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>ContainmentType Contains(ref BoundingSphere sphere)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>bool Intersects(ref BoundingSphere sphere)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Contains"><code>ContainmentType Contains(ref BoundingSphere sphere, ref MyOrientedBoundingBox box)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Contains"><code>bool Contains(ref Vector3 point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>Nullable<float> Intersects(ref Ray ray)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>Nullable<float> Intersects(ref Line line)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Intersects"><code>PlaneIntersectionType Intersects(ref Plane plane)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.GetCorners"><code>void GetCorners(Vector3[] corners, int startIndex)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.ContainsRelativeBox"><code>ContainmentType ContainsRelativeBox(ref Vector3 hA, ref Vector3 hB, ref Matrix mB)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.ConvertToFrustum"><code>BoundingFrustum ConvertToFrustum()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.GetAABB"><code>BoundingBox GetAABB()</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Create"><code>MyOrientedBoundingBox Create(BoundingBox boundingBox, Matrix matrix)</code></a>_</td><td></td></tr>
</table>
