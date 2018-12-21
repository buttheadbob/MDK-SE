← [Index](index)
# MyDynamicAABBTree Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Dynamic aabb tree implementation as a prunning structure
### Fields
<table style="width:100%;display:table">
<tr><td>static _<a href="VRageMath.NullNode"><code>int NullNode</code></a>_</td><td>A dynamic tree arranges data in a binary tree to accelerate queries such as volume queries and ray casts. Leafs are proxies with an BoundingBox. In the tree we expand the proxy BoundingBox by Settings.b2_fatAABBFactor so that the proxy BoundingBox is bigger than the client object. This allows the client object to move by small amounts without triggering a tree update. Nodes are pooled and relocatable, so we use node indices rather than pointers.</td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Leaves"><code>DictionaryValuesReader<int, DynamicTreeNode> Leaves</code></a>_</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.AddProxy"><code>int AddProxy(ref BoundingBox aabb, Object userData, uint userFlags, bool rebalance)</code></a>_</td><td>Create a proxy. Provide a tight fitting BoundingBox and a userData pointer.</td></tr>
<tr><td>_<a href="VRageMath.RemoveProxy"><code>void RemoveProxy(int proxyId)</code></a>_</td><td>Destroy a proxy. This asserts if the id is invalid.</td></tr>
<tr><td>_<a href="VRageMath.MoveProxy"><code>bool MoveProxy(int proxyId, ref BoundingBox aabb, Vector3 displacement)</code></a>_</td><td>Move a proxy with a swepted BoundingBox. If the proxy has moved outside of its fattened BoundingBox, then the proxy is removed from the tree and re-inserted. Otherwise the function returns immediately.</td></tr>
<tr><td>_<a href="VRageMath.GetUserData"><code>T GetUserData<T>(int proxyId)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.GetRoot"><code>int GetRoot()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.GetLeafCount"><code>int GetLeafCount()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.GetLeafCount"><code>int GetLeafCount(int proxyId)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.GetNodeLeaves"><code>void GetNodeLeaves(int proxyId, List<int> children)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.GetAabb"><code>BoundingBox GetAabb(int proxyId)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.GetChildren"><code>void GetChildren(int proxyId, ref int left, ref int right)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.GetFatAABB"><code>void GetFatAABB(int proxyId, ref BoundingBox fatAABB)</code></a>_</td><td>Get the fat BoundingBox for a proxy.</td></tr>
<tr><td>_<a href="VRageMath.Query"><code>void Query(Func<int, bool> callback, ref BoundingBox aabb)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.CountLeaves"><code>int CountLeaves(int nodeId)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.GetHeight"><code>int GetHeight()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Balance"><code>int Balance(int iA)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.OverlapAllFrustum"><code>void OverlapAllFrustum<T>(ref BoundingFrustum frustum, List<T> elementsList, bool clear)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.OverlapAllFrustum"><code>void OverlapAllFrustum<T>(ref BoundingFrustum frustum, List<T> elementsList, uint requiredFlags, bool clear)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.OverlapAllFrustum"><code>void OverlapAllFrustum<T>(ref BoundingFrustum frustum, List<T> elementsList, List<bool> isInsideList, bool clear)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.OverlapAllFrustum"><code>void OverlapAllFrustum<T>(ref BoundingFrustum frustum, Action<T, bool> add)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.OverlapAllFrustum"><code>void OverlapAllFrustum<T, Op>(ref BoundingFrustum frustum, ref Op add)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.OverlapAllFrustum"><code>void OverlapAllFrustum<T>(ref BoundingFrustum frustum, List<T> elementsList, List<bool> isInsideList, float tSqr, bool clear)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.OverlapAllFrustum"><code>void OverlapAllFrustum<T>(ref BoundingFrustum frustum, Action<T, bool> add, float tSqr)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.OverlapAllFrustum"><code>void OverlapAllFrustum<T, Op>(ref BoundingFrustum frustum, float tSqr, ref Op add)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.OverlapAllFrustumConservative"><code>void OverlapAllFrustumConservative<T>(ref BoundingFrustum frustum, List<T> elementsList, uint requiredFlags, bool clear)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.OverlapAllFrustumAny"><code>void OverlapAllFrustumAny<T>(ref BoundingFrustum frustum, List<T> elementsList, bool clear)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.OverlapAllLineSegment"><code>void OverlapAllLineSegment<T>(ref Line line, List<MyLineSegmentOverlapResult<T>> elementsList)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.OverlapAllLineSegment"><code>void OverlapAllLineSegment<T>(ref Line line, List<MyLineSegmentOverlapResult<T>> elementsList, uint requiredFlags)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.OverlapAllBoundingBox"><code>void OverlapAllBoundingBox<T>(ref BoundingBox bbox, List<T> elementsList, uint requiredFlags, bool clear)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.OverlapsAnyLeafBoundingBox"><code>bool OverlapsAnyLeafBoundingBox(ref BoundingBox bbox)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.OverlapSizeableClusters"><code>void OverlapSizeableClusters(ref BoundingBox bbox, List<BoundingBox> boundList, double minSize)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.OverlapAllBoundingSphere"><code>void OverlapAllBoundingSphere<T>(ref BoundingSphere sphere, List<T> overlapElementsList, bool clear)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.GetAll"><code>void GetAll<T>(List<T> elementsList, bool clear, List<BoundingBox> boxsList)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.GetAllNodeBounds"><code>void GetAllNodeBounds(List<BoundingBox> boxsList)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Clear"><code>void Clear()</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Dispose"><code>void Dispose()</code></a>_</td><td></td></tr>
</table>
