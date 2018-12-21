← [Index](index.md)
#MyVector3Grid Class
**Namespace:** VRageMath.Spatial  
**Assembly:** VRage.Math.dll  
###Properties
|Member|Description|
|---|---|
|[`int Count`](VRageMath.Spatial.Count.md)||
|[`int InvalidIndex`](VRageMath.Spatial.InvalidIndex.md)||
###Methods
|Member|Description|
|---|---|
|[`void Clear()`](VRageMath.Spatial.Clear.md)||
|[`void ClearFast()`](VRageMath.Spatial.ClearFast.md)||
|[`void AddPoint(ref Vector3 point, T data)`](VRageMath.Spatial.AddPoint.md)||
|[`void RemovePoint(ref Vector3 point)`](VRageMath.Spatial.RemovePoint.md)||
|[`void MovePoint(int index, ref Vector3 newPosition)`](VRageMath.Spatial.MovePoint.md)||
|[`int FindPointIndex(ref Vector3 point, T data)`](VRageMath.Spatial.FindPointIndex.md)||
|[`T GetData(int index)`](VRageMath.Spatial.GetData.md)||
|[`Vector3 GetPoint(int index)`](VRageMath.Spatial.GetPoint.md)||
|[`SphereQuery<T> QueryPointsSphere(ref Vector3 point, float dist)`](VRageMath.Spatial.QueryPointsSphere.md)||
|[`void RemoveTwo(ref SphereQuery<T> en0, ref SphereQuery<T> en1)`](VRageMath.Spatial.RemoveTwo.md)||
|[`Enumerator<Vector3I, int> EnumerateBins()`](VRageMath.Spatial.EnumerateBins.md)||
|[`int GetNextBinIndex(int currentIndex)`](VRageMath.Spatial.GetNextBinIndex.md)||
|[`void GetLocalBinBB(ref Vector3I binPosition, ref BoundingBoxD output)`](VRageMath.Spatial.GetLocalBinBB.md)||
|[`void CollectStorage(int startingIndex, ref List<T> output)`](VRageMath.Spatial.CollectStorage.md)||
|[`void CollectEntireStorage(List<T> output)`](VRageMath.Spatial.CollectEntireStorage.md)||
