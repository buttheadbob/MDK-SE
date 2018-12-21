← [Index](index)
# Vector4D Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with four components.
### Fields
|Member|Description|
|---|---|
|[`double X`](VRageMath.X)||
|[`double Y`](VRageMath.Y)||
|[`double Z`](VRageMath.Z)||
|[`double W`](VRageMath.W)||
|[`Vector4D Zero`](VRageMath.Zero)||
|[`Vector4D One`](VRageMath.One)||
|[`Vector4D UnitX`](VRageMath.UnitX)||
|[`Vector4D UnitY`](VRageMath.UnitY)||
|[`Vector4D UnitZ`](VRageMath.UnitZ)||
|[`Vector4D UnitW`](VRageMath.UnitW)||
### Methods
|Member|Description|
|---|---|
|[`Vector4D PackOrthoMatrix(Vector3D position, Vector3D forward, Vector3D up)`](VRageMath.PackOrthoMatrix)||
|[`Vector4D PackOrthoMatrix(ref MatrixD matrix)`](VRageMath.PackOrthoMatrix)||
|[`MatrixD UnpackOrthoMatrix(ref Vector4D packed)`](VRageMath.UnpackOrthoMatrix)||
|[`string ToString()`](VRageMath.ToString)||
|[`bool Equals(Vector4 other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector4.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`double Length()`](VRageMath.Length)||
|[`double LengthSquared()`](VRageMath.LengthSquared)||
|[`double Distance(Vector4 value1, Vector4 value2)`](VRageMath.Distance)||
|[`void Distance(ref Vector4 value1, ref Vector4 value2, ref double result)`](VRageMath.Distance)||
|[`double DistanceSquared(Vector4 value1, Vector4 value2)`](VRageMath.DistanceSquared)||
|[`void DistanceSquared(ref Vector4 value1, ref Vector4 value2, ref double result)`](VRageMath.DistanceSquared)||
|[`double Dot(Vector4 vector1, Vector4 vector2)`](VRageMath.Dot)||
|[`void Dot(ref Vector4 vector1, ref Vector4 vector2, ref double result)`](VRageMath.Dot)||
|[`void Normalize()`](VRageMath.Normalize)||
|[`Vector4D Normalize(Vector4D vector)`](VRageMath.Normalize)|Creates a unit vector from the specified vector.|
|[`void Normalize(ref Vector4D vector, ref Vector4D result)`](VRageMath.Normalize)||
|[`Vector4 Min(Vector4 value1, Vector4 value2)`](VRageMath.Min)||
|[`void Min(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Min)||
|[`Vector4 Max(Vector4 value1, Vector4 value2)`](VRageMath.Max)||
|[`void Max(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Max)||
|[`Vector4D Clamp(Vector4D value1, Vector4D min, Vector4D max)`](VRageMath.Clamp)||
|[`void Clamp(ref Vector4D value1, ref Vector4D min, ref Vector4D max, ref Vector4D result)`](VRageMath.Clamp)||
|[`Vector4D Lerp(Vector4D value1, Vector4D value2, double amount)`](VRageMath.Lerp)||
|[`void Lerp(ref Vector4D value1, ref Vector4D value2, double amount, ref Vector4D result)`](VRageMath.Lerp)||
|[`Vector4D Barycentric(Vector4D value1, Vector4D value2, Vector4D value3, double amount1, double amount2)`](VRageMath.Barycentric)||
|[`void Barycentric(ref Vector4D value1, ref Vector4D value2, ref Vector4D value3, double amount1, double amount2, ref Vector4D result)`](VRageMath.Barycentric)||
|[`Vector4D SmoothStep(Vector4D value1, Vector4D value2, double amount)`](VRageMath.SmoothStep)||
|[`void SmoothStep(ref Vector4D value1, ref Vector4D value2, double amount, ref Vector4D result)`](VRageMath.SmoothStep)||
|[`Vector4D CatmullRom(Vector4D value1, Vector4D value2, Vector4D value3, Vector4D value4, double amount)`](VRageMath.CatmullRom)||
|[`void CatmullRom(ref Vector4D value1, ref Vector4D value2, ref Vector4D value3, ref Vector4D value4, double amount, ref Vector4D result)`](VRageMath.CatmullRom)||
|[`Vector4D Hermite(Vector4D value1, Vector4D tangent1, Vector4D value2, Vector4D tangent2, double amount)`](VRageMath.Hermite)||
|[`void Hermite(ref Vector4D value1, ref Vector4D tangent1, ref Vector4D value2, ref Vector4D tangent2, double amount, ref Vector4D result)`](VRageMath.Hermite)||
|[`Vector4D Transform(Vector2 position, MatrixD matrix)`](VRageMath.Transform)||
|[`void Transform(ref Vector2 position, ref MatrixD matrix, ref Vector4D result)`](VRageMath.Transform)||
|[`Vector4D Transform(Vector3D position, MatrixD matrix)`](VRageMath.Transform)||
|[`void Transform(ref Vector3D position, ref MatrixD matrix, ref Vector4D result)`](VRageMath.Transform)||
|[`Vector4D Transform(Vector4D vector, MatrixD matrix)`](VRageMath.Transform)||
|[`void Transform(ref Vector4D vector, ref MatrixD matrix, ref Vector4D result)`](VRageMath.Transform)||
|[`Vector4D Transform(Vector2 value, Quaternion rotation)`](VRageMath.Transform)||
|[`void Transform(ref Vector2 value, ref Quaternion rotation, ref Vector4D result)`](VRageMath.Transform)||
|[`Vector4D Transform(Vector3D value, Quaternion rotation)`](VRageMath.Transform)||
|[`void Transform(ref Vector3D value, ref Quaternion rotation, ref Vector4D result)`](VRageMath.Transform)||
|[`Vector4D Transform(Vector4D value, Quaternion rotation)`](VRageMath.Transform)||
|[`void Transform(ref Vector4D value, ref Quaternion rotation, ref Vector4D result)`](VRageMath.Transform)||
|[`void Transform(Vector4D[] sourceArray, ref MatrixD matrix, Vector4D[] destinationArray)`](VRageMath.Transform)||
|[`void Transform(Vector4D[] sourceArray, int sourceIndex, ref MatrixD matrix, Vector4D[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)||
|[`void Transform(Vector4D[] sourceArray, ref Quaternion rotation, Vector4D[] destinationArray)`](VRageMath.Transform)||
|[`void Transform(Vector4D[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector4D[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)||
|[`Vector4D Negate(Vector4D value)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|[`void Negate(ref Vector4D value, ref Vector4D result)`](VRageMath.Negate)||
|[`Vector4D Add(Vector4D value1, Vector4D value2)`](VRageMath.Add)||
|[`void Add(ref Vector4D value1, ref Vector4D value2, ref Vector4D result)`](VRageMath.Add)||
|[`Vector4 Subtract(Vector4 value1, Vector4 value2)`](VRageMath.Subtract)||
|[`void Subtract(ref Vector4D value1, ref Vector4D value2, ref Vector4D result)`](VRageMath.Subtract)||
|[`Vector4D Multiply(Vector4D value1, Vector4D value2)`](VRageMath.Multiply)||
|[`void Multiply(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Multiply)||
|[`Vector4D Multiply(Vector4D value1, double scaleFactor)`](VRageMath.Multiply)||
|[`void Multiply(ref Vector4D value1, double scaleFactor, ref Vector4D result)`](VRageMath.Multiply)||
|[`Vector4D Divide(Vector4D value1, Vector4D value2)`](VRageMath.Divide)||
|[`void Divide(ref Vector4D value1, ref Vector4D value2, ref Vector4D result)`](VRageMath.Divide)||
|[`Vector4D Divide(Vector4D value1, double divider)`](VRageMath.Divide)||
|[`void Divide(ref Vector4D value1, double divider, ref Vector4D result)`](VRageMath.Divide)||
