← [Index](index)
# Matrix Struct
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
|[`Up`](VRageMath.Up)|Gets and sets the up vector of the Matrix.|
|[`Down`](VRageMath.Down)|Gets and sets the down vector of the Matrix.|
|[`Right`](VRageMath.Right)|Gets and sets the right vector of the Matrix.|
|[`Col0`](VRageMath.Col0)||
|[`Col1`](VRageMath.Col1)||
|[`Col2`](VRageMath.Col2)||
|[`Left`](VRageMath.Left)|Gets and sets the left vector of the Matrix.|
|[`Forward`](VRageMath.Forward)|Gets and sets the forward vector of the Matrix.|
|[`Backward`](VRageMath.Backward)|Gets and sets the backward vector of the Matrix.|
|[`Scale`](VRageMath.Scale)||
|[`Translation`](VRageMath.Translation)|Gets and sets the translation vector of the Matrix.|
|[`Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|static [`Subtract(ref Matrix, ref Matrix, ref Matrix)`](VRageMath.Subtract)|Subtracts matrices.|
|static [`Multiply(Matrix, Matrix)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static [`Multiply(ref Matrix, ref Matrix, ref Matrix)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static [`MultiplyRotation(ref Matrix, ref Matrix, ref Matrix)`](VRageMath.MultiplyRotation)|Multiplies a matrix by another matrix, only rotation parts.|
|static [`Multiply(Matrix, float)`](VRageMath.Multiply)|Multiplies a matrix by a scalar value.|
|static [`Multiply(ref Matrix, float, ref Matrix)`](VRageMath.Multiply)|Multiplies a matrix by a scalar value.|
|static [`Divide(Matrix, Matrix)`](VRageMath.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|static [`Divide(ref Matrix, ref Matrix, ref Matrix)`](VRageMath.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|static [`Divide(Matrix, float)`](VRageMath.Divide)|Divides the components of a matrix by a scalar.|
|static [`Divide(ref Matrix, float, ref Matrix)`](VRageMath.Divide)|Divides the components of a matrix by a scalar.|
|[`GetOrientation()`](VRageMath.GetOrientation)|Gets the orientation.|
|[`AssertIsValid()`](VRageMath.AssertIsValid)||
|[`IsValid()`](VRageMath.IsValid)||
|[`IsNan()`](VRageMath.IsNan)||
|[`IsRotation()`](VRageMath.IsRotation)||
|[`HasNoTranslationOrPerspective()`](VRageMath.HasNoTranslationOrPerspective)|Returns true if this matrix represents invertible (you can call Invert on it) linear (it does not contain translation or perspective transformation) transformation. Such matrix consist solely of rotations, shearing, mirroring and scaling. It can be orthogonalized to create an orthogonal rotation matrix.|
|static [`CreateFromDir(Vector3)`](VRageMath.CreateFromDir)||
|static [`CreateFromDir(Vector3, Vector3)`](VRageMath.CreateFromDir)||
|static [`Normalize(Matrix)`](VRageMath.Normalize)||
|static [`Orthogonalize(Matrix)`](VRageMath.Orthogonalize)||
|static [`Round(ref Matrix)`](VRageMath.Round)||
|static [`AlignRotationToAxes(ref Matrix, ref Matrix)`](VRageMath.AlignRotationToAxes)||
|static [`GetEulerAnglesXYZ(ref Matrix, ref Vector3)`](VRageMath.GetEulerAnglesXYZ)||
|static [`SwapYZCoordinates(Matrix)`](VRageMath.SwapYZCoordinates)||
|[`IsMirrored()`](VRageMath.IsMirrored)||
|[`IsOrthogonal()`](VRageMath.IsOrthogonal)||
|[`GetDirectionVector(Direction)`](VRageMath.GetDirectionVector)||
|[`SetDirectionVector(Direction, Vector3)`](VRageMath.SetDirectionVector)||
|[`GetClosestDirection(Vector3)`](VRageMath.GetClosestDirection)||
|[`GetClosestDirection(ref Vector3)`](VRageMath.GetClosestDirection)||
|static [`Rescale(ref Matrix, float)`](VRageMath.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|static [`Rescale(ref Matrix, ref Vector3)`](VRageMath.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|static [`Rescale(Matrix, float)`](VRageMath.Rescale)||
|static [`Rescale(Matrix, Vector3)`](VRageMath.Rescale)||
|static [`CreateBillboard(Vector3, Vector3, Vector3, Nullable<Vector3>)`](VRageMath.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|static [`CreateBillboard(ref Vector3, ref Vector3, ref Vector3, Nullable<Vector3>, ref Matrix)`](VRageMath.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|static [`CreateConstrainedBillboard(Vector3, Vector3, Vector3, Nullable<Vector3>, Nullable<Vector3>)`](VRageMath.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|static [`CreateConstrainedBillboard(ref Vector3, ref Vector3, ref Vector3, Nullable<Vector3>, Nullable<Vector3>, ref Matrix)`](VRageMath.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|static [`CreateTranslation(Vector3)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static [`CreateTranslation(ref Vector3, ref Matrix)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static [`CreateTranslation(float, float, float)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static [`CreateTranslation(float, float, float, ref Matrix)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static [`CreateScale(float, float, float)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`CreateScale(float, float, float, ref Matrix)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`CreateScale(Vector3)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`CreateScale(ref Vector3, ref Matrix)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`CreateScale(float)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`CreateScale(float, ref Matrix)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`CreateRotationX(float)`](VRageMath.CreateRotationX)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|static [`CreateRotationX(float, ref Matrix)`](VRageMath.CreateRotationX)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the x-axis.|
|static [`CreateRotationY(float)`](VRageMath.CreateRotationY)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|static [`CreateRotationY(float, ref Matrix)`](VRageMath.CreateRotationY)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the y-axis.|
|static [`CreateRotationZ(float)`](VRageMath.CreateRotationZ)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|static [`CreateRotationZ(float, ref Matrix)`](VRageMath.CreateRotationZ)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the z-axis.|
|static [`CreateFromAxisAngle(Vector3, float)`](VRageMath.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|static [`CreateFromAxisAngle(ref Vector3, float, ref Matrix)`](VRageMath.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|static [`CreateRotationFromTwoVectors(ref Vector3, ref Vector3, ref Matrix)`](VRageMath.CreateRotationFromTwoVectors)||
|static [`CreatePerspectiveFieldOfView(float, float, float, float)`](VRageMath.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by value.|
|static [`CreatePerspectiveFovRhComplementary(float, float, float, float)`](VRageMath.CreatePerspectiveFovRhComplementary)||
|static [`CreatePerspectiveFovRhInfinite(float, float, float)`](VRageMath.CreatePerspectiveFovRhInfinite)||
|static [`CreatePerspectiveFovRhInfiniteComplementary(float, float, float)`](VRageMath.CreatePerspectiveFovRhInfiniteComplementary)||
|static [`CreatePerspectiveFovRhInverse(float, float, float, float)`](VRageMath.CreatePerspectiveFovRhInverse)||
|static [`CreatePerspectiveFovRhInfiniteInverse(float, float, float)`](VRageMath.CreatePerspectiveFovRhInfiniteInverse)||
|static [`CreatePerspectiveFovRhInfiniteComplementaryInverse(float, float, float)`](VRageMath.CreatePerspectiveFovRhInfiniteComplementaryInverse)||
|static [`CreateFromPerspectiveFieldOfView(ref Matrix, float, float)`](VRageMath.CreateFromPerspectiveFieldOfView)||
|static [`CreatePerspectiveFieldOfView(float, float, float, float, ref Matrix)`](VRageMath.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by reference.|
|static [`CreatePerspective(float, float, float, float)`](VRageMath.CreatePerspective)|Builds a perspective projection matrix and returns the result by value.|
|static [`CreatePerspective(float, float, float, float, ref Matrix)`](VRageMath.CreatePerspective)|Builds a perspective projection matrix and returns the result by reference.|
|static [`CreatePerspectiveOffCenter(float, float, float, float, float, float)`](VRageMath.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|static [`CreatePerspectiveOffCenter(float, float, float, float, float, float, ref Matrix)`](VRageMath.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|static [`CreateOrthographic(float, float, float, float)`](VRageMath.CreateOrthographic)|Builds an orthogonal projection matrix.|
|static [`CreateOrthographic(float, float, float, float, ref Matrix)`](VRageMath.CreateOrthographic)|Builds an orthogonal projection matrix.|
|static [`CreateOrthographicOffCenter(float, float, float, float, float, float)`](VRageMath.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|static [`CreateOrthographicOffCenter(float, float, float, float, float, float, ref Matrix)`](VRageMath.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|static [`CreateLookAt(Vector3, Vector3, Vector3)`](VRageMath.CreateLookAt)|Creates a view matrix.|
|static [`CreateLookAtInverse(Vector3, Vector3, Vector3)`](VRageMath.CreateLookAtInverse)||
|static [`CreateLookAt(ref Vector3, ref Vector3, ref Vector3, ref Matrix)`](VRageMath.CreateLookAt)|Creates a view matrix.|
|static [`CreateWorld(Vector3)`](VRageMath.CreateWorld)||
|static [`CreateWorld(Vector3, Vector3, Vector3)`](VRageMath.CreateWorld)|Creates a world matrix with the specified parameters.|
|static [`CreateWorld(ref Vector3, ref Vector3, ref Vector3, ref Matrix)`](VRageMath.CreateWorld)|Creates a world matrix with the specified parameters.|
|static [`CreateFromQuaternion(Quaternion)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|static [`CreateFromQuaternion(ref Quaternion, ref Matrix)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|static [`CreateFromYawPitchRoll(float, float, float)`](VRageMath.CreateFromYawPitchRoll)|Creates a new rotation matrix from a specified yaw, pitch, and roll.|
|static [`CreateFromYawPitchRoll(float, float, float, ref Matrix)`](VRageMath.CreateFromYawPitchRoll)|Fills in a rotation matrix from a specified yaw, pitch, and roll.|
|static [`CreateFromTransformScale(Quaternion, Vector3, Vector3)`](VRageMath.CreateFromTransformScale)||
|static [`CreateShadow(Vector3, Plane)`](VRageMath.CreateShadow)|Creates a Matrix that flattens geometry into a specified Plane as if casting a shadow from a specified light source.|
|static [`CreateShadow(ref Vector3, ref Plane, ref Matrix)`](VRageMath.CreateShadow)|Fills in a Matrix to flatten geometry into a specified Plane as if casting a shadow from a specified light source.|
|static [`CreateReflection(Plane)`](VRageMath.CreateReflection)|Creates a Matrix that reflects the coordinate system about a specified Plane.|
|static [`CreateReflection(ref Plane, ref Matrix)`](VRageMath.CreateReflection)|Fills in an existing Matrix so that it reflects the coordinate system about a specified Plane.|
|static [`Transform(Matrix, Quaternion)`](VRageMath.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|static [`Transform(ref Matrix, ref Quaternion, ref Matrix)`](VRageMath.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|[`GetRow(int)`](VRageMath.GetRow)||
|[`SetRow(int, Vector4)`](VRageMath.SetRow)||
|[`ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`Equals(Matrix)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Matrix.|
|[`EqualsFast(ref Matrix, float)`](VRageMath.EqualsFast)|Compares just position, forward and up|
|[`Equals(Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of this object.|
|static [`Transpose(Matrix)`](VRageMath.Transpose)|Transposes the rows and columns of a matrix.|
|static [`Transpose(ref Matrix, ref Matrix)`](VRageMath.Transpose)|Transposes the rows and columns of a matrix.|
|[`TransposeRotationInPlace()`](VRageMath.TransposeRotationInPlace)|Transposes the rows and columns of a matrix that is assumed to be rotation only in place.|
|[`Determinant()`](VRageMath.Determinant)|Calculates the determinant of the matrix.|
|static [`Invert(Matrix)`](VRageMath.Invert)|Calculates the inverse of a matrix.|
|static [`Invert(ref Matrix)`](VRageMath.Invert)||
|static [`Invert(ref Matrix, ref Matrix)`](VRageMath.Invert)|Calculates the inverse of a matrix.|
|static [`Lerp(Matrix, Matrix, float)`](VRageMath.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|static [`Lerp(ref Matrix, ref Matrix, float, ref Matrix)`](VRageMath.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|static [`Slerp(ref Matrix, ref Matrix, float, ref Matrix)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|static [`SlerpScale(ref Matrix, ref Matrix, float, ref Matrix)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static [`Slerp(Matrix, Matrix, float, ref Matrix)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|static [`Slerp(Matrix, Matrix, float)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|static [`SlerpScale(Matrix, Matrix, float, ref Matrix)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static [`SlerpScale(Matrix, Matrix, float)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static [`Negate(Matrix)`](VRageMath.Negate)|Negates individual elements of a matrix.|
|static [`Negate(ref Matrix, ref Matrix)`](VRageMath.Negate)|Negates individual elements of a matrix.|
|static [`Add(Matrix, Matrix)`](VRageMath.Add)|Adds a matrix to another matrix.|
|static [`Add(ref Matrix, ref Matrix, ref Matrix)`](VRageMath.Add)|Adds a matrix to another matrix.|
|static [`Subtract(Matrix, Matrix)`](VRageMath.Subtract)|Subtracts matrices.|
