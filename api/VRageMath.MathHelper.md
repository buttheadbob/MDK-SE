← [Index](index)
# MathHelper Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Contains commonly used precalculated values.
### Fields
|Member|Description|
|---|---|
|static [`E`](VRageMath.E)|Represents the mathematical constant e.|
|static [`Log2E`](VRageMath.Log2E)|Represents the log base two of e.|
|static [`Log10E`](VRageMath.Log10E)|Represents the log base ten of e.|
|static [`Pi`](VRageMath.Pi)|Represents the value of pi.|
|static [`TwoPi`](VRageMath.TwoPi)|Represents the value of pi times two.|
|static [`FourPi`](VRageMath.FourPi)|Represents the value of pi times two.|
|static [`PiOver2`](VRageMath.PiOver2)|Represents the value of pi divided by two.|
|static [`PiOver4`](VRageMath.PiOver4)|Represents the value of pi divided by four.|
|static [`Sqrt2`](VRageMath.Sqrt2)|Represents the value of the square root of two|
|static [`Sqrt3`](VRageMath.Sqrt3)|Represents the value of the square root of three|
|static [`RadiansPerSecondToRPM`](VRageMath.RadiansPerSecondToRPM)|60 / 2*pi|
|static [`RPMToRadiansPerSecond`](VRageMath.RPMToRadiansPerSecond)|2*pi / 60|
|static [`RPMToRadiansPerMillisec`](VRageMath.RPMToRadiansPerMillisec)|2*pi / 60000|
|static [`EPSILON`](VRageMath.EPSILON)||
|static [`EPSILON10`](VRageMath.EPSILON10)||
### Methods
|Member|Description|
|---|---|
|static [`ToRadians(float)`](VRageMath.ToRadians)|Converts degrees to radians.|
|static [`ToRadians(Vector3)`](VRageMath.ToRadians)||
|static [`ToRadians(double)`](VRageMath.ToRadians)|Converts degrees to radians.|
|static [`ToDegrees(float)`](VRageMath.ToDegrees)|Converts radians to degrees.|
|static [`ToDegrees(double)`](VRageMath.ToDegrees)||
|static [`Distance(float, float)`](VRageMath.Distance)|Calculates the absolute value of the difference of two values.|
|static [`Min(float, float)`](VRageMath.Min)|Returns the lesser of two values.|
|static [`Max(float, float)`](VRageMath.Max)|Returns the greater of two values.|
|static [`Min(double, double)`](VRageMath.Min)|Returns the lesser of two values.|
|static [`Max(double, double)`](VRageMath.Max)|Returns the greater of two values.|
|static [`Clamp(float, float, float)`](VRageMath.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|static [`Clamp(double, double, double)`](VRageMath.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|static [`Clamp(MyFixedPoint, MyFixedPoint, MyFixedPoint)`](VRageMath.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|static [`Clamp(int, int, int)`](VRageMath.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|static [`Lerp(float, float, float)`](VRageMath.Lerp)|Linearly interpolates between two values.|
|static [`Lerp(double, double, double)`](VRageMath.Lerp)|Linearly interpolates between two values.|
|static [`InterpLog(float, float, float)`](VRageMath.InterpLog)|Performs interpolation on logarithmic scale.|
|static [`InterpLogInv(float, float, float)`](VRageMath.InterpLogInv)||
|static [`Barycentric(float, float, float, float, float)`](VRageMath.Barycentric)|Returns the Cartesian coordinate for one axis of a point that is defined by a given triangle and two normalized barycentric (areal) coordinates.|
|static [`SmoothStep(float, float, float)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`SmoothStep(double, double, double)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`SmoothStepStable(float)`](VRageMath.SmoothStepStable)|Interpolates between zero and one using cubic equiation, solved by de Casteljau.|
|static [`SmoothStepStable(double)`](VRageMath.SmoothStepStable)|Interpolates between zero and one using cubic equiation, solved by de Casteljau.|
|static [`CatmullRom(float, float, float, float, float)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`Hermite(float, float, float, float, float)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`CalculateBezierPoint(double, Vector3D, Vector3D, Vector3D, Vector3D)`](VRageMath.CalculateBezierPoint)||
|static [`WrapAngle(float)`](VRageMath.WrapAngle)|Reduces a given angle to a value between π and -π.|
|static [`GetNearestBiggerPowerOfTwo(int)`](VRageMath.GetNearestBiggerPowerOfTwo)||
|static [`GetNearestBiggerPowerOfTwo(uint)`](VRageMath.GetNearestBiggerPowerOfTwo)||
|static [`GetNumberOfMipmaps(int)`](VRageMath.GetNumberOfMipmaps)||
|static [`GetNearestBiggerPowerOfTwo(float)`](VRageMath.GetNearestBiggerPowerOfTwo)|Returns nearest bigger power of two|
|static [`GetNearestBiggerPowerOfTwo(double)`](VRageMath.GetNearestBiggerPowerOfTwo)||
|static [`Max(float, float, float)`](VRageMath.Max)||
|static [`Max(int, int, int)`](VRageMath.Max)||
|static [`Min(float, float, float)`](VRageMath.Min)||
|static [`Max(double, double, double)`](VRageMath.Max)||
|static [`Min(double, double, double)`](VRageMath.Min)||
|static [`ComputeHashFromBytes(Byte[])`](VRageMath.ComputeHashFromBytes)||
|static [`RoundOn2(float)`](VRageMath.RoundOn2)||
|static [`IsPowerOfTwo(int)`](VRageMath.IsPowerOfTwo)|Returns true if value is power of two|
|static [`SCurve3(float)`](VRageMath.SCurve3)||
|static [`SCurve3(double)`](VRageMath.SCurve3)||
|static [`SCurve5(float)`](VRageMath.SCurve5)||
|static [`SCurve5(double)`](VRageMath.SCurve5)||
|static [`Saturate(float)`](VRageMath.Saturate)||
|static [`Saturate(double)`](VRageMath.Saturate)||
|static [`Floor(float)`](VRageMath.Floor)||
|static [`Floor(double)`](VRageMath.Floor)||
|static [`Log2Floor(int)`](VRageMath.Log2Floor)||
|static [`Log2Ceiling(int)`](VRageMath.Log2Ceiling)||
|static [`Log2(int)`](VRageMath.Log2)||
|static [`Log2(uint)`](VRageMath.Log2)||
|static [`Pow2(int)`](VRageMath.Pow2)|Returns 2^n|
|static [`CubicInterp(double, double, double, double, double)`](VRageMath.CubicInterp)||
|static [`LimitRadians2PI(ref double)`](VRageMath.LimitRadians2PI)|Returns angle in range 0..2*PI|
|static [`LimitRadians(ref float)`](VRageMath.LimitRadians)|Returns angle in range 0..2*PI|
|static [`LimitRadiansPI(ref double)`](VRageMath.LimitRadiansPI)|Returns angle in range -PI..PI|
|static [`LimitRadiansPI(ref float)`](VRageMath.LimitRadiansPI)|Returns angle in range -PI..PI|
|static [`CalculateVectorOnSphere(Vector3, float, float)`](VRageMath.CalculateVectorOnSphere)||
|static [`MonotonicCosine(float)`](VRageMath.MonotonicCosine)|Calculate the monotonic cosine of a value. Monotonic cosine is an alternative cosine encoding that is monotonic in the [-pi, pi] interval. We use this when some parameter of an onject in a planet is constrained by latitude. The 'monotonicity' is guaranteed by subtracting the cosine value from 2 if the angle is positive. So for instance MonotonicCos(pi/2) = 2. This only works in the above interval of course.|
|static [`MonotonicAcos(float)`](VRageMath.MonotonicAcos)||
|static [`Atan(float)`](VRageMath.Atan)|Faster Atan implementation. Good only in the [-pi/2, pi/2] range.|
|static [`Atan(double)`](VRageMath.Atan)|Faster Atan implementation. Good only in the [-pi/2, pi/2] range.|
|static [`IsEqual(float, float)`](VRageMath.IsEqual)||
|static [`IsEqual(Vector2, Vector2)`](VRageMath.IsEqual)||
|static [`IsEqual(Vector3, Vector3)`](VRageMath.IsEqual)||
|static [`IsEqual(Quaternion, Quaternion)`](VRageMath.IsEqual)||
|static [`IsEqual(QuaternionD, QuaternionD)`](VRageMath.IsEqual)||
|static [`IsEqual(Matrix, Matrix)`](VRageMath.IsEqual)||
|static [`IsValid(Matrix)`](VRageMath.IsValid)||
|static [`IsValid(MatrixD)`](VRageMath.IsValid)||
|static [`IsValid(Vector3)`](VRageMath.IsValid)||
|static [`IsValid(Vector3D)`](VRageMath.IsValid)||
|static [`IsValid(Vector2)`](VRageMath.IsValid)||
|static [`IsValid(float)`](VRageMath.IsValid)||
|static [`IsValid(double)`](VRageMath.IsValid)||
|static [`IsValid(Nullable<Vector3>)`](VRageMath.IsValid)||
|static [`IsValid(Quaternion)`](VRageMath.IsValid)||
|static [`IsValidNormal(Vector3)`](VRageMath.IsValidNormal)||
|static [`IsValidOrZero(Matrix)`](VRageMath.IsValidOrZero)||
|static [`IsZero(float, float)`](VRageMath.IsZero)||
|static [`IsZero(double, float)`](VRageMath.IsZero)||
|static [`IsZero(Vector3, float)`](VRageMath.IsZero)||
|static [`IsZero(Vector3D, float)`](VRageMath.IsZero)||
|static [`IsZero(Quaternion, float)`](VRageMath.IsZero)||
|static [`IsZero(Vector4)`](VRageMath.IsZero)||
|static [`Smooth(int, int)`](VRageMath.Smooth)||
|static [`Smooth(float, float)`](VRageMath.Smooth)||
