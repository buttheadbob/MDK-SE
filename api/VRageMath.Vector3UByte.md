← [Index](index)
# Vector3UByte Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.X"><code>byte X</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Y"><code>byte Y</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Z"><code>byte Z</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Comparer"><code>EqualityComparer Comparer</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Zero"><code>Vector3UByte Zero</code></a>_</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.ToString"><code>string ToString()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.GetHashCode"><code>int GetHashCode()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Object obj)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Round"><code>Vector3UByte Round(Vector3 vec)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Floor"><code>Vector3UByte Floor(Vector3 vec)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.LengthSquared"><code>int LengthSquared()</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsMiddle"><code>bool IsMiddle(Vector3UByte vec)</code></a>_</td><td>Returns true when all components are 127</td></tr>
<tr><td>static _<a href="VRageMath.Normalize"><code>Vector3UByte Normalize(Vector3 vec, float range)</code></a>_</td><td>Normalizes Vector3 into Vector4UByte, scales vector from (-range, range) to (0, 255). Unsafe for values "range >= any_vec_value / 257";</td></tr>
<tr><td>static _<a href="VRageMath.Denormalize"><code>Vector3 Denormalize(Vector3UByte vec, float range)</code></a>_</td><td>Unpacks Vector3 from Vector3UByte, scales vector from (0, 255) to (-range, range)</td></tr>
</table>
