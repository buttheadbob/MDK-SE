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
|\$1static float E](VRageMath.MathHelper.E)|Represents the mathematical constant e.|
|\$1static float EPSILON](VRageMath.MathHelper.EPSILON)||
|\$1static float EPSILON10](VRageMath.MathHelper.EPSILON10)||
|\$1static float FourPi](VRageMath.MathHelper.FourPi)|Represents the value of pi times two.|
|\$1static float Log10E](VRageMath.MathHelper.Log10E)|Represents the log base ten of e.|
|\$1static float Log2E](VRageMath.MathHelper.Log2E)|Represents the log base two of e.|
|\$1static float Pi](VRageMath.MathHelper.Pi)|Represents the value of pi.|
|\$1static float PiOver2](VRageMath.MathHelper.PiOver2)|Represents the value of pi divided by two.|
|\$1static float PiOver4](VRageMath.MathHelper.PiOver4)|Represents the value of pi divided by four.|
|\$1static float RadiansPerSecondToRPM](VRageMath.MathHelper.RadiansPerSecondToRPM)|60 / 2*pi|
|\$1static float RPMToRadiansPerMillisec](VRageMath.MathHelper.RPMToRadiansPerMillisec)|2*pi / 60000|
|\$1static float RPMToRadiansPerSecond](VRageMath.MathHelper.RPMToRadiansPerSecond)|2*pi / 60|
|\$1static float Sqrt2](VRageMath.MathHelper.Sqrt2)|Represents the value of the square root of two|
|\$1static float Sqrt3](VRageMath.MathHelper.Sqrt3)|Represents the value of the square root of three|
|\$1static float TwoPi](VRageMath.MathHelper.TwoPi)|Represents the value of pi times two.|

#### Methods

