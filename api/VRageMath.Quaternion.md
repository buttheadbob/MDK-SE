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
|static [`VRageMath.Quaternion Identity`](VRageMath.Identity)||
|static [`VRageMath.Quaternion Zero`](VRageMath.Zero)||
### Properties
|Member|Description|
|---|---|
|[`VRageMath.Vector3 Forward`](VRageMath.Forward)||
|[`VRageMath.Vector3 Right`](VRageMath.Right)||
|[`VRageMath.Vector3 Up`](VRageMath.Up)||
### Methods
|Member|Description|
|---|---|
|[`string ToString()`](VRageMath.ToString)|Retireves a string representation of the current object.|
|[`string ToString(string)`](VRageMath.ToString)||
|[`string ToStringAxisAngle(string)`](VRageMath.ToStringAxisAngle)||
|[`bool Equals(VRageMath.Quaternion)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Quaternion.|
|[`bool Equals(VRageMath.Quaternion, float)`](VRageMath.Equals)||
|[`bool Equals(System.Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Get the hash code of this object.|
|[`float LengthSquared()`](VRageMath.LengthSquared)|Calculates the length squared of a Quaternion.|
|[`float Length()`](VRageMath.Length)|Calculates the length of a Quaternion.|
|[`void Normalize()`](VRageMath.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[`void GetAxisAngle(ref VRageMath.Vector3, ref float)`](VRageMath.GetAxisAngle)||
|static [`VRageMath.Quaternion Normalize(VRageMath.Quaternion)`](VRageMath.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|static [`void Normalize(ref VRageMath.Quaternion, ref VRageMath.Quaternion)`](VRageMath.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[`void Conjugate()`](VRageMath.Conjugate)|Transforms this Quaternion into its conjugate.|
|static [`VRageMath.Quaternion Conjugate(VRageMath.Quaternion)`](VRageMath.Conjugate)|Returns the conjugate of a specified Quaternion.|
|static [`void Conjugate(ref VRageMath.Quaternion, ref VRageMath.Quaternion)`](VRageMath.Conjugate)|Returns the conjugate of a specified Quaternion.|
|static [`VRageMath.Quaternion Inverse(VRageMath.Quaternion)`](VRageMath.Inverse)|Returns the inverse of a Quaternion.|
|static [`void Inverse(ref VRageMath.Quaternion, ref VRageMath.Quaternion)`](VRageMath.Inverse)|Returns the inverse of a Quaternion.|
|static [`VRageMath.Quaternion CreateFromAxisAngle(VRageMath.Vector3, float)`](VRageMath.CreateFromAxisAngle)|Creates a Quaternion from a vector and an angle to rotate about the vector.|
|static [`void CreateFromAxisAngle(ref VRageMath.Vector3, float, ref VRageMath.Quaternion)`](VRageMath.CreateFromAxisAngle)|Creates a Quaternion from a vector and an angle to rotate about the vector.|
|static [`VRageMath.Quaternion CreateFromYawPitchRoll(float, float, float)`](VRageMath.CreateFromYawPitchRoll)|Creates a new Quaternion from specified yaw, pitch, and roll angles.|
|static [`void CreateFromYawPitchRoll(float, float, float, ref VRageMath.Quaternion)`](VRageMath.CreateFromYawPitchRoll)|Creates a new Quaternion from specified yaw, pitch, and roll angles.|
|static [`VRageMath.Quaternion CreateFromForwardUp(VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.CreateFromForwardUp)|Works for normalized vectors only|
|static [`VRageMath.Quaternion CreateFromRotationMatrix(VRageMath.MatrixD)`](VRageMath.CreateFromRotationMatrix)||
|static [`VRageMath.Quaternion CreateFromRotationMatrix(VRageMath.Matrix)`](VRageMath.CreateFromRotationMatrix)|Creates a Quaternion from a rotation Matrix.|
|static [`void CreateFromRotationMatrix(ref VRageMath.MatrixD, ref VRageMath.Quaternion)`](VRageMath.CreateFromRotationMatrix)||
|static [`void CreateFromTwoVectors(ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Quaternion)`](VRageMath.CreateFromTwoVectors)||
|static [`VRageMath.Quaternion CreateFromTwoVectors(VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.CreateFromTwoVectors)||
|static [`void CreateFromRotationMatrix(ref VRageMath.Matrix, ref VRageMath.Quaternion)`](VRageMath.CreateFromRotationMatrix)|Creates a Quaternion from a rotation Matrix.|
|static [`void CreateFromRotationMatrix(ref VRageMath.Matrix3x3, ref VRageMath.Quaternion)`](VRageMath.CreateFromRotationMatrix)|Creates a Quaternion from a rotation Matrix.|
|static [`float Dot(VRageMath.Quaternion, VRageMath.Quaternion)`](VRageMath.Dot)|Calculates the dot product of two Quaternions.|
|static [`void Dot(ref VRageMath.Quaternion, ref VRageMath.Quaternion, ref float)`](VRageMath.Dot)|Calculates the dot product of two Quaternions.|
|static [`VRageMath.Quaternion Slerp(VRageMath.Quaternion, VRageMath.Quaternion, float)`](VRageMath.Slerp)|Interpolates between two quaternions, using spherical linear interpolation.|
|static [`void Slerp(ref VRageMath.Quaternion, ref VRageMath.Quaternion, float, ref VRageMath.Quaternion)`](VRageMath.Slerp)|Interpolates between two quaternions, using spherical linear interpolation.|
|static [`VRageMath.Quaternion Lerp(VRageMath.Quaternion, VRageMath.Quaternion, float)`](VRageMath.Lerp)|Linearly interpolates between two quaternions.|
|static [`void Lerp(ref VRageMath.Quaternion, ref VRageMath.Quaternion, float, ref VRageMath.Quaternion)`](VRageMath.Lerp)|Linearly interpolates between two quaternions.|
|static [`VRageMath.Quaternion Concatenate(VRageMath.Quaternion, VRageMath.Quaternion)`](VRageMath.Concatenate)|Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.|
|static [`void Concatenate(ref VRageMath.Quaternion, ref VRageMath.Quaternion, ref VRageMath.Quaternion)`](VRageMath.Concatenate)|Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.|
|static [`VRageMath.Quaternion Negate(VRageMath.Quaternion)`](VRageMath.Negate)|Flips the sign of each component of the quaternion.|
|static [`void Negate(ref VRageMath.Quaternion, ref VRageMath.Quaternion)`](VRageMath.Negate)|Flips the sign of each component of the quaternion.|
|static [`VRageMath.Quaternion Add(VRageMath.Quaternion, VRageMath.Quaternion)`](VRageMath.Add)|Adds two Quaternions.|
|static [`void Add(ref VRageMath.Quaternion, ref VRageMath.Quaternion, ref VRageMath.Quaternion)`](VRageMath.Add)|Adds two Quaternions.|
|static [`VRageMath.Quaternion Subtract(VRageMath.Quaternion, VRageMath.Quaternion)`](VRageMath.Subtract)|Subtracts a quaternion from another quaternion.|
|static [`void Subtract(ref VRageMath.Quaternion, ref VRageMath.Quaternion, ref VRageMath.Quaternion)`](VRageMath.Subtract)|Subtracts a quaternion from another quaternion.|
|static [`VRageMath.Quaternion Multiply(VRageMath.Quaternion, VRageMath.Quaternion)`](VRageMath.Multiply)|Multiplies two quaternions.|
|static [`void Multiply(ref VRageMath.Quaternion, ref VRageMath.Quaternion, ref VRageMath.Quaternion)`](VRageMath.Multiply)|Multiplies two quaternions.|
|static [`VRageMath.Quaternion Multiply(VRageMath.Quaternion, float)`](VRageMath.Multiply)|Multiplies a quaternion by a scalar value.|
|static [`void Multiply(ref VRageMath.Quaternion, float, ref VRageMath.Quaternion)`](VRageMath.Multiply)|Multiplies a quaternion by a scalar value.|
|static [`VRageMath.Quaternion Divide(VRageMath.Quaternion, VRageMath.Quaternion)`](VRageMath.Divide)|Divides a Quaternion by another Quaternion.|
|static [`void Divide(ref VRageMath.Quaternion, ref VRageMath.Quaternion, ref VRageMath.Quaternion)`](VRageMath.Divide)|Divides a Quaternion by another Quaternion.|
|static [`VRageMath.Quaternion FromVector4(VRageMath.Vector4)`](VRageMath.FromVector4)||
|[`VRageMath.Vector4 ToVector4()`](VRageMath.ToVector4)||
|static [`bool IsZero(VRageMath.Quaternion)`](VRageMath.IsZero)||
|static [`bool IsZero(VRageMath.Quaternion, float)`](VRageMath.IsZero)||
|static [`void GetForward(ref VRageMath.Quaternion, ref VRageMath.Vector3)`](VRageMath.GetForward)|Gets forward vector (0,0,-1) transformed by quaternion.|
|static [`void GetRight(ref VRageMath.Quaternion, ref VRageMath.Vector3)`](VRageMath.GetRight)|Gets right vector (1,0,0) transformed by quaternion.|
|static [`void GetUp(ref VRageMath.Quaternion, ref VRageMath.Vector3)`](VRageMath.GetUp)|Gets up vector (0,1,0) transformed by quaternion.|
|[`float GetComponent(int)`](VRageMath.GetComponent)||
|[`void SetComponent(int, float)`](VRageMath.SetComponent)||
|[`int FindLargestIndex()`](VRageMath.FindLargestIndex)||
