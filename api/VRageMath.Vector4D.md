← [Index](index.md)
# Vector4D Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with four components.
### Fields
|Member|Description|
|---|---|
|[`double X`](VRageMath.X.md)||
|[`double Y`](VRageMath.Y.md)||
|[`double Z`](VRageMath.Z.md)||
|[`double W`](VRageMath.W.md)||
|[`Vector4D Zero`](VRageMath.Zero.md)||
|[`Vector4D One`](VRageMath.One.md)||
|[`Vector4D UnitX`](VRageMath.UnitX.md)||
|[`Vector4D UnitY`](VRageMath.UnitY.md)||
|[`Vector4D UnitZ`](VRageMath.UnitZ.md)||
|[`Vector4D UnitW`](VRageMath.UnitW.md)||
### Methods
|Member|Description|
|---|---|
|[`Vector4D PackOrthoMatrix(Vector3D position, Vector3D forward, Vector3D up)`](VRageMath.PackOrthoMatrix.md)||
|[`Vector4D PackOrthoMatrix(ref MatrixD matrix)`](VRageMath.PackOrthoMatrix.md)||
|[`MatrixD UnpackOrthoMatrix(ref Vector4D packed)`](VRageMath.UnpackOrthoMatrix.md)||
|[`string ToString()`](VRageMath.ToString.md)||
|[`bool Equals(Vector4 other)`](VRageMath.Equals.md)|Determines whether the specified Object is equal to the Vector4.|
|[`bool Equals(Object obj)`](VRageMath.Equals.md)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`double Length()`](VRageMath.Length.md)||
|[`double LengthSquared()`](VRageMath.LengthSquared.md)||
|[`double Distance(Vector4 value1, Vector4 value2)`](VRageMath.Distance.md)||
|[`void Distance(ref Vector4 value1, ref Vector4 value2, ref double result)`](VRageMath.Distance.md)||
|[`double DistanceSquared(Vector4 value1, Vector4 value2)`](VRageMath.DistanceSquared.md)||
|[`void DistanceSquared(ref Vector4 value1, ref Vector4 value2, ref double result)`](VRageMath.DistanceSquared.md)||
|[`double Dot(Vector4 vector1, Vector4 vector2)`](VRageMath.Dot.md)||
|[`void Dot(ref Vector4 vector1, ref Vector4 vector2, ref double result)`](VRageMath.Dot.md)||
|[`void Normalize()`](VRageMath.Normalize.md)||
|[`Vector4D Normalize(Vector4D vector)`](VRageMath.Normalize.md)|Creates a unit vector from the specified vector.|
|[`void Normalize(ref Vector4D vector, ref Vector4D result)`](VRageMath.Normalize.md)||
|[`Vector4 Min(Vector4 value1, Vector4 value2)`](VRageMath.Min.md)||
|[`void Min(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Min.md)||
|[`Vector4 Max(Vector4 value1, Vector4 value2)`](VRageMath.Max.md)||
|[`void Max(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Max.md)||
|[`Vector4D Clamp(Vector4D value1, Vector4D min, Vector4D max)`](VRageMath.Clamp.md)||
|[`void Clamp(ref Vector4D value1, ref Vector4D min, ref Vector4D max, ref Vector4D result)`](VRageMath.Clamp.md)||
|[`Vector4D Lerp(Vector4D value1, Vector4D value2, double amount)`](VRageMath.Lerp.md)||
|[`void Lerp(ref Vector4D value1, ref Vector4D value2, double amount, ref Vector4D result)`](VRageMath.Lerp.md)||
|[`Vector4D Barycentric(Vector4D value1, Vector4D value2, Vector4D value3, double amount1, double amount2)`](VRageMath.Barycentric.md)||
|[`void Barycentric(ref Vector4D value1, ref Vector4D value2, ref Vector4D value3, double amount1, double amount2, ref Vector4D result)`](VRageMath.Barycentric.md)||
|[`Vector4D SmoothStep(Vector4D value1, Vector4D value2, double amount)`](VRageMath.SmoothStep.md)||
|[`void SmoothStep(ref Vector4D value1, ref Vector4D value2, double amount, ref Vector4D result)`](VRageMath.SmoothStep.md)||
|[`Vector4D CatmullRom(Vector4D value1, Vector4D value2, Vector4D value3, Vector4D value4, double amount)`](VRageMath.CatmullRom.md)||
|[`void CatmullRom(ref Vector4D value1, ref Vector4D value2, ref Vector4D value3, ref Vector4D value4, double amount, ref Vector4D result)`](VRageMath.CatmullRom.md)||
|[`Vector4D Hermite(Vector4D value1, Vector4D tangent1, Vector4D value2, Vector4D tangent2, double amount)`](VRageMath.Hermite.md)||
|[`void Hermite(ref Vector4D value1, ref Vector4D tangent1, ref Vector4D value2, ref Vector4D tangent2, double amount, ref Vector4D result)`](VRageMath.Hermite.md)||
|[`Vector4D Transform(Vector2 position, MatrixD matrix)`](VRageMath.Transform.md)||
|[`void Transform(ref Vector2 position, ref MatrixD matrix, ref Vector4D result)`](VRageMath.Transform.md)||
|[`Vector4D Transform(Vector3D position, MatrixD matrix)`](VRageMath.Transform.md)||
|[`void Transform(ref Vector3D position, ref MatrixD matrix, ref Vector4D result)`](VRageMath.Transform.md)||
|[`Vector4D Transform(Vector4D vector, MatrixD matrix)`](VRageMath.Transform.md)||
|[`void Transform(ref Vector4D vector, ref MatrixD matrix, ref Vector4D result)`](VRageMath.Transform.md)||
|[`Vector4D Transform(Vector2 value, Quaternion rotation)`](VRageMath.Transform.md)||
|[`void Transform(ref Vector2 value, ref Quaternion rotation, ref Vector4D result)`](VRageMath.Transform.md)||
|[`Vector4D Transform(Vector3D value, Quaternion rotation)`](VRageMath.Transform.md)||
|[`void Transform(ref Vector3D value, ref Quaternion rotation, ref Vector4D result)`](VRageMath.Transform.md)||
|[`Vector4D Transform(Vector4D value, Quaternion rotation)`](VRageMath.Transform.md)||
|[`void Transform(ref Vector4D value, ref Quaternion rotation, ref Vector4D result)`](VRageMath.Transform.md)||
|[`void Transform(Vector4D[] sourceArray, ref MatrixD matrix, Vector4D[] destinationArray)`](VRageMath.Transform.md)||
|[`void Transform(Vector4D[] sourceArray, int sourceIndex, ref MatrixD matrix, Vector4D[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform.md)||
|[`void Transform(Vector4D[] sourceArray, ref Quaternion rotation, Vector4D[] destinationArray)`](VRageMath.Transform.md)||
|[`void Transform(Vector4D[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector4D[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform.md)||
|[`Vector4D Negate(Vector4D value)`](VRageMath.Negate.md)|Returns a vector pointing in the opposite direction.|
|[`void Negate(ref Vector4D value, ref Vector4D result)`](VRageMath.Negate.md)||
|[`Vector4D Add(Vector4D value1, Vector4D value2)`](VRageMath.Add.md)||
|[`void Add(ref Vector4D value1, ref Vector4D value2, ref Vector4D result)`](VRageMath.Add.md)||
|[`Vector4 Subtract(Vector4 value1, Vector4 value2)`](VRageMath.Subtract.md)||
|[`void Subtract(ref Vector4D value1, ref Vector4D value2, ref Vector4D result)`](VRageMath.Subtract.md)||
|[`Vector4D Multiply(Vector4D value1, Vector4D value2)`](VRageMath.Multiply.md)||
|[`void Multiply(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Multiply.md)||
|[`Vector4D Multiply(Vector4D value1, double scaleFactor)`](VRageMath.Multiply.md)||
|[`void Multiply(ref Vector4D value1, double scaleFactor, ref Vector4D result)`](VRageMath.Multiply.md)||
|[`Vector4D Divide(Vector4D value1, Vector4D value2)`](VRageMath.Divide.md)||
|[`void Divide(ref Vector4D value1, ref Vector4D value2, ref Vector4D result)`](VRageMath.Divide.md)||
|[`Vector4D Divide(Vector4D value1, double divider)`](VRageMath.Divide.md)||
|[`void Divide(ref Vector4D value1, double divider, ref Vector4D result)`](VRageMath.Divide.md)||
