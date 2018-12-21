← [Index](index.md)
# MathHelper Class
** Namespace: ** VRageMath  
** Assembly: ** VRage.Math.dll  
## Summary
Contains commonly used precalculated values.
### Fields
|Member|Description|
|---|---|
|[`float E`](VRageMath.E.md)||
|[`float Log2E`](VRageMath.Log2E.md)||
|[`float Log10E`](VRageMath.Log10E.md)||
|[`float Pi`](VRageMath.Pi.md)||
|[`float TwoPi`](VRageMath.TwoPi.md)||
|[`float FourPi`](VRageMath.FourPi.md)||
|[`float PiOver2`](VRageMath.PiOver2.md)||
|[`float PiOver4`](VRageMath.PiOver4.md)||
|[`float Sqrt2`](VRageMath.Sqrt2.md)||
|[`float Sqrt3`](VRageMath.Sqrt3.md)||
|[`float RadiansPerSecondToRPM`](VRageMath.RadiansPerSecondToRPM.md)||
|[`float RPMToRadiansPerSecond`](VRageMath.RPMToRadiansPerSecond.md)||
|[`float RPMToRadiansPerMillisec`](VRageMath.RPMToRadiansPerMillisec.md)||
|[`float EPSILON`](VRageMath.EPSILON.md)||
|[`float EPSILON10`](VRageMath.EPSILON10.md)||
### Methods
|Member|Description|
|---|---|
|[`float ToRadians(float degrees)`](VRageMath.ToRadians.md)|Converts degrees to radians.|
|[`Vector3 ToRadians(Vector3 v)`](VRageMath.ToRadians.md)||
|[`double ToRadians(double degrees)`](VRageMath.ToRadians.md)|Converts degrees to radians.|
|[`float ToDegrees(float radians)`](VRageMath.ToDegrees.md)|Converts radians to degrees.|
|[`double ToDegrees(double radians)`](VRageMath.ToDegrees.md)||
|[`float Distance(float value1, float value2)`](VRageMath.Distance.md)||
|[`float Min(float value1, float value2)`](VRageMath.Min.md)||
|[`float Max(float value1, float value2)`](VRageMath.Max.md)||
|[`double Min(double value1, double value2)`](VRageMath.Min.md)||
|[`double Max(double value1, double value2)`](VRageMath.Max.md)||
|[`float Clamp(float value, float min, float max)`](VRageMath.Clamp.md)||
|[`double Clamp(double value, double min, double max)`](VRageMath.Clamp.md)||
|[`MyFixedPoint Clamp(MyFixedPoint value, MyFixedPoint min, MyFixedPoint max)`](VRageMath.Clamp.md)||
|[`int Clamp(int value, int min, int max)`](VRageMath.Clamp.md)||
|[`float Lerp(float value1, float value2, float amount)`](VRageMath.Lerp.md)||
|[`double Lerp(double value1, double value2, double amount)`](VRageMath.Lerp.md)||
|[`float InterpLog(float value, float amount1, float amount2)`](VRageMath.InterpLog.md)||
|[`float InterpLogInv(float value, float amount1, float amount2)`](VRageMath.InterpLogInv.md)||
|[`float Barycentric(float value1, float value2, float value3, float amount1, float amount2)`](VRageMath.Barycentric.md)||
|[`float SmoothStep(float value1, float value2, float amount)`](VRageMath.SmoothStep.md)||
|[`double SmoothStep(double value1, double value2, double amount)`](VRageMath.SmoothStep.md)||
|[`float SmoothStepStable(float amount)`](VRageMath.SmoothStepStable.md)|Interpolates between zero and one using cubic equiation, solved by de Casteljau.|
|[`double SmoothStepStable(double amount)`](VRageMath.SmoothStepStable.md)|Interpolates between zero and one using cubic equiation, solved by de Casteljau.|
|[`float CatmullRom(float value1, float value2, float value3, float value4, float amount)`](VRageMath.CatmullRom.md)||
|[`float Hermite(float value1, float tangent1, float value2, float tangent2, float amount)`](VRageMath.Hermite.md)||
|[`Vector3D CalculateBezierPoint(double t, Vector3D p0, Vector3D p1, Vector3D p2, Vector3D p3)`](VRageMath.CalculateBezierPoint.md)||
|[`float WrapAngle(float angle)`](VRageMath.WrapAngle.md)|Reduces a given angle to a value between π and -π.|
|[`int GetNearestBiggerPowerOfTwo(int v)`](VRageMath.GetNearestBiggerPowerOfTwo.md)||
|[`uint GetNearestBiggerPowerOfTwo(uint v)`](VRageMath.GetNearestBiggerPowerOfTwo.md)||
|[`int GetNumberOfMipmaps(int v)`](VRageMath.GetNumberOfMipmaps.md)||
|[`int GetNearestBiggerPowerOfTwo(float f)`](VRageMath.GetNearestBiggerPowerOfTwo.md)|Returns nearest bigger power of two|
|[`int GetNearestBiggerPowerOfTwo(double f)`](VRageMath.GetNearestBiggerPowerOfTwo.md)||
|[`float Max(float a, float b, float c)`](VRageMath.Max.md)||
|[`int Max(int a, int b, int c)`](VRageMath.Max.md)||
|[`float Min(float a, float b, float c)`](VRageMath.Min.md)||
|[`double Max(double a, double b, double c)`](VRageMath.Max.md)||
|[`double Min(double a, double b, double c)`](VRageMath.Min.md)||
|[`int ComputeHashFromBytes(Byte[] bytes)`](VRageMath.ComputeHashFromBytes.md)||
|[`float RoundOn2(float x)`](VRageMath.RoundOn2.md)||
|[`bool IsPowerOfTwo(int x)`](VRageMath.IsPowerOfTwo.md)|Returns true if value is power of two|
|[`float SCurve3(float t)`](VRageMath.SCurve3.md)||
|[`double SCurve3(double t)`](VRageMath.SCurve3.md)||
|[`float SCurve5(float t)`](VRageMath.SCurve5.md)||
|[`double SCurve5(double t)`](VRageMath.SCurve5.md)||
|[`float Saturate(float n)`](VRageMath.Saturate.md)||
|[`double Saturate(double n)`](VRageMath.Saturate.md)||
|[`int Floor(float n)`](VRageMath.Floor.md)||
|[`int Floor(double n)`](VRageMath.Floor.md)||
|[`int Log2Floor(int value)`](VRageMath.Log2Floor.md)||
|[`int Log2Ceiling(int value)`](VRageMath.Log2Ceiling.md)||
|[`int Log2(int n)`](VRageMath.Log2.md)||
|[`int Log2(uint n)`](VRageMath.Log2.md)||
|[`int Pow2(int n)`](VRageMath.Pow2.md)|Returns 2^n|
|[`double CubicInterp(double p0, double p1, double p2, double p3, double t)`](VRageMath.CubicInterp.md)||
|[`void LimitRadians2PI(ref double angle)`](VRageMath.LimitRadians2PI.md)||
|[`void LimitRadians(ref float angle)`](VRageMath.LimitRadians.md)||
|[`void LimitRadiansPI(ref double angle)`](VRageMath.LimitRadiansPI.md)||
|[`void LimitRadiansPI(ref float angle)`](VRageMath.LimitRadiansPI.md)||
|[`Vector3 CalculateVectorOnSphere(Vector3 northPoleDir, float phi, float theta)`](VRageMath.CalculateVectorOnSphere.md)||
|[`float MonotonicCosine(float radians)`](VRageMath.MonotonicCosine.md)|Calculate the monotonic cosine of a value. Monotonic cosine is an alternative cosine encoding that is monotonic in the [-pi, pi] interval. We use this when some parameter of an onject in a planet is constrained by latitude. The 'monotonicity' is guaranteed by subtracting the cosine value from 2 if the angle is positive. So for instance MonotonicCos(pi/2) = 2. This only works in the above interval of course.|
|[`float MonotonicAcos(float cos)`](VRageMath.MonotonicAcos.md)||
|[`float Atan(float x)`](VRageMath.Atan.md)|Faster Atan implementation. Good only in the [-pi/2, pi/2] range.|
|[`double Atan(double x)`](VRageMath.Atan.md)|Faster Atan implementation. Good only in the [-pi/2, pi/2] range.|
|[`bool IsEqual(float value1, float value2)`](VRageMath.IsEqual.md)||
|[`bool IsEqual(Vector2 value1, Vector2 value2)`](VRageMath.IsEqual.md)||
|[`bool IsEqual(Vector3 value1, Vector3 value2)`](VRageMath.IsEqual.md)||
|[`bool IsEqual(Quaternion value1, Quaternion value2)`](VRageMath.IsEqual.md)||
|[`bool IsEqual(QuaternionD value1, QuaternionD value2)`](VRageMath.IsEqual.md)||
|[`bool IsEqual(Matrix value1, Matrix value2)`](VRageMath.IsEqual.md)||
|[`bool IsValid(Matrix matrix)`](VRageMath.IsValid.md)||
|[`bool IsValid(MatrixD matrix)`](VRageMath.IsValid.md)||
|[`bool IsValid(Vector3 vec)`](VRageMath.IsValid.md)||
|[`bool IsValid(Vector3D vec)`](VRageMath.IsValid.md)||
|[`bool IsValid(Vector2 vec)`](VRageMath.IsValid.md)||
|[`bool IsValid(float f)`](VRageMath.IsValid.md)||
|[`bool IsValid(double f)`](VRageMath.IsValid.md)||
|[`bool IsValid(Nullable<Vector3> vec)`](VRageMath.IsValid.md)||
|[`bool IsValid(Quaternion q)`](VRageMath.IsValid.md)||
|[`bool IsValidNormal(Vector3 vec)`](VRageMath.IsValidNormal.md)||
|[`bool IsValidOrZero(Matrix matrix)`](VRageMath.IsValidOrZero.md)||
|[`bool IsZero(float value, float epsilon)`](VRageMath.IsZero.md)||
|[`bool IsZero(double value, float epsilon)`](VRageMath.IsZero.md)||
|[`bool IsZero(Vector3 value, float epsilon)`](VRageMath.IsZero.md)||
|[`bool IsZero(Vector3D value, float epsilon)`](VRageMath.IsZero.md)||
|[`bool IsZero(Quaternion value, float epsilon)`](VRageMath.IsZero.md)||
|[`bool IsZero(Vector4 value)`](VRageMath.IsZero.md)||
|[`int Smooth(int newValue, int lastSmooth)`](VRageMath.Smooth.md)||
|[`float Smooth(float newValue, float lastSmooth)`](VRageMath.Smooth.md)||
