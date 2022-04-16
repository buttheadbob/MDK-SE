← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MyDynamicAABBTree Class

```csharp
public class MyDynamicAABBTree
```

Dynamic aabb tree implementation as a prunning structure

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

#### Fields

[static int NullNode](VRageMath.MyDynamicAABBTree.NullNode)

> A dynamic tree arranges data in a binary tree to accelerate queries such as volume queries and ray casts. Leafs are proxies with an BoundingBox. In the tree we expand the proxy BoundingBox by Settings.b2_fatAABBFactor so that the proxy BoundingBox is bigger than the client object. This allows the client object to move by small amounts without triggering a tree update. Nodes are pooled and relocatable, so we use node indices rather than pointers.

#### Properties

[DictionaryValuesReader&lt;int, DynamicTreeNode&gt; Leaves { get; }](VRageMath.MyDynamicAABBTree.Leaves)

> 

[ReadOnlySpan&lt;DynamicTreeNode&gt; Nodes { get; }](VRageMath.MyDynamicAABBTree.Nodes)

> 

#### Constructors

[MyDynamicAABBTree()](VRageMath.MyDynamicAABBTree..ctor)

> 

[MyDynamicAABBTree(Vector3, float = 1)](VRageMath.MyDynamicAABBTree..ctor)

> 

#### Methods

[static void Dispose()](VRageMath.MyDynamicAABBTree.Dispose)

> 

[int AddProxy(ref BoundingBox, object, uint, bool = default)](VRageMath.MyDynamicAABBTree.AddProxy)

> Create a proxy. Provide a tight fitting BoundingBox and a userData pointer.

[int Balance(int)](VRageMath.MyDynamicAABBTree.Balance)

> 

[void Clear()](VRageMath.MyDynamicAABBTree.Clear)

> 

[int CountLeaves(int)](VRageMath.MyDynamicAABBTree.CountLeaves)

> 

[BoundingBox GetAabb(int)](VRageMath.MyDynamicAABBTree.GetAabb)

> 

[void GetAll&lt;T&gt;(List&lt;T&gt;, bool, List&lt;BoundingBox&gt; = null)](VRageMath.MyDynamicAABBTree.GetAll)

> 

[void GetAllNodeBounds(List&lt;BoundingBox&gt;)](VRageMath.MyDynamicAABBTree.GetAllNodeBounds)

> 

[void GetChildren(int, out int, out int)](VRageMath.MyDynamicAABBTree.GetChildren)

> 

[void GetFatAABB(int, out BoundingBox)](VRageMath.MyDynamicAABBTree.GetFatAABB)

> Get the fat BoundingBox for a proxy.

[int GetHeight()](VRageMath.MyDynamicAABBTree.GetHeight)

> 

[int GetLeafCount()](VRageMath.MyDynamicAABBTree.GetLeafCount)

> 

[int GetLeafCount(int)](VRageMath.MyDynamicAABBTree.GetLeafCount)

> 

[void GetNodeLeaves(int, List&lt;int&gt;)](VRageMath.MyDynamicAABBTree.GetNodeLeaves)

> 

[int GetRoot()](VRageMath.MyDynamicAABBTree.GetRoot)

> 

[T GetUserData&lt;T&gt;(int)](VRageMath.MyDynamicAABBTree.GetUserData)

> 

[bool MoveProxy(int, ref BoundingBox, Vector3)](VRageMath.MyDynamicAABBTree.MoveProxy)

> Move a proxy with a swepted BoundingBox. If the proxy has moved outside of its fattened BoundingBox, then the proxy is removed from the tree and re-inserted. Otherwise the function returns immediately.

[void OverlapAllBoundingBox&lt;T&gt;(ref BoundingBox, List&lt;T&gt;, uint = 0, bool = default)](VRageMath.MyDynamicAABBTree.OverlapAllBoundingBox)

> 

[void OverlapAllBoundingSphere&lt;T&gt;(ref BoundingSphere, List&lt;T&gt;, bool = default)](VRageMath.MyDynamicAABBTree.OverlapAllBoundingSphere)

> 

[void OverlapAllFrustum&lt;T&gt;(ref BoundingFrustum, List&lt;T&gt;, bool = default)](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)

> 

[void OverlapAllFrustum&lt;T&gt;(ref BoundingFrustum, List&lt;T&gt;, uint, bool = default)](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)

> 

[void OverlapAllFrustum&lt;T&gt;(ref BoundingFrustum, List&lt;T&gt;, List&lt;bool&gt;, bool = default)](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)

> 

[void OverlapAllFrustum&lt;T&gt;(ref BoundingFrustum, Action&lt;T, bool&gt;)](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)

> 

[void OverlapAllFrustum&lt;T, Op&gt;(ref BoundingFrustum, ref Op)](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)

> 

[void OverlapAllFrustum&lt;T&gt;(ref BoundingFrustum, List&lt;T&gt;, List&lt;bool&gt;, float, bool = default)](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)

> 

[void OverlapAllFrustum&lt;T&gt;(ref BoundingFrustum, Action&lt;T, bool&gt;, float)](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)

> 

[void OverlapAllFrustum&lt;T, Op&gt;(ref BoundingFrustum, float, ref Op)](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)

> 

[void OverlapAllFrustumAny&lt;T&gt;(ref BoundingFrustum, List&lt;T&gt;, bool = default)](VRageMath.MyDynamicAABBTree.OverlapAllFrustumAny)

> 

[void OverlapAllFrustumConservative&lt;T&gt;(ref BoundingFrustum, List&lt;T&gt;, uint, bool = default)](VRageMath.MyDynamicAABBTree.OverlapAllFrustumConservative)

> 

[void OverlapAllLineSegment&lt;T&gt;(ref Line, List&lt;MyLineSegmentOverlapResult&lt;T&gt;&gt;)](VRageMath.MyDynamicAABBTree.OverlapAllLineSegment)

> 

[void OverlapAllLineSegment&lt;T&gt;(ref Line, List&lt;MyLineSegmentOverlapResult&lt;T&gt;&gt;, uint)](VRageMath.MyDynamicAABBTree.OverlapAllLineSegment)

> 

[bool OverlapsAnyLeafBoundingBox(ref BoundingBox)](VRageMath.MyDynamicAABBTree.OverlapsAnyLeafBoundingBox)

> 

[void OverlapSizeableClusters(ref BoundingBox, List&lt;BoundingBox&gt;, double)](VRageMath.MyDynamicAABBTree.OverlapSizeableClusters)

> 

[void Query(Func&lt;int, bool&gt;, ref BoundingBox)](VRageMath.MyDynamicAABBTree.Query)

> 

[void RemoveProxy(int)](VRageMath.MyDynamicAABBTree.RemoveProxy)

> Destroy a proxy. This asserts if the id is invalid.

