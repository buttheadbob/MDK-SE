← [Index](index)
# MyClusterTree Class
**Namespace:** [`VRageMath.Spatial`](VRageMath.Spatial)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`OnClusterCreated`](VRageMath.Spatial.OnClusterCreated)||
|[`OnClusterRemoved`](VRageMath.Spatial.OnClusterRemoved)||
|[`OnFinishBatch`](VRageMath.Spatial.OnFinishBatch)||
|[`OnClustersReordered`](VRageMath.Spatial.OnClustersReordered)||
|[`GetEntityReplicableExistsById`](VRageMath.Spatial.GetEntityReplicableExistsById)||
|[`SingleCluster`](VRageMath.Spatial.SingleCluster)||
|[`ForcedClusters`](VRageMath.Spatial.ForcedClusters)||
|static [`IdealClusterSize`](VRageMath.Spatial.IdealClusterSize)||
|static [`IdealClusterSizeHalfSqr`](VRageMath.Spatial.IdealClusterSizeHalfSqr)||
|static [`MinimumDistanceFromBorder`](VRageMath.Spatial.MinimumDistanceFromBorder)||
|static [`MaximumForSplit`](VRageMath.Spatial.MaximumForSplit)||
|static [`MaximumClusterSize`](VRageMath.Spatial.MaximumClusterSize)||
|static [`CLUSTERED_OBJECT_ID_UNITIALIZED`](VRageMath.Spatial.CLUSTERED_OBJECT_ID_UNITIALIZED)||
### Properties
|Member|Description|
|---|---|
|[`SuppressClusterReorder`](VRageMath.Spatial.SuppressClusterReorder)||
### Methods
|Member|Description|
|---|---|
|[`AddObject(BoundingBoxD, IMyActivationHandler, Nullable<ulong>, string, long, bool)`](VRageMath.Spatial.AddObject)||
|static [`AdjustAABBByVelocity(BoundingBoxD, Vector3, float)`](VRageMath.Spatial.AdjustAABBByVelocity)||
|[`MoveObject(ulong, BoundingBoxD, Vector3)`](VRageMath.Spatial.MoveObject)||
|[`EnsureClusterSpace(BoundingBoxD)`](VRageMath.Spatial.EnsureClusterSpace)||
|[`RemoveObject(ulong)`](VRageMath.Spatial.RemoveObject)||
|[`GetObjectOffset(ulong)`](VRageMath.Spatial.GetObjectOffset)||
|[`GetClusterForPosition(Vector3D)`](VRageMath.Spatial.GetClusterForPosition)||
|[`Dispose()`](VRageMath.Spatial.Dispose)||
|[`GetList()`](VRageMath.Spatial.GetList)||
|[`GetListCopy()`](VRageMath.Spatial.GetListCopy)||
|[`GetClusters()`](VRageMath.Spatial.GetClusters)||
|[`CastRay(Vector3D, Vector3D, List<MyClusterQueryResult>)`](VRageMath.Spatial.CastRay)||
|[`Intersects(Vector3D, List<MyClusterQueryResult>)`](VRageMath.Spatial.Intersects)||
|[`GetAll(List<MyClusterQueryResult>)`](VRageMath.Spatial.GetAll)||
|[`ReorderClusters(BoundingBoxD, ulong)`](VRageMath.Spatial.ReorderClusters)||
|[`GetAllStaticObjects(List<BoundingBoxD>)`](VRageMath.Spatial.GetAllStaticObjects)||
|[`Serialize(List<BoundingBoxD>)`](VRageMath.Spatial.Serialize)||
|[`Deserialize(List<BoundingBoxD>)`](VRageMath.Spatial.Deserialize)||
