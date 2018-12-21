← [Index](index)
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
|static [`Identity`](VRageMath.Identity)||
|static [`Zero`](VRageMath.Zero)||
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
|static [`Subtract(Matrix, Matrix)`](VRageMath.Subtract)|Subtracts matrices.|
|static [`Subtract(ref MatrixD, ref MatrixD, ref MatrixD)`](VRageMath.Subtract)|Subtracts matrices.|
|static [`Multiply(MatrixD, MatrixD)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static [`Multiply(MatrixD, Matrix)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static [`Multiply(ref MatrixD, ref Matrix, ref MatrixD)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static [`Multiply(ref Matrix, ref MatrixD, ref MatrixD)`](VRageMath.Multiply)||
|static [`Multiply(ref MatrixD, ref MatrixD, ref MatrixD)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static [`Multiply(MatrixD, double)`](VRageMath.Multiply)|Multiplies a matrix by a scalar value.|
|static [`Multiply(ref MatrixD, double, ref MatrixD)`](VRageMath.Multiply)|Multiplies a matrix by a scalar value.|
|static [`Divide(MatrixD, MatrixD)`](VRageMath.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|static [`Divide(ref MatrixD, ref MatrixD, ref MatrixD)`](VRageMath.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|static [`Divide(MatrixD, double)`](VRageMath.Divide)|Divides the components of a matrix by a scalar.|
|static [`Divide(ref MatrixD, double, ref MatrixD)`](VRageMath.Divide)|Divides the components of a matrix by a scalar.|
|[`GetOrientation()`](VRageMath.GetOrientation)|Gets the orientation.|
|[`AssertIsValid()`](VRageMath.AssertIsValid)||
|[`IsValid()`](VRageMath.IsValid)||
|[`IsNan()`](VRageMath.IsNan)||
|[`IsRotation()`](VRageMath.IsRotation)||
|[`HasNoTranslationOrPerspective()`](VRageMath.HasNoTranslationOrPerspective)|Returns true if this matrix represents invertible (you can call Invert on it) linear (it does not contain translation or perspective transformation) transformation. Such matrix consist solely of rotations, shearing, mirroring and scaling. It can be orthogonalized to create an orthogonal rotation matrix.|
|static [`CreateFromDir(Vector3D)`](VRageMath.CreateFromDir)||
|static [`CreateFromDir(Vector3D, Vector3D)`](VRageMath.CreateFromDir)||
|static [`Normalize(MatrixD)`](VRageMath.Normalize)||
|[`Orthogonalize()`](VRageMath.Orthogonalize)||
|static [`Orthogonalize(MatrixD)`](VRageMath.Orthogonalize)||
|static [`AlignRotationToAxes(ref MatrixD, ref MatrixD)`](VRageMath.AlignRotationToAxes)||
|static [`GetEulerAnglesXYZ(ref MatrixD, ref Vector3D)`](VRageMath.GetEulerAnglesXYZ)||
|static [`SwapYZCoordinates(MatrixD)`](VRageMath.SwapYZCoordinates)||
|[`IsMirrored()`](VRageMath.IsMirrored)||
|[`GetDirectionVector(Direction)`](VRageMath.GetDirectionVector)||
|[`SetDirectionVector(Direction, Vector3D)`](VRageMath.SetDirectionVector)||
|[`GetClosestDirection(Vector3D)`](VRageMath.GetClosestDirection)||
|[`GetClosestDirection(ref Vector3D)`](VRageMath.GetClosestDirection)||
|static [`Rescale(ref MatrixD, double)`](VRageMath.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|static [`Rescale(ref MatrixD, float)`](VRageMath.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|static [`Rescale(ref MatrixD, ref Vector3D)`](VRageMath.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|static [`Rescale(MatrixD, double)`](VRageMath.Rescale)||
|static [`Rescale(MatrixD, Vector3D)`](VRageMath.Rescale)||
|static [`CreateBillboard(Vector3D, Vector3D, Vector3D, Nullable<Vector3D>)`](VRageMath.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|static [`CreateBillboard(ref Vector3D, ref Vector3D, ref Vector3D, Nullable<Vector3D>, ref MatrixD)`](VRageMath.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|static [`CreateConstrainedBillboard(Vector3D, Vector3D, Vector3D, Nullable<Vector3D>, Nullable<Vector3D>)`](VRageMath.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|static [`CreateConstrainedBillboard(ref Vector3D, ref Vector3D, ref Vector3D, Nullable<Vector3D>, Nullable<Vector3D>, ref MatrixD)`](VRageMath.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|static [`CreateTranslation(Vector3D)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static [`CreateTranslation(Vector3)`](VRageMath.CreateTranslation)||
|static [`CreateTranslation(ref Vector3D, ref MatrixD)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static [`CreateTranslation(double, double, double)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static [`CreateTranslation(double, double, double, ref MatrixD)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static [`CreateScale(double, double, double)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`CreateScale(double, double, double, ref MatrixD)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`CreateScale(Vector3D)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`CreateScale(ref Vector3D, ref MatrixD)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`CreateScale(double)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`CreateScale(double, ref MatrixD)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`CreateRotationX(double)`](VRageMath.CreateRotationX)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|static [`CreateRotationX(double, ref MatrixD)`](VRageMath.CreateRotationX)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the x-axis.|
|static [`CreateRotationY(double)`](VRageMath.CreateRotationY)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|static [`CreateRotationY(double, ref MatrixD)`](VRageMath.CreateRotationY)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the y-axis.|
|static [`CreateRotationZ(double)`](VRageMath.CreateRotationZ)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|static [`CreateRotationZ(double, ref MatrixD)`](VRageMath.CreateRotationZ)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the z-axis.|
|static [`CreateFromAxisAngle(Vector3D, double)`](VRageMath.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|static [`CreateFromAxisAngle(ref Vector3D, double, ref MatrixD)`](VRageMath.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|static [`CreatePerspectiveFieldOfView(double, double, double, double)`](VRageMath.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by value.|
|static [`CreatePerspectiveFieldOfView(double, double, double, double, ref MatrixD)`](VRageMath.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by reference.|
|static [`CreatePerspective(double, double, double, double)`](VRageMath.CreatePerspective)|Builds a perspective projection matrix and returns the result by value.|
|static [`CreatePerspective(double, double, double, double, ref MatrixD)`](VRageMath.CreatePerspective)|Builds a perspective projection matrix and returns the result by reference.|
|static [`CreatePerspectiveOffCenter(double, double, double, double, double, double)`](VRageMath.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|static [`CreatePerspectiveOffCenter(double, double, double, double, double, double, ref MatrixD)`](VRageMath.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|static [`CreateOrthographic(double, double, double, double)`](VRageMath.CreateOrthographic)|Builds an orthogonal projection matrix.|
|static [`CreateOrthographic(double, double, double, double, ref MatrixD)`](VRageMath.CreateOrthographic)|Builds an orthogonal projection matrix.|
|static [`CreateOrthographicOffCenter(double, double, double, double, double, double)`](VRageMath.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|static [`CreateOrthographicOffCenter(double, double, double, double, double, double, ref MatrixD)`](VRageMath.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|static [`CreateLookAt(Vector3D, Vector3D, Vector3)`](VRageMath.CreateLookAt)||
|static [`CreateLookAt(Vector3D, Vector3D, Vector3D)`](VRageMath.CreateLookAt)|Creates a view matrix.|
|static [`CreateLookAtInverse(Vector3D, Vector3D, Vector3D)`](VRageMath.CreateLookAtInverse)||
|static [`CreateLookAt(ref Vector3D, ref Vector3D, ref Vector3D, ref MatrixD)`](VRageMath.CreateLookAt)|Creates a view matrix.|
|static [`CreateWorld(Vector3D, Vector3, Vector3)`](VRageMath.CreateWorld)||
|static [`CreateWorld(Vector3D)`](VRageMath.CreateWorld)||
|static [`CreateWorld(Vector3D, Vector3D, Vector3D)`](VRageMath.CreateWorld)|Creates a world matrix with the specified parameters.|
|static [`CreateWorld(ref Vector3D, ref Vector3D, ref Vector3D, ref MatrixD)`](VRageMath.CreateWorld)|Creates a world matrix with the specified parameters.|
|static [`CreateFromQuaternion(Quaternion)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|static [`CreateFromQuaternion(QuaternionD)`](VRageMath.CreateFromQuaternion)||
|static [`CreateFromQuaternion(ref Quaternion, ref MatrixD)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|static [`CreateFromYawPitchRoll(double, double, double)`](VRageMath.CreateFromYawPitchRoll)|Creates a new rotation matrix from a specified yaw, pitch, and roll.|
|static [`CreateFromYawPitchRoll(double, double, double, ref MatrixD)`](VRageMath.CreateFromYawPitchRoll)|Fills in a rotation matrix from a specified yaw, pitch, and roll.|
|static [`CreateFromTransformScale(Quaternion, Vector3D, Vector3D)`](VRageMath.CreateFromTransformScale)||
|static [`CreateShadow(Vector3D, Plane)`](VRageMath.CreateShadow)|Creates a Matrix that flattens geometry into a specified Plane as if casting a shadow from a specified light source.|
|static [`CreateShadow(ref Vector3D, ref Plane, ref MatrixD)`](VRageMath.CreateShadow)|Fills in a Matrix to flatten geometry into a specified Plane as if casting a shadow from a specified light source.|
|static [`CreateReflection(Plane)`](VRageMath.CreateReflection)|Creates a Matrix that reflects the coordinate system about a specified Plane.|
|static [`CreateReflection(ref Plane, ref MatrixD)`](VRageMath.CreateReflection)|Fills in an existing Matrix so that it reflects the coordinate system about a specified Plane.|
|static [`Transform(MatrixD, Quaternion)`](VRageMath.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|static [`Transform(ref MatrixD, ref Quaternion, ref MatrixD)`](VRageMath.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|[`GetRow(int)`](VRageMath.GetRow)||
|[`SetRow(int, Vector4)`](VRageMath.SetRow)||
|[`ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`Equals(MatrixD)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Matrix.|
|[`EqualsFast(ref MatrixD, double)`](VRageMath.EqualsFast)|Compares just position, forward and up|
|[`Equals(Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of this object.|
|static [`Transpose(MatrixD)`](VRageMath.Transpose)|Transposes the rows and columns of a matrix.|
|static [`Transpose(ref MatrixD, ref MatrixD)`](VRageMath.Transpose)|Transposes the rows and columns of a matrix.|
|[`Determinant()`](VRageMath.Determinant)|Calculates the determinant of the matrix.|
|static [`Invert(MatrixD)`](VRageMath.Invert)|Calculates the inverse of a matrix.|
|static [`Invert(ref MatrixD)`](VRageMath.Invert)||
|static [`Invert(ref MatrixD, ref MatrixD)`](VRageMath.Invert)|Calculates the inverse of a matrix.|
|static [`Lerp(MatrixD, MatrixD, double)`](VRageMath.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|static [`Lerp(ref MatrixD, ref MatrixD, double, ref MatrixD)`](VRageMath.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|static [`Slerp(ref MatrixD, ref MatrixD, float, ref MatrixD)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|[`IsOrthogonal()`](VRageMath.IsOrthogonal)||
|[`IsOrthogonal(double)`](VRageMath.IsOrthogonal)||
|static [`SlerpScale(ref MatrixD, ref MatrixD, float, ref MatrixD)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static [`Slerp(MatrixD, MatrixD, float, ref MatrixD)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|static [`Slerp(MatrixD, MatrixD, float)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|static [`SlerpScale(MatrixD, MatrixD, float, ref MatrixD)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static [`SlerpScale(MatrixD, MatrixD, float)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static [`Negate(MatrixD)`](VRageMath.Negate)|Negates individual elements of a matrix.|
|static [`Negate(ref MatrixD, ref MatrixD)`](VRageMath.Negate)|Negates individual elements of a matrix.|
|static [`Add(MatrixD, MatrixD)`](VRageMath.Add)|Adds a matrix to another matrix.|
|static [`Add(ref MatrixD, ref MatrixD, ref MatrixD)`](VRageMath.Add)|Adds a matrix to another matrix.|
