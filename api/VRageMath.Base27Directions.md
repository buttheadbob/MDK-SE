← [Index](index)
# Base27Directions Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Base 26 directions and Vector3.Zero Each component is only 0,-1 or 1;
### Fields
<table style="width:100%;display:table">
<tr><td>static _<a href="VRageMath.Directions"><code>Vector3[] Directions</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.DirectionsInt"><code>Vector3I[] DirectionsInt</code></a>_</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>static _<a href="VRageMath.IsBaseDirection"><code>bool IsBaseDirection(ref Vector3 vec)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsBaseDirection"><code>bool IsBaseDirection(ref Vector3I vec)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsBaseDirection"><code>bool IsBaseDirection(Vector3 vec)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetVector"><code>Vector3 GetVector(int direction)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetVectorInt"><code>Vector3I GetVectorInt(int direction)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetVector"><code>Vector3 GetVector(Direction dir)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetVectorInt"><code>Vector3I GetVectorInt(Direction dir)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetDirection"><code>Direction GetDirection(Vector3 vec)</code></a>_</td><td>Vector must be normalized, allowed values for components are: 0, 1, -1, 0.707, -0.707, 0.577, -0.577</td></tr>
<tr><td>static _<a href="VRageMath.GetDirection"><code>Direction GetDirection(Vector3I vec)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetDirection"><code>Direction GetDirection(ref Vector3 vec)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetDirection"><code>Direction GetDirection(ref Vector3I vec)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetForward"><code>Direction GetForward(ref Quaternion rot)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetUp"><code>Direction GetUp(ref Quaternion rot)</code></a>_</td><td></td></tr>
</table>
