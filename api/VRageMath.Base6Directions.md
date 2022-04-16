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
|\\$1static Vector3\\$1] Directions](VRageMath.Base6Directions.Directions)||
|\\$1static Direction\\$1] EnumDirections](VRageMath.Base6Directions.EnumDirections)|Because Enum.GetValues(...) returns array of objects|
|\\$1static Vector3I\\$1] IntDirections](VRageMath.Base6Directions.IntDirections)||

#### Methods

|Member|Description|
|---|---|
|\\$1static Axis GetAxis(Direction)](VRageMath.Base6Directions.GetAxis)||
|\\$1static Direction GetBaseAxisDirection(Axis)](VRageMath.Base6Directions.GetBaseAxisDirection)||
|\\$1static Direction GetClosestDirection(Vector3)](VRageMath.Base6Directions.GetClosestDirection)||
|\\$1static Direction GetClosestDirection(ref Vector3)](VRageMath.Base6Directions.GetClosestDirection)||
|\\$1static Direction GetCross(Direction, Direction)](VRageMath.Base6Directions.GetCross)||
|\\$1static Direction GetDirection(Vector3)](VRageMath.Base6Directions.GetDirection)||
|\\$1static Direction GetDirection(ref Vector3)](VRageMath.Base6Directions.GetDirection)||
|\\$1static Direction GetDirection(Vector3I)](VRageMath.Base6Directions.GetDirection)||
|\\$1static Direction GetDirection(ref Vector3I)](VRageMath.Base6Directions.GetDirection)||
|\\$1static DirectionFlags GetDirectionFlag(Direction)](VRageMath.Base6Directions.GetDirectionFlag)||
|\\$1static Direction GetDirectionInAxis(Vector3, Axis)](VRageMath.Base6Directions.GetDirectionInAxis)||
|\\$1static Direction GetDirectionInAxis(ref Vector3, Axis)](VRageMath.Base6Directions.GetDirectionInAxis)||
|\\$1static Direction GetFlippedDirection(Direction)](VRageMath.Base6Directions.GetFlippedDirection)||
|\\$1static Direction GetForward(Quaternion)](VRageMath.Base6Directions.GetForward)||
|\\$1static Direction GetForward(ref Quaternion)](VRageMath.Base6Directions.GetForward)||
|\\$1static Direction GetForward(ref Matrix)](VRageMath.Base6Directions.GetForward)||
|\\$1static Vector3I GetIntVector(int)](VRageMath.Base6Directions.GetIntVector)||
|\\$1static Vector3I GetIntVector(Direction)](VRageMath.Base6Directions.GetIntVector)||
|\\$1static Direction GetLeft(Direction, Direction)](VRageMath.Base6Directions.GetLeft)||
|\\$1static Direction GetOppositeDirection(Direction)](VRageMath.Base6Directions.GetOppositeDirection)||
|\\$1static Quaternion GetOrientation(Direction, Direction)](VRageMath.Base6Directions.GetOrientation)||
|\\$1static Direction GetPerpendicular(Direction)](VRageMath.Base6Directions.GetPerpendicular)||
|\\$1static Direction GetUp(Quaternion)](VRageMath.Base6Directions.GetUp)||
|\\$1static Direction GetUp(ref Quaternion)](VRageMath.Base6Directions.GetUp)||
|\\$1static Direction GetUp(ref Matrix)](VRageMath.Base6Directions.GetUp)||
|\\$1static Vector3 GetVector(int)](VRageMath.Base6Directions.GetVector)||
|\\$1static Vector3 GetVector(Direction)](VRageMath.Base6Directions.GetVector)||
|\\$1static void GetVector(Direction, out Vector3)](VRageMath.Base6Directions.GetVector)||
|\\$1static bool IsBaseDirection(ref Vector3)](VRageMath.Base6Directions.IsBaseDirection)||
|\\$1static bool IsBaseDirection(Vector3)](VRageMath.Base6Directions.IsBaseDirection)||
|\\$1static bool IsBaseDirection(ref Vector3I)](VRageMath.Base6Directions.IsBaseDirection)||
|\\$1static bool IsValidBlockOrientation(Direction, Direction)](VRageMath.Base6Directions.IsValidBlockOrientation)||

