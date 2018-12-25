← [Index](Api-Index) ← [IMyCameraBlock](Sandbox.ModAPI.Ingame.IMyCameraBlock)

```csharp[MyDetectedEntityInfo](Sandbox.ModAPI.Ingame.MyDetectedEntityInfo) Raycast([double](System.Double) distance, [float](System.Single) pitch, [float](System.Single) yaw)```##### Summary

Does a raycast in the direction the camera is facing. Pitch and Yaw are in degrees. Will return an empty struct if distance or angle are out of bounds.

##### Returns



```csharp[MyDetectedEntityInfo](Sandbox.ModAPI.Ingame.MyDetectedEntityInfo) Raycast([Vector3D](VRageMath.Vector3D) targetPos)```##### Summary

Does a raycast to the given point. Will return an empty struct if distance or angle are out of bounds.

##### Returns



```csharp[MyDetectedEntityInfo](Sandbox.ModAPI.Ingame.MyDetectedEntityInfo) Raycast([double](System.Double) distance, [Vector3D](VRageMath.Vector3D) targetDirection)```##### Summary

Does a raycast in the given direction. Will return an empty struct if distance or angle are out of bounds.

##### Returns



