← [Index](Api-Index) ← [MatrixD](VRageMath.MatrixD)

### Summary

```csharp
public MatrixD CreateShadow(Vector3D lightDirection, Plane plane)
```

Creates a Matrix that flattens geometry into a specified Plane as if casting a shadow from a specified light source.

### Returns

[MatrixD](VRageMath.MatrixD)

### Parameters

* [Vector3D](VRageMath.Vector3D) lightDirection
* [Plane](VRageMath.Plane) plane
### Summary

```csharp
public void CreateShadow(ref Vector3D lightDirection, ref Plane plane, ref MatrixD result)
```

Fills in a Matrix to flatten geometry into a specified Plane as if casting a shadow from a specified light source.

### Parameters

* [Vector3D](VRageMath.Vector3D) lightDirection
* [Plane](VRageMath.Plane) plane
* [MatrixD](VRageMath.MatrixD) result
