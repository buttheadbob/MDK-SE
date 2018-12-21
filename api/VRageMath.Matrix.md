← [Index](index)
# Matrix Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a matrix.
### Fields
|Member|Description|
|---|---|
|[`float M11`](VRageMath.M11)|Value at row 1 column 1 of the matrix.|
|[`float M12`](VRageMath.M12)|Value at row 1 column 2 of the matrix.|
|[`float M13`](VRageMath.M13)|Value at row 1 column 3 of the matrix.|
|[`float M14`](VRageMath.M14)|Value at row 1 column 4 of the matrix.|
|[`float M21`](VRageMath.M21)|Value at row 2 column 1 of the matrix.|
|[`float M22`](VRageMath.M22)|Value at row 2 column 2 of the matrix.|
|[`float M23`](VRageMath.M23)|Value at row 2 column 3 of the matrix.|
|[`float M24`](VRageMath.M24)|Value at row 2 column 4 of the matrix.|
|[`float M31`](VRageMath.M31)|Value at row 3 column 1 of the matrix.|
|[`float M32`](VRageMath.M32)|Value at row 3 column 2 of the matrix.|
|[`float M33`](VRageMath.M33)|Value at row 3 column 3 of the matrix.|
|[`float M34`](VRageMath.M34)|Value at row 3 column 4 of the matrix.|
|[`float M41`](VRageMath.M41)|Value at row 4 column 1 of the matrix.|
|[`float M42`](VRageMath.M42)|Value at row 4 column 2 of the matrix.|
|[`float M43`](VRageMath.M43)|Value at row 4 column 3 of the matrix.|
|[`float M44`](VRageMath.M44)|Value at row 4 column 4 of the matrix.|
|static [`Matrix Identity`](VRageMath.Identity)||
|static [`Matrix Zero`](VRageMath.Zero)||
### Properties
|Member|Description|
|---|---|
|[`Vector3 Up`](VRageMath.Up)|Gets and sets the up vector of the Matrix.|
|[`Vector3 Down`](VRageMath.Down)|Gets and sets the down vector of the Matrix.|
|[`Vector3 Right`](VRageMath.Right)|Gets and sets the right vector of the Matrix.|
|[`Vector3 Col0`](VRageMath.Col0)||
|[`Vector3 Col1`](VRageMath.Col1)||
|[`Vector3 Col2`](VRageMath.Col2)||
|[`Vector3 Left`](VRageMath.Left)|Gets and sets the left vector of the Matrix.|
|[`Vector3 Forward`](VRageMath.Forward)|Gets and sets the forward vector of the Matrix.|
|[`Vector3 Backward`](VRageMath.Backward)|Gets and sets the backward vector of the Matrix.|
|[`Vector3 Scale`](VRageMath.Scale)||
|[`Vector3 Translation`](VRageMath.Translation)|Gets and sets the translation vector of the Matrix.|
|[`float Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|static [`void Subtract(ref Matrix matrix1, ref Matrix matrix2, ref Matrix result)`](VRageMath.Subtract)|Subtracts matrices.|
|static [`Matrix Multiply(Matrix matrix1, Matrix matrix2)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static [`void Multiply(ref Matrix matrix1, ref Matrix matrix2, ref Matrix result)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static [`void MultiplyRotation(ref Matrix matrix1, ref Matrix matrix2, ref Matrix result)`](VRageMath.MultiplyRotation)|Multiplies a matrix by another matrix, only rotation parts.|
|static [`Matrix Multiply(Matrix matrix1, float scaleFactor)`](VRageMath.Multiply)|Multiplies a matrix by a scalar value.|
|static [`void Multiply(ref Matrix matrix1, float scaleFactor, ref Matrix result)`](VRageMath.Multiply)|Multiplies a matrix by a scalar value.|
|static [`Matrix Divide(Matrix matrix1, Matrix matrix2)`](VRageMath.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|static [`void Divide(ref Matrix matrix1, ref Matrix matrix2, ref Matrix result)`](VRageMath.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|static [`Matrix Divide(Matrix matrix1, float divider)`](VRageMath.Divide)|Divides the components of a matrix by a scalar.|
|static [`void Divide(ref Matrix matrix1, float divider, ref Matrix result)`](VRageMath.Divide)|Divides the components of a matrix by a scalar.|
|[`Matrix GetOrientation()`](VRageMath.GetOrientation)|Gets the orientation.|
|[`void AssertIsValid()`](VRageMath.AssertIsValid)||
|[`bool IsValid()`](VRageMath.IsValid)||
|[`bool IsNan()`](VRageMath.IsNan)||
|[`bool IsRotation()`](VRageMath.IsRotation)||
|[`bool HasNoTranslationOrPerspective()`](VRageMath.HasNoTranslationOrPerspective)|Returns true if this matrix represents invertible (you can call Invert on it) linear (it does not contain translation or perspective transformation) transformation. Such matrix consist solely of rotations, shearing, mirroring and scaling. It can be orthogonalized to create an orthogonal rotation matrix.|
|static [`Matrix CreateFromDir(Vector3 dir)`](VRageMath.CreateFromDir)||
|static [`Matrix CreateFromDir(Vector3 dir, Vector3 suggestedUp)`](VRageMath.CreateFromDir)||
|static [`Matrix Normalize(Matrix matrix)`](VRageMath.Normalize)||
|static [`Matrix Orthogonalize(Matrix rotationMatrix)`](VRageMath.Orthogonalize)||
|static [`Matrix Round(ref Matrix matrix)`](VRageMath.Round)||
|static [`Matrix AlignRotationToAxes(ref Matrix toAlign, ref Matrix axisDefinitionMatrix)`](VRageMath.AlignRotationToAxes)||
|static [`bool GetEulerAnglesXYZ(ref Matrix mat, ref Vector3 xyz)`](VRageMath.GetEulerAnglesXYZ)||
|static [`Matrix SwapYZCoordinates(Matrix m)`](VRageMath.SwapYZCoordinates)||
|[`bool IsMirrored()`](VRageMath.IsMirrored)||
|[`bool IsOrthogonal()`](VRageMath.IsOrthogonal)||
|[`Vector3 GetDirectionVector(Direction direction)`](VRageMath.GetDirectionVector)||
|[`void SetDirectionVector(Direction direction, Vector3 newValue)`](VRageMath.SetDirectionVector)||
|[`Direction GetClosestDirection(Vector3 referenceVector)`](VRageMath.GetClosestDirection)||
|[`Direction GetClosestDirection(ref Vector3 referenceVector)`](VRageMath.GetClosestDirection)||
|static [`void Rescale(ref Matrix matrix, float scale)`](VRageMath.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|static [`void Rescale(ref Matrix matrix, ref Vector3 scale)`](VRageMath.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|static [`Matrix Rescale(Matrix matrix, float scale)`](VRageMath.Rescale)||
|static [`Matrix Rescale(Matrix matrix, Vector3 scale)`](VRageMath.Rescale)||
|static [`Matrix CreateBillboard(Vector3 objectPosition, Vector3 cameraPosition, Vector3 cameraUpVector, Nullable<Vector3> cameraForwardVector)`](VRageMath.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|static [`void CreateBillboard(ref Vector3 objectPosition, ref Vector3 cameraPosition, ref Vector3 cameraUpVector, Nullable<Vector3> cameraForwardVector, ref Matrix result)`](VRageMath.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|static [`Matrix CreateConstrainedBillboard(Vector3 objectPosition, Vector3 cameraPosition, Vector3 rotateAxis, Nullable<Vector3> cameraForwardVector, Nullable<Vector3> objectForwardVector)`](VRageMath.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|static [`void CreateConstrainedBillboard(ref Vector3 objectPosition, ref Vector3 cameraPosition, ref Vector3 rotateAxis, Nullable<Vector3> cameraForwardVector, Nullable<Vector3> objectForwardVector, ref Matrix result)`](VRageMath.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|static [`Matrix CreateTranslation(Vector3 position)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static [`void CreateTranslation(ref Vector3 position, ref Matrix result)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static [`Matrix CreateTranslation(float xPosition, float yPosition, float zPosition)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static [`void CreateTranslation(float xPosition, float yPosition, float zPosition, ref Matrix result)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static [`Matrix CreateScale(float xScale, float yScale, float zScale)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`void CreateScale(float xScale, float yScale, float zScale, ref Matrix result)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`Matrix CreateScale(Vector3 scales)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`void CreateScale(ref Vector3 scales, ref Matrix result)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`Matrix CreateScale(float scale)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`void CreateScale(float scale, ref Matrix result)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`Matrix CreateRotationX(float radians)`](VRageMath.CreateRotationX)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|static [`void CreateRotationX(float radians, ref Matrix result)`](VRageMath.CreateRotationX)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the x-axis.|
|static [`Matrix CreateRotationY(float radians)`](VRageMath.CreateRotationY)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|static [`void CreateRotationY(float radians, ref Matrix result)`](VRageMath.CreateRotationY)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the y-axis.|
|static [`Matrix CreateRotationZ(float radians)`](VRageMath.CreateRotationZ)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|static [`void CreateRotationZ(float radians, ref Matrix result)`](VRageMath.CreateRotationZ)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the z-axis.|
|static [`Matrix CreateFromAxisAngle(Vector3 axis, float angle)`](VRageMath.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|static [`void CreateFromAxisAngle(ref Vector3 axis, float angle, ref Matrix result)`](VRageMath.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|static [`void CreateRotationFromTwoVectors(ref Vector3 fromVector, ref Vector3 toVector, ref Matrix resultMatrix)`](VRageMath.CreateRotationFromTwoVectors)||
|static [`Matrix CreatePerspectiveFieldOfView(float fieldOfView, float aspectRatio, float nearPlaneDistance, float farPlaneDistance)`](VRageMath.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by value.|
|static [`Matrix CreatePerspectiveFovRhComplementary(float fieldOfView, float aspectRatio, float nearPlaneDistance, float farPlaneDistance)`](VRageMath.CreatePerspectiveFovRhComplementary)||
|static [`Matrix CreatePerspectiveFovRhInfinite(float fieldOfView, float aspectRatio, float nearPlaneDistance)`](VRageMath.CreatePerspectiveFovRhInfinite)||
|static [`Matrix CreatePerspectiveFovRhInfiniteComplementary(float fieldOfView, float aspectRatio, float nearPlaneDistance)`](VRageMath.CreatePerspectiveFovRhInfiniteComplementary)||
|static [`Matrix CreatePerspectiveFovRhInverse(float fieldOfView, float aspectRatio, float nearPlaneDistance, float farPlaneDistance)`](VRageMath.CreatePerspectiveFovRhInverse)||
|static [`Matrix CreatePerspectiveFovRhInfiniteInverse(float fieldOfView, float aspectRatio, float nearPlaneDistance)`](VRageMath.CreatePerspectiveFovRhInfiniteInverse)||
|static [`Matrix CreatePerspectiveFovRhInfiniteComplementaryInverse(float fieldOfView, float aspectRatio, float nearPlaneDistance)`](VRageMath.CreatePerspectiveFovRhInfiniteComplementaryInverse)||
|static [`Matrix CreateFromPerspectiveFieldOfView(ref Matrix proj, float nearPlaneDistance, float farPlaneDistance)`](VRageMath.CreateFromPerspectiveFieldOfView)||
|static [`void CreatePerspectiveFieldOfView(float fieldOfView, float aspectRatio, float nearPlaneDistance, float farPlaneDistance, ref Matrix result)`](VRageMath.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by reference.|
|static [`Matrix CreatePerspective(float width, float height, float nearPlaneDistance, float farPlaneDistance)`](VRageMath.CreatePerspective)|Builds a perspective projection matrix and returns the result by value.|
|static [`void CreatePerspective(float width, float height, float nearPlaneDistance, float farPlaneDistance, ref Matrix result)`](VRageMath.CreatePerspective)|Builds a perspective projection matrix and returns the result by reference.|
|static [`Matrix CreatePerspectiveOffCenter(float left, float right, float bottom, float top, float nearPlaneDistance, float farPlaneDistance)`](VRageMath.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|static [`void CreatePerspectiveOffCenter(float left, float right, float bottom, float top, float nearPlaneDistance, float farPlaneDistance, ref Matrix result)`](VRageMath.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|static [`Matrix CreateOrthographic(float width, float height, float zNearPlane, float zFarPlane)`](VRageMath.CreateOrthographic)|Builds an orthogonal projection matrix.|
|static [`void CreateOrthographic(float width, float height, float zNearPlane, float zFarPlane, ref Matrix result)`](VRageMath.CreateOrthographic)|Builds an orthogonal projection matrix.|
|static [`Matrix CreateOrthographicOffCenter(float left, float right, float bottom, float top, float zNearPlane, float zFarPlane)`](VRageMath.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|static [`void CreateOrthographicOffCenter(float left, float right, float bottom, float top, float zNearPlane, float zFarPlane, ref Matrix result)`](VRageMath.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|static [`Matrix CreateLookAt(Vector3 cameraPosition, Vector3 cameraTarget, Vector3 cameraUpVector)`](VRageMath.CreateLookAt)|Creates a view matrix.|
|static [`Matrix CreateLookAtInverse(Vector3 cameraPosition, Vector3 cameraTarget, Vector3 cameraUpVector)`](VRageMath.CreateLookAtInverse)||
|static [`void CreateLookAt(ref Vector3 cameraPosition, ref Vector3 cameraTarget, ref Vector3 cameraUpVector, ref Matrix result)`](VRageMath.CreateLookAt)|Creates a view matrix.|
|static [`Matrix CreateWorld(Vector3 position)`](VRageMath.CreateWorld)||
|static [`Matrix CreateWorld(Vector3 position, Vector3 forward, Vector3 up)`](VRageMath.CreateWorld)|Creates a world matrix with the specified parameters.|
|static [`void CreateWorld(ref Vector3 position, ref Vector3 forward, ref Vector3 up, ref Matrix result)`](VRageMath.CreateWorld)|Creates a world matrix with the specified parameters.|
|static [`Matrix CreateFromQuaternion(Quaternion quaternion)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|static [`void CreateFromQuaternion(ref Quaternion quaternion, ref Matrix result)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|static [`Matrix CreateFromYawPitchRoll(float yaw, float pitch, float roll)`](VRageMath.CreateFromYawPitchRoll)|Creates a new rotation matrix from a specified yaw, pitch, and roll.|
|static [`void CreateFromYawPitchRoll(float yaw, float pitch, float roll, ref Matrix result)`](VRageMath.CreateFromYawPitchRoll)|Fills in a rotation matrix from a specified yaw, pitch, and roll.|
|static [`Matrix CreateFromTransformScale(Quaternion orientation, Vector3 position, Vector3 scale)`](VRageMath.CreateFromTransformScale)||
|static [`Matrix CreateShadow(Vector3 lightDirection, Plane plane)`](VRageMath.CreateShadow)|Creates a Matrix that flattens geometry into a specified Plane as if casting a shadow from a specified light source.|
|static [`void CreateShadow(ref Vector3 lightDirection, ref Plane plane, ref Matrix result)`](VRageMath.CreateShadow)|Fills in a Matrix to flatten geometry into a specified Plane as if casting a shadow from a specified light source.|
|static [`Matrix CreateReflection(Plane value)`](VRageMath.CreateReflection)|Creates a Matrix that reflects the coordinate system about a specified Plane.|
|static [`void CreateReflection(ref Plane value, ref Matrix result)`](VRageMath.CreateReflection)|Fills in an existing Matrix so that it reflects the coordinate system about a specified Plane.|
|static [`Matrix Transform(Matrix value, Quaternion rotation)`](VRageMath.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|static [`void Transform(ref Matrix value, ref Quaternion rotation, ref Matrix result)`](VRageMath.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|[`Vector4 GetRow(int row)`](VRageMath.GetRow)||
|[`void SetRow(int row, Vector4 value)`](VRageMath.SetRow)||
|[`string ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`bool Equals(Matrix other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Matrix.|
|[`bool EqualsFast(ref Matrix other, float epsilon)`](VRageMath.EqualsFast)|Compares just position, forward and up|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of this object.|
|static [`Matrix Transpose(Matrix matrix)`](VRageMath.Transpose)|Transposes the rows and columns of a matrix.|
|static [`void Transpose(ref Matrix matrix, ref Matrix result)`](VRageMath.Transpose)|Transposes the rows and columns of a matrix.|
|[`void TransposeRotationInPlace()`](VRageMath.TransposeRotationInPlace)|Transposes the rows and columns of a matrix that is assumed to be rotation only in place.|
|[`float Determinant()`](VRageMath.Determinant)|Calculates the determinant of the matrix.|
|static [`Matrix Invert(Matrix matrix)`](VRageMath.Invert)|Calculates the inverse of a matrix.|
|static [`Matrix Invert(ref Matrix matrix)`](VRageMath.Invert)||
|static [`void Invert(ref Matrix matrix, ref Matrix result)`](VRageMath.Invert)|Calculates the inverse of a matrix.|
|static [`Matrix Lerp(Matrix matrix1, Matrix matrix2, float amount)`](VRageMath.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|static [`void Lerp(ref Matrix matrix1, ref Matrix matrix2, float amount, ref Matrix result)`](VRageMath.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|static [`void Slerp(ref Matrix matrix1, ref Matrix matrix2, float amount, ref Matrix result)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|static [`void SlerpScale(ref Matrix matrix1, ref Matrix matrix2, float amount, ref Matrix result)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static [`void Slerp(Matrix matrix1, Matrix matrix2, float amount, ref Matrix result)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|static [`Matrix Slerp(Matrix matrix1, Matrix matrix2, float amount)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|static [`void SlerpScale(Matrix matrix1, Matrix matrix2, float amount, ref Matrix result)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static [`Matrix SlerpScale(Matrix matrix1, Matrix matrix2, float amount)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static [`Matrix Negate(Matrix matrix)`](VRageMath.Negate)|Negates individual elements of a matrix.|
|static [`void Negate(ref Matrix matrix, ref Matrix result)`](VRageMath.Negate)|Negates individual elements of a matrix.|
|static [`Matrix Add(Matrix matrix1, Matrix matrix2)`](VRageMath.Add)|Adds a matrix to another matrix.|
|static [`void Add(ref Matrix matrix1, ref Matrix matrix2, ref Matrix result)`](VRageMath.Add)|Adds a matrix to another matrix.|
|static [`Matrix Subtract(Matrix matrix1, Matrix matrix2)`](VRageMath.Subtract)|Subtracts matrices.|
