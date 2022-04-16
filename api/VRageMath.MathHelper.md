← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MathHelper Class

```csharp
public abstract sealed class MathHelper
```

Contains commonly used precalculated values.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

#### Fields

|Member|Description|
|---|---|
|[static float E](VRageMath.MathHelper.E)|Represents the mathematical constant e.|
|[static float EPSILON](VRageMath.MathHelper.EPSILON)||
|[static float EPSILON10](VRageMath.MathHelper.EPSILON10)||
|[static float FourPi](VRageMath.MathHelper.FourPi)|Represents the value of pi times two.|
|[static float Log10E](VRageMath.MathHelper.Log10E)|Represents the log base ten of e.|
|[static float Log2E](VRageMath.MathHelper.Log2E)|Represents the log base two of e.|
|[static float Pi](VRageMath.MathHelper.Pi)|Represents the value of pi.|
|[static float PiOver2](VRageMath.MathHelper.PiOver2)|Represents the value of pi divided by two.|
|[static float PiOver4](VRageMath.MathHelper.PiOver4)|Represents the value of pi divided by four.|
|[static float RadiansPerSecondToRPM](VRageMath.MathHelper.RadiansPerSecondToRPM)|60 / 2*pi|
|[static float RPMToRadiansPerMillisec](VRageMath.MathHelper.RPMToRadiansPerMillisec)|2*pi / 60000|
|[static float RPMToRadiansPerSecond](VRageMath.MathHelper.RPMToRadiansPerSecond)|2*pi / 60|
|[static float Sqrt2](VRageMath.MathHelper.Sqrt2)|Represents the value of the square root of two|
|[static float Sqrt3](VRageMath.MathHelper.Sqrt3)|Represents the value of the square root of three|
|[static float TwoPi](VRageMath.MathHelper.TwoPi)|Represents the value of pi times two.|

#### Methods

