← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### Base6Directions Class

```csharp
public class Base6Directions
```

Workaround because .NET XML serializer is stupid and does not like enum inside static class

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

#### Fields

|Member|Description|
|---|---|
|[static Vector3\[] Directions](VRageMath.Base6Directions.Directions)||
|[static Direction\[] EnumDirections](VRageMath.Base6Directions.EnumDirections)|Because Enum.GetValues(...) returns array of objects|
|[static Vector3I\[] IntDirections](VRageMath.Base6Directions.IntDirections)||

#### Methods

|Member|Description|
|---|---|
|[static Axis GetAxis(Direction)](VRageMath.Base6Directions.GetAxis)||
|[static Direction GetBaseAxisDirection(Axis)](VRageMath.Base6Directions.GetBaseAxisDirection)||
|[static Direction GetClosestDirection(Vector3)](VRageMath.Base6Directions.GetClosestDirection)||
|[static Direction GetClosestDirection(ref Vector3)](VRageMath.Base6Directions.GetClosestDirection)||
|[static Direction GetCross(Direction, Direction)](VRageMath.Base6Directions.GetCross)||
|[static Direction GetDirection(Vector3)](VRageMath.Base6Directions.GetDirection)||
|[static Direction GetDirection(ref Vector3)](VRageMath.Base6Directions.GetDirection)||
|[static Direction GetDirection(Vector3I)](VRageMath.Base6Directions.GetDirection)||
|[static Direction GetDirection(ref Vector3I)](VRageMath.Base6Directions.GetDirection)||
|[static DirectionFlags GetDirectionFlag(Direction)](VRageMath.Base6Directions.GetDirectionFlag)||
|[static Direction GetDirectionInAxis(Vector3, Axis)](VRageMath.Base6Directions.GetDirectionInAxis)||
|[static Direction GetDirectionInAxis(ref Vector3, Axis)](VRageMath.Base6Directions.GetDirectionInAxis)||
|[static Direction GetFlippedDirection(Direction)](VRageMath.Base6Directions.GetFlippedDirection)||
|[static Direction GetForward(Quaternion)](VRageMath.Base6Directions.GetForward)||
|[static Direction GetForward(ref Quaternion)](VRageMath.Base6Directions.GetForward)||
|[static Direction GetForward(ref Matrix)](VRageMath.Base6Directions.GetForward)||
|[static Vector3I GetIntVector(int)](VRageMath.Base6Directions.GetIntVector)||
|[static Vector3I GetIntVector(Direction)](VRageMath.Base6Directions.GetIntVector)||
|[static Direction GetLeft(Direction, Direction)](VRageMath.Base6Directions.GetLeft)||
|[static Direction GetOppositeDirection(Direction)](VRageMath.Base6Directions.GetOppositeDirection)||
|[static Quaternion GetOrientation(Direction, Direction)](VRageMath.Base6Directions.GetOrientation)||
|[static Direction GetPerpendicular(Direction)](VRageMath.Base6Directions.GetPerpendicular)||
|[static Direction GetUp(Quaternion)](VRageMath.Base6Directions.GetUp)||
|[static Direction GetUp(ref Quaternion)](VRageMath.Base6Directions.GetUp)||
|[static Direction GetUp(ref Matrix)](VRageMath.Base6Directions.GetUp)||
|[static Vector3 GetVector(int)](VRageMath.Base6Directions.GetVector)||
|[static Vector3 GetVector(Direction)](VRageMath.Base6Directions.GetVector)||
|[static void GetVector(Direction, out Vector3)](VRageMath.Base6Directions.GetVector)||
|[static bool IsBaseDirection(ref Vector3)](VRageMath.Base6Directions.IsBaseDirection)||
|[static bool IsBaseDirection(Vector3)](VRageMath.Base6Directions.IsBaseDirection)||
|[static bool IsBaseDirection(ref Vector3I)](VRageMath.Base6Directions.IsBaseDirection)||
|[static bool IsValidBlockOrientation(Direction, Direction)](VRageMath.Base6Directions.IsValidBlockOrientation)||

