← [Index](index.md)
#Base27Directions Class
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
##Summary
Base 26 directions and Vector3.Zero Each component is only 0,-1 or 1;
###Fields
|Member|Description|
|---|---|
|[`Vector3[] Directions`](VRageMath.Directions.md)||
|[`Vector3I[] DirectionsInt`](VRageMath.DirectionsInt.md)||
###Methods
|Member|Description|
|---|---|
|[`bool IsBaseDirection(ref Vector3 vec)`](VRageMath.IsBaseDirection.md)||
|[`bool IsBaseDirection(ref Vector3I vec)`](VRageMath.IsBaseDirection.md)||
|[`bool IsBaseDirection(Vector3 vec)`](VRageMath.IsBaseDirection.md)||
|[`Vector3 GetVector(int direction)`](VRageMath.GetVector.md)||
|[`Vector3I GetVectorInt(int direction)`](VRageMath.GetVectorInt.md)||
|[`Vector3 GetVector(Direction dir)`](VRageMath.GetVector.md)||
|[`Vector3I GetVectorInt(Direction dir)`](VRageMath.GetVectorInt.md)||
|[`Direction GetDirection(Vector3 vec)`](VRageMath.GetDirection.md)|Vector must be normalized, allowed values for components are: 0, 1, -1, 0.707, -0.707, 0.577, -0.577|
|[`Direction GetDirection(Vector3I vec)`](VRageMath.GetDirection.md)||
|[`Direction GetDirection(ref Vector3 vec)`](VRageMath.GetDirection.md)||
|[`Direction GetDirection(ref Vector3I vec)`](VRageMath.GetDirection.md)||
|[`Direction GetForward(ref Quaternion rot)`](VRageMath.GetForward.md)||
|[`Direction GetUp(ref Quaternion rot)`](VRageMath.GetUp.md)||
