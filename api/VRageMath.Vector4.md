← [Index](index)
# Vector4 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with four components.
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.X"><code>float X</code></a>_</td><td>Gets or sets the x-component of the vector.</td></tr>
<tr><td>_<a href="VRageMath.Y"><code>float Y</code></a>_</td><td>Gets or sets the y-component of the vector.</td></tr>
<tr><td>_<a href="VRageMath.Z"><code>float Z</code></a>_</td><td>Gets or sets the z-component of the vector.</td></tr>
<tr><td>_<a href="VRageMath.W"><code>float W</code></a>_</td><td>Gets or sets the w-component of the vector.</td></tr>
<tr><td>static _<a href="VRageMath.Zero"><code>Vector4 Zero</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.One"><code>Vector4 One</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.UnitX"><code>Vector4 UnitX</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.UnitY"><code>Vector4 UnitY</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.UnitZ"><code>Vector4 UnitZ</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.UnitW"><code>Vector4 UnitW</code></a>_</td><td></td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Item"><code>float Item</code></a>_</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>static _<a href="VRageMath.PackOrthoMatrix"><code>Vector4 PackOrthoMatrix(Vector3 position, Vector3 forward, Vector3 up)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.PackOrthoMatrix"><code>Vector4 PackOrthoMatrix(ref Matrix matrix)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.UnpackOrthoMatrix"><code>Matrix UnpackOrthoMatrix(ref Vector4 packed)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.UnpackOrthoMatrix"><code>void UnpackOrthoMatrix(ref Vector4 packed, ref Matrix matrix)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.ToString"><code>string ToString()</code></a>_</td><td>Retrieves a string representation of the current object.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Vector4 other)</code></a>_</td><td>Determines whether the specified Object is equal to the Vector4.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Object obj)</code></a>_</td><td>Returns a value that indicates whether the current instance is equal to a specified object.</td></tr>
<tr><td>_<a href="VRageMath.GetHashCode"><code>int GetHashCode()</code></a>_</td><td>Gets the hash code of this object.</td></tr>
<tr><td>_<a href="VRageMath.Length"><code>float Length()</code></a>_</td><td>Calculates the length of the vector.</td></tr>
<tr><td>_<a href="VRageMath.LengthSquared"><code>float LengthSquared()</code></a>_</td><td>Calculates the length of the vector squared.</td></tr>
<tr><td>static _<a href="VRageMath.Distance"><code>float Distance(Vector4 value1, Vector4 value2)</code></a>_</td><td>Calculates the distance between two vectors.</td></tr>
<tr><td>static _<a href="VRageMath.Distance"><code>void Distance(ref Vector4 value1, ref Vector4 value2, ref float result)</code></a>_</td><td>Calculates the distance between two vectors.</td></tr>
<tr><td>static _<a href="VRageMath.DistanceSquared"><code>float DistanceSquared(Vector4 value1, Vector4 value2)</code></a>_</td><td>Calculates the distance between two vectors squared.</td></tr>
<tr><td>static _<a href="VRageMath.DistanceSquared"><code>void DistanceSquared(ref Vector4 value1, ref Vector4 value2, ref float result)</code></a>_</td><td>Calculates the distance between two vectors squared.</td></tr>
<tr><td>static _<a href="VRageMath.Dot"><code>float Dot(Vector4 vector1, Vector4 vector2)</code></a>_</td><td>Calculates the dot product of two vectors.</td></tr>
<tr><td>static _<a href="VRageMath.Dot"><code>void Dot(ref Vector4 vector1, ref Vector4 vector2, ref float result)</code></a>_</td><td>Calculates the dot product of two vectors.</td></tr>
<tr><td>_<a href="VRageMath.Normalize"><code>void Normalize()</code></a>_</td><td>Turns the current vector into a unit vector.</td></tr>
<tr><td>static _<a href="VRageMath.Normalize"><code>Vector4 Normalize(Vector4 vector)</code></a>_</td><td>Creates a unit vector from the specified vector.</td></tr>
<tr><td>static _<a href="VRageMath.Normalize"><code>void Normalize(ref Vector4 vector, ref Vector4 result)</code></a>_</td><td>Returns a normalized version of the specified vector.</td></tr>
<tr><td>static _<a href="VRageMath.Min"><code>Vector4 Min(Vector4 value1, Vector4 value2)</code></a>_</td><td>Returns a vector that contains the lowest value from each matching pair of components.</td></tr>
<tr><td>static _<a href="VRageMath.Min"><code>void Min(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)</code></a>_</td><td>Returns a vector that contains the lowest value from each matching pair of components.</td></tr>
<tr><td>static _<a href="VRageMath.Max"><code>Vector4 Max(Vector4 value1, Vector4 value2)</code></a>_</td><td>Returns a vector that contains the highest value from each matching pair of components.</td></tr>
<tr><td>static _<a href="VRageMath.Max"><code>void Max(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)</code></a>_</td><td>Returns a vector that contains the highest value from each matching pair of components.</td></tr>
<tr><td>static _<a href="VRageMath.Clamp"><code>Vector4 Clamp(Vector4 value1, Vector4 min, Vector4 max)</code></a>_</td><td>Restricts a value to be within a specified range.</td></tr>
<tr><td>static _<a href="VRageMath.Clamp"><code>void Clamp(ref Vector4 value1, ref Vector4 min, ref Vector4 max, ref Vector4 result)</code></a>_</td><td>Restricts a value to be within a specified range.</td></tr>
<tr><td>static _<a href="VRageMath.Lerp"><code>Vector4 Lerp(Vector4 value1, Vector4 value2, float amount)</code></a>_</td><td>Performs a linear interpolation between two vectors.</td></tr>
<tr><td>static _<a href="VRageMath.Lerp"><code>void Lerp(ref Vector4 value1, ref Vector4 value2, float amount, ref Vector4 result)</code></a>_</td><td>Performs a linear interpolation between two vectors.</td></tr>
<tr><td>static _<a href="VRageMath.Barycentric"><code>Vector4 Barycentric(Vector4 value1, Vector4 value2, Vector4 value3, float amount1, float amount2)</code></a>_</td><td>Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 4D triangle.</td></tr>
<tr><td>static _<a href="VRageMath.Barycentric"><code>void Barycentric(ref Vector4 value1, ref Vector4 value2, ref Vector4 value3, float amount1, float amount2, ref Vector4 result)</code></a>_</td><td>Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in Barycentric (areal) coordinates relative to a 4D triangle.</td></tr>
<tr><td>static _<a href="VRageMath.SmoothStep"><code>Vector4 SmoothStep(Vector4 value1, Vector4 value2, float amount)</code></a>_</td><td>Interpolates between two values using a cubic equation.</td></tr>
<tr><td>static _<a href="VRageMath.SmoothStep"><code>void SmoothStep(ref Vector4 value1, ref Vector4 value2, float amount, ref Vector4 result)</code></a>_</td><td>Interpolates between two values using a cubic equation.</td></tr>
<tr><td>static _<a href="VRageMath.CatmullRom"><code>Vector4 CatmullRom(Vector4 value1, Vector4 value2, Vector4 value3, Vector4 value4, float amount)</code></a>_</td><td>Performs a Catmull-Rom interpolation using the specified positions.</td></tr>
<tr><td>static _<a href="VRageMath.CatmullRom"><code>void CatmullRom(ref Vector4 value1, ref Vector4 value2, ref Vector4 value3, ref Vector4 value4, float amount, ref Vector4 result)</code></a>_</td><td>Performs a Catmull-Rom interpolation using the specified positions.</td></tr>
<tr><td>static _<a href="VRageMath.Hermite"><code>Vector4 Hermite(Vector4 value1, Vector4 tangent1, Vector4 value2, Vector4 tangent2, float amount)</code></a>_</td><td>Performs a Hermite spline interpolation.</td></tr>
<tr><td>static _<a href="VRageMath.Hermite"><code>void Hermite(ref Vector4 value1, ref Vector4 tangent1, ref Vector4 value2, ref Vector4 tangent2, float amount, ref Vector4 result)</code></a>_</td><td>Performs a Hermite spline interpolation.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>Vector4 Transform(Vector2 position, Matrix matrix)</code></a>_</td><td>Transforms a Vector2 by the given Matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(ref Vector2 position, ref Matrix matrix, ref Vector4 result)</code></a>_</td><td>Transforms a Vector2 by the given Matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>Vector4 Transform(Vector3 position, Matrix matrix)</code></a>_</td><td>Transforms a Vector3 by the given Matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(ref Vector3 position, ref Matrix matrix, ref Vector4 result)</code></a>_</td><td>Transforms a Vector3 by the given Matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>Vector4 Transform(Vector4 vector, Matrix matrix)</code></a>_</td><td>Transforms a Vector4 by the specified Matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(ref Vector4 vector, ref Matrix matrix, ref Vector4 result)</code></a>_</td><td>Transforms a Vector4 by the given Matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>Vector4 Transform(Vector2 value, Quaternion rotation)</code></a>_</td><td>Transforms a Vector2 by a specified Quaternion into a Vector4.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(ref Vector2 value, ref Quaternion rotation, ref Vector4 result)</code></a>_</td><td>Transforms a Vector2 by a specified Quaternion into a Vector4.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>Vector4 Transform(Vector3 value, Quaternion rotation)</code></a>_</td><td>Transforms a Vector3 by a specified Quaternion into a Vector4.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(ref Vector3 value, ref Quaternion rotation, ref Vector4 result)</code></a>_</td><td>Transforms a Vector3 by a specified Quaternion into a Vector4.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>Vector4 Transform(Vector4 value, Quaternion rotation)</code></a>_</td><td>Transforms a Vector4 by a specified Quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(ref Vector4 value, ref Quaternion rotation, ref Vector4 result)</code></a>_</td><td>Transforms a Vector4 by a specified Quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(Vector4[] sourceArray, ref Matrix matrix, Vector4[] destinationArray)</code></a>_</td><td>Transforms an array of Vector4s by a specified Matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(Vector4[] sourceArray, int sourceIndex, ref Matrix matrix, Vector4[] destinationArray, int destinationIndex, int length)</code></a>_</td><td>Transforms a specified range in an array of Vector4s by a specified Matrix into a specified range in a destination array.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(Vector4[] sourceArray, ref Quaternion rotation, Vector4[] destinationArray)</code></a>_</td><td>Transforms an array of Vector4s by a specified Quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(Vector4[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector4[] destinationArray, int destinationIndex, int length)</code></a>_</td><td>Transforms a specified range in an array of Vector4s by a specified Quaternion into a specified range in a destination array.</td></tr>
<tr><td>static _<a href="VRageMath.Negate"><code>Vector4 Negate(Vector4 value)</code></a>_</td><td>Returns a vector pointing in the opposite direction.</td></tr>
<tr><td>static _<a href="VRageMath.Negate"><code>void Negate(ref Vector4 value, ref Vector4 result)</code></a>_</td><td>Returns a vector pointing in the opposite direction.</td></tr>
<tr><td>static _<a href="VRageMath.Add"><code>Vector4 Add(Vector4 value1, Vector4 value2)</code></a>_</td><td>Adds two vectors.</td></tr>
<tr><td>static _<a href="VRageMath.Add"><code>void Add(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)</code></a>_</td><td>Adds two vectors.</td></tr>
<tr><td>static _<a href="VRageMath.Subtract"><code>Vector4 Subtract(Vector4 value1, Vector4 value2)</code></a>_</td><td>Subtracts a vector from a vector.</td></tr>
<tr><td>static _<a href="VRageMath.Subtract"><code>void Subtract(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)</code></a>_</td><td>Subtracts a vector from a vector.</td></tr>
<tr><td>static _<a href="VRageMath.Multiply"><code>Vector4 Multiply(Vector4 value1, Vector4 value2)</code></a>_</td><td>Multiplies the components of two vectors by each other.</td></tr>
<tr><td>static _<a href="VRageMath.Multiply"><code>void Multiply(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)</code></a>_</td><td>Multiplies the components of two vectors by each other.</td></tr>
<tr><td>static _<a href="VRageMath.Multiply"><code>Vector4 Multiply(Vector4 value1, float scaleFactor)</code></a>_</td><td>Multiplies a vector by a scalar.</td></tr>
<tr><td>static _<a href="VRageMath.Multiply"><code>void Multiply(ref Vector4 value1, float scaleFactor, ref Vector4 result)</code></a>_</td><td>Multiplies a vector by a scalar value.</td></tr>
<tr><td>static _<a href="VRageMath.Divide"><code>Vector4 Divide(Vector4 value1, Vector4 value2)</code></a>_</td><td>Divides the components of a vector by the components of another vector.</td></tr>
<tr><td>static _<a href="VRageMath.Divide"><code>void Divide(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)</code></a>_</td><td>Divides the components of a vector by the components of another vector.</td></tr>
<tr><td>static _<a href="VRageMath.Divide"><code>Vector4 Divide(Vector4 value1, float divider)</code></a>_</td><td>Divides a vector by a scalar value.</td></tr>
<tr><td>static _<a href="VRageMath.Divide"><code>void Divide(ref Vector4 value1, float divider, ref Vector4 result)</code></a>_</td><td>Divides a vector by a scalar value.</td></tr>
</table>
