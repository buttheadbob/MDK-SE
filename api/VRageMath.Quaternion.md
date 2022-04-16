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
|[static Quaternion Identity](VRageMath.Quaternion.Identity)||
|[static Quaternion Zero](VRageMath.Quaternion.Zero)||
|[float W](VRageMath.Quaternion.W)|Specifies the rotation component of the quaternion.|
|[float X](VRageMath.Quaternion.X)|Specifies the x-value of the vector component of the quaternion.|
|[float Y](VRageMath.Quaternion.Y)|Specifies the y-value of the vector component of the quaternion.|
|[float Z](VRageMath.Quaternion.Z)|Specifies the z-value of the vector component of the quaternion.|

#### Properties

|Member|Description|
|---|---|
|[Vector3 Forward { get; }](VRageMath.Quaternion.Forward)||
|[Vector3 Right { get; }](VRageMath.Quaternion.Right)||
|[Vector3 Up { get; }](VRageMath.Quaternion.Up)||

#### Constructors

|Member|Description|
|---|---|
|[Quaternion(float, float, float, float)](VRageMath.Quaternion..ctor)||
|[Quaternion(Vector3, float)](VRageMath.Quaternion..ctor)||

#### Methods

|Member|Description|
|---|---|
|[static Quaternion Add(Quaternion, Quaternion)](VRageMath.Quaternion.Add)|Adds two Quaternions.|
|[static void Add(ref Quaternion, ref Quaternion, out Quaternion)](VRageMath.Quaternion.Add)|Adds two Quaternions.|
|[static Quaternion Concatenate(Quaternion, Quaternion)](VRageMath.Quaternion.Concatenate)|Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.|
|[static void Concatenate(ref Quaternion, ref Quaternion, out Quaternion)](VRageMath.Quaternion.Concatenate)|Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.|
|[static Quaternion Conjugate(Quaternion)](VRageMath.Quaternion.Conjugate)|Returns the conjugate of a specified Quaternion.|
|[static void Conjugate(ref Quaternion, out Quaternion)](VRageMath.Quaternion.Conjugate)|Returns the conjugate of a specified Quaternion.|
|[static Quaternion CreateFromAxisAngle(Vector3, float)](VRageMath.Quaternion.CreateFromAxisAngle)|Creates a Quaternion from a vector and an angle to rotate about the vector.|
|[static void CreateFromAxisAngle(ref Vector3, float, out Quaternion)](VRageMath.Quaternion.CreateFromAxisAngle)|Creates a Quaternion from a vector and an angle to rotate about the vector.|
|[static Quaternion CreateFromForwardUp(Vector3, Vector3)](VRageMath.Quaternion.CreateFromForwardUp)|Works for normalized vectors only|
|[static Quaternion CreateFromRotationMatrix(ref MatrixD)](VRageMath.Quaternion.CreateFromRotationMatrix)||
|[static Quaternion CreateFromRotationMatrix(Matrix)](VRageMath.Quaternion.CreateFromRotationMatrix)|Creates a Quaternion from a rotation Matrix.|
|[static void CreateFromRotationMatrix(ref MatrixD, out Quaternion)](VRageMath.Quaternion.CreateFromRotationMatrix)||
|[static void CreateFromRotationMatrix(ref Matrix, out Quaternion)](VRageMath.Quaternion.CreateFromRotationMatrix)|Creates a Quaternion from a rotation Matrix.|
|[static void CreateFromRotationMatrix(ref Matrix3x3, out Quaternion)](VRageMath.Quaternion.CreateFromRotationMatrix)|Creates a Quaternion from a rotation Matrix.|
|[static void CreateFromTwoVectors(ref Vector3, ref Vector3, out Quaternion)](VRageMath.Quaternion.CreateFromTwoVectors)||
|[static Quaternion CreateFromTwoVectors(Vector3, Vector3)](VRageMath.Quaternion.CreateFromTwoVectors)||
|[static Quaternion CreateFromYawPitchRoll(float, float, float)](VRageMath.Quaternion.CreateFromYawPitchRoll)|Creates a new Quaternion from specified yaw, pitch, and roll angles.|
|[static void CreateFromYawPitchRoll(float, float, float, out Quaternion)](VRageMath.Quaternion.CreateFromYawPitchRoll)|Creates a new Quaternion from specified yaw, pitch, and roll angles.|
|[static Quaternion Divide(Quaternion, Quaternion)](VRageMath.Quaternion.Divide)|Divides a Quaternion by another Quaternion.|
|[static void Divide(ref Quaternion, ref Quaternion, out Quaternion)](VRageMath.Quaternion.Divide)|Divides a Quaternion by another Quaternion.|
|[static float Dot(Quaternion, Quaternion)](VRageMath.Quaternion.Dot)|Calculates the dot product of two Quaternions.|
|[static void Dot(ref Quaternion, ref Quaternion, out float)](VRageMath.Quaternion.Dot)|Calculates the dot product of two Quaternions.|
|[static Quaternion FromVector4(Vector4)](VRageMath.Quaternion.FromVector4)||
|[static void GetForward(ref Quaternion, out Vector3)](VRageMath.Quaternion.GetForward)|Gets forward vector (0,0,-1) transformed by quaternion.|
|[static void GetRight(ref Quaternion, out Vector3)](VRageMath.Quaternion.GetRight)|Gets right vector (1,0,0) transformed by quaternion.|
|[static void GetUp(ref Quaternion, out Vector3)](VRageMath.Quaternion.GetUp)|Gets up vector (0,1,0) transformed by quaternion.|
|[static Quaternion Inverse(Quaternion)](VRageMath.Quaternion.Inverse)|Returns the inverse of a Quaternion.|
|[static void Inverse(ref Quaternion, out Quaternion)](VRageMath.Quaternion.Inverse)|Returns the inverse of a Quaternion.|
|[static bool IsZero(Quaternion)](VRageMath.Quaternion.IsZero)||
|[static bool IsZero(Quaternion, float)](VRageMath.Quaternion.IsZero)||
|[static Quaternion Lerp(Quaternion, Quaternion, float)](VRageMath.Quaternion.Lerp)|Linearly interpolates between two quaternions.|
|[static void Lerp(ref Quaternion, ref Quaternion, float, out Quaternion)](VRageMath.Quaternion.Lerp)|Linearly interpolates between two quaternions.|
|[static Quaternion Multiply(Quaternion, Quaternion)](VRageMath.Quaternion.Multiply)|Multiplies two quaternions.|
|[static void Multiply(ref Quaternion, ref Quaternion, out Quaternion)](VRageMath.Quaternion.Multiply)|Multiplies two quaternions.|
|[static Quaternion Multiply(Quaternion, float)](VRageMath.Quaternion.Multiply)|Multiplies a quaternion by a scalar value.|
|[static void Multiply(ref Quaternion, float, out Quaternion)](VRageMath.Quaternion.Multiply)|Multiplies a quaternion by a scalar value.|
|[static Quaternion Negate(Quaternion)](VRageMath.Quaternion.Negate)|Flips the sign of each component of the quaternion.|
|[static void Negate(ref Quaternion, out Quaternion)](VRageMath.Quaternion.Negate)|Flips the sign of each component of the quaternion.|
|[static Quaternion Normalize(Quaternion)](VRageMath.Quaternion.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[static void Normalize(ref Quaternion, out Quaternion)](VRageMath.Quaternion.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[static Quaternion Slerp(Quaternion, Quaternion, float)](VRageMath.Quaternion.Slerp)|Interpolates between two quaternions, using spherical linear interpolation.|
|[static void Slerp(ref Quaternion, ref Quaternion, float, out Quaternion)](VRageMath.Quaternion.Slerp)|Interpolates between two quaternions, using spherical linear interpolation.|
|[static Quaternion Subtract(Quaternion, Quaternion)](VRageMath.Quaternion.Subtract)|Subtracts a quaternion from another quaternion.|
|[static void Subtract(ref Quaternion, ref Quaternion, out Quaternion)](VRageMath.Quaternion.Subtract)|Subtracts a quaternion from another quaternion.|
|[void Conjugate()](VRageMath.Quaternion.Conjugate)|Transforms this Quaternion into its conjugate.|
|[bool Equals(Quaternion)](VRageMath.Quaternion.Equals)|Determines whether the specified Object is equal to the Quaternion.|
|[bool Equals(Quaternion, float)](VRageMath.Quaternion.Equals)||
|[bool Equals(object)](VRageMath.Quaternion.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[int FindLargestIndex()](VRageMath.Quaternion.FindLargestIndex)||
|[void GetAxisAngle(out Vector3, out float)](VRageMath.Quaternion.GetAxisAngle)||
|[float GetComponent(int)](VRageMath.Quaternion.GetComponent)||
|[int GetHashCode()](VRageMath.Quaternion.GetHashCode)|Get the hash code of this object.|
|[float Length()](VRageMath.Quaternion.Length)|Calculates the length of a Quaternion.|
|[float LengthSquared()](VRageMath.Quaternion.LengthSquared)|Calculates the length squared of a Quaternion.|
|[void Normalize()](VRageMath.Quaternion.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|[void SetComponent(int, float)](VRageMath.Quaternion.SetComponent)||
|[string ToString()](VRageMath.Quaternion.ToString)|Retireves a string representation of the current object.|
|[string ToString(string)](VRageMath.Quaternion.ToString)||
|[string ToStringAxisAngle([string])](VRageMath.Quaternion.ToStringAxisAngle)||
|[Vector4 ToVector4()](VRageMath.Quaternion.ToVector4)||

