← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MatrixD Struct

```csharp
public struct MatrixD: IEquatable<VRageMath.MatrixD>
```

Defines a matrix.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<VRageMath.MatrixD>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[M11](VRageMath.MatrixD.M11)|Value at row 1 column 1 of the matrix.|
|[M12](VRageMath.MatrixD.M12)|Value at row 1 column 2 of the matrix.|
|[M13](VRageMath.MatrixD.M13)|Value at row 1 column 3 of the matrix.|
|[M14](VRageMath.MatrixD.M14)|Value at row 1 column 4 of the matrix.|
|[M21](VRageMath.MatrixD.M21)|Value at row 2 column 1 of the matrix.|
|[M22](VRageMath.MatrixD.M22)|Value at row 2 column 2 of the matrix.|
|[M23](VRageMath.MatrixD.M23)|Value at row 2 column 3 of the matrix.|
|[M24](VRageMath.MatrixD.M24)|Value at row 2 column 4 of the matrix.|
|[M31](VRageMath.MatrixD.M31)|Value at row 3 column 1 of the matrix.|
|[M32](VRageMath.MatrixD.M32)|Value at row 3 column 2 of the matrix.|
|[M33](VRageMath.MatrixD.M33)|Value at row 3 column 3 of the matrix.|
|[M34](VRageMath.MatrixD.M34)|Value at row 3 column 4 of the matrix.|
|[M41](VRageMath.MatrixD.M41)|Value at row 4 column 1 of the matrix.|
|[M42](VRageMath.MatrixD.M42)|Value at row 4 column 2 of the matrix.|
|[M43](VRageMath.MatrixD.M43)|Value at row 4 column 3 of the matrix.|
|[M44](VRageMath.MatrixD.M44)|Value at row 4 column 4 of the matrix.|
|[Identity](VRageMath.MatrixD.Identity)||
|[Zero](VRageMath.MatrixD.Zero)||

#### Properties

|Member|Description|
|---|---|
|[Col0 { get; }](VRageMath.MatrixD.Col0)||
|[Col1 { get; }](VRageMath.MatrixD.Col1)||
|[Col2 { get; }](VRageMath.MatrixD.Col2)||
|[Up { get; set; }](VRageMath.MatrixD.Up)|Gets and sets the up vector of the Matrix.|
|[Down { get; set; }](VRageMath.MatrixD.Down)|Gets and sets the down vector of the Matrix.|
|[Right { get; set; }](VRageMath.MatrixD.Right)|Gets and sets the right vector of the Matrix.|
|[Left { get; set; }](VRageMath.MatrixD.Left)|Gets and sets the left vector of the Matrix.|
|[Forward { get; set; }](VRageMath.MatrixD.Forward)|Gets and sets the forward vector of the Matrix.|
|[Backward { get; set; }](VRageMath.MatrixD.Backward)|Gets and sets the backward vector of the Matrix.|
|[Scale { get; }](VRageMath.MatrixD.Scale)||
|[Translation { get; set; }](VRageMath.MatrixD.Translation)|Gets and sets the translation vector of the Matrix.|
|[Rotation { get; }](VRageMath.MatrixD.Rotation)||
|[Item { get; set; }](VRageMath.MatrixD.Item)||

#### Constructors

|Member|Description|
|---|---|
|[MatrixD(double, double, double, double, double, double, double, double, double, double, double, double, double, double, double, double)](VRageMath.MatrixD..ctor)||
|[MatrixD(double, double, double, double, double, double, double, double, double)](VRageMath.MatrixD..ctor)||
|[MatrixD(Matrix)](VRageMath.MatrixD..ctor)||

#### Methods

