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
|[static int NullNode](VRageMath.MyDynamicAABBTree.NullNode)|A dynamic tree arranges data in a binary tree to accelerate queries such as volume queries and ray casts. Leafs are proxies with an BoundingBox. In the tree we expand the proxy BoundingBox by Settings.b2_fatAABBFactor so that the proxy BoundingBox is bigger than the client object. This allows the client object to move by small amounts without triggering a tree update. Nodes are pooled and relocatable, so we use node indices rather than pointers.|

#### Properties

|Member|Description|
|---|---|
|[DictionaryValuesReader Leaves { get; }](VRageMath.MyDynamicAABBTree.Leaves)||
|[ReadOnlySpan Nodes { get; }](VRageMath.MyDynamicAABBTree.Nodes)||

#### Constructors

|Member|Description|
|---|---|
|[MyDynamicAABBTree()](VRageMath.MyDynamicAABBTree..ctor)||
|[MyDynamicAABBTree(Vector3, [float])](VRageMath.MyDynamicAABBTree..ctor)||

#### Methods

|Member|Description|
|---|---|
|[static void Dispose()](VRageMath.MyDynamicAABBTree.Dispose)||
|[int AddProxy(ref BoundingBox, object, uint, [bool])](VRageMath.MyDynamicAABBTree.AddProxy)|Create a proxy. Provide a tight fitting BoundingBox and a userData pointer.|
|[int Balance(int)](VRageMath.MyDynamicAABBTree.Balance)||
|[void Clear()](VRageMath.MyDynamicAABBTree.Clear)||
|[int CountLeaves(int)](VRageMath.MyDynamicAABBTree.CountLeaves)||
|[BoundingBox GetAabb(int)](VRageMath.MyDynamicAABBTree.GetAabb)||
|[void GetAll(List, bool, [List])](VRageMath.MyDynamicAABBTree.GetAll)||
|[void GetAllNodeBounds(List)](VRageMath.MyDynamicAABBTree.GetAllNodeBounds)||
|[void GetChildren(int, out int, out int)](VRageMath.MyDynamicAABBTree.GetChildren)||
|[void GetFatAABB(int, out BoundingBox)](VRageMath.MyDynamicAABBTree.GetFatAABB)|Get the fat BoundingBox for a proxy.|
|[int GetHeight()](VRageMath.MyDynamicAABBTree.GetHeight)||
|[int GetLeafCount()](VRageMath.MyDynamicAABBTree.GetLeafCount)||
|[int GetLeafCount(int)](VRageMath.MyDynamicAABBTree.GetLeafCount)||
|[void GetNodeLeaves(int, List)](VRageMath.MyDynamicAABBTree.GetNodeLeaves)||
|[int GetRoot()](VRageMath.MyDynamicAABBTree.GetRoot)||
|[T GetUserData(int)](VRageMath.MyDynamicAABBTree.GetUserData)||
|[bool MoveProxy(int, ref BoundingBox, Vector3)](VRageMath.MyDynamicAABBTree.MoveProxy)|Move a proxy with a swepted BoundingBox. If the proxy has moved outside of its fattened BoundingBox, then the proxy is removed from the tree and re-inserted. Otherwise the function returns immediately.|
|[void OverlapAllBoundingBox(ref BoundingBox, List, [uint], [bool])](VRageMath.MyDynamicAABBTree.OverlapAllBoundingBox)||
|[void OverlapAllBoundingSphere(ref BoundingSphere, List, [bool])](VRageMath.MyDynamicAABBTree.OverlapAllBoundingSphere)||
|[void OverlapAllFrustum(ref BoundingFrustum, List, [bool])](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)||
|[void OverlapAllFrustum(ref BoundingFrustum, List, uint, [bool])](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)||
|[void OverlapAllFrustum(ref BoundingFrustum, List, List, [bool])](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)||
|[void OverlapAllFrustum(ref BoundingFrustum, Action)](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)||
|[void OverlapAllFrustum(ref BoundingFrustum, ref Op)](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)||
|[void OverlapAllFrustum(ref BoundingFrustum, List, List, float, [bool])](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)||
|[void OverlapAllFrustum(ref BoundingFrustum, Action, float)](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)||
|[void OverlapAllFrustum(ref BoundingFrustum, float, ref Op)](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)||
|[void OverlapAllFrustumAny(ref BoundingFrustum, List, [bool])](VRageMath.MyDynamicAABBTree.OverlapAllFrustumAny)||
|[void OverlapAllFrustumConservative(ref BoundingFrustum, List, uint, [bool])](VRageMath.MyDynamicAABBTree.OverlapAllFrustumConservative)||
|[void OverlapAllLineSegment(ref Line, List)](VRageMath.MyDynamicAABBTree.OverlapAllLineSegment)||
|[void OverlapAllLineSegment(ref Line, List, uint)](VRageMath.MyDynamicAABBTree.OverlapAllLineSegment)||
|[bool OverlapsAnyLeafBoundingBox(ref BoundingBox)](VRageMath.MyDynamicAABBTree.OverlapsAnyLeafBoundingBox)||
|[void OverlapSizeableClusters(ref BoundingBox, List, double)](VRageMath.MyDynamicAABBTree.OverlapSizeableClusters)||
|[void Query(Func, ref BoundingBox)](VRageMath.MyDynamicAABBTree.Query)||
|[void RemoveProxy(int)](VRageMath.MyDynamicAABBTree.RemoveProxy)|Destroy a proxy. This asserts if the id is invalid.|

