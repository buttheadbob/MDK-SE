← [Index](index)
# Vector2 Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with two components.
### Fields
|Member|Description|
|---|---|
|[`float X`](VRageMath.X)||
|[`float Y`](VRageMath.Y)||
|[`Vector2 Zero`](VRageMath.Zero)||
|[`Vector2 One`](VRageMath.One)||
|[`Vector2 UnitX`](VRageMath.UnitX)||
|[`Vector2 UnitY`](VRageMath.UnitY)||
|[`Vector2 PositiveInfinity`](VRageMath.PositiveInfinity)||
### Properties
|Member|Description|
|---|---|
|[`float Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|[`string ToString()`](VRageMath.ToString)||
|[`bool Equals(Vector2 other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector2.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`bool IsValid()`](VRageMath.IsValid)||
|[`void AssertIsValid()`](VRageMath.AssertIsValid)||
|[`float Length()`](VRageMath.Length)||
|[`float LengthSquared()`](VRageMath.LengthSquared)||
|[`float Distance(Vector2 value1, Vector2 value2)`](VRageMath.Distance)||
|[`void Distance(ref Vector2 value1, ref Vector2 value2, ref float result)`](VRageMath.Distance)||
|[`float DistanceSquared(Vector2 value1, Vector2 value2)`](VRageMath.DistanceSquared)||
|[`void DistanceSquared(ref Vector2 value1, ref Vector2 value2, ref float result)`](VRageMath.DistanceSquared)||
|[`float Dot(Vector2 value1, Vector2 value2)`](VRageMath.Dot)||
|[`void Dot(ref Vector2 value1, ref Vector2 value2, ref float result)`](VRageMath.Dot)||
|[`void Normalize()`](VRageMath.Normalize)||
|[`Vector2 Normalize(Vector2 value)`](VRageMath.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[`void Normalize(ref Vector2 value, ref Vector2 result)`](VRageMath.Normalize)||
|[`Vector2 Reflect(Vector2 vector, Vector2 normal)`](VRageMath.Reflect)||
|[`void Reflect(ref Vector2 vector, ref Vector2 normal, ref Vector2 result)`](VRageMath.Reflect)||
|[`Vector2 Min(Vector2 value1, Vector2 value2)`](VRageMath.Min)||
|[`void Min(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)`](VRageMath.Min)||
|[`Vector2 Max(Vector2 value1, Vector2 value2)`](VRageMath.Max)||
|[`void Max(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)`](VRageMath.Max)||
|[`Vector2 Clamp(Vector2 value1, Vector2 min, Vector2 max)`](VRageMath.Clamp)||
|[`void Clamp(ref Vector2 value1, ref Vector2 min, ref Vector2 max, ref Vector2 result)`](VRageMath.Clamp)||
|[`Vector2 ClampToSphere(Vector2 vector, float radius)`](VRageMath.ClampToSphere)||
|[`void ClampToSphere(ref Vector2 vector, float radius)`](VRageMath.ClampToSphere)||
|[`Vector2 Lerp(Vector2 value1, Vector2 value2, float amount)`](VRageMath.Lerp)||
|[`void Lerp(ref Vector2 value1, ref Vector2 value2, float amount, ref Vector2 result)`](VRageMath.Lerp)||
|[`Vector2 Barycentric(Vector2 value1, Vector2 value2, Vector2 value3, float amount1, float amount2)`](VRageMath.Barycentric)||
|[`void Barycentric(ref Vector2 value1, ref Vector2 value2, ref Vector2 value3, float amount1, float amount2, ref Vector2 result)`](VRageMath.Barycentric)||
|[`Vector2 SmoothStep(Vector2 value1, Vector2 value2, float amount)`](VRageMath.SmoothStep)||
|[`void SmoothStep(ref Vector2 value1, ref Vector2 value2, float amount, ref Vector2 result)`](VRageMath.SmoothStep)||
|[`Vector2 CatmullRom(Vector2 value1, Vector2 value2, Vector2 value3, Vector2 value4, float amount)`](VRageMath.CatmullRom)||
|[`void CatmullRom(ref Vector2 value1, ref Vector2 value2, ref Vector2 value3, ref Vector2 value4, float amount, ref Vector2 result)`](VRageMath.CatmullRom)||
|[`Vector2 Hermite(Vector2 value1, Vector2 tangent1, Vector2 value2, Vector2 tangent2, float amount)`](VRageMath.Hermite)||
|[`void Hermite(ref Vector2 value1, ref Vector2 tangent1, ref Vector2 value2, ref Vector2 tangent2, float amount, ref Vector2 result)`](VRageMath.Hermite)||
|[`Vector2 Transform(Vector2 position, Matrix matrix)`](VRageMath.Transform)||
|[`void Transform(ref Vector2 position, ref Matrix matrix, ref Vector2 result)`](VRageMath.Transform)||
|[`Vector2 TransformNormal(Vector2 normal, Matrix matrix)`](VRageMath.TransformNormal)||
|[`void TransformNormal(ref Vector2 normal, ref Matrix matrix, ref Vector2 result)`](VRageMath.TransformNormal)||
|[`Vector2 Transform(Vector2 value, Quaternion rotation)`](VRageMath.Transform)||
|[`void Transform(ref Vector2 value, ref Quaternion rotation, ref Vector2 result)`](VRageMath.Transform)||
|[`void Transform(Vector2[] sourceArray, ref Matrix matrix, Vector2[] destinationArray)`](VRageMath.Transform)||
|[`void Transform(Vector2[] sourceArray, int sourceIndex, ref Matrix matrix, Vector2[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)||
|[`void TransformNormal(Vector2[] sourceArray, ref Matrix matrix, Vector2[] destinationArray)`](VRageMath.TransformNormal)||
|[`void TransformNormal(Vector2[] sourceArray, int sourceIndex, ref Matrix matrix, Vector2[] destinationArray, int destinationIndex, int length)`](VRageMath.TransformNormal)||
|[`void Transform(Vector2[] sourceArray, ref Quaternion rotation, Vector2[] destinationArray)`](VRageMath.Transform)||
|[`void Transform(Vector2[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector2[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)||
|[`Vector2 Negate(Vector2 value)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|[`void Negate(ref Vector2 value, ref Vector2 result)`](VRageMath.Negate)||
|[`Vector2 Add(Vector2 value1, Vector2 value2)`](VRageMath.Add)||
|[`void Add(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)`](VRageMath.Add)||
|[`Vector2 Subtract(Vector2 value1, Vector2 value2)`](VRageMath.Subtract)||
|[`void Subtract(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)`](VRageMath.Subtract)||
|[`Vector2 Multiply(Vector2 value1, Vector2 value2)`](VRageMath.Multiply)||
|[`void Multiply(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)`](VRageMath.Multiply)||
|[`Vector2 Multiply(Vector2 value1, float scaleFactor)`](VRageMath.Multiply)||
|[`void Multiply(ref Vector2 value1, float scaleFactor, ref Vector2 result)`](VRageMath.Multiply)||
|[`Vector2 Divide(Vector2 value1, Vector2 value2)`](VRageMath.Divide)||
|[`void Divide(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)`](VRageMath.Divide)||
|[`Vector2 Divide(Vector2 value1, float divider)`](VRageMath.Divide)||
|[`void Divide(ref Vector2 value1, float divider, ref Vector2 result)`](VRageMath.Divide)||
|[`bool Between(ref Vector2 start, ref Vector2 end)`](VRageMath.Between)||
|[`Vector2 Floor(Vector2 position)`](VRageMath.Floor)||
|[`void Rotate(double angle)`](VRageMath.Rotate)||
|[`bool IsZero(ref Vector2 value)`](VRageMath.IsZero)||
|[`bool IsZero(ref Vector2 value, float epsilon)`](VRageMath.IsZero)||
|[`bool IsZero(Vector2 value, float epsilon)`](VRageMath.IsZero)||
|[`Vector2 SignNonZero(Vector2 value)`](VRageMath.SignNonZero)||
