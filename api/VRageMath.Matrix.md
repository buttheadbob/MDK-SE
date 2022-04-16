← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### Matrix Struct

```csharp
public struct Matrix: IEquatable<Matrix>
```

Defines a matrix.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<Matrix>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\\%1static Matrix Identity](VRageMath.Matrix.Identity)||
|\\%1static Matrix Zero](VRageMath.Matrix.Zero)||
|\\%1float M11](VRageMath.Matrix.M11)|Value at row 1 column 1 of the matrix.|
|\\%1float M12](VRageMath.Matrix.M12)|Value at row 1 column 2 of the matrix.|
|\\%1float M13](VRageMath.Matrix.M13)|Value at row 1 column 3 of the matrix.|
|\\%1float M14](VRageMath.Matrix.M14)|Value at row 1 column 4 of the matrix.|
|\\%1float M21](VRageMath.Matrix.M21)|Value at row 2 column 1 of the matrix.|
|\\%1float M22](VRageMath.Matrix.M22)|Value at row 2 column 2 of the matrix.|
|\\%1float M23](VRageMath.Matrix.M23)|Value at row 2 column 3 of the matrix.|
|\\%1float M24](VRageMath.Matrix.M24)|Value at row 2 column 4 of the matrix.|
|\\%1float M31](VRageMath.Matrix.M31)|Value at row 3 column 1 of the matrix.|
|\\%1float M32](VRageMath.Matrix.M32)|Value at row 3 column 2 of the matrix.|
|\\%1float M33](VRageMath.Matrix.M33)|Value at row 3 column 3 of the matrix.|
|\\%1float M34](VRageMath.Matrix.M34)|Value at row 3 column 4 of the matrix.|
|\\%1float M41](VRageMath.Matrix.M41)|Value at row 4 column 1 of the matrix.|
|\\%1float M42](VRageMath.Matrix.M42)|Value at row 4 column 2 of the matrix.|
|\\%1float M43](VRageMath.Matrix.M43)|Value at row 4 column 3 of the matrix.|
|\\%1float M44](VRageMath.Matrix.M44)|Value at row 4 column 4 of the matrix.|

#### Properties

|Member|Description|
|---|---|
|\\%1Vector3 Backward { get; set; }](VRageMath.Matrix.Backward)|Gets and sets the backward vector of the Matrix.|
|\\%1Vector3 Col0 { get; }](VRageMath.Matrix.Col0)||
|\\%1Vector3 Col1 { get; }](VRageMath.Matrix.Col1)||
|\\%1Vector3 Col2 { get; }](VRageMath.Matrix.Col2)||
|\\%1Vector3 Down { get; set; }](VRageMath.Matrix.Down)|Gets and sets the down vector of the Matrix.|
|\\%1Vector3 Forward { get; set; }](VRageMath.Matrix.Forward)|Gets and sets the forward vector of the Matrix.|
|\\%1float Item { get; set; }](VRageMath.Matrix.Item)||
|\\%1Vector3 Left { get; set; }](VRageMath.Matrix.Left)|Gets and sets the left vector of the Matrix.|
|\\%1Vector3 Right { get; set; }](VRageMath.Matrix.Right)|Gets and sets the right vector of the Matrix.|
|\\%1Vector3 Scale { get; }](VRageMath.Matrix.Scale)||
|\\%1Vector3 Translation { get; set; }](VRageMath.Matrix.Translation)|Gets and sets the translation vector of the Matrix.|
|\\%1Vector3 Up { get; set; }](VRageMath.Matrix.Up)|Gets and sets the up vector of the Matrix.|

#### Constructors

