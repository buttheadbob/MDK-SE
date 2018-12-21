← [Index](index)
# MyClusterTree Class
**Namespace:** [`VRageMath.Spatial`](VRageMath.Spatial)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`Func<int,&nbsp;BoundingBoxD,&nbsp;Object>&nbsp;OnClusterCreated`](VRageMath.Spatial.OnClusterCreated)||
|[`Action<Object>&nbsp;OnClusterRemoved`](VRageMath.Spatial.OnClusterRemoved)||
|[`Action<Object>&nbsp;OnFinishBatch`](VRageMath.Spatial.OnFinishBatch)||
|[`Action&nbsp;OnClustersReordered`](VRageMath.Spatial.OnClustersReordered)||
|[`Func<long,&nbsp;bool>&nbsp;GetEntityReplicableExistsById`](VRageMath.Spatial.GetEntityReplicableExistsById)||
|[`Nullable<BoundingBoxD>&nbsp;SingleCluster`](VRageMath.Spatial.SingleCluster)||
|[`bool&nbsp;ForcedClusters`](VRageMath.Spatial.ForcedClusters)||
|static&nbsp;[`Vector3&nbsp;IdealClusterSize`](VRageMath.Spatial.IdealClusterSize)||
|static&nbsp;[`Vector3&nbsp;IdealClusterSizeHalfSqr`](VRageMath.Spatial.IdealClusterSizeHalfSqr)||
|static&nbsp;[`Vector3&nbsp;MinimumDistanceFromBorder`](VRageMath.Spatial.MinimumDistanceFromBorder)||
|static&nbsp;[`Vector3&nbsp;MaximumForSplit`](VRageMath.Spatial.MaximumForSplit)||
|static&nbsp;[`float&nbsp;MaximumClusterSize`](VRageMath.Spatial.MaximumClusterSize)||
|static&nbsp;[`ulong&nbsp;CLUSTERED_OBJECT_ID_UNITIALIZED`](VRageMath.Spatial.CLUSTERED_OBJECT_ID_UNITIALIZED)||
### Properties
|Member|Description|
|---|---|
|[`bool&nbsp;SuppressClusterReorder`](VRageMath.Spatial.SuppressClusterReorder)||
### Methods
|Member|Description|
|---|---|
|[`ulong&nbsp;AddObject(BoundingBoxD&nbsp;bbox,&nbsp;IMyActivationHandler&nbsp;activationHandler,&nbsp;Nullable<ulong>&nbsp;customId,&nbsp;string&nbsp;tag,&nbsp;long&nbsp;entityId,&nbsp;bool&nbsp;batch)`](VRageMath.Spatial.AddObject)||
|static&nbsp;[`BoundingBoxD&nbsp;AdjustAABBByVelocity(BoundingBoxD&nbsp;aabb,&nbsp;Vector3&nbsp;velocity,&nbsp;float&nbsp;inflate)`](VRageMath.Spatial.AdjustAABBByVelocity)||
|[`void&nbsp;MoveObject(ulong&nbsp;id,&nbsp;BoundingBoxD&nbsp;aabb,&nbsp;Vector3&nbsp;velocity)`](VRageMath.Spatial.MoveObject)||
|[`void&nbsp;EnsureClusterSpace(BoundingBoxD&nbsp;aabb)`](VRageMath.Spatial.EnsureClusterSpace)||
|[`void&nbsp;RemoveObject(ulong&nbsp;id)`](VRageMath.Spatial.RemoveObject)||
|[`Vector3D&nbsp;GetObjectOffset(ulong&nbsp;id)`](VRageMath.Spatial.GetObjectOffset)||
|[`MyCluster&nbsp;GetClusterForPosition(Vector3D&nbsp;pos)`](VRageMath.Spatial.GetClusterForPosition)||
|[`void&nbsp;Dispose()`](VRageMath.Spatial.Dispose)||
|[`ListReader<Object>&nbsp;GetList()`](VRageMath.Spatial.GetList)||
|[`ListReader<Object>&nbsp;GetListCopy()`](VRageMath.Spatial.GetListCopy)||
|[`ListReader<MyCluster>&nbsp;GetClusters()`](VRageMath.Spatial.GetClusters)||
|[`void&nbsp;CastRay(Vector3D&nbsp;from,&nbsp;Vector3D&nbsp;to,&nbsp;List<MyClusterQueryResult>&nbsp;results)`](VRageMath.Spatial.CastRay)||
|[`void&nbsp;Intersects(Vector3D&nbsp;translation,&nbsp;List<MyClusterQueryResult>&nbsp;results)`](VRageMath.Spatial.Intersects)||
|[`void&nbsp;GetAll(List<MyClusterQueryResult>&nbsp;results)`](VRageMath.Spatial.GetAll)||
|[`void&nbsp;ReorderClusters(BoundingBoxD&nbsp;aabb,&nbsp;ulong&nbsp;objectId)`](VRageMath.Spatial.ReorderClusters)||
|[`void&nbsp;GetAllStaticObjects(List<BoundingBoxD>&nbsp;staticObjects)`](VRageMath.Spatial.GetAllStaticObjects)||
|[`void&nbsp;Serialize(List<BoundingBoxD>&nbsp;list)`](VRageMath.Spatial.Serialize)||
|[`void&nbsp;Deserialize(List<BoundingBoxD>&nbsp;list)`](VRageMath.Spatial.Deserialize)||
