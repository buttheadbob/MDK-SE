← [Index](index)
# MyClusterTree Class
**Namespace:** [`VRageMath.Spatial`](VRageMath.Spatial)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`Func<System.Int32, VRageMath.BoundingBoxD, System.Object> OnClusterCreated`](VRageMath.Spatial.OnClusterCreated)||
|[`Action<System.Object> OnClusterRemoved`](VRageMath.Spatial.OnClusterRemoved)||
|[`Action<System.Object> OnFinishBatch`](VRageMath.Spatial.OnFinishBatch)||
|[`System.Action OnClustersReordered`](VRageMath.Spatial.OnClustersReordered)||
|[`Func<System.Int64, System.Boolean> GetEntityReplicableExistsById`](VRageMath.Spatial.GetEntityReplicableExistsById)||
|[`Nullable<VRageMath.BoundingBoxD> SingleCluster`](VRageMath.Spatial.SingleCluster)||
|[`bool ForcedClusters`](VRageMath.Spatial.ForcedClusters)||
|static [`VRageMath.Vector3 IdealClusterSize`](VRageMath.Spatial.IdealClusterSize)||
|static [`VRageMath.Vector3 IdealClusterSizeHalfSqr`](VRageMath.Spatial.IdealClusterSizeHalfSqr)||
|static [`VRageMath.Vector3 MinimumDistanceFromBorder`](VRageMath.Spatial.MinimumDistanceFromBorder)||
|static [`VRageMath.Vector3 MaximumForSplit`](VRageMath.Spatial.MaximumForSplit)||
|static [`float MaximumClusterSize`](VRageMath.Spatial.MaximumClusterSize)||
|static [`ulong CLUSTERED_OBJECT_ID_UNITIALIZED`](VRageMath.Spatial.CLUSTERED_OBJECT_ID_UNITIALIZED)||
### Properties
|Member|Description|
|---|---|
|[`bool SuppressClusterReorder`](VRageMath.Spatial.SuppressClusterReorder)||
### Methods
|Member|Description|
|---|---|
|[`ulong AddObject(VRageMath.BoundingBoxD, VRageMath.Spatial.IMyActivationHandler, Nullable<System.UInt64>, string, long, bool)`](VRageMath.Spatial.AddObject)||
|static [`VRageMath.BoundingBoxD AdjustAABBByVelocity(VRageMath.BoundingBoxD, VRageMath.Vector3, float)`](VRageMath.Spatial.AdjustAABBByVelocity)||
|[`void MoveObject(ulong, VRageMath.BoundingBoxD, VRageMath.Vector3)`](VRageMath.Spatial.MoveObject)||
|[`void EnsureClusterSpace(VRageMath.BoundingBoxD)`](VRageMath.Spatial.EnsureClusterSpace)||
|[`void RemoveObject(ulong)`](VRageMath.Spatial.RemoveObject)||
|[`VRageMath.Vector3D GetObjectOffset(ulong)`](VRageMath.Spatial.GetObjectOffset)||
|[`VRageMath.Spatial.MyCluster GetClusterForPosition(VRageMath.Vector3D)`](VRageMath.Spatial.GetClusterForPosition)||
|[`void Dispose()`](VRageMath.Spatial.Dispose)||
|[`ListReader<System.Object> GetList()`](VRageMath.Spatial.GetList)||
|[`ListReader<System.Object> GetListCopy()`](VRageMath.Spatial.GetListCopy)||
|[`ListReader<VRageMath.Spatial.MyClusterTree+MyCluster> GetClusters()`](VRageMath.Spatial.GetClusters)||
|[`void CastRay(VRageMath.Vector3D, VRageMath.Vector3D, List<VRageMath.Spatial.MyClusterTree+MyClusterQueryResult>)`](VRageMath.Spatial.CastRay)||
|[`void Intersects(VRageMath.Vector3D, List<VRageMath.Spatial.MyClusterTree+MyClusterQueryResult>)`](VRageMath.Spatial.Intersects)||
|[`void GetAll(List<VRageMath.Spatial.MyClusterTree+MyClusterQueryResult>)`](VRageMath.Spatial.GetAll)||
|[`void ReorderClusters(VRageMath.BoundingBoxD, ulong)`](VRageMath.Spatial.ReorderClusters)||
|[`void GetAllStaticObjects(List<VRageMath.BoundingBoxD>)`](VRageMath.Spatial.GetAllStaticObjects)||
|[`void Serialize(List<VRageMath.BoundingBoxD>)`](VRageMath.Spatial.Serialize)||
|[`void Deserialize(List<VRageMath.BoundingBoxD>)`](VRageMath.Spatial.Deserialize)||
