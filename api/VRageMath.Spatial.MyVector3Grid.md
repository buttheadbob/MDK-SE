← [Index](index)
# MyVector3Grid Class
**Namespace:** [`VRageMath.Spatial`](VRageMath.Spatial)  
**Assembly:** VRage.Math.dll  
### Properties
|Member|Description|
|---|---|
|[`int&nbsp;Count`](VRageMath.Spatial.Count)||
|[`int&nbsp;InvalidIndex`](VRageMath.Spatial.InvalidIndex)||
### Methods
|Member|Description|
|---|---|
|[`void&nbsp;Clear()`](VRageMath.Spatial.Clear)||
|[`void&nbsp;ClearFast()`](VRageMath.Spatial.ClearFast)||
|[`void&nbsp;AddPoint(ref&nbsp;Vector3&nbsp;point,&nbsp;T&nbsp;data)`](VRageMath.Spatial.AddPoint)||
|[`void&nbsp;RemovePoint(ref&nbsp;Vector3&nbsp;point)`](VRageMath.Spatial.RemovePoint)||
|[`void&nbsp;MovePoint(int&nbsp;index,&nbsp;ref&nbsp;Vector3&nbsp;newPosition)`](VRageMath.Spatial.MovePoint)||
|[`int&nbsp;FindPointIndex(ref&nbsp;Vector3&nbsp;point,&nbsp;T&nbsp;data)`](VRageMath.Spatial.FindPointIndex)||
|[`T&nbsp;GetData(int&nbsp;index)`](VRageMath.Spatial.GetData)||
|[`Vector3&nbsp;GetPoint(int&nbsp;index)`](VRageMath.Spatial.GetPoint)||
|[`SphereQuery<T>&nbsp;QueryPointsSphere(ref&nbsp;Vector3&nbsp;point,&nbsp;float&nbsp;dist)`](VRageMath.Spatial.QueryPointsSphere)||
|[`void&nbsp;RemoveTwo(ref&nbsp;SphereQuery<T>&nbsp;en0,&nbsp;ref&nbsp;SphereQuery<T>&nbsp;en1)`](VRageMath.Spatial.RemoveTwo)||
|[`Enumerator<Vector3I,&nbsp;int>&nbsp;EnumerateBins()`](VRageMath.Spatial.EnumerateBins)||
|[`int&nbsp;GetNextBinIndex(int&nbsp;currentIndex)`](VRageMath.Spatial.GetNextBinIndex)||
|[`void&nbsp;GetLocalBinBB(ref&nbsp;Vector3I&nbsp;binPosition,&nbsp;ref&nbsp;BoundingBoxD&nbsp;output)`](VRageMath.Spatial.GetLocalBinBB)||
|[`void&nbsp;CollectStorage(int&nbsp;startingIndex,&nbsp;ref&nbsp;List<T>&nbsp;output)`](VRageMath.Spatial.CollectStorage)||
|[`void&nbsp;CollectEntireStorage(List<T>&nbsp;output)`](VRageMath.Spatial.CollectEntireStorage)||
