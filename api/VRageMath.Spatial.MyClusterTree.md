← [Index](index.md)
# MyClusterTree Class
**Namespace:** VRageMath.Spatial  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`Func<int, BoundingBoxD, Object> OnClusterCreated`](VRageMath.Spatial.OnClusterCreated.md)||
|[`Action<Object> OnClusterRemoved`](VRageMath.Spatial.OnClusterRemoved.md)||
|[`Action<Object> OnFinishBatch`](VRageMath.Spatial.OnFinishBatch.md)||
|[`Action OnClustersReordered`](VRageMath.Spatial.OnClustersReordered.md)||
|[`Func<long, bool> GetEntityReplicableExistsById`](VRageMath.Spatial.GetEntityReplicableExistsById.md)||
|[`Nullable<BoundingBoxD> SingleCluster`](VRageMath.Spatial.SingleCluster.md)||
|[`bool ForcedClusters`](VRageMath.Spatial.ForcedClusters.md)||
|[`Vector3 IdealClusterSize`](VRageMath.Spatial.IdealClusterSize.md)||
|[`Vector3 IdealClusterSizeHalfSqr`](VRageMath.Spatial.IdealClusterSizeHalfSqr.md)||
|[`Vector3 MinimumDistanceFromBorder`](VRageMath.Spatial.MinimumDistanceFromBorder.md)||
|[`Vector3 MaximumForSplit`](VRageMath.Spatial.MaximumForSplit.md)||
|[`float MaximumClusterSize`](VRageMath.Spatial.MaximumClusterSize.md)||
|[`ulong CLUSTERED_OBJECT_ID_UNITIALIZED`](VRageMath.Spatial.CLUSTERED_OBJECT_ID_UNITIALIZED.md)||
### Properties
|Member|Description|
|---|---|
|[`bool SuppressClusterReorder`](VRageMath.Spatial.SuppressClusterReorder.md)||
### Methods
|Member|Description|
|---|---|
|[`ulong AddObject(BoundingBoxD bbox, IMyActivationHandler activationHandler, Nullable<ulong> customId, string tag, long entityId, bool batch)`](VRageMath.Spatial.AddObject.md)||
|[`BoundingBoxD AdjustAABBByVelocity(BoundingBoxD aabb, Vector3 velocity, float inflate)`](VRageMath.Spatial.AdjustAABBByVelocity.md)||
|[`void MoveObject(ulong id, BoundingBoxD aabb, Vector3 velocity)`](VRageMath.Spatial.MoveObject.md)||
|[`void EnsureClusterSpace(BoundingBoxD aabb)`](VRageMath.Spatial.EnsureClusterSpace.md)||
|[`void RemoveObject(ulong id)`](VRageMath.Spatial.RemoveObject.md)||
|[`Vector3D GetObjectOffset(ulong id)`](VRageMath.Spatial.GetObjectOffset.md)||
|[`MyCluster GetClusterForPosition(Vector3D pos)`](VRageMath.Spatial.GetClusterForPosition.md)||
|[`void Dispose()`](VRageMath.Spatial.Dispose.md)||
|[`ListReader<Object> GetList()`](VRageMath.Spatial.GetList.md)||
|[`ListReader<Object> GetListCopy()`](VRageMath.Spatial.GetListCopy.md)||
|[`ListReader<MyCluster> GetClusters()`](VRageMath.Spatial.GetClusters.md)||
|[`void CastRay(Vector3D from, Vector3D to, List<MyClusterQueryResult> results)`](VRageMath.Spatial.CastRay.md)||
|[`void Intersects(Vector3D translation, List<MyClusterQueryResult> results)`](VRageMath.Spatial.Intersects.md)||
|[`void GetAll(List<MyClusterQueryResult> results)`](VRageMath.Spatial.GetAll.md)||
|[`void ReorderClusters(BoundingBoxD aabb, ulong objectId)`](VRageMath.Spatial.ReorderClusters.md)||
|[`void GetAllStaticObjects(List<BoundingBoxD> staticObjects)`](VRageMath.Spatial.GetAllStaticObjects.md)||
|[`void Serialize(List<BoundingBoxD> list)`](VRageMath.Spatial.Serialize.md)||
|[`void Deserialize(List<BoundingBoxD> list)`](VRageMath.Spatial.Deserialize.md)||
