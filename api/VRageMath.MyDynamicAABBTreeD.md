← [Index](Api-Index)

#### MyDynamicAABBTreeD Class

```csharp
public class MyDynamicAABBTreeD
```

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

#### Example

#### Remarks

#### Fields

|Member|Description|
|---|---|
|[NullNode](VRageMath.MyDynamicAABBTreeD.NullNode)|A dynamic tree arranges data in a binary tree to accelerate queries such as volume queries and ray casts. Leafs are proxies with an BoundingBox. In the tree we expand the proxy BoundingBox by Settings.b2_fatAABBFactor so that the proxy BoundingBox is bigger than the client object. This allows the client object to move by small amounts without triggering a tree update. Nodes are pooled and relocatable, so we use node indices rather than pointers.|

#### Methods

|Member|Description|
|---|---|
|[AddProxy(ref BoundingBoxD, object, uint, bool)](VRageMath.MyDynamicAABBTreeD.AddProxy)|Create a proxy. Provide a tight fitting BoundingBox and a userData pointer.|
|[RemoveProxy(int)](VRageMath.MyDynamicAABBTreeD.RemoveProxy)|Destroy a proxy. This asserts if the id is invalid.|
|[MoveProxy(int, ref BoundingBoxD, Vector3D)](VRageMath.MyDynamicAABBTreeD.MoveProxy)|Move a proxy with a swepted BoundingBox. If the proxy has moved outside of its fattened BoundingBox, then the proxy is removed from the tree and re-inserted. Otherwise the function returns immediately.|
|[GetUserData(int)](VRageMath.MyDynamicAABBTreeD.GetUserData)||
|[GetRoot()](VRageMath.MyDynamicAABBTreeD.GetRoot)||
|[GetLeafCount(int)](VRageMath.MyDynamicAABBTreeD.GetLeafCount)||
|[GetNodeLeaves(int, List)](VRageMath.MyDynamicAABBTreeD.GetNodeLeaves)||
|[GetAabb(int)](VRageMath.MyDynamicAABBTreeD.GetAabb)||
|[GetChildren(int, ref int, ref int)](VRageMath.MyDynamicAABBTreeD.GetChildren)||
|[GetFatAABB(int, ref BoundingBoxD)](VRageMath.MyDynamicAABBTreeD.GetFatAABB)|Get the fat BoundingBox for a proxy.|
|[Query(Func, ref BoundingBoxD)](VRageMath.MyDynamicAABBTreeD.Query)||
|[QueryPoint(Func, ref Vector3D)](VRageMath.MyDynamicAABBTreeD.QueryPoint)||
|[CountLeaves(int)](VRageMath.MyDynamicAABBTreeD.CountLeaves)||
|[GetHeight()](VRageMath.MyDynamicAABBTreeD.GetHeight)||
|[IsRootNull()](VRageMath.MyDynamicAABBTreeD.IsRootNull)||
|[Balance(int)](VRageMath.MyDynamicAABBTreeD.Balance)||
|[OverlapAllFrustum(ref BoundingFrustumD, List, bool)](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|[OverlapAllFrustum(ref BoundingFrustumD, List, uint, bool)](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|[OverlapAllFrustumAny(ref BoundingFrustumD, List, bool)](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustumAny)||
|[OverlapAllFrustum(ref BoundingFrustumD, List, List)](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|[OverlapAllFrustum(ref BoundingFrustumD, T)](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|[OverlapAllFrustum(ref BoundingFrustumD, List, List, float, bool)](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|[OverlapAllFrustum(ref BoundingFrustumD, Action, float)](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|[OverlapAllFrustum(ref BoundingFrustumD, T, float)](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|[OverlapAllLineSegment(ref LineD, List, bool)](VRageMath.MyDynamicAABBTreeD.OverlapAllLineSegment)||
|[OverlapAllLineSegment(ref LineD, List, uint, bool)](VRageMath.MyDynamicAABBTreeD.OverlapAllLineSegment)||
|[OverlapAllBoundingBox(ref BoundingBoxD, List, uint, bool)](VRageMath.MyDynamicAABBTreeD.OverlapAllBoundingBox)||
|[OverlapAllBoundingBox(ref MyOrientedBoundingBoxD, List, uint, bool)](VRageMath.MyDynamicAABBTreeD.OverlapAllBoundingBox)||
|[OverlapsAnyLeafBoundingBox(ref BoundingBoxD)](VRageMath.MyDynamicAABBTreeD.OverlapsAnyLeafBoundingBox)||
|[GetAproximateClustersForAabb(ref BoundingBoxD, double, List)](VRageMath.MyDynamicAABBTreeD.GetAproximateClustersForAabb)||
|[OverlapAllBoundingSphere(ref BoundingSphereD, List, bool)](VRageMath.MyDynamicAABBTreeD.OverlapAllBoundingSphere)||
|[OverlapAllBoundingSphere(ref BoundingSphereD, Action)](VRageMath.MyDynamicAABBTreeD.OverlapAllBoundingSphere)||
|[GetAll(List, bool, List)](VRageMath.MyDynamicAABBTreeD.GetAll)||
|[GetAll(Action)](VRageMath.MyDynamicAABBTreeD.GetAll)||
|[GetAll(Action)](VRageMath.MyDynamicAABBTreeD.GetAll)||
|[GetAllNodeBounds(List)](VRageMath.MyDynamicAABBTreeD.GetAllNodeBounds)||
|[Clear()](VRageMath.MyDynamicAABBTreeD.Clear)||
|[Dispose()](VRageMath.MyDynamicAABBTreeD.Dispose)||

