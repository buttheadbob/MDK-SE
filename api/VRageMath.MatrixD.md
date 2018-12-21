← [Index](Api-Index)
# MatrixD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a matrix.
### Fields
|Member|Description|
|---|---|
|[`M11`](VRageMath.M11)|Value at row 1 column 1 of the matrix.|
|[`M12`](VRageMath.M12)|Value at row 1 column 2 of the matrix.|
|[`M13`](VRageMath.M13)|Value at row 1 column 3 of the matrix.|
|[`M14`](VRageMath.M14)|Value at row 1 column 4 of the matrix.|
|[`M21`](VRageMath.M21)|Value at row 2 column 1 of the matrix.|
|[`M22`](VRageMath.M22)|Value at row 2 column 2 of the matrix.|
|[`M23`](VRageMath.M23)|Value at row 2 column 3 of the matrix.|
|[`M24`](VRageMath.M24)|Value at row 2 column 4 of the matrix.|
|[`M31`](VRageMath.M31)|Value at row 3 column 1 of the matrix.|
|[`M32`](VRageMath.M32)|Value at row 3 column 2 of the matrix.|
|[`M33`](VRageMath.M33)|Value at row 3 column 3 of the matrix.|
|[`M34`](VRageMath.M34)|Value at row 3 column 4 of the matrix.|
|[`M41`](VRageMath.M41)|Value at row 4 column 1 of the matrix.|
|[`M42`](VRageMath.M42)|Value at row 4 column 2 of the matrix.|
|[`M43`](VRageMath.M43)|Value at row 4 column 3 of the matrix.|
|[`M44`](VRageMath.M44)|Value at row 4 column 4 of the matrix.|
|[`Identity`](VRageMath.Identity)||
|[`Zero`](VRageMath.Zero)||
### Properties
|Member|Description|
|---|---|
|[`Col0`](VRageMath.Col0)||
|[`Col1`](VRageMath.Col1)||
|[`Col2`](VRageMath.Col2)||
|[`Up`](VRageMath.Up)|Gets and sets the up vector of the Matrix.|
|[`Down`](VRageMath.Down)|Gets and sets the down vector of the Matrix.|
|[`Right`](VRageMath.Right)|Gets and sets the right vector of the Matrix.|
|[`Left`](VRageMath.Left)|Gets and sets the left vector of the Matrix.|
|[`Forward`](VRageMath.Forward)|Gets and sets the forward vector of the Matrix.|
|[`Backward`](VRageMath.Backward)|Gets and sets the backward vector of the Matrix.|
|[`Scale`](VRageMath.Scale)||
|[`Translation`](VRageMath.Translation)|Gets and sets the translation vector of the Matrix.|
|[`Rotation`](VRageMath.Rotation)||
|[`Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|[`Subtract(Matrix, Matrix)`](VRageMath.Subtract)|Subtracts matrices.|
|[`Subtract(ref MatrixD, ref MatrixD, ref MatrixD)`](VRageMath.Subtract)|Subtracts matrices.|
|[`Multiply(MatrixD, MatrixD)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|[`Multiply(MatrixD, Matrix)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|[`Multiply(ref MatrixD, ref Matrix, ref MatrixD)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|[`Multiply(ref Matrix, ref MatrixD, ref MatrixD)`](VRageMath.Multiply)||
|[`Multiply(ref MatrixD, ref MatrixD, ref MatrixD)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|[`Multiply(MatrixD, double)`](VRageMath.Multiply)|Multiplies a matrix by a scalar value.|
|[`Multiply(ref MatrixD, double, ref MatrixD)`](VRageMath.Multiply)|Multiplies a matrix by a scalar value.|
|[`Divide(MatrixD, MatrixD)`](VRageMath.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|[`Divide(ref MatrixD, ref MatrixD, ref MatrixD)`](VRageMath.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|[`Divide(MatrixD, double)`](VRageMath.Divide)|Divides the components of a matrix by a scalar.|
|[`Divide(ref MatrixD, double, ref MatrixD)`](VRageMath.Divide)|Divides the components of a matrix by a scalar.|
|[`GetOrientation()`](VRageMath.GetOrientation)|Gets the orientation.|
|[`AssertIsValid()`](VRageMath.AssertIsValid)||
|[`IsValid()`](VRageMath.IsValid)||
|[`IsNan()`](VRageMath.IsNan)||
|[`IsRotation()`](VRageMath.IsRotation)||
|[`HasNoTranslationOrPerspective()`](VRageMath.HasNoTranslationOrPerspective)|Returns true if this matrix represents invertible (you can call Invert on it) linear (it does not contain translation or perspective transformation) transformation. Such matrix consist solely of rotations, shearing, mirroring and scaling. It can be orthogonalized to create an orthogonal rotation matrix.|
|[`CreateFromDir(Vector3D)`](VRageMath.CreateFromDir)||
|[`CreateFromDir(Vector3D, Vector3D)`](VRageMath.CreateFromDir)||
|[`Normalize(MatrixD)`](VRageMath.Normalize)||
|[`Orthogonalize()`](VRageMath.Orthogonalize)||
|[`Orthogonalize(MatrixD)`](VRageMath.Orthogonalize)||
|[`AlignRotationToAxes(ref MatrixD, ref MatrixD)`](VRageMath.AlignRotationToAxes)||
|[`GetEulerAnglesXYZ(ref MatrixD, ref Vector3D)`](VRageMath.GetEulerAnglesXYZ)||
|[`SwapYZCoordinates(MatrixD)`](VRageMath.SwapYZCoordinates)||
|[`IsMirrored()`](VRageMath.IsMirrored)||
|[`GetDirectionVector(Direction)`](VRageMath.GetDirectionVector)||
|[`SetDirectionVector(Direction, Vector3D)`](VRageMath.SetDirectionVector)||
|[`GetClosestDirection(Vector3D)`](VRageMath.GetClosestDirection)||
|[`GetClosestDirection(ref Vector3D)`](VRageMath.GetClosestDirection)||
|[`Rescale(ref MatrixD, double)`](VRageMath.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|[`Rescale(ref MatrixD, float)`](VRageMath.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|[`Rescale(ref MatrixD, ref Vector3D)`](VRageMath.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|[`Rescale(MatrixD, double)`](VRageMath.Rescale)||
|[`Rescale(MatrixD, Vector3D)`](VRageMath.Rescale)||
|[`CreateBillboard(Vector3D, Vector3D, Vector3D, Nullable<Vector3D>)`](VRageMath.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|[`CreateBillboard(ref Vector3D, ref Vector3D, ref Vector3D, Nullable<Vector3D>, ref MatrixD)`](VRageMath.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|[`CreateConstrainedBillboard(Vector3D, Vector3D, Vector3D, Nullable<Vector3D>, Nullable<Vector3D>)`](VRageMath.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|[`CreateConstrainedBillboard(ref Vector3D, ref Vector3D, ref Vector3D, Nullable<Vector3D>, Nullable<Vector3D>, ref MatrixD)`](VRageMath.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|[`CreateTranslation(Vector3D)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|[`CreateTranslation(Vector3)`](VRageMath.CreateTranslation)||
|[`CreateTranslation(ref Vector3D, ref MatrixD)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|[`CreateTranslation(double, double, double)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|[`CreateTranslation(double, double, double, ref MatrixD)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|[`CreateScale(double, double, double)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|[`CreateScale(double, double, double, ref MatrixD)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|[`CreateScale(Vector3D)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|[`CreateScale(ref Vector3D, ref MatrixD)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|[`CreateScale(double)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|[`CreateScale(double, ref MatrixD)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|[`CreateRotationX(double)`](VRageMath.CreateRotationX)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|[`CreateRotationX(double, ref MatrixD)`](VRageMath.CreateRotationX)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the x-axis.|
|[`CreateRotationY(double)`](VRageMath.CreateRotationY)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|[`CreateRotationY(double, ref MatrixD)`](VRageMath.CreateRotationY)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the y-axis.|
|[`CreateRotationZ(double)`](VRageMath.CreateRotationZ)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|[`CreateRotationZ(double, ref MatrixD)`](VRageMath.CreateRotationZ)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the z-axis.|
|[`CreateFromAxisAngle(Vector3D, double)`](VRageMath.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|[`CreateFromAxisAngle(ref Vector3D, double, ref MatrixD)`](VRageMath.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|[`CreatePerspectiveFieldOfView(double, double, double, double)`](VRageMath.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by value.|
|[`CreatePerspectiveFieldOfView(double, double, double, double, ref MatrixD)`](VRageMath.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by reference.|
|[`CreatePerspective(double, double, double, double)`](VRageMath.CreatePerspective)|Builds a perspective projection matrix and returns the result by value.|
|[`CreatePerspective(double, double, double, double, ref MatrixD)`](VRageMath.CreatePerspective)|Builds a perspective projection matrix and returns the result by reference.|
|[`CreatePerspectiveOffCenter(double, double, double, double, double, double)`](VRageMath.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|[`CreatePerspectiveOffCenter(double, double, double, double, double, double, ref MatrixD)`](VRageMath.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|[`CreateOrthographic(double, double, double, double)`](VRageMath.CreateOrthographic)|Builds an orthogonal projection matrix.|
|[`CreateOrthographic(double, double, double, double, ref MatrixD)`](VRageMath.CreateOrthographic)|Builds an orthogonal projection matrix.|
|[`CreateOrthographicOffCenter(double, double, double, double, double, double)`](VRageMath.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|[`CreateOrthographicOffCenter(double, double, double, double, double, double, ref MatrixD)`](VRageMath.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|[`CreateLookAt(Vector3D, Vector3D, Vector3)`](VRageMath.CreateLookAt)||
|[`CreateLookAt(Vector3D, Vector3D, Vector3D)`](VRageMath.CreateLookAt)|Creates a view matrix.|
|[`CreateLookAtInverse(Vector3D, Vector3D, Vector3D)`](VRageMath.CreateLookAtInverse)||
|[`CreateLookAt(ref Vector3D, ref Vector3D, ref Vector3D, ref MatrixD)`](VRageMath.CreateLookAt)|Creates a view matrix.|
|[`CreateWorld(Vector3D, Vector3, Vector3)`](VRageMath.CreateWorld)||
|[`CreateWorld(Vector3D)`](VRageMath.CreateWorld)||
|[`CreateWorld(Vector3D, Vector3D, Vector3D)`](VRageMath.CreateWorld)|Creates a world matrix with the specified parameters.|
|[`CreateWorld(ref Vector3D, ref Vector3D, ref Vector3D, ref MatrixD)`](VRageMath.CreateWorld)|Creates a world matrix with the specified parameters.|
|[`CreateFromQuaternion(Quaternion)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|[`CreateFromQuaternion(QuaternionD)`](VRageMath.CreateFromQuaternion)||
|[`CreateFromQuaternion(ref Quaternion, ref MatrixD)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|[`CreateFromYawPitchRoll(double, double, double)`](VRageMath.CreateFromYawPitchRoll)|Creates a new rotation matrix from a specified yaw, pitch, and roll.|
|[`CreateFromYawPitchRoll(double, double, double, ref MatrixD)`](VRageMath.CreateFromYawPitchRoll)|Fills in a rotation matrix from a specified yaw, pitch, and roll.|
|[`CreateFromTransformScale(Quaternion, Vector3D, Vector3D)`](VRageMath.CreateFromTransformScale)||
|[`CreateShadow(Vector3D, Plane)`](VRageMath.CreateShadow)|Creates a Matrix that flattens geometry into a specified Plane as if casting a shadow from a specified light source.|
|[`CreateShadow(ref Vector3D, ref Plane, ref MatrixD)`](VRageMath.CreateShadow)|Fills in a Matrix to flatten geometry into a specified Plane as if casting a shadow from a specified light source.|
|[`CreateReflection(Plane)`](VRageMath.CreateReflection)|Creates a Matrix that reflects the coordinate system about a specified Plane.|
|[`CreateReflection(ref Plane, ref MatrixD)`](VRageMath.CreateReflection)|Fills in an existing Matrix so that it reflects the coordinate system about a specified Plane.|
|[`Transform(MatrixD, Quaternion)`](VRageMath.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|[`Transform(ref MatrixD, ref Quaternion, ref MatrixD)`](VRageMath.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|[`GetRow(int)`](VRageMath.GetRow)||
|[`SetRow(int, Vector4)`](VRageMath.SetRow)||
|[`ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`Equals(MatrixD)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Matrix.|
|[`EqualsFast(ref MatrixD, double)`](VRageMath.EqualsFast)|Compares just position, forward and up|
|[`Equals(Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of this object.|
|[`Transpose(MatrixD)`](VRageMath.Transpose)|Transposes the rows and columns of a matrix.|
|[`Transpose(ref MatrixD, ref MatrixD)`](VRageMath.Transpose)|Transposes the rows and columns of a matrix.|
|[`Determinant()`](VRageMath.Determinant)|Calculates the determinant of the matrix.|
|[`Invert(MatrixD)`](VRageMath.Invert)|Calculates the inverse of a matrix.|
|[`Invert(ref MatrixD)`](VRageMath.Invert)||
|[`Invert(ref MatrixD, ref MatrixD)`](VRageMath.Invert)|Calculates the inverse of a matrix.|
|[`Lerp(MatrixD, MatrixD, double)`](VRageMath.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|[`Lerp(ref MatrixD, ref MatrixD, double, ref MatrixD)`](VRageMath.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|[`Slerp(ref MatrixD, ref MatrixD, float, ref MatrixD)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|[`IsOrthogonal()`](VRageMath.IsOrthogonal)||
|[`IsOrthogonal(double)`](VRageMath.IsOrthogonal)||
|[`SlerpScale(ref MatrixD, ref MatrixD, float, ref MatrixD)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|[`Slerp(MatrixD, MatrixD, float, ref MatrixD)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|[`Slerp(MatrixD, MatrixD, float)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|[`SlerpScale(MatrixD, MatrixD, float, ref MatrixD)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|[`SlerpScale(MatrixD, MatrixD, float)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|[`Negate(MatrixD)`](VRageMath.Negate)|Negates individual elements of a matrix.|
|[`Negate(ref MatrixD, ref MatrixD)`](VRageMath.Negate)|Negates individual elements of a matrix.|
|[`Add(MatrixD, MatrixD)`](VRageMath.Add)|Adds a matrix to another matrix.|
|[`Add(ref MatrixD, ref MatrixD, ref MatrixD)`](VRageMath.Add)|Adds a matrix to another matrix.|
