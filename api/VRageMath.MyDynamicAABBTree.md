← [Index](index)
# MyDynamicAABBTree Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Dynamic aabb tree implementation as a prunning structure
### Fields
<table style="width:100%;display:table">
<tr><td>static [`int NullNode`](VRageMath.NullNode)</td><td>A dynamic tree arranges data in a binary tree to accelerate queries such as volume queries and ray casts. Leafs are proxies with an BoundingBox. In the tree we expand the proxy BoundingBox by Settings.b2_fatAABBFactor so that the proxy BoundingBox is bigger than the client object. This allows the client object to move by small amounts without triggering a tree update. Nodes are pooled and relocatable, so we use node indices rather than pointers.</td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>[`DictionaryValuesReader<int, DynamicTreeNode> Leaves`](VRageMath.Leaves)</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>[`int AddProxy(ref BoundingBox aabb, Object userData, uint userFlags, bool rebalance)`](VRageMath.AddProxy)</td><td>Create a proxy. Provide a tight fitting BoundingBox and a userData pointer.</td></tr>
<tr><td>[`void RemoveProxy(int proxyId)`](VRageMath.RemoveProxy)</td><td>Destroy a proxy. This asserts if the id is invalid.</td></tr>
<tr><td>[`bool MoveProxy(int proxyId, ref BoundingBox aabb, Vector3 displacement)`](VRageMath.MoveProxy)</td><td>Move a proxy with a swepted BoundingBox. If the proxy has moved outside of its fattened BoundingBox, then the proxy is removed from the tree and re-inserted. Otherwise the function returns immediately.</td></tr>
<tr><td>[`T GetUserData<T>(int proxyId)`](VRageMath.GetUserData)</td><td></td></tr>
<tr><td>[`int GetRoot()`](VRageMath.GetRoot)</td><td></td></tr>
<tr><td>[`int GetLeafCount()`](VRageMath.GetLeafCount)</td><td></td></tr>
<tr><td>[`int GetLeafCount(int proxyId)`](VRageMath.GetLeafCount)</td><td></td></tr>
<tr><td>[`void GetNodeLeaves(int proxyId, List<int> children)`](VRageMath.GetNodeLeaves)</td><td></td></tr>
<tr><td>[`BoundingBox GetAabb(int proxyId)`](VRageMath.GetAabb)</td><td></td></tr>
<tr><td>[`void GetChildren(int proxyId, ref int left, ref int right)`](VRageMath.GetChildren)</td><td></td></tr>
<tr><td>[`void GetFatAABB(int proxyId, ref BoundingBox fatAABB)`](VRageMath.GetFatAABB)</td><td>Get the fat BoundingBox for a proxy.</td></tr>
<tr><td>[`void Query(Func<int, bool> callback, ref BoundingBox aabb)`](VRageMath.Query)</td><td></td></tr>
<tr><td>[`int CountLeaves(int nodeId)`](VRageMath.CountLeaves)</td><td></td></tr>
<tr><td>[`int GetHeight()`](VRageMath.GetHeight)</td><td></td></tr>
<tr><td>[`int Balance(int iA)`](VRageMath.Balance)</td><td></td></tr>
<tr><td>[`void OverlapAllFrustum<T>(ref BoundingFrustum frustum, List<T> elementsList, bool clear)`](VRageMath.OverlapAllFrustum)</td><td></td></tr>
<tr><td>[`void OverlapAllFrustum<T>(ref BoundingFrustum frustum, List<T> elementsList, uint requiredFlags, bool clear)`](VRageMath.OverlapAllFrustum)</td><td></td></tr>
<tr><td>[`void OverlapAllFrustum<T>(ref BoundingFrustum frustum, List<T> elementsList, List<bool> isInsideList, bool clear)`](VRageMath.OverlapAllFrustum)</td><td></td></tr>
<tr><td>[`void OverlapAllFrustum<T>(ref BoundingFrustum frustum, Action<T, bool> add)`](VRageMath.OverlapAllFrustum)</td><td></td></tr>
<tr><td>[`void OverlapAllFrustum<T, Op>(ref BoundingFrustum frustum, ref Op add)`](VRageMath.OverlapAllFrustum)</td><td></td></tr>
<tr><td>[`void OverlapAllFrustum<T>(ref BoundingFrustum frustum, List<T> elementsList, List<bool> isInsideList, float tSqr, bool clear)`](VRageMath.OverlapAllFrustum)</td><td></td></tr>
<tr><td>[`void OverlapAllFrustum<T>(ref BoundingFrustum frustum, Action<T, bool> add, float tSqr)`](VRageMath.OverlapAllFrustum)</td><td></td></tr>
<tr><td>[`void OverlapAllFrustum<T, Op>(ref BoundingFrustum frustum, float tSqr, ref Op add)`](VRageMath.OverlapAllFrustum)</td><td></td></tr>
<tr><td>[`void OverlapAllFrustumConservative<T>(ref BoundingFrustum frustum, List<T> elementsList, uint requiredFlags, bool clear)`](VRageMath.OverlapAllFrustumConservative)</td><td></td></tr>
<tr><td>[`void OverlapAllFrustumAny<T>(ref BoundingFrustum frustum, List<T> elementsList, bool clear)`](VRageMath.OverlapAllFrustumAny)</td><td></td></tr>
<tr><td>[`void OverlapAllLineSegment<T>(ref Line line, List<MyLineSegmentOverlapResult<T>> elementsList)`](VRageMath.OverlapAllLineSegment)</td><td></td></tr>
<tr><td>[`void OverlapAllLineSegment<T>(ref Line line, List<MyLineSegmentOverlapResult<T>> elementsList, uint requiredFlags)`](VRageMath.OverlapAllLineSegment)</td><td></td></tr>
<tr><td>[`void OverlapAllBoundingBox<T>(ref BoundingBox bbox, List<T> elementsList, uint requiredFlags, bool clear)`](VRageMath.OverlapAllBoundingBox)</td><td></td></tr>
<tr><td>[`bool OverlapsAnyLeafBoundingBox(ref BoundingBox bbox)`](VRageMath.OverlapsAnyLeafBoundingBox)</td><td></td></tr>
<tr><td>[`void OverlapSizeableClusters(ref BoundingBox bbox, List<BoundingBox> boundList, double minSize)`](VRageMath.OverlapSizeableClusters)</td><td></td></tr>
<tr><td>[`void OverlapAllBoundingSphere<T>(ref BoundingSphere sphere, List<T> overlapElementsList, bool clear)`](VRageMath.OverlapAllBoundingSphere)</td><td></td></tr>
<tr><td>[`void GetAll<T>(List<T> elementsList, bool clear, List<BoundingBox> boxsList)`](VRageMath.GetAll)</td><td></td></tr>
<tr><td>[`void GetAllNodeBounds(List<BoundingBox> boxsList)`](VRageMath.GetAllNodeBounds)</td><td></td></tr>
<tr><td>[`void Clear()`](VRageMath.Clear)</td><td></td></tr>
<tr><td>static [`void Dispose()`](VRageMath.Dispose)</td><td></td></tr>
</table>
