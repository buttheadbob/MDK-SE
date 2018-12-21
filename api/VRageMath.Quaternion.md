← [Index](index)
# Quaternion Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a four-dimensional vector (x,y,z,w), which is used to efficiently rotate an object about the (x, y, z) vector by the angle theta, where w = cos(theta/2).
### Fields
|Member|Description|
|---|---|
|[`float&nbsp;X`](VRageMath.X)|Specifies the x-value of the vector component of the quaternion.|
|[`float&nbsp;Y`](VRageMath.Y)|Specifies the y-value of the vector component of the quaternion.|
|[`float&nbsp;Z`](VRageMath.Z)|Specifies the z-value of the vector component of the quaternion.|
|[`float&nbsp;W`](VRageMath.W)|Specifies the rotation component of the quaternion.|
|static&nbsp;[`Quaternion&nbsp;Identity`](VRageMath.Identity)||
|static&nbsp;[`Quaternion&nbsp;Zero`](VRageMath.Zero)||
### Properties
|Member|Description|
|---|---|
|[`Vector3&nbsp;Forward`](VRageMath.Forward)||
|[`Vector3&nbsp;Right`](VRageMath.Right)||
|[`Vector3&nbsp;Up`](VRageMath.Up)||
### Methods
|Member|Description|
|---|---|
|[`string&nbsp;ToString()`](VRageMath.ToString)|Retireves a string representation of the current object.|
|[`string&nbsp;ToString(string&nbsp;format)`](VRageMath.ToString)||
|[`string&nbsp;ToStringAxisAngle(string&nbsp;format)`](VRageMath.ToStringAxisAngle)||
|[`bool&nbsp;Equals(Quaternion&nbsp;other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Quaternion.|
|[`bool&nbsp;Equals(Quaternion&nbsp;value,&nbsp;float&nbsp;epsilon)`](VRageMath.Equals)||
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)|Get the hash code of this object.|
|[`float&nbsp;LengthSquared()`](VRageMath.LengthSquared)|Calculates the length squared of a Quaternion.|
|[`float&nbsp;Length()`](VRageMath.Length)|Calculates the length of a Quaternion.|
|[`void&nbsp;Normalize()`](VRageMath.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[`void&nbsp;GetAxisAngle(ref&nbsp;Vector3&nbsp;axis,&nbsp;ref&nbsp;float&nbsp;angle)`](VRageMath.GetAxisAngle)||
|static&nbsp;[`Quaternion&nbsp;Normalize(Quaternion&nbsp;quaternion)`](VRageMath.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|static&nbsp;[`void&nbsp;Normalize(ref&nbsp;Quaternion&nbsp;quaternion,&nbsp;ref&nbsp;Quaternion&nbsp;result)`](VRageMath.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[`void&nbsp;Conjugate()`](VRageMath.Conjugate)|Transforms this Quaternion into its conjugate.|
|static&nbsp;[`Quaternion&nbsp;Conjugate(Quaternion&nbsp;value)`](VRageMath.Conjugate)|Returns the conjugate of a specified Quaternion.|
|static&nbsp;[`void&nbsp;Conjugate(ref&nbsp;Quaternion&nbsp;value,&nbsp;ref&nbsp;Quaternion&nbsp;result)`](VRageMath.Conjugate)|Returns the conjugate of a specified Quaternion.|
|static&nbsp;[`Quaternion&nbsp;Inverse(Quaternion&nbsp;quaternion)`](VRageMath.Inverse)|Returns the inverse of a Quaternion.|
|static&nbsp;[`void&nbsp;Inverse(ref&nbsp;Quaternion&nbsp;quaternion,&nbsp;ref&nbsp;Quaternion&nbsp;result)`](VRageMath.Inverse)|Returns the inverse of a Quaternion.|
|static&nbsp;[`Quaternion&nbsp;CreateFromAxisAngle(Vector3&nbsp;axis,&nbsp;float&nbsp;angle)`](VRageMath.CreateFromAxisAngle)|Creates a Quaternion from a vector and an angle to rotate about the vector.|
|static&nbsp;[`void&nbsp;CreateFromAxisAngle(ref&nbsp;Vector3&nbsp;axis,&nbsp;float&nbsp;angle,&nbsp;ref&nbsp;Quaternion&nbsp;result)`](VRageMath.CreateFromAxisAngle)|Creates a Quaternion from a vector and an angle to rotate about the vector.|
|static&nbsp;[`Quaternion&nbsp;CreateFromYawPitchRoll(float&nbsp;yaw,&nbsp;float&nbsp;pitch,&nbsp;float&nbsp;roll)`](VRageMath.CreateFromYawPitchRoll)|Creates a new Quaternion from specified yaw, pitch, and roll angles.|
|static&nbsp;[`void&nbsp;CreateFromYawPitchRoll(float&nbsp;yaw,&nbsp;float&nbsp;pitch,&nbsp;float&nbsp;roll,&nbsp;ref&nbsp;Quaternion&nbsp;result)`](VRageMath.CreateFromYawPitchRoll)|Creates a new Quaternion from specified yaw, pitch, and roll angles.|
|static&nbsp;[`Quaternion&nbsp;CreateFromForwardUp(Vector3&nbsp;forward,&nbsp;Vector3&nbsp;up)`](VRageMath.CreateFromForwardUp)|Works for normalized vectors only|
|static&nbsp;[`Quaternion&nbsp;CreateFromRotationMatrix(MatrixD&nbsp;matrix)`](VRageMath.CreateFromRotationMatrix)||
|static&nbsp;[`Quaternion&nbsp;CreateFromRotationMatrix(Matrix&nbsp;matrix)`](VRageMath.CreateFromRotationMatrix)|Creates a Quaternion from a rotation Matrix.|
|static&nbsp;[`void&nbsp;CreateFromRotationMatrix(ref&nbsp;MatrixD&nbsp;matrix,&nbsp;ref&nbsp;Quaternion&nbsp;result)`](VRageMath.CreateFromRotationMatrix)||
|static&nbsp;[`void&nbsp;CreateFromTwoVectors(ref&nbsp;Vector3&nbsp;firstVector,&nbsp;ref&nbsp;Vector3&nbsp;secondVector,&nbsp;ref&nbsp;Quaternion&nbsp;result)`](VRageMath.CreateFromTwoVectors)||
|static&nbsp;[`Quaternion&nbsp;CreateFromTwoVectors(Vector3&nbsp;firstVector,&nbsp;Vector3&nbsp;secondVector)`](VRageMath.CreateFromTwoVectors)||
|static&nbsp;[`void&nbsp;CreateFromRotationMatrix(ref&nbsp;Matrix&nbsp;matrix,&nbsp;ref&nbsp;Quaternion&nbsp;result)`](VRageMath.CreateFromRotationMatrix)|Creates a Quaternion from a rotation Matrix.|
|static&nbsp;[`void&nbsp;CreateFromRotationMatrix(ref&nbsp;Matrix3x3&nbsp;matrix,&nbsp;ref&nbsp;Quaternion&nbsp;result)`](VRageMath.CreateFromRotationMatrix)|Creates a Quaternion from a rotation Matrix.|
|static&nbsp;[`float&nbsp;Dot(Quaternion&nbsp;quaternion1,&nbsp;Quaternion&nbsp;quaternion2)`](VRageMath.Dot)|Calculates the dot product of two Quaternions.|
|static&nbsp;[`void&nbsp;Dot(ref&nbsp;Quaternion&nbsp;quaternion1,&nbsp;ref&nbsp;Quaternion&nbsp;quaternion2,&nbsp;ref&nbsp;float&nbsp;result)`](VRageMath.Dot)|Calculates the dot product of two Quaternions.|
|static&nbsp;[`Quaternion&nbsp;Slerp(Quaternion&nbsp;quaternion1,&nbsp;Quaternion&nbsp;quaternion2,&nbsp;float&nbsp;amount)`](VRageMath.Slerp)|Interpolates between two quaternions, using spherical linear interpolation.|
|static&nbsp;[`void&nbsp;Slerp(ref&nbsp;Quaternion&nbsp;quaternion1,&nbsp;ref&nbsp;Quaternion&nbsp;quaternion2,&nbsp;float&nbsp;amount,&nbsp;ref&nbsp;Quaternion&nbsp;result)`](VRageMath.Slerp)|Interpolates between two quaternions, using spherical linear interpolation.|
|static&nbsp;[`Quaternion&nbsp;Lerp(Quaternion&nbsp;quaternion1,&nbsp;Quaternion&nbsp;quaternion2,&nbsp;float&nbsp;amount)`](VRageMath.Lerp)|Linearly interpolates between two quaternions.|
|static&nbsp;[`void&nbsp;Lerp(ref&nbsp;Quaternion&nbsp;quaternion1,&nbsp;ref&nbsp;Quaternion&nbsp;quaternion2,&nbsp;float&nbsp;amount,&nbsp;ref&nbsp;Quaternion&nbsp;result)`](VRageMath.Lerp)|Linearly interpolates between two quaternions.|
|static&nbsp;[`Quaternion&nbsp;Concatenate(Quaternion&nbsp;value1,&nbsp;Quaternion&nbsp;value2)`](VRageMath.Concatenate)|Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.|
|static&nbsp;[`void&nbsp;Concatenate(ref&nbsp;Quaternion&nbsp;value1,&nbsp;ref&nbsp;Quaternion&nbsp;value2,&nbsp;ref&nbsp;Quaternion&nbsp;result)`](VRageMath.Concatenate)|Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.|
|static&nbsp;[`Quaternion&nbsp;Negate(Quaternion&nbsp;quaternion)`](VRageMath.Negate)|Flips the sign of each component of the quaternion.|
|static&nbsp;[`void&nbsp;Negate(ref&nbsp;Quaternion&nbsp;quaternion,&nbsp;ref&nbsp;Quaternion&nbsp;result)`](VRageMath.Negate)|Flips the sign of each component of the quaternion.|
|static&nbsp;[`Quaternion&nbsp;Add(Quaternion&nbsp;quaternion1,&nbsp;Quaternion&nbsp;quaternion2)`](VRageMath.Add)|Adds two Quaternions.|
|static&nbsp;[`void&nbsp;Add(ref&nbsp;Quaternion&nbsp;quaternion1,&nbsp;ref&nbsp;Quaternion&nbsp;quaternion2,&nbsp;ref&nbsp;Quaternion&nbsp;result)`](VRageMath.Add)|Adds two Quaternions.|
|static&nbsp;[`Quaternion&nbsp;Subtract(Quaternion&nbsp;quaternion1,&nbsp;Quaternion&nbsp;quaternion2)`](VRageMath.Subtract)|Subtracts a quaternion from another quaternion.|
|static&nbsp;[`void&nbsp;Subtract(ref&nbsp;Quaternion&nbsp;quaternion1,&nbsp;ref&nbsp;Quaternion&nbsp;quaternion2,&nbsp;ref&nbsp;Quaternion&nbsp;result)`](VRageMath.Subtract)|Subtracts a quaternion from another quaternion.|
|static&nbsp;[`Quaternion&nbsp;Multiply(Quaternion&nbsp;quaternion1,&nbsp;Quaternion&nbsp;quaternion2)`](VRageMath.Multiply)|Multiplies two quaternions.|
|static&nbsp;[`void&nbsp;Multiply(ref&nbsp;Quaternion&nbsp;quaternion1,&nbsp;ref&nbsp;Quaternion&nbsp;quaternion2,&nbsp;ref&nbsp;Quaternion&nbsp;result)`](VRageMath.Multiply)|Multiplies two quaternions.|
|static&nbsp;[`Quaternion&nbsp;Multiply(Quaternion&nbsp;quaternion1,&nbsp;float&nbsp;scaleFactor)`](VRageMath.Multiply)|Multiplies a quaternion by a scalar value.|
|static&nbsp;[`void&nbsp;Multiply(ref&nbsp;Quaternion&nbsp;quaternion1,&nbsp;float&nbsp;scaleFactor,&nbsp;ref&nbsp;Quaternion&nbsp;result)`](VRageMath.Multiply)|Multiplies a quaternion by a scalar value.|
|static&nbsp;[`Quaternion&nbsp;Divide(Quaternion&nbsp;quaternion1,&nbsp;Quaternion&nbsp;quaternion2)`](VRageMath.Divide)|Divides a Quaternion by another Quaternion.|
|static&nbsp;[`void&nbsp;Divide(ref&nbsp;Quaternion&nbsp;quaternion1,&nbsp;ref&nbsp;Quaternion&nbsp;quaternion2,&nbsp;ref&nbsp;Quaternion&nbsp;result)`](VRageMath.Divide)|Divides a Quaternion by another Quaternion.|
|static&nbsp;[`Quaternion&nbsp;FromVector4(Vector4&nbsp;v)`](VRageMath.FromVector4)||
|[`Vector4&nbsp;ToVector4()`](VRageMath.ToVector4)||
|static&nbsp;[`bool&nbsp;IsZero(Quaternion&nbsp;value)`](VRageMath.IsZero)||
|static&nbsp;[`bool&nbsp;IsZero(Quaternion&nbsp;value,&nbsp;float&nbsp;epsilon)`](VRageMath.IsZero)||
|static&nbsp;[`void&nbsp;GetForward(ref&nbsp;Quaternion&nbsp;q,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.GetForward)|Gets forward vector (0,0,-1) transformed by quaternion.|
|static&nbsp;[`void&nbsp;GetRight(ref&nbsp;Quaternion&nbsp;q,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.GetRight)|Gets right vector (1,0,0) transformed by quaternion.|
|static&nbsp;[`void&nbsp;GetUp(ref&nbsp;Quaternion&nbsp;q,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.GetUp)|Gets up vector (0,1,0) transformed by quaternion.|
|[`float&nbsp;GetComponent(int&nbsp;index)`](VRageMath.GetComponent)||
|[`void&nbsp;SetComponent(int&nbsp;index,&nbsp;float&nbsp;value)`](VRageMath.SetComponent)||
|[`int&nbsp;FindLargestIndex()`](VRageMath.FindLargestIndex)||
