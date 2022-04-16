← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MatrixD Struct

```csharp
public struct MatrixD: IEquatable<MatrixD\>
```

Defines a matrix.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<MatrixD\>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\$1static MatrixD Identity](VRageMath.MatrixD.Identity)||
|\$1static MatrixD Zero](VRageMath.MatrixD.Zero)||
|\$1double M11](VRageMath.MatrixD.M11)|Value at row 1 column 1 of the matrix.|
|\$1double M12](VRageMath.MatrixD.M12)|Value at row 1 column 2 of the matrix.|
|\$1double M13](VRageMath.MatrixD.M13)|Value at row 1 column 3 of the matrix.|
|\$1double M14](VRageMath.MatrixD.M14)|Value at row 1 column 4 of the matrix.|
|\$1double M21](VRageMath.MatrixD.M21)|Value at row 2 column 1 of the matrix.|
|\$1double M22](VRageMath.MatrixD.M22)|Value at row 2 column 2 of the matrix.|
|\$1double M23](VRageMath.MatrixD.M23)|Value at row 2 column 3 of the matrix.|
|\$1double M24](VRageMath.MatrixD.M24)|Value at row 2 column 4 of the matrix.|
|\$1double M31](VRageMath.MatrixD.M31)|Value at row 3 column 1 of the matrix.|
|\$1double M32](VRageMath.MatrixD.M32)|Value at row 3 column 2 of the matrix.|
|\$1double M33](VRageMath.MatrixD.M33)|Value at row 3 column 3 of the matrix.|
|\$1double M34](VRageMath.MatrixD.M34)|Value at row 3 column 4 of the matrix.|
|\$1double M41](VRageMath.MatrixD.M41)|Value at row 4 column 1 of the matrix.|
|\$1double M42](VRageMath.MatrixD.M42)|Value at row 4 column 2 of the matrix.|
|\$1double M43](VRageMath.MatrixD.M43)|Value at row 4 column 3 of the matrix.|
|\$1double M44](VRageMath.MatrixD.M44)|Value at row 4 column 4 of the matrix.|

#### Properties

|Member|Description|
|---|---|
|\$1Vector3D Backward { get; set; }](VRageMath.MatrixD.Backward)|Gets and sets the backward vector of the Matrix.|
|\$1Vector3D Col0 { get; }](VRageMath.MatrixD.Col0)||
|\$1Vector3D Col1 { get; }](VRageMath.MatrixD.Col1)||
|\$1Vector3D Col2 { get; }](VRageMath.MatrixD.Col2)||
|\$1Vector3D Down { get; set; }](VRageMath.MatrixD.Down)|Gets and sets the down vector of the Matrix.|
|\$1Vector3D Forward { get; set; }](VRageMath.MatrixD.Forward)|Gets and sets the forward vector of the Matrix.|
|\$1double Item { get; set; }](VRageMath.MatrixD.Item)||
|\$1Vector3D Left { get; set; }](VRageMath.MatrixD.Left)|Gets and sets the left vector of the Matrix.|
|\$1Vector3D Right { get; set; }](VRageMath.MatrixD.Right)|Gets and sets the right vector of the Matrix.|
|\$1Matrix3x3 Rotation { get; }](VRageMath.MatrixD.Rotation)||
|\$1Vector3D Scale { get; }](VRageMath.MatrixD.Scale)||
|\$1Vector3D Translation { get; set; }](VRageMath.MatrixD.Translation)|Gets and sets the translation vector of the Matrix.|
|\$1Vector3D Up { get; set; }](VRageMath.MatrixD.Up)|Gets and sets the up vector of the Matrix.|

#### Constructors

|Member|Description|
|---|---|
|\$1MatrixD(double, double, double, double, double, double, double, double, double, double, double, double, double, double, double, double)](VRageMath.MatrixD..ctor)||
|\$1MatrixD(double, double, double, double, double, double, double, double, double)](VRageMath.MatrixD..ctor)||
|\$1MatrixD(Matrix)](VRageMath.MatrixD..ctor)||

#### Methods

