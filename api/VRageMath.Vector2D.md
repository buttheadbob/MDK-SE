← [Index](index.md)
#Vector2D Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
##Summary
Defines a vector with two components.
###Fields
|Member|Description|
|---|---|
|[`double X`](VRageMath.X.md)||
|[`double Y`](VRageMath.Y.md)||
|[`Vector2D Zero`](VRageMath.Zero.md)||
|[`Vector2D One`](VRageMath.One.md)||
|[`Vector2D UnitX`](VRageMath.UnitX.md)||
|[`Vector2D UnitY`](VRageMath.UnitY.md)||
|[`Vector2D PositiveInfinity`](VRageMath.PositiveInfinity.md)||
###Properties
|Member|Description|
|---|---|
|[`double Item`](VRageMath.Item.md)||
###Methods
|Member|Description|
|---|---|
|[`string ToString()`](VRageMath.ToString.md)||
|[`bool Equals(Vector2D other)`](VRageMath.Equals.md)|Determines whether the specified Object is equal to the Vector2D.|
|[`bool Equals(Object obj)`](VRageMath.Equals.md)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`bool IsValid()`](VRageMath.IsValid.md)||
|[`void AssertIsValid()`](VRageMath.AssertIsValid.md)||
|[`double Length()`](VRageMath.Length.md)||
|[`double LengthSquared()`](VRageMath.LengthSquared.md)||
|[`double Distance(Vector2D value1, Vector2D value2)`](VRageMath.Distance.md)||
|[`void Distance(ref Vector2D value1, ref Vector2D value2, ref double result)`](VRageMath.Distance.md)||
|[`double DistanceSquared(Vector2D value1, Vector2D value2)`](VRageMath.DistanceSquared.md)||
|[`void DistanceSquared(ref Vector2D value1, ref Vector2D value2, ref double result)`](VRageMath.DistanceSquared.md)||
|[`double Dot(Vector2D value1, Vector2D value2)`](VRageMath.Dot.md)||
|[`void Dot(ref Vector2D value1, ref Vector2D value2, ref double result)`](VRageMath.Dot.md)||
|[`void Normalize()`](VRageMath.Normalize.md)||
|[`Vector2D Normalize(Vector2D value)`](VRageMath.Normalize.md)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[`void Normalize(ref Vector2D value, ref Vector2D result)`](VRageMath.Normalize.md)||
|[`Vector2D Reflect(Vector2D vector, Vector2D normal)`](VRageMath.Reflect.md)||
|[`void Reflect(ref Vector2D vector, ref Vector2D normal, ref Vector2D result)`](VRageMath.Reflect.md)||
|[`Vector2D Min(Vector2D value1, Vector2D value2)`](VRageMath.Min.md)||
|[`void Min(ref Vector2D value1, ref Vector2D value2, ref Vector2D result)`](VRageMath.Min.md)||
|[`Vector2D Max(Vector2D value1, Vector2D value2)`](VRageMath.Max.md)||
|[`void Max(ref Vector2D value1, ref Vector2D value2, ref Vector2D result)`](VRageMath.Max.md)||
|[`Vector2D Clamp(Vector2D value1, Vector2D min, Vector2D max)`](VRageMath.Clamp.md)||
|[`void Clamp(ref Vector2D value1, ref Vector2D min, ref Vector2D max, ref Vector2D result)`](VRageMath.Clamp.md)||
|[`Vector2D ClampToSphere(Vector2D vector, double radius)`](VRageMath.ClampToSphere.md)||
|[`void ClampToSphere(ref Vector2D vector, double radius)`](VRageMath.ClampToSphere.md)||
|[`Vector2D Lerp(Vector2D value1, Vector2D value2, double amount)`](VRageMath.Lerp.md)||
|[`void Lerp(ref Vector2D value1, ref Vector2D value2, double amount, ref Vector2D result)`](VRageMath.Lerp.md)||
|[`Vector2D Barycentric(Vector2D value1, Vector2D value2, Vector2D value3, double amount1, double amount2)`](VRageMath.Barycentric.md)||
|[`void Barycentric(ref Vector2D value1, ref Vector2D value2, ref Vector2D value3, double amount1, double amount2, ref Vector2D result)`](VRageMath.Barycentric.md)||
|[`Vector2D SmoothStep(Vector2D value1, Vector2D value2, double amount)`](VRageMath.SmoothStep.md)||
|[`void SmoothStep(ref Vector2D value1, ref Vector2D value2, double amount, ref Vector2D result)`](VRageMath.SmoothStep.md)||
|[`Vector2D CatmullRom(Vector2D value1, Vector2D value2, Vector2D value3, Vector2D value4, double amount)`](VRageMath.CatmullRom.md)||
|[`void CatmullRom(ref Vector2D value1, ref Vector2D value2, ref Vector2D value3, ref Vector2D value4, double amount, ref Vector2D result)`](VRageMath.CatmullRom.md)||
|[`Vector2D Hermite(Vector2D value1, Vector2D tangent1, Vector2D value2, Vector2D tangent2, double amount)`](VRageMath.Hermite.md)||
|[`void Hermite(ref Vector2D value1, ref Vector2D tangent1, ref Vector2D value2, ref Vector2D tangent2, double amount, ref Vector2D result)`](VRageMath.Hermite.md)||
|[`Vector2D Transform(Vector2D position, Matrix matrix)`](VRageMath.Transform.md)||
|[`void Transform(ref Vector2D position, ref Matrix matrix, ref Vector2D result)`](VRageMath.Transform.md)||
|[`Vector2D TransformNormal(Vector2D normal, Matrix matrix)`](VRageMath.TransformNormal.md)||
|[`void TransformNormal(ref Vector2D normal, ref Matrix matrix, ref Vector2D result)`](VRageMath.TransformNormal.md)||
|[`Vector2D Transform(Vector2D value, Quaternion rotation)`](VRageMath.Transform.md)||
|[`void Transform(ref Vector2D value, ref Quaternion rotation, ref Vector2D result)`](VRageMath.Transform.md)||
|[`void Transform(Vector2D[] sourceArray, ref Matrix matrix, Vector2D[] destinationArray)`](VRageMath.Transform.md)||
|[`void Transform(Vector2D[] sourceArray, int sourceIndex, ref Matrix matrix, Vector2D[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform.md)||
|[`void TransformNormal(Vector2D[] sourceArray, ref Matrix matrix, Vector2D[] destinationArray)`](VRageMath.TransformNormal.md)||
|[`void TransformNormal(Vector2D[] sourceArray, int sourceIndex, ref Matrix matrix, Vector2D[] destinationArray, int destinationIndex, int length)`](VRageMath.TransformNormal.md)||
|[`void Transform(Vector2D[] sourceArray, ref Quaternion rotation, Vector2D[] destinationArray)`](VRageMath.Transform.md)||
|[`void Transform(Vector2D[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector2D[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform.md)||
|[`Vector2D Negate(Vector2D value)`](VRageMath.Negate.md)|Returns a vector pointing in the opposite direction.|
|[`void Negate(ref Vector2D value, ref Vector2D result)`](VRageMath.Negate.md)||
|[`Vector2D Add(Vector2D value1, Vector2D value2)`](VRageMath.Add.md)||
|[`void Add(ref Vector2D value1, ref Vector2D value2, ref Vector2D result)`](VRageMath.Add.md)||
|[`Vector2D Subtract(Vector2D value1, Vector2D value2)`](VRageMath.Subtract.md)||
|[`void Subtract(ref Vector2D value1, ref Vector2D value2, ref Vector2D result)`](VRageMath.Subtract.md)||
|[`Vector2D Multiply(Vector2D value1, Vector2D value2)`](VRageMath.Multiply.md)||
|[`void Multiply(ref Vector2D value1, ref Vector2D value2, ref Vector2D result)`](VRageMath.Multiply.md)||
|[`Vector2D Multiply(Vector2D value1, double scaleFactor)`](VRageMath.Multiply.md)||
|[`void Multiply(ref Vector2D value1, double scaleFactor, ref Vector2D result)`](VRageMath.Multiply.md)||
|[`Vector2D Divide(Vector2D value1, Vector2D value2)`](VRageMath.Divide.md)||
|[`void Divide(ref Vector2D value1, ref Vector2D value2, ref Vector2D result)`](VRageMath.Divide.md)||
|[`Vector2D Divide(Vector2D value1, double divider)`](VRageMath.Divide.md)||
|[`void Divide(ref Vector2D value1, double divider, ref Vector2D result)`](VRageMath.Divide.md)||
|[`bool Between(ref Vector2D start, ref Vector2D end)`](VRageMath.Between.md)||
|[`Vector2D Floor(Vector2D position)`](VRageMath.Floor.md)||
|[`void Rotate(double angle)`](VRageMath.Rotate.md)||
