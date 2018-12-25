← [Index](Api-Index)

#### MathHelper Class

```csharp
public abstract sealed class MathHelper: object
```

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Inheritance: **[object](System.Object)

#### Example

#### Remarks

#### Fields

|Member|Description|
|---|---|
|[E](VRageMath.MathHelper.E)|Represents the mathematical constant e.|
|[Log2E](VRageMath.MathHelper.Log2E)|Represents the log base two of e.|
|[Log10E](VRageMath.MathHelper.Log10E)|Represents the log base ten of e.|
|[Pi](VRageMath.MathHelper.Pi)|Represents the value of pi.|
|[TwoPi](VRageMath.MathHelper.TwoPi)|Represents the value of pi times two.|
|[FourPi](VRageMath.MathHelper.FourPi)|Represents the value of pi times two.|
|[PiOver2](VRageMath.MathHelper.PiOver2)|Represents the value of pi divided by two.|
|[PiOver4](VRageMath.MathHelper.PiOver4)|Represents the value of pi divided by four.|
|[Sqrt2](VRageMath.MathHelper.Sqrt2)|Represents the value of the square root of two|
|[Sqrt3](VRageMath.MathHelper.Sqrt3)|Represents the value of the square root of three|
|[RadiansPerSecondToRPM](VRageMath.MathHelper.RadiansPerSecondToRPM)|60 / 2*pi|
|[RPMToRadiansPerSecond](VRageMath.MathHelper.RPMToRadiansPerSecond)|2*pi / 60|
|[RPMToRadiansPerMillisec](VRageMath.MathHelper.RPMToRadiansPerMillisec)|2*pi / 60000|
|[EPSILON](VRageMath.MathHelper.EPSILON)||
|[EPSILON10](VRageMath.MathHelper.EPSILON10)||

#### Methods

