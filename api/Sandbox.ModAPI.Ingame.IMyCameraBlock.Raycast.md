← [Index](Api-Index) ← [Namespace Index](Namespace-Index) ← [IMyCameraBlock](Sandbox.ModAPI.Ingame.IMyCameraBlock)

### Summary

```csharp
public MyDetectedEntityInfo Raycast(double distance, float pitch, float yaw)
```

Does a raycast in the direction the camera is facing. Pitch and Yaw are in degrees. Will return an empty struct if distance or angle are out of bounds.

### Returns

[MyDetectedEntityInfo](Sandbox.ModAPI.Ingame.MyDetectedEntityInfo)



### Parameters

* [double](https://docs.microsoft.com/en-us/dotnet/api/System.Double?view=netframework-4.6) distance
* [float](https://docs.microsoft.com/en-us/dotnet/api/System.Single?view=netframework-4.6) pitch
* [float](https://docs.microsoft.com/en-us/dotnet/api/System.Single?view=netframework-4.6) yaw
### Summary

```csharp
public MyDetectedEntityInfo Raycast(Vector3D targetPos)
```

Does a raycast to the given point. Will return an empty struct if distance or angle are out of bounds.

### Returns

[MyDetectedEntityInfo](Sandbox.ModAPI.Ingame.MyDetectedEntityInfo)



### Parameters

* [Vector3D](VRageMath.Vector3D) targetPos
### Summary

```csharp
public MyDetectedEntityInfo Raycast(double distance, Vector3D targetDirection)
```

Does a raycast in the given direction (in camera local space). Will return an empty struct if distance or angle are out of bounds.

### Returns

[MyDetectedEntityInfo](Sandbox.ModAPI.Ingame.MyDetectedEntityInfo)



### Parameters

* [double](https://docs.microsoft.com/en-us/dotnet/api/System.Double?view=netframework-4.6) distance
* [Vector3D](VRageMath.Vector3D) targetDirection
