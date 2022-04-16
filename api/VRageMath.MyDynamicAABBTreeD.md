← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MyDynamicAABBTreeD Class

```csharp
public class MyDynamicAABBTreeD
```

Dynamic aabb tree implementation as a prunning structure

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

#### Fields

|Member|Description|
|---|---|
|[static int NullNode](VRageMath.MyDynamicAABBTreeD.NullNode)|A dynamic tree arranges data in a binary tree to accelerate queries such as volume queries and ray casts. Leafs are proxies with an BoundingBox. In the tree we expand the proxy BoundingBox by Settings.b2_fatAABBFactor so that the proxy BoundingBox is bigger than the client object. This allows the client object to move by small amounts without triggering a tree update. Nodes are pooled and relocatable, so we use node indices rather than pointers.|

#### Properties

|Member|Description|
|---|---|
|[int ElementsCount { get; }](VRageMath.MyDynamicAABBTreeD.ElementsCount)||

#### Constructors

|Member|Description|
|---|---|
|[MyDynamicAABBTreeD()](VRageMath.MyDynamicAABBTreeD..ctor)||
|[MyDynamicAABBTreeD(Vector3D, double = 1)](VRageMath.MyDynamicAABBTreeD..ctor)||

#### Methods

|Member|Description|
|---|---|
|[static void Dispose()](VRageMath.MyDynamicAABBTreeD.Dispose)||
|[int AddProxy(ref BoundingBoxD, object, uint, bool = default)](VRageMath.MyDynamicAABBTreeD.AddProxy)|Create a proxy. Provide a tight fitting BoundingBox and a userData pointer.|
|[int Balance(int)](VRageMath.MyDynamicAABBTreeD.Balance)||
|[void Clear()](VRageMath.MyDynamicAABBTreeD.Clear)||
|[int CountLeaves(int)](VRageMath.MyDynamicAABBTreeD.CountLeaves)||
|[BoundingBoxD GetAabb(int)](VRageMath.MyDynamicAABBTreeD.GetAabb)||
|[void GetAll&lt;T&gt;(List&lt;T&gt;, bool, List&lt;BoundingBoxD&gt; = null)](VRageMath.MyDynamicAABBTreeD.GetAll)||
|[void GetAll&lt;T&gt;(Action&lt;T&gt;)](VRageMath.MyDynamicAABBTreeD.GetAll)||
|[void GetAll&lt;T&gt;(Action&lt;T, BoundingBoxD&gt;)](VRageMath.MyDynamicAABBTreeD.GetAll)||
|[void GetAllNodeBounds(List&lt;BoundingBoxD&gt;)](VRageMath.MyDynamicAABBTreeD.GetAllNodeBounds)||
|[void GetAproximateClustersForAabb(ref BoundingBoxD, double, List&lt;BoundingBoxD&gt;)](VRageMath.MyDynamicAABBTreeD.GetAproximateClustersForAabb)||
|[void GetChildren(int, out int, out int)](VRageMath.MyDynamicAABBTreeD.GetChildren)||
|[void GetFatAABB(int, out BoundingBoxD)](VRageMath.MyDynamicAABBTreeD.GetFatAABB)|Get the fat BoundingBox for a proxy.|
|[int GetHeight()](VRageMath.MyDynamicAABBTreeD.GetHeight)||
|[int GetLeafCount(int)](VRageMath.MyDynamicAABBTreeD.GetLeafCount)||
|[void GetNodeLeaves(int, List&lt;int&gt;)](VRageMath.MyDynamicAABBTreeD.GetNodeLeaves)||
|[int GetRoot()](VRageMath.MyDynamicAABBTreeD.GetRoot)||
|[T GetUserData&lt;T&gt;(int)](VRageMath.MyDynamicAABBTreeD.GetUserData)||
|[bool IsRootNull()](VRageMath.MyDynamicAABBTreeD.IsRootNull)||
|[bool MoveProxy(int, ref BoundingBoxD, Vector3D)](VRageMath.MyDynamicAABBTreeD.MoveProxy)|Move a proxy with a swepted BoundingBox. If the proxy has moved outside of its fattened BoundingBox, then the proxy is removed from the tree and re-inserted. Otherwise the function returns immediately.|
|[void OverlapAllBoundingBox&lt;T&gt;(ref BoundingBoxD, List&lt;T&gt;, uint = 0, bool = default)](VRageMath.MyDynamicAABBTreeD.OverlapAllBoundingBox)||
|[void OverlapAllBoundingBox&lt;T&gt;(ref MyOrientedBoundingBoxD, List&lt;T&gt;, uint = 0, bool = default)](VRageMath.MyDynamicAABBTreeD.OverlapAllBoundingBox)||
|[void OverlapAllBoundingSphere&lt;T&gt;(ref BoundingSphereD, List&lt;T&gt;, bool = default)](VRageMath.MyDynamicAABBTreeD.OverlapAllBoundingSphere)||
|[void OverlapAllBoundingSphere&lt;T&gt;(ref BoundingSphereD, Action&lt;T&gt;)](VRageMath.MyDynamicAABBTreeD.OverlapAllBoundingSphere)||
|[void OverlapAllFrustum&lt;T&gt;(ref BoundingFrustumD, List&lt;T&gt;, bool = default)](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|[void OverlapAllFrustum&lt;T&gt;(ref BoundingFrustumD, List&lt;T&gt;, uint, bool = default)](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|[void OverlapAllFrustum&lt;T&gt;(ref BoundingFrustumD, List&lt;T&gt;, List&lt;bool&gt;)](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|[void OverlapAllFrustum&lt;T&gt;(ref BoundingFrustumD, T)](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|[void OverlapAllFrustum&lt;T&gt;(ref BoundingFrustumD, List&lt;T&gt;, List&lt;bool&gt;, float, bool = default)](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|[void OverlapAllFrustum&lt;T&gt;(ref BoundingFrustumD, Action&lt;T, bool&gt;, float)](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|[void OverlapAllFrustum&lt;T&gt;(ref BoundingFrustumD, T, float)](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|[void OverlapAllFrustumAny&lt;T&gt;(ref BoundingFrustumD, List&lt;T&gt;, bool = default)](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustumAny)||
|[void OverlapAllLineSegment&lt;T&gt;(ref LineD, List&lt;MyLineSegmentOverlapResult&lt;T&gt;&gt;, bool = default)](VRageMath.MyDynamicAABBTreeD.OverlapAllLineSegment)||
|[void OverlapAllLineSegment&lt;T&gt;(ref LineD, List&lt;MyLineSegmentOverlapResult&lt;T&gt;&gt;, uint, bool = default)](VRageMath.MyDynamicAABBTreeD.OverlapAllLineSegment)||
|[bool OverlapsAnyLeafBoundingBox(ref BoundingBoxD)](VRageMath.MyDynamicAABBTreeD.OverlapsAnyLeafBoundingBox)||
|[void Query(Func&lt;int, bool&gt;, ref BoundingBoxD)](VRageMath.MyDynamicAABBTreeD.Query)||
|[void QueryPoint(Func&lt;int, bool&gt;, ref Vector3D)](VRageMath.MyDynamicAABBTreeD.QueryPoint)||
|[void RemoveProxy(int)](VRageMath.MyDynamicAABBTreeD.RemoveProxy)|Destroy a proxy. This asserts if the id is invalid.|

