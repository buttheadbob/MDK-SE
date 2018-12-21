← [Index](index)
# Vector3 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with three components.
### Fields
<table style="width:100%;display:table">
<tr><td>[`float X`](VRageMath.X)</td><td>Gets or sets the x-component of the vector.</td></tr>
<tr><td>[`float Y`](VRageMath.Y)</td><td>Gets or sets the y-component of the vector.</td></tr>
<tr><td>[`float Z`](VRageMath.Z)</td><td>Gets or sets the z-component of the vector.</td></tr>
<tr><td>static [`Vector3 Zero`](VRageMath.Zero)</td><td></td></tr>
<tr><td>static [`Vector3 One`](VRageMath.One)</td><td></td></tr>
<tr><td>static [`Vector3 MinusOne`](VRageMath.MinusOne)</td><td></td></tr>
<tr><td>static [`Vector3 Half`](VRageMath.Half)</td><td></td></tr>
<tr><td>static [`Vector3 PositiveInfinity`](VRageMath.PositiveInfinity)</td><td></td></tr>
<tr><td>static [`Vector3 NegativeInfinity`](VRageMath.NegativeInfinity)</td><td></td></tr>
<tr><td>static [`Vector3 UnitX`](VRageMath.UnitX)</td><td></td></tr>
<tr><td>static [`Vector3 UnitY`](VRageMath.UnitY)</td><td></td></tr>
<tr><td>static [`Vector3 UnitZ`](VRageMath.UnitZ)</td><td></td></tr>
<tr><td>static [`Vector3 Up`](VRageMath.Up)</td><td></td></tr>
<tr><td>static [`Vector3 Down`](VRageMath.Down)</td><td></td></tr>
<tr><td>static [`Vector3 Right`](VRageMath.Right)</td><td></td></tr>
<tr><td>static [`Vector3 Left`](VRageMath.Left)</td><td></td></tr>
<tr><td>static [`Vector3 Forward`](VRageMath.Forward)</td><td></td></tr>
<tr><td>static [`Vector3 Backward`](VRageMath.Backward)</td><td></td></tr>
<tr><td>static [`Vector3 MaxValue`](VRageMath.MaxValue)</td><td></td></tr>
<tr><td>static [`Vector3 MinValue`](VRageMath.MinValue)</td><td></td></tr>
<tr><td>static [`Vector3 Invalid`](VRageMath.Invalid)</td><td></td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>[`float Sum`](VRageMath.Sum)</td><td></td></tr>
<tr><td>[`float Volume`](VRageMath.Volume)</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>static [`void Negate(ref Vector3 value, ref Vector3 result)`](VRageMath.Negate)</td><td>Returns a vector pointing in the opposite direction.</td></tr>
<tr><td>static [`Vector3 Add(Vector3 value1, Vector3 value2)`](VRageMath.Add)</td><td>Adds two vectors.</td></tr>
<tr><td>static [`void Add(ref Vector3 value1, ref Vector3 value2, ref Vector3 result)`](VRageMath.Add)</td><td>Adds two vectors.</td></tr>
<tr><td>static [`Vector3 Subtract(Vector3 value1, Vector3 value2)`](VRageMath.Subtract)</td><td>Subtracts a vector from a vector.</td></tr>
<tr><td>static [`void Subtract(ref Vector3 value1, ref Vector3 value2, ref Vector3 result)`](VRageMath.Subtract)</td><td>Subtracts a vector from a vector.</td></tr>
<tr><td>static [`Vector3 Multiply(Vector3 value1, Vector3 value2)`](VRageMath.Multiply)</td><td>Multiplies the components of two vectors by each other.</td></tr>
<tr><td>static [`void Multiply(ref Vector3 value1, ref Vector3 value2, ref Vector3 result)`](VRageMath.Multiply)</td><td>Multiplies the components of two vectors by each other.</td></tr>
<tr><td>static [`Vector3 Multiply(Vector3 value1, float scaleFactor)`](VRageMath.Multiply)</td><td>Multiplies a vector by a scalar value.</td></tr>
<tr><td>static [`void Multiply(ref Vector3 value1, float scaleFactor, ref Vector3 result)`](VRageMath.Multiply)</td><td>Multiplies a vector by a scalar value.</td></tr>
<tr><td>static [`Vector3 Divide(Vector3 value1, Vector3 value2)`](VRageMath.Divide)</td><td>Divides the components of a vector by the components of another vector.</td></tr>
<tr><td>static [`void Divide(ref Vector3 value1, ref Vector3 value2, ref Vector3 result)`](VRageMath.Divide)</td><td>Divides the components of a vector by the components of another vector.</td></tr>
<tr><td>static [`Vector3 Divide(Vector3 value1, float value2)`](VRageMath.Divide)</td><td>Divides a vector by a scalar value.</td></tr>
<tr><td>static [`void Divide(ref Vector3 value1, float value2, ref Vector3 result)`](VRageMath.Divide)</td><td>Divides a vector by a scalar value.</td></tr>
<tr><td>static [`Vector3 CalculatePerpendicularVector(Vector3 v)`](VRageMath.CalculatePerpendicularVector)</td><td></td></tr>
<tr><td>[`void CalculatePerpendicularVector(ref Vector3 result)`](VRageMath.CalculatePerpendicularVector)</td><td></td></tr>
<tr><td>static [`void GetAzimuthAndElevation(Vector3 v, ref float azimuth, ref float elevation)`](VRageMath.GetAzimuthAndElevation)</td><td></td></tr>
<tr><td>static [`void CreateFromAzimuthAndElevation(float azimuth, float elevation, ref Vector3 direction)`](VRageMath.CreateFromAzimuthAndElevation)</td><td></td></tr>
<tr><td>[`long VolumeInt(float multiplier)`](VRageMath.VolumeInt)</td><td></td></tr>
<tr><td>[`bool IsInsideInclusive(ref Vector3 min, ref Vector3 max)`](VRageMath.IsInsideInclusive)</td><td></td></tr>
<tr><td>static [`Vector3 SwapYZCoordinates(Vector3 v)`](VRageMath.SwapYZCoordinates)</td><td></td></tr>
<tr><td>[`float GetDim(int i)`](VRageMath.GetDim)</td><td></td></tr>
<tr><td>[`void SetDim(int i, float value)`](VRageMath.SetDim)</td><td></td></tr>
<tr><td>static [`Vector3 Ceiling(Vector3 v)`](VRageMath.Ceiling)</td><td></td></tr>
<tr><td>static [`Vector3 Floor(Vector3 v)`](VRageMath.Floor)</td><td></td></tr>
<tr><td>static [`Vector3 Round(Vector3 v)`](VRageMath.Round)</td><td></td></tr>
<tr><td>static [`Vector3 Round(Vector3 v, int numDecimals)`](VRageMath.Round)</td><td></td></tr>
<tr><td>static [`Vector3 ProjectOnPlane(ref Vector3 vec, ref Vector3 planeNormal)`](VRageMath.ProjectOnPlane)</td><td>Projects given vector on plane specified by it's normal.</td></tr>
<tr><td>static [`Vector3 ProjectOnVector(ref Vector3 vec, ref Vector3 guideVector)`](VRageMath.ProjectOnVector)</td><td>Projects vector on another vector resulting in new vector in guided vector's direction with different length.</td></tr>
<tr><td>static [`bool IsZero(ref Vector3 vec)`](VRageMath.IsZero)</td><td></td></tr>
<tr><td>[`void Divide(float divider)`](VRageMath.Divide)</td><td></td></tr>
<tr><td>[`void Multiply(float scale)`](VRageMath.Multiply)</td><td></td></tr>
<tr><td>[`void Add(Vector3 other)`](VRageMath.Add)</td><td></td></tr>
<tr><td>static [`Vector3 Abs(Vector3 value)`](VRageMath.Abs)</td><td></td></tr>
<tr><td>static [`Vector3 Sign(Vector3 value)`](VRageMath.Sign)</td><td></td></tr>
<tr><td>static [`Vector3 Sign(Vector3 value, float epsilon)`](VRageMath.Sign)</td><td></td></tr>
<tr><td>static [`Vector3 SignNonZero(Vector3 value)`](VRageMath.SignNonZero)</td><td>Returns per component sign, never returns zero. For zero component returns sign 1. Faster than Sign.</td></tr>
<tr><td>[`void Interpolate3(Vector3 v0, Vector3 v1, float rt)`](VRageMath.Interpolate3)</td><td></td></tr>
<tr><td>[`bool IsValid()`](VRageMath.IsValid)</td><td></td></tr>
<tr><td>[`void AssertIsValid()`](VRageMath.AssertIsValid)</td><td></td></tr>
<tr><td>static [`bool IsUnit(ref Vector3 value)`](VRageMath.IsUnit)</td><td></td></tr>
<tr><td>static [`bool ArePerpendicular(ref Vector3 a, ref Vector3 b)`](VRageMath.ArePerpendicular)</td><td></td></tr>
<tr><td>static [`bool IsZero(Vector3 value)`](VRageMath.IsZero)</td><td></td></tr>
<tr><td>static [`bool IsZero(Vector3 value, float epsilon)`](VRageMath.IsZero)</td><td></td></tr>
<tr><td>static [`Vector3 IsZeroVector(Vector3 value)`](VRageMath.IsZeroVector)</td><td></td></tr>
<tr><td>static [`Vector3 IsZeroVector(Vector3 value, float epsilon)`](VRageMath.IsZeroVector)</td><td></td></tr>
<tr><td>static [`Vector3 Step(Vector3 value)`](VRageMath.Step)</td><td></td></tr>
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td>Retrieves a string representation of the current object.</td></tr>
<tr><td>[`string ToString(string format)`](VRageMath.ToString)</td><td></td></tr>
<tr><td>[`bool Equals(Vector3 other)`](VRageMath.Equals)</td><td>Determines whether the specified Object is equal to the Vector3.</td></tr>
<tr><td>[`bool Equals(Vector3 other, float epsilon)`](VRageMath.Equals)</td><td></td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td>Returns a value that indicates whether the current instance is equal to a specified object.</td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td></td></tr>
<tr><td>[`long GetHash()`](VRageMath.GetHash)</td><td>Gets the hash code of the vector object.</td></tr>
<tr><td>[`float Length()`](VRageMath.Length)</td><td>Calculates the length of the vector.</td></tr>
<tr><td>[`float LengthSquared()`](VRageMath.LengthSquared)</td><td>Calculates the length of the vector squared.</td></tr>
<tr><td>static [`float Distance(Vector3 value1, Vector3 value2)`](VRageMath.Distance)</td><td>Calculates the distance between two vectors.</td></tr>
<tr><td>static [`void Distance(ref Vector3 value1, ref Vector3 value2, ref float result)`](VRageMath.Distance)</td><td>Calculates the distance between two vectors.</td></tr>
<tr><td>static [`float DistanceSquared(Vector3 value1, Vector3 value2)`](VRageMath.DistanceSquared)</td><td>Calculates the distance between two vectors squared.</td></tr>
<tr><td>static [`void DistanceSquared(ref Vector3 value1, ref Vector3 value2, ref float result)`](VRageMath.DistanceSquared)</td><td>Calculates the distance between two vectors squared.</td></tr>
<tr><td>static [`float RectangularDistance(Vector3 value1, Vector3 value2)`](VRageMath.RectangularDistance)</td><td>Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.</td></tr>
<tr><td>static [`float RectangularDistance(ref Vector3 value1, ref Vector3 value2)`](VRageMath.RectangularDistance)</td><td>Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.</td></tr>
<tr><td>static [`float Dot(Vector3 vector1, Vector3 vector2)`](VRageMath.Dot)</td><td>Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.</td></tr>
<tr><td>static [`void Dot(ref Vector3 vector1, ref Vector3 vector2, ref float result)`](VRageMath.Dot)</td><td>Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.</td></tr>
<tr><td>[`float Dot(Vector3 v)`](VRageMath.Dot)</td><td></td></tr>
<tr><td>[`float Dot(ref Vector3 v)`](VRageMath.Dot)</td><td></td></tr>
<tr><td>[`Vector3 Cross(Vector3 v)`](VRageMath.Cross)</td><td></td></tr>
<tr><td>[`float Normalize()`](VRageMath.Normalize)</td><td>Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.</td></tr>
<tr><td>static [`Vector3 Normalize(Vector3 value)`](VRageMath.Normalize)</td><td>Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.</td></tr>
<tr><td>static [`Vector3 Normalize(Vector3D value)`](VRageMath.Normalize)</td><td></td></tr>
<tr><td>static [`bool GetNormalized(ref Vector3 value)`](VRageMath.GetNormalized)</td><td></td></tr>
<tr><td>static [`void Normalize(ref Vector3 value, ref Vector3 result)`](VRageMath.Normalize)</td><td>Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.</td></tr>
<tr><td>static [`Vector3 Cross(Vector3 vector1, Vector3 vector2)`](VRageMath.Cross)</td><td>Calculates the cross product of two vectors.</td></tr>
<tr><td>static [`void Cross(ref Vector3 vector1, ref Vector3 vector2, ref Vector3 result)`](VRageMath.Cross)</td><td>Calculates the cross product of two vectors.</td></tr>
<tr><td>static [`Vector3 Reflect(Vector3 vector, Vector3 normal)`](VRageMath.Reflect)</td><td>Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.</td></tr>
<tr><td>static [`void Reflect(ref Vector3 vector, ref Vector3 normal, ref Vector3 result)`](VRageMath.Reflect)</td><td>Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.</td></tr>
<tr><td>static [`Vector3 Reject(Vector3 vector, Vector3 direction)`](VRageMath.Reject)</td><td>Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction</td></tr>
<tr><td>static [`void Reject(ref Vector3 vector, ref Vector3 direction, ref Vector3 result)`](VRageMath.Reject)</td><td>Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction</td></tr>
<tr><td>[`float Min()`](VRageMath.Min)</td><td>Returns the component of the vector that is smallest of all the three components.</td></tr>
<tr><td>[`float AbsMin()`](VRageMath.AbsMin)</td><td>Returns the component of the vector, whose absolute value is smallest of all the three components.</td></tr>
<tr><td>[`float Max()`](VRageMath.Max)</td><td>Returns the component of the vector that is largest of all the three components.</td></tr>
<tr><td>[`Vector3 MaxAbsComponent()`](VRageMath.MaxAbsComponent)</td><td>Keeps only component with maximal absolute, others are set to zero.</td></tr>
<tr><td>[`float AbsMax()`](VRageMath.AbsMax)</td><td>Returns the component of the vector, whose absolute value is largest of all the three components.</td></tr>
<tr><td>static [`Vector3 Min(Vector3 value1, Vector3 value2)`](VRageMath.Min)</td><td>Returns a vector that contains the lowest value from each matching pair of components.</td></tr>
<tr><td>static [`void Min(ref Vector3 value1, ref Vector3 value2, ref Vector3 result)`](VRageMath.Min)</td><td>Returns a vector that contains the lowest value from each matching pair of components.</td></tr>
<tr><td>static [`Vector3 Max(Vector3 value1, Vector3 value2)`](VRageMath.Max)</td><td>Returns a vector that contains the highest value from each matching pair of components.</td></tr>
<tr><td>static [`void Max(ref Vector3 value1, ref Vector3 value2, ref Vector3 result)`](VRageMath.Max)</td><td>Returns a vector that contains the highest value from each matching pair of components.</td></tr>
<tr><td>static [`void MinMax(ref Vector3 min, ref Vector3 max)`](VRageMath.MinMax)</td><td>Separates minimal and maximal values of any two input vectors</td></tr>
<tr><td>static [`Vector3 DominantAxisProjection(Vector3 value1)`](VRageMath.DominantAxisProjection)</td><td>Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.</td></tr>
<tr><td>static [`void DominantAxisProjection(ref Vector3 value1, ref Vector3 result)`](VRageMath.DominantAxisProjection)</td><td>Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved into a user-specified variable.</td></tr>
<tr><td>static [`Vector3 Clamp(Vector3 value1, Vector3 min, Vector3 max)`](VRageMath.Clamp)</td><td>Restricts a value to be within a specified range.</td></tr>
<tr><td>static [`void Clamp(ref Vector3 value1, ref Vector3 min, ref Vector3 max, ref Vector3 result)`](VRageMath.Clamp)</td><td>Restricts a value to be within a specified range.</td></tr>
<tr><td>static [`Vector3 ClampToSphere(Vector3 vector, float radius)`](VRageMath.ClampToSphere)</td><td></td></tr>
<tr><td>static [`void ClampToSphere(ref Vector3 vector, float radius)`](VRageMath.ClampToSphere)</td><td></td></tr>
<tr><td>static [`Vector3 Lerp(Vector3 value1, Vector3 value2, float amount)`](VRageMath.Lerp)</td><td>Performs a linear interpolation between two vectors.</td></tr>
<tr><td>static [`void Lerp(ref Vector3 value1, ref Vector3 value2, float amount, ref Vector3 result)`](VRageMath.Lerp)</td><td>Performs a linear interpolation between two vectors.</td></tr>
<tr><td>static [`Vector3 Barycentric(Vector3 value1, Vector3 value2, Vector3 value3, float amount1, float amount2)`](VRageMath.Barycentric)</td><td>Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in Barycentric coordinates relative to a 3D triangle.</td></tr>
<tr><td>static [`void Barycentric(ref Vector3 value1, ref Vector3 value2, ref Vector3 value3, float amount1, float amount2, ref Vector3 result)`](VRageMath.Barycentric)</td><td>Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 3D triangle.</td></tr>
<tr><td>static [`void Barycentric(Vector3 p, Vector3 a, Vector3 b, Vector3 c, ref float u, ref float v, ref float w)`](VRageMath.Barycentric)</td><td>Compute barycentric coordinates (u, v, w) for point p with respect to triangle (a, b, c) From : Real-Time Collision Detection, Christer Ericson, CRC Press 3.4 Barycentric Coordinates</td></tr>
<tr><td>static [`float TriangleArea(Vector3 v1, Vector3 v2, Vector3 v3)`](VRageMath.TriangleArea)</td><td></td></tr>
<tr><td>static [`float TriangleArea(ref Vector3 v1, ref Vector3 v2, ref Vector3 v3)`](VRageMath.TriangleArea)</td><td></td></tr>
<tr><td>static [`Vector3 SmoothStep(Vector3 value1, Vector3 value2, float amount)`](VRageMath.SmoothStep)</td><td>Interpolates between two values using a cubic equation.</td></tr>
<tr><td>static [`void SmoothStep(ref Vector3 value1, ref Vector3 value2, float amount, ref Vector3 result)`](VRageMath.SmoothStep)</td><td>Interpolates between two values using a cubic equation.</td></tr>
<tr><td>static [`Vector3 CatmullRom(Vector3 value1, Vector3 value2, Vector3 value3, Vector3 value4, float amount)`](VRageMath.CatmullRom)</td><td>Performs a Catmull-Rom interpolation using the specified positions.</td></tr>
<tr><td>static [`void CatmullRom(ref Vector3 value1, ref Vector3 value2, ref Vector3 value3, ref Vector3 value4, float amount, ref Vector3 result)`](VRageMath.CatmullRom)</td><td>Performs a Catmull-Rom interpolation using the specified positions.</td></tr>
<tr><td>static [`Vector3 Hermite(Vector3 value1, Vector3 tangent1, Vector3 value2, Vector3 tangent2, float amount)`](VRageMath.Hermite)</td><td>Performs a Hermite spline interpolation.</td></tr>
<tr><td>static [`void Hermite(ref Vector3 value1, ref Vector3 tangent1, ref Vector3 value2, ref Vector3 tangent2, float amount, ref Vector3 result)`](VRageMath.Hermite)</td><td>Performs a Hermite spline interpolation.</td></tr>
<tr><td>static [`Vector3 Transform(Vector3 position, Matrix matrix)`](VRageMath.Transform)</td><td>Transforms a 3D vector by the given matrix.</td></tr>
<tr><td>static [`Vector3D Transform(Vector3 position, MatrixD matrix)`](VRageMath.Transform)</td><td>Transforms a 3D vector by the given matrix.</td></tr>
<tr><td>static [`Vector3 Transform(Vector3 position, ref Matrix matrix)`](VRageMath.Transform)</td><td></td></tr>
<tr><td>static [`void Transform(ref Vector3 position, ref Matrix matrix, ref Vector3 result)`](VRageMath.Transform)</td><td>Transforms a Vector3 by the given Matrix.</td></tr>
<tr><td>static [`void Transform(ref Vector3 position, ref MatrixI matrix, ref Vector3 result)`](VRageMath.Transform)</td><td></td></tr>
<tr><td>static [`void TransformProjection(ref Vector3 position, ref Matrix matrix, ref Vector3 result)`](VRageMath.TransformProjection)</td><td>Transforms a Vector3 by the given projection matrix (both ortho and perspective are supported)</td></tr>
<tr><td>static [`void TransformNoProjection(ref Vector3 vector, ref Matrix matrix, ref Vector3 result)`](VRageMath.TransformNoProjection)</td><td></td></tr>
<tr><td>static [`void RotateAndScale(ref Vector3 vector, ref Matrix matrix, ref Vector3 result)`](VRageMath.RotateAndScale)</td><td></td></tr>
<tr><td>static [`Vector3 RotateAndScale(Vector3 vector, Matrix matrix)`](VRageMath.RotateAndScale)</td><td></td></tr>
<tr><td>static [`Vector3 TransformNormal(Vector3 normal, Matrix matrix)`](VRageMath.TransformNormal)</td><td>Transforms a 3D vector normal by a matrix.</td></tr>
<tr><td>static [`Vector3 TransformNormal(Vector3 normal, MatrixD matrix)`](VRageMath.TransformNormal)</td><td>Transforms a 3D vector normal by a matrix.</td></tr>
<tr><td>static [`Vector3 TransformNormal(Vector3D normal, Matrix matrix)`](VRageMath.TransformNormal)</td><td>Transforms a 3D vector normal by a matrix.</td></tr>
<tr><td>static [`void TransformNormal(ref Vector3 normal, ref Matrix matrix, ref Vector3 result)`](VRageMath.TransformNormal)</td><td>Transforms a vector normal by a matrix.</td></tr>
<tr><td>static [`void TransformNormal(ref Vector3 normal, ref MatrixD matrix, ref Vector3 result)`](VRageMath.TransformNormal)</td><td></td></tr>
<tr><td>static [`void TransformNormal(ref Vector3 normal, ref MatrixI matrix, ref Vector3 result)`](VRageMath.TransformNormal)</td><td></td></tr>
<tr><td>static [`Vector3 TransformNormal(Vector3 normal, MyBlockOrientation orientation)`](VRageMath.TransformNormal)</td><td></td></tr>
<tr><td>static [`void TransformNormal(ref Vector3 normal, MyBlockOrientation orientation, ref Vector3 result)`](VRageMath.TransformNormal)</td><td></td></tr>
<tr><td>static [`Vector3 TransformNormal(Vector3 normal, ref Matrix matrix)`](VRageMath.TransformNormal)</td><td></td></tr>
<tr><td>static [`Vector3 Transform(Vector3 value, Quaternion rotation)`](VRageMath.Transform)</td><td>Transforms a Vector3 by a specified Quaternion rotation.</td></tr>
<tr><td>static [`void Transform(ref Vector3 value, ref Quaternion rotation, ref Vector3 result)`](VRageMath.Transform)</td><td>Transforms a Vector3 by a specified Quaternion rotation.</td></tr>
<tr><td>static [`void Transform(Vector3[] sourceArray, ref Matrix matrix, Vector3[] destinationArray)`](VRageMath.Transform)</td><td>Transforms a source array of Vector3s by a specified Matrix and writes the results to an existing destination array.</td></tr>
<tr><td>static [`void Transform(Vector3[] sourceArray, int sourceIndex, ref Matrix matrix, Vector3[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)</td><td>Applies a specified transform Matrix to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.</td></tr>
<tr><td>static [`void TransformNormal(Vector3[] sourceArray, ref Matrix matrix, Vector3[] destinationArray)`](VRageMath.TransformNormal)</td><td>Transforms an array of 3D vector normals by a specified Matrix.</td></tr>
<tr><td>static [`void TransformNormal(Vector3[] sourceArray, int sourceIndex, ref Matrix matrix, Vector3[] destinationArray, int destinationIndex, int length)`](VRageMath.TransformNormal)</td><td>Transforms a specified range in an array of 3D vector normals by a specified Matrix and writes the results to a specified range in a destination array.</td></tr>
<tr><td>static [`void Transform(Vector3[] sourceArray, ref Quaternion rotation, Vector3[] destinationArray)`](VRageMath.Transform)</td><td>Transforms a source array of Vector3s by a specified Quaternion rotation and writes the results to an existing destination array.</td></tr>
<tr><td>static [`void Transform(Vector3[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector3[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)</td><td>Applies a specified Quaternion rotation to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.</td></tr>
<tr><td>static [`Vector3 Negate(Vector3 value)`](VRageMath.Negate)</td><td>Returns a vector pointing in the opposite direction.</td></tr>
</table>
