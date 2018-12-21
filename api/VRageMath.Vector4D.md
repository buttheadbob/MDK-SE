← [Index](index)
# Vector4D Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with four components.
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.X"><code>double X</code></a>_</td><td>Gets or sets the x-component of the vector.</td></tr>
<tr><td>_<a href="VRageMath.Y"><code>double Y</code></a>_</td><td>Gets or sets the y-component of the vector.</td></tr>
<tr><td>_<a href="VRageMath.Z"><code>double Z</code></a>_</td><td>Gets or sets the z-component of the vector.</td></tr>
<tr><td>_<a href="VRageMath.W"><code>double W</code></a>_</td><td>Gets or sets the w-component of the vector.</td></tr>
<tr><td>static _<a href="VRageMath.Zero"><code>Vector4D Zero</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.One"><code>Vector4D One</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.UnitX"><code>Vector4D UnitX</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.UnitY"><code>Vector4D UnitY</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.UnitZ"><code>Vector4D UnitZ</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.UnitW"><code>Vector4D UnitW</code></a>_</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>static _<a href="VRageMath.PackOrthoMatrix"><code>Vector4D PackOrthoMatrix(Vector3D position, Vector3D forward, Vector3D up)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.PackOrthoMatrix"><code>Vector4D PackOrthoMatrix(ref MatrixD matrix)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.UnpackOrthoMatrix"><code>MatrixD UnpackOrthoMatrix(ref Vector4D packed)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.ToString"><code>string ToString()</code></a>_</td><td>Retrieves a string representation of the current object.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Vector4 other)</code></a>_</td><td>Determines whether the specified Object is equal to the Vector4.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Object obj)</code></a>_</td><td>Returns a value that indicates whether the current instance is equal to a specified object.</td></tr>
<tr><td>_<a href="VRageMath.GetHashCode"><code>int GetHashCode()</code></a>_</td><td>Gets the hash code of this object.</td></tr>
<tr><td>_<a href="VRageMath.Length"><code>double Length()</code></a>_</td><td>Calculates the length of the vector.</td></tr>
<tr><td>_<a href="VRageMath.LengthSquared"><code>double LengthSquared()</code></a>_</td><td>Calculates the length of the vector squared.</td></tr>
<tr><td>static _<a href="VRageMath.Distance"><code>double Distance(Vector4 value1, Vector4 value2)</code></a>_</td><td>Calculates the distance between two vectors.</td></tr>
<tr><td>static _<a href="VRageMath.Distance"><code>void Distance(ref Vector4 value1, ref Vector4 value2, ref double result)</code></a>_</td><td>Calculates the distance between two vectors.</td></tr>
<tr><td>static _<a href="VRageMath.DistanceSquared"><code>double DistanceSquared(Vector4 value1, Vector4 value2)</code></a>_</td><td>Calculates the distance between two vectors squared.</td></tr>
<tr><td>static _<a href="VRageMath.DistanceSquared"><code>void DistanceSquared(ref Vector4 value1, ref Vector4 value2, ref double result)</code></a>_</td><td>Calculates the distance between two vectors squared.</td></tr>
<tr><td>static _<a href="VRageMath.Dot"><code>double Dot(Vector4 vector1, Vector4 vector2)</code></a>_</td><td>Calculates the dot product of two vectors.</td></tr>
<tr><td>static _<a href="VRageMath.Dot"><code>void Dot(ref Vector4 vector1, ref Vector4 vector2, ref double result)</code></a>_</td><td>Calculates the dot product of two vectors.</td></tr>
<tr><td>_<a href="VRageMath.Normalize"><code>void Normalize()</code></a>_</td><td>Turns the current vector into a unit vector.</td></tr>
<tr><td>static _<a href="VRageMath.Normalize"><code>Vector4D Normalize(Vector4D vector)</code></a>_</td><td>Creates a unit vector from the specified vector.</td></tr>
<tr><td>static _<a href="VRageMath.Normalize"><code>void Normalize(ref Vector4D vector, ref Vector4D result)</code></a>_</td><td>Returns a normalized version of the specified vector.</td></tr>
<tr><td>static _<a href="VRageMath.Min"><code>Vector4 Min(Vector4 value1, Vector4 value2)</code></a>_</td><td>Returns a vector that contains the lowest value from each matching pair of components.</td></tr>
<tr><td>static _<a href="VRageMath.Min"><code>void Min(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)</code></a>_</td><td>Returns a vector that contains the lowest value from each matching pair of components.</td></tr>
<tr><td>static _<a href="VRageMath.Max"><code>Vector4 Max(Vector4 value1, Vector4 value2)</code></a>_</td><td>Returns a vector that contains the highest value from each matching pair of components.</td></tr>
<tr><td>static _<a href="VRageMath.Max"><code>void Max(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)</code></a>_</td><td>Returns a vector that contains the highest value from each matching pair of components.</td></tr>
<tr><td>static _<a href="VRageMath.Clamp"><code>Vector4D Clamp(Vector4D value1, Vector4D min, Vector4D max)</code></a>_</td><td>Restricts a value to be within a specified range.</td></tr>
<tr><td>static _<a href="VRageMath.Clamp"><code>void Clamp(ref Vector4D value1, ref Vector4D min, ref Vector4D max, ref Vector4D result)</code></a>_</td><td>Restricts a value to be within a specified range.</td></tr>
<tr><td>static _<a href="VRageMath.Lerp"><code>Vector4D Lerp(Vector4D value1, Vector4D value2, double amount)</code></a>_</td><td>Performs a linear interpolation between two vectors.</td></tr>
<tr><td>static _<a href="VRageMath.Lerp"><code>void Lerp(ref Vector4D value1, ref Vector4D value2, double amount, ref Vector4D result)</code></a>_</td><td>Performs a linear interpolation between two vectors.</td></tr>
<tr><td>static _<a href="VRageMath.Barycentric"><code>Vector4D Barycentric(Vector4D value1, Vector4D value2, Vector4D value3, double amount1, double amount2)</code></a>_</td><td>Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 4D triangle.</td></tr>
<tr><td>static _<a href="VRageMath.Barycentric"><code>void Barycentric(ref Vector4D value1, ref Vector4D value2, ref Vector4D value3, double amount1, double amount2, ref Vector4D result)</code></a>_</td><td>Returns a Vector4 containing the 4D Cartesian coordinates of a point specified in Barycentric (areal) coordinates relative to a 4D triangle.</td></tr>
<tr><td>static _<a href="VRageMath.SmoothStep"><code>Vector4D SmoothStep(Vector4D value1, Vector4D value2, double amount)</code></a>_</td><td>Interpolates between two values using a cubic equation.</td></tr>
<tr><td>static _<a href="VRageMath.SmoothStep"><code>void SmoothStep(ref Vector4D value1, ref Vector4D value2, double amount, ref Vector4D result)</code></a>_</td><td>Interpolates between two values using a cubic equation.</td></tr>
<tr><td>static _<a href="VRageMath.CatmullRom"><code>Vector4D CatmullRom(Vector4D value1, Vector4D value2, Vector4D value3, Vector4D value4, double amount)</code></a>_</td><td>Performs a Catmull-Rom interpolation using the specified positions.</td></tr>
<tr><td>static _<a href="VRageMath.CatmullRom"><code>void CatmullRom(ref Vector4D value1, ref Vector4D value2, ref Vector4D value3, ref Vector4D value4, double amount, ref Vector4D result)</code></a>_</td><td>Performs a Catmull-Rom interpolation using the specified positions.</td></tr>
<tr><td>static _<a href="VRageMath.Hermite"><code>Vector4D Hermite(Vector4D value1, Vector4D tangent1, Vector4D value2, Vector4D tangent2, double amount)</code></a>_</td><td>Performs a Hermite spline interpolation.</td></tr>
<tr><td>static _<a href="VRageMath.Hermite"><code>void Hermite(ref Vector4D value1, ref Vector4D tangent1, ref Vector4D value2, ref Vector4D tangent2, double amount, ref Vector4D result)</code></a>_</td><td>Performs a Hermite spline interpolation.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>Vector4D Transform(Vector2 position, MatrixD matrix)</code></a>_</td><td>Transforms a Vector2 by the given Matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(ref Vector2 position, ref MatrixD matrix, ref Vector4D result)</code></a>_</td><td>Transforms a Vector2 by the given Matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>Vector4D Transform(Vector3D position, MatrixD matrix)</code></a>_</td><td>Transforms a Vector3 by the given Matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(ref Vector3D position, ref MatrixD matrix, ref Vector4D result)</code></a>_</td><td>Transforms a Vector3 by the given Matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>Vector4D Transform(Vector4D vector, MatrixD matrix)</code></a>_</td><td>Transforms a Vector4 by the specified Matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(ref Vector4D vector, ref MatrixD matrix, ref Vector4D result)</code></a>_</td><td>Transforms a Vector4 by the given Matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>Vector4D Transform(Vector2 value, Quaternion rotation)</code></a>_</td><td>Transforms a Vector2 by a specified Quaternion into a Vector4.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(ref Vector2 value, ref Quaternion rotation, ref Vector4D result)</code></a>_</td><td>Transforms a Vector2 by a specified Quaternion into a Vector4.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>Vector4D Transform(Vector3D value, Quaternion rotation)</code></a>_</td><td>Transforms a Vector3 by a specified Quaternion into a Vector4.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(ref Vector3D value, ref Quaternion rotation, ref Vector4D result)</code></a>_</td><td>Transforms a Vector3 by a specified Quaternion into a Vector4.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>Vector4D Transform(Vector4D value, Quaternion rotation)</code></a>_</td><td>Transforms a Vector4 by a specified Quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(ref Vector4D value, ref Quaternion rotation, ref Vector4D result)</code></a>_</td><td>Transforms a Vector4 by a specified Quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(Vector4D[] sourceArray, ref MatrixD matrix, Vector4D[] destinationArray)</code></a>_</td><td>Transforms an array of Vector4s by a specified Matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(Vector4D[] sourceArray, int sourceIndex, ref MatrixD matrix, Vector4D[] destinationArray, int destinationIndex, int length)</code></a>_</td><td>Transforms a specified range in an array of Vector4s by a specified Matrix into a specified range in a destination array.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(Vector4D[] sourceArray, ref Quaternion rotation, Vector4D[] destinationArray)</code></a>_</td><td>Transforms an array of Vector4s by a specified Quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(Vector4D[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector4D[] destinationArray, int destinationIndex, int length)</code></a>_</td><td>Transforms a specified range in an array of Vector4s by a specified Quaternion into a specified range in a destination array.</td></tr>
<tr><td>static _<a href="VRageMath.Negate"><code>Vector4D Negate(Vector4D value)</code></a>_</td><td>Returns a vector pointing in the opposite direction.</td></tr>
<tr><td>static _<a href="VRageMath.Negate"><code>void Negate(ref Vector4D value, ref Vector4D result)</code></a>_</td><td>Returns a vector pointing in the opposite direction.</td></tr>
<tr><td>static _<a href="VRageMath.Add"><code>Vector4D Add(Vector4D value1, Vector4D value2)</code></a>_</td><td>Adds two vectors.</td></tr>
<tr><td>static _<a href="VRageMath.Add"><code>void Add(ref Vector4D value1, ref Vector4D value2, ref Vector4D result)</code></a>_</td><td>Adds two vectors.</td></tr>
<tr><td>static _<a href="VRageMath.Subtract"><code>Vector4 Subtract(Vector4 value1, Vector4 value2)</code></a>_</td><td>Subtracts a vector from a vector.</td></tr>
<tr><td>static _<a href="VRageMath.Subtract"><code>void Subtract(ref Vector4D value1, ref Vector4D value2, ref Vector4D result)</code></a>_</td><td>Subtracts a vector from a vector.</td></tr>
<tr><td>static _<a href="VRageMath.Multiply"><code>Vector4D Multiply(Vector4D value1, Vector4D value2)</code></a>_</td><td>Multiplies the components of two vectors by each other.</td></tr>
<tr><td>static _<a href="VRageMath.Multiply"><code>void Multiply(ref Vector4 value1, ref Vector4 value2, ref Vector4 result)</code></a>_</td><td>Multiplies the components of two vectors by each other.</td></tr>
<tr><td>static _<a href="VRageMath.Multiply"><code>Vector4D Multiply(Vector4D value1, double scaleFactor)</code></a>_</td><td>Multiplies a vector by a scalar.</td></tr>
<tr><td>static _<a href="VRageMath.Multiply"><code>void Multiply(ref Vector4D value1, double scaleFactor, ref Vector4D result)</code></a>_</td><td>Multiplies a vector by a scalar value.</td></tr>
<tr><td>static _<a href="VRageMath.Divide"><code>Vector4D Divide(Vector4D value1, Vector4D value2)</code></a>_</td><td>Divides the components of a vector by the components of another vector.</td></tr>
<tr><td>static _<a href="VRageMath.Divide"><code>void Divide(ref Vector4D value1, ref Vector4D value2, ref Vector4D result)</code></a>_</td><td>Divides the components of a vector by the components of another vector.</td></tr>
<tr><td>static _<a href="VRageMath.Divide"><code>Vector4D Divide(Vector4D value1, double divider)</code></a>_</td><td>Divides a vector by a scalar value.</td></tr>
<tr><td>static _<a href="VRageMath.Divide"><code>void Divide(ref Vector4D value1, double divider, ref Vector4D result)</code></a>_</td><td>Divides a vector by a scalar value.</td></tr>
</table>
