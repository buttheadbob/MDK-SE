← [Index](index)
# Vector2 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with two components.
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.X"><code>float X</code></a>_</td><td>Gets or sets the x-component of the vector.</td></tr>
<tr><td>_<a href="VRageMath.Y"><code>float Y</code></a>_</td><td>Gets or sets the y-component of the vector.</td></tr>
<tr><td>static _<a href="VRageMath.Zero"><code>Vector2 Zero</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.One"><code>Vector2 One</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.UnitX"><code>Vector2 UnitX</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.UnitY"><code>Vector2 UnitY</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.PositiveInfinity"><code>Vector2 PositiveInfinity</code></a>_</td><td></td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Item"><code>float Item</code></a>_</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.ToString"><code>string ToString()</code></a>_</td><td>Retrieves a string representation of the current object.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Vector2 other)</code></a>_</td><td>Determines whether the specified Object is equal to the Vector2.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Object obj)</code></a>_</td><td>Returns a value that indicates whether the current instance is equal to a specified object.</td></tr>
<tr><td>_<a href="VRageMath.GetHashCode"><code>int GetHashCode()</code></a>_</td><td>Gets the hash code of the vector object.</td></tr>
<tr><td>_<a href="VRageMath.IsValid"><code>bool IsValid()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.AssertIsValid"><code>void AssertIsValid()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Length"><code>float Length()</code></a>_</td><td>Calculates the length of the vector.</td></tr>
<tr><td>_<a href="VRageMath.LengthSquared"><code>float LengthSquared()</code></a>_</td><td>Calculates the length of the vector squared.</td></tr>
<tr><td>static _<a href="VRageMath.Distance"><code>float Distance(Vector2 value1, Vector2 value2)</code></a>_</td><td>Calculates the distance between two vectors.</td></tr>
<tr><td>static _<a href="VRageMath.Distance"><code>void Distance(ref Vector2 value1, ref Vector2 value2, ref float result)</code></a>_</td><td>Calculates the distance between two vectors.</td></tr>
<tr><td>static _<a href="VRageMath.DistanceSquared"><code>float DistanceSquared(Vector2 value1, Vector2 value2)</code></a>_</td><td>Calculates the distance between two vectors squared.</td></tr>
<tr><td>static _<a href="VRageMath.DistanceSquared"><code>void DistanceSquared(ref Vector2 value1, ref Vector2 value2, ref float result)</code></a>_</td><td>Calculates the distance between two vectors squared.</td></tr>
<tr><td>static _<a href="VRageMath.Dot"><code>float Dot(Vector2 value1, Vector2 value2)</code></a>_</td><td>Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.</td></tr>
<tr><td>static _<a href="VRageMath.Dot"><code>void Dot(ref Vector2 value1, ref Vector2 value2, ref float result)</code></a>_</td><td>Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.</td></tr>
<tr><td>_<a href="VRageMath.Normalize"><code>void Normalize()</code></a>_</td><td>Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.</td></tr>
<tr><td>static _<a href="VRageMath.Normalize"><code>Vector2 Normalize(Vector2 value)</code></a>_</td><td>Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.</td></tr>
<tr><td>static _<a href="VRageMath.Normalize"><code>void Normalize(ref Vector2 value, ref Vector2 result)</code></a>_</td><td>Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.</td></tr>
<tr><td>static _<a href="VRageMath.Reflect"><code>Vector2 Reflect(Vector2 vector, Vector2 normal)</code></a>_</td><td>Determines the reflect vector of the given vector and normal.</td></tr>
<tr><td>static _<a href="VRageMath.Reflect"><code>void Reflect(ref Vector2 vector, ref Vector2 normal, ref Vector2 result)</code></a>_</td><td>Determines the reflect vector of the given vector and normal.</td></tr>
<tr><td>static _<a href="VRageMath.Min"><code>Vector2 Min(Vector2 value1, Vector2 value2)</code></a>_</td><td>Returns a vector that contains the lowest value from each matching pair of components.</td></tr>
<tr><td>static _<a href="VRageMath.Min"><code>void Min(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)</code></a>_</td><td>Returns a vector that contains the lowest value from each matching pair of components.</td></tr>
<tr><td>static _<a href="VRageMath.Max"><code>Vector2 Max(Vector2 value1, Vector2 value2)</code></a>_</td><td>Returns a vector that contains the highest value from each matching pair of components.</td></tr>
<tr><td>static _<a href="VRageMath.Max"><code>void Max(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)</code></a>_</td><td>Returns a vector that contains the highest value from each matching pair of components.</td></tr>
<tr><td>static _<a href="VRageMath.Clamp"><code>Vector2 Clamp(Vector2 value1, Vector2 min, Vector2 max)</code></a>_</td><td>Restricts a value to be within a specified range.</td></tr>
<tr><td>static _<a href="VRageMath.Clamp"><code>void Clamp(ref Vector2 value1, ref Vector2 min, ref Vector2 max, ref Vector2 result)</code></a>_</td><td>Restricts a value to be within a specified range.</td></tr>
<tr><td>static _<a href="VRageMath.ClampToSphere"><code>Vector2 ClampToSphere(Vector2 vector, float radius)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.ClampToSphere"><code>void ClampToSphere(ref Vector2 vector, float radius)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Lerp"><code>Vector2 Lerp(Vector2 value1, Vector2 value2, float amount)</code></a>_</td><td>Performs a linear interpolation between two vectors.</td></tr>
<tr><td>static _<a href="VRageMath.Lerp"><code>void Lerp(ref Vector2 value1, ref Vector2 value2, float amount, ref Vector2 result)</code></a>_</td><td>Performs a linear interpolation between two vectors.</td></tr>
<tr><td>static _<a href="VRageMath.Barycentric"><code>Vector2 Barycentric(Vector2 value1, Vector2 value2, Vector2 value3, float amount1, float amount2)</code></a>_</td><td>Returns a Vector2 containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.</td></tr>
<tr><td>static _<a href="VRageMath.Barycentric"><code>void Barycentric(ref Vector2 value1, ref Vector2 value2, ref Vector2 value3, float amount1, float amount2, ref Vector2 result)</code></a>_</td><td>Returns a Vector2 containing the 2D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 2D triangle.</td></tr>
<tr><td>static _<a href="VRageMath.SmoothStep"><code>Vector2 SmoothStep(Vector2 value1, Vector2 value2, float amount)</code></a>_</td><td>Interpolates between two values using a cubic equation.</td></tr>
<tr><td>static _<a href="VRageMath.SmoothStep"><code>void SmoothStep(ref Vector2 value1, ref Vector2 value2, float amount, ref Vector2 result)</code></a>_</td><td>Interpolates between two values using a cubic equation.</td></tr>
<tr><td>static _<a href="VRageMath.CatmullRom"><code>Vector2 CatmullRom(Vector2 value1, Vector2 value2, Vector2 value3, Vector2 value4, float amount)</code></a>_</td><td>Performs a Catmull-Rom interpolation using the specified positions.</td></tr>
<tr><td>static _<a href="VRageMath.CatmullRom"><code>void CatmullRom(ref Vector2 value1, ref Vector2 value2, ref Vector2 value3, ref Vector2 value4, float amount, ref Vector2 result)</code></a>_</td><td>Performs a Catmull-Rom interpolation using the specified positions.</td></tr>
<tr><td>static _<a href="VRageMath.Hermite"><code>Vector2 Hermite(Vector2 value1, Vector2 tangent1, Vector2 value2, Vector2 tangent2, float amount)</code></a>_</td><td>Performs a Hermite spline interpolation.</td></tr>
<tr><td>static _<a href="VRageMath.Hermite"><code>void Hermite(ref Vector2 value1, ref Vector2 tangent1, ref Vector2 value2, ref Vector2 tangent2, float amount, ref Vector2 result)</code></a>_</td><td>Performs a Hermite spline interpolation.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>Vector2 Transform(Vector2 position, Matrix matrix)</code></a>_</td><td>Transforms the vector (x, y, 0, 1) by the specified matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(ref Vector2 position, ref Matrix matrix, ref Vector2 result)</code></a>_</td><td>Transforms a Vector2 by the given Matrix.</td></tr>
<tr><td>static _<a href="VRageMath.TransformNormal"><code>Vector2 TransformNormal(Vector2 normal, Matrix matrix)</code></a>_</td><td>Transforms a 2D vector normal by a matrix.</td></tr>
<tr><td>static _<a href="VRageMath.TransformNormal"><code>void TransformNormal(ref Vector2 normal, ref Matrix matrix, ref Vector2 result)</code></a>_</td><td>Transforms a vector normal by a matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>Vector2 Transform(Vector2 value, Quaternion rotation)</code></a>_</td><td>Transforms a single Vector2, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(ref Vector2 value, ref Quaternion rotation, ref Vector2 result)</code></a>_</td><td>Transforms a Vector2, or the vector normal (x, y, 0, 0), by a specified Quaternion rotation.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(Vector2[] sourceArray, ref Matrix matrix, Vector2[] destinationArray)</code></a>_</td><td>Transforms an array of Vector2s by a specified Matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(Vector2[] sourceArray, int sourceIndex, ref Matrix matrix, Vector2[] destinationArray, int destinationIndex, int length)</code></a>_</td><td>Transforms a specified range in an array of Vector2s by a specified Matrix and places the results in a specified range in a destination array.</td></tr>
<tr><td>static _<a href="VRageMath.TransformNormal"><code>void TransformNormal(Vector2[] sourceArray, ref Matrix matrix, Vector2[] destinationArray)</code></a>_</td><td>Transforms an array of Vector2 vector normals by a specified Matrix.</td></tr>
<tr><td>static _<a href="VRageMath.TransformNormal"><code>void TransformNormal(Vector2[] sourceArray, int sourceIndex, ref Matrix matrix, Vector2[] destinationArray, int destinationIndex, int length)</code></a>_</td><td>Transforms a specified range in an array of Vector2 vector normals by a specified Matrix and places the results in a specified range in a destination array.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(Vector2[] sourceArray, ref Quaternion rotation, Vector2[] destinationArray)</code></a>_</td><td>Transforms an array of Vector2s by a specified Quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(Vector2[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector2[] destinationArray, int destinationIndex, int length)</code></a>_</td><td>Transforms a specified range in an array of Vector2s by a specified Quaternion and places the results in a specified range in a destination array.</td></tr>
<tr><td>static _<a href="VRageMath.Negate"><code>Vector2 Negate(Vector2 value)</code></a>_</td><td>Returns a vector pointing in the opposite direction.</td></tr>
<tr><td>static _<a href="VRageMath.Negate"><code>void Negate(ref Vector2 value, ref Vector2 result)</code></a>_</td><td>Returns a vector pointing in the opposite direction.</td></tr>
<tr><td>static _<a href="VRageMath.Add"><code>Vector2 Add(Vector2 value1, Vector2 value2)</code></a>_</td><td>Adds two vectors.</td></tr>
<tr><td>static _<a href="VRageMath.Add"><code>void Add(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)</code></a>_</td><td>Adds two vectors.</td></tr>
<tr><td>static _<a href="VRageMath.Subtract"><code>Vector2 Subtract(Vector2 value1, Vector2 value2)</code></a>_</td><td>Subtracts a vector from a vector.</td></tr>
<tr><td>static _<a href="VRageMath.Subtract"><code>void Subtract(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)</code></a>_</td><td>Subtracts a vector from a vector.</td></tr>
<tr><td>static _<a href="VRageMath.Multiply"><code>Vector2 Multiply(Vector2 value1, Vector2 value2)</code></a>_</td><td>Multiplies the components of two vectors by each other.</td></tr>
<tr><td>static _<a href="VRageMath.Multiply"><code>void Multiply(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)</code></a>_</td><td>Multiplies the components of two vectors by each other.</td></tr>
<tr><td>static _<a href="VRageMath.Multiply"><code>Vector2 Multiply(Vector2 value1, float scaleFactor)</code></a>_</td><td>Multiplies a vector by a scalar value.</td></tr>
<tr><td>static _<a href="VRageMath.Multiply"><code>void Multiply(ref Vector2 value1, float scaleFactor, ref Vector2 result)</code></a>_</td><td>Multiplies a vector by a scalar value.</td></tr>
<tr><td>static _<a href="VRageMath.Divide"><code>Vector2 Divide(Vector2 value1, Vector2 value2)</code></a>_</td><td>Divides the components of a vector by the components of another vector.</td></tr>
<tr><td>static _<a href="VRageMath.Divide"><code>void Divide(ref Vector2 value1, ref Vector2 value2, ref Vector2 result)</code></a>_</td><td>Divides the components of a vector by the components of another vector.</td></tr>
<tr><td>static _<a href="VRageMath.Divide"><code>Vector2 Divide(Vector2 value1, float divider)</code></a>_</td><td>Divides a vector by a scalar value.</td></tr>
<tr><td>static _<a href="VRageMath.Divide"><code>void Divide(ref Vector2 value1, float divider, ref Vector2 result)</code></a>_</td><td>Divides a vector by a scalar value.</td></tr>
<tr><td>_<a href="VRageMath.Between"><code>bool Between(ref Vector2 start, ref Vector2 end)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Floor"><code>Vector2 Floor(Vector2 position)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Rotate"><code>void Rotate(double angle)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsZero"><code>bool IsZero(ref Vector2 value)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsZero"><code>bool IsZero(ref Vector2 value, float epsilon)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsZero"><code>bool IsZero(Vector2 value, float epsilon)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.SignNonZero"><code>Vector2 SignNonZero(Vector2 value)</code></a>_</td><td></td></tr>
</table>
