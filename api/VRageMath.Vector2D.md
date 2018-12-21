← [Index](index)
# Vector2D Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with two components.
### Fields
<table style="width:100%;display:table">
<tr><td>[`double X`](VRageMath.X)</td><td>Gets or sets the x-component of the vector.</td></tr>
<tr><td>[`double Y`](VRageMath.Y)</td><td>Gets or sets the y-component of the vector.</td></tr>
<tr><td>static [`Vector2D Zero`](VRageMath.Zero)</td><td></td></tr>
<tr><td>static [`Vector2D One`](VRageMath.One)</td><td></td></tr>
<tr><td>static [`Vector2D UnitX`](VRageMath.UnitX)</td><td></td></tr>
<tr><td>static [`Vector2D UnitY`](VRageMath.UnitY)</td><td></td></tr>
<tr><td>static [`Vector2D PositiveInfinity`](VRageMath.PositiveInfinity)</td><td></td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>[`double Item`](VRageMath.Item)</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td>Retrieves a string representation of the current object.</td></tr>
<tr><td>[`bool Equals(Vector2D other)`](VRageMath.Equals)</td><td>Determines whether the specified Object is equal to the Vector2D.</td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td>Returns a value that indicates whether the current instance is equal to a specified object.</td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td>Gets the hash code of the vector object.</td></tr>
<tr><td>[`bool IsValid()`](VRageMath.IsValid)</td><td></td></tr>
<tr><td>[`void AssertIsValid()`](VRageMath.AssertIsValid)</td><td></td></tr>
<tr><td>[`double Length()`](VRageMath.Length)</td><td>Calculates the length of the vector.</td></tr>
<tr><td>[`double LengthSquared()`](VRageMath.LengthSquared)</td><td>Calculates the length of the vector squared.</td></tr>
<tr><td>static [`double Distance(Vector2D value1, Vector2D value2)`](VRageMath.Distance)</td><td>Calculates the distance between two vectors.</td></tr>
<tr><td>static [`void Distance(ref Vector2D value1, ref Vector2D value2, ref double result)`](VRageMath.Distance)</td><td>Calculates the distance between two vectors.</td></tr>
<tr><td>static [`double DistanceSquared(Vector2D value1, Vector2D value2)`](VRageMath.DistanceSquared)</td><td>Calculates the distance between two vectors squared.</td></tr>
<tr><td>static [`void DistanceSquared(ref Vector2D value1, ref Vector2D value2, ref double result)`](VRageMath.DistanceSquared)</td><td>Calculates the distance between two vectors squared.</td></tr>
<tr><td>static [`double Dot(Vector2D value1, Vector2D value2)`](VRageMath.Dot)</td><td>Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.</td></tr>
<tr><td>static [`void Dot(ref Vector2D value1, ref Vector2D value2, ref double result)`](VRageMath.Dot)</td><td>Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.</td></tr>
<tr><td>[`void Normalize()`](VRageMath.Normalize)</td><td>Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.</td></tr>
<tr><td>static [`Vector2D Normalize(Vector2D value)`](VRageMath.Normalize)</td><td>Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.</td></tr>
<tr><td>static [`void Normalize(ref Vector2D value, ref Vector2D result)`](VRageMath.Normalize)</td><td>Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.</td></tr>
<tr><td>static [`Vector2D Reflect(Vector2D vector, Vector2D normal)`](VRageMath.Reflect)</td><td>Determines the reflect vector of the given vector and normal.</td></tr>
<tr><td>static [`void Reflect(ref Vector2D vector, ref Vector2D normal, ref Vector2D result)`](VRageMath.Reflect)</td><td>Determines the reflect vector of the given vector and normal.</td></tr>
<tr><td>static [`Vector2D Min(Vector2D value1, Vector2D value2)`](VRageMath.Min)</td><td>Returns a vector that contains the lowest value from each matching pair of components.</td></tr>
<tr><td>static [`void Min(ref Vector2D value1, ref Vector2D value2, ref Vector2D result)`](VRageMath.Min)</td><td>Returns a vector that contains the lowest value from each matching pair of components.</td></tr>
<tr><td>static [`Vector2D Max(Vector2D value1, Vector2D value2)`](VRageMath.Max)</td><td>Returns a vector that contains the highest value from each matching pair of components.</td></tr>
<tr><td>static [`void Max(ref Vector2D value1, ref Vector2D value2, ref Vector2D result)`](VRageMath.Max)</td><td>Returns a vector that contains the highest value from each matching pair of components.</td></tr>
<tr><td>static [`Vector2D Clamp(Vector2D value1, Vector2D min, Vector2D max)`](VRageMath.Clamp)</td><td>Restricts a value to be within a specified range.</td></tr>
<tr><td>static [`void Clamp(ref Vector2D value1, ref Vector2D min, ref Vector2D max, ref Vector2D result)`](VRageMath.Clamp)</td><td>Restricts a value to be within a specified range.</td></tr>
<tr><td>static [`Vector2D ClampToSphere(Vector2D vector, double radius)`](VRageMath.ClampToSphere)</td><td></td></tr>
<tr><td>static [`void ClampToSphere(ref Vector2D vector, double radius)`](VRageMath.ClampToSphere)</td><td></td></tr>
<tr><td>static [`Vector2D Lerp(Vector2D value1, Vector2D value2, double amount)`](VRageMath.Lerp)</td><td>Performs a linear interpolation between two vectors.</td></tr>
<tr><td>static [`void Lerp(ref Vector2D value1, ref Vector2D value2, double amount, ref Vector2D result)`](VRageMath.Lerp)</td><td>Performs a linear interpolation between two vectors.</td></tr>
<tr><td>static [`Vector2D Barycentric(Vector2D value1, Vector2D value2, Vector2D value3, double amount1, double amount2)`](VRageMath.Barycentric)</td><td>Returns a Vector2D containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.</td></tr>
<tr><td>static [`void Barycentric(ref Vector2D value1, ref Vector2D value2, ref Vector2D value3, double amount1, double amount2, ref Vector2D result)`](VRageMath.Barycentric)</td><td>Returns a Vector2D containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.</td></tr>
<tr><td>static [`Vector2D SmoothStep(Vector2D value1, Vector2D value2, double amount)`](VRageMath.SmoothStep)</td><td>Interpolates between two values using a cubic equation.</td></tr>
<tr><td>static [`void SmoothStep(ref Vector2D value1, ref Vector2D value2, double amount, ref Vector2D result)`](VRageMath.SmoothStep)</td><td>Interpolates between two values using a cubic equation.</td></tr>
<tr><td>static [`Vector2D CatmullRom(Vector2D value1, Vector2D value2, Vector2D value3, Vector2D value4, double amount)`](VRageMath.CatmullRom)</td><td>Performs a Catmull-Rom interpolation using the specified positions.</td></tr>
<tr><td>static [`void CatmullRom(ref Vector2D value1, ref Vector2D value2, ref Vector2D value3, ref Vector2D value4, double amount, ref Vector2D result)`](VRageMath.CatmullRom)</td><td>Performs a Catmull-Rom interpolation using the specified positions.</td></tr>
<tr><td>static [`Vector2D Hermite(Vector2D value1, Vector2D tangent1, Vector2D value2, Vector2D tangent2, double amount)`](VRageMath.Hermite)</td><td>Performs a Hermite spline interpolation.</td></tr>
<tr><td>static [`void Hermite(ref Vector2D value1, ref Vector2D tangent1, ref Vector2D value2, ref Vector2D tangent2, double amount, ref Vector2D result)`](VRageMath.Hermite)</td><td>Performs a Hermite spline interpolation.</td></tr>
<tr><td>static [`Vector2D Transform(Vector2D position, Matrix matrix)`](VRageMath.Transform)</td><td>Transforms the vector (x, y, 0, 1) by the specified matrix.</td></tr>
<tr><td>static [`void Transform(ref Vector2D position, ref Matrix matrix, ref Vector2D result)`](VRageMath.Transform)</td><td>Transforms a Vector2D by the given Matrix.</td></tr>
<tr><td>static [`Vector2D TransformNormal(Vector2D normal, Matrix matrix)`](VRageMath.TransformNormal)</td><td>Transforms a 2D vector normal by a matrix.</td></tr>
<tr><td>static [`void TransformNormal(ref Vector2D normal, ref Matrix matrix, ref Vector2D result)`](VRageMath.TransformNormal)</td><td>Transforms a vector normal by a matrix.</td></tr>
<tr><td>static [`Vector2D Transform(Vector2D value, Quaternion rotation)`](VRageMath.Transform)</td><td>Transforms a single Vector2D, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.</td></tr>
<tr><td>static [`void Transform(ref Vector2D value, ref Quaternion rotation, ref Vector2D result)`](VRageMath.Transform)</td><td>Transforms a Vector2D, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.</td></tr>
<tr><td>static [`void Transform(Vector2D[] sourceArray, ref Matrix matrix, Vector2D[] destinationArray)`](VRageMath.Transform)</td><td>Transforms an array of Vector2s by a specified Matrix.</td></tr>
<tr><td>static [`void Transform(Vector2D[] sourceArray, int sourceIndex, ref Matrix matrix, Vector2D[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)</td><td>Transforms a specified range in an array of Vector2s by a specified Matrix and places the results in a specified range in a destination array.</td></tr>
<tr><td>static [`void TransformNormal(Vector2D[] sourceArray, ref Matrix matrix, Vector2D[] destinationArray)`](VRageMath.TransformNormal)</td><td>Transforms an array of Vector2D vector normals by a specified Matrix.</td></tr>
<tr><td>static [`void TransformNormal(Vector2D[] sourceArray, int sourceIndex, ref Matrix matrix, Vector2D[] destinationArray, int destinationIndex, int length)`](VRageMath.TransformNormal)</td><td>Transforms a specified range in an array of Vector2D vector normals by a specified Matrix and places the results in a specified range in a destination array.</td></tr>
<tr><td>static [`void Transform(Vector2D[] sourceArray, ref Quaternion rotation, Vector2D[] destinationArray)`](VRageMath.Transform)</td><td>Transforms an array of Vector2s by a specified Quaternion.</td></tr>
<tr><td>static [`void Transform(Vector2D[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector2D[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)</td><td>Transforms a specified range in an array of Vector2s by a specified Quaternion and places the results in a specified range in a destination array.</td></tr>
<tr><td>static [`Vector2D Negate(Vector2D value)`](VRageMath.Negate)</td><td>Returns a vector pointing in the opposite direction.</td></tr>
<tr><td>static [`void Negate(ref Vector2D value, ref Vector2D result)`](VRageMath.Negate)</td><td>Returns a vector pointing in the opposite direction.</td></tr>
<tr><td>static [`Vector2D Add(Vector2D value1, Vector2D value2)`](VRageMath.Add)</td><td>Adds two vectors.</td></tr>
<tr><td>static [`void Add(ref Vector2D value1, ref Vector2D value2, ref Vector2D result)`](VRageMath.Add)</td><td>Adds two vectors.</td></tr>
<tr><td>static [`Vector2D Subtract(Vector2D value1, Vector2D value2)`](VRageMath.Subtract)</td><td>Subtracts a vector from a vector.</td></tr>
<tr><td>static [`void Subtract(ref Vector2D value1, ref Vector2D value2, ref Vector2D result)`](VRageMath.Subtract)</td><td>Subtracts a vector from a vector.</td></tr>
<tr><td>static [`Vector2D Multiply(Vector2D value1, Vector2D value2)`](VRageMath.Multiply)</td><td>Multiplies the components of two vectors by each other.</td></tr>
<tr><td>static [`void Multiply(ref Vector2D value1, ref Vector2D value2, ref Vector2D result)`](VRageMath.Multiply)</td><td>Multiplies the components of two vectors by each other.</td></tr>
<tr><td>static [`Vector2D Multiply(Vector2D value1, double scaleFactor)`](VRageMath.Multiply)</td><td>Multiplies a vector by a scalar value.</td></tr>
<tr><td>static [`void Multiply(ref Vector2D value1, double scaleFactor, ref Vector2D result)`](VRageMath.Multiply)</td><td>Multiplies a vector by a scalar value.</td></tr>
<tr><td>static [`Vector2D Divide(Vector2D value1, Vector2D value2)`](VRageMath.Divide)</td><td>Divides the components of a vector by the components of another vector.</td></tr>
<tr><td>static [`void Divide(ref Vector2D value1, ref Vector2D value2, ref Vector2D result)`](VRageMath.Divide)</td><td>Divides the components of a vector by the components of another vector.</td></tr>
<tr><td>static [`Vector2D Divide(Vector2D value1, double divider)`](VRageMath.Divide)</td><td>Divides a vector by a scalar value.</td></tr>
<tr><td>static [`void Divide(ref Vector2D value1, double divider, ref Vector2D result)`](VRageMath.Divide)</td><td>Divides a vector by a scalar value.</td></tr>
<tr><td>[`bool Between(ref Vector2D start, ref Vector2D end)`](VRageMath.Between)</td><td></td></tr>
<tr><td>static [`Vector2D Floor(Vector2D position)`](VRageMath.Floor)</td><td></td></tr>
<tr><td>[`void Rotate(double angle)`](VRageMath.Rotate)</td><td></td></tr>
</table>
