← [Index](index)
# Vector4D Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with four components.
### Fields
<table style="width: 100%">
<tr><td>[`double X`](VRageMath.X)</td><td>Gets or sets the x-component of the vector.</td></tr>
<tr><td>[`double Y`](VRageMath.Y)</td><td>Gets or sets the y-component of the vector.</td></tr>
<tr><td>[`double Z`](VRageMath.Z)</td><td>Gets or sets the z-component of the vector.</td></tr>
<tr><td>[`double W`](VRageMath.W)</td><td>Gets or sets the w-component of the vector.</td></tr>
<tr><td>static [`Vector4D Zero`](VRageMath.Zero)</td><td></td></tr>
<tr><td>static [`Vector4D One`](VRageMath.One)</td><td></td></tr>
<tr><td>static [`Vector4D UnitX`](VRageMath.UnitX)</td><td></td></tr>
<tr><td>static [`Vector4D UnitY`](VRageMath.UnitY)</td><td></td></tr>
<tr><td>static [`Vector4D UnitZ`](VRageMath.UnitZ)</td><td></td></tr>
<tr><td>static [`Vector4D UnitW`](VRageMath.UnitW)</td><td></td></tr>
</table>
### Methods
<table style="width: 100%">
<tr><td>static [`Vector4D PackOrthoMatrix(Vector3D position, Vector3D forward, Vector3D up)`](VRageMath.PackOrthoMatrix)</td><td></td></tr>
<tr><td>static [`Vector4D PackOrthoMatrix(ref MatrixD matrix)`](VRageMath.PackOrthoMatrix)</td><td></td></tr>
<tr><td>static [`MatrixD UnpackOrthoMatrix(ref Vector4D packed)`](VRageMath.UnpackOrthoMatrix)</td><td></td></tr>
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td>Retrieves a string representation of the current object.</td></tr>
<tr><td>[`bool Equals(Vector4 other)`](VRageMath.Equals)</td><td>Determines whether the specified Object is equal to the Vector4.</td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td>Returns a value that indicates whether the current instance is equal to a specified object.</td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td>Gets the hash code of this object.</td></tr>
<tr><td>[`double Length()`](VRageMath.Length)</td><td>Calculates the length of the vector.</td></tr>
<tr><td>[`double LengthSquared()`](VRageMath.LengthSquared)</td><td>Calculates the length of the vector squared.</td></tr>
<tr><td>static [`double Distance(Vector4 value1, Vector4 value2)`](VRageMath.Distance)</td><td>Calculates the distance between two vectors.</td></tr>
<tr><td>static [`void Distance(ref Vector4 value1, ref Vector4 value2, ref double result)`](VRageMath.Distance)</td><td>Calculates the distance between two vectors.</td></tr>
<tr><td>static [`double DistanceSquared(Vector4 value1, Vector4 value2)`](VRageMath.DistanceSquared)</td><td>Calculates the distance between two vectors squared.</td></tr>
<tr><td>static [`void DistanceSquared(ref Vector4 value1, ref Vector4 value2, ref double result)`](VRageMath.DistanceSquared)</td><td>Calculates the distance between two vectors squared.</td></tr>
<tr><td>static [`double Dot(Vector4 vector1, Vector4 vector2)`](VRageMath.Dot)</td><td>Calculates the dot product of two vectors.</td></tr>
<tr><td>static [`void Dot(ref Vector4 vector1, ref Vector4 vector2, ref double result)`](VRageMath.Dot)</td><td>Calculates the dot product of two vectors.</td></tr>
<tr><td>[`void Normalize()`](VRageMath.Normalize)</td><td>Turns the current vector into a unit vector.</td></tr>
<tr><td>static [`Vector4D Normalize(Vector4D vector)`](VRageMath.Normalize)</td><td>Creates a unit vector from the specified vector.</td></tr>
<tr><td>static [`void Normalize(ref Vector4D vector, ref Vector4D result)`](VRageMath.Normalize)</td><td>Returns a normalized version of the specified vector.</td></tr>
<tr><td>static [`Vector4 Min(Vector4 value1, Vector4 value2)`](VRageMath.Min)</td><td>Returns a vector that contains the lowest value from each matching pair of components.</td></tr>
<tr><td>static [`void Min(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Min)</td><td>Returns a vector that contains the lowest value from each matching pair of components.</td></tr>
<tr><td>static [`Vector4 Max(Vector4 value1, Vector4 value2)`](VRageMath.Max)</td><td>Returns a vector that contains the highest value from each matching pair of components.</td></tr>
<tr><td>static [`void Max(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Max)</td><td>Returns a vector that contains the highest value from each matching pair of components.</td></tr>
<tr><td>static [`Vector4D Clamp(Vector4D value1, Vector4D min, Vector4D max)`](VRageMath.Clamp)</td><td>Restricts a value to be within a specified range.</td></tr>
<tr><td>static [`void Clamp(ref Vector4D value1, ref Vector4D min, ref Vector4D max, ref Vector4D result)`](VRageMath.Clamp)</td><td>Restricts a value to be within a specified range.</td></tr>
<tr><td>static [`Vector4D Lerp(Vector4D value1, Vector4D value2, double amount)`](VRageMath.Lerp)</td><td>Performs a linear interpolation between two vectors.</td></tr>
<tr><td>static [`void Lerp(ref Vector4D value1, ref Vector4D value2, double amount, ref Vector4D result)`](VRageMath.Lerp)</td><td>Performs a linear interpolation between two vectors.</td></tr>
<tr><td>static [`Vector4D Barycentric(Vector4D value1, Vector4D value2, Vector4D value3, double amount1, double amount2)`](VRageMath.Barycentric)</td><td>Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 4D triangle.</td></tr>
<tr><td>static [`void Barycentric(ref Vector4D value1, ref Vector4D value2, ref Vector4D value3, double amount1, double amount2, ref Vector4D result)`](VRageMath.Barycentric)</td><td>Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in Barycentric (areal) coordinates relative to a 4D triangle.</td></tr>
<tr><td>static [`Vector4D SmoothStep(Vector4D value1, Vector4D value2, double amount)`](VRageMath.SmoothStep)</td><td>Interpolates between two values using a cubic equation.</td></tr>
<tr><td>static [`void SmoothStep(ref Vector4D value1, ref Vector4D value2, double amount, ref Vector4D result)`](VRageMath.SmoothStep)</td><td>Interpolates between two values using a cubic equation.</td></tr>
<tr><td>static [`Vector4D CatmullRom(Vector4D value1, Vector4D value2, Vector4D value3, Vector4D value4, double amount)`](VRageMath.CatmullRom)</td><td>Performs a Catmull-Rom interpolation using the specified positions.</td></tr>
<tr><td>static [`void CatmullRom(ref Vector4D value1, ref Vector4D value2, ref Vector4D value3, ref Vector4D value4, double amount, ref Vector4D result)`](VRageMath.CatmullRom)</td><td>Performs a Catmull-Rom interpolation using the specified positions.</td></tr>
<tr><td>static [`Vector4D Hermite(Vector4D value1, Vector4D tangent1, Vector4D value2, Vector4D tangent2, double amount)`](VRageMath.Hermite)</td><td>Performs a Hermite spline interpolation.</td></tr>
<tr><td>static [`void Hermite(ref Vector4D value1, ref Vector4D tangent1, ref Vector4D value2, ref Vector4D tangent2, double amount, ref Vector4D result)`](VRageMath.Hermite)</td><td>Performs a Hermite spline interpolation.</td></tr>
<tr><td>static [`Vector4D Transform(Vector2 position, MatrixD matrix)`](VRageMath.Transform)</td><td>Transforms a Vector2 by the given Matrix.</td></tr>
<tr><td>static [`void Transform(ref Vector2 position, ref MatrixD matrix, ref Vector4D result)`](VRageMath.Transform)</td><td>Transforms a Vector2 by the given Matrix.</td></tr>
<tr><td>static [`Vector4D Transform(Vector3D position, MatrixD matrix)`](VRageMath.Transform)</td><td>Transforms a Vector3 by the given Matrix.</td></tr>
<tr><td>static [`void Transform(ref Vector3D position, ref MatrixD matrix, ref Vector4D result)`](VRageMath.Transform)</td><td>Transforms a Vector3 by the given Matrix.</td></tr>
<tr><td>static [`Vector4D Transform(Vector4D vector, MatrixD matrix)`](VRageMath.Transform)</td><td>Transforms a Vector4 by the specified Matrix.</td></tr>
<tr><td>static [`void Transform(ref Vector4D vector, ref MatrixD matrix, ref Vector4D result)`](VRageMath.Transform)</td><td>Transforms a Vector4 by the given Matrix.</td></tr>
<tr><td>static [`Vector4D Transform(Vector2 value, Quaternion rotation)`](VRageMath.Transform)</td><td>Transforms a Vector2 by a specified Quaternion into a Vector4.</td></tr>
<tr><td>static [`void Transform(ref Vector2 value, ref Quaternion rotation, ref Vector4D result)`](VRageMath.Transform)</td><td>Transforms a Vector2 by a specified Quaternion into a Vector4.</td></tr>
<tr><td>static [`Vector4D Transform(Vector3D value, Quaternion rotation)`](VRageMath.Transform)</td><td>Transforms a Vector3 by a specified Quaternion into a Vector4.</td></tr>
<tr><td>static [`void Transform(ref Vector3D value, ref Quaternion rotation, ref Vector4D result)`](VRageMath.Transform)</td><td>Transforms a Vector3 by a specified Quaternion into a Vector4.</td></tr>
<tr><td>static [`Vector4D Transform(Vector4D value, Quaternion rotation)`](VRageMath.Transform)</td><td>Transforms a Vector4 by a specified Quaternion.</td></tr>
<tr><td>static [`void Transform(ref Vector4D value, ref Quaternion rotation, ref Vector4D result)`](VRageMath.Transform)</td><td>Transforms a Vector4 by a specified Quaternion.</td></tr>
<tr><td>static [`void Transform(Vector4D[] sourceArray, ref MatrixD matrix, Vector4D[] destinationArray)`](VRageMath.Transform)</td><td>Transforms an array of Vector4s by a specified Matrix.</td></tr>
<tr><td>static [`void Transform(Vector4D[] sourceArray, int sourceIndex, ref MatrixD matrix, Vector4D[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)</td><td>Transforms a specified range in an array of Vector4s by a specified Matrix into a specified range in a destination array.</td></tr>
<tr><td>static [`void Transform(Vector4D[] sourceArray, ref Quaternion rotation, Vector4D[] destinationArray)`](VRageMath.Transform)</td><td>Transforms an array of Vector4s by a specified Quaternion.</td></tr>
<tr><td>static [`void Transform(Vector4D[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector4D[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)</td><td>Transforms a specified range in an array of Vector4s by a specified Quaternion into a specified range in a destination array.</td></tr>
<tr><td>static [`Vector4D Negate(Vector4D value)`](VRageMath.Negate)</td><td>Returns a vector pointing in the opposite direction.</td></tr>
<tr><td>static [`void Negate(ref Vector4D value, ref Vector4D result)`](VRageMath.Negate)</td><td>Returns a vector pointing in the opposite direction.</td></tr>
<tr><td>static [`Vector4D Add(Vector4D value1, Vector4D value2)`](VRageMath.Add)</td><td>Adds two vectors.</td></tr>
<tr><td>static [`void Add(ref Vector4D value1, ref Vector4D value2, ref Vector4D result)`](VRageMath.Add)</td><td>Adds two vectors.</td></tr>
<tr><td>static [`Vector4 Subtract(Vector4 value1, Vector4 value2)`](VRageMath.Subtract)</td><td>Subtracts a vector from a vector.</td></tr>
<tr><td>static [`void Subtract(ref Vector4D value1, ref Vector4D value2, ref Vector4D result)`](VRageMath.Subtract)</td><td>Subtracts a vector from a vector.</td></tr>
<tr><td>static [`Vector4D Multiply(Vector4D value1, Vector4D value2)`](VRageMath.Multiply)</td><td>Multiplies the components of two vectors by each other.</td></tr>
<tr><td>static [`void Multiply(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Multiply)</td><td>Multiplies the components of two vectors by each other.</td></tr>
<tr><td>static [`Vector4D Multiply(Vector4D value1, double scaleFactor)`](VRageMath.Multiply)</td><td>Multiplies a vector by a scalar.</td></tr>
<tr><td>static [`void Multiply(ref Vector4D value1, double scaleFactor, ref Vector4D result)`](VRageMath.Multiply)</td><td>Multiplies a vector by a scalar value.</td></tr>
<tr><td>static [`Vector4D Divide(Vector4D value1, Vector4D value2)`](VRageMath.Divide)</td><td>Divides the components of a vector by the components of another vector.</td></tr>
<tr><td>static [`void Divide(ref Vector4D value1, ref Vector4D value2, ref Vector4D result)`](VRageMath.Divide)</td><td>Divides the components of a vector by the components of another vector.</td></tr>
<tr><td>static [`Vector4D Divide(Vector4D value1, double divider)`](VRageMath.Divide)</td><td>Divides a vector by a scalar value.</td></tr>
<tr><td>static [`void Divide(ref Vector4D value1, double divider, ref Vector4D result)`](VRageMath.Divide)</td><td>Divides a vector by a scalar value.</td></tr>
</table>
