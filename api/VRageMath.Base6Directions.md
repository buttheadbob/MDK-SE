← [Index](index)
# Base6Directions Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
<table style="width:100%;display:table">
<tr><td>static _<a href="VRageMath.EnumDirections"><code>Direction[] EnumDirections</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Directions"><code>Vector3[] Directions</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IntDirections"><code>Vector3I[] IntDirections</code></a>_</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>static _<a href="VRageMath.IsBaseDirection"><code>bool IsBaseDirection(ref Vector3 vec)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsBaseDirection"><code>bool IsBaseDirection(Vector3 vec)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsBaseDirection"><code>bool IsBaseDirection(ref Vector3I vec)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetVector"><code>Vector3 GetVector(int direction)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetVector"><code>Vector3 GetVector(Direction dir)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetIntVector"><code>Vector3I GetIntVector(int direction)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetIntVector"><code>Vector3I GetIntVector(Direction dir)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetVector"><code>void GetVector(Direction dir, ref Vector3 result)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetDirectionFlag"><code>DirectionFlags GetDirectionFlag(Direction dir)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetPerpendicular"><code>Direction GetPerpendicular(Direction dir)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetDirection"><code>Direction GetDirection(Vector3 vec)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetDirection"><code>Direction GetDirection(ref Vector3 vec)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetDirection"><code>Direction GetDirection(Vector3I vec)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetDirection"><code>Direction GetDirection(ref Vector3I vec)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetClosestDirection"><code>Direction GetClosestDirection(Vector3 vec)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetClosestDirection"><code>Direction GetClosestDirection(ref Vector3 vec)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetDirectionInAxis"><code>Direction GetDirectionInAxis(Vector3 vec, Axis axis)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetDirectionInAxis"><code>Direction GetDirectionInAxis(ref Vector3 vec, Axis axis)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetForward"><code>Direction GetForward(Quaternion rot)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetForward"><code>Direction GetForward(ref Quaternion rot)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetForward"><code>Direction GetForward(ref Matrix rotation)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetUp"><code>Direction GetUp(Quaternion rot)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetUp"><code>Direction GetUp(ref Quaternion rot)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetUp"><code>Direction GetUp(ref Matrix rotation)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetAxis"><code>Axis GetAxis(Direction direction)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetBaseAxisDirection"><code>Direction GetBaseAxisDirection(Axis axis)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetFlippedDirection"><code>Direction GetFlippedDirection(Direction toFlip)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetCross"><code>Direction GetCross(Direction dir1, Direction dir2)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetLeft"><code>Direction GetLeft(Direction up, Direction forward)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetOppositeDirection"><code>Direction GetOppositeDirection(Direction dir)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetOrientation"><code>Quaternion GetOrientation(Direction forward, Direction up)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsValidBlockOrientation"><code>bool IsValidBlockOrientation(Direction forward, Direction up)</code></a>_</td><td></td></tr>
</table>