|Member|Description|
|---|---|
|[ToRadians(float)](VRageMath.MathHelper.ToRadians)|Converts degrees to radians.|
|[ToRadians(Vector3)](VRageMath.MathHelper.ToRadians)||
|[ToRadians(double)](VRageMath.MathHelper.ToRadians)|Converts degrees to radians.|
|[ToDegrees(float)](VRageMath.MathHelper.ToDegrees)|Converts radians to degrees.|
|[ToDegrees(double)](VRageMath.MathHelper.ToDegrees)||
|[Distance(float, float)](VRageMath.MathHelper.Distance)|Calculates the absolute value of the difference of two values.|
|[Min(float, float)](VRageMath.MathHelper.Min)|Returns the lesser of two values.|
|[Max(float, float)](VRageMath.MathHelper.Max)|Returns the greater of two values.|
|[Min(double, double)](VRageMath.MathHelper.Min)|Returns the lesser of two values.|
|[Max(double, double)](VRageMath.MathHelper.Max)|Returns the greater of two values.|
|[Clamp(float, float, float)](VRageMath.MathHelper.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|[Clamp(double, double, double)](VRageMath.MathHelper.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|[Clamp(MyFixedPoint, MyFixedPoint, MyFixedPoint)](VRageMath.MathHelper.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|[Clamp(int, int, int)](VRageMath.MathHelper.Clamp)|Restricts a value to be within a specified range. Reference page contains links to related code samples.|
|[Lerp(float, float, float)](VRageMath.MathHelper.Lerp)|Linearly interpolates between two values.|
|[Lerp(double, double, double)](VRageMath.MathHelper.Lerp)|Linearly interpolates between two values.|
|[InterpLog(float, float, float)](VRageMath.MathHelper.InterpLog)|Performs interpolation on logarithmic scale.|
|[InterpLogInv(float, float, float)](VRageMath.MathHelper.InterpLogInv)||
|[Barycentric(float, float, float, float, float)](VRageMath.MathHelper.Barycentric)|Returns the Cartesian coordinate for one axis of a point that is defined by a given triangle and two normalized barycentric (areal) coordinates.|
|[SmoothStep(float, float, float)](VRageMath.MathHelper.SmoothStep)|Interpolates between two values using a cubic equation.|
|[SmoothStep(double, double, double)](VRageMath.MathHelper.SmoothStep)|Interpolates between two values using a cubic equation.|
|[SmoothStepStable(float)](VRageMath.MathHelper.SmoothStepStable)|Interpolates between zero and one using cubic equiation, solved by de Casteljau.|
|[SmoothStepStable(double)](VRageMath.MathHelper.SmoothStepStable)|Interpolates between zero and one using cubic equiation, solved by de Casteljau.|
|[CatmullRom(float, float, float, float, float)](VRageMath.MathHelper.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|[Hermite(float, float, float, float, float)](VRageMath.MathHelper.Hermite)|Performs a Hermite spline interpolation.|
|[CalculateBezierPoint(double, Vector3D, Vector3D, Vector3D, Vector3D)](VRageMath.MathHelper.CalculateBezierPoint)||
|[WrapAngle(float)](VRageMath.MathHelper.WrapAngle)|Reduces a given angle to a value between π and -π.|
|[GetNearestBiggerPowerOfTwo(int)](VRageMath.MathHelper.GetNearestBiggerPowerOfTwo)||
|[GetNearestBiggerPowerOfTwo(uint)](VRageMath.MathHelper.GetNearestBiggerPowerOfTwo)||
|[GetNumberOfMipmaps(int)](VRageMath.MathHelper.GetNumberOfMipmaps)||
|[GetNearestBiggerPowerOfTwo(float)](VRageMath.MathHelper.GetNearestBiggerPowerOfTwo)|Returns nearest bigger power of two|
|[GetNearestBiggerPowerOfTwo(double)](VRageMath.MathHelper.GetNearestBiggerPowerOfTwo)||
|[Max(float, float, float)](VRageMath.MathHelper.Max)||
|[Max(int, int, int)](VRageMath.MathHelper.Max)||
|[Min(float, float, float)](VRageMath.MathHelper.Min)||
|[Max(double, double, double)](VRageMath.MathHelper.Max)||
|[Min(double, double, double)](VRageMath.MathHelper.Min)||
|[ComputeHashFromBytes(Byte[])](VRageMath.MathHelper.ComputeHashFromBytes)||
|[RoundOn2(float)](VRageMath.MathHelper.RoundOn2)||
|[IsPowerOfTwo(int)](VRageMath.MathHelper.IsPowerOfTwo)|Returns true if value is power of two|
|[SCurve3(float)](VRageMath.MathHelper.SCurve3)||
|[SCurve3(double)](VRageMath.MathHelper.SCurve3)||
|[SCurve5(float)](VRageMath.MathHelper.SCurve5)||
|[SCurve5(double)](VRageMath.MathHelper.SCurve5)||
|[Saturate(float)](VRageMath.MathHelper.Saturate)||
|[Saturate(double)](VRageMath.MathHelper.Saturate)||
|[Floor(float)](VRageMath.MathHelper.Floor)||
|[Floor(double)](VRageMath.MathHelper.Floor)||
|[Log2Floor(int)](VRageMath.MathHelper.Log2Floor)||
|[Log2Ceiling(int)](VRageMath.MathHelper.Log2Ceiling)||
|[Log2(int)](VRageMath.MathHelper.Log2)||
|[Log2(uint)](VRageMath.MathHelper.Log2)||
|[Pow2(int)](VRageMath.MathHelper.Pow2)|Returns 2^n|
|[CubicInterp(double, double, double, double, double)](VRageMath.MathHelper.CubicInterp)||
|[LimitRadians2PI(ref double)](VRageMath.MathHelper.LimitRadians2PI)|Returns angle in range 0..2*PI|
|[LimitRadians(ref float)](VRageMath.MathHelper.LimitRadians)|Returns angle in range 0..2*PI|
|[LimitRadiansPI(ref double)](VRageMath.MathHelper.LimitRadiansPI)|Returns angle in range -PI..PI|
|[LimitRadiansPI(ref float)](VRageMath.MathHelper.LimitRadiansPI)|Returns angle in range -PI..PI|
|[CalculateVectorOnSphere(Vector3, float, float)](VRageMath.MathHelper.CalculateVectorOnSphere)||
|[MonotonicCosine(float)](VRageMath.MathHelper.MonotonicCosine)|Calculate the monotonic cosine of a value. Monotonic cosine is an alternative cosine encoding that is monotonic in the [-pi, pi] interval. We use this when some parameter of an onject in a planet is constrained by latitude. The 'monotonicity' is guaranteed by subtracting the cosine value from 2 if the angle is positive. So for instance MonotonicCos(pi/2) = 2. This only works in the above interval of course.|
|[MonotonicAcos(float)](VRageMath.MathHelper.MonotonicAcos)||
|[Atan(float)](VRageMath.MathHelper.Atan)|Faster Atan implementation. Good only in the [-pi/2, pi/2] range.|
|[Atan(double)](VRageMath.MathHelper.Atan)|Faster Atan implementation. Good only in the [-pi/2, pi/2] range.|
|[IsEqual(float, float)](VRageMath.MathHelper.IsEqual)||
|[IsEqual(Vector2, Vector2)](VRageMath.MathHelper.IsEqual)||
|[IsEqual(Vector3, Vector3)](VRageMath.MathHelper.IsEqual)||
|[IsEqual(Quaternion, Quaternion)](VRageMath.MathHelper.IsEqual)||
|[IsEqual(QuaternionD, QuaternionD)](VRageMath.MathHelper.IsEqual)||
|[IsEqual(Matrix, Matrix)](VRageMath.MathHelper.IsEqual)||
|[IsValid(Matrix)](VRageMath.MathHelper.IsValid)||
|[IsValid(MatrixD)](VRageMath.MathHelper.IsValid)||
|[IsValid(Vector3)](VRageMath.MathHelper.IsValid)||
|[IsValid(Vector3D)](VRageMath.MathHelper.IsValid)||
|[IsValid(Vector2)](VRageMath.MathHelper.IsValid)||
|[IsValid(float)](VRageMath.MathHelper.IsValid)||
|[IsValid(double)](VRageMath.MathHelper.IsValid)||
|[IsValid(Nullable)](VRageMath.MathHelper.IsValid)||
|[IsValid(Quaternion)](VRageMath.MathHelper.IsValid)||
|[IsValidNormal(Vector3)](VRageMath.MathHelper.IsValidNormal)||
|[IsValidOrZero(Matrix)](VRageMath.MathHelper.IsValidOrZero)||
|[IsZero(float, float)](VRageMath.MathHelper.IsZero)||
|[IsZero(double, float)](VRageMath.MathHelper.IsZero)||
|[IsZero(Vector3, float)](VRageMath.MathHelper.IsZero)||
|[IsZero(Vector3D, float)](VRageMath.MathHelper.IsZero)||
|[IsZero(Quaternion, float)](VRageMath.MathHelper.IsZero)||
|[IsZero(Vector4)](VRageMath.MathHelper.IsZero)||
|[Smooth(int, int)](VRageMath.MathHelper.Smooth)||
|[Smooth(float, float)](VRageMath.MathHelper.Smooth)||

