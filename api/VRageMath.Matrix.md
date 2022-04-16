← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### Matrix Struct

```csharp
public struct Matrix: IEquatable<Matrix>
```

Defines a matrix.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable&lt;Matrix&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[static Matrix Identity](VRageMath.Matrix.Identity)||
|[static Matrix Zero](VRageMath.Matrix.Zero)||
|[float M11](VRageMath.Matrix.M11)|Value at row 1 column 1 of the matrix.|
|[float M12](VRageMath.Matrix.M12)|Value at row 1 column 2 of the matrix.|
|[float M13](VRageMath.Matrix.M13)|Value at row 1 column 3 of the matrix.|
|[float M14](VRageMath.Matrix.M14)|Value at row 1 column 4 of the matrix.|
|[float M21](VRageMath.Matrix.M21)|Value at row 2 column 1 of the matrix.|
|[float M22](VRageMath.Matrix.M22)|Value at row 2 column 2 of the matrix.|
|[float M23](VRageMath.Matrix.M23)|Value at row 2 column 3 of the matrix.|
|[float M24](VRageMath.Matrix.M24)|Value at row 2 column 4 of the matrix.|
|[float M31](VRageMath.Matrix.M31)|Value at row 3 column 1 of the matrix.|
|[float M32](VRageMath.Matrix.M32)|Value at row 3 column 2 of the matrix.|
|[float M33](VRageMath.Matrix.M33)|Value at row 3 column 3 of the matrix.|
|[float M34](VRageMath.Matrix.M34)|Value at row 3 column 4 of the matrix.|
|[float M41](VRageMath.Matrix.M41)|Value at row 4 column 1 of the matrix.|
|[float M42](VRageMath.Matrix.M42)|Value at row 4 column 2 of the matrix.|
|[float M43](VRageMath.Matrix.M43)|Value at row 4 column 3 of the matrix.|
|[float M44](VRageMath.Matrix.M44)|Value at row 4 column 4 of the matrix.|

#### Properties

|Member|Description|
|---|---|
|[Vector3 Backward { get; set; }](VRageMath.Matrix.Backward)|Gets and sets the backward vector of the Matrix.|
|[Vector3 Col0 { get; }](VRageMath.Matrix.Col0)||
|[Vector3 Col1 { get; }](VRageMath.Matrix.Col1)||
|[Vector3 Col2 { get; }](VRageMath.Matrix.Col2)||
|[Vector3 Down { get; set; }](VRageMath.Matrix.Down)|Gets and sets the down vector of the Matrix.|
|[Vector3 Forward { get; set; }](VRageMath.Matrix.Forward)|Gets and sets the forward vector of the Matrix.|
|[float Item { get; set; }](VRageMath.Matrix.Item)||
|[Vector3 Left { get; set; }](VRageMath.Matrix.Left)|Gets and sets the left vector of the Matrix.|
|[Vector3 Right { get; set; }](VRageMath.Matrix.Right)|Gets and sets the right vector of the Matrix.|
|[Vector3 Scale { get; }](VRageMath.Matrix.Scale)||
|[Vector3 Translation { get; set; }](VRageMath.Matrix.Translation)|Gets and sets the translation vector of the Matrix.|
|[Vector3 Up { get; set; }](VRageMath.Matrix.Up)|Gets and sets the up vector of the Matrix.|

#### Constructors

|Member|Description|
|---|---|
|[Matrix(float, float, float, float, float, float, float, float, float, float, float, float, float, float, float, float)](VRageMath.Matrix..ctor)||
|[Matrix(float, float, float, float, float, float, float, float, float)](VRageMath.Matrix..ctor)||
|[Matrix(MatrixD)](VRageMath.Matrix..ctor)||

#### Methods

