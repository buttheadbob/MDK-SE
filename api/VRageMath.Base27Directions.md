← [Index](index)
# Base27Directions Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Base 26 directions and Vector3.Zero Each component is only 0,-1 or 1;
### Fields
|Member|Description|
|---|---|
|static [`VRageMath.Vector3[] Directions`](VRageMath.Directions)||
|static [`VRageMath.Vector3I[] DirectionsInt`](VRageMath.DirectionsInt)||
### Methods
|Member|Description|
|---|---|
|static [`bool IsBaseDirection(ref VRageMath.Vector3)`](VRageMath.IsBaseDirection)||
|static [`bool IsBaseDirection(ref VRageMath.Vector3I)`](VRageMath.IsBaseDirection)||
|static [`bool IsBaseDirection(VRageMath.Vector3)`](VRageMath.IsBaseDirection)||
|static [`VRageMath.Vector3 GetVector(int)`](VRageMath.GetVector)||
|static [`VRageMath.Vector3I GetVectorInt(int)`](VRageMath.GetVectorInt)||
|static [`VRageMath.Vector3 GetVector(VRageMath.Direction)`](VRageMath.GetVector)||
|static [`VRageMath.Vector3I GetVectorInt(VRageMath.Direction)`](VRageMath.GetVectorInt)||
|static [`VRageMath.Direction GetDirection(VRageMath.Vector3)`](VRageMath.GetDirection)|Vector must be normalized, allowed values for components are: 0, 1, -1, 0.707, -0.707, 0.577, -0.577|
|static [`VRageMath.Direction GetDirection(VRageMath.Vector3I)`](VRageMath.GetDirection)||
|static [`VRageMath.Direction GetDirection(ref VRageMath.Vector3)`](VRageMath.GetDirection)||
|static [`VRageMath.Direction GetDirection(ref VRageMath.Vector3I)`](VRageMath.GetDirection)||
|static [`VRageMath.Direction GetForward(ref VRageMath.Quaternion)`](VRageMath.GetForward)||
|static [`VRageMath.Direction GetUp(ref VRageMath.Quaternion)`](VRageMath.GetUp)||
