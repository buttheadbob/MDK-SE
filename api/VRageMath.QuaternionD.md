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
|static [`VRageMath.QuaternionD Identity`](VRageMath.Identity)||
### Methods
|Member|Description|
|---|---|
|[`string ToString()`](VRageMath.ToString)|Retireves a string representation of the current object.|
|[`bool Equals(VRageMath.QuaternionD)`](VRageMath.Equals)|Determines whether the specified Object is equal to the QuaternionD.|
|[`bool Equals(System.Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Get the hash code of this object.|
|[`double LengthSquared()`](VRageMath.LengthSquared)|Calculates the length squared of a QuaternionD.|
|[`double Length()`](VRageMath.Length)|Calculates the length of a QuaternionD.|
|[`void Normalize()`](VRageMath.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[`void GetAxisAngle(ref VRageMath.Vector3D, ref double)`](VRageMath.GetAxisAngle)||
|static [`VRageMath.QuaternionD Normalize(VRageMath.QuaternionD)`](VRageMath.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|static [`void Normalize(ref VRageMath.QuaternionD, ref VRageMath.QuaternionD)`](VRageMath.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[`void Conjugate()`](VRageMath.Conjugate)|Transforms this QuaternionD into its conjugate.|
|static [`VRageMath.QuaternionD Conjugate(VRageMath.QuaternionD)`](VRageMath.Conjugate)|Returns the conjugate of a specified QuaternionD.|
|static [`void Conjugate(ref VRageMath.QuaternionD, ref VRageMath.QuaternionD)`](VRageMath.Conjugate)|Returns the conjugate of a specified QuaternionD.|
|static [`VRageMath.QuaternionD Inverse(VRageMath.QuaternionD)`](VRageMath.Inverse)|Returns the inverse of a QuaternionD.|
|static [`void Inverse(ref VRageMath.QuaternionD, ref VRageMath.QuaternionD)`](VRageMath.Inverse)|Returns the inverse of a QuaternionD.|
|static [`VRageMath.QuaternionD CreateFromAxisAngle(VRageMath.Vector3D, double)`](VRageMath.CreateFromAxisAngle)|Creates a QuaternionD from a vector and an angle to rotate about the vector.|
|static [`void CreateFromAxisAngle(ref VRageMath.Vector3D, double, ref VRageMath.QuaternionD)`](VRageMath.CreateFromAxisAngle)|Creates a QuaternionD from a vector and an angle to rotate about the vector.|
|static [`VRageMath.QuaternionD CreateFromYawPitchRoll(double, double, double)`](VRageMath.CreateFromYawPitchRoll)|Creates a new QuaternionD from specified yaw, pitch, and roll angles.|
|static [`void CreateFromYawPitchRoll(double, double, double, ref VRageMath.QuaternionD)`](VRageMath.CreateFromYawPitchRoll)|Creates a new QuaternionD from specified yaw, pitch, and roll angles.|
|static [`VRageMath.QuaternionD CreateFromForwardUp(VRageMath.Vector3D, VRageMath.Vector3D)`](VRageMath.CreateFromForwardUp)|Works for normalized vectors only|
|static [`VRageMath.QuaternionD CreateFromRotationMatrix(VRageMath.MatrixD)`](VRageMath.CreateFromRotationMatrix)|Creates a QuaternionD from a rotation MatrixD.|
|static [`void CreateFromRotationMatrix(ref VRageMath.MatrixD, ref VRageMath.QuaternionD)`](VRageMath.CreateFromRotationMatrix)|Creates a QuaternionD from a rotation MatrixD.|
|static [`double Dot(VRageMath.QuaternionD, VRageMath.QuaternionD)`](VRageMath.Dot)|Calculates the dot product of two Quaternions.|
|static [`void Dot(ref VRageMath.QuaternionD, ref VRageMath.QuaternionD, ref double)`](VRageMath.Dot)|Calculates the dot product of two Quaternions.|
|static [`VRageMath.QuaternionD Slerp(VRageMath.QuaternionD, VRageMath.QuaternionD, double)`](VRageMath.Slerp)|Interpolates between two quaternions, using spherical linear interpolation.|
|static [`void Slerp(ref VRageMath.QuaternionD, ref VRageMath.QuaternionD, double, ref VRageMath.QuaternionD)`](VRageMath.Slerp)|Interpolates between two quaternions, using spherical linear interpolation.|
|static [`VRageMath.QuaternionD Lerp(VRageMath.QuaternionD, VRageMath.QuaternionD, double)`](VRageMath.Lerp)|Linearly interpolates between two quaternions.|
|static [`void Lerp(ref VRageMath.QuaternionD, ref VRageMath.QuaternionD, double, ref VRageMath.QuaternionD)`](VRageMath.Lerp)|Linearly interpolates between two quaternions.|
|static [`VRageMath.QuaternionD Concatenate(VRageMath.QuaternionD, VRageMath.QuaternionD)`](VRageMath.Concatenate)|Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.|
|static [`void Concatenate(ref VRageMath.QuaternionD, ref VRageMath.QuaternionD, ref VRageMath.QuaternionD)`](VRageMath.Concatenate)|Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.|
|static [`VRageMath.QuaternionD Negate(VRageMath.QuaternionD)`](VRageMath.Negate)|Flips the sign of each component of the quaternion.|
|static [`void Negate(ref VRageMath.QuaternionD, ref VRageMath.QuaternionD)`](VRageMath.Negate)|Flips the sign of each component of the quaternion.|
|static [`VRageMath.QuaternionD Add(VRageMath.QuaternionD, VRageMath.QuaternionD)`](VRageMath.Add)|Adds two Quaternions.|
|static [`void Add(ref VRageMath.QuaternionD, ref VRageMath.QuaternionD, ref VRageMath.QuaternionD)`](VRageMath.Add)|Adds two Quaternions.|
|static [`VRageMath.QuaternionD Subtract(VRageMath.QuaternionD, VRageMath.QuaternionD)`](VRageMath.Subtract)|Subtracts a quaternion from another quaternion.|
|static [`void Subtract(ref VRageMath.QuaternionD, ref VRageMath.QuaternionD, ref VRageMath.QuaternionD)`](VRageMath.Subtract)|Subtracts a quaternion from another quaternion.|
|static [`VRageMath.QuaternionD Multiply(VRageMath.QuaternionD, VRageMath.QuaternionD)`](VRageMath.Multiply)|Multiplies two quaternions.|
|static [`void Multiply(ref VRageMath.QuaternionD, ref VRageMath.QuaternionD, ref VRageMath.QuaternionD)`](VRageMath.Multiply)|Multiplies two quaternions.|
|static [`VRageMath.QuaternionD Multiply(VRageMath.QuaternionD, double)`](VRageMath.Multiply)|Multiplies a quaternion by a scalar value.|
|static [`void Multiply(ref VRageMath.QuaternionD, double, ref VRageMath.QuaternionD)`](VRageMath.Multiply)|Multiplies a quaternion by a scalar value.|
|static [`VRageMath.QuaternionD Divide(VRageMath.QuaternionD, VRageMath.QuaternionD)`](VRageMath.Divide)|Divides a QuaternionD by another QuaternionD.|
|static [`void Divide(ref VRageMath.QuaternionD, ref VRageMath.QuaternionD, ref VRageMath.QuaternionD)`](VRageMath.Divide)|Divides a QuaternionD by another QuaternionD.|
|static [`VRageMath.QuaternionD FromVector4(VRageMath.Vector4D)`](VRageMath.FromVector4)||
|[`VRageMath.Vector4D ToVector4()`](VRageMath.ToVector4)||
|static [`bool IsZero(VRageMath.QuaternionD)`](VRageMath.IsZero)||
|static [`bool IsZero(VRageMath.QuaternionD, double)`](VRageMath.IsZero)||
|static [`void CreateFromTwoVectors(ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref VRageMath.QuaternionD)`](VRageMath.CreateFromTwoVectors)||
|static [`VRageMath.QuaternionD CreateFromTwoVectors(VRageMath.Vector3D, VRageMath.Vector3D)`](VRageMath.CreateFromTwoVectors)||