|Member|Description|
|---|---|
|\\%1Matrix(float, float, float, float, float, float, float, float, float, float, float, float, float, float, float, float)](VRageMath.Matrix..ctor)||
|\\%1Matrix(float, float, float, float, float, float, float, float, float)](VRageMath.Matrix..ctor)||
|\\%1Matrix(MatrixD)](VRageMath.Matrix..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\%1static Matrix Add(Matrix, Matrix)](VRageMath.Matrix.Add)|Adds a matrix to another matrix.|
|\\%1static void Add(ref Matrix, ref Matrix, out Matrix)](VRageMath.Matrix.Add)|Adds a matrix to another matrix.|
|\\%1static Matrix AlignRotationToAxes(ref Matrix, ref Matrix)](VRageMath.Matrix.AlignRotationToAxes)||
|\\%1static Matrix CreateBillboard(Vector3, Vector3, Vector3, Vector3?)](VRageMath.Matrix.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|\\%1static void CreateBillboard(ref Vector3, ref Vector3, ref Vector3, Vector3?, out Matrix)](VRageMath.Matrix.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|\\%1static Matrix CreateConstrainedBillboard(Vector3, Vector3, Vector3, Vector3?, Vector3?)](VRageMath.Matrix.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|\\%1static void CreateConstrainedBillboard(ref Vector3, ref Vector3, ref Vector3, Vector3?, Vector3?, out Matrix)](VRageMath.Matrix.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|\\%1static Matrix CreateFromAxisAngle(Vector3, float)](VRageMath.Matrix.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|\\%1static void CreateFromAxisAngle(ref Vector3, float, out Matrix)](VRageMath.Matrix.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|\\%1static Matrix CreateFromDir(Vector3)](VRageMath.Matrix.CreateFromDir)||
|\\%1static Matrix CreateFromDir(Vector3, Vector3)](VRageMath.Matrix.CreateFromDir)||
|\\%1static Matrix CreateFromPerspectiveFieldOfView(ref Matrix, float, float)](VRageMath.Matrix.CreateFromPerspectiveFieldOfView)||
|\\%1static Matrix CreateFromQuaternion(Quaternion)](VRageMath.Matrix.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|\\%1static void CreateFromQuaternion(ref Quaternion, out Matrix)](VRageMath.Matrix.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|\\%1static Matrix CreateFromTransformScale(Quaternion, Vector3, Vector3)](VRageMath.Matrix.CreateFromTransformScale)||
|\\%1static Matrix CreateFromYawPitchRoll(float, float, float)](VRageMath.Matrix.CreateFromYawPitchRoll)|Creates a new rotation matrix from a specified yaw, pitch, and roll.|
|\\%1static void CreateFromYawPitchRoll(float, float, float, out Matrix)](VRageMath.Matrix.CreateFromYawPitchRoll)|Fills in a rotation matrix from a specified yaw, pitch, and roll.|
|\\%1static Matrix CreateLookAt(Vector3, Vector3, Vector3)](VRageMath.Matrix.CreateLookAt)|Creates a view matrix.|
|\\%1static void CreateLookAt(ref Vector3, ref Vector3, ref Vector3, out Matrix)](VRageMath.Matrix.CreateLookAt)|Creates a view matrix.|
|\\%1static Matrix CreateLookAtInverse(Vector3, Vector3, Vector3)](VRageMath.Matrix.CreateLookAtInverse)||
|\\%1static Matrix CreateOrthographic(float, float, float, float)](VRageMath.Matrix.CreateOrthographic)|Builds an orthogonal projection matrix.|
|\\%1static void CreateOrthographic(float, float, float, float, out Matrix)](VRageMath.Matrix.CreateOrthographic)|Builds an orthogonal projection matrix.|
|\\%1static Matrix CreateOrthographicOffCenter(float, float, float, float, float, float)](VRageMath.Matrix.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|\\%1static void CreateOrthographicOffCenter(float, float, float, float, float, float, out Matrix)](VRageMath.Matrix.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|\\%1static Matrix CreatePerspective(float, float, float, float)](VRageMath.Matrix.CreatePerspective)|Builds a perspective projection matrix and returns the result by value.|
|\\%1static void CreatePerspective(float, float, float, float, out Matrix)](VRageMath.Matrix.CreatePerspective)|Builds a perspective projection matrix and returns the result by reference.|
|\\%1static Matrix CreatePerspectiveFieldOfView(float, float, float, float)](VRageMath.Matrix.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by value.|
|\\%1static void CreatePerspectiveFieldOfView(float, float, float, float, out Matrix)](VRageMath.Matrix.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by reference.|
|\\%1static Matrix CreatePerspectiveFovRhComplementary(float, float, float, float)](VRageMath.Matrix.CreatePerspectiveFovRhComplementary)||
|\\%1static Matrix CreatePerspectiveFovRhInfinite(float, float, float)](VRageMath.Matrix.CreatePerspectiveFovRhInfinite)||
|\\%1static Matrix CreatePerspectiveFovRhInfiniteComplementary(float, float, float)](VRageMath.Matrix.CreatePerspectiveFovRhInfiniteComplementary)||
|\\%1static Matrix CreatePerspectiveFovRhInfiniteComplementaryInverse(float, float, float)](VRageMath.Matrix.CreatePerspectiveFovRhInfiniteComplementaryInverse)||
|\\%1static Matrix CreatePerspectiveFovRhInfiniteInverse(float, float, float)](VRageMath.Matrix.CreatePerspectiveFovRhInfiniteInverse)||
|\\%1static Matrix CreatePerspectiveFovRhInverse(float, float, float, float)](VRageMath.Matrix.CreatePerspectiveFovRhInverse)||
|\\%1static Matrix CreatePerspectiveOffCenter(float, float, float, float, float, float)](VRageMath.Matrix.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|\\%1static void CreatePerspectiveOffCenter(float, float, float, float, float, float, out Matrix)](VRageMath.Matrix.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|\\%1static Matrix CreateReflection(Plane)](VRageMath.Matrix.CreateReflection)|Creates a Matrix that reflects the coordinate system about a specified Plane.|
|\\%1static void CreateReflection(ref Plane, out Matrix)](VRageMath.Matrix.CreateReflection)|Fills in an existing Matrix so that it reflects the coordinate system about a specified Plane.|
|\\%1static void CreateRotationFromTwoVectors(ref Vector3, ref Vector3, out Matrix)](VRageMath.Matrix.CreateRotationFromTwoVectors)||
|\\%1static Matrix CreateRotationX(float)](VRageMath.Matrix.CreateRotationX)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|\\%1static void CreateRotationX(float, out Matrix)](VRageMath.Matrix.CreateRotationX)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the x-axis.|
|\\%1static Matrix CreateRotationY(float)](VRageMath.Matrix.CreateRotationY)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|\\%1static void CreateRotationY(float, out Matrix)](VRageMath.Matrix.CreateRotationY)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the y-axis.|
|\\%1static Matrix CreateRotationZ(float)](VRageMath.Matrix.CreateRotationZ)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|\\%1static void CreateRotationZ(float, out Matrix)](VRageMath.Matrix.CreateRotationZ)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the z-axis.|
|\\%1static Matrix CreateScale(float, float, float)](VRageMath.Matrix.CreateScale)|Creates a scaling Matrix.|
|\\%1static void CreateScale(float, float, float, out Matrix)](VRageMath.Matrix.CreateScale)|Creates a scaling Matrix.|
|\\%1static Matrix CreateScale(Vector3)](VRageMath.Matrix.CreateScale)|Creates a scaling Matrix.|
|\\%1static void CreateScale(ref Vector3, out Matrix)](VRageMath.Matrix.CreateScale)|Creates a scaling Matrix.|
|\\%1static Matrix CreateScale(float)](VRageMath.Matrix.CreateScale)|Creates a scaling Matrix.|
|\\%1static void CreateScale(float, out Matrix)](VRageMath.Matrix.CreateScale)|Creates a scaling Matrix.|
|\\%1static Matrix CreateShadow(Vector3, Plane)](VRageMath.Matrix.CreateShadow)|Creates a Matrix that flattens geometry into a specified Plane as if casting a shadow from a specified light source.|
|\\%1static void CreateShadow(ref Vector3, ref Plane, out Matrix)](VRageMath.Matrix.CreateShadow)|Fills in a Matrix to flatten geometry into a specified Plane as if casting a shadow from a specified light source.|
|\\%1static Matrix CreateTranslation(Vector3)](VRageMath.Matrix.CreateTranslation)|Creates a translation Matrix.|
|\\%1static void CreateTranslation(ref Vector3, out Matrix)](VRageMath.Matrix.CreateTranslation)|Creates a translation Matrix.|
|\\%1static Matrix CreateTranslation(float, float, float)](VRageMath.Matrix.CreateTranslation)|Creates a translation Matrix.|
|\\%1static void CreateTranslation(float, float, float, out Matrix)](VRageMath.Matrix.CreateTranslation)|Creates a translation Matrix.|
|\\%1static Matrix CreateWorld(Vector3)](VRageMath.Matrix.CreateWorld)||
|\\%1static Matrix CreateWorld(Vector3, Vector3, Vector3)](VRageMath.Matrix.CreateWorld)|Creates a world matrix with the specified parameters.|
|\\%1static void CreateWorld(ref Vector3, ref Vector3, ref Vector3, out Matrix)](VRageMath.Matrix.CreateWorld)|Creates a world matrix with the specified parameters.|
|\\%1static Matrix Divide(Matrix, Matrix)](VRageMath.Matrix.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|\\%1static void Divide(ref Matrix, ref Matrix, out Matrix)](VRageMath.Matrix.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|\\%1static Matrix Divide(Matrix, float)](VRageMath.Matrix.Divide)|Divides the components of a matrix by a scalar.|
|\\%1static void Divide(ref Matrix, float, out Matrix)](VRageMath.Matrix.Divide)|Divides the components of a matrix by a scalar.|
|\\%1static bool GetEulerAnglesXYZ(ref Matrix, out Vector3)](VRageMath.Matrix.GetEulerAnglesXYZ)||
|\\%1static Matrix Invert(Matrix)](VRageMath.Matrix.Invert)|Calculates the inverse of a matrix.|
|\\%1static Matrix Invert(ref Matrix)](VRageMath.Matrix.Invert)||
|\\%1static void Invert(ref Matrix, out Matrix)](VRageMath.Matrix.Invert)|Calculates the inverse of a matrix.|
|\\%1static Matrix Lerp(Matrix, Matrix, float)](VRageMath.Matrix.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|\\%1static void Lerp(ref Matrix, ref Matrix, float, out Matrix)](VRageMath.Matrix.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|\\%1static Matrix Multiply(Matrix, Matrix)](VRageMath.Matrix.Multiply)|Multiplies a matrix by another matrix.|
|\\%1static void Multiply(ref Matrix, ref Matrix, out Matrix)](VRageMath.Matrix.Multiply)|Multiplies a matrix by another matrix.|
|\\%1static Matrix Multiply(Matrix, float)](VRageMath.Matrix.Multiply)|Multiplies a matrix by a scalar value.|
|\\%1static void Multiply(ref Matrix, float, out Matrix)](VRageMath.Matrix.Multiply)|Multiplies a matrix by a scalar value.|
|\\%1static void MultiplyRotation(ref Matrix, ref Matrix, out Matrix)](VRageMath.Matrix.MultiplyRotation)|Multiplies a matrix by another matrix, only rotation parts.|
|\\%1static Matrix Negate(Matrix)](VRageMath.Matrix.Negate)|Negates individual elements of a matrix.|
|\\%1static void Negate(ref Matrix, out Matrix)](VRageMath.Matrix.Negate)|Negates individual elements of a matrix.|
|\\%1static Matrix Normalize(Matrix)](VRageMath.Matrix.Normalize)||
|\\%1static Matrix Orthogonalize(Matrix)](VRageMath.Matrix.Orthogonalize)||
|\\%1static void Rescale(ref Matrix, float)](VRageMath.Matrix.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|\\%1static void Rescale(ref Matrix, ref Vector3)](VRageMath.Matrix.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|\\%1static Matrix Rescale(Matrix, float)](VRageMath.Matrix.Rescale)||
|\\%1static Matrix Rescale(Matrix, Vector3)](VRageMath.Matrix.Rescale)||
|\\%1static Matrix Round(ref Matrix)](VRageMath.Matrix.Round)||
|\\%1static void Slerp(ref Matrix, ref Matrix, float, out Matrix)](VRageMath.Matrix.Slerp)|Performs spherical linear interpolation of position and rotation.|
|\\%1static void Slerp(Matrix, Matrix, float, out Matrix)](VRageMath.Matrix.Slerp)|Performs spherical linear interpolation of position and rotation.|
|\\%1static Matrix Slerp(Matrix, Matrix, float)](VRageMath.Matrix.Slerp)|Performs spherical linear interpolation of position and rotation.|
|\\%1static void SlerpScale(ref Matrix, ref Matrix, float, out Matrix)](VRageMath.Matrix.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|\\%1static void SlerpScale(Matrix, Matrix, float, out Matrix)](VRageMath.Matrix.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|\\%1static Matrix SlerpScale(Matrix, Matrix, float)](VRageMath.Matrix.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|\\%1static void Subtract(ref Matrix, ref Matrix, out Matrix)](VRageMath.Matrix.Subtract)|Subtracts matrices.|
|\\%1static Matrix Subtract(Matrix, Matrix)](VRageMath.Matrix.Subtract)|Subtracts matrices.|
|\\%1static Matrix SwapYZCoordinates(Matrix)](VRageMath.Matrix.SwapYZCoordinates)||
|\\%1static Matrix Transform(Matrix, Quaternion)](VRageMath.Matrix.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|\\%1static void Transform(ref Matrix, ref Quaternion, out Matrix)](VRageMath.Matrix.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|\\%1static Matrix Transpose(Matrix)](VRageMath.Matrix.Transpose)|Transposes the rows and columns of a matrix.|
|\\%1static void Transpose(ref Matrix, out Matrix)](VRageMath.Matrix.Transpose)|Transposes the rows and columns of a matrix.|
|\\%1void AssertIsValid()](VRageMath.Matrix.AssertIsValid)||
|\\%1float Determinant()](VRageMath.Matrix.Determinant)|Calculates the determinant of the matrix.|
|\\%1bool Equals(Matrix)](VRageMath.Matrix.Equals)|Determines whether the specified Object is equal to the Matrix.|
|\\%1bool Equals(object)](VRageMath.Matrix.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|\\%1bool EqualsFast(ref Matrix, \\%1float])](VRageMath.Matrix.EqualsFast)|Compares just position, forward and up|
|\\%1Direction GetClosestDirection(Vector3)](VRageMath.Matrix.GetClosestDirection)||
|\\%1Direction GetClosestDirection(ref Vector3)](VRageMath.Matrix.GetClosestDirection)||
|\\%1Vector3 GetDirectionVector(Direction)](VRageMath.Matrix.GetDirectionVector)||
|\\%1int GetHashCode()](VRageMath.Matrix.GetHashCode)|Gets the hash code of this object.|
|\\%1Matrix GetOrientation()](VRageMath.Matrix.GetOrientation)|Gets the orientation.|
|\\%1Vector4 GetRow(int)](VRageMath.Matrix.GetRow)||
|\\%1bool HasNoTranslationOrPerspective()](VRageMath.Matrix.HasNoTranslationOrPerspective)|Returns true if this matrix represents invertible (you can call Invert on it) linear (it does not contain translation or perspective transformation) transformation. Such matrix consist solely of rotations, shearing, mirroring and scaling. It can be orthogonalized to create an orthogonal rotation matrix.|
|\\%1bool IsMirrored()](VRageMath.Matrix.IsMirrored)||
|\\%1bool IsNan()](VRageMath.Matrix.IsNan)||
|\\%1bool IsOrthogonal()](VRageMath.Matrix.IsOrthogonal)||
|\\%1bool IsRotation()](VRageMath.Matrix.IsRotation)||
|\\%1bool IsValid()](VRageMath.Matrix.IsValid)||
|\\%1void SetDirectionVector(Direction, Vector3)](VRageMath.Matrix.SetDirectionVector)||
|\\%1void SetFrom(ref MatrixD)](VRageMath.Matrix.SetFrom)|Set this ma|
|\\%1void SetRotationAndScale(ref MatrixD)](VRageMath.Matrix.SetRotationAndScale)||
|\\%1void SetRow(int, Vector4)](VRageMath.Matrix.SetRow)||
|\\%1string ToString()](VRageMath.Matrix.ToString)|Retrieves a string representation of the current object.|
|\\%1void TransposeRotationInPlace()](VRageMath.Matrix.TransposeRotationInPlace)|Transposes the rows and columns of a matrix that is assumed to be rotation only in place.|

