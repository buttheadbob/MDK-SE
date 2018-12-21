← [Index](index)
# MathHelper Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Contains commonly used precalculated values.
### Fields
|Member|Description|
|---|---|
|static [`float E`](VRageMath.E)|Represents the mathematical constant e.|
|static [`float Log2E`](VRageMath.Log2E)|Represents the log base two of e.|
|static [`float Log10E`](VRageMath.Log10E)|Represents the log base ten of e.|
|static [`float Pi`](VRageMath.Pi)|Represents the value of pi.|
|static [`float TwoPi`](VRageMath.TwoPi)|Represents the value of pi times two.|
|static [`float FourPi`](VRageMath.FourPi)|Represents the value of pi times two.|
|static [`float PiOver2`](VRageMath.PiOver2)|Represents the value of pi divided by two.|
|static [`float PiOver4`](VRageMath.PiOver4)|Represents the value of pi divided by four.|
|static [`float Sqrt2`](VRageMath.Sqrt2)|Represents the value of the square root of two|
|static [`float Sqrt3`](VRageMath.Sqrt3)|Represents the value of the square root of three|
|static [`float RadiansPerSecondToRPM`](VRageMath.RadiansPerSecondToRPM)|60 / 2*pi|
|static [`float RPMToRadiansPerSecond`](VRageMath.RPMToRadiansPerSecond)|2*pi / 60|
|static [`float RPMToRadiansPerMillisec`](VRageMath.RPMToRadiansPerMillisec)|2*pi / 60000|
|static [`float EPSILON`](VRageMath.EPSILON)||
|static [`float EPSILON10`](VRageMath.EPSILON10)||
### Methods
|Member|Description|
|---|---|
|static [`float ToRadians(float degrees)`](VRageMath.ToRadians)|Converts degrees to radians.|
|static [`Vector3 ToRadians(Vector3 v)`](VRageMath.ToRadians)||
|static [`double ToRadians(double degrees)`](VRageMath.ToRadians)|Converts degrees to radians.|
|static [`float ToDegrees(float radians)`](VRageMath.ToDegrees)|Converts radians to degrees.|
|static [`double ToDegrees(double radians)`](VRageMath.ToDegrees)||
|static [`float Distance(float value1, float value2)`](VRageMath.Distance)|Calculates the absolute value of the difference of two values.|
|static [`float Min(float value1, float value2)`](VRageMath.Min)|Returns the lesser of two values.|
|static [`float Max(float value1, float value2)`](VRageMath.Max)|Returns the greater of two values.|
|static [`double Min(double value1, double value2)`](VRageMath.Min)|Returns the lesser of two values.|
|static [`double Max(double value1, double value2)`](VRageMath.Max)|Returns the greater of two values.|
|static [`float Clamp(float value, float min, float max)`](VRageMath.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|static [`double Clamp(double value, double min, double max)`](VRageMath.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|static [`MyFixedPoint Clamp(MyFixedPoint value, MyFixedPoint min, MyFixedPoint max)`](VRageMath.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|static [`int Clamp(int value, int min, int max)`](VRageMath.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|static [`float Lerp(float value1, float value2, float amount)`](VRageMath.Lerp)|Linearly interpolates between two values.|
|static [`double Lerp(double value1, double value2, double amount)`](VRageMath.Lerp)|Linearly interpolates between two values.|
|static [`float InterpLog(float value, float amount1, float amount2)`](VRageMath.InterpLog)|Performs interpolation on logarithmic scale.|
|static [`float InterpLogInv(float value, float amount1, float amount2)`](VRageMath.InterpLogInv)||
|static [`float Barycentric(float value1, float value2, float value3, float amount1, float amount2)`](VRageMath.Barycentric)|Returns the Cartesian coordinate for one axis of a point that is defined by a given triangle and two normalized barycentric (areal) coordinates.|
|static [`float SmoothStep(float value1, float value2, float amount)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`double SmoothStep(double value1, double value2, double amount)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`float SmoothStepStable(float amount)`](VRageMath.SmoothStepStable)|Interpolates between zero and one using cubic equiation, solved by de Casteljau.|
|static [`double SmoothStepStable(double amount)`](VRageMath.SmoothStepStable)|Interpolates between zero and one using cubic equiation, solved by de Casteljau.|
|static [`float CatmullRom(float value1, float value2, float value3, float value4, float amount)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`float Hermite(float value1, float tangent1, float value2, float tangent2, float amount)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`Vector3D CalculateBezierPoint(double t, Vector3D p0, Vector3D p1, Vector3D p2, Vector3D p3)`](VRageMath.CalculateBezierPoint)||
|static [`float WrapAngle(float angle)`](VRageMath.WrapAngle)|Reduces a given angle to a value between π and -π.|
|static [`int GetNearestBiggerPowerOfTwo(int v)`](VRageMath.GetNearestBiggerPowerOfTwo)||
|static [`uint GetNearestBiggerPowerOfTwo(uint v)`](VRageMath.GetNearestBiggerPowerOfTwo)||
|static [`int GetNumberOfMipmaps(int v)`](VRageMath.GetNumberOfMipmaps)||
|static [`int GetNearestBiggerPowerOfTwo(float f)`](VRageMath.GetNearestBiggerPowerOfTwo)|Returns nearest bigger power of two|
|static [`int GetNearestBiggerPowerOfTwo(double f)`](VRageMath.GetNearestBiggerPowerOfTwo)||
|static [`float Max(float a, float b, float c)`](VRageMath.Max)||
|static [`int Max(int a, int b, int c)`](VRageMath.Max)||
|static [`float Min(float a, float b, float c)`](VRageMath.Min)||
|static [`double Max(double a, double b, double c)`](VRageMath.Max)||
|static [`double Min(double a, double b, double c)`](VRageMath.Min)||
|static [`int ComputeHashFromBytes(Byte[] bytes)`](VRageMath.ComputeHashFromBytes)||
|static [`float RoundOn2(float x)`](VRageMath.RoundOn2)||
|static [`bool IsPowerOfTwo(int x)`](VRageMath.IsPowerOfTwo)|Returns true if value is power of two|
|static [`float SCurve3(float t)`](VRageMath.SCurve3)||
|static [`double SCurve3(double t)`](VRageMath.SCurve3)||
|static [`float SCurve5(float t)`](VRageMath.SCurve5)||
|static [`double SCurve5(double t)`](VRageMath.SCurve5)||
|static [`float Saturate(float n)`](VRageMath.Saturate)||
|static [`double Saturate(double n)`](VRageMath.Saturate)||
|static [`int Floor(float n)`](VRageMath.Floor)||
|static [`int Floor(double n)`](VRageMath.Floor)||
|static [`int Log2Floor(int value)`](VRageMath.Log2Floor)||
|static [`int Log2Ceiling(int value)`](VRageMath.Log2Ceiling)||
|static [`int Log2(int n)`](VRageMath.Log2)||
|static [`int Log2(uint n)`](VRageMath.Log2)||
|static [`int Pow2(int n)`](VRageMath.Pow2)|Returns 2^n|
|static [`double CubicInterp(double p0, double p1, double p2, double p3, double t)`](VRageMath.CubicInterp)||
|static [`void LimitRadians2PI(ref double angle)`](VRageMath.LimitRadians2PI)|Returns angle in range 0..2*PI|
|static [`void LimitRadians(ref float angle)`](VRageMath.LimitRadians)|Returns angle in range 0..2*PI|
|static [`void LimitRadiansPI(ref double angle)`](VRageMath.LimitRadiansPI)|Returns angle in range -PI..PI|
|static [`void LimitRadiansPI(ref float angle)`](VRageMath.LimitRadiansPI)|Returns angle in range -PI..PI|
|static [`Vector3 CalculateVectorOnSphere(Vector3 northPoleDir, float phi, float theta)`](VRageMath.CalculateVectorOnSphere)||
|static [`float MonotonicCosine(float radians)`](VRageMath.MonotonicCosine)|Calculate the monotonic cosine of a value. Monotonic cosine is an alternative cosine encoding that is monotonic in the [-pi, pi] interval. We use this when some parameter of an onject in a planet is constrained by latitude. The 'monotonicity' is guaranteed by subtracting the cosine value from 2 if the angle is positive. So for instance MonotonicCos(pi/2) = 2. This only works in the above interval of course.|
|static [`float MonotonicAcos(float cos)`](VRageMath.MonotonicAcos)||
|static [`float Atan(float x)`](VRageMath.Atan)|Faster Atan implementation. Good only in the [-pi/2, pi/2] range.|
|static [`double Atan(double x)`](VRageMath.Atan)|Faster Atan implementation. Good only in the [-pi/2, pi/2] range.|
|static [`bool IsEqual(float value1, float value2)`](VRageMath.IsEqual)||
|static [`bool IsEqual(Vector2 value1, Vector2 value2)`](VRageMath.IsEqual)||
|static [`bool IsEqual(Vector3 value1, Vector3 value2)`](VRageMath.IsEqual)||
|static [`bool IsEqual(Quaternion value1, Quaternion value2)`](VRageMath.IsEqual)||
|static [`bool IsEqual(QuaternionD value1, QuaternionD value2)`](VRageMath.IsEqual)||
|static [`bool IsEqual(Matrix value1, Matrix value2)`](VRageMath.IsEqual)||
|static [`bool IsValid(Matrix matrix)`](VRageMath.IsValid)||
|static [`bool IsValid(MatrixD matrix)`](VRageMath.IsValid)||
|static [`bool IsValid(Vector3 vec)`](VRageMath.IsValid)||
|static [`bool IsValid(Vector3D vec)`](VRageMath.IsValid)||
|static [`bool IsValid(Vector2 vec)`](VRageMath.IsValid)||
|static [`bool IsValid(float f)`](VRageMath.IsValid)||
|static [`bool IsValid(double f)`](VRageMath.IsValid)||
|static [`bool IsValid(Nullable<Vector3> vec)`](VRageMath.IsValid)||
|static [`bool IsValid(Quaternion q)`](VRageMath.IsValid)||
|static [`bool IsValidNormal(Vector3 vec)`](VRageMath.IsValidNormal)||
|static [`bool IsValidOrZero(Matrix matrix)`](VRageMath.IsValidOrZero)||
|static [`bool IsZero(float value, float epsilon)`](VRageMath.IsZero)||
|static [`bool IsZero(double value, float epsilon)`](VRageMath.IsZero)||
|static [`bool IsZero(Vector3 value, float epsilon)`](VRageMath.IsZero)||
|static [`bool IsZero(Vector3D value, float epsilon)`](VRageMath.IsZero)||
|static [`bool IsZero(Quaternion value, float epsilon)`](VRageMath.IsZero)||
|static [`bool IsZero(Vector4 value)`](VRageMath.IsZero)||
|static [`int Smooth(int newValue, int lastSmooth)`](VRageMath.Smooth)||
|static [`float Smooth(float newValue, float lastSmooth)`](VRageMath.Smooth)||
