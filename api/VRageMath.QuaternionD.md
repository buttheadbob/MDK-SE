← [Index](Api-Index)

#### QuaternionD Struct

```csharp
public struct QuaternionD: ValueType
```

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Inheritance: **[ValueType](System.ValueType)

#### Example

#### Remarks

#### Fields

|Member|Description|
|---|---|
|[X](VRageMath.QuaternionD.X)|Specifies the x-value of the vector component of the quaternion.|
|[Y](VRageMath.QuaternionD.Y)|Specifies the y-value of the vector component of the quaternion.|
|[Z](VRageMath.QuaternionD.Z)|Specifies the z-value of the vector component of the quaternion.|
|[W](VRageMath.QuaternionD.W)|Specifies the rotation component of the quaternion.|
|[Identity](VRageMath.QuaternionD.Identity)||

#### Methods

|Member|Description|
|---|---|
|[ToString()](VRageMath.QuaternionD.ToString)|Retireves a string representation of the current object.|
|[Equals(QuaternionD)](VRageMath.QuaternionD.Equals)|Determines whether the specified Object is equal to the QuaternionD.|
|[Equals(object)](VRageMath.QuaternionD.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[GetHashCode()](VRageMath.QuaternionD.GetHashCode)|Get the hash code of this object.|
|[LengthSquared()](VRageMath.QuaternionD.LengthSquared)|Calculates the length squared of a QuaternionD.|
|[Length()](VRageMath.QuaternionD.Length)|Calculates the length of a QuaternionD.|
|[Normalize()](VRageMath.QuaternionD.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[GetAxisAngle(ref Vector3D, ref double)](VRageMath.QuaternionD.GetAxisAngle)||
|[Normalize(QuaternionD)](VRageMath.QuaternionD.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[Normalize(ref QuaternionD, ref QuaternionD)](VRageMath.QuaternionD.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[Conjugate()](VRageMath.QuaternionD.Conjugate)|Transforms this QuaternionD into its conjugate.|
|[Conjugate(QuaternionD)](VRageMath.QuaternionD.Conjugate)|Returns the conjugate of a specified QuaternionD.|
|[Conjugate(ref QuaternionD, ref QuaternionD)](VRageMath.QuaternionD.Conjugate)|Returns the conjugate of a specified QuaternionD.|
|[Inverse(QuaternionD)](VRageMath.QuaternionD.Inverse)|Returns the inverse of a QuaternionD.|
|[Inverse(ref QuaternionD, ref QuaternionD)](VRageMath.QuaternionD.Inverse)|Returns the inverse of a QuaternionD.|
|[CreateFromAxisAngle(Vector3D, double)](VRageMath.QuaternionD.CreateFromAxisAngle)|Creates a QuaternionD from a vector and an angle to rotate about the vector.|
|[CreateFromAxisAngle(ref Vector3D, double, ref QuaternionD)](VRageMath.QuaternionD.CreateFromAxisAngle)|Creates a QuaternionD from a vector and an angle to rotate about the vector.|
|[CreateFromYawPitchRoll(double, double, double)](VRageMath.QuaternionD.CreateFromYawPitchRoll)|Creates a new QuaternionD from specified yaw, pitch, and roll angles.|
|[CreateFromYawPitchRoll(double, double, double, ref QuaternionD)](VRageMath.QuaternionD.CreateFromYawPitchRoll)|Creates a new QuaternionD from specified yaw, pitch, and roll angles.|
|[CreateFromForwardUp(Vector3D, Vector3D)](VRageMath.QuaternionD.CreateFromForwardUp)|Works for normalized vectors only|
|[CreateFromRotationMatrix(MatrixD)](VRageMath.QuaternionD.CreateFromRotationMatrix)|Creates a QuaternionD from a rotation MatrixD.|
|[CreateFromRotationMatrix(ref MatrixD, ref QuaternionD)](VRageMath.QuaternionD.CreateFromRotationMatrix)|Creates a QuaternionD from a rotation MatrixD.|
|[Dot(QuaternionD, QuaternionD)](VRageMath.QuaternionD.Dot)|Calculates the dot product of two Quaternions.|
|[Dot(ref QuaternionD, ref QuaternionD, ref double)](VRageMath.QuaternionD.Dot)|Calculates the dot product of two Quaternions.|
|[Slerp(QuaternionD, QuaternionD, double)](VRageMath.QuaternionD.Slerp)|Interpolates between two quaternions, using spherical linear interpolation.|
|[Slerp(ref QuaternionD, ref QuaternionD, double, ref QuaternionD)](VRageMath.QuaternionD.Slerp)|Interpolates between two quaternions, using spherical linear interpolation.|
|[Lerp(QuaternionD, QuaternionD, double)](VRageMath.QuaternionD.Lerp)|Linearly interpolates between two quaternions.|
|[Lerp(ref QuaternionD, ref QuaternionD, double, ref QuaternionD)](VRageMath.QuaternionD.Lerp)|Linearly interpolates between two quaternions.|
|[Concatenate(QuaternionD, QuaternionD)](VRageMath.QuaternionD.Concatenate)|Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.|
|[Concatenate(ref QuaternionD, ref QuaternionD, ref QuaternionD)](VRageMath.QuaternionD.Concatenate)|Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.|
|[Negate(QuaternionD)](VRageMath.QuaternionD.Negate)|Flips the sign of each component of the quaternion.|
|[Negate(ref QuaternionD, ref QuaternionD)](VRageMath.QuaternionD.Negate)|Flips the sign of each component of the quaternion.|
|[Add(QuaternionD, QuaternionD)](VRageMath.QuaternionD.Add)|Adds two Quaternions.|
|[Add(ref QuaternionD, ref QuaternionD, ref QuaternionD)](VRageMath.QuaternionD.Add)|Adds two Quaternions.|
|[Subtract(QuaternionD, QuaternionD)](VRageMath.QuaternionD.Subtract)|Subtracts a quaternion from another quaternion.|
|[Subtract(ref QuaternionD, ref QuaternionD, ref QuaternionD)](VRageMath.QuaternionD.Subtract)|Subtracts a quaternion from another quaternion.|
|[Multiply(QuaternionD, QuaternionD)](VRageMath.QuaternionD.Multiply)|Multiplies two quaternions.|
|[Multiply(ref QuaternionD, ref QuaternionD, ref QuaternionD)](VRageMath.QuaternionD.Multiply)|Multiplies two quaternions.|
|[Multiply(QuaternionD, double)](VRageMath.QuaternionD.Multiply)|Multiplies a quaternion by a scalar value.|
|[Multiply(ref QuaternionD, double, ref QuaternionD)](VRageMath.QuaternionD.Multiply)|Multiplies a quaternion by a scalar value.|
|[Divide(QuaternionD, QuaternionD)](VRageMath.QuaternionD.Divide)|Divides a QuaternionD by another QuaternionD.|
|[Divide(ref QuaternionD, ref QuaternionD, ref QuaternionD)](VRageMath.QuaternionD.Divide)|Divides a QuaternionD by another QuaternionD.|
|[FromVector4(Vector4D)](VRageMath.QuaternionD.FromVector4)||
|[ToVector4()](VRageMath.QuaternionD.ToVector4)||
|[IsZero(QuaternionD)](VRageMath.QuaternionD.IsZero)||
|[IsZero(QuaternionD, double)](VRageMath.QuaternionD.IsZero)||
|[CreateFromTwoVectors(ref Vector3D, ref Vector3D, ref QuaternionD)](VRageMath.QuaternionD.CreateFromTwoVectors)||
|[CreateFromTwoVectors(Vector3D, Vector3D)](VRageMath.QuaternionD.CreateFromTwoVectors)||

