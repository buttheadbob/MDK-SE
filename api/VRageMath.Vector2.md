← [Index](index)
# Vector2 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with two components.
### Fields
<table style="width:100%;display:table">
<tr><td>[`float X`](VRageMath.X)</td><td>Gets or sets the x-component of the vector.</td></tr>
<tr><td>[`float Y`](VRageMath.Y)</td><td>Gets or sets the y-component of the vector.</td></tr>
<tr><td>static [`Vector2 Zero`](VRageMath.Zero)</td><td></td></tr>
<tr><td>static [`Vector2 One`](VRageMath.One)</td><td></td></tr>
<tr><td>static [`Vector2 UnitX`](VRageMath.UnitX)</td><td></td></tr>
<tr><td>static [`Vector2 UnitY`](VRageMath.UnitY)</td><td></td></tr>
<tr><td>static [`Vector2 PositiveInfinity`](VRageMath.PositiveInfinity)</td><td></td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>[`float Item`](VRageMath.Item)</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td>Retrieves a string representation of the current object.</td></tr>
<tr><td>[`bool Equals(Vector2 other)`](VRageMath.Equals)</td><td>Determines whether the specified Object is equal to the Vector2.</td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td>Returns a value that indicates whether the current instance is equal to a specified object.</td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td>Gets the hash code of the vector object.</td></tr>
<tr><td>[`bool IsValid()`](VRageMath.IsValid)</td><td></td></tr>
<tr><td>[`void AssertIsValid()`](VRageMath.AssertIsValid)</td><td></td></tr>
<tr><td>[`float Length()`](VRageMath.Length)</td><td>Calculates the length of the vector.</td></tr>
<tr><td>[`float LengthSquared()`](VRageMath.LengthSquared)</td><td>Calculates the length of the vector squared.</td></tr>
<tr><td>static [`float Distance(Vector2 value1, Vector2 value2)`](VRageMath.Distance)</td><td>Calculates the distance between two vectors.</td></tr>
<tr><td>static [`void Distance(ref Vector2 value1, ref Vector2 value2, ref float result)`](VRageMath.Distance)</td><td>Calculates the distance between two vectors.</td></tr>
<tr><td>static [`float DistanceSquared(Vector2 value1, Vector2 value2)`](VRageMath.DistanceSquared)</td><td>Calculates the distance between two vectors squared.</td></tr>
<tr><td>static [`void DistanceSquared(ref Vector2 value1, ref Vector2 value2, ref float result)`](VRageMath.DistanceSquared)</td><td>Calculates the distance between two vectors squared.</td></tr>
<tr><td>static [`float Dot(Vector2 value1, Vector2 value2)`](VRageMath.Dot)</td><td>Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.</td></tr>
<tr><td>static [`void Dot(ref Vector2 value1, ref Vector2 value2, ref float result)`](VRageMath.Dot)</td><td>Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.</td></tr>
<tr><td>[`void Normalize()`](VRageMath.Normalize)</td><td>Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.</td></tr>
<tr><td>static [`Vector2 Normalize(Vector2 value)`](VRageMath.Normalize)</td><td>Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.</td></tr>
<tr><td>static [`void Normalize(ref Vector2 value, ref Vector2 result)`](VRageMath.Normalize)</td><td>Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.</td></tr>
<tr><td>static [`Vector2 Reflect(Vector2 vector, Vector2 normal)`](VRageMath.Reflect)</td><td>Determines the reflect vector of the given vector and normal.</td></tr>
<tr><td>static [`void Reflect(ref Vector2 vector, ref Vector2 normal, ref Vector2 result)`](VRageMath.Reflect)</td><td>Determines the reflect vector of the given vector and normal.</td></tr>
<tr><td>static [`Vector2 Min(Vector2 value1, Vector2 value2)`](VRageMath.Min)</td><td>Returns a vector that contains the lowest value from each matching pair of components.</td></tr>
<tr><td>static [`void Min(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)`](VRageMath.Min)</td><td>Returns a vector that contains the lowest value from each matching pair of components.</td></tr>
<tr><td>static [`Vector2 Max(Vector2 value1, Vector2 value2)`](VRageMath.Max)</td><td>Returns a vector that contains the highest value from each matching pair of components.</td></tr>
<tr><td>static [`void Max(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)`](VRageMath.Max)</td><td>Returns a vector that contains the highest value from each matching pair of components.</td></tr>
<tr><td>static [`Vector2 Clamp(Vector2 value1, Vector2 min, Vector2 max)`](VRageMath.Clamp)</td><td>Restricts a value to be within a specified range.</td></tr>
<tr><td>static [`void Clamp(ref Vector2 value1, ref Vector2 min, ref Vector2 max, ref Vector2 result)`](VRageMath.Clamp)</td><td>Restricts a value to be within a specified range.</td></tr>
<tr><td>static [`Vector2 ClampToSphere(Vector2 vector, float radius)`](VRageMath.ClampToSphere)</td><td></td></tr>
<tr><td>static [`void ClampToSphere(ref Vector2 vector, float radius)`](VRageMath.ClampToSphere)</td><td></td></tr>
<tr><td>static [`Vector2 Lerp(Vector2 value1, Vector2 value2, float amount)`](VRageMath.Lerp)</td><td>Performs a linear interpolation between two vectors.</td></tr>
<tr><td>static [`void Lerp(ref Vector2 value1, ref Vector2 value2, float amount, ref Vector2 result)`](VRageMath.Lerp)</td><td>Performs a linear interpolation between two vectors.</td></tr>
<tr><td>static [`Vector2 Barycentric(Vector2 value1, Vector2 value2, Vector2 value3, float amount1, float amount2)`](VRageMath.Barycentric)</td><td>Returns a Vector2 containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.</td></tr>
<tr><td>static [`void Barycentric(ref Vector2 value1, ref Vector2 value2, ref Vector2 value3, float amount1, float amount2, ref Vector2 result)`](VRageMath.Barycentric)</td><td>Returns a Vector2 containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.</td></tr>
<tr><td>static [`Vector2 SmoothStep(Vector2 value1, Vector2 value2, float amount)`](VRageMath.SmoothStep)</td><td>Interpolates between two values using a cubic equation.</td></tr>
<tr><td>static [`void SmoothStep(ref Vector2 value1, ref Vector2 value2, float amount, ref Vector2 result)`](VRageMath.SmoothStep)</td><td>Interpolates between two values using a cubic equation.</td></tr>
<tr><td>static [`Vector2 CatmullRom(Vector2 value1, Vector2 value2, Vector2 value3, Vector2 value4, float amount)`](VRageMath.CatmullRom)</td><td>Performs a Catmull-Rom interpolation using the specified positions.</td></tr>
<tr><td>static [`void CatmullRom(ref Vector2 value1, ref Vector2 value2, ref Vector2 value3, ref Vector2 value4, float amount, ref Vector2 result)`](VRageMath.CatmullRom)</td><td>Performs a Catmull-Rom interpolation using the specified positions.</td></tr>
<tr><td>static [`Vector2 Hermite(Vector2 value1, Vector2 tangent1, Vector2 value2, Vector2 tangent2, float amount)`](VRageMath.Hermite)</td><td>Performs a Hermite spline interpolation.</td></tr>
<tr><td>static [`void Hermite(ref Vector2 value1, ref Vector2 tangent1, ref Vector2 value2, ref Vector2 tangent2, float amount, ref Vector2 result)`](VRageMath.Hermite)</td><td>Performs a Hermite spline interpolation.</td></tr>
<tr><td>static [`Vector2 Transform(Vector2 position, Matrix matrix)`](VRageMath.Transform)</td><td>Transforms the vector (x, y, 0, 1) by the specified matrix.</td></tr>
<tr><td>static [`void Transform(ref Vector2 position, ref Matrix matrix, ref Vector2 result)`](VRageMath.Transform)</td><td>Transforms a Vector2 by the given Matrix.</td></tr>
<tr><td>static [`Vector2 TransformNormal(Vector2 normal, Matrix matrix)`](VRageMath.TransformNormal)</td><td>Transforms a 2D vector normal by a matrix.</td></tr>
<tr><td>static [`void TransformNormal(ref Vector2 normal, ref Matrix matrix, ref Vector2 result)`](VRageMath.TransformNormal)</td><td>Transforms a vector normal by a matrix.</td></tr>
<tr><td>static [`Vector2 Transform(Vector2 value, Quaternion rotation)`](VRageMath.Transform)</td><td>Transforms a single Vector2, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.</td></tr>
<tr><td>static [`void Transform(ref Vector2 value, ref Quaternion rotation, ref Vector2 result)`](VRageMath.Transform)</td><td>Transforms a Vector2, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.</td></tr>
<tr><td>static [`void Transform(Vector2[] sourceArray, ref Matrix matrix, Vector2[] destinationArray)`](VRageMath.Transform)</td><td>Transforms an array of Vector2s by a specified Matrix.</td></tr>
<tr><td>static [`void Transform(Vector2[] sourceArray, int sourceIndex, ref Matrix matrix, Vector2[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)</td><td>Transforms a specified range in an array of Vector2s by a specified Matrix and places the results in a specified range in a destination array.</td></tr>
<tr><td>static [`void TransformNormal(Vector2[] sourceArray, ref Matrix matrix, Vector2[] destinationArray)`](VRageMath.TransformNormal)</td><td>Transforms an array of Vector2 vector normals by a specified Matrix.</td></tr>
<tr><td>static [`void TransformNormal(Vector2[] sourceArray, int sourceIndex, ref Matrix matrix, Vector2[] destinationArray, int destinationIndex, int length)`](VRageMath.TransformNormal)</td><td>Transforms a specified range in an array of Vector2 vector normals by a specified Matrix and places the results in a specified range in a destination array.</td></tr>
<tr><td>static [`void Transform(Vector2[] sourceArray, ref Quaternion rotation, Vector2[] destinationArray)`](VRageMath.Transform)</td><td>Transforms an array of Vector2s by a specified Quaternion.</td></tr>
<tr><td>static [`void Transform(Vector2[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector2[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)</td><td>Transforms a specified range in an array of Vector2s by a specified Quaternion and places the results in a specified range in a destination array.</td></tr>
<tr><td>static [`Vector2 Negate(Vector2 value)`](VRageMath.Negate)</td><td>Returns a vector pointing in the opposite direction.</td></tr>
<tr><td>static [`void Negate(ref Vector2 value, ref Vector2 result)`](VRageMath.Negate)</td><td>Returns a vector pointing in the opposite direction.</td></tr>
<tr><td>static [`Vector2 Add(Vector2 value1, Vector2 value2)`](VRageMath.Add)</td><td>Adds two vectors.</td></tr>
<tr><td>static [`void Add(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)`](VRageMath.Add)</td><td>Adds two vectors.</td></tr>
<tr><td>static [`Vector2 Subtract(Vector2 value1, Vector2 value2)`](VRageMath.Subtract)</td><td>Subtracts a vector from a vector.</td></tr>
<tr><td>static [`void Subtract(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)`](VRageMath.Subtract)</td><td>Subtracts a vector from a vector.</td></tr>
<tr><td>static [`Vector2 Multiply(Vector2 value1, Vector2 value2)`](VRageMath.Multiply)</td><td>Multiplies the components of two vectors by each other.</td></tr>
<tr><td>static [`void Multiply(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)`](VRageMath.Multiply)</td><td>Multiplies the components of two vectors by each other.</td></tr>
<tr><td>static [`Vector2 Multiply(Vector2 value1, float scaleFactor)`](VRageMath.Multiply)</td><td>Multiplies a vector by a scalar value.</td></tr>
<tr><td>static [`void Multiply(ref Vector2 value1, float scaleFactor, ref Vector2 result)`](VRageMath.Multiply)</td><td>Multiplies a vector by a scalar value.</td></tr>
<tr><td>static [`Vector2 Divide(Vector2 value1, Vector2 value2)`](VRageMath.Divide)</td><td>Divides the components of a vector by the components of another vector.</td></tr>
<tr><td>static [`void Divide(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)`](VRageMath.Divide)</td><td>Divides the components of a vector by the components of another vector.</td></tr>
<tr><td>static [`Vector2 Divide(Vector2 value1, float divider)`](VRageMath.Divide)</td><td>Divides a vector by a scalar value.</td></tr>
<tr><td>static [`void Divide(ref Vector2 value1, float divider, ref Vector2 result)`](VRageMath.Divide)</td><td>Divides a vector by a scalar value.</td></tr>
<tr><td>[`bool Between(ref Vector2 start, ref Vector2 end)`](VRageMath.Between)</td><td></td></tr>
<tr><td>static [`Vector2 Floor(Vector2 position)`](VRageMath.Floor)</td><td></td></tr>
<tr><td>[`void Rotate(double angle)`](VRageMath.Rotate)</td><td></td></tr>
<tr><td>static [`bool IsZero(ref Vector2 value)`](VRageMath.IsZero)</td><td></td></tr>
<tr><td>static [`bool IsZero(ref Vector2 value, float epsilon)`](VRageMath.IsZero)</td><td></td></tr>
<tr><td>static [`bool IsZero(Vector2 value, float epsilon)`](VRageMath.IsZero)</td><td></td></tr>
<tr><td>static [`Vector2 SignNonZero(Vector2 value)`](VRageMath.SignNonZero)</td><td></td></tr>
</table>
