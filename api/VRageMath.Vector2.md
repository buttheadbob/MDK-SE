← [Index](index.md)
#Vector2 Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
##Summary
Defines a vector with two components.
###Fields
|Member|Description|
|---|---|
|[`float X`](VRageMath.X.md)||
|[`float Y`](VRageMath.Y.md)||
|[`Vector2 Zero`](VRageMath.Zero.md)||
|[`Vector2 One`](VRageMath.One.md)||
|[`Vector2 UnitX`](VRageMath.UnitX.md)||
|[`Vector2 UnitY`](VRageMath.UnitY.md)||
|[`Vector2 PositiveInfinity`](VRageMath.PositiveInfinity.md)||
###Properties
|Member|Description|
|---|---|
|[`float Item`](VRageMath.Item.md)||
###Methods
|Member|Description|
|---|---|
|[`string ToString()`](VRageMath.ToString.md)||
|[`bool Equals(Vector2 other)`](VRageMath.Equals.md)|Determines whether the specified Object is equal to the Vector2.|
|[`bool Equals(Object obj)`](VRageMath.Equals.md)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`bool IsValid()`](VRageMath.IsValid.md)||
|[`void AssertIsValid()`](VRageMath.AssertIsValid.md)||
|[`float Length()`](VRageMath.Length.md)||
|[`float LengthSquared()`](VRageMath.LengthSquared.md)||
|[`float Distance(Vector2 value1, Vector2 value2)`](VRageMath.Distance.md)||
|[`void Distance(ref Vector2 value1, ref Vector2 value2, ref float result)`](VRageMath.Distance.md)||
|[`float DistanceSquared(Vector2 value1, Vector2 value2)`](VRageMath.DistanceSquared.md)||
|[`void DistanceSquared(ref Vector2 value1, ref Vector2 value2, ref float result)`](VRageMath.DistanceSquared.md)||
|[`float Dot(Vector2 value1, Vector2 value2)`](VRageMath.Dot.md)||
|[`void Dot(ref Vector2 value1, ref Vector2 value2, ref float result)`](VRageMath.Dot.md)||
|[`void Normalize()`](VRageMath.Normalize.md)||
|[`Vector2 Normalize(Vector2 value)`](VRageMath.Normalize.md)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[`void Normalize(ref Vector2 value, ref Vector2 result)`](VRageMath.Normalize.md)||
|[`Vector2 Reflect(Vector2 vector, Vector2 normal)`](VRageMath.Reflect.md)||
|[`void Reflect(ref Vector2 vector, ref Vector2 normal, ref Vector2 result)`](VRageMath.Reflect.md)||
|[`Vector2 Min(Vector2 value1, Vector2 value2)`](VRageMath.Min.md)||
|[`void Min(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)`](VRageMath.Min.md)||
|[`Vector2 Max(Vector2 value1, Vector2 value2)`](VRageMath.Max.md)||
|[`void Max(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)`](VRageMath.Max.md)||
|[`Vector2 Clamp(Vector2 value1, Vector2 min, Vector2 max)`](VRageMath.Clamp.md)||
|[`void Clamp(ref Vector2 value1, ref Vector2 min, ref Vector2 max, ref Vector2 result)`](VRageMath.Clamp.md)||
|[`Vector2 ClampToSphere(Vector2 vector, float radius)`](VRageMath.ClampToSphere.md)||
|[`void ClampToSphere(ref Vector2 vector, float radius)`](VRageMath.ClampToSphere.md)||
|[`Vector2 Lerp(Vector2 value1, Vector2 value2, float amount)`](VRageMath.Lerp.md)||
|[`void Lerp(ref Vector2 value1, ref Vector2 value2, float amount, ref Vector2 result)`](VRageMath.Lerp.md)||
|[`Vector2 Barycentric(Vector2 value1, Vector2 value2, Vector2 value3, float amount1, float amount2)`](VRageMath.Barycentric.md)||
|[`void Barycentric(ref Vector2 value1, ref Vector2 value2, ref Vector2 value3, float amount1, float amount2, ref Vector2 result)`](VRageMath.Barycentric.md)||
|[`Vector2 SmoothStep(Vector2 value1, Vector2 value2, float amount)`](VRageMath.SmoothStep.md)||
|[`void SmoothStep(ref Vector2 value1, ref Vector2 value2, float amount, ref Vector2 result)`](VRageMath.SmoothStep.md)||
|[`Vector2 CatmullRom(Vector2 value1, Vector2 value2, Vector2 value3, Vector2 value4, float amount)`](VRageMath.CatmullRom.md)||
|[`void CatmullRom(ref Vector2 value1, ref Vector2 value2, ref Vector2 value3, ref Vector2 value4, float amount, ref Vector2 result)`](VRageMath.CatmullRom.md)||
|[`Vector2 Hermite(Vector2 value1, Vector2 tangent1, Vector2 value2, Vector2 tangent2, float amount)`](VRageMath.Hermite.md)||
|[`void Hermite(ref Vector2 value1, ref Vector2 tangent1, ref Vector2 value2, ref Vector2 tangent2, float amount, ref Vector2 result)`](VRageMath.Hermite.md)||
|[`Vector2 Transform(Vector2 position, Matrix matrix)`](VRageMath.Transform.md)||
|[`void Transform(ref Vector2 position, ref Matrix matrix, ref Vector2 result)`](VRageMath.Transform.md)||
|[`Vector2 TransformNormal(Vector2 normal, Matrix matrix)`](VRageMath.TransformNormal.md)||
|[`void TransformNormal(ref Vector2 normal, ref Matrix matrix, ref Vector2 result)`](VRageMath.TransformNormal.md)||
|[`Vector2 Transform(Vector2 value, Quaternion rotation)`](VRageMath.Transform.md)||
|[`void Transform(ref Vector2 value, ref Quaternion rotation, ref Vector2 result)`](VRageMath.Transform.md)||
|[`void Transform(Vector2[] sourceArray, ref Matrix matrix, Vector2[] destinationArray)`](VRageMath.Transform.md)||
|[`void Transform(Vector2[] sourceArray, int sourceIndex, ref Matrix matrix, Vector2[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform.md)||
|[`void TransformNormal(Vector2[] sourceArray, ref Matrix matrix, Vector2[] destinationArray)`](VRageMath.TransformNormal.md)||
|[`void TransformNormal(Vector2[] sourceArray, int sourceIndex, ref Matrix matrix, Vector2[] destinationArray, int destinationIndex, int length)`](VRageMath.TransformNormal.md)||
|[`void Transform(Vector2[] sourceArray, ref Quaternion rotation, Vector2[] destinationArray)`](VRageMath.Transform.md)||
|[`void Transform(Vector2[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector2[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform.md)||
|[`Vector2 Negate(Vector2 value)`](VRageMath.Negate.md)|Returns a vector pointing in the opposite direction.|
|[`void Negate(ref Vector2 value, ref Vector2 result)`](VRageMath.Negate.md)||
|[`Vector2 Add(Vector2 value1, Vector2 value2)`](VRageMath.Add.md)||
|[`void Add(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)`](VRageMath.Add.md)||
|[`Vector2 Subtract(Vector2 value1, Vector2 value2)`](VRageMath.Subtract.md)||
|[`void Subtract(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)`](VRageMath.Subtract.md)||
|[`Vector2 Multiply(Vector2 value1, Vector2 value2)`](VRageMath.Multiply.md)||
|[`void Multiply(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)`](VRageMath.Multiply.md)||
|[`Vector2 Multiply(Vector2 value1, float scaleFactor)`](VRageMath.Multiply.md)||
|[`void Multiply(ref Vector2 value1, float scaleFactor, ref Vector2 result)`](VRageMath.Multiply.md)||
|[`Vector2 Divide(Vector2 value1, Vector2 value2)`](VRageMath.Divide.md)||
|[`void Divide(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)`](VRageMath.Divide.md)||
|[`Vector2 Divide(Vector2 value1, float divider)`](VRageMath.Divide.md)||
|[`void Divide(ref Vector2 value1, float divider, ref Vector2 result)`](VRageMath.Divide.md)||
|[`bool Between(ref Vector2 start, ref Vector2 end)`](VRageMath.Between.md)||
|[`Vector2 Floor(Vector2 position)`](VRageMath.Floor.md)||
|[`void Rotate(double angle)`](VRageMath.Rotate.md)||
|[`bool IsZero(ref Vector2 value)`](VRageMath.IsZero.md)||
|[`bool IsZero(ref Vector2 value, float epsilon)`](VRageMath.IsZero.md)||
|[`bool IsZero(Vector2 value, float epsilon)`](VRageMath.IsZero.md)||
|[`Vector2 SignNonZero(Vector2 value)`](VRageMath.SignNonZero.md)||
