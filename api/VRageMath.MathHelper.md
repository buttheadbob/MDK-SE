← [Index](index)
# MathHelper Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Contains commonly used precalculated values.
### Fields
|Member|Description|
|---|---|
|[`E`](VRageMath.E)|Represents the mathematical constant e.|
|[`Log2E`](VRageMath.Log2E)|Represents the log base two of e.|
|[`Log10E`](VRageMath.Log10E)|Represents the log base ten of e.|
|[`Pi`](VRageMath.Pi)|Represents the value of pi.|
|[`TwoPi`](VRageMath.TwoPi)|Represents the value of pi times two.|
|[`FourPi`](VRageMath.FourPi)|Represents the value of pi times two.|
|[`PiOver2`](VRageMath.PiOver2)|Represents the value of pi divided by two.|
|[`PiOver4`](VRageMath.PiOver4)|Represents the value of pi divided by four.|
|[`Sqrt2`](VRageMath.Sqrt2)|Represents the value of the square root of two|
|[`Sqrt3`](VRageMath.Sqrt3)|Represents the value of the square root of three|
|[`RadiansPerSecondToRPM`](VRageMath.RadiansPerSecondToRPM)|60 / 2*pi|
|[`RPMToRadiansPerSecond`](VRageMath.RPMToRadiansPerSecond)|2*pi / 60|
|[`RPMToRadiansPerMillisec`](VRageMath.RPMToRadiansPerMillisec)|2*pi / 60000|
|[`EPSILON`](VRageMath.EPSILON)||
|[`EPSILON10`](VRageMath.EPSILON10)||
### Methods
|Member|Description|
|---|---|
|[`ToRadians(float)`](VRageMath.ToRadians)|Converts degrees to radians.|
|[`ToRadians(Vector3)`](VRageMath.ToRadians)||
|[`ToRadians(double)`](VRageMath.ToRadians)|Converts degrees to radians.|
|[`ToDegrees(float)`](VRageMath.ToDegrees)|Converts radians to degrees.|
|[`ToDegrees(double)`](VRageMath.ToDegrees)||
|[`Distance(float, float)`](VRageMath.Distance)|Calculates the absolute value of the difference of two values.|
|[`Min(float, float)`](VRageMath.Min)|Returns the lesser of two values.|
|[`Max(float, float)`](VRageMath.Max)|Returns the greater of two values.|
|[`Min(double, double)`](VRageMath.Min)|Returns the lesser of two values.|
|[`Max(double, double)`](VRageMath.Max)|Returns the greater of two values.|
|[`Clamp(float, float, float)`](VRageMath.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|[`Clamp(double, double, double)`](VRageMath.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|[`Clamp(MyFixedPoint, MyFixedPoint, MyFixedPoint)`](VRageMath.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|[`Clamp(int, int, int)`](VRageMath.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|[`Lerp(float, float, float)`](VRageMath.Lerp)|Linearly interpolates between two values.|
|[`Lerp(double, double, double)`](VRageMath.Lerp)|Linearly interpolates between two values.|
|[`InterpLog(float, float, float)`](VRageMath.InterpLog)|Performs interpolation on logarithmic scale.|
|[`InterpLogInv(float, float, float)`](VRageMath.InterpLogInv)||
|[`Barycentric(float, float, float, float, float)`](VRageMath.Barycentric)|Returns the Cartesian coordinate for one axis of a point that is defined by a given triangle and two normalized barycentric (areal) coordinates.|
|[`SmoothStep(float, float, float)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|[`SmoothStep(double, double, double)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|[`SmoothStepStable(float)`](VRageMath.SmoothStepStable)|Interpolates between zero and one using cubic equiation, solved by de Casteljau.|
|[`SmoothStepStable(double)`](VRageMath.SmoothStepStable)|Interpolates between zero and one using cubic equiation, solved by de Casteljau.|
|[`CatmullRom(float, float, float, float, float)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|[`Hermite(float, float, float, float, float)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|[`CalculateBezierPoint(double, Vector3D, Vector3D, Vector3D, Vector3D)`](VRageMath.CalculateBezierPoint)||
|[`WrapAngle(float)`](VRageMath.WrapAngle)|Reduces a given angle to a value between π and -π.|
|[`GetNearestBiggerPowerOfTwo(int)`](VRageMath.GetNearestBiggerPowerOfTwo)||
|[`GetNearestBiggerPowerOfTwo(uint)`](VRageMath.GetNearestBiggerPowerOfTwo)||
|[`GetNumberOfMipmaps(int)`](VRageMath.GetNumberOfMipmaps)||
|[`GetNearestBiggerPowerOfTwo(float)`](VRageMath.GetNearestBiggerPowerOfTwo)|Returns nearest bigger power of two|
|[`GetNearestBiggerPowerOfTwo(double)`](VRageMath.GetNearestBiggerPowerOfTwo)||
|[`Max(float, float, float)`](VRageMath.Max)||
|[`Max(int, int, int)`](VRageMath.Max)||
|[`Min(float, float, float)`](VRageMath.Min)||
|[`Max(double, double, double)`](VRageMath.Max)||
|[`Min(double, double, double)`](VRageMath.Min)||
|[`ComputeHashFromBytes(Byte[])`](VRageMath.ComputeHashFromBytes)||
|[`RoundOn2(float)`](VRageMath.RoundOn2)||
|[`IsPowerOfTwo(int)`](VRageMath.IsPowerOfTwo)|Returns true if value is power of two|
|[`SCurve3(float)`](VRageMath.SCurve3)||
|[`SCurve3(double)`](VRageMath.SCurve3)||
|[`SCurve5(float)`](VRageMath.SCurve5)||
|[`SCurve5(double)`](VRageMath.SCurve5)||
|[`Saturate(float)`](VRageMath.Saturate)||
|[`Saturate(double)`](VRageMath.Saturate)||
|[`Floor(float)`](VRageMath.Floor)||
|[`Floor(double)`](VRageMath.Floor)||
|[`Log2Floor(int)`](VRageMath.Log2Floor)||
|[`Log2Ceiling(int)`](VRageMath.Log2Ceiling)||
|[`Log2(int)`](VRageMath.Log2)||
|[`Log2(uint)`](VRageMath.Log2)||
|[`Pow2(int)`](VRageMath.Pow2)|Returns 2^n|
|[`CubicInterp(double, double, double, double, double)`](VRageMath.CubicInterp)||
|[`LimitRadians2PI(ref double)`](VRageMath.LimitRadians2PI)|Returns angle in range 0..2*PI|
|[`LimitRadians(ref float)`](VRageMath.LimitRadians)|Returns angle in range 0..2*PI|
|[`LimitRadiansPI(ref double)`](VRageMath.LimitRadiansPI)|Returns angle in range -PI..PI|
|[`LimitRadiansPI(ref float)`](VRageMath.LimitRadiansPI)|Returns angle in range -PI..PI|
|[`CalculateVectorOnSphere(Vector3, float, float)`](VRageMath.CalculateVectorOnSphere)||
|[`MonotonicCosine(float)`](VRageMath.MonotonicCosine)|Calculate the monotonic cosine of a value. Monotonic cosine is an alternative cosine encoding that is monotonic in the [-pi, pi] interval. We use this when some parameter of an onject in a planet is constrained by latitude. The 'monotonicity' is guaranteed by subtracting the cosine value from 2 if the angle is positive. So for instance MonotonicCos(pi/2) = 2. This only works in the above interval of course.|
|[`MonotonicAcos(float)`](VRageMath.MonotonicAcos)||
|[`Atan(float)`](VRageMath.Atan)|Faster Atan implementation. Good only in the [-pi/2, pi/2] range.|
|[`Atan(double)`](VRageMath.Atan)|Faster Atan implementation. Good only in the [-pi/2, pi/2] range.|
|[`IsEqual(float, float)`](VRageMath.IsEqual)||
|[`IsEqual(Vector2, Vector2)`](VRageMath.IsEqual)||
|[`IsEqual(Vector3, Vector3)`](VRageMath.IsEqual)||
|[`IsEqual(Quaternion, Quaternion)`](VRageMath.IsEqual)||
|[`IsEqual(QuaternionD, QuaternionD)`](VRageMath.IsEqual)||
|[`IsEqual(Matrix, Matrix)`](VRageMath.IsEqual)||
|[`IsValid(Matrix)`](VRageMath.IsValid)||
|[`IsValid(MatrixD)`](VRageMath.IsValid)||
|[`IsValid(Vector3)`](VRageMath.IsValid)||
|[`IsValid(Vector3D)`](VRageMath.IsValid)||
|[`IsValid(Vector2)`](VRageMath.IsValid)||
|[`IsValid(float)`](VRageMath.IsValid)||
|[`IsValid(double)`](VRageMath.IsValid)||
|[`IsValid(Nullable<Vector3>)`](VRageMath.IsValid)||
|[`IsValid(Quaternion)`](VRageMath.IsValid)||
|[`IsValidNormal(Vector3)`](VRageMath.IsValidNormal)||
|[`IsValidOrZero(Matrix)`](VRageMath.IsValidOrZero)||
|[`IsZero(float, float)`](VRageMath.IsZero)||
|[`IsZero(double, float)`](VRageMath.IsZero)||
|[`IsZero(Vector3, float)`](VRageMath.IsZero)||
|[`IsZero(Vector3D, float)`](VRageMath.IsZero)||
|[`IsZero(Quaternion, float)`](VRageMath.IsZero)||
|[`IsZero(Vector4)`](VRageMath.IsZero)||
|[`Smooth(int, int)`](VRageMath.Smooth)||
|[`Smooth(float, float)`](VRageMath.Smooth)||
