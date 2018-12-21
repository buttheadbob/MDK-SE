← [Index](index.md)
#MyDynamicAABBTreeD Class
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
##Summary
Dynamic aabb tree implementation as a prunning structure
###Fields
|Member|Description|
|---|---|
|[`int NullNode`](VRageMath.NullNode.md)||
###Methods
|Member|Description|
|---|---|
|[`int AddProxy(ref BoundingBoxD aabb, Object userData, uint userFlags, bool rebalance)`](VRageMath.AddProxy.md)||
|[`void RemoveProxy(int proxyId)`](VRageMath.RemoveProxy.md)|Destroy a proxy. This asserts if the id is invalid.|
|[`bool MoveProxy(int proxyId, ref BoundingBoxD aabb, Vector3D displacement)`](VRageMath.MoveProxy.md)||
|[`T GetUserData<T>(int proxyId)`](VRageMath.GetUserData.md)||
|[`int GetRoot()`](VRageMath.GetRoot.md)||
|[`int GetLeafCount(int proxyId)`](VRageMath.GetLeafCount.md)||
|[`void GetNodeLeaves(int proxyId, List<int> children)`](VRageMath.GetNodeLeaves.md)||
|[`BoundingBoxD GetAabb(int proxyId)`](VRageMath.GetAabb.md)||
|[`void GetChildren(int proxyId, ref int left, ref int right)`](VRageMath.GetChildren.md)||
|[`void GetFatAABB(int proxyId, ref BoundingBoxD fatAABB)`](VRageMath.GetFatAABB.md)||
|[`void Query(Func<int, bool> callback, ref BoundingBoxD aabb)`](VRageMath.Query.md)||
|[`void QueryPoint(Func<int, bool> callback, ref Vector3D point)`](VRageMath.QueryPoint.md)||
|[`int CountLeaves(int nodeId)`](VRageMath.CountLeaves.md)||
|[`int GetHeight()`](VRageMath.GetHeight.md)||
|[`bool IsRootNull()`](VRageMath.IsRootNull.md)||
|[`int Balance(int iA)`](VRageMath.Balance.md)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustumD frustum, List<T> elementsList, bool clear)`](VRageMath.OverlapAllFrustum.md)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustumD frustum, List<T> elementsList, uint requiredFlags, bool clear)`](VRageMath.OverlapAllFrustum.md)||
|[`void OverlapAllFrustumAny<T>(ref BoundingFrustumD frustum, List<T> elementsList, bool clear)`](VRageMath.OverlapAllFrustumAny.md)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustumD frustum, List<T> elementsList, List<bool> isInsideList)`](VRageMath.OverlapAllFrustum.md)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustumD frustum, T results)`](VRageMath.OverlapAllFrustum.md)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustumD frustum, List<T> elementsList, List<bool> isInsideList, float tSqr, bool clear)`](VRageMath.OverlapAllFrustum.md)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustumD frustum, Action<T, bool> add, float tSqr)`](VRageMath.OverlapAllFrustum.md)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustumD frustum, T results, float tSqr)`](VRageMath.OverlapAllFrustum.md)||
|[`void OverlapAllLineSegment<T>(ref LineD line, List<MyLineSegmentOverlapResult<T>> elementsList, bool clear)`](VRageMath.OverlapAllLineSegment.md)||
|[`void OverlapAllLineSegment<T>(ref LineD line, List<MyLineSegmentOverlapResult<T>> elementsList, uint requiredFlags, bool clear)`](VRageMath.OverlapAllLineSegment.md)||
|[`void OverlapAllBoundingBox<T>(ref BoundingBoxD bbox, List<T> elementsList, uint requiredFlags, bool clear)`](VRageMath.OverlapAllBoundingBox.md)||
|[`void OverlapAllBoundingBox<T>(ref MyOrientedBoundingBoxD obb, List<T> elementsList, uint requiredFlags, bool clear)`](VRageMath.OverlapAllBoundingBox.md)||
|[`bool OverlapsAnyLeafBoundingBox(ref BoundingBoxD bbox)`](VRageMath.OverlapsAnyLeafBoundingBox.md)||
|[`void GetAproximateClustersForAabb(ref BoundingBoxD bbox, double minSize, List<BoundingBoxD> boundList)`](VRageMath.GetAproximateClustersForAabb.md)||
|[`void OverlapAllBoundingSphere<T>(ref BoundingSphereD sphere, List<T> overlapElementsList, bool clear)`](VRageMath.OverlapAllBoundingSphere.md)||
|[`void OverlapAllBoundingSphere<T>(ref BoundingSphereD sphere, Action<T> addAction)`](VRageMath.OverlapAllBoundingSphere.md)||
|[`void GetAll<T>(List<T> elementsList, bool clear, List<BoundingBoxD> boxsList)`](VRageMath.GetAll.md)||
|[`void GetAll<T>(Action<T> add)`](VRageMath.GetAll.md)||
|[`void GetAll<T>(Action<T, BoundingBoxD> add)`](VRageMath.GetAll.md)||
|[`void GetAllNodeBounds(List<BoundingBoxD> boxsList)`](VRageMath.GetAllNodeBounds.md)||
|[`void Clear()`](VRageMath.Clear.md)||
|[`void Dispose()`](VRageMath.Dispose.md)||
