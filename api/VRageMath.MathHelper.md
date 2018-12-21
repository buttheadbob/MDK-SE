← [Index](index)
# MathHelper Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Contains commonly used precalculated values.
### Fields
|Member|Description|
|---|---|
|static [`float E`](VRageMath.E)|Represents the mathematical constant e.|
|static [`float Log2E`](VRageMath.Log2E)|Represents the log base two of e.|
|static [`float Log10E`](VRageMath.Log10E)|Represents the log base ten of e.|
|static [`float Pi`](VRageMath.Pi)|Represents the value of pi.|
|static [`float TwoPi`](VRageMath.TwoPi)|Represents the value of pi times two.|
|static [`float FourPi`](VRageMath.FourPi)|Represents the value of pi times two.|
|static [`float PiOver2`](VRageMath.PiOver2)|Represents the value of pi divided by two.|
|static [`float PiOver4`](VRageMath.PiOver4)|Represents the value of pi divided by four.|
|static [`float Sqrt2`](VRageMath.Sqrt2)|Represents the value of the square root of two|
|static [`float Sqrt3`](VRageMath.Sqrt3)|Represents the value of the square root of three|
|static [`float RadiansPerSecondToRPM`](VRageMath.RadiansPerSecondToRPM)|60 / 2*pi|
|static [`float RPMToRadiansPerSecond`](VRageMath.RPMToRadiansPerSecond)|2*pi / 60|
|static [`float RPMToRadiansPerMillisec`](VRageMath.RPMToRadiansPerMillisec)|2*pi / 60000|
|static [`float EPSILON`](VRageMath.EPSILON)||
|static [`float EPSILON10`](VRageMath.EPSILON10)||
### Methods
|Member|Description|
|---|---|
|static [`float ToRadians(float)`](VRageMath.ToRadians)|Converts degrees to radians.|
|static [`VRageMath.Vector3 ToRadians(VRageMath.Vector3)`](VRageMath.ToRadians)||
|static [`double ToRadians(double)`](VRageMath.ToRadians)|Converts degrees to radians.|
|static [`float ToDegrees(float)`](VRageMath.ToDegrees)|Converts radians to degrees.|
|static [`double ToDegrees(double)`](VRageMath.ToDegrees)||
|static [`float Distance(float, float)`](VRageMath.Distance)|Calculates the absolute value of the difference of two values.|
|static [`float Min(float, float)`](VRageMath.Min)|Returns the lesser of two values.|
|static [`float Max(float, float)`](VRageMath.Max)|Returns the greater of two values.|
|static [`double Min(double, double)`](VRageMath.Min)|Returns the lesser of two values.|
|static [`double Max(double, double)`](VRageMath.Max)|Returns the greater of two values.|
|static [`float Clamp(float, float, float)`](VRageMath.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|static [`double Clamp(double, double, double)`](VRageMath.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|static [`VRage.MyFixedPoint Clamp(VRage.MyFixedPoint, VRage.MyFixedPoint, VRage.MyFixedPoint)`](VRageMath.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|static [`int Clamp(int, int, int)`](VRageMath.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|static [`float Lerp(float, float, float)`](VRageMath.Lerp)|Linearly interpolates between two values.|
|static [`double Lerp(double, double, double)`](VRageMath.Lerp)|Linearly interpolates between two values.|
|static [`float InterpLog(float, float, float)`](VRageMath.InterpLog)|Performs interpolation on logarithmic scale.|
|static [`float InterpLogInv(float, float, float)`](VRageMath.InterpLogInv)||
|static [`float Barycentric(float, float, float, float, float)`](VRageMath.Barycentric)|Returns the Cartesian coordinate for one axis of a point that is defined by a given triangle and two normalized barycentric (areal) coordinates.|
|static [`float SmoothStep(float, float, float)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`double SmoothStep(double, double, double)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`float SmoothStepStable(float)`](VRageMath.SmoothStepStable)|Interpolates between zero and one using cubic equiation, solved by de Casteljau.|
|static [`double SmoothStepStable(double)`](VRageMath.SmoothStepStable)|Interpolates between zero and one using cubic equiation, solved by de Casteljau.|
|static [`float CatmullRom(float, float, float, float, float)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`float Hermite(float, float, float, float, float)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`VRageMath.Vector3D CalculateBezierPoint(double, VRageMath.Vector3D, VRageMath.Vector3D, VRageMath.Vector3D, VRageMath.Vector3D)`](VRageMath.CalculateBezierPoint)||
|static [`float WrapAngle(float)`](VRageMath.WrapAngle)|Reduces a given angle to a value between π and -π.|
|static [`int GetNearestBiggerPowerOfTwo(int)`](VRageMath.GetNearestBiggerPowerOfTwo)||
|static [`uint GetNearestBiggerPowerOfTwo(uint)`](VRageMath.GetNearestBiggerPowerOfTwo)||
|static [`int GetNumberOfMipmaps(int)`](VRageMath.GetNumberOfMipmaps)||
|static [`int GetNearestBiggerPowerOfTwo(float)`](VRageMath.GetNearestBiggerPowerOfTwo)|Returns nearest bigger power of two|
|static [`int GetNearestBiggerPowerOfTwo(double)`](VRageMath.GetNearestBiggerPowerOfTwo)||
|static [`float Max(float, float, float)`](VRageMath.Max)||
|static [`int Max(int, int, int)`](VRageMath.Max)||
|static [`float Min(float, float, float)`](VRageMath.Min)||
|static [`double Max(double, double, double)`](VRageMath.Max)||
|static [`double Min(double, double, double)`](VRageMath.Min)||
|static [`int ComputeHashFromBytes(System.Byte[])`](VRageMath.ComputeHashFromBytes)||
|static [`float RoundOn2(float)`](VRageMath.RoundOn2)||
|static [`bool IsPowerOfTwo(int)`](VRageMath.IsPowerOfTwo)|Returns true if value is power of two|
|static [`float SCurve3(float)`](VRageMath.SCurve3)||
|static [`double SCurve3(double)`](VRageMath.SCurve3)||
|static [`float SCurve5(float)`](VRageMath.SCurve5)||
|static [`double SCurve5(double)`](VRageMath.SCurve5)||
|static [`float Saturate(float)`](VRageMath.Saturate)||
|static [`double Saturate(double)`](VRageMath.Saturate)||
|static [`int Floor(float)`](VRageMath.Floor)||
|static [`int Floor(double)`](VRageMath.Floor)||
|static [`int Log2Floor(int)`](VRageMath.Log2Floor)||
|static [`int Log2Ceiling(int)`](VRageMath.Log2Ceiling)||
|static [`int Log2(int)`](VRageMath.Log2)||
|static [`int Log2(uint)`](VRageMath.Log2)||
|static [`int Pow2(int)`](VRageMath.Pow2)|Returns 2^n|
|static [`double CubicInterp(double, double, double, double, double)`](VRageMath.CubicInterp)||
|static [`void LimitRadians2PI(ref double)`](VRageMath.LimitRadians2PI)|Returns angle in range 0..2*PI|
|static [`void LimitRadians(ref float)`](VRageMath.LimitRadians)|Returns angle in range 0..2*PI|
|static [`void LimitRadiansPI(ref double)`](VRageMath.LimitRadiansPI)|Returns angle in range -PI..PI|
|static [`void LimitRadiansPI(ref float)`](VRageMath.LimitRadiansPI)|Returns angle in range -PI..PI|
|static [`VRageMath.Vector3 CalculateVectorOnSphere(VRageMath.Vector3, float, float)`](VRageMath.CalculateVectorOnSphere)||
|static [`float MonotonicCosine(float)`](VRageMath.MonotonicCosine)|Calculate the monotonic cosine of a value. Monotonic cosine is an alternative cosine encoding that is monotonic in the [-pi, pi] interval. We use this when some parameter of an onject in a planet is constrained by latitude. The 'monotonicity' is guaranteed by subtracting the cosine value from 2 if the angle is positive. So for instance MonotonicCos(pi/2) = 2. This only works in the above interval of course.|
|static [`float MonotonicAcos(float)`](VRageMath.MonotonicAcos)||
|static [`float Atan(float)`](VRageMath.Atan)|Faster Atan implementation. Good only in the [-pi/2, pi/2] range.|
|static [`double Atan(double)`](VRageMath.Atan)|Faster Atan implementation. Good only in the [-pi/2, pi/2] range.|
|static [`bool IsEqual(float, float)`](VRageMath.IsEqual)||
|static [`bool IsEqual(VRageMath.Vector2, VRageMath.Vector2)`](VRageMath.IsEqual)||
|static [`bool IsEqual(VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.IsEqual)||
|static [`bool IsEqual(VRageMath.Quaternion, VRageMath.Quaternion)`](VRageMath.IsEqual)||
|static [`bool IsEqual(VRageMath.QuaternionD, VRageMath.QuaternionD)`](VRageMath.IsEqual)||
|static [`bool IsEqual(VRageMath.Matrix, VRageMath.Matrix)`](VRageMath.IsEqual)||
|static [`bool IsValid(VRageMath.Matrix)`](VRageMath.IsValid)||
|static [`bool IsValid(VRageMath.MatrixD)`](VRageMath.IsValid)||
|static [`bool IsValid(VRageMath.Vector3)`](VRageMath.IsValid)||
|static [`bool IsValid(VRageMath.Vector3D)`](VRageMath.IsValid)||
|static [`bool IsValid(VRageMath.Vector2)`](VRageMath.IsValid)||
|static [`bool IsValid(float)`](VRageMath.IsValid)||
|static [`bool IsValid(double)`](VRageMath.IsValid)||
|static [`bool IsValid(Nullable<VRageMath.Vector3>)`](VRageMath.IsValid)||
|static [`bool IsValid(VRageMath.Quaternion)`](VRageMath.IsValid)||
|static [`bool IsValidNormal(VRageMath.Vector3)`](VRageMath.IsValidNormal)||
|static [`bool IsValidOrZero(VRageMath.Matrix)`](VRageMath.IsValidOrZero)||
|static [`bool IsZero(float, float)`](VRageMath.IsZero)||
|static [`bool IsZero(double, float)`](VRageMath.IsZero)||
|static [`bool IsZero(VRageMath.Vector3, float)`](VRageMath.IsZero)||
|static [`bool IsZero(VRageMath.Vector3D, float)`](VRageMath.IsZero)||
|static [`bool IsZero(VRageMath.Quaternion, float)`](VRageMath.IsZero)||
|static [`bool IsZero(VRageMath.Vector4)`](VRageMath.IsZero)||
|static [`int Smooth(int, int)`](VRageMath.Smooth)||
|static [`float Smooth(float, float)`](VRageMath.Smooth)||