|Member|Description|
|---|---|
|[static Matrix Add(Matrix, Matrix)](VRageMath.Matrix.Add)|Adds a matrix to another matrix.|
|[static void Add(ref Matrix, ref Matrix, out Matrix)](VRageMath.Matrix.Add)|Adds a matrix to another matrix.|
|[static Matrix AlignRotationToAxes(ref Matrix, ref Matrix)](VRageMath.Matrix.AlignRotationToAxes)||
|[static Matrix CreateBillboard(Vector3, Vector3, Vector3, Vector3?)](VRageMath.Matrix.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|[static void CreateBillboard(ref Vector3, ref Vector3, ref Vector3, Vector3?, out Matrix)](VRageMath.Matrix.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|[static Matrix CreateConstrainedBillboard(Vector3, Vector3, Vector3, Vector3?, Vector3?)](VRageMath.Matrix.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|[static void CreateConstrainedBillboard(ref Vector3, ref Vector3, ref Vector3, Vector3?, Vector3?, out Matrix)](VRageMath.Matrix.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|[static Matrix CreateFromAxisAngle(Vector3, float)](VRageMath.Matrix.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|[static void CreateFromAxisAngle(ref Vector3, float, out Matrix)](VRageMath.Matrix.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|[static Matrix CreateFromDir(Vector3)](VRageMath.Matrix.CreateFromDir)||
|[static Matrix CreateFromDir(Vector3, Vector3)](VRageMath.Matrix.CreateFromDir)||
|[static Matrix CreateFromPerspectiveFieldOfView(ref Matrix, float, float)](VRageMath.Matrix.CreateFromPerspectiveFieldOfView)||
|[static Matrix CreateFromQuaternion(Quaternion)](VRageMath.Matrix.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|[static void CreateFromQuaternion(ref Quaternion, out Matrix)](VRageMath.Matrix.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|[static Matrix CreateFromTransformScale(Quaternion, Vector3, Vector3)](VRageMath.Matrix.CreateFromTransformScale)||
|[static Matrix CreateFromYawPitchRoll(float, float, float)](VRageMath.Matrix.CreateFromYawPitchRoll)|Creates a new rotation matrix from a specified yaw, pitch, and roll.|
|[static void CreateFromYawPitchRoll(float, float, float, out Matrix)](VRageMath.Matrix.CreateFromYawPitchRoll)|Fills in a rotation matrix from a specified yaw, pitch, and roll.|
|[static Matrix CreateLookAt(Vector3, Vector3, Vector3)](VRageMath.Matrix.CreateLookAt)|Creates a view matrix.|
|[static void CreateLookAt(ref Vector3, ref Vector3, ref Vector3, out Matrix)](VRageMath.Matrix.CreateLookAt)|Creates a view matrix.|
|[static Matrix CreateLookAtInverse(Vector3, Vector3, Vector3)](VRageMath.Matrix.CreateLookAtInverse)||
|[static Matrix CreateOrthographic(float, float, float, float)](VRageMath.Matrix.CreateOrthographic)|Builds an orthogonal projection matrix.|
|[static void CreateOrthographic(float, float, float, float, out Matrix)](VRageMath.Matrix.CreateOrthographic)|Builds an orthogonal projection matrix.|
|[static Matrix CreateOrthographicOffCenter(float, float, float, float, float, float)](VRageMath.Matrix.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|[static void CreateOrthographicOffCenter(float, float, float, float, float, float, out Matrix)](VRageMath.Matrix.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|[static Matrix CreatePerspective(float, float, float, float)](VRageMath.Matrix.CreatePerspective)|Builds a perspective projection matrix and returns the result by value.|
|[static void CreatePerspective(float, float, float, float, out Matrix)](VRageMath.Matrix.CreatePerspective)|Builds a perspective projection matrix and returns the result by reference.|
|[static Matrix CreatePerspectiveFieldOfView(float, float, float, float)](VRageMath.Matrix.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by value.|
|[static void CreatePerspectiveFieldOfView(float, float, float, float, out Matrix)](VRageMath.Matrix.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by reference.|
|[static Matrix CreatePerspectiveFovRhComplementary(float, float, float, float)](VRageMath.Matrix.CreatePerspectiveFovRhComplementary)||
|[static Matrix CreatePerspectiveFovRhInfinite(float, float, float)](VRageMath.Matrix.CreatePerspectiveFovRhInfinite)||
|[static Matrix CreatePerspectiveFovRhInfiniteComplementary(float, float, float)](VRageMath.Matrix.CreatePerspectiveFovRhInfiniteComplementary)||
|[static Matrix CreatePerspectiveFovRhInfiniteComplementaryInverse(float, float, float)](VRageMath.Matrix.CreatePerspectiveFovRhInfiniteComplementaryInverse)||
|[static Matrix CreatePerspectiveFovRhInfiniteInverse(float, float, float)](VRageMath.Matrix.CreatePerspectiveFovRhInfiniteInverse)||
|[static Matrix CreatePerspectiveFovRhInverse(float, float, float, float)](VRageMath.Matrix.CreatePerspectiveFovRhInverse)||
|[static Matrix CreatePerspectiveOffCenter(float, float, float, float, float, float)](VRageMath.Matrix.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|[static void CreatePerspectiveOffCenter(float, float, float, float, float, float, out Matrix)](VRageMath.Matrix.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|[static Matrix CreateReflection(Plane)](VRageMath.Matrix.CreateReflection)|Creates a Matrix that reflects the coordinate system about a specified Plane.|
|[static void CreateReflection(ref Plane, out Matrix)](VRageMath.Matrix.CreateReflection)|Fills in an existing Matrix so that it reflects the coordinate system about a specified Plane.|
|[static void CreateRotationFromTwoVectors(ref Vector3, ref Vector3, out Matrix)](VRageMath.Matrix.CreateRotationFromTwoVectors)||
|[static Matrix CreateRotationX(float)](VRageMath.Matrix.CreateRotationX)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|[static void CreateRotationX(float, out Matrix)](VRageMath.Matrix.CreateRotationX)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the x-axis.|
|[static Matrix CreateRotationY(float)](VRageMath.Matrix.CreateRotationY)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|[static void CreateRotationY(float, out Matrix)](VRageMath.Matrix.CreateRotationY)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the y-axis.|
|[static Matrix CreateRotationZ(float)](VRageMath.Matrix.CreateRotationZ)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|[static void CreateRotationZ(float, out Matrix)](VRageMath.Matrix.CreateRotationZ)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the z-axis.|
|[static Matrix CreateScale(float, float, float)](VRageMath.Matrix.CreateScale)|Creates a scaling Matrix.|
|[static void CreateScale(float, float, float, out Matrix)](VRageMath.Matrix.CreateScale)|Creates a scaling Matrix.|
|[static Matrix CreateScale(Vector3)](VRageMath.Matrix.CreateScale)|Creates a scaling Matrix.|
|[static void CreateScale(ref Vector3, out Matrix)](VRageMath.Matrix.CreateScale)|Creates a scaling Matrix.|
|[static Matrix CreateScale(float)](VRageMath.Matrix.CreateScale)|Creates a scaling Matrix.|
|[static void CreateScale(float, out Matrix)](VRageMath.Matrix.CreateScale)|Creates a scaling Matrix.|
|[static Matrix CreateShadow(Vector3, Plane)](VRageMath.Matrix.CreateShadow)|Creates a Matrix that flattens geometry into a specified Plane as if casting a shadow from a specified light source.|
|[static void CreateShadow(ref Vector3, ref Plane, out Matrix)](VRageMath.Matrix.CreateShadow)|Fills in a Matrix to flatten geometry into a specified Plane as if casting a shadow from a specified light source.|
|[static Matrix CreateTranslation(Vector3)](VRageMath.Matrix.CreateTranslation)|Creates a translation Matrix.|
|[static void CreateTranslation(ref Vector3, out Matrix)](VRageMath.Matrix.CreateTranslation)|Creates a translation Matrix.|
|[static Matrix CreateTranslation(float, float, float)](VRageMath.Matrix.CreateTranslation)|Creates a translation Matrix.|
|[static void CreateTranslation(float, float, float, out Matrix)](VRageMath.Matrix.CreateTranslation)|Creates a translation Matrix.|
|[static Matrix CreateWorld(Vector3)](VRageMath.Matrix.CreateWorld)||
|[static Matrix CreateWorld(Vector3, Vector3, Vector3)](VRageMath.Matrix.CreateWorld)|Creates a world matrix with the specified parameters.|
|[static void CreateWorld(ref Vector3, ref Vector3, ref Vector3, out Matrix)](VRageMath.Matrix.CreateWorld)|Creates a world matrix with the specified parameters.|
|[static Matrix Divide(Matrix, Matrix)](VRageMath.Matrix.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|[static void Divide(ref Matrix, ref Matrix, out Matrix)](VRageMath.Matrix.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|[static Matrix Divide(Matrix, float)](VRageMath.Matrix.Divide)|Divides the components of a matrix by a scalar.|
|[static void Divide(ref Matrix, float, out Matrix)](VRageMath.Matrix.Divide)|Divides the components of a matrix by a scalar.|
|[static bool GetEulerAnglesXYZ(ref Matrix, out Vector3)](VRageMath.Matrix.GetEulerAnglesXYZ)||
|[static Matrix Invert(Matrix)](VRageMath.Matrix.Invert)|Calculates the inverse of a matrix.|
|[static Matrix Invert(ref Matrix)](VRageMath.Matrix.Invert)||
|[static void Invert(ref Matrix, out Matrix)](VRageMath.Matrix.Invert)|Calculates the inverse of a matrix.|
|[static Matrix Lerp(Matrix, Matrix, float)](VRageMath.Matrix.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|[static void Lerp(ref Matrix, ref Matrix, float, out Matrix)](VRageMath.Matrix.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|[static Matrix Multiply(Matrix, Matrix)](VRageMath.Matrix.Multiply)|Multiplies a matrix by another matrix.|
|[static void Multiply(ref Matrix, ref Matrix, out Matrix)](VRageMath.Matrix.Multiply)|Multiplies a matrix by another matrix.|
|[static Matrix Multiply(Matrix, float)](VRageMath.Matrix.Multiply)|Multiplies a matrix by a scalar value.|
|[static void Multiply(ref Matrix, float, out Matrix)](VRageMath.Matrix.Multiply)|Multiplies a matrix by a scalar value.|
|[static void MultiplyRotation(ref Matrix, ref Matrix, out Matrix)](VRageMath.Matrix.MultiplyRotation)|Multiplies a matrix by another matrix, only rotation parts.|
|[static Matrix Negate(Matrix)](VRageMath.Matrix.Negate)|Negates individual elements of a matrix.|
|[static void Negate(ref Matrix, out Matrix)](VRageMath.Matrix.Negate)|Negates individual elements of a matrix.|
|[static Matrix Normalize(Matrix)](VRageMath.Matrix.Normalize)||
|[static Matrix Orthogonalize(Matrix)](VRageMath.Matrix.Orthogonalize)||
|[static void Rescale(ref Matrix, float)](VRageMath.Matrix.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|[static void Rescale(ref Matrix, ref Vector3)](VRageMath.Matrix.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|[static Matrix Rescale(Matrix, float)](VRageMath.Matrix.Rescale)||
|[static Matrix Rescale(Matrix, Vector3)](VRageMath.Matrix.Rescale)||
|[static Matrix Round(ref Matrix)](VRageMath.Matrix.Round)||
|[static void Slerp(ref Matrix, ref Matrix, float, out Matrix)](VRageMath.Matrix.Slerp)|Performs spherical linear interpolation of position and rotation.|
|[static void Slerp(Matrix, Matrix, float, out Matrix)](VRageMath.Matrix.Slerp)|Performs spherical linear interpolation of position and rotation.|
|[static Matrix Slerp(Matrix, Matrix, float)](VRageMath.Matrix.Slerp)|Performs spherical linear interpolation of position and rotation.|
|[static void SlerpScale(ref Matrix, ref Matrix, float, out Matrix)](VRageMath.Matrix.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|[static void SlerpScale(Matrix, Matrix, float, out Matrix)](VRageMath.Matrix.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|[static Matrix SlerpScale(Matrix, Matrix, float)](VRageMath.Matrix.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|[static void Subtract(ref Matrix, ref Matrix, out Matrix)](VRageMath.Matrix.Subtract)|Subtracts matrices.|
|[static Matrix Subtract(Matrix, Matrix)](VRageMath.Matrix.Subtract)|Subtracts matrices.|
|[static Matrix SwapYZCoordinates(Matrix)](VRageMath.Matrix.SwapYZCoordinates)||
|[static Matrix Transform(Matrix, Quaternion)](VRageMath.Matrix.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|[static void Transform(ref Matrix, ref Quaternion, out Matrix)](VRageMath.Matrix.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|[static Matrix Transpose(Matrix)](VRageMath.Matrix.Transpose)|Transposes the rows and columns of a matrix.|
|[static void Transpose(ref Matrix, out Matrix)](VRageMath.Matrix.Transpose)|Transposes the rows and columns of a matrix.|
|[void AssertIsValid()](VRageMath.Matrix.AssertIsValid)||
|[float Determinant()](VRageMath.Matrix.Determinant)|Calculates the determinant of the matrix.|
|[bool Equals(Matrix)](VRageMath.Matrix.Equals)|Determines whether the specified Object is equal to the Matrix.|
|[bool Equals(object)](VRageMath.Matrix.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[bool EqualsFast(ref Matrix, float = 0.0001)](VRageMath.Matrix.EqualsFast)|Compares just position, forward and up|
|[Direction GetClosestDirection(Vector3)](VRageMath.Matrix.GetClosestDirection)||
|[Direction GetClosestDirection(ref Vector3)](VRageMath.Matrix.GetClosestDirection)||
|[Vector3 GetDirectionVector(Direction)](VRageMath.Matrix.GetDirectionVector)||
|[int GetHashCode()](VRageMath.Matrix.GetHashCode)|Gets the hash code of this object.|
|[Matrix GetOrientation()](VRageMath.Matrix.GetOrientation)|Gets the orientation.|
|[Vector4 GetRow(int)](VRageMath.Matrix.GetRow)||
|[bool HasNoTranslationOrPerspective()](VRageMath.Matrix.HasNoTranslationOrPerspective)|Returns true if this matrix represents invertible (you can call Invert on it) linear (it does not contain translation or perspective transformation) transformation. Such matrix consist solely of rotations, shearing, mirroring and scaling. It can be orthogonalized to create an orthogonal rotation matrix.|
|[bool IsMirrored()](VRageMath.Matrix.IsMirrored)||
|[bool IsNan()](VRageMath.Matrix.IsNan)||
|[bool IsOrthogonal()](VRageMath.Matrix.IsOrthogonal)||
|[bool IsRotation()](VRageMath.Matrix.IsRotation)||
|[bool IsValid()](VRageMath.Matrix.IsValid)||
|[void SetDirectionVector(Direction, Vector3)](VRageMath.Matrix.SetDirectionVector)||
|[void SetFrom(ref MatrixD)](VRageMath.Matrix.SetFrom)|Set this ma|
|[void SetRotationAndScale(ref MatrixD)](VRageMath.Matrix.SetRotationAndScale)||
|[void SetRow(int, Vector4)](VRageMath.Matrix.SetRow)||
|[string ToString()](VRageMath.Matrix.ToString)|Retrieves a string representation of the current object.|
|[void TransposeRotationInPlace()](VRageMath.Matrix.TransposeRotationInPlace)|Transposes the rows and columns of a matrix that is assumed to be rotation only in place.|

