← [Index](index)
# MyDynamicAABBTreeD Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Dynamic aabb tree implementation as a prunning structure
### Fields
|Member|Description|
|---|---|
|[`int NullNode`](VRageMath.NullNode)||
### Methods
|Member|Description|
|---|---|
|[`int AddProxy(ref BoundingBoxD aabb, Object userData, uint userFlags, bool rebalance)`](VRageMath.AddProxy)||
|[`void RemoveProxy(int proxyId)`](VRageMath.RemoveProxy)|Destroy a proxy. This asserts if the id is invalid.|
|[`bool MoveProxy(int proxyId, ref BoundingBoxD aabb, Vector3D displacement)`](VRageMath.MoveProxy)||
|[`T GetUserData<T>(int proxyId)`](VRageMath.GetUserData)||
|[`int GetRoot()`](VRageMath.GetRoot)||
|[`int GetLeafCount(int proxyId)`](VRageMath.GetLeafCount)||
|[`void GetNodeLeaves(int proxyId, List<int> children)`](VRageMath.GetNodeLeaves)||
|[`BoundingBoxD GetAabb(int proxyId)`](VRageMath.GetAabb)||
|[`void GetChildren(int proxyId, ref int left, ref int right)`](VRageMath.GetChildren)||
|[`void GetFatAABB(int proxyId, ref BoundingBoxD fatAABB)`](VRageMath.GetFatAABB)||
|[`void Query(Func<int, bool> callback, ref BoundingBoxD aabb)`](VRageMath.Query)||
|[`void QueryPoint(Func<int, bool> callback, ref Vector3D point)`](VRageMath.QueryPoint)||
|[`int CountLeaves(int nodeId)`](VRageMath.CountLeaves)||
|[`int GetHeight()`](VRageMath.GetHeight)||
|[`bool IsRootNull()`](VRageMath.IsRootNull)||
|[`int Balance(int iA)`](VRageMath.Balance)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustumD frustum, List<T> elementsList, bool clear)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustumD frustum, List<T> elementsList, uint requiredFlags, bool clear)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustumAny<T>(ref BoundingFrustumD frustum, List<T> elementsList, bool clear)`](VRageMath.OverlapAllFrustumAny)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustumD frustum, List<T> elementsList, List<bool> isInsideList)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustumD frustum, T results)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustumD frustum, List<T> elementsList, List<bool> isInsideList, float tSqr, bool clear)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustumD frustum, Action<T, bool> add, float tSqr)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T>(ref BoundingFrustumD frustum, T results, float tSqr)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllLineSegment<T>(ref LineD line, List<MyLineSegmentOverlapResult<T>> elementsList, bool clear)`](VRageMath.OverlapAllLineSegment)||
|[`void OverlapAllLineSegment<T>(ref LineD line, List<MyLineSegmentOverlapResult<T>> elementsList, uint requiredFlags, bool clear)`](VRageMath.OverlapAllLineSegment)||
|[`void OverlapAllBoundingBox<T>(ref BoundingBoxD bbox, List<T> elementsList, uint requiredFlags, bool clear)`](VRageMath.OverlapAllBoundingBox)||
|[`void OverlapAllBoundingBox<T>(ref MyOrientedBoundingBoxD obb, List<T> elementsList, uint requiredFlags, bool clear)`](VRageMath.OverlapAllBoundingBox)||
|[`bool OverlapsAnyLeafBoundingBox(ref BoundingBoxD bbox)`](VRageMath.OverlapsAnyLeafBoundingBox)||
|[`void GetAproximateClustersForAabb(ref BoundingBoxD bbox, double minSize, List<BoundingBoxD> boundList)`](VRageMath.GetAproximateClustersForAabb)||
|[`void OverlapAllBoundingSphere<T>(ref BoundingSphereD sphere, List<T> overlapElementsList, bool clear)`](VRageMath.OverlapAllBoundingSphere)||
|[`void OverlapAllBoundingSphere<T>(ref BoundingSphereD sphere, Action<T> addAction)`](VRageMath.OverlapAllBoundingSphere)||
|[`void GetAll<T>(List<T> elementsList, bool clear, List<BoundingBoxD> boxsList)`](VRageMath.GetAll)||
|[`void GetAll<T>(Action<T> add)`](VRageMath.GetAll)||
|[`void GetAll<T>(Action<T, BoundingBoxD> add)`](VRageMath.GetAll)||
|[`void GetAllNodeBounds(List<BoundingBoxD> boxsList)`](VRageMath.GetAllNodeBounds)||
|[`void Clear()`](VRageMath.Clear)||
|[`void Dispose()`](VRageMath.Dispose)||
