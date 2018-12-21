← [Index](index.md)
# MyDynamicAABBTree Class
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Dynamic aabb tree implementation as a prunning structure
### Fields
|Member|Description|
|---|---|
|[`int NullNode`](VRageMath.NullNode.md)||
### Properties
|Member|Description|
|---|---|
|[`DictionaryValuesReader<int, DynamicTreeNode> Leaves`](VRageMath.Leaves.md)||
### Methods
|Member|Description|
|---|---|
|[`int AddProxy(ref BoundingBox aabb, Object userData, uint userFlags, bool rebalance)`](VRageMath.AddProxy.md)||
|[`void RemoveProxy(int proxyId)`](VRageMath.RemoveProxy.md)|Destroy a proxy. This asserts if the id is invalid.|
|[`bool MoveProxy(int proxyId, ref BoundingBox aabb, Vector3 displacement)`](VRageMath.MoveProxy.md)||
|[`T GetUserData<T>(int proxyId)`](VRageMath.GetUserData.md)||
|[`int GetRoot()`](VRageMath.GetRoot.md)||
|[`int GetLeafCount()`](VRageMath.GetLeafCount.md)||
|[`int GetLeafCount(int proxyId)`](VRageMath.GetLeafCount.md)||
|[`void GetNodeLeaves(int proxyId, List<int> children)`](VRageMath.GetNodeLeaves.md)||
|[`BoundingBox GetAabb(int proxyId)`](VRageMath.GetAabb.md)||
|[`void GetChildren(int proxyId, ref int left, ref int right)`](VRageMath.GetChildren.md)||
|[`void GetFatAABB(int proxyId, ref BoundingBox fatAABB)`](VRageMath.GetFatAABB.md)||
|[`void Query(Func<int, bool> callback, ref BoundingBox aabb)`](VRageMath.Query.md)||
|[`int CountLeaves(int nodeId)`](VRageMath.CountLeaves.md)||
|[`int GetHeight()`](VRageMath.GetHeight.md)||
|[`int Balance(int iA)`](VRageMath.Balance.md)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustum frustum, List<T> elementsList, bool clear)`](VRageMath.OverlapAllFrustum.md)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustum frustum, List<T> elementsList, uint requiredFlags, bool clear)`](VRageMath.OverlapAllFrustum.md)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustum frustum, List<T> elementsList, List<bool> isInsideList, bool clear)`](VRageMath.OverlapAllFrustum.md)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustum frustum, Action<T, bool> add)`](VRageMath.OverlapAllFrustum.md)||
|[`void OverlapAllFrustum<T, Op>(ref BoundingFrustum frustum, ref Op add)`](VRageMath.OverlapAllFrustum.md)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustum frustum, List<T> elementsList, List<bool> isInsideList, float tSqr, bool clear)`](VRageMath.OverlapAllFrustum.md)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustum frustum, Action<T, bool> add, float tSqr)`](VRageMath.OverlapAllFrustum.md)||
|[`void OverlapAllFrustum<T, Op>(ref BoundingFrustum frustum, float tSqr, ref Op add)`](VRageMath.OverlapAllFrustum.md)||
|[`void OverlapAllFrustumConservative<T>(ref BoundingFrustum frustum, List<T> elementsList, uint requiredFlags, bool clear)`](VRageMath.OverlapAllFrustumConservative.md)||
|[`void OverlapAllFrustumAny<T>(ref BoundingFrustum frustum, List<T> elementsList, bool clear)`](VRageMath.OverlapAllFrustumAny.md)||
|[`void OverlapAllLineSegment<T>(ref Line line, List<MyLineSegmentOverlapResult<T>> elementsList)`](VRageMath.OverlapAllLineSegment.md)||
|[`void OverlapAllLineSegment<T>(ref Line line, List<MyLineSegmentOverlapResult<T>> elementsList, uint requiredFlags)`](VRageMath.OverlapAllLineSegment.md)||
|[`void OverlapAllBoundingBox<T>(ref BoundingBox bbox, List<T> elementsList, uint requiredFlags, bool clear)`](VRageMath.OverlapAllBoundingBox.md)||
|[`bool OverlapsAnyLeafBoundingBox(ref BoundingBox bbox)`](VRageMath.OverlapsAnyLeafBoundingBox.md)||
|[`void OverlapSizeableClusters(ref BoundingBox bbox, List<BoundingBox> boundList, double minSize)`](VRageMath.OverlapSizeableClusters.md)||
|[`void OverlapAllBoundingSphere<T>(ref BoundingSphere sphere, List<T> overlapElementsList, bool clear)`](VRageMath.OverlapAllBoundingSphere.md)||
|[`void GetAll<T>(List<T> elementsList, bool clear, List<BoundingBox> boxsList)`](VRageMath.GetAll.md)||
|[`void GetAllNodeBounds(List<BoundingBox> boxsList)`](VRageMath.GetAllNodeBounds.md)||
|[`void Clear()`](VRageMath.Clear.md)||
|[`void Dispose()`](VRageMath.Dispose.md)||
