← [Index](index.md)
# QuaternionD Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Defines a four-dimensional vector (x,y,z,w), which is used to efficiently rotate an object about the (x, y, z) vector by the angle theta, where w = cos(theta/2). Uses double precision floating point numbers for calculation and storage
### Fields
|Member|Description|
|---|---|
|[`double X`](VRageMath.X)||
|[`double Y`](VRageMath.Y)||
|[`double Z`](VRageMath.Z)||
|[`double W`](VRageMath.W)||
|[`QuaternionD Identity`](VRageMath.Identity)||
### Methods
|Member|Description|
|---|---|
|[`string ToString()`](VRageMath.ToString)||
|[`bool Equals(QuaternionD other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the QuaternionD.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`double LengthSquared()`](VRageMath.LengthSquared)||
|[`double Length()`](VRageMath.Length)||
|[`void Normalize()`](VRageMath.Normalize)||
|[`void GetAxisAngle(ref Vector3D axis, ref double angle)`](VRageMath.GetAxisAngle)||
|[`QuaternionD Normalize(QuaternionD quaternion)`](VRageMath.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[`void Normalize(ref QuaternionD quaternion, ref QuaternionD result)`](VRageMath.Normalize)||
|[`void Conjugate()`](VRageMath.Conjugate)||
|[`QuaternionD Conjugate(QuaternionD value)`](VRageMath.Conjugate)|Returns the conjugate of a specified QuaternionD.|
|[`void Conjugate(ref QuaternionD value, ref QuaternionD result)`](VRageMath.Conjugate)||
|[`QuaternionD Inverse(QuaternionD quaternion)`](VRageMath.Inverse)|Returns the inverse of a QuaternionD.|
|[`void Inverse(ref QuaternionD quaternion, ref QuaternionD result)`](VRageMath.Inverse)||
|[`QuaternionD CreateFromAxisAngle(Vector3D axis, double angle)`](VRageMath.CreateFromAxisAngle)||
|[`void CreateFromAxisAngle(ref Vector3D axis, double angle, ref QuaternionD result)`](VRageMath.CreateFromAxisAngle)||
|[`QuaternionD CreateFromYawPitchRoll(double yaw, double pitch, double roll)`](VRageMath.CreateFromYawPitchRoll)||
|[`void CreateFromYawPitchRoll(double yaw, double pitch, double roll, ref QuaternionD result)`](VRageMath.CreateFromYawPitchRoll)||
|[`QuaternionD CreateFromForwardUp(Vector3D forward, Vector3D up)`](VRageMath.CreateFromForwardUp)||
|[`QuaternionD CreateFromRotationMatrix(MatrixD matrix)`](VRageMath.CreateFromRotationMatrix)|Creates a QuaternionD from a rotation MatrixD.|
|[`void CreateFromRotationMatrix(ref MatrixD matrix, ref QuaternionD result)`](VRageMath.CreateFromRotationMatrix)||
|[`double Dot(QuaternionD quaternion1, QuaternionD quaternion2)`](VRageMath.Dot)||
|[`void Dot(ref QuaternionD quaternion1, ref QuaternionD quaternion2, ref double result)`](VRageMath.Dot)||
|[`QuaternionD Slerp(QuaternionD quaternion1, QuaternionD quaternion2, double amount)`](VRageMath.Slerp)||
|[`void Slerp(ref QuaternionD quaternion1, ref QuaternionD quaternion2, double amount, ref QuaternionD result)`](VRageMath.Slerp)||
|[`QuaternionD Lerp(QuaternionD quaternion1, QuaternionD quaternion2, double amount)`](VRageMath.Lerp)||
|[`void Lerp(ref QuaternionD quaternion1, ref QuaternionD quaternion2, double amount, ref QuaternionD result)`](VRageMath.Lerp)||
|[`QuaternionD Concatenate(QuaternionD value1, QuaternionD value2)`](VRageMath.Concatenate)||
|[`void Concatenate(ref QuaternionD value1, ref QuaternionD value2, ref QuaternionD result)`](VRageMath.Concatenate)||
|[`QuaternionD Negate(QuaternionD quaternion)`](VRageMath.Negate)|Flips the sign of each component of the quaternion.|
|[`void Negate(ref QuaternionD quaternion, ref QuaternionD result)`](VRageMath.Negate)||
|[`QuaternionD Add(QuaternionD quaternion1, QuaternionD quaternion2)`](VRageMath.Add)||
|[`void Add(ref QuaternionD quaternion1, ref QuaternionD quaternion2, ref QuaternionD result)`](VRageMath.Add)||
|[`QuaternionD Subtract(QuaternionD quaternion1, QuaternionD quaternion2)`](VRageMath.Subtract)||
|[`void Subtract(ref QuaternionD quaternion1, ref QuaternionD quaternion2, ref QuaternionD result)`](VRageMath.Subtract)||
|[`QuaternionD Multiply(QuaternionD quaternion1, QuaternionD quaternion2)`](VRageMath.Multiply)||
|[`void Multiply(ref QuaternionD quaternion1, ref QuaternionD quaternion2, ref QuaternionD result)`](VRageMath.Multiply)||
|[`QuaternionD Multiply(QuaternionD quaternion1, double scaleFactor)`](VRageMath.Multiply)||
|[`void Multiply(ref QuaternionD quaternion1, double scaleFactor, ref QuaternionD result)`](VRageMath.Multiply)||
|[`QuaternionD Divide(QuaternionD quaternion1, QuaternionD quaternion2)`](VRageMath.Divide)||
|[`void Divide(ref QuaternionD quaternion1, ref QuaternionD quaternion2, ref QuaternionD result)`](VRageMath.Divide)||
|[`QuaternionD FromVector4(Vector4D v)`](VRageMath.FromVector4)||
|[`Vector4D ToVector4()`](VRageMath.ToVector4)||
|[`bool IsZero(QuaternionD value)`](VRageMath.IsZero)||
|[`bool IsZero(QuaternionD value, double epsilon)`](VRageMath.IsZero)||
|[`void CreateFromTwoVectors(ref Vector3D firstVector, ref Vector3D secondVector, ref QuaternionD result)`](VRageMath.CreateFromTwoVectors)||
|[`QuaternionD CreateFromTwoVectors(Vector3D firstVector, Vector3D secondVector)`](VRageMath.CreateFromTwoVectors)||
