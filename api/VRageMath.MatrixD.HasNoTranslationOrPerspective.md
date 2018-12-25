← [Index](Api-Index) ← [MatrixD](VRageMath.MatrixD)

```csharp[bool](System.Boolean) HasNoTranslationOrPerspective()```##### Summary

Returns true if this matrix represents invertible (you can call Invert on it) linear (it does not contain translation or perspective transformation) transformation. Such matrix consist solely of rotations, shearing, mirroring and scaling. It can be orthogonalized to create an orthogonal rotation matrix.

