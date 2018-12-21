← [Index](index)
# QuaternionD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a four-dimensional vector (x,y,z,w), which is used to efficiently rotate an object about the (x, y, z) vector by the angle theta, where w = cos(theta/2). Uses double precision floating point numbers for calculation and storage
### Fields
<table style="width:100%;display:table">
<tr><td>[`double X`](VRageMath.X)</td><td>Specifies the x-value of the vector component of the quaternion.</td></tr>
<tr><td>[`double Y`](VRageMath.Y)</td><td>Specifies the y-value of the vector component of the quaternion.</td></tr>
<tr><td>[`double Z`](VRageMath.Z)</td><td>Specifies the z-value of the vector component of the quaternion.</td></tr>
<tr><td>[`double W`](VRageMath.W)</td><td>Specifies the rotation component of the quaternion.</td></tr>
<tr><td>static [`QuaternionD Identity`](VRageMath.Identity)</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td>Retireves a string representation of the current object.</td></tr>
<tr><td>[`bool Equals(QuaternionD other)`](VRageMath.Equals)</td><td>Determines whether the specified Object is equal to the QuaternionD.</td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td>Returns a value that indicates whether the current instance is equal to a specified object.</td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td>Get the hash code of this object.</td></tr>
<tr><td>[`double LengthSquared()`](VRageMath.LengthSquared)</td><td>Calculates the length squared of a QuaternionD.</td></tr>
<tr><td>[`double Length()`](VRageMath.Length)</td><td>Calculates the length of a QuaternionD.</td></tr>
<tr><td>[`void Normalize()`](VRageMath.Normalize)</td><td>Divides each component of the quaternion by the length of the quaternion.</td></tr>
<tr><td>[`void GetAxisAngle(ref Vector3D axis, ref double angle)`](VRageMath.GetAxisAngle)</td><td></td></tr>
<tr><td>static [`QuaternionD Normalize(QuaternionD quaternion)`](VRageMath.Normalize)</td><td>Divides each component of the quaternion by the length of the quaternion.</td></tr>
<tr><td>static [`void Normalize(ref QuaternionD quaternion, ref QuaternionD result)`](VRageMath.Normalize)</td><td>Divides each component of the quaternion by the length of the quaternion.</td></tr>
<tr><td>[`void Conjugate()`](VRageMath.Conjugate)</td><td>Transforms this QuaternionD into its conjugate.</td></tr>
<tr><td>static [`QuaternionD Conjugate(QuaternionD value)`](VRageMath.Conjugate)</td><td>Returns the conjugate of a specified QuaternionD.</td></tr>
<tr><td>static [`void Conjugate(ref QuaternionD value, ref QuaternionD result)`](VRageMath.Conjugate)</td><td>Returns the conjugate of a specified QuaternionD.</td></tr>
<tr><td>static [`QuaternionD Inverse(QuaternionD quaternion)`](VRageMath.Inverse)</td><td>Returns the inverse of a QuaternionD.</td></tr>
<tr><td>static [`void Inverse(ref QuaternionD quaternion, ref QuaternionD result)`](VRageMath.Inverse)</td><td>Returns the inverse of a QuaternionD.</td></tr>
<tr><td>static [`QuaternionD CreateFromAxisAngle(Vector3D axis, double angle)`](VRageMath.CreateFromAxisAngle)</td><td>Creates a QuaternionD from a vector and an angle to rotate about the vector.</td></tr>
<tr><td>static [`void CreateFromAxisAngle(ref Vector3D axis, double angle, ref QuaternionD result)`](VRageMath.CreateFromAxisAngle)</td><td>Creates a QuaternionD from a vector and an angle to rotate about the vector.</td></tr>
<tr><td>static [`QuaternionD CreateFromYawPitchRoll(double yaw, double pitch, double roll)`](VRageMath.CreateFromYawPitchRoll)</td><td>Creates a new QuaternionD from specified yaw, pitch, and roll angles.</td></tr>
<tr><td>static [`void CreateFromYawPitchRoll(double yaw, double pitch, double roll, ref QuaternionD result)`](VRageMath.CreateFromYawPitchRoll)</td><td>Creates a new QuaternionD from specified yaw, pitch, and roll angles.</td></tr>
<tr><td>static [`QuaternionD CreateFromForwardUp(Vector3D forward, Vector3D up)`](VRageMath.CreateFromForwardUp)</td><td>Works for normalized vectors only</td></tr>
<tr><td>static [`QuaternionD CreateFromRotationMatrix(MatrixD matrix)`](VRageMath.CreateFromRotationMatrix)</td><td>Creates a QuaternionD from a rotation MatrixD.</td></tr>
<tr><td>static [`void CreateFromRotationMatrix(ref MatrixD matrix, ref QuaternionD result)`](VRageMath.CreateFromRotationMatrix)</td><td>Creates a QuaternionD from a rotation MatrixD.</td></tr>
<tr><td>static [`double Dot(QuaternionD quaternion1, QuaternionD quaternion2)`](VRageMath.Dot)</td><td>Calculates the dot product of two Quaternions.</td></tr>
<tr><td>static [`void Dot(ref QuaternionD quaternion1, ref QuaternionD quaternion2, ref double result)`](VRageMath.Dot)</td><td>Calculates the dot product of two Quaternions.</td></tr>
<tr><td>static [`QuaternionD Slerp(QuaternionD quaternion1, QuaternionD quaternion2, double amount)`](VRageMath.Slerp)</td><td>Interpolates between two quaternions, using spherical linear interpolation.</td></tr>
<tr><td>static [`void Slerp(ref QuaternionD quaternion1, ref QuaternionD quaternion2, double amount, ref QuaternionD result)`](VRageMath.Slerp)</td><td>Interpolates between two quaternions, using spherical linear interpolation.</td></tr>
<tr><td>static [`QuaternionD Lerp(QuaternionD quaternion1, QuaternionD quaternion2, double amount)`](VRageMath.Lerp)</td><td>Linearly interpolates between two quaternions.</td></tr>
<tr><td>static [`void Lerp(ref QuaternionD quaternion1, ref QuaternionD quaternion2, double amount, ref QuaternionD result)`](VRageMath.Lerp)</td><td>Linearly interpolates between two quaternions.</td></tr>
<tr><td>static [`QuaternionD Concatenate(QuaternionD value1, QuaternionD value2)`](VRageMath.Concatenate)</td><td>Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.</td></tr>
<tr><td>static [`void Concatenate(ref QuaternionD value1, ref QuaternionD value2, ref QuaternionD result)`](VRageMath.Concatenate)</td><td>Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.</td></tr>
<tr><td>static [`QuaternionD Negate(QuaternionD quaternion)`](VRageMath.Negate)</td><td>Flips the sign of each component of the quaternion.</td></tr>
<tr><td>static [`void Negate(ref QuaternionD quaternion, ref QuaternionD result)`](VRageMath.Negate)</td><td>Flips the sign of each component of the quaternion.</td></tr>
<tr><td>static [`QuaternionD Add(QuaternionD quaternion1, QuaternionD quaternion2)`](VRageMath.Add)</td><td>Adds two Quaternions.</td></tr>
<tr><td>static [`void Add(ref QuaternionD quaternion1, ref QuaternionD quaternion2, ref QuaternionD result)`](VRageMath.Add)</td><td>Adds two Quaternions.</td></tr>
<tr><td>static [`QuaternionD Subtract(QuaternionD quaternion1, QuaternionD quaternion2)`](VRageMath.Subtract)</td><td>Subtracts a quaternion from another quaternion.</td></tr>
<tr><td>static [`void Subtract(ref QuaternionD quaternion1, ref QuaternionD quaternion2, ref QuaternionD result)`](VRageMath.Subtract)</td><td>Subtracts a quaternion from another quaternion.</td></tr>
<tr><td>static [`QuaternionD Multiply(QuaternionD quaternion1, QuaternionD quaternion2)`](VRageMath.Multiply)</td><td>Multiplies two quaternions.</td></tr>
<tr><td>static [`void Multiply(ref QuaternionD quaternion1, ref QuaternionD quaternion2, ref QuaternionD result)`](VRageMath.Multiply)</td><td>Multiplies two quaternions.</td></tr>
<tr><td>static [`QuaternionD Multiply(QuaternionD quaternion1, double scaleFactor)`](VRageMath.Multiply)</td><td>Multiplies a quaternion by a scalar value.</td></tr>
<tr><td>static [`void Multiply(ref QuaternionD quaternion1, double scaleFactor, ref QuaternionD result)`](VRageMath.Multiply)</td><td>Multiplies a quaternion by a scalar value.</td></tr>
<tr><td>static [`QuaternionD Divide(QuaternionD quaternion1, QuaternionD quaternion2)`](VRageMath.Divide)</td><td>Divides a QuaternionD by another QuaternionD.</td></tr>
<tr><td>static [`void Divide(ref QuaternionD quaternion1, ref QuaternionD quaternion2, ref QuaternionD result)`](VRageMath.Divide)</td><td>Divides a QuaternionD by another QuaternionD.</td></tr>
<tr><td>static [`QuaternionD FromVector4(Vector4D v)`](VRageMath.FromVector4)</td><td></td></tr>
<tr><td>[`Vector4D ToVector4()`](VRageMath.ToVector4)</td><td></td></tr>
<tr><td>static [`bool IsZero(QuaternionD value)`](VRageMath.IsZero)</td><td></td></tr>
<tr><td>static [`bool IsZero(QuaternionD value, double epsilon)`](VRageMath.IsZero)</td><td></td></tr>
<tr><td>static [`void CreateFromTwoVectors(ref Vector3D firstVector, ref Vector3D secondVector, ref QuaternionD result)`](VRageMath.CreateFromTwoVectors)</td><td></td></tr>
<tr><td>static [`QuaternionD CreateFromTwoVectors(Vector3D firstVector, Vector3D secondVector)`](VRageMath.CreateFromTwoVectors)</td><td></td></tr>
</table>
