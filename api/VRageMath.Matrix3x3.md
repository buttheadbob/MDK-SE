← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### Matrix3x3 Struct

```csharp
public struct Matrix3x3: IEquatable<Matrix3x3\>
```

Defines a matrix.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<Matrix3x3\>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\$1static Matrix3x3 Identity](VRageMath.Matrix3x3.Identity)||
|\$1static Matrix3x3 Zero](VRageMath.Matrix3x3.Zero)||
|\$1float M11](VRageMath.Matrix3x3.M11)|Value at row 1 column 1 of the matrix.|
|\$1float M12](VRageMath.Matrix3x3.M12)|Value at row 1 column 2 of the matrix.|
|\$1float M13](VRageMath.Matrix3x3.M13)|Value at row 1 column 3 of the matrix.|
|\$1float M21](VRageMath.Matrix3x3.M21)|Value at row 2 column 1 of the matrix.|
|\$1float M22](VRageMath.Matrix3x3.M22)|Value at row 2 column 2 of the matrix.|
|\$1float M23](VRageMath.Matrix3x3.M23)|Value at row 2 column 3 of the matrix.|
|\$1float M31](VRageMath.Matrix3x3.M31)|Value at row 3 column 1 of the matrix.|
|\$1float M32](VRageMath.Matrix3x3.M32)|Value at row 3 column 2 of the matrix.|
|\$1float M33](VRageMath.Matrix3x3.M33)|Value at row 3 column 3 of the matrix.|

#### Properties

|Member|Description|
|---|---|
|\$1Vector3 Backward { get; set; }](VRageMath.Matrix3x3.Backward)|Gets and sets the backward vector of the Matrix3x3.|
|\$1Vector3 Col0 { get; }](VRageMath.Matrix3x3.Col0)||
|\$1Vector3 Col1 { get; }](VRageMath.Matrix3x3.Col1)||
|\$1Vector3 Col2 { get; }](VRageMath.Matrix3x3.Col2)||
|\$1Vector3 Down { get; set; }](VRageMath.Matrix3x3.Down)|Gets and sets the down vector of the Matrix3x3.|
|\$1Vector3 Forward { get; set; }](VRageMath.Matrix3x3.Forward)|Gets and sets the forward vector of the Matrix3x3.|
|\$1float Item { get; set; }](VRageMath.Matrix3x3.Item)||
|\$1Vector3 Left { get; set; }](VRageMath.Matrix3x3.Left)|Gets and sets the left vector of the Matrix3x3.|
|\$1Vector3 Right { get; set; }](VRageMath.Matrix3x3.Right)|Gets and sets the right vector of the Matrix3x3.|
|\$1Vector3 Scale { get; }](VRageMath.Matrix3x3.Scale)||
|\$1Vector3 Up { get; set; }](VRageMath.Matrix3x3.Up)|Gets and sets the up vector of the Matrix3x3.|

#### Constructors

|Member|Description|
|---|---|
|\$1Matrix3x3(float, float, float, float, float, float, float, float, float)](VRageMath.Matrix3x3..ctor)||
|\$1Matrix3x3(Matrix3x3)](VRageMath.Matrix3x3..ctor)||
|\$1Matrix3x3(MatrixD)](VRageMath.Matrix3x3..ctor)||

#### Methods

