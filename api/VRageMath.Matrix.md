← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### Matrix Struct

```csharp
public struct Matrix: IEquatable<VRageMath.Matrix>
```

Defines a matrix.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<VRageMath.Matrix>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[M11](VRageMath.Matrix.M11)|Value at row 1 column 1 of the matrix.|
|[M12](VRageMath.Matrix.M12)|Value at row 1 column 2 of the matrix.|
|[M13](VRageMath.Matrix.M13)|Value at row 1 column 3 of the matrix.|
|[M14](VRageMath.Matrix.M14)|Value at row 1 column 4 of the matrix.|
|[M21](VRageMath.Matrix.M21)|Value at row 2 column 1 of the matrix.|
|[M22](VRageMath.Matrix.M22)|Value at row 2 column 2 of the matrix.|
|[M23](VRageMath.Matrix.M23)|Value at row 2 column 3 of the matrix.|
|[M24](VRageMath.Matrix.M24)|Value at row 2 column 4 of the matrix.|
|[M31](VRageMath.Matrix.M31)|Value at row 3 column 1 of the matrix.|
|[M32](VRageMath.Matrix.M32)|Value at row 3 column 2 of the matrix.|
|[M33](VRageMath.Matrix.M33)|Value at row 3 column 3 of the matrix.|
|[M34](VRageMath.Matrix.M34)|Value at row 3 column 4 of the matrix.|
|[M41](VRageMath.Matrix.M41)|Value at row 4 column 1 of the matrix.|
|[M42](VRageMath.Matrix.M42)|Value at row 4 column 2 of the matrix.|
|[M43](VRageMath.Matrix.M43)|Value at row 4 column 3 of the matrix.|
|[M44](VRageMath.Matrix.M44)|Value at row 4 column 4 of the matrix.|
|[Identity](VRageMath.Matrix.Identity)||
|[Zero](VRageMath.Matrix.Zero)||

#### Properties

|Member|Description|
|---|---|
|[Up { get; set; }](VRageMath.Matrix.Up)|Gets and sets the up vector of the Matrix.|
|[Down { get; set; }](VRageMath.Matrix.Down)|Gets and sets the down vector of the Matrix.|
|[Right { get; set; }](VRageMath.Matrix.Right)|Gets and sets the right vector of the Matrix.|
|[Col0 { get; }](VRageMath.Matrix.Col0)||
|[Col1 { get; }](VRageMath.Matrix.Col1)||
|[Col2 { get; }](VRageMath.Matrix.Col2)||
|[Left { get; set; }](VRageMath.Matrix.Left)|Gets and sets the left vector of the Matrix.|
|[Forward { get; set; }](VRageMath.Matrix.Forward)|Gets and sets the forward vector of the Matrix.|
|[Backward { get; set; }](VRageMath.Matrix.Backward)|Gets and sets the backward vector of the Matrix.|
|[Scale { get; }](VRageMath.Matrix.Scale)||
|[Translation { get; set; }](VRageMath.Matrix.Translation)|Gets and sets the translation vector of the Matrix.|
|[Item { get; set; }](VRageMath.Matrix.Item)||

#### Constructors

|Member|Description|
|---|---|
|[Matrix(float, float, float, float, float, float, float, float, float, float, float, float, float, float, float, float)](VRageMath.Matrix..ctor)||
|[Matrix(float, float, float, float, float, float, float, float, float)](VRageMath.Matrix..ctor)||
|[Matrix(MatrixD)](VRageMath.Matrix..ctor)||

#### Methods

