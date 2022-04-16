← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### Quaternion Struct

```csharp
public struct Quaternion: IEquatable<Quaternion>
```

Defines a four-dimensional vector (x,y,z,w), which is used to efficiently rotate an object about the (x, y, z) vector by the angle theta, where w = cos(theta/2).

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<Quaternion>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\\$1static Quaternion Identity](VRageMath.Quaternion.Identity)||
|\\$1static Quaternion Zero](VRageMath.Quaternion.Zero)||
|\\$1float W](VRageMath.Quaternion.W)|Specifies the rotation component of the quaternion.|
|\\$1float X](VRageMath.Quaternion.X)|Specifies the x-value of the vector component of the quaternion.|
|\\$1float Y](VRageMath.Quaternion.Y)|Specifies the y-value of the vector component of the quaternion.|
|\\$1float Z](VRageMath.Quaternion.Z)|Specifies the z-value of the vector component of the quaternion.|

#### Properties

|Member|Description|
|---|---|
|\\$1Vector3 Forward { get; }](VRageMath.Quaternion.Forward)||
|\\$1Vector3 Right { get; }](VRageMath.Quaternion.Right)||
|\\$1Vector3 Up { get; }](VRageMath.Quaternion.Up)||

#### Constructors

|Member|Description|
|---|---|
|\\$1Quaternion(float, float, float, float)](VRageMath.Quaternion..ctor)||
|\\$1Quaternion(Vector3, float)](VRageMath.Quaternion..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\$1static Quaternion Add(Quaternion, Quaternion)](VRageMath.Quaternion.Add)|Adds two Quaternions.|
|\\$1static void Add(ref Quaternion, ref Quaternion, out Quaternion)](VRageMath.Quaternion.Add)|Adds two Quaternions.|
|\\$1static Quaternion Concatenate(Quaternion, Quaternion)](VRageMath.Quaternion.Concatenate)|Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.|
|\\$1static void Concatenate(ref Quaternion, ref Quaternion, out Quaternion)](VRageMath.Quaternion.Concatenate)|Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.|
|\\$1static Quaternion Conjugate(Quaternion)](VRageMath.Quaternion.Conjugate)|Returns the conjugate of a specified Quaternion.|
|\\$1static void Conjugate(ref Quaternion, out Quaternion)](VRageMath.Quaternion.Conjugate)|Returns the conjugate of a specified Quaternion.|
|\\$1static Quaternion CreateFromAxisAngle(Vector3, float)](VRageMath.Quaternion.CreateFromAxisAngle)|Creates a Quaternion from a vector and an angle to rotate about the vector.|
|\\$1static void CreateFromAxisAngle(ref Vector3, float, out Quaternion)](VRageMath.Quaternion.CreateFromAxisAngle)|Creates a Quaternion from a vector and an angle to rotate about the vector.|
|\\$1static Quaternion CreateFromForwardUp(Vector3, Vector3)](VRageMath.Quaternion.CreateFromForwardUp)|Works for normalized vectors only|
|\\$1static Quaternion CreateFromRotationMatrix(ref MatrixD)](VRageMath.Quaternion.CreateFromRotationMatrix)||
|\\$1static Quaternion CreateFromRotationMatrix(Matrix)](VRageMath.Quaternion.CreateFromRotationMatrix)|Creates a Quaternion from a rotation Matrix.|
|\\$1static void CreateFromRotationMatrix(ref MatrixD, out Quaternion)](VRageMath.Quaternion.CreateFromRotationMatrix)||
|\\$1static void CreateFromRotationMatrix(ref Matrix, out Quaternion)](VRageMath.Quaternion.CreateFromRotationMatrix)|Creates a Quaternion from a rotation Matrix.|
|\\$1static void CreateFromRotationMatrix(ref Matrix3x3, out Quaternion)](VRageMath.Quaternion.CreateFromRotationMatrix)|Creates a Quaternion from a rotation Matrix.|
|\\$1static void CreateFromTwoVectors(ref Vector3, ref Vector3, out Quaternion)](VRageMath.Quaternion.CreateFromTwoVectors)||
|\\$1static Quaternion CreateFromTwoVectors(Vector3, Vector3)](VRageMath.Quaternion.CreateFromTwoVectors)||
|\\$1static Quaternion CreateFromYawPitchRoll(float, float, float)](VRageMath.Quaternion.CreateFromYawPitchRoll)|Creates a new Quaternion from specified yaw, pitch, and roll angles.|
|\\$1static void CreateFromYawPitchRoll(float, float, float, out Quaternion)](VRageMath.Quaternion.CreateFromYawPitchRoll)|Creates a new Quaternion from specified yaw, pitch, and roll angles.|
|\\$1static Quaternion Divide(Quaternion, Quaternion)](VRageMath.Quaternion.Divide)|Divides a Quaternion by another Quaternion.|
|\\$1static void Divide(ref Quaternion, ref Quaternion, out Quaternion)](VRageMath.Quaternion.Divide)|Divides a Quaternion by another Quaternion.|
|\\$1static float Dot(Quaternion, Quaternion)](VRageMath.Quaternion.Dot)|Calculates the dot product of two Quaternions.|
|\\$1static void Dot(ref Quaternion, ref Quaternion, out float)](VRageMath.Quaternion.Dot)|Calculates the dot product of two Quaternions.|
|\\$1static Quaternion FromVector4(Vector4)](VRageMath.Quaternion.FromVector4)||
|\\$1static void GetForward(ref Quaternion, out Vector3)](VRageMath.Quaternion.GetForward)|Gets forward vector (0,0,-1) transformed by quaternion.|
|\\$1static void GetRight(ref Quaternion, out Vector3)](VRageMath.Quaternion.GetRight)|Gets right vector (1,0,0) transformed by quaternion.|
|\\$1static void GetUp(ref Quaternion, out Vector3)](VRageMath.Quaternion.GetUp)|Gets up vector (0,1,0) transformed by quaternion.|
|\\$1static Quaternion Inverse(Quaternion)](VRageMath.Quaternion.Inverse)|Returns the inverse of a Quaternion.|
|\\$1static void Inverse(ref Quaternion, out Quaternion)](VRageMath.Quaternion.Inverse)|Returns the inverse of a Quaternion.|
|\\$1static bool IsZero(Quaternion)](VRageMath.Quaternion.IsZero)||
|\\$1static bool IsZero(Quaternion, float)](VRageMath.Quaternion.IsZero)||
|\\$1static Quaternion Lerp(Quaternion, Quaternion, float)](VRageMath.Quaternion.Lerp)|Linearly interpolates between two quaternions.|
|\\$1static void Lerp(ref Quaternion, ref Quaternion, float, out Quaternion)](VRageMath.Quaternion.Lerp)|Linearly interpolates between two quaternions.|
|\\$1static Quaternion Multiply(Quaternion, Quaternion)](VRageMath.Quaternion.Multiply)|Multiplies two quaternions.|
|\\$1static void Multiply(ref Quaternion, ref Quaternion, out Quaternion)](VRageMath.Quaternion.Multiply)|Multiplies two quaternions.|
|\\$1static Quaternion Multiply(Quaternion, float)](VRageMath.Quaternion.Multiply)|Multiplies a quaternion by a scalar value.|
|\\$1static void Multiply(ref Quaternion, float, out Quaternion)](VRageMath.Quaternion.Multiply)|Multiplies a quaternion by a scalar value.|
|\\$1static Quaternion Negate(Quaternion)](VRageMath.Quaternion.Negate)|Flips the sign of each component of the quaternion.|
|\\$1static void Negate(ref Quaternion, out Quaternion)](VRageMath.Quaternion.Negate)|Flips the sign of each component of the quaternion.|
|\\$1static Quaternion Normalize(Quaternion)](VRageMath.Quaternion.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|\\$1static void Normalize(ref Quaternion, out Quaternion)](VRageMath.Quaternion.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|\\$1static Quaternion Slerp(Quaternion, Quaternion, float)](VRageMath.Quaternion.Slerp)|Interpolates between two quaternions, using spherical linear interpolation.|
|\\$1static void Slerp(ref Quaternion, ref Quaternion, float, out Quaternion)](VRageMath.Quaternion.Slerp)|Interpolates between two quaternions, using spherical linear interpolation.|
|\\$1static Quaternion Subtract(Quaternion, Quaternion)](VRageMath.Quaternion.Subtract)|Subtracts a quaternion from another quaternion.|
|\\$1static void Subtract(ref Quaternion, ref Quaternion, out Quaternion)](VRageMath.Quaternion.Subtract)|Subtracts a quaternion from another quaternion.|
|\\$1void Conjugate()](VRageMath.Quaternion.Conjugate)|Transforms this Quaternion into its conjugate.|
|\\$1bool Equals(Quaternion)](VRageMath.Quaternion.Equals)|Determines whether the specified Object is equal to the Quaternion.|
|\\$1bool Equals(Quaternion, float)](VRageMath.Quaternion.Equals)||
|\\$1bool Equals(object)](VRageMath.Quaternion.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|\\$1int FindLargestIndex()](VRageMath.Quaternion.FindLargestIndex)||
|\\$1void GetAxisAngle(out Vector3, out float)](VRageMath.Quaternion.GetAxisAngle)||
|\\$1float GetComponent(int)](VRageMath.Quaternion.GetComponent)||
|\\$1int GetHashCode()](VRageMath.Quaternion.GetHashCode)|Get the hash code of this object.|
|\\$1float Length()](VRageMath.Quaternion.Length)|Calculates the length of a Quaternion.|
|\\$1float LengthSquared()](VRageMath.Quaternion.LengthSquared)|Calculates the length squared of a Quaternion.|
|\\$1void Normalize()](VRageMath.Quaternion.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|\\$1void SetComponent(int, float)](VRageMath.Quaternion.SetComponent)||
|\\$1string ToString()](VRageMath.Quaternion.ToString)|Retireves a string representation of the current object.|
|\\$1string ToString(string)](VRageMath.Quaternion.ToString)||
|\\$1string ToStringAxisAngle(\\$1string])](VRageMath.Quaternion.ToStringAxisAngle)||
|\\$1Vector4 ToVector4()](VRageMath.Quaternion.ToVector4)||

