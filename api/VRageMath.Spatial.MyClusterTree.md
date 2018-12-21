← [Index](index)
# MyClusterTree Class
**Namespace:** [`VRageMath.Spatial`](VRageMath.Spatial)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`Func<int, BoundingBoxD, Object> OnClusterCreated`](VRageMath.Spatial.OnClusterCreated)||
|[`Action<Object> OnClusterRemoved`](VRageMath.Spatial.OnClusterRemoved)||
|[`Action<Object> OnFinishBatch`](VRageMath.Spatial.OnFinishBatch)||
|[`Action OnClustersReordered`](VRageMath.Spatial.OnClustersReordered)||
|[`Func<long, bool> GetEntityReplicableExistsById`](VRageMath.Spatial.GetEntityReplicableExistsById)||
|[`Nullable<BoundingBoxD> SingleCluster`](VRageMath.Spatial.SingleCluster)||
|[`bool ForcedClusters`](VRageMath.Spatial.ForcedClusters)||
|static [`Vector3 IdealClusterSize`](VRageMath.Spatial.IdealClusterSize)||
|static [`Vector3 IdealClusterSizeHalfSqr`](VRageMath.Spatial.IdealClusterSizeHalfSqr)||
|static [`Vector3 MinimumDistanceFromBorder`](VRageMath.Spatial.MinimumDistanceFromBorder)||
|static [`Vector3 MaximumForSplit`](VRageMath.Spatial.MaximumForSplit)||
|static [`float MaximumClusterSize`](VRageMath.Spatial.MaximumClusterSize)||
|static [`ulong CLUSTERED_OBJECT_ID_UNITIALIZED`](VRageMath.Spatial.CLUSTERED_OBJECT_ID_UNITIALIZED)||
### Properties
|Member|Description|
|---|---|
|[`bool SuppressClusterReorder`](VRageMath.Spatial.SuppressClusterReorder)||
### Methods
|Member|Description|
|---|---|
|[`ulong AddObject(BoundingBoxD bbox, IMyActivationHandler activationHandler, Nullable<ulong> customId, string tag, long entityId, bool batch)`](VRageMath.Spatial.AddObject)||
|static [`BoundingBoxD AdjustAABBByVelocity(BoundingBoxD aabb, Vector3 velocity, float inflate)`](VRageMath.Spatial.AdjustAABBByVelocity)||
|[`void MoveObject(ulong id, BoundingBoxD aabb, Vector3 velocity)`](VRageMath.Spatial.MoveObject)||
|[`void EnsureClusterSpace(BoundingBoxD aabb)`](VRageMath.Spatial.EnsureClusterSpace)||
|[`void RemoveObject(ulong id)`](VRageMath.Spatial.RemoveObject)||
|[`Vector3D GetObjectOffset(ulong id)`](VRageMath.Spatial.GetObjectOffset)||
|[`MyCluster GetClusterForPosition(Vector3D pos)`](VRageMath.Spatial.GetClusterForPosition)||
|[`void Dispose()`](VRageMath.Spatial.Dispose)||
|[`ListReader<Object> GetList()`](VRageMath.Spatial.GetList)||
|[`ListReader<Object> GetListCopy()`](VRageMath.Spatial.GetListCopy)||
|[`ListReader<MyCluster> GetClusters()`](VRageMath.Spatial.GetClusters)||
|[`void CastRay(Vector3D from, Vector3D to, List<MyClusterQueryResult> results)`](VRageMath.Spatial.CastRay)||
|[`void Intersects(Vector3D translation, List<MyClusterQueryResult> results)`](VRageMath.Spatial.Intersects)||
|[`void GetAll(List<MyClusterQueryResult> results)`](VRageMath.Spatial.GetAll)||
|[`void ReorderClusters(BoundingBoxD aabb, ulong objectId)`](VRageMath.Spatial.ReorderClusters)||
|[`void GetAllStaticObjects(List<BoundingBoxD> staticObjects)`](VRageMath.Spatial.GetAllStaticObjects)||
|[`void Serialize(List<BoundingBoxD> list)`](VRageMath.Spatial.Serialize)||
|[`void Deserialize(List<BoundingBoxD> list)`](VRageMath.Spatial.Deserialize)||
