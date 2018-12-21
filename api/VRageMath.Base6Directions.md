← [Index](index.md)
# Base6Directions Class
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`Direction[] EnumDirections`](VRageMath.EnumDirections.md)||
|[`Vector3[] Directions`](VRageMath.Directions.md)||
|[`Vector3I[] IntDirections`](VRageMath.IntDirections.md)||
### Methods
|Member|Description|
|---|---|
|[`bool IsBaseDirection(ref Vector3 vec)`](VRageMath.IsBaseDirection.md)||
|[`bool IsBaseDirection(Vector3 vec)`](VRageMath.IsBaseDirection.md)||
|[`bool IsBaseDirection(ref Vector3I vec)`](VRageMath.IsBaseDirection.md)||
|[`Vector3 GetVector(int direction)`](VRageMath.GetVector.md)||
|[`Vector3 GetVector(Direction dir)`](VRageMath.GetVector.md)||
|[`Vector3I GetIntVector(int direction)`](VRageMath.GetIntVector.md)||
|[`Vector3I GetIntVector(Direction dir)`](VRageMath.GetIntVector.md)||
|[`void GetVector(Direction dir, ref Vector3 result)`](VRageMath.GetVector.md)||
|[`DirectionFlags GetDirectionFlag(Direction dir)`](VRageMath.GetDirectionFlag.md)||
|[`Direction GetPerpendicular(Direction dir)`](VRageMath.GetPerpendicular.md)||
|[`Direction GetDirection(Vector3 vec)`](VRageMath.GetDirection.md)||
|[`Direction GetDirection(ref Vector3 vec)`](VRageMath.GetDirection.md)||
|[`Direction GetDirection(Vector3I vec)`](VRageMath.GetDirection.md)||
|[`Direction GetDirection(ref Vector3I vec)`](VRageMath.GetDirection.md)||
|[`Direction GetClosestDirection(Vector3 vec)`](VRageMath.GetClosestDirection.md)||
|[`Direction GetClosestDirection(ref Vector3 vec)`](VRageMath.GetClosestDirection.md)||
|[`Direction GetDirectionInAxis(Vector3 vec, Axis axis)`](VRageMath.GetDirectionInAxis.md)||
|[`Direction GetDirectionInAxis(ref Vector3 vec, Axis axis)`](VRageMath.GetDirectionInAxis.md)||
|[`Direction GetForward(Quaternion rot)`](VRageMath.GetForward.md)||
|[`Direction GetForward(ref Quaternion rot)`](VRageMath.GetForward.md)||
|[`Direction GetForward(ref Matrix rotation)`](VRageMath.GetForward.md)||
|[`Direction GetUp(Quaternion rot)`](VRageMath.GetUp.md)||
|[`Direction GetUp(ref Quaternion rot)`](VRageMath.GetUp.md)||
|[`Direction GetUp(ref Matrix rotation)`](VRageMath.GetUp.md)||
|[`Axis GetAxis(Direction direction)`](VRageMath.GetAxis.md)||
|[`Direction GetBaseAxisDirection(Axis axis)`](VRageMath.GetBaseAxisDirection.md)||
|[`Direction GetFlippedDirection(Direction toFlip)`](VRageMath.GetFlippedDirection.md)||
|[`Direction GetCross(Direction dir1, Direction dir2)`](VRageMath.GetCross.md)||
|[`Direction GetLeft(Direction up, Direction forward)`](VRageMath.GetLeft.md)||
|[`Direction GetOppositeDirection(Direction dir)`](VRageMath.GetOppositeDirection.md)||
|[`Quaternion GetOrientation(Direction forward, Direction up)`](VRageMath.GetOrientation.md)||
|[`bool IsValidBlockOrientation(Direction forward, Direction up)`](VRageMath.IsValidBlockOrientation.md)||
