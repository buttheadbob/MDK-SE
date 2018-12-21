← [Index](index)
# MyDynamicAABBTreeD Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Dynamic aabb tree implementation as a prunning structure
### Fields
|Member|Description|
|---|---|
|static [`int NullNode`](VRageMath.NullNode)|A dynamic tree arranges data in a binary tree to accelerate queries such as volume queries and ray casts. Leafs are proxies with an BoundingBox. In the tree we expand the proxy BoundingBox by Settings.b2_fatAABBFactor so that the proxy BoundingBox is bigger than the client object. This allows the client object to move by small amounts without triggering a tree update. Nodes are pooled and relocatable, so we use node indices rather than pointers.|
### Methods
|Member|Description|
|---|---|
|[`int AddProxy(ref VRageMath.BoundingBoxD, System.Object, uint, bool)`](VRageMath.AddProxy)|Create a proxy. Provide a tight fitting BoundingBox and a userData pointer.|
|[`void RemoveProxy(int)`](VRageMath.RemoveProxy)|Destroy a proxy. This asserts if the id is invalid.|
|[`bool MoveProxy(int, ref VRageMath.BoundingBoxD, VRageMath.Vector3D)`](VRageMath.MoveProxy)|Move a proxy with a swepted BoundingBox. If the proxy has moved outside of its fattened BoundingBox, then the proxy is removed from the tree and re-inserted. Otherwise the function returns immediately.|
|[`VRageMath.T GetUserData<T>(int)`](VRageMath.GetUserData)||
|[`int GetRoot()`](VRageMath.GetRoot)||
|[`int GetLeafCount(int)`](VRageMath.GetLeafCount)||
|[`void GetNodeLeaves(int, List<System.Int32>)`](VRageMath.GetNodeLeaves)||
|[`VRageMath.BoundingBoxD GetAabb(int)`](VRageMath.GetAabb)||
|[`void GetChildren(int, ref int, ref int)`](VRageMath.GetChildren)||
|[`void GetFatAABB(int, ref VRageMath.BoundingBoxD)`](VRageMath.GetFatAABB)|Get the fat BoundingBox for a proxy.|
|[`void Query(Func<System.Int32, System.Boolean>, ref VRageMath.BoundingBoxD)`](VRageMath.Query)||
|[`void QueryPoint(Func<System.Int32, System.Boolean>, ref VRageMath.Vector3D)`](VRageMath.QueryPoint)||
|[`int CountLeaves(int)`](VRageMath.CountLeaves)||
|[`int GetHeight()`](VRageMath.GetHeight)||
|[`bool IsRootNull()`](VRageMath.IsRootNull)||
|[`int Balance(int)`](VRageMath.Balance)||
|[`void OverlapAllFrustum<T>(ref VRageMath.BoundingFrustumD, List<T>, bool)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T>(ref VRageMath.BoundingFrustumD, List<T>, uint, bool)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustumAny<T>(ref VRageMath.BoundingFrustumD, List<T>, bool)`](VRageMath.OverlapAllFrustumAny)||
|[`void OverlapAllFrustum<T>(ref VRageMath.BoundingFrustumD, List<T>, List<System.Boolean>)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T>(ref VRageMath.BoundingFrustumD, VRageMath.T)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T>(ref VRageMath.BoundingFrustumD, List<T>, List<System.Boolean>, float, bool)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T>(ref VRageMath.BoundingFrustumD, Action<T, System.Boolean>, float)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T>(ref VRageMath.BoundingFrustumD, VRageMath.T, float)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllLineSegment<T>(ref VRageMath.LineD, List<>, bool)`](VRageMath.OverlapAllLineSegment)||
|[`void OverlapAllLineSegment<T>(ref VRageMath.LineD, List<>, uint, bool)`](VRageMath.OverlapAllLineSegment)||
|[`void OverlapAllBoundingBox<T>(ref VRageMath.BoundingBoxD, List<T>, uint, bool)`](VRageMath.OverlapAllBoundingBox)||
|[`void OverlapAllBoundingBox<T>(ref VRageMath.MyOrientedBoundingBoxD, List<T>, uint, bool)`](VRageMath.OverlapAllBoundingBox)||
|[`bool OverlapsAnyLeafBoundingBox(ref VRageMath.BoundingBoxD)`](VRageMath.OverlapsAnyLeafBoundingBox)||
|[`void GetAproximateClustersForAabb(ref VRageMath.BoundingBoxD, double, List<VRageMath.BoundingBoxD>)`](VRageMath.GetAproximateClustersForAabb)||
|[`void OverlapAllBoundingSphere<T>(ref VRageMath.BoundingSphereD, List<T>, bool)`](VRageMath.OverlapAllBoundingSphere)||
|[`void OverlapAllBoundingSphere<T>(ref VRageMath.BoundingSphereD, Action<T>)`](VRageMath.OverlapAllBoundingSphere)||
|[`void GetAll<T>(List<T>, bool, List<VRageMath.BoundingBoxD>)`](VRageMath.GetAll)||
|[`void GetAll<T>(Action<T>)`](VRageMath.GetAll)||
|[`void GetAll<T>(Action<T, VRageMath.BoundingBoxD>)`](VRageMath.GetAll)||
|[`void GetAllNodeBounds(List<VRageMath.BoundingBoxD>)`](VRageMath.GetAllNodeBounds)||
|[`void Clear()`](VRageMath.Clear)||
|static [`void Dispose()`](VRageMath.Dispose)||
