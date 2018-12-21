← [Index](index)
# Quaternion Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a four-dimensional vector (x,y,z,w), which is used to efficiently rotate an object about the (x, y, z) vector by the angle theta, where w = cos(theta/2).
### Fields
|Member|Description|
|---|---|
|[`X`](VRageMath.X)|Specifies the x-value of the vector component of the quaternion.|
|[`Y`](VRageMath.Y)|Specifies the y-value of the vector component of the quaternion.|
|[`Z`](VRageMath.Z)|Specifies the z-value of the vector component of the quaternion.|
|[`W`](VRageMath.W)|Specifies the rotation component of the quaternion.|
|static [`Identity`](VRageMath.Identity)||
|static [`Zero`](VRageMath.Zero)||
### Properties
|Member|Description|
|---|---|
|[`Forward`](VRageMath.Forward)||
|[`Right`](VRageMath.Right)||
|[`Up`](VRageMath.Up)||
### Methods
|Member|Description|
|---|---|
|[`ToString()`](VRageMath.ToString)|Retireves a string representation of the current object.|
|[`ToString(string)`](VRageMath.ToString)||
|[`ToStringAxisAngle(string)`](VRageMath.ToStringAxisAngle)||
|[`Equals(Quaternion)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Quaternion.|
|[`Equals(Quaternion, float)`](VRageMath.Equals)||
|[`Equals(Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`GetHashCode()`](VRageMath.GetHashCode)|Get the hash code of this object.|
|[`LengthSquared()`](VRageMath.LengthSquared)|Calculates the length squared of a Quaternion.|
|[`Length()`](VRageMath.Length)|Calculates the length of a Quaternion.|
|[`Normalize()`](VRageMath.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[`GetAxisAngle(ref Vector3, ref float)`](VRageMath.GetAxisAngle)||
|static [`Normalize(Quaternion)`](VRageMath.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|static [`Normalize(ref Quaternion, ref Quaternion)`](VRageMath.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[`Conjugate()`](VRageMath.Conjugate)|Transforms this Quaternion into its conjugate.|
|static [`Conjugate(Quaternion)`](VRageMath.Conjugate)|Returns the conjugate of a specified Quaternion.|
|static [`Conjugate(ref Quaternion, ref Quaternion)`](VRageMath.Conjugate)|Returns the conjugate of a specified Quaternion.|
|static [`Inverse(Quaternion)`](VRageMath.Inverse)|Returns the inverse of a Quaternion.|
|static [`Inverse(ref Quaternion, ref Quaternion)`](VRageMath.Inverse)|Returns the inverse of a Quaternion.|
|static [`CreateFromAxisAngle(Vector3, float)`](VRageMath.CreateFromAxisAngle)|Creates a Quaternion from a vector and an angle to rotate about the vector.|
|static [`CreateFromAxisAngle(ref Vector3, float, ref Quaternion)`](VRageMath.CreateFromAxisAngle)|Creates a Quaternion from a vector and an angle to rotate about the vector.|
|static [`CreateFromYawPitchRoll(float, float, float)`](VRageMath.CreateFromYawPitchRoll)|Creates a new Quaternion from specified yaw, pitch, and roll angles.|
|static [`CreateFromYawPitchRoll(float, float, float, ref Quaternion)`](VRageMath.CreateFromYawPitchRoll)|Creates a new Quaternion from specified yaw, pitch, and roll angles.|
|static [`CreateFromForwardUp(Vector3, Vector3)`](VRageMath.CreateFromForwardUp)|Works for normalized vectors only|
|static [`CreateFromRotationMatrix(MatrixD)`](VRageMath.CreateFromRotationMatrix)||
|static [`CreateFromRotationMatrix(Matrix)`](VRageMath.CreateFromRotationMatrix)|Creates a Quaternion from a rotation Matrix.|
|static [`CreateFromRotationMatrix(ref MatrixD, ref Quaternion)`](VRageMath.CreateFromRotationMatrix)||
|static [`CreateFromTwoVectors(ref Vector3, ref Vector3, ref Quaternion)`](VRageMath.CreateFromTwoVectors)||
|static [`CreateFromTwoVectors(Vector3, Vector3)`](VRageMath.CreateFromTwoVectors)||
|static [`CreateFromRotationMatrix(ref Matrix, ref Quaternion)`](VRageMath.CreateFromRotationMatrix)|Creates a Quaternion from a rotation Matrix.|
|static [`CreateFromRotationMatrix(ref Matrix3x3, ref Quaternion)`](VRageMath.CreateFromRotationMatrix)|Creates a Quaternion from a rotation Matrix.|
|static [`Dot(Quaternion, Quaternion)`](VRageMath.Dot)|Calculates the dot product of two Quaternions.|
|static [`Dot(ref Quaternion, ref Quaternion, ref float)`](VRageMath.Dot)|Calculates the dot product of two Quaternions.|
|static [`Slerp(Quaternion, Quaternion, float)`](VRageMath.Slerp)|Interpolates between two quaternions, using spherical linear interpolation.|
|static [`Slerp(ref Quaternion, ref Quaternion, float, ref Quaternion)`](VRageMath.Slerp)|Interpolates between two quaternions, using spherical linear interpolation.|
|static [`Lerp(Quaternion, Quaternion, float)`](VRageMath.Lerp)|Linearly interpolates between two quaternions.|
|static [`Lerp(ref Quaternion, ref Quaternion, float, ref Quaternion)`](VRageMath.Lerp)|Linearly interpolates between two quaternions.|
|static [`Concatenate(Quaternion, Quaternion)`](VRageMath.Concatenate)|Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.|
|static [`Concatenate(ref Quaternion, ref Quaternion, ref Quaternion)`](VRageMath.Concatenate)|Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.|
|static [`Negate(Quaternion)`](VRageMath.Negate)|Flips the sign of each component of the quaternion.|
|static [`Negate(ref Quaternion, ref Quaternion)`](VRageMath.Negate)|Flips the sign of each component of the quaternion.|
|static [`Add(Quaternion, Quaternion)`](VRageMath.Add)|Adds two Quaternions.|
|static [`Add(ref Quaternion, ref Quaternion, ref Quaternion)`](VRageMath.Add)|Adds two Quaternions.|
|static [`Subtract(Quaternion, Quaternion)`](VRageMath.Subtract)|Subtracts a quaternion from another quaternion.|
|static [`Subtract(ref Quaternion, ref Quaternion, ref Quaternion)`](VRageMath.Subtract)|Subtracts a quaternion from another quaternion.|
|static [`Multiply(Quaternion, Quaternion)`](VRageMath.Multiply)|Multiplies two quaternions.|
|static [`Multiply(ref Quaternion, ref Quaternion, ref Quaternion)`](VRageMath.Multiply)|Multiplies two quaternions.|
|static [`Multiply(Quaternion, float)`](VRageMath.Multiply)|Multiplies a quaternion by a scalar value.|
|static [`Multiply(ref Quaternion, float, ref Quaternion)`](VRageMath.Multiply)|Multiplies a quaternion by a scalar value.|
|static [`Divide(Quaternion, Quaternion)`](VRageMath.Divide)|Divides a Quaternion by another Quaternion.|
|static [`Divide(ref Quaternion, ref Quaternion, ref Quaternion)`](VRageMath.Divide)|Divides a Quaternion by another Quaternion.|
|static [`FromVector4(Vector4)`](VRageMath.FromVector4)||
|[`ToVector4()`](VRageMath.ToVector4)||
|static [`IsZero(Quaternion)`](VRageMath.IsZero)||
|static [`IsZero(Quaternion, float)`](VRageMath.IsZero)||
|static [`GetForward(ref Quaternion, ref Vector3)`](VRageMath.GetForward)|Gets forward vector (0,0,-1) transformed by quaternion.|
|static [`GetRight(ref Quaternion, ref Vector3)`](VRageMath.GetRight)|Gets right vector (1,0,0) transformed by quaternion.|
|static [`GetUp(ref Quaternion, ref Vector3)`](VRageMath.GetUp)|Gets up vector (0,1,0) transformed by quaternion.|
|[`GetComponent(int)`](VRageMath.GetComponent)||
|[`SetComponent(int, float)`](VRageMath.SetComponent)||
|[`FindLargestIndex()`](VRageMath.FindLargestIndex)||