|Member|Description|
|---|---|
|\$1static void Add(ref Matrix3x3, ref Matrix3x3, out Matrix3x3)](VRageMath.Matrix3x3.Add)|Adds a matrix to another matrix.|
|\$1static Matrix3x3 AlignRotationToAxes(ref Matrix3x3, ref Matrix3x3)](VRageMath.Matrix3x3.AlignRotationToAxes)||
|\$1static Matrix3x3 CreateFromAxisAngle(Vector3, float)](VRageMath.Matrix3x3.CreateFromAxisAngle)|Creates a new Matrix3x3 that rotates around an arbitrary vector.|
|\$1static void CreateFromAxisAngle(ref Vector3, float, out Matrix3x3)](VRageMath.Matrix3x3.CreateFromAxisAngle)|Creates a new Matrix3x3 that rotates around an arbitrary vector.|
|\$1static Matrix3x3 CreateFromDir(Vector3)](VRageMath.Matrix3x3.CreateFromDir)||
|\$1static Matrix3x3 CreateFromDir(Vector3, Vector3)](VRageMath.Matrix3x3.CreateFromDir)||
|\$1static Matrix3x3 CreateFromQuaternion(Quaternion)](VRageMath.Matrix3x3.CreateFromQuaternion)|Creates a rotation Matrix3x3 from a Quaternion.|
|\$1static void CreateFromQuaternion(ref Quaternion, out Matrix3x3)](VRageMath.Matrix3x3.CreateFromQuaternion)|Creates a rotation Matrix3x3 from a Quaternion.|
|\$1static Matrix3x3 CreateFromYawPitchRoll(float, float, float)](VRageMath.Matrix3x3.CreateFromYawPitchRoll)|Creates a new rotation matrix from a specified yaw, pitch, and roll.|
|\$1static void CreateFromYawPitchRoll(float, float, float, out Matrix3x3)](VRageMath.Matrix3x3.CreateFromYawPitchRoll)|Fills in a rotation matrix from a specified yaw, pitch, and roll.|
|\$1static void CreateRotationFromTwoVectors(ref Vector3, ref Vector3, out Matrix3x3)](VRageMath.Matrix3x3.CreateRotationFromTwoVectors)||
|\$1static Matrix3x3 CreateRotationX(float)](VRageMath.Matrix3x3.CreateRotationX)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|\$1static void CreateRotationX(float, out Matrix3x3)](VRageMath.Matrix3x3.CreateRotationX)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the x-axis.|
|\$1static Matrix3x3 CreateRotationY(float)](VRageMath.Matrix3x3.CreateRotationY)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|\$1static void CreateRotationY(float, out Matrix3x3)](VRageMath.Matrix3x3.CreateRotationY)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the y-axis.|
|\$1static Matrix3x3 CreateRotationZ(float)](VRageMath.Matrix3x3.CreateRotationZ)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|\$1static void CreateRotationZ(float, out Matrix3x3)](VRageMath.Matrix3x3.CreateRotationZ)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the z-axis.|
|\$1static Matrix3x3 CreateScale(float, float, float)](VRageMath.Matrix3x3.CreateScale)|Creates a scaling Matrix3x3.|
|\$1static void CreateScale(float, float, float, out Matrix3x3)](VRageMath.Matrix3x3.CreateScale)|Creates a scaling Matrix3x3.|
|\$1static Matrix3x3 CreateScale(Vector3)](VRageMath.Matrix3x3.CreateScale)|Creates a scaling Matrix3x3.|
|\$1static void CreateScale(ref Vector3, out Matrix3x3)](VRageMath.Matrix3x3.CreateScale)|Creates a scaling Matrix3x3.|
|\$1static Matrix3x3 CreateScale(float)](VRageMath.Matrix3x3.CreateScale)|Creates a scaling Matrix3x3.|
|\$1static void CreateScale(float, out Matrix3x3)](VRageMath.Matrix3x3.CreateScale)|Creates a scaling Matrix3x3.|
|\$1static Matrix3x3 CreateWorld(ref Vector3, ref Vector3)](VRageMath.Matrix3x3.CreateWorld)|Creates a world matrix with the specified parameters.|
|\$1static void Divide(ref Matrix3x3, ref Matrix3x3, out Matrix3x3)](VRageMath.Matrix3x3.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|\$1static void Divide(ref Matrix3x3, float, out Matrix3x3)](VRageMath.Matrix3x3.Divide)|Divides the components of a matrix by a scalar.|
|\$1static bool GetEulerAnglesXYZ(ref Matrix3x3, out Vector3)](VRageMath.Matrix3x3.GetEulerAnglesXYZ)||
|\$1static void Invert(ref Matrix3x3, out Matrix3x3)](VRageMath.Matrix3x3.Invert)|Calculates the inverse of a matrix.|
|\$1static void Lerp(ref Matrix3x3, ref Matrix3x3, float, out Matrix3x3)](VRageMath.Matrix3x3.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|\$1static void Multiply(ref Matrix3x3, ref Matrix3x3, out Matrix3x3)](VRageMath.Matrix3x3.Multiply)|Multiplies a matrix by another matrix.|
|\$1static void Multiply(ref Matrix3x3, float, out Matrix3x3)](VRageMath.Matrix3x3.Multiply)|Multiplies a matrix by a scalar value.|
|\$1static void Negate(ref Matrix3x3, out Matrix3x3)](VRageMath.Matrix3x3.Negate)|Negates individual elements of a matrix.|
|\$1static Matrix3x3 Normalize(Matrix3x3)](VRageMath.Matrix3x3.Normalize)||
|\$1static Matrix3x3 Orthogonalize(Matrix3x3)](VRageMath.Matrix3x3.Orthogonalize)||
|\$1static void Rescale(ref Matrix3x3, float)](VRageMath.Matrix3x3.Rescale)|Same result as Matrix3x3.CreateScale(scale) * matrix, but much faster|
|\$1static void Rescale(ref Matrix3x3, ref Vector3)](VRageMath.Matrix3x3.Rescale)|Same result as Matrix3x3.CreateScale(scale) * matrix, but much faster|
|\$1static Matrix3x3 Rescale(Matrix3x3, float)](VRageMath.Matrix3x3.Rescale)||
|\$1static Matrix3x3 Rescale(Matrix3x3, Vector3)](VRageMath.Matrix3x3.Rescale)||
|\$1static Matrix3x3 Round(ref Matrix3x3)](VRageMath.Matrix3x3.Round)||
|\$1static void Slerp(ref Matrix3x3, ref Matrix3x3, float, out Matrix3x3)](VRageMath.Matrix3x3.Slerp)|Performs spherical linear interpolation of position and rotation.|
|\$1static void SlerpScale(ref Matrix3x3, ref Matrix3x3, float, out Matrix3x3)](VRageMath.Matrix3x3.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|\$1static void Subtract(ref Matrix3x3, ref Matrix3x3, out Matrix3x3)](VRageMath.Matrix3x3.Subtract)|Subtracts matrices.|
|\$1static void Transform(ref Matrix3x3, ref Quaternion, out Matrix3x3)](VRageMath.Matrix3x3.Transform)|Transforms a Matrix3x3 by applying a Quaternion rotation.|
|\$1static void Transpose(ref Matrix3x3, out Matrix3x3)](VRageMath.Matrix3x3.Transpose)|Transposes the rows and columns of a matrix.|
|\$1void AssertIsValid()](VRageMath.Matrix3x3.AssertIsValid)||
|\$1float Determinant()](VRageMath.Matrix3x3.Determinant)||
|\$1bool Equals(Matrix3x3)](VRageMath.Matrix3x3.Equals)|Determines whether the specified Object is equal to the Matrix3x3.|
|\$1bool Equals(object)](VRageMath.Matrix3x3.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|\$1bool EqualsFast(ref Matrix3x3, \$1float])](VRageMath.Matrix3x3.EqualsFast)|Compares just position, forward and up|
|\$1Direction GetClosestDirection(Vector3)](VRageMath.Matrix3x3.GetClosestDirection)||
|\$1Direction GetClosestDirection(ref Vector3)](VRageMath.Matrix3x3.GetClosestDirection)||
|\$1Vector3 GetDirectionVector(Direction)](VRageMath.Matrix3x3.GetDirectionVector)||
|\$1int GetHashCode()](VRageMath.Matrix3x3.GetHashCode)|Gets the hash code of this object.|
|\$1Matrix3x3 GetOrientation()](VRageMath.Matrix3x3.GetOrientation)|Gets the orientation.|
|\$1Vector3 GetRow(int)](VRageMath.Matrix3x3.GetRow)||
|\$1bool IsMirrored()](VRageMath.Matrix3x3.IsMirrored)||
|\$1bool IsNan()](VRageMath.Matrix3x3.IsNan)||
|\$1bool IsOrthogonal()](VRageMath.Matrix3x3.IsOrthogonal)||
|\$1bool IsRotation()](VRageMath.Matrix3x3.IsRotation)||
|\$1bool IsValid()](VRageMath.Matrix3x3.IsValid)||
|\$1void SetDirectionVector(Direction, Vector3)](VRageMath.Matrix3x3.SetDirectionVector)||
|\$1void SetRow(int, Vector3)](VRageMath.Matrix3x3.SetRow)||
|\$1string ToString()](VRageMath.Matrix3x3.ToString)|Retrieves a string representation of the current object.|
|\$1void Transpose()](VRageMath.Matrix3x3.Transpose)||

