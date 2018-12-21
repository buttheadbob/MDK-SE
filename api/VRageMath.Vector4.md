← [Index](index)
# Vector4 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with four components.
### Fields
<table style="width:100%;display:table">
<tr><td>[`float X`](VRageMath.X)</td><td>Gets or sets the x-component of the vector.</td></tr>
<tr><td>[`float Y`](VRageMath.Y)</td><td>Gets or sets the y-component of the vector.</td></tr>
<tr><td>[`float Z`](VRageMath.Z)</td><td>Gets or sets the z-component of the vector.</td></tr>
<tr><td>[`float W`](VRageMath.W)</td><td>Gets or sets the w-component of the vector.</td></tr>
<tr><td>static [`Vector4 Zero`](VRageMath.Zero)</td><td></td></tr>
<tr><td>static [`Vector4 One`](VRageMath.One)</td><td></td></tr>
<tr><td>static [`Vector4 UnitX`](VRageMath.UnitX)</td><td></td></tr>
<tr><td>static [`Vector4 UnitY`](VRageMath.UnitY)</td><td></td></tr>
<tr><td>static [`Vector4 UnitZ`](VRageMath.UnitZ)</td><td></td></tr>
<tr><td>static [`Vector4 UnitW`](VRageMath.UnitW)</td><td></td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>[`float Item`](VRageMath.Item)</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>static [`Vector4 PackOrthoMatrix(Vector3 position, Vector3 forward, Vector3 up)`](VRageMath.PackOrthoMatrix)</td><td></td></tr>
<tr><td>static [`Vector4 PackOrthoMatrix(ref Matrix matrix)`](VRageMath.PackOrthoMatrix)</td><td></td></tr>
<tr><td>static [`Matrix UnpackOrthoMatrix(ref Vector4 packed)`](VRageMath.UnpackOrthoMatrix)</td><td></td></tr>
<tr><td>static [`void UnpackOrthoMatrix(ref Vector4 packed, ref Matrix matrix)`](VRageMath.UnpackOrthoMatrix)</td><td></td></tr>
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td>Retrieves a string representation of the current object.</td></tr>
<tr><td>[`bool Equals(Vector4 other)`](VRageMath.Equals)</td><td>Determines whether the specified Object is equal to the Vector4.</td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td>Returns a value that indicates whether the current instance is equal to a specified object.</td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td>Gets the hash code of this object.</td></tr>
<tr><td>[`float Length()`](VRageMath.Length)</td><td>Calculates the length of the vector.</td></tr>
<tr><td>[`float LengthSquared()`](VRageMath.LengthSquared)</td><td>Calculates the length of the vector squared.</td></tr>
<tr><td>static [`float Distance(Vector4 value1, Vector4 value2)`](VRageMath.Distance)</td><td>Calculates the distance between two vectors.</td></tr>
<tr><td>static [`void Distance(ref Vector4 value1, ref Vector4 value2, ref float result)`](VRageMath.Distance)</td><td>Calculates the distance between two vectors.</td></tr>
<tr><td>static [`float DistanceSquared(Vector4 value1, Vector4 value2)`](VRageMath.DistanceSquared)</td><td>Calculates the distance between two vectors squared.</td></tr>
<tr><td>static [`void DistanceSquared(ref Vector4 value1, ref Vector4 value2, ref float result)`](VRageMath.DistanceSquared)</td><td>Calculates the distance between two vectors squared.</td></tr>
<tr><td>static [`float Dot(Vector4 vector1, Vector4 vector2)`](VRageMath.Dot)</td><td>Calculates the dot product of two vectors.</td></tr>
<tr><td>static [`void Dot(ref Vector4 vector1, ref Vector4 vector2, ref float result)`](VRageMath.Dot)</td><td>Calculates the dot product of two vectors.</td></tr>
<tr><td>[`void Normalize()`](VRageMath.Normalize)</td><td>Turns the current vector into a unit vector.</td></tr>
<tr><td>static [`Vector4 Normalize(Vector4 vector)`](VRageMath.Normalize)</td><td>Creates a unit vector from the specified vector.</td></tr>
<tr><td>static [`void Normalize(ref Vector4 vector, ref Vector4 result)`](VRageMath.Normalize)</td><td>Returns a normalized version of the specified vector.</td></tr>
<tr><td>static [`Vector4 Min(Vector4 value1, Vector4 value2)`](VRageMath.Min)</td><td>Returns a vector that contains the lowest value from each matching pair of components.</td></tr>
<tr><td>static [`void Min(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Min)</td><td>Returns a vector that contains the lowest value from each matching pair of components.</td></tr>
<tr><td>static [`Vector4 Max(Vector4 value1, Vector4 value2)`](VRageMath.Max)</td><td>Returns a vector that contains the highest value from each matching pair of components.</td></tr>
<tr><td>static [`void Max(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Max)</td><td>Returns a vector that contains the highest value from each matching pair of components.</td></tr>
<tr><td>static [`Vector4 Clamp(Vector4 value1, Vector4 min, Vector4 max)`](VRageMath.Clamp)</td><td>Restricts a value to be within a specified range.</td></tr>
<tr><td>static [`void Clamp(ref Vector4 value1, ref Vector4 min, ref Vector4 max, ref Vector4 result)`](VRageMath.Clamp)</td><td>Restricts a value to be within a specified range.</td></tr>
<tr><td>static [`Vector4 Lerp(Vector4 value1, Vector4 value2, float amount)`](VRageMath.Lerp)</td><td>Performs a linear interpolation between two vectors.</td></tr>
<tr><td>static [`void Lerp(ref Vector4 value1, ref Vector4 value2, float amount, ref Vector4 result)`](VRageMath.Lerp)</td><td>Performs a linear interpolation between two vectors.</td></tr>
<tr><td>static [`Vector4 Barycentric(Vector4 value1, Vector4 value2, Vector4 value3, float amount1, float amount2)`](VRageMath.Barycentric)</td><td>Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 4D triangle.</td></tr>
<tr><td>static [`void Barycentric(ref Vector4 value1, ref Vector4 value2, ref Vector4 value3, float amount1, float amount2, ref Vector4 result)`](VRageMath.Barycentric)</td><td>Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in Barycentric (areal) coordinates relative to a 4D triangle.</td></tr>
<tr><td>static [`Vector4 SmoothStep(Vector4 value1, Vector4 value2, float amount)`](VRageMath.SmoothStep)</td><td>Interpolates between two values using a cubic equation.</td></tr>
<tr><td>static [`void SmoothStep(ref Vector4 value1, ref Vector4 value2, float amount, ref Vector4 result)`](VRageMath.SmoothStep)</td><td>Interpolates between two values using a cubic equation.</td></tr>
<tr><td>static [`Vector4 CatmullRom(Vector4 value1, Vector4 value2, Vector4 value3, Vector4 value4, float amount)`](VRageMath.CatmullRom)</td><td>Performs a Catmull-Rom interpolation using the specified positions.</td></tr>
<tr><td>static [`void CatmullRom(ref Vector4 value1, ref Vector4 value2, ref Vector4 value3, ref Vector4 value4, float amount, ref Vector4 result)`](VRageMath.CatmullRom)</td><td>Performs a Catmull-Rom interpolation using the specified positions.</td></tr>
<tr><td>static [`Vector4 Hermite(Vector4 value1, Vector4 tangent1, Vector4 value2, Vector4 tangent2, float amount)`](VRageMath.Hermite)</td><td>Performs a Hermite spline interpolation.</td></tr>
<tr><td>static [`void Hermite(ref Vector4 value1, ref Vector4 tangent1, ref Vector4 value2, ref Vector4 tangent2, float amount, ref Vector4 result)`](VRageMath.Hermite)</td><td>Performs a Hermite spline interpolation.</td></tr>
<tr><td>static [`Vector4 Transform(Vector2 position, Matrix matrix)`](VRageMath.Transform)</td><td>Transforms a Vector2 by the given Matrix.</td></tr>
<tr><td>static [`void Transform(ref Vector2 position, ref Matrix matrix, ref Vector4 result)`](VRageMath.Transform)</td><td>Transforms a Vector2 by the given Matrix.</td></tr>
<tr><td>static [`Vector4 Transform(Vector3 position, Matrix matrix)`](VRageMath.Transform)</td><td>Transforms a Vector3 by the given Matrix.</td></tr>
<tr><td>static [`void Transform(ref Vector3 position, ref Matrix matrix, ref Vector4 result)`](VRageMath.Transform)</td><td>Transforms a Vector3 by the given Matrix.</td></tr>
<tr><td>static [`Vector4 Transform(Vector4 vector, Matrix matrix)`](VRageMath.Transform)</td><td>Transforms a Vector4 by the specified Matrix.</td></tr>
<tr><td>static [`void Transform(ref Vector4 vector, ref Matrix matrix, ref Vector4 result)`](VRageMath.Transform)</td><td>Transforms a Vector4 by the given Matrix.</td></tr>
<tr><td>static [`Vector4 Transform(Vector2 value, Quaternion rotation)`](VRageMath.Transform)</td><td>Transforms a Vector2 by a specified Quaternion into a Vector4.</td></tr>
<tr><td>static [`void Transform(ref Vector2 value, ref Quaternion rotation, ref Vector4 result)`](VRageMath.Transform)</td><td>Transforms a Vector2 by a specified Quaternion into a Vector4.</td></tr>
<tr><td>static [`Vector4 Transform(Vector3 value, Quaternion rotation)`](VRageMath.Transform)</td><td>Transforms a Vector3 by a specified Quaternion into a Vector4.</td></tr>
<tr><td>static [`void Transform(ref Vector3 value, ref Quaternion rotation, ref Vector4 result)`](VRageMath.Transform)</td><td>Transforms a Vector3 by a specified Quaternion into a Vector4.</td></tr>
<tr><td>static [`Vector4 Transform(Vector4 value, Quaternion rotation)`](VRageMath.Transform)</td><td>Transforms a Vector4 by a specified Quaternion.</td></tr>
<tr><td>static [`void Transform(ref Vector4 value, ref Quaternion rotation, ref Vector4 result)`](VRageMath.Transform)</td><td>Transforms a Vector4 by a specified Quaternion.</td></tr>
<tr><td>static [`void Transform(Vector4[] sourceArray, ref Matrix matrix, Vector4[] destinationArray)`](VRageMath.Transform)</td><td>Transforms an array of Vector4s by a specified Matrix.</td></tr>
<tr><td>static [`void Transform(Vector4[] sourceArray, int sourceIndex, ref Matrix matrix, Vector4[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)</td><td>Transforms a specified range in an array of Vector4s by a specified Matrix into a specified range in a destination array.</td></tr>
<tr><td>static [`void Transform(Vector4[] sourceArray, ref Quaternion rotation, Vector4[] destinationArray)`](VRageMath.Transform)</td><td>Transforms an array of Vector4s by a specified Quaternion.</td></tr>
<tr><td>static [`void Transform(Vector4[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector4[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform)</td><td>Transforms a specified range in an array of Vector4s by a specified Quaternion into a specified range in a destination array.</td></tr>
<tr><td>static [`Vector4 Negate(Vector4 value)`](VRageMath.Negate)</td><td>Returns a vector pointing in the opposite direction.</td></tr>
<tr><td>static [`void Negate(ref Vector4 value, ref Vector4 result)`](VRageMath.Negate)</td><td>Returns a vector pointing in the opposite direction.</td></tr>
<tr><td>static [`Vector4 Add(Vector4 value1, Vector4 value2)`](VRageMath.Add)</td><td>Adds two vectors.</td></tr>
<tr><td>static [`void Add(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Add)</td><td>Adds two vectors.</td></tr>
<tr><td>static [`Vector4 Subtract(Vector4 value1, Vector4 value2)`](VRageMath.Subtract)</td><td>Subtracts a vector from a vector.</td></tr>
<tr><td>static [`void Subtract(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Subtract)</td><td>Subtracts a vector from a vector.</td></tr>
<tr><td>static [`Vector4 Multiply(Vector4 value1, Vector4 value2)`](VRageMath.Multiply)</td><td>Multiplies the components of two vectors by each other.</td></tr>
<tr><td>static [`void Multiply(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Multiply)</td><td>Multiplies the components of two vectors by each other.</td></tr>
<tr><td>static [`Vector4 Multiply(Vector4 value1, float scaleFactor)`](VRageMath.Multiply)</td><td>Multiplies a vector by a scalar.</td></tr>
<tr><td>static [`void Multiply(ref Vector4 value1, float scaleFactor, ref Vector4 result)`](VRageMath.Multiply)</td><td>Multiplies a vector by a scalar value.</td></tr>
<tr><td>static [`Vector4 Divide(Vector4 value1, Vector4 value2)`](VRageMath.Divide)</td><td>Divides the components of a vector by the components of another vector.</td></tr>
<tr><td>static [`void Divide(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)`](VRageMath.Divide)</td><td>Divides the components of a vector by the components of another vector.</td></tr>
<tr><td>static [`Vector4 Divide(Vector4 value1, float divider)`](VRageMath.Divide)</td><td>Divides a vector by a scalar value.</td></tr>
<tr><td>static [`void Divide(ref Vector4 value1, float divider, ref Vector4 result)`](VRageMath.Divide)</td><td>Divides a vector by a scalar value.</td></tr>
</table>
