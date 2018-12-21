← [Index](index.md)
# MatrixD Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Defines a matrix.
### Fields
|Member|Description|
|---|---|
|[`double M11`](VRageMath.M11)||
|[`double M12`](VRageMath.M12)||
|[`double M13`](VRageMath.M13)||
|[`double M14`](VRageMath.M14)||
|[`double M21`](VRageMath.M21)||
|[`double M22`](VRageMath.M22)||
|[`double M23`](VRageMath.M23)||
|[`double M24`](VRageMath.M24)||
|[`double M31`](VRageMath.M31)||
|[`double M32`](VRageMath.M32)||
|[`double M33`](VRageMath.M33)||
|[`double M34`](VRageMath.M34)||
|[`double M41`](VRageMath.M41)||
|[`double M42`](VRageMath.M42)||
|[`double M43`](VRageMath.M43)||
|[`double M44`](VRageMath.M44)||
|[`MatrixD Identity`](VRageMath.Identity)||
|[`MatrixD Zero`](VRageMath.Zero)||
### Properties
|Member|Description|
|---|---|
|[`Vector3D Col0`](VRageMath.Col0)||
|[`Vector3D Col1`](VRageMath.Col1)||
|[`Vector3D Col2`](VRageMath.Col2)||
|[`Vector3D Up`](VRageMath.Up)||
|[`Vector3D Down`](VRageMath.Down)||
|[`Vector3D Right`](VRageMath.Right)||
|[`Vector3D Left`](VRageMath.Left)||
|[`Vector3D Forward`](VRageMath.Forward)||
|[`Vector3D Backward`](VRageMath.Backward)||
|[`Vector3D Scale`](VRageMath.Scale)||
|[`Vector3D Translation`](VRageMath.Translation)||
|[`Matrix3x3 Rotation`](VRageMath.Rotation)||
|[`double Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|[`Matrix Subtract(Matrix matrix1, Matrix matrix2)`](VRageMath.Subtract)||
|[`void Subtract(ref MatrixD matrix1, ref MatrixD matrix2, ref MatrixD result)`](VRageMath.Subtract)||
|[`MatrixD Multiply(MatrixD matrix1, MatrixD matrix2)`](VRageMath.Multiply)||
|[`MatrixD Multiply(MatrixD matrix1, Matrix matrix2)`](VRageMath.Multiply)||
|[`void Multiply(ref MatrixD matrix1, ref Matrix matrix2, ref MatrixD result)`](VRageMath.Multiply)||
|[`void Multiply(ref Matrix matrix1, ref MatrixD matrix2, ref MatrixD result)`](VRageMath.Multiply)||
|[`void Multiply(ref MatrixD matrix1, ref MatrixD matrix2, ref MatrixD result)`](VRageMath.Multiply)||
|[`MatrixD Multiply(MatrixD matrix1, double scaleFactor)`](VRageMath.Multiply)||
|[`void Multiply(ref MatrixD matrix1, double scaleFactor, ref MatrixD result)`](VRageMath.Multiply)||
|[`MatrixD Divide(MatrixD matrix1, MatrixD matrix2)`](VRageMath.Divide)||
|[`void Divide(ref MatrixD matrix1, ref MatrixD matrix2, ref MatrixD result)`](VRageMath.Divide)||
|[`MatrixD Divide(MatrixD matrix1, double divider)`](VRageMath.Divide)||
|[`void Divide(ref MatrixD matrix1, double divider, ref MatrixD result)`](VRageMath.Divide)||
|[`MatrixD GetOrientation()`](VRageMath.GetOrientation)||
|[`void AssertIsValid()`](VRageMath.AssertIsValid)||
|[`bool IsValid()`](VRageMath.IsValid)||
|[`bool IsNan()`](VRageMath.IsNan)||
|[`bool IsRotation()`](VRageMath.IsRotation)||
|[`bool HasNoTranslationOrPerspective()`](VRageMath.HasNoTranslationOrPerspective)||
|[`MatrixD CreateFromDir(Vector3D dir)`](VRageMath.CreateFromDir)||
|[`MatrixD CreateFromDir(Vector3D dir, Vector3D suggestedUp)`](VRageMath.CreateFromDir)||
|[`MatrixD Normalize(MatrixD matrix)`](VRageMath.Normalize)||
|[`void Orthogonalize()`](VRageMath.Orthogonalize)||
|[`MatrixD Orthogonalize(MatrixD rotationMatrix)`](VRageMath.Orthogonalize)||
|[`MatrixD AlignRotationToAxes(ref MatrixD toAlign, ref MatrixD axisDefinitionMatrix)`](VRageMath.AlignRotationToAxes)||
|[`bool GetEulerAnglesXYZ(ref MatrixD mat, ref Vector3D xyz)`](VRageMath.GetEulerAnglesXYZ)||
|[`MatrixD SwapYZCoordinates(MatrixD m)`](VRageMath.SwapYZCoordinates)||
|[`bool IsMirrored()`](VRageMath.IsMirrored)||
|[`Vector3D GetDirectionVector(Direction direction)`](VRageMath.GetDirectionVector)||
|[`void SetDirectionVector(Direction direction, Vector3D newValue)`](VRageMath.SetDirectionVector)||
|[`Direction GetClosestDirection(Vector3D referenceVector)`](VRageMath.GetClosestDirection)||
|[`Direction GetClosestDirection(ref Vector3D referenceVector)`](VRageMath.GetClosestDirection)||
|[`void Rescale(ref MatrixD matrix, double scale)`](VRageMath.Rescale)||
|[`void Rescale(ref MatrixD matrix, float scale)`](VRageMath.Rescale)||
|[`void Rescale(ref MatrixD matrix, ref Vector3D scale)`](VRageMath.Rescale)||
|[`MatrixD Rescale(MatrixD matrix, double scale)`](VRageMath.Rescale)||
|[`MatrixD Rescale(MatrixD matrix, Vector3D scale)`](VRageMath.Rescale)||
|[`MatrixD CreateBillboard(Vector3D objectPosition, Vector3D cameraPosition, Vector3D cameraUpVector, Nullable<Vector3D> cameraForwardVector)`](VRageMath.CreateBillboard)||
|[`void CreateBillboard(ref Vector3D objectPosition, ref Vector3D cameraPosition, ref Vector3D cameraUpVector, Nullable<Vector3D> cameraForwardVector, ref MatrixD result)`](VRageMath.CreateBillboard)||
|[`MatrixD CreateConstrainedBillboard(Vector3D objectPosition, Vector3D cameraPosition, Vector3D rotateAxis, Nullable<Vector3D> cameraForwardVector, Nullable<Vector3D> objectForwardVector)`](VRageMath.CreateConstrainedBillboard)||
|[`void CreateConstrainedBillboard(ref Vector3D objectPosition, ref Vector3D cameraPosition, ref Vector3D rotateAxis, Nullable<Vector3D> cameraForwardVector, Nullable<Vector3D> objectForwardVector, ref MatrixD result)`](VRageMath.CreateConstrainedBillboard)||
|[`MatrixD CreateTranslation(Vector3D position)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|[`MatrixD CreateTranslation(Vector3 position)`](VRageMath.CreateTranslation)||
|[`void CreateTranslation(ref Vector3D position, ref MatrixD result)`](VRageMath.CreateTranslation)||
|[`MatrixD CreateTranslation(double xPosition, double yPosition, double zPosition)`](VRageMath.CreateTranslation)||
|[`void CreateTranslation(double xPosition, double yPosition, double zPosition, ref MatrixD result)`](VRageMath.CreateTranslation)||
|[`MatrixD CreateScale(double xScale, double yScale, double zScale)`](VRageMath.CreateScale)||
|[`void CreateScale(double xScale, double yScale, double zScale, ref MatrixD result)`](VRageMath.CreateScale)||
|[`MatrixD CreateScale(Vector3D scales)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|[`void CreateScale(ref Vector3D scales, ref MatrixD result)`](VRageMath.CreateScale)||
|[`MatrixD CreateScale(double scale)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|[`void CreateScale(double scale, ref MatrixD result)`](VRageMath.CreateScale)||
|[`MatrixD CreateRotationX(double radians)`](VRageMath.CreateRotationX)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|[`void CreateRotationX(double radians, ref MatrixD result)`](VRageMath.CreateRotationX)||
|[`MatrixD CreateRotationY(double radians)`](VRageMath.CreateRotationY)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|[`void CreateRotationY(double radians, ref MatrixD result)`](VRageMath.CreateRotationY)||
|[`MatrixD CreateRotationZ(double radians)`](VRageMath.CreateRotationZ)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|[`void CreateRotationZ(double radians, ref MatrixD result)`](VRageMath.CreateRotationZ)||
|[`MatrixD CreateFromAxisAngle(Vector3D axis, double angle)`](VRageMath.CreateFromAxisAngle)||
|[`void CreateFromAxisAngle(ref Vector3D axis, double angle, ref MatrixD result)`](VRageMath.CreateFromAxisAngle)||
|[`MatrixD CreatePerspectiveFieldOfView(double fieldOfView, double aspectRatio, double nearPlaneDistance, double farPlaneDistance)`](VRageMath.CreatePerspectiveFieldOfView)||
|[`void CreatePerspectiveFieldOfView(double fieldOfView, double aspectRatio, double nearPlaneDistance, double farPlaneDistance, ref MatrixD result)`](VRageMath.CreatePerspectiveFieldOfView)||
|[`MatrixD CreatePerspective(double width, double height, double nearPlaneDistance, double farPlaneDistance)`](VRageMath.CreatePerspective)||
|[`void CreatePerspective(double width, double height, double nearPlaneDistance, double farPlaneDistance, ref MatrixD result)`](VRageMath.CreatePerspective)||
|[`MatrixD CreatePerspectiveOffCenter(double left, double right, double bottom, double top, double nearPlaneDistance, double farPlaneDistance)`](VRageMath.CreatePerspectiveOffCenter)||
|[`void CreatePerspectiveOffCenter(double left, double right, double bottom, double top, double nearPlaneDistance, double farPlaneDistance, ref MatrixD result)`](VRageMath.CreatePerspectiveOffCenter)||
|[`MatrixD CreateOrthographic(double width, double height, double zNearPlane, double zFarPlane)`](VRageMath.CreateOrthographic)||
|[`void CreateOrthographic(double width, double height, double zNearPlane, double zFarPlane, ref MatrixD result)`](VRageMath.CreateOrthographic)||
|[`MatrixD CreateOrthographicOffCenter(double left, double right, double bottom, double top, double zNearPlane, double zFarPlane)`](VRageMath.CreateOrthographicOffCenter)||
|[`void CreateOrthographicOffCenter(double left, double right, double bottom, double top, double zNearPlane, double zFarPlane, ref MatrixD result)`](VRageMath.CreateOrthographicOffCenter)||
|[`MatrixD CreateLookAt(Vector3D cameraPosition, Vector3D cameraTarget, Vector3 cameraUpVector)`](VRageMath.CreateLookAt)||
|[`MatrixD CreateLookAt(Vector3D cameraPosition, Vector3D cameraTarget, Vector3D cameraUpVector)`](VRageMath.CreateLookAt)||
|[`Matrix CreateLookAtInverse(Vector3D cameraPosition, Vector3D cameraTarget, Vector3D cameraUpVector)`](VRageMath.CreateLookAtInverse)||
|[`void CreateLookAt(ref Vector3D cameraPosition, ref Vector3D cameraTarget, ref Vector3D cameraUpVector, ref MatrixD result)`](VRageMath.CreateLookAt)||
|[`MatrixD CreateWorld(Vector3D position, Vector3 forward, Vector3 up)`](VRageMath.CreateWorld)||
|[`MatrixD CreateWorld(Vector3D position)`](VRageMath.CreateWorld)||
|[`MatrixD CreateWorld(Vector3D position, Vector3D forward, Vector3D up)`](VRageMath.CreateWorld)||
|[`void CreateWorld(ref Vector3D position, ref Vector3D forward, ref Vector3D up, ref MatrixD result)`](VRageMath.CreateWorld)||
|[`MatrixD CreateFromQuaternion(Quaternion quaternion)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|[`MatrixD CreateFromQuaternion(QuaternionD quaternion)`](VRageMath.CreateFromQuaternion)||
|[`void CreateFromQuaternion(ref Quaternion quaternion, ref MatrixD result)`](VRageMath.CreateFromQuaternion)||
|[`MatrixD CreateFromYawPitchRoll(double yaw, double pitch, double roll)`](VRageMath.CreateFromYawPitchRoll)||
|[`void CreateFromYawPitchRoll(double yaw, double pitch, double roll, ref MatrixD result)`](VRageMath.CreateFromYawPitchRoll)||
|[`MatrixD CreateFromTransformScale(Quaternion orientation, Vector3D position, Vector3D scale)`](VRageMath.CreateFromTransformScale)||
|[`MatrixD CreateShadow(Vector3D lightDirection, Plane plane)`](VRageMath.CreateShadow)||
|[`void CreateShadow(ref Vector3D lightDirection, ref Plane plane, ref MatrixD result)`](VRageMath.CreateShadow)||
|[`MatrixD CreateReflection(Plane value)`](VRageMath.CreateReflection)|Creates a Matrix that reflects the coordinate system about a specified Plane.|
|[`void CreateReflection(ref Plane value, ref MatrixD result)`](VRageMath.CreateReflection)||
|[`MatrixD Transform(MatrixD value, Quaternion rotation)`](VRageMath.Transform)||
|[`void Transform(ref MatrixD value, ref Quaternion rotation, ref MatrixD result)`](VRageMath.Transform)||
|[`Vector4 GetRow(int row)`](VRageMath.GetRow)||
|[`void SetRow(int row, Vector4 value)`](VRageMath.SetRow)||
|[`string ToString()`](VRageMath.ToString)||
|[`bool Equals(MatrixD other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Matrix.|
|[`bool EqualsFast(ref MatrixD other, double epsilon)`](VRageMath.EqualsFast)||
|[`bool Equals(Object obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`MatrixD Transpose(MatrixD matrix)`](VRageMath.Transpose)|Transposes the rows and columns of a matrix.|
|[`void Transpose(ref MatrixD matrix, ref MatrixD result)`](VRageMath.Transpose)||
|[`double Determinant()`](VRageMath.Determinant)||
|[`MatrixD Invert(MatrixD matrix)`](VRageMath.Invert)|Calculates the inverse of a matrix.|
|[`MatrixD Invert(ref MatrixD matrix)`](VRageMath.Invert)||
|[`void Invert(ref MatrixD matrix, ref MatrixD result)`](VRageMath.Invert)||
|[`MatrixD Lerp(MatrixD matrix1, MatrixD matrix2, double amount)`](VRageMath.Lerp)||
|[`void Lerp(ref MatrixD matrix1, ref MatrixD matrix2, double amount, ref MatrixD result)`](VRageMath.Lerp)||
|[`void Slerp(ref MatrixD matrix1, ref MatrixD matrix2, float amount, ref MatrixD result)`](VRageMath.Slerp)||
|[`bool IsOrthogonal()`](VRageMath.IsOrthogonal)||
|[`bool IsOrthogonal(double epsilon)`](VRageMath.IsOrthogonal)||
|[`void SlerpScale(ref MatrixD matrix1, ref MatrixD matrix2, float amount, ref MatrixD result)`](VRageMath.SlerpScale)||
|[`void Slerp(MatrixD matrix1, MatrixD matrix2, float amount, ref MatrixD result)`](VRageMath.Slerp)||
|[`MatrixD Slerp(MatrixD matrix1, MatrixD matrix2, float amount)`](VRageMath.Slerp)||
|[`void SlerpScale(MatrixD matrix1, MatrixD matrix2, float amount, ref MatrixD result)`](VRageMath.SlerpScale)||
|[`MatrixD SlerpScale(MatrixD matrix1, MatrixD matrix2, float amount)`](VRageMath.SlerpScale)||
|[`MatrixD Negate(MatrixD matrix)`](VRageMath.Negate)|Negates individual elements of a matrix.|
|[`void Negate(ref MatrixD matrix, ref MatrixD result)`](VRageMath.Negate)||
|[`MatrixD Add(MatrixD matrix1, MatrixD matrix2)`](VRageMath.Add)||
|[`void Add(ref MatrixD matrix1, ref MatrixD matrix2, ref MatrixD result)`](VRageMath.Add)||
