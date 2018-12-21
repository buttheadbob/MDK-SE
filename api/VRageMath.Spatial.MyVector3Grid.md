← [Index](index)
# MyVector3Grid Class
**Namespace:** [`VRageMath.Spatial`](VRageMath.Spatial)  
**Assembly:** VRage.Math.dll  
### Properties
|Member|Description|
|---|---|
|[`int Count`](VRageMath.Spatial.Count)||
|[`int InvalidIndex`](VRageMath.Spatial.InvalidIndex)||
### Methods
|Member|Description|
|---|---|
|[`void Clear()`](VRageMath.Spatial.Clear)||
|[`void ClearFast()`](VRageMath.Spatial.ClearFast)||
|[`void AddPoint(ref VRageMath.Vector3, VRageMath.Spatial.T)`](VRageMath.Spatial.AddPoint)||
|[`void RemovePoint(ref VRageMath.Vector3)`](VRageMath.Spatial.RemovePoint)||
|[`void MovePoint(int, ref VRageMath.Vector3)`](VRageMath.Spatial.MovePoint)||
|[`int FindPointIndex(ref VRageMath.Vector3, VRageMath.Spatial.T)`](VRageMath.Spatial.FindPointIndex)||
|[`VRageMath.Spatial.T GetData(int)`](VRageMath.Spatial.GetData)||
|[`VRageMath.Vector3 GetPoint(int)`](VRageMath.Spatial.GetPoint)||
|[`SphereQuery<T> QueryPointsSphere(ref VRageMath.Vector3, float)`](VRageMath.Spatial.QueryPointsSphere)||
|[`void RemoveTwo(ref SphereQuery<T>, ref SphereQuery<T>)`](VRageMath.Spatial.RemoveTwo)||
|[`Enumerator<VRageMath.Vector3I, System.Int32> EnumerateBins()`](VRageMath.Spatial.EnumerateBins)||
|[`int GetNextBinIndex(int)`](VRageMath.Spatial.GetNextBinIndex)||
|[`void GetLocalBinBB(ref VRageMath.Vector3I, ref VRageMath.BoundingBoxD)`](VRageMath.Spatial.GetLocalBinBB)||
|[`void CollectStorage(int, ref List<T>)`](VRageMath.Spatial.CollectStorage)||
|[`void CollectEntireStorage(List<T>)`](VRageMath.Spatial.CollectEntireStorage)||