|Member|Description|
|---|---|
|\$1static MatrixD Add(MatrixD, MatrixD)](VRageMath.MatrixD.Add)|Adds a matrix to another matrix.|
|\$1static void Add(ref MatrixD, ref MatrixD, out MatrixD)](VRageMath.MatrixD.Add)|Adds a matrix to another matrix.|
|\$1static MatrixD AlignRotationToAxes(ref MatrixD, ref MatrixD)](VRageMath.MatrixD.AlignRotationToAxes)||
|\$1static MatrixD CreateBillboard(Vector3D, Vector3D, Vector3D, Vector3D?)](VRageMath.MatrixD.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|\$1static void CreateBillboard(ref Vector3D, ref Vector3D, ref Vector3D, Vector3D?, out MatrixD)](VRageMath.MatrixD.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|\$1static MatrixD CreateConstrainedBillboard(Vector3D, Vector3D, Vector3D, Vector3D?, Vector3D?)](VRageMath.MatrixD.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|\$1static void CreateConstrainedBillboard(ref Vector3D, ref Vector3D, ref Vector3D, Vector3D?, Vector3D?, out MatrixD)](VRageMath.MatrixD.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|\$1static MatrixD CreateFromAxisAngle(Vector3D, double)](VRageMath.MatrixD.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|\$1static void CreateFromAxisAngle(ref Vector3D, double, out MatrixD)](VRageMath.MatrixD.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|\$1static MatrixD CreateFromDir(Vector3D)](VRageMath.MatrixD.CreateFromDir)||
|\$1static MatrixD CreateFromDir(Vector3D, Vector3D)](VRageMath.MatrixD.CreateFromDir)||
|\$1static MatrixD CreateFromQuaternion(Quaternion)](VRageMath.MatrixD.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|\$1static MatrixD CreateFromQuaternion(QuaternionD)](VRageMath.MatrixD.CreateFromQuaternion)||
|\$1static void CreateFromQuaternion(ref Quaternion, out MatrixD)](VRageMath.MatrixD.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|\$1static MatrixD CreateFromTransformScale(Quaternion, Vector3D, Vector3D)](VRageMath.MatrixD.CreateFromTransformScale)||
|\$1static MatrixD CreateFromYawPitchRoll(double, double, double)](VRageMath.MatrixD.CreateFromYawPitchRoll)|Creates a new rotation matrix from a specified yaw, pitch, and roll.|
|\$1static void CreateFromYawPitchRoll(double, double, double, out MatrixD)](VRageMath.MatrixD.CreateFromYawPitchRoll)|Fills in a rotation matrix from a specified yaw, pitch, and roll.|
|\$1static MatrixD CreateLookAt(Vector3D, Vector3D, Vector3)](VRageMath.MatrixD.CreateLookAt)||
|\$1static MatrixD CreateLookAt(Vector3D, Vector3D, Vector3D)](VRageMath.MatrixD.CreateLookAt)|Creates a view matrix.|
|\$1static void CreateLookAt(ref Vector3D, ref Vector3D, ref Vector3D, out MatrixD)](VRageMath.MatrixD.CreateLookAt)|Creates a view matrix.|
|\$1static MatrixD CreateLookAtInverse(Vector3D, Vector3D, Vector3D)](VRageMath.MatrixD.CreateLookAtInverse)||
|\$1static MatrixD CreateOrthographic(double, double, double, double)](VRageMath.MatrixD.CreateOrthographic)|Builds an orthogonal projection matrix.|
|\$1static void CreateOrthographic(double, double, double, double, out MatrixD)](VRageMath.MatrixD.CreateOrthographic)|Builds an orthogonal projection matrix.|
|\$1static MatrixD CreateOrthographicOffCenter(double, double, double, double, double, double)](VRageMath.MatrixD.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|\$1static void CreateOrthographicOffCenter(double, double, double, double, double, double, out MatrixD)](VRageMath.MatrixD.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|\$1static MatrixD CreatePerspective(double, double, double, double)](VRageMath.MatrixD.CreatePerspective)|Builds a perspective projection matrix and returns the result by value.|
|\$1static void CreatePerspective(double, double, double, double, out MatrixD)](VRageMath.MatrixD.CreatePerspective)|Builds a perspective projection matrix and returns the result by reference.|
|\$1static MatrixD CreatePerspectiveFieldOfView(double, double, double, double)](VRageMath.MatrixD.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by value.|
|\$1static void CreatePerspectiveFieldOfView(double, double, double, double, out MatrixD)](VRageMath.MatrixD.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by reference.|
|\$1static MatrixD CreatePerspectiveOffCenter(double, double, double, double, double, double)](VRageMath.MatrixD.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|\$1static void CreatePerspectiveOffCenter(double, double, double, double, double, double, out MatrixD)](VRageMath.MatrixD.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|\$1static MatrixD CreateReflection(Plane)](VRageMath.MatrixD.CreateReflection)|Creates a Matrix that reflects the coordinate system about a specified Plane.|
|\$1static void CreateReflection(ref Plane, out MatrixD)](VRageMath.MatrixD.CreateReflection)|Fills in an existing Matrix so that it reflects the coordinate system about a specified Plane.|
|\$1static MatrixD CreateRotationX(double)](VRageMath.MatrixD.CreateRotationX)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|\$1static void CreateRotationX(double, out MatrixD)](VRageMath.MatrixD.CreateRotationX)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the x-axis.|
|\$1static MatrixD CreateRotationY(double)](VRageMath.MatrixD.CreateRotationY)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|\$1static void CreateRotationY(double, out MatrixD)](VRageMath.MatrixD.CreateRotationY)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the y-axis.|
|\$1static MatrixD CreateRotationZ(double)](VRageMath.MatrixD.CreateRotationZ)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|\$1static void CreateRotationZ(double, out MatrixD)](VRageMath.MatrixD.CreateRotationZ)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the z-axis.|
|\$1static MatrixD CreateScale(double, double, double)](VRageMath.MatrixD.CreateScale)|Creates a scaling Matrix.|
|\$1static void CreateScale(double, double, double, out MatrixD)](VRageMath.MatrixD.CreateScale)|Creates a scaling Matrix.|
|\$1static MatrixD CreateScale(Vector3D)](VRageMath.MatrixD.CreateScale)|Creates a scaling Matrix.|
|\$1static void CreateScale(ref Vector3D, out MatrixD)](VRageMath.MatrixD.CreateScale)|Creates a scaling Matrix.|
|\$1static MatrixD CreateScale(double)](VRageMath.MatrixD.CreateScale)|Creates a scaling Matrix.|
|\$1static void CreateScale(double, out MatrixD)](VRageMath.MatrixD.CreateScale)|Creates a scaling Matrix.|
|\$1static MatrixD CreateShadow(Vector3D, Plane)](VRageMath.MatrixD.CreateShadow)|Creates a Matrix that flattens geometry into a specified Plane as if casting a shadow from a specified light source.|
|\$1static void CreateShadow(ref Vector3D, ref Plane, out MatrixD)](VRageMath.MatrixD.CreateShadow)|Fills in a Matrix to flatten geometry into a specified Plane as if casting a shadow from a specified light source.|
|\$1static MatrixD CreateTranslation(Vector3D)](VRageMath.MatrixD.CreateTranslation)|Creates a translation Matrix.|
|\$1static MatrixD CreateTranslation(Vector3)](VRageMath.MatrixD.CreateTranslation)||
|\$1static void CreateTranslation(ref Vector3D, out MatrixD)](VRageMath.MatrixD.CreateTranslation)|Creates a translation Matrix.|
|\$1static MatrixD CreateTranslation(double, double, double)](VRageMath.MatrixD.CreateTranslation)|Creates a translation Matrix.|
|\$1static void CreateTranslation(double, double, double, out MatrixD)](VRageMath.MatrixD.CreateTranslation)|Creates a translation Matrix.|
|\$1static MatrixD CreateWorld(Vector3D, Vector3, Vector3)](VRageMath.MatrixD.CreateWorld)||
|\$1static MatrixD CreateWorld(Vector3D)](VRageMath.MatrixD.CreateWorld)||
|\$1static MatrixD CreateWorld(Vector3D, Vector3D, Vector3D)](VRageMath.MatrixD.CreateWorld)|Creates a world matrix with the specified parameters.|
|\$1static void CreateWorld(ref Vector3D, ref Vector3D, ref Vector3D, out MatrixD)](VRageMath.MatrixD.CreateWorld)|Creates a world matrix with the specified parameters.|
|\$1static MatrixD Divide(MatrixD, MatrixD)](VRageMath.MatrixD.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|\$1static void Divide(ref MatrixD, ref MatrixD, out MatrixD)](VRageMath.MatrixD.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|\$1static MatrixD Divide(MatrixD, double)](VRageMath.MatrixD.Divide)|Divides the components of a matrix by a scalar.|
|\$1static void Divide(ref MatrixD, double, out MatrixD)](VRageMath.MatrixD.Divide)|Divides the components of a matrix by a scalar.|
|\$1static bool GetEulerAnglesXYZ(ref MatrixD, out Vector3D)](VRageMath.MatrixD.GetEulerAnglesXYZ)||
|\$1static MatrixD Invert(MatrixD)](VRageMath.MatrixD.Invert)|Calculates the inverse of a matrix.|
|\$1static MatrixD Invert(ref MatrixD)](VRageMath.MatrixD.Invert)||
|\$1static void Invert(ref MatrixD, out MatrixD)](VRageMath.MatrixD.Invert)|Calculates the inverse of a matrix.|
|\$1static MatrixD Lerp(MatrixD, MatrixD, double)](VRageMath.MatrixD.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|\$1static void Lerp(ref MatrixD, ref MatrixD, double, out MatrixD)](VRageMath.MatrixD.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|\$1static MatrixD Multiply(MatrixD, MatrixD)](VRageMath.MatrixD.Multiply)|Multiplies a matrix by another matrix.|
|\$1static MatrixD Multiply(MatrixD, Matrix)](VRageMath.MatrixD.Multiply)|Multiplies a matrix by another matrix.|
|\$1static void Multiply(ref MatrixD, ref Matrix, out MatrixD)](VRageMath.MatrixD.Multiply)|Multiplies a matrix by another matrix.|
|\$1static void Multiply(ref Matrix, ref MatrixD, out MatrixD)](VRageMath.MatrixD.Multiply)||
|\$1static void Multiply(ref MatrixD, ref MatrixD, out MatrixD)](VRageMath.MatrixD.Multiply)|Multiplies a matrix by another matrix.|
|\$1static MatrixD Multiply(MatrixD, double)](VRageMath.MatrixD.Multiply)|Multiplies a matrix by a scalar value.|
|\$1static void Multiply(ref MatrixD, double, out MatrixD)](VRageMath.MatrixD.Multiply)|Multiplies a matrix by a scalar value.|
|\$1static MatrixD Negate(MatrixD)](VRageMath.MatrixD.Negate)|Negates individual elements of a matrix.|
|\$1static void Negate(ref MatrixD, out MatrixD)](VRageMath.MatrixD.Negate)|Negates individual elements of a matrix.|
|\$1static MatrixD Normalize(MatrixD)](VRageMath.MatrixD.Normalize)||
|\$1static MatrixD Orthogonalize(MatrixD)](VRageMath.MatrixD.Orthogonalize)||
|\$1static void Rescale(ref MatrixD, double)](VRageMath.MatrixD.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|\$1static void Rescale(ref MatrixD, float)](VRageMath.MatrixD.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|\$1static void Rescale(ref MatrixD, ref Vector3D)](VRageMath.MatrixD.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|\$1static MatrixD Rescale(MatrixD, double)](VRageMath.MatrixD.Rescale)||
|\$1static MatrixD Rescale(MatrixD, Vector3D)](VRageMath.MatrixD.Rescale)||
|\$1static void Slerp(ref MatrixD, ref MatrixD, double, out MatrixD)](VRageMath.MatrixD.Slerp)|Performs spherical linear interpolation of position and rotation.|
|\$1static MatrixD Slerp(MatrixD, MatrixD, double)](VRageMath.MatrixD.Slerp)|Performs spherical linear interpolation of position and rotation.|
|\$1static void SlerpScale(ref MatrixD, ref MatrixD, double, out MatrixD)](VRageMath.MatrixD.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|\$1static void SlerpScale(MatrixD, MatrixD, double, out MatrixD)](VRageMath.MatrixD.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|\$1static MatrixD SlerpScale(MatrixD, MatrixD, double)](VRageMath.MatrixD.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|\$1static void Subtract(ref MatrixD, ref MatrixD, out MatrixD)](VRageMath.MatrixD.Subtract)|Subtracts matrices.|
|\$1static Matrix Subtract(Matrix, Matrix)](VRageMath.MatrixD.Subtract)|Subtracts matrices.|
|\$1static MatrixD SwapYZCoordinates(MatrixD)](VRageMath.MatrixD.SwapYZCoordinates)||
|\$1static MatrixD Transform(MatrixD, Quaternion)](VRageMath.MatrixD.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|\$1static void Transform(ref MatrixD, ref Quaternion, out MatrixD)](VRageMath.MatrixD.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|\$1static MatrixD Transpose(MatrixD)](VRageMath.MatrixD.Transpose)|Transposes the rows and columns of a matrix.|
|\$1static void Transpose(ref MatrixD, out MatrixD)](VRageMath.MatrixD.Transpose)|Transposes the rows and columns of a matrix.|
|\$1void AssertIsValid(\$1string])](VRageMath.MatrixD.AssertIsValid)||
|\$1double Determinant()](VRageMath.MatrixD.Determinant)|Calculates the determinant of the matrix.|
|\$1bool Equals(MatrixD)](VRageMath.MatrixD.Equals)|Determines whether the specified Object is equal to the Matrix.|
|\$1bool Equals(object)](VRageMath.MatrixD.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|\$1bool EqualsFast(ref MatrixD, \$1double])](VRageMath.MatrixD.EqualsFast)|Compares just position, forward and up|
|\$1Direction GetClosestDirection(Vector3D)](VRageMath.MatrixD.GetClosestDirection)||
|\$1Direction GetClosestDirection(ref Vector3D)](VRageMath.MatrixD.GetClosestDirection)||
|\$1Vector3D GetDirectionVector(Direction)](VRageMath.MatrixD.GetDirectionVector)||
|\$1int GetHashCode()](VRageMath.MatrixD.GetHashCode)|Gets the hash code of this object.|
|\$1MatrixD GetOrientation()](VRageMath.MatrixD.GetOrientation)|Gets the orientation.|
|\$1Vector4D GetRow(int)](VRageMath.MatrixD.GetRow)||
|\$1bool HasNoTranslationOrPerspective()](VRageMath.MatrixD.HasNoTranslationOrPerspective)|Returns true if this matrix represents invertible (you can call Invert on it) linear (it does not contain translation or perspective transformation) transformation. Such matrix consist solely of rotations, shearing, mirroring and scaling. It can be orthogonalized to create an orthogonal rotation matrix.|
|\$1bool IsMirrored()](VRageMath.MatrixD.IsMirrored)||
|\$1bool IsNan()](VRageMath.MatrixD.IsNan)||
|\$1bool IsOrthogonal()](VRageMath.MatrixD.IsOrthogonal)||
|\$1bool IsOrthogonal(double)](VRageMath.MatrixD.IsOrthogonal)||
|\$1bool IsRotation()](VRageMath.MatrixD.IsRotation)||
|\$1bool IsValid()](VRageMath.MatrixD.IsValid)||
|\$1void Orthogonalize()](VRageMath.MatrixD.Orthogonalize)||
|\$1void SetDirectionVector(Direction, Vector3D)](VRageMath.MatrixD.SetDirectionVector)||
|\$1void SetFrom(ref Matrix)](VRageMath.MatrixD.SetFrom)||
|\$1void SetRotationAndScale(ref Matrix)](VRageMath.MatrixD.SetRotationAndScale)||
|\$1void SetRow(int, Vector4)](VRageMath.MatrixD.SetRow)||
|\$1string ToString()](VRageMath.MatrixD.ToString)|Retrieves a string representation of the current object.|

