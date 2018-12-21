← [Index](index)
# MyVector3Grid Class
**Namespace:** [`VRageMath.Spatial`](VRageMath.Spatial)  
**Assembly:** VRage.Math.dll  
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Spatial.Count"><code>int Count</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.InvalidIndex"><code>int InvalidIndex</code></a>_</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Spatial.Clear"><code>void Clear()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.ClearFast"><code>void ClearFast()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.AddPoint"><code>void AddPoint(ref Vector3 point, T data)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.RemovePoint"><code>void RemovePoint(ref Vector3 point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.MovePoint"><code>void MovePoint(int index, ref Vector3 newPosition)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.FindPointIndex"><code>int FindPointIndex(ref Vector3 point, T data)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.GetData"><code>T GetData(int index)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.GetPoint"><code>Vector3 GetPoint(int index)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.QueryPointsSphere"><code>SphereQuery<T> QueryPointsSphere(ref Vector3 point, float dist)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.RemoveTwo"><code>void RemoveTwo(ref SphereQuery<T> en0, ref SphereQuery<T> en1)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.EnumerateBins"><code>Enumerator<Vector3I, int> EnumerateBins()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.GetNextBinIndex"><code>int GetNextBinIndex(int currentIndex)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.GetLocalBinBB"><code>void GetLocalBinBB(ref Vector3I binPosition, ref BoundingBoxD output)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.CollectStorage"><code>void CollectStorage(int startingIndex, ref List<T> output)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.CollectEntireStorage"><code>void CollectEntireStorage(List<T> output)</code></a>_</td><td></td></tr>
</table>
