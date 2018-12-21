← [Index](index.md)
# QuaternionD Struct
** Namespace: ** VRageMath  
** Assembly: ** VRage.Math.dll  
## Summary
Defines a four-dimensional vector (x,y,z,w), which is used to efficiently rotate an object about the (x, y, z) vector by the angle theta, where w = cos(theta/2). Uses double precision floating point numbers for calculation and storage
### Fields
|Member|Description|
|---|---|
|[`double X`](VRageMath.X.md)||
|[`double Y`](VRageMath.Y.md)||
|[`double Z`](VRageMath.Z.md)||
|[`double W`](VRageMath.W.md)||
|[`QuaternionD Identity`](VRageMath.Identity.md)||
### Methods
|Member|Description|
|---|---|
|[`string ToString()`](VRageMath.ToString.md)||
|[`bool Equals(QuaternionD other)`](VRageMath.Equals.md)|Determines whether the specified Object is equal to the QuaternionD.|
|[`bool Equals(Object obj)`](VRageMath.Equals.md)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`double LengthSquared()`](VRageMath.LengthSquared.md)||
|[`double Length()`](VRageMath.Length.md)||
|[`void Normalize()`](VRageMath.Normalize.md)||
|[`void GetAxisAngle(ref Vector3D axis, ref double angle)`](VRageMath.GetAxisAngle.md)||
|[`QuaternionD Normalize(QuaternionD quaternion)`](VRageMath.Normalize.md)|Divides each component of the quaternion by the length of the quaternion.|
|[`void Normalize(ref QuaternionD quaternion, ref QuaternionD result)`](VRageMath.Normalize.md)||
|[`void Conjugate()`](VRageMath.Conjugate.md)||
|[`QuaternionD Conjugate(QuaternionD value)`](VRageMath.Conjugate.md)|Returns the conjugate of a specified QuaternionD.|
|[`void Conjugate(ref QuaternionD value, ref QuaternionD result)`](VRageMath.Conjugate.md)||
|[`QuaternionD Inverse(QuaternionD quaternion)`](VRageMath.Inverse.md)|Returns the inverse of a QuaternionD.|
|[`void Inverse(ref QuaternionD quaternion, ref QuaternionD result)`](VRageMath.Inverse.md)||
|[`QuaternionD CreateFromAxisAngle(Vector3D axis, double angle)`](VRageMath.CreateFromAxisAngle.md)||
|[`void CreateFromAxisAngle(ref Vector3D axis, double angle, ref QuaternionD result)`](VRageMath.CreateFromAxisAngle.md)||
|[`QuaternionD CreateFromYawPitchRoll(double yaw, double pitch, double roll)`](VRageMath.CreateFromYawPitchRoll.md)||
|[`void CreateFromYawPitchRoll(double yaw, double pitch, double roll, ref QuaternionD result)`](VRageMath.CreateFromYawPitchRoll.md)||
|[`QuaternionD CreateFromForwardUp(Vector3D forward, Vector3D up)`](VRageMath.CreateFromForwardUp.md)||
|[`QuaternionD CreateFromRotationMatrix(MatrixD matrix)`](VRageMath.CreateFromRotationMatrix.md)|Creates a QuaternionD from a rotation MatrixD.|
|[`void CreateFromRotationMatrix(ref MatrixD matrix, ref QuaternionD result)`](VRageMath.CreateFromRotationMatrix.md)||
|[`double Dot(QuaternionD quaternion1, QuaternionD quaternion2)`](VRageMath.Dot.md)||
|[`void Dot(ref QuaternionD quaternion1, ref QuaternionD quaternion2, ref double result)`](VRageMath.Dot.md)||
|[`QuaternionD Slerp(QuaternionD quaternion1, QuaternionD quaternion2, double amount)`](VRageMath.Slerp.md)||
|[`void Slerp(ref QuaternionD quaternion1, ref QuaternionD quaternion2, double amount, ref QuaternionD result)`](VRageMath.Slerp.md)||
|[`QuaternionD Lerp(QuaternionD quaternion1, QuaternionD quaternion2, double amount)`](VRageMath.Lerp.md)||
|[`void Lerp(ref QuaternionD quaternion1, ref QuaternionD quaternion2, double amount, ref QuaternionD result)`](VRageMath.Lerp.md)||
|[`QuaternionD Concatenate(QuaternionD value1, QuaternionD value2)`](VRageMath.Concatenate.md)||
|[`void Concatenate(ref QuaternionD value1, ref QuaternionD value2, ref QuaternionD result)`](VRageMath.Concatenate.md)||
|[`QuaternionD Negate(QuaternionD quaternion)`](VRageMath.Negate.md)|Flips the sign of each component of the quaternion.|
|[`void Negate(ref QuaternionD quaternion, ref QuaternionD result)`](VRageMath.Negate.md)||
|[`QuaternionD Add(QuaternionD quaternion1, QuaternionD quaternion2)`](VRageMath.Add.md)||
|[`void Add(ref QuaternionD quaternion1, ref QuaternionD quaternion2, ref QuaternionD result)`](VRageMath.Add.md)||
|[`QuaternionD Subtract(QuaternionD quaternion1, QuaternionD quaternion2)`](VRageMath.Subtract.md)||
|[`void Subtract(ref QuaternionD quaternion1, ref QuaternionD quaternion2, ref QuaternionD result)`](VRageMath.Subtract.md)||
|[`QuaternionD Multiply(QuaternionD quaternion1, QuaternionD quaternion2)`](VRageMath.Multiply.md)||
|[`void Multiply(ref QuaternionD quaternion1, ref QuaternionD quaternion2, ref QuaternionD result)`](VRageMath.Multiply.md)||
|[`QuaternionD Multiply(QuaternionD quaternion1, double scaleFactor)`](VRageMath.Multiply.md)||
|[`void Multiply(ref QuaternionD quaternion1, double scaleFactor, ref QuaternionD result)`](VRageMath.Multiply.md)||
|[`QuaternionD Divide(QuaternionD quaternion1, QuaternionD quaternion2)`](VRageMath.Divide.md)||
|[`void Divide(ref QuaternionD quaternion1, ref QuaternionD quaternion2, ref QuaternionD result)`](VRageMath.Divide.md)||
|[`QuaternionD FromVector4(Vector4D v)`](VRageMath.FromVector4.md)||
|[`Vector4D ToVector4()`](VRageMath.ToVector4.md)||
|[`bool IsZero(QuaternionD value)`](VRageMath.IsZero.md)||
|[`bool IsZero(QuaternionD value, double epsilon)`](VRageMath.IsZero.md)||
|[`void CreateFromTwoVectors(ref Vector3D firstVector, ref Vector3D secondVector, ref QuaternionD result)`](VRageMath.CreateFromTwoVectors.md)||
|[`QuaternionD CreateFromTwoVectors(Vector3D firstVector, Vector3D secondVector)`](VRageMath.CreateFromTwoVectors.md)||
