← [Index](index)
# Base27Directions Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Base 26 directions and Vector3.Zero Each component is only 0,-1 or 1;
### Fields
|Member|Description|
|---|---|
|static&nbsp;[`Vector3[]&nbsp;Directions`](VRageMath.Directions)||
|static&nbsp;[`Vector3I[]&nbsp;DirectionsInt`](VRageMath.DirectionsInt)||
### Methods
|Member|Description|
|---|---|
|static&nbsp;[`bool&nbsp;IsBaseDirection(ref&nbsp;Vector3&nbsp;vec)`](VRageMath.IsBaseDirection)||
|static&nbsp;[`bool&nbsp;IsBaseDirection(ref&nbsp;Vector3I&nbsp;vec)`](VRageMath.IsBaseDirection)||
|static&nbsp;[`bool&nbsp;IsBaseDirection(Vector3&nbsp;vec)`](VRageMath.IsBaseDirection)||
|static&nbsp;[`Vector3&nbsp;GetVector(int&nbsp;direction)`](VRageMath.GetVector)||
|static&nbsp;[`Vector3I&nbsp;GetVectorInt(int&nbsp;direction)`](VRageMath.GetVectorInt)||
|static&nbsp;[`Vector3&nbsp;GetVector(Direction&nbsp;dir)`](VRageMath.GetVector)||
|static&nbsp;[`Vector3I&nbsp;GetVectorInt(Direction&nbsp;dir)`](VRageMath.GetVectorInt)||
|static&nbsp;[`Direction&nbsp;GetDirection(Vector3&nbsp;vec)`](VRageMath.GetDirection)|Vector must be normalized, allowed values for components are: 0, 1, -1, 0.707, -0.707, 0.577, -0.577|
|static&nbsp;[`Direction&nbsp;GetDirection(Vector3I&nbsp;vec)`](VRageMath.GetDirection)||
|static&nbsp;[`Direction&nbsp;GetDirection(ref&nbsp;Vector3&nbsp;vec)`](VRageMath.GetDirection)||
|static&nbsp;[`Direction&nbsp;GetDirection(ref&nbsp;Vector3I&nbsp;vec)`](VRageMath.GetDirection)||
|static&nbsp;[`Direction&nbsp;GetForward(ref&nbsp;Quaternion&nbsp;rot)`](VRageMath.GetForward)||
|static&nbsp;[`Direction&nbsp;GetUp(ref&nbsp;Quaternion&nbsp;rot)`](VRageMath.GetUp)||
