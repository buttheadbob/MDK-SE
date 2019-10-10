← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MyDynamicAABBTree Class

```csharp
public class MyDynamicAABBTree
```

Dynamic aabb tree implementation as a prunning structure

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

#### Fields

|Member|Description|
|---|---|
|[NullNode](VRageMath.MyDynamicAABBTree.NullNode)|A dynamic tree arranges data in a binary tree to accelerate queries such as volume queries and ray casts. Leafs are proxies with an BoundingBox. In the tree we expand the proxy BoundingBox by Settings.b2_fatAABBFactor so that the proxy BoundingBox is bigger than the client object. This allows the client object to move by small amounts without triggering a tree update. Nodes are pooled and relocatable, so we use node indices rather than pointers.|

#### Properties

|Member|Description|
|---|---|
|[Leaves](VRageMath.MyDynamicAABBTree.Leaves)||

#### Constructors

|Member|Description|
|---|---|
|[MyDynamicAABBTree()](VRageMath.MyDynamicAABBTree..ctor)||
|[MyDynamicAABBTree(Vector3, float)](VRageMath.MyDynamicAABBTree..ctor)||

#### Methods

|Member|Description|
|---|---|
|[AddProxy(ref BoundingBox, object, uint, bool)](VRageMath.MyDynamicAABBTree.AddProxy)|Create a proxy. Provide a tight fitting BoundingBox and a userData pointer.|
|[RemoveProxy(int)](VRageMath.MyDynamicAABBTree.RemoveProxy)|Destroy a proxy. This asserts if the id is invalid.|
|[MoveProxy(int, ref BoundingBox, Vector3)](VRageMath.MyDynamicAABBTree.MoveProxy)|Move a proxy with a swepted BoundingBox. If the proxy has moved outside of its fattened BoundingBox, then the proxy is removed from the tree and re-inserted. Otherwise the function returns immediately.|
|[GetUserData(int)](VRageMath.MyDynamicAABBTree.GetUserData)||
|[GetRoot()](VRageMath.MyDynamicAABBTree.GetRoot)||
|[GetLeafCount()](VRageMath.MyDynamicAABBTree.GetLeafCount)||
|[GetLeafCount(int)](VRageMath.MyDynamicAABBTree.GetLeafCount)||
|[GetNodeLeaves(int, List)](VRageMath.MyDynamicAABBTree.GetNodeLeaves)||
|[GetAabb(int)](VRageMath.MyDynamicAABBTree.GetAabb)||
|[GetChildren(int, out int, out int)](VRageMath.MyDynamicAABBTree.GetChildren)||
|[GetFatAABB(int, out BoundingBox)](VRageMath.MyDynamicAABBTree.GetFatAABB)|Get the fat BoundingBox for a proxy.|
|[Query(Func, ref BoundingBox)](VRageMath.MyDynamicAABBTree.Query)||
|[CountLeaves(int)](VRageMath.MyDynamicAABBTree.CountLeaves)||
|[GetHeight()](VRageMath.MyDynamicAABBTree.GetHeight)||
|[Balance(int)](VRageMath.MyDynamicAABBTree.Balance)||
|[OverlapAllFrustum(ref BoundingFrustum, List, bool)](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)||
|[OverlapAllFrustum(ref BoundingFrustum, List, uint, bool)](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)||
|[OverlapAllFrustum(ref BoundingFrustum, List, List, bool)](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)||
|[OverlapAllFrustum(ref BoundingFrustum, Action)](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)||
|[OverlapAllFrustum(ref BoundingFrustum, ref Op)](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)||
|[OverlapAllFrustum(ref BoundingFrustum, List, List, float, bool)](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)||
|[OverlapAllFrustum(ref BoundingFrustum, Action, float)](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)||
|[OverlapAllFrustum(ref BoundingFrustum, float, ref Op)](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)||
|[OverlapAllFrustumConservative(ref BoundingFrustum, List, uint, bool)](VRageMath.MyDynamicAABBTree.OverlapAllFrustumConservative)||
|[OverlapAllFrustumAny(ref BoundingFrustum, List, bool)](VRageMath.MyDynamicAABBTree.OverlapAllFrustumAny)||
|[OverlapAllLineSegment(ref Line, List)](VRageMath.MyDynamicAABBTree.OverlapAllLineSegment)||
|[OverlapAllLineSegment(ref Line, List, uint)](VRageMath.MyDynamicAABBTree.OverlapAllLineSegment)||
|[OverlapAllBoundingBox(ref BoundingBox, List, uint, bool)](VRageMath.MyDynamicAABBTree.OverlapAllBoundingBox)||
|[OverlapsAnyLeafBoundingBox(ref BoundingBox)](VRageMath.MyDynamicAABBTree.OverlapsAnyLeafBoundingBox)||
|[OverlapSizeableClusters(ref BoundingBox, List, double)](VRageMath.MyDynamicAABBTree.OverlapSizeableClusters)||
|[OverlapAllBoundingSphere(ref BoundingSphere, List, bool)](VRageMath.MyDynamicAABBTree.OverlapAllBoundingSphere)||
|[GetAll(List, bool, List)](VRageMath.MyDynamicAABBTree.GetAll)||
|[GetAllNodeBounds(List)](VRageMath.MyDynamicAABBTree.GetAllNodeBounds)||
|[Clear()](VRageMath.MyDynamicAABBTree.Clear)||
|[Dispose()](VRageMath.MyDynamicAABBTree.Dispose)||

