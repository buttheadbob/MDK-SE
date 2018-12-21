← [Index](index)
# Vector3D Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with three components.
### Fields
|Member|Description|
|---|---|
|[`double X`](VRageMath.X)|Gets or sets the x-component of the vector.|
|[`double Y`](VRageMath.Y)|Gets or sets the y-component of the vector.|
|[`double Z`](VRageMath.Z)|Gets or sets the z-component of the vector.|
|static [`VRageMath.Vector3D Zero`](VRageMath.Zero)||
|static [`VRageMath.Vector3D One`](VRageMath.One)||
|static [`VRageMath.Vector3D Half`](VRageMath.Half)||
|static [`VRageMath.Vector3D PositiveInfinity`](VRageMath.PositiveInfinity)||
|static [`VRageMath.Vector3D NegativeInfinity`](VRageMath.NegativeInfinity)||
|static [`VRageMath.Vector3D UnitX`](VRageMath.UnitX)||
|static [`VRageMath.Vector3D UnitY`](VRageMath.UnitY)||
|static [`VRageMath.Vector3D UnitZ`](VRageMath.UnitZ)||
|static [`VRageMath.Vector3D Up`](VRageMath.Up)||
|static [`VRageMath.Vector3D Down`](VRageMath.Down)||
|static [`VRageMath.Vector3D Right`](VRageMath.Right)||
|static [`VRageMath.Vector3D Left`](VRageMath.Left)||
|static [`VRageMath.Vector3D Forward`](VRageMath.Forward)||
|static [`VRageMath.Vector3D Backward`](VRageMath.Backward)||
|static [`VRageMath.Vector3D MaxValue`](VRageMath.MaxValue)||
|static [`VRageMath.Vector3D MinValue`](VRageMath.MinValue)||
### Properties
|Member|Description|
|---|---|
|[`double Sum`](VRageMath.Sum)||
|[`double Volume`](VRageMath.Volume)||
### Methods
|Member|Description|
|---|---|
|static [`void TransformNormal(ref VRageMath.Vector3D, ref VRageMath.MatrixI, ref VRageMath.Vector3D)`](VRageMath.TransformNormal)||
|static [`VRageMath.Vector3D TransformNormal(VRageMath.Vector3D, VRageMath.MyBlockOrientation)`](VRageMath.TransformNormal)||
|static [`void TransformNormal(ref VRageMath.Vector3D, VRageMath.MyBlockOrientation, ref VRageMath.Vector3D)`](VRageMath.TransformNormal)||
|static [`VRageMath.Vector3D TransformNormal(VRageMath.Vector3D, ref VRageMath.MatrixD)`](VRageMath.TransformNormal)||
|static [`VRageMath.Vector3D Transform(VRageMath.Vector3D, VRageMath.Quaternion)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|static [`void Transform(ref VRageMath.Vector3D, ref VRageMath.Quaternion, ref VRageMath.Vector3D)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|static [`void Rotate(ref VRageMath.Vector3D, ref VRageMath.MatrixD, ref VRageMath.Vector3D)`](VRageMath.Rotate)||
|static [`VRageMath.Vector3D Rotate(VRageMath.Vector3D, VRageMath.MatrixD)`](VRageMath.Rotate)||
|static [`void Transform(VRageMath.Vector3D[], ref VRageMath.MatrixD, VRageMath.Vector3D[])`](VRageMath.Transform)|Transforms a source array of Vector3s by a specified Matrix and writes the results to an existing destination array.|
|static [`void Transform(VRageMath.Vector3D[], ref VRageMath.MatrixD, *VRageMath.Vector3D)`](VRageMath.Transform)||
|static [`void Transform(VRageMath.Vector3D[], int, ref VRageMath.Matrix, VRageMath.Vector3D[], int, int)`](VRageMath.Transform)|Applies a specified transform Matrix to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|static [`void TransformNormal(VRageMath.Vector3D[], ref VRageMath.Matrix, VRageMath.Vector3D[])`](VRageMath.TransformNormal)|Transforms an array of 3D vector normals by a specified Matrix.|
|static [`void TransformNormal(VRageMath.Vector3D[], ref VRageMath.Matrix, *VRageMath.Vector3D)`](VRageMath.TransformNormal)||
|static [`void TransformNormal(VRageMath.Vector3D[], int, ref VRageMath.Matrix, VRageMath.Vector3D[], int, int)`](VRageMath.TransformNormal)|Transforms a specified range in an array of 3D vector normals by a specified Matrix and writes the results to a specified range in a destination array.|
|static [`void Transform(VRageMath.Vector3D[], ref VRageMath.Quaternion, VRageMath.Vector3D[])`](VRageMath.Transform)|Transforms a source array of Vector3s by a specified Quaternion rotation and writes the results to an existing destination array.|
|static [`void Transform(VRageMath.Vector3D[], int, ref VRageMath.Quaternion, VRageMath.Vector3D[], int, int)`](VRageMath.Transform)|Applies a specified Quaternion rotation to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|static [`VRageMath.Vector3D Negate(VRageMath.Vector3D)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`void Negate(ref VRageMath.Vector3D, ref VRageMath.Vector3D)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`VRageMath.Vector3D Add(VRageMath.Vector3D, VRageMath.Vector3D)`](VRageMath.Add)|Adds two vectors.|
|static [`void Add(ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref VRageMath.Vector3D)`](VRageMath.Add)|Adds two vectors.|
|static [`VRageMath.Vector3D Subtract(VRageMath.Vector3D, VRageMath.Vector3D)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`void Subtract(ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref VRageMath.Vector3D)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`VRageMath.Vector3D Multiply(VRageMath.Vector3D, VRageMath.Vector3D)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`void Multiply(ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref VRageMath.Vector3D)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`VRageMath.Vector3D Multiply(VRageMath.Vector3D, double)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`void Multiply(ref VRageMath.Vector3D, double, ref VRageMath.Vector3D)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`VRageMath.Vector3D Divide(VRageMath.Vector3D, VRageMath.Vector3D)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`void Divide(ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref VRageMath.Vector3D)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`VRageMath.Vector3D Divide(VRageMath.Vector3D, double)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static [`void Divide(ref VRageMath.Vector3D, double, ref VRageMath.Vector3D)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static [`VRageMath.Vector3D CalculatePerpendicularVector(VRageMath.Vector3D)`](VRageMath.CalculatePerpendicularVector)||
|[`void CalculatePerpendicularVector(ref VRageMath.Vector3D)`](VRageMath.CalculatePerpendicularVector)||
|static [`void GetAzimuthAndElevation(VRageMath.Vector3D, ref double, ref double)`](VRageMath.GetAzimuthAndElevation)||
|static [`void CreateFromAzimuthAndElevation(double, double, ref VRageMath.Vector3D)`](VRageMath.CreateFromAzimuthAndElevation)||
|[`long VolumeInt(double)`](VRageMath.VolumeInt)||
|[`bool IsInsideInclusive(ref VRageMath.Vector3D, ref VRageMath.Vector3D)`](VRageMath.IsInsideInclusive)||
|static [`VRageMath.Vector3D SwapYZCoordinates(VRageMath.Vector3D)`](VRageMath.SwapYZCoordinates)||
|[`double GetDim(int)`](VRageMath.GetDim)||
|[`void SetDim(int, double)`](VRageMath.SetDim)||
|static [`VRageMath.Vector3I Round(VRageMath.Vector3D)`](VRageMath.Round)||
|static [`VRageMath.Vector3I Floor(VRageMath.Vector3D)`](VRageMath.Floor)||
|static [`void Fract(ref VRageMath.Vector3D, ref VRageMath.Vector3D)`](VRageMath.Fract)||
|static [`VRageMath.Vector3D Round(VRageMath.Vector3D, int)`](VRageMath.Round)||
|static [`void Abs(ref VRageMath.Vector3D, ref VRageMath.Vector3D)`](VRageMath.Abs)||
|static [`VRageMath.Vector3D ProjectOnPlane(ref VRageMath.Vector3D, ref VRageMath.Vector3D)`](VRageMath.ProjectOnPlane)|Projects given vector on plane specified by it's normal.|
|static [`VRageMath.Vector3D ProjectOnVector(ref VRageMath.Vector3D, ref VRageMath.Vector3D)`](VRageMath.ProjectOnVector)|Projects vector on another vector resulting in new vector in guided vector's direction with different length.|
|static [`VRageMath.Vector3D Abs(VRageMath.Vector3D)`](VRageMath.Abs)||
|static [`VRageMath.Vector3D Sign(VRageMath.Vector3D)`](VRageMath.Sign)||
|static [`VRageMath.Vector3D SignNonZero(VRageMath.Vector3D)`](VRageMath.SignNonZero)|Returns per component sign, never returns zero. For zero component returns sign 1. Faster than Sign.|
|[`void Interpolate3(VRageMath.Vector3D, VRageMath.Vector3D, double)`](VRageMath.Interpolate3)||
|[`bool IsValid()`](VRageMath.IsValid)||
|[`void AssertIsValid()`](VRageMath.AssertIsValid)||
|static [`bool IsUnit(ref VRageMath.Vector3D)`](VRageMath.IsUnit)||
|static [`bool ArePerpendicular(ref VRageMath.Vector3D, ref VRageMath.Vector3D)`](VRageMath.ArePerpendicular)||
|static [`bool IsZero(VRageMath.Vector3D)`](VRageMath.IsZero)||
|static [`bool IsZero(VRageMath.Vector3D, double)`](VRageMath.IsZero)||
|static [`VRageMath.Vector3D IsZeroVector(VRageMath.Vector3D)`](VRageMath.IsZeroVector)||
|static [`VRageMath.Vector3D IsZeroVector(VRageMath.Vector3D, double)`](VRageMath.IsZeroVector)||
|static [`VRageMath.Vector3D Step(VRageMath.Vector3D)`](VRageMath.Step)||
|[`string ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|static [`bool TryParse(string, ref VRageMath.Vector3D)`](VRageMath.TryParse)||
|[`string ToString(string)`](VRageMath.ToString)||
|[`bool Equals(VRageMath.Vector3D)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector3.|
|[`bool Equals(VRageMath.Vector3D, double)`](VRageMath.Equals)||
|[`bool Equals(System.Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`long GetHash()`](VRageMath.GetHash)|Gets the hash code of the vector object.|
|[`double Length()`](VRageMath.Length)|Calculates the length of the vector.|
|[`double LengthSquared()`](VRageMath.LengthSquared)|Calculates the length of the vector squared.|
|static [`double Distance(VRageMath.Vector3D, VRageMath.Vector3D)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`double Distance(VRageMath.Vector3D, VRageMath.Vector3)`](VRageMath.Distance)||
|static [`double Distance(VRageMath.Vector3, VRageMath.Vector3D)`](VRageMath.Distance)||
|static [`void Distance(ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref double)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`double DistanceSquared(VRageMath.Vector3D, VRageMath.Vector3D)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`void DistanceSquared(ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref double)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`double RectangularDistance(VRageMath.Vector3D, VRageMath.Vector3D)`](VRageMath.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|static [`double RectangularDistance(ref VRageMath.Vector3D, ref VRageMath.Vector3D)`](VRageMath.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|static [`double Dot(VRageMath.Vector3D, VRageMath.Vector3D)`](VRageMath.Dot)|Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|static [`double Dot(VRageMath.Vector3D, VRageMath.Vector3)`](VRageMath.Dot)||
|static [`void Dot(ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref double)`](VRageMath.Dot)|Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|static [`void Dot(ref VRageMath.Vector3D, ref VRageMath.Vector3, ref double)`](VRageMath.Dot)||
|static [`void Dot(ref VRageMath.Vector3, ref VRageMath.Vector3D, ref double)`](VRageMath.Dot)||
|[`double Dot(VRageMath.Vector3D)`](VRageMath.Dot)||
|[`double Dot(VRageMath.Vector3)`](VRageMath.Dot)||
|[`double Dot(ref VRageMath.Vector3D)`](VRageMath.Dot)||
|[`VRageMath.Vector3D Cross(VRageMath.Vector3D)`](VRageMath.Cross)||
|[`double Normalize()`](VRageMath.Normalize)|Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`VRageMath.Vector3D Normalize(VRageMath.Vector3D)`](VRageMath.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`void Normalize(ref VRageMath.Vector3D, ref VRageMath.Vector3D)`](VRageMath.Normalize)|Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`VRageMath.Vector3D Cross(VRageMath.Vector3D, VRageMath.Vector3D)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|static [`void Cross(ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref VRageMath.Vector3D)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|static [`VRageMath.Vector3D Reflect(VRageMath.Vector3D, VRageMath.Vector3D)`](VRageMath.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|static [`void Reflect(ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref VRageMath.Vector3D)`](VRageMath.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|static [`VRageMath.Vector3D Reject(VRageMath.Vector3D, VRageMath.Vector3D)`](VRageMath.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|static [`void Reject(ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref VRageMath.Vector3D)`](VRageMath.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|[`double Min()`](VRageMath.Min)|Returns the component of the vector that is smallest of all the three components.|
|[`double AbsMin()`](VRageMath.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|[`double Max()`](VRageMath.Max)|Returns the component of the vector that is largest of all the three components.|
|[`double AbsMax()`](VRageMath.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|[`int AbsMaxComponent()`](VRageMath.AbsMaxComponent)||
|static [`VRageMath.Vector3D Min(VRageMath.Vector3D, VRageMath.Vector3D)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`void Min(ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref VRageMath.Vector3D)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`VRageMath.Vector3D Max(VRageMath.Vector3D, VRageMath.Vector3D)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`void Max(ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref VRageMath.Vector3D)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`void MinMax(ref VRageMath.Vector3D, ref VRageMath.Vector3D)`](VRageMath.MinMax)|Separates minimal and maximal values of any two input vectors|
|static [`VRageMath.Vector3D DominantAxisProjection(VRageMath.Vector3D)`](VRageMath.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|static [`void DominantAxisProjection(ref VRageMath.Vector3D, ref VRageMath.Vector3D)`](VRageMath.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved into a user-specified variable.|
|static [`VRageMath.Vector3D Clamp(VRageMath.Vector3D, VRageMath.Vector3D, VRageMath.Vector3D)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`void Clamp(ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref VRageMath.Vector3D)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`VRageMath.Vector3D ClampToSphere(VRageMath.Vector3D, double)`](VRageMath.ClampToSphere)||
|static [`void ClampToSphere(ref VRageMath.Vector3D, double)`](VRageMath.ClampToSphere)||
|static [`VRageMath.Vector3D Lerp(VRageMath.Vector3D, VRageMath.Vector3D, double)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`void Lerp(ref VRageMath.Vector3D, ref VRageMath.Vector3D, double, ref VRageMath.Vector3D)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`VRageMath.Vector3D Barycentric(VRageMath.Vector3D, VRageMath.Vector3D, VRageMath.Vector3D, double, double)`](VRageMath.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in Barycentric coordinates relative to a 3D triangle.|
|static [`void Barycentric(ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref VRageMath.Vector3D, double, double, ref VRageMath.Vector3D)`](VRageMath.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 3D triangle.|
|static [`void Barycentric(VRageMath.Vector3D, VRageMath.Vector3D, VRageMath.Vector3D, VRageMath.Vector3D, ref double, ref double, ref double)`](VRageMath.Barycentric)|Compute barycentric coordinates (u, v, w) for point p with respect to triangle (a, b, c) From : Real-Time Collision Detection, Christer Ericson, CRC Press 3.4 Barycentric Coordinates|
|static [`VRageMath.Vector3D SmoothStep(VRageMath.Vector3D, VRageMath.Vector3D, double)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`void SmoothStep(ref VRageMath.Vector3D, ref VRageMath.Vector3D, double, ref VRageMath.Vector3D)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`VRageMath.Vector3D CatmullRom(VRageMath.Vector3D, VRageMath.Vector3D, VRageMath.Vector3D, VRageMath.Vector3D, double)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`void CatmullRom(ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref VRageMath.Vector3D, double, ref VRageMath.Vector3D)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`VRageMath.Vector3D Hermite(VRageMath.Vector3D, VRageMath.Vector3D, VRageMath.Vector3D, VRageMath.Vector3D, double)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`void Hermite(ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref VRageMath.Vector3D, double, ref VRageMath.Vector3D)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`VRageMath.Vector3D Transform(VRageMath.Vector3D, VRageMath.MatrixD)`](VRageMath.Transform)|Transforms a 3D vector by the given matrix.|
|static [`VRageMath.Vector3D Transform(VRageMath.Vector3, VRageMath.MatrixD)`](VRageMath.Transform)||
|static [`VRageMath.Vector3D Transform(VRageMath.Vector3D, VRageMath.Matrix)`](VRageMath.Transform)|Transforms a 3D vector by the given matrix.|
|static [`VRageMath.Vector3D Transform(VRageMath.Vector3D, ref VRageMath.MatrixD)`](VRageMath.Transform)||
|static [`void Transform(ref VRageMath.Vector3D, ref VRageMath.MatrixD, ref VRageMath.Vector3D)`](VRageMath.Transform)|Transforms a Vector3 by the given Matrix.|
|static [`void Transform(ref VRageMath.Vector3, ref VRageMath.MatrixD, ref VRageMath.Vector3D)`](VRageMath.Transform)||
|static [`void TransformNoProjection(ref VRageMath.Vector3D, ref VRageMath.MatrixD, ref VRageMath.Vector3D)`](VRageMath.TransformNoProjection)||
|static [`void RotateAndScale(ref VRageMath.Vector3D, ref VRageMath.MatrixD, ref VRageMath.Vector3D)`](VRageMath.RotateAndScale)||
|static [`void Transform(ref VRageMath.Vector3D, ref VRageMath.MatrixI, ref VRageMath.Vector3D)`](VRageMath.Transform)||
|static [`VRageMath.Vector3D TransformNormal(VRageMath.Vector3D, VRageMath.Matrix)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|static [`VRageMath.Vector3D TransformNormal(VRageMath.Vector3, VRageMath.MatrixD)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|static [`VRageMath.Vector3D TransformNormal(VRageMath.Vector3D, VRageMath.MatrixD)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|static [`void TransformNormal(ref VRageMath.Vector3D, ref VRageMath.MatrixD, ref VRageMath.Vector3D)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|static [`void TransformNormal(ref VRageMath.Vector3, ref VRageMath.MatrixD, ref VRageMath.Vector3D)`](VRageMath.TransformNormal)||
