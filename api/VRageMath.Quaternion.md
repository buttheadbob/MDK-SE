← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### Quaternion Struct

```csharp
public struct Quaternion: IEquatable<VRageMath.Quaternion>
```

Defines a four-dimensional vector (x,y,z,w), which is used to efficiently rotate an object about the (x, y, z) vector by the angle theta, where w = cos(theta/2).

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<VRageMath.Quaternion>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[X](VRageMath.Quaternion.X)|Specifies the x-value of the vector component of the quaternion.|
|[Y](VRageMath.Quaternion.Y)|Specifies the y-value of the vector component of the quaternion.|
|[Z](VRageMath.Quaternion.Z)|Specifies the z-value of the vector component of the quaternion.|
|[W](VRageMath.Quaternion.W)|Specifies the rotation component of the quaternion.|
|[Identity](VRageMath.Quaternion.Identity)||
|[Zero](VRageMath.Quaternion.Zero)||

#### Properties

|Member|Description|
|---|---|
|[Forward](VRageMath.Quaternion.Forward)||
|[Right](VRageMath.Quaternion.Right)||
|[Up](VRageMath.Quaternion.Up)||

#### Constructors

|Member|Description|
|---|---|
|[Quaternion(float, float, float, float)](VRageMath.Quaternion..ctor)||
|[Quaternion(Vector3, float)](VRageMath.Quaternion..ctor)||

#### Methods

