← [Index](index)
# MyDynamicAABBTreeD Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Dynamic aabb tree implementation as a prunning structure
### Fields
|Member|Description|
|---|---|
|static&nbsp;[`int&nbsp;NullNode`](VRageMath.NullNode)|A dynamic tree arranges data in a binary tree to accelerate queries such as volume queries and ray casts. Leafs are proxies with an BoundingBox. In the tree we expand the proxy BoundingBox by Settings.b2_fatAABBFactor so that the proxy BoundingBox is bigger than the client object. This allows the client object to move by small amounts without triggering a tree update. Nodes are pooled and relocatable, so we use node indices rather than pointers.|
### Methods
|Member|Description|
|---|---|
|[`int&nbsp;AddProxy(ref&nbsp;BoundingBoxD&nbsp;aabb,&nbsp;Object&nbsp;userData,&nbsp;uint&nbsp;userFlags,&nbsp;bool&nbsp;rebalance)`](VRageMath.AddProxy)|Create a proxy. Provide a tight fitting BoundingBox and a userData pointer.|
|[`void&nbsp;RemoveProxy(int&nbsp;proxyId)`](VRageMath.RemoveProxy)|Destroy a proxy. This asserts if the id is invalid.|
|[`bool&nbsp;MoveProxy(int&nbsp;proxyId,&nbsp;ref&nbsp;BoundingBoxD&nbsp;aabb,&nbsp;Vector3D&nbsp;displacement)`](VRageMath.MoveProxy)|Move a proxy with a swepted BoundingBox. If the proxy has moved outside of its fattened BoundingBox, then the proxy is removed from the tree and re-inserted. Otherwise the function returns immediately.|
|[`T&nbsp;GetUserData<T>(int&nbsp;proxyId)`](VRageMath.GetUserData)||
|[`int&nbsp;GetRoot()`](VRageMath.GetRoot)||
|[`int&nbsp;GetLeafCount(int&nbsp;proxyId)`](VRageMath.GetLeafCount)||
|[`void&nbsp;GetNodeLeaves(int&nbsp;proxyId,&nbsp;List<int>&nbsp;children)`](VRageMath.GetNodeLeaves)||
|[`BoundingBoxD&nbsp;GetAabb(int&nbsp;proxyId)`](VRageMath.GetAabb)||
|[`void&nbsp;GetChildren(int&nbsp;proxyId,&nbsp;ref&nbsp;int&nbsp;left,&nbsp;ref&nbsp;int&nbsp;right)`](VRageMath.GetChildren)||
|[`void&nbsp;GetFatAABB(int&nbsp;proxyId,&nbsp;ref&nbsp;BoundingBoxD&nbsp;fatAABB)`](VRageMath.GetFatAABB)|Get the fat BoundingBox for a proxy.|
|[`void&nbsp;Query(Func<int,&nbsp;bool>&nbsp;callback,&nbsp;ref&nbsp;BoundingBoxD&nbsp;aabb)`](VRageMath.Query)||
|[`void&nbsp;QueryPoint(Func<int,&nbsp;bool>&nbsp;callback,&nbsp;ref&nbsp;Vector3D&nbsp;point)`](VRageMath.QueryPoint)||
|[`int&nbsp;CountLeaves(int&nbsp;nodeId)`](VRageMath.CountLeaves)||
|[`int&nbsp;GetHeight()`](VRageMath.GetHeight)||
|[`bool&nbsp;IsRootNull()`](VRageMath.IsRootNull)||
|[`int&nbsp;Balance(int&nbsp;iA)`](VRageMath.Balance)||
|[`void&nbsp;OverlapAllFrustum<T>(ref&nbsp;BoundingFrustumD&nbsp;frustum,&nbsp;List<T>&nbsp;elementsList,&nbsp;bool&nbsp;clear)`](VRageMath.OverlapAllFrustum)||
|[`void&nbsp;OverlapAllFrustum<T>(ref&nbsp;BoundingFrustumD&nbsp;frustum,&nbsp;List<T>&nbsp;elementsList,&nbsp;uint&nbsp;requiredFlags,&nbsp;bool&nbsp;clear)`](VRageMath.OverlapAllFrustum)||
|[`void&nbsp;OverlapAllFrustumAny<T>(ref&nbsp;BoundingFrustumD&nbsp;frustum,&nbsp;List<T>&nbsp;elementsList,&nbsp;bool&nbsp;clear)`](VRageMath.OverlapAllFrustumAny)||
|[`void&nbsp;OverlapAllFrustum<T>(ref&nbsp;BoundingFrustumD&nbsp;frustum,&nbsp;List<T>&nbsp;elementsList,&nbsp;List<bool>&nbsp;isInsideList)`](VRageMath.OverlapAllFrustum)||
|[`void&nbsp;OverlapAllFrustum<T>(ref&nbsp;BoundingFrustumD&nbsp;frustum,&nbsp;T&nbsp;results)`](VRageMath.OverlapAllFrustum)||
|[`void&nbsp;OverlapAllFrustum<T>(ref&nbsp;BoundingFrustumD&nbsp;frustum,&nbsp;List<T>&nbsp;elementsList,&nbsp;List<bool>&nbsp;isInsideList,&nbsp;float&nbsp;tSqr,&nbsp;bool&nbsp;clear)`](VRageMath.OverlapAllFrustum)||
|[`void&nbsp;OverlapAllFrustum<T>(ref&nbsp;BoundingFrustumD&nbsp;frustum,&nbsp;Action<T,&nbsp;bool>&nbsp;add,&nbsp;float&nbsp;tSqr)`](VRageMath.OverlapAllFrustum)||
|[`void&nbsp;OverlapAllFrustum<T>(ref&nbsp;BoundingFrustumD&nbsp;frustum,&nbsp;T&nbsp;results,&nbsp;float&nbsp;tSqr)`](VRageMath.OverlapAllFrustum)||
|[`void&nbsp;OverlapAllLineSegment<T>(ref&nbsp;LineD&nbsp;line,&nbsp;List<MyLineSegmentOverlapResult<T>>&nbsp;elementsList,&nbsp;bool&nbsp;clear)`](VRageMath.OverlapAllLineSegment)||
|[`void&nbsp;OverlapAllLineSegment<T>(ref&nbsp;LineD&nbsp;line,&nbsp;List<MyLineSegmentOverlapResult<T>>&nbsp;elementsList,&nbsp;uint&nbsp;requiredFlags,&nbsp;bool&nbsp;clear)`](VRageMath.OverlapAllLineSegment)||
|[`void&nbsp;OverlapAllBoundingBox<T>(ref&nbsp;BoundingBoxD&nbsp;bbox,&nbsp;List<T>&nbsp;elementsList,&nbsp;uint&nbsp;requiredFlags,&nbsp;bool&nbsp;clear)`](VRageMath.OverlapAllBoundingBox)||
|[`void&nbsp;OverlapAllBoundingBox<T>(ref&nbsp;MyOrientedBoundingBoxD&nbsp;obb,&nbsp;List<T>&nbsp;elementsList,&nbsp;uint&nbsp;requiredFlags,&nbsp;bool&nbsp;clear)`](VRageMath.OverlapAllBoundingBox)||
|[`bool&nbsp;OverlapsAnyLeafBoundingBox(ref&nbsp;BoundingBoxD&nbsp;bbox)`](VRageMath.OverlapsAnyLeafBoundingBox)||
|[`void&nbsp;GetAproximateClustersForAabb(ref&nbsp;BoundingBoxD&nbsp;bbox,&nbsp;double&nbsp;minSize,&nbsp;List<BoundingBoxD>&nbsp;boundList)`](VRageMath.GetAproximateClustersForAabb)||
|[`void&nbsp;OverlapAllBoundingSphere<T>(ref&nbsp;BoundingSphereD&nbsp;sphere,&nbsp;List<T>&nbsp;overlapElementsList,&nbsp;bool&nbsp;clear)`](VRageMath.OverlapAllBoundingSphere)||
|[`void&nbsp;OverlapAllBoundingSphere<T>(ref&nbsp;BoundingSphereD&nbsp;sphere,&nbsp;Action<T>&nbsp;addAction)`](VRageMath.OverlapAllBoundingSphere)||
|[`void&nbsp;GetAll<T>(List<T>&nbsp;elementsList,&nbsp;bool&nbsp;clear,&nbsp;List<BoundingBoxD>&nbsp;boxsList)`](VRageMath.GetAll)||
|[`void&nbsp;GetAll<T>(Action<T>&nbsp;add)`](VRageMath.GetAll)||
|[`void&nbsp;GetAll<T>(Action<T,&nbsp;BoundingBoxD>&nbsp;add)`](VRageMath.GetAll)||
|[`void&nbsp;GetAllNodeBounds(List<BoundingBoxD>&nbsp;boxsList)`](VRageMath.GetAllNodeBounds)||
|[`void&nbsp;Clear()`](VRageMath.Clear)||
|static&nbsp;[`void&nbsp;Dispose()`](VRageMath.Dispose)||
