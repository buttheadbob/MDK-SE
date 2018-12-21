← [Index](index)
# Base27Directions Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Base 26 directions and Vector3.Zero Each component is only 0,-1 or 1;
### Fields
<table style="width:100%;display:table">
<tr><td>static [`Vector3[] Directions`](VRageMath.Directions)</td><td></td></tr>
<tr><td>static [`Vector3I[] DirectionsInt`](VRageMath.DirectionsInt)</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>static [`bool IsBaseDirection(ref Vector3 vec)`](VRageMath.IsBaseDirection)</td><td></td></tr>
<tr><td>static [`bool IsBaseDirection(ref Vector3I vec)`](VRageMath.IsBaseDirection)</td><td></td></tr>
<tr><td>static [`bool IsBaseDirection(Vector3 vec)`](VRageMath.IsBaseDirection)</td><td></td></tr>
<tr><td>static [`Vector3 GetVector(int direction)`](VRageMath.GetVector)</td><td></td></tr>
<tr><td>static [`Vector3I GetVectorInt(int direction)`](VRageMath.GetVectorInt)</td><td></td></tr>
<tr><td>static [`Vector3 GetVector(Direction dir)`](VRageMath.GetVector)</td><td></td></tr>
<tr><td>static [`Vector3I GetVectorInt(Direction dir)`](VRageMath.GetVectorInt)</td><td></td></tr>
<tr><td>static [`Direction GetDirection(Vector3 vec)`](VRageMath.GetDirection)</td><td>Vector must be normalized, allowed values for components are: 0, 1, -1, 0.707, -0.707, 0.577, -0.577</td></tr>
<tr><td>static [`Direction GetDirection(Vector3I vec)`](VRageMath.GetDirection)</td><td></td></tr>
<tr><td>static [`Direction GetDirection(ref Vector3 vec)`](VRageMath.GetDirection)</td><td></td></tr>
<tr><td>static [`Direction GetDirection(ref Vector3I vec)`](VRageMath.GetDirection)</td><td></td></tr>
<tr><td>static [`Direction GetForward(ref Quaternion rot)`](VRageMath.GetForward)</td><td></td></tr>
<tr><td>static [`Direction GetUp(ref Quaternion rot)`](VRageMath.GetUp)</td><td></td></tr>
</table>
