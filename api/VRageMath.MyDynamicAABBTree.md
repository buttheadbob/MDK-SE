← [Index](index)
# MyDynamicAABBTree Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Dynamic aabb tree implementation as a prunning structure
### Fields
|Member|Description|
|---|---|
|static&nbsp;[`int&nbsp;NullNode`](VRageMath.NullNode)|A dynamic tree arranges data in a binary tree to accelerate queries such as volume queries and ray casts. Leafs are proxies with an BoundingBox. In the tree we expand the proxy BoundingBox by Settings.b2_fatAABBFactor so that the proxy BoundingBox is bigger than the client object. This allows the client object to move by small amounts without triggering a tree update. Nodes are pooled and relocatable, so we use node indices rather than pointers.|
### Properties
|Member|Description|
|---|---|
|[`DictionaryValuesReader<int,&nbsp;DynamicTreeNode>&nbsp;Leaves`](VRageMath.Leaves)||
### Methods
|Member|Description|
|---|---|
|[`int&nbsp;AddProxy(ref&nbsp;BoundingBox&nbsp;aabb,&nbsp;Object&nbsp;userData,&nbsp;uint&nbsp;userFlags,&nbsp;bool&nbsp;rebalance)`](VRageMath.AddProxy)|Create a proxy. Provide a tight fitting BoundingBox and a userData pointer.|
|[`void&nbsp;RemoveProxy(int&nbsp;proxyId)`](VRageMath.RemoveProxy)|Destroy a proxy. This asserts if the id is invalid.|
|[`bool&nbsp;MoveProxy(int&nbsp;proxyId,&nbsp;ref&nbsp;BoundingBox&nbsp;aabb,&nbsp;Vector3&nbsp;displacement)`](VRageMath.MoveProxy)|Move a proxy with a swepted BoundingBox. If the proxy has moved outside of its fattened BoundingBox, then the proxy is removed from the tree and re-inserted. Otherwise the function returns immediately.|
|[`T&nbsp;GetUserData<T>(int&nbsp;proxyId)`](VRageMath.GetUserData)||
|[`int&nbsp;GetRoot()`](VRageMath.GetRoot)||
|[`int&nbsp;GetLeafCount()`](VRageMath.GetLeafCount)||
|[`int&nbsp;GetLeafCount(int&nbsp;proxyId)`](VRageMath.GetLeafCount)||
|[`void&nbsp;GetNodeLeaves(int&nbsp;proxyId,&nbsp;List<int>&nbsp;children)`](VRageMath.GetNodeLeaves)||
|[`BoundingBox&nbsp;GetAabb(int&nbsp;proxyId)`](VRageMath.GetAabb)||
|[`void&nbsp;GetChildren(int&nbsp;proxyId,&nbsp;ref&nbsp;int&nbsp;left,&nbsp;ref&nbsp;int&nbsp;right)`](VRageMath.GetChildren)||
|[`void&nbsp;GetFatAABB(int&nbsp;proxyId,&nbsp;ref&nbsp;BoundingBox&nbsp;fatAABB)`](VRageMath.GetFatAABB)|Get the fat BoundingBox for a proxy.|
|[`void&nbsp;Query(Func<int,&nbsp;bool>&nbsp;callback,&nbsp;ref&nbsp;BoundingBox&nbsp;aabb)`](VRageMath.Query)||
|[`int&nbsp;CountLeaves(int&nbsp;nodeId)`](VRageMath.CountLeaves)||
|[`int&nbsp;GetHeight()`](VRageMath.GetHeight)||
|[`int&nbsp;Balance(int&nbsp;iA)`](VRageMath.Balance)||
|[`void&nbsp;OverlapAllFrustum<T>(ref&nbsp;BoundingFrustum&nbsp;frustum,&nbsp;List<T>&nbsp;elementsList,&nbsp;bool&nbsp;clear)`](VRageMath.OverlapAllFrustum)||
|[`void&nbsp;OverlapAllFrustum<T>(ref&nbsp;BoundingFrustum&nbsp;frustum,&nbsp;List<T>&nbsp;elementsList,&nbsp;uint&nbsp;requiredFlags,&nbsp;bool&nbsp;clear)`](VRageMath.OverlapAllFrustum)||
|[`void&nbsp;OverlapAllFrustum<T>(ref&nbsp;BoundingFrustum&nbsp;frustum,&nbsp;List<T>&nbsp;elementsList,&nbsp;List<bool>&nbsp;isInsideList,&nbsp;bool&nbsp;clear)`](VRageMath.OverlapAllFrustum)||
|[`void&nbsp;OverlapAllFrustum<T>(ref&nbsp;BoundingFrustum&nbsp;frustum,&nbsp;Action<T,&nbsp;bool>&nbsp;add)`](VRageMath.OverlapAllFrustum)||
|[`void&nbsp;OverlapAllFrustum<T,&nbsp;Op>(ref&nbsp;BoundingFrustum&nbsp;frustum,&nbsp;ref&nbsp;Op&nbsp;add)`](VRageMath.OverlapAllFrustum)||
|[`void&nbsp;OverlapAllFrustum<T>(ref&nbsp;BoundingFrustum&nbsp;frustum,&nbsp;List<T>&nbsp;elementsList,&nbsp;List<bool>&nbsp;isInsideList,&nbsp;float&nbsp;tSqr,&nbsp;bool&nbsp;clear)`](VRageMath.OverlapAllFrustum)||
|[`void&nbsp;OverlapAllFrustum<T>(ref&nbsp;BoundingFrustum&nbsp;frustum,&nbsp;Action<T,&nbsp;bool>&nbsp;add,&nbsp;float&nbsp;tSqr)`](VRageMath.OverlapAllFrustum)||
|[`void&nbsp;OverlapAllFrustum<T,&nbsp;Op>(ref&nbsp;BoundingFrustum&nbsp;frustum,&nbsp;float&nbsp;tSqr,&nbsp;ref&nbsp;Op&nbsp;add)`](VRageMath.OverlapAllFrustum)||
|[`void&nbsp;OverlapAllFrustumConservative<T>(ref&nbsp;BoundingFrustum&nbsp;frustum,&nbsp;List<T>&nbsp;elementsList,&nbsp;uint&nbsp;requiredFlags,&nbsp;bool&nbsp;clear)`](VRageMath.OverlapAllFrustumConservative)||
|[`void&nbsp;OverlapAllFrustumAny<T>(ref&nbsp;BoundingFrustum&nbsp;frustum,&nbsp;List<T>&nbsp;elementsList,&nbsp;bool&nbsp;clear)`](VRageMath.OverlapAllFrustumAny)||
|[`void&nbsp;OverlapAllLineSegment<T>(ref&nbsp;Line&nbsp;line,&nbsp;List<MyLineSegmentOverlapResult<T>>&nbsp;elementsList)`](VRageMath.OverlapAllLineSegment)||
|[`void&nbsp;OverlapAllLineSegment<T>(ref&nbsp;Line&nbsp;line,&nbsp;List<MyLineSegmentOverlapResult<T>>&nbsp;elementsList,&nbsp;uint&nbsp;requiredFlags)`](VRageMath.OverlapAllLineSegment)||
|[`void&nbsp;OverlapAllBoundingBox<T>(ref&nbsp;BoundingBox&nbsp;bbox,&nbsp;List<T>&nbsp;elementsList,&nbsp;uint&nbsp;requiredFlags,&nbsp;bool&nbsp;clear)`](VRageMath.OverlapAllBoundingBox)||
|[`bool&nbsp;OverlapsAnyLeafBoundingBox(ref&nbsp;BoundingBox&nbsp;bbox)`](VRageMath.OverlapsAnyLeafBoundingBox)||
|[`void&nbsp;OverlapSizeableClusters(ref&nbsp;BoundingBox&nbsp;bbox,&nbsp;List<BoundingBox>&nbsp;boundList,&nbsp;double&nbsp;minSize)`](VRageMath.OverlapSizeableClusters)||
|[`void&nbsp;OverlapAllBoundingSphere<T>(ref&nbsp;BoundingSphere&nbsp;sphere,&nbsp;List<T>&nbsp;overlapElementsList,&nbsp;bool&nbsp;clear)`](VRageMath.OverlapAllBoundingSphere)||
|[`void&nbsp;GetAll<T>(List<T>&nbsp;elementsList,&nbsp;bool&nbsp;clear,&nbsp;List<BoundingBox>&nbsp;boxsList)`](VRageMath.GetAll)||
|[`void&nbsp;GetAllNodeBounds(List<BoundingBox>&nbsp;boxsList)`](VRageMath.GetAllNodeBounds)||
|[`void&nbsp;Clear()`](VRageMath.Clear)||
|static&nbsp;[`void&nbsp;Dispose()`](VRageMath.Dispose)||
