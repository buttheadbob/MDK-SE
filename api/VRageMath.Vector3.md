← [Index](index.md)
# Vector3 Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with three components.
### Fields
|Member|Description|
|---|---|
|[`float X`](VRageMath.X.md)||
|[`float Y`](VRageMath.Y.md)||
|[`float Z`](VRageMath.Z.md)||
|[`Vector3 Zero`](VRageMath.Zero.md)||
|[`Vector3 One`](VRageMath.One.md)||
|[`Vector3 MinusOne`](VRageMath.MinusOne.md)||
|[`Vector3 Half`](VRageMath.Half.md)||
|[`Vector3 PositiveInfinity`](VRageMath.PositiveInfinity.md)||
|[`Vector3 NegativeInfinity`](VRageMath.NegativeInfinity.md)||
|[`Vector3 UnitX`](VRageMath.UnitX.md)||
|[`Vector3 UnitY`](VRageMath.UnitY.md)||
|[`Vector3 UnitZ`](VRageMath.UnitZ.md)||
|[`Vector3 Up`](VRageMath.Up.md)||
|[`Vector3 Down`](VRageMath.Down.md)||
|[`Vector3 Right`](VRageMath.Right.md)||
|[`Vector3 Left`](VRageMath.Left.md)||
|[`Vector3 Forward`](VRageMath.Forward.md)||
|[`Vector3 Backward`](VRageMath.Backward.md)||
|[`Vector3 MaxValue`](VRageMath.MaxValue.md)||
|[`Vector3 MinValue`](VRageMath.MinValue.md)||
|[`Vector3 Invalid`](VRageMath.Invalid.md)||
### Properties
|Member|Description|
|---|---|
|[`float Sum`](VRageMath.Sum.md)||
|[`float Volume`](VRageMath.Volume.md)||
### Methods
|Member|Description|
|---|---|
|[`void Negate(ref Vector3 value, ref Vector3 result)`](VRageMath.Negate.md)||
|[`Vector3 Add(Vector3 value1, Vector3 value2)`](VRageMath.Add.md)||
|[`void Add(ref Vector3 value1, ref Vector3 value2, ref Vector3 result)`](VRageMath.Add.md)||
|[`Vector3 Subtract(Vector3 value1, Vector3 value2)`](VRageMath.Subtract.md)||
|[`void Subtract(ref Vector3 value1, ref Vector3 value2, ref Vector3 result)`](VRageMath.Subtract.md)||
|[`Vector3 Multiply(Vector3 value1, Vector3 value2)`](VRageMath.Multiply.md)||
|[`void Multiply(ref Vector3 value1, ref Vector3 value2, ref Vector3 result)`](VRageMath.Multiply.md)||
|[`Vector3 Multiply(Vector3 value1, float scaleFactor)`](VRageMath.Multiply.md)||
|[`void Multiply(ref Vector3 value1, float scaleFactor, ref Vector3 result)`](VRageMath.Multiply.md)||
|[`Vector3 Divide(Vector3 value1, Vector3 value2)`](VRageMath.Divide.md)||
|[`void Divide(ref Vector3 value1, ref Vector3 value2, ref Vector3 result)`](VRageMath.Divide.md)||
|[`Vector3 Divide(Vector3 value1, float value2)`](VRageMath.Divide.md)||
|[`void Divide(ref Vector3 value1, float value2, ref Vector3 result)`](VRageMath.Divide.md)||
|[`Vector3 CalculatePerpendicularVector(Vector3 v)`](VRageMath.CalculatePerpendicularVector.md)||
|[`void CalculatePerpendicularVector(ref Vector3 result)`](VRageMath.CalculatePerpendicularVector.md)||
|[`void GetAzimuthAndElevation(Vector3 v, ref float azimuth, ref float elevation)`](VRageMath.GetAzimuthAndElevation.md)||
|[`void CreateFromAzimuthAndElevation(float azimuth, float elevation, ref Vector3 direction)`](VRageMath.CreateFromAzimuthAndElevation.md)||
|[`long VolumeInt(float multiplier)`](VRageMath.VolumeInt.md)||
|[`bool IsInsideInclusive(ref Vector3 min, ref Vector3 max)`](VRageMath.IsInsideInclusive.md)||
|[`Vector3 SwapYZCoordinates(Vector3 v)`](VRageMath.SwapYZCoordinates.md)||
|[`float GetDim(int i)`](VRageMath.GetDim.md)||
|[`void SetDim(int i, float value)`](VRageMath.SetDim.md)||
|[`Vector3 Ceiling(Vector3 v)`](VRageMath.Ceiling.md)||
|[`Vector3 Floor(Vector3 v)`](VRageMath.Floor.md)||
|[`Vector3 Round(Vector3 v)`](VRageMath.Round.md)||
|[`Vector3 Round(Vector3 v, int numDecimals)`](VRageMath.Round.md)||
|[`Vector3 ProjectOnPlane(ref Vector3 vec, ref Vector3 planeNormal)`](VRageMath.ProjectOnPlane.md)||
|[`Vector3 ProjectOnVector(ref Vector3 vec, ref Vector3 guideVector)`](VRageMath.ProjectOnVector.md)||
|[`bool IsZero(ref Vector3 vec)`](VRageMath.IsZero.md)||
|[`void Divide(float divider)`](VRageMath.Divide.md)||
|[`void Multiply(float scale)`](VRageMath.Multiply.md)||
|[`void Add(Vector3 other)`](VRageMath.Add.md)||
|[`Vector3 Abs(Vector3 value)`](VRageMath.Abs.md)||
|[`Vector3 Sign(Vector3 value)`](VRageMath.Sign.md)||
|[`Vector3 Sign(Vector3 value, float epsilon)`](VRageMath.Sign.md)||
|[`Vector3 SignNonZero(Vector3 value)`](VRageMath.SignNonZero.md)|Returns per component sign, never returns zero. For zero component returns sign 1. Faster than Sign.|
|[`void Interpolate3(Vector3 v0, Vector3 v1, float rt)`](VRageMath.Interpolate3.md)||
|[`bool IsValid()`](VRageMath.IsValid.md)||
|[`void AssertIsValid()`](VRageMath.AssertIsValid.md)||
|[`bool IsUnit(ref Vector3 value)`](VRageMath.IsUnit.md)||
|[`bool ArePerpendicular(ref Vector3 a, ref Vector3 b)`](VRageMath.ArePerpendicular.md)||
|[`bool IsZero(Vector3 value)`](VRageMath.IsZero.md)||
|[`bool IsZero(Vector3 value, float epsilon)`](VRageMath.IsZero.md)||
|[`Vector3 IsZeroVector(Vector3 value)`](VRageMath.IsZeroVector.md)||
|[`Vector3 IsZeroVector(Vector3 value, float epsilon)`](VRageMath.IsZeroVector.md)||
|[`Vector3 Step(Vector3 value)`](VRageMath.Step.md)||
|[`string ToString()`](VRageMath.ToString.md)||
|[`string ToString(string format)`](VRageMath.ToString.md)||
|[`bool Equals(Vector3 other)`](VRageMath.Equals.md)|Determines whether the specified Object is equal to the Vector3.|
|[`bool Equals(Vector3 other, float epsilon)`](VRageMath.Equals.md)||
|[`bool Equals(Object obj)`](VRageMath.Equals.md)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`long GetHash()`](VRageMath.GetHash.md)||
|[`float Length()`](VRageMath.Length.md)||
|[`float LengthSquared()`](VRageMath.LengthSquared.md)||
|[`float Distance(Vector3 value1, Vector3 value2)`](VRageMath.Distance.md)||
|[`void Distance(ref Vector3 value1, ref Vector3 value2, ref float result)`](VRageMath.Distance.md)||
|[`float DistanceSquared(Vector3 value1, Vector3 value2)`](VRageMath.DistanceSquared.md)||
|[`void DistanceSquared(ref Vector3 value1, ref Vector3 value2, ref float result)`](VRageMath.DistanceSquared.md)||
|[`float RectangularDistance(Vector3 value1, Vector3 value2)`](VRageMath.RectangularDistance.md)||
|[`float RectangularDistance(ref Vector3 value1, ref Vector3 value2)`](VRageMath.RectangularDistance.md)||
|[`float Dot(Vector3 vector1, Vector3 vector2)`](VRageMath.Dot.md)||
|[`void Dot(ref Vector3 vector1, ref Vector3 vector2, ref float result)`](VRageMath.Dot.md)||
|[`float Dot(Vector3 v)`](VRageMath.Dot.md)||
|[`float Dot(ref Vector3 v)`](VRageMath.Dot.md)||
|[`Vector3 Cross(Vector3 v)`](VRageMath.Cross.md)||
|[`float Normalize()`](VRageMath.Normalize.md)||
|[`Vector3 Normalize(Vector3 value)`](VRageMath.Normalize.md)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[`Vector3 Normalize(Vector3D value)`](VRageMath.Normalize.md)||
|[`bool GetNormalized(ref Vector3 value)`](VRageMath.GetNormalized.md)||
|[`void Normalize(ref Vector3 value, ref Vector3 result)`](VRageMath.Normalize.md)||
|[`Vector3 Cross(Vector3 vector1, Vector3 vector2)`](VRageMath.Cross.md)||
|[`void Cross(ref Vector3 vector1, ref Vector3 vector2, ref Vector3 result)`](VRageMath.Cross.md)||
|[`Vector3 Reflect(Vector3 vector, Vector3 normal)`](VRageMath.Reflect.md)||
|[`void Reflect(ref Vector3 vector, ref Vector3 normal, ref Vector3 result)`](VRageMath.Reflect.md)||
|[`Vector3 Reject(Vector3 vector, Vector3 direction)`](VRageMath.Reject.md)||
|[`void Reject(ref Vector3 vector, ref Vector3 direction, ref Vector3 result)`](VRageMath.Reject.md)||
|[`float Min()`](VRageMath.Min.md)||
|[`float AbsMin()`](VRageMath.AbsMin.md)||
|[`float Max()`](VRageMath.Max.md)||
|[`Vector3 MaxAbsComponent()`](VRageMath.MaxAbsComponent.md)||
|[`float AbsMax()`](VRageMath.AbsMax.md)||
|[`Vector3 Min(Vector3 value1, Vector3 value2)`](VRageMath.Min.md)||
|[`void Min(ref Vector3 value1, ref Vector3 value2, ref Vector3 result)`](VRageMath.Min.md)||
|[`Vector3 Max(Vector3 value1, Vector3 value2)`](VRageMath.Max.md)||
|[`void Max(ref Vector3 value1, ref Vector3 value2, ref Vector3 result)`](VRageMath.Max.md)||
|[`void MinMax(ref Vector3 min, ref Vector3 max)`](VRageMath.MinMax.md)||
|[`Vector3 DominantAxisProjection(Vector3 value1)`](VRageMath.DominantAxisProjection.md)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|[`void DominantAxisProjection(ref Vector3 value1, ref Vector3 result)`](VRageMath.DominantAxisProjection.md)||
|[`Vector3 Clamp(Vector3 value1, Vector3 min, Vector3 max)`](VRageMath.Clamp.md)||
|[`void Clamp(ref Vector3 value1, ref Vector3 min, ref Vector3 max, ref Vector3 result)`](VRageMath.Clamp.md)||
|[`Vector3 ClampToSphere(Vector3 vector, float radius)`](VRageMath.ClampToSphere.md)||
|[`void ClampToSphere(ref Vector3 vector, float radius)`](VRageMath.ClampToSphere.md)||
|[`Vector3 Lerp(Vector3 value1, Vector3 value2, float amount)`](VRageMath.Lerp.md)||
|[`void Lerp(ref Vector3 value1, ref Vector3 value2, float amount, ref Vector3 result)`](VRageMath.Lerp.md)||
|[`Vector3 Barycentric(Vector3 value1, Vector3 value2, Vector3 value3, float amount1, float amount2)`](VRageMath.Barycentric.md)||
|[`void Barycentric(ref Vector3 value1, ref Vector3 value2, ref Vector3 value3, float amount1, float amount2, ref Vector3 result)`](VRageMath.Barycentric.md)||
|[`void Barycentric(Vector3 p, Vector3 a, Vector3 b, Vector3 c, ref float u, ref float v, ref float w)`](VRageMath.Barycentric.md)||
|[`float TriangleArea(Vector3 v1, Vector3 v2, Vector3 v3)`](VRageMath.TriangleArea.md)||
|[`float TriangleArea(ref Vector3 v1, ref Vector3 v2, ref Vector3 v3)`](VRageMath.TriangleArea.md)||
|[`Vector3 SmoothStep(Vector3 value1, Vector3 value2, float amount)`](VRageMath.SmoothStep.md)||
|[`void SmoothStep(ref Vector3 value1, ref Vector3 value2, float amount, ref Vector3 result)`](VRageMath.SmoothStep.md)||
|[`Vector3 CatmullRom(Vector3 value1, Vector3 value2, Vector3 value3, Vector3 value4, float amount)`](VRageMath.CatmullRom.md)||
|[`void CatmullRom(ref Vector3 value1, ref Vector3 value2, ref Vector3 value3, ref Vector3 value4, float amount, ref Vector3 result)`](VRageMath.CatmullRom.md)||
|[`Vector3 Hermite(Vector3 value1, Vector3 tangent1, Vector3 value2, Vector3 tangent2, float amount)`](VRageMath.Hermite.md)||
|[`void Hermite(ref Vector3 value1, ref Vector3 tangent1, ref Vector3 value2, ref Vector3 tangent2, float amount, ref Vector3 result)`](VRageMath.Hermite.md)||
|[`Vector3 Transform(Vector3 position, Matrix matrix)`](VRageMath.Transform.md)||
|[`Vector3D Transform(Vector3 position, MatrixD matrix)`](VRageMath.Transform.md)||
|[`Vector3 Transform(Vector3 position, ref Matrix matrix)`](VRageMath.Transform.md)||
|[`void Transform(ref Vector3 position, ref Matrix matrix, ref Vector3 result)`](VRageMath.Transform.md)||
|[`void Transform(ref Vector3 position, ref MatrixI matrix, ref Vector3 result)`](VRageMath.Transform.md)||
|[`void TransformProjection(ref Vector3 position, ref Matrix matrix, ref Vector3 result)`](VRageMath.TransformProjection.md)||
|[`void TransformNoProjection(ref Vector3 vector, ref Matrix matrix, ref Vector3 result)`](VRageMath.TransformNoProjection.md)||
|[`void RotateAndScale(ref Vector3 vector, ref Matrix matrix, ref Vector3 result)`](VRageMath.RotateAndScale.md)||
|[`Vector3 RotateAndScale(Vector3 vector, Matrix matrix)`](VRageMath.RotateAndScale.md)||
|[`Vector3 TransformNormal(Vector3 normal, Matrix matrix)`](VRageMath.TransformNormal.md)||
|[`Vector3 TransformNormal(Vector3 normal, MatrixD matrix)`](VRageMath.TransformNormal.md)||
|[`Vector3 TransformNormal(Vector3D normal, Matrix matrix)`](VRageMath.TransformNormal.md)||
|[`void TransformNormal(ref Vector3 normal, ref Matrix matrix, ref Vector3 result)`](VRageMath.TransformNormal.md)||
|[`void TransformNormal(ref Vector3 normal, ref MatrixD matrix, ref Vector3 result)`](VRageMath.TransformNormal.md)||
|[`void TransformNormal(ref Vector3 normal, ref MatrixI matrix, ref Vector3 result)`](VRageMath.TransformNormal.md)||
|[`Vector3 TransformNormal(Vector3 normal, MyBlockOrientation orientation)`](VRageMath.TransformNormal.md)||
|[`void TransformNormal(ref Vector3 normal, MyBlockOrientation orientation, ref Vector3 result)`](VRageMath.TransformNormal.md)||
|[`Vector3 TransformNormal(Vector3 normal, ref Matrix matrix)`](VRageMath.TransformNormal.md)||
|[`Vector3 Transform(Vector3 value, Quaternion rotation)`](VRageMath.Transform.md)||
|[`void Transform(ref Vector3 value, ref Quaternion rotation, ref Vector3 result)`](VRageMath.Transform.md)||
|[`void Transform(Vector3[] sourceArray, ref Matrix matrix, Vector3[] destinationArray)`](VRageMath.Transform.md)||
|[`void Transform(Vector3[] sourceArray, int sourceIndex, ref Matrix matrix, Vector3[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform.md)||
|[`void TransformNormal(Vector3[] sourceArray, ref Matrix matrix, Vector3[] destinationArray)`](VRageMath.TransformNormal.md)||
|[`void TransformNormal(Vector3[] sourceArray, int sourceIndex, ref Matrix matrix, Vector3[] destinationArray, int destinationIndex, int length)`](VRageMath.TransformNormal.md)||
|[`void Transform(Vector3[] sourceArray, ref Quaternion rotation, Vector3[] destinationArray)`](VRageMath.Transform.md)||
|[`void Transform(Vector3[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector3[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform.md)||
|[`Vector3 Negate(Vector3 value)`](VRageMath.Negate.md)|Returns a vector pointing in the opposite direction.|
