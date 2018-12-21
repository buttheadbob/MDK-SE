← [Index](index)
# MatrixD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a matrix.
### Fields
|Member|Description|
|---|---|
|[`double M11`](VRageMath.M11)|Value at row 1 column 1 of the matrix.|
|[`double M12`](VRageMath.M12)|Value at row 1 column 2 of the matrix.|
|[`double M13`](VRageMath.M13)|Value at row 1 column 3 of the matrix.|
|[`double M14`](VRageMath.M14)|Value at row 1 column 4 of the matrix.|
|[`double M21`](VRageMath.M21)|Value at row 2 column 1 of the matrix.|
|[`double M22`](VRageMath.M22)|Value at row 2 column 2 of the matrix.|
|[`double M23`](VRageMath.M23)|Value at row 2 column 3 of the matrix.|
|[`double M24`](VRageMath.M24)|Value at row 2 column 4 of the matrix.|
|[`double M31`](VRageMath.M31)|Value at row 3 column 1 of the matrix.|
|[`double M32`](VRageMath.M32)|Value at row 3 column 2 of the matrix.|
|[`double M33`](VRageMath.M33)|Value at row 3 column 3 of the matrix.|
|[`double M34`](VRageMath.M34)|Value at row 3 column 4 of the matrix.|
|[`double M41`](VRageMath.M41)|Value at row 4 column 1 of the matrix.|
|[`double M42`](VRageMath.M42)|Value at row 4 column 2 of the matrix.|
|[`double M43`](VRageMath.M43)|Value at row 4 column 3 of the matrix.|
|[`double M44`](VRageMath.M44)|Value at row 4 column 4 of the matrix.|
|static [`MatrixD Identity`](VRageMath.Identity)||
|static [`MatrixD Zero`](VRageMath.Zero)||
### Properties
|Member|Description|
|---|---|
|[`Vector3D Col0`](VRageMath.Col0)||
|[`Vector3D Col1`](VRageMath.Col1)||
|[`Vector3D Col2`](VRageMath.Col2)||
|[`Vector3D Up`](VRageMath.Up)|Gets and sets the up vector of the Matrix.|
|[`Vector3D Down`](VRageMath.Down)|Gets and sets the down vector of the Matrix.|
|[`Vector3D Right`](VRageMath.Right)|Gets and sets the right vector of the Matrix.|
|[`Vector3D Left`](VRageMath.Left)|Gets and sets the left vector of the Matrix.|
|[`Vector3D Forward`](VRageMath.Forward)|Gets and sets the forward vector of the Matrix.|
|[`Vector3D Backward`](VRageMath.Backward)|Gets and sets the backward vector of the Matrix.|
|[`Vector3D Scale`](VRageMath.Scale)||
|[`Vector3D Translation`](VRageMath.Translation)|Gets and sets the translation vector of the Matrix.|
|[`Matrix3x3 Rotation`](VRageMath.Rotation)||
|[`double Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|static [`Matrix Subtract(Matrix matrix1, Matrix matrix2)`](VRageMath.Subtract)|Subtracts matrices.|
|static [`void Subtract(ref MatrixD matrix1, ref MatrixD matrix2, ref MatrixD result)`](VRageMath.Subtract)|Subtracts matrices.|
|static [`MatrixD Multiply(MatrixD matrix1, MatrixD matrix2)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static [`MatrixD Multiply(MatrixD matrix1, Matrix matrix2)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static [`void Multiply(ref MatrixD matrix1, ref Matrix matrix2, ref MatrixD result)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static [`void Multiply(ref Matrix matrix1, ref MatrixD matrix2, ref MatrixD result)`](VRageMath.Multiply)||
|static [`void Multiply(ref MatrixD matrix1, ref MatrixD matrix2, ref MatrixD result)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static [`MatrixD Multiply(MatrixD matrix1, double scaleFactor)`](VRageMath.Multiply)|Multiplies a matrix by a scalar value.|
|static [`void Multiply(ref MatrixD matrix1, double scaleFactor, ref MatrixD result)`](VRageMath.Multiply)|Multiplies a matrix by a scalar value.|
|static [`MatrixD Divide(MatrixD matrix1, MatrixD matrix2)`](VRageMath.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|static [`void Divide(ref MatrixD matrix1, ref MatrixD matrix2, ref MatrixD result)`](VRageMath.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|static [`MatrixD Divide(MatrixD matrix1, double divider)`](VRageMath.Divide)|Divides the components of a matrix by a scalar.|
|static [`void Divide(ref MatrixD matrix1, double divider, ref MatrixD result)`](VRageMath.Divide)|Divides the components of a matrix by a scalar.|
|[`MatrixD GetOrientation()`](VRageMath.GetOrientation)|Gets the orientation.|
|[`void AssertIsValid()`](VRageMath.AssertIsValid)||
|[`bool IsValid()`](VRageMath.IsValid)||
|[`bool IsNan()`](VRageMath.IsNan)||
|[`bool IsRotation()`](VRageMath.IsRotation)||
|[`bool HasNoTranslationOrPerspective()`](VRageMath.HasNoTranslationOrPerspective)|Returns true if this matrix represents invertible (you can call Invert on it) linear (it does not contain translation or perspective transformation) transformation. Such matrix consist solely of rotations, shearing, mirroring and scaling. It can be orthogonalized to create an orthogonal rotation matrix.|
|static [`MatrixD CreateFromDir(Vector3D dir)`](VRageMath.CreateFromDir)||
|static [`MatrixD CreateFromDir(Vector3D dir, Vector3D suggestedUp)`](VRageMath.CreateFromDir)||
|static [`MatrixD Normalize(MatrixD matrix)`](VRageMath.Normalize)||
|[`void Orthogonalize()`](VRageMath.Orthogonalize)||
|static [`MatrixD Orthogonalize(MatrixD rotationMatrix)`](VRageMath.Orthogonalize)||
|static [`MatrixD AlignRotationToAxes(ref MatrixD toAlign, ref MatrixD axisDefinitionMatrix)`](VRageMath.AlignRotationToAxes)||
|static [`bool GetEulerAnglesXYZ(ref MatrixD mat, ref Vector3D xyz)`](VRageMath.GetEulerAnglesXYZ)||
|static [`MatrixD SwapYZCoordinates(MatrixD m)`](VRageMath.SwapYZCoordinates)||
|[`bool IsMirrored()`](VRageMath.IsMirrored)||
|[`Vector3D GetDirectionVector(Direction direction)`](VRageMath.GetDirectionVector)||
|[`void SetDirectionVector(Direction direction, Vector3D newValue)`](VRageMath.SetDirectionVector)||
|[`Direction GetClosestDirection(Vector3D referenceVector)`](VRageMath.GetClosestDirection)||
|[`Direction GetClosestDirection(ref Vector3D referenceVector)`](VRageMath.GetClosestDirection)||
|static [`void Rescale(ref MatrixD matrix, double scale)`](VRageMath.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|static [`void Rescale(ref MatrixD matrix, float scale)`](VRageMath.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|static [`void Rescale(ref MatrixD matrix, ref Vector3D scale)`](VRageMath.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|static [`MatrixD Rescale(MatrixD matrix, double scale)`](VRageMath.Rescale)||
|static [`MatrixD Rescale(MatrixD matrix, Vector3D scale)`](VRageMath.Rescale)||
|static [`MatrixD CreateBillboard(Vector3D objectPosition, Vector3D cameraPosition, Vector3D cameraUpVector, Nullable<Vector3D> cameraForwardVector)`](VRageMath.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|static [`void CreateBillboard(ref Vector3D objectPosition, ref Vector3D cameraPosition, ref Vector3D cameraUpVector, Nullable<Vector3D> cameraForwardVector, ref MatrixD result)`](VRageMath.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|static [`MatrixD CreateConstrainedBillboard(Vector3D objectPosition, Vector3D cameraPosition, Vector3D rotateAxis, Nullable<Vector3D> cameraForwardVector, Nullable<Vector3D> objectForwardVector)`](VRageMath.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|static [`void CreateConstrainedBillboard(ref Vector3D objectPosition, ref Vector3D cameraPosition, ref Vector3D rotateAxis, Nullable<Vector3D> cameraForwardVector, Nullable<Vector3D> objectForwardVector, ref MatrixD result)`](VRageMath.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|static [`MatrixD CreateTranslation(Vector3D position)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static [`MatrixD CreateTranslation(Vector3 position)`](VRageMath.CreateTranslation)||
|static [`void CreateTranslation(ref Vector3D position, ref MatrixD result)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static [`MatrixD CreateTranslation(double xPosition, double yPosition, double zPosition)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static [`void CreateTranslation(double xPosition, double yPosition, double zPosition, ref MatrixD result)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static [`MatrixD CreateScale(double xScale, double yScale, double zScale)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`void CreateScale(double xScale, double yScale, double zScale, ref MatrixD result)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`MatrixD CreateScale(Vector3D scales)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`void CreateScale(ref Vector3D scales, ref MatrixD result)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`MatrixD CreateScale(double scale)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`void CreateScale(double scale, ref MatrixD result)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`MatrixD CreateRotationX(double radians)`](VRageMath.CreateRotationX)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|static [`void CreateRotationX(double radians, ref MatrixD result)`](VRageMath.CreateRotationX)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the x-axis.|
|static [`MatrixD CreateRotationY(double radians)`](VRageMath.CreateRotationY)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|static [`void CreateRotationY(double radians, ref MatrixD result)`](VRageMath.CreateRotationY)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the y-axis.|
|static [`MatrixD CreateRotationZ(double radians)`](VRageMath.CreateRotationZ)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|static [`void CreateRotationZ(double radians, ref MatrixD result)`](VRageMath.CreateRotationZ)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the z-axis.|
|static [`MatrixD CreateFromAxisAngle(Vector3D axis, double angle)`](VRageMath.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|static [`void CreateFromAxisAngle(ref Vector3D axis, double angle, ref MatrixD result)`](VRageMath.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|static [`MatrixD CreatePerspectiveFieldOfView(double fieldOfView, double aspectRatio, double nearPlaneDistance, double farPlaneDistance)`](VRageMath.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by value.|
|static [`void CreatePerspectiveFieldOfView(double fieldOfView, double aspectRatio, double nearPlaneDistance, double farPlaneDistance, ref MatrixD result)`](VRageMath.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by reference.|
|static [`MatrixD CreatePerspective(double width, double height, double nearPlaneDistance, double farPlaneDistance)`](VRageMath.CreatePerspective)|Builds a perspective projection matrix and returns the result by value.|
|static [`void CreatePerspective(double width, double height, double nearPlaneDistance, double farPlaneDistance, ref MatrixD result)`](VRageMath.CreatePerspective)|Builds a perspective projection matrix and returns the result by reference.|
|static [`MatrixD CreatePerspectiveOffCenter(double left, double right, double bottom, double top, double nearPlaneDistance, double farPlaneDistance)`](VRageMath.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|static [`void CreatePerspectiveOffCenter(double left, double right, double bottom, double top, double nearPlaneDistance, double farPlaneDistance, ref MatrixD result)`](VRageMath.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|static [`MatrixD CreateOrthographic(double width, double height, double zNearPlane, double zFarPlane)`](VRageMath.CreateOrthographic)|Builds an orthogonal projection matrix.|
|static [`void CreateOrthographic(double width, double height, double zNearPlane, double zFarPlane, ref MatrixD result)`](VRageMath.CreateOrthographic)|Builds an orthogonal projection matrix.|
|static [`MatrixD CreateOrthographicOffCenter(double left, double right, double bottom, double top, double zNearPlane, double zFarPlane)`](VRageMath.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|static [`void CreateOrthographicOffCenter(double left, double right, double bottom, double top, double zNearPlane, double zFarPlane, ref MatrixD result)`](VRageMath.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|static [`MatrixD CreateLookAt(Vector3D cameraPosition, Vector3D cameraTarget, Vector3 cameraUpVector)`](VRageMath.CreateLookAt)||
|static [`MatrixD CreateLookAt(Vector3D cameraPosition, Vector3D cameraTarget, Vector3D cameraUpVector)`](VRageMath.CreateLookAt)|Creates a view matrix.|
|static [`Matrix CreateLookAtInverse(Vector3D cameraPosition, Vector3D cameraTarget, Vector3D cameraUpVector)`](VRageMath.CreateLookAtInverse)||
|static [`void CreateLookAt(ref Vector3D cameraPosition, ref Vector3D cameraTarget, ref Vector3D cameraUpVector, ref MatrixD result)`](VRageMath.CreateLookAt)|Creates a view matrix.|
|static [`MatrixD CreateWorld(Vector3D position, Vector3 forward, Vector3 up)`](VRageMath.CreateWorld)||
|static [`MatrixD CreateWorld(Vector3D position)`](VRageMath.CreateWorld)||
|static [`MatrixD CreateWorld(Vector3D position, Vector3D forward, Vector3D up)`](VRageMath.CreateWorld)|Creates a world matrix with the specified parameters.|
|static [`void CreateWorld(ref Vector3D position, ref Vector3D forward, ref Vector3D up, ref MatrixD result)`](VRageMath.CreateWorld)|Creates a world matrix with the specified parameters.|
|static [`MatrixD CreateFromQuaternion(Quaternion quaternion)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|static [`MatrixD CreateFromQuaternion(QuaternionD quaternion)`](VRageMath.CreateFromQuaternion)||
|static [`void CreateFromQuaternion(ref Quaternion quaternion, ref MatrixD result)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|static [`MatrixD CreateFromYawPitchRoll(double yaw, double pitch, double roll)`](VRageMath.CreateFromYawPitchRoll)|Creates a new rotation matrix from a specified yaw, pitch, and roll.|
|static [`void CreateFromYawPitchRoll(double yaw, double pitch, double roll, ref MatrixD result)`](VRageMath.CreateFromYawPitchRoll)|Fills in a rotation matrix from a specified yaw, pitch, and roll.|
|static [`MatrixD CreateFromTransformScale(Quaternion orientation, Vector3D position, Vector3D scale)`](VRageMath.CreateFromTransformScale)||
|static [`MatrixD CreateShadow(Vector3D lightDirection, Plane plane)`](VRageMath.CreateShadow)|Creates a Matrix that flattens geometry into a specified Plane as if casting a shadow from a specified light source.|
|static [`void CreateShadow(ref Vector3D lightDirection, ref Plane plane, ref MatrixD result)`](VRageMath.CreateShadow)|Fills in a Matrix to flatten geometry into a specified Plane as if casting a shadow from a specified light source.|
|static [`MatrixD CreateReflection(Plane value)`](VRageMath.CreateReflection)|Creates a Matrix that reflects the coordinate system about a specified Plane.|
|static [`void CreateReflection(ref Plane value, ref MatrixD result)`](VRageMath.CreateReflection)|Fills in an existing Matrix so that it reflects the coordinate system about a specified Plane.|
|static [`MatrixD Transform(MatrixD value, Quaternion rotation)`](VRageMath.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|static [`void Transform(ref MatrixD value, ref Quaternion rotation, ref MatrixD result)`](VRageMath.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|[`Vector4 GetRow(int row)`](VRageMath.GetRow)||
|[`void SetRow(int row, Vector4 value)`](VRageMath.SetRow)||
|[`string ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`bool Equals(MatrixD other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Matrix.|
|[`bool EqualsFast(ref MatrixD other, double epsilon)`](VRageMath.EqualsFast)|Compares just position, forward and up|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of this object.|
|static [`MatrixD Transpose(MatrixD matrix)`](VRageMath.Transpose)|Transposes the rows and columns of a matrix.|
|static [`void Transpose(ref MatrixD matrix, ref MatrixD result)`](VRageMath.Transpose)|Transposes the rows and columns of a matrix.|
|[`double Determinant()`](VRageMath.Determinant)|Calculates the determinant of the matrix.|
|static [`MatrixD Invert(MatrixD matrix)`](VRageMath.Invert)|Calculates the inverse of a matrix.|
|static [`MatrixD Invert(ref MatrixD matrix)`](VRageMath.Invert)||
|static [`void Invert(ref MatrixD matrix, ref MatrixD result)`](VRageMath.Invert)|Calculates the inverse of a matrix.|
|static [`MatrixD Lerp(MatrixD matrix1, MatrixD matrix2, double amount)`](VRageMath.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|static [`void Lerp(ref MatrixD matrix1, ref MatrixD matrix2, double amount, ref MatrixD result)`](VRageMath.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|static [`void Slerp(ref MatrixD matrix1, ref MatrixD matrix2, float amount, ref MatrixD result)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|[`bool IsOrthogonal()`](VRageMath.IsOrthogonal)||
|[`bool IsOrthogonal(double epsilon)`](VRageMath.IsOrthogonal)||
|static [`void SlerpScale(ref MatrixD matrix1, ref MatrixD matrix2, float amount, ref MatrixD result)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static [`void Slerp(MatrixD matrix1, MatrixD matrix2, float amount, ref MatrixD result)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|static [`MatrixD Slerp(MatrixD matrix1, MatrixD matrix2, float amount)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|static [`void SlerpScale(MatrixD matrix1, MatrixD matrix2, float amount, ref MatrixD result)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static [`MatrixD SlerpScale(MatrixD matrix1, MatrixD matrix2, float amount)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static [`MatrixD Negate(MatrixD matrix)`](VRageMath.Negate)|Negates individual elements of a matrix.|
|static [`void Negate(ref MatrixD matrix, ref MatrixD result)`](VRageMath.Negate)|Negates individual elements of a matrix.|
|static [`MatrixD Add(MatrixD matrix1, MatrixD matrix2)`](VRageMath.Add)|Adds a matrix to another matrix.|
|static [`void Add(ref MatrixD matrix1, ref MatrixD matrix2, ref MatrixD result)`](VRageMath.Add)|Adds a matrix to another matrix.|
