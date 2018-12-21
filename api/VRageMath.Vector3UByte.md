← [Index](index)
# Vector3UByte Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
<table style="width:100%;display:table">
<tr><td>[`byte X`](VRageMath.X)</td><td></td></tr>
<tr><td>[`byte Y`](VRageMath.Y)</td><td></td></tr>
<tr><td>[`byte Z`](VRageMath.Z)</td><td></td></tr>
<tr><td>static [`EqualityComparer Comparer`](VRageMath.Comparer)</td><td></td></tr>
<tr><td>static [`Vector3UByte Zero`](VRageMath.Zero)</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td></td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td></td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td></td></tr>
<tr><td>static [`Vector3UByte Round(Vector3 vec)`](VRageMath.Round)</td><td></td></tr>
<tr><td>static [`Vector3UByte Floor(Vector3 vec)`](VRageMath.Floor)</td><td></td></tr>
<tr><td>[`int LengthSquared()`](VRageMath.LengthSquared)</td><td></td></tr>
<tr><td>static [`bool IsMiddle(Vector3UByte vec)`](VRageMath.IsMiddle)</td><td>Returns true when all components are 127</td></tr>
<tr><td>static [`Vector3UByte Normalize(Vector3 vec, float range)`](VRageMath.Normalize)</td><td>Normalizes Vector3 into Vector4UByte, scales vector from (-range, range) to (0, 255). Unsafe for values "range >= any_vec_value / 257";</td></tr>
<tr><td>static [`Vector3 Denormalize(Vector3UByte vec, float range)`](VRageMath.Denormalize)</td><td>Unpacks Vector3 from Vector3UByte, scales vector from (0, 255) to (-range, range)</td></tr>
</table>
