← [Index](Api-Index) ← [Namespace Index](Namespace-Index) ← [Vector3UByte](VRageMath.Vector3UByte)

### Summary

```csharp
public Vector3UByte Normalize(Vector3 vec, float range)
```

Normalizes Vector3 into Vector4UByte, scales vector from (-range, range) to (0, 255). Unsafe for values "range >= any_vec_value / 257";

### Returns

[Vector3UByte](VRageMath.Vector3UByte)

### Parameters

* [Vector3](VRageMath.Vector3) vec
* [float](https://docs.microsoft.com/en-us/dotnet/api/system.single?view=netframework-4.6) range
