← [Index](index.md)
# Vector4 Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with four components.
### Fields
|Member|Description|
|---|---|
|[`float X`](VRageMath.X.md)||
|[`float Y`](VRageMath.Y.md)||
|[`float Z`](VRageMath.Z.md)||
|[`float W`](VRageMath.W.md)||
|[`Vector4 Zero`](VRageMath.Zero.md)||
|[`Vector4 One`](VRageMath.One.md)||
|[`Vector4 UnitX`](VRageMath.UnitX.md)||
|[`Vector4 UnitY`](VRageMath.UnitY.md)||
|[`Vector4 UnitZ`](VRageMath.UnitZ.md)||
|[`Vector4 UnitW`](VRageMath.UnitW.md)||
### Properties
|Member|Description|
|---|---|
|[`float Item`](VRageMath.Item.md)||
### Methods
|Member|Description|
|---|---|
|[`Vector4 PackOrthoMatrix(Vector3 position, Vector3 forward, Vector3 up)`](VRageMath.PackOrthoMatrix.md)||
|[`Vector4 PackOrthoMatrix(ref Matrix matrix)`](VRageMath.PackOrthoMatrix.md)||
|[`Matrix UnpackOrthoMatrix(ref Vector4 packed)`](VRageMath.UnpackOrthoMatrix.md)||
|[`void UnpackOrthoMatrix(ref Vector4 packed, ref Matrix matrix)`](VRageMath.UnpackOrthoMatrix.md)||
|[`string ToString()`](VRageMath.ToString.md)||
|[`bool Equals(Vector4 other)`](VRageMath.Equals.md)|Determines whether the specified Object is equal to the Vector4.|
|[`bool Equals(Object obj)`](VRageMath.Equals.md)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`float Length()`](VRageMath.Length.md)||
|[`float LengthSquared()`](VRageMath.LengthSquared.md)||
|[`float Distance(Vector4 value1, Vector4 value2)`](VRageMath.Distance.md)||
|[`void Distance(ref Vector4 value1, ref Vector4 value2, ref float result)`](VRageMath.Distance.md)||
|[`float DistanceSquared(Vector4 value1, Vector4 value2)`](VRageMath.DistanceSquared.md)||
|[`void DistanceSquared(ref Vector4 value1, ref Vector4 value2, ref float result)`](VRageMath.DistanceSquared.md)||
|[`float Dot(Vector4 vector1, Vector4 vector2)`](VRageMath.Dot.md)||
|[`void Dot(ref Vector4 vector1, ref Vector4 vector2, ref float result)`](VRageMath.Dot.md)||
|[`void Normalize()`](VRageMath.Normalize.md)||
|[`Vector4 Normalize(Vector4 vector)`](VRageMath.Normalize.md)|Creates a unit vector from the specified vector.|
|[`void Normalize(ref Vector4 vector, ref Vector4 result)`](VRageMath.Normalize.md)||
|[`Vector4 Min(Vector4 value1, Vector4 value2)`](VRageMath.Min.md)||
|[`void Min(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Min.md)||
|[`Vector4 Max(Vector4 value1, Vector4 value2)`](VRageMath.Max.md)||
|[`void Max(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Max.md)||
|[`Vector4 Clamp(Vector4 value1, Vector4 min, Vector4 max)`](VRageMath.Clamp.md)||
|[`void Clamp(ref Vector4 value1, ref Vector4 min, ref Vector4 max, ref Vector4 result)`](VRageMath.Clamp.md)||
|[`Vector4 Lerp(Vector4 value1, Vector4 value2, float amount)`](VRageMath.Lerp.md)||
|[`void Lerp(ref Vector4 value1, ref Vector4 value2, float amount, ref Vector4 result)`](VRageMath.Lerp.md)||
|[`Vector4 Barycentric(Vector4 value1, Vector4 value2, Vector4 value3, float amount1, float amount2)`](VRageMath.Barycentric.md)||
|[`void Barycentric(ref Vector4 value1, ref Vector4 value2, ref Vector4 value3, float amount1, float amount2, ref Vector4 result)`](VRageMath.Barycentric.md)||
|[`Vector4 SmoothStep(Vector4 value1, Vector4 value2, float amount)`](VRageMath.SmoothStep.md)||
|[`void SmoothStep(ref Vector4 value1, ref Vector4 value2, float amount, ref Vector4 result)`](VRageMath.SmoothStep.md)||
|[`Vector4 CatmullRom(Vector4 value1, Vector4 value2, Vector4 value3, Vector4 value4, float amount)`](VRageMath.CatmullRom.md)||
|[`void CatmullRom(ref Vector4 value1, ref Vector4 value2, ref Vector4 value3, ref Vector4 value4, float amount, ref Vector4 result)`](VRageMath.CatmullRom.md)||
|[`Vector4 Hermite(Vector4 value1, Vector4 tangent1, Vector4 value2, Vector4 tangent2, float amount)`](VRageMath.Hermite.md)||
|[`void Hermite(ref Vector4 value1, ref Vector4 tangent1, ref Vector4 value2, ref Vector4 tangent2, float amount, ref Vector4 result)`](VRageMath.Hermite.md)||
|[`Vector4 Transform(Vector2 position, Matrix matrix)`](VRageMath.Transform.md)||
|[`void Transform(ref Vector2 position, ref Matrix matrix, ref Vector4 result)`](VRageMath.Transform.md)||
|[`Vector4 Transform(Vector3 position, Matrix matrix)`](VRageMath.Transform.md)||
|[`void Transform(ref Vector3 position, ref Matrix matrix, ref Vector4 result)`](VRageMath.Transform.md)||
|[`Vector4 Transform(Vector4 vector, Matrix matrix)`](VRageMath.Transform.md)||
|[`void Transform(ref Vector4 vector, ref Matrix matrix, ref Vector4 result)`](VRageMath.Transform.md)||
|[`Vector4 Transform(Vector2 value, Quaternion rotation)`](VRageMath.Transform.md)||
|[`void Transform(ref Vector2 value, ref Quaternion rotation, ref Vector4 result)`](VRageMath.Transform.md)||
|[`Vector4 Transform(Vector3 value, Quaternion rotation)`](VRageMath.Transform.md)||
|[`void Transform(ref Vector3 value, ref Quaternion rotation, ref Vector4 result)`](VRageMath.Transform.md)||
|[`Vector4 Transform(Vector4 value, Quaternion rotation)`](VRageMath.Transform.md)||
|[`void Transform(ref Vector4 value, ref Quaternion rotation, ref Vector4 result)`](VRageMath.Transform.md)||
|[`void Transform(Vector4[] sourceArray, ref Matrix matrix, Vector4[] destinationArray)`](VRageMath.Transform.md)||
|[`void Transform(Vector4[] sourceArray, int sourceIndex, ref Matrix matrix, Vector4[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform.md)||
|[`void Transform(Vector4[] sourceArray, ref Quaternion rotation, Vector4[] destinationArray)`](VRageMath.Transform.md)||
|[`void Transform(Vector4[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector4[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform.md)||
|[`Vector4 Negate(Vector4 value)`](VRageMath.Negate.md)|Returns a vector pointing in the opposite direction.|
|[`void Negate(ref Vector4 value, ref Vector4 result)`](VRageMath.Negate.md)||
|[`Vector4 Add(Vector4 value1, Vector4 value2)`](VRageMath.Add.md)||
|[`void Add(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Add.md)||
|[`Vector4 Subtract(Vector4 value1, Vector4 value2)`](VRageMath.Subtract.md)||
|[`void Subtract(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Subtract.md)||
|[`Vector4 Multiply(Vector4 value1, Vector4 value2)`](VRageMath.Multiply.md)||
|[`void Multiply(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Multiply.md)||
|[`Vector4 Multiply(Vector4 value1, float scaleFactor)`](VRageMath.Multiply.md)||
|[`void Multiply(ref Vector4 value1, float scaleFactor, ref Vector4 result)`](VRageMath.Multiply.md)||
|[`Vector4 Divide(Vector4 value1, Vector4 value2)`](VRageMath.Divide.md)||
|[`void Divide(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Divide.md)||
|[`Vector4 Divide(Vector4 value1, float divider)`](VRageMath.Divide.md)||
|[`void Divide(ref Vector4 value1, float divider, ref Vector4 result)`](VRageMath.Divide.md)||
