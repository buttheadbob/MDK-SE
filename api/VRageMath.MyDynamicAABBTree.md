← [Index](index.md)
# MyDynamicAABBTree Class
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Dynamic aabb tree implementation as a prunning structure
### Fields
|Member|Description|
|---|---|
|[`int NullNode`](VRageMath.NullNode)||
### Properties
|Member|Description|
|---|---|
|[`DictionaryValuesReader<int, DynamicTreeNode> Leaves`](VRageMath.Leaves)||
### Methods
|Member|Description|
|---|---|
|[`int AddProxy(ref BoundingBox aabb, Object userData, uint userFlags, bool rebalance)`](VRageMath.AddProxy)||
|[`void RemoveProxy(int proxyId)`](VRageMath.RemoveProxy)|Destroy a proxy. This asserts if the id is invalid.|
|[`bool MoveProxy(int proxyId, ref BoundingBox aabb, Vector3 displacement)`](VRageMath.MoveProxy)||
|[`T GetUserData<T>(int proxyId)`](VRageMath.GetUserData)||
|[`int GetRoot()`](VRageMath.GetRoot)||
|[`int GetLeafCount()`](VRageMath.GetLeafCount)||
|[`int GetLeafCount(int proxyId)`](VRageMath.GetLeafCount)||
|[`void GetNodeLeaves(int proxyId, List<int> children)`](VRageMath.GetNodeLeaves)||
|[`BoundingBox GetAabb(int proxyId)`](VRageMath.GetAabb)||
|[`void GetChildren(int proxyId, ref int left, ref int right)`](VRageMath.GetChildren)||
|[`void GetFatAABB(int proxyId, ref BoundingBox fatAABB)`](VRageMath.GetFatAABB)||
|[`void Query(Func<int, bool> callback, ref BoundingBox aabb)`](VRageMath.Query)||
|[`int CountLeaves(int nodeId)`](VRageMath.CountLeaves)||
|[`int GetHeight()`](VRageMath.GetHeight)||
|[`int Balance(int iA)`](VRageMath.Balance)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustum frustum, List<T> elementsList, bool clear)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustum frustum, List<T> elementsList, uint requiredFlags, bool clear)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustum frustum, List<T> elementsList, List<bool> isInsideList, bool clear)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustum frustum, Action<T, bool> add)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T, Op>(ref BoundingFrustum frustum, ref Op add)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustum frustum, List<T> elementsList, List<bool> isInsideList, float tSqr, bool clear)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustum frustum, Action<T, bool> add, float tSqr)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T, Op>(ref BoundingFrustum frustum, float tSqr, ref Op add)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustumConservative<T>(ref BoundingFrustum frustum, List<T> elementsList, uint requiredFlags, bool clear)`](VRageMath.OverlapAllFrustumConservative)||
|[`void OverlapAllFrustumAny<T>(ref BoundingFrustum frustum, List<T> elementsList, bool clear)`](VRageMath.OverlapAllFrustumAny)||
|[`void OverlapAllLineSegment<T>(ref Line line, List<MyLineSegmentOverlapResult<T>> elementsList)`](VRageMath.OverlapAllLineSegment)||
|[`void OverlapAllLineSegment<T>(ref Line line, List<MyLineSegmentOverlapResult<T>> elementsList, uint requiredFlags)`](VRageMath.OverlapAllLineSegment)||
|[`void OverlapAllBoundingBox<T>(ref BoundingBox bbox, List<T> elementsList, uint requiredFlags, bool clear)`](VRageMath.OverlapAllBoundingBox)||
|[`bool OverlapsAnyLeafBoundingBox(ref BoundingBox bbox)`](VRageMath.OverlapsAnyLeafBoundingBox)||
|[`void OverlapSizeableClusters(ref BoundingBox bbox, List<BoundingBox> boundList, double minSize)`](VRageMath.OverlapSizeableClusters)||
|[`void OverlapAllBoundingSphere<T>(ref BoundingSphere sphere, List<T> overlapElementsList, bool clear)`](VRageMath.OverlapAllBoundingSphere)||
|[`void GetAll<T>(List<T> elementsList, bool clear, List<BoundingBox> boxsList)`](VRageMath.GetAll)||
|[`void GetAllNodeBounds(List<BoundingBox> boxsList)`](VRageMath.GetAllNodeBounds)||
|[`void Clear()`](VRageMath.Clear)||
|[`void Dispose()`](VRageMath.Dispose)||
