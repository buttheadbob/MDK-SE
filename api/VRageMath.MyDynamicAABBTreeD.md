← [Index](index)
# MyDynamicAABBTreeD Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Dynamic aabb tree implementation as a prunning structure
### Fields
<table style="width: 100%">
<tr><td>static [`int NullNode`](VRageMath.NullNode)</td><td>A dynamic tree arranges data in a binary tree to accelerate queries such as volume queries and ray casts. Leafs are proxies with an BoundingBox. In the tree we expand the proxy BoundingBox by Settings.b2_fatAABBFactor so that the proxy BoundingBox is bigger than the client object. This allows the client object to move by small amounts without triggering a tree update. Nodes are pooled and relocatable, so we use node indices rather than pointers.</td></tr>
</table>
### Methods
<table style="width: 100%">
<tr><td>[`int AddProxy(ref BoundingBoxD aabb, Object userData, uint userFlags, bool rebalance)`](VRageMath.AddProxy)</td><td>Create a proxy. Provide a tight fitting BoundingBox and a userData pointer.</td></tr>
<tr><td>[`void RemoveProxy(int proxyId)`](VRageMath.RemoveProxy)</td><td>Destroy a proxy. This asserts if the id is invalid.</td></tr>
<tr><td>[`bool MoveProxy(int proxyId, ref BoundingBoxD aabb, Vector3D displacement)`](VRageMath.MoveProxy)</td><td>Move a proxy with a swepted BoundingBox. If the proxy has moved outside of its fattened BoundingBox, then the proxy is removed from the tree and re-inserted. Otherwise the function returns immediately.</td></tr>
<tr><td>[`T GetUserData<T>(int proxyId)`](VRageMath.GetUserData)</td><td></td></tr>
<tr><td>[`int GetRoot()`](VRageMath.GetRoot)</td><td></td></tr>
<tr><td>[`int GetLeafCount(int proxyId)`](VRageMath.GetLeafCount)</td><td></td></tr>
<tr><td>[`void GetNodeLeaves(int proxyId, List<int> children)`](VRageMath.GetNodeLeaves)</td><td></td></tr>
<tr><td>[`BoundingBoxD GetAabb(int proxyId)`](VRageMath.GetAabb)</td><td></td></tr>
<tr><td>[`void GetChildren(int proxyId, ref int left, ref int right)`](VRageMath.GetChildren)</td><td></td></tr>
<tr><td>[`void GetFatAABB(int proxyId, ref BoundingBoxD fatAABB)`](VRageMath.GetFatAABB)</td><td>Get the fat BoundingBox for a proxy.</td></tr>
<tr><td>[`void Query(Func<int, bool> callback, ref BoundingBoxD aabb)`](VRageMath.Query)</td><td></td></tr>
<tr><td>[`void QueryPoint(Func<int, bool> callback, ref Vector3D point)`](VRageMath.QueryPoint)</td><td></td></tr>
<tr><td>[`int CountLeaves(int nodeId)`](VRageMath.CountLeaves)</td><td></td></tr>
<tr><td>[`int GetHeight()`](VRageMath.GetHeight)</td><td></td></tr>
<tr><td>[`bool IsRootNull()`](VRageMath.IsRootNull)</td><td></td></tr>
<tr><td>[`int Balance(int iA)`](VRageMath.Balance)</td><td></td></tr>
<tr><td>[`void OverlapAllFrustum<T>(ref BoundingFrustumD frustum, List<T> elementsList, bool clear)`](VRageMath.OverlapAllFrustum)</td><td></td></tr>
<tr><td>[`void OverlapAllFrustum<T>(ref BoundingFrustumD frustum, List<T> elementsList, uint requiredFlags, bool clear)`](VRageMath.OverlapAllFrustum)</td><td></td></tr>
<tr><td>[`void OverlapAllFrustumAny<T>(ref BoundingFrustumD frustum, List<T> elementsList, bool clear)`](VRageMath.OverlapAllFrustumAny)</td><td></td></tr>
<tr><td>[`void OverlapAllFrustum<T>(ref BoundingFrustumD frustum, List<T> elementsList, List<bool> isInsideList)`](VRageMath.OverlapAllFrustum)</td><td></td></tr>
<tr><td>[`void OverlapAllFrustum<T>(ref BoundingFrustumD frustum, T results)`](VRageMath.OverlapAllFrustum)</td><td></td></tr>
<tr><td>[`void OverlapAllFrustum<T>(ref BoundingFrustumD frustum, List<T> elementsList, List<bool> isInsideList, float tSqr, bool clear)`](VRageMath.OverlapAllFrustum)</td><td></td></tr>
<tr><td>[`void OverlapAllFrustum<T>(ref BoundingFrustumD frustum, Action<T, bool> add, float tSqr)`](VRageMath.OverlapAllFrustum)</td><td></td></tr>
<tr><td>[`void OverlapAllFrustum<T>(ref BoundingFrustumD frustum, T results, float tSqr)`](VRageMath.OverlapAllFrustum)</td><td></td></tr>
<tr><td>[`void OverlapAllLineSegment<T>(ref LineD line, List<MyLineSegmentOverlapResult<T>> elementsList, bool clear)`](VRageMath.OverlapAllLineSegment)</td><td></td></tr>
<tr><td>[`void OverlapAllLineSegment<T>(ref LineD line, List<MyLineSegmentOverlapResult<T>> elementsList, uint requiredFlags, bool clear)`](VRageMath.OverlapAllLineSegment)</td><td></td></tr>
<tr><td>[`void OverlapAllBoundingBox<T>(ref BoundingBoxD bbox, List<T> elementsList, uint requiredFlags, bool clear)`](VRageMath.OverlapAllBoundingBox)</td><td></td></tr>
<tr><td>[`void OverlapAllBoundingBox<T>(ref MyOrientedBoundingBoxD obb, List<T> elementsList, uint requiredFlags, bool clear)`](VRageMath.OverlapAllBoundingBox)</td><td></td></tr>
<tr><td>[`bool OverlapsAnyLeafBoundingBox(ref BoundingBoxD bbox)`](VRageMath.OverlapsAnyLeafBoundingBox)</td><td></td></tr>
<tr><td>[`void GetAproximateClustersForAabb(ref BoundingBoxD bbox, double minSize, List<BoundingBoxD> boundList)`](VRageMath.GetAproximateClustersForAabb)</td><td></td></tr>
<tr><td>[`void OverlapAllBoundingSphere<T>(ref BoundingSphereD sphere, List<T> overlapElementsList, bool clear)`](VRageMath.OverlapAllBoundingSphere)</td><td></td></tr>
<tr><td>[`void OverlapAllBoundingSphere<T>(ref BoundingSphereD sphere, Action<T> addAction)`](VRageMath.OverlapAllBoundingSphere)</td><td></td></tr>
<tr><td>[`void GetAll<T>(List<T> elementsList, bool clear, List<BoundingBoxD> boxsList)`](VRageMath.GetAll)</td><td></td></tr>
<tr><td>[`void GetAll<T>(Action<T> add)`](VRageMath.GetAll)</td><td></td></tr>
<tr><td>[`void GetAll<T>(Action<T, BoundingBoxD> add)`](VRageMath.GetAll)</td><td></td></tr>
<tr><td>[`void GetAllNodeBounds(List<BoundingBoxD> boxsList)`](VRageMath.GetAllNodeBounds)</td><td></td></tr>
<tr><td>[`void Clear()`](VRageMath.Clear)</td><td></td></tr>
<tr><td>static [`void Dispose()`](VRageMath.Dispose)</td><td></td></tr>
</table>
