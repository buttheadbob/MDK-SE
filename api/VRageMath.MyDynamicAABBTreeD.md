← [Index](index)
# MyDynamicAABBTreeD Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Dynamic aabb tree implementation as a prunning structure
### Fields
|Member|Description|
|---|---|
|[`NullNode`](VRageMath.NullNode)|A dynamic tree arranges data in a binary tree to accelerate queries such as volume queries and ray casts. Leafs are proxies with an BoundingBox. In the tree we expand the proxy BoundingBox by Settings.b2_fatAABBFactor so that the proxy BoundingBox is bigger than the client object. This allows the client object to move by small amounts without triggering a tree update. Nodes are pooled and relocatable, so we use node indices rather than pointers.|
### Methods
|Member|Description|
|---|---|
|[`AddProxy(ref BoundingBoxD, Object, uint, bool)`](VRageMath.AddProxy)|Create a proxy. Provide a tight fitting BoundingBox and a userData pointer.|
|[`RemoveProxy(int)`](VRageMath.RemoveProxy)|Destroy a proxy. This asserts if the id is invalid.|
|[`MoveProxy(int, ref BoundingBoxD, Vector3D)`](VRageMath.MoveProxy)|Move a proxy with a swepted BoundingBox. If the proxy has moved outside of its fattened BoundingBox, then the proxy is removed from the tree and re-inserted. Otherwise the function returns immediately.|
|[`GetUserData<T>(int)`](VRageMath.GetUserData)||
|[`GetRoot()`](VRageMath.GetRoot)||
|[`GetLeafCount(int)`](VRageMath.GetLeafCount)||
|[`GetNodeLeaves(int, List<int>)`](VRageMath.GetNodeLeaves)||
|[`GetAabb(int)`](VRageMath.GetAabb)||
|[`GetChildren(int, ref int, ref int)`](VRageMath.GetChildren)||
|[`GetFatAABB(int, ref BoundingBoxD)`](VRageMath.GetFatAABB)|Get the fat BoundingBox for a proxy.|
|[`Query(Func<int, bool>, ref BoundingBoxD)`](VRageMath.Query)||
|[`QueryPoint(Func<int, bool>, ref Vector3D)`](VRageMath.QueryPoint)||
|[`CountLeaves(int)`](VRageMath.CountLeaves)||
|[`GetHeight()`](VRageMath.GetHeight)||
|[`IsRootNull()`](VRageMath.IsRootNull)||
|[`Balance(int)`](VRageMath.Balance)||
|[`OverlapAllFrustum<T>(ref BoundingFrustumD, List<T>, bool)`](VRageMath.OverlapAllFrustum)||
|[`OverlapAllFrustum<T>(ref BoundingFrustumD, List<T>, uint, bool)`](VRageMath.OverlapAllFrustum)||
|[`OverlapAllFrustumAny<T>(ref BoundingFrustumD, List<T>, bool)`](VRageMath.OverlapAllFrustumAny)||
|[`OverlapAllFrustum<T>(ref BoundingFrustumD, List<T>, List<bool>)`](VRageMath.OverlapAllFrustum)||
|[`OverlapAllFrustum<T>(ref BoundingFrustumD, T)`](VRageMath.OverlapAllFrustum)||
|[`OverlapAllFrustum<T>(ref BoundingFrustumD, List<T>, List<bool>, float, bool)`](VRageMath.OverlapAllFrustum)||
|[`OverlapAllFrustum<T>(ref BoundingFrustumD, Action<T, bool>, float)`](VRageMath.OverlapAllFrustum)||
|[`OverlapAllFrustum<T>(ref BoundingFrustumD, T, float)`](VRageMath.OverlapAllFrustum)||
|[`OverlapAllLineSegment<T>(ref LineD, List<MyLineSegmentOverlapResult<T>>, bool)`](VRageMath.OverlapAllLineSegment)||
|[`OverlapAllLineSegment<T>(ref LineD, List<MyLineSegmentOverlapResult<T>>, uint, bool)`](VRageMath.OverlapAllLineSegment)||
|[`OverlapAllBoundingBox<T>(ref BoundingBoxD, List<T>, uint, bool)`](VRageMath.OverlapAllBoundingBox)||
|[`OverlapAllBoundingBox<T>(ref MyOrientedBoundingBoxD, List<T>, uint, bool)`](VRageMath.OverlapAllBoundingBox)||
|[`OverlapsAnyLeafBoundingBox(ref BoundingBoxD)`](VRageMath.OverlapsAnyLeafBoundingBox)||
|[`GetAproximateClustersForAabb(ref BoundingBoxD, double, List<BoundingBoxD>)`](VRageMath.GetAproximateClustersForAabb)||
|[`OverlapAllBoundingSphere<T>(ref BoundingSphereD, List<T>, bool)`](VRageMath.OverlapAllBoundingSphere)||
|[`OverlapAllBoundingSphere<T>(ref BoundingSphereD, Action<T>)`](VRageMath.OverlapAllBoundingSphere)||
|[`GetAll<T>(List<T>, bool, List<BoundingBoxD>)`](VRageMath.GetAll)||
|[`GetAll<T>(Action<T>)`](VRageMath.GetAll)||
|[`GetAll<T>(Action<T, BoundingBoxD>)`](VRageMath.GetAll)||
|[`GetAllNodeBounds(List<BoundingBoxD>)`](VRageMath.GetAllNodeBounds)||
|[`Clear()`](VRageMath.Clear)||
|[`Dispose()`](VRageMath.Dispose)||
