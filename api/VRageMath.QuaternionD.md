← [Index](index)
# QuaternionD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a four-dimensional vector (x,y,z,w), which is used to efficiently rotate an object about the (x, y, z) vector by the angle theta, where w = cos(theta/2). Uses double precision floating point numbers for calculation and storage
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.X"><code>double X</code></a>_</td><td>Specifies the x-value of the vector component of the quaternion.</td></tr>
<tr><td>_<a href="VRageMath.Y"><code>double Y</code></a>_</td><td>Specifies the y-value of the vector component of the quaternion.</td></tr>
<tr><td>_<a href="VRageMath.Z"><code>double Z</code></a>_</td><td>Specifies the z-value of the vector component of the quaternion.</td></tr>
<tr><td>_<a href="VRageMath.W"><code>double W</code></a>_</td><td>Specifies the rotation component of the quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.Identity"><code>QuaternionD Identity</code></a>_</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.ToString"><code>string ToString()</code></a>_</td><td>Retireves a string representation of the current object.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(QuaternionD other)</code></a>_</td><td>Determines whether the specified Object is equal to the QuaternionD.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Object obj)</code></a>_</td><td>Returns a value that indicates whether the current instance is equal to a specified object.</td></tr>
<tr><td>_<a href="VRageMath.GetHashCode"><code>int GetHashCode()</code></a>_</td><td>Get the hash code of this object.</td></tr>
<tr><td>_<a href="VRageMath.LengthSquared"><code>double LengthSquared()</code></a>_</td><td>Calculates the length squared of a QuaternionD.</td></tr>
<tr><td>_<a href="VRageMath.Length"><code>double Length()</code></a>_</td><td>Calculates the length of a QuaternionD.</td></tr>
<tr><td>_<a href="VRageMath.Normalize"><code>void Normalize()</code></a>_</td><td>Divides each component of the quaternion by the length of the quaternion.</td></tr>
<tr><td>_<a href="VRageMath.GetAxisAngle"><code>void GetAxisAngle(ref Vector3D axis, ref double angle)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Normalize"><code>QuaternionD Normalize(QuaternionD quaternion)</code></a>_</td><td>Divides each component of the quaternion by the length of the quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.Normalize"><code>void Normalize(ref QuaternionD quaternion, ref QuaternionD result)</code></a>_</td><td>Divides each component of the quaternion by the length of the quaternion.</td></tr>
<tr><td>_<a href="VRageMath.Conjugate"><code>void Conjugate()</code></a>_</td><td>Transforms this QuaternionD into its conjugate.</td></tr>
<tr><td>static _<a href="VRageMath.Conjugate"><code>QuaternionD Conjugate(QuaternionD value)</code></a>_</td><td>Returns the conjugate of a specified QuaternionD.</td></tr>
<tr><td>static _<a href="VRageMath.Conjugate"><code>void Conjugate(ref QuaternionD value, ref QuaternionD result)</code></a>_</td><td>Returns the conjugate of a specified QuaternionD.</td></tr>
<tr><td>static _<a href="VRageMath.Inverse"><code>QuaternionD Inverse(QuaternionD quaternion)</code></a>_</td><td>Returns the inverse of a QuaternionD.</td></tr>
<tr><td>static _<a href="VRageMath.Inverse"><code>void Inverse(ref QuaternionD quaternion, ref QuaternionD result)</code></a>_</td><td>Returns the inverse of a QuaternionD.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromAxisAngle"><code>QuaternionD CreateFromAxisAngle(Vector3D axis, double angle)</code></a>_</td><td>Creates a QuaternionD from a vector and an angle to rotate about the vector.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromAxisAngle"><code>void CreateFromAxisAngle(ref Vector3D axis, double angle, ref QuaternionD result)</code></a>_</td><td>Creates a QuaternionD from a vector and an angle to rotate about the vector.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromYawPitchRoll"><code>QuaternionD CreateFromYawPitchRoll(double yaw, double pitch, double roll)</code></a>_</td><td>Creates a new QuaternionD from specified yaw, pitch, and roll angles.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromYawPitchRoll"><code>void CreateFromYawPitchRoll(double yaw, double pitch, double roll, ref QuaternionD result)</code></a>_</td><td>Creates a new QuaternionD from specified yaw, pitch, and roll angles.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromForwardUp"><code>QuaternionD CreateFromForwardUp(Vector3D forward, Vector3D up)</code></a>_</td><td>Works for normalized vectors only</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromRotationMatrix"><code>QuaternionD CreateFromRotationMatrix(MatrixD matrix)</code></a>_</td><td>Creates a QuaternionD from a rotation MatrixD.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromRotationMatrix"><code>void CreateFromRotationMatrix(ref MatrixD matrix, ref QuaternionD result)</code></a>_</td><td>Creates a QuaternionD from a rotation MatrixD.</td></tr>
<tr><td>static _<a href="VRageMath.Dot"><code>double Dot(QuaternionD quaternion1, QuaternionD quaternion2)</code></a>_</td><td>Calculates the dot product of two Quaternions.</td></tr>
<tr><td>static _<a href="VRageMath.Dot"><code>void Dot(ref QuaternionD quaternion1, ref QuaternionD quaternion2, ref double result)</code></a>_</td><td>Calculates the dot product of two Quaternions.</td></tr>
<tr><td>static _<a href="VRageMath.Slerp"><code>QuaternionD Slerp(QuaternionD quaternion1, QuaternionD quaternion2, double amount)</code></a>_</td><td>Interpolates between two quaternions, using spherical linear interpolation.</td></tr>
<tr><td>static _<a href="VRageMath.Slerp"><code>void Slerp(ref QuaternionD quaternion1, ref QuaternionD quaternion2, double amount, ref QuaternionD result)</code></a>_</td><td>Interpolates between two quaternions, using spherical linear interpolation.</td></tr>
<tr><td>static _<a href="VRageMath.Lerp"><code>QuaternionD Lerp(QuaternionD quaternion1, QuaternionD quaternion2, double amount)</code></a>_</td><td>Linearly interpolates between two quaternions.</td></tr>
<tr><td>static _<a href="VRageMath.Lerp"><code>void Lerp(ref QuaternionD quaternion1, ref QuaternionD quaternion2, double amount, ref QuaternionD result)</code></a>_</td><td>Linearly interpolates between two quaternions.</td></tr>
<tr><td>static _<a href="VRageMath.Concatenate"><code>QuaternionD Concatenate(QuaternionD value1, QuaternionD value2)</code></a>_</td><td>Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.</td></tr>
<tr><td>static _<a href="VRageMath.Concatenate"><code>void Concatenate(ref QuaternionD value1, ref QuaternionD value2, ref QuaternionD result)</code></a>_</td><td>Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.</td></tr>
<tr><td>static _<a href="VRageMath.Negate"><code>QuaternionD Negate(QuaternionD quaternion)</code></a>_</td><td>Flips the sign of each component of the quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.Negate"><code>void Negate(ref QuaternionD quaternion, ref QuaternionD result)</code></a>_</td><td>Flips the sign of each component of the quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.Add"><code>QuaternionD Add(QuaternionD quaternion1, QuaternionD quaternion2)</code></a>_</td><td>Adds two Quaternions.</td></tr>
<tr><td>static _<a href="VRageMath.Add"><code>void Add(ref QuaternionD quaternion1, ref QuaternionD quaternion2, ref QuaternionD result)</code></a>_</td><td>Adds two Quaternions.</td></tr>
<tr><td>static _<a href="VRageMath.Subtract"><code>QuaternionD Subtract(QuaternionD quaternion1, QuaternionD quaternion2)</code></a>_</td><td>Subtracts a quaternion from another quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.Subtract"><code>void Subtract(ref QuaternionD quaternion1, ref QuaternionD quaternion2, ref QuaternionD result)</code></a>_</td><td>Subtracts a quaternion from another quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.Multiply"><code>QuaternionD Multiply(QuaternionD quaternion1, QuaternionD quaternion2)</code></a>_</td><td>Multiplies two quaternions.</td></tr>
<tr><td>static _<a href="VRageMath.Multiply"><code>void Multiply(ref QuaternionD quaternion1, ref QuaternionD quaternion2, ref QuaternionD result)</code></a>_</td><td>Multiplies two quaternions.</td></tr>
<tr><td>static _<a href="VRageMath.Multiply"><code>QuaternionD Multiply(QuaternionD quaternion1, double scaleFactor)</code></a>_</td><td>Multiplies a quaternion by a scalar value.</td></tr>
<tr><td>static _<a href="VRageMath.Multiply"><code>void Multiply(ref QuaternionD quaternion1, double scaleFactor, ref QuaternionD result)</code></a>_</td><td>Multiplies a quaternion by a scalar value.</td></tr>
<tr><td>static _<a href="VRageMath.Divide"><code>QuaternionD Divide(QuaternionD quaternion1, QuaternionD quaternion2)</code></a>_</td><td>Divides a QuaternionD by another QuaternionD.</td></tr>
<tr><td>static _<a href="VRageMath.Divide"><code>void Divide(ref QuaternionD quaternion1, ref QuaternionD quaternion2, ref QuaternionD result)</code></a>_</td><td>Divides a QuaternionD by another QuaternionD.</td></tr>
<tr><td>static _<a href="VRageMath.FromVector4"><code>QuaternionD FromVector4(Vector4D v)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.ToVector4"><code>Vector4D ToVector4()</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsZero"><code>bool IsZero(QuaternionD value)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsZero"><code>bool IsZero(QuaternionD value, double epsilon)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CreateFromTwoVectors"><code>void CreateFromTwoVectors(ref Vector3D firstVector, ref Vector3D secondVector, ref QuaternionD result)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CreateFromTwoVectors"><code>QuaternionD CreateFromTwoVectors(Vector3D firstVector, Vector3D secondVector)</code></a>_</td><td></td></tr>
</table>
