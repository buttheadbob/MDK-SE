← [Index](index.md)
# Base27Directions Class
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Base 26 directions and Vector3.Zero Each component is only 0,-1 or 1;
### Fields
|Member|Description|
|---|---|
|[`Vector3[] Directions`](VRageMath.Directions)||
|[`Vector3I[] DirectionsInt`](VRageMath.DirectionsInt)||
### Methods
|Member|Description|
|---|---|
|[`bool IsBaseDirection(ref Vector3 vec)`](VRageMath.IsBaseDirection)||
|[`bool IsBaseDirection(ref Vector3I vec)`](VRageMath.IsBaseDirection)||
|[`bool IsBaseDirection(Vector3 vec)`](VRageMath.IsBaseDirection)||
|[`Vector3 GetVector(int direction)`](VRageMath.GetVector)||
|[`Vector3I GetVectorInt(int direction)`](VRageMath.GetVectorInt)||
|[`Vector3 GetVector(Direction dir)`](VRageMath.GetVector)||
|[`Vector3I GetVectorInt(Direction dir)`](VRageMath.GetVectorInt)||
|[`Direction GetDirection(Vector3 vec)`](VRageMath.GetDirection)|Vector must be normalized, allowed values for components are: 0, 1, -1, 0.707, -0.707, 0.577, -0.577|
|[`Direction GetDirection(Vector3I vec)`](VRageMath.GetDirection)||
|[`Direction GetDirection(ref Vector3 vec)`](VRageMath.GetDirection)||
|[`Direction GetDirection(ref Vector3I vec)`](VRageMath.GetDirection)||
|[`Direction GetForward(ref Quaternion rot)`](VRageMath.GetForward)||
|[`Direction GetUp(ref Quaternion rot)`](VRageMath.GetUp)||