|Member|Description|
|---|---|
|[ToString()](VRageMath.Quaternion.ToString)|Retireves a string representation of the current object.|
|[ToString(string)](VRageMath.Quaternion.ToString)||
|[ToStringAxisAngle(string)](VRageMath.Quaternion.ToStringAxisAngle)||
|[Equals(Quaternion)](VRageMath.Quaternion.Equals)|Determines whether the specified Object is equal to the Quaternion.|
|[Equals(Quaternion, float)](VRageMath.Quaternion.Equals)||
|[Equals(object)](VRageMath.Quaternion.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[GetHashCode()](VRageMath.Quaternion.GetHashCode)|Get the hash code of this object.|
|[LengthSquared()](VRageMath.Quaternion.LengthSquared)|Calculates the length squared of a Quaternion.|
|[Length()](VRageMath.Quaternion.Length)|Calculates the length of a Quaternion.|
|[Normalize()](VRageMath.Quaternion.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[GetAxisAngle(ref Vector3, ref float)](VRageMath.Quaternion.GetAxisAngle)||
|[Normalize(Quaternion)](VRageMath.Quaternion.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[Normalize(ref Quaternion, ref Quaternion)](VRageMath.Quaternion.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[Conjugate()](VRageMath.Quaternion.Conjugate)|Transforms this Quaternion into its conjugate.|
|[Conjugate(Quaternion)](VRageMath.Quaternion.Conjugate)|Returns the conjugate of a specified Quaternion.|
|[Conjugate(ref Quaternion, ref Quaternion)](VRageMath.Quaternion.Conjugate)|Returns the conjugate of a specified Quaternion.|
|[Inverse(Quaternion)](VRageMath.Quaternion.Inverse)|Returns the inverse of a Quaternion.|
|[Inverse(ref Quaternion, ref Quaternion)](VRageMath.Quaternion.Inverse)|Returns the inverse of a Quaternion.|
|[CreateFromAxisAngle(Vector3, float)](VRageMath.Quaternion.CreateFromAxisAngle)|Creates a Quaternion from a vector and an angle to rotate about the vector.|
|[CreateFromAxisAngle(ref Vector3, float, ref Quaternion)](VRageMath.Quaternion.CreateFromAxisAngle)|Creates a Quaternion from a vector and an angle to rotate about the vector.|
|[CreateFromYawPitchRoll(float, float, float)](VRageMath.Quaternion.CreateFromYawPitchRoll)|Creates a new Quaternion from specified yaw, pitch, and roll angles.|
|[CreateFromYawPitchRoll(float, float, float, ref Quaternion)](VRageMath.Quaternion.CreateFromYawPitchRoll)|Creates a new Quaternion from specified yaw, pitch, and roll angles.|
|[CreateFromForwardUp(Vector3, Vector3)](VRageMath.Quaternion.CreateFromForwardUp)|Works for normalized vectors only|
|[CreateFromRotationMatrix(MatrixD)](VRageMath.Quaternion.CreateFromRotationMatrix)||
|[CreateFromRotationMatrix(Matrix)](VRageMath.Quaternion.CreateFromRotationMatrix)|Creates a Quaternion from a rotation Matrix.|
|[CreateFromRotationMatrix(ref MatrixD, ref Quaternion)](VRageMath.Quaternion.CreateFromRotationMatrix)||
|[CreateFromTwoVectors(ref Vector3, ref Vector3, ref Quaternion)](VRageMath.Quaternion.CreateFromTwoVectors)||
|[CreateFromTwoVectors(Vector3, Vector3)](VRageMath.Quaternion.CreateFromTwoVectors)||
|[CreateFromRotationMatrix(ref Matrix, ref Quaternion)](VRageMath.Quaternion.CreateFromRotationMatrix)|Creates a Quaternion from a rotation Matrix.|
|[CreateFromRotationMatrix(ref Matrix3x3, ref Quaternion)](VRageMath.Quaternion.CreateFromRotationMatrix)|Creates a Quaternion from a rotation Matrix.|
|[Dot(Quaternion, Quaternion)](VRageMath.Quaternion.Dot)|Calculates the dot product of two Quaternions.|
|[Dot(ref Quaternion, ref Quaternion, ref float)](VRageMath.Quaternion.Dot)|Calculates the dot product of two Quaternions.|
|[Slerp(Quaternion, Quaternion, float)](VRageMath.Quaternion.Slerp)|Interpolates between two quaternions, using spherical linear interpolation.|
|[Slerp(ref Quaternion, ref Quaternion, float, ref Quaternion)](VRageMath.Quaternion.Slerp)|Interpolates between two quaternions, using spherical linear interpolation.|
|[Lerp(Quaternion, Quaternion, float)](VRageMath.Quaternion.Lerp)|Linearly interpolates between two quaternions.|
|[Lerp(ref Quaternion, ref Quaternion, float, ref Quaternion)](VRageMath.Quaternion.Lerp)|Linearly interpolates between two quaternions.|
|[Concatenate(Quaternion, Quaternion)](VRageMath.Quaternion.Concatenate)|Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.|
|[Concatenate(ref Quaternion, ref Quaternion, ref Quaternion)](VRageMath.Quaternion.Concatenate)|Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.|
|[Negate(Quaternion)](VRageMath.Quaternion.Negate)|Flips the sign of each component of the quaternion.|
|[Negate(ref Quaternion, ref Quaternion)](VRageMath.Quaternion.Negate)|Flips the sign of each component of the quaternion.|
|[Add(Quaternion, Quaternion)](VRageMath.Quaternion.Add)|Adds two Quaternions.|
|[Add(ref Quaternion, ref Quaternion, ref Quaternion)](VRageMath.Quaternion.Add)|Adds two Quaternions.|
|[Subtract(Quaternion, Quaternion)](VRageMath.Quaternion.Subtract)|Subtracts a quaternion from another quaternion.|
|[Subtract(ref Quaternion, ref Quaternion, ref Quaternion)](VRageMath.Quaternion.Subtract)|Subtracts a quaternion from another quaternion.|
|[Multiply(Quaternion, Quaternion)](VRageMath.Quaternion.Multiply)|Multiplies two quaternions.|
|[Multiply(ref Quaternion, ref Quaternion, ref Quaternion)](VRageMath.Quaternion.Multiply)|Multiplies two quaternions.|
|[Multiply(Quaternion, float)](VRageMath.Quaternion.Multiply)|Multiplies a quaternion by a scalar value.|
|[Multiply(ref Quaternion, float, ref Quaternion)](VRageMath.Quaternion.Multiply)|Multiplies a quaternion by a scalar value.|
|[Divide(Quaternion, Quaternion)](VRageMath.Quaternion.Divide)|Divides a Quaternion by another Quaternion.|
|[Divide(ref Quaternion, ref Quaternion, ref Quaternion)](VRageMath.Quaternion.Divide)|Divides a Quaternion by another Quaternion.|
|[FromVector4(Vector4)](VRageMath.Quaternion.FromVector4)||
|[ToVector4()](VRageMath.Quaternion.ToVector4)||
|[IsZero(Quaternion)](VRageMath.Quaternion.IsZero)||
|[IsZero(Quaternion, float)](VRageMath.Quaternion.IsZero)||
|[GetForward(ref Quaternion, ref Vector3)](VRageMath.Quaternion.GetForward)|Gets forward vector (0,0,-1) transformed by quaternion.|
|[GetRight(ref Quaternion, ref Vector3)](VRageMath.Quaternion.GetRight)|Gets right vector (1,0,0) transformed by quaternion.|
|[GetUp(ref Quaternion, ref Vector3)](VRageMath.Quaternion.GetUp)|Gets up vector (0,1,0) transformed by quaternion.|
|[GetComponent(int)](VRageMath.Quaternion.GetComponent)||
|[SetComponent(int, float)](VRageMath.Quaternion.SetComponent)||
|[FindLargestIndex()](VRageMath.Quaternion.FindLargestIndex)||

