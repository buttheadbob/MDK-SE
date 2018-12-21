← [Index](index)
# MyVector3Grid Class
**Namespace:** [`VRageMath.Spatial`](VRageMath.Spatial)  
**Assembly:** VRage.Math.dll  
### Properties
<table style="width:100%;display:table">
<tr><td>[`int Count`](VRageMath.Spatial.Count)</td><td></td></tr>
<tr><td>[`int InvalidIndex`](VRageMath.Spatial.InvalidIndex)</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>[`void Clear()`](VRageMath.Spatial.Clear)</td><td></td></tr>
<tr><td>[`void ClearFast()`](VRageMath.Spatial.ClearFast)</td><td></td></tr>
<tr><td>[`void AddPoint(ref Vector3 point, T data)`](VRageMath.Spatial.AddPoint)</td><td></td></tr>
<tr><td>[`void RemovePoint(ref Vector3 point)`](VRageMath.Spatial.RemovePoint)</td><td></td></tr>
<tr><td>[`void MovePoint(int index, ref Vector3 newPosition)`](VRageMath.Spatial.MovePoint)</td><td></td></tr>
<tr><td>[`int FindPointIndex(ref Vector3 point, T data)`](VRageMath.Spatial.FindPointIndex)</td><td></td></tr>
<tr><td>[`T GetData(int index)`](VRageMath.Spatial.GetData)</td><td></td></tr>
<tr><td>[`Vector3 GetPoint(int index)`](VRageMath.Spatial.GetPoint)</td><td></td></tr>
<tr><td>[`SphereQuery<T> QueryPointsSphere(ref Vector3 point, float dist)`](VRageMath.Spatial.QueryPointsSphere)</td><td></td></tr>
<tr><td>[`void RemoveTwo(ref SphereQuery<T> en0, ref SphereQuery<T> en1)`](VRageMath.Spatial.RemoveTwo)</td><td></td></tr>
<tr><td>[`Enumerator<Vector3I, int> EnumerateBins()`](VRageMath.Spatial.EnumerateBins)</td><td></td></tr>
<tr><td>[`int GetNextBinIndex(int currentIndex)`](VRageMath.Spatial.GetNextBinIndex)</td><td></td></tr>
<tr><td>[`void GetLocalBinBB(ref Vector3I binPosition, ref BoundingBoxD output)`](VRageMath.Spatial.GetLocalBinBB)</td><td></td></tr>
<tr><td>[`void CollectStorage(int startingIndex, ref List<T> output)`](VRageMath.Spatial.CollectStorage)</td><td></td></tr>
<tr><td>[`void CollectEntireStorage(List<T> output)`](VRageMath.Spatial.CollectEntireStorage)</td><td></td></tr>
</table>
