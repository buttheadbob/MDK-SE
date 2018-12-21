← [Index](index)
# Vector3D Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with three components.
### Fields
<table style="width:100%;display:table">
<tr><td>[`double X`](VRageMath.X)</td><td>Gets or sets the x-component of the vector.</td></tr>
<tr><td>[`double Y`](VRageMath.Y)</td><td>Gets or sets the y-component of the vector.</td></tr>
<tr><td>[`double Z`](VRageMath.Z)</td><td>Gets or sets the z-component of the vector.</td></tr>
<tr><td>static [`Vector3D Zero`](VRageMath.Zero)</td><td></td></tr>
<tr><td>static [`Vector3D One`](VRageMath.One)</td><td></td></tr>
<tr><td>static [`Vector3D Half`](VRageMath.Half)</td><td></td></tr>
<tr><td>static [`Vector3D PositiveInfinity`](VRageMath.PositiveInfinity)</td><td></td></tr>
<tr><td>static [`Vector3D NegativeInfinity`](VRageMath.NegativeInfinity)</td><td></td></tr>
<tr><td>static [`Vector3D UnitX`](VRageMath.UnitX)</td><td></td></tr>
<tr><td>static [`Vector3D UnitY`](VRageMath.UnitY)</td><td></td></tr>
<tr><td>static [`Vector3D UnitZ`](VRageMath.UnitZ)</td><td></td></tr>
<tr><td>static [`Vector3D Up`](VRageMath.Up)</td><td></td></tr>
<tr><td>static [`Vector3D Down`](VRageMath.Down)</td><td></td></tr>
<tr><td>static [`Vector3D Right`](VRageMath.Right)</td><td></td></tr>
<tr><td>static [`Vector3D Left`](VRageMath.Left)</td><td></td></tr>
<tr><td>static [`Vector3D Forward`](VRageMath.Forward)</td><td></td></tr>
<tr><td>static [`Vector3D Backward`](VRageMath.Backward)</td><td></td></tr>
<tr><td>static [`Vector3D MaxValue`](VRageMath.MaxValue)</td><td></td></tr>
<tr><td>static [`Vector3D MinValue`](VRageMath.MinValue)</td><td></td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>[`double Sum`](VRageMath.Sum)</td><td></td></tr>
<tr><td>[`double Volume`](VRageMath.Volume)</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>static [`void TransformNormal(ref Vector3D normal, ref MatrixI matrix, ref Vector3D result)`](VRageMath.TransformNormal)</td><td></td></tr>
<tr><td>static [`Vector3D TransformNormal(Vector3D normal, MyBlockOrientation orientation)`](VRageMath.TransformNormal)</td><td></td></tr>
<tr><td>static [`void TransformNormal(ref Vector3D normal, MyBlockOrientation orientation, ref Vector3D result)`](VRageMath.TransformNormal)</td><td></td></tr>
<tr><td>static [`Vector3D TransformNormal(Vector3D normal, ref MatrixD matrix)`](VRageMath.TransformNormal)</td><td></td></tr>
<tr><td>static [`Vector3D Transform(Vector3D value, Quaternion rotation)`](VRageMath.Transform)</td><td>Transforms a Vector3 by a specified Quaternion rotation.</td></tr>
<tr><td>static [`void Transform(ref Vector3D value, ref Quaternion rotation, ref Vector3D result)`](VRageMath.Transform)</td><td>Transforms a Vector3 by a specified Quaternion rotation.</td></tr>
<tr><td>static [`void Rotate(ref Vector3D vector, ref MatrixD rotationMatrix, ref Vector3D result)`](VRageMath.Rotate)</td><td></td></tr>
<tr><td>static [`Vector3D Rotate(Vector3D vector, MatrixD rotationMatrix)`](VRageMath.Rotate)</td><td></td></tr>
<tr><td>static [`void Transform(Vector3D[] sourceArray, ref MatrixD matrix, Vector3D[] destinationArray)`](VRageMath.Transform)</td><td>Transforms a source array of Vector3s by a specified Matrix and writes the results to an existing destination array.</td></tr>
<tr><td>static [`void Transform(Vector3D[] sourceArray, ref MatrixD matrix, *Vector3D destinationArray)`](VRageMath.Transform)</td><td></td></tr>
<tr><td>static [`void Transform(Vector3D[] sourceArray, int sourceIndex, ref Matrix matrix, Vector3D[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)</td><td>Applies a specified transform Matrix to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.</td></tr>
<tr><td>static [`void TransformNormal(Vector3D[] sourceArray, ref Matrix matrix, Vector3D[] destinationArray)`](VRageMath.TransformNormal)</td><td>Transforms an array of 3D vector normals by a specified Matrix.</td></tr>
<tr><td>static [`void TransformNormal(Vector3D[] sourceArray, ref Matrix matrix, *Vector3D destinationArray)`](VRageMath.TransformNormal)</td><td></td></tr>
<tr><td>static [`void TransformNormal(Vector3D[] sourceArray, int sourceIndex, ref Matrix matrix, Vector3D[] destinationArray, int destinationIndex, int length)`](VRageMath.TransformNormal)</td><td>Transforms a specified range in an array of 3D vector normals by a specified Matrix and writes the results to a specified range in a destination array.</td></tr>
<tr><td>static [`void Transform(Vector3D[] sourceArray, ref Quaternion rotation, Vector3D[] destinationArray)`](VRageMath.Transform)</td><td>Transforms a source array of Vector3s by a specified Quaternion rotation and writes the results to an existing destination array.</td></tr>
<tr><td>static [`void Transform(Vector3D[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector3D[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)</td><td>Applies a specified Quaternion rotation to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.</td></tr>
<tr><td>static [`Vector3D Negate(Vector3D value)`](VRageMath.Negate)</td><td>Returns a vector pointing in the opposite direction.</td></tr>
<tr><td>static [`void Negate(ref Vector3D value, ref Vector3D result)`](VRageMath.Negate)</td><td>Returns a vector pointing in the opposite direction.</td></tr>
<tr><td>static [`Vector3D Add(Vector3D value1, Vector3D value2)`](VRageMath.Add)</td><td>Adds two vectors.</td></tr>
<tr><td>static [`void Add(ref Vector3D value1, ref Vector3D value2, ref Vector3D result)`](VRageMath.Add)</td><td>Adds two vectors.</td></tr>
<tr><td>static [`Vector3D Subtract(Vector3D value1, Vector3D value2)`](VRageMath.Subtract)</td><td>Subtracts a vector from a vector.</td></tr>
<tr><td>static [`void Subtract(ref Vector3D value1, ref Vector3D value2, ref Vector3D result)`](VRageMath.Subtract)</td><td>Subtracts a vector from a vector.</td></tr>
<tr><td>static [`Vector3D Multiply(Vector3D value1, Vector3D value2)`](VRageMath.Multiply)</td><td>Multiplies the components of two vectors by each other.</td></tr>
<tr><td>static [`void Multiply(ref Vector3D value1, ref Vector3D value2, ref Vector3D result)`](VRageMath.Multiply)</td><td>Multiplies the components of two vectors by each other.</td></tr>
<tr><td>static [`Vector3D Multiply(Vector3D value1, double scaleFactor)`](VRageMath.Multiply)</td><td>Multiplies a vector by a scalar value.</td></tr>
<tr><td>static [`void Multiply(ref Vector3D value1, double scaleFactor, ref Vector3D result)`](VRageMath.Multiply)</td><td>Multiplies a vector by a scalar value.</td></tr>
<tr><td>static [`Vector3D Divide(Vector3D value1, Vector3D value2)`](VRageMath.Divide)</td><td>Divides the components of a vector by the components of another vector.</td></tr>
<tr><td>static [`void Divide(ref Vector3D value1, ref Vector3D value2, ref Vector3D result)`](VRageMath.Divide)</td><td>Divides the components of a vector by the components of another vector.</td></tr>
<tr><td>static [`Vector3D Divide(Vector3D value1, double value2)`](VRageMath.Divide)</td><td>Divides a vector by a scalar value.</td></tr>
<tr><td>static [`void Divide(ref Vector3D value1, double value2, ref Vector3D result)`](VRageMath.Divide)</td><td>Divides a vector by a scalar value.</td></tr>
<tr><td>static [`Vector3D CalculatePerpendicularVector(Vector3D v)`](VRageMath.CalculatePerpendicularVector)</td><td></td></tr>
<tr><td>[`void CalculatePerpendicularVector(ref Vector3D result)`](VRageMath.CalculatePerpendicularVector)</td><td></td></tr>
<tr><td>static [`void GetAzimuthAndElevation(Vector3D v, ref double azimuth, ref double elevation)`](VRageMath.GetAzimuthAndElevation)</td><td></td></tr>
<tr><td>static [`void CreateFromAzimuthAndElevation(double azimuth, double elevation, ref Vector3D direction)`](VRageMath.CreateFromAzimuthAndElevation)</td><td></td></tr>
<tr><td>[`long VolumeInt(double multiplier)`](VRageMath.VolumeInt)</td><td></td></tr>
<tr><td>[`bool IsInsideInclusive(ref Vector3D min, ref Vector3D max)`](VRageMath.IsInsideInclusive)</td><td></td></tr>
<tr><td>static [`Vector3D SwapYZCoordinates(Vector3D v)`](VRageMath.SwapYZCoordinates)</td><td></td></tr>
<tr><td>[`double GetDim(int i)`](VRageMath.GetDim)</td><td></td></tr>
<tr><td>[`void SetDim(int i, double value)`](VRageMath.SetDim)</td><td></td></tr>
<tr><td>static [`Vector3I Round(Vector3D vect3d)`](VRageMath.Round)</td><td></td></tr>
<tr><td>static [`Vector3I Floor(Vector3D vect3d)`](VRageMath.Floor)</td><td></td></tr>
<tr><td>static [`void Fract(ref Vector3D o, ref Vector3D r)`](VRageMath.Fract)</td><td></td></tr>
<tr><td>static [`Vector3D Round(Vector3D v, int numDecimals)`](VRageMath.Round)</td><td></td></tr>
<tr><td>static [`void Abs(ref Vector3D vector3D, ref Vector3D abs)`](VRageMath.Abs)</td><td></td></tr>
<tr><td>static [`Vector3D ProjectOnPlane(ref Vector3D vec, ref Vector3D planeNormal)`](VRageMath.ProjectOnPlane)</td><td>Projects given vector on plane specified by it's normal.</td></tr>
<tr><td>static [`Vector3D ProjectOnVector(ref Vector3D vec, ref Vector3D guideVector)`](VRageMath.ProjectOnVector)</td><td>Projects vector on another vector resulting in new vector in guided vector's direction with different length.</td></tr>
<tr><td>static [`Vector3D Abs(Vector3D value)`](VRageMath.Abs)</td><td></td></tr>
<tr><td>static [`Vector3D Sign(Vector3D value)`](VRageMath.Sign)</td><td></td></tr>
<tr><td>static [`Vector3D SignNonZero(Vector3D value)`](VRageMath.SignNonZero)</td><td>Returns per component sign, never returns zero. For zero component returns sign 1. Faster than Sign.</td></tr>
<tr><td>[`void Interpolate3(Vector3D v0, Vector3D v1, double rt)`](VRageMath.Interpolate3)</td><td></td></tr>
<tr><td>[`bool IsValid()`](VRageMath.IsValid)</td><td></td></tr>
<tr><td>[`void AssertIsValid()`](VRageMath.AssertIsValid)</td><td></td></tr>
<tr><td>static [`bool IsUnit(ref Vector3D value)`](VRageMath.IsUnit)</td><td></td></tr>
<tr><td>static [`bool ArePerpendicular(ref Vector3D a, ref Vector3D b)`](VRageMath.ArePerpendicular)</td><td></td></tr>
<tr><td>static [`bool IsZero(Vector3D value)`](VRageMath.IsZero)</td><td></td></tr>
<tr><td>static [`bool IsZero(Vector3D value, double epsilon)`](VRageMath.IsZero)</td><td></td></tr>
<tr><td>static [`Vector3D IsZeroVector(Vector3D value)`](VRageMath.IsZeroVector)</td><td></td></tr>
<tr><td>static [`Vector3D IsZeroVector(Vector3D value, double epsilon)`](VRageMath.IsZeroVector)</td><td></td></tr>
<tr><td>static [`Vector3D Step(Vector3D value)`](VRageMath.Step)</td><td></td></tr>
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td>Retrieves a string representation of the current object.</td></tr>
<tr><td>static [`bool TryParse(string str, ref Vector3D retval)`](VRageMath.TryParse)</td><td></td></tr>
<tr><td>[`string ToString(string format)`](VRageMath.ToString)</td><td></td></tr>
<tr><td>[`bool Equals(Vector3D other)`](VRageMath.Equals)</td><td>Determines whether the specified Object is equal to the Vector3.</td></tr>
<tr><td>[`bool Equals(Vector3D other, double epsilon)`](VRageMath.Equals)</td><td></td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td>Returns a value that indicates whether the current instance is equal to a specified object.</td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td></td></tr>
<tr><td>[`long GetHash()`](VRageMath.GetHash)</td><td>Gets the hash code of the vector object.</td></tr>
<tr><td>[`double Length()`](VRageMath.Length)</td><td>Calculates the length of the vector.</td></tr>
<tr><td>[`double LengthSquared()`](VRageMath.LengthSquared)</td><td>Calculates the length of the vector squared.</td></tr>
<tr><td>static [`double Distance(Vector3D value1, Vector3D value2)`](VRageMath.Distance)</td><td>Calculates the distance between two vectors.</td></tr>
<tr><td>static [`double Distance(Vector3D value1, Vector3 value2)`](VRageMath.Distance)</td><td></td></tr>
<tr><td>static [`double Distance(Vector3 value1, Vector3D value2)`](VRageMath.Distance)</td><td></td></tr>
<tr><td>static [`void Distance(ref Vector3D value1, ref Vector3D value2, ref double result)`](VRageMath.Distance)</td><td>Calculates the distance between two vectors.</td></tr>
<tr><td>static [`double DistanceSquared(Vector3D value1, Vector3D value2)`](VRageMath.DistanceSquared)</td><td>Calculates the distance between two vectors squared.</td></tr>
<tr><td>static [`void DistanceSquared(ref Vector3D value1, ref Vector3D value2, ref double result)`](VRageMath.DistanceSquared)</td><td>Calculates the distance between two vectors squared.</td></tr>
<tr><td>static [`double RectangularDistance(Vector3D value1, Vector3D value2)`](VRageMath.RectangularDistance)</td><td>Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.</td></tr>
<tr><td>static [`double RectangularDistance(ref Vector3D value1, ref Vector3D value2)`](VRageMath.RectangularDistance)</td><td>Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.</td></tr>
<tr><td>static [`double Dot(Vector3D vector1, Vector3D vector2)`](VRageMath.Dot)</td><td>Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.</td></tr>
<tr><td>static [`double Dot(Vector3D vector1, Vector3 vector2)`](VRageMath.Dot)</td><td></td></tr>
<tr><td>static [`void Dot(ref Vector3D vector1, ref Vector3D vector2, ref double result)`](VRageMath.Dot)</td><td>Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.</td></tr>
<tr><td>static [`void Dot(ref Vector3D vector1, ref Vector3 vector2, ref double result)`](VRageMath.Dot)</td><td></td></tr>
<tr><td>static [`void Dot(ref Vector3 vector1, ref Vector3D vector2, ref double result)`](VRageMath.Dot)</td><td></td></tr>
<tr><td>[`double Dot(Vector3D v)`](VRageMath.Dot)</td><td></td></tr>
<tr><td>[`double Dot(Vector3 v)`](VRageMath.Dot)</td><td></td></tr>
<tr><td>[`double Dot(ref Vector3D v)`](VRageMath.Dot)</td><td></td></tr>
<tr><td>[`Vector3D Cross(Vector3D v)`](VRageMath.Cross)</td><td></td></tr>
<tr><td>[`double Normalize()`](VRageMath.Normalize)</td><td>Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.</td></tr>
<tr><td>static [`Vector3D Normalize(Vector3D value)`](VRageMath.Normalize)</td><td>Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.</td></tr>
<tr><td>static [`void Normalize(ref Vector3D value, ref Vector3D result)`](VRageMath.Normalize)</td><td>Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.</td></tr>
<tr><td>static [`Vector3D Cross(Vector3D vector1, Vector3D vector2)`](VRageMath.Cross)</td><td>Calculates the cross product of two vectors.</td></tr>
<tr><td>static [`void Cross(ref Vector3D vector1, ref Vector3D vector2, ref Vector3D result)`](VRageMath.Cross)</td><td>Calculates the cross product of two vectors.</td></tr>
<tr><td>static [`Vector3D Reflect(Vector3D vector, Vector3D normal)`](VRageMath.Reflect)</td><td>Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.</td></tr>
<tr><td>static [`void Reflect(ref Vector3D vector, ref Vector3D normal, ref Vector3D result)`](VRageMath.Reflect)</td><td>Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.</td></tr>
<tr><td>static [`Vector3D Reject(Vector3D vector, Vector3D direction)`](VRageMath.Reject)</td><td>Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction</td></tr>
<tr><td>static [`void Reject(ref Vector3D vector, ref Vector3D direction, ref Vector3D result)`](VRageMath.Reject)</td><td>Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction</td></tr>
<tr><td>[`double Min()`](VRageMath.Min)</td><td>Returns the component of the vector that is smallest of all the three components.</td></tr>
<tr><td>[`double AbsMin()`](VRageMath.AbsMin)</td><td>Returns the component of the vector, whose absolute value is smallest of all the three components.</td></tr>
<tr><td>[`double Max()`](VRageMath.Max)</td><td>Returns the component of the vector that is largest of all the three components.</td></tr>
<tr><td>[`double AbsMax()`](VRageMath.AbsMax)</td><td>Returns the component of the vector, whose absolute value is largest of all the three components.</td></tr>
<tr><td>[`int AbsMaxComponent()`](VRageMath.AbsMaxComponent)</td><td></td></tr>
<tr><td>static [`Vector3D Min(Vector3D value1, Vector3D value2)`](VRageMath.Min)</td><td>Returns a vector that contains the lowest value from each matching pair of components.</td></tr>
<tr><td>static [`void Min(ref Vector3D value1, ref Vector3D value2, ref Vector3D result)`](VRageMath.Min)</td><td>Returns a vector that contains the lowest value from each matching pair of components.</td></tr>
<tr><td>static [`Vector3D Max(Vector3D value1, Vector3D value2)`](VRageMath.Max)</td><td>Returns a vector that contains the highest value from each matching pair of components.</td></tr>
<tr><td>static [`void Max(ref Vector3D value1, ref Vector3D value2, ref Vector3D result)`](VRageMath.Max)</td><td>Returns a vector that contains the highest value from each matching pair of components.</td></tr>
<tr><td>static [`void MinMax(ref Vector3D min, ref Vector3D max)`](VRageMath.MinMax)</td><td>Separates minimal and maximal values of any two input vectors</td></tr>
<tr><td>static [`Vector3D DominantAxisProjection(Vector3D value1)`](VRageMath.DominantAxisProjection)</td><td>Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.</td></tr>
<tr><td>static [`void DominantAxisProjection(ref Vector3D value1, ref Vector3D result)`](VRageMath.DominantAxisProjection)</td><td>Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved into a user-specified variable.</td></tr>
<tr><td>static [`Vector3D Clamp(Vector3D value1, Vector3D min, Vector3D max)`](VRageMath.Clamp)</td><td>Restricts a value to be within a specified range.</td></tr>
<tr><td>static [`void Clamp(ref Vector3D value1, ref Vector3D min, ref Vector3D max, ref Vector3D result)`](VRageMath.Clamp)</td><td>Restricts a value to be within a specified range.</td></tr>
<tr><td>static [`Vector3D ClampToSphere(Vector3D vector, double radius)`](VRageMath.ClampToSphere)</td><td></td></tr>
<tr><td>static [`void ClampToSphere(ref Vector3D vector, double radius)`](VRageMath.ClampToSphere)</td><td></td></tr>
<tr><td>static [`Vector3D Lerp(Vector3D value1, Vector3D value2, double amount)`](VRageMath.Lerp)</td><td>Performs a linear interpolation between two vectors.</td></tr>
<tr><td>static [`void Lerp(ref Vector3D value1, ref Vector3D value2, double amount, ref Vector3D result)`](VRageMath.Lerp)</td><td>Performs a linear interpolation between two vectors.</td></tr>
<tr><td>static [`Vector3D Barycentric(Vector3D value1, Vector3D value2, Vector3D value3, double amount1, double amount2)`](VRageMath.Barycentric)</td><td>Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in Barycentric coordinates relative to a 3D triangle.</td></tr>
<tr><td>static [`void Barycentric(ref Vector3D value1, ref Vector3D value2, ref Vector3D value3, double amount1, double amount2, ref Vector3D result)`](VRageMath.Barycentric)</td><td>Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 3D triangle.</td></tr>
<tr><td>static [`void Barycentric(Vector3D p, Vector3D a, Vector3D b, Vector3D c, ref double u, ref double v, ref double w)`](VRageMath.Barycentric)</td><td>Compute barycentric coordinates (u, v, w) for point p with respect to triangle (a, b, c) From : Real-Time Collision Detection, Christer Ericson, CRC Press 3.4 Barycentric Coordinates</td></tr>
<tr><td>static [`Vector3D SmoothStep(Vector3D value1, Vector3D value2, double amount)`](VRageMath.SmoothStep)</td><td>Interpolates between two values using a cubic equation.</td></tr>
<tr><td>static [`void SmoothStep(ref Vector3D value1, ref Vector3D value2, double amount, ref Vector3D result)`](VRageMath.SmoothStep)</td><td>Interpolates between two values using a cubic equation.</td></tr>
<tr><td>static [`Vector3D CatmullRom(Vector3D value1, Vector3D value2, Vector3D value3, Vector3D value4, double amount)`](VRageMath.CatmullRom)</td><td>Performs a Catmull-Rom interpolation using the specified positions.</td></tr>
<tr><td>static [`void CatmullRom(ref Vector3D value1, ref Vector3D value2, ref Vector3D value3, ref Vector3D value4, double amount, ref Vector3D result)`](VRageMath.CatmullRom)</td><td>Performs a Catmull-Rom interpolation using the specified positions.</td></tr>
<tr><td>static [`Vector3D Hermite(Vector3D value1, Vector3D tangent1, Vector3D value2, Vector3D tangent2, double amount)`](VRageMath.Hermite)</td><td>Performs a Hermite spline interpolation.</td></tr>
<tr><td>static [`void Hermite(ref Vector3D value1, ref Vector3D tangent1, ref Vector3D value2, ref Vector3D tangent2, double amount, ref Vector3D result)`](VRageMath.Hermite)</td><td>Performs a Hermite spline interpolation.</td></tr>
<tr><td>static [`Vector3D Transform(Vector3D position, MatrixD matrix)`](VRageMath.Transform)</td><td>Transforms a 3D vector by the given matrix.</td></tr>
<tr><td>static [`Vector3D Transform(Vector3 position, MatrixD matrix)`](VRageMath.Transform)</td><td></td></tr>
<tr><td>static [`Vector3D Transform(Vector3D position, Matrix matrix)`](VRageMath.Transform)</td><td>Transforms a 3D vector by the given matrix.</td></tr>
<tr><td>static [`Vector3D Transform(Vector3D position, ref MatrixD matrix)`](VRageMath.Transform)</td><td></td></tr>
<tr><td>static [`void Transform(ref Vector3D position, ref MatrixD matrix, ref Vector3D result)`](VRageMath.Transform)</td><td>Transforms a Vector3 by the given Matrix.</td></tr>
<tr><td>static [`void Transform(ref Vector3 position, ref MatrixD matrix, ref Vector3D result)`](VRageMath.Transform)</td><td></td></tr>
<tr><td>static [`void TransformNoProjection(ref Vector3D vector, ref MatrixD matrix, ref Vector3D result)`](VRageMath.TransformNoProjection)</td><td></td></tr>
<tr><td>static [`void RotateAndScale(ref Vector3D vector, ref MatrixD matrix, ref Vector3D result)`](VRageMath.RotateAndScale)</td><td></td></tr>
<tr><td>static [`void Transform(ref Vector3D position, ref MatrixI matrix, ref Vector3D result)`](VRageMath.Transform)</td><td></td></tr>
<tr><td>static [`Vector3D TransformNormal(Vector3D normal, Matrix matrix)`](VRageMath.TransformNormal)</td><td>Transforms a 3D vector normal by a matrix.</td></tr>
<tr><td>static [`Vector3D TransformNormal(Vector3 normal, MatrixD matrix)`](VRageMath.TransformNormal)</td><td>Transforms a 3D vector normal by a matrix.</td></tr>
<tr><td>static [`Vector3D TransformNormal(Vector3D normal, MatrixD matrix)`](VRageMath.TransformNormal)</td><td>Transforms a 3D vector normal by a matrix.</td></tr>
<tr><td>static [`void TransformNormal(ref Vector3D normal, ref MatrixD matrix, ref Vector3D result)`](VRageMath.TransformNormal)</td><td>Transforms a vector normal by a matrix.</td></tr>
<tr><td>static [`void TransformNormal(ref Vector3 normal, ref MatrixD matrix, ref Vector3D result)`](VRageMath.TransformNormal)</td><td></td></tr>
</table>