|Member|Description|
|---|---|
|\$1static int Align(int, int)](VRageMath.MathHelper.Align)||
|\$1static float Atan(float)](VRageMath.MathHelper.Atan)|Faster Atan implementation. Good only in the [-pi/2, pi/2] range.|
|\$1static double Atan(double)](VRageMath.MathHelper.Atan)|Faster Atan implementation. Good only in the [-pi/2, pi/2] range.|
|\$1static float Barycentric(float, float, float, float, float)](VRageMath.MathHelper.Barycentric)|Returns the Cartesian coordinate for one axis of a point that is defined by a given triangle and two normalized barycentric (areal) coordinates.|
|\$1static Vector3D CalculateBezierPoint(double, Vector3D, Vector3D, Vector3D, Vector3D)](VRageMath.MathHelper.CalculateBezierPoint)||
|\$1static Vector3 CalculateVectorOnSphere(Vector3, float, float)](VRageMath.MathHelper.CalculateVectorOnSphere)||
|\$1static float CatmullRom(float, float, float, float, float)](VRageMath.MathHelper.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|\$1static int CeilToInt(float)](VRageMath.MathHelper.CeilToInt)||
|\$1static int CeilToInt(double)](VRageMath.MathHelper.CeilToInt)||
|\$1static float Clamp(float, float, float)](VRageMath.MathHelper.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|\$1static double Clamp(double, double, double)](VRageMath.MathHelper.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|\$1static MyFixedPoint Clamp(MyFixedPoint, MyFixedPoint, MyFixedPoint)](VRageMath.MathHelper.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|\$1static int Clamp(int, int, int)](VRageMath.MathHelper.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|\$1static int ComputeHashFromBytes(Byte\$1])](VRageMath.MathHelper.ComputeHashFromBytes)||
|\$1static double CubicInterp(double, double, double, double, double)](VRageMath.MathHelper.CubicInterp)||
|\$1static float Distance(float, float)](VRageMath.MathHelper.Distance)|Calculates the absolute value of the difference of two values.|
|\$1static int Floor(float)](VRageMath.MathHelper.Floor)||
|\$1static int Floor(double)](VRageMath.MathHelper.Floor)||
|\$1static int FloorToInt(float)](VRageMath.MathHelper.FloorToInt)||
|\$1static int FloorToInt(double)](VRageMath.MathHelper.FloorToInt)||
|\$1static int GetNearestBiggerPowerOfTwo(int)](VRageMath.MathHelper.GetNearestBiggerPowerOfTwo)||
|\$1static uint GetNearestBiggerPowerOfTwo(uint)](VRageMath.MathHelper.GetNearestBiggerPowerOfTwo)||
|\$1static int GetNearestBiggerPowerOfTwo(float)](VRageMath.MathHelper.GetNearestBiggerPowerOfTwo)|Returns nearest bigger power of two|
|\$1static int GetNearestBiggerPowerOfTwo(double)](VRageMath.MathHelper.GetNearestBiggerPowerOfTwo)||
|\$1static int GetNumberOfMipmaps(int)](VRageMath.MathHelper.GetNumberOfMipmaps)||
|\$1static float Hermite(float, float, float, float, float)](VRageMath.MathHelper.Hermite)|Performs a Hermite spline interpolation.|
|\$1static float InterpLog(float, float, float)](VRageMath.MathHelper.InterpLog)|Performs interpolation on logarithmic scale.|
|\$1static float InterpLogInv(float, float, float)](VRageMath.MathHelper.InterpLogInv)||
|\$1static bool IsEqual(float, float)](VRageMath.MathHelper.IsEqual)||
|\$1static bool IsEqual(Vector2, Vector2)](VRageMath.MathHelper.IsEqual)||
|\$1static bool IsEqual(Vector3, Vector3)](VRageMath.MathHelper.IsEqual)||
|\$1static bool IsEqual(Quaternion, Quaternion)](VRageMath.MathHelper.IsEqual)||
|\$1static bool IsEqual(QuaternionD, QuaternionD)](VRageMath.MathHelper.IsEqual)||
|\$1static bool IsEqual(Matrix, Matrix)](VRageMath.MathHelper.IsEqual)||
|\$1static bool IsPowerOfTwo(int)](VRageMath.MathHelper.IsPowerOfTwo)|Returns true if value is power of two|
|\$1static bool IsValid(Matrix)](VRageMath.MathHelper.IsValid)||
|\$1static bool IsValid(MatrixD)](VRageMath.MathHelper.IsValid)||
|\$1static bool IsValid(Vector3)](VRageMath.MathHelper.IsValid)||
|\$1static bool IsValid(Vector3D)](VRageMath.MathHelper.IsValid)||
|\$1static bool IsValid(Vector2)](VRageMath.MathHelper.IsValid)||
|\$1static bool IsValid(float)](VRageMath.MathHelper.IsValid)||
|\$1static bool IsValid(double)](VRageMath.MathHelper.IsValid)||
|\$1static bool IsValid(Vector3?)](VRageMath.MathHelper.IsValid)||
|\$1static bool IsValid(Quaternion)](VRageMath.MathHelper.IsValid)||
|\$1static bool IsValidNormal(Vector3)](VRageMath.MathHelper.IsValidNormal)||
|\$1static bool IsValidOrZero(Matrix)](VRageMath.MathHelper.IsValidOrZero)||
|\$1static bool IsZero(float, \$1float])](VRageMath.MathHelper.IsZero)||
|\$1static bool IsZero(double, \$1float])](VRageMath.MathHelper.IsZero)||
|\$1static bool IsZero(Vector3, \$1float])](VRageMath.MathHelper.IsZero)||
|\$1static bool IsZero(Vector3D, \$1float])](VRageMath.MathHelper.IsZero)||
|\$1static bool IsZero(Quaternion, \$1float])](VRageMath.MathHelper.IsZero)||
|\$1static bool IsZero(Vector4)](VRageMath.MathHelper.IsZero)||
|\$1static float Lerp(float, float, float)](VRageMath.MathHelper.Lerp)|Linearly interpolates between two values.|
|\$1static double Lerp(double, double, double)](VRageMath.MathHelper.Lerp)|Linearly interpolates between two values.|
|\$1static void LimitRadians(ref float)](VRageMath.MathHelper.LimitRadians)|Returns angle in range 0..2*PI|
|\$1static void LimitRadians2PI(ref double)](VRageMath.MathHelper.LimitRadians2PI)|Returns angle in range 0..2*PI|
|\$1static void LimitRadiansPI(ref double)](VRageMath.MathHelper.LimitRadiansPI)|Returns angle in range -PI..PI|
|\$1static void LimitRadiansPI(ref float)](VRageMath.MathHelper.LimitRadiansPI)|Returns angle in range -PI..PI|
|\$1static int Log2(int)](VRageMath.MathHelper.Log2)||
|\$1static int Log2(uint)](VRageMath.MathHelper.Log2)||
|\$1static int Log2Ceiling(int)](VRageMath.MathHelper.Log2Ceiling)||
|\$1static int Log2Floor(int)](VRageMath.MathHelper.Log2Floor)||
|\$1static float Max(float, float)](VRageMath.MathHelper.Max)|Returns the greater of two values.|
|\$1static double Max(double, double)](VRageMath.MathHelper.Max)|Returns the greater of two values.|
|\$1static float Max(float, float, float)](VRageMath.MathHelper.Max)||
|\$1static int Max(int, int, int)](VRageMath.MathHelper.Max)||
|\$1static double Max(double, double, double)](VRageMath.MathHelper.Max)||
|\$1static float Min(float, float)](VRageMath.MathHelper.Min)|Returns the lesser of two values.|
|\$1static double Min(double, double)](VRageMath.MathHelper.Min)|Returns the lesser of two values.|
|\$1static float Min(float, float, float)](VRageMath.MathHelper.Min)||
|\$1static double Min(double, double, double)](VRageMath.MathHelper.Min)||
|\$1static float MonotonicAcos(float)](VRageMath.MathHelper.MonotonicAcos)||
|\$1static float MonotonicCosine(float)](VRageMath.MathHelper.MonotonicCosine)|Calculate the monotonic cosine of a value. Monotonic cosine is an alternative cosine encoding that is monotonic in the [-pi, pi] interval. We use this when some parameter of an onject in a planet is constrained by latitude. The 'monotonicity' is guaranteed by subtracting the cosine value from 2 if the angle is positive. So for instance MonotonicCos(pi/2) = 2. This only works in the above interval of course.|
|\$1static int Pow2(int)](VRageMath.MathHelper.Pow2)|Returns 2^n|
|\$1static float RoundOn2(float)](VRageMath.MathHelper.RoundOn2)||
|\$1static int RoundToInt(float)](VRageMath.MathHelper.RoundToInt)||
|\$1static int RoundToInt(double)](VRageMath.MathHelper.RoundToInt)||
|\$1static float Saturate(float)](VRageMath.MathHelper.Saturate)||
|\$1static double Saturate(double)](VRageMath.MathHelper.Saturate)||
|\$1static float SCurve3(float)](VRageMath.MathHelper.SCurve3)||
|\$1static double SCurve3(double)](VRageMath.MathHelper.SCurve3)||
|\$1static float SCurve5(float)](VRageMath.MathHelper.SCurve5)||
|\$1static double SCurve5(double)](VRageMath.MathHelper.SCurve5)||
|\$1static int Smooth(int, int)](VRageMath.MathHelper.Smooth)||
|\$1static float Smooth(float, float)](VRageMath.MathHelper.Smooth)||
|\$1static float SmoothStep(float, float, float)](VRageMath.MathHelper.SmoothStep)|Interpolates between two values using a cubic equation.|
|\$1static double SmoothStep(double, double, double)](VRageMath.MathHelper.SmoothStep)|Interpolates between two values using a cubic equation.|
|\$1static float SmoothStepStable(float)](VRageMath.MathHelper.SmoothStepStable)|Interpolates between zero and one using cubic equiation, solved by de Casteljau.|
|\$1static double SmoothStepStable(double)](VRageMath.MathHelper.SmoothStepStable)|Interpolates between zero and one using cubic equiation, solved by de Casteljau.|
|\$1static float ToDegrees(float)](VRageMath.MathHelper.ToDegrees)|Converts radians to degrees.|
|\$1static double ToDegrees(double)](VRageMath.MathHelper.ToDegrees)||
|\$1static float ToRadians(float)](VRageMath.MathHelper.ToRadians)|Converts degrees to radians.|
|\$1static Vector3 ToRadians(Vector3)](VRageMath.MathHelper.ToRadians)||
|\$1static double ToRadians(double)](VRageMath.MathHelper.ToRadians)|Converts degrees to radians.|
|\$1static float WrapAngle(float)](VRageMath.MathHelper.WrapAngle)|Reduces a given angle to a value between π and -π.|

