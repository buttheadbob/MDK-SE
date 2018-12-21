← [Index](index)
# Vector3D Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with three components.
### Fields
|Member|Description|
|---|---|
|[`double X`](VRageMath.X)||
|[`double Y`](VRageMath.Y)||
|[`double Z`](VRageMath.Z)||
|[`Vector3D Zero`](VRageMath.Zero)||
|[`Vector3D One`](VRageMath.One)||
|[`Vector3D Half`](VRageMath.Half)||
|[`Vector3D PositiveInfinity`](VRageMath.PositiveInfinity)||
|[`Vector3D NegativeInfinity`](VRageMath.NegativeInfinity)||
|[`Vector3D UnitX`](VRageMath.UnitX)||
|[`Vector3D UnitY`](VRageMath.UnitY)||
|[`Vector3D UnitZ`](VRageMath.UnitZ)||
|[`Vector3D Up`](VRageMath.Up)||
|[`Vector3D Down`](VRageMath.Down)||
|[`Vector3D Right`](VRageMath.Right)||
|[`Vector3D Left`](VRageMath.Left)||
|[`Vector3D Forward`](VRageMath.Forward)||
|[`Vector3D Backward`](VRageMath.Backward)||
|[`Vector3D MaxValue`](VRageMath.MaxValue)||
|[`Vector3D MinValue`](VRageMath.MinValue)||
### Properties
|Member|Description|
|---|---|
|[`double Sum`](VRageMath.Sum)||
|[`double Volume`](VRageMath.Volume)||
### Methods
|Member|Description|
|---|---|
|[`void TransformNormal(ref Vector3D normal, ref MatrixI matrix, ref Vector3D result)`](VRageMath.TransformNormal)||
|[`Vector3D TransformNormal(Vector3D normal, MyBlockOrientation orientation)`](VRageMath.TransformNormal)||
|[`void TransformNormal(ref Vector3D normal, MyBlockOrientation orientation, ref Vector3D result)`](VRageMath.TransformNormal)||
|[`Vector3D TransformNormal(Vector3D normal, ref MatrixD matrix)`](VRageMath.TransformNormal)||
|[`Vector3D Transform(Vector3D value, Quaternion rotation)`](VRageMath.Transform)||
|[`void Transform(ref Vector3D value, ref Quaternion rotation, ref Vector3D result)`](VRageMath.Transform)||
|[`void Rotate(ref Vector3D vector, ref MatrixD rotationMatrix, ref Vector3D result)`](VRageMath.Rotate)||
|[`Vector3D Rotate(Vector3D vector, MatrixD rotationMatrix)`](VRageMath.Rotate)||
|[`void Transform(Vector3D[] sourceArray, ref MatrixD matrix, Vector3D[] destinationArray)`](VRageMath.Transform)||
|[`void Transform(Vector3D[] sourceArray, ref MatrixD matrix, *Vector3D destinationArray)`](VRageMath.Transform)||
|[`void Transform(Vector3D[] sourceArray, int sourceIndex, ref Matrix matrix, Vector3D[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)||
|[`void TransformNormal(Vector3D[] sourceArray, ref Matrix matrix, Vector3D[] destinationArray)`](VRageMath.TransformNormal)||
|[`void TransformNormal(Vector3D[] sourceArray, ref Matrix matrix, *Vector3D destinationArray)`](VRageMath.TransformNormal)||
|[`void TransformNormal(Vector3D[] sourceArray, int sourceIndex, ref Matrix matrix, Vector3D[] destinationArray, int destinationIndex, int length)`](VRageMath.TransformNormal)||
|[`void Transform(Vector3D[] sourceArray, ref Quaternion rotation, Vector3D[] destinationArray)`](VRageMath.Transform)||
|[`void Transform(Vector3D[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector3D[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)||
|[`Vector3D Negate(Vector3D value)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|[`void Negate(ref Vector3D value, ref Vector3D result)`](VRageMath.Negate)||
|[`Vector3D Add(Vector3D value1, Vector3D value2)`](VRageMath.Add)||
|[`void Add(ref Vector3D value1, ref Vector3D value2, ref Vector3D result)`](VRageMath.Add)||
|[`Vector3D Subtract(Vector3D value1, Vector3D value2)`](VRageMath.Subtract)||
|[`void Subtract(ref Vector3D value1, ref Vector3D value2, ref Vector3D result)`](VRageMath.Subtract)||
|[`Vector3D Multiply(Vector3D value1, Vector3D value2)`](VRageMath.Multiply)||
|[`void Multiply(ref Vector3D value1, ref Vector3D value2, ref Vector3D result)`](VRageMath.Multiply)||
|[`Vector3D Multiply(Vector3D value1, double scaleFactor)`](VRageMath.Multiply)||
|[`void Multiply(ref Vector3D value1, double scaleFactor, ref Vector3D result)`](VRageMath.Multiply)||
|[`Vector3D Divide(Vector3D value1, Vector3D value2)`](VRageMath.Divide)||
|[`void Divide(ref Vector3D value1, ref Vector3D value2, ref Vector3D result)`](VRageMath.Divide)||
|[`Vector3D Divide(Vector3D value1, double value2)`](VRageMath.Divide)||
|[`void Divide(ref Vector3D value1, double value2, ref Vector3D result)`](VRageMath.Divide)||
|[`Vector3D CalculatePerpendicularVector(Vector3D v)`](VRageMath.CalculatePerpendicularVector)||
|[`void CalculatePerpendicularVector(ref Vector3D result)`](VRageMath.CalculatePerpendicularVector)||
|[`void GetAzimuthAndElevation(Vector3D v, ref double azimuth, ref double elevation)`](VRageMath.GetAzimuthAndElevation)||
|[`void CreateFromAzimuthAndElevation(double azimuth, double elevation, ref Vector3D direction)`](VRageMath.CreateFromAzimuthAndElevation)||
|[`long VolumeInt(double multiplier)`](VRageMath.VolumeInt)||
|[`bool IsInsideInclusive(ref Vector3D min, ref Vector3D max)`](VRageMath.IsInsideInclusive)||
|[`Vector3D SwapYZCoordinates(Vector3D v)`](VRageMath.SwapYZCoordinates)||
|[`double GetDim(int i)`](VRageMath.GetDim)||
|[`void SetDim(int i, double value)`](VRageMath.SetDim)||
|[`Vector3I Round(Vector3D vect3d)`](VRageMath.Round)||
|[`Vector3I Floor(Vector3D vect3d)`](VRageMath.Floor)||
|[`void Fract(ref Vector3D o, ref Vector3D r)`](VRageMath.Fract)||
|[`Vector3D Round(Vector3D v, int numDecimals)`](VRageMath.Round)||
|[`void Abs(ref Vector3D vector3D, ref Vector3D abs)`](VRageMath.Abs)||
|[`Vector3D ProjectOnPlane(ref Vector3D vec, ref Vector3D planeNormal)`](VRageMath.ProjectOnPlane)||
|[`Vector3D ProjectOnVector(ref Vector3D vec, ref Vector3D guideVector)`](VRageMath.ProjectOnVector)||
|[`Vector3D Abs(Vector3D value)`](VRageMath.Abs)||
|[`Vector3D Sign(Vector3D value)`](VRageMath.Sign)||
|[`Vector3D SignNonZero(Vector3D value)`](VRageMath.SignNonZero)|Returns per component sign, never returns zero. For zero component returns sign 1. Faster than Sign.|
|[`void Interpolate3(Vector3D v0, Vector3D v1, double rt)`](VRageMath.Interpolate3)||
|[`bool IsValid()`](VRageMath.IsValid)||
|[`void AssertIsValid()`](VRageMath.AssertIsValid)||
|[`bool IsUnit(ref Vector3D value)`](VRageMath.IsUnit)||
|[`bool ArePerpendicular(ref Vector3D a, ref Vector3D b)`](VRageMath.ArePerpendicular)||
|[`bool IsZero(Vector3D value)`](VRageMath.IsZero)||
|[`bool IsZero(Vector3D value, double epsilon)`](VRageMath.IsZero)||
|[`Vector3D IsZeroVector(Vector3D value)`](VRageMath.IsZeroVector)||
|[`Vector3D IsZeroVector(Vector3D value, double epsilon)`](VRageMath.IsZeroVector)||
|[`Vector3D Step(Vector3D value)`](VRageMath.Step)||
|[`string ToString()`](VRageMath.ToString)||
|[`bool TryParse(string str, ref Vector3D retval)`](VRageMath.TryParse)||
|[`string ToString(string format)`](VRageMath.ToString)||
|[`bool Equals(Vector3D other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector3.|
|[`bool Equals(Vector3D other, double epsilon)`](VRageMath.Equals)||
|[`bool Equals(Object obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`long GetHash()`](VRageMath.GetHash)||
|[`double Length()`](VRageMath.Length)||
|[`double LengthSquared()`](VRageMath.LengthSquared)||
|[`double Distance(Vector3D value1, Vector3D value2)`](VRageMath.Distance)||
|[`double Distance(Vector3D value1, Vector3 value2)`](VRageMath.Distance)||
|[`double Distance(Vector3 value1, Vector3D value2)`](VRageMath.Distance)||
|[`void Distance(ref Vector3D value1, ref Vector3D value2, ref double result)`](VRageMath.Distance)||
|[`double DistanceSquared(Vector3D value1, Vector3D value2)`](VRageMath.DistanceSquared)||
|[`void DistanceSquared(ref Vector3D value1, ref Vector3D value2, ref double result)`](VRageMath.DistanceSquared)||
|[`double RectangularDistance(Vector3D value1, Vector3D value2)`](VRageMath.RectangularDistance)||
|[`double RectangularDistance(ref Vector3D value1, ref Vector3D value2)`](VRageMath.RectangularDistance)||
|[`double Dot(Vector3D vector1, Vector3D vector2)`](VRageMath.Dot)||
|[`double Dot(Vector3D vector1, Vector3 vector2)`](VRageMath.Dot)||
|[`void Dot(ref Vector3D vector1, ref Vector3D vector2, ref double result)`](VRageMath.Dot)||
|[`void Dot(ref Vector3D vector1, ref Vector3 vector2, ref double result)`](VRageMath.Dot)||
|[`void Dot(ref Vector3 vector1, ref Vector3D vector2, ref double result)`](VRageMath.Dot)||
|[`double Dot(Vector3D v)`](VRageMath.Dot)||
|[`double Dot(Vector3 v)`](VRageMath.Dot)||
|[`double Dot(ref Vector3D v)`](VRageMath.Dot)||
|[`Vector3D Cross(Vector3D v)`](VRageMath.Cross)||
|[`double Normalize()`](VRageMath.Normalize)||
|[`Vector3D Normalize(Vector3D value)`](VRageMath.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[`void Normalize(ref Vector3D value, ref Vector3D result)`](VRageMath.Normalize)||
|[`Vector3D Cross(Vector3D vector1, Vector3D vector2)`](VRageMath.Cross)||
|[`void Cross(ref Vector3D vector1, ref Vector3D vector2, ref Vector3D result)`](VRageMath.Cross)||
|[`Vector3D Reflect(Vector3D vector, Vector3D normal)`](VRageMath.Reflect)||
|[`void Reflect(ref Vector3D vector, ref Vector3D normal, ref Vector3D result)`](VRageMath.Reflect)||
|[`Vector3D Reject(Vector3D vector, Vector3D direction)`](VRageMath.Reject)||
|[`void Reject(ref Vector3D vector, ref Vector3D direction, ref Vector3D result)`](VRageMath.Reject)||
|[`double Min()`](VRageMath.Min)||
|[`double AbsMin()`](VRageMath.AbsMin)||
|[`double Max()`](VRageMath.Max)||
|[`double AbsMax()`](VRageMath.AbsMax)||
|[`int AbsMaxComponent()`](VRageMath.AbsMaxComponent)||
|[`Vector3D Min(Vector3D value1, Vector3D value2)`](VRageMath.Min)||
|[`void Min(ref Vector3D value1, ref Vector3D value2, ref Vector3D result)`](VRageMath.Min)||
|[`Vector3D Max(Vector3D value1, Vector3D value2)`](VRageMath.Max)||
|[`void Max(ref Vector3D value1, ref Vector3D value2, ref Vector3D result)`](VRageMath.Max)||
|[`void MinMax(ref Vector3D min, ref Vector3D max)`](VRageMath.MinMax)||
|[`Vector3D DominantAxisProjection(Vector3D value1)`](VRageMath.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|[`void DominantAxisProjection(ref Vector3D value1, ref Vector3D result)`](VRageMath.DominantAxisProjection)||
|[`Vector3D Clamp(Vector3D value1, Vector3D min, Vector3D max)`](VRageMath.Clamp)||
|[`void Clamp(ref Vector3D value1, ref Vector3D min, ref Vector3D max, ref Vector3D result)`](VRageMath.Clamp)||
|[`Vector3D ClampToSphere(Vector3D vector, double radius)`](VRageMath.ClampToSphere)||
|[`void ClampToSphere(ref Vector3D vector, double radius)`](VRageMath.ClampToSphere)||
|[`Vector3D Lerp(Vector3D value1, Vector3D value2, double amount)`](VRageMath.Lerp)||
|[`void Lerp(ref Vector3D value1, ref Vector3D value2, double amount, ref Vector3D result)`](VRageMath.Lerp)||
|[`Vector3D Barycentric(Vector3D value1, Vector3D value2, Vector3D value3, double amount1, double amount2)`](VRageMath.Barycentric)||
|[`void Barycentric(ref Vector3D value1, ref Vector3D value2, ref Vector3D value3, double amount1, double amount2, ref Vector3D result)`](VRageMath.Barycentric)||
|[`void Barycentric(Vector3D p, Vector3D a, Vector3D b, Vector3D c, ref double u, ref double v, ref double w)`](VRageMath.Barycentric)||
|[`Vector3D SmoothStep(Vector3D value1, Vector3D value2, double amount)`](VRageMath.SmoothStep)||
|[`void SmoothStep(ref Vector3D value1, ref Vector3D value2, double amount, ref Vector3D result)`](VRageMath.SmoothStep)||
|[`Vector3D CatmullRom(Vector3D value1, Vector3D value2, Vector3D value3, Vector3D value4, double amount)`](VRageMath.CatmullRom)||
|[`void CatmullRom(ref Vector3D value1, ref Vector3D value2, ref Vector3D value3, ref Vector3D value4, double amount, ref Vector3D result)`](VRageMath.CatmullRom)||
|[`Vector3D Hermite(Vector3D value1, Vector3D tangent1, Vector3D value2, Vector3D tangent2, double amount)`](VRageMath.Hermite)||
|[`void Hermite(ref Vector3D value1, ref Vector3D tangent1, ref Vector3D value2, ref Vector3D tangent2, double amount, ref Vector3D result)`](VRageMath.Hermite)||
|[`Vector3D Transform(Vector3D position, MatrixD matrix)`](VRageMath.Transform)||
|[`Vector3D Transform(Vector3 position, MatrixD matrix)`](VRageMath.Transform)||
|[`Vector3D Transform(Vector3D position, Matrix matrix)`](VRageMath.Transform)||
|[`Vector3D Transform(Vector3D position, ref MatrixD matrix)`](VRageMath.Transform)||
|[`void Transform(ref Vector3D position, ref MatrixD matrix, ref Vector3D result)`](VRageMath.Transform)||
|[`void Transform(ref Vector3 position, ref MatrixD matrix, ref Vector3D result)`](VRageMath.Transform)||
|[`void TransformNoProjection(ref Vector3D vector, ref MatrixD matrix, ref Vector3D result)`](VRageMath.TransformNoProjection)||
|[`void RotateAndScale(ref Vector3D vector, ref MatrixD matrix, ref Vector3D result)`](VRageMath.RotateAndScale)||
|[`void Transform(ref Vector3D position, ref MatrixI matrix, ref Vector3D result)`](VRageMath.Transform)||
|[`Vector3D TransformNormal(Vector3D normal, Matrix matrix)`](VRageMath.TransformNormal)||
|[`Vector3D TransformNormal(Vector3 normal, MatrixD matrix)`](VRageMath.TransformNormal)||
|[`Vector3D TransformNormal(Vector3D normal, MatrixD matrix)`](VRageMath.TransformNormal)||
|[`void TransformNormal(ref Vector3D normal, ref MatrixD matrix, ref Vector3D result)`](VRageMath.TransformNormal)||
|[`void TransformNormal(ref Vector3 normal, ref MatrixD matrix, ref Vector3D result)`](VRageMath.TransformNormal)||
