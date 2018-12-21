← [Index](index)
# Vector3 Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with three components.
### Fields
|Member|Description|
|---|---|
|[`float X`](VRageMath.X)||
|[`float Y`](VRageMath.Y)||
|[`float Z`](VRageMath.Z)||
|[`Vector3 Zero`](VRageMath.Zero)||
|[`Vector3 One`](VRageMath.One)||
|[`Vector3 MinusOne`](VRageMath.MinusOne)||
|[`Vector3 Half`](VRageMath.Half)||
|[`Vector3 PositiveInfinity`](VRageMath.PositiveInfinity)||
|[`Vector3 NegativeInfinity`](VRageMath.NegativeInfinity)||
|[`Vector3 UnitX`](VRageMath.UnitX)||
|[`Vector3 UnitY`](VRageMath.UnitY)||
|[`Vector3 UnitZ`](VRageMath.UnitZ)||
|[`Vector3 Up`](VRageMath.Up)||
|[`Vector3 Down`](VRageMath.Down)||
|[`Vector3 Right`](VRageMath.Right)||
|[`Vector3 Left`](VRageMath.Left)||
|[`Vector3 Forward`](VRageMath.Forward)||
|[`Vector3 Backward`](VRageMath.Backward)||
|[`Vector3 MaxValue`](VRageMath.MaxValue)||
|[`Vector3 MinValue`](VRageMath.MinValue)||
|[`Vector3 Invalid`](VRageMath.Invalid)||
### Properties
|Member|Description|
|---|---|
|[`float Sum`](VRageMath.Sum)||
|[`float Volume`](VRageMath.Volume)||
### Methods
|Member|Description|
|---|---|
|[`void Negate(ref Vector3 value, ref Vector3 result)`](VRageMath.Negate)||
|[`Vector3 Add(Vector3 value1, Vector3 value2)`](VRageMath.Add)||
|[`void Add(ref Vector3 value1, ref Vector3 value2, ref Vector3 result)`](VRageMath.Add)||
|[`Vector3 Subtract(Vector3 value1, Vector3 value2)`](VRageMath.Subtract)||
|[`void Subtract(ref Vector3 value1, ref Vector3 value2, ref Vector3 result)`](VRageMath.Subtract)||
|[`Vector3 Multiply(Vector3 value1, Vector3 value2)`](VRageMath.Multiply)||
|[`void Multiply(ref Vector3 value1, ref Vector3 value2, ref Vector3 result)`](VRageMath.Multiply)||
|[`Vector3 Multiply(Vector3 value1, float scaleFactor)`](VRageMath.Multiply)||
|[`void Multiply(ref Vector3 value1, float scaleFactor, ref Vector3 result)`](VRageMath.Multiply)||
|[`Vector3 Divide(Vector3 value1, Vector3 value2)`](VRageMath.Divide)||
|[`void Divide(ref Vector3 value1, ref Vector3 value2, ref Vector3 result)`](VRageMath.Divide)||
|[`Vector3 Divide(Vector3 value1, float value2)`](VRageMath.Divide)||
|[`void Divide(ref Vector3 value1, float value2, ref Vector3 result)`](VRageMath.Divide)||
|[`Vector3 CalculatePerpendicularVector(Vector3 v)`](VRageMath.CalculatePerpendicularVector)||
|[`void CalculatePerpendicularVector(ref Vector3 result)`](VRageMath.CalculatePerpendicularVector)||
|[`void GetAzimuthAndElevation(Vector3 v, ref float azimuth, ref float elevation)`](VRageMath.GetAzimuthAndElevation)||
|[`void CreateFromAzimuthAndElevation(float azimuth, float elevation, ref Vector3 direction)`](VRageMath.CreateFromAzimuthAndElevation)||
|[`long VolumeInt(float multiplier)`](VRageMath.VolumeInt)||
|[`bool IsInsideInclusive(ref Vector3 min, ref Vector3 max)`](VRageMath.IsInsideInclusive)||
|[`Vector3 SwapYZCoordinates(Vector3 v)`](VRageMath.SwapYZCoordinates)||
|[`float GetDim(int i)`](VRageMath.GetDim)||
|[`void SetDim(int i, float value)`](VRageMath.SetDim)||
|[`Vector3 Ceiling(Vector3 v)`](VRageMath.Ceiling)||
|[`Vector3 Floor(Vector3 v)`](VRageMath.Floor)||
|[`Vector3 Round(Vector3 v)`](VRageMath.Round)||
|[`Vector3 Round(Vector3 v, int numDecimals)`](VRageMath.Round)||
|[`Vector3 ProjectOnPlane(ref Vector3 vec, ref Vector3 planeNormal)`](VRageMath.ProjectOnPlane)||
|[`Vector3 ProjectOnVector(ref Vector3 vec, ref Vector3 guideVector)`](VRageMath.ProjectOnVector)||
|[`bool IsZero(ref Vector3 vec)`](VRageMath.IsZero)||
|[`void Divide(float divider)`](VRageMath.Divide)||
|[`void Multiply(float scale)`](VRageMath.Multiply)||
|[`void Add(Vector3 other)`](VRageMath.Add)||
|[`Vector3 Abs(Vector3 value)`](VRageMath.Abs)||
|[`Vector3 Sign(Vector3 value)`](VRageMath.Sign)||
|[`Vector3 Sign(Vector3 value, float epsilon)`](VRageMath.Sign)||
|[`Vector3 SignNonZero(Vector3 value)`](VRageMath.SignNonZero)|Returns per component sign, never returns zero. For zero component returns sign 1. Faster than Sign.|
|[`void Interpolate3(Vector3 v0, Vector3 v1, float rt)`](VRageMath.Interpolate3)||
|[`bool IsValid()`](VRageMath.IsValid)||
|[`void AssertIsValid()`](VRageMath.AssertIsValid)||
|[`bool IsUnit(ref Vector3 value)`](VRageMath.IsUnit)||
|[`bool ArePerpendicular(ref Vector3 a, ref Vector3 b)`](VRageMath.ArePerpendicular)||
|[`bool IsZero(Vector3 value)`](VRageMath.IsZero)||
|[`bool IsZero(Vector3 value, float epsilon)`](VRageMath.IsZero)||
|[`Vector3 IsZeroVector(Vector3 value)`](VRageMath.IsZeroVector)||
|[`Vector3 IsZeroVector(Vector3 value, float epsilon)`](VRageMath.IsZeroVector)||
|[`Vector3 Step(Vector3 value)`](VRageMath.Step)||
|[`string ToString()`](VRageMath.ToString)||
|[`string ToString(string format)`](VRageMath.ToString)||
|[`bool Equals(Vector3 other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector3.|
|[`bool Equals(Vector3 other, float epsilon)`](VRageMath.Equals)||
|[`bool Equals(Object obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`long GetHash()`](VRageMath.GetHash)||
|[`float Length()`](VRageMath.Length)||
|[`float LengthSquared()`](VRageMath.LengthSquared)||
|[`float Distance(Vector3 value1, Vector3 value2)`](VRageMath.Distance)||
|[`void Distance(ref Vector3 value1, ref Vector3 value2, ref float result)`](VRageMath.Distance)||
|[`float DistanceSquared(Vector3 value1, Vector3 value2)`](VRageMath.DistanceSquared)||
|[`void DistanceSquared(ref Vector3 value1, ref Vector3 value2, ref float result)`](VRageMath.DistanceSquared)||
|[`float RectangularDistance(Vector3 value1, Vector3 value2)`](VRageMath.RectangularDistance)||
|[`float RectangularDistance(ref Vector3 value1, ref Vector3 value2)`](VRageMath.RectangularDistance)||
|[`float Dot(Vector3 vector1, Vector3 vector2)`](VRageMath.Dot)||
|[`void Dot(ref Vector3 vector1, ref Vector3 vector2, ref float result)`](VRageMath.Dot)||
|[`float Dot(Vector3 v)`](VRageMath.Dot)||
|[`float Dot(ref Vector3 v)`](VRageMath.Dot)||
|[`Vector3 Cross(Vector3 v)`](VRageMath.Cross)||
|[`float Normalize()`](VRageMath.Normalize)||
|[`Vector3 Normalize(Vector3 value)`](VRageMath.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[`Vector3 Normalize(Vector3D value)`](VRageMath.Normalize)||
|[`bool GetNormalized(ref Vector3 value)`](VRageMath.GetNormalized)||
|[`void Normalize(ref Vector3 value, ref Vector3 result)`](VRageMath.Normalize)||
|[`Vector3 Cross(Vector3 vector1, Vector3 vector2)`](VRageMath.Cross)||
|[`void Cross(ref Vector3 vector1, ref Vector3 vector2, ref Vector3 result)`](VRageMath.Cross)||
|[`Vector3 Reflect(Vector3 vector, Vector3 normal)`](VRageMath.Reflect)||
|[`void Reflect(ref Vector3 vector, ref Vector3 normal, ref Vector3 result)`](VRageMath.Reflect)||
|[`Vector3 Reject(Vector3 vector, Vector3 direction)`](VRageMath.Reject)||
|[`void Reject(ref Vector3 vector, ref Vector3 direction, ref Vector3 result)`](VRageMath.Reject)||
|[`float Min()`](VRageMath.Min)||
|[`float AbsMin()`](VRageMath.AbsMin)||
|[`float Max()`](VRageMath.Max)||
|[`Vector3 MaxAbsComponent()`](VRageMath.MaxAbsComponent)||
|[`float AbsMax()`](VRageMath.AbsMax)||
|[`Vector3 Min(Vector3 value1, Vector3 value2)`](VRageMath.Min)||
|[`void Min(ref Vector3 value1, ref Vector3 value2, ref Vector3 result)`](VRageMath.Min)||
|[`Vector3 Max(Vector3 value1, Vector3 value2)`](VRageMath.Max)||
|[`void Max(ref Vector3 value1, ref Vector3 value2, ref Vector3 result)`](VRageMath.Max)||
|[`void MinMax(ref Vector3 min, ref Vector3 max)`](VRageMath.MinMax)||
|[`Vector3 DominantAxisProjection(Vector3 value1)`](VRageMath.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|[`void DominantAxisProjection(ref Vector3 value1, ref Vector3 result)`](VRageMath.DominantAxisProjection)||
|[`Vector3 Clamp(Vector3 value1, Vector3 min, Vector3 max)`](VRageMath.Clamp)||
|[`void Clamp(ref Vector3 value1, ref Vector3 min, ref Vector3 max, ref Vector3 result)`](VRageMath.Clamp)||
|[`Vector3 ClampToSphere(Vector3 vector, float radius)`](VRageMath.ClampToSphere)||
|[`void ClampToSphere(ref Vector3 vector, float radius)`](VRageMath.ClampToSphere)||
|[`Vector3 Lerp(Vector3 value1, Vector3 value2, float amount)`](VRageMath.Lerp)||
|[`void Lerp(ref Vector3 value1, ref Vector3 value2, float amount, ref Vector3 result)`](VRageMath.Lerp)||
|[`Vector3 Barycentric(Vector3 value1, Vector3 value2, Vector3 value3, float amount1, float amount2)`](VRageMath.Barycentric)||
|[`void Barycentric(ref Vector3 value1, ref Vector3 value2, ref Vector3 value3, float amount1, float amount2, ref Vector3 result)`](VRageMath.Barycentric)||
|[`void Barycentric(Vector3 p, Vector3 a, Vector3 b, Vector3 c, ref float u, ref float v, ref float w)`](VRageMath.Barycentric)||
|[`float TriangleArea(Vector3 v1, Vector3 v2, Vector3 v3)`](VRageMath.TriangleArea)||
|[`float TriangleArea(ref Vector3 v1, ref Vector3 v2, ref Vector3 v3)`](VRageMath.TriangleArea)||
|[`Vector3 SmoothStep(Vector3 value1, Vector3 value2, float amount)`](VRageMath.SmoothStep)||
|[`void SmoothStep(ref Vector3 value1, ref Vector3 value2, float amount, ref Vector3 result)`](VRageMath.SmoothStep)||
|[`Vector3 CatmullRom(Vector3 value1, Vector3 value2, Vector3 value3, Vector3 value4, float amount)`](VRageMath.CatmullRom)||
|[`void CatmullRom(ref Vector3 value1, ref Vector3 value2, ref Vector3 value3, ref Vector3 value4, float amount, ref Vector3 result)`](VRageMath.CatmullRom)||
|[`Vector3 Hermite(Vector3 value1, Vector3 tangent1, Vector3 value2, Vector3 tangent2, float amount)`](VRageMath.Hermite)||
|[`void Hermite(ref Vector3 value1, ref Vector3 tangent1, ref Vector3 value2, ref Vector3 tangent2, float amount, ref Vector3 result)`](VRageMath.Hermite)||
|[`Vector3 Transform(Vector3 position, Matrix matrix)`](VRageMath.Transform)||
|[`Vector3D Transform(Vector3 position, MatrixD matrix)`](VRageMath.Transform)||
|[`Vector3 Transform(Vector3 position, ref Matrix matrix)`](VRageMath.Transform)||
|[`void Transform(ref Vector3 position, ref Matrix matrix, ref Vector3 result)`](VRageMath.Transform)||
|[`void Transform(ref Vector3 position, ref MatrixI matrix, ref Vector3 result)`](VRageMath.Transform)||
|[`void TransformProjection(ref Vector3 position, ref Matrix matrix, ref Vector3 result)`](VRageMath.TransformProjection)||
|[`void TransformNoProjection(ref Vector3 vector, ref Matrix matrix, ref Vector3 result)`](VRageMath.TransformNoProjection)||
|[`void RotateAndScale(ref Vector3 vector, ref Matrix matrix, ref Vector3 result)`](VRageMath.RotateAndScale)||
|[`Vector3 RotateAndScale(Vector3 vector, Matrix matrix)`](VRageMath.RotateAndScale)||
|[`Vector3 TransformNormal(Vector3 normal, Matrix matrix)`](VRageMath.TransformNormal)||
|[`Vector3 TransformNormal(Vector3 normal, MatrixD matrix)`](VRageMath.TransformNormal)||
|[`Vector3 TransformNormal(Vector3D normal, Matrix matrix)`](VRageMath.TransformNormal)||
|[`void TransformNormal(ref Vector3 normal, ref Matrix matrix, ref Vector3 result)`](VRageMath.TransformNormal)||
|[`void TransformNormal(ref Vector3 normal, ref MatrixD matrix, ref Vector3 result)`](VRageMath.TransformNormal)||
|[`void TransformNormal(ref Vector3 normal, ref MatrixI matrix, ref Vector3 result)`](VRageMath.TransformNormal)||
|[`Vector3 TransformNormal(Vector3 normal, MyBlockOrientation orientation)`](VRageMath.TransformNormal)||
|[`void TransformNormal(ref Vector3 normal, MyBlockOrientation orientation, ref Vector3 result)`](VRageMath.TransformNormal)||
|[`Vector3 TransformNormal(Vector3 normal, ref Matrix matrix)`](VRageMath.TransformNormal)||
|[`Vector3 Transform(Vector3 value, Quaternion rotation)`](VRageMath.Transform)||
|[`void Transform(ref Vector3 value, ref Quaternion rotation, ref Vector3 result)`](VRageMath.Transform)||
|[`void Transform(Vector3[] sourceArray, ref Matrix matrix, Vector3[] destinationArray)`](VRageMath.Transform)||
|[`void Transform(Vector3[] sourceArray, int sourceIndex, ref Matrix matrix, Vector3[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)||
|[`void TransformNormal(Vector3[] sourceArray, ref Matrix matrix, Vector3[] destinationArray)`](VRageMath.TransformNormal)||
|[`void TransformNormal(Vector3[] sourceArray, int sourceIndex, ref Matrix matrix, Vector3[] destinationArray, int destinationIndex, int length)`](VRageMath.TransformNormal)||
|[`void Transform(Vector3[] sourceArray, ref Quaternion rotation, Vector3[] destinationArray)`](VRageMath.Transform)||
|[`void Transform(Vector3[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector3[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)||
|[`Vector3 Negate(Vector3 value)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
