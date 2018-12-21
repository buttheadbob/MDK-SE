← [Index](Api-Index)
# MyDynamicAABBTree Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Dynamic aabb tree implementation as a prunning structure
### Fields
|Member|Description|
|---|---|
|[`NullNode`](VRageMath.NullNode)|A dynamic tree arranges data in a binary tree to accelerate queries such as volume queries and ray casts. Leafs are proxies with an BoundingBox. In the tree we expand the proxy BoundingBox by Settings.b2_fatAABBFactor so that the proxy BoundingBox is bigger than the client object. This allows the client object to move by small amounts without triggering a tree update. Nodes are pooled and relocatable, so we use node indices rather than pointers.|
### Properties
|Member|Description|
|---|---|
|[`Leaves`](VRageMath.Leaves)||
### Methods
|Member|Description|
|---|---|
|[`AddProxy(ref BoundingBox, Object, uint, bool)`](VRageMath.AddProxy)|Create a proxy. Provide a tight fitting BoundingBox and a userData pointer.|
|[`RemoveProxy(int)`](VRageMath.RemoveProxy)|Destroy a proxy. This asserts if the id is invalid.|
|[`MoveProxy(int, ref BoundingBox, Vector3)`](VRageMath.MoveProxy)|Move a proxy with a swepted BoundingBox. If the proxy has moved outside of its fattened BoundingBox, then the proxy is removed from the tree and re-inserted. Otherwise the function returns immediately.|
|[`GetUserData<T>(int)`](VRageMath.GetUserData)||
|[`GetRoot()`](VRageMath.GetRoot)||
|[`GetLeafCount()`](VRageMath.GetLeafCount)||
|[`GetLeafCount(int)`](VRageMath.GetLeafCount)||
|[`GetNodeLeaves(int, List<int>)`](VRageMath.GetNodeLeaves)||
|[`GetAabb(int)`](VRageMath.GetAabb)||
|[`GetChildren(int, ref int, ref int)`](VRageMath.GetChildren)||
|[`GetFatAABB(int, ref BoundingBox)`](VRageMath.GetFatAABB)|Get the fat BoundingBox for a proxy.|
|[`Query(Func<int, bool>, ref BoundingBox)`](VRageMath.Query)||
|[`CountLeaves(int)`](VRageMath.CountLeaves)||
|[`GetHeight()`](VRageMath.GetHeight)||
|[`Balance(int)`](VRageMath.Balance)||
|[`OverlapAllFrustum<T>(ref BoundingFrustum, List<T>, bool)`](VRageMath.OverlapAllFrustum)||
|[`OverlapAllFrustum<T>(ref BoundingFrustum, List<T>, uint, bool)`](VRageMath.OverlapAllFrustum)||
|[`OverlapAllFrustum<T>(ref BoundingFrustum, List<T>, List<bool>, bool)`](VRageMath.OverlapAllFrustum)||
|[`OverlapAllFrustum<T>(ref BoundingFrustum, Action<T, bool>)`](VRageMath.OverlapAllFrustum)||
|[`OverlapAllFrustum<T, Op>(ref BoundingFrustum, ref Op)`](VRageMath.OverlapAllFrustum)||
|[`OverlapAllFrustum<T>(ref BoundingFrustum, List<T>, List<bool>, float, bool)`](VRageMath.OverlapAllFrustum)||
|[`OverlapAllFrustum<T>(ref BoundingFrustum, Action<T, bool>, float)`](VRageMath.OverlapAllFrustum)||
|[`OverlapAllFrustum<T, Op>(ref BoundingFrustum, float, ref Op)`](VRageMath.OverlapAllFrustum)||
|[`OverlapAllFrustumConservative<T>(ref BoundingFrustum, List<T>, uint, bool)`](VRageMath.OverlapAllFrustumConservative)||
|[`OverlapAllFrustumAny<T>(ref BoundingFrustum, List<T>, bool)`](VRageMath.OverlapAllFrustumAny)||
|[`OverlapAllLineSegment<T>(ref Line, List<MyLineSegmentOverlapResult<T>>)`](VRageMath.OverlapAllLineSegment)||
|[`OverlapAllLineSegment<T>(ref Line, List<MyLineSegmentOverlapResult<T>>, uint)`](VRageMath.OverlapAllLineSegment)||
|[`OverlapAllBoundingBox<T>(ref BoundingBox, List<T>, uint, bool)`](VRageMath.OverlapAllBoundingBox)||
|[`OverlapsAnyLeafBoundingBox(ref BoundingBox)`](VRageMath.OverlapsAnyLeafBoundingBox)||
|[`OverlapSizeableClusters(ref BoundingBox, List<BoundingBox>, double)`](VRageMath.OverlapSizeableClusters)||
|[`OverlapAllBoundingSphere<T>(ref BoundingSphere, List<T>, bool)`](VRageMath.OverlapAllBoundingSphere)||
|[`GetAll<T>(List<T>, bool, List<BoundingBox>)`](VRageMath.GetAll)||
|[`GetAllNodeBounds(List<BoundingBox>)`](VRageMath.GetAllNodeBounds)||
|[`Clear()`](VRageMath.Clear)||
|[`Dispose()`](VRageMath.Dispose)||
