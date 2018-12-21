← [Index](index)
# MyDynamicAABBTree Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Dynamic aabb tree implementation as a prunning structure
### Fields
|Member|Description|
|---|---|
|static [`int NullNode`](VRageMath.NullNode)|A dynamic tree arranges data in a binary tree to accelerate queries such as volume queries and ray casts. Leafs are proxies with an BoundingBox. In the tree we expand the proxy BoundingBox by Settings.b2_fatAABBFactor so that the proxy BoundingBox is bigger than the client object. This allows the client object to move by small amounts without triggering a tree update. Nodes are pooled and relocatable, so we use node indices rather than pointers.|
### Properties
|Member|Description|
|---|---|
|[`DictionaryValuesReader<int, DynamicTreeNode> Leaves`](VRageMath.Leaves)||
### Methods
|Member|Description|
|---|---|
|[`int AddProxy(ref BoundingBox aabb, Object userData, uint userFlags, bool rebalance)`](VRageMath.AddProxy)|Create a proxy. Provide a tight fitting BoundingBox and a userData pointer.|
|[`void RemoveProxy(int proxyId)`](VRageMath.RemoveProxy)|Destroy a proxy. This asserts if the id is invalid.|
|[`bool MoveProxy(int proxyId, ref BoundingBox aabb, Vector3 displacement)`](VRageMath.MoveProxy)|Move a proxy with a swepted BoundingBox. If the proxy has moved outside of its fattened BoundingBox, then the proxy is removed from the tree and re-inserted. Otherwise the function returns immediately.|
|[`T GetUserData<T>(int proxyId)`](VRageMath.GetUserData)||
|[`int GetRoot()`](VRageMath.GetRoot)||
|[`int GetLeafCount()`](VRageMath.GetLeafCount)||
|[`int GetLeafCount(int proxyId)`](VRageMath.GetLeafCount)||
|[`void GetNodeLeaves(int proxyId, List<int> children)`](VRageMath.GetNodeLeaves)||
|[`BoundingBox GetAabb(int proxyId)`](VRageMath.GetAabb)||
|[`void GetChildren(int proxyId, ref int left, ref int right)`](VRageMath.GetChildren)||
|[`void GetFatAABB(int proxyId, ref BoundingBox fatAABB)`](VRageMath.GetFatAABB)|Get the fat BoundingBox for a proxy.|
|[`void Query(Func<int, bool> callback, ref BoundingBox aabb)`](VRageMath.Query)||
|[`int CountLeaves(int nodeId)`](VRageMath.CountLeaves)||
|[`int GetHeight()`](VRageMath.GetHeight)||
|[`int Balance(int iA)`](VRageMath.Balance)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustum frustum, List<T> elementsList, bool clear)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustum frustum, List<T> elementsList, uint requiredFlags, bool clear)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustum frustum, List<T> elementsList, List<bool> isInsideList, bool clear)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustum frustum, Action<T, bool> add)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T, Op>(ref BoundingFrustum frustum, ref Op add)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustum frustum, List<T> elementsList, List<bool> isInsideList, float tSqr, bool clear)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustum frustum, Action<T, bool> add, float tSqr)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T, Op>(ref BoundingFrustum frustum, float tSqr, ref Op add)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustumConservative<T>(ref BoundingFrustum frustum, List<T> elementsList, uint requiredFlags, bool clear)`](VRageMath.OverlapAllFrustumConservative)||
|[`void OverlapAllFrustumAny<T>(ref BoundingFrustum frustum, List<T> elementsList, bool clear)`](VRageMath.OverlapAllFrustumAny)||
|[`void OverlapAllLineSegment<T>(ref Line line, List<MyLineSegmentOverlapResult<T>> elementsList)`](VRageMath.OverlapAllLineSegment)||
|[`void OverlapAllLineSegment<T>(ref Line line, List<MyLineSegmentOverlapResult<T>> elementsList, uint requiredFlags)`](VRageMath.OverlapAllLineSegment)||
|[`void OverlapAllBoundingBox<T>(ref BoundingBox bbox, List<T> elementsList, uint requiredFlags, bool clear)`](VRageMath.OverlapAllBoundingBox)||
|[`bool OverlapsAnyLeafBoundingBox(ref BoundingBox bbox)`](VRageMath.OverlapsAnyLeafBoundingBox)||
|[`void OverlapSizeableClusters(ref BoundingBox bbox, List<BoundingBox> boundList, double minSize)`](VRageMath.OverlapSizeableClusters)||
|[`void OverlapAllBoundingSphere<T>(ref BoundingSphere sphere, List<T> overlapElementsList, bool clear)`](VRageMath.OverlapAllBoundingSphere)||
|[`void GetAll<T>(List<T> elementsList, bool clear, List<BoundingBox> boxsList)`](VRageMath.GetAll)||
|[`void GetAllNodeBounds(List<BoundingBox> boxsList)`](VRageMath.GetAllNodeBounds)||
|[`void Clear()`](VRageMath.Clear)||
|static [`void Dispose()`](VRageMath.Dispose)||
