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
|[MyDynamicAABBTreeD(Vector3D, [double])](VRageMath.MyDynamicAABBTreeD..ctor)||

#### Methods

|Member|Description|
|---|---|
|[static void Dispose()](VRageMath.MyDynamicAABBTreeD.Dispose)||
|[int AddProxy(ref BoundingBoxD, object, uint, [bool])](VRageMath.MyDynamicAABBTreeD.AddProxy)|Create a proxy. Provide a tight fitting BoundingBox and a userData pointer.|
|[int Balance(int)](VRageMath.MyDynamicAABBTreeD.Balance)||
|[void Clear()](VRageMath.MyDynamicAABBTreeD.Clear)||
|[int CountLeaves(int)](VRageMath.MyDynamicAABBTreeD.CountLeaves)||
|[BoundingBoxD GetAabb(int)](VRageMath.MyDynamicAABBTreeD.GetAabb)||
|[void GetAll(List<T>, bool, [List<VRageMath.BoundingBoxD>])](VRageMath.MyDynamicAABBTreeD.GetAll)||
|[void GetAll(Action<T>)](VRageMath.MyDynamicAABBTreeD.GetAll)||
|[void GetAll(Action<T, VRageMath.BoundingBoxD>)](VRageMath.MyDynamicAABBTreeD.GetAll)||
|[void GetAllNodeBounds(List<VRageMath.BoundingBoxD>)](VRageMath.MyDynamicAABBTreeD.GetAllNodeBounds)||
|[void GetAproximateClustersForAabb(ref BoundingBoxD, double, List<VRageMath.BoundingBoxD>)](VRageMath.MyDynamicAABBTreeD.GetAproximateClustersForAabb)||
|[void GetChildren(int, out int, out int)](VRageMath.MyDynamicAABBTreeD.GetChildren)||
|[void GetFatAABB(int, out BoundingBoxD)](VRageMath.MyDynamicAABBTreeD.GetFatAABB)|Get the fat BoundingBox for a proxy.|
|[int GetHeight()](VRageMath.MyDynamicAABBTreeD.GetHeight)||
|[int GetLeafCount(int)](VRageMath.MyDynamicAABBTreeD.GetLeafCount)||
|[void GetNodeLeaves(int, List<System.Int32>)](VRageMath.MyDynamicAABBTreeD.GetNodeLeaves)||
|[int GetRoot()](VRageMath.MyDynamicAABBTreeD.GetRoot)||
|[T GetUserData(int)](VRageMath.MyDynamicAABBTreeD.GetUserData)||
|[bool IsRootNull()](VRageMath.MyDynamicAABBTreeD.IsRootNull)||
|[bool MoveProxy(int, ref BoundingBoxD, Vector3D)](VRageMath.MyDynamicAABBTreeD.MoveProxy)|Move a proxy with a swepted BoundingBox. If the proxy has moved outside of its fattened BoundingBox, then the proxy is removed from the tree and re-inserted. Otherwise the function returns immediately.|
|[void OverlapAllBoundingBox(ref BoundingBoxD, List<T>, [uint], [bool])](VRageMath.MyDynamicAABBTreeD.OverlapAllBoundingBox)||
|[void OverlapAllBoundingBox(ref MyOrientedBoundingBoxD, List<T>, [uint], [bool])](VRageMath.MyDynamicAABBTreeD.OverlapAllBoundingBox)||
|[void OverlapAllBoundingSphere(ref BoundingSphereD, List<T>, [bool])](VRageMath.MyDynamicAABBTreeD.OverlapAllBoundingSphere)||
|[void OverlapAllBoundingSphere(ref BoundingSphereD, Action<T>)](VRageMath.MyDynamicAABBTreeD.OverlapAllBoundingSphere)||
|[void OverlapAllFrustum(ref BoundingFrustumD, List<T>, [bool])](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|[void OverlapAllFrustum(ref BoundingFrustumD, List<T>, uint, [bool])](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|[void OverlapAllFrustum(ref BoundingFrustumD, List<T>, List<System.Boolean>)](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|[void OverlapAllFrustum(ref BoundingFrustumD, T)](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|[void OverlapAllFrustum(ref BoundingFrustumD, List<T>, List<System.Boolean>, float, [bool])](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|[void OverlapAllFrustum(ref BoundingFrustumD, Action<T, System.Boolean>, float)](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|[void OverlapAllFrustum(ref BoundingFrustumD, T, float)](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|[void OverlapAllFrustumAny(ref BoundingFrustumD, List<T>, [bool])](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustumAny)||
|[void OverlapAllLineSegment(ref LineD, List<>, [bool])](VRageMath.MyDynamicAABBTreeD.OverlapAllLineSegment)||
|[void OverlapAllLineSegment(ref LineD, List<>, uint, [bool])](VRageMath.MyDynamicAABBTreeD.OverlapAllLineSegment)||
|[bool OverlapsAnyLeafBoundingBox(ref BoundingBoxD)](VRageMath.MyDynamicAABBTreeD.OverlapsAnyLeafBoundingBox)||
|[void Query(Func<System.Int32, System.Boolean>, ref BoundingBoxD)](VRageMath.MyDynamicAABBTreeD.Query)||
|[void QueryPoint(Func<System.Int32, System.Boolean>, ref Vector3D)](VRageMath.MyDynamicAABBTreeD.QueryPoint)||
|[void RemoveProxy(int)](VRageMath.MyDynamicAABBTreeD.RemoveProxy)|Destroy a proxy. This asserts if the id is invalid.|

