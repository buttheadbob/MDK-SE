← [Index](ApiIndex)
# QuaternionD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a four-dimensional vector (x,y,z,w), which is used to efficiently rotate an object about the (x, y, z) vector by the angle theta, where w = cos(theta/2). Uses double precision floating point numbers for calculation and storage
### Fields
|Member|Description|
|---|---|
|[`X`](VRageMath.X)|Specifies the x-value of the vector component of the quaternion.|
|[`Y`](VRageMath.Y)|Specifies the y-value of the vector component of the quaternion.|
|[`Z`](VRageMath.Z)|Specifies the z-value of the vector component of the quaternion.|
|[`W`](VRageMath.W)|Specifies the rotation component of the quaternion.|
|[`Identity`](VRageMath.Identity)||
### Methods
|Member|Description|
|---|---|
|[`ToString()`](VRageMath.ToString)|Retireves a string representation of the current object.|
|[`Equals(QuaternionD)`](VRageMath.Equals)|Determines whether the specified Object is equal to the QuaternionD.|
|[`Equals(Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`GetHashCode()`](VRageMath.GetHashCode)|Get the hash code of this object.|
|[`LengthSquared()`](VRageMath.LengthSquared)|Calculates the length squared of a QuaternionD.|
|[`Length()`](VRageMath.Length)|Calculates the length of a QuaternionD.|
|[`Normalize()`](VRageMath.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[`GetAxisAngle(ref Vector3D, ref double)`](VRageMath.GetAxisAngle)||
|[`Normalize(QuaternionD)`](VRageMath.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[`Normalize(ref QuaternionD, ref QuaternionD)`](VRageMath.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[`Conjugate()`](VRageMath.Conjugate)|Transforms this QuaternionD into its conjugate.|
|[`Conjugate(QuaternionD)`](VRageMath.Conjugate)|Returns the conjugate of a specified QuaternionD.|
|[`Conjugate(ref QuaternionD, ref QuaternionD)`](VRageMath.Conjugate)|Returns the conjugate of a specified QuaternionD.|
|[`Inverse(QuaternionD)`](VRageMath.Inverse)|Returns the inverse of a QuaternionD.|
|[`Inverse(ref QuaternionD, ref QuaternionD)`](VRageMath.Inverse)|Returns the inverse of a QuaternionD.|
|[`CreateFromAxisAngle(Vector3D, double)`](VRageMath.CreateFromAxisAngle)|Creates a QuaternionD from a vector and an angle to rotate about the vector.|
|[`CreateFromAxisAngle(ref Vector3D, double, ref QuaternionD)`](VRageMath.CreateFromAxisAngle)|Creates a QuaternionD from a vector and an angle to rotate about the vector.|
|[`CreateFromYawPitchRoll(double, double, double)`](VRageMath.CreateFromYawPitchRoll)|Creates a new QuaternionD from specified yaw, pitch, and roll angles.|
|[`CreateFromYawPitchRoll(double, double, double, ref QuaternionD)`](VRageMath.CreateFromYawPitchRoll)|Creates a new QuaternionD from specified yaw, pitch, and roll angles.|
|[`CreateFromForwardUp(Vector3D, Vector3D)`](VRageMath.CreateFromForwardUp)|Works for normalized vectors only|
|[`CreateFromRotationMatrix(MatrixD)`](VRageMath.CreateFromRotationMatrix)|Creates a QuaternionD from a rotation MatrixD.|
|[`CreateFromRotationMatrix(ref MatrixD, ref QuaternionD)`](VRageMath.CreateFromRotationMatrix)|Creates a QuaternionD from a rotation MatrixD.|
|[`Dot(QuaternionD, QuaternionD)`](VRageMath.Dot)|Calculates the dot product of two Quaternions.|
|[`Dot(ref QuaternionD, ref QuaternionD, ref double)`](VRageMath.Dot)|Calculates the dot product of two Quaternions.|
|[`Slerp(QuaternionD, QuaternionD, double)`](VRageMath.Slerp)|Interpolates between two quaternions, using spherical linear interpolation.|
|[`Slerp(ref QuaternionD, ref QuaternionD, double, ref QuaternionD)`](VRageMath.Slerp)|Interpolates between two quaternions, using spherical linear interpolation.|
|[`Lerp(QuaternionD, QuaternionD, double)`](VRageMath.Lerp)|Linearly interpolates between two quaternions.|
|[`Lerp(ref QuaternionD, ref QuaternionD, double, ref QuaternionD)`](VRageMath.Lerp)|Linearly interpolates between two quaternions.|
|[`Concatenate(QuaternionD, QuaternionD)`](VRageMath.Concatenate)|Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.|
|[`Concatenate(ref QuaternionD, ref QuaternionD, ref QuaternionD)`](VRageMath.Concatenate)|Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.|
|[`Negate(QuaternionD)`](VRageMath.Negate)|Flips the sign of each component of the quaternion.|
|[`Negate(ref QuaternionD, ref QuaternionD)`](VRageMath.Negate)|Flips the sign of each component of the quaternion.|
|[`Add(QuaternionD, QuaternionD)`](VRageMath.Add)|Adds two Quaternions.|
|[`Add(ref QuaternionD, ref QuaternionD, ref QuaternionD)`](VRageMath.Add)|Adds two Quaternions.|
|[`Subtract(QuaternionD, QuaternionD)`](VRageMath.Subtract)|Subtracts a quaternion from another quaternion.|
|[`Subtract(ref QuaternionD, ref QuaternionD, ref QuaternionD)`](VRageMath.Subtract)|Subtracts a quaternion from another quaternion.|
|[`Multiply(QuaternionD, QuaternionD)`](VRageMath.Multiply)|Multiplies two quaternions.|
|[`Multiply(ref QuaternionD, ref QuaternionD, ref QuaternionD)`](VRageMath.Multiply)|Multiplies two quaternions.|
|[`Multiply(QuaternionD, double)`](VRageMath.Multiply)|Multiplies a quaternion by a scalar value.|
|[`Multiply(ref QuaternionD, double, ref QuaternionD)`](VRageMath.Multiply)|Multiplies a quaternion by a scalar value.|
|[`Divide(QuaternionD, QuaternionD)`](VRageMath.Divide)|Divides a QuaternionD by another QuaternionD.|
|[`Divide(ref QuaternionD, ref QuaternionD, ref QuaternionD)`](VRageMath.Divide)|Divides a QuaternionD by another QuaternionD.|
|[`FromVector4(Vector4D)`](VRageMath.FromVector4)||
|[`ToVector4()`](VRageMath.ToVector4)||
|[`IsZero(QuaternionD)`](VRageMath.IsZero)||
|[`IsZero(QuaternionD, double)`](VRageMath.IsZero)||
|[`CreateFromTwoVectors(ref Vector3D, ref Vector3D, ref QuaternionD)`](VRageMath.CreateFromTwoVectors)||
|[`CreateFromTwoVectors(Vector3D, Vector3D)`](VRageMath.CreateFromTwoVectors)||
