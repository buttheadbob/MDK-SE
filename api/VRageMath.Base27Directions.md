← [Index](index)
# Base27Directions Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Base 26 directions and Vector3.Zero Each component is only 0,-1 or 1;
### Fields
|Member|Description|
|---|---|
|static [`Vector3[] Directions`](VRageMath.Directions)||
|static [`Vector3I[] DirectionsInt`](VRageMath.DirectionsInt)||
### Methods
|Member|Description|
|---|---|
|static [`bool IsBaseDirection(ref Vector3 vec)`](VRageMath.IsBaseDirection)||
|static [`bool IsBaseDirection(ref Vector3I vec)`](VRageMath.IsBaseDirection)||
|static [`bool IsBaseDirection(Vector3 vec)`](VRageMath.IsBaseDirection)||
|static [`Vector3 GetVector(int direction)`](VRageMath.GetVector)||
|static [`Vector3I GetVectorInt(int direction)`](VRageMath.GetVectorInt)||
|static [`Vector3 GetVector(Direction dir)`](VRageMath.GetVector)||
|static [`Vector3I GetVectorInt(Direction dir)`](VRageMath.GetVectorInt)||
|static [`Direction GetDirection(Vector3 vec)`](VRageMath.GetDirection)|Vector must be normalized, allowed values for components are: 0, 1, -1, 0.707, -0.707, 0.577, -0.577|
|static [`Direction GetDirection(Vector3I vec)`](VRageMath.GetDirection)||
|static [`Direction GetDirection(ref Vector3 vec)`](VRageMath.GetDirection)||
|static [`Direction GetDirection(ref Vector3I vec)`](VRageMath.GetDirection)||
|static [`Direction GetForward(ref Quaternion rot)`](VRageMath.GetForward)||
|static [`Direction GetUp(ref Quaternion rot)`](VRageMath.GetUp)||
