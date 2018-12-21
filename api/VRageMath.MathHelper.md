← [Index](index)
# MathHelper Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Contains commonly used precalculated values.
### Fields
|Member|Description|
|---|---|
|[`float E`](VRageMath.E)||
|[`float Log2E`](VRageMath.Log2E)||
|[`float Log10E`](VRageMath.Log10E)||
|[`float Pi`](VRageMath.Pi)||
|[`float TwoPi`](VRageMath.TwoPi)||
|[`float FourPi`](VRageMath.FourPi)||
|[`float PiOver2`](VRageMath.PiOver2)||
|[`float PiOver4`](VRageMath.PiOver4)||
|[`float Sqrt2`](VRageMath.Sqrt2)||
|[`float Sqrt3`](VRageMath.Sqrt3)||
|[`float RadiansPerSecondToRPM`](VRageMath.RadiansPerSecondToRPM)||
|[`float RPMToRadiansPerSecond`](VRageMath.RPMToRadiansPerSecond)||
|[`float RPMToRadiansPerMillisec`](VRageMath.RPMToRadiansPerMillisec)||
|[`float EPSILON`](VRageMath.EPSILON)||
|[`float EPSILON10`](VRageMath.EPSILON10)||
### Methods
|Member|Description|
|---|---|
|[`float ToRadians(float degrees)`](VRageMath.ToRadians)|Converts degrees to radians.|
|[`Vector3 ToRadians(Vector3 v)`](VRageMath.ToRadians)||
|[`double ToRadians(double degrees)`](VRageMath.ToRadians)|Converts degrees to radians.|
|[`float ToDegrees(float radians)`](VRageMath.ToDegrees)|Converts radians to degrees.|
|[`double ToDegrees(double radians)`](VRageMath.ToDegrees)||
|[`float Distance(float value1, float value2)`](VRageMath.Distance)||
|[`float Min(float value1, float value2)`](VRageMath.Min)||
|[`float Max(float value1, float value2)`](VRageMath.Max)||
|[`double Min(double value1, double value2)`](VRageMath.Min)||
|[`double Max(double value1, double value2)`](VRageMath.Max)||
|[`float Clamp(float value, float min, float max)`](VRageMath.Clamp)||
|[`double Clamp(double value, double min, double max)`](VRageMath.Clamp)||
|[`MyFixedPoint Clamp(MyFixedPoint value, MyFixedPoint min, MyFixedPoint max)`](VRageMath.Clamp)||
|[`int Clamp(int value, int min, int max)`](VRageMath.Clamp)||
|[`float Lerp(float value1, float value2, float amount)`](VRageMath.Lerp)||
|[`double Lerp(double value1, double value2, double amount)`](VRageMath.Lerp)||
|[`float InterpLog(float value, float amount1, float amount2)`](VRageMath.InterpLog)||
|[`float InterpLogInv(float value, float amount1, float amount2)`](VRageMath.InterpLogInv)||
|[`float Barycentric(float value1, float value2, float value3, float amount1, float amount2)`](VRageMath.Barycentric)||
|[`float SmoothStep(float value1, float value2, float amount)`](VRageMath.SmoothStep)||
|[`double SmoothStep(double value1, double value2, double amount)`](VRageMath.SmoothStep)||
|[`float SmoothStepStable(float amount)`](VRageMath.SmoothStepStable)|Interpolates between zero and one using cubic equiation, solved by de Casteljau.|
|[`double SmoothStepStable(double amount)`](VRageMath.SmoothStepStable)|Interpolates between zero and one using cubic equiation, solved by de Casteljau.|
|[`float CatmullRom(float value1, float value2, float value3, float value4, float amount)`](VRageMath.CatmullRom)||
|[`float Hermite(float value1, float tangent1, float value2, float tangent2, float amount)`](VRageMath.Hermite)||
|[`Vector3D CalculateBezierPoint(double t, Vector3D p0, Vector3D p1, Vector3D p2, Vector3D p3)`](VRageMath.CalculateBezierPoint)||
|[`float WrapAngle(float angle)`](VRageMath.WrapAngle)|Reduces a given angle to a value between π and -π.|
|[`int GetNearestBiggerPowerOfTwo(int v)`](VRageMath.GetNearestBiggerPowerOfTwo)||
|[`uint GetNearestBiggerPowerOfTwo(uint v)`](VRageMath.GetNearestBiggerPowerOfTwo)||
|[`int GetNumberOfMipmaps(int v)`](VRageMath.GetNumberOfMipmaps)||
|[`int GetNearestBiggerPowerOfTwo(float f)`](VRageMath.GetNearestBiggerPowerOfTwo)|Returns nearest bigger power of two|
|[`int GetNearestBiggerPowerOfTwo(double f)`](VRageMath.GetNearestBiggerPowerOfTwo)||
|[`float Max(float a, float b, float c)`](VRageMath.Max)||
|[`int Max(int a, int b, int c)`](VRageMath.Max)||
|[`float Min(float a, float b, float c)`](VRageMath.Min)||
|[`double Max(double a, double b, double c)`](VRageMath.Max)||
|[`double Min(double a, double b, double c)`](VRageMath.Min)||
|[`int ComputeHashFromBytes(Byte[] bytes)`](VRageMath.ComputeHashFromBytes)||
|[`float RoundOn2(float x)`](VRageMath.RoundOn2)||
|[`bool IsPowerOfTwo(int x)`](VRageMath.IsPowerOfTwo)|Returns true if value is power of two|
|[`float SCurve3(float t)`](VRageMath.SCurve3)||
|[`double SCurve3(double t)`](VRageMath.SCurve3)||
|[`float SCurve5(float t)`](VRageMath.SCurve5)||
|[`double SCurve5(double t)`](VRageMath.SCurve5)||
|[`float Saturate(float n)`](VRageMath.Saturate)||
|[`double Saturate(double n)`](VRageMath.Saturate)||
|[`int Floor(float n)`](VRageMath.Floor)||
|[`int Floor(double n)`](VRageMath.Floor)||
|[`int Log2Floor(int value)`](VRageMath.Log2Floor)||
|[`int Log2Ceiling(int value)`](VRageMath.Log2Ceiling)||
|[`int Log2(int n)`](VRageMath.Log2)||
|[`int Log2(uint n)`](VRageMath.Log2)||
|[`int Pow2(int n)`](VRageMath.Pow2)|Returns 2^n|
|[`double CubicInterp(double p0, double p1, double p2, double p3, double t)`](VRageMath.CubicInterp)||
|[`void LimitRadians2PI(ref double angle)`](VRageMath.LimitRadians2PI)||
|[`void LimitRadians(ref float angle)`](VRageMath.LimitRadians)||
|[`void LimitRadiansPI(ref double angle)`](VRageMath.LimitRadiansPI)||
|[`void LimitRadiansPI(ref float angle)`](VRageMath.LimitRadiansPI)||
|[`Vector3 CalculateVectorOnSphere(Vector3 northPoleDir, float phi, float theta)`](VRageMath.CalculateVectorOnSphere)||
|[`float MonotonicCosine(float radians)`](VRageMath.MonotonicCosine)|Calculate the monotonic cosine of a value. Monotonic cosine is an alternative cosine encoding that is monotonic in the [-pi, pi] interval. We use this when some parameter of an onject in a planet is constrained by latitude. The 'monotonicity' is guaranteed by subtracting the cosine value from 2 if the angle is positive. So for instance MonotonicCos(pi/2) = 2. This only works in the above interval of course.|
|[`float MonotonicAcos(float cos)`](VRageMath.MonotonicAcos)||
|[`float Atan(float x)`](VRageMath.Atan)|Faster Atan implementation. Good only in the [-pi/2, pi/2] range.|
|[`double Atan(double x)`](VRageMath.Atan)|Faster Atan implementation. Good only in the [-pi/2, pi/2] range.|
|[`bool IsEqual(float value1, float value2)`](VRageMath.IsEqual)||
|[`bool IsEqual(Vector2 value1, Vector2 value2)`](VRageMath.IsEqual)||
|[`bool IsEqual(Vector3 value1, Vector3 value2)`](VRageMath.IsEqual)||
|[`bool IsEqual(Quaternion value1, Quaternion value2)`](VRageMath.IsEqual)||
|[`bool IsEqual(QuaternionD value1, QuaternionD value2)`](VRageMath.IsEqual)||
|[`bool IsEqual(Matrix value1, Matrix value2)`](VRageMath.IsEqual)||
|[`bool IsValid(Matrix matrix)`](VRageMath.IsValid)||
|[`bool IsValid(MatrixD matrix)`](VRageMath.IsValid)||
|[`bool IsValid(Vector3 vec)`](VRageMath.IsValid)||
|[`bool IsValid(Vector3D vec)`](VRageMath.IsValid)||
|[`bool IsValid(Vector2 vec)`](VRageMath.IsValid)||
|[`bool IsValid(float f)`](VRageMath.IsValid)||
|[`bool IsValid(double f)`](VRageMath.IsValid)||
|[`bool IsValid(Nullable<Vector3> vec)`](VRageMath.IsValid)||
|[`bool IsValid(Quaternion q)`](VRageMath.IsValid)||
|[`bool IsValidNormal(Vector3 vec)`](VRageMath.IsValidNormal)||
|[`bool IsValidOrZero(Matrix matrix)`](VRageMath.IsValidOrZero)||
|[`bool IsZero(float value, float epsilon)`](VRageMath.IsZero)||
|[`bool IsZero(double value, float epsilon)`](VRageMath.IsZero)||
|[`bool IsZero(Vector3 value, float epsilon)`](VRageMath.IsZero)||
|[`bool IsZero(Vector3D value, float epsilon)`](VRageMath.IsZero)||
|[`bool IsZero(Quaternion value, float epsilon)`](VRageMath.IsZero)||
|[`bool IsZero(Vector4 value)`](VRageMath.IsZero)||
|[`int Smooth(int newValue, int lastSmooth)`](VRageMath.Smooth)||
|[`float Smooth(float newValue, float lastSmooth)`](VRageMath.Smooth)||
