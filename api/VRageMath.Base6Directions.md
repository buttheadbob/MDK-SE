← [Index](index)
# Base6Directions Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
<table style="width:100%;display:table">
<tr><td>static [`Direction[] EnumDirections`](VRageMath.EnumDirections)</td><td></td></tr>
<tr><td>static [`Vector3[] Directions`](VRageMath.Directions)</td><td></td></tr>
<tr><td>static [`Vector3I[] IntDirections`](VRageMath.IntDirections)</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>static [`bool IsBaseDirection(ref Vector3 vec)`](VRageMath.IsBaseDirection)</td><td></td></tr>
<tr><td>static [`bool IsBaseDirection(Vector3 vec)`](VRageMath.IsBaseDirection)</td><td></td></tr>
<tr><td>static [`bool IsBaseDirection(ref Vector3I vec)`](VRageMath.IsBaseDirection)</td><td></td></tr>
<tr><td>static [`Vector3 GetVector(int direction)`](VRageMath.GetVector)</td><td></td></tr>
<tr><td>static [`Vector3 GetVector(Direction dir)`](VRageMath.GetVector)</td><td></td></tr>
<tr><td>static [`Vector3I GetIntVector(int direction)`](VRageMath.GetIntVector)</td><td></td></tr>
<tr><td>static [`Vector3I GetIntVector(Direction dir)`](VRageMath.GetIntVector)</td><td></td></tr>
<tr><td>static [`void GetVector(Direction dir, ref Vector3 result)`](VRageMath.GetVector)</td><td></td></tr>
<tr><td>static [`DirectionFlags GetDirectionFlag(Direction dir)`](VRageMath.GetDirectionFlag)</td><td></td></tr>
<tr><td>static [`Direction GetPerpendicular(Direction dir)`](VRageMath.GetPerpendicular)</td><td></td></tr>
<tr><td>static [`Direction GetDirection(Vector3 vec)`](VRageMath.GetDirection)</td><td></td></tr>
<tr><td>static [`Direction GetDirection(ref Vector3 vec)`](VRageMath.GetDirection)</td><td></td></tr>
<tr><td>static [`Direction GetDirection(Vector3I vec)`](VRageMath.GetDirection)</td><td></td></tr>
<tr><td>static [`Direction GetDirection(ref Vector3I vec)`](VRageMath.GetDirection)</td><td></td></tr>
<tr><td>static [`Direction GetClosestDirection(Vector3 vec)`](VRageMath.GetClosestDirection)</td><td></td></tr>
<tr><td>static [`Direction GetClosestDirection(ref Vector3 vec)`](VRageMath.GetClosestDirection)</td><td></td></tr>
<tr><td>static [`Direction GetDirectionInAxis(Vector3 vec, Axis axis)`](VRageMath.GetDirectionInAxis)</td><td></td></tr>
<tr><td>static [`Direction GetDirectionInAxis(ref Vector3 vec, Axis axis)`](VRageMath.GetDirectionInAxis)</td><td></td></tr>
<tr><td>static [`Direction GetForward(Quaternion rot)`](VRageMath.GetForward)</td><td></td></tr>
<tr><td>static [`Direction GetForward(ref Quaternion rot)`](VRageMath.GetForward)</td><td></td></tr>
<tr><td>static [`Direction GetForward(ref Matrix rotation)`](VRageMath.GetForward)</td><td></td></tr>
<tr><td>static [`Direction GetUp(Quaternion rot)`](VRageMath.GetUp)</td><td></td></tr>
<tr><td>static [`Direction GetUp(ref Quaternion rot)`](VRageMath.GetUp)</td><td></td></tr>
<tr><td>static [`Direction GetUp(ref Matrix rotation)`](VRageMath.GetUp)</td><td></td></tr>
<tr><td>static [`Axis GetAxis(Direction direction)`](VRageMath.GetAxis)</td><td></td></tr>
<tr><td>static [`Direction GetBaseAxisDirection(Axis axis)`](VRageMath.GetBaseAxisDirection)</td><td></td></tr>
<tr><td>static [`Direction GetFlippedDirection(Direction toFlip)`](VRageMath.GetFlippedDirection)</td><td></td></tr>
<tr><td>static [`Direction GetCross(Direction dir1, Direction dir2)`](VRageMath.GetCross)</td><td></td></tr>
<tr><td>static [`Direction GetLeft(Direction up, Direction forward)`](VRageMath.GetLeft)</td><td></td></tr>
<tr><td>static [`Direction GetOppositeDirection(Direction dir)`](VRageMath.GetOppositeDirection)</td><td></td></tr>
<tr><td>static [`Quaternion GetOrientation(Direction forward, Direction up)`](VRageMath.GetOrientation)</td><td></td></tr>
<tr><td>static [`bool IsValidBlockOrientation(Direction forward, Direction up)`](VRageMath.IsValidBlockOrientation)</td><td></td></tr>
</table>
