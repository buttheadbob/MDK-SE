← [Index](Api-Index) ← [Namespace Index](Namespace-Index) ← [MatrixD](VRageMath.MatrixD)

### Summary

```csharp
public bool HasNoTranslationOrPerspective()
```

Returns true if this matrix represents invertible (you can call Invert on it) linear (it does not contain translation or perspective transformation) transformation. Such matrix consist solely of rotations, shearing, mirroring and scaling. It can be orthogonalized to create an orthogonal rotation matrix.

### Returns

[bool](https://docs.microsoft.com/en-us/dotnet/api/system.boolean?view=netframework-4.6)

