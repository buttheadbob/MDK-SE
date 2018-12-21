← [Index](index)
# Vector3 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with three components.
### Fields
|Member|Description|
|---|---|
|[`float X`](VRageMath.X)|Gets or sets the x-component of the vector.|
|[`float Y`](VRageMath.Y)|Gets or sets the y-component of the vector.|
|[`float Z`](VRageMath.Z)|Gets or sets the z-component of the vector.|
|static [`Vector3 Zero`](VRageMath.Zero)||
|static [`Vector3 One`](VRageMath.One)||
|static [`Vector3 MinusOne`](VRageMath.MinusOne)||
|static [`Vector3 Half`](VRageMath.Half)||
|static [`Vector3 PositiveInfinity`](VRageMath.PositiveInfinity)||
|static [`Vector3 NegativeInfinity`](VRageMath.NegativeInfinity)||
|static [`Vector3 UnitX`](VRageMath.UnitX)||
|static [`Vector3 UnitY`](VRageMath.UnitY)||
|static [`Vector3 UnitZ`](VRageMath.UnitZ)||
|static [`Vector3 Up`](VRageMath.Up)||
|static [`Vector3 Down`](VRageMath.Down)||
|static [`Vector3 Right`](VRageMath.Right)||
|static [`Vector3 Left`](VRageMath.Left)||
|static [`Vector3 Forward`](VRageMath.Forward)||
|static [`Vector3 Backward`](VRageMath.Backward)||
|static [`Vector3 MaxValue`](VRageMath.MaxValue)||
|static [`Vector3 MinValue`](VRageMath.MinValue)||
|static [`Vector3 Invalid`](VRageMath.Invalid)||
### Properties
|Member|Description|
|---|---|
|[`float Sum`](VRageMath.Sum)||
|[`float Volume`](VRageMath.Volume)||
### Methods
|Member|Description|
|---|---|
|static [`void Negate(ref Vector3 value, ref Vector3 result)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`Vector3 Add(Vector3 value1, Vector3 value2)`](VRageMath.Add)|Adds two vectors.|
|static [`void Add(ref Vector3 value1, ref Vector3 value2, ref Vector3 result)`](VRageMath.Add)|Adds two vectors.|
|static [`Vector3 Subtract(Vector3 value1, Vector3 value2)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`void Subtract(ref Vector3 value1, ref Vector3 value2, ref Vector3 result)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`Vector3 Multiply(Vector3 value1, Vector3 value2)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`void Multiply(ref Vector3 value1, ref Vector3 value2, ref Vector3 result)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`Vector3 Multiply(Vector3 value1, float scaleFactor)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`void Multiply(ref Vector3 value1, float scaleFactor, ref Vector3 result)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`Vector3 Divide(Vector3 value1, Vector3 value2)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`void Divide(ref Vector3 value1, ref Vector3 value2, ref Vector3 result)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`Vector3 Divide(Vector3 value1, float value2)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static [`void Divide(ref Vector3 value1, float value2, ref Vector3 result)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static [`Vector3 CalculatePerpendicularVector(Vector3 v)`](VRageMath.CalculatePerpendicularVector)||
|[`void CalculatePerpendicularVector(ref Vector3 result)`](VRageMath.CalculatePerpendicularVector)||
|static [`void GetAzimuthAndElevation(Vector3 v, ref float azimuth, ref float elevation)`](VRageMath.GetAzimuthAndElevation)||
|static [`void CreateFromAzimuthAndElevation(float azimuth, float elevation, ref Vector3 direction)`](VRageMath.CreateFromAzimuthAndElevation)||
|[`long VolumeInt(float multiplier)`](VRageMath.VolumeInt)||
|[`bool IsInsideInclusive(ref Vector3 min, ref Vector3 max)`](VRageMath.IsInsideInclusive)||
|static [`Vector3 SwapYZCoordinates(Vector3 v)`](VRageMath.SwapYZCoordinates)||
|[`float GetDim(int i)`](VRageMath.GetDim)||
|[`void SetDim(int i, float value)`](VRageMath.SetDim)||
|static [`Vector3 Ceiling(Vector3 v)`](VRageMath.Ceiling)||
|static [`Vector3 Floor(Vector3 v)`](VRageMath.Floor)||
|static [`Vector3 Round(Vector3 v)`](VRageMath.Round)||
|static [`Vector3 Round(Vector3 v, int numDecimals)`](VRageMath.Round)||
|static [`Vector3 ProjectOnPlane(ref Vector3 vec, ref Vector3 planeNormal)`](VRageMath.ProjectOnPlane)|Projects given vector on plane specified by it's normal.|
|static [`Vector3 ProjectOnVector(ref Vector3 vec, ref Vector3 guideVector)`](VRageMath.ProjectOnVector)|Projects vector on another vector resulting in new vector in guided vector's direction with different length.|
|static [`bool IsZero(ref Vector3 vec)`](VRageMath.IsZero)||
|[`void Divide(float divider)`](VRageMath.Divide)||
|[`void Multiply(float scale)`](VRageMath.Multiply)||
|[`void Add(Vector3 other)`](VRageMath.Add)||
|static [`Vector3 Abs(Vector3 value)`](VRageMath.Abs)||
|static [`Vector3 Sign(Vector3 value)`](VRageMath.Sign)||
|static [`Vector3 Sign(Vector3 value, float epsilon)`](VRageMath.Sign)||
|static [`Vector3 SignNonZero(Vector3 value)`](VRageMath.SignNonZero)|Returns per component sign, never returns zero. For zero component returns sign 1. Faster than Sign.|
|[`void Interpolate3(Vector3 v0, Vector3 v1, float rt)`](VRageMath.Interpolate3)||
|[`bool IsValid()`](VRageMath.IsValid)||
|[`void AssertIsValid()`](VRageMath.AssertIsValid)||
|static [`bool IsUnit(ref Vector3 value)`](VRageMath.IsUnit)||
|static [`bool ArePerpendicular(ref Vector3 a, ref Vector3 b)`](VRageMath.ArePerpendicular)||
|static [`bool IsZero(Vector3 value)`](VRageMath.IsZero)||
|static [`bool IsZero(Vector3 value, float epsilon)`](VRageMath.IsZero)||
|static [`Vector3 IsZeroVector(Vector3 value)`](VRageMath.IsZeroVector)||
|static [`Vector3 IsZeroVector(Vector3 value, float epsilon)`](VRageMath.IsZeroVector)||
|static [`Vector3 Step(Vector3 value)`](VRageMath.Step)||
|[`string ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`string ToString(string format)`](VRageMath.ToString)||
|[`bool Equals(Vector3 other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector3.|
|[`bool Equals(Vector3 other, float epsilon)`](VRageMath.Equals)||
|[`bool Equals(Object obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`long GetHash()`](VRageMath.GetHash)|Gets the hash code of the vector object.|
|[`float Length()`](VRageMath.Length)|Calculates the length of the vector.|
|[`float LengthSquared()`](VRageMath.LengthSquared)|Calculates the length of the vector squared.|
|static [`float Distance(Vector3 value1, Vector3 value2)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`void Distance(ref Vector3 value1, ref Vector3 value2, ref float result)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`float DistanceSquared(Vector3 value1, Vector3 value2)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`void DistanceSquared(ref Vector3 value1, ref Vector3 value2, ref float result)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`float RectangularDistance(Vector3 value1, Vector3 value2)`](VRageMath.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|static [`float RectangularDistance(ref Vector3 value1, ref Vector3 value2)`](VRageMath.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|static [`float Dot(Vector3 vector1, Vector3 vector2)`](VRageMath.Dot)|Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|static [`void Dot(ref Vector3 vector1, ref Vector3 vector2, ref float result)`](VRageMath.Dot)|Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[`float Dot(Vector3 v)`](VRageMath.Dot)||
|[`float Dot(ref Vector3 v)`](VRageMath.Dot)||
|[`Vector3 Cross(Vector3 v)`](VRageMath.Cross)||
|[`float Normalize()`](VRageMath.Normalize)|Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`Vector3 Normalize(Vector3 value)`](VRageMath.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`Vector3 Normalize(Vector3D value)`](VRageMath.Normalize)||
|static [`bool GetNormalized(ref Vector3 value)`](VRageMath.GetNormalized)||
|static [`void Normalize(ref Vector3 value, ref Vector3 result)`](VRageMath.Normalize)|Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`Vector3 Cross(Vector3 vector1, Vector3 vector2)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|static [`void Cross(ref Vector3 vector1, ref Vector3 vector2, ref Vector3 result)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|static [`Vector3 Reflect(Vector3 vector, Vector3 normal)`](VRageMath.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|static [`void Reflect(ref Vector3 vector, ref Vector3 normal, ref Vector3 result)`](VRageMath.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|static [`Vector3 Reject(Vector3 vector, Vector3 direction)`](VRageMath.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|static [`void Reject(ref Vector3 vector, ref Vector3 direction, ref Vector3 result)`](VRageMath.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|[`float Min()`](VRageMath.Min)|Returns the component of the vector that is smallest of all the three components.|
|[`float AbsMin()`](VRageMath.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|[`float Max()`](VRageMath.Max)|Returns the component of the vector that is largest of all the three components.|
|[`Vector3 MaxAbsComponent()`](VRageMath.MaxAbsComponent)|Keeps only component with maximal absolute, others are set to zero.|
|[`float AbsMax()`](VRageMath.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|static [`Vector3 Min(Vector3 value1, Vector3 value2)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`void Min(ref Vector3 value1, ref Vector3 value2, ref Vector3 result)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`Vector3 Max(Vector3 value1, Vector3 value2)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`void Max(ref Vector3 value1, ref Vector3 value2, ref Vector3 result)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`void MinMax(ref Vector3 min, ref Vector3 max)`](VRageMath.MinMax)|Separates minimal and maximal values of any two input vectors|
|static [`Vector3 DominantAxisProjection(Vector3 value1)`](VRageMath.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|static [`void DominantAxisProjection(ref Vector3 value1, ref Vector3 result)`](VRageMath.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved into a user-specified variable.|
|static [`Vector3 Clamp(Vector3 value1, Vector3 min, Vector3 max)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`void Clamp(ref Vector3 value1, ref Vector3 min, ref Vector3 max, ref Vector3 result)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`Vector3 ClampToSphere(Vector3 vector, float radius)`](VRageMath.ClampToSphere)||
|static [`void ClampToSphere(ref Vector3 vector, float radius)`](VRageMath.ClampToSphere)||
|static [`Vector3 Lerp(Vector3 value1, Vector3 value2, float amount)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`void Lerp(ref Vector3 value1, ref Vector3 value2, float amount, ref Vector3 result)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`Vector3 Barycentric(Vector3 value1, Vector3 value2, Vector3 value3, float amount1, float amount2)`](VRageMath.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in Barycentric coordinates relative to a 3D triangle.|
|static [`void Barycentric(ref Vector3 value1, ref Vector3 value2, ref Vector3 value3, float amount1, float amount2, ref Vector3 result)`](VRageMath.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 3D triangle.|
|static [`void Barycentric(Vector3 p, Vector3 a, Vector3 b, Vector3 c, ref float u, ref float v, ref float w)`](VRageMath.Barycentric)|Compute barycentric coordinates (u, v, w) for point p with respect to triangle (a, b, c) From : Real-Time Collision Detection, Christer Ericson, CRC Press 3.4 Barycentric Coordinates|
|static [`float TriangleArea(Vector3 v1, Vector3 v2, Vector3 v3)`](VRageMath.TriangleArea)||
|static [`float TriangleArea(ref Vector3 v1, ref Vector3 v2, ref Vector3 v3)`](VRageMath.TriangleArea)||
|static [`Vector3 SmoothStep(Vector3 value1, Vector3 value2, float amount)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`void SmoothStep(ref Vector3 value1, ref Vector3 value2, float amount, ref Vector3 result)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`Vector3 CatmullRom(Vector3 value1, Vector3 value2, Vector3 value3, Vector3 value4, float amount)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`void CatmullRom(ref Vector3 value1, ref Vector3 value2, ref Vector3 value3, ref Vector3 value4, float amount, ref Vector3 result)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`Vector3 Hermite(Vector3 value1, Vector3 tangent1, Vector3 value2, Vector3 tangent2, float amount)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`void Hermite(ref Vector3 value1, ref Vector3 tangent1, ref Vector3 value2, ref Vector3 tangent2, float amount, ref Vector3 result)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`Vector3 Transform(Vector3 position, Matrix matrix)`](VRageMath.Transform)|Transforms a 3D vector by the given matrix.|
|static [`Vector3D Transform(Vector3 position, MatrixD matrix)`](VRageMath.Transform)|Transforms a 3D vector by the given matrix.|
|static [`Vector3 Transform(Vector3 position, ref Matrix matrix)`](VRageMath.Transform)||
|static [`void Transform(ref Vector3 position, ref Matrix matrix, ref Vector3 result)`](VRageMath.Transform)|Transforms a Vector3 by the given Matrix.|
|static [`void Transform(ref Vector3 position, ref MatrixI matrix, ref Vector3 result)`](VRageMath.Transform)||
|static [`void TransformProjection(ref Vector3 position, ref Matrix matrix, ref Vector3 result)`](VRageMath.TransformProjection)|Transforms a Vector3 by the given projection matrix (both ortho and perspective are supported)|
|static [`void TransformNoProjection(ref Vector3 vector, ref Matrix matrix, ref Vector3 result)`](VRageMath.TransformNoProjection)||
|static [`void RotateAndScale(ref Vector3 vector, ref Matrix matrix, ref Vector3 result)`](VRageMath.RotateAndScale)||
|static [`Vector3 RotateAndScale(Vector3 vector, Matrix matrix)`](VRageMath.RotateAndScale)||
|static [`Vector3 TransformNormal(Vector3 normal, Matrix matrix)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|static [`Vector3 TransformNormal(Vector3 normal, MatrixD matrix)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|static [`Vector3 TransformNormal(Vector3D normal, Matrix matrix)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|static [`void TransformNormal(ref Vector3 normal, ref Matrix matrix, ref Vector3 result)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|static [`void TransformNormal(ref Vector3 normal, ref MatrixD matrix, ref Vector3 result)`](VRageMath.TransformNormal)||
|static [`void TransformNormal(ref Vector3 normal, ref MatrixI matrix, ref Vector3 result)`](VRageMath.TransformNormal)||
|static [`Vector3 TransformNormal(Vector3 normal, MyBlockOrientation orientation)`](VRageMath.TransformNormal)||
|static [`void TransformNormal(ref Vector3 normal, MyBlockOrientation orientation, ref Vector3 result)`](VRageMath.TransformNormal)||
|static [`Vector3 TransformNormal(Vector3 normal, ref Matrix matrix)`](VRageMath.TransformNormal)||
|static [`Vector3 Transform(Vector3 value, Quaternion rotation)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|static [`void Transform(ref Vector3 value, ref Quaternion rotation, ref Vector3 result)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|static [`void Transform(Vector3[] sourceArray, ref Matrix matrix, Vector3[] destinationArray)`](VRageMath.Transform)|Transforms a source array of Vector3s by a specified Matrix and writes the results to an existing destination array.|
|static [`void Transform(Vector3[] sourceArray, int sourceIndex, ref Matrix matrix, Vector3[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)|Applies a specified transform Matrix to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|static [`void TransformNormal(Vector3[] sourceArray, ref Matrix matrix, Vector3[] destinationArray)`](VRageMath.TransformNormal)|Transforms an array of 3D vector normals by a specified Matrix.|
|static [`void TransformNormal(Vector3[] sourceArray, int sourceIndex, ref Matrix matrix, Vector3[] destinationArray, int destinationIndex, int length)`](VRageMath.TransformNormal)|Transforms a specified range in an array of 3D vector normals by a specified Matrix and writes the results to a specified range in a destination array.|
|static [`void Transform(Vector3[] sourceArray, ref Quaternion rotation, Vector3[] destinationArray)`](VRageMath.Transform)|Transforms a source array of Vector3s by a specified Quaternion rotation and writes the results to an existing destination array.|
|static [`void Transform(Vector3[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector3[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)|Applies a specified Quaternion rotation to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|static [`Vector3 Negate(Vector3 value)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
