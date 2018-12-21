← [Index](index)
# MatrixD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a matrix.
### Fields
<table style="width: 100%">
<tr><td>[`double M11`](VRageMath.M11)</td><td>Value at row 1 column 1 of the matrix.</td></tr>
<tr><td>[`double M12`](VRageMath.M12)</td><td>Value at row 1 column 2 of the matrix.</td></tr>
<tr><td>[`double M13`](VRageMath.M13)</td><td>Value at row 1 column 3 of the matrix.</td></tr>
<tr><td>[`double M14`](VRageMath.M14)</td><td>Value at row 1 column 4 of the matrix.</td></tr>
<tr><td>[`double M21`](VRageMath.M21)</td><td>Value at row 2 column 1 of the matrix.</td></tr>
<tr><td>[`double M22`](VRageMath.M22)</td><td>Value at row 2 column 2 of the matrix.</td></tr>
<tr><td>[`double M23`](VRageMath.M23)</td><td>Value at row 2 column 3 of the matrix.</td></tr>
<tr><td>[`double M24`](VRageMath.M24)</td><td>Value at row 2 column 4 of the matrix.</td></tr>
<tr><td>[`double M31`](VRageMath.M31)</td><td>Value at row 3 column 1 of the matrix.</td></tr>
<tr><td>[`double M32`](VRageMath.M32)</td><td>Value at row 3 column 2 of the matrix.</td></tr>
<tr><td>[`double M33`](VRageMath.M33)</td><td>Value at row 3 column 3 of the matrix.</td></tr>
<tr><td>[`double M34`](VRageMath.M34)</td><td>Value at row 3 column 4 of the matrix.</td></tr>
<tr><td>[`double M41`](VRageMath.M41)</td><td>Value at row 4 column 1 of the matrix.</td></tr>
<tr><td>[`double M42`](VRageMath.M42)</td><td>Value at row 4 column 2 of the matrix.</td></tr>
<tr><td>[`double M43`](VRageMath.M43)</td><td>Value at row 4 column 3 of the matrix.</td></tr>
<tr><td>[`double M44`](VRageMath.M44)</td><td>Value at row 4 column 4 of the matrix.</td></tr>
<tr><td>static [`MatrixD Identity`](VRageMath.Identity)</td><td></td></tr>
<tr><td>static [`MatrixD Zero`](VRageMath.Zero)</td><td></td></tr>
</table>
### Properties
<table style="width: 100%">
<tr><td>[`Vector3D Col0`](VRageMath.Col0)</td><td></td></tr>
<tr><td>[`Vector3D Col1`](VRageMath.Col1)</td><td></td></tr>
<tr><td>[`Vector3D Col2`](VRageMath.Col2)</td><td></td></tr>
<tr><td>[`Vector3D Up`](VRageMath.Up)</td><td>Gets and sets the up vector of the Matrix.</td></tr>
<tr><td>[`Vector3D Down`](VRageMath.Down)</td><td>Gets and sets the down vector of the Matrix.</td></tr>
<tr><td>[`Vector3D Right`](VRageMath.Right)</td><td>Gets and sets the right vector of the Matrix.</td></tr>
<tr><td>[`Vector3D Left`](VRageMath.Left)</td><td>Gets and sets the left vector of the Matrix.</td></tr>
<tr><td>[`Vector3D Forward`](VRageMath.Forward)</td><td>Gets and sets the forward vector of the Matrix.</td></tr>
<tr><td>[`Vector3D Backward`](VRageMath.Backward)</td><td>Gets and sets the backward vector of the Matrix.</td></tr>
<tr><td>[`Vector3D Scale`](VRageMath.Scale)</td><td></td></tr>
<tr><td>[`Vector3D Translation`](VRageMath.Translation)</td><td>Gets and sets the translation vector of the Matrix.</td></tr>
<tr><td>[`Matrix3x3 Rotation`](VRageMath.Rotation)</td><td></td></tr>
<tr><td>[`double Item`](VRageMath.Item)</td><td></td></tr>
</table>
### Methods
<table style="width: 100%">
<tr><td>static [`Matrix Subtract(Matrix matrix1, Matrix matrix2)`](VRageMath.Subtract)</td><td>Subtracts matrices.</td></tr>
<tr><td>static [`void Subtract(ref MatrixD matrix1, ref MatrixD matrix2, ref MatrixD result)`](VRageMath.Subtract)</td><td>Subtracts matrices.</td></tr>
<tr><td>static [`MatrixD Multiply(MatrixD matrix1, MatrixD matrix2)`](VRageMath.Multiply)</td><td>Multiplies a matrix by another matrix.</td></tr>
<tr><td>static [`MatrixD Multiply(MatrixD matrix1, Matrix matrix2)`](VRageMath.Multiply)</td><td>Multiplies a matrix by another matrix.</td></tr>
<tr><td>static [`void Multiply(ref MatrixD matrix1, ref Matrix matrix2, ref MatrixD result)`](VRageMath.Multiply)</td><td>Multiplies a matrix by another matrix.</td></tr>
<tr><td>static [`void Multiply(ref Matrix matrix1, ref MatrixD matrix2, ref MatrixD result)`](VRageMath.Multiply)</td><td></td></tr>
<tr><td>static [`void Multiply(ref MatrixD matrix1, ref MatrixD matrix2, ref MatrixD result)`](VRageMath.Multiply)</td><td>Multiplies a matrix by another matrix.</td></tr>
<tr><td>static [`MatrixD Multiply(MatrixD matrix1, double scaleFactor)`](VRageMath.Multiply)</td><td>Multiplies a matrix by a scalar value.</td></tr>
<tr><td>static [`void Multiply(ref MatrixD matrix1, double scaleFactor, ref MatrixD result)`](VRageMath.Multiply)</td><td>Multiplies a matrix by a scalar value.</td></tr>
<tr><td>static [`MatrixD Divide(MatrixD matrix1, MatrixD matrix2)`](VRageMath.Divide)</td><td>Divides the components of a matrix by the corresponding components of another matrix.</td></tr>
<tr><td>static [`void Divide(ref MatrixD matrix1, ref MatrixD matrix2, ref MatrixD result)`](VRageMath.Divide)</td><td>Divides the components of a matrix by the corresponding components of another matrix.</td></tr>
<tr><td>static [`MatrixD Divide(MatrixD matrix1, double divider)`](VRageMath.Divide)</td><td>Divides the components of a matrix by a scalar.</td></tr>
<tr><td>static [`void Divide(ref MatrixD matrix1, double divider, ref MatrixD result)`](VRageMath.Divide)</td><td>Divides the components of a matrix by a scalar.</td></tr>
<tr><td>[`MatrixD GetOrientation()`](VRageMath.GetOrientation)</td><td>Gets the orientation.</td></tr>
<tr><td>[`void AssertIsValid()`](VRageMath.AssertIsValid)</td><td></td></tr>
<tr><td>[`bool IsValid()`](VRageMath.IsValid)</td><td></td></tr>
<tr><td>[`bool IsNan()`](VRageMath.IsNan)</td><td></td></tr>
<tr><td>[`bool IsRotation()`](VRageMath.IsRotation)</td><td></td></tr>
<tr><td>[`bool HasNoTranslationOrPerspective()`](VRageMath.HasNoTranslationOrPerspective)</td><td>Returns true if this matrix represents invertible (you can call Invert on it) linear (it does not contain translation or perspective transformation) transformation. Such matrix consist solely of rotations, shearing, mirroring and scaling. It can be orthogonalized to create an orthogonal rotation matrix.</td></tr>
<tr><td>static [`MatrixD CreateFromDir(Vector3D dir)`](VRageMath.CreateFromDir)</td><td></td></tr>
<tr><td>static [`MatrixD CreateFromDir(Vector3D dir, Vector3D suggestedUp)`](VRageMath.CreateFromDir)</td><td></td></tr>
<tr><td>static [`MatrixD Normalize(MatrixD matrix)`](VRageMath.Normalize)</td><td></td></tr>
<tr><td>[`void Orthogonalize()`](VRageMath.Orthogonalize)</td><td></td></tr>
<tr><td>static [`MatrixD Orthogonalize(MatrixD rotationMatrix)`](VRageMath.Orthogonalize)</td><td></td></tr>
<tr><td>static [`MatrixD AlignRotationToAxes(ref MatrixD toAlign, ref MatrixD axisDefinitionMatrix)`](VRageMath.AlignRotationToAxes)</td><td></td></tr>
<tr><td>static [`bool GetEulerAnglesXYZ(ref MatrixD mat, ref Vector3D xyz)`](VRageMath.GetEulerAnglesXYZ)</td><td></td></tr>
<tr><td>static [`MatrixD SwapYZCoordinates(MatrixD m)`](VRageMath.SwapYZCoordinates)</td><td></td></tr>
<tr><td>[`bool IsMirrored()`](VRageMath.IsMirrored)</td><td></td></tr>
<tr><td>[`Vector3D GetDirectionVector(Direction direction)`](VRageMath.GetDirectionVector)</td><td></td></tr>
<tr><td>[`void SetDirectionVector(Direction direction, Vector3D newValue)`](VRageMath.SetDirectionVector)</td><td></td></tr>
<tr><td>[`Direction GetClosestDirection(Vector3D referenceVector)`](VRageMath.GetClosestDirection)</td><td></td></tr>
<tr><td>[`Direction GetClosestDirection(ref Vector3D referenceVector)`](VRageMath.GetClosestDirection)</td><td></td></tr>
<tr><td>static [`void Rescale(ref MatrixD matrix, double scale)`](VRageMath.Rescale)</td><td>Same result as Matrix.CreateScale(scale) * matrix, but much faster</td></tr>
<tr><td>static [`void Rescale(ref MatrixD matrix, float scale)`](VRageMath.Rescale)</td><td>Same result as Matrix.CreateScale(scale) * matrix, but much faster</td></tr>
<tr><td>static [`void Rescale(ref MatrixD matrix, ref Vector3D scale)`](VRageMath.Rescale)</td><td>Same result as Matrix.CreateScale(scale) * matrix, but much faster</td></tr>
<tr><td>static [`MatrixD Rescale(MatrixD matrix, double scale)`](VRageMath.Rescale)</td><td></td></tr>
<tr><td>static [`MatrixD Rescale(MatrixD matrix, Vector3D scale)`](VRageMath.Rescale)</td><td></td></tr>
<tr><td>static [`MatrixD CreateBillboard(Vector3D objectPosition, Vector3D cameraPosition, Vector3D cameraUpVector, Nullable<Vector3D> cameraForwardVector)`](VRageMath.CreateBillboard)</td><td>Creates a spherical billboard that rotates around a specified object position.</td></tr>
<tr><td>static [`void CreateBillboard(ref Vector3D objectPosition, ref Vector3D cameraPosition, ref Vector3D cameraUpVector, Nullable<Vector3D> cameraForwardVector, ref MatrixD result)`](VRageMath.CreateBillboard)</td><td>Creates a spherical billboard that rotates around a specified object position.</td></tr>
<tr><td>static [`MatrixD CreateConstrainedBillboard(Vector3D objectPosition, Vector3D cameraPosition, Vector3D rotateAxis, Nullable<Vector3D> cameraForwardVector, Nullable<Vector3D> objectForwardVector)`](VRageMath.CreateConstrainedBillboard)</td><td>Creates a cylindrical billboard that rotates around a specified axis.</td></tr>
<tr><td>static [`void CreateConstrainedBillboard(ref Vector3D objectPosition, ref Vector3D cameraPosition, ref Vector3D rotateAxis, Nullable<Vector3D> cameraForwardVector, Nullable<Vector3D> objectForwardVector, ref MatrixD result)`](VRageMath.CreateConstrainedBillboard)</td><td>Creates a cylindrical billboard that rotates around a specified axis.</td></tr>
<tr><td>static [`MatrixD CreateTranslation(Vector3D position)`](VRageMath.CreateTranslation)</td><td>Creates a translation Matrix.</td></tr>
<tr><td>static [`MatrixD CreateTranslation(Vector3 position)`](VRageMath.CreateTranslation)</td><td></td></tr>
<tr><td>static [`void CreateTranslation(ref Vector3D position, ref MatrixD result)`](VRageMath.CreateTranslation)</td><td>Creates a translation Matrix.</td></tr>
<tr><td>static [`MatrixD CreateTranslation(double xPosition, double yPosition, double zPosition)`](VRageMath.CreateTranslation)</td><td>Creates a translation Matrix.</td></tr>
<tr><td>static [`void CreateTranslation(double xPosition, double yPosition, double zPosition, ref MatrixD result)`](VRageMath.CreateTranslation)</td><td>Creates a translation Matrix.</td></tr>
<tr><td>static [`MatrixD CreateScale(double xScale, double yScale, double zScale)`](VRageMath.CreateScale)</td><td>Creates a scaling Matrix.</td></tr>
<tr><td>static [`void CreateScale(double xScale, double yScale, double zScale, ref MatrixD result)`](VRageMath.CreateScale)</td><td>Creates a scaling Matrix.</td></tr>
<tr><td>static [`MatrixD CreateScale(Vector3D scales)`](VRageMath.CreateScale)</td><td>Creates a scaling Matrix.</td></tr>
<tr><td>static [`void CreateScale(ref Vector3D scales, ref MatrixD result)`](VRageMath.CreateScale)</td><td>Creates a scaling Matrix.</td></tr>
<tr><td>static [`MatrixD CreateScale(double scale)`](VRageMath.CreateScale)</td><td>Creates a scaling Matrix.</td></tr>
<tr><td>static [`void CreateScale(double scale, ref MatrixD result)`](VRageMath.CreateScale)</td><td>Creates a scaling Matrix.</td></tr>
<tr><td>static [`MatrixD CreateRotationX(double radians)`](VRageMath.CreateRotationX)</td><td>Returns a matrix that can be used to rotate a set of vertices around the x-axis.</td></tr>
<tr><td>static [`void CreateRotationX(double radians, ref MatrixD result)`](VRageMath.CreateRotationX)</td><td>Populates data into a user-specified matrix that can be used to rotate a set of vertices around the x-axis.</td></tr>
<tr><td>static [`MatrixD CreateRotationY(double radians)`](VRageMath.CreateRotationY)</td><td>Returns a matrix that can be used to rotate a set of vertices around the y-axis.</td></tr>
<tr><td>static [`void CreateRotationY(double radians, ref MatrixD result)`](VRageMath.CreateRotationY)</td><td>Populates data into a user-specified matrix that can be used to rotate a set of vertices around the y-axis.</td></tr>
<tr><td>static [`MatrixD CreateRotationZ(double radians)`](VRageMath.CreateRotationZ)</td><td>Returns a matrix that can be used to rotate a set of vertices around the z-axis.</td></tr>
<tr><td>static [`void CreateRotationZ(double radians, ref MatrixD result)`](VRageMath.CreateRotationZ)</td><td>Populates data into a user-specified matrix that can be used to rotate a set of vertices around the z-axis.</td></tr>
<tr><td>static [`MatrixD CreateFromAxisAngle(Vector3D axis, double angle)`](VRageMath.CreateFromAxisAngle)</td><td>Creates a new Matrix that rotates around an arbitrary vector.</td></tr>
<tr><td>static [`void CreateFromAxisAngle(ref Vector3D axis, double angle, ref MatrixD result)`](VRageMath.CreateFromAxisAngle)</td><td>Creates a new Matrix that rotates around an arbitrary vector.</td></tr>
<tr><td>static [`MatrixD CreatePerspectiveFieldOfView(double fieldOfView, double aspectRatio, double nearPlaneDistance, double farPlaneDistance)`](VRageMath.CreatePerspectiveFieldOfView)</td><td>Builds a perspective projection matrix based on a field of view and returns by value.</td></tr>
<tr><td>static [`void CreatePerspectiveFieldOfView(double fieldOfView, double aspectRatio, double nearPlaneDistance, double farPlaneDistance, ref MatrixD result)`](VRageMath.CreatePerspectiveFieldOfView)</td><td>Builds a perspective projection matrix based on a field of view and returns by reference.</td></tr>
<tr><td>static [`MatrixD CreatePerspective(double width, double height, double nearPlaneDistance, double farPlaneDistance)`](VRageMath.CreatePerspective)</td><td>Builds a perspective projection matrix and returns the result by value.</td></tr>
<tr><td>static [`void CreatePerspective(double width, double height, double nearPlaneDistance, double farPlaneDistance, ref MatrixD result)`](VRageMath.CreatePerspective)</td><td>Builds a perspective projection matrix and returns the result by reference.</td></tr>
<tr><td>static [`MatrixD CreatePerspectiveOffCenter(double left, double right, double bottom, double top, double nearPlaneDistance, double farPlaneDistance)`](VRageMath.CreatePerspectiveOffCenter)</td><td>Builds a customized, perspective projection matrix.</td></tr>
<tr><td>static [`void CreatePerspectiveOffCenter(double left, double right, double bottom, double top, double nearPlaneDistance, double farPlaneDistance, ref MatrixD result)`](VRageMath.CreatePerspectiveOffCenter)</td><td>Builds a customized, perspective projection matrix.</td></tr>
<tr><td>static [`MatrixD CreateOrthographic(double width, double height, double zNearPlane, double zFarPlane)`](VRageMath.CreateOrthographic)</td><td>Builds an orthogonal projection matrix.</td></tr>
<tr><td>static [`void CreateOrthographic(double width, double height, double zNearPlane, double zFarPlane, ref MatrixD result)`](VRageMath.CreateOrthographic)</td><td>Builds an orthogonal projection matrix.</td></tr>
<tr><td>static [`MatrixD CreateOrthographicOffCenter(double left, double right, double bottom, double top, double zNearPlane, double zFarPlane)`](VRageMath.CreateOrthographicOffCenter)</td><td>Builds a customized, orthogonal projection matrix.</td></tr>
<tr><td>static [`void CreateOrthographicOffCenter(double left, double right, double bottom, double top, double zNearPlane, double zFarPlane, ref MatrixD result)`](VRageMath.CreateOrthographicOffCenter)</td><td>Builds a customized, orthogonal projection matrix.</td></tr>
<tr><td>static [`MatrixD CreateLookAt(Vector3D cameraPosition, Vector3D cameraTarget, Vector3 cameraUpVector)`](VRageMath.CreateLookAt)</td><td></td></tr>
<tr><td>static [`MatrixD CreateLookAt(Vector3D cameraPosition, Vector3D cameraTarget, Vector3D cameraUpVector)`](VRageMath.CreateLookAt)</td><td>Creates a view matrix.</td></tr>
<tr><td>static [`Matrix CreateLookAtInverse(Vector3D cameraPosition, Vector3D cameraTarget, Vector3D cameraUpVector)`](VRageMath.CreateLookAtInverse)</td><td></td></tr>
<tr><td>static [`void CreateLookAt(ref Vector3D cameraPosition, ref Vector3D cameraTarget, ref Vector3D cameraUpVector, ref MatrixD result)`](VRageMath.CreateLookAt)</td><td>Creates a view matrix.</td></tr>
<tr><td>static [`MatrixD CreateWorld(Vector3D position, Vector3 forward, Vector3 up)`](VRageMath.CreateWorld)</td><td></td></tr>
<tr><td>static [`MatrixD CreateWorld(Vector3D position)`](VRageMath.CreateWorld)</td><td></td></tr>
<tr><td>static [`MatrixD CreateWorld(Vector3D position, Vector3D forward, Vector3D up)`](VRageMath.CreateWorld)</td><td>Creates a world matrix with the specified parameters.</td></tr>
<tr><td>static [`void CreateWorld(ref Vector3D position, ref Vector3D forward, ref Vector3D up, ref MatrixD result)`](VRageMath.CreateWorld)</td><td>Creates a world matrix with the specified parameters.</td></tr>
<tr><td>static [`MatrixD CreateFromQuaternion(Quaternion quaternion)`](VRageMath.CreateFromQuaternion)</td><td>Creates a rotation Matrix from a Quaternion.</td></tr>
<tr><td>static [`MatrixD CreateFromQuaternion(QuaternionD quaternion)`](VRageMath.CreateFromQuaternion)</td><td></td></tr>
<tr><td>static [`void CreateFromQuaternion(ref Quaternion quaternion, ref MatrixD result)`](VRageMath.CreateFromQuaternion)</td><td>Creates a rotation Matrix from a Quaternion.</td></tr>
<tr><td>static [`MatrixD CreateFromYawPitchRoll(double yaw, double pitch, double roll)`](VRageMath.CreateFromYawPitchRoll)</td><td>Creates a new rotation matrix from a specified yaw, pitch, and roll.</td></tr>
<tr><td>static [`void CreateFromYawPitchRoll(double yaw, double pitch, double roll, ref MatrixD result)`](VRageMath.CreateFromYawPitchRoll)</td><td>Fills in a rotation matrix from a specified yaw, pitch, and roll.</td></tr>
<tr><td>static [`MatrixD CreateFromTransformScale(Quaternion orientation, Vector3D position, Vector3D scale)`](VRageMath.CreateFromTransformScale)</td><td></td></tr>
<tr><td>static [`MatrixD CreateShadow(Vector3D lightDirection, Plane plane)`](VRageMath.CreateShadow)</td><td>Creates a Matrix that flattens geometry into a specified Plane as if casting a shadow from a specified light source.</td></tr>
<tr><td>static [`void CreateShadow(ref Vector3D lightDirection, ref Plane plane, ref MatrixD result)`](VRageMath.CreateShadow)</td><td>Fills in a Matrix to flatten geometry into a specified Plane as if casting a shadow from a specified light source.</td></tr>
<tr><td>static [`MatrixD CreateReflection(Plane value)`](VRageMath.CreateReflection)</td><td>Creates a Matrix that reflects the coordinate system about a specified Plane.</td></tr>
<tr><td>static [`void CreateReflection(ref Plane value, ref MatrixD result)`](VRageMath.CreateReflection)</td><td>Fills in an existing Matrix so that it reflects the coordinate system about a specified Plane.</td></tr>
<tr><td>static [`MatrixD Transform(MatrixD value, Quaternion rotation)`](VRageMath.Transform)</td><td>Transforms a Matrix by applying a Quaternion rotation.</td></tr>
<tr><td>static [`void Transform(ref MatrixD value, ref Quaternion rotation, ref MatrixD result)`](VRageMath.Transform)</td><td>Transforms a Matrix by applying a Quaternion rotation.</td></tr>
<tr><td>[`Vector4 GetRow(int row)`](VRageMath.GetRow)</td><td></td></tr>
<tr><td>[`void SetRow(int row, Vector4 value)`](VRageMath.SetRow)</td><td></td></tr>
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td>Retrieves a string representation of the current object.</td></tr>
<tr><td>[`bool Equals(MatrixD other)`](VRageMath.Equals)</td><td>Determines whether the specified Object is equal to the Matrix.</td></tr>
<tr><td>[`bool EqualsFast(ref MatrixD other, double epsilon)`](VRageMath.EqualsFast)</td><td>Compares just position, forward and up</td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td>Returns a value that indicates whether the current instance is equal to a specified object.</td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td>Gets the hash code of this object.</td></tr>
<tr><td>static [`MatrixD Transpose(MatrixD matrix)`](VRageMath.Transpose)</td><td>Transposes the rows and columns of a matrix.</td></tr>
<tr><td>static [`void Transpose(ref MatrixD matrix, ref MatrixD result)`](VRageMath.Transpose)</td><td>Transposes the rows and columns of a matrix.</td></tr>
<tr><td>[`double Determinant()`](VRageMath.Determinant)</td><td>Calculates the determinant of the matrix.</td></tr>
<tr><td>static [`MatrixD Invert(MatrixD matrix)`](VRageMath.Invert)</td><td>Calculates the inverse of a matrix.</td></tr>
<tr><td>static [`MatrixD Invert(ref MatrixD matrix)`](VRageMath.Invert)</td><td></td></tr>
<tr><td>static [`void Invert(ref MatrixD matrix, ref MatrixD result)`](VRageMath.Invert)</td><td>Calculates the inverse of a matrix.</td></tr>
<tr><td>static [`MatrixD Lerp(MatrixD matrix1, MatrixD matrix2, double amount)`](VRageMath.Lerp)</td><td>Linearly interpolates between the corresponding values of two matrices.</td></tr>
<tr><td>static [`void Lerp(ref MatrixD matrix1, ref MatrixD matrix2, double amount, ref MatrixD result)`](VRageMath.Lerp)</td><td>Linearly interpolates between the corresponding values of two matrices.</td></tr>
<tr><td>static [`void Slerp(ref MatrixD matrix1, ref MatrixD matrix2, float amount, ref MatrixD result)`](VRageMath.Slerp)</td><td>Performs spherical linear interpolation of position and rotation.</td></tr>
<tr><td>[`bool IsOrthogonal()`](VRageMath.IsOrthogonal)</td><td></td></tr>
<tr><td>[`bool IsOrthogonal(double epsilon)`](VRageMath.IsOrthogonal)</td><td></td></tr>
<tr><td>static [`void SlerpScale(ref MatrixD matrix1, ref MatrixD matrix2, float amount, ref MatrixD result)`](VRageMath.SlerpScale)</td><td>Performs spherical linear interpolation of position and rotation and scale.</td></tr>
<tr><td>static [`void Slerp(MatrixD matrix1, MatrixD matrix2, float amount, ref MatrixD result)`](VRageMath.Slerp)</td><td>Performs spherical linear interpolation of position and rotation.</td></tr>
<tr><td>static [`MatrixD Slerp(MatrixD matrix1, MatrixD matrix2, float amount)`](VRageMath.Slerp)</td><td>Performs spherical linear interpolation of position and rotation.</td></tr>
<tr><td>static [`void SlerpScale(MatrixD matrix1, MatrixD matrix2, float amount, ref MatrixD result)`](VRageMath.SlerpScale)</td><td>Performs spherical linear interpolation of position and rotation and scale.</td></tr>
<tr><td>static [`MatrixD SlerpScale(MatrixD matrix1, MatrixD matrix2, float amount)`](VRageMath.SlerpScale)</td><td>Performs spherical linear interpolation of position and rotation and scale.</td></tr>
<tr><td>static [`MatrixD Negate(MatrixD matrix)`](VRageMath.Negate)</td><td>Negates individual elements of a matrix.</td></tr>
<tr><td>static [`void Negate(ref MatrixD matrix, ref MatrixD result)`](VRageMath.Negate)</td><td>Negates individual elements of a matrix.</td></tr>
<tr><td>static [`MatrixD Add(MatrixD matrix1, MatrixD matrix2)`](VRageMath.Add)</td><td>Adds a matrix to another matrix.</td></tr>
<tr><td>static [`void Add(ref MatrixD matrix1, ref MatrixD matrix2, ref MatrixD result)`](VRageMath.Add)</td><td>Adds a matrix to another matrix.</td></tr>
</table>
