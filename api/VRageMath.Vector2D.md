← [Index](index.md)
# Vector2D Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with two components.
### Fields
|Member|Description|
|---|---|
|[`double X`](VRageMath.X)||
|[`double Y`](VRageMath.Y)||
|[`Vector2D Zero`](VRageMath.Zero)||
|[`Vector2D One`](VRageMath.One)||
|[`Vector2D UnitX`](VRageMath.UnitX)||
|[`Vector2D UnitY`](VRageMath.UnitY)||
|[`Vector2D PositiveInfinity`](VRageMath.PositiveInfinity)||
### Properties
|Member|Description|
|---|---|
|[`double Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|[`string ToString()`](VRageMath.ToString)||
|[`bool Equals(Vector2D other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector2D.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`bool IsValid()`](VRageMath.IsValid)||
|[`void AssertIsValid()`](VRageMath.AssertIsValid)||
|[`double Length()`](VRageMath.Length)||
|[`double LengthSquared()`](VRageMath.LengthSquared)||
|[`double Distance(Vector2D value1, Vector2D value2)`](VRageMath.Distance)||
|[`void Distance(ref Vector2D value1, ref Vector2D value2, ref double result)`](VRageMath.Distance)||
|[`double DistanceSquared(Vector2D value1, Vector2D value2)`](VRageMath.DistanceSquared)||
|[`void DistanceSquared(ref Vector2D value1, ref Vector2D value2, ref double result)`](VRageMath.DistanceSquared)||
|[`double Dot(Vector2D value1, Vector2D value2)`](VRageMath.Dot)||
|[`void Dot(ref Vector2D value1, ref Vector2D value2, ref double result)`](VRageMath.Dot)||
|[`void Normalize()`](VRageMath.Normalize)||
|[`Vector2D Normalize(Vector2D value)`](VRageMath.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[`void Normalize(ref Vector2D value, ref Vector2D result)`](VRageMath.Normalize)||
|[`Vector2D Reflect(Vector2D vector, Vector2D normal)`](VRageMath.Reflect)||
|[`void Reflect(ref Vector2D vector, ref Vector2D normal, ref Vector2D result)`](VRageMath.Reflect)||
|[`Vector2D Min(Vector2D value1, Vector2D value2)`](VRageMath.Min)||
|[`void Min(ref Vector2D value1, ref Vector2D value2, ref Vector2D result)`](VRageMath.Min)||
|[`Vector2D Max(Vector2D value1, Vector2D value2)`](VRageMath.Max)||
|[`void Max(ref Vector2D value1, ref Vector2D value2, ref Vector2D result)`](VRageMath.Max)||
|[`Vector2D Clamp(Vector2D value1, Vector2D min, Vector2D max)`](VRageMath.Clamp)||
|[`void Clamp(ref Vector2D value1, ref Vector2D min, ref Vector2D max, ref Vector2D result)`](VRageMath.Clamp)||
|[`Vector2D ClampToSphere(Vector2D vector, double radius)`](VRageMath.ClampToSphere)||
|[`void ClampToSphere(ref Vector2D vector, double radius)`](VRageMath.ClampToSphere)||
|[`Vector2D Lerp(Vector2D value1, Vector2D value2, double amount)`](VRageMath.Lerp)||
|[`void Lerp(ref Vector2D value1, ref Vector2D value2, double amount, ref Vector2D result)`](VRageMath.Lerp)||
|[`Vector2D Barycentric(Vector2D value1, Vector2D value2, Vector2D value3, double amount1, double amount2)`](VRageMath.Barycentric)||
|[`void Barycentric(ref Vector2D value1, ref Vector2D value2, ref Vector2D value3, double amount1, double amount2, ref Vector2D result)`](VRageMath.Barycentric)||
|[`Vector2D SmoothStep(Vector2D value1, Vector2D value2, double amount)`](VRageMath.SmoothStep)||
|[`void SmoothStep(ref Vector2D value1, ref Vector2D value2, double amount, ref Vector2D result)`](VRageMath.SmoothStep)||
|[`Vector2D CatmullRom(Vector2D value1, Vector2D value2, Vector2D value3, Vector2D value4, double amount)`](VRageMath.CatmullRom)||
|[`void CatmullRom(ref Vector2D value1, ref Vector2D value2, ref Vector2D value3, ref Vector2D value4, double amount, ref Vector2D result)`](VRageMath.CatmullRom)||
|[`Vector2D Hermite(Vector2D value1, Vector2D tangent1, Vector2D value2, Vector2D tangent2, double amount)`](VRageMath.Hermite)||
|[`void Hermite(ref Vector2D value1, ref Vector2D tangent1, ref Vector2D value2, ref Vector2D tangent2, double amount, ref Vector2D result)`](VRageMath.Hermite)||
|[`Vector2D Transform(Vector2D position, Matrix matrix)`](VRageMath.Transform)||
|[`void Transform(ref Vector2D position, ref Matrix matrix, ref Vector2D result)`](VRageMath.Transform)||
|[`Vector2D TransformNormal(Vector2D normal, Matrix matrix)`](VRageMath.TransformNormal)||
|[`void TransformNormal(ref Vector2D normal, ref Matrix matrix, ref Vector2D result)`](VRageMath.TransformNormal)||
|[`Vector2D Transform(Vector2D value, Quaternion rotation)`](VRageMath.Transform)||
|[`void Transform(ref Vector2D value, ref Quaternion rotation, ref Vector2D result)`](VRageMath.Transform)||
|[`void Transform(Vector2D[] sourceArray, ref Matrix matrix, Vector2D[] destinationArray)`](VRageMath.Transform)||
|[`void Transform(Vector2D[] sourceArray, int sourceIndex, ref Matrix matrix, Vector2D[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)||
|[`void TransformNormal(Vector2D[] sourceArray, ref Matrix matrix, Vector2D[] destinationArray)`](VRageMath.TransformNormal)||
|[`void TransformNormal(Vector2D[] sourceArray, int sourceIndex, ref Matrix matrix, Vector2D[] destinationArray, int destinationIndex, int length)`](VRageMath.TransformNormal)||
|[`void Transform(Vector2D[] sourceArray, ref Quaternion rotation, Vector2D[] destinationArray)`](VRageMath.Transform)||
|[`void Transform(Vector2D[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector2D[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)||
|[`Vector2D Negate(Vector2D value)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|[`void Negate(ref Vector2D value, ref Vector2D result)`](VRageMath.Negate)||
|[`Vector2D Add(Vector2D value1, Vector2D value2)`](VRageMath.Add)||
|[`void Add(ref Vector2D value1, ref Vector2D value2, ref Vector2D result)`](VRageMath.Add)||
|[`Vector2D Subtract(Vector2D value1, Vector2D value2)`](VRageMath.Subtract)||
|[`void Subtract(ref Vector2D value1, ref Vector2D value2, ref Vector2D result)`](VRageMath.Subtract)||
|[`Vector2D Multiply(Vector2D value1, Vector2D value2)`](VRageMath.Multiply)||
|[`void Multiply(ref Vector2D value1, ref Vector2D value2, ref Vector2D result)`](VRageMath.Multiply)||
|[`Vector2D Multiply(Vector2D value1, double scaleFactor)`](VRageMath.Multiply)||
|[`void Multiply(ref Vector2D value1, double scaleFactor, ref Vector2D result)`](VRageMath.Multiply)||
|[`Vector2D Divide(Vector2D value1, Vector2D value2)`](VRageMath.Divide)||
|[`void Divide(ref Vector2D value1, ref Vector2D value2, ref Vector2D result)`](VRageMath.Divide)||
|[`Vector2D Divide(Vector2D value1, double divider)`](VRageMath.Divide)||
|[`void Divide(ref Vector2D value1, double divider, ref Vector2D result)`](VRageMath.Divide)||
|[`bool Between(ref Vector2D start, ref Vector2D end)`](VRageMath.Between)||
|[`Vector2D Floor(Vector2D position)`](VRageMath.Floor)||
|[`void Rotate(double angle)`](VRageMath.Rotate)||
