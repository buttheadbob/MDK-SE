← [Index](Api-Index) ← [IMyCameraBlock](Sandbox.ModAPI.Ingame.IMyCameraBlock)

### Summary

```csharp
public MyDetectedEntityInfo Raycast(double distance, float pitch, float yaw)
```

Does a raycast in the direction the camera is facing. Pitch and Yaw are in degrees. Will return an empty struct if distance or angle are out of bounds.

### Returns



### Example

### Remarks

### Summary

```csharp
public MyDetectedEntityInfo Raycast(Vector3D targetPos)
```

Does a raycast to the given point. Will return an empty struct if distance or angle are out of bounds.

### Returns



### Example

### Remarks

### Summary

```csharp
public MyDetectedEntityInfo Raycast(double distance, Vector3D targetDirection)
```

Does a raycast in the given direction. Will return an empty struct if distance or angle are out of bounds.

### Returns



### Example

### Remarks

