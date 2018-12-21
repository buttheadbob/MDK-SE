← [Index](index)
# QuaternionD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a four-dimensional vector (x,y,z,w), which is used to efficiently rotate an object about the (x, y, z) vector by the angle theta, where w = cos(theta/2). Uses double precision floating point numbers for calculation and storage
### Fields
|Member|Description|
|---|---|
|[`double&nbsp;X`](VRageMath.X)|Specifies the x-value of the vector component of the quaternion.|
|[`double&nbsp;Y`](VRageMath.Y)|Specifies the y-value of the vector component of the quaternion.|
|[`double&nbsp;Z`](VRageMath.Z)|Specifies the z-value of the vector component of the quaternion.|
|[`double&nbsp;W`](VRageMath.W)|Specifies the rotation component of the quaternion.|
|static&nbsp;[`QuaternionD&nbsp;Identity`](VRageMath.Identity)||
### Methods
|Member|Description|
|---|---|
|[`string&nbsp;ToString()`](VRageMath.ToString)|Retireves a string representation of the current object.|
|[`bool&nbsp;Equals(QuaternionD&nbsp;other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the QuaternionD.|
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)|Get the hash code of this object.|
|[`double&nbsp;LengthSquared()`](VRageMath.LengthSquared)|Calculates the length squared of a QuaternionD.|
|[`double&nbsp;Length()`](VRageMath.Length)|Calculates the length of a QuaternionD.|
|[`void&nbsp;Normalize()`](VRageMath.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[`void&nbsp;GetAxisAngle(ref&nbsp;Vector3D&nbsp;axis,&nbsp;ref&nbsp;double&nbsp;angle)`](VRageMath.GetAxisAngle)||
|static&nbsp;[`QuaternionD&nbsp;Normalize(QuaternionD&nbsp;quaternion)`](VRageMath.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|static&nbsp;[`void&nbsp;Normalize(ref&nbsp;QuaternionD&nbsp;quaternion,&nbsp;ref&nbsp;QuaternionD&nbsp;result)`](VRageMath.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[`void&nbsp;Conjugate()`](VRageMath.Conjugate)|Transforms this QuaternionD into its conjugate.|
|static&nbsp;[`QuaternionD&nbsp;Conjugate(QuaternionD&nbsp;value)`](VRageMath.Conjugate)|Returns the conjugate of a specified QuaternionD.|
|static&nbsp;[`void&nbsp;Conjugate(ref&nbsp;QuaternionD&nbsp;value,&nbsp;ref&nbsp;QuaternionD&nbsp;result)`](VRageMath.Conjugate)|Returns the conjugate of a specified QuaternionD.|
|static&nbsp;[`QuaternionD&nbsp;Inverse(QuaternionD&nbsp;quaternion)`](VRageMath.Inverse)|Returns the inverse of a QuaternionD.|
|static&nbsp;[`void&nbsp;Inverse(ref&nbsp;QuaternionD&nbsp;quaternion,&nbsp;ref&nbsp;QuaternionD&nbsp;result)`](VRageMath.Inverse)|Returns the inverse of a QuaternionD.|
|static&nbsp;[`QuaternionD&nbsp;CreateFromAxisAngle(Vector3D&nbsp;axis,&nbsp;double&nbsp;angle)`](VRageMath.CreateFromAxisAngle)|Creates a QuaternionD from a vector and an angle to rotate about the vector.|
|static&nbsp;[`void&nbsp;CreateFromAxisAngle(ref&nbsp;Vector3D&nbsp;axis,&nbsp;double&nbsp;angle,&nbsp;ref&nbsp;QuaternionD&nbsp;result)`](VRageMath.CreateFromAxisAngle)|Creates a QuaternionD from a vector and an angle to rotate about the vector.|
|static&nbsp;[`QuaternionD&nbsp;CreateFromYawPitchRoll(double&nbsp;yaw,&nbsp;double&nbsp;pitch,&nbsp;double&nbsp;roll)`](VRageMath.CreateFromYawPitchRoll)|Creates a new QuaternionD from specified yaw, pitch, and roll angles.|
|static&nbsp;[`void&nbsp;CreateFromYawPitchRoll(double&nbsp;yaw,&nbsp;double&nbsp;pitch,&nbsp;double&nbsp;roll,&nbsp;ref&nbsp;QuaternionD&nbsp;result)`](VRageMath.CreateFromYawPitchRoll)|Creates a new QuaternionD from specified yaw, pitch, and roll angles.|
|static&nbsp;[`QuaternionD&nbsp;CreateFromForwardUp(Vector3D&nbsp;forward,&nbsp;Vector3D&nbsp;up)`](VRageMath.CreateFromForwardUp)|Works for normalized vectors only|
|static&nbsp;[`QuaternionD&nbsp;CreateFromRotationMatrix(MatrixD&nbsp;matrix)`](VRageMath.CreateFromRotationMatrix)|Creates a QuaternionD from a rotation MatrixD.|
|static&nbsp;[`void&nbsp;CreateFromRotationMatrix(ref&nbsp;MatrixD&nbsp;matrix,&nbsp;ref&nbsp;QuaternionD&nbsp;result)`](VRageMath.CreateFromRotationMatrix)|Creates a QuaternionD from a rotation MatrixD.|
|static&nbsp;[`double&nbsp;Dot(QuaternionD&nbsp;quaternion1,&nbsp;QuaternionD&nbsp;quaternion2)`](VRageMath.Dot)|Calculates the dot product of two Quaternions.|
|static&nbsp;[`void&nbsp;Dot(ref&nbsp;QuaternionD&nbsp;quaternion1,&nbsp;ref&nbsp;QuaternionD&nbsp;quaternion2,&nbsp;ref&nbsp;double&nbsp;result)`](VRageMath.Dot)|Calculates the dot product of two Quaternions.|
|static&nbsp;[`QuaternionD&nbsp;Slerp(QuaternionD&nbsp;quaternion1,&nbsp;QuaternionD&nbsp;quaternion2,&nbsp;double&nbsp;amount)`](VRageMath.Slerp)|Interpolates between two quaternions, using spherical linear interpolation.|
|static&nbsp;[`void&nbsp;Slerp(ref&nbsp;QuaternionD&nbsp;quaternion1,&nbsp;ref&nbsp;QuaternionD&nbsp;quaternion2,&nbsp;double&nbsp;amount,&nbsp;ref&nbsp;QuaternionD&nbsp;result)`](VRageMath.Slerp)|Interpolates between two quaternions, using spherical linear interpolation.|
|static&nbsp;[`QuaternionD&nbsp;Lerp(QuaternionD&nbsp;quaternion1,&nbsp;QuaternionD&nbsp;quaternion2,&nbsp;double&nbsp;amount)`](VRageMath.Lerp)|Linearly interpolates between two quaternions.|
|static&nbsp;[`void&nbsp;Lerp(ref&nbsp;QuaternionD&nbsp;quaternion1,&nbsp;ref&nbsp;QuaternionD&nbsp;quaternion2,&nbsp;double&nbsp;amount,&nbsp;ref&nbsp;QuaternionD&nbsp;result)`](VRageMath.Lerp)|Linearly interpolates between two quaternions.|
|static&nbsp;[`QuaternionD&nbsp;Concatenate(QuaternionD&nbsp;value1,&nbsp;QuaternionD&nbsp;value2)`](VRageMath.Concatenate)|Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.|
|static&nbsp;[`void&nbsp;Concatenate(ref&nbsp;QuaternionD&nbsp;value1,&nbsp;ref&nbsp;QuaternionD&nbsp;value2,&nbsp;ref&nbsp;QuaternionD&nbsp;result)`](VRageMath.Concatenate)|Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.|
|static&nbsp;[`QuaternionD&nbsp;Negate(QuaternionD&nbsp;quaternion)`](VRageMath.Negate)|Flips the sign of each component of the quaternion.|
|static&nbsp;[`void&nbsp;Negate(ref&nbsp;QuaternionD&nbsp;quaternion,&nbsp;ref&nbsp;QuaternionD&nbsp;result)`](VRageMath.Negate)|Flips the sign of each component of the quaternion.|
|static&nbsp;[`QuaternionD&nbsp;Add(QuaternionD&nbsp;quaternion1,&nbsp;QuaternionD&nbsp;quaternion2)`](VRageMath.Add)|Adds two Quaternions.|
|static&nbsp;[`void&nbsp;Add(ref&nbsp;QuaternionD&nbsp;quaternion1,&nbsp;ref&nbsp;QuaternionD&nbsp;quaternion2,&nbsp;ref&nbsp;QuaternionD&nbsp;result)`](VRageMath.Add)|Adds two Quaternions.|
|static&nbsp;[`QuaternionD&nbsp;Subtract(QuaternionD&nbsp;quaternion1,&nbsp;QuaternionD&nbsp;quaternion2)`](VRageMath.Subtract)|Subtracts a quaternion from another quaternion.|
|static&nbsp;[`void&nbsp;Subtract(ref&nbsp;QuaternionD&nbsp;quaternion1,&nbsp;ref&nbsp;QuaternionD&nbsp;quaternion2,&nbsp;ref&nbsp;QuaternionD&nbsp;result)`](VRageMath.Subtract)|Subtracts a quaternion from another quaternion.|
|static&nbsp;[`QuaternionD&nbsp;Multiply(QuaternionD&nbsp;quaternion1,&nbsp;QuaternionD&nbsp;quaternion2)`](VRageMath.Multiply)|Multiplies two quaternions.|
|static&nbsp;[`void&nbsp;Multiply(ref&nbsp;QuaternionD&nbsp;quaternion1,&nbsp;ref&nbsp;QuaternionD&nbsp;quaternion2,&nbsp;ref&nbsp;QuaternionD&nbsp;result)`](VRageMath.Multiply)|Multiplies two quaternions.|
|static&nbsp;[`QuaternionD&nbsp;Multiply(QuaternionD&nbsp;quaternion1,&nbsp;double&nbsp;scaleFactor)`](VRageMath.Multiply)|Multiplies a quaternion by a scalar value.|
|static&nbsp;[`void&nbsp;Multiply(ref&nbsp;QuaternionD&nbsp;quaternion1,&nbsp;double&nbsp;scaleFactor,&nbsp;ref&nbsp;QuaternionD&nbsp;result)`](VRageMath.Multiply)|Multiplies a quaternion by a scalar value.|
|static&nbsp;[`QuaternionD&nbsp;Divide(QuaternionD&nbsp;quaternion1,&nbsp;QuaternionD&nbsp;quaternion2)`](VRageMath.Divide)|Divides a QuaternionD by another QuaternionD.|
|static&nbsp;[`void&nbsp;Divide(ref&nbsp;QuaternionD&nbsp;quaternion1,&nbsp;ref&nbsp;QuaternionD&nbsp;quaternion2,&nbsp;ref&nbsp;QuaternionD&nbsp;result)`](VRageMath.Divide)|Divides a QuaternionD by another QuaternionD.|
|static&nbsp;[`QuaternionD&nbsp;FromVector4(Vector4D&nbsp;v)`](VRageMath.FromVector4)||
|[`Vector4D&nbsp;ToVector4()`](VRageMath.ToVector4)||
|static&nbsp;[`bool&nbsp;IsZero(QuaternionD&nbsp;value)`](VRageMath.IsZero)||
|static&nbsp;[`bool&nbsp;IsZero(QuaternionD&nbsp;value,&nbsp;double&nbsp;epsilon)`](VRageMath.IsZero)||
|static&nbsp;[`void&nbsp;CreateFromTwoVectors(ref&nbsp;Vector3D&nbsp;firstVector,&nbsp;ref&nbsp;Vector3D&nbsp;secondVector,&nbsp;ref&nbsp;QuaternionD&nbsp;result)`](VRageMath.CreateFromTwoVectors)||
|static&nbsp;[`QuaternionD&nbsp;CreateFromTwoVectors(Vector3D&nbsp;firstVector,&nbsp;Vector3D&nbsp;secondVector)`](VRageMath.CreateFromTwoVectors)||
