← [Index](index)
# MyVector3DGrid Class
**Namespace:** VRageMath.Spatial  
**Assembly:** VRage.Math.dll  
### Properties
|Member|Description|
|---|---|
|[`int Count`](VRageMath.Spatial.Count)||
### Methods
|Member|Description|
|---|---|
|[`void Clear()`](VRageMath.Spatial.Clear)||
|[`void ClearFast()`](VRageMath.Spatial.ClearFast)||
|[`void AddPoint(ref Vector3D point, T data)`](VRageMath.Spatial.AddPoint)||
|[`void RemovePoint(ref Vector3D point)`](VRageMath.Spatial.RemovePoint)||
|[`Enumerator<T> GetPointsCloserThan(ref Vector3D point, double dist)`](VRageMath.Spatial.GetPointsCloserThan)||
|[`void RemoveTwo(ref Enumerator<T> en0, ref Enumerator<T> en1)`](VRageMath.Spatial.RemoveTwo)||
|[`Enumerator<Vector3I, int> EnumerateBins()`](VRageMath.Spatial.EnumerateBins)||
|[`void GetLocalBinBB(ref Vector3I binPosition, ref BoundingBoxD output)`](VRageMath.Spatial.GetLocalBinBB)||
|[`void CollectStorage(int startingIndex, ref List<T> output)`](VRageMath.Spatial.CollectStorage)||
