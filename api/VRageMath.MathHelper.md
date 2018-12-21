← [Index](index)
# MathHelper Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Contains commonly used precalculated values.
### Fields
<table style="width:100%;display:table">
<tr><td>static _<a href="VRageMath.E"><code>float E</code></a>_</td><td>Represents the mathematical constant e.</td></tr>
<tr><td>static _<a href="VRageMath.Log2E"><code>float Log2E</code></a>_</td><td>Represents the log base two of e.</td></tr>
<tr><td>static _<a href="VRageMath.Log10E"><code>float Log10E</code></a>_</td><td>Represents the log base ten of e.</td></tr>
<tr><td>static _<a href="VRageMath.Pi"><code>float Pi</code></a>_</td><td>Represents the value of pi.</td></tr>
<tr><td>static _<a href="VRageMath.TwoPi"><code>float TwoPi</code></a>_</td><td>Represents the value of pi times two.</td></tr>
<tr><td>static _<a href="VRageMath.FourPi"><code>float FourPi</code></a>_</td><td>Represents the value of pi times two.</td></tr>
<tr><td>static _<a href="VRageMath.PiOver2"><code>float PiOver2</code></a>_</td><td>Represents the value of pi divided by two.</td></tr>
<tr><td>static _<a href="VRageMath.PiOver4"><code>float PiOver4</code></a>_</td><td>Represents the value of pi divided by four.</td></tr>
<tr><td>static _<a href="VRageMath.Sqrt2"><code>float Sqrt2</code></a>_</td><td>Represents the value of the square root of two</td></tr>
<tr><td>static _<a href="VRageMath.Sqrt3"><code>float Sqrt3</code></a>_</td><td>Represents the value of the square root of three</td></tr>
<tr><td>static _<a href="VRageMath.RadiansPerSecondToRPM"><code>float RadiansPerSecondToRPM</code></a>_</td><td>60 / 2*pi</td></tr>
<tr><td>static _<a href="VRageMath.RPMToRadiansPerSecond"><code>float RPMToRadiansPerSecond</code></a>_</td><td>2*pi / 60</td></tr>
<tr><td>static _<a href="VRageMath.RPMToRadiansPerMillisec"><code>float RPMToRadiansPerMillisec</code></a>_</td><td>2*pi / 60000</td></tr>
<tr><td>static _<a href="VRageMath.EPSILON"><code>float EPSILON</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.EPSILON10"><code>float EPSILON10</code></a>_</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>static _<a href="VRageMath.ToRadians"><code>float ToRadians(float degrees)</code></a>_</td><td>Converts degrees to radians.</td></tr>
<tr><td>static _<a href="VRageMath.ToRadians"><code>Vector3 ToRadians(Vector3 v)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.ToRadians"><code>double ToRadians(double degrees)</code></a>_</td><td>Converts degrees to radians.</td></tr>
<tr><td>static _<a href="VRageMath.ToDegrees"><code>float ToDegrees(float radians)</code></a>_</td><td>Converts radians to degrees.</td></tr>
<tr><td>static _<a href="VRageMath.ToDegrees"><code>double ToDegrees(double radians)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Distance"><code>float Distance(float value1, float value2)</code></a>_</td><td>Calculates the absolute value of the difference of two values.</td></tr>
<tr><td>static _<a href="VRageMath.Min"><code>float Min(float value1, float value2)</code></a>_</td><td>Returns the lesser of two values.</td></tr>
<tr><td>static _<a href="VRageMath.Max"><code>float Max(float value1, float value2)</code></a>_</td><td>Returns the greater of two values.</td></tr>
<tr><td>static _<a href="VRageMath.Min"><code>double Min(double value1, double value2)</code></a>_</td><td>Returns the lesser of two values.</td></tr>
<tr><td>static _<a href="VRageMath.Max"><code>double Max(double value1, double value2)</code></a>_</td><td>Returns the greater of two values.</td></tr>
<tr><td>static _<a href="VRageMath.Clamp"><code>float Clamp(float value, float min, float max)</code></a>_</td><td>Restricts a value to be within a specified range. Reference page contains links to related code samples.</td></tr>
<tr><td>static _<a href="VRageMath.Clamp"><code>double Clamp(double value, double min, double max)</code></a>_</td><td>Restricts a value to be within a specified range. Reference page contains links to related code samples.</td></tr>
<tr><td>static _<a href="VRageMath.Clamp"><code>MyFixedPoint Clamp(MyFixedPoint value, MyFixedPoint min, MyFixedPoint max)</code></a>_</td><td>Restricts a value to be within a specified range. Reference page contains links to related code samples.</td></tr>
<tr><td>static _<a href="VRageMath.Clamp"><code>int Clamp(int value, int min, int max)</code></a>_</td><td>Restricts a value to be within a specified range. Reference page contains links to related code samples.</td></tr>
<tr><td>static _<a href="VRageMath.Lerp"><code>float Lerp(float value1, float value2, float amount)</code></a>_</td><td>Linearly interpolates between two values.</td></tr>
<tr><td>static _<a href="VRageMath.Lerp"><code>double Lerp(double value1, double value2, double amount)</code></a>_</td><td>Linearly interpolates between two values.</td></tr>
<tr><td>static _<a href="VRageMath.InterpLog"><code>float InterpLog(float value, float amount1, float amount2)</code></a>_</td><td>Performs interpolation on logarithmic scale.</td></tr>
<tr><td>static _<a href="VRageMath.InterpLogInv"><code>float InterpLogInv(float value, float amount1, float amount2)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Barycentric"><code>float Barycentric(float value1, float value2, float value3, float amount1, float amount2)</code></a>_</td><td>Returns the Cartesian coordinate for one axis of a point that is defined by a given triangle and two normalized barycentric (areal) coordinates.</td></tr>
<tr><td>static _<a href="VRageMath.SmoothStep"><code>float SmoothStep(float value1, float value2, float amount)</code></a>_</td><td>Interpolates between two values using a cubic equation.</td></tr>
<tr><td>static _<a href="VRageMath.SmoothStep"><code>double SmoothStep(double value1, double value2, double amount)</code></a>_</td><td>Interpolates between two values using a cubic equation.</td></tr>
<tr><td>static _<a href="VRageMath.SmoothStepStable"><code>float SmoothStepStable(float amount)</code></a>_</td><td>Interpolates between zero and one using cubic equiation, solved by de Casteljau.</td></tr>
<tr><td>static _<a href="VRageMath.SmoothStepStable"><code>double SmoothStepStable(double amount)</code></a>_</td><td>Interpolates between zero and one using cubic equiation, solved by de Casteljau.</td></tr>
<tr><td>static _<a href="VRageMath.CatmullRom"><code>float CatmullRom(float value1, float value2, float value3, float value4, float amount)</code></a>_</td><td>Performs a Catmull-Rom interpolation using the specified positions.</td></tr>
<tr><td>static _<a href="VRageMath.Hermite"><code>float Hermite(float value1, float tangent1, float value2, float tangent2, float amount)</code></a>_</td><td>Performs a Hermite spline interpolation.</td></tr>
<tr><td>static _<a href="VRageMath.CalculateBezierPoint"><code>Vector3D CalculateBezierPoint(double t, Vector3D p0, Vector3D p1, Vector3D p2, Vector3D p3)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.WrapAngle"><code>float WrapAngle(float angle)</code></a>_</td><td>Reduces a given angle to a value between π and -π.</td></tr>
<tr><td>static _<a href="VRageMath.GetNearestBiggerPowerOfTwo"><code>int GetNearestBiggerPowerOfTwo(int v)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetNearestBiggerPowerOfTwo"><code>uint GetNearestBiggerPowerOfTwo(uint v)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetNumberOfMipmaps"><code>int GetNumberOfMipmaps(int v)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetNearestBiggerPowerOfTwo"><code>int GetNearestBiggerPowerOfTwo(float f)</code></a>_</td><td>Returns nearest bigger power of two</td></tr>
<tr><td>static _<a href="VRageMath.GetNearestBiggerPowerOfTwo"><code>int GetNearestBiggerPowerOfTwo(double f)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Max"><code>float Max(float a, float b, float c)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Max"><code>int Max(int a, int b, int c)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Min"><code>float Min(float a, float b, float c)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Max"><code>double Max(double a, double b, double c)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Min"><code>double Min(double a, double b, double c)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.ComputeHashFromBytes"><code>int ComputeHashFromBytes(Byte[] bytes)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.RoundOn2"><code>float RoundOn2(float x)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsPowerOfTwo"><code>bool IsPowerOfTwo(int x)</code></a>_</td><td>Returns true if value is power of two</td></tr>
<tr><td>static _<a href="VRageMath.SCurve3"><code>float SCurve3(float t)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.SCurve3"><code>double SCurve3(double t)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.SCurve5"><code>float SCurve5(float t)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.SCurve5"><code>double SCurve5(double t)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Saturate"><code>float Saturate(float n)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Saturate"><code>double Saturate(double n)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Floor"><code>int Floor(float n)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Floor"><code>int Floor(double n)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Log2Floor"><code>int Log2Floor(int value)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Log2Ceiling"><code>int Log2Ceiling(int value)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Log2"><code>int Log2(int n)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Log2"><code>int Log2(uint n)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Pow2"><code>int Pow2(int n)</code></a>_</td><td>Returns 2^n</td></tr>
<tr><td>static _<a href="VRageMath.CubicInterp"><code>double CubicInterp(double p0, double p1, double p2, double p3, double t)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.LimitRadians2PI"><code>void LimitRadians2PI(ref double angle)</code></a>_</td><td>Returns angle in range 0..2*PI</td></tr>
<tr><td>static _<a href="VRageMath.LimitRadians"><code>void LimitRadians(ref float angle)</code></a>_</td><td>Returns angle in range 0..2*PI</td></tr>
<tr><td>static _<a href="VRageMath.LimitRadiansPI"><code>void LimitRadiansPI(ref double angle)</code></a>_</td><td>Returns angle in range -PI..PI</td></tr>
<tr><td>static _<a href="VRageMath.LimitRadiansPI"><code>void LimitRadiansPI(ref float angle)</code></a>_</td><td>Returns angle in range -PI..PI</td></tr>
<tr><td>static _<a href="VRageMath.CalculateVectorOnSphere"><code>Vector3 CalculateVectorOnSphere(Vector3 northPoleDir, float phi, float theta)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.MonotonicCosine"><code>float MonotonicCosine(float radians)</code></a>_</td><td>Calculate the monotonic cosine of a value. Monotonic cosine is an alternative cosine encoding that is monotonic in the [-pi, pi] interval. We use this when some parameter of an onject in a planet is constrained by latitude. The 'monotonicity' is guaranteed by subtracting the cosine value from 2 if the angle is positive. So for instance MonotonicCos(pi/2) = 2. This only works in the above interval of course.</td></tr>
<tr><td>static _<a href="VRageMath.MonotonicAcos"><code>float MonotonicAcos(float cos)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Atan"><code>float Atan(float x)</code></a>_</td><td>Faster Atan implementation. Good only in the [-pi/2, pi/2] range.</td></tr>
<tr><td>static _<a href="VRageMath.Atan"><code>double Atan(double x)</code></a>_</td><td>Faster Atan implementation. Good only in the [-pi/2, pi/2] range.</td></tr>
<tr><td>static _<a href="VRageMath.IsEqual"><code>bool IsEqual(float value1, float value2)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsEqual"><code>bool IsEqual(Vector2 value1, Vector2 value2)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsEqual"><code>bool IsEqual(Vector3 value1, Vector3 value2)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsEqual"><code>bool IsEqual(Quaternion value1, Quaternion value2)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsEqual"><code>bool IsEqual(QuaternionD value1, QuaternionD value2)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsEqual"><code>bool IsEqual(Matrix value1, Matrix value2)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsValid"><code>bool IsValid(Matrix matrix)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsValid"><code>bool IsValid(MatrixD matrix)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsValid"><code>bool IsValid(Vector3 vec)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsValid"><code>bool IsValid(Vector3D vec)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsValid"><code>bool IsValid(Vector2 vec)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsValid"><code>bool IsValid(float f)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsValid"><code>bool IsValid(double f)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsValid"><code>bool IsValid(Nullable<Vector3> vec)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsValid"><code>bool IsValid(Quaternion q)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsValidNormal"><code>bool IsValidNormal(Vector3 vec)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsValidOrZero"><code>bool IsValidOrZero(Matrix matrix)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsZero"><code>bool IsZero(float value, float epsilon)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsZero"><code>bool IsZero(double value, float epsilon)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsZero"><code>bool IsZero(Vector3 value, float epsilon)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsZero"><code>bool IsZero(Vector3D value, float epsilon)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsZero"><code>bool IsZero(Quaternion value, float epsilon)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsZero"><code>bool IsZero(Vector4 value)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Smooth"><code>int Smooth(int newValue, int lastSmooth)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Smooth"><code>float Smooth(float newValue, float lastSmooth)</code></a>_</td><td></td></tr>
</table>
