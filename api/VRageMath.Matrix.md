← [Index](index)
# Matrix Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a matrix.
### Fields
|Member|Description|
|---|---|
|[`float&nbsp;M11`](VRageMath.M11)|Value at row 1 column 1 of the matrix.|
|[`float&nbsp;M12`](VRageMath.M12)|Value at row 1 column 2 of the matrix.|
|[`float&nbsp;M13`](VRageMath.M13)|Value at row 1 column 3 of the matrix.|
|[`float&nbsp;M14`](VRageMath.M14)|Value at row 1 column 4 of the matrix.|
|[`float&nbsp;M21`](VRageMath.M21)|Value at row 2 column 1 of the matrix.|
|[`float&nbsp;M22`](VRageMath.M22)|Value at row 2 column 2 of the matrix.|
|[`float&nbsp;M23`](VRageMath.M23)|Value at row 2 column 3 of the matrix.|
|[`float&nbsp;M24`](VRageMath.M24)|Value at row 2 column 4 of the matrix.|
|[`float&nbsp;M31`](VRageMath.M31)|Value at row 3 column 1 of the matrix.|
|[`float&nbsp;M32`](VRageMath.M32)|Value at row 3 column 2 of the matrix.|
|[`float&nbsp;M33`](VRageMath.M33)|Value at row 3 column 3 of the matrix.|
|[`float&nbsp;M34`](VRageMath.M34)|Value at row 3 column 4 of the matrix.|
|[`float&nbsp;M41`](VRageMath.M41)|Value at row 4 column 1 of the matrix.|
|[`float&nbsp;M42`](VRageMath.M42)|Value at row 4 column 2 of the matrix.|
|[`float&nbsp;M43`](VRageMath.M43)|Value at row 4 column 3 of the matrix.|
|[`float&nbsp;M44`](VRageMath.M44)|Value at row 4 column 4 of the matrix.|
|static&nbsp;[`Matrix&nbsp;Identity`](VRageMath.Identity)||
|static&nbsp;[`Matrix&nbsp;Zero`](VRageMath.Zero)||
### Properties
|Member|Description|
|---|---|
|[`Vector3&nbsp;Up`](VRageMath.Up)|Gets and sets the up vector of the Matrix.|
|[`Vector3&nbsp;Down`](VRageMath.Down)|Gets and sets the down vector of the Matrix.|
|[`Vector3&nbsp;Right`](VRageMath.Right)|Gets and sets the right vector of the Matrix.|
|[`Vector3&nbsp;Col0`](VRageMath.Col0)||
|[`Vector3&nbsp;Col1`](VRageMath.Col1)||
|[`Vector3&nbsp;Col2`](VRageMath.Col2)||
|[`Vector3&nbsp;Left`](VRageMath.Left)|Gets and sets the left vector of the Matrix.|
|[`Vector3&nbsp;Forward`](VRageMath.Forward)|Gets and sets the forward vector of the Matrix.|
|[`Vector3&nbsp;Backward`](VRageMath.Backward)|Gets and sets the backward vector of the Matrix.|
|[`Vector3&nbsp;Scale`](VRageMath.Scale)||
|[`Vector3&nbsp;Translation`](VRageMath.Translation)|Gets and sets the translation vector of the Matrix.|
|[`float&nbsp;Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|static&nbsp;[`void&nbsp;Subtract(ref&nbsp;Matrix&nbsp;matrix1,&nbsp;ref&nbsp;Matrix&nbsp;matrix2,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.Subtract)|Subtracts matrices.|
|static&nbsp;[`Matrix&nbsp;Multiply(Matrix&nbsp;matrix1,&nbsp;Matrix&nbsp;matrix2)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static&nbsp;[`void&nbsp;Multiply(ref&nbsp;Matrix&nbsp;matrix1,&nbsp;ref&nbsp;Matrix&nbsp;matrix2,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static&nbsp;[`void&nbsp;MultiplyRotation(ref&nbsp;Matrix&nbsp;matrix1,&nbsp;ref&nbsp;Matrix&nbsp;matrix2,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.MultiplyRotation)|Multiplies a matrix by another matrix, only rotation parts.|
|static&nbsp;[`Matrix&nbsp;Multiply(Matrix&nbsp;matrix1,&nbsp;float&nbsp;scaleFactor)`](VRageMath.Multiply)|Multiplies a matrix by a scalar value.|
|static&nbsp;[`void&nbsp;Multiply(ref&nbsp;Matrix&nbsp;matrix1,&nbsp;float&nbsp;scaleFactor,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.Multiply)|Multiplies a matrix by a scalar value.|
|static&nbsp;[`Matrix&nbsp;Divide(Matrix&nbsp;matrix1,&nbsp;Matrix&nbsp;matrix2)`](VRageMath.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|static&nbsp;[`void&nbsp;Divide(ref&nbsp;Matrix&nbsp;matrix1,&nbsp;ref&nbsp;Matrix&nbsp;matrix2,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|static&nbsp;[`Matrix&nbsp;Divide(Matrix&nbsp;matrix1,&nbsp;float&nbsp;divider)`](VRageMath.Divide)|Divides the components of a matrix by a scalar.|
|static&nbsp;[`void&nbsp;Divide(ref&nbsp;Matrix&nbsp;matrix1,&nbsp;float&nbsp;divider,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.Divide)|Divides the components of a matrix by a scalar.|
|[`Matrix&nbsp;GetOrientation()`](VRageMath.GetOrientation)|Gets the orientation.|
|[`void&nbsp;AssertIsValid()`](VRageMath.AssertIsValid)||
|[`bool&nbsp;IsValid()`](VRageMath.IsValid)||
|[`bool&nbsp;IsNan()`](VRageMath.IsNan)||
|[`bool&nbsp;IsRotation()`](VRageMath.IsRotation)||
|[`bool&nbsp;HasNoTranslationOrPerspective()`](VRageMath.HasNoTranslationOrPerspective)|Returns true if this matrix represents invertible (you can call Invert on it) linear (it does not contain translation or perspective transformation) transformation. Such matrix consist solely of rotations, shearing, mirroring and scaling. It can be orthogonalized to create an orthogonal rotation matrix.|
|static&nbsp;[`Matrix&nbsp;CreateFromDir(Vector3&nbsp;dir)`](VRageMath.CreateFromDir)||
|static&nbsp;[`Matrix&nbsp;CreateFromDir(Vector3&nbsp;dir,&nbsp;Vector3&nbsp;suggestedUp)`](VRageMath.CreateFromDir)||
|static&nbsp;[`Matrix&nbsp;Normalize(Matrix&nbsp;matrix)`](VRageMath.Normalize)||
|static&nbsp;[`Matrix&nbsp;Orthogonalize(Matrix&nbsp;rotationMatrix)`](VRageMath.Orthogonalize)||
|static&nbsp;[`Matrix&nbsp;Round(ref&nbsp;Matrix&nbsp;matrix)`](VRageMath.Round)||
|static&nbsp;[`Matrix&nbsp;AlignRotationToAxes(ref&nbsp;Matrix&nbsp;toAlign,&nbsp;ref&nbsp;Matrix&nbsp;axisDefinitionMatrix)`](VRageMath.AlignRotationToAxes)||
|static&nbsp;[`bool&nbsp;GetEulerAnglesXYZ(ref&nbsp;Matrix&nbsp;mat,&nbsp;ref&nbsp;Vector3&nbsp;xyz)`](VRageMath.GetEulerAnglesXYZ)||
|static&nbsp;[`Matrix&nbsp;SwapYZCoordinates(Matrix&nbsp;m)`](VRageMath.SwapYZCoordinates)||
|[`bool&nbsp;IsMirrored()`](VRageMath.IsMirrored)||
|[`bool&nbsp;IsOrthogonal()`](VRageMath.IsOrthogonal)||
|[`Vector3&nbsp;GetDirectionVector(Direction&nbsp;direction)`](VRageMath.GetDirectionVector)||
|[`void&nbsp;SetDirectionVector(Direction&nbsp;direction,&nbsp;Vector3&nbsp;newValue)`](VRageMath.SetDirectionVector)||
|[`Direction&nbsp;GetClosestDirection(Vector3&nbsp;referenceVector)`](VRageMath.GetClosestDirection)||
|[`Direction&nbsp;GetClosestDirection(ref&nbsp;Vector3&nbsp;referenceVector)`](VRageMath.GetClosestDirection)||
|static&nbsp;[`void&nbsp;Rescale(ref&nbsp;Matrix&nbsp;matrix,&nbsp;float&nbsp;scale)`](VRageMath.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|static&nbsp;[`void&nbsp;Rescale(ref&nbsp;Matrix&nbsp;matrix,&nbsp;ref&nbsp;Vector3&nbsp;scale)`](VRageMath.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|static&nbsp;[`Matrix&nbsp;Rescale(Matrix&nbsp;matrix,&nbsp;float&nbsp;scale)`](VRageMath.Rescale)||
|static&nbsp;[`Matrix&nbsp;Rescale(Matrix&nbsp;matrix,&nbsp;Vector3&nbsp;scale)`](VRageMath.Rescale)||
|static&nbsp;[`Matrix&nbsp;CreateBillboard(Vector3&nbsp;objectPosition,&nbsp;Vector3&nbsp;cameraPosition,&nbsp;Vector3&nbsp;cameraUpVector,&nbsp;Nullable<Vector3>&nbsp;cameraForwardVector)`](VRageMath.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|static&nbsp;[`void&nbsp;CreateBillboard(ref&nbsp;Vector3&nbsp;objectPosition,&nbsp;ref&nbsp;Vector3&nbsp;cameraPosition,&nbsp;ref&nbsp;Vector3&nbsp;cameraUpVector,&nbsp;Nullable<Vector3>&nbsp;cameraForwardVector,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|static&nbsp;[`Matrix&nbsp;CreateConstrainedBillboard(Vector3&nbsp;objectPosition,&nbsp;Vector3&nbsp;cameraPosition,&nbsp;Vector3&nbsp;rotateAxis,&nbsp;Nullable<Vector3>&nbsp;cameraForwardVector,&nbsp;Nullable<Vector3>&nbsp;objectForwardVector)`](VRageMath.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|static&nbsp;[`void&nbsp;CreateConstrainedBillboard(ref&nbsp;Vector3&nbsp;objectPosition,&nbsp;ref&nbsp;Vector3&nbsp;cameraPosition,&nbsp;ref&nbsp;Vector3&nbsp;rotateAxis,&nbsp;Nullable<Vector3>&nbsp;cameraForwardVector,&nbsp;Nullable<Vector3>&nbsp;objectForwardVector,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|static&nbsp;[`Matrix&nbsp;CreateTranslation(Vector3&nbsp;position)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static&nbsp;[`void&nbsp;CreateTranslation(ref&nbsp;Vector3&nbsp;position,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static&nbsp;[`Matrix&nbsp;CreateTranslation(float&nbsp;xPosition,&nbsp;float&nbsp;yPosition,&nbsp;float&nbsp;zPosition)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static&nbsp;[`void&nbsp;CreateTranslation(float&nbsp;xPosition,&nbsp;float&nbsp;yPosition,&nbsp;float&nbsp;zPosition,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static&nbsp;[`Matrix&nbsp;CreateScale(float&nbsp;xScale,&nbsp;float&nbsp;yScale,&nbsp;float&nbsp;zScale)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static&nbsp;[`void&nbsp;CreateScale(float&nbsp;xScale,&nbsp;float&nbsp;yScale,&nbsp;float&nbsp;zScale,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static&nbsp;[`Matrix&nbsp;CreateScale(Vector3&nbsp;scales)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static&nbsp;[`void&nbsp;CreateScale(ref&nbsp;Vector3&nbsp;scales,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static&nbsp;[`Matrix&nbsp;CreateScale(float&nbsp;scale)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static&nbsp;[`void&nbsp;CreateScale(float&nbsp;scale,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static&nbsp;[`Matrix&nbsp;CreateRotationX(float&nbsp;radians)`](VRageMath.CreateRotationX)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|static&nbsp;[`void&nbsp;CreateRotationX(float&nbsp;radians,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.CreateRotationX)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the x-axis.|
|static&nbsp;[`Matrix&nbsp;CreateRotationY(float&nbsp;radians)`](VRageMath.CreateRotationY)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|static&nbsp;[`void&nbsp;CreateRotationY(float&nbsp;radians,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.CreateRotationY)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the y-axis.|
|static&nbsp;[`Matrix&nbsp;CreateRotationZ(float&nbsp;radians)`](VRageMath.CreateRotationZ)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|static&nbsp;[`void&nbsp;CreateRotationZ(float&nbsp;radians,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.CreateRotationZ)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the z-axis.|
|static&nbsp;[`Matrix&nbsp;CreateFromAxisAngle(Vector3&nbsp;axis,&nbsp;float&nbsp;angle)`](VRageMath.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|static&nbsp;[`void&nbsp;CreateFromAxisAngle(ref&nbsp;Vector3&nbsp;axis,&nbsp;float&nbsp;angle,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|static&nbsp;[`void&nbsp;CreateRotationFromTwoVectors(ref&nbsp;Vector3&nbsp;fromVector,&nbsp;ref&nbsp;Vector3&nbsp;toVector,&nbsp;ref&nbsp;Matrix&nbsp;resultMatrix)`](VRageMath.CreateRotationFromTwoVectors)||
|static&nbsp;[`Matrix&nbsp;CreatePerspectiveFieldOfView(float&nbsp;fieldOfView,&nbsp;float&nbsp;aspectRatio,&nbsp;float&nbsp;nearPlaneDistance,&nbsp;float&nbsp;farPlaneDistance)`](VRageMath.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by value.|
|static&nbsp;[`Matrix&nbsp;CreatePerspectiveFovRhComplementary(float&nbsp;fieldOfView,&nbsp;float&nbsp;aspectRatio,&nbsp;float&nbsp;nearPlaneDistance,&nbsp;float&nbsp;farPlaneDistance)`](VRageMath.CreatePerspectiveFovRhComplementary)||
|static&nbsp;[`Matrix&nbsp;CreatePerspectiveFovRhInfinite(float&nbsp;fieldOfView,&nbsp;float&nbsp;aspectRatio,&nbsp;float&nbsp;nearPlaneDistance)`](VRageMath.CreatePerspectiveFovRhInfinite)||
|static&nbsp;[`Matrix&nbsp;CreatePerspectiveFovRhInfiniteComplementary(float&nbsp;fieldOfView,&nbsp;float&nbsp;aspectRatio,&nbsp;float&nbsp;nearPlaneDistance)`](VRageMath.CreatePerspectiveFovRhInfiniteComplementary)||
|static&nbsp;[`Matrix&nbsp;CreatePerspectiveFovRhInverse(float&nbsp;fieldOfView,&nbsp;float&nbsp;aspectRatio,&nbsp;float&nbsp;nearPlaneDistance,&nbsp;float&nbsp;farPlaneDistance)`](VRageMath.CreatePerspectiveFovRhInverse)||
|static&nbsp;[`Matrix&nbsp;CreatePerspectiveFovRhInfiniteInverse(float&nbsp;fieldOfView,&nbsp;float&nbsp;aspectRatio,&nbsp;float&nbsp;nearPlaneDistance)`](VRageMath.CreatePerspectiveFovRhInfiniteInverse)||
|static&nbsp;[`Matrix&nbsp;CreatePerspectiveFovRhInfiniteComplementaryInverse(float&nbsp;fieldOfView,&nbsp;float&nbsp;aspectRatio,&nbsp;float&nbsp;nearPlaneDistance)`](VRageMath.CreatePerspectiveFovRhInfiniteComplementaryInverse)||
|static&nbsp;[`Matrix&nbsp;CreateFromPerspectiveFieldOfView(ref&nbsp;Matrix&nbsp;proj,&nbsp;float&nbsp;nearPlaneDistance,&nbsp;float&nbsp;farPlaneDistance)`](VRageMath.CreateFromPerspectiveFieldOfView)||
|static&nbsp;[`void&nbsp;CreatePerspectiveFieldOfView(float&nbsp;fieldOfView,&nbsp;float&nbsp;aspectRatio,&nbsp;float&nbsp;nearPlaneDistance,&nbsp;float&nbsp;farPlaneDistance,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by reference.|
|static&nbsp;[`Matrix&nbsp;CreatePerspective(float&nbsp;width,&nbsp;float&nbsp;height,&nbsp;float&nbsp;nearPlaneDistance,&nbsp;float&nbsp;farPlaneDistance)`](VRageMath.CreatePerspective)|Builds a perspective projection matrix and returns the result by value.|
|static&nbsp;[`void&nbsp;CreatePerspective(float&nbsp;width,&nbsp;float&nbsp;height,&nbsp;float&nbsp;nearPlaneDistance,&nbsp;float&nbsp;farPlaneDistance,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.CreatePerspective)|Builds a perspective projection matrix and returns the result by reference.|
|static&nbsp;[`Matrix&nbsp;CreatePerspectiveOffCenter(float&nbsp;left,&nbsp;float&nbsp;right,&nbsp;float&nbsp;bottom,&nbsp;float&nbsp;top,&nbsp;float&nbsp;nearPlaneDistance,&nbsp;float&nbsp;farPlaneDistance)`](VRageMath.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|static&nbsp;[`void&nbsp;CreatePerspectiveOffCenter(float&nbsp;left,&nbsp;float&nbsp;right,&nbsp;float&nbsp;bottom,&nbsp;float&nbsp;top,&nbsp;float&nbsp;nearPlaneDistance,&nbsp;float&nbsp;farPlaneDistance,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|static&nbsp;[`Matrix&nbsp;CreateOrthographic(float&nbsp;width,&nbsp;float&nbsp;height,&nbsp;float&nbsp;zNearPlane,&nbsp;float&nbsp;zFarPlane)`](VRageMath.CreateOrthographic)|Builds an orthogonal projection matrix.|
|static&nbsp;[`void&nbsp;CreateOrthographic(float&nbsp;width,&nbsp;float&nbsp;height,&nbsp;float&nbsp;zNearPlane,&nbsp;float&nbsp;zFarPlane,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.CreateOrthographic)|Builds an orthogonal projection matrix.|
|static&nbsp;[`Matrix&nbsp;CreateOrthographicOffCenter(float&nbsp;left,&nbsp;float&nbsp;right,&nbsp;float&nbsp;bottom,&nbsp;float&nbsp;top,&nbsp;float&nbsp;zNearPlane,&nbsp;float&nbsp;zFarPlane)`](VRageMath.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|static&nbsp;[`void&nbsp;CreateOrthographicOffCenter(float&nbsp;left,&nbsp;float&nbsp;right,&nbsp;float&nbsp;bottom,&nbsp;float&nbsp;top,&nbsp;float&nbsp;zNearPlane,&nbsp;float&nbsp;zFarPlane,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|static&nbsp;[`Matrix&nbsp;CreateLookAt(Vector3&nbsp;cameraPosition,&nbsp;Vector3&nbsp;cameraTarget,&nbsp;Vector3&nbsp;cameraUpVector)`](VRageMath.CreateLookAt)|Creates a view matrix.|
|static&nbsp;[`Matrix&nbsp;CreateLookAtInverse(Vector3&nbsp;cameraPosition,&nbsp;Vector3&nbsp;cameraTarget,&nbsp;Vector3&nbsp;cameraUpVector)`](VRageMath.CreateLookAtInverse)||
|static&nbsp;[`void&nbsp;CreateLookAt(ref&nbsp;Vector3&nbsp;cameraPosition,&nbsp;ref&nbsp;Vector3&nbsp;cameraTarget,&nbsp;ref&nbsp;Vector3&nbsp;cameraUpVector,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.CreateLookAt)|Creates a view matrix.|
|static&nbsp;[`Matrix&nbsp;CreateWorld(Vector3&nbsp;position)`](VRageMath.CreateWorld)||
|static&nbsp;[`Matrix&nbsp;CreateWorld(Vector3&nbsp;position,&nbsp;Vector3&nbsp;forward,&nbsp;Vector3&nbsp;up)`](VRageMath.CreateWorld)|Creates a world matrix with the specified parameters.|
|static&nbsp;[`void&nbsp;CreateWorld(ref&nbsp;Vector3&nbsp;position,&nbsp;ref&nbsp;Vector3&nbsp;forward,&nbsp;ref&nbsp;Vector3&nbsp;up,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.CreateWorld)|Creates a world matrix with the specified parameters.|
|static&nbsp;[`Matrix&nbsp;CreateFromQuaternion(Quaternion&nbsp;quaternion)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|static&nbsp;[`void&nbsp;CreateFromQuaternion(ref&nbsp;Quaternion&nbsp;quaternion,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|static&nbsp;[`Matrix&nbsp;CreateFromYawPitchRoll(float&nbsp;yaw,&nbsp;float&nbsp;pitch,&nbsp;float&nbsp;roll)`](VRageMath.CreateFromYawPitchRoll)|Creates a new rotation matrix from a specified yaw, pitch, and roll.|
|static&nbsp;[`void&nbsp;CreateFromYawPitchRoll(float&nbsp;yaw,&nbsp;float&nbsp;pitch,&nbsp;float&nbsp;roll,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.CreateFromYawPitchRoll)|Fills in a rotation matrix from a specified yaw, pitch, and roll.|
|static&nbsp;[`Matrix&nbsp;CreateFromTransformScale(Quaternion&nbsp;orientation,&nbsp;Vector3&nbsp;position,&nbsp;Vector3&nbsp;scale)`](VRageMath.CreateFromTransformScale)||
|static&nbsp;[`Matrix&nbsp;CreateShadow(Vector3&nbsp;lightDirection,&nbsp;Plane&nbsp;plane)`](VRageMath.CreateShadow)|Creates a Matrix that flattens geometry into a specified Plane as if casting a shadow from a specified light source.|
|static&nbsp;[`void&nbsp;CreateShadow(ref&nbsp;Vector3&nbsp;lightDirection,&nbsp;ref&nbsp;Plane&nbsp;plane,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.CreateShadow)|Fills in a Matrix to flatten geometry into a specified Plane as if casting a shadow from a specified light source.|
|static&nbsp;[`Matrix&nbsp;CreateReflection(Plane&nbsp;value)`](VRageMath.CreateReflection)|Creates a Matrix that reflects the coordinate system about a specified Plane.|
|static&nbsp;[`void&nbsp;CreateReflection(ref&nbsp;Plane&nbsp;value,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.CreateReflection)|Fills in an existing Matrix so that it reflects the coordinate system about a specified Plane.|
|static&nbsp;[`Matrix&nbsp;Transform(Matrix&nbsp;value,&nbsp;Quaternion&nbsp;rotation)`](VRageMath.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Matrix&nbsp;value,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|[`Vector4&nbsp;GetRow(int&nbsp;row)`](VRageMath.GetRow)||
|[`void&nbsp;SetRow(int&nbsp;row,&nbsp;Vector4&nbsp;value)`](VRageMath.SetRow)||
|[`string&nbsp;ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`bool&nbsp;Equals(Matrix&nbsp;other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Matrix.|
|[`bool&nbsp;EqualsFast(ref&nbsp;Matrix&nbsp;other,&nbsp;float&nbsp;epsilon)`](VRageMath.EqualsFast)|Compares just position, forward and up|
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of this object.|
|static&nbsp;[`Matrix&nbsp;Transpose(Matrix&nbsp;matrix)`](VRageMath.Transpose)|Transposes the rows and columns of a matrix.|
|static&nbsp;[`void&nbsp;Transpose(ref&nbsp;Matrix&nbsp;matrix,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.Transpose)|Transposes the rows and columns of a matrix.|
|[`void&nbsp;TransposeRotationInPlace()`](VRageMath.TransposeRotationInPlace)|Transposes the rows and columns of a matrix that is assumed to be rotation only in place.|
|[`float&nbsp;Determinant()`](VRageMath.Determinant)|Calculates the determinant of the matrix.|
|static&nbsp;[`Matrix&nbsp;Invert(Matrix&nbsp;matrix)`](VRageMath.Invert)|Calculates the inverse of a matrix.|
|static&nbsp;[`Matrix&nbsp;Invert(ref&nbsp;Matrix&nbsp;matrix)`](VRageMath.Invert)||
|static&nbsp;[`void&nbsp;Invert(ref&nbsp;Matrix&nbsp;matrix,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.Invert)|Calculates the inverse of a matrix.|
|static&nbsp;[`Matrix&nbsp;Lerp(Matrix&nbsp;matrix1,&nbsp;Matrix&nbsp;matrix2,&nbsp;float&nbsp;amount)`](VRageMath.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|static&nbsp;[`void&nbsp;Lerp(ref&nbsp;Matrix&nbsp;matrix1,&nbsp;ref&nbsp;Matrix&nbsp;matrix2,&nbsp;float&nbsp;amount,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|static&nbsp;[`void&nbsp;Slerp(ref&nbsp;Matrix&nbsp;matrix1,&nbsp;ref&nbsp;Matrix&nbsp;matrix2,&nbsp;float&nbsp;amount,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|static&nbsp;[`void&nbsp;SlerpScale(ref&nbsp;Matrix&nbsp;matrix1,&nbsp;ref&nbsp;Matrix&nbsp;matrix2,&nbsp;float&nbsp;amount,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static&nbsp;[`void&nbsp;Slerp(Matrix&nbsp;matrix1,&nbsp;Matrix&nbsp;matrix2,&nbsp;float&nbsp;amount,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|static&nbsp;[`Matrix&nbsp;Slerp(Matrix&nbsp;matrix1,&nbsp;Matrix&nbsp;matrix2,&nbsp;float&nbsp;amount)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|static&nbsp;[`void&nbsp;SlerpScale(Matrix&nbsp;matrix1,&nbsp;Matrix&nbsp;matrix2,&nbsp;float&nbsp;amount,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static&nbsp;[`Matrix&nbsp;SlerpScale(Matrix&nbsp;matrix1,&nbsp;Matrix&nbsp;matrix2,&nbsp;float&nbsp;amount)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static&nbsp;[`Matrix&nbsp;Negate(Matrix&nbsp;matrix)`](VRageMath.Negate)|Negates individual elements of a matrix.|
|static&nbsp;[`void&nbsp;Negate(ref&nbsp;Matrix&nbsp;matrix,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.Negate)|Negates individual elements of a matrix.|
|static&nbsp;[`Matrix&nbsp;Add(Matrix&nbsp;matrix1,&nbsp;Matrix&nbsp;matrix2)`](VRageMath.Add)|Adds a matrix to another matrix.|
|static&nbsp;[`void&nbsp;Add(ref&nbsp;Matrix&nbsp;matrix1,&nbsp;ref&nbsp;Matrix&nbsp;matrix2,&nbsp;ref&nbsp;Matrix&nbsp;result)`](VRageMath.Add)|Adds a matrix to another matrix.|
|static&nbsp;[`Matrix&nbsp;Subtract(Matrix&nbsp;matrix1,&nbsp;Matrix&nbsp;matrix2)`](VRageMath.Subtract)|Subtracts matrices.|
