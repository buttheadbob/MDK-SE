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
|static [`VRageMath.Vector3 Zero`](VRageMath.Zero)||
|static [`VRageMath.Vector3 One`](VRageMath.One)||
|static [`VRageMath.Vector3 MinusOne`](VRageMath.MinusOne)||
|static [`VRageMath.Vector3 Half`](VRageMath.Half)||
|static [`VRageMath.Vector3 PositiveInfinity`](VRageMath.PositiveInfinity)||
|static [`VRageMath.Vector3 NegativeInfinity`](VRageMath.NegativeInfinity)||
|static [`VRageMath.Vector3 UnitX`](VRageMath.UnitX)||
|static [`VRageMath.Vector3 UnitY`](VRageMath.UnitY)||
|static [`VRageMath.Vector3 UnitZ`](VRageMath.UnitZ)||
|static [`VRageMath.Vector3 Up`](VRageMath.Up)||
|static [`VRageMath.Vector3 Down`](VRageMath.Down)||
|static [`VRageMath.Vector3 Right`](VRageMath.Right)||
|static [`VRageMath.Vector3 Left`](VRageMath.Left)||
|static [`VRageMath.Vector3 Forward`](VRageMath.Forward)||
|static [`VRageMath.Vector3 Backward`](VRageMath.Backward)||
|static [`VRageMath.Vector3 MaxValue`](VRageMath.MaxValue)||
|static [`VRageMath.Vector3 MinValue`](VRageMath.MinValue)||
|static [`VRageMath.Vector3 Invalid`](VRageMath.Invalid)||
### Properties
|Member|Description|
|---|---|
|[`float Sum`](VRageMath.Sum)||
|[`float Volume`](VRageMath.Volume)||
### Methods
|Member|Description|
|---|---|
|static [`void Negate(ref VRageMath.Vector3, ref VRageMath.Vector3)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`VRageMath.Vector3 Add(VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.Add)|Adds two vectors.|
|static [`void Add(ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Vector3)`](VRageMath.Add)|Adds two vectors.|
|static [`VRageMath.Vector3 Subtract(VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`void Subtract(ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Vector3)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`VRageMath.Vector3 Multiply(VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`void Multiply(ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Vector3)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`VRageMath.Vector3 Multiply(VRageMath.Vector3, float)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`void Multiply(ref VRageMath.Vector3, float, ref VRageMath.Vector3)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`VRageMath.Vector3 Divide(VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`void Divide(ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Vector3)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`VRageMath.Vector3 Divide(VRageMath.Vector3, float)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static [`void Divide(ref VRageMath.Vector3, float, ref VRageMath.Vector3)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static [`VRageMath.Vector3 CalculatePerpendicularVector(VRageMath.Vector3)`](VRageMath.CalculatePerpendicularVector)||
|[`void CalculatePerpendicularVector(ref VRageMath.Vector3)`](VRageMath.CalculatePerpendicularVector)||
|static [`void GetAzimuthAndElevation(VRageMath.Vector3, ref float, ref float)`](VRageMath.GetAzimuthAndElevation)||
|static [`void CreateFromAzimuthAndElevation(float, float, ref VRageMath.Vector3)`](VRageMath.CreateFromAzimuthAndElevation)||
|[`long VolumeInt(float)`](VRageMath.VolumeInt)||
|[`bool IsInsideInclusive(ref VRageMath.Vector3, ref VRageMath.Vector3)`](VRageMath.IsInsideInclusive)||
|static [`VRageMath.Vector3 SwapYZCoordinates(VRageMath.Vector3)`](VRageMath.SwapYZCoordinates)||
|[`float GetDim(int)`](VRageMath.GetDim)||
|[`void SetDim(int, float)`](VRageMath.SetDim)||
|static [`VRageMath.Vector3 Ceiling(VRageMath.Vector3)`](VRageMath.Ceiling)||
|static [`VRageMath.Vector3 Floor(VRageMath.Vector3)`](VRageMath.Floor)||
|static [`VRageMath.Vector3 Round(VRageMath.Vector3)`](VRageMath.Round)||
|static [`VRageMath.Vector3 Round(VRageMath.Vector3, int)`](VRageMath.Round)||
|static [`VRageMath.Vector3 ProjectOnPlane(ref VRageMath.Vector3, ref VRageMath.Vector3)`](VRageMath.ProjectOnPlane)|Projects given vector on plane specified by it's normal.|
|static [`VRageMath.Vector3 ProjectOnVector(ref VRageMath.Vector3, ref VRageMath.Vector3)`](VRageMath.ProjectOnVector)|Projects vector on another vector resulting in new vector in guided vector's direction with different length.|
|static [`bool IsZero(ref VRageMath.Vector3)`](VRageMath.IsZero)||
|[`void Divide(float)`](VRageMath.Divide)||
|[`void Multiply(float)`](VRageMath.Multiply)||
|[`void Add(VRageMath.Vector3)`](VRageMath.Add)||
|static [`VRageMath.Vector3 Abs(VRageMath.Vector3)`](VRageMath.Abs)||
|static [`VRageMath.Vector3 Sign(VRageMath.Vector3)`](VRageMath.Sign)||
|static [`VRageMath.Vector3 Sign(VRageMath.Vector3, float)`](VRageMath.Sign)||
|static [`VRageMath.Vector3 SignNonZero(VRageMath.Vector3)`](VRageMath.SignNonZero)|Returns per component sign, never returns zero. For zero component returns sign 1. Faster than Sign.|
|[`void Interpolate3(VRageMath.Vector3, VRageMath.Vector3, float)`](VRageMath.Interpolate3)||
|[`bool IsValid()`](VRageMath.IsValid)||
|[`void AssertIsValid()`](VRageMath.AssertIsValid)||
|static [`bool IsUnit(ref VRageMath.Vector3)`](VRageMath.IsUnit)||
|static [`bool ArePerpendicular(ref VRageMath.Vector3, ref VRageMath.Vector3)`](VRageMath.ArePerpendicular)||
|static [`bool IsZero(VRageMath.Vector3)`](VRageMath.IsZero)||
|static [`bool IsZero(VRageMath.Vector3, float)`](VRageMath.IsZero)||
|static [`VRageMath.Vector3 IsZeroVector(VRageMath.Vector3)`](VRageMath.IsZeroVector)||
|static [`VRageMath.Vector3 IsZeroVector(VRageMath.Vector3, float)`](VRageMath.IsZeroVector)||
|static [`VRageMath.Vector3 Step(VRageMath.Vector3)`](VRageMath.Step)||
|[`string ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`string ToString(string)`](VRageMath.ToString)||
|[`bool Equals(VRageMath.Vector3)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector3.|
|[`bool Equals(VRageMath.Vector3, float)`](VRageMath.Equals)||
|[`bool Equals(System.Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`long GetHash()`](VRageMath.GetHash)|Gets the hash code of the vector object.|
|[`float Length()`](VRageMath.Length)|Calculates the length of the vector.|
|[`float LengthSquared()`](VRageMath.LengthSquared)|Calculates the length of the vector squared.|
|static [`float Distance(VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`void Distance(ref VRageMath.Vector3, ref VRageMath.Vector3, ref float)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`float DistanceSquared(VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`void DistanceSquared(ref VRageMath.Vector3, ref VRageMath.Vector3, ref float)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`float RectangularDistance(VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|static [`float RectangularDistance(ref VRageMath.Vector3, ref VRageMath.Vector3)`](VRageMath.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|static [`float Dot(VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.Dot)|Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|static [`void Dot(ref VRageMath.Vector3, ref VRageMath.Vector3, ref float)`](VRageMath.Dot)|Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[`float Dot(VRageMath.Vector3)`](VRageMath.Dot)||
|[`float Dot(ref VRageMath.Vector3)`](VRageMath.Dot)||
|[`VRageMath.Vector3 Cross(VRageMath.Vector3)`](VRageMath.Cross)||
|[`float Normalize()`](VRageMath.Normalize)|Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`VRageMath.Vector3 Normalize(VRageMath.Vector3)`](VRageMath.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`VRageMath.Vector3 Normalize(VRageMath.Vector3D)`](VRageMath.Normalize)||
|static [`bool GetNormalized(ref VRageMath.Vector3)`](VRageMath.GetNormalized)||
|static [`void Normalize(ref VRageMath.Vector3, ref VRageMath.Vector3)`](VRageMath.Normalize)|Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`VRageMath.Vector3 Cross(VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|static [`void Cross(ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Vector3)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|static [`VRageMath.Vector3 Reflect(VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|static [`void Reflect(ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Vector3)`](VRageMath.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|static [`VRageMath.Vector3 Reject(VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|static [`void Reject(ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Vector3)`](VRageMath.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|[`float Min()`](VRageMath.Min)|Returns the component of the vector that is smallest of all the three components.|
|[`float AbsMin()`](VRageMath.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|[`float Max()`](VRageMath.Max)|Returns the component of the vector that is largest of all the three components.|
|[`VRageMath.Vector3 MaxAbsComponent()`](VRageMath.MaxAbsComponent)|Keeps only component with maximal absolute, others are set to zero.|
|[`float AbsMax()`](VRageMath.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|static [`VRageMath.Vector3 Min(VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`void Min(ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Vector3)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`VRageMath.Vector3 Max(VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`void Max(ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Vector3)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`void MinMax(ref VRageMath.Vector3, ref VRageMath.Vector3)`](VRageMath.MinMax)|Separates minimal and maximal values of any two input vectors|
|static [`VRageMath.Vector3 DominantAxisProjection(VRageMath.Vector3)`](VRageMath.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|static [`void DominantAxisProjection(ref VRageMath.Vector3, ref VRageMath.Vector3)`](VRageMath.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved into a user-specified variable.|
|static [`VRageMath.Vector3 Clamp(VRageMath.Vector3, VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`void Clamp(ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Vector3)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`VRageMath.Vector3 ClampToSphere(VRageMath.Vector3, float)`](VRageMath.ClampToSphere)||
|static [`void ClampToSphere(ref VRageMath.Vector3, float)`](VRageMath.ClampToSphere)||
|static [`VRageMath.Vector3 Lerp(VRageMath.Vector3, VRageMath.Vector3, float)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`void Lerp(ref VRageMath.Vector3, ref VRageMath.Vector3, float, ref VRageMath.Vector3)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`VRageMath.Vector3 Barycentric(VRageMath.Vector3, VRageMath.Vector3, VRageMath.Vector3, float, float)`](VRageMath.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in Barycentric coordinates relative to a 3D triangle.|
|static [`void Barycentric(ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Vector3, float, float, ref VRageMath.Vector3)`](VRageMath.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 3D triangle.|
|static [`void Barycentric(VRageMath.Vector3, VRageMath.Vector3, VRageMath.Vector3, VRageMath.Vector3, ref float, ref float, ref float)`](VRageMath.Barycentric)|Compute barycentric coordinates (u, v, w) for point p with respect to triangle (a, b, c) From : Real-Time Collision Detection, Christer Ericson, CRC Press 3.4 Barycentric Coordinates|
|static [`float TriangleArea(VRageMath.Vector3, VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.TriangleArea)||
|static [`float TriangleArea(ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Vector3)`](VRageMath.TriangleArea)||
|static [`VRageMath.Vector3 SmoothStep(VRageMath.Vector3, VRageMath.Vector3, float)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`void SmoothStep(ref VRageMath.Vector3, ref VRageMath.Vector3, float, ref VRageMath.Vector3)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`VRageMath.Vector3 CatmullRom(VRageMath.Vector3, VRageMath.Vector3, VRageMath.Vector3, VRageMath.Vector3, float)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`void CatmullRom(ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Vector3, float, ref VRageMath.Vector3)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`VRageMath.Vector3 Hermite(VRageMath.Vector3, VRageMath.Vector3, VRageMath.Vector3, VRageMath.Vector3, float)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`void Hermite(ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Vector3, float, ref VRageMath.Vector3)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`VRageMath.Vector3 Transform(VRageMath.Vector3, VRageMath.Matrix)`](VRageMath.Transform)|Transforms a 3D vector by the given matrix.|
|static [`VRageMath.Vector3D Transform(VRageMath.Vector3, VRageMath.MatrixD)`](VRageMath.Transform)|Transforms a 3D vector by the given matrix.|
|static [`VRageMath.Vector3 Transform(VRageMath.Vector3, ref VRageMath.Matrix)`](VRageMath.Transform)||
|static [`void Transform(ref VRageMath.Vector3, ref VRageMath.Matrix, ref VRageMath.Vector3)`](VRageMath.Transform)|Transforms a Vector3 by the given Matrix.|
|static [`void Transform(ref VRageMath.Vector3, ref VRageMath.MatrixI, ref VRageMath.Vector3)`](VRageMath.Transform)||
|static [`void TransformProjection(ref VRageMath.Vector3, ref VRageMath.Matrix, ref VRageMath.Vector3)`](VRageMath.TransformProjection)|Transforms a Vector3 by the given projection matrix (both ortho and perspective are supported)|
|static [`void TransformNoProjection(ref VRageMath.Vector3, ref VRageMath.Matrix, ref VRageMath.Vector3)`](VRageMath.TransformNoProjection)||
|static [`void RotateAndScale(ref VRageMath.Vector3, ref VRageMath.Matrix, ref VRageMath.Vector3)`](VRageMath.RotateAndScale)||
|static [`VRageMath.Vector3 RotateAndScale(VRageMath.Vector3, VRageMath.Matrix)`](VRageMath.RotateAndScale)||
|static [`VRageMath.Vector3 TransformNormal(VRageMath.Vector3, VRageMath.Matrix)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|static [`VRageMath.Vector3 TransformNormal(VRageMath.Vector3, VRageMath.MatrixD)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|static [`VRageMath.Vector3 TransformNormal(VRageMath.Vector3D, VRageMath.Matrix)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|static [`void TransformNormal(ref VRageMath.Vector3, ref VRageMath.Matrix, ref VRageMath.Vector3)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|static [`void TransformNormal(ref VRageMath.Vector3, ref VRageMath.MatrixD, ref VRageMath.Vector3)`](VRageMath.TransformNormal)||
|static [`void TransformNormal(ref VRageMath.Vector3, ref VRageMath.MatrixI, ref VRageMath.Vector3)`](VRageMath.TransformNormal)||
|static [`VRageMath.Vector3 TransformNormal(VRageMath.Vector3, VRageMath.MyBlockOrientation)`](VRageMath.TransformNormal)||
|static [`void TransformNormal(ref VRageMath.Vector3, VRageMath.MyBlockOrientation, ref VRageMath.Vector3)`](VRageMath.TransformNormal)||
|static [`VRageMath.Vector3 TransformNormal(VRageMath.Vector3, ref VRageMath.Matrix)`](VRageMath.TransformNormal)||
|static [`VRageMath.Vector3 Transform(VRageMath.Vector3, VRageMath.Quaternion)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|static [`void Transform(ref VRageMath.Vector3, ref VRageMath.Quaternion, ref VRageMath.Vector3)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|static [`void Transform(VRageMath.Vector3[], ref VRageMath.Matrix, VRageMath.Vector3[])`](VRageMath.Transform)|Transforms a source array of Vector3s by a specified Matrix and writes the results to an existing destination array.|
|static [`void Transform(VRageMath.Vector3[], int, ref VRageMath.Matrix, VRageMath.Vector3[], int, int)`](VRageMath.Transform)|Applies a specified transform Matrix to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|static [`void TransformNormal(VRageMath.Vector3[], ref VRageMath.Matrix, VRageMath.Vector3[])`](VRageMath.TransformNormal)|Transforms an array of 3D vector normals by a specified Matrix.|
|static [`void TransformNormal(VRageMath.Vector3[], int, ref VRageMath.Matrix, VRageMath.Vector3[], int, int)`](VRageMath.TransformNormal)|Transforms a specified range in an array of 3D vector normals by a specified Matrix and writes the results to a specified range in a destination array.|
|static [`void Transform(VRageMath.Vector3[], ref VRageMath.Quaternion, VRageMath.Vector3[])`](VRageMath.Transform)|Transforms a source array of Vector3s by a specified Quaternion rotation and writes the results to an existing destination array.|
|static [`void Transform(VRageMath.Vector3[], int, ref VRageMath.Quaternion, VRageMath.Vector3[], int, int)`](VRageMath.Transform)|Applies a specified Quaternion rotation to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|static [`VRageMath.Vector3 Negate(VRageMath.Vector3)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
