← [Index](index)
# Quaternion Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Defines a four-dimensional vector (x,y,z,w), which is used to efficiently rotate an object about the (x, y, z) vector by the angle theta, where w = cos(theta/2).
### Fields
|Member|Description|
|---|---|
|[`float X`](VRageMath.X)||
|[`float Y`](VRageMath.Y)||
|[`float Z`](VRageMath.Z)||
|[`float W`](VRageMath.W)||
|[`Quaternion Identity`](VRageMath.Identity)||
|[`Quaternion Zero`](VRageMath.Zero)||
### Properties
|Member|Description|
|---|---|
|[`Vector3 Forward`](VRageMath.Forward)||
|[`Vector3 Right`](VRageMath.Right)||
|[`Vector3 Up`](VRageMath.Up)||
### Methods
|Member|Description|
|---|---|
|[`string ToString()`](VRageMath.ToString)||
|[`string ToString(string format)`](VRageMath.ToString)||
|[`string ToStringAxisAngle(string format)`](VRageMath.ToStringAxisAngle)||
|[`bool Equals(Quaternion other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Quaternion.|
|[`bool Equals(Quaternion value, float epsilon)`](VRageMath.Equals)||
|[`bool Equals(Object obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`float LengthSquared()`](VRageMath.LengthSquared)||
|[`float Length()`](VRageMath.Length)||
|[`void Normalize()`](VRageMath.Normalize)||
|[`void GetAxisAngle(ref Vector3 axis, ref float angle)`](VRageMath.GetAxisAngle)||
|[`Quaternion Normalize(Quaternion quaternion)`](VRageMath.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[`void Normalize(ref Quaternion quaternion, ref Quaternion result)`](VRageMath.Normalize)||
|[`void Conjugate()`](VRageMath.Conjugate)||
|[`Quaternion Conjugate(Quaternion value)`](VRageMath.Conjugate)|Returns the conjugate of a specified Quaternion.|
|[`void Conjugate(ref Quaternion value, ref Quaternion result)`](VRageMath.Conjugate)||
|[`Quaternion Inverse(Quaternion quaternion)`](VRageMath.Inverse)|Returns the inverse of a Quaternion.|
|[`void Inverse(ref Quaternion quaternion, ref Quaternion result)`](VRageMath.Inverse)||
|[`Quaternion CreateFromAxisAngle(Vector3 axis, float angle)`](VRageMath.CreateFromAxisAngle)||
|[`void CreateFromAxisAngle(ref Vector3 axis, float angle, ref Quaternion result)`](VRageMath.CreateFromAxisAngle)||
|[`Quaternion CreateFromYawPitchRoll(float yaw, float pitch, float roll)`](VRageMath.CreateFromYawPitchRoll)||
|[`void CreateFromYawPitchRoll(float yaw, float pitch, float roll, ref Quaternion result)`](VRageMath.CreateFromYawPitchRoll)||
|[`Quaternion CreateFromForwardUp(Vector3 forward, Vector3 up)`](VRageMath.CreateFromForwardUp)||
|[`Quaternion CreateFromRotationMatrix(MatrixD matrix)`](VRageMath.CreateFromRotationMatrix)||
|[`Quaternion CreateFromRotationMatrix(Matrix matrix)`](VRageMath.CreateFromRotationMatrix)|Creates a Quaternion from a rotation Matrix.|
|[`void CreateFromRotationMatrix(ref MatrixD matrix, ref Quaternion result)`](VRageMath.CreateFromRotationMatrix)||
|[`void CreateFromTwoVectors(ref Vector3 firstVector, ref Vector3 secondVector, ref Quaternion result)`](VRageMath.CreateFromTwoVectors)||
|[`Quaternion CreateFromTwoVectors(Vector3 firstVector, Vector3 secondVector)`](VRageMath.CreateFromTwoVectors)||
|[`void CreateFromRotationMatrix(ref Matrix matrix, ref Quaternion result)`](VRageMath.CreateFromRotationMatrix)||
|[`void CreateFromRotationMatrix(ref Matrix3x3 matrix, ref Quaternion result)`](VRageMath.CreateFromRotationMatrix)||
|[`float Dot(Quaternion quaternion1, Quaternion quaternion2)`](VRageMath.Dot)||
|[`void Dot(ref Quaternion quaternion1, ref Quaternion quaternion2, ref float result)`](VRageMath.Dot)||
|[`Quaternion Slerp(Quaternion quaternion1, Quaternion quaternion2, float amount)`](VRageMath.Slerp)||
|[`void Slerp(ref Quaternion quaternion1, ref Quaternion quaternion2, float amount, ref Quaternion result)`](VRageMath.Slerp)||
|[`Quaternion Lerp(Quaternion quaternion1, Quaternion quaternion2, float amount)`](VRageMath.Lerp)||
|[`void Lerp(ref Quaternion quaternion1, ref Quaternion quaternion2, float amount, ref Quaternion result)`](VRageMath.Lerp)||
|[`Quaternion Concatenate(Quaternion value1, Quaternion value2)`](VRageMath.Concatenate)||
|[`void Concatenate(ref Quaternion value1, ref Quaternion value2, ref Quaternion result)`](VRageMath.Concatenate)||
|[`Quaternion Negate(Quaternion quaternion)`](VRageMath.Negate)|Flips the sign of each component of the quaternion.|
|[`void Negate(ref Quaternion quaternion, ref Quaternion result)`](VRageMath.Negate)||
|[`Quaternion Add(Quaternion quaternion1, Quaternion quaternion2)`](VRageMath.Add)||
|[`void Add(ref Quaternion quaternion1, ref Quaternion quaternion2, ref Quaternion result)`](VRageMath.Add)||
|[`Quaternion Subtract(Quaternion quaternion1, Quaternion quaternion2)`](VRageMath.Subtract)||
|[`void Subtract(ref Quaternion quaternion1, ref Quaternion quaternion2, ref Quaternion result)`](VRageMath.Subtract)||
|[`Quaternion Multiply(Quaternion quaternion1, Quaternion quaternion2)`](VRageMath.Multiply)||
|[`void Multiply(ref Quaternion quaternion1, ref Quaternion quaternion2, ref Quaternion result)`](VRageMath.Multiply)||
|[`Quaternion Multiply(Quaternion quaternion1, float scaleFactor)`](VRageMath.Multiply)||
|[`void Multiply(ref Quaternion quaternion1, float scaleFactor, ref Quaternion result)`](VRageMath.Multiply)||
|[`Quaternion Divide(Quaternion quaternion1, Quaternion quaternion2)`](VRageMath.Divide)||
|[`void Divide(ref Quaternion quaternion1, ref Quaternion quaternion2, ref Quaternion result)`](VRageMath.Divide)||
|[`Quaternion FromVector4(Vector4 v)`](VRageMath.FromVector4)||
|[`Vector4 ToVector4()`](VRageMath.ToVector4)||
|[`bool IsZero(Quaternion value)`](VRageMath.IsZero)||
|[`bool IsZero(Quaternion value, float epsilon)`](VRageMath.IsZero)||
|[`void GetForward(ref Quaternion q, ref Vector3 result)`](VRageMath.GetForward)||
|[`void GetRight(ref Quaternion q, ref Vector3 result)`](VRageMath.GetRight)||
|[`void GetUp(ref Quaternion q, ref Vector3 result)`](VRageMath.GetUp)||
|[`float GetComponent(int index)`](VRageMath.GetComponent)||
|[`void SetComponent(int index, float value)`](VRageMath.SetComponent)||
|[`int FindLargestIndex()`](VRageMath.FindLargestIndex)||
