← [Index](index)
# MyVector3DGrid Class
**Namespace:** [`VRageMath.Spatial`](VRageMath.Spatial)  
**Assembly:** VRage.Math.dll  
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Spatial.Count"><code>int Count</code></a>_</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Spatial.Clear"><code>void Clear()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.ClearFast"><code>void ClearFast()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.AddPoint"><code>void AddPoint(ref Vector3D point, T data)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.RemovePoint"><code>void RemovePoint(ref Vector3D point)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.GetPointsCloserThan"><code>Enumerator<T> GetPointsCloserThan(ref Vector3D point, double dist)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.RemoveTwo"><code>void RemoveTwo(ref Enumerator<T> en0, ref Enumerator<T> en1)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.EnumerateBins"><code>Enumerator<Vector3I, int> EnumerateBins()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.GetLocalBinBB"><code>void GetLocalBinBB(ref Vector3I binPosition, ref BoundingBoxD output)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Spatial.CollectStorage"><code>void CollectStorage(int startingIndex, ref List<T> output)</code></a>_</td><td></td></tr>
</table>
