← [Index](index.md)
# Matrix Struct
** Namespace: ** VRageMath  
** Assembly: ** VRage.Math.dll  
## Summary
Defines a matrix.
### Fields
|Member|Description|
|---|---|
|[`float M11`](VRageMath.M11.md)||
|[`float M12`](VRageMath.M12.md)||
|[`float M13`](VRageMath.M13.md)||
|[`float M14`](VRageMath.M14.md)||
|[`float M21`](VRageMath.M21.md)||
|[`float M22`](VRageMath.M22.md)||
|[`float M23`](VRageMath.M23.md)||
|[`float M24`](VRageMath.M24.md)||
|[`float M31`](VRageMath.M31.md)||
|[`float M32`](VRageMath.M32.md)||
|[`float M33`](VRageMath.M33.md)||
|[`float M34`](VRageMath.M34.md)||
|[`float M41`](VRageMath.M41.md)||
|[`float M42`](VRageMath.M42.md)||
|[`float M43`](VRageMath.M43.md)||
|[`float M44`](VRageMath.M44.md)||
|[`Matrix Identity`](VRageMath.Identity.md)||
|[`Matrix Zero`](VRageMath.Zero.md)||
### Properties
|Member|Description|
|---|---|
|[`Vector3 Up`](VRageMath.Up.md)||
|[`Vector3 Down`](VRageMath.Down.md)||
|[`Vector3 Right`](VRageMath.Right.md)||
|[`Vector3 Col0`](VRageMath.Col0.md)||
|[`Vector3 Col1`](VRageMath.Col1.md)||
|[`Vector3 Col2`](VRageMath.Col2.md)||
|[`Vector3 Left`](VRageMath.Left.md)||
|[`Vector3 Forward`](VRageMath.Forward.md)||
|[`Vector3 Backward`](VRageMath.Backward.md)||
|[`Vector3 Scale`](VRageMath.Scale.md)||
|[`Vector3 Translation`](VRageMath.Translation.md)||
|[`float Item`](VRageMath.Item.md)||
### Methods
|Member|Description|
|---|---|
|[`void Subtract(ref Matrix matrix1, ref Matrix matrix2, ref Matrix result)`](VRageMath.Subtract.md)||
|[`Matrix Multiply(Matrix matrix1, Matrix matrix2)`](VRageMath.Multiply.md)||
|[`void Multiply(ref Matrix matrix1, ref Matrix matrix2, ref Matrix result)`](VRageMath.Multiply.md)||
|[`void MultiplyRotation(ref Matrix matrix1, ref Matrix matrix2, ref Matrix result)`](VRageMath.MultiplyRotation.md)||
|[`Matrix Multiply(Matrix matrix1, float scaleFactor)`](VRageMath.Multiply.md)||
|[`void Multiply(ref Matrix matrix1, float scaleFactor, ref Matrix result)`](VRageMath.Multiply.md)||
|[`Matrix Divide(Matrix matrix1, Matrix matrix2)`](VRageMath.Divide.md)||
|[`void Divide(ref Matrix matrix1, ref Matrix matrix2, ref Matrix result)`](VRageMath.Divide.md)||
|[`Matrix Divide(Matrix matrix1, float divider)`](VRageMath.Divide.md)||
|[`void Divide(ref Matrix matrix1, float divider, ref Matrix result)`](VRageMath.Divide.md)||
|[`Matrix GetOrientation()`](VRageMath.GetOrientation.md)||
|[`void AssertIsValid()`](VRageMath.AssertIsValid.md)||
|[`bool IsValid()`](VRageMath.IsValid.md)||
|[`bool IsNan()`](VRageMath.IsNan.md)||
|[`bool IsRotation()`](VRageMath.IsRotation.md)||
|[`bool HasNoTranslationOrPerspective()`](VRageMath.HasNoTranslationOrPerspective.md)||
|[`Matrix CreateFromDir(Vector3 dir)`](VRageMath.CreateFromDir.md)||
|[`Matrix CreateFromDir(Vector3 dir, Vector3 suggestedUp)`](VRageMath.CreateFromDir.md)||
|[`Matrix Normalize(Matrix matrix)`](VRageMath.Normalize.md)||
|[`Matrix Orthogonalize(Matrix rotationMatrix)`](VRageMath.Orthogonalize.md)||
|[`Matrix Round(ref Matrix matrix)`](VRageMath.Round.md)||
|[`Matrix AlignRotationToAxes(ref Matrix toAlign, ref Matrix axisDefinitionMatrix)`](VRageMath.AlignRotationToAxes.md)||
|[`bool GetEulerAnglesXYZ(ref Matrix mat, ref Vector3 xyz)`](VRageMath.GetEulerAnglesXYZ.md)||
|[`Matrix SwapYZCoordinates(Matrix m)`](VRageMath.SwapYZCoordinates.md)||
|[`bool IsMirrored()`](VRageMath.IsMirrored.md)||
|[`bool IsOrthogonal()`](VRageMath.IsOrthogonal.md)||
|[`Vector3 GetDirectionVector(Direction direction)`](VRageMath.GetDirectionVector.md)||
|[`void SetDirectionVector(Direction direction, Vector3 newValue)`](VRageMath.SetDirectionVector.md)||
|[`Direction GetClosestDirection(Vector3 referenceVector)`](VRageMath.GetClosestDirection.md)||
|[`Direction GetClosestDirection(ref Vector3 referenceVector)`](VRageMath.GetClosestDirection.md)||
|[`void Rescale(ref Matrix matrix, float scale)`](VRageMath.Rescale.md)||
|[`void Rescale(ref Matrix matrix, ref Vector3 scale)`](VRageMath.Rescale.md)||
|[`Matrix Rescale(Matrix matrix, float scale)`](VRageMath.Rescale.md)||
|[`Matrix Rescale(Matrix matrix, Vector3 scale)`](VRageMath.Rescale.md)||
|[`Matrix CreateBillboard(Vector3 objectPosition, Vector3 cameraPosition, Vector3 cameraUpVector, Nullable<Vector3> cameraForwardVector)`](VRageMath.CreateBillboard.md)||
|[`void CreateBillboard(ref Vector3 objectPosition, ref Vector3 cameraPosition, ref Vector3 cameraUpVector, Nullable<Vector3> cameraForwardVector, ref Matrix result)`](VRageMath.CreateBillboard.md)||
|[`Matrix CreateConstrainedBillboard(Vector3 objectPosition, Vector3 cameraPosition, Vector3 rotateAxis, Nullable<Vector3> cameraForwardVector, Nullable<Vector3> objectForwardVector)`](VRageMath.CreateConstrainedBillboard.md)||
|[`void CreateConstrainedBillboard(ref Vector3 objectPosition, ref Vector3 cameraPosition, ref Vector3 rotateAxis, Nullable<Vector3> cameraForwardVector, Nullable<Vector3> objectForwardVector, ref Matrix result)`](VRageMath.CreateConstrainedBillboard.md)||
|[`Matrix CreateTranslation(Vector3 position)`](VRageMath.CreateTranslation.md)|Creates a translation Matrix.|
|[`void CreateTranslation(ref Vector3 position, ref Matrix result)`](VRageMath.CreateTranslation.md)||
|[`Matrix CreateTranslation(float xPosition, float yPosition, float zPosition)`](VRageMath.CreateTranslation.md)||
|[`void CreateTranslation(float xPosition, float yPosition, float zPosition, ref Matrix result)`](VRageMath.CreateTranslation.md)||
|[`Matrix CreateScale(float xScale, float yScale, float zScale)`](VRageMath.CreateScale.md)||
|[`void CreateScale(float xScale, float yScale, float zScale, ref Matrix result)`](VRageMath.CreateScale.md)||
|[`Matrix CreateScale(Vector3 scales)`](VRageMath.CreateScale.md)|Creates a scaling Matrix.|
|[`void CreateScale(ref Vector3 scales, ref Matrix result)`](VRageMath.CreateScale.md)||
|[`Matrix CreateScale(float scale)`](VRageMath.CreateScale.md)|Creates a scaling Matrix.|
|[`void CreateScale(float scale, ref Matrix result)`](VRageMath.CreateScale.md)||
|[`Matrix CreateRotationX(float radians)`](VRageMath.CreateRotationX.md)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|[`void CreateRotationX(float radians, ref Matrix result)`](VRageMath.CreateRotationX.md)||
|[`Matrix CreateRotationY(float radians)`](VRageMath.CreateRotationY.md)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|[`void CreateRotationY(float radians, ref Matrix result)`](VRageMath.CreateRotationY.md)||
|[`Matrix CreateRotationZ(float radians)`](VRageMath.CreateRotationZ.md)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|[`void CreateRotationZ(float radians, ref Matrix result)`](VRageMath.CreateRotationZ.md)||
|[`Matrix CreateFromAxisAngle(Vector3 axis, float angle)`](VRageMath.CreateFromAxisAngle.md)||
|[`void CreateFromAxisAngle(ref Vector3 axis, float angle, ref Matrix result)`](VRageMath.CreateFromAxisAngle.md)||
|[`void CreateRotationFromTwoVectors(ref Vector3 fromVector, ref Vector3 toVector, ref Matrix resultMatrix)`](VRageMath.CreateRotationFromTwoVectors.md)||
|[`Matrix CreatePerspectiveFieldOfView(float fieldOfView, float aspectRatio, float nearPlaneDistance, float farPlaneDistance)`](VRageMath.CreatePerspectiveFieldOfView.md)||
|[`Matrix CreatePerspectiveFovRhComplementary(float fieldOfView, float aspectRatio, float nearPlaneDistance, float farPlaneDistance)`](VRageMath.CreatePerspectiveFovRhComplementary.md)||
|[`Matrix CreatePerspectiveFovRhInfinite(float fieldOfView, float aspectRatio, float nearPlaneDistance)`](VRageMath.CreatePerspectiveFovRhInfinite.md)||
|[`Matrix CreatePerspectiveFovRhInfiniteComplementary(float fieldOfView, float aspectRatio, float nearPlaneDistance)`](VRageMath.CreatePerspectiveFovRhInfiniteComplementary.md)||
|[`Matrix CreatePerspectiveFovRhInverse(float fieldOfView, float aspectRatio, float nearPlaneDistance, float farPlaneDistance)`](VRageMath.CreatePerspectiveFovRhInverse.md)||
|[`Matrix CreatePerspectiveFovRhInfiniteInverse(float fieldOfView, float aspectRatio, float nearPlaneDistance)`](VRageMath.CreatePerspectiveFovRhInfiniteInverse.md)||
|[`Matrix CreatePerspectiveFovRhInfiniteComplementaryInverse(float fieldOfView, float aspectRatio, float nearPlaneDistance)`](VRageMath.CreatePerspectiveFovRhInfiniteComplementaryInverse.md)||
|[`Matrix CreateFromPerspectiveFieldOfView(ref Matrix proj, float nearPlaneDistance, float farPlaneDistance)`](VRageMath.CreateFromPerspectiveFieldOfView.md)||
|[`void CreatePerspectiveFieldOfView(float fieldOfView, float aspectRatio, float nearPlaneDistance, float farPlaneDistance, ref Matrix result)`](VRageMath.CreatePerspectiveFieldOfView.md)||
|[`Matrix CreatePerspective(float width, float height, float nearPlaneDistance, float farPlaneDistance)`](VRageMath.CreatePerspective.md)||
|[`void CreatePerspective(float width, float height, float nearPlaneDistance, float farPlaneDistance, ref Matrix result)`](VRageMath.CreatePerspective.md)||
|[`Matrix CreatePerspectiveOffCenter(float left, float right, float bottom, float top, float nearPlaneDistance, float farPlaneDistance)`](VRageMath.CreatePerspectiveOffCenter.md)||
|[`void CreatePerspectiveOffCenter(float left, float right, float bottom, float top, float nearPlaneDistance, float farPlaneDistance, ref Matrix result)`](VRageMath.CreatePerspectiveOffCenter.md)||
|[`Matrix CreateOrthographic(float width, float height, float zNearPlane, float zFarPlane)`](VRageMath.CreateOrthographic.md)||
|[`void CreateOrthographic(float width, float height, float zNearPlane, float zFarPlane, ref Matrix result)`](VRageMath.CreateOrthographic.md)||
|[`Matrix CreateOrthographicOffCenter(float left, float right, float bottom, float top, float zNearPlane, float zFarPlane)`](VRageMath.CreateOrthographicOffCenter.md)||
|[`void CreateOrthographicOffCenter(float left, float right, float bottom, float top, float zNearPlane, float zFarPlane, ref Matrix result)`](VRageMath.CreateOrthographicOffCenter.md)||
|[`Matrix CreateLookAt(Vector3 cameraPosition, Vector3 cameraTarget, Vector3 cameraUpVector)`](VRageMath.CreateLookAt.md)||
|[`Matrix CreateLookAtInverse(Vector3 cameraPosition, Vector3 cameraTarget, Vector3 cameraUpVector)`](VRageMath.CreateLookAtInverse.md)||
|[`void CreateLookAt(ref Vector3 cameraPosition, ref Vector3 cameraTarget, ref Vector3 cameraUpVector, ref Matrix result)`](VRageMath.CreateLookAt.md)||
|[`Matrix CreateWorld(Vector3 position)`](VRageMath.CreateWorld.md)||
|[`Matrix CreateWorld(Vector3 position, Vector3 forward, Vector3 up)`](VRageMath.CreateWorld.md)||
|[`void CreateWorld(ref Vector3 position, ref Vector3 forward, ref Vector3 up, ref Matrix result)`](VRageMath.CreateWorld.md)||
|[`Matrix CreateFromQuaternion(Quaternion quaternion)`](VRageMath.CreateFromQuaternion.md)|Creates a rotation Matrix from a Quaternion.|
|[`void CreateFromQuaternion(ref Quaternion quaternion, ref Matrix result)`](VRageMath.CreateFromQuaternion.md)||
|[`Matrix CreateFromYawPitchRoll(float yaw, float pitch, float roll)`](VRageMath.CreateFromYawPitchRoll.md)||
|[`void CreateFromYawPitchRoll(float yaw, float pitch, float roll, ref Matrix result)`](VRageMath.CreateFromYawPitchRoll.md)||
|[`Matrix CreateFromTransformScale(Quaternion orientation, Vector3 position, Vector3 scale)`](VRageMath.CreateFromTransformScale.md)||
|[`Matrix CreateShadow(Vector3 lightDirection, Plane plane)`](VRageMath.CreateShadow.md)||
|[`void CreateShadow(ref Vector3 lightDirection, ref Plane plane, ref Matrix result)`](VRageMath.CreateShadow.md)||
|[`Matrix CreateReflection(Plane value)`](VRageMath.CreateReflection.md)|Creates a Matrix that reflects the coordinate system about a specified Plane.|
|[`void CreateReflection(ref Plane value, ref Matrix result)`](VRageMath.CreateReflection.md)||
|[`Matrix Transform(Matrix value, Quaternion rotation)`](VRageMath.Transform.md)||
|[`void Transform(ref Matrix value, ref Quaternion rotation, ref Matrix result)`](VRageMath.Transform.md)||
|[`Vector4 GetRow(int row)`](VRageMath.GetRow.md)||
|[`void SetRow(int row, Vector4 value)`](VRageMath.SetRow.md)||
|[`string ToString()`](VRageMath.ToString.md)||
|[`bool Equals(Matrix other)`](VRageMath.Equals.md)|Determines whether the specified Object is equal to the Matrix.|
|[`bool EqualsFast(ref Matrix other, float epsilon)`](VRageMath.EqualsFast.md)||
|[`bool Equals(Object obj)`](VRageMath.Equals.md)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`Matrix Transpose(Matrix matrix)`](VRageMath.Transpose.md)|Transposes the rows and columns of a matrix.|
|[`void Transpose(ref Matrix matrix, ref Matrix result)`](VRageMath.Transpose.md)||
|[`void TransposeRotationInPlace()`](VRageMath.TransposeRotationInPlace.md)||
|[`float Determinant()`](VRageMath.Determinant.md)||
|[`Matrix Invert(Matrix matrix)`](VRageMath.Invert.md)|Calculates the inverse of a matrix.|
|[`Matrix Invert(ref Matrix matrix)`](VRageMath.Invert.md)||
|[`void Invert(ref Matrix matrix, ref Matrix result)`](VRageMath.Invert.md)||
|[`Matrix Lerp(Matrix matrix1, Matrix matrix2, float amount)`](VRageMath.Lerp.md)||
|[`void Lerp(ref Matrix matrix1, ref Matrix matrix2, float amount, ref Matrix result)`](VRageMath.Lerp.md)||
|[`void Slerp(ref Matrix matrix1, ref Matrix matrix2, float amount, ref Matrix result)`](VRageMath.Slerp.md)||
|[`void SlerpScale(ref Matrix matrix1, ref Matrix matrix2, float amount, ref Matrix result)`](VRageMath.SlerpScale.md)||
|[`void Slerp(Matrix matrix1, Matrix matrix2, float amount, ref Matrix result)`](VRageMath.Slerp.md)||
|[`Matrix Slerp(Matrix matrix1, Matrix matrix2, float amount)`](VRageMath.Slerp.md)||
|[`void SlerpScale(Matrix matrix1, Matrix matrix2, float amount, ref Matrix result)`](VRageMath.SlerpScale.md)||
|[`Matrix SlerpScale(Matrix matrix1, Matrix matrix2, float amount)`](VRageMath.SlerpScale.md)||
|[`Matrix Negate(Matrix matrix)`](VRageMath.Negate.md)|Negates individual elements of a matrix.|
|[`void Negate(ref Matrix matrix, ref Matrix result)`](VRageMath.Negate.md)||
|[`Matrix Add(Matrix matrix1, Matrix matrix2)`](VRageMath.Add.md)||
|[`void Add(ref Matrix matrix1, ref Matrix matrix2, ref Matrix result)`](VRageMath.Add.md)||
|[`Matrix Subtract(Matrix matrix1, Matrix matrix2)`](VRageMath.Subtract.md)||
