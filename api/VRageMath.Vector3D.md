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
|static [`Vector3D Zero`](VRageMath.Zero)||
|static [`Vector3D One`](VRageMath.One)||
|static [`Vector3D Half`](VRageMath.Half)||
|static [`Vector3D PositiveInfinity`](VRageMath.PositiveInfinity)||
|static [`Vector3D NegativeInfinity`](VRageMath.NegativeInfinity)||
|static [`Vector3D UnitX`](VRageMath.UnitX)||
|static [`Vector3D UnitY`](VRageMath.UnitY)||
|static [`Vector3D UnitZ`](VRageMath.UnitZ)||
|static [`Vector3D Up`](VRageMath.Up)||
|static [`Vector3D Down`](VRageMath.Down)||
|static [`Vector3D Right`](VRageMath.Right)||
|static [`Vector3D Left`](VRageMath.Left)||
|static [`Vector3D Forward`](VRageMath.Forward)||
|static [`Vector3D Backward`](VRageMath.Backward)||
|static [`Vector3D MaxValue`](VRageMath.MaxValue)||
|static [`Vector3D MinValue`](VRageMath.MinValue)||
### Properties
|Member|Description|
|---|---|
|[`double Sum`](VRageMath.Sum)||
|[`double Volume`](VRageMath.Volume)||
### Methods
|Member|Description|
|---|---|
|static [`void TransformNormal(ref Vector3D normal, ref MatrixI matrix, ref Vector3D result)`](VRageMath.TransformNormal)||
|static [`Vector3D TransformNormal(Vector3D normal, MyBlockOrientation orientation)`](VRageMath.TransformNormal)||
|static [`void TransformNormal(ref Vector3D normal, MyBlockOrientation orientation, ref Vector3D result)`](VRageMath.TransformNormal)||
|static [`Vector3D TransformNormal(Vector3D normal, ref MatrixD matrix)`](VRageMath.TransformNormal)||
|static [`Vector3D Transform(Vector3D value, Quaternion rotation)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|static [`void Transform(ref Vector3D value, ref Quaternion rotation, ref Vector3D result)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|static [`void Rotate(ref Vector3D vector, ref MatrixD rotationMatrix, ref Vector3D result)`](VRageMath.Rotate)||
|static [`Vector3D Rotate(Vector3D vector, MatrixD rotationMatrix)`](VRageMath.Rotate)||
|static [`void Transform(Vector3D[] sourceArray, ref MatrixD matrix, Vector3D[] destinationArray)`](VRageMath.Transform)|Transforms a source array of Vector3s by a specified Matrix and writes the results to an existing destination array.|
|static [`void Transform(Vector3D[] sourceArray, ref MatrixD matrix, *Vector3D destinationArray)`](VRageMath.Transform)||
|static [`void Transform(Vector3D[] sourceArray, int sourceIndex, ref Matrix matrix, Vector3D[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)|Applies a specified transform Matrix to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|static [`void TransformNormal(Vector3D[] sourceArray, ref Matrix matrix, Vector3D[] destinationArray)`](VRageMath.TransformNormal)|Transforms an array of 3D vector normals by a specified Matrix.|
|static [`void TransformNormal(Vector3D[] sourceArray, ref Matrix matrix, *Vector3D destinationArray)`](VRageMath.TransformNormal)||
|static [`void TransformNormal(Vector3D[] sourceArray, int sourceIndex, ref Matrix matrix, Vector3D[] destinationArray, int destinationIndex, int length)`](VRageMath.TransformNormal)|Transforms a specified range in an array of 3D vector normals by a specified Matrix and writes the results to a specified range in a destination array.|
|static [`void Transform(Vector3D[] sourceArray, ref Quaternion rotation, Vector3D[] destinationArray)`](VRageMath.Transform)|Transforms a source array of Vector3s by a specified Quaternion rotation and writes the results to an existing destination array.|
|static [`void Transform(Vector3D[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector3D[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)|Applies a specified Quaternion rotation to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|static [`Vector3D Negate(Vector3D value)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`void Negate(ref Vector3D value, ref Vector3D result)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`Vector3D Add(Vector3D value1, Vector3D value2)`](VRageMath.Add)|Adds two vectors.|
|static [`void Add(ref Vector3D value1, ref Vector3D value2, ref Vector3D result)`](VRageMath.Add)|Adds two vectors.|
|static [`Vector3D Subtract(Vector3D value1, Vector3D value2)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`void Subtract(ref Vector3D value1, ref Vector3D value2, ref Vector3D result)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`Vector3D Multiply(Vector3D value1, Vector3D value2)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`void Multiply(ref Vector3D value1, ref Vector3D value2, ref Vector3D result)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`Vector3D Multiply(Vector3D value1, double scaleFactor)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`void Multiply(ref Vector3D value1, double scaleFactor, ref Vector3D result)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`Vector3D Divide(Vector3D value1, Vector3D value2)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`void Divide(ref Vector3D value1, ref Vector3D value2, ref Vector3D result)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`Vector3D Divide(Vector3D value1, double value2)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static [`void Divide(ref Vector3D value1, double value2, ref Vector3D result)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static [`Vector3D CalculatePerpendicularVector(Vector3D v)`](VRageMath.CalculatePerpendicularVector)||
|[`void CalculatePerpendicularVector(ref Vector3D result)`](VRageMath.CalculatePerpendicularVector)||
|static [`void GetAzimuthAndElevation(Vector3D v, ref double azimuth, ref double elevation)`](VRageMath.GetAzimuthAndElevation)||
|static [`void CreateFromAzimuthAndElevation(double azimuth, double elevation, ref Vector3D direction)`](VRageMath.CreateFromAzimuthAndElevation)||
|[`long VolumeInt(double multiplier)`](VRageMath.VolumeInt)||
|[`bool IsInsideInclusive(ref Vector3D min, ref Vector3D max)`](VRageMath.IsInsideInclusive)||
|static [`Vector3D SwapYZCoordinates(Vector3D v)`](VRageMath.SwapYZCoordinates)||
|[`double GetDim(int i)`](VRageMath.GetDim)||
|[`void SetDim(int i, double value)`](VRageMath.SetDim)||
|static [`Vector3I Round(Vector3D vect3d)`](VRageMath.Round)||
|static [`Vector3I Floor(Vector3D vect3d)`](VRageMath.Floor)||
|static [`void Fract(ref Vector3D o, ref Vector3D r)`](VRageMath.Fract)||
|static [`Vector3D Round(Vector3D v, int numDecimals)`](VRageMath.Round)||
|static [`void Abs(ref Vector3D vector3D, ref Vector3D abs)`](VRageMath.Abs)||
|static [`Vector3D ProjectOnPlane(ref Vector3D vec, ref Vector3D planeNormal)`](VRageMath.ProjectOnPlane)|Projects given vector on plane specified by it's normal.|
|static [`Vector3D ProjectOnVector(ref Vector3D vec, ref Vector3D guideVector)`](VRageMath.ProjectOnVector)|Projects vector on another vector resulting in new vector in guided vector's direction with different length.|
|static [`Vector3D Abs(Vector3D value)`](VRageMath.Abs)||
|static [`Vector3D Sign(Vector3D value)`](VRageMath.Sign)||
|static [`Vector3D SignNonZero(Vector3D value)`](VRageMath.SignNonZero)|Returns per component sign, never returns zero. For zero component returns sign 1. Faster than Sign.|
|[`void Interpolate3(Vector3D v0, Vector3D v1, double rt)`](VRageMath.Interpolate3)||
|[`bool IsValid()`](VRageMath.IsValid)||
|[`void AssertIsValid()`](VRageMath.AssertIsValid)||
|static [`bool IsUnit(ref Vector3D value)`](VRageMath.IsUnit)||
|static [`bool ArePerpendicular(ref Vector3D a, ref Vector3D b)`](VRageMath.ArePerpendicular)||
|static [`bool IsZero(Vector3D value)`](VRageMath.IsZero)||
|static [`bool IsZero(Vector3D value, double epsilon)`](VRageMath.IsZero)||
|static [`Vector3D IsZeroVector(Vector3D value)`](VRageMath.IsZeroVector)||
|static [`Vector3D IsZeroVector(Vector3D value, double epsilon)`](VRageMath.IsZeroVector)||
|static [`Vector3D Step(Vector3D value)`](VRageMath.Step)||
|[`string ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|static [`bool TryParse(string str, ref Vector3D retval)`](VRageMath.TryParse)||
|[`string ToString(string format)`](VRageMath.ToString)||
|[`bool Equals(Vector3D other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector3.|
|[`bool Equals(Vector3D other, double epsilon)`](VRageMath.Equals)||
|[`bool Equals(Object obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`long GetHash()`](VRageMath.GetHash)|Gets the hash code of the vector object.|
|[`double Length()`](VRageMath.Length)|Calculates the length of the vector.|
|[`double LengthSquared()`](VRageMath.LengthSquared)|Calculates the length of the vector squared.|
|static [`double Distance(Vector3D value1, Vector3D value2)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`double Distance(Vector3D value1, Vector3 value2)`](VRageMath.Distance)||
|static [`double Distance(Vector3 value1, Vector3D value2)`](VRageMath.Distance)||
|static [`void Distance(ref Vector3D value1, ref Vector3D value2, ref double result)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`double DistanceSquared(Vector3D value1, Vector3D value2)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`void DistanceSquared(ref Vector3D value1, ref Vector3D value2, ref double result)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`double RectangularDistance(Vector3D value1, Vector3D value2)`](VRageMath.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|static [`double RectangularDistance(ref Vector3D value1, ref Vector3D value2)`](VRageMath.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|static [`double Dot(Vector3D vector1, Vector3D vector2)`](VRageMath.Dot)|Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|static [`double Dot(Vector3D vector1, Vector3 vector2)`](VRageMath.Dot)||
|static [`void Dot(ref Vector3D vector1, ref Vector3D vector2, ref double result)`](VRageMath.Dot)|Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|static [`void Dot(ref Vector3D vector1, ref Vector3 vector2, ref double result)`](VRageMath.Dot)||
|static [`void Dot(ref Vector3 vector1, ref Vector3D vector2, ref double result)`](VRageMath.Dot)||
|[`double Dot(Vector3D v)`](VRageMath.Dot)||
|[`double Dot(Vector3 v)`](VRageMath.Dot)||
|[`double Dot(ref Vector3D v)`](VRageMath.Dot)||
|[`Vector3D Cross(Vector3D v)`](VRageMath.Cross)||
|[`double Normalize()`](VRageMath.Normalize)|Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`Vector3D Normalize(Vector3D value)`](VRageMath.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`void Normalize(ref Vector3D value, ref Vector3D result)`](VRageMath.Normalize)|Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`Vector3D Cross(Vector3D vector1, Vector3D vector2)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|static [`void Cross(ref Vector3D vector1, ref Vector3D vector2, ref Vector3D result)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|static [`Vector3D Reflect(Vector3D vector, Vector3D normal)`](VRageMath.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|static [`void Reflect(ref Vector3D vector, ref Vector3D normal, ref Vector3D result)`](VRageMath.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|static [`Vector3D Reject(Vector3D vector, Vector3D direction)`](VRageMath.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|static [`void Reject(ref Vector3D vector, ref Vector3D direction, ref Vector3D result)`](VRageMath.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|[`double Min()`](VRageMath.Min)|Returns the component of the vector that is smallest of all the three components.|
|[`double AbsMin()`](VRageMath.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|[`double Max()`](VRageMath.Max)|Returns the component of the vector that is largest of all the three components.|
|[`double AbsMax()`](VRageMath.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|[`int AbsMaxComponent()`](VRageMath.AbsMaxComponent)||
|static [`Vector3D Min(Vector3D value1, Vector3D value2)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`void Min(ref Vector3D value1, ref Vector3D value2, ref Vector3D result)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`Vector3D Max(Vector3D value1, Vector3D value2)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`void Max(ref Vector3D value1, ref Vector3D value2, ref Vector3D result)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`void MinMax(ref Vector3D min, ref Vector3D max)`](VRageMath.MinMax)|Separates minimal and maximal values of any two input vectors|
|static [`Vector3D DominantAxisProjection(Vector3D value1)`](VRageMath.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|static [`void DominantAxisProjection(ref Vector3D value1, ref Vector3D result)`](VRageMath.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved into a user-specified variable.|
|static [`Vector3D Clamp(Vector3D value1, Vector3D min, Vector3D max)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`void Clamp(ref Vector3D value1, ref Vector3D min, ref Vector3D max, ref Vector3D result)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`Vector3D ClampToSphere(Vector3D vector, double radius)`](VRageMath.ClampToSphere)||
|static [`void ClampToSphere(ref Vector3D vector, double radius)`](VRageMath.ClampToSphere)||
|static [`Vector3D Lerp(Vector3D value1, Vector3D value2, double amount)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`void Lerp(ref Vector3D value1, ref Vector3D value2, double amount, ref Vector3D result)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`Vector3D Barycentric(Vector3D value1, Vector3D value2, Vector3D value3, double amount1, double amount2)`](VRageMath.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in Barycentric coordinates relative to a 3D triangle.|
|static [`void Barycentric(ref Vector3D value1, ref Vector3D value2, ref Vector3D value3, double amount1, double amount2, ref Vector3D result)`](VRageMath.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 3D triangle.|
|static [`void Barycentric(Vector3D p, Vector3D a, Vector3D b, Vector3D c, ref double u, ref double v, ref double w)`](VRageMath.Barycentric)|Compute barycentric coordinates (u, v, w) for point p with respect to triangle (a, b, c) From : Real-Time Collision Detection, Christer Ericson, CRC Press 3.4 Barycentric Coordinates|
|static [`Vector3D SmoothStep(Vector3D value1, Vector3D value2, double amount)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`void SmoothStep(ref Vector3D value1, ref Vector3D value2, double amount, ref Vector3D result)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`Vector3D CatmullRom(Vector3D value1, Vector3D value2, Vector3D value3, Vector3D value4, double amount)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`void CatmullRom(ref Vector3D value1, ref Vector3D value2, ref Vector3D value3, ref Vector3D value4, double amount, ref Vector3D result)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`Vector3D Hermite(Vector3D value1, Vector3D tangent1, Vector3D value2, Vector3D tangent2, double amount)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`void Hermite(ref Vector3D value1, ref Vector3D tangent1, ref Vector3D value2, ref Vector3D tangent2, double amount, ref Vector3D result)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`Vector3D Transform(Vector3D position, MatrixD matrix)`](VRageMath.Transform)|Transforms a 3D vector by the given matrix.|
|static [`Vector3D Transform(Vector3 position, MatrixD matrix)`](VRageMath.Transform)||
|static [`Vector3D Transform(Vector3D position, Matrix matrix)`](VRageMath.Transform)|Transforms a 3D vector by the given matrix.|
|static [`Vector3D Transform(Vector3D position, ref MatrixD matrix)`](VRageMath.Transform)||
|static [`void Transform(ref Vector3D position, ref MatrixD matrix, ref Vector3D result)`](VRageMath.Transform)|Transforms a Vector3 by the given Matrix.|
|static [`void Transform(ref Vector3 position, ref MatrixD matrix, ref Vector3D result)`](VRageMath.Transform)||
|static [`void TransformNoProjection(ref Vector3D vector, ref MatrixD matrix, ref Vector3D result)`](VRageMath.TransformNoProjection)||
|static [`void RotateAndScale(ref Vector3D vector, ref MatrixD matrix, ref Vector3D result)`](VRageMath.RotateAndScale)||
|static [`void Transform(ref Vector3D position, ref MatrixI matrix, ref Vector3D result)`](VRageMath.Transform)||
|static [`Vector3D TransformNormal(Vector3D normal, Matrix matrix)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|static [`Vector3D TransformNormal(Vector3 normal, MatrixD matrix)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|static [`Vector3D TransformNormal(Vector3D normal, MatrixD matrix)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|static [`void TransformNormal(ref Vector3D normal, ref MatrixD matrix, ref Vector3D result)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|static [`void TransformNormal(ref Vector3 normal, ref MatrixD matrix, ref Vector3D result)`](VRageMath.TransformNormal)||
