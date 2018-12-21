← [Index](index)
# MyClusterTree Class
**Namespace:** [`VRageMath.Spatial`](VRageMath.Spatial)  
**Assembly:** VRage.Math.dll  
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Spatial.OnClusterCreated"><code>Func<int, BoundingBoxD, Object> OnClusterCreated</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.OnClusterRemoved"><code>Action<Object> OnClusterRemoved</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.OnFinishBatch"><code>Action<Object> OnFinishBatch</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.OnClustersReordered"><code>Action OnClustersReordered</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.GetEntityReplicableExistsById"><code>Func<long, bool> GetEntityReplicableExistsById</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.SingleCluster"><code>Nullable<BoundingBoxD> SingleCluster</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.ForcedClusters"><code>bool ForcedClusters</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Spatial.IdealClusterSize"><code>Vector3 IdealClusterSize</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Spatial.IdealClusterSizeHalfSqr"><code>Vector3 IdealClusterSizeHalfSqr</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Spatial.MinimumDistanceFromBorder"><code>Vector3 MinimumDistanceFromBorder</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Spatial.MaximumForSplit"><code>Vector3 MaximumForSplit</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Spatial.MaximumClusterSize"><code>float MaximumClusterSize</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Spatial.CLUSTERED_OBJECT_ID_UNITIALIZED"><code>ulong CLUSTERED_OBJECT_ID_UNITIALIZED</code></a>_</td><td></td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Spatial.SuppressClusterReorder"><code>bool SuppressClusterReorder</code></a>_</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Spatial.AddObject"><code>ulong AddObject(BoundingBoxD bbox, IMyActivationHandler activationHandler, Nullable<ulong> customId, string tag, long entityId, bool batch)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Spatial.AdjustAABBByVelocity"><code>BoundingBoxD AdjustAABBByVelocity(BoundingBoxD aabb, Vector3 velocity, float inflate)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.MoveObject"><code>void MoveObject(ulong id, BoundingBoxD aabb, Vector3 velocity)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.EnsureClusterSpace"><code>void EnsureClusterSpace(BoundingBoxD aabb)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.RemoveObject"><code>void RemoveObject(ulong id)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.GetObjectOffset"><code>Vector3D GetObjectOffset(ulong id)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.GetClusterForPosition"><code>MyCluster GetClusterForPosition(Vector3D pos)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.Dispose"><code>void Dispose()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.GetList"><code>ListReader<Object> GetList()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.GetListCopy"><code>ListReader<Object> GetListCopy()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.GetClusters"><code>ListReader<MyCluster> GetClusters()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.CastRay"><code>void CastRay(Vector3D from, Vector3D to, List<MyClusterQueryResult> results)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.Intersects"><code>void Intersects(Vector3D translation, List<MyClusterQueryResult> results)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.GetAll"><code>void GetAll(List<MyClusterQueryResult> results)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.ReorderClusters"><code>void ReorderClusters(BoundingBoxD aabb, ulong objectId)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.GetAllStaticObjects"><code>void GetAllStaticObjects(List<BoundingBoxD> staticObjects)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.Serialize"><code>void Serialize(List<BoundingBoxD> list)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.Deserialize"><code>void Deserialize(List<BoundingBoxD> list)</code></a>_</td><td></td></tr>
</table>