|Member|Description|
|---|---|
|[Subtract(ref MatrixD, ref MatrixD, out MatrixD)](VRageMath.MatrixD.Subtract)|Subtracts matrices.|
|[Multiply(MatrixD, MatrixD)](VRageMath.MatrixD.Multiply)|Multiplies a matrix by another matrix.|
|[Multiply(MatrixD, Matrix)](VRageMath.MatrixD.Multiply)|Multiplies a matrix by another matrix.|
|[Multiply(ref MatrixD, ref Matrix, out MatrixD)](VRageMath.MatrixD.Multiply)|Multiplies a matrix by another matrix.|
|[Multiply(ref Matrix, ref MatrixD, out MatrixD)](VRageMath.MatrixD.Multiply)||
|[Multiply(ref MatrixD, ref MatrixD, out MatrixD)](VRageMath.MatrixD.Multiply)|Multiplies a matrix by another matrix.|
|[Multiply(MatrixD, double)](VRageMath.MatrixD.Multiply)|Multiplies a matrix by a scalar value.|
|[Multiply(ref MatrixD, double, out MatrixD)](VRageMath.MatrixD.Multiply)|Multiplies a matrix by a scalar value.|
|[Divide(MatrixD, MatrixD)](VRageMath.MatrixD.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|[Divide(ref MatrixD, ref MatrixD, out MatrixD)](VRageMath.MatrixD.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|[Divide(MatrixD, double)](VRageMath.MatrixD.Divide)|Divides the components of a matrix by a scalar.|
|[Divide(ref MatrixD, double, out MatrixD)](VRageMath.MatrixD.Divide)|Divides the components of a matrix by a scalar.|
|[GetOrientation()](VRageMath.MatrixD.GetOrientation)|Gets the orientation.|
|[AssertIsValid(string)](VRageMath.MatrixD.AssertIsValid)||
|[IsValid()](VRageMath.MatrixD.IsValid)||
|[IsNan()](VRageMath.MatrixD.IsNan)||
|[IsRotation()](VRageMath.MatrixD.IsRotation)||
|[HasNoTranslationOrPerspective()](VRageMath.MatrixD.HasNoTranslationOrPerspective)|Returns true if this matrix represents invertible (you can call Invert on it) linear (it does not contain translation or perspective transformation) transformation. Such matrix consist solely of rotations, shearing, mirroring and scaling. It can be orthogonalized to create an orthogonal rotation matrix.|
|[CreateFromDir(Vector3D)](VRageMath.MatrixD.CreateFromDir)||
|[CreateFromDir(Vector3D, Vector3D)](VRageMath.MatrixD.CreateFromDir)||
|[Normalize(MatrixD)](VRageMath.MatrixD.Normalize)||
|[Orthogonalize()](VRageMath.MatrixD.Orthogonalize)||
|[Orthogonalize(MatrixD)](VRageMath.MatrixD.Orthogonalize)||
|[AlignRotationToAxes(ref MatrixD, ref MatrixD)](VRageMath.MatrixD.AlignRotationToAxes)||
|[GetEulerAnglesXYZ(ref MatrixD, out Vector3D)](VRageMath.MatrixD.GetEulerAnglesXYZ)||
|[SwapYZCoordinates(MatrixD)](VRageMath.MatrixD.SwapYZCoordinates)||
|[IsMirrored()](VRageMath.MatrixD.IsMirrored)||
|[SetFrom(ref Matrix)](VRageMath.MatrixD.SetFrom)||
|[SetRotationAndScale(ref Matrix)](VRageMath.MatrixD.SetRotationAndScale)||
|[GetDirectionVector(Direction)](VRageMath.MatrixD.GetDirectionVector)||
|[SetDirectionVector(Direction, Vector3D)](VRageMath.MatrixD.SetDirectionVector)||
|[GetClosestDirection(Vector3D)](VRageMath.MatrixD.GetClosestDirection)||
|[GetClosestDirection(ref Vector3D)](VRageMath.MatrixD.GetClosestDirection)||
|[Rescale(ref MatrixD, double)](VRageMath.MatrixD.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|[Rescale(ref MatrixD, float)](VRageMath.MatrixD.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|[Rescale(ref MatrixD, ref Vector3D)](VRageMath.MatrixD.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|[Rescale(MatrixD, double)](VRageMath.MatrixD.Rescale)||
|[Rescale(MatrixD, Vector3D)](VRageMath.MatrixD.Rescale)||
|[CreateBillboard(Vector3D, Vector3D, Vector3D, Vector3D?)](VRageMath.MatrixD.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|[CreateBillboard(ref Vector3D, ref Vector3D, ref Vector3D, Vector3D?, out MatrixD)](VRageMath.MatrixD.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|[CreateConstrainedBillboard(Vector3D, Vector3D, Vector3D, Vector3D?, Vector3D?)](VRageMath.MatrixD.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|[CreateConstrainedBillboard(ref Vector3D, ref Vector3D, ref Vector3D, Vector3D?, Vector3D?, out MatrixD)](VRageMath.MatrixD.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|[CreateTranslation(Vector3D)](VRageMath.MatrixD.CreateTranslation)|Creates a translation Matrix.|
|[CreateTranslation(Vector3)](VRageMath.MatrixD.CreateTranslation)||
|[CreateTranslation(ref Vector3D, out MatrixD)](VRageMath.MatrixD.CreateTranslation)|Creates a translation Matrix.|
|[CreateTranslation(double, double, double)](VRageMath.MatrixD.CreateTranslation)|Creates a translation Matrix.|
|[CreateTranslation(double, double, double, out MatrixD)](VRageMath.MatrixD.CreateTranslation)|Creates a translation Matrix.|
|[CreateScale(double, double, double)](VRageMath.MatrixD.CreateScale)|Creates a scaling Matrix.|
|[CreateScale(double, double, double, out MatrixD)](VRageMath.MatrixD.CreateScale)|Creates a scaling Matrix.|
|[CreateScale(Vector3D)](VRageMath.MatrixD.CreateScale)|Creates a scaling Matrix.|
|[CreateScale(ref Vector3D, out MatrixD)](VRageMath.MatrixD.CreateScale)|Creates a scaling Matrix.|
|[CreateScale(double)](VRageMath.MatrixD.CreateScale)|Creates a scaling Matrix.|
|[CreateScale(double, out MatrixD)](VRageMath.MatrixD.CreateScale)|Creates a scaling Matrix.|
|[CreateRotationX(double)](VRageMath.MatrixD.CreateRotationX)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|[CreateRotationX(double, out MatrixD)](VRageMath.MatrixD.CreateRotationX)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the x-axis.|
|[CreateRotationY(double)](VRageMath.MatrixD.CreateRotationY)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|[CreateRotationY(double, out MatrixD)](VRageMath.MatrixD.CreateRotationY)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the y-axis.|
|[CreateRotationZ(double)](VRageMath.MatrixD.CreateRotationZ)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|[CreateRotationZ(double, out MatrixD)](VRageMath.MatrixD.CreateRotationZ)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the z-axis.|
|[CreateFromAxisAngle(Vector3D, double)](VRageMath.MatrixD.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|[CreateFromAxisAngle(ref Vector3D, double, out MatrixD)](VRageMath.MatrixD.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|[CreatePerspectiveFieldOfView(double, double, double, double)](VRageMath.MatrixD.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by value.|
|[CreatePerspectiveFieldOfView(double, double, double, double, out MatrixD)](VRageMath.MatrixD.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by reference.|
|[CreatePerspective(double, double, double, double)](VRageMath.MatrixD.CreatePerspective)|Builds a perspective projection matrix and returns the result by value.|
|[CreatePerspective(double, double, double, double, out MatrixD)](VRageMath.MatrixD.CreatePerspective)|Builds a perspective projection matrix and returns the result by reference.|
|[CreatePerspectiveOffCenter(double, double, double, double, double, double)](VRageMath.MatrixD.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|[CreatePerspectiveOffCenter(double, double, double, double, double, double, out MatrixD)](VRageMath.MatrixD.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|[CreateOrthographic(double, double, double, double)](VRageMath.MatrixD.CreateOrthographic)|Builds an orthogonal projection matrix.|
|[CreateOrthographic(double, double, double, double, out MatrixD)](VRageMath.MatrixD.CreateOrthographic)|Builds an orthogonal projection matrix.|
|[CreateOrthographicOffCenter(double, double, double, double, double, double)](VRageMath.MatrixD.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|[CreateOrthographicOffCenter(double, double, double, double, double, double, out MatrixD)](VRageMath.MatrixD.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|[CreateLookAt(Vector3D, Vector3D, Vector3)](VRageMath.MatrixD.CreateLookAt)||
|[CreateLookAt(Vector3D, Vector3D, Vector3D)](VRageMath.MatrixD.CreateLookAt)|Creates a view matrix.|
|[CreateLookAtInverse(Vector3D, Vector3D, Vector3D)](VRageMath.MatrixD.CreateLookAtInverse)||
|[CreateLookAt(ref Vector3D, ref Vector3D, ref Vector3D, out MatrixD)](VRageMath.MatrixD.CreateLookAt)|Creates a view matrix.|
|[CreateWorld(Vector3D, Vector3, Vector3)](VRageMath.MatrixD.CreateWorld)||
|[CreateWorld(Vector3D)](VRageMath.MatrixD.CreateWorld)||
|[CreateWorld(Vector3D, Vector3D, Vector3D)](VRageMath.MatrixD.CreateWorld)|Creates a world matrix with the specified parameters.|
|[CreateWorld(ref Vector3D, ref Vector3D, ref Vector3D, out MatrixD)](VRageMath.MatrixD.CreateWorld)|Creates a world matrix with the specified parameters.|
|[CreateFromQuaternion(Quaternion)](VRageMath.MatrixD.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|[CreateFromQuaternion(QuaternionD)](VRageMath.MatrixD.CreateFromQuaternion)||
|[CreateFromQuaternion(ref Quaternion, out MatrixD)](VRageMath.MatrixD.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|[CreateFromYawPitchRoll(double, double, double)](VRageMath.MatrixD.CreateFromYawPitchRoll)|Creates a new rotation matrix from a specified yaw, pitch, and roll.|
|[CreateFromYawPitchRoll(double, double, double, out MatrixD)](VRageMath.MatrixD.CreateFromYawPitchRoll)|Fills in a rotation matrix from a specified yaw, pitch, and roll.|
|[CreateFromTransformScale(Quaternion, Vector3D, Vector3D)](VRageMath.MatrixD.CreateFromTransformScale)||
|[CreateShadow(Vector3D, Plane)](VRageMath.MatrixD.CreateShadow)|Creates a Matrix that flattens geometry into a specified Plane as if casting a shadow from a specified light source.|
|[CreateShadow(ref Vector3D, ref Plane, out MatrixD)](VRageMath.MatrixD.CreateShadow)|Fills in a Matrix to flatten geometry into a specified Plane as if casting a shadow from a specified light source.|
|[CreateReflection(Plane)](VRageMath.MatrixD.CreateReflection)|Creates a Matrix that reflects the coordinate system about a specified Plane.|
|[CreateReflection(ref Plane, out MatrixD)](VRageMath.MatrixD.CreateReflection)|Fills in an existing Matrix so that it reflects the coordinate system about a specified Plane.|
|[Transform(MatrixD, Quaternion)](VRageMath.MatrixD.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|[Transform(ref MatrixD, ref Quaternion, out MatrixD)](VRageMath.MatrixD.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|[GetRow(int)](VRageMath.MatrixD.GetRow)||
|[SetRow(int, Vector4)](VRageMath.MatrixD.SetRow)||
|[ToString()](VRageMath.MatrixD.ToString)|Retrieves a string representation of the current object.|
|[Equals(MatrixD)](VRageMath.MatrixD.Equals)|Determines whether the specified Object is equal to the Matrix.|
|[EqualsFast(ref MatrixD, double)](VRageMath.MatrixD.EqualsFast)|Compares just position, forward and up|
|[Equals(object)](VRageMath.MatrixD.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[GetHashCode()](VRageMath.MatrixD.GetHashCode)|Gets the hash code of this object.|
|[Transpose(MatrixD)](VRageMath.MatrixD.Transpose)|Transposes the rows and columns of a matrix.|
|[Transpose(ref MatrixD, out MatrixD)](VRageMath.MatrixD.Transpose)|Transposes the rows and columns of a matrix.|
|[Determinant()](VRageMath.MatrixD.Determinant)|Calculates the determinant of the matrix.|
|[Invert(MatrixD)](VRageMath.MatrixD.Invert)|Calculates the inverse of a matrix.|
|[Invert(ref MatrixD)](VRageMath.MatrixD.Invert)||
|[Invert(ref MatrixD, out MatrixD)](VRageMath.MatrixD.Invert)|Calculates the inverse of a matrix.|
|[Lerp(MatrixD, MatrixD, double)](VRageMath.MatrixD.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|[Lerp(ref MatrixD, ref MatrixD, double, out MatrixD)](VRageMath.MatrixD.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|[Slerp(ref MatrixD, ref MatrixD, double, out MatrixD)](VRageMath.MatrixD.Slerp)|Performs spherical linear interpolation of position and rotation.|
|[IsOrthogonal()](VRageMath.MatrixD.IsOrthogonal)||
|[IsOrthogonal(double)](VRageMath.MatrixD.IsOrthogonal)||
|[SlerpScale(ref MatrixD, ref MatrixD, double, out MatrixD)](VRageMath.MatrixD.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|[Slerp(MatrixD, MatrixD, double)](VRageMath.MatrixD.Slerp)|Performs spherical linear interpolation of position and rotation.|
|[SlerpScale(MatrixD, MatrixD, double, out MatrixD)](VRageMath.MatrixD.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|[SlerpScale(MatrixD, MatrixD, double)](VRageMath.MatrixD.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|[Negate(MatrixD)](VRageMath.MatrixD.Negate)|Negates individual elements of a matrix.|
|[Negate(ref MatrixD, out MatrixD)](VRageMath.MatrixD.Negate)|Negates individual elements of a matrix.|
|[Add(MatrixD, MatrixD)](VRageMath.MatrixD.Add)|Adds a matrix to another matrix.|
|[Add(ref MatrixD, ref MatrixD, out MatrixD)](VRageMath.MatrixD.Add)|Adds a matrix to another matrix.|
|[Subtract(Matrix, Matrix)](VRageMath.MatrixD.Subtract)|Subtracts matrices.|

