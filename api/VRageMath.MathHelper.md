← [Index](index)
# MathHelper Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Contains commonly used precalculated values.
### Fields
|Member|Description|
|---|---|
|static&nbsp;[`float&nbsp;E`](VRageMath.E)|Represents the mathematical constant e.|
|static&nbsp;[`float&nbsp;Log2E`](VRageMath.Log2E)|Represents the log base two of e.|
|static&nbsp;[`float&nbsp;Log10E`](VRageMath.Log10E)|Represents the log base ten of e.|
|static&nbsp;[`float&nbsp;Pi`](VRageMath.Pi)|Represents the value of pi.|
|static&nbsp;[`float&nbsp;TwoPi`](VRageMath.TwoPi)|Represents the value of pi times two.|
|static&nbsp;[`float&nbsp;FourPi`](VRageMath.FourPi)|Represents the value of pi times two.|
|static&nbsp;[`float&nbsp;PiOver2`](VRageMath.PiOver2)|Represents the value of pi divided by two.|
|static&nbsp;[`float&nbsp;PiOver4`](VRageMath.PiOver4)|Represents the value of pi divided by four.|
|static&nbsp;[`float&nbsp;Sqrt2`](VRageMath.Sqrt2)|Represents the value of the square root of two|
|static&nbsp;[`float&nbsp;Sqrt3`](VRageMath.Sqrt3)|Represents the value of the square root of three|
|static&nbsp;[`float&nbsp;RadiansPerSecondToRPM`](VRageMath.RadiansPerSecondToRPM)|60 / 2*pi|
|static&nbsp;[`float&nbsp;RPMToRadiansPerSecond`](VRageMath.RPMToRadiansPerSecond)|2*pi / 60|
|static&nbsp;[`float&nbsp;RPMToRadiansPerMillisec`](VRageMath.RPMToRadiansPerMillisec)|2*pi / 60000|
|static&nbsp;[`float&nbsp;EPSILON`](VRageMath.EPSILON)||
|static&nbsp;[`float&nbsp;EPSILON10`](VRageMath.EPSILON10)||
### Methods
|Member|Description|
|---|---|
|static&nbsp;[`float&nbsp;ToRadians(float&nbsp;degrees)`](VRageMath.ToRadians)|Converts degrees to radians.|
|static&nbsp;[`Vector3&nbsp;ToRadians(Vector3&nbsp;v)`](VRageMath.ToRadians)||
|static&nbsp;[`double&nbsp;ToRadians(double&nbsp;degrees)`](VRageMath.ToRadians)|Converts degrees to radians.|
|static&nbsp;[`float&nbsp;ToDegrees(float&nbsp;radians)`](VRageMath.ToDegrees)|Converts radians to degrees.|
|static&nbsp;[`double&nbsp;ToDegrees(double&nbsp;radians)`](VRageMath.ToDegrees)||
|static&nbsp;[`float&nbsp;Distance(float&nbsp;value1,&nbsp;float&nbsp;value2)`](VRageMath.Distance)|Calculates the absolute value of the difference of two values.|
|static&nbsp;[`float&nbsp;Min(float&nbsp;value1,&nbsp;float&nbsp;value2)`](VRageMath.Min)|Returns the lesser of two values.|
|static&nbsp;[`float&nbsp;Max(float&nbsp;value1,&nbsp;float&nbsp;value2)`](VRageMath.Max)|Returns the greater of two values.|
|static&nbsp;[`double&nbsp;Min(double&nbsp;value1,&nbsp;double&nbsp;value2)`](VRageMath.Min)|Returns the lesser of two values.|
|static&nbsp;[`double&nbsp;Max(double&nbsp;value1,&nbsp;double&nbsp;value2)`](VRageMath.Max)|Returns the greater of two values.|
|static&nbsp;[`float&nbsp;Clamp(float&nbsp;value,&nbsp;float&nbsp;min,&nbsp;float&nbsp;max)`](VRageMath.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|static&nbsp;[`double&nbsp;Clamp(double&nbsp;value,&nbsp;double&nbsp;min,&nbsp;double&nbsp;max)`](VRageMath.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|static&nbsp;[`MyFixedPoint&nbsp;Clamp(MyFixedPoint&nbsp;value,&nbsp;MyFixedPoint&nbsp;min,&nbsp;MyFixedPoint&nbsp;max)`](VRageMath.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|static&nbsp;[`int&nbsp;Clamp(int&nbsp;value,&nbsp;int&nbsp;min,&nbsp;int&nbsp;max)`](VRageMath.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|static&nbsp;[`float&nbsp;Lerp(float&nbsp;value1,&nbsp;float&nbsp;value2,&nbsp;float&nbsp;amount)`](VRageMath.Lerp)|Linearly interpolates between two values.|
|static&nbsp;[`double&nbsp;Lerp(double&nbsp;value1,&nbsp;double&nbsp;value2,&nbsp;double&nbsp;amount)`](VRageMath.Lerp)|Linearly interpolates between two values.|
|static&nbsp;[`float&nbsp;InterpLog(float&nbsp;value,&nbsp;float&nbsp;amount1,&nbsp;float&nbsp;amount2)`](VRageMath.InterpLog)|Performs interpolation on logarithmic scale.|
|static&nbsp;[`float&nbsp;InterpLogInv(float&nbsp;value,&nbsp;float&nbsp;amount1,&nbsp;float&nbsp;amount2)`](VRageMath.InterpLogInv)||
|static&nbsp;[`float&nbsp;Barycentric(float&nbsp;value1,&nbsp;float&nbsp;value2,&nbsp;float&nbsp;value3,&nbsp;float&nbsp;amount1,&nbsp;float&nbsp;amount2)`](VRageMath.Barycentric)|Returns the Cartesian coordinate for one axis of a point that is defined by a given triangle and two normalized barycentric (areal) coordinates.|
|static&nbsp;[`float&nbsp;SmoothStep(float&nbsp;value1,&nbsp;float&nbsp;value2,&nbsp;float&nbsp;amount)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static&nbsp;[`double&nbsp;SmoothStep(double&nbsp;value1,&nbsp;double&nbsp;value2,&nbsp;double&nbsp;amount)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static&nbsp;[`float&nbsp;SmoothStepStable(float&nbsp;amount)`](VRageMath.SmoothStepStable)|Interpolates between zero and one using cubic equiation, solved by de Casteljau.|
|static&nbsp;[`double&nbsp;SmoothStepStable(double&nbsp;amount)`](VRageMath.SmoothStepStable)|Interpolates between zero and one using cubic equiation, solved by de Casteljau.|
|static&nbsp;[`float&nbsp;CatmullRom(float&nbsp;value1,&nbsp;float&nbsp;value2,&nbsp;float&nbsp;value3,&nbsp;float&nbsp;value4,&nbsp;float&nbsp;amount)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static&nbsp;[`float&nbsp;Hermite(float&nbsp;value1,&nbsp;float&nbsp;tangent1,&nbsp;float&nbsp;value2,&nbsp;float&nbsp;tangent2,&nbsp;float&nbsp;amount)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static&nbsp;[`Vector3D&nbsp;CalculateBezierPoint(double&nbsp;t,&nbsp;Vector3D&nbsp;p0,&nbsp;Vector3D&nbsp;p1,&nbsp;Vector3D&nbsp;p2,&nbsp;Vector3D&nbsp;p3)`](VRageMath.CalculateBezierPoint)||
|static&nbsp;[`float&nbsp;WrapAngle(float&nbsp;angle)`](VRageMath.WrapAngle)|Reduces a given angle to a value between π and -π.|
|static&nbsp;[`int&nbsp;GetNearestBiggerPowerOfTwo(int&nbsp;v)`](VRageMath.GetNearestBiggerPowerOfTwo)||
|static&nbsp;[`uint&nbsp;GetNearestBiggerPowerOfTwo(uint&nbsp;v)`](VRageMath.GetNearestBiggerPowerOfTwo)||
|static&nbsp;[`int&nbsp;GetNumberOfMipmaps(int&nbsp;v)`](VRageMath.GetNumberOfMipmaps)||
|static&nbsp;[`int&nbsp;GetNearestBiggerPowerOfTwo(float&nbsp;f)`](VRageMath.GetNearestBiggerPowerOfTwo)|Returns nearest bigger power of two|
|static&nbsp;[`int&nbsp;GetNearestBiggerPowerOfTwo(double&nbsp;f)`](VRageMath.GetNearestBiggerPowerOfTwo)||
|static&nbsp;[`float&nbsp;Max(float&nbsp;a,&nbsp;float&nbsp;b,&nbsp;float&nbsp;c)`](VRageMath.Max)||
|static&nbsp;[`int&nbsp;Max(int&nbsp;a,&nbsp;int&nbsp;b,&nbsp;int&nbsp;c)`](VRageMath.Max)||
|static&nbsp;[`float&nbsp;Min(float&nbsp;a,&nbsp;float&nbsp;b,&nbsp;float&nbsp;c)`](VRageMath.Min)||
|static&nbsp;[`double&nbsp;Max(double&nbsp;a,&nbsp;double&nbsp;b,&nbsp;double&nbsp;c)`](VRageMath.Max)||
|static&nbsp;[`double&nbsp;Min(double&nbsp;a,&nbsp;double&nbsp;b,&nbsp;double&nbsp;c)`](VRageMath.Min)||
|static&nbsp;[`int&nbsp;ComputeHashFromBytes(Byte[]&nbsp;bytes)`](VRageMath.ComputeHashFromBytes)||
|static&nbsp;[`float&nbsp;RoundOn2(float&nbsp;x)`](VRageMath.RoundOn2)||
|static&nbsp;[`bool&nbsp;IsPowerOfTwo(int&nbsp;x)`](VRageMath.IsPowerOfTwo)|Returns true if value is power of two|
|static&nbsp;[`float&nbsp;SCurve3(float&nbsp;t)`](VRageMath.SCurve3)||
|static&nbsp;[`double&nbsp;SCurve3(double&nbsp;t)`](VRageMath.SCurve3)||
|static&nbsp;[`float&nbsp;SCurve5(float&nbsp;t)`](VRageMath.SCurve5)||
|static&nbsp;[`double&nbsp;SCurve5(double&nbsp;t)`](VRageMath.SCurve5)||
|static&nbsp;[`float&nbsp;Saturate(float&nbsp;n)`](VRageMath.Saturate)||
|static&nbsp;[`double&nbsp;Saturate(double&nbsp;n)`](VRageMath.Saturate)||
|static&nbsp;[`int&nbsp;Floor(float&nbsp;n)`](VRageMath.Floor)||
|static&nbsp;[`int&nbsp;Floor(double&nbsp;n)`](VRageMath.Floor)||
|static&nbsp;[`int&nbsp;Log2Floor(int&nbsp;value)`](VRageMath.Log2Floor)||
|static&nbsp;[`int&nbsp;Log2Ceiling(int&nbsp;value)`](VRageMath.Log2Ceiling)||
|static&nbsp;[`int&nbsp;Log2(int&nbsp;n)`](VRageMath.Log2)||
|static&nbsp;[`int&nbsp;Log2(uint&nbsp;n)`](VRageMath.Log2)||
|static&nbsp;[`int&nbsp;Pow2(int&nbsp;n)`](VRageMath.Pow2)|Returns 2^n|
|static&nbsp;[`double&nbsp;CubicInterp(double&nbsp;p0,&nbsp;double&nbsp;p1,&nbsp;double&nbsp;p2,&nbsp;double&nbsp;p3,&nbsp;double&nbsp;t)`](VRageMath.CubicInterp)||
|static&nbsp;[`void&nbsp;LimitRadians2PI(ref&nbsp;double&nbsp;angle)`](VRageMath.LimitRadians2PI)|Returns angle in range 0..2*PI|
|static&nbsp;[`void&nbsp;LimitRadians(ref&nbsp;float&nbsp;angle)`](VRageMath.LimitRadians)|Returns angle in range 0..2*PI|
|static&nbsp;[`void&nbsp;LimitRadiansPI(ref&nbsp;double&nbsp;angle)`](VRageMath.LimitRadiansPI)|Returns angle in range -PI..PI|
|static&nbsp;[`void&nbsp;LimitRadiansPI(ref&nbsp;float&nbsp;angle)`](VRageMath.LimitRadiansPI)|Returns angle in range -PI..PI|
|static&nbsp;[`Vector3&nbsp;CalculateVectorOnSphere(Vector3&nbsp;northPoleDir,&nbsp;float&nbsp;phi,&nbsp;float&nbsp;theta)`](VRageMath.CalculateVectorOnSphere)||
|static&nbsp;[`float&nbsp;MonotonicCosine(float&nbsp;radians)`](VRageMath.MonotonicCosine)|Calculate the monotonic cosine of a value. Monotonic cosine is an alternative cosine encoding that is monotonic in the [-pi, pi] interval. We use this when some parameter of an onject in a planet is constrained by latitude. The 'monotonicity' is guaranteed by subtracting the cosine value from 2 if the angle is positive. So for instance MonotonicCos(pi/2) = 2. This only works in the above interval of course.|
|static&nbsp;[`float&nbsp;MonotonicAcos(float&nbsp;cos)`](VRageMath.MonotonicAcos)||
|static&nbsp;[`float&nbsp;Atan(float&nbsp;x)`](VRageMath.Atan)|Faster Atan implementation. Good only in the [-pi/2, pi/2] range.|
|static&nbsp;[`double&nbsp;Atan(double&nbsp;x)`](VRageMath.Atan)|Faster Atan implementation. Good only in the [-pi/2, pi/2] range.|
|static&nbsp;[`bool&nbsp;IsEqual(float&nbsp;value1,&nbsp;float&nbsp;value2)`](VRageMath.IsEqual)||
|static&nbsp;[`bool&nbsp;IsEqual(Vector2&nbsp;value1,&nbsp;Vector2&nbsp;value2)`](VRageMath.IsEqual)||
|static&nbsp;[`bool&nbsp;IsEqual(Vector3&nbsp;value1,&nbsp;Vector3&nbsp;value2)`](VRageMath.IsEqual)||
|static&nbsp;[`bool&nbsp;IsEqual(Quaternion&nbsp;value1,&nbsp;Quaternion&nbsp;value2)`](VRageMath.IsEqual)||
|static&nbsp;[`bool&nbsp;IsEqual(QuaternionD&nbsp;value1,&nbsp;QuaternionD&nbsp;value2)`](VRageMath.IsEqual)||
|static&nbsp;[`bool&nbsp;IsEqual(Matrix&nbsp;value1,&nbsp;Matrix&nbsp;value2)`](VRageMath.IsEqual)||
|static&nbsp;[`bool&nbsp;IsValid(Matrix&nbsp;matrix)`](VRageMath.IsValid)||
|static&nbsp;[`bool&nbsp;IsValid(MatrixD&nbsp;matrix)`](VRageMath.IsValid)||
|static&nbsp;[`bool&nbsp;IsValid(Vector3&nbsp;vec)`](VRageMath.IsValid)||
|static&nbsp;[`bool&nbsp;IsValid(Vector3D&nbsp;vec)`](VRageMath.IsValid)||
|static&nbsp;[`bool&nbsp;IsValid(Vector2&nbsp;vec)`](VRageMath.IsValid)||
|static&nbsp;[`bool&nbsp;IsValid(float&nbsp;f)`](VRageMath.IsValid)||
|static&nbsp;[`bool&nbsp;IsValid(double&nbsp;f)`](VRageMath.IsValid)||
|static&nbsp;[`bool&nbsp;IsValid(Nullable<Vector3>&nbsp;vec)`](VRageMath.IsValid)||
|static&nbsp;[`bool&nbsp;IsValid(Quaternion&nbsp;q)`](VRageMath.IsValid)||
|static&nbsp;[`bool&nbsp;IsValidNormal(Vector3&nbsp;vec)`](VRageMath.IsValidNormal)||
|static&nbsp;[`bool&nbsp;IsValidOrZero(Matrix&nbsp;matrix)`](VRageMath.IsValidOrZero)||
|static&nbsp;[`bool&nbsp;IsZero(float&nbsp;value,&nbsp;float&nbsp;epsilon)`](VRageMath.IsZero)||
|static&nbsp;[`bool&nbsp;IsZero(double&nbsp;value,&nbsp;float&nbsp;epsilon)`](VRageMath.IsZero)||
|static&nbsp;[`bool&nbsp;IsZero(Vector3&nbsp;value,&nbsp;float&nbsp;epsilon)`](VRageMath.IsZero)||
|static&nbsp;[`bool&nbsp;IsZero(Vector3D&nbsp;value,&nbsp;float&nbsp;epsilon)`](VRageMath.IsZero)||
|static&nbsp;[`bool&nbsp;IsZero(Quaternion&nbsp;value,&nbsp;float&nbsp;epsilon)`](VRageMath.IsZero)||
|static&nbsp;[`bool&nbsp;IsZero(Vector4&nbsp;value)`](VRageMath.IsZero)||
|static&nbsp;[`int&nbsp;Smooth(int&nbsp;newValue,&nbsp;int&nbsp;lastSmooth)`](VRageMath.Smooth)||
|static&nbsp;[`float&nbsp;Smooth(float&nbsp;newValue,&nbsp;float&nbsp;lastSmooth)`](VRageMath.Smooth)||
