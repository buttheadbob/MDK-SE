← [Index](index)
# MyClusterTree Class
**Namespace:** [`VRageMath.Spatial`](VRageMath.Spatial)  
**Assembly:** VRage.Math.dll  
### Fields
<table style="width:100%;display:table">
<tr><td>[`Func<int, BoundingBoxD, Object> OnClusterCreated`](VRageMath.Spatial.OnClusterCreated)</td><td></td></tr>
<tr><td>[`Action<Object> OnClusterRemoved`](VRageMath.Spatial.OnClusterRemoved)</td><td></td></tr>
<tr><td>[`Action<Object> OnFinishBatch`](VRageMath.Spatial.OnFinishBatch)</td><td></td></tr>
<tr><td>[`Action OnClustersReordered`](VRageMath.Spatial.OnClustersReordered)</td><td></td></tr>
<tr><td>[`Func<long, bool> GetEntityReplicableExistsById`](VRageMath.Spatial.GetEntityReplicableExistsById)</td><td></td></tr>
<tr><td>[`Nullable<BoundingBoxD> SingleCluster`](VRageMath.Spatial.SingleCluster)</td><td></td></tr>
<tr><td>[`bool ForcedClusters`](VRageMath.Spatial.ForcedClusters)</td><td></td></tr>
<tr><td>static [`Vector3 IdealClusterSize`](VRageMath.Spatial.IdealClusterSize)</td><td></td></tr>
<tr><td>static [`Vector3 IdealClusterSizeHalfSqr`](VRageMath.Spatial.IdealClusterSizeHalfSqr)</td><td></td></tr>
<tr><td>static [`Vector3 MinimumDistanceFromBorder`](VRageMath.Spatial.MinimumDistanceFromBorder)</td><td></td></tr>
<tr><td>static [`Vector3 MaximumForSplit`](VRageMath.Spatial.MaximumForSplit)</td><td></td></tr>
<tr><td>static [`float MaximumClusterSize`](VRageMath.Spatial.MaximumClusterSize)</td><td></td></tr>
<tr><td>static [`ulong CLUSTERED_OBJECT_ID_UNITIALIZED`](VRageMath.Spatial.CLUSTERED_OBJECT_ID_UNITIALIZED)</td><td></td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>[`bool SuppressClusterReorder`](VRageMath.Spatial.SuppressClusterReorder)</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>[`ulong AddObject(BoundingBoxD bbox, IMyActivationHandler activationHandler, Nullable<ulong> customId, string tag, long entityId, bool batch)`](VRageMath.Spatial.AddObject)</td><td></td></tr>
<tr><td>static [`BoundingBoxD AdjustAABBByVelocity(BoundingBoxD aabb, Vector3 velocity, float inflate)`](VRageMath.Spatial.AdjustAABBByVelocity)</td><td></td></tr>
<tr><td>[`void MoveObject(ulong id, BoundingBoxD aabb, Vector3 velocity)`](VRageMath.Spatial.MoveObject)</td><td></td></tr>
<tr><td>[`void EnsureClusterSpace(BoundingBoxD aabb)`](VRageMath.Spatial.EnsureClusterSpace)</td><td></td></tr>
<tr><td>[`void RemoveObject(ulong id)`](VRageMath.Spatial.RemoveObject)</td><td></td></tr>
<tr><td>[`Vector3D GetObjectOffset(ulong id)`](VRageMath.Spatial.GetObjectOffset)</td><td></td></tr>
<tr><td>[`MyCluster GetClusterForPosition(Vector3D pos)`](VRageMath.Spatial.GetClusterForPosition)</td><td></td></tr>
<tr><td>[`void Dispose()`](VRageMath.Spatial.Dispose)</td><td></td></tr>
<tr><td>[`ListReader<Object> GetList()`](VRageMath.Spatial.GetList)</td><td></td></tr>
<tr><td>[`ListReader<Object> GetListCopy()`](VRageMath.Spatial.GetListCopy)</td><td></td></tr>
<tr><td>[`ListReader<MyCluster> GetClusters()`](VRageMath.Spatial.GetClusters)</td><td></td></tr>
<tr><td>[`void CastRay(Vector3D from, Vector3D to, List<MyClusterQueryResult> results)`](VRageMath.Spatial.CastRay)</td><td></td></tr>
<tr><td>[`void Intersects(Vector3D translation, List<MyClusterQueryResult> results)`](VRageMath.Spatial.Intersects)</td><td></td></tr>
<tr><td>[`void GetAll(List<MyClusterQueryResult> results)`](VRageMath.Spatial.GetAll)</td><td></td></tr>
<tr><td>[`void ReorderClusters(BoundingBoxD aabb, ulong objectId)`](VRageMath.Spatial.ReorderClusters)</td><td></td></tr>
<tr><td>[`void GetAllStaticObjects(List<BoundingBoxD> staticObjects)`](VRageMath.Spatial.GetAllStaticObjects)</td><td></td></tr>
<tr><td>[`void Serialize(List<BoundingBoxD> list)`](VRageMath.Spatial.Serialize)</td><td></td></tr>
<tr><td>[`void Deserialize(List<BoundingBoxD> list)`](VRageMath.Spatial.Deserialize)</td><td></td></tr>
</table>
