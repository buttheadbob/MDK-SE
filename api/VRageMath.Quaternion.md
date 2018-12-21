← [Index](index)
# Quaternion Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a four-dimensional vector (x,y,z,w), which is used to efficiently rotate an object about the (x, y, z) vector by the angle theta, where w = cos(theta/2).
### Fields
|Member|Description|
|---|---|
|[`float X`](VRageMath.X)|Specifies the x-value of the vector component of the quaternion.|
|[`float Y`](VRageMath.Y)|Specifies the y-value of the vector component of the quaternion.|
|[`float Z`](VRageMath.Z)|Specifies the z-value of the vector component of the quaternion.|
|[`float W`](VRageMath.W)|Specifies the rotation component of the quaternion.|
|static [`Quaternion Identity`](VRageMath.Identity)||
|static [`Quaternion Zero`](VRageMath.Zero)||
### Properties
|Member|Description|
|---|---|
|[`Vector3 Forward`](VRageMath.Forward)||
|[`Vector3 Right`](VRageMath.Right)||
|[`Vector3 Up`](VRageMath.Up)||
### Methods
|Member|Description|
|---|---|
|[`string ToString()`](VRageMath.ToString)|Retireves a string representation of the current object.|
|[`string ToString(string format)`](VRageMath.ToString)||
|[`string ToStringAxisAngle(string format)`](VRageMath.ToStringAxisAngle)||
|[`bool Equals(Quaternion other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Quaternion.|
|[`bool Equals(Quaternion value, float epsilon)`](VRageMath.Equals)||
|[`bool Equals(Object obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Get the hash code of this object.|
|[`float LengthSquared()`](VRageMath.LengthSquared)|Calculates the length squared of a Quaternion.|
|[`float Length()`](VRageMath.Length)|Calculates the length of a Quaternion.|
|[`void Normalize()`](VRageMath.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[`void GetAxisAngle(ref Vector3 axis, ref float angle)`](VRageMath.GetAxisAngle)||
|static [`Quaternion Normalize(Quaternion quaternion)`](VRageMath.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|static [`void Normalize(ref Quaternion quaternion, ref Quaternion result)`](VRageMath.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[`void Conjugate()`](VRageMath.Conjugate)|Transforms this Quaternion into its conjugate.|
|static [`Quaternion Conjugate(Quaternion value)`](VRageMath.Conjugate)|Returns the conjugate of a specified Quaternion.|
|static [`void Conjugate(ref Quaternion value, ref Quaternion result)`](VRageMath.Conjugate)|Returns the conjugate of a specified Quaternion.|
|static [`Quaternion Inverse(Quaternion quaternion)`](VRageMath.Inverse)|Returns the inverse of a Quaternion.|
|static [`void Inverse(ref Quaternion quaternion, ref Quaternion result)`](VRageMath.Inverse)|Returns the inverse of a Quaternion.|
|static [`Quaternion CreateFromAxisAngle(Vector3 axis, float angle)`](VRageMath.CreateFromAxisAngle)|Creates a Quaternion from a vector and an angle to rotate about the vector.|
|static [`void CreateFromAxisAngle(ref Vector3 axis, float angle, ref Quaternion result)`](VRageMath.CreateFromAxisAngle)|Creates a Quaternion from a vector and an angle to rotate about the vector.|
|static [`Quaternion CreateFromYawPitchRoll(float yaw, float pitch, float roll)`](VRageMath.CreateFromYawPitchRoll)|Creates a new Quaternion from specified yaw, pitch, and roll angles.|
|static [`void CreateFromYawPitchRoll(float yaw, float pitch, float roll, ref Quaternion result)`](VRageMath.CreateFromYawPitchRoll)|Creates a new Quaternion from specified yaw, pitch, and roll angles.|
|static [`Quaternion CreateFromForwardUp(Vector3 forward, Vector3 up)`](VRageMath.CreateFromForwardUp)|Works for normalized vectors only|
|static [`Quaternion CreateFromRotationMatrix(MatrixD matrix)`](VRageMath.CreateFromRotationMatrix)||
|static [`Quaternion CreateFromRotationMatrix(Matrix matrix)`](VRageMath.CreateFromRotationMatrix)|Creates a Quaternion from a rotation Matrix.|
|static [`void CreateFromRotationMatrix(ref MatrixD matrix, ref Quaternion result)`](VRageMath.CreateFromRotationMatrix)||
|static [`void CreateFromTwoVectors(ref Vector3 firstVector, ref Vector3 secondVector, ref Quaternion result)`](VRageMath.CreateFromTwoVectors)||
|static [`Quaternion CreateFromTwoVectors(Vector3 firstVector, Vector3 secondVector)`](VRageMath.CreateFromTwoVectors)||
|static [`void CreateFromRotationMatrix(ref Matrix matrix, ref Quaternion result)`](VRageMath.CreateFromRotationMatrix)|Creates a Quaternion from a rotation Matrix.|
|static [`void CreateFromRotationMatrix(ref Matrix3x3 matrix, ref Quaternion result)`](VRageMath.CreateFromRotationMatrix)|Creates a Quaternion from a rotation Matrix.|
|static [`float Dot(Quaternion quaternion1, Quaternion quaternion2)`](VRageMath.Dot)|Calculates the dot product of two Quaternions.|
|static [`void Dot(ref Quaternion quaternion1, ref Quaternion quaternion2, ref float result)`](VRageMath.Dot)|Calculates the dot product of two Quaternions.|
|static [`Quaternion Slerp(Quaternion quaternion1, Quaternion quaternion2, float amount)`](VRageMath.Slerp)|Interpolates between two quaternions, using spherical linear interpolation.|
|static [`void Slerp(ref Quaternion quaternion1, ref Quaternion quaternion2, float amount, ref Quaternion result)`](VRageMath.Slerp)|Interpolates between two quaternions, using spherical linear interpolation.|
|static [`Quaternion Lerp(Quaternion quaternion1, Quaternion quaternion2, float amount)`](VRageMath.Lerp)|Linearly interpolates between two quaternions.|
|static [`void Lerp(ref Quaternion quaternion1, ref Quaternion quaternion2, float amount, ref Quaternion result)`](VRageMath.Lerp)|Linearly interpolates between two quaternions.|
|static [`Quaternion Concatenate(Quaternion value1, Quaternion value2)`](VRageMath.Concatenate)|Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.|
|static [`void Concatenate(ref Quaternion value1, ref Quaternion value2, ref Quaternion result)`](VRageMath.Concatenate)|Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.|
|static [`Quaternion Negate(Quaternion quaternion)`](VRageMath.Negate)|Flips the sign of each component of the quaternion.|
|static [`void Negate(ref Quaternion quaternion, ref Quaternion result)`](VRageMath.Negate)|Flips the sign of each component of the quaternion.|
|static [`Quaternion Add(Quaternion quaternion1, Quaternion quaternion2)`](VRageMath.Add)|Adds two Quaternions.|
|static [`void Add(ref Quaternion quaternion1, ref Quaternion quaternion2, ref Quaternion result)`](VRageMath.Add)|Adds two Quaternions.|
|static [`Quaternion Subtract(Quaternion quaternion1, Quaternion quaternion2)`](VRageMath.Subtract)|Subtracts a quaternion from another quaternion.|
|static [`void Subtract(ref Quaternion quaternion1, ref Quaternion quaternion2, ref Quaternion result)`](VRageMath.Subtract)|Subtracts a quaternion from another quaternion.|
|static [`Quaternion Multiply(Quaternion quaternion1, Quaternion quaternion2)`](VRageMath.Multiply)|Multiplies two quaternions.|
|static [`void Multiply(ref Quaternion quaternion1, ref Quaternion quaternion2, ref Quaternion result)`](VRageMath.Multiply)|Multiplies two quaternions.|
|static [`Quaternion Multiply(Quaternion quaternion1, float scaleFactor)`](VRageMath.Multiply)|Multiplies a quaternion by a scalar value.|
|static [`void Multiply(ref Quaternion quaternion1, float scaleFactor, ref Quaternion result)`](VRageMath.Multiply)|Multiplies a quaternion by a scalar value.|
|static [`Quaternion Divide(Quaternion quaternion1, Quaternion quaternion2)`](VRageMath.Divide)|Divides a Quaternion by another Quaternion.|
|static [`void Divide(ref Quaternion quaternion1, ref Quaternion quaternion2, ref Quaternion result)`](VRageMath.Divide)|Divides a Quaternion by another Quaternion.|
|static [`Quaternion FromVector4(Vector4 v)`](VRageMath.FromVector4)||
|[`Vector4 ToVector4()`](VRageMath.ToVector4)||
|static [`bool IsZero(Quaternion value)`](VRageMath.IsZero)||
|static [`bool IsZero(Quaternion value, float epsilon)`](VRageMath.IsZero)||
|static [`void GetForward(ref Quaternion q, ref Vector3 result)`](VRageMath.GetForward)|Gets forward vector (0,0,-1) transformed by quaternion.|
|static [`void GetRight(ref Quaternion q, ref Vector3 result)`](VRageMath.GetRight)|Gets right vector (1,0,0) transformed by quaternion.|
|static [`void GetUp(ref Quaternion q, ref Vector3 result)`](VRageMath.GetUp)|Gets up vector (0,1,0) transformed by quaternion.|
|[`float GetComponent(int index)`](VRageMath.GetComponent)||
|[`void SetComponent(int index, float value)`](VRageMath.SetComponent)||
|[`int FindLargestIndex()`](VRageMath.FindLargestIndex)||
