← [Index](index)
# Quaternion Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a four-dimensional vector (x,y,z,w), which is used to efficiently rotate an object about the (x, y, z) vector by the angle theta, where w = cos(theta/2).
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.X"><code>float X</code></a>_</td><td>Specifies the x-value of the vector component of the quaternion.</td></tr>
<tr><td>_<a href="VRageMath.Y"><code>float Y</code></a>_</td><td>Specifies the y-value of the vector component of the quaternion.</td></tr>
<tr><td>_<a href="VRageMath.Z"><code>float Z</code></a>_</td><td>Specifies the z-value of the vector component of the quaternion.</td></tr>
<tr><td>_<a href="VRageMath.W"><code>float W</code></a>_</td><td>Specifies the rotation component of the quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.Identity"><code>Quaternion Identity</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Zero"><code>Quaternion Zero</code></a>_</td><td></td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Forward"><code>Vector3 Forward</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Right"><code>Vector3 Right</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Up"><code>Vector3 Up</code></a>_</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.ToString"><code>string ToString()</code></a>_</td><td>Retireves a string representation of the current object.</td></tr>
<tr><td>_<a href="VRageMath.ToString"><code>string ToString(string format)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.ToStringAxisAngle"><code>string ToStringAxisAngle(string format)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Quaternion other)</code></a>_</td><td>Determines whether the specified Object is equal to the Quaternion.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Quaternion value, float epsilon)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Object obj)</code></a>_</td><td>Returns a value that indicates whether the current instance is equal to a specified object.</td></tr>
<tr><td>_<a href="VRageMath.GetHashCode"><code>int GetHashCode()</code></a>_</td><td>Get the hash code of this object.</td></tr>
<tr><td>_<a href="VRageMath.LengthSquared"><code>float LengthSquared()</code></a>_</td><td>Calculates the length squared of a Quaternion.</td></tr>
<tr><td>_<a href="VRageMath.Length"><code>float Length()</code></a>_</td><td>Calculates the length of a Quaternion.</td></tr>
<tr><td>_<a href="VRageMath.Normalize"><code>void Normalize()</code></a>_</td><td>Divides each component of the quaternion by the length of the quaternion.</td></tr>
<tr><td>_<a href="VRageMath.GetAxisAngle"><code>void GetAxisAngle(ref Vector3 axis, ref float angle)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Normalize"><code>Quaternion Normalize(Quaternion quaternion)</code></a>_</td><td>Divides each component of the quaternion by the length of the quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.Normalize"><code>void Normalize(ref Quaternion quaternion, ref Quaternion result)</code></a>_</td><td>Divides each component of the quaternion by the length of the quaternion.</td></tr>
<tr><td>_<a href="VRageMath.Conjugate"><code>void Conjugate()</code></a>_</td><td>Transforms this Quaternion into its conjugate.</td></tr>
<tr><td>static _<a href="VRageMath.Conjugate"><code>Quaternion Conjugate(Quaternion value)</code></a>_</td><td>Returns the conjugate of a specified Quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.Conjugate"><code>void Conjugate(ref Quaternion value, ref Quaternion result)</code></a>_</td><td>Returns the conjugate of a specified Quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.Inverse"><code>Quaternion Inverse(Quaternion quaternion)</code></a>_</td><td>Returns the inverse of a Quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.Inverse"><code>void Inverse(ref Quaternion quaternion, ref Quaternion result)</code></a>_</td><td>Returns the inverse of a Quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromAxisAngle"><code>Quaternion CreateFromAxisAngle(Vector3 axis, float angle)</code></a>_</td><td>Creates a Quaternion from a vector and an angle to rotate about the vector.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromAxisAngle"><code>void CreateFromAxisAngle(ref Vector3 axis, float angle, ref Quaternion result)</code></a>_</td><td>Creates a Quaternion from a vector and an angle to rotate about the vector.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromYawPitchRoll"><code>Quaternion CreateFromYawPitchRoll(float yaw, float pitch, float roll)</code></a>_</td><td>Creates a new Quaternion from specified yaw, pitch, and roll angles.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromYawPitchRoll"><code>void CreateFromYawPitchRoll(float yaw, float pitch, float roll, ref Quaternion result)</code></a>_</td><td>Creates a new Quaternion from specified yaw, pitch, and roll angles.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromForwardUp"><code>Quaternion CreateFromForwardUp(Vector3 forward, Vector3 up)</code></a>_</td><td>Works for normalized vectors only</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromRotationMatrix"><code>Quaternion CreateFromRotationMatrix(MatrixD matrix)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CreateFromRotationMatrix"><code>Quaternion CreateFromRotationMatrix(Matrix matrix)</code></a>_</td><td>Creates a Quaternion from a rotation Matrix.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromRotationMatrix"><code>void CreateFromRotationMatrix(ref MatrixD matrix, ref Quaternion result)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CreateFromTwoVectors"><code>void CreateFromTwoVectors(ref Vector3 firstVector, ref Vector3 secondVector, ref Quaternion result)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CreateFromTwoVectors"><code>Quaternion CreateFromTwoVectors(Vector3 firstVector, Vector3 secondVector)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CreateFromRotationMatrix"><code>void CreateFromRotationMatrix(ref Matrix matrix, ref Quaternion result)</code></a>_</td><td>Creates a Quaternion from a rotation Matrix.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromRotationMatrix"><code>void CreateFromRotationMatrix(ref Matrix3x3 matrix, ref Quaternion result)</code></a>_</td><td>Creates a Quaternion from a rotation Matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Dot"><code>float Dot(Quaternion quaternion1, Quaternion quaternion2)</code></a>_</td><td>Calculates the dot product of two Quaternions.</td></tr>
<tr><td>static _<a href="VRageMath.Dot"><code>void Dot(ref Quaternion quaternion1, ref Quaternion quaternion2, ref float result)</code></a>_</td><td>Calculates the dot product of two Quaternions.</td></tr>
<tr><td>static _<a href="VRageMath.Slerp"><code>Quaternion Slerp(Quaternion quaternion1, Quaternion quaternion2, float amount)</code></a>_</td><td>Interpolates between two quaternions, using spherical linear interpolation.</td></tr>
<tr><td>static _<a href="VRageMath.Slerp"><code>void Slerp(ref Quaternion quaternion1, ref Quaternion quaternion2, float amount, ref Quaternion result)</code></a>_</td><td>Interpolates between two quaternions, using spherical linear interpolation.</td></tr>
<tr><td>static _<a href="VRageMath.Lerp"><code>Quaternion Lerp(Quaternion quaternion1, Quaternion quaternion2, float amount)</code></a>_</td><td>Linearly interpolates between two quaternions.</td></tr>
<tr><td>static _<a href="VRageMath.Lerp"><code>void Lerp(ref Quaternion quaternion1, ref Quaternion quaternion2, float amount, ref Quaternion result)</code></a>_</td><td>Linearly interpolates between two quaternions.</td></tr>
<tr><td>static _<a href="VRageMath.Concatenate"><code>Quaternion Concatenate(Quaternion value1, Quaternion value2)</code></a>_</td><td>Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.</td></tr>
<tr><td>static _<a href="VRageMath.Concatenate"><code>void Concatenate(ref Quaternion value1, ref Quaternion value2, ref Quaternion result)</code></a>_</td><td>Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.</td></tr>
<tr><td>static _<a href="VRageMath.Negate"><code>Quaternion Negate(Quaternion quaternion)</code></a>_</td><td>Flips the sign of each component of the quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.Negate"><code>void Negate(ref Quaternion quaternion, ref Quaternion result)</code></a>_</td><td>Flips the sign of each component of the quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.Add"><code>Quaternion Add(Quaternion quaternion1, Quaternion quaternion2)</code></a>_</td><td>Adds two Quaternions.</td></tr>
<tr><td>static _<a href="VRageMath.Add"><code>void Add(ref Quaternion quaternion1, ref Quaternion quaternion2, ref Quaternion result)</code></a>_</td><td>Adds two Quaternions.</td></tr>
<tr><td>static _<a href="VRageMath.Subtract"><code>Quaternion Subtract(Quaternion quaternion1, Quaternion quaternion2)</code></a>_</td><td>Subtracts a quaternion from another quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.Subtract"><code>void Subtract(ref Quaternion quaternion1, ref Quaternion quaternion2, ref Quaternion result)</code></a>_</td><td>Subtracts a quaternion from another quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.Multiply"><code>Quaternion Multiply(Quaternion quaternion1, Quaternion quaternion2)</code></a>_</td><td>Multiplies two quaternions.</td></tr>
<tr><td>static _<a href="VRageMath.Multiply"><code>void Multiply(ref Quaternion quaternion1, ref Quaternion quaternion2, ref Quaternion result)</code></a>_</td><td>Multiplies two quaternions.</td></tr>
<tr><td>static _<a href="VRageMath.Multiply"><code>Quaternion Multiply(Quaternion quaternion1, float scaleFactor)</code></a>_</td><td>Multiplies a quaternion by a scalar value.</td></tr>
<tr><td>static _<a href="VRageMath.Multiply"><code>void Multiply(ref Quaternion quaternion1, float scaleFactor, ref Quaternion result)</code></a>_</td><td>Multiplies a quaternion by a scalar value.</td></tr>
<tr><td>static _<a href="VRageMath.Divide"><code>Quaternion Divide(Quaternion quaternion1, Quaternion quaternion2)</code></a>_</td><td>Divides a Quaternion by another Quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.Divide"><code>void Divide(ref Quaternion quaternion1, ref Quaternion quaternion2, ref Quaternion result)</code></a>_</td><td>Divides a Quaternion by another Quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.FromVector4"><code>Quaternion FromVector4(Vector4 v)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.ToVector4"><code>Vector4 ToVector4()</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsZero"><code>bool IsZero(Quaternion value)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.IsZero"><code>bool IsZero(Quaternion value, float epsilon)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetForward"><code>void GetForward(ref Quaternion q, ref Vector3 result)</code></a>_</td><td>Gets forward vector (0,0,-1) transformed by quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.GetRight"><code>void GetRight(ref Quaternion q, ref Vector3 result)</code></a>_</td><td>Gets right vector (1,0,0) transformed by quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.GetUp"><code>void GetUp(ref Quaternion q, ref Vector3 result)</code></a>_</td><td>Gets up vector (0,1,0) transformed by quaternion.</td></tr>
<tr><td>_<a href="VRageMath.GetComponent"><code>float GetComponent(int index)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.SetComponent"><code>void SetComponent(int index, float value)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.FindLargestIndex"><code>int FindLargestIndex()</code></a>_</td><td></td></tr>
</table>
