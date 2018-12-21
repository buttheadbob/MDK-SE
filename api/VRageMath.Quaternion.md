← [Index](index.md)
# Quaternion Struct
** Namespace: ** VRageMath  
** Assembly: ** VRage.Math.dll  
## Summary
Defines a four-dimensional vector (x,y,z,w), which is used to efficiently rotate an object about the (x, y, z) vector by the angle theta, where w = cos(theta/2).
### Fields
|Member|Description|
|---|---|
|[`float X`](VRageMath.X.md)||
|[`float Y`](VRageMath.Y.md)||
|[`float Z`](VRageMath.Z.md)||
|[`float W`](VRageMath.W.md)||
|[`Quaternion Identity`](VRageMath.Identity.md)||
|[`Quaternion Zero`](VRageMath.Zero.md)||
### Properties
|Member|Description|
|---|---|
|[`Vector3 Forward`](VRageMath.Forward.md)||
|[`Vector3 Right`](VRageMath.Right.md)||
|[`Vector3 Up`](VRageMath.Up.md)||
### Methods
|Member|Description|
|---|---|
|[`string ToString()`](VRageMath.ToString.md)||
|[`string ToString(string format)`](VRageMath.ToString.md)||
|[`string ToStringAxisAngle(string format)`](VRageMath.ToStringAxisAngle.md)||
|[`bool Equals(Quaternion other)`](VRageMath.Equals.md)|Determines whether the specified Object is equal to the Quaternion.|
|[`bool Equals(Quaternion value, float epsilon)`](VRageMath.Equals.md)||
|[`bool Equals(Object obj)`](VRageMath.Equals.md)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`float LengthSquared()`](VRageMath.LengthSquared.md)||
|[`float Length()`](VRageMath.Length.md)||
|[`void Normalize()`](VRageMath.Normalize.md)||
|[`void GetAxisAngle(ref Vector3 axis, ref float angle)`](VRageMath.GetAxisAngle.md)||
|[`Quaternion Normalize(Quaternion quaternion)`](VRageMath.Normalize.md)|Divides each component of the quaternion by the length of the quaternion.|
|[`void Normalize(ref Quaternion quaternion, ref Quaternion result)`](VRageMath.Normalize.md)||
|[`void Conjugate()`](VRageMath.Conjugate.md)||
|[`Quaternion Conjugate(Quaternion value)`](VRageMath.Conjugate.md)|Returns the conjugate of a specified Quaternion.|
|[`void Conjugate(ref Quaternion value, ref Quaternion result)`](VRageMath.Conjugate.md)||
|[`Quaternion Inverse(Quaternion quaternion)`](VRageMath.Inverse.md)|Returns the inverse of a Quaternion.|
|[`void Inverse(ref Quaternion quaternion, ref Quaternion result)`](VRageMath.Inverse.md)||
|[`Quaternion CreateFromAxisAngle(Vector3 axis, float angle)`](VRageMath.CreateFromAxisAngle.md)||
|[`void CreateFromAxisAngle(ref Vector3 axis, float angle, ref Quaternion result)`](VRageMath.CreateFromAxisAngle.md)||
|[`Quaternion CreateFromYawPitchRoll(float yaw, float pitch, float roll)`](VRageMath.CreateFromYawPitchRoll.md)||
|[`void CreateFromYawPitchRoll(float yaw, float pitch, float roll, ref Quaternion result)`](VRageMath.CreateFromYawPitchRoll.md)||
|[`Quaternion CreateFromForwardUp(Vector3 forward, Vector3 up)`](VRageMath.CreateFromForwardUp.md)||
|[`Quaternion CreateFromRotationMatrix(MatrixD matrix)`](VRageMath.CreateFromRotationMatrix.md)||
|[`Quaternion CreateFromRotationMatrix(Matrix matrix)`](VRageMath.CreateFromRotationMatrix.md)|Creates a Quaternion from a rotation Matrix.|
|[`void CreateFromRotationMatrix(ref MatrixD matrix, ref Quaternion result)`](VRageMath.CreateFromRotationMatrix.md)||
|[`void CreateFromTwoVectors(ref Vector3 firstVector, ref Vector3 secondVector, ref Quaternion result)`](VRageMath.CreateFromTwoVectors.md)||
|[`Quaternion CreateFromTwoVectors(Vector3 firstVector, Vector3 secondVector)`](VRageMath.CreateFromTwoVectors.md)||
|[`void CreateFromRotationMatrix(ref Matrix matrix, ref Quaternion result)`](VRageMath.CreateFromRotationMatrix.md)||
|[`void CreateFromRotationMatrix(ref Matrix3x3 matrix, ref Quaternion result)`](VRageMath.CreateFromRotationMatrix.md)||
|[`float Dot(Quaternion quaternion1, Quaternion quaternion2)`](VRageMath.Dot.md)||
|[`void Dot(ref Quaternion quaternion1, ref Quaternion quaternion2, ref float result)`](VRageMath.Dot.md)||
|[`Quaternion Slerp(Quaternion quaternion1, Quaternion quaternion2, float amount)`](VRageMath.Slerp.md)||
|[`void Slerp(ref Quaternion quaternion1, ref Quaternion quaternion2, float amount, ref Quaternion result)`](VRageMath.Slerp.md)||
|[`Quaternion Lerp(Quaternion quaternion1, Quaternion quaternion2, float amount)`](VRageMath.Lerp.md)||
|[`void Lerp(ref Quaternion quaternion1, ref Quaternion quaternion2, float amount, ref Quaternion result)`](VRageMath.Lerp.md)||
|[`Quaternion Concatenate(Quaternion value1, Quaternion value2)`](VRageMath.Concatenate.md)||
|[`void Concatenate(ref Quaternion value1, ref Quaternion value2, ref Quaternion result)`](VRageMath.Concatenate.md)||
|[`Quaternion Negate(Quaternion quaternion)`](VRageMath.Negate.md)|Flips the sign of each component of the quaternion.|
|[`void Negate(ref Quaternion quaternion, ref Quaternion result)`](VRageMath.Negate.md)||
|[`Quaternion Add(Quaternion quaternion1, Quaternion quaternion2)`](VRageMath.Add.md)||
|[`void Add(ref Quaternion quaternion1, ref Quaternion quaternion2, ref Quaternion result)`](VRageMath.Add.md)||
|[`Quaternion Subtract(Quaternion quaternion1, Quaternion quaternion2)`](VRageMath.Subtract.md)||
|[`void Subtract(ref Quaternion quaternion1, ref Quaternion quaternion2, ref Quaternion result)`](VRageMath.Subtract.md)||
|[`Quaternion Multiply(Quaternion quaternion1, Quaternion quaternion2)`](VRageMath.Multiply.md)||
|[`void Multiply(ref Quaternion quaternion1, ref Quaternion quaternion2, ref Quaternion result)`](VRageMath.Multiply.md)||
|[`Quaternion Multiply(Quaternion quaternion1, float scaleFactor)`](VRageMath.Multiply.md)||
|[`void Multiply(ref Quaternion quaternion1, float scaleFactor, ref Quaternion result)`](VRageMath.Multiply.md)||
|[`Quaternion Divide(Quaternion quaternion1, Quaternion quaternion2)`](VRageMath.Divide.md)||
|[`void Divide(ref Quaternion quaternion1, ref Quaternion quaternion2, ref Quaternion result)`](VRageMath.Divide.md)||
|[`Quaternion FromVector4(Vector4 v)`](VRageMath.FromVector4.md)||
|[`Vector4 ToVector4()`](VRageMath.ToVector4.md)||
|[`bool IsZero(Quaternion value)`](VRageMath.IsZero.md)||
|[`bool IsZero(Quaternion value, float epsilon)`](VRageMath.IsZero.md)||
|[`void GetForward(ref Quaternion q, ref Vector3 result)`](VRageMath.GetForward.md)||
|[`void GetRight(ref Quaternion q, ref Vector3 result)`](VRageMath.GetRight.md)||
|[`void GetUp(ref Quaternion q, ref Vector3 result)`](VRageMath.GetUp.md)||
|[`float GetComponent(int index)`](VRageMath.GetComponent.md)||
|[`void SetComponent(int index, float value)`](VRageMath.SetComponent.md)||
|[`int FindLargestIndex()`](VRageMath.FindLargestIndex.md)||
