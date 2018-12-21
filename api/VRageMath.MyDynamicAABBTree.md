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
|[`DictionaryValuesReader<System.Int32, VRageMath.MyDynamicAABBTree+DynamicTreeNode> Leaves`](VRageMath.Leaves)||
### Methods
|Member|Description|
|---|---|
|[`int AddProxy(ref VRageMath.BoundingBox, System.Object, uint, bool)`](VRageMath.AddProxy)|Create a proxy. Provide a tight fitting BoundingBox and a userData pointer.|
|[`void RemoveProxy(int)`](VRageMath.RemoveProxy)|Destroy a proxy. This asserts if the id is invalid.|
|[`bool MoveProxy(int, ref VRageMath.BoundingBox, VRageMath.Vector3)`](VRageMath.MoveProxy)|Move a proxy with a swepted BoundingBox. If the proxy has moved outside of its fattened BoundingBox, then the proxy is removed from the tree and re-inserted. Otherwise the function returns immediately.|
|[`VRageMath.T GetUserData<T>(int)`](VRageMath.GetUserData)||
|[`int GetRoot()`](VRageMath.GetRoot)||
|[`int GetLeafCount()`](VRageMath.GetLeafCount)||
|[`int GetLeafCount(int)`](VRageMath.GetLeafCount)||
|[`void GetNodeLeaves(int, List<System.Int32>)`](VRageMath.GetNodeLeaves)||
|[`VRageMath.BoundingBox GetAabb(int)`](VRageMath.GetAabb)||
|[`void GetChildren(int, ref int, ref int)`](VRageMath.GetChildren)||
|[`void GetFatAABB(int, ref VRageMath.BoundingBox)`](VRageMath.GetFatAABB)|Get the fat BoundingBox for a proxy.|
|[`void Query(Func<System.Int32, System.Boolean>, ref VRageMath.BoundingBox)`](VRageMath.Query)||
|[`int CountLeaves(int)`](VRageMath.CountLeaves)||
|[`int GetHeight()`](VRageMath.GetHeight)||
|[`int Balance(int)`](VRageMath.Balance)||
|[`void OverlapAllFrustum<T>(ref VRageMath.BoundingFrustum, List<T>, bool)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T>(ref VRageMath.BoundingFrustum, List<T>, uint, bool)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T>(ref VRageMath.BoundingFrustum, List<T>, List<System.Boolean>, bool)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T>(ref VRageMath.BoundingFrustum, Action<T, System.Boolean>)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T, Op>(ref VRageMath.BoundingFrustum, ref VRageMath.Op)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T>(ref VRageMath.BoundingFrustum, List<T>, List<System.Boolean>, float, bool)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T>(ref VRageMath.BoundingFrustum, Action<T, System.Boolean>, float)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustum<T, Op>(ref VRageMath.BoundingFrustum, float, ref VRageMath.Op)`](VRageMath.OverlapAllFrustum)||
|[`void OverlapAllFrustumConservative<T>(ref VRageMath.BoundingFrustum, List<T>, uint, bool)`](VRageMath.OverlapAllFrustumConservative)||
|[`void OverlapAllFrustumAny<T>(ref VRageMath.BoundingFrustum, List<T>, bool)`](VRageMath.OverlapAllFrustumAny)||
|[`void OverlapAllLineSegment<T>(ref VRageMath.Line, List<>)`](VRageMath.OverlapAllLineSegment)||
|[`void OverlapAllLineSegment<T>(ref VRageMath.Line, List<>, uint)`](VRageMath.OverlapAllLineSegment)||
|[`void OverlapAllBoundingBox<T>(ref VRageMath.BoundingBox, List<T>, uint, bool)`](VRageMath.OverlapAllBoundingBox)||
|[`bool OverlapsAnyLeafBoundingBox(ref VRageMath.BoundingBox)`](VRageMath.OverlapsAnyLeafBoundingBox)||
|[`void OverlapSizeableClusters(ref VRageMath.BoundingBox, List<VRageMath.BoundingBox>, double)`](VRageMath.OverlapSizeableClusters)||
|[`void OverlapAllBoundingSphere<T>(ref VRageMath.BoundingSphere, List<T>, bool)`](VRageMath.OverlapAllBoundingSphere)||
|[`void GetAll<T>(List<T>, bool, List<VRageMath.BoundingBox>)`](VRageMath.GetAll)||
|[`void GetAllNodeBounds(List<VRageMath.BoundingBox>)`](VRageMath.GetAllNodeBounds)||
|[`void Clear()`](VRageMath.Clear)||
|static [`void Dispose()`](VRageMath.Dispose)||
