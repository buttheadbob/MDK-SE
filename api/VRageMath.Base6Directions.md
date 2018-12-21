← [Index](index)
# Base6Directions Class
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`Direction[] EnumDirections`](VRageMath.EnumDirections)||
|[`Vector3[] Directions`](VRageMath.Directions)||
|[`Vector3I[] IntDirections`](VRageMath.IntDirections)||
### Methods
|Member|Description|
|---|---|
|[`bool IsBaseDirection(ref Vector3 vec)`](VRageMath.IsBaseDirection)||
|[`bool IsBaseDirection(Vector3 vec)`](VRageMath.IsBaseDirection)||
|[`bool IsBaseDirection(ref Vector3I vec)`](VRageMath.IsBaseDirection)||
|[`Vector3 GetVector(int direction)`](VRageMath.GetVector)||
|[`Vector3 GetVector(Direction dir)`](VRageMath.GetVector)||
|[`Vector3I GetIntVector(int direction)`](VRageMath.GetIntVector)||
|[`Vector3I GetIntVector(Direction dir)`](VRageMath.GetIntVector)||
|[`void GetVector(Direction dir, ref Vector3 result)`](VRageMath.GetVector)||
|[`DirectionFlags GetDirectionFlag(Direction dir)`](VRageMath.GetDirectionFlag)||
|[`Direction GetPerpendicular(Direction dir)`](VRageMath.GetPerpendicular)||
|[`Direction GetDirection(Vector3 vec)`](VRageMath.GetDirection)||
|[`Direction GetDirection(ref Vector3 vec)`](VRageMath.GetDirection)||
|[`Direction GetDirection(Vector3I vec)`](VRageMath.GetDirection)||
|[`Direction GetDirection(ref Vector3I vec)`](VRageMath.GetDirection)||
|[`Direction GetClosestDirection(Vector3 vec)`](VRageMath.GetClosestDirection)||
|[`Direction GetClosestDirection(ref Vector3 vec)`](VRageMath.GetClosestDirection)||
|[`Direction GetDirectionInAxis(Vector3 vec, Axis axis)`](VRageMath.GetDirectionInAxis)||
|[`Direction GetDirectionInAxis(ref Vector3 vec, Axis axis)`](VRageMath.GetDirectionInAxis)||
|[`Direction GetForward(Quaternion rot)`](VRageMath.GetForward)||
|[`Direction GetForward(ref Quaternion rot)`](VRageMath.GetForward)||
|[`Direction GetForward(ref Matrix rotation)`](VRageMath.GetForward)||
|[`Direction GetUp(Quaternion rot)`](VRageMath.GetUp)||
|[`Direction GetUp(ref Quaternion rot)`](VRageMath.GetUp)||
|[`Direction GetUp(ref Matrix rotation)`](VRageMath.GetUp)||
|[`Axis GetAxis(Direction direction)`](VRageMath.GetAxis)||
|[`Direction GetBaseAxisDirection(Axis axis)`](VRageMath.GetBaseAxisDirection)||
|[`Direction GetFlippedDirection(Direction toFlip)`](VRageMath.GetFlippedDirection)||
|[`Direction GetCross(Direction dir1, Direction dir2)`](VRageMath.GetCross)||
|[`Direction GetLeft(Direction up, Direction forward)`](VRageMath.GetLeft)||
|[`Direction GetOppositeDirection(Direction dir)`](VRageMath.GetOppositeDirection)||
|[`Quaternion GetOrientation(Direction forward, Direction up)`](VRageMath.GetOrientation)||
|[`bool IsValidBlockOrientation(Direction forward, Direction up)`](VRageMath.IsValidBlockOrientation)||
