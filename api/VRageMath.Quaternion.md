← [Index](index)
# Quaternion Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a four-dimensional vector (x,y,z,w), which is used to efficiently rotate an object about the (x, y, z) vector by the angle theta, where w = cos(theta/2).
### Fields
<table style="width: 100%">
<tr><td>[`float X`](VRageMath.X)</td><td>Specifies the x-value of the vector component of the quaternion.</td></tr>
<tr><td>[`float Y`](VRageMath.Y)</td><td>Specifies the y-value of the vector component of the quaternion.</td></tr>
<tr><td>[`float Z`](VRageMath.Z)</td><td>Specifies the z-value of the vector component of the quaternion.</td></tr>
<tr><td>[`float W`](VRageMath.W)</td><td>Specifies the rotation component of the quaternion.</td></tr>
<tr><td>static [`Quaternion Identity`](VRageMath.Identity)</td><td></td></tr>
<tr><td>static [`Quaternion Zero`](VRageMath.Zero)</td><td></td></tr>
</table>
### Properties
<table style="width: 100%">
<tr><td>[`Vector3 Forward`](VRageMath.Forward)</td><td></td></tr>
<tr><td>[`Vector3 Right`](VRageMath.Right)</td><td></td></tr>
<tr><td>[`Vector3 Up`](VRageMath.Up)</td><td></td></tr>
</table>
### Methods
<table style="width: 100%">
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td>Retireves a string representation of the current object.</td></tr>
<tr><td>[`string ToString(string format)`](VRageMath.ToString)</td><td></td></tr>
<tr><td>[`string ToStringAxisAngle(string format)`](VRageMath.ToStringAxisAngle)</td><td></td></tr>
<tr><td>[`bool Equals(Quaternion other)`](VRageMath.Equals)</td><td>Determines whether the specified Object is equal to the Quaternion.</td></tr>
<tr><td>[`bool Equals(Quaternion value, float epsilon)`](VRageMath.Equals)</td><td></td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td>Returns a value that indicates whether the current instance is equal to a specified object.</td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td>Get the hash code of this object.</td></tr>
<tr><td>[`float LengthSquared()`](VRageMath.LengthSquared)</td><td>Calculates the length squared of a Quaternion.</td></tr>
<tr><td>[`float Length()`](VRageMath.Length)</td><td>Calculates the length of a Quaternion.</td></tr>
<tr><td>[`void Normalize()`](VRageMath.Normalize)</td><td>Divides each component of the quaternion by the length of the quaternion.</td></tr>
<tr><td>[`void GetAxisAngle(ref Vector3 axis, ref float angle)`](VRageMath.GetAxisAngle)</td><td></td></tr>
<tr><td>static [`Quaternion Normalize(Quaternion quaternion)`](VRageMath.Normalize)</td><td>Divides each component of the quaternion by the length of the quaternion.</td></tr>
<tr><td>static [`void Normalize(ref Quaternion quaternion, ref Quaternion result)`](VRageMath.Normalize)</td><td>Divides each component of the quaternion by the length of the quaternion.</td></tr>
<tr><td>[`void Conjugate()`](VRageMath.Conjugate)</td><td>Transforms this Quaternion into its conjugate.</td></tr>
<tr><td>static [`Quaternion Conjugate(Quaternion value)`](VRageMath.Conjugate)</td><td>Returns the conjugate of a specified Quaternion.</td></tr>
<tr><td>static [`void Conjugate(ref Quaternion value, ref Quaternion result)`](VRageMath.Conjugate)</td><td>Returns the conjugate of a specified Quaternion.</td></tr>
<tr><td>static [`Quaternion Inverse(Quaternion quaternion)`](VRageMath.Inverse)</td><td>Returns the inverse of a Quaternion.</td></tr>
<tr><td>static [`void Inverse(ref Quaternion quaternion, ref Quaternion result)`](VRageMath.Inverse)</td><td>Returns the inverse of a Quaternion.</td></tr>
<tr><td>static [`Quaternion CreateFromAxisAngle(Vector3 axis, float angle)`](VRageMath.CreateFromAxisAngle)</td><td>Creates a Quaternion from a vector and an angle to rotate about the vector.</td></tr>
<tr><td>static [`void CreateFromAxisAngle(ref Vector3 axis, float angle, ref Quaternion result)`](VRageMath.CreateFromAxisAngle)</td><td>Creates a Quaternion from a vector and an angle to rotate about the vector.</td></tr>
<tr><td>static [`Quaternion CreateFromYawPitchRoll(float yaw, float pitch, float roll)`](VRageMath.CreateFromYawPitchRoll)</td><td>Creates a new Quaternion from specified yaw, pitch, and roll angles.</td></tr>
<tr><td>static [`void CreateFromYawPitchRoll(float yaw, float pitch, float roll, ref Quaternion result)`](VRageMath.CreateFromYawPitchRoll)</td><td>Creates a new Quaternion from specified yaw, pitch, and roll angles.</td></tr>
<tr><td>static [`Quaternion CreateFromForwardUp(Vector3 forward, Vector3 up)`](VRageMath.CreateFromForwardUp)</td><td>Works for normalized vectors only</td></tr>
<tr><td>static [`Quaternion CreateFromRotationMatrix(MatrixD matrix)`](VRageMath.CreateFromRotationMatrix)</td><td></td></tr>
<tr><td>static [`Quaternion CreateFromRotationMatrix(Matrix matrix)`](VRageMath.CreateFromRotationMatrix)</td><td>Creates a Quaternion from a rotation Matrix.</td></tr>
<tr><td>static [`void CreateFromRotationMatrix(ref MatrixD matrix, ref Quaternion result)`](VRageMath.CreateFromRotationMatrix)</td><td></td></tr>
<tr><td>static [`void CreateFromTwoVectors(ref Vector3 firstVector, ref Vector3 secondVector, ref Quaternion result)`](VRageMath.CreateFromTwoVectors)</td><td></td></tr>
<tr><td>static [`Quaternion CreateFromTwoVectors(Vector3 firstVector, Vector3 secondVector)`](VRageMath.CreateFromTwoVectors)</td><td></td></tr>
<tr><td>static [`void CreateFromRotationMatrix(ref Matrix matrix, ref Quaternion result)`](VRageMath.CreateFromRotationMatrix)</td><td>Creates a Quaternion from a rotation Matrix.</td></tr>
<tr><td>static [`void CreateFromRotationMatrix(ref Matrix3x3 matrix, ref Quaternion result)`](VRageMath.CreateFromRotationMatrix)</td><td>Creates a Quaternion from a rotation Matrix.</td></tr>
<tr><td>static [`float Dot(Quaternion quaternion1, Quaternion quaternion2)`](VRageMath.Dot)</td><td>Calculates the dot product of two Quaternions.</td></tr>
<tr><td>static [`void Dot(ref Quaternion quaternion1, ref Quaternion quaternion2, ref float result)`](VRageMath.Dot)</td><td>Calculates the dot product of two Quaternions.</td></tr>
<tr><td>static [`Quaternion Slerp(Quaternion quaternion1, Quaternion quaternion2, float amount)`](VRageMath.Slerp)</td><td>Interpolates between two quaternions, using spherical linear interpolation.</td></tr>
<tr><td>static [`void Slerp(ref Quaternion quaternion1, ref Quaternion quaternion2, float amount, ref Quaternion result)`](VRageMath.Slerp)</td><td>Interpolates between two quaternions, using spherical linear interpolation.</td></tr>
<tr><td>static [`Quaternion Lerp(Quaternion quaternion1, Quaternion quaternion2, float amount)`](VRageMath.Lerp)</td><td>Linearly interpolates between two quaternions.</td></tr>
<tr><td>static [`void Lerp(ref Quaternion quaternion1, ref Quaternion quaternion2, float amount, ref Quaternion result)`](VRageMath.Lerp)</td><td>Linearly interpolates between two quaternions.</td></tr>
<tr><td>static [`Quaternion Concatenate(Quaternion value1, Quaternion value2)`](VRageMath.Concatenate)</td><td>Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.</td></tr>
<tr><td>static [`void Concatenate(ref Quaternion value1, ref Quaternion value2, ref Quaternion result)`](VRageMath.Concatenate)</td><td>Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.</td></tr>
<tr><td>static [`Quaternion Negate(Quaternion quaternion)`](VRageMath.Negate)</td><td>Flips the sign of each component of the quaternion.</td></tr>
<tr><td>static [`void Negate(ref Quaternion quaternion, ref Quaternion result)`](VRageMath.Negate)</td><td>Flips the sign of each component of the quaternion.</td></tr>
<tr><td>static [`Quaternion Add(Quaternion quaternion1, Quaternion quaternion2)`](VRageMath.Add)</td><td>Adds two Quaternions.</td></tr>
<tr><td>static [`void Add(ref Quaternion quaternion1, ref Quaternion quaternion2, ref Quaternion result)`](VRageMath.Add)</td><td>Adds two Quaternions.</td></tr>
<tr><td>static [`Quaternion Subtract(Quaternion quaternion1, Quaternion quaternion2)`](VRageMath.Subtract)</td><td>Subtracts a quaternion from another quaternion.</td></tr>
<tr><td>static [`void Subtract(ref Quaternion quaternion1, ref Quaternion quaternion2, ref Quaternion result)`](VRageMath.Subtract)</td><td>Subtracts a quaternion from another quaternion.</td></tr>
<tr><td>static [`Quaternion Multiply(Quaternion quaternion1, Quaternion quaternion2)`](VRageMath.Multiply)</td><td>Multiplies two quaternions.</td></tr>
<tr><td>static [`void Multiply(ref Quaternion quaternion1, ref Quaternion quaternion2, ref Quaternion result)`](VRageMath.Multiply)</td><td>Multiplies two quaternions.</td></tr>
<tr><td>static [`Quaternion Multiply(Quaternion quaternion1, float scaleFactor)`](VRageMath.Multiply)</td><td>Multiplies a quaternion by a scalar value.</td></tr>
<tr><td>static [`void Multiply(ref Quaternion quaternion1, float scaleFactor, ref Quaternion result)`](VRageMath.Multiply)</td><td>Multiplies a quaternion by a scalar value.</td></tr>
<tr><td>static [`Quaternion Divide(Quaternion quaternion1, Quaternion quaternion2)`](VRageMath.Divide)</td><td>Divides a Quaternion by another Quaternion.</td></tr>
<tr><td>static [`void Divide(ref Quaternion quaternion1, ref Quaternion quaternion2, ref Quaternion result)`](VRageMath.Divide)</td><td>Divides a Quaternion by another Quaternion.</td></tr>
<tr><td>static [`Quaternion FromVector4(Vector4 v)`](VRageMath.FromVector4)</td><td></td></tr>
<tr><td>[`Vector4 ToVector4()`](VRageMath.ToVector4)</td><td></td></tr>
<tr><td>static [`bool IsZero(Quaternion value)`](VRageMath.IsZero)</td><td></td></tr>
<tr><td>static [`bool IsZero(Quaternion value, float epsilon)`](VRageMath.IsZero)</td><td></td></tr>
<tr><td>static [`void GetForward(ref Quaternion q, ref Vector3 result)`](VRageMath.GetForward)</td><td>Gets forward vector (0,0,-1) transformed by quaternion.</td></tr>
<tr><td>static [`void GetRight(ref Quaternion q, ref Vector3 result)`](VRageMath.GetRight)</td><td>Gets right vector (1,0,0) transformed by quaternion.</td></tr>
<tr><td>static [`void GetUp(ref Quaternion q, ref Vector3 result)`](VRageMath.GetUp)</td><td>Gets up vector (0,1,0) transformed by quaternion.</td></tr>
<tr><td>[`float GetComponent(int index)`](VRageMath.GetComponent)</td><td></td></tr>
<tr><td>[`void SetComponent(int index, float value)`](VRageMath.SetComponent)</td><td></td></tr>
<tr><td>[`int FindLargestIndex()`](VRageMath.FindLargestIndex)</td><td></td></tr>
</table>
