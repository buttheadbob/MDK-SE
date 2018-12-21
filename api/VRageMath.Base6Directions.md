← [Index](index)
# Base6Directions Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|static [`Direction[] EnumDirections`](VRageMath.EnumDirections)||
|static [`Vector3[] Directions`](VRageMath.Directions)||
|static [`Vector3I[] IntDirections`](VRageMath.IntDirections)||
### Methods
|Member|Description|
|---|---|
|static [`bool IsBaseDirection(ref Vector3 vec)`](VRageMath.IsBaseDirection)||
|static [`bool IsBaseDirection(Vector3 vec)`](VRageMath.IsBaseDirection)||
|static [`bool IsBaseDirection(ref Vector3I vec)`](VRageMath.IsBaseDirection)||
|static [`Vector3 GetVector(int direction)`](VRageMath.GetVector)||
|static [`Vector3 GetVector(Direction dir)`](VRageMath.GetVector)||
|static [`Vector3I GetIntVector(int direction)`](VRageMath.GetIntVector)||
|static [`Vector3I GetIntVector(Direction dir)`](VRageMath.GetIntVector)||
|static [`void GetVector(Direction dir, ref Vector3 result)`](VRageMath.GetVector)||
|static [`DirectionFlags GetDirectionFlag(Direction dir)`](VRageMath.GetDirectionFlag)||
|static [`Direction GetPerpendicular(Direction dir)`](VRageMath.GetPerpendicular)||
|static [`Direction GetDirection(Vector3 vec)`](VRageMath.GetDirection)||
|static [`Direction GetDirection(ref Vector3 vec)`](VRageMath.GetDirection)||
|static [`Direction GetDirection(Vector3I vec)`](VRageMath.GetDirection)||
|static [`Direction GetDirection(ref Vector3I vec)`](VRageMath.GetDirection)||
|static [`Direction GetClosestDirection(Vector3 vec)`](VRageMath.GetClosestDirection)||
|static [`Direction GetClosestDirection(ref Vector3 vec)`](VRageMath.GetClosestDirection)||
|static [`Direction GetDirectionInAxis(Vector3 vec, Axis axis)`](VRageMath.GetDirectionInAxis)||
|static [`Direction GetDirectionInAxis(ref Vector3 vec, Axis axis)`](VRageMath.GetDirectionInAxis)||
|static [`Direction GetForward(Quaternion rot)`](VRageMath.GetForward)||
|static [`Direction GetForward(ref Quaternion rot)`](VRageMath.GetForward)||
|static [`Direction GetForward(ref Matrix rotation)`](VRageMath.GetForward)||
|static [`Direction GetUp(Quaternion rot)`](VRageMath.GetUp)||
|static [`Direction GetUp(ref Quaternion rot)`](VRageMath.GetUp)||
|static [`Direction GetUp(ref Matrix rotation)`](VRageMath.GetUp)||
|static [`Axis GetAxis(Direction direction)`](VRageMath.GetAxis)||
|static [`Direction GetBaseAxisDirection(Axis axis)`](VRageMath.GetBaseAxisDirection)||
|static [`Direction GetFlippedDirection(Direction toFlip)`](VRageMath.GetFlippedDirection)||
|static [`Direction GetCross(Direction dir1, Direction dir2)`](VRageMath.GetCross)||
|static [`Direction GetLeft(Direction up, Direction forward)`](VRageMath.GetLeft)||
|static [`Direction GetOppositeDirection(Direction dir)`](VRageMath.GetOppositeDirection)||
|static [`Quaternion GetOrientation(Direction forward, Direction up)`](VRageMath.GetOrientation)||
|static [`bool IsValidBlockOrientation(Direction forward, Direction up)`](VRageMath.IsValidBlockOrientation)||
