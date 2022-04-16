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
|\$1static int NullNode](VRageMath.MyDynamicAABBTree.NullNode)|A dynamic tree arranges data in a binary tree to accelerate queries such as volume queries and ray casts. Leafs are proxies with an BoundingBox. In the tree we expand the proxy BoundingBox by Settings.b2_fatAABBFactor so that the proxy BoundingBox is bigger than the client object. This allows the client object to move by small amounts without triggering a tree update. Nodes are pooled and relocatable, so we use node indices rather than pointers.|

#### Properties

|Member|Description|
|---|---|
|\$1DictionaryValuesReader\$1int, DynamicTreeNode\> Leaves { get; }](VRageMath.MyDynamicAABBTree.Leaves)||
|\$1ReadOnlySpan\$1DynamicTreeNode\> Nodes { get; }](VRageMath.MyDynamicAABBTree.Nodes)||

#### Constructors

|Member|Description|
|---|---|
|\$1MyDynamicAABBTree()](VRageMath.MyDynamicAABBTree..ctor)||
|\$1MyDynamicAABBTree(Vector3, \$1float])](VRageMath.MyDynamicAABBTree..ctor)||

#### Methods

|Member|Description|
|---|---|
|\$1static void Dispose()](VRageMath.MyDynamicAABBTree.Dispose)||
|\$1int AddProxy(ref BoundingBox, object, uint, \$1bool])](VRageMath.MyDynamicAABBTree.AddProxy)|Create a proxy. Provide a tight fitting BoundingBox and a userData pointer.|
|\$1int Balance(int)](VRageMath.MyDynamicAABBTree.Balance)||
|\$1void Clear()](VRageMath.MyDynamicAABBTree.Clear)||
|\$1int CountLeaves(int)](VRageMath.MyDynamicAABBTree.CountLeaves)||
|\$1BoundingBox GetAabb(int)](VRageMath.MyDynamicAABBTree.GetAabb)||
|\$1void GetAll\$1T>(List\$1T\>, bool, \$1List\$1BoundingBox\>])](VRageMath.MyDynamicAABBTree.GetAll)||
|\$1void GetAllNodeBounds(List\$1BoundingBox\>)](VRageMath.MyDynamicAABBTree.GetAllNodeBounds)||
|\$1void GetChildren(int, out int, out int)](VRageMath.MyDynamicAABBTree.GetChildren)||
|\$1void GetFatAABB(int, out BoundingBox)](VRageMath.MyDynamicAABBTree.GetFatAABB)|Get the fat BoundingBox for a proxy.|
|\$1int GetHeight()](VRageMath.MyDynamicAABBTree.GetHeight)||
|\$1int GetLeafCount()](VRageMath.MyDynamicAABBTree.GetLeafCount)||
|\$1int GetLeafCount(int)](VRageMath.MyDynamicAABBTree.GetLeafCount)||
|\$1void GetNodeLeaves(int, List\$1int\>)](VRageMath.MyDynamicAABBTree.GetNodeLeaves)||
|\$1int GetRoot()](VRageMath.MyDynamicAABBTree.GetRoot)||
|\$1T GetUserData\$1T>(int)](VRageMath.MyDynamicAABBTree.GetUserData)||
|\$1bool MoveProxy(int, ref BoundingBox, Vector3)](VRageMath.MyDynamicAABBTree.MoveProxy)|Move a proxy with a swepted BoundingBox. If the proxy has moved outside of its fattened BoundingBox, then the proxy is removed from the tree and re-inserted. Otherwise the function returns immediately.|
|\$1void OverlapAllBoundingBox\$1T>(ref BoundingBox, List\$1T\>, \$1uint], \$1bool])](VRageMath.MyDynamicAABBTree.OverlapAllBoundingBox)||
|\$1void OverlapAllBoundingSphere\$1T>(ref BoundingSphere, List\$1T\>, \$1bool])](VRageMath.MyDynamicAABBTree.OverlapAllBoundingSphere)||
|\$1void OverlapAllFrustum\$1T>(ref BoundingFrustum, List\$1T\>, \$1bool])](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)||
|\$1void OverlapAllFrustum\$1T>(ref BoundingFrustum, List\$1T\>, uint, \$1bool])](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)||
|\$1void OverlapAllFrustum\$1T>(ref BoundingFrustum, List\$1T\>, List\$1bool\>, \$1bool])](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)||
|\$1void OverlapAllFrustum\$1T>(ref BoundingFrustum, Action\$1T, bool\>)](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)||
|\$1void OverlapAllFrustum\$1T, Op>(ref BoundingFrustum, ref Op)](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)||
|\$1void OverlapAllFrustum\$1T>(ref BoundingFrustum, List\$1T\>, List\$1bool\>, float, \$1bool])](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)||
|\$1void OverlapAllFrustum\$1T>(ref BoundingFrustum, Action\$1T, bool\>, float)](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)||
|\$1void OverlapAllFrustum\$1T, Op>(ref BoundingFrustum, float, ref Op)](VRageMath.MyDynamicAABBTree.OverlapAllFrustum)||
|\$1void OverlapAllFrustumAny\$1T>(ref BoundingFrustum, List\$1T\>, \$1bool])](VRageMath.MyDynamicAABBTree.OverlapAllFrustumAny)||
|\$1void OverlapAllFrustumConservative\$1T>(ref BoundingFrustum, List\$1T\>, uint, \$1bool])](VRageMath.MyDynamicAABBTree.OverlapAllFrustumConservative)||
|\$1void OverlapAllLineSegment\$1T>(ref Line, List\$1MyLineSegmentOverlapResult\$1T\>\>)](VRageMath.MyDynamicAABBTree.OverlapAllLineSegment)||
|\$1void OverlapAllLineSegment\$1T>(ref Line, List\$1MyLineSegmentOverlapResult\$1T\>\>, uint)](VRageMath.MyDynamicAABBTree.OverlapAllLineSegment)||
|\$1bool OverlapsAnyLeafBoundingBox(ref BoundingBox)](VRageMath.MyDynamicAABBTree.OverlapsAnyLeafBoundingBox)||
|\$1void OverlapSizeableClusters(ref BoundingBox, List\$1BoundingBox\>, double)](VRageMath.MyDynamicAABBTree.OverlapSizeableClusters)||
|\$1void Query(Func\$1int, bool\>, ref BoundingBox)](VRageMath.MyDynamicAABBTree.Query)||
|\$1void RemoveProxy(int)](VRageMath.MyDynamicAABBTree.RemoveProxy)|Destroy a proxy. This asserts if the id is invalid.|

