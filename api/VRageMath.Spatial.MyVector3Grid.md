← [Index](index.md)
# MyVector3Grid Class
**Namespace:** VRageMath.Spatial  
**Assembly:** VRage.Math.dll  
### Properties
|Member|Description|
|---|---|
|[`int Count`](VRageMath.Spatial.Count)||
|[`int InvalidIndex`](VRageMath.Spatial.InvalidIndex)||
### Methods
|Member|Description|
|---|---|
|[`void Clear()`](VRageMath.Spatial.Clear)||
|[`void ClearFast()`](VRageMath.Spatial.ClearFast)||
|[`void AddPoint(ref Vector3 point, T data)`](VRageMath.Spatial.AddPoint)||
|[`void RemovePoint(ref Vector3 point)`](VRageMath.Spatial.RemovePoint)||
|[`void MovePoint(int index, ref Vector3 newPosition)`](VRageMath.Spatial.MovePoint)||
|[`int FindPointIndex(ref Vector3 point, T data)`](VRageMath.Spatial.FindPointIndex)||
|[`T GetData(int index)`](VRageMath.Spatial.GetData)||
|[`Vector3 GetPoint(int index)`](VRageMath.Spatial.GetPoint)||
|[`SphereQuery<T> QueryPointsSphere(ref Vector3 point, float dist)`](VRageMath.Spatial.QueryPointsSphere)||
|[`void RemoveTwo(ref SphereQuery<T> en0, ref SphereQuery<T> en1)`](VRageMath.Spatial.RemoveTwo)||
|[`Enumerator<Vector3I, int> EnumerateBins()`](VRageMath.Spatial.EnumerateBins)||
|[`int GetNextBinIndex(int currentIndex)`](VRageMath.Spatial.GetNextBinIndex)||
|[`void GetLocalBinBB(ref Vector3I binPosition, ref BoundingBoxD output)`](VRageMath.Spatial.GetLocalBinBB)||
|[`void CollectStorage(int startingIndex, ref List<T> output)`](VRageMath.Spatial.CollectStorage)||
|[`void CollectEntireStorage(List<T> output)`](VRageMath.Spatial.CollectEntireStorage)||
