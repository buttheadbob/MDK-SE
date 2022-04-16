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
|\\$1static int NullNode](VRageMath.MyDynamicAABBTreeD.NullNode)|A dynamic tree arranges data in a binary tree to accelerate queries such as volume queries and ray casts. Leafs are proxies with an BoundingBox. In the tree we expand the proxy BoundingBox by Settings.b2_fatAABBFactor so that the proxy BoundingBox is bigger than the client object. This allows the client object to move by small amounts without triggering a tree update. Nodes are pooled and relocatable, so we use node indices rather than pointers.|

#### Properties

|Member|Description|
|---|---|
|\\$1int ElementsCount { get; }](VRageMath.MyDynamicAABBTreeD.ElementsCount)||

#### Constructors

|Member|Description|
|---|---|
|\\$1MyDynamicAABBTreeD()](VRageMath.MyDynamicAABBTreeD..ctor)||
|\\$1MyDynamicAABBTreeD(Vector3D, \\$1double])](VRageMath.MyDynamicAABBTreeD..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\$1static void Dispose()](VRageMath.MyDynamicAABBTreeD.Dispose)||
|\\$1int AddProxy(ref BoundingBoxD, object, uint, \\$1bool])](VRageMath.MyDynamicAABBTreeD.AddProxy)|Create a proxy. Provide a tight fitting BoundingBox and a userData pointer.|
|\\$1int Balance(int)](VRageMath.MyDynamicAABBTreeD.Balance)||
|\\$1void Clear()](VRageMath.MyDynamicAABBTreeD.Clear)||
|\\$1int CountLeaves(int)](VRageMath.MyDynamicAABBTreeD.CountLeaves)||
|\\$1BoundingBoxD GetAabb(int)](VRageMath.MyDynamicAABBTreeD.GetAabb)||
|\\$1void GetAll\\$1T>(List\\$1T>, bool, \\$1List\\$1BoundingBoxD>])](VRageMath.MyDynamicAABBTreeD.GetAll)||
|\\$1void GetAll\\$1T>(Action\\$1T>)](VRageMath.MyDynamicAABBTreeD.GetAll)||
|\\$1void GetAll\\$1T>(Action\\$1T, BoundingBoxD>)](VRageMath.MyDynamicAABBTreeD.GetAll)||
|\\$1void GetAllNodeBounds(List\\$1BoundingBoxD>)](VRageMath.MyDynamicAABBTreeD.GetAllNodeBounds)||
|\\$1void GetAproximateClustersForAabb(ref BoundingBoxD, double, List\\$1BoundingBoxD>)](VRageMath.MyDynamicAABBTreeD.GetAproximateClustersForAabb)||
|\\$1void GetChildren(int, out int, out int)](VRageMath.MyDynamicAABBTreeD.GetChildren)||
|\\$1void GetFatAABB(int, out BoundingBoxD)](VRageMath.MyDynamicAABBTreeD.GetFatAABB)|Get the fat BoundingBox for a proxy.|
|\\$1int GetHeight()](VRageMath.MyDynamicAABBTreeD.GetHeight)||
|\\$1int GetLeafCount(int)](VRageMath.MyDynamicAABBTreeD.GetLeafCount)||
|\\$1void GetNodeLeaves(int, List\\$1int>)](VRageMath.MyDynamicAABBTreeD.GetNodeLeaves)||
|\\$1int GetRoot()](VRageMath.MyDynamicAABBTreeD.GetRoot)||
|\\$1T GetUserData\\$1T>(int)](VRageMath.MyDynamicAABBTreeD.GetUserData)||
|\\$1bool IsRootNull()](VRageMath.MyDynamicAABBTreeD.IsRootNull)||
|\\$1bool MoveProxy(int, ref BoundingBoxD, Vector3D)](VRageMath.MyDynamicAABBTreeD.MoveProxy)|Move a proxy with a swepted BoundingBox. If the proxy has moved outside of its fattened BoundingBox, then the proxy is removed from the tree and re-inserted. Otherwise the function returns immediately.|
|\\$1void OverlapAllBoundingBox\\$1T>(ref BoundingBoxD, List\\$1T>, \\$1uint], \\$1bool])](VRageMath.MyDynamicAABBTreeD.OverlapAllBoundingBox)||
|\\$1void OverlapAllBoundingBox\\$1T>(ref MyOrientedBoundingBoxD, List\\$1T>, \\$1uint], \\$1bool])](VRageMath.MyDynamicAABBTreeD.OverlapAllBoundingBox)||
|\\$1void OverlapAllBoundingSphere\\$1T>(ref BoundingSphereD, List\\$1T>, \\$1bool])](VRageMath.MyDynamicAABBTreeD.OverlapAllBoundingSphere)||
|\\$1void OverlapAllBoundingSphere\\$1T>(ref BoundingSphereD, Action\\$1T>)](VRageMath.MyDynamicAABBTreeD.OverlapAllBoundingSphere)||
|\\$1void OverlapAllFrustum\\$1T>(ref BoundingFrustumD, List\\$1T>, \\$1bool])](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|\\$1void OverlapAllFrustum\\$1T>(ref BoundingFrustumD, List\\$1T>, uint, \\$1bool])](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|\\$1void OverlapAllFrustum\\$1T>(ref BoundingFrustumD, List\\$1T>, List\\$1bool>)](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|\\$1void OverlapAllFrustum\\$1T>(ref BoundingFrustumD, T)](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|\\$1void OverlapAllFrustum\\$1T>(ref BoundingFrustumD, List\\$1T>, List\\$1bool>, float, \\$1bool])](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|\\$1void OverlapAllFrustum\\$1T>(ref BoundingFrustumD, Action\\$1T, bool>, float)](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|\\$1void OverlapAllFrustum\\$1T>(ref BoundingFrustumD, T, float)](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustum)||
|\\$1void OverlapAllFrustumAny\\$1T>(ref BoundingFrustumD, List\\$1T>, \\$1bool])](VRageMath.MyDynamicAABBTreeD.OverlapAllFrustumAny)||
|\\$1void OverlapAllLineSegment\\$1T>(ref LineD, List\\$1MyLineSegmentOverlapResult\\$1T>>, \\$1bool])](VRageMath.MyDynamicAABBTreeD.OverlapAllLineSegment)||
|\\$1void OverlapAllLineSegment\\$1T>(ref LineD, List\\$1MyLineSegmentOverlapResult\\$1T>>, uint, \\$1bool])](VRageMath.MyDynamicAABBTreeD.OverlapAllLineSegment)||
|\\$1bool OverlapsAnyLeafBoundingBox(ref BoundingBoxD)](VRageMath.MyDynamicAABBTreeD.OverlapsAnyLeafBoundingBox)||
|\\$1void Query(Func\\$1int, bool>, ref BoundingBoxD)](VRageMath.MyDynamicAABBTreeD.Query)||
|\\$1void QueryPoint(Func\\$1int, bool>, ref Vector3D)](VRageMath.MyDynamicAABBTreeD.QueryPoint)||
|\\$1void RemoveProxy(int)](VRageMath.MyDynamicAABBTreeD.RemoveProxy)|Destroy a proxy. This asserts if the id is invalid.|

