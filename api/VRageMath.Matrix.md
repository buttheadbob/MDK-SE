← [Index](index)
# Matrix Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a matrix.
### Fields
|Member|Description|
|---|---|
|[`float M11`](VRageMath.M11)||
|[`float M12`](VRageMath.M12)||
|[`float M13`](VRageMath.M13)||
|[`float M14`](VRageMath.M14)||
|[`float M21`](VRageMath.M21)||
|[`float M22`](VRageMath.M22)||
|[`float M23`](VRageMath.M23)||
|[`float M24`](VRageMath.M24)||
|[`float M31`](VRageMath.M31)||
|[`float M32`](VRageMath.M32)||
|[`float M33`](VRageMath.M33)||
|[`float M34`](VRageMath.M34)||
|[`float M41`](VRageMath.M41)||
|[`float M42`](VRageMath.M42)||
|[`float M43`](VRageMath.M43)||
|[`float M44`](VRageMath.M44)||
|[`Matrix Identity`](VRageMath.Identity)||
|[`Matrix Zero`](VRageMath.Zero)||
### Properties
|Member|Description|
|---|---|
|[`Vector3 Up`](VRageMath.Up)||
|[`Vector3 Down`](VRageMath.Down)||
|[`Vector3 Right`](VRageMath.Right)||
|[`Vector3 Col0`](VRageMath.Col0)||
|[`Vector3 Col1`](VRageMath.Col1)||
|[`Vector3 Col2`](VRageMath.Col2)||
|[`Vector3 Left`](VRageMath.Left)||
|[`Vector3 Forward`](VRageMath.Forward)||
|[`Vector3 Backward`](VRageMath.Backward)||
|[`Vector3 Scale`](VRageMath.Scale)||
|[`Vector3 Translation`](VRageMath.Translation)||
|[`float Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|[`void Subtract(ref Matrix matrix1, ref Matrix matrix2, ref Matrix result)`](VRageMath.Subtract)||
|[`Matrix Multiply(Matrix matrix1, Matrix matrix2)`](VRageMath.Multiply)||
|[`void Multiply(ref Matrix matrix1, ref Matrix matrix2, ref Matrix result)`](VRageMath.Multiply)||
|[`void MultiplyRotation(ref Matrix matrix1, ref Matrix matrix2, ref Matrix result)`](VRageMath.MultiplyRotation)||
|[`Matrix Multiply(Matrix matrix1, float scaleFactor)`](VRageMath.Multiply)||
|[`void Multiply(ref Matrix matrix1, float scaleFactor, ref Matrix result)`](VRageMath.Multiply)||
|[`Matrix Divide(Matrix matrix1, Matrix matrix2)`](VRageMath.Divide)||
|[`void Divide(ref Matrix matrix1, ref Matrix matrix2, ref Matrix result)`](VRageMath.Divide)||
|[`Matrix Divide(Matrix matrix1, float divider)`](VRageMath.Divide)||
|[`void Divide(ref Matrix matrix1, float divider, ref Matrix result)`](VRageMath.Divide)||
|[`Matrix GetOrientation()`](VRageMath.GetOrientation)||
|[`void AssertIsValid()`](VRageMath.AssertIsValid)||
|[`bool IsValid()`](VRageMath.IsValid)||
|[`bool IsNan()`](VRageMath.IsNan)||
|[`bool IsRotation()`](VRageMath.IsRotation)||
|[`bool HasNoTranslationOrPerspective()`](VRageMath.HasNoTranslationOrPerspective)||
|[`Matrix CreateFromDir(Vector3 dir)`](VRageMath.CreateFromDir)||
|[`Matrix CreateFromDir(Vector3 dir, Vector3 suggestedUp)`](VRageMath.CreateFromDir)||
|[`Matrix Normalize(Matrix matrix)`](VRageMath.Normalize)||
|[`Matrix Orthogonalize(Matrix rotationMatrix)`](VRageMath.Orthogonalize)||
|[`Matrix Round(ref Matrix matrix)`](VRageMath.Round)||
|[`Matrix AlignRotationToAxes(ref Matrix toAlign, ref Matrix axisDefinitionMatrix)`](VRageMath.AlignRotationToAxes)||
|[`bool GetEulerAnglesXYZ(ref Matrix mat, ref Vector3 xyz)`](VRageMath.GetEulerAnglesXYZ)||
|[`Matrix SwapYZCoordinates(Matrix m)`](VRageMath.SwapYZCoordinates)||
|[`bool IsMirrored()`](VRageMath.IsMirrored)||
|[`bool IsOrthogonal()`](VRageMath.IsOrthogonal)||
|[`Vector3 GetDirectionVector(Direction direction)`](VRageMath.GetDirectionVector)||
|[`void SetDirectionVector(Direction direction, Vector3 newValue)`](VRageMath.SetDirectionVector)||
|[`Direction GetClosestDirection(Vector3 referenceVector)`](VRageMath.GetClosestDirection)||
|[`Direction GetClosestDirection(ref Vector3 referenceVector)`](VRageMath.GetClosestDirection)||
|[`void Rescale(ref Matrix matrix, float scale)`](VRageMath.Rescale)||
|[`void Rescale(ref Matrix matrix, ref Vector3 scale)`](VRageMath.Rescale)||
|[`Matrix Rescale(Matrix matrix, float scale)`](VRageMath.Rescale)||
|[`Matrix Rescale(Matrix matrix, Vector3 scale)`](VRageMath.Rescale)||
|[`Matrix CreateBillboard(Vector3 objectPosition, Vector3 cameraPosition, Vector3 cameraUpVector, Nullable<Vector3> cameraForwardVector)`](VRageMath.CreateBillboard)||
|[`void CreateBillboard(ref Vector3 objectPosition, ref Vector3 cameraPosition, ref Vector3 cameraUpVector, Nullable<Vector3> cameraForwardVector, ref Matrix result)`](VRageMath.CreateBillboard)||
|[`Matrix CreateConstrainedBillboard(Vector3 objectPosition, Vector3 cameraPosition, Vector3 rotateAxis, Nullable<Vector3> cameraForwardVector, Nullable<Vector3> objectForwardVector)`](VRageMath.CreateConstrainedBillboard)||
|[`void CreateConstrainedBillboard(ref Vector3 objectPosition, ref Vector3 cameraPosition, ref Vector3 rotateAxis, Nullable<Vector3> cameraForwardVector, Nullable<Vector3> objectForwardVector, ref Matrix result)`](VRageMath.CreateConstrainedBillboard)||
|[`Matrix CreateTranslation(Vector3 position)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|[`void CreateTranslation(ref Vector3 position, ref Matrix result)`](VRageMath.CreateTranslation)||
|[`Matrix CreateTranslation(float xPosition, float yPosition, float zPosition)`](VRageMath.CreateTranslation)||
|[`void CreateTranslation(float xPosition, float yPosition, float zPosition, ref Matrix result)`](VRageMath.CreateTranslation)||
|[`Matrix CreateScale(float xScale, float yScale, float zScale)`](VRageMath.CreateScale)||
|[`void CreateScale(float xScale, float yScale, float zScale, ref Matrix result)`](VRageMath.CreateScale)||
|[`Matrix CreateScale(Vector3 scales)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|[`void CreateScale(ref Vector3 scales, ref Matrix result)`](VRageMath.CreateScale)||
|[`Matrix CreateScale(float scale)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|[`void CreateScale(float scale, ref Matrix result)`](VRageMath.CreateScale)||
|[`Matrix CreateRotationX(float radians)`](VRageMath.CreateRotationX)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|[`void CreateRotationX(float radians, ref Matrix result)`](VRageMath.CreateRotationX)||
|[`Matrix CreateRotationY(float radians)`](VRageMath.CreateRotationY)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|[`void CreateRotationY(float radians, ref Matrix result)`](VRageMath.CreateRotationY)||
|[`Matrix CreateRotationZ(float radians)`](VRageMath.CreateRotationZ)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|[`void CreateRotationZ(float radians, ref Matrix result)`](VRageMath.CreateRotationZ)||
|[`Matrix CreateFromAxisAngle(Vector3 axis, float angle)`](VRageMath.CreateFromAxisAngle)||
|[`void CreateFromAxisAngle(ref Vector3 axis, float angle, ref Matrix result)`](VRageMath.CreateFromAxisAngle)||
|[`void CreateRotationFromTwoVectors(ref Vector3 fromVector, ref Vector3 toVector, ref Matrix resultMatrix)`](VRageMath.CreateRotationFromTwoVectors)||
|[`Matrix CreatePerspectiveFieldOfView(float fieldOfView, float aspectRatio, float nearPlaneDistance, float farPlaneDistance)`](VRageMath.CreatePerspectiveFieldOfView)||
|[`Matrix CreatePerspectiveFovRhComplementary(float fieldOfView, float aspectRatio, float nearPlaneDistance, float farPlaneDistance)`](VRageMath.CreatePerspectiveFovRhComplementary)||
|[`Matrix CreatePerspectiveFovRhInfinite(float fieldOfView, float aspectRatio, float nearPlaneDistance)`](VRageMath.CreatePerspectiveFovRhInfinite)||
|[`Matrix CreatePerspectiveFovRhInfiniteComplementary(float fieldOfView, float aspectRatio, float nearPlaneDistance)`](VRageMath.CreatePerspectiveFovRhInfiniteComplementary)||
|[`Matrix CreatePerspectiveFovRhInverse(float fieldOfView, float aspectRatio, float nearPlaneDistance, float farPlaneDistance)`](VRageMath.CreatePerspectiveFovRhInverse)||
|[`Matrix CreatePerspectiveFovRhInfiniteInverse(float fieldOfView, float aspectRatio, float nearPlaneDistance)`](VRageMath.CreatePerspectiveFovRhInfiniteInverse)||
|[`Matrix CreatePerspectiveFovRhInfiniteComplementaryInverse(float fieldOfView, float aspectRatio, float nearPlaneDistance)`](VRageMath.CreatePerspectiveFovRhInfiniteComplementaryInverse)||
|[`Matrix CreateFromPerspectiveFieldOfView(ref Matrix proj, float nearPlaneDistance, float farPlaneDistance)`](VRageMath.CreateFromPerspectiveFieldOfView)||
|[`void CreatePerspectiveFieldOfView(float fieldOfView, float aspectRatio, float nearPlaneDistance, float farPlaneDistance, ref Matrix result)`](VRageMath.CreatePerspectiveFieldOfView)||
|[`Matrix CreatePerspective(float width, float height, float nearPlaneDistance, float farPlaneDistance)`](VRageMath.CreatePerspective)||
|[`void CreatePerspective(float width, float height, float nearPlaneDistance, float farPlaneDistance, ref Matrix result)`](VRageMath.CreatePerspective)||
|[`Matrix CreatePerspectiveOffCenter(float left, float right, float bottom, float top, float nearPlaneDistance, float farPlaneDistance)`](VRageMath.CreatePerspectiveOffCenter)||
|[`void CreatePerspectiveOffCenter(float left, float right, float bottom, float top, float nearPlaneDistance, float farPlaneDistance, ref Matrix result)`](VRageMath.CreatePerspectiveOffCenter)||
|[`Matrix CreateOrthographic(float width, float height, float zNearPlane, float zFarPlane)`](VRageMath.CreateOrthographic)||
|[`void CreateOrthographic(float width, float height, float zNearPlane, float zFarPlane, ref Matrix result)`](VRageMath.CreateOrthographic)||
|[`Matrix CreateOrthographicOffCenter(float left, float right, float bottom, float top, float zNearPlane, float zFarPlane)`](VRageMath.CreateOrthographicOffCenter)||
|[`void CreateOrthographicOffCenter(float left, float right, float bottom, float top, float zNearPlane, float zFarPlane, ref Matrix result)`](VRageMath.CreateOrthographicOffCenter)||
|[`Matrix CreateLookAt(Vector3 cameraPosition, Vector3 cameraTarget, Vector3 cameraUpVector)`](VRageMath.CreateLookAt)||
|[`Matrix CreateLookAtInverse(Vector3 cameraPosition, Vector3 cameraTarget, Vector3 cameraUpVector)`](VRageMath.CreateLookAtInverse)||
|[`void CreateLookAt(ref Vector3 cameraPosition, ref Vector3 cameraTarget, ref Vector3 cameraUpVector, ref Matrix result)`](VRageMath.CreateLookAt)||
|[`Matrix CreateWorld(Vector3 position)`](VRageMath.CreateWorld)||
|[`Matrix CreateWorld(Vector3 position, Vector3 forward, Vector3 up)`](VRageMath.CreateWorld)||
|[`void CreateWorld(ref Vector3 position, ref Vector3 forward, ref Vector3 up, ref Matrix result)`](VRageMath.CreateWorld)||
|[`Matrix CreateFromQuaternion(Quaternion quaternion)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|[`void CreateFromQuaternion(ref Quaternion quaternion, ref Matrix result)`](VRageMath.CreateFromQuaternion)||
|[`Matrix CreateFromYawPitchRoll(float yaw, float pitch, float roll)`](VRageMath.CreateFromYawPitchRoll)||
|[`void CreateFromYawPitchRoll(float yaw, float pitch, float roll, ref Matrix result)`](VRageMath.CreateFromYawPitchRoll)||
|[`Matrix CreateFromTransformScale(Quaternion orientation, Vector3 position, Vector3 scale)`](VRageMath.CreateFromTransformScale)||
|[`Matrix CreateShadow(Vector3 lightDirection, Plane plane)`](VRageMath.CreateShadow)||
|[`void CreateShadow(ref Vector3 lightDirection, ref Plane plane, ref Matrix result)`](VRageMath.CreateShadow)||
|[`Matrix CreateReflection(Plane value)`](VRageMath.CreateReflection)|Creates a Matrix that reflects the coordinate system about a specified Plane.|
|[`void CreateReflection(ref Plane value, ref Matrix result)`](VRageMath.CreateReflection)||
|[`Matrix Transform(Matrix value, Quaternion rotation)`](VRageMath.Transform)||
|[`void Transform(ref Matrix value, ref Quaternion rotation, ref Matrix result)`](VRageMath.Transform)||
|[`Vector4 GetRow(int row)`](VRageMath.GetRow)||
|[`void SetRow(int row, Vector4 value)`](VRageMath.SetRow)||
|[`string ToString()`](VRageMath.ToString)||
|[`bool Equals(Matrix other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Matrix.|
|[`bool EqualsFast(ref Matrix other, float epsilon)`](VRageMath.EqualsFast)||
|[`bool Equals(Object obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`Matrix Transpose(Matrix matrix)`](VRageMath.Transpose)|Transposes the rows and columns of a matrix.|
|[`void Transpose(ref Matrix matrix, ref Matrix result)`](VRageMath.Transpose)||
|[`void TransposeRotationInPlace()`](VRageMath.TransposeRotationInPlace)||
|[`float Determinant()`](VRageMath.Determinant)||
|[`Matrix Invert(Matrix matrix)`](VRageMath.Invert)|Calculates the inverse of a matrix.|
|[`Matrix Invert(ref Matrix matrix)`](VRageMath.Invert)||
|[`void Invert(ref Matrix matrix, ref Matrix result)`](VRageMath.Invert)||
|[`Matrix Lerp(Matrix matrix1, Matrix matrix2, float amount)`](VRageMath.Lerp)||
|[`void Lerp(ref Matrix matrix1, ref Matrix matrix2, float amount, ref Matrix result)`](VRageMath.Lerp)||
|[`void Slerp(ref Matrix matrix1, ref Matrix matrix2, float amount, ref Matrix result)`](VRageMath.Slerp)||
|[`void SlerpScale(ref Matrix matrix1, ref Matrix matrix2, float amount, ref Matrix result)`](VRageMath.SlerpScale)||
|[`void Slerp(Matrix matrix1, Matrix matrix2, float amount, ref Matrix result)`](VRageMath.Slerp)||
|[`Matrix Slerp(Matrix matrix1, Matrix matrix2, float amount)`](VRageMath.Slerp)||
|[`void SlerpScale(Matrix matrix1, Matrix matrix2, float amount, ref Matrix result)`](VRageMath.SlerpScale)||
|[`Matrix SlerpScale(Matrix matrix1, Matrix matrix2, float amount)`](VRageMath.SlerpScale)||
|[`Matrix Negate(Matrix matrix)`](VRageMath.Negate)|Negates individual elements of a matrix.|
|[`void Negate(ref Matrix matrix, ref Matrix result)`](VRageMath.Negate)||
|[`Matrix Add(Matrix matrix1, Matrix matrix2)`](VRageMath.Add)||
|[`void Add(ref Matrix matrix1, ref Matrix matrix2, ref Matrix result)`](VRageMath.Add)||
|[`Matrix Subtract(Matrix matrix1, Matrix matrix2)`](VRageMath.Subtract)||
