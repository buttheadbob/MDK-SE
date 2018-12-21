← [Index](index.md)
#MatrixD Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
##Summary
Defines a matrix.
###Fields
|Member|Description|
|---|---|
|[`double M11`](VRageMath.M11.md)||
|[`double M12`](VRageMath.M12.md)||
|[`double M13`](VRageMath.M13.md)||
|[`double M14`](VRageMath.M14.md)||
|[`double M21`](VRageMath.M21.md)||
|[`double M22`](VRageMath.M22.md)||
|[`double M23`](VRageMath.M23.md)||
|[`double M24`](VRageMath.M24.md)||
|[`double M31`](VRageMath.M31.md)||
|[`double M32`](VRageMath.M32.md)||
|[`double M33`](VRageMath.M33.md)||
|[`double M34`](VRageMath.M34.md)||
|[`double M41`](VRageMath.M41.md)||
|[`double M42`](VRageMath.M42.md)||
|[`double M43`](VRageMath.M43.md)||
|[`double M44`](VRageMath.M44.md)||
|[`MatrixD Identity`](VRageMath.Identity.md)||
|[`MatrixD Zero`](VRageMath.Zero.md)||
###Properties
|Member|Description|
|---|---|
|[`Vector3D Col0`](VRageMath.Col0.md)||
|[`Vector3D Col1`](VRageMath.Col1.md)||
|[`Vector3D Col2`](VRageMath.Col2.md)||
|[`Vector3D Up`](VRageMath.Up.md)||
|[`Vector3D Down`](VRageMath.Down.md)||
|[`Vector3D Right`](VRageMath.Right.md)||
|[`Vector3D Left`](VRageMath.Left.md)||
|[`Vector3D Forward`](VRageMath.Forward.md)||
|[`Vector3D Backward`](VRageMath.Backward.md)||
|[`Vector3D Scale`](VRageMath.Scale.md)||
|[`Vector3D Translation`](VRageMath.Translation.md)||
|[`Matrix3x3 Rotation`](VRageMath.Rotation.md)||
|[`double Item`](VRageMath.Item.md)||
###Methods
|Member|Description|
|---|---|
|[`Matrix Subtract(Matrix matrix1, Matrix matrix2)`](VRageMath.Subtract.md)||
|[`void Subtract(ref MatrixD matrix1, ref MatrixD matrix2, ref MatrixD result)`](VRageMath.Subtract.md)||
|[`MatrixD Multiply(MatrixD matrix1, MatrixD matrix2)`](VRageMath.Multiply.md)||
|[`MatrixD Multiply(MatrixD matrix1, Matrix matrix2)`](VRageMath.Multiply.md)||
|[`void Multiply(ref MatrixD matrix1, ref Matrix matrix2, ref MatrixD result)`](VRageMath.Multiply.md)||
|[`void Multiply(ref Matrix matrix1, ref MatrixD matrix2, ref MatrixD result)`](VRageMath.Multiply.md)||
|[`void Multiply(ref MatrixD matrix1, ref MatrixD matrix2, ref MatrixD result)`](VRageMath.Multiply.md)||
|[`MatrixD Multiply(MatrixD matrix1, double scaleFactor)`](VRageMath.Multiply.md)||
|[`void Multiply(ref MatrixD matrix1, double scaleFactor, ref MatrixD result)`](VRageMath.Multiply.md)||
|[`MatrixD Divide(MatrixD matrix1, MatrixD matrix2)`](VRageMath.Divide.md)||
|[`void Divide(ref MatrixD matrix1, ref MatrixD matrix2, ref MatrixD result)`](VRageMath.Divide.md)||
|[`MatrixD Divide(MatrixD matrix1, double divider)`](VRageMath.Divide.md)||
|[`void Divide(ref MatrixD matrix1, double divider, ref MatrixD result)`](VRageMath.Divide.md)||
|[`MatrixD GetOrientation()`](VRageMath.GetOrientation.md)||
|[`void AssertIsValid()`](VRageMath.AssertIsValid.md)||
|[`bool IsValid()`](VRageMath.IsValid.md)||
|[`bool IsNan()`](VRageMath.IsNan.md)||
|[`bool IsRotation()`](VRageMath.IsRotation.md)||
|[`bool HasNoTranslationOrPerspective()`](VRageMath.HasNoTranslationOrPerspective.md)||
|[`MatrixD CreateFromDir(Vector3D dir)`](VRageMath.CreateFromDir.md)||
|[`MatrixD CreateFromDir(Vector3D dir, Vector3D suggestedUp)`](VRageMath.CreateFromDir.md)||
|[`MatrixD Normalize(MatrixD matrix)`](VRageMath.Normalize.md)||
|[`void Orthogonalize()`](VRageMath.Orthogonalize.md)||
|[`MatrixD Orthogonalize(MatrixD rotationMatrix)`](VRageMath.Orthogonalize.md)||
|[`MatrixD AlignRotationToAxes(ref MatrixD toAlign, ref MatrixD axisDefinitionMatrix)`](VRageMath.AlignRotationToAxes.md)||
|[`bool GetEulerAnglesXYZ(ref MatrixD mat, ref Vector3D xyz)`](VRageMath.GetEulerAnglesXYZ.md)||
|[`MatrixD SwapYZCoordinates(MatrixD m)`](VRageMath.SwapYZCoordinates.md)||
|[`bool IsMirrored()`](VRageMath.IsMirrored.md)||
|[`Vector3D GetDirectionVector(Direction direction)`](VRageMath.GetDirectionVector.md)||
|[`void SetDirectionVector(Direction direction, Vector3D newValue)`](VRageMath.SetDirectionVector.md)||
|[`Direction GetClosestDirection(Vector3D referenceVector)`](VRageMath.GetClosestDirection.md)||
|[`Direction GetClosestDirection(ref Vector3D referenceVector)`](VRageMath.GetClosestDirection.md)||
|[`void Rescale(ref MatrixD matrix, double scale)`](VRageMath.Rescale.md)||
|[`void Rescale(ref MatrixD matrix, float scale)`](VRageMath.Rescale.md)||
|[`void Rescale(ref MatrixD matrix, ref Vector3D scale)`](VRageMath.Rescale.md)||
|[`MatrixD Rescale(MatrixD matrix, double scale)`](VRageMath.Rescale.md)||
|[`MatrixD Rescale(MatrixD matrix, Vector3D scale)`](VRageMath.Rescale.md)||
|[`MatrixD CreateBillboard(Vector3D objectPosition, Vector3D cameraPosition, Vector3D cameraUpVector, Nullable<Vector3D> cameraForwardVector)`](VRageMath.CreateBillboard.md)||
|[`void CreateBillboard(ref Vector3D objectPosition, ref Vector3D cameraPosition, ref Vector3D cameraUpVector, Nullable<Vector3D> cameraForwardVector, ref MatrixD result)`](VRageMath.CreateBillboard.md)||
|[`MatrixD CreateConstrainedBillboard(Vector3D objectPosition, Vector3D cameraPosition, Vector3D rotateAxis, Nullable<Vector3D> cameraForwardVector, Nullable<Vector3D> objectForwardVector)`](VRageMath.CreateConstrainedBillboard.md)||
|[`void CreateConstrainedBillboard(ref Vector3D objectPosition, ref Vector3D cameraPosition, ref Vector3D rotateAxis, Nullable<Vector3D> cameraForwardVector, Nullable<Vector3D> objectForwardVector, ref MatrixD result)`](VRageMath.CreateConstrainedBillboard.md)||
|[`MatrixD CreateTranslation(Vector3D position)`](VRageMath.CreateTranslation.md)|Creates a translation Matrix.|
|[`MatrixD CreateTranslation(Vector3 position)`](VRageMath.CreateTranslation.md)||
|[`void CreateTranslation(ref Vector3D position, ref MatrixD result)`](VRageMath.CreateTranslation.md)||
|[`MatrixD CreateTranslation(double xPosition, double yPosition, double zPosition)`](VRageMath.CreateTranslation.md)||
|[`void CreateTranslation(double xPosition, double yPosition, double zPosition, ref MatrixD result)`](VRageMath.CreateTranslation.md)||
|[`MatrixD CreateScale(double xScale, double yScale, double zScale)`](VRageMath.CreateScale.md)||
|[`void CreateScale(double xScale, double yScale, double zScale, ref MatrixD result)`](VRageMath.CreateScale.md)||
|[`MatrixD CreateScale(Vector3D scales)`](VRageMath.CreateScale.md)|Creates a scaling Matrix.|
|[`void CreateScale(ref Vector3D scales, ref MatrixD result)`](VRageMath.CreateScale.md)||
|[`MatrixD CreateScale(double scale)`](VRageMath.CreateScale.md)|Creates a scaling Matrix.|
|[`void CreateScale(double scale, ref MatrixD result)`](VRageMath.CreateScale.md)||
|[`MatrixD CreateRotationX(double radians)`](VRageMath.CreateRotationX.md)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|[`void CreateRotationX(double radians, ref MatrixD result)`](VRageMath.CreateRotationX.md)||
|[`MatrixD CreateRotationY(double radians)`](VRageMath.CreateRotationY.md)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|[`void CreateRotationY(double radians, ref MatrixD result)`](VRageMath.CreateRotationY.md)||
|[`MatrixD CreateRotationZ(double radians)`](VRageMath.CreateRotationZ.md)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|[`void CreateRotationZ(double radians, ref MatrixD result)`](VRageMath.CreateRotationZ.md)||
|[`MatrixD CreateFromAxisAngle(Vector3D axis, double angle)`](VRageMath.CreateFromAxisAngle.md)||
|[`void CreateFromAxisAngle(ref Vector3D axis, double angle, ref MatrixD result)`](VRageMath.CreateFromAxisAngle.md)||
|[`MatrixD CreatePerspectiveFieldOfView(double fieldOfView, double aspectRatio, double nearPlaneDistance, double farPlaneDistance)`](VRageMath.CreatePerspectiveFieldOfView.md)||
|[`void CreatePerspectiveFieldOfView(double fieldOfView, double aspectRatio, double nearPlaneDistance, double farPlaneDistance, ref MatrixD result)`](VRageMath.CreatePerspectiveFieldOfView.md)||
|[`MatrixD CreatePerspective(double width, double height, double nearPlaneDistance, double farPlaneDistance)`](VRageMath.CreatePerspective.md)||
|[`void CreatePerspective(double width, double height, double nearPlaneDistance, double farPlaneDistance, ref MatrixD result)`](VRageMath.CreatePerspective.md)||
|[`MatrixD CreatePerspectiveOffCenter(double left, double right, double bottom, double top, double nearPlaneDistance, double farPlaneDistance)`](VRageMath.CreatePerspectiveOffCenter.md)||
|[`void CreatePerspectiveOffCenter(double left, double right, double bottom, double top, double nearPlaneDistance, double farPlaneDistance, ref MatrixD result)`](VRageMath.CreatePerspectiveOffCenter.md)||
|[`MatrixD CreateOrthographic(double width, double height, double zNearPlane, double zFarPlane)`](VRageMath.CreateOrthographic.md)||
|[`void CreateOrthographic(double width, double height, double zNearPlane, double zFarPlane, ref MatrixD result)`](VRageMath.CreateOrthographic.md)||
|[`MatrixD CreateOrthographicOffCenter(double left, double right, double bottom, double top, double zNearPlane, double zFarPlane)`](VRageMath.CreateOrthographicOffCenter.md)||
|[`void CreateOrthographicOffCenter(double left, double right, double bottom, double top, double zNearPlane, double zFarPlane, ref MatrixD result)`](VRageMath.CreateOrthographicOffCenter.md)||
|[`MatrixD CreateLookAt(Vector3D cameraPosition, Vector3D cameraTarget, Vector3 cameraUpVector)`](VRageMath.CreateLookAt.md)||
|[`MatrixD CreateLookAt(Vector3D cameraPosition, Vector3D cameraTarget, Vector3D cameraUpVector)`](VRageMath.CreateLookAt.md)||
|[`Matrix CreateLookAtInverse(Vector3D cameraPosition, Vector3D cameraTarget, Vector3D cameraUpVector)`](VRageMath.CreateLookAtInverse.md)||
|[`void CreateLookAt(ref Vector3D cameraPosition, ref Vector3D cameraTarget, ref Vector3D cameraUpVector, ref MatrixD result)`](VRageMath.CreateLookAt.md)||
|[`MatrixD CreateWorld(Vector3D position, Vector3 forward, Vector3 up)`](VRageMath.CreateWorld.md)||
|[`MatrixD CreateWorld(Vector3D position)`](VRageMath.CreateWorld.md)||
|[`MatrixD CreateWorld(Vector3D position, Vector3D forward, Vector3D up)`](VRageMath.CreateWorld.md)||
|[`void CreateWorld(ref Vector3D position, ref Vector3D forward, ref Vector3D up, ref MatrixD result)`](VRageMath.CreateWorld.md)||
|[`MatrixD CreateFromQuaternion(Quaternion quaternion)`](VRageMath.CreateFromQuaternion.md)|Creates a rotation Matrix from a Quaternion.|
|[`MatrixD CreateFromQuaternion(QuaternionD quaternion)`](VRageMath.CreateFromQuaternion.md)||
|[`void CreateFromQuaternion(ref Quaternion quaternion, ref MatrixD result)`](VRageMath.CreateFromQuaternion.md)||
|[`MatrixD CreateFromYawPitchRoll(double yaw, double pitch, double roll)`](VRageMath.CreateFromYawPitchRoll.md)||
|[`void CreateFromYawPitchRoll(double yaw, double pitch, double roll, ref MatrixD result)`](VRageMath.CreateFromYawPitchRoll.md)||
|[`MatrixD CreateFromTransformScale(Quaternion orientation, Vector3D position, Vector3D scale)`](VRageMath.CreateFromTransformScale.md)||
|[`MatrixD CreateShadow(Vector3D lightDirection, Plane plane)`](VRageMath.CreateShadow.md)||
|[`void CreateShadow(ref Vector3D lightDirection, ref Plane plane, ref MatrixD result)`](VRageMath.CreateShadow.md)||
|[`MatrixD CreateReflection(Plane value)`](VRageMath.CreateReflection.md)|Creates a Matrix that reflects the coordinate system about a specified Plane.|
|[`void CreateReflection(ref Plane value, ref MatrixD result)`](VRageMath.CreateReflection.md)||
|[`MatrixD Transform(MatrixD value, Quaternion rotation)`](VRageMath.Transform.md)||
|[`void Transform(ref MatrixD value, ref Quaternion rotation, ref MatrixD result)`](VRageMath.Transform.md)||
|[`Vector4 GetRow(int row)`](VRageMath.GetRow.md)||
|[`void SetRow(int row, Vector4 value)`](VRageMath.SetRow.md)||
|[`string ToString()`](VRageMath.ToString.md)||
|[`bool Equals(MatrixD other)`](VRageMath.Equals.md)|Determines whether the specified Object is equal to the Matrix.|
|[`bool EqualsFast(ref MatrixD other, double epsilon)`](VRageMath.EqualsFast.md)||
|[`bool Equals(Object obj)`](VRageMath.Equals.md)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`MatrixD Transpose(MatrixD matrix)`](VRageMath.Transpose.md)|Transposes the rows and columns of a matrix.|
|[`void Transpose(ref MatrixD matrix, ref MatrixD result)`](VRageMath.Transpose.md)||
|[`double Determinant()`](VRageMath.Determinant.md)||
|[`MatrixD Invert(MatrixD matrix)`](VRageMath.Invert.md)|Calculates the inverse of a matrix.|
|[`MatrixD Invert(ref MatrixD matrix)`](VRageMath.Invert.md)||
|[`void Invert(ref MatrixD matrix, ref MatrixD result)`](VRageMath.Invert.md)||
|[`MatrixD Lerp(MatrixD matrix1, MatrixD matrix2, double amount)`](VRageMath.Lerp.md)||
|[`void Lerp(ref MatrixD matrix1, ref MatrixD matrix2, double amount, ref MatrixD result)`](VRageMath.Lerp.md)||
|[`void Slerp(ref MatrixD matrix1, ref MatrixD matrix2, float amount, ref MatrixD result)`](VRageMath.Slerp.md)||
|[`bool IsOrthogonal()`](VRageMath.IsOrthogonal.md)||
|[`bool IsOrthogonal(double epsilon)`](VRageMath.IsOrthogonal.md)||
|[`void SlerpScale(ref MatrixD matrix1, ref MatrixD matrix2, float amount, ref MatrixD result)`](VRageMath.SlerpScale.md)||
|[`void Slerp(MatrixD matrix1, MatrixD matrix2, float amount, ref MatrixD result)`](VRageMath.Slerp.md)||
|[`MatrixD Slerp(MatrixD matrix1, MatrixD matrix2, float amount)`](VRageMath.Slerp.md)||
|[`void SlerpScale(MatrixD matrix1, MatrixD matrix2, float amount, ref MatrixD result)`](VRageMath.SlerpScale.md)||
|[`MatrixD SlerpScale(MatrixD matrix1, MatrixD matrix2, float amount)`](VRageMath.SlerpScale.md)||
|[`MatrixD Negate(MatrixD matrix)`](VRageMath.Negate.md)|Negates individual elements of a matrix.|
|[`void Negate(ref MatrixD matrix, ref MatrixD result)`](VRageMath.Negate.md)||
|[`MatrixD Add(MatrixD matrix1, MatrixD matrix2)`](VRageMath.Add.md)||
|[`void Add(ref MatrixD matrix1, ref MatrixD matrix2, ref MatrixD result)`](VRageMath.Add.md)||
