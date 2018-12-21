← [Index](index)
# MathHelper Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Contains commonly used precalculated values.
### Fields
<table style="width:100%;display:table">
<tr><td>static [`float E`](VRageMath.E)</td><td>Represents the mathematical constant e.</td></tr>
<tr><td>static [`float Log2E`](VRageMath.Log2E)</td><td>Represents the log base two of e.</td></tr>
<tr><td>static [`float Log10E`](VRageMath.Log10E)</td><td>Represents the log base ten of e.</td></tr>
<tr><td>static [`float Pi`](VRageMath.Pi)</td><td>Represents the value of pi.</td></tr>
<tr><td>static [`float TwoPi`](VRageMath.TwoPi)</td><td>Represents the value of pi times two.</td></tr>
<tr><td>static [`float FourPi`](VRageMath.FourPi)</td><td>Represents the value of pi times two.</td></tr>
<tr><td>static [`float PiOver2`](VRageMath.PiOver2)</td><td>Represents the value of pi divided by two.</td></tr>
<tr><td>static [`float PiOver4`](VRageMath.PiOver4)</td><td>Represents the value of pi divided by four.</td></tr>
<tr><td>static [`float Sqrt2`](VRageMath.Sqrt2)</td><td>Represents the value of the square root of two</td></tr>
<tr><td>static [`float Sqrt3`](VRageMath.Sqrt3)</td><td>Represents the value of the square root of three</td></tr>
<tr><td>static [`float RadiansPerSecondToRPM`](VRageMath.RadiansPerSecondToRPM)</td><td>60 / 2*pi</td></tr>
<tr><td>static [`float RPMToRadiansPerSecond`](VRageMath.RPMToRadiansPerSecond)</td><td>2*pi / 60</td></tr>
<tr><td>static [`float RPMToRadiansPerMillisec`](VRageMath.RPMToRadiansPerMillisec)</td><td>2*pi / 60000</td></tr>
<tr><td>static [`float EPSILON`](VRageMath.EPSILON)</td><td></td></tr>
<tr><td>static [`float EPSILON10`](VRageMath.EPSILON10)</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>static [`float ToRadians(float degrees)`](VRageMath.ToRadians)</td><td>Converts degrees to radians.</td></tr>
<tr><td>static [`Vector3 ToRadians(Vector3 v)`](VRageMath.ToRadians)</td><td></td></tr>
<tr><td>static [`double ToRadians(double degrees)`](VRageMath.ToRadians)</td><td>Converts degrees to radians.</td></tr>
<tr><td>static [`float ToDegrees(float radians)`](VRageMath.ToDegrees)</td><td>Converts radians to degrees.</td></tr>
<tr><td>static [`double ToDegrees(double radians)`](VRageMath.ToDegrees)</td><td></td></tr>
<tr><td>static [`float Distance(float value1, float value2)`](VRageMath.Distance)</td><td>Calculates the absolute value of the difference of two values.</td></tr>
<tr><td>static [`float Min(float value1, float value2)`](VRageMath.Min)</td><td>Returns the lesser of two values.</td></tr>
<tr><td>static [`float Max(float value1, float value2)`](VRageMath.Max)</td><td>Returns the greater of two values.</td></tr>
<tr><td>static [`double Min(double value1, double value2)`](VRageMath.Min)</td><td>Returns the lesser of two values.</td></tr>
<tr><td>static [`double Max(double value1, double value2)`](VRageMath.Max)</td><td>Returns the greater of two values.</td></tr>
<tr><td>static [`float Clamp(float value, float min, float max)`](VRageMath.Clamp)</td><td>Restricts a value to be within a specified range. Reference page contains links to related code samples.</td></tr>
<tr><td>static [`double Clamp(double value, double min, double max)`](VRageMath.Clamp)</td><td>Restricts a value to be within a specified range. Reference page contains links to related code samples.</td></tr>
<tr><td>static [`MyFixedPoint Clamp(MyFixedPoint value, MyFixedPoint min, MyFixedPoint max)`](VRageMath.Clamp)</td><td>Restricts a value to be within a specified range. Reference page contains links to related code samples.</td></tr>
<tr><td>static [`int Clamp(int value, int min, int max)`](VRageMath.Clamp)</td><td>Restricts a value to be within a specified range. Reference page contains links to related code samples.</td></tr>
<tr><td>static [`float Lerp(float value1, float value2, float amount)`](VRageMath.Lerp)</td><td>Linearly interpolates between two values.</td></tr>
<tr><td>static [`double Lerp(double value1, double value2, double amount)`](VRageMath.Lerp)</td><td>Linearly interpolates between two values.</td></tr>
<tr><td>static [`float InterpLog(float value, float amount1, float amount2)`](VRageMath.InterpLog)</td><td>Performs interpolation on logarithmic scale.</td></tr>
<tr><td>static [`float InterpLogInv(float value, float amount1, float amount2)`](VRageMath.InterpLogInv)</td><td></td></tr>
<tr><td>static [`float Barycentric(float value1, float value2, float value3, float amount1, float amount2)`](VRageMath.Barycentric)</td><td>Returns the Cartesian coordinate for one axis of a point that is defined by a given triangle and two normalized barycentric (areal) coordinates.</td></tr>
<tr><td>static [`float SmoothStep(float value1, float value2, float amount)`](VRageMath.SmoothStep)</td><td>Interpolates between two values using a cubic equation.</td></tr>
<tr><td>static [`double SmoothStep(double value1, double value2, double amount)`](VRageMath.SmoothStep)</td><td>Interpolates between two values using a cubic equation.</td></tr>
<tr><td>static [`float SmoothStepStable(float amount)`](VRageMath.SmoothStepStable)</td><td>Interpolates between zero and one using cubic equiation, solved by de Casteljau.</td></tr>
<tr><td>static [`double SmoothStepStable(double amount)`](VRageMath.SmoothStepStable)</td><td>Interpolates between zero and one using cubic equiation, solved by de Casteljau.</td></tr>
<tr><td>static [`float CatmullRom(float value1, float value2, float value3, float value4, float amount)`](VRageMath.CatmullRom)</td><td>Performs a Catmull-Rom interpolation using the specified positions.</td></tr>
<tr><td>static [`float Hermite(float value1, float tangent1, float value2, float tangent2, float amount)`](VRageMath.Hermite)</td><td>Performs a Hermite spline interpolation.</td></tr>
<tr><td>static [`Vector3D CalculateBezierPoint(double t, Vector3D p0, Vector3D p1, Vector3D p2, Vector3D p3)`](VRageMath.CalculateBezierPoint)</td><td></td></tr>
<tr><td>static [`float WrapAngle(float angle)`](VRageMath.WrapAngle)</td><td>Reduces a given angle to a value between π and -π.</td></tr>
<tr><td>static [`int GetNearestBiggerPowerOfTwo(int v)`](VRageMath.GetNearestBiggerPowerOfTwo)</td><td></td></tr>
<tr><td>static [`uint GetNearestBiggerPowerOfTwo(uint v)`](VRageMath.GetNearestBiggerPowerOfTwo)</td><td></td></tr>
<tr><td>static [`int GetNumberOfMipmaps(int v)`](VRageMath.GetNumberOfMipmaps)</td><td></td></tr>
<tr><td>static [`int GetNearestBiggerPowerOfTwo(float f)`](VRageMath.GetNearestBiggerPowerOfTwo)</td><td>Returns nearest bigger power of two</td></tr>
<tr><td>static [`int GetNearestBiggerPowerOfTwo(double f)`](VRageMath.GetNearestBiggerPowerOfTwo)</td><td></td></tr>
<tr><td>static [`float Max(float a, float b, float c)`](VRageMath.Max)</td><td></td></tr>
<tr><td>static [`int Max(int a, int b, int c)`](VRageMath.Max)</td><td></td></tr>
<tr><td>static [`float Min(float a, float b, float c)`](VRageMath.Min)</td><td></td></tr>
<tr><td>static [`double Max(double a, double b, double c)`](VRageMath.Max)</td><td></td></tr>
<tr><td>static [`double Min(double a, double b, double c)`](VRageMath.Min)</td><td></td></tr>
<tr><td>static [`int ComputeHashFromBytes(Byte[] bytes)`](VRageMath.ComputeHashFromBytes)</td><td></td></tr>
<tr><td>static [`float RoundOn2(float x)`](VRageMath.RoundOn2)</td><td></td></tr>
<tr><td>static [`bool IsPowerOfTwo(int x)`](VRageMath.IsPowerOfTwo)</td><td>Returns true if value is power of two</td></tr>
<tr><td>static [`float SCurve3(float t)`](VRageMath.SCurve3)</td><td></td></tr>
<tr><td>static [`double SCurve3(double t)`](VRageMath.SCurve3)</td><td></td></tr>
<tr><td>static [`float SCurve5(float t)`](VRageMath.SCurve5)</td><td></td></tr>
<tr><td>static [`double SCurve5(double t)`](VRageMath.SCurve5)</td><td></td></tr>
<tr><td>static [`float Saturate(float n)`](VRageMath.Saturate)</td><td></td></tr>
<tr><td>static [`double Saturate(double n)`](VRageMath.Saturate)</td><td></td></tr>
<tr><td>static [`int Floor(float n)`](VRageMath.Floor)</td><td></td></tr>
<tr><td>static [`int Floor(double n)`](VRageMath.Floor)</td><td></td></tr>
<tr><td>static [`int Log2Floor(int value)`](VRageMath.Log2Floor)</td><td></td></tr>
<tr><td>static [`int Log2Ceiling(int value)`](VRageMath.Log2Ceiling)</td><td></td></tr>
<tr><td>static [`int Log2(int n)`](VRageMath.Log2)</td><td></td></tr>
<tr><td>static [`int Log2(uint n)`](VRageMath.Log2)</td><td></td></tr>
<tr><td>static [`int Pow2(int n)`](VRageMath.Pow2)</td><td>Returns 2^n</td></tr>
<tr><td>static [`double CubicInterp(double p0, double p1, double p2, double p3, double t)`](VRageMath.CubicInterp)</td><td></td></tr>
<tr><td>static [`void LimitRadians2PI(ref double angle)`](VRageMath.LimitRadians2PI)</td><td>Returns angle in range 0..2*PI</td></tr>
<tr><td>static [`void LimitRadians(ref float angle)`](VRageMath.LimitRadians)</td><td>Returns angle in range 0..2*PI</td></tr>
<tr><td>static [`void LimitRadiansPI(ref double angle)`](VRageMath.LimitRadiansPI)</td><td>Returns angle in range -PI..PI</td></tr>
<tr><td>static [`void LimitRadiansPI(ref float angle)`](VRageMath.LimitRadiansPI)</td><td>Returns angle in range -PI..PI</td></tr>
<tr><td>static [`Vector3 CalculateVectorOnSphere(Vector3 northPoleDir, float phi, float theta)`](VRageMath.CalculateVectorOnSphere)</td><td></td></tr>
<tr><td>static [`float MonotonicCosine(float radians)`](VRageMath.MonotonicCosine)</td><td>Calculate the monotonic cosine of a value. Monotonic cosine is an alternative cosine encoding that is monotonic in the [-pi, pi] interval. We use this when some parameter of an onject in a planet is constrained by latitude. The 'monotonicity' is guaranteed by subtracting the cosine value from 2 if the angle is positive. So for instance MonotonicCos(pi/2) = 2. This only works in the above interval of course.</td></tr>
<tr><td>static [`float MonotonicAcos(float cos)`](VRageMath.MonotonicAcos)</td><td></td></tr>
<tr><td>static [`float Atan(float x)`](VRageMath.Atan)</td><td>Faster Atan implementation. Good only in the [-pi/2, pi/2] range.</td></tr>
<tr><td>static [`double Atan(double x)`](VRageMath.Atan)</td><td>Faster Atan implementation. Good only in the [-pi/2, pi/2] range.</td></tr>
<tr><td>static [`bool IsEqual(float value1, float value2)`](VRageMath.IsEqual)</td><td></td></tr>
<tr><td>static [`bool IsEqual(Vector2 value1, Vector2 value2)`](VRageMath.IsEqual)</td><td></td></tr>
<tr><td>static [`bool IsEqual(Vector3 value1, Vector3 value2)`](VRageMath.IsEqual)</td><td></td></tr>
<tr><td>static [`bool IsEqual(Quaternion value1, Quaternion value2)`](VRageMath.IsEqual)</td><td></td></tr>
<tr><td>static [`bool IsEqual(QuaternionD value1, QuaternionD value2)`](VRageMath.IsEqual)</td><td></td></tr>
<tr><td>static [`bool IsEqual(Matrix value1, Matrix value2)`](VRageMath.IsEqual)</td><td></td></tr>
<tr><td>static [`bool IsValid(Matrix matrix)`](VRageMath.IsValid)</td><td></td></tr>
<tr><td>static [`bool IsValid(MatrixD matrix)`](VRageMath.IsValid)</td><td></td></tr>
<tr><td>static [`bool IsValid(Vector3 vec)`](VRageMath.IsValid)</td><td></td></tr>
<tr><td>static [`bool IsValid(Vector3D vec)`](VRageMath.IsValid)</td><td></td></tr>
<tr><td>static [`bool IsValid(Vector2 vec)`](VRageMath.IsValid)</td><td></td></tr>
<tr><td>static [`bool IsValid(float f)`](VRageMath.IsValid)</td><td></td></tr>
<tr><td>static [`bool IsValid(double f)`](VRageMath.IsValid)</td><td></td></tr>
<tr><td>static [`bool IsValid(Nullable<Vector3> vec)`](VRageMath.IsValid)</td><td></td></tr>
<tr><td>static [`bool IsValid(Quaternion q)`](VRageMath.IsValid)</td><td></td></tr>
<tr><td>static [`bool IsValidNormal(Vector3 vec)`](VRageMath.IsValidNormal)</td><td></td></tr>
<tr><td>static [`bool IsValidOrZero(Matrix matrix)`](VRageMath.IsValidOrZero)</td><td></td></tr>
<tr><td>static [`bool IsZero(float value, float epsilon)`](VRageMath.IsZero)</td><td></td></tr>
<tr><td>static [`bool IsZero(double value, float epsilon)`](VRageMath.IsZero)</td><td></td></tr>
<tr><td>static [`bool IsZero(Vector3 value, float epsilon)`](VRageMath.IsZero)</td><td></td></tr>
<tr><td>static [`bool IsZero(Vector3D value, float epsilon)`](VRageMath.IsZero)</td><td></td></tr>
<tr><td>static [`bool IsZero(Quaternion value, float epsilon)`](VRageMath.IsZero)</td><td></td></tr>
<tr><td>static [`bool IsZero(Vector4 value)`](VRageMath.IsZero)</td><td></td></tr>
<tr><td>static [`int Smooth(int newValue, int lastSmooth)`](VRageMath.Smooth)</td><td></td></tr>
<tr><td>static [`float Smooth(float newValue, float lastSmooth)`](VRageMath.Smooth)</td><td></td></tr>
</table>
