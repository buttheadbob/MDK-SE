← [Index](index)
# Base6Directions Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|static&nbsp;[`Direction[]&nbsp;EnumDirections`](VRageMath.EnumDirections)||
|static&nbsp;[`Vector3[]&nbsp;Directions`](VRageMath.Directions)||
|static&nbsp;[`Vector3I[]&nbsp;IntDirections`](VRageMath.IntDirections)||
### Methods
|Member|Description|
|---|---|
|static&nbsp;[`bool&nbsp;IsBaseDirection(ref&nbsp;Vector3&nbsp;vec)`](VRageMath.IsBaseDirection)||
|static&nbsp;[`bool&nbsp;IsBaseDirection(Vector3&nbsp;vec)`](VRageMath.IsBaseDirection)||
|static&nbsp;[`bool&nbsp;IsBaseDirection(ref&nbsp;Vector3I&nbsp;vec)`](VRageMath.IsBaseDirection)||
|static&nbsp;[`Vector3&nbsp;GetVector(int&nbsp;direction)`](VRageMath.GetVector)||
|static&nbsp;[`Vector3&nbsp;GetVector(Direction&nbsp;dir)`](VRageMath.GetVector)||
|static&nbsp;[`Vector3I&nbsp;GetIntVector(int&nbsp;direction)`](VRageMath.GetIntVector)||
|static&nbsp;[`Vector3I&nbsp;GetIntVector(Direction&nbsp;dir)`](VRageMath.GetIntVector)||
|static&nbsp;[`void&nbsp;GetVector(Direction&nbsp;dir,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.GetVector)||
|static&nbsp;[`DirectionFlags&nbsp;GetDirectionFlag(Direction&nbsp;dir)`](VRageMath.GetDirectionFlag)||
|static&nbsp;[`Direction&nbsp;GetPerpendicular(Direction&nbsp;dir)`](VRageMath.GetPerpendicular)||
|static&nbsp;[`Direction&nbsp;GetDirection(Vector3&nbsp;vec)`](VRageMath.GetDirection)||
|static&nbsp;[`Direction&nbsp;GetDirection(ref&nbsp;Vector3&nbsp;vec)`](VRageMath.GetDirection)||
|static&nbsp;[`Direction&nbsp;GetDirection(Vector3I&nbsp;vec)`](VRageMath.GetDirection)||
|static&nbsp;[`Direction&nbsp;GetDirection(ref&nbsp;Vector3I&nbsp;vec)`](VRageMath.GetDirection)||
|static&nbsp;[`Direction&nbsp;GetClosestDirection(Vector3&nbsp;vec)`](VRageMath.GetClosestDirection)||
|static&nbsp;[`Direction&nbsp;GetClosestDirection(ref&nbsp;Vector3&nbsp;vec)`](VRageMath.GetClosestDirection)||
|static&nbsp;[`Direction&nbsp;GetDirectionInAxis(Vector3&nbsp;vec,&nbsp;Axis&nbsp;axis)`](VRageMath.GetDirectionInAxis)||
|static&nbsp;[`Direction&nbsp;GetDirectionInAxis(ref&nbsp;Vector3&nbsp;vec,&nbsp;Axis&nbsp;axis)`](VRageMath.GetDirectionInAxis)||
|static&nbsp;[`Direction&nbsp;GetForward(Quaternion&nbsp;rot)`](VRageMath.GetForward)||
|static&nbsp;[`Direction&nbsp;GetForward(ref&nbsp;Quaternion&nbsp;rot)`](VRageMath.GetForward)||
|static&nbsp;[`Direction&nbsp;GetForward(ref&nbsp;Matrix&nbsp;rotation)`](VRageMath.GetForward)||
|static&nbsp;[`Direction&nbsp;GetUp(Quaternion&nbsp;rot)`](VRageMath.GetUp)||
|static&nbsp;[`Direction&nbsp;GetUp(ref&nbsp;Quaternion&nbsp;rot)`](VRageMath.GetUp)||
|static&nbsp;[`Direction&nbsp;GetUp(ref&nbsp;Matrix&nbsp;rotation)`](VRageMath.GetUp)||
|static&nbsp;[`Axis&nbsp;GetAxis(Direction&nbsp;direction)`](VRageMath.GetAxis)||
|static&nbsp;[`Direction&nbsp;GetBaseAxisDirection(Axis&nbsp;axis)`](VRageMath.GetBaseAxisDirection)||
|static&nbsp;[`Direction&nbsp;GetFlippedDirection(Direction&nbsp;toFlip)`](VRageMath.GetFlippedDirection)||
|static&nbsp;[`Direction&nbsp;GetCross(Direction&nbsp;dir1,&nbsp;Direction&nbsp;dir2)`](VRageMath.GetCross)||
|static&nbsp;[`Direction&nbsp;GetLeft(Direction&nbsp;up,&nbsp;Direction&nbsp;forward)`](VRageMath.GetLeft)||
|static&nbsp;[`Direction&nbsp;GetOppositeDirection(Direction&nbsp;dir)`](VRageMath.GetOppositeDirection)||
|static&nbsp;[`Quaternion&nbsp;GetOrientation(Direction&nbsp;forward,&nbsp;Direction&nbsp;up)`](VRageMath.GetOrientation)||
|static&nbsp;[`bool&nbsp;IsValidBlockOrientation(Direction&nbsp;forward,&nbsp;Direction&nbsp;up)`](VRageMath.IsValidBlockOrientation)||
