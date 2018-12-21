← [Index](index)
# QuaternionD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a four-dimensional vector (x,y,z,w), which is used to efficiently rotate an object about the (x, y, z) vector by the angle theta, where w = cos(theta/2). Uses double precision floating point numbers for calculation and storage
### Fields
|Member|Description|
|---|---|
|[`double X`](VRageMath.X)|Specifies the x-value of the vector component of the quaternion.|
|[`double Y`](VRageMath.Y)|Specifies the y-value of the vector component of the quaternion.|
|[`double Z`](VRageMath.Z)|Specifies the z-value of the vector component of the quaternion.|
|[`double W`](VRageMath.W)|Specifies the rotation component of the quaternion.|
|static [`QuaternionD Identity`](VRageMath.Identity)||
### Methods
|Member|Description|
|---|---|
|[`string ToString()`](VRageMath.ToString)|Retireves a string representation of the current object.|
|[`bool Equals(QuaternionD other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the QuaternionD.|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Get the hash code of this object.|
|[`double LengthSquared()`](VRageMath.LengthSquared)|Calculates the length squared of a QuaternionD.|
|[`double Length()`](VRageMath.Length)|Calculates the length of a QuaternionD.|
|[`void Normalize()`](VRageMath.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[`void GetAxisAngle(ref Vector3D axis, ref double angle)`](VRageMath.GetAxisAngle)||
|static [`QuaternionD Normalize(QuaternionD quaternion)`](VRageMath.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|static [`void Normalize(ref QuaternionD quaternion, ref QuaternionD result)`](VRageMath.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[`void Conjugate()`](VRageMath.Conjugate)|Transforms this QuaternionD into its conjugate.|
|static [`QuaternionD Conjugate(QuaternionD value)`](VRageMath.Conjugate)|Returns the conjugate of a specified QuaternionD.|
|static [`void Conjugate(ref QuaternionD value, ref QuaternionD result)`](VRageMath.Conjugate)|Returns the conjugate of a specified QuaternionD.|
|static [`QuaternionD Inverse(QuaternionD quaternion)`](VRageMath.Inverse)|Returns the inverse of a QuaternionD.|
|static [`void Inverse(ref QuaternionD quaternion, ref QuaternionD result)`](VRageMath.Inverse)|Returns the inverse of a QuaternionD.|
|static [`QuaternionD CreateFromAxisAngle(Vector3D axis, double angle)`](VRageMath.CreateFromAxisAngle)|Creates a QuaternionD from a vector and an angle to rotate about the vector.|
|static [`void CreateFromAxisAngle(ref Vector3D axis, double angle, ref QuaternionD result)`](VRageMath.CreateFromAxisAngle)|Creates a QuaternionD from a vector and an angle to rotate about the vector.|
|static [`QuaternionD CreateFromYawPitchRoll(double yaw, double pitch, double roll)`](VRageMath.CreateFromYawPitchRoll)|Creates a new QuaternionD from specified yaw, pitch, and roll angles.|
|static [`void CreateFromYawPitchRoll(double yaw, double pitch, double roll, ref QuaternionD result)`](VRageMath.CreateFromYawPitchRoll)|Creates a new QuaternionD from specified yaw, pitch, and roll angles.|
|static [`QuaternionD CreateFromForwardUp(Vector3D forward, Vector3D up)`](VRageMath.CreateFromForwardUp)|Works for normalized vectors only|
|static [`QuaternionD CreateFromRotationMatrix(MatrixD matrix)`](VRageMath.CreateFromRotationMatrix)|Creates a QuaternionD from a rotation MatrixD.|
|static [`void CreateFromRotationMatrix(ref MatrixD matrix, ref QuaternionD result)`](VRageMath.CreateFromRotationMatrix)|Creates a QuaternionD from a rotation MatrixD.|
|static [`double Dot(QuaternionD quaternion1, QuaternionD quaternion2)`](VRageMath.Dot)|Calculates the dot product of two Quaternions.|
|static [`void Dot(ref QuaternionD quaternion1, ref QuaternionD quaternion2, ref double result)`](VRageMath.Dot)|Calculates the dot product of two Quaternions.|
|static [`QuaternionD Slerp(QuaternionD quaternion1, QuaternionD quaternion2, double amount)`](VRageMath.Slerp)|Interpolates between two quaternions, using spherical linear interpolation.|
|static [`void Slerp(ref QuaternionD quaternion1, ref QuaternionD quaternion2, double amount, ref QuaternionD result)`](VRageMath.Slerp)|Interpolates between two quaternions, using spherical linear interpolation.|
|static [`QuaternionD Lerp(QuaternionD quaternion1, QuaternionD quaternion2, double amount)`](VRageMath.Lerp)|Linearly interpolates between two quaternions.|
|static [`void Lerp(ref QuaternionD quaternion1, ref QuaternionD quaternion2, double amount, ref QuaternionD result)`](VRageMath.Lerp)|Linearly interpolates between two quaternions.|
|static [`QuaternionD Concatenate(QuaternionD value1, QuaternionD value2)`](VRageMath.Concatenate)|Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.|
|static [`void Concatenate(ref QuaternionD value1, ref QuaternionD value2, ref QuaternionD result)`](VRageMath.Concatenate)|Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.|
|static [`QuaternionD Negate(QuaternionD quaternion)`](VRageMath.Negate)|Flips the sign of each component of the quaternion.|
|static [`void Negate(ref QuaternionD quaternion, ref QuaternionD result)`](VRageMath.Negate)|Flips the sign of each component of the quaternion.|
|static [`QuaternionD Add(QuaternionD quaternion1, QuaternionD quaternion2)`](VRageMath.Add)|Adds two Quaternions.|
|static [`void Add(ref QuaternionD quaternion1, ref QuaternionD quaternion2, ref QuaternionD result)`](VRageMath.Add)|Adds two Quaternions.|
|static [`QuaternionD Subtract(QuaternionD quaternion1, QuaternionD quaternion2)`](VRageMath.Subtract)|Subtracts a quaternion from another quaternion.|
|static [`void Subtract(ref QuaternionD quaternion1, ref QuaternionD quaternion2, ref QuaternionD result)`](VRageMath.Subtract)|Subtracts a quaternion from another quaternion.|
|static [`QuaternionD Multiply(QuaternionD quaternion1, QuaternionD quaternion2)`](VRageMath.Multiply)|Multiplies two quaternions.|
|static [`void Multiply(ref QuaternionD quaternion1, ref QuaternionD quaternion2, ref QuaternionD result)`](VRageMath.Multiply)|Multiplies two quaternions.|
|static [`QuaternionD Multiply(QuaternionD quaternion1, double scaleFactor)`](VRageMath.Multiply)|Multiplies a quaternion by a scalar value.|
|static [`void Multiply(ref QuaternionD quaternion1, double scaleFactor, ref QuaternionD result)`](VRageMath.Multiply)|Multiplies a quaternion by a scalar value.|
|static [`QuaternionD Divide(QuaternionD quaternion1, QuaternionD quaternion2)`](VRageMath.Divide)|Divides a QuaternionD by another QuaternionD.|
|static [`void Divide(ref QuaternionD quaternion1, ref QuaternionD quaternion2, ref QuaternionD result)`](VRageMath.Divide)|Divides a QuaternionD by another QuaternionD.|
|static [`QuaternionD FromVector4(Vector4D v)`](VRageMath.FromVector4)||
|[`Vector4D ToVector4()`](VRageMath.ToVector4)||
|static [`bool IsZero(QuaternionD value)`](VRageMath.IsZero)||
|static [`bool IsZero(QuaternionD value, double epsilon)`](VRageMath.IsZero)||
|static [`void CreateFromTwoVectors(ref Vector3D firstVector, ref Vector3D secondVector, ref QuaternionD result)`](VRageMath.CreateFromTwoVectors)||
|static [`QuaternionD CreateFromTwoVectors(Vector3D firstVector, Vector3D secondVector)`](VRageMath.CreateFromTwoVectors)||
