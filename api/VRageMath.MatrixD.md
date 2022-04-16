← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MatrixD Struct

```csharp
public struct MatrixD: IEquatable<MatrixD>
```

Defines a matrix.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable\<MatrixD>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[static MatrixD Identity](VRageMath.MatrixD.Identity)||
|[static MatrixD Zero](VRageMath.MatrixD.Zero)||
|[double M11](VRageMath.MatrixD.M11)|Value at row 1 column 1 of the matrix.|
|[double M12](VRageMath.MatrixD.M12)|Value at row 1 column 2 of the matrix.|
|[double M13](VRageMath.MatrixD.M13)|Value at row 1 column 3 of the matrix.|
|[double M14](VRageMath.MatrixD.M14)|Value at row 1 column 4 of the matrix.|
|[double M21](VRageMath.MatrixD.M21)|Value at row 2 column 1 of the matrix.|
|[double M22](VRageMath.MatrixD.M22)|Value at row 2 column 2 of the matrix.|
|[double M23](VRageMath.MatrixD.M23)|Value at row 2 column 3 of the matrix.|
|[double M24](VRageMath.MatrixD.M24)|Value at row 2 column 4 of the matrix.|
|[double M31](VRageMath.MatrixD.M31)|Value at row 3 column 1 of the matrix.|
|[double M32](VRageMath.MatrixD.M32)|Value at row 3 column 2 of the matrix.|
|[double M33](VRageMath.MatrixD.M33)|Value at row 3 column 3 of the matrix.|
|[double M34](VRageMath.MatrixD.M34)|Value at row 3 column 4 of the matrix.|
|[double M41](VRageMath.MatrixD.M41)|Value at row 4 column 1 of the matrix.|
|[double M42](VRageMath.MatrixD.M42)|Value at row 4 column 2 of the matrix.|
|[double M43](VRageMath.MatrixD.M43)|Value at row 4 column 3 of the matrix.|
|[double M44](VRageMath.MatrixD.M44)|Value at row 4 column 4 of the matrix.|

#### Properties

|Member|Description|
|---|---|
|[Vector3D Backward { get; set; }](VRageMath.MatrixD.Backward)|Gets and sets the backward vector of the Matrix.|
|[Vector3D Col0 { get; }](VRageMath.MatrixD.Col0)||
|[Vector3D Col1 { get; }](VRageMath.MatrixD.Col1)||
|[Vector3D Col2 { get; }](VRageMath.MatrixD.Col2)||
|[Vector3D Down { get; set; }](VRageMath.MatrixD.Down)|Gets and sets the down vector of the Matrix.|
|[Vector3D Forward { get; set; }](VRageMath.MatrixD.Forward)|Gets and sets the forward vector of the Matrix.|
|[double Item { get; set; }](VRageMath.MatrixD.Item)||
|[Vector3D Left { get; set; }](VRageMath.MatrixD.Left)|Gets and sets the left vector of the Matrix.|
|[Vector3D Right { get; set; }](VRageMath.MatrixD.Right)|Gets and sets the right vector of the Matrix.|
|[Matrix3x3 Rotation { get; }](VRageMath.MatrixD.Rotation)||
|[Vector3D Scale { get; }](VRageMath.MatrixD.Scale)||
|[Vector3D Translation { get; set; }](VRageMath.MatrixD.Translation)|Gets and sets the translation vector of the Matrix.|
|[Vector3D Up { get; set; }](VRageMath.MatrixD.Up)|Gets and sets the up vector of the Matrix.|

#### Constructors

|Member|Description|
|---|---|
|[MatrixD(double, double, double, double, double, double, double, double, double, double, double, double, double, double, double, double)](VRageMath.MatrixD..ctor)||
|[MatrixD(double, double, double, double, double, double, double, double, double)](VRageMath.MatrixD..ctor)||
|[MatrixD(Matrix)](VRageMath.MatrixD..ctor)||

#### Methods

