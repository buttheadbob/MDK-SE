← [Index](index)
# Matrix Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a matrix.
### Fields
<table style="width: 100%">
<tr><td>[`float M11`](VRageMath.M11)</td><td>Value at row 1 column 1 of the matrix.</td></tr>
<tr><td>[`float M12`](VRageMath.M12)</td><td>Value at row 1 column 2 of the matrix.</td></tr>
<tr><td>[`float M13`](VRageMath.M13)</td><td>Value at row 1 column 3 of the matrix.</td></tr>
<tr><td>[`float M14`](VRageMath.M14)</td><td>Value at row 1 column 4 of the matrix.</td></tr>
<tr><td>[`float M21`](VRageMath.M21)</td><td>Value at row 2 column 1 of the matrix.</td></tr>
<tr><td>[`float M22`](VRageMath.M22)</td><td>Value at row 2 column 2 of the matrix.</td></tr>
<tr><td>[`float M23`](VRageMath.M23)</td><td>Value at row 2 column 3 of the matrix.</td></tr>
<tr><td>[`float M24`](VRageMath.M24)</td><td>Value at row 2 column 4 of the matrix.</td></tr>
<tr><td>[`float M31`](VRageMath.M31)</td><td>Value at row 3 column 1 of the matrix.</td></tr>
<tr><td>[`float M32`](VRageMath.M32)</td><td>Value at row 3 column 2 of the matrix.</td></tr>
<tr><td>[`float M33`](VRageMath.M33)</td><td>Value at row 3 column 3 of the matrix.</td></tr>
<tr><td>[`float M34`](VRageMath.M34)</td><td>Value at row 3 column 4 of the matrix.</td></tr>
<tr><td>[`float M41`](VRageMath.M41)</td><td>Value at row 4 column 1 of the matrix.</td></tr>
<tr><td>[`float M42`](VRageMath.M42)</td><td>Value at row 4 column 2 of the matrix.</td></tr>
<tr><td>[`float M43`](VRageMath.M43)</td><td>Value at row 4 column 3 of the matrix.</td></tr>
<tr><td>[`float M44`](VRageMath.M44)</td><td>Value at row 4 column 4 of the matrix.</td></tr>
<tr><td>static [`Matrix Identity`](VRageMath.Identity)</td><td></td></tr>
<tr><td>static [`Matrix Zero`](VRageMath.Zero)</td><td></td></tr>
</table>
### Properties
<table style="width: 100%">
<tr><td>[`Vector3 Up`](VRageMath.Up)</td><td>Gets and sets the up vector of the Matrix.</td></tr>
<tr><td>[`Vector3 Down`](VRageMath.Down)</td><td>Gets and sets the down vector of the Matrix.</td></tr>
<tr><td>[`Vector3 Right`](VRageMath.Right)</td><td>Gets and sets the right vector of the Matrix.</td></tr>
<tr><td>[`Vector3 Col0`](VRageMath.Col0)</td><td></td></tr>
<tr><td>[`Vector3 Col1`](VRageMath.Col1)</td><td></td></tr>
<tr><td>[`Vector3 Col2`](VRageMath.Col2)</td><td></td></tr>
<tr><td>[`Vector3 Left`](VRageMath.Left)</td><td>Gets and sets the left vector of the Matrix.</td></tr>
<tr><td>[`Vector3 Forward`](VRageMath.Forward)</td><td>Gets and sets the forward vector of the Matrix.</td></tr>
<tr><td>[`Vector3 Backward`](VRageMath.Backward)</td><td>Gets and sets the backward vector of the Matrix.</td></tr>
<tr><td>[`Vector3 Scale`](VRageMath.Scale)</td><td></td></tr>
<tr><td>[`Vector3 Translation`](VRageMath.Translation)</td><td>Gets and sets the translation vector of the Matrix.</td></tr>
<tr><td>[`float Item`](VRageMath.Item)</td><td></td></tr>
</table>
### Methods
<table style="width: 100%">
<tr><td>static [`void Subtract(ref Matrix matrix1, ref Matrix matrix2, ref Matrix result)`](VRageMath.Subtract)</td><td>Subtracts matrices.</td></tr>
<tr><td>static [`Matrix Multiply(Matrix matrix1, Matrix matrix2)`](VRageMath.Multiply)</td><td>Multiplies a matrix by another matrix.</td></tr>
<tr><td>static [`void Multiply(ref Matrix matrix1, ref Matrix matrix2, ref Matrix result)`](VRageMath.Multiply)</td><td>Multiplies a matrix by another matrix.</td></tr>
<tr><td>static [`void MultiplyRotation(ref Matrix matrix1, ref Matrix matrix2, ref Matrix result)`](VRageMath.MultiplyRotation)</td><td>Multiplies a matrix by another matrix, only rotation parts.</td></tr>
<tr><td>static [`Matrix Multiply(Matrix matrix1, float scaleFactor)`](VRageMath.Multiply)</td><td>Multiplies a matrix by a scalar value.</td></tr>
<tr><td>static [`void Multiply(ref Matrix matrix1, float scaleFactor, ref Matrix result)`](VRageMath.Multiply)</td><td>Multiplies a matrix by a scalar value.</td></tr>
<tr><td>static [`Matrix Divide(Matrix matrix1, Matrix matrix2)`](VRageMath.Divide)</td><td>Divides the components of a matrix by the corresponding components of another matrix.</td></tr>
<tr><td>static [`void Divide(ref Matrix matrix1, ref Matrix matrix2, ref Matrix result)`](VRageMath.Divide)</td><td>Divides the components of a matrix by the corresponding components of another matrix.</td></tr>
<tr><td>static [`Matrix Divide(Matrix matrix1, float divider)`](VRageMath.Divide)</td><td>Divides the components of a matrix by a scalar.</td></tr>
<tr><td>static [`void Divide(ref Matrix matrix1, float divider, ref Matrix result)`](VRageMath.Divide)</td><td>Divides the components of a matrix by a scalar.</td></tr>
<tr><td>[`Matrix GetOrientation()`](VRageMath.GetOrientation)</td><td>Gets the orientation.</td></tr>
<tr><td>[`void AssertIsValid()`](VRageMath.AssertIsValid)</td><td></td></tr>
<tr><td>[`bool IsValid()`](VRageMath.IsValid)</td><td></td></tr>
<tr><td>[`bool IsNan()`](VRageMath.IsNan)</td><td></td></tr>
<tr><td>[`bool IsRotation()`](VRageMath.IsRotation)</td><td></td></tr>
<tr><td>[`bool HasNoTranslationOrPerspective()`](VRageMath.HasNoTranslationOrPerspective)</td><td>Returns true if this matrix represents invertible (you can call Invert on it) linear (it does not contain translation or perspective transformation) transformation. Such matrix consist solely of rotations, shearing, mirroring and scaling. It can be orthogonalized to create an orthogonal rotation matrix.</td></tr>
<tr><td>static [`Matrix CreateFromDir(Vector3 dir)`](VRageMath.CreateFromDir)</td><td></td></tr>
<tr><td>static [`Matrix CreateFromDir(Vector3 dir, Vector3 suggestedUp)`](VRageMath.CreateFromDir)</td><td></td></tr>
<tr><td>static [`Matrix Normalize(Matrix matrix)`](VRageMath.Normalize)</td><td></td></tr>
<tr><td>static [`Matrix Orthogonalize(Matrix rotationMatrix)`](VRageMath.Orthogonalize)</td><td></td></tr>
<tr><td>static [`Matrix Round(ref Matrix matrix)`](VRageMath.Round)</td><td></td></tr>
<tr><td>static [`Matrix AlignRotationToAxes(ref Matrix toAlign, ref Matrix axisDefinitionMatrix)`](VRageMath.AlignRotationToAxes)</td><td></td></tr>
<tr><td>static [`bool GetEulerAnglesXYZ(ref Matrix mat, ref Vector3 xyz)`](VRageMath.GetEulerAnglesXYZ)</td><td></td></tr>
<tr><td>static [`Matrix SwapYZCoordinates(Matrix m)`](VRageMath.SwapYZCoordinates)</td><td></td></tr>
<tr><td>[`bool IsMirrored()`](VRageMath.IsMirrored)</td><td></td></tr>
<tr><td>[`bool IsOrthogonal()`](VRageMath.IsOrthogonal)</td><td></td></tr>
<tr><td>[`Vector3 GetDirectionVector(Direction direction)`](VRageMath.GetDirectionVector)</td><td></td></tr>
<tr><td>[`void SetDirectionVector(Direction direction, Vector3 newValue)`](VRageMath.SetDirectionVector)</td><td></td></tr>
<tr><td>[`Direction GetClosestDirection(Vector3 referenceVector)`](VRageMath.GetClosestDirection)</td><td></td></tr>
<tr><td>[`Direction GetClosestDirection(ref Vector3 referenceVector)`](VRageMath.GetClosestDirection)</td><td></td></tr>
<tr><td>static [`void Rescale(ref Matrix matrix, float scale)`](VRageMath.Rescale)</td><td>Same result as Matrix.CreateScale(scale) * matrix, but much faster</td></tr>
<tr><td>static [`void Rescale(ref Matrix matrix, ref Vector3 scale)`](VRageMath.Rescale)</td><td>Same result as Matrix.CreateScale(scale) * matrix, but much faster</td></tr>
<tr><td>static [`Matrix Rescale(Matrix matrix, float scale)`](VRageMath.Rescale)</td><td></td></tr>
<tr><td>static [`Matrix Rescale(Matrix matrix, Vector3 scale)`](VRageMath.Rescale)</td><td></td></tr>
<tr><td>static [`Matrix CreateBillboard(Vector3 objectPosition, Vector3 cameraPosition, Vector3 cameraUpVector, Nullable<Vector3> cameraForwardVector)`](VRageMath.CreateBillboard)</td><td>Creates a spherical billboard that rotates around a specified object position.</td></tr>
<tr><td>static [`void CreateBillboard(ref Vector3 objectPosition, ref Vector3 cameraPosition, ref Vector3 cameraUpVector, Nullable<Vector3> cameraForwardVector, ref Matrix result)`](VRageMath.CreateBillboard)</td><td>Creates a spherical billboard that rotates around a specified object position.</td></tr>
<tr><td>static [`Matrix CreateConstrainedBillboard(Vector3 objectPosition, Vector3 cameraPosition, Vector3 rotateAxis, Nullable<Vector3> cameraForwardVector, Nullable<Vector3> objectForwardVector)`](VRageMath.CreateConstrainedBillboard)</td><td>Creates a cylindrical billboard that rotates around a specified axis.</td></tr>
<tr><td>static [`void CreateConstrainedBillboard(ref Vector3 objectPosition, ref Vector3 cameraPosition, ref Vector3 rotateAxis, Nullable<Vector3> cameraForwardVector, Nullable<Vector3> objectForwardVector, ref Matrix result)`](VRageMath.CreateConstrainedBillboard)</td><td>Creates a cylindrical billboard that rotates around a specified axis.</td></tr>
<tr><td>static [`Matrix CreateTranslation(Vector3 position)`](VRageMath.CreateTranslation)</td><td>Creates a translation Matrix.</td></tr>
<tr><td>static [`void CreateTranslation(ref Vector3 position, ref Matrix result)`](VRageMath.CreateTranslation)</td><td>Creates a translation Matrix.</td></tr>
<tr><td>static [`Matrix CreateTranslation(float xPosition, float yPosition, float zPosition)`](VRageMath.CreateTranslation)</td><td>Creates a translation Matrix.</td></tr>
<tr><td>static [`void CreateTranslation(float xPosition, float yPosition, float zPosition, ref Matrix result)`](VRageMath.CreateTranslation)</td><td>Creates a translation Matrix.</td></tr>
<tr><td>static [`Matrix CreateScale(float xScale, float yScale, float zScale)`](VRageMath.CreateScale)</td><td>Creates a scaling Matrix.</td></tr>
<tr><td>static [`void CreateScale(float xScale, float yScale, float zScale, ref Matrix result)`](VRageMath.CreateScale)</td><td>Creates a scaling Matrix.</td></tr>
<tr><td>static [`Matrix CreateScale(Vector3 scales)`](VRageMath.CreateScale)</td><td>Creates a scaling Matrix.</td></tr>
<tr><td>static [`void CreateScale(ref Vector3 scales, ref Matrix result)`](VRageMath.CreateScale)</td><td>Creates a scaling Matrix.</td></tr>
<tr><td>static [`Matrix CreateScale(float scale)`](VRageMath.CreateScale)</td><td>Creates a scaling Matrix.</td></tr>
<tr><td>static [`void CreateScale(float scale, ref Matrix result)`](VRageMath.CreateScale)</td><td>Creates a scaling Matrix.</td></tr>
<tr><td>static [`Matrix CreateRotationX(float radians)`](VRageMath.CreateRotationX)</td><td>Returns a matrix that can be used to rotate a set of vertices around the x-axis.</td></tr>
<tr><td>static [`void CreateRotationX(float radians, ref Matrix result)`](VRageMath.CreateRotationX)</td><td>Populates data into a user-specified matrix that can be used to rotate a set of vertices around the x-axis.</td></tr>
<tr><td>static [`Matrix CreateRotationY(float radians)`](VRageMath.CreateRotationY)</td><td>Returns a matrix that can be used to rotate a set of vertices around the y-axis.</td></tr>
<tr><td>static [`void CreateRotationY(float radians, ref Matrix result)`](VRageMath.CreateRotationY)</td><td>Populates data into a user-specified matrix that can be used to rotate a set of vertices around the y-axis.</td></tr>
<tr><td>static [`Matrix CreateRotationZ(float radians)`](VRageMath.CreateRotationZ)</td><td>Returns a matrix that can be used to rotate a set of vertices around the z-axis.</td></tr>
<tr><td>static [`void CreateRotationZ(float radians, ref Matrix result)`](VRageMath.CreateRotationZ)</td><td>Populates data into a user-specified matrix that can be used to rotate a set of vertices around the z-axis.</td></tr>
<tr><td>static [`Matrix CreateFromAxisAngle(Vector3 axis, float angle)`](VRageMath.CreateFromAxisAngle)</td><td>Creates a new Matrix that rotates around an arbitrary vector.</td></tr>
<tr><td>static [`void CreateFromAxisAngle(ref Vector3 axis, float angle, ref Matrix result)`](VRageMath.CreateFromAxisAngle)</td><td>Creates a new Matrix that rotates around an arbitrary vector.</td></tr>
<tr><td>static [`void CreateRotationFromTwoVectors(ref Vector3 fromVector, ref Vector3 toVector, ref Matrix resultMatrix)`](VRageMath.CreateRotationFromTwoVectors)</td><td></td></tr>
<tr><td>static [`Matrix CreatePerspectiveFieldOfView(float fieldOfView, float aspectRatio, float nearPlaneDistance, float farPlaneDistance)`](VRageMath.CreatePerspectiveFieldOfView)</td><td>Builds a perspective projection matrix based on a field of view and returns by value.</td></tr>
<tr><td>static [`Matrix CreatePerspectiveFovRhComplementary(float fieldOfView, float aspectRatio, float nearPlaneDistance, float farPlaneDistance)`](VRageMath.CreatePerspectiveFovRhComplementary)</td><td></td></tr>
<tr><td>static [`Matrix CreatePerspectiveFovRhInfinite(float fieldOfView, float aspectRatio, float nearPlaneDistance)`](VRageMath.CreatePerspectiveFovRhInfinite)</td><td></td></tr>
<tr><td>static [`Matrix CreatePerspectiveFovRhInfiniteComplementary(float fieldOfView, float aspectRatio, float nearPlaneDistance)`](VRageMath.CreatePerspectiveFovRhInfiniteComplementary)</td><td></td></tr>
<tr><td>static [`Matrix CreatePerspectiveFovRhInverse(float fieldOfView, float aspectRatio, float nearPlaneDistance, float farPlaneDistance)`](VRageMath.CreatePerspectiveFovRhInverse)</td><td></td></tr>
<tr><td>static [`Matrix CreatePerspectiveFovRhInfiniteInverse(float fieldOfView, float aspectRatio, float nearPlaneDistance)`](VRageMath.CreatePerspectiveFovRhInfiniteInverse)</td><td></td></tr>
<tr><td>static [`Matrix CreatePerspectiveFovRhInfiniteComplementaryInverse(float fieldOfView, float aspectRatio, float nearPlaneDistance)`](VRageMath.CreatePerspectiveFovRhInfiniteComplementaryInverse)</td><td></td></tr>
<tr><td>static [`Matrix CreateFromPerspectiveFieldOfView(ref Matrix proj, float nearPlaneDistance, float farPlaneDistance)`](VRageMath.CreateFromPerspectiveFieldOfView)</td><td></td></tr>
<tr><td>static [`void CreatePerspectiveFieldOfView(float fieldOfView, float aspectRatio, float nearPlaneDistance, float farPlaneDistance, ref Matrix result)`](VRageMath.CreatePerspectiveFieldOfView)</td><td>Builds a perspective projection matrix based on a field of view and returns by reference.</td></tr>
<tr><td>static [`Matrix CreatePerspective(float width, float height, float nearPlaneDistance, float farPlaneDistance)`](VRageMath.CreatePerspective)</td><td>Builds a perspective projection matrix and returns the result by value.</td></tr>
<tr><td>static [`void CreatePerspective(float width, float height, float nearPlaneDistance, float farPlaneDistance, ref Matrix result)`](VRageMath.CreatePerspective)</td><td>Builds a perspective projection matrix and returns the result by reference.</td></tr>
<tr><td>static [`Matrix CreatePerspectiveOffCenter(float left, float right, float bottom, float top, float nearPlaneDistance, float farPlaneDistance)`](VRageMath.CreatePerspectiveOffCenter)</td><td>Builds a customized, perspective projection matrix.</td></tr>
<tr><td>static [`void CreatePerspectiveOffCenter(float left, float right, float bottom, float top, float nearPlaneDistance, float farPlaneDistance, ref Matrix result)`](VRageMath.CreatePerspectiveOffCenter)</td><td>Builds a customized, perspective projection matrix.</td></tr>
<tr><td>static [`Matrix CreateOrthographic(float width, float height, float zNearPlane, float zFarPlane)`](VRageMath.CreateOrthographic)</td><td>Builds an orthogonal projection matrix.</td></tr>
<tr><td>static [`void CreateOrthographic(float width, float height, float zNearPlane, float zFarPlane, ref Matrix result)`](VRageMath.CreateOrthographic)</td><td>Builds an orthogonal projection matrix.</td></tr>
<tr><td>static [`Matrix CreateOrthographicOffCenter(float left, float right, float bottom, float top, float zNearPlane, float zFarPlane)`](VRageMath.CreateOrthographicOffCenter)</td><td>Builds a customized, orthogonal projection matrix.</td></tr>
<tr><td>static [`void CreateOrthographicOffCenter(float left, float right, float bottom, float top, float zNearPlane, float zFarPlane, ref Matrix result)`](VRageMath.CreateOrthographicOffCenter)</td><td>Builds a customized, orthogonal projection matrix.</td></tr>
<tr><td>static [`Matrix CreateLookAt(Vector3 cameraPosition, Vector3 cameraTarget, Vector3 cameraUpVector)`](VRageMath.CreateLookAt)</td><td>Creates a view matrix.</td></tr>
<tr><td>static [`Matrix CreateLookAtInverse(Vector3 cameraPosition, Vector3 cameraTarget, Vector3 cameraUpVector)`](VRageMath.CreateLookAtInverse)</td><td></td></tr>
<tr><td>static [`void CreateLookAt(ref Vector3 cameraPosition, ref Vector3 cameraTarget, ref Vector3 cameraUpVector, ref Matrix result)`](VRageMath.CreateLookAt)</td><td>Creates a view matrix.</td></tr>
<tr><td>static [`Matrix CreateWorld(Vector3 position)`](VRageMath.CreateWorld)</td><td></td></tr>
<tr><td>static [`Matrix CreateWorld(Vector3 position, Vector3 forward, Vector3 up)`](VRageMath.CreateWorld)</td><td>Creates a world matrix with the specified parameters.</td></tr>
<tr><td>static [`void CreateWorld(ref Vector3 position, ref Vector3 forward, ref Vector3 up, ref Matrix result)`](VRageMath.CreateWorld)</td><td>Creates a world matrix with the specified parameters.</td></tr>
<tr><td>static [`Matrix CreateFromQuaternion(Quaternion quaternion)`](VRageMath.CreateFromQuaternion)</td><td>Creates a rotation Matrix from a Quaternion.</td></tr>
<tr><td>static [`void CreateFromQuaternion(ref Quaternion quaternion, ref Matrix result)`](VRageMath.CreateFromQuaternion)</td><td>Creates a rotation Matrix from a Quaternion.</td></tr>
<tr><td>static [`Matrix CreateFromYawPitchRoll(float yaw, float pitch, float roll)`](VRageMath.CreateFromYawPitchRoll)</td><td>Creates a new rotation matrix from a specified yaw, pitch, and roll.</td></tr>
<tr><td>static [`void CreateFromYawPitchRoll(float yaw, float pitch, float roll, ref Matrix result)`](VRageMath.CreateFromYawPitchRoll)</td><td>Fills in a rotation matrix from a specified yaw, pitch, and roll.</td></tr>
<tr><td>static [`Matrix CreateFromTransformScale(Quaternion orientation, Vector3 position, Vector3 scale)`](VRageMath.CreateFromTransformScale)</td><td></td></tr>
<tr><td>static [`Matrix CreateShadow(Vector3 lightDirection, Plane plane)`](VRageMath.CreateShadow)</td><td>Creates a Matrix that flattens geometry into a specified Plane as if casting a shadow from a specified light source.</td></tr>
<tr><td>static [`void CreateShadow(ref Vector3 lightDirection, ref Plane plane, ref Matrix result)`](VRageMath.CreateShadow)</td><td>Fills in a Matrix to flatten geometry into a specified Plane as if casting a shadow from a specified light source.</td></tr>
<tr><td>static [`Matrix CreateReflection(Plane value)`](VRageMath.CreateReflection)</td><td>Creates a Matrix that reflects the coordinate system about a specified Plane.</td></tr>
<tr><td>static [`void CreateReflection(ref Plane value, ref Matrix result)`](VRageMath.CreateReflection)</td><td>Fills in an existing Matrix so that it reflects the coordinate system about a specified Plane.</td></tr>
<tr><td>static [`Matrix Transform(Matrix value, Quaternion rotation)`](VRageMath.Transform)</td><td>Transforms a Matrix by applying a Quaternion rotation.</td></tr>
<tr><td>static [`void Transform(ref Matrix value, ref Quaternion rotation, ref Matrix result)`](VRageMath.Transform)</td><td>Transforms a Matrix by applying a Quaternion rotation.</td></tr>
<tr><td>[`Vector4 GetRow(int row)`](VRageMath.GetRow)</td><td></td></tr>
<tr><td>[`void SetRow(int row, Vector4 value)`](VRageMath.SetRow)</td><td></td></tr>
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td>Retrieves a string representation of the current object.</td></tr>
<tr><td>[`bool Equals(Matrix other)`](VRageMath.Equals)</td><td>Determines whether the specified Object is equal to the Matrix.</td></tr>
<tr><td>[`bool EqualsFast(ref Matrix other, float epsilon)`](VRageMath.EqualsFast)</td><td>Compares just position, forward and up</td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td>Returns a value that indicates whether the current instance is equal to a specified object.</td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td>Gets the hash code of this object.</td></tr>
<tr><td>static [`Matrix Transpose(Matrix matrix)`](VRageMath.Transpose)</td><td>Transposes the rows and columns of a matrix.</td></tr>
<tr><td>static [`void Transpose(ref Matrix matrix, ref Matrix result)`](VRageMath.Transpose)</td><td>Transposes the rows and columns of a matrix.</td></tr>
<tr><td>[`void TransposeRotationInPlace()`](VRageMath.TransposeRotationInPlace)</td><td>Transposes the rows and columns of a matrix that is assumed to be rotation only in place.</td></tr>
<tr><td>[`float Determinant()`](VRageMath.Determinant)</td><td>Calculates the determinant of the matrix.</td></tr>
<tr><td>static [`Matrix Invert(Matrix matrix)`](VRageMath.Invert)</td><td>Calculates the inverse of a matrix.</td></tr>
<tr><td>static [`Matrix Invert(ref Matrix matrix)`](VRageMath.Invert)</td><td></td></tr>
<tr><td>static [`void Invert(ref Matrix matrix, ref Matrix result)`](VRageMath.Invert)</td><td>Calculates the inverse of a matrix.</td></tr>
<tr><td>static [`Matrix Lerp(Matrix matrix1, Matrix matrix2, float amount)`](VRageMath.Lerp)</td><td>Linearly interpolates between the corresponding values of two matrices.</td></tr>
<tr><td>static [`void Lerp(ref Matrix matrix1, ref Matrix matrix2, float amount, ref Matrix result)`](VRageMath.Lerp)</td><td>Linearly interpolates between the corresponding values of two matrices.</td></tr>
<tr><td>static [`void Slerp(ref Matrix matrix1, ref Matrix matrix2, float amount, ref Matrix result)`](VRageMath.Slerp)</td><td>Performs spherical linear interpolation of position and rotation.</td></tr>
<tr><td>static [`void SlerpScale(ref Matrix matrix1, ref Matrix matrix2, float amount, ref Matrix result)`](VRageMath.SlerpScale)</td><td>Performs spherical linear interpolation of position and rotation and scale.</td></tr>
<tr><td>static [`void Slerp(Matrix matrix1, Matrix matrix2, float amount, ref Matrix result)`](VRageMath.Slerp)</td><td>Performs spherical linear interpolation of position and rotation.</td></tr>
<tr><td>static [`Matrix Slerp(Matrix matrix1, Matrix matrix2, float amount)`](VRageMath.Slerp)</td><td>Performs spherical linear interpolation of position and rotation.</td></tr>
<tr><td>static [`void SlerpScale(Matrix matrix1, Matrix matrix2, float amount, ref Matrix result)`](VRageMath.SlerpScale)</td><td>Performs spherical linear interpolation of position and rotation and scale.</td></tr>
<tr><td>static [`Matrix SlerpScale(Matrix matrix1, Matrix matrix2, float amount)`](VRageMath.SlerpScale)</td><td>Performs spherical linear interpolation of position and rotation and scale.</td></tr>
<tr><td>static [`Matrix Negate(Matrix matrix)`](VRageMath.Negate)</td><td>Negates individual elements of a matrix.</td></tr>
<tr><td>static [`void Negate(ref Matrix matrix, ref Matrix result)`](VRageMath.Negate)</td><td>Negates individual elements of a matrix.</td></tr>
<tr><td>static [`Matrix Add(Matrix matrix1, Matrix matrix2)`](VRageMath.Add)</td><td>Adds a matrix to another matrix.</td></tr>
<tr><td>static [`void Add(ref Matrix matrix1, ref Matrix matrix2, ref Matrix result)`](VRageMath.Add)</td><td>Adds a matrix to another matrix.</td></tr>
<tr><td>static [`Matrix Subtract(Matrix matrix1, Matrix matrix2)`](VRageMath.Subtract)</td><td>Subtracts matrices.</td></tr>
</table>