|Member|Description|
|---|---|
|[Subtract(ref Matrix, ref Matrix, out Matrix)](VRageMath.Matrix.Subtract)|Subtracts matrices.|
|[Multiply(Matrix, Matrix)](VRageMath.Matrix.Multiply)|Multiplies a matrix by another matrix.|
|[Multiply(ref Matrix, ref Matrix, out Matrix)](VRageMath.Matrix.Multiply)|Multiplies a matrix by another matrix.|
|[MultiplyRotation(ref Matrix, ref Matrix, out Matrix)](VRageMath.Matrix.MultiplyRotation)|Multiplies a matrix by another matrix, only rotation parts.|
|[Multiply(Matrix, float)](VRageMath.Matrix.Multiply)|Multiplies a matrix by a scalar value.|
|[Multiply(ref Matrix, float, out Matrix)](VRageMath.Matrix.Multiply)|Multiplies a matrix by a scalar value.|
|[Divide(Matrix, Matrix)](VRageMath.Matrix.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|[Divide(ref Matrix, ref Matrix, out Matrix)](VRageMath.Matrix.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|[Divide(Matrix, float)](VRageMath.Matrix.Divide)|Divides the components of a matrix by a scalar.|
|[Divide(ref Matrix, float, out Matrix)](VRageMath.Matrix.Divide)|Divides the components of a matrix by a scalar.|
|[GetOrientation()](VRageMath.Matrix.GetOrientation)|Gets the orientation.|
|[AssertIsValid()](VRageMath.Matrix.AssertIsValid)||
|[IsValid()](VRageMath.Matrix.IsValid)||
|[IsNan()](VRageMath.Matrix.IsNan)||
|[IsRotation()](VRageMath.Matrix.IsRotation)||
|[HasNoTranslationOrPerspective()](VRageMath.Matrix.HasNoTranslationOrPerspective)|Returns true if this matrix represents invertible (you can call Invert on it) linear (it does not contain translation or perspective transformation) transformation. Such matrix consist solely of rotations, shearing, mirroring and scaling. It can be orthogonalized to create an orthogonal rotation matrix.|
|[CreateFromDir(Vector3)](VRageMath.Matrix.CreateFromDir)||
|[CreateFromDir(Vector3, Vector3)](VRageMath.Matrix.CreateFromDir)||
|[Normalize(Matrix)](VRageMath.Matrix.Normalize)||
|[Orthogonalize(Matrix)](VRageMath.Matrix.Orthogonalize)||
|[Round(ref Matrix)](VRageMath.Matrix.Round)||
|[AlignRotationToAxes(ref Matrix, ref Matrix)](VRageMath.Matrix.AlignRotationToAxes)||
|[GetEulerAnglesXYZ(ref Matrix, out Vector3)](VRageMath.Matrix.GetEulerAnglesXYZ)||
|[SwapYZCoordinates(Matrix)](VRageMath.Matrix.SwapYZCoordinates)||
|[IsMirrored()](VRageMath.Matrix.IsMirrored)||
|[IsOrthogonal()](VRageMath.Matrix.IsOrthogonal)||
|[GetDirectionVector(Direction)](VRageMath.Matrix.GetDirectionVector)||
|[SetDirectionVector(Direction, Vector3)](VRageMath.Matrix.SetDirectionVector)||
|[GetClosestDirection(Vector3)](VRageMath.Matrix.GetClosestDirection)||
|[GetClosestDirection(ref Vector3)](VRageMath.Matrix.GetClosestDirection)||
|[Rescale(ref Matrix, float)](VRageMath.Matrix.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|[Rescale(ref Matrix, ref Vector3)](VRageMath.Matrix.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|[Rescale(Matrix, float)](VRageMath.Matrix.Rescale)||
|[Rescale(Matrix, Vector3)](VRageMath.Matrix.Rescale)||
|[CreateBillboard(Vector3, Vector3, Vector3, Vector3?)](VRageMath.Matrix.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|[CreateBillboard(ref Vector3, ref Vector3, ref Vector3, Vector3?, out Matrix)](VRageMath.Matrix.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|[CreateConstrainedBillboard(Vector3, Vector3, Vector3, Vector3?, Vector3?)](VRageMath.Matrix.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|[CreateConstrainedBillboard(ref Vector3, ref Vector3, ref Vector3, Vector3?, Vector3?, out Matrix)](VRageMath.Matrix.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|[CreateTranslation(Vector3)](VRageMath.Matrix.CreateTranslation)|Creates a translation Matrix.|
|[CreateTranslation(ref Vector3, out Matrix)](VRageMath.Matrix.CreateTranslation)|Creates a translation Matrix.|
|[CreateTranslation(float, float, float)](VRageMath.Matrix.CreateTranslation)|Creates a translation Matrix.|
|[CreateTranslation(float, float, float, out Matrix)](VRageMath.Matrix.CreateTranslation)|Creates a translation Matrix.|
|[CreateScale(float, float, float)](VRageMath.Matrix.CreateScale)|Creates a scaling Matrix.|
|[CreateScale(float, float, float, out Matrix)](VRageMath.Matrix.CreateScale)|Creates a scaling Matrix.|
|[CreateScale(Vector3)](VRageMath.Matrix.CreateScale)|Creates a scaling Matrix.|
|[CreateScale(ref Vector3, out Matrix)](VRageMath.Matrix.CreateScale)|Creates a scaling Matrix.|
|[CreateScale(float)](VRageMath.Matrix.CreateScale)|Creates a scaling Matrix.|
|[CreateScale(float, out Matrix)](VRageMath.Matrix.CreateScale)|Creates a scaling Matrix.|
|[CreateRotationX(float)](VRageMath.Matrix.CreateRotationX)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|[CreateRotationX(float, out Matrix)](VRageMath.Matrix.CreateRotationX)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the x-axis.|
|[CreateRotationY(float)](VRageMath.Matrix.CreateRotationY)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|[CreateRotationY(float, out Matrix)](VRageMath.Matrix.CreateRotationY)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the y-axis.|
|[CreateRotationZ(float)](VRageMath.Matrix.CreateRotationZ)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|[CreateRotationZ(float, out Matrix)](VRageMath.Matrix.CreateRotationZ)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the z-axis.|
|[CreateFromAxisAngle(Vector3, float)](VRageMath.Matrix.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|[CreateFromAxisAngle(ref Vector3, float, out Matrix)](VRageMath.Matrix.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|[CreateRotationFromTwoVectors(ref Vector3, ref Vector3, out Matrix)](VRageMath.Matrix.CreateRotationFromTwoVectors)||
|[CreatePerspectiveFieldOfView(float, float, float, float)](VRageMath.Matrix.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by value.|
|[CreatePerspectiveFovRhComplementary(float, float, float, float)](VRageMath.Matrix.CreatePerspectiveFovRhComplementary)||
|[CreatePerspectiveFovRhInfinite(float, float, float)](VRageMath.Matrix.CreatePerspectiveFovRhInfinite)||
|[CreatePerspectiveFovRhInfiniteComplementary(float, float, float)](VRageMath.Matrix.CreatePerspectiveFovRhInfiniteComplementary)||
|[CreatePerspectiveFovRhInverse(float, float, float, float)](VRageMath.Matrix.CreatePerspectiveFovRhInverse)||
|[CreatePerspectiveFovRhInfiniteInverse(float, float, float)](VRageMath.Matrix.CreatePerspectiveFovRhInfiniteInverse)||
|[CreatePerspectiveFovRhInfiniteComplementaryInverse(float, float, float)](VRageMath.Matrix.CreatePerspectiveFovRhInfiniteComplementaryInverse)||
|[CreateFromPerspectiveFieldOfView(ref Matrix, float, float)](VRageMath.Matrix.CreateFromPerspectiveFieldOfView)||
|[CreatePerspectiveFieldOfView(float, float, float, float, out Matrix)](VRageMath.Matrix.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by reference.|
|[CreatePerspective(float, float, float, float)](VRageMath.Matrix.CreatePerspective)|Builds a perspective projection matrix and returns the result by value.|
|[CreatePerspective(float, float, float, float, out Matrix)](VRageMath.Matrix.CreatePerspective)|Builds a perspective projection matrix and returns the result by reference.|
|[CreatePerspectiveOffCenter(float, float, float, float, float, float)](VRageMath.Matrix.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|[CreatePerspectiveOffCenter(float, float, float, float, float, float, out Matrix)](VRageMath.Matrix.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|[CreateOrthographic(float, float, float, float)](VRageMath.Matrix.CreateOrthographic)|Builds an orthogonal projection matrix.|
|[CreateOrthographic(float, float, float, float, out Matrix)](VRageMath.Matrix.CreateOrthographic)|Builds an orthogonal projection matrix.|
|[CreateOrthographicOffCenter(float, float, float, float, float, float)](VRageMath.Matrix.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|[CreateOrthographicOffCenter(float, float, float, float, float, float, out Matrix)](VRageMath.Matrix.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|[CreateLookAt(Vector3, Vector3, Vector3)](VRageMath.Matrix.CreateLookAt)|Creates a view matrix.|
|[CreateLookAtInverse(Vector3, Vector3, Vector3)](VRageMath.Matrix.CreateLookAtInverse)||
|[CreateLookAt(ref Vector3, ref Vector3, ref Vector3, out Matrix)](VRageMath.Matrix.CreateLookAt)|Creates a view matrix.|
|[CreateWorld(Vector3)](VRageMath.Matrix.CreateWorld)||
|[CreateWorld(Vector3, Vector3, Vector3)](VRageMath.Matrix.CreateWorld)|Creates a world matrix with the specified parameters.|
|[CreateWorld(ref Vector3, ref Vector3, ref Vector3, out Matrix)](VRageMath.Matrix.CreateWorld)|Creates a world matrix with the specified parameters.|
|[CreateFromQuaternion(Quaternion)](VRageMath.Matrix.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|[CreateFromQuaternion(ref Quaternion, out Matrix)](VRageMath.Matrix.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|[CreateFromYawPitchRoll(float, float, float)](VRageMath.Matrix.CreateFromYawPitchRoll)|Creates a new rotation matrix from a specified yaw, pitch, and roll.|
|[CreateFromYawPitchRoll(float, float, float, out Matrix)](VRageMath.Matrix.CreateFromYawPitchRoll)|Fills in a rotation matrix from a specified yaw, pitch, and roll.|
|[CreateFromTransformScale(Quaternion, Vector3, Vector3)](VRageMath.Matrix.CreateFromTransformScale)||
|[CreateShadow(Vector3, Plane)](VRageMath.Matrix.CreateShadow)|Creates a Matrix that flattens geometry into a specified Plane as if casting a shadow from a specified light source.|
|[CreateShadow(ref Vector3, ref Plane, out Matrix)](VRageMath.Matrix.CreateShadow)|Fills in a Matrix to flatten geometry into a specified Plane as if casting a shadow from a specified light source.|
|[CreateReflection(Plane)](VRageMath.Matrix.CreateReflection)|Creates a Matrix that reflects the coordinate system about a specified Plane.|
|[CreateReflection(ref Plane, out Matrix)](VRageMath.Matrix.CreateReflection)|Fills in an existing Matrix so that it reflects the coordinate system about a specified Plane.|
|[Transform(Matrix, Quaternion)](VRageMath.Matrix.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|[Transform(ref Matrix, ref Quaternion, out Matrix)](VRageMath.Matrix.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|[GetRow(int)](VRageMath.Matrix.GetRow)||
|[SetRow(int, Vector4)](VRageMath.Matrix.SetRow)||
|[ToString()](VRageMath.Matrix.ToString)|Retrieves a string representation of the current object.|
|[Equals(Matrix)](VRageMath.Matrix.Equals)|Determines whether the specified Object is equal to the Matrix.|
|[EqualsFast(ref Matrix, float)](VRageMath.Matrix.EqualsFast)|Compares just position, forward and up|
|[Equals(object)](VRageMath.Matrix.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[GetHashCode()](VRageMath.Matrix.GetHashCode)|Gets the hash code of this object.|
|[Transpose(Matrix)](VRageMath.Matrix.Transpose)|Transposes the rows and columns of a matrix.|
|[Transpose(ref Matrix, out Matrix)](VRageMath.Matrix.Transpose)|Transposes the rows and columns of a matrix.|
|[TransposeRotationInPlace()](VRageMath.Matrix.TransposeRotationInPlace)|Transposes the rows and columns of a matrix that is assumed to be rotation only in place.|
|[Determinant()](VRageMath.Matrix.Determinant)|Calculates the determinant of the matrix.|
|[Invert(Matrix)](VRageMath.Matrix.Invert)|Calculates the inverse of a matrix.|
|[Invert(ref Matrix)](VRageMath.Matrix.Invert)||
|[Invert(ref Matrix, out Matrix)](VRageMath.Matrix.Invert)|Calculates the inverse of a matrix.|
|[Lerp(Matrix, Matrix, float)](VRageMath.Matrix.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|[Lerp(ref Matrix, ref Matrix, float, out Matrix)](VRageMath.Matrix.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|[Slerp(ref Matrix, ref Matrix, float, out Matrix)](VRageMath.Matrix.Slerp)|Performs spherical linear interpolation of position and rotation.|
|[SlerpScale(ref Matrix, ref Matrix, float, out Matrix)](VRageMath.Matrix.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|[Slerp(Matrix, Matrix, float, out Matrix)](VRageMath.Matrix.Slerp)|Performs spherical linear interpolation of position and rotation.|
|[Slerp(Matrix, Matrix, float)](VRageMath.Matrix.Slerp)|Performs spherical linear interpolation of position and rotation.|
|[SlerpScale(Matrix, Matrix, float, out Matrix)](VRageMath.Matrix.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|[SlerpScale(Matrix, Matrix, float)](VRageMath.Matrix.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|[Negate(Matrix)](VRageMath.Matrix.Negate)|Negates individual elements of a matrix.|
|[Negate(ref Matrix, out Matrix)](VRageMath.Matrix.Negate)|Negates individual elements of a matrix.|
|[Add(Matrix, Matrix)](VRageMath.Matrix.Add)|Adds a matrix to another matrix.|
|[Add(ref Matrix, ref Matrix, out Matrix)](VRageMath.Matrix.Add)|Adds a matrix to another matrix.|
|[Subtract(Matrix, Matrix)](VRageMath.Matrix.Subtract)|Subtracts matrices.|