|Member|Description|
|---|---|
|[static int Align(int, int)](VRageMath.MathHelper.Align)||
|[static float Atan(float)](VRageMath.MathHelper.Atan)|Faster Atan implementation. Good only in the [-pi/2, pi/2] range.|
|[static double Atan(double)](VRageMath.MathHelper.Atan)|Faster Atan implementation. Good only in the [-pi/2, pi/2] range.|
|[static float Barycentric(float, float, float, float, float)](VRageMath.MathHelper.Barycentric)|Returns the Cartesian coordinate for one axis of a point that is defined by a given triangle and two normalized barycentric (areal) coordinates.|
|[static Vector3D CalculateBezierPoint(double, Vector3D, Vector3D, Vector3D, Vector3D)](VRageMath.MathHelper.CalculateBezierPoint)||
|[static Vector3 CalculateVectorOnSphere(Vector3, float, float)](VRageMath.MathHelper.CalculateVectorOnSphere)||
|[static float CatmullRom(float, float, float, float, float)](VRageMath.MathHelper.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|[static int CeilToInt(float)](VRageMath.MathHelper.CeilToInt)||
|[static int CeilToInt(double)](VRageMath.MathHelper.CeilToInt)||
|[static float Clamp(float, float, float)](VRageMath.MathHelper.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|[static double Clamp(double, double, double)](VRageMath.MathHelper.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|[static MyFixedPoint Clamp(MyFixedPoint, MyFixedPoint, MyFixedPoint)](VRageMath.MathHelper.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|[static int Clamp(int, int, int)](VRageMath.MathHelper.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|[static int ComputeHashFromBytes(Byte\[])](VRageMath.MathHelper.ComputeHashFromBytes)||
|[static double CubicInterp(double, double, double, double, double)](VRageMath.MathHelper.CubicInterp)||
|[static float Distance(float, float)](VRageMath.MathHelper.Distance)|Calculates the absolute value of the difference of two values.|
|[static int Floor(float)](VRageMath.MathHelper.Floor)||
|[static int Floor(double)](VRageMath.MathHelper.Floor)||
|[static int FloorToInt(float)](VRageMath.MathHelper.FloorToInt)||
|[static int FloorToInt(double)](VRageMath.MathHelper.FloorToInt)||
|[static int GetNearestBiggerPowerOfTwo(int)](VRageMath.MathHelper.GetNearestBiggerPowerOfTwo)||
|[static uint GetNearestBiggerPowerOfTwo(uint)](VRageMath.MathHelper.GetNearestBiggerPowerOfTwo)||
|[static int GetNearestBiggerPowerOfTwo(float)](VRageMath.MathHelper.GetNearestBiggerPowerOfTwo)|Returns nearest bigger power of two|
|[static int GetNearestBiggerPowerOfTwo(double)](VRageMath.MathHelper.GetNearestBiggerPowerOfTwo)||
|[static int GetNumberOfMipmaps(int)](VRageMath.MathHelper.GetNumberOfMipmaps)||
|[static float Hermite(float, float, float, float, float)](VRageMath.MathHelper.Hermite)|Performs a Hermite spline interpolation.|
|[static float InterpLog(float, float, float)](VRageMath.MathHelper.InterpLog)|Performs interpolation on logarithmic scale.|
|[static float InterpLogInv(float, float, float)](VRageMath.MathHelper.InterpLogInv)||
|[static bool IsEqual(float, float)](VRageMath.MathHelper.IsEqual)||
|[static bool IsEqual(Vector2, Vector2)](VRageMath.MathHelper.IsEqual)||
|[static bool IsEqual(Vector3, Vector3)](VRageMath.MathHelper.IsEqual)||
|[static bool IsEqual(Quaternion, Quaternion)](VRageMath.MathHelper.IsEqual)||
|[static bool IsEqual(QuaternionD, QuaternionD)](VRageMath.MathHelper.IsEqual)||
|[static bool IsEqual(Matrix, Matrix)](VRageMath.MathHelper.IsEqual)||
|[static bool IsPowerOfTwo(int)](VRageMath.MathHelper.IsPowerOfTwo)|Returns true if value is power of two|
|[static bool IsValid(Matrix)](VRageMath.MathHelper.IsValid)||
|[static bool IsValid(MatrixD)](VRageMath.MathHelper.IsValid)||
|[static bool IsValid(Vector3)](VRageMath.MathHelper.IsValid)||
|[static bool IsValid(Vector3D)](VRageMath.MathHelper.IsValid)||
|[static bool IsValid(Vector2)](VRageMath.MathHelper.IsValid)||
|[static bool IsValid(float)](VRageMath.MathHelper.IsValid)||
|[static bool IsValid(double)](VRageMath.MathHelper.IsValid)||
|[static bool IsValid(Vector3?)](VRageMath.MathHelper.IsValid)||
|[static bool IsValid(Quaternion)](VRageMath.MathHelper.IsValid)||
|[static bool IsValidNormal(Vector3)](VRageMath.MathHelper.IsValidNormal)||
|[static bool IsValidOrZero(Matrix)](VRageMath.MathHelper.IsValidOrZero)||
|[static bool IsZero(float, \[float])](VRageMath.MathHelper.IsZero)||
|[static bool IsZero(double, \[float])](VRageMath.MathHelper.IsZero)||
|[static bool IsZero(Vector3, \[float])](VRageMath.MathHelper.IsZero)||
|[static bool IsZero(Vector3D, \[float])](VRageMath.MathHelper.IsZero)||
|[static bool IsZero(Quaternion, \[float])](VRageMath.MathHelper.IsZero)||
|[static bool IsZero(Vector4)](VRageMath.MathHelper.IsZero)||
|[static float Lerp(float, float, float)](VRageMath.MathHelper.Lerp)|Linearly interpolates between two values.|
|[static double Lerp(double, double, double)](VRageMath.MathHelper.Lerp)|Linearly interpolates between two values.|
|[static void LimitRadians(ref float)](VRageMath.MathHelper.LimitRadians)|Returns angle in range 0..2*PI|
|[static void LimitRadians2PI(ref double)](VRageMath.MathHelper.LimitRadians2PI)|Returns angle in range 0..2*PI|
|[static void LimitRadiansPI(ref double)](VRageMath.MathHelper.LimitRadiansPI)|Returns angle in range -PI..PI|
|[static void LimitRadiansPI(ref float)](VRageMath.MathHelper.LimitRadiansPI)|Returns angle in range -PI..PI|
|[static int Log2(int)](VRageMath.MathHelper.Log2)||
|[static int Log2(uint)](VRageMath.MathHelper.Log2)||
|[static int Log2Ceiling(int)](VRageMath.MathHelper.Log2Ceiling)||
|[static int Log2Floor(int)](VRageMath.MathHelper.Log2Floor)||
|[static float Max(float, float)](VRageMath.MathHelper.Max)|Returns the greater of two values.|
|[static double Max(double, double)](VRageMath.MathHelper.Max)|Returns the greater of two values.|
|[static float Max(float, float, float)](VRageMath.MathHelper.Max)||
|[static int Max(int, int, int)](VRageMath.MathHelper.Max)||
|[static double Max(double, double, double)](VRageMath.MathHelper.Max)||
|[static float Min(float, float)](VRageMath.MathHelper.Min)|Returns the lesser of two values.|
|[static double Min(double, double)](VRageMath.MathHelper.Min)|Returns the lesser of two values.|
|[static float Min(float, float, float)](VRageMath.MathHelper.Min)||
|[static double Min(double, double, double)](VRageMath.MathHelper.Min)||
|[static float MonotonicAcos(float)](VRageMath.MathHelper.MonotonicAcos)||
|[static float MonotonicCosine(float)](VRageMath.MathHelper.MonotonicCosine)|Calculate the monotonic cosine of a value. Monotonic cosine is an alternative cosine encoding that is monotonic in the [-pi, pi] interval. We use this when some parameter of an onject in a planet is constrained by latitude. The 'monotonicity' is guaranteed by subtracting the cosine value from 2 if the angle is positive. So for instance MonotonicCos(pi/2) = 2. This only works in the above interval of course.|
|[static int Pow2(int)](VRageMath.MathHelper.Pow2)|Returns 2^n|
|[static float RoundOn2(float)](VRageMath.MathHelper.RoundOn2)||
|[static int RoundToInt(float)](VRageMath.MathHelper.RoundToInt)||
|[static int RoundToInt(double)](VRageMath.MathHelper.RoundToInt)||
|[static float Saturate(float)](VRageMath.MathHelper.Saturate)||
|[static double Saturate(double)](VRageMath.MathHelper.Saturate)||
|[static float SCurve3(float)](VRageMath.MathHelper.SCurve3)||
|[static double SCurve3(double)](VRageMath.MathHelper.SCurve3)||
|[static float SCurve5(float)](VRageMath.MathHelper.SCurve5)||
|[static double SCurve5(double)](VRageMath.MathHelper.SCurve5)||
|[static int Smooth(int, int)](VRageMath.MathHelper.Smooth)||
|[static float Smooth(float, float)](VRageMath.MathHelper.Smooth)||
|[static float SmoothStep(float, float, float)](VRageMath.MathHelper.SmoothStep)|Interpolates between two values using a cubic equation.|
|[static double SmoothStep(double, double, double)](VRageMath.MathHelper.SmoothStep)|Interpolates between two values using a cubic equation.|
|[static float SmoothStepStable(float)](VRageMath.MathHelper.SmoothStepStable)|Interpolates between zero and one using cubic equiation, solved by de Casteljau.|
|[static double SmoothStepStable(double)](VRageMath.MathHelper.SmoothStepStable)|Interpolates between zero and one using cubic equiation, solved by de Casteljau.|
|[static float ToDegrees(float)](VRageMath.MathHelper.ToDegrees)|Converts radians to degrees.|
|[static double ToDegrees(double)](VRageMath.MathHelper.ToDegrees)||
|[static float ToRadians(float)](VRageMath.MathHelper.ToRadians)|Converts degrees to radians.|
|[static Vector3 ToRadians(Vector3)](VRageMath.MathHelper.ToRadians)||
|[static double ToRadians(double)](VRageMath.MathHelper.ToRadians)|Converts degrees to radians.|
|[static float WrapAngle(float)](VRageMath.MathHelper.WrapAngle)|Reduces a given angle to a value between π and -π.|

