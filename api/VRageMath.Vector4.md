← [Index](index)
# Vector4 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with four components.
### Fields
|Member|Description|
|---|---|
|[`float X`](VRageMath.X)||
|[`float Y`](VRageMath.Y)||
|[`float Z`](VRageMath.Z)||
|[`float W`](VRageMath.W)||
|[`Vector4 Zero`](VRageMath.Zero)||
|[`Vector4 One`](VRageMath.One)||
|[`Vector4 UnitX`](VRageMath.UnitX)||
|[`Vector4 UnitY`](VRageMath.UnitY)||
|[`Vector4 UnitZ`](VRageMath.UnitZ)||
|[`Vector4 UnitW`](VRageMath.UnitW)||
### Properties
|Member|Description|
|---|---|
|[`float Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|[`Vector4 PackOrthoMatrix(Vector3 position, Vector3 forward, Vector3 up)`](VRageMath.PackOrthoMatrix)||
|[`Vector4 PackOrthoMatrix(ref Matrix matrix)`](VRageMath.PackOrthoMatrix)||
|[`Matrix UnpackOrthoMatrix(ref Vector4 packed)`](VRageMath.UnpackOrthoMatrix)||
|[`void UnpackOrthoMatrix(ref Vector4 packed, ref Matrix matrix)`](VRageMath.UnpackOrthoMatrix)||
|[`string ToString()`](VRageMath.ToString)||
|[`bool Equals(Vector4 other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector4.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`float Length()`](VRageMath.Length)||
|[`float LengthSquared()`](VRageMath.LengthSquared)||
|[`float Distance(Vector4 value1, Vector4 value2)`](VRageMath.Distance)||
|[`void Distance(ref Vector4 value1, ref Vector4 value2, ref float result)`](VRageMath.Distance)||
|[`float DistanceSquared(Vector4 value1, Vector4 value2)`](VRageMath.DistanceSquared)||
|[`void DistanceSquared(ref Vector4 value1, ref Vector4 value2, ref float result)`](VRageMath.DistanceSquared)||
|[`float Dot(Vector4 vector1, Vector4 vector2)`](VRageMath.Dot)||
|[`void Dot(ref Vector4 vector1, ref Vector4 vector2, ref float result)`](VRageMath.Dot)||
|[`void Normalize()`](VRageMath.Normalize)||
|[`Vector4 Normalize(Vector4 vector)`](VRageMath.Normalize)|Creates a unit vector from the specified vector.|
|[`void Normalize(ref Vector4 vector, ref Vector4 result)`](VRageMath.Normalize)||
|[`Vector4 Min(Vector4 value1, Vector4 value2)`](VRageMath.Min)||
|[`void Min(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Min)||
|[`Vector4 Max(Vector4 value1, Vector4 value2)`](VRageMath.Max)||
|[`void Max(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Max)||
|[`Vector4 Clamp(Vector4 value1, Vector4 min, Vector4 max)`](VRageMath.Clamp)||
|[`void Clamp(ref Vector4 value1, ref Vector4 min, ref Vector4 max, ref Vector4 result)`](VRageMath.Clamp)||
|[`Vector4 Lerp(Vector4 value1, Vector4 value2, float amount)`](VRageMath.Lerp)||
|[`void Lerp(ref Vector4 value1, ref Vector4 value2, float amount, ref Vector4 result)`](VRageMath.Lerp)||
|[`Vector4 Barycentric(Vector4 value1, Vector4 value2, Vector4 value3, float amount1, float amount2)`](VRageMath.Barycentric)||
|[`void Barycentric(ref Vector4 value1, ref Vector4 value2, ref Vector4 value3, float amount1, float amount2, ref Vector4 result)`](VRageMath.Barycentric)||
|[`Vector4 SmoothStep(Vector4 value1, Vector4 value2, float amount)`](VRageMath.SmoothStep)||
|[`void SmoothStep(ref Vector4 value1, ref Vector4 value2, float amount, ref Vector4 result)`](VRageMath.SmoothStep)||
|[`Vector4 CatmullRom(Vector4 value1, Vector4 value2, Vector4 value3, Vector4 value4, float amount)`](VRageMath.CatmullRom)||
|[`void CatmullRom(ref Vector4 value1, ref Vector4 value2, ref Vector4 value3, ref Vector4 value4, float amount, ref Vector4 result)`](VRageMath.CatmullRom)||
|[`Vector4 Hermite(Vector4 value1, Vector4 tangent1, Vector4 value2, Vector4 tangent2, float amount)`](VRageMath.Hermite)||
|[`void Hermite(ref Vector4 value1, ref Vector4 tangent1, ref Vector4 value2, ref Vector4 tangent2, float amount, ref Vector4 result)`](VRageMath.Hermite)||
|[`Vector4 Transform(Vector2 position, Matrix matrix)`](VRageMath.Transform)||
|[`void Transform(ref Vector2 position, ref Matrix matrix, ref Vector4 result)`](VRageMath.Transform)||
|[`Vector4 Transform(Vector3 position, Matrix matrix)`](VRageMath.Transform)||
|[`void Transform(ref Vector3 position, ref Matrix matrix, ref Vector4 result)`](VRageMath.Transform)||
|[`Vector4 Transform(Vector4 vector, Matrix matrix)`](VRageMath.Transform)||
|[`void Transform(ref Vector4 vector, ref Matrix matrix, ref Vector4 result)`](VRageMath.Transform)||
|[`Vector4 Transform(Vector2 value, Quaternion rotation)`](VRageMath.Transform)||
|[`void Transform(ref Vector2 value, ref Quaternion rotation, ref Vector4 result)`](VRageMath.Transform)||
|[`Vector4 Transform(Vector3 value, Quaternion rotation)`](VRageMath.Transform)||
|[`void Transform(ref Vector3 value, ref Quaternion rotation, ref Vector4 result)`](VRageMath.Transform)||
|[`Vector4 Transform(Vector4 value, Quaternion rotation)`](VRageMath.Transform)||
|[`void Transform(ref Vector4 value, ref Quaternion rotation, ref Vector4 result)`](VRageMath.Transform)||
|[`void Transform(Vector4[] sourceArray, ref Matrix matrix, Vector4[] destinationArray)`](VRageMath.Transform)||
|[`void Transform(Vector4[] sourceArray, int sourceIndex, ref Matrix matrix, Vector4[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)||
|[`void Transform(Vector4[] sourceArray, ref Quaternion rotation, Vector4[] destinationArray)`](VRageMath.Transform)||
|[`void Transform(Vector4[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector4[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)||
|[`Vector4 Negate(Vector4 value)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|[`void Negate(ref Vector4 value, ref Vector4 result)`](VRageMath.Negate)||
|[`Vector4 Add(Vector4 value1, Vector4 value2)`](VRageMath.Add)||
|[`void Add(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Add)||
|[`Vector4 Subtract(Vector4 value1, Vector4 value2)`](VRageMath.Subtract)||
|[`void Subtract(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Subtract)||
|[`Vector4 Multiply(Vector4 value1, Vector4 value2)`](VRageMath.Multiply)||
|[`void Multiply(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Multiply)||
|[`Vector4 Multiply(Vector4 value1, float scaleFactor)`](VRageMath.Multiply)||
|[`void Multiply(ref Vector4 value1, float scaleFactor, ref Vector4 result)`](VRageMath.Multiply)||
|[`Vector4 Divide(Vector4 value1, Vector4 value2)`](VRageMath.Divide)||
|[`void Divide(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Divide)||
|[`Vector4 Divide(Vector4 value1, float divider)`](VRageMath.Divide)||
|[`void Divide(ref Vector4 value1, float divider, ref Vector4 result)`](VRageMath.Divide)||
