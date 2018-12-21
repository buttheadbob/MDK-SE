← [Index](index)
# MatrixD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a matrix.
### Fields
|Member|Description|
|---|---|
|[`double&nbsp;M11`](VRageMath.M11)|Value at row 1 column 1 of the matrix.|
|[`double&nbsp;M12`](VRageMath.M12)|Value at row 1 column 2 of the matrix.|
|[`double&nbsp;M13`](VRageMath.M13)|Value at row 1 column 3 of the matrix.|
|[`double&nbsp;M14`](VRageMath.M14)|Value at row 1 column 4 of the matrix.|
|[`double&nbsp;M21`](VRageMath.M21)|Value at row 2 column 1 of the matrix.|
|[`double&nbsp;M22`](VRageMath.M22)|Value at row 2 column 2 of the matrix.|
|[`double&nbsp;M23`](VRageMath.M23)|Value at row 2 column 3 of the matrix.|
|[`double&nbsp;M24`](VRageMath.M24)|Value at row 2 column 4 of the matrix.|
|[`double&nbsp;M31`](VRageMath.M31)|Value at row 3 column 1 of the matrix.|
|[`double&nbsp;M32`](VRageMath.M32)|Value at row 3 column 2 of the matrix.|
|[`double&nbsp;M33`](VRageMath.M33)|Value at row 3 column 3 of the matrix.|
|[`double&nbsp;M34`](VRageMath.M34)|Value at row 3 column 4 of the matrix.|
|[`double&nbsp;M41`](VRageMath.M41)|Value at row 4 column 1 of the matrix.|
|[`double&nbsp;M42`](VRageMath.M42)|Value at row 4 column 2 of the matrix.|
|[`double&nbsp;M43`](VRageMath.M43)|Value at row 4 column 3 of the matrix.|
|[`double&nbsp;M44`](VRageMath.M44)|Value at row 4 column 4 of the matrix.|
|static&nbsp;[`MatrixD&nbsp;Identity`](VRageMath.Identity)||
|static&nbsp;[`MatrixD&nbsp;Zero`](VRageMath.Zero)||
### Properties
|Member|Description|
|---|---|
|[`Vector3D&nbsp;Col0`](VRageMath.Col0)||
|[`Vector3D&nbsp;Col1`](VRageMath.Col1)||
|[`Vector3D&nbsp;Col2`](VRageMath.Col2)||
|[`Vector3D&nbsp;Up`](VRageMath.Up)|Gets and sets the up vector of the Matrix.|
|[`Vector3D&nbsp;Down`](VRageMath.Down)|Gets and sets the down vector of the Matrix.|
|[`Vector3D&nbsp;Right`](VRageMath.Right)|Gets and sets the right vector of the Matrix.|
|[`Vector3D&nbsp;Left`](VRageMath.Left)|Gets and sets the left vector of the Matrix.|
|[`Vector3D&nbsp;Forward`](VRageMath.Forward)|Gets and sets the forward vector of the Matrix.|
|[`Vector3D&nbsp;Backward`](VRageMath.Backward)|Gets and sets the backward vector of the Matrix.|
|[`Vector3D&nbsp;Scale`](VRageMath.Scale)||
|[`Vector3D&nbsp;Translation`](VRageMath.Translation)|Gets and sets the translation vector of the Matrix.|
|[`Matrix3x3&nbsp;Rotation`](VRageMath.Rotation)||
|[`double&nbsp;Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|static&nbsp;[`Matrix&nbsp;Subtract(Matrix&nbsp;matrix1,&nbsp;Matrix&nbsp;matrix2)`](VRageMath.Subtract)|Subtracts matrices.|
|static&nbsp;[`void&nbsp;Subtract(ref&nbsp;MatrixD&nbsp;matrix1,&nbsp;ref&nbsp;MatrixD&nbsp;matrix2,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.Subtract)|Subtracts matrices.|
|static&nbsp;[`MatrixD&nbsp;Multiply(MatrixD&nbsp;matrix1,&nbsp;MatrixD&nbsp;matrix2)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static&nbsp;[`MatrixD&nbsp;Multiply(MatrixD&nbsp;matrix1,&nbsp;Matrix&nbsp;matrix2)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static&nbsp;[`void&nbsp;Multiply(ref&nbsp;MatrixD&nbsp;matrix1,&nbsp;ref&nbsp;Matrix&nbsp;matrix2,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static&nbsp;[`void&nbsp;Multiply(ref&nbsp;Matrix&nbsp;matrix1,&nbsp;ref&nbsp;MatrixD&nbsp;matrix2,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.Multiply)||
|static&nbsp;[`void&nbsp;Multiply(ref&nbsp;MatrixD&nbsp;matrix1,&nbsp;ref&nbsp;MatrixD&nbsp;matrix2,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static&nbsp;[`MatrixD&nbsp;Multiply(MatrixD&nbsp;matrix1,&nbsp;double&nbsp;scaleFactor)`](VRageMath.Multiply)|Multiplies a matrix by a scalar value.|
|static&nbsp;[`void&nbsp;Multiply(ref&nbsp;MatrixD&nbsp;matrix1,&nbsp;double&nbsp;scaleFactor,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.Multiply)|Multiplies a matrix by a scalar value.|
|static&nbsp;[`MatrixD&nbsp;Divide(MatrixD&nbsp;matrix1,&nbsp;MatrixD&nbsp;matrix2)`](VRageMath.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|static&nbsp;[`void&nbsp;Divide(ref&nbsp;MatrixD&nbsp;matrix1,&nbsp;ref&nbsp;MatrixD&nbsp;matrix2,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|static&nbsp;[`MatrixD&nbsp;Divide(MatrixD&nbsp;matrix1,&nbsp;double&nbsp;divider)`](VRageMath.Divide)|Divides the components of a matrix by a scalar.|
|static&nbsp;[`void&nbsp;Divide(ref&nbsp;MatrixD&nbsp;matrix1,&nbsp;double&nbsp;divider,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.Divide)|Divides the components of a matrix by a scalar.|
|[`MatrixD&nbsp;GetOrientation()`](VRageMath.GetOrientation)|Gets the orientation.|
|[`void&nbsp;AssertIsValid()`](VRageMath.AssertIsValid)||
|[`bool&nbsp;IsValid()`](VRageMath.IsValid)||
|[`bool&nbsp;IsNan()`](VRageMath.IsNan)||
|[`bool&nbsp;IsRotation()`](VRageMath.IsRotation)||
|[`bool&nbsp;HasNoTranslationOrPerspective()`](VRageMath.HasNoTranslationOrPerspective)|Returns true if this matrix represents invertible (you can call Invert on it) linear (it does not contain translation or perspective transformation) transformation. Such matrix consist solely of rotations, shearing, mirroring and scaling. It can be orthogonalized to create an orthogonal rotation matrix.|
|static&nbsp;[`MatrixD&nbsp;CreateFromDir(Vector3D&nbsp;dir)`](VRageMath.CreateFromDir)||
|static&nbsp;[`MatrixD&nbsp;CreateFromDir(Vector3D&nbsp;dir,&nbsp;Vector3D&nbsp;suggestedUp)`](VRageMath.CreateFromDir)||
|static&nbsp;[`MatrixD&nbsp;Normalize(MatrixD&nbsp;matrix)`](VRageMath.Normalize)||
|[`void&nbsp;Orthogonalize()`](VRageMath.Orthogonalize)||
|static&nbsp;[`MatrixD&nbsp;Orthogonalize(MatrixD&nbsp;rotationMatrix)`](VRageMath.Orthogonalize)||
|static&nbsp;[`MatrixD&nbsp;AlignRotationToAxes(ref&nbsp;MatrixD&nbsp;toAlign,&nbsp;ref&nbsp;MatrixD&nbsp;axisDefinitionMatrix)`](VRageMath.AlignRotationToAxes)||
|static&nbsp;[`bool&nbsp;GetEulerAnglesXYZ(ref&nbsp;MatrixD&nbsp;mat,&nbsp;ref&nbsp;Vector3D&nbsp;xyz)`](VRageMath.GetEulerAnglesXYZ)||
|static&nbsp;[`MatrixD&nbsp;SwapYZCoordinates(MatrixD&nbsp;m)`](VRageMath.SwapYZCoordinates)||
|[`bool&nbsp;IsMirrored()`](VRageMath.IsMirrored)||
|[`Vector3D&nbsp;GetDirectionVector(Direction&nbsp;direction)`](VRageMath.GetDirectionVector)||
|[`void&nbsp;SetDirectionVector(Direction&nbsp;direction,&nbsp;Vector3D&nbsp;newValue)`](VRageMath.SetDirectionVector)||
|[`Direction&nbsp;GetClosestDirection(Vector3D&nbsp;referenceVector)`](VRageMath.GetClosestDirection)||
|[`Direction&nbsp;GetClosestDirection(ref&nbsp;Vector3D&nbsp;referenceVector)`](VRageMath.GetClosestDirection)||
|static&nbsp;[`void&nbsp;Rescale(ref&nbsp;MatrixD&nbsp;matrix,&nbsp;double&nbsp;scale)`](VRageMath.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|static&nbsp;[`void&nbsp;Rescale(ref&nbsp;MatrixD&nbsp;matrix,&nbsp;float&nbsp;scale)`](VRageMath.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|static&nbsp;[`void&nbsp;Rescale(ref&nbsp;MatrixD&nbsp;matrix,&nbsp;ref&nbsp;Vector3D&nbsp;scale)`](VRageMath.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|static&nbsp;[`MatrixD&nbsp;Rescale(MatrixD&nbsp;matrix,&nbsp;double&nbsp;scale)`](VRageMath.Rescale)||
|static&nbsp;[`MatrixD&nbsp;Rescale(MatrixD&nbsp;matrix,&nbsp;Vector3D&nbsp;scale)`](VRageMath.Rescale)||
|static&nbsp;[`MatrixD&nbsp;CreateBillboard(Vector3D&nbsp;objectPosition,&nbsp;Vector3D&nbsp;cameraPosition,&nbsp;Vector3D&nbsp;cameraUpVector,&nbsp;Nullable<Vector3D>&nbsp;cameraForwardVector)`](VRageMath.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|static&nbsp;[`void&nbsp;CreateBillboard(ref&nbsp;Vector3D&nbsp;objectPosition,&nbsp;ref&nbsp;Vector3D&nbsp;cameraPosition,&nbsp;ref&nbsp;Vector3D&nbsp;cameraUpVector,&nbsp;Nullable<Vector3D>&nbsp;cameraForwardVector,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|static&nbsp;[`MatrixD&nbsp;CreateConstrainedBillboard(Vector3D&nbsp;objectPosition,&nbsp;Vector3D&nbsp;cameraPosition,&nbsp;Vector3D&nbsp;rotateAxis,&nbsp;Nullable<Vector3D>&nbsp;cameraForwardVector,&nbsp;Nullable<Vector3D>&nbsp;objectForwardVector)`](VRageMath.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|static&nbsp;[`void&nbsp;CreateConstrainedBillboard(ref&nbsp;Vector3D&nbsp;objectPosition,&nbsp;ref&nbsp;Vector3D&nbsp;cameraPosition,&nbsp;ref&nbsp;Vector3D&nbsp;rotateAxis,&nbsp;Nullable<Vector3D>&nbsp;cameraForwardVector,&nbsp;Nullable<Vector3D>&nbsp;objectForwardVector,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|static&nbsp;[`MatrixD&nbsp;CreateTranslation(Vector3D&nbsp;position)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static&nbsp;[`MatrixD&nbsp;CreateTranslation(Vector3&nbsp;position)`](VRageMath.CreateTranslation)||
|static&nbsp;[`void&nbsp;CreateTranslation(ref&nbsp;Vector3D&nbsp;position,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static&nbsp;[`MatrixD&nbsp;CreateTranslation(double&nbsp;xPosition,&nbsp;double&nbsp;yPosition,&nbsp;double&nbsp;zPosition)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static&nbsp;[`void&nbsp;CreateTranslation(double&nbsp;xPosition,&nbsp;double&nbsp;yPosition,&nbsp;double&nbsp;zPosition,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static&nbsp;[`MatrixD&nbsp;CreateScale(double&nbsp;xScale,&nbsp;double&nbsp;yScale,&nbsp;double&nbsp;zScale)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static&nbsp;[`void&nbsp;CreateScale(double&nbsp;xScale,&nbsp;double&nbsp;yScale,&nbsp;double&nbsp;zScale,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static&nbsp;[`MatrixD&nbsp;CreateScale(Vector3D&nbsp;scales)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static&nbsp;[`void&nbsp;CreateScale(ref&nbsp;Vector3D&nbsp;scales,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static&nbsp;[`MatrixD&nbsp;CreateScale(double&nbsp;scale)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static&nbsp;[`void&nbsp;CreateScale(double&nbsp;scale,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static&nbsp;[`MatrixD&nbsp;CreateRotationX(double&nbsp;radians)`](VRageMath.CreateRotationX)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|static&nbsp;[`void&nbsp;CreateRotationX(double&nbsp;radians,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.CreateRotationX)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the x-axis.|
|static&nbsp;[`MatrixD&nbsp;CreateRotationY(double&nbsp;radians)`](VRageMath.CreateRotationY)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|static&nbsp;[`void&nbsp;CreateRotationY(double&nbsp;radians,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.CreateRotationY)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the y-axis.|
|static&nbsp;[`MatrixD&nbsp;CreateRotationZ(double&nbsp;radians)`](VRageMath.CreateRotationZ)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|static&nbsp;[`void&nbsp;CreateRotationZ(double&nbsp;radians,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.CreateRotationZ)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the z-axis.|
|static&nbsp;[`MatrixD&nbsp;CreateFromAxisAngle(Vector3D&nbsp;axis,&nbsp;double&nbsp;angle)`](VRageMath.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|static&nbsp;[`void&nbsp;CreateFromAxisAngle(ref&nbsp;Vector3D&nbsp;axis,&nbsp;double&nbsp;angle,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|static&nbsp;[`MatrixD&nbsp;CreatePerspectiveFieldOfView(double&nbsp;fieldOfView,&nbsp;double&nbsp;aspectRatio,&nbsp;double&nbsp;nearPlaneDistance,&nbsp;double&nbsp;farPlaneDistance)`](VRageMath.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by value.|
|static&nbsp;[`void&nbsp;CreatePerspectiveFieldOfView(double&nbsp;fieldOfView,&nbsp;double&nbsp;aspectRatio,&nbsp;double&nbsp;nearPlaneDistance,&nbsp;double&nbsp;farPlaneDistance,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by reference.|
|static&nbsp;[`MatrixD&nbsp;CreatePerspective(double&nbsp;width,&nbsp;double&nbsp;height,&nbsp;double&nbsp;nearPlaneDistance,&nbsp;double&nbsp;farPlaneDistance)`](VRageMath.CreatePerspective)|Builds a perspective projection matrix and returns the result by value.|
|static&nbsp;[`void&nbsp;CreatePerspective(double&nbsp;width,&nbsp;double&nbsp;height,&nbsp;double&nbsp;nearPlaneDistance,&nbsp;double&nbsp;farPlaneDistance,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.CreatePerspective)|Builds a perspective projection matrix and returns the result by reference.|
|static&nbsp;[`MatrixD&nbsp;CreatePerspectiveOffCenter(double&nbsp;left,&nbsp;double&nbsp;right,&nbsp;double&nbsp;bottom,&nbsp;double&nbsp;top,&nbsp;double&nbsp;nearPlaneDistance,&nbsp;double&nbsp;farPlaneDistance)`](VRageMath.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|static&nbsp;[`void&nbsp;CreatePerspectiveOffCenter(double&nbsp;left,&nbsp;double&nbsp;right,&nbsp;double&nbsp;bottom,&nbsp;double&nbsp;top,&nbsp;double&nbsp;nearPlaneDistance,&nbsp;double&nbsp;farPlaneDistance,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|static&nbsp;[`MatrixD&nbsp;CreateOrthographic(double&nbsp;width,&nbsp;double&nbsp;height,&nbsp;double&nbsp;zNearPlane,&nbsp;double&nbsp;zFarPlane)`](VRageMath.CreateOrthographic)|Builds an orthogonal projection matrix.|
|static&nbsp;[`void&nbsp;CreateOrthographic(double&nbsp;width,&nbsp;double&nbsp;height,&nbsp;double&nbsp;zNearPlane,&nbsp;double&nbsp;zFarPlane,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.CreateOrthographic)|Builds an orthogonal projection matrix.|
|static&nbsp;[`MatrixD&nbsp;CreateOrthographicOffCenter(double&nbsp;left,&nbsp;double&nbsp;right,&nbsp;double&nbsp;bottom,&nbsp;double&nbsp;top,&nbsp;double&nbsp;zNearPlane,&nbsp;double&nbsp;zFarPlane)`](VRageMath.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|static&nbsp;[`void&nbsp;CreateOrthographicOffCenter(double&nbsp;left,&nbsp;double&nbsp;right,&nbsp;double&nbsp;bottom,&nbsp;double&nbsp;top,&nbsp;double&nbsp;zNearPlane,&nbsp;double&nbsp;zFarPlane,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|static&nbsp;[`MatrixD&nbsp;CreateLookAt(Vector3D&nbsp;cameraPosition,&nbsp;Vector3D&nbsp;cameraTarget,&nbsp;Vector3&nbsp;cameraUpVector)`](VRageMath.CreateLookAt)||
|static&nbsp;[`MatrixD&nbsp;CreateLookAt(Vector3D&nbsp;cameraPosition,&nbsp;Vector3D&nbsp;cameraTarget,&nbsp;Vector3D&nbsp;cameraUpVector)`](VRageMath.CreateLookAt)|Creates a view matrix.|
|static&nbsp;[`Matrix&nbsp;CreateLookAtInverse(Vector3D&nbsp;cameraPosition,&nbsp;Vector3D&nbsp;cameraTarget,&nbsp;Vector3D&nbsp;cameraUpVector)`](VRageMath.CreateLookAtInverse)||
|static&nbsp;[`void&nbsp;CreateLookAt(ref&nbsp;Vector3D&nbsp;cameraPosition,&nbsp;ref&nbsp;Vector3D&nbsp;cameraTarget,&nbsp;ref&nbsp;Vector3D&nbsp;cameraUpVector,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.CreateLookAt)|Creates a view matrix.|
|static&nbsp;[`MatrixD&nbsp;CreateWorld(Vector3D&nbsp;position,&nbsp;Vector3&nbsp;forward,&nbsp;Vector3&nbsp;up)`](VRageMath.CreateWorld)||
|static&nbsp;[`MatrixD&nbsp;CreateWorld(Vector3D&nbsp;position)`](VRageMath.CreateWorld)||
|static&nbsp;[`MatrixD&nbsp;CreateWorld(Vector3D&nbsp;position,&nbsp;Vector3D&nbsp;forward,&nbsp;Vector3D&nbsp;up)`](VRageMath.CreateWorld)|Creates a world matrix with the specified parameters.|
|static&nbsp;[`void&nbsp;CreateWorld(ref&nbsp;Vector3D&nbsp;position,&nbsp;ref&nbsp;Vector3D&nbsp;forward,&nbsp;ref&nbsp;Vector3D&nbsp;up,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.CreateWorld)|Creates a world matrix with the specified parameters.|
|static&nbsp;[`MatrixD&nbsp;CreateFromQuaternion(Quaternion&nbsp;quaternion)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|static&nbsp;[`MatrixD&nbsp;CreateFromQuaternion(QuaternionD&nbsp;quaternion)`](VRageMath.CreateFromQuaternion)||
|static&nbsp;[`void&nbsp;CreateFromQuaternion(ref&nbsp;Quaternion&nbsp;quaternion,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|static&nbsp;[`MatrixD&nbsp;CreateFromYawPitchRoll(double&nbsp;yaw,&nbsp;double&nbsp;pitch,&nbsp;double&nbsp;roll)`](VRageMath.CreateFromYawPitchRoll)|Creates a new rotation matrix from a specified yaw, pitch, and roll.|
|static&nbsp;[`void&nbsp;CreateFromYawPitchRoll(double&nbsp;yaw,&nbsp;double&nbsp;pitch,&nbsp;double&nbsp;roll,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.CreateFromYawPitchRoll)|Fills in a rotation matrix from a specified yaw, pitch, and roll.|
|static&nbsp;[`MatrixD&nbsp;CreateFromTransformScale(Quaternion&nbsp;orientation,&nbsp;Vector3D&nbsp;position,&nbsp;Vector3D&nbsp;scale)`](VRageMath.CreateFromTransformScale)||
|static&nbsp;[`MatrixD&nbsp;CreateShadow(Vector3D&nbsp;lightDirection,&nbsp;Plane&nbsp;plane)`](VRageMath.CreateShadow)|Creates a Matrix that flattens geometry into a specified Plane as if casting a shadow from a specified light source.|
|static&nbsp;[`void&nbsp;CreateShadow(ref&nbsp;Vector3D&nbsp;lightDirection,&nbsp;ref&nbsp;Plane&nbsp;plane,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.CreateShadow)|Fills in a Matrix to flatten geometry into a specified Plane as if casting a shadow from a specified light source.|
|static&nbsp;[`MatrixD&nbsp;CreateReflection(Plane&nbsp;value)`](VRageMath.CreateReflection)|Creates a Matrix that reflects the coordinate system about a specified Plane.|
|static&nbsp;[`void&nbsp;CreateReflection(ref&nbsp;Plane&nbsp;value,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.CreateReflection)|Fills in an existing Matrix so that it reflects the coordinate system about a specified Plane.|
|static&nbsp;[`MatrixD&nbsp;Transform(MatrixD&nbsp;value,&nbsp;Quaternion&nbsp;rotation)`](VRageMath.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;MatrixD&nbsp;value,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|[`Vector4&nbsp;GetRow(int&nbsp;row)`](VRageMath.GetRow)||
|[`void&nbsp;SetRow(int&nbsp;row,&nbsp;Vector4&nbsp;value)`](VRageMath.SetRow)||
|[`string&nbsp;ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`bool&nbsp;Equals(MatrixD&nbsp;other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Matrix.|
|[`bool&nbsp;EqualsFast(ref&nbsp;MatrixD&nbsp;other,&nbsp;double&nbsp;epsilon)`](VRageMath.EqualsFast)|Compares just position, forward and up|
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of this object.|
|static&nbsp;[`MatrixD&nbsp;Transpose(MatrixD&nbsp;matrix)`](VRageMath.Transpose)|Transposes the rows and columns of a matrix.|
|static&nbsp;[`void&nbsp;Transpose(ref&nbsp;MatrixD&nbsp;matrix,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.Transpose)|Transposes the rows and columns of a matrix.|
|[`double&nbsp;Determinant()`](VRageMath.Determinant)|Calculates the determinant of the matrix.|
|static&nbsp;[`MatrixD&nbsp;Invert(MatrixD&nbsp;matrix)`](VRageMath.Invert)|Calculates the inverse of a matrix.|
|static&nbsp;[`MatrixD&nbsp;Invert(ref&nbsp;MatrixD&nbsp;matrix)`](VRageMath.Invert)||
|static&nbsp;[`void&nbsp;Invert(ref&nbsp;MatrixD&nbsp;matrix,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.Invert)|Calculates the inverse of a matrix.|
|static&nbsp;[`MatrixD&nbsp;Lerp(MatrixD&nbsp;matrix1,&nbsp;MatrixD&nbsp;matrix2,&nbsp;double&nbsp;amount)`](VRageMath.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|static&nbsp;[`void&nbsp;Lerp(ref&nbsp;MatrixD&nbsp;matrix1,&nbsp;ref&nbsp;MatrixD&nbsp;matrix2,&nbsp;double&nbsp;amount,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|static&nbsp;[`void&nbsp;Slerp(ref&nbsp;MatrixD&nbsp;matrix1,&nbsp;ref&nbsp;MatrixD&nbsp;matrix2,&nbsp;float&nbsp;amount,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|[`bool&nbsp;IsOrthogonal()`](VRageMath.IsOrthogonal)||
|[`bool&nbsp;IsOrthogonal(double&nbsp;epsilon)`](VRageMath.IsOrthogonal)||
|static&nbsp;[`void&nbsp;SlerpScale(ref&nbsp;MatrixD&nbsp;matrix1,&nbsp;ref&nbsp;MatrixD&nbsp;matrix2,&nbsp;float&nbsp;amount,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static&nbsp;[`void&nbsp;Slerp(MatrixD&nbsp;matrix1,&nbsp;MatrixD&nbsp;matrix2,&nbsp;float&nbsp;amount,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|static&nbsp;[`MatrixD&nbsp;Slerp(MatrixD&nbsp;matrix1,&nbsp;MatrixD&nbsp;matrix2,&nbsp;float&nbsp;amount)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|static&nbsp;[`void&nbsp;SlerpScale(MatrixD&nbsp;matrix1,&nbsp;MatrixD&nbsp;matrix2,&nbsp;float&nbsp;amount,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static&nbsp;[`MatrixD&nbsp;SlerpScale(MatrixD&nbsp;matrix1,&nbsp;MatrixD&nbsp;matrix2,&nbsp;float&nbsp;amount)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static&nbsp;[`MatrixD&nbsp;Negate(MatrixD&nbsp;matrix)`](VRageMath.Negate)|Negates individual elements of a matrix.|
|static&nbsp;[`void&nbsp;Negate(ref&nbsp;MatrixD&nbsp;matrix,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.Negate)|Negates individual elements of a matrix.|
|static&nbsp;[`MatrixD&nbsp;Add(MatrixD&nbsp;matrix1,&nbsp;MatrixD&nbsp;matrix2)`](VRageMath.Add)|Adds a matrix to another matrix.|
|static&nbsp;[`void&nbsp;Add(ref&nbsp;MatrixD&nbsp;matrix1,&nbsp;ref&nbsp;MatrixD&nbsp;matrix2,&nbsp;ref&nbsp;MatrixD&nbsp;result)`](VRageMath.Add)|Adds a matrix to another matrix.|
