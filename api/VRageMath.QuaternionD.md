← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### QuaternionD Struct

```csharp
public struct QuaternionD
```

Defines a four-dimensional vector (x,y,z,w), which is used to efficiently rotate an object about the (x, y, z) vector by the angle theta, where w = cos(theta/2). Uses double precision floating point numbers for calculation and storage

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

#### Fields

|Member|Description|
|---|---|
|\\$1static QuaternionD Identity](VRageMath.QuaternionD.Identity)||
|\\$1double W](VRageMath.QuaternionD.W)|Specifies the rotation component of the quaternion.|
|\\$1double X](VRageMath.QuaternionD.X)|Specifies the x-value of the vector component of the quaternion.|
|\\$1double Y](VRageMath.QuaternionD.Y)|Specifies the y-value of the vector component of the quaternion.|
|\\$1double Z](VRageMath.QuaternionD.Z)|Specifies the z-value of the vector component of the quaternion.|

#### Constructors

|Member|Description|
|---|---|
|\\$1QuaternionD(double, double, double, double)](VRageMath.QuaternionD..ctor)||
|\\$1QuaternionD(Vector3D, double)](VRageMath.QuaternionD..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\$1static QuaternionD Add(QuaternionD, QuaternionD)](VRageMath.QuaternionD.Add)|Adds two Quaternions.|
|\\$1static void Add(ref QuaternionD, ref QuaternionD, out QuaternionD)](VRageMath.QuaternionD.Add)|Adds two Quaternions.|
|\\$1static QuaternionD Concatenate(QuaternionD, QuaternionD)](VRageMath.QuaternionD.Concatenate)|Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.|
|\\$1static void Concatenate(ref QuaternionD, ref QuaternionD, out QuaternionD)](VRageMath.QuaternionD.Concatenate)|Concatenates two Quaternions; the result represents the value1 rotation followed by the value2 rotation.|
|\\$1static QuaternionD Conjugate(QuaternionD)](VRageMath.QuaternionD.Conjugate)|Returns the conjugate of a specified QuaternionD.|
|\\$1static void Conjugate(ref QuaternionD, out QuaternionD)](VRageMath.QuaternionD.Conjugate)|Returns the conjugate of a specified QuaternionD.|
|\\$1static QuaternionD CreateFromAxisAngle(Vector3D, double)](VRageMath.QuaternionD.CreateFromAxisAngle)|Creates a QuaternionD from a vector and an angle to rotate about the vector.|
|\\$1static void CreateFromAxisAngle(ref Vector3D, double, out QuaternionD)](VRageMath.QuaternionD.CreateFromAxisAngle)|Creates a QuaternionD from a vector and an angle to rotate about the vector.|
|\\$1static QuaternionD CreateFromForwardUp(Vector3D, Vector3D)](VRageMath.QuaternionD.CreateFromForwardUp)|Works for normalized vectors only|
|\\$1static QuaternionD CreateFromRotationMatrix(MatrixD)](VRageMath.QuaternionD.CreateFromRotationMatrix)|Creates a QuaternionD from a rotation MatrixD.|
|\\$1static void CreateFromRotationMatrix(ref MatrixD, out QuaternionD)](VRageMath.QuaternionD.CreateFromRotationMatrix)|Creates a QuaternionD from a rotation MatrixD.|
|\\$1static void CreateFromTwoVectors(ref Vector3D, ref Vector3D, out QuaternionD)](VRageMath.QuaternionD.CreateFromTwoVectors)||
|\\$1static QuaternionD CreateFromTwoVectors(Vector3D, Vector3D)](VRageMath.QuaternionD.CreateFromTwoVectors)||
|\\$1static QuaternionD CreateFromYawPitchRoll(double, double, double)](VRageMath.QuaternionD.CreateFromYawPitchRoll)|Creates a new QuaternionD from specified yaw, pitch, and roll angles.|
|\\$1static void CreateFromYawPitchRoll(double, double, double, out QuaternionD)](VRageMath.QuaternionD.CreateFromYawPitchRoll)|Creates a new QuaternionD from specified yaw, pitch, and roll angles.|
|\\$1static QuaternionD Divide(QuaternionD, QuaternionD)](VRageMath.QuaternionD.Divide)|Divides a QuaternionD by another QuaternionD.|
|\\$1static void Divide(ref QuaternionD, ref QuaternionD, out QuaternionD)](VRageMath.QuaternionD.Divide)|Divides a QuaternionD by another QuaternionD.|
|\\$1static double Dot(QuaternionD, QuaternionD)](VRageMath.QuaternionD.Dot)|Calculates the dot product of two Quaternions.|
|\\$1static void Dot(ref QuaternionD, ref QuaternionD, out double)](VRageMath.QuaternionD.Dot)|Calculates the dot product of two Quaternions.|
|\\$1static QuaternionD FromVector4(Vector4D)](VRageMath.QuaternionD.FromVector4)||
|\\$1static QuaternionD Inverse(QuaternionD)](VRageMath.QuaternionD.Inverse)|Returns the inverse of a QuaternionD.|
|\\$1static void Inverse(ref QuaternionD, out QuaternionD)](VRageMath.QuaternionD.Inverse)|Returns the inverse of a QuaternionD.|
|\\$1static bool IsZero(QuaternionD)](VRageMath.QuaternionD.IsZero)||
|\\$1static bool IsZero(QuaternionD, double)](VRageMath.QuaternionD.IsZero)||
|\\$1static QuaternionD Lerp(QuaternionD, QuaternionD, double)](VRageMath.QuaternionD.Lerp)|Linearly interpolates between two quaternions.|
|\\$1static void Lerp(ref QuaternionD, ref QuaternionD, double, out QuaternionD)](VRageMath.QuaternionD.Lerp)|Linearly interpolates between two quaternions.|
|\\$1static QuaternionD Multiply(QuaternionD, QuaternionD)](VRageMath.QuaternionD.Multiply)|Multiplies two quaternions.|
|\\$1static void Multiply(ref QuaternionD, ref QuaternionD, out QuaternionD)](VRageMath.QuaternionD.Multiply)|Multiplies two quaternions.|
|\\$1static QuaternionD Multiply(QuaternionD, double)](VRageMath.QuaternionD.Multiply)|Multiplies a quaternion by a scalar value.|
|\\$1static void Multiply(ref QuaternionD, double, out QuaternionD)](VRageMath.QuaternionD.Multiply)|Multiplies a quaternion by a scalar value.|
|\\$1static QuaternionD Negate(QuaternionD)](VRageMath.QuaternionD.Negate)|Flips the sign of each component of the quaternion.|
|\\$1static void Negate(ref QuaternionD, out QuaternionD)](VRageMath.QuaternionD.Negate)|Flips the sign of each component of the quaternion.|
|\\$1static QuaternionD Normalize(QuaternionD)](VRageMath.QuaternionD.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|\\$1static void Normalize(ref QuaternionD, out QuaternionD)](VRageMath.QuaternionD.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|\\$1static QuaternionD Slerp(QuaternionD, QuaternionD, double)](VRageMath.QuaternionD.Slerp)|Interpolates between two quaternions, using spherical linear interpolation.|
|\\$1static void Slerp(ref QuaternionD, ref QuaternionD, double, out QuaternionD)](VRageMath.QuaternionD.Slerp)|Interpolates between two quaternions, using spherical linear interpolation.|
|\\$1static QuaternionD Subtract(QuaternionD, QuaternionD)](VRageMath.QuaternionD.Subtract)|Subtracts a quaternion from another quaternion.|
|\\$1static void Subtract(ref QuaternionD, ref QuaternionD, out QuaternionD)](VRageMath.QuaternionD.Subtract)|Subtracts a quaternion from another quaternion.|
|\\$1void Conjugate()](VRageMath.QuaternionD.Conjugate)|Transforms this QuaternionD into its conjugate.|
|\\$1bool Equals(QuaternionD)](VRageMath.QuaternionD.Equals)|Determines whether the specified Object is equal to the QuaternionD.|
|\\$1bool Equals(object)](VRageMath.QuaternionD.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|\\$1void GetAxisAngle(out Vector3D, out double)](VRageMath.QuaternionD.GetAxisAngle)||
|\\$1int GetHashCode()](VRageMath.QuaternionD.GetHashCode)|Get the hash code of this object.|
|\\$1double Length()](VRageMath.QuaternionD.Length)|Calculates the length of a QuaternionD.|
|\\$1double LengthSquared()](VRageMath.QuaternionD.LengthSquared)|Calculates the length squared of a QuaternionD.|
|\\$1void Normalize()](VRageMath.QuaternionD.Normalize)|Divides each component of the quaternion by the length of the quaternion.|
|\\$1string ToString()](VRageMath.QuaternionD.ToString)|Retireves a string representation of the current object.|
|\\$1Vector4D ToVector4()](VRageMath.QuaternionD.ToVector4)||