|Member|Description|
|---|---|
|[static MatrixD Add(MatrixD, MatrixD)](VRageMath.MatrixD.Add)|Adds a matrix to another matrix.|
|[static void Add(ref MatrixD, ref MatrixD, out MatrixD)](VRageMath.MatrixD.Add)|Adds a matrix to another matrix.|
|[static MatrixD AlignRotationToAxes(ref MatrixD, ref MatrixD)](VRageMath.MatrixD.AlignRotationToAxes)||
|[static MatrixD CreateBillboard(Vector3D, Vector3D, Vector3D, Vector3D?)](VRageMath.MatrixD.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|[static void CreateBillboard(ref Vector3D, ref Vector3D, ref Vector3D, Vector3D?, out MatrixD)](VRageMath.MatrixD.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|[static MatrixD CreateConstrainedBillboard(Vector3D, Vector3D, Vector3D, Vector3D?, Vector3D?)](VRageMath.MatrixD.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|[static void CreateConstrainedBillboard(ref Vector3D, ref Vector3D, ref Vector3D, Vector3D?, Vector3D?, out MatrixD)](VRageMath.MatrixD.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|[static MatrixD CreateFromAxisAngle(Vector3D, double)](VRageMath.MatrixD.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|[static void CreateFromAxisAngle(ref Vector3D, double, out MatrixD)](VRageMath.MatrixD.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|[static MatrixD CreateFromDir(Vector3D)](VRageMath.MatrixD.CreateFromDir)||
|[static MatrixD CreateFromDir(Vector3D, Vector3D)](VRageMath.MatrixD.CreateFromDir)||
|[static MatrixD CreateFromQuaternion(Quaternion)](VRageMath.MatrixD.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|[static MatrixD CreateFromQuaternion(QuaternionD)](VRageMath.MatrixD.CreateFromQuaternion)||
|[static void CreateFromQuaternion(ref Quaternion, out MatrixD)](VRageMath.MatrixD.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|[static MatrixD CreateFromTransformScale(Quaternion, Vector3D, Vector3D)](VRageMath.MatrixD.CreateFromTransformScale)||
|[static MatrixD CreateFromYawPitchRoll(double, double, double)](VRageMath.MatrixD.CreateFromYawPitchRoll)|Creates a new rotation matrix from a specified yaw, pitch, and roll.|
|[static void CreateFromYawPitchRoll(double, double, double, out MatrixD)](VRageMath.MatrixD.CreateFromYawPitchRoll)|Fills in a rotation matrix from a specified yaw, pitch, and roll.|
|[static MatrixD CreateLookAt(Vector3D, Vector3D, Vector3)](VRageMath.MatrixD.CreateLookAt)||
|[static MatrixD CreateLookAt(Vector3D, Vector3D, Vector3D)](VRageMath.MatrixD.CreateLookAt)|Creates a view matrix.|
|[static void CreateLookAt(ref Vector3D, ref Vector3D, ref Vector3D, out MatrixD)](VRageMath.MatrixD.CreateLookAt)|Creates a view matrix.|
|[static MatrixD CreateLookAtInverse(Vector3D, Vector3D, Vector3D)](VRageMath.MatrixD.CreateLookAtInverse)||
|[static MatrixD CreateOrthographic(double, double, double, double)](VRageMath.MatrixD.CreateOrthographic)|Builds an orthogonal projection matrix.|
|[static void CreateOrthographic(double, double, double, double, out MatrixD)](VRageMath.MatrixD.CreateOrthographic)|Builds an orthogonal projection matrix.|
|[static MatrixD CreateOrthographicOffCenter(double, double, double, double, double, double)](VRageMath.MatrixD.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|[static void CreateOrthographicOffCenter(double, double, double, double, double, double, out MatrixD)](VRageMath.MatrixD.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|[static MatrixD CreatePerspective(double, double, double, double)](VRageMath.MatrixD.CreatePerspective)|Builds a perspective projection matrix and returns the result by value.|
|[static void CreatePerspective(double, double, double, double, out MatrixD)](VRageMath.MatrixD.CreatePerspective)|Builds a perspective projection matrix and returns the result by reference.|
|[static MatrixD CreatePerspectiveFieldOfView(double, double, double, double)](VRageMath.MatrixD.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by value.|
|[static void CreatePerspectiveFieldOfView(double, double, double, double, out MatrixD)](VRageMath.MatrixD.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by reference.|
|[static MatrixD CreatePerspectiveOffCenter(double, double, double, double, double, double)](VRageMath.MatrixD.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|[static void CreatePerspectiveOffCenter(double, double, double, double, double, double, out MatrixD)](VRageMath.MatrixD.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|[static MatrixD CreateReflection(Plane)](VRageMath.MatrixD.CreateReflection)|Creates a Matrix that reflects the coordinate system about a specified Plane.|
|[static void CreateReflection(ref Plane, out MatrixD)](VRageMath.MatrixD.CreateReflection)|Fills in an existing Matrix so that it reflects the coordinate system about a specified Plane.|
|[static MatrixD CreateRotationX(double)](VRageMath.MatrixD.CreateRotationX)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|[static void CreateRotationX(double, out MatrixD)](VRageMath.MatrixD.CreateRotationX)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the x-axis.|
|[static MatrixD CreateRotationY(double)](VRageMath.MatrixD.CreateRotationY)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|[static void CreateRotationY(double, out MatrixD)](VRageMath.MatrixD.CreateRotationY)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the y-axis.|
|[static MatrixD CreateRotationZ(double)](VRageMath.MatrixD.CreateRotationZ)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|[static void CreateRotationZ(double, out MatrixD)](VRageMath.MatrixD.CreateRotationZ)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the z-axis.|
|[static MatrixD CreateScale(double, double, double)](VRageMath.MatrixD.CreateScale)|Creates a scaling Matrix.|
|[static void CreateScale(double, double, double, out MatrixD)](VRageMath.MatrixD.CreateScale)|Creates a scaling Matrix.|
|[static MatrixD CreateScale(Vector3D)](VRageMath.MatrixD.CreateScale)|Creates a scaling Matrix.|
|[static void CreateScale(ref Vector3D, out MatrixD)](VRageMath.MatrixD.CreateScale)|Creates a scaling Matrix.|
|[static MatrixD CreateScale(double)](VRageMath.MatrixD.CreateScale)|Creates a scaling Matrix.|
|[static void CreateScale(double, out MatrixD)](VRageMath.MatrixD.CreateScale)|Creates a scaling Matrix.|
|[static MatrixD CreateShadow(Vector3D, Plane)](VRageMath.MatrixD.CreateShadow)|Creates a Matrix that flattens geometry into a specified Plane as if casting a shadow from a specified light source.|
|[static void CreateShadow(ref Vector3D, ref Plane, out MatrixD)](VRageMath.MatrixD.CreateShadow)|Fills in a Matrix to flatten geometry into a specified Plane as if casting a shadow from a specified light source.|
|[static MatrixD CreateTranslation(Vector3D)](VRageMath.MatrixD.CreateTranslation)|Creates a translation Matrix.|
|[static MatrixD CreateTranslation(Vector3)](VRageMath.MatrixD.CreateTranslation)||
|[static void CreateTranslation(ref Vector3D, out MatrixD)](VRageMath.MatrixD.CreateTranslation)|Creates a translation Matrix.|
|[static MatrixD CreateTranslation(double, double, double)](VRageMath.MatrixD.CreateTranslation)|Creates a translation Matrix.|
|[static void CreateTranslation(double, double, double, out MatrixD)](VRageMath.MatrixD.CreateTranslation)|Creates a translation Matrix.|
|[static MatrixD CreateWorld(Vector3D, Vector3, Vector3)](VRageMath.MatrixD.CreateWorld)||
|[static MatrixD CreateWorld(Vector3D)](VRageMath.MatrixD.CreateWorld)||
|[static MatrixD CreateWorld(Vector3D, Vector3D, Vector3D)](VRageMath.MatrixD.CreateWorld)|Creates a world matrix with the specified parameters.|
|[static void CreateWorld(ref Vector3D, ref Vector3D, ref Vector3D, out MatrixD)](VRageMath.MatrixD.CreateWorld)|Creates a world matrix with the specified parameters.|
|[static MatrixD Divide(MatrixD, MatrixD)](VRageMath.MatrixD.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|[static void Divide(ref MatrixD, ref MatrixD, out MatrixD)](VRageMath.MatrixD.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|[static MatrixD Divide(MatrixD, double)](VRageMath.MatrixD.Divide)|Divides the components of a matrix by a scalar.|
|[static void Divide(ref MatrixD, double, out MatrixD)](VRageMath.MatrixD.Divide)|Divides the components of a matrix by a scalar.|
|[static bool GetEulerAnglesXYZ(ref MatrixD, out Vector3D)](VRageMath.MatrixD.GetEulerAnglesXYZ)||
|[static MatrixD Invert(MatrixD)](VRageMath.MatrixD.Invert)|Calculates the inverse of a matrix.|
|[static MatrixD Invert(ref MatrixD)](VRageMath.MatrixD.Invert)||
|[static void Invert(ref MatrixD, out MatrixD)](VRageMath.MatrixD.Invert)|Calculates the inverse of a matrix.|
|[static MatrixD Lerp(MatrixD, MatrixD, double)](VRageMath.MatrixD.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|[static void Lerp(ref MatrixD, ref MatrixD, double, out MatrixD)](VRageMath.MatrixD.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|[static MatrixD Multiply(MatrixD, MatrixD)](VRageMath.MatrixD.Multiply)|Multiplies a matrix by another matrix.|
|[static MatrixD Multiply(MatrixD, Matrix)](VRageMath.MatrixD.Multiply)|Multiplies a matrix by another matrix.|
|[static void Multiply(ref MatrixD, ref Matrix, out MatrixD)](VRageMath.MatrixD.Multiply)|Multiplies a matrix by another matrix.|
|[static void Multiply(ref Matrix, ref MatrixD, out MatrixD)](VRageMath.MatrixD.Multiply)||
|[static void Multiply(ref MatrixD, ref MatrixD, out MatrixD)](VRageMath.MatrixD.Multiply)|Multiplies a matrix by another matrix.|
|[static MatrixD Multiply(MatrixD, double)](VRageMath.MatrixD.Multiply)|Multiplies a matrix by a scalar value.|
|[static void Multiply(ref MatrixD, double, out MatrixD)](VRageMath.MatrixD.Multiply)|Multiplies a matrix by a scalar value.|
|[static MatrixD Negate(MatrixD)](VRageMath.MatrixD.Negate)|Negates individual elements of a matrix.|
|[static void Negate(ref MatrixD, out MatrixD)](VRageMath.MatrixD.Negate)|Negates individual elements of a matrix.|
|[static MatrixD Normalize(MatrixD)](VRageMath.MatrixD.Normalize)||
|[static MatrixD Orthogonalize(MatrixD)](VRageMath.MatrixD.Orthogonalize)||
|[static void Rescale(ref MatrixD, double)](VRageMath.MatrixD.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|[static void Rescale(ref MatrixD, float)](VRageMath.MatrixD.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|[static void Rescale(ref MatrixD, ref Vector3D)](VRageMath.MatrixD.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|[static MatrixD Rescale(MatrixD, double)](VRageMath.MatrixD.Rescale)||
|[static MatrixD Rescale(MatrixD, Vector3D)](VRageMath.MatrixD.Rescale)||
|[static void Slerp(ref MatrixD, ref MatrixD, double, out MatrixD)](VRageMath.MatrixD.Slerp)|Performs spherical linear interpolation of position and rotation.|
|[static MatrixD Slerp(MatrixD, MatrixD, double)](VRageMath.MatrixD.Slerp)|Performs spherical linear interpolation of position and rotation.|
|[static void SlerpScale(ref MatrixD, ref MatrixD, double, out MatrixD)](VRageMath.MatrixD.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|[static void SlerpScale(MatrixD, MatrixD, double, out MatrixD)](VRageMath.MatrixD.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|[static MatrixD SlerpScale(MatrixD, MatrixD, double)](VRageMath.MatrixD.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|[static void Subtract(ref MatrixD, ref MatrixD, out MatrixD)](VRageMath.MatrixD.Subtract)|Subtracts matrices.|
|[static Matrix Subtract(Matrix, Matrix)](VRageMath.MatrixD.Subtract)|Subtracts matrices.|
|[static MatrixD SwapYZCoordinates(MatrixD)](VRageMath.MatrixD.SwapYZCoordinates)||
|[static MatrixD Transform(MatrixD, Quaternion)](VRageMath.MatrixD.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|[static void Transform(ref MatrixD, ref Quaternion, out MatrixD)](VRageMath.MatrixD.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|[static MatrixD Transpose(MatrixD)](VRageMath.MatrixD.Transpose)|Transposes the rows and columns of a matrix.|
|[static void Transpose(ref MatrixD, out MatrixD)](VRageMath.MatrixD.Transpose)|Transposes the rows and columns of a matrix.|
|[void AssertIsValid(\[string])](VRageMath.MatrixD.AssertIsValid)||
|[double Determinant()](VRageMath.MatrixD.Determinant)|Calculates the determinant of the matrix.|
|[bool Equals(MatrixD)](VRageMath.MatrixD.Equals)|Determines whether the specified Object is equal to the Matrix.|
|[bool Equals(object)](VRageMath.MatrixD.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[bool EqualsFast(ref MatrixD, \[double])](VRageMath.MatrixD.EqualsFast)|Compares just position, forward and up|
|[Direction GetClosestDirection(Vector3D)](VRageMath.MatrixD.GetClosestDirection)||
|[Direction GetClosestDirection(ref Vector3D)](VRageMath.MatrixD.GetClosestDirection)||
|[Vector3D GetDirectionVector(Direction)](VRageMath.MatrixD.GetDirectionVector)||
|[int GetHashCode()](VRageMath.MatrixD.GetHashCode)|Gets the hash code of this object.|
|[MatrixD GetOrientation()](VRageMath.MatrixD.GetOrientation)|Gets the orientation.|
|[Vector4D GetRow(int)](VRageMath.MatrixD.GetRow)||
|[bool HasNoTranslationOrPerspective()](VRageMath.MatrixD.HasNoTranslationOrPerspective)|Returns true if this matrix represents invertible (you can call Invert on it) linear (it does not contain translation or perspective transformation) transformation. Such matrix consist solely of rotations, shearing, mirroring and scaling. It can be orthogonalized to create an orthogonal rotation matrix.|
|[bool IsMirrored()](VRageMath.MatrixD.IsMirrored)||
|[bool IsNan()](VRageMath.MatrixD.IsNan)||
|[bool IsOrthogonal()](VRageMath.MatrixD.IsOrthogonal)||
|[bool IsOrthogonal(double)](VRageMath.MatrixD.IsOrthogonal)||
|[bool IsRotation()](VRageMath.MatrixD.IsRotation)||
|[bool IsValid()](VRageMath.MatrixD.IsValid)||
|[void Orthogonalize()](VRageMath.MatrixD.Orthogonalize)||
|[void SetDirectionVector(Direction, Vector3D)](VRageMath.MatrixD.SetDirectionVector)||
|[void SetFrom(ref Matrix)](VRageMath.MatrixD.SetFrom)||
|[void SetRotationAndScale(ref Matrix)](VRageMath.MatrixD.SetRotationAndScale)||
|[void SetRow(int, Vector4)](VRageMath.MatrixD.SetRow)||
|[string ToString()](VRageMath.MatrixD.ToString)|Retrieves a string representation of the current object.|

