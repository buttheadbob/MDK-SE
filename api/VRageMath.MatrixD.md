← [Index](index)
# MatrixD Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a matrix.
### Fields
|Member|Description|
|---|---|
|[`double M11`](VRageMath.M11)|Value at row 1 column 1 of the matrix.|
|[`double M12`](VRageMath.M12)|Value at row 1 column 2 of the matrix.|
|[`double M13`](VRageMath.M13)|Value at row 1 column 3 of the matrix.|
|[`double M14`](VRageMath.M14)|Value at row 1 column 4 of the matrix.|
|[`double M21`](VRageMath.M21)|Value at row 2 column 1 of the matrix.|
|[`double M22`](VRageMath.M22)|Value at row 2 column 2 of the matrix.|
|[`double M23`](VRageMath.M23)|Value at row 2 column 3 of the matrix.|
|[`double M24`](VRageMath.M24)|Value at row 2 column 4 of the matrix.|
|[`double M31`](VRageMath.M31)|Value at row 3 column 1 of the matrix.|
|[`double M32`](VRageMath.M32)|Value at row 3 column 2 of the matrix.|
|[`double M33`](VRageMath.M33)|Value at row 3 column 3 of the matrix.|
|[`double M34`](VRageMath.M34)|Value at row 3 column 4 of the matrix.|
|[`double M41`](VRageMath.M41)|Value at row 4 column 1 of the matrix.|
|[`double M42`](VRageMath.M42)|Value at row 4 column 2 of the matrix.|
|[`double M43`](VRageMath.M43)|Value at row 4 column 3 of the matrix.|
|[`double M44`](VRageMath.M44)|Value at row 4 column 4 of the matrix.|
|static [`VRageMath.MatrixD Identity`](VRageMath.Identity)||
|static [`VRageMath.MatrixD Zero`](VRageMath.Zero)||
### Properties
|Member|Description|
|---|---|
|[`VRageMath.Vector3D Col0`](VRageMath.Col0)||
|[`VRageMath.Vector3D Col1`](VRageMath.Col1)||
|[`VRageMath.Vector3D Col2`](VRageMath.Col2)||
|[`VRageMath.Vector3D Up`](VRageMath.Up)|Gets and sets the up vector of the Matrix.|
|[`VRageMath.Vector3D Down`](VRageMath.Down)|Gets and sets the down vector of the Matrix.|
|[`VRageMath.Vector3D Right`](VRageMath.Right)|Gets and sets the right vector of the Matrix.|
|[`VRageMath.Vector3D Left`](VRageMath.Left)|Gets and sets the left vector of the Matrix.|
|[`VRageMath.Vector3D Forward`](VRageMath.Forward)|Gets and sets the forward vector of the Matrix.|
|[`VRageMath.Vector3D Backward`](VRageMath.Backward)|Gets and sets the backward vector of the Matrix.|
|[`VRageMath.Vector3D Scale`](VRageMath.Scale)||
|[`VRageMath.Vector3D Translation`](VRageMath.Translation)|Gets and sets the translation vector of the Matrix.|
|[`VRageMath.Matrix3x3 Rotation`](VRageMath.Rotation)||
|[`double Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|static [`VRageMath.Matrix Subtract(VRageMath.Matrix, VRageMath.Matrix)`](VRageMath.Subtract)|Subtracts matrices.|
|static [`void Subtract(ref VRageMath.MatrixD, ref VRageMath.MatrixD, ref VRageMath.MatrixD)`](VRageMath.Subtract)|Subtracts matrices.|
|static [`VRageMath.MatrixD Multiply(VRageMath.MatrixD, VRageMath.MatrixD)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static [`VRageMath.MatrixD Multiply(VRageMath.MatrixD, VRageMath.Matrix)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static [`void Multiply(ref VRageMath.MatrixD, ref VRageMath.Matrix, ref VRageMath.MatrixD)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static [`void Multiply(ref VRageMath.Matrix, ref VRageMath.MatrixD, ref VRageMath.MatrixD)`](VRageMath.Multiply)||
|static [`void Multiply(ref VRageMath.MatrixD, ref VRageMath.MatrixD, ref VRageMath.MatrixD)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static [`VRageMath.MatrixD Multiply(VRageMath.MatrixD, double)`](VRageMath.Multiply)|Multiplies a matrix by a scalar value.|
|static [`void Multiply(ref VRageMath.MatrixD, double, ref VRageMath.MatrixD)`](VRageMath.Multiply)|Multiplies a matrix by a scalar value.|
|static [`VRageMath.MatrixD Divide(VRageMath.MatrixD, VRageMath.MatrixD)`](VRageMath.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|static [`void Divide(ref VRageMath.MatrixD, ref VRageMath.MatrixD, ref VRageMath.MatrixD)`](VRageMath.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|static [`VRageMath.MatrixD Divide(VRageMath.MatrixD, double)`](VRageMath.Divide)|Divides the components of a matrix by a scalar.|
|static [`void Divide(ref VRageMath.MatrixD, double, ref VRageMath.MatrixD)`](VRageMath.Divide)|Divides the components of a matrix by a scalar.|
|[`VRageMath.MatrixD GetOrientation()`](VRageMath.GetOrientation)|Gets the orientation.|
|[`void AssertIsValid()`](VRageMath.AssertIsValid)||
|[`bool IsValid()`](VRageMath.IsValid)||
|[`bool IsNan()`](VRageMath.IsNan)||
|[`bool IsRotation()`](VRageMath.IsRotation)||
|[`bool HasNoTranslationOrPerspective()`](VRageMath.HasNoTranslationOrPerspective)|Returns true if this matrix represents invertible (you can call Invert on it) linear (it does not contain translation or perspective transformation) transformation. Such matrix consist solely of rotations, shearing, mirroring and scaling. It can be orthogonalized to create an orthogonal rotation matrix.|
|static [`VRageMath.MatrixD CreateFromDir(VRageMath.Vector3D)`](VRageMath.CreateFromDir)||
|static [`VRageMath.MatrixD CreateFromDir(VRageMath.Vector3D, VRageMath.Vector3D)`](VRageMath.CreateFromDir)||
|static [`VRageMath.MatrixD Normalize(VRageMath.MatrixD)`](VRageMath.Normalize)||
|[`void Orthogonalize()`](VRageMath.Orthogonalize)||
|static [`VRageMath.MatrixD Orthogonalize(VRageMath.MatrixD)`](VRageMath.Orthogonalize)||
|static [`VRageMath.MatrixD AlignRotationToAxes(ref VRageMath.MatrixD, ref VRageMath.MatrixD)`](VRageMath.AlignRotationToAxes)||
|static [`bool GetEulerAnglesXYZ(ref VRageMath.MatrixD, ref VRageMath.Vector3D)`](VRageMath.GetEulerAnglesXYZ)||
|static [`VRageMath.MatrixD SwapYZCoordinates(VRageMath.MatrixD)`](VRageMath.SwapYZCoordinates)||
|[`bool IsMirrored()`](VRageMath.IsMirrored)||
|[`VRageMath.Vector3D GetDirectionVector(VRageMath.Direction)`](VRageMath.GetDirectionVector)||
|[`void SetDirectionVector(VRageMath.Direction, VRageMath.Vector3D)`](VRageMath.SetDirectionVector)||
|[`VRageMath.Direction GetClosestDirection(VRageMath.Vector3D)`](VRageMath.GetClosestDirection)||
|[`VRageMath.Direction GetClosestDirection(ref VRageMath.Vector3D)`](VRageMath.GetClosestDirection)||
|static [`void Rescale(ref VRageMath.MatrixD, double)`](VRageMath.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|static [`void Rescale(ref VRageMath.MatrixD, float)`](VRageMath.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|static [`void Rescale(ref VRageMath.MatrixD, ref VRageMath.Vector3D)`](VRageMath.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|static [`VRageMath.MatrixD Rescale(VRageMath.MatrixD, double)`](VRageMath.Rescale)||
|static [`VRageMath.MatrixD Rescale(VRageMath.MatrixD, VRageMath.Vector3D)`](VRageMath.Rescale)||
|static [`VRageMath.MatrixD CreateBillboard(VRageMath.Vector3D, VRageMath.Vector3D, VRageMath.Vector3D, Nullable<VRageMath.Vector3D>)`](VRageMath.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|static [`void CreateBillboard(ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref VRageMath.Vector3D, Nullable<VRageMath.Vector3D>, ref VRageMath.MatrixD)`](VRageMath.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|static [`VRageMath.MatrixD CreateConstrainedBillboard(VRageMath.Vector3D, VRageMath.Vector3D, VRageMath.Vector3D, Nullable<VRageMath.Vector3D>, Nullable<VRageMath.Vector3D>)`](VRageMath.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|static [`void CreateConstrainedBillboard(ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref VRageMath.Vector3D, Nullable<VRageMath.Vector3D>, Nullable<VRageMath.Vector3D>, ref VRageMath.MatrixD)`](VRageMath.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|static [`VRageMath.MatrixD CreateTranslation(VRageMath.Vector3D)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static [`VRageMath.MatrixD CreateTranslation(VRageMath.Vector3)`](VRageMath.CreateTranslation)||
|static [`void CreateTranslation(ref VRageMath.Vector3D, ref VRageMath.MatrixD)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static [`VRageMath.MatrixD CreateTranslation(double, double, double)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static [`void CreateTranslation(double, double, double, ref VRageMath.MatrixD)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static [`VRageMath.MatrixD CreateScale(double, double, double)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`void CreateScale(double, double, double, ref VRageMath.MatrixD)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`VRageMath.MatrixD CreateScale(VRageMath.Vector3D)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`void CreateScale(ref VRageMath.Vector3D, ref VRageMath.MatrixD)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`VRageMath.MatrixD CreateScale(double)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`void CreateScale(double, ref VRageMath.MatrixD)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`VRageMath.MatrixD CreateRotationX(double)`](VRageMath.CreateRotationX)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|static [`void CreateRotationX(double, ref VRageMath.MatrixD)`](VRageMath.CreateRotationX)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the x-axis.|
|static [`VRageMath.MatrixD CreateRotationY(double)`](VRageMath.CreateRotationY)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|static [`void CreateRotationY(double, ref VRageMath.MatrixD)`](VRageMath.CreateRotationY)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the y-axis.|
|static [`VRageMath.MatrixD CreateRotationZ(double)`](VRageMath.CreateRotationZ)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|static [`void CreateRotationZ(double, ref VRageMath.MatrixD)`](VRageMath.CreateRotationZ)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the z-axis.|
|static [`VRageMath.MatrixD CreateFromAxisAngle(VRageMath.Vector3D, double)`](VRageMath.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|static [`void CreateFromAxisAngle(ref VRageMath.Vector3D, double, ref VRageMath.MatrixD)`](VRageMath.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|static [`VRageMath.MatrixD CreatePerspectiveFieldOfView(double, double, double, double)`](VRageMath.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by value.|
|static [`void CreatePerspectiveFieldOfView(double, double, double, double, ref VRageMath.MatrixD)`](VRageMath.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by reference.|
|static [`VRageMath.MatrixD CreatePerspective(double, double, double, double)`](VRageMath.CreatePerspective)|Builds a perspective projection matrix and returns the result by value.|
|static [`void CreatePerspective(double, double, double, double, ref VRageMath.MatrixD)`](VRageMath.CreatePerspective)|Builds a perspective projection matrix and returns the result by reference.|
|static [`VRageMath.MatrixD CreatePerspectiveOffCenter(double, double, double, double, double, double)`](VRageMath.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|static [`void CreatePerspectiveOffCenter(double, double, double, double, double, double, ref VRageMath.MatrixD)`](VRageMath.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|static [`VRageMath.MatrixD CreateOrthographic(double, double, double, double)`](VRageMath.CreateOrthographic)|Builds an orthogonal projection matrix.|
|static [`void CreateOrthographic(double, double, double, double, ref VRageMath.MatrixD)`](VRageMath.CreateOrthographic)|Builds an orthogonal projection matrix.|
|static [`VRageMath.MatrixD CreateOrthographicOffCenter(double, double, double, double, double, double)`](VRageMath.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|static [`void CreateOrthographicOffCenter(double, double, double, double, double, double, ref VRageMath.MatrixD)`](VRageMath.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|static [`VRageMath.MatrixD CreateLookAt(VRageMath.Vector3D, VRageMath.Vector3D, VRageMath.Vector3)`](VRageMath.CreateLookAt)||
|static [`VRageMath.MatrixD CreateLookAt(VRageMath.Vector3D, VRageMath.Vector3D, VRageMath.Vector3D)`](VRageMath.CreateLookAt)|Creates a view matrix.|
|static [`VRageMath.Matrix CreateLookAtInverse(VRageMath.Vector3D, VRageMath.Vector3D, VRageMath.Vector3D)`](VRageMath.CreateLookAtInverse)||
|static [`void CreateLookAt(ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref VRageMath.MatrixD)`](VRageMath.CreateLookAt)|Creates a view matrix.|
|static [`VRageMath.MatrixD CreateWorld(VRageMath.Vector3D, VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.CreateWorld)||
|static [`VRageMath.MatrixD CreateWorld(VRageMath.Vector3D)`](VRageMath.CreateWorld)||
|static [`VRageMath.MatrixD CreateWorld(VRageMath.Vector3D, VRageMath.Vector3D, VRageMath.Vector3D)`](VRageMath.CreateWorld)|Creates a world matrix with the specified parameters.|
|static [`void CreateWorld(ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref VRageMath.Vector3D, ref VRageMath.MatrixD)`](VRageMath.CreateWorld)|Creates a world matrix with the specified parameters.|
|static [`VRageMath.MatrixD CreateFromQuaternion(VRageMath.Quaternion)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|static [`VRageMath.MatrixD CreateFromQuaternion(VRageMath.QuaternionD)`](VRageMath.CreateFromQuaternion)||
|static [`void CreateFromQuaternion(ref VRageMath.Quaternion, ref VRageMath.MatrixD)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|static [`VRageMath.MatrixD CreateFromYawPitchRoll(double, double, double)`](VRageMath.CreateFromYawPitchRoll)|Creates a new rotation matrix from a specified yaw, pitch, and roll.|
|static [`void CreateFromYawPitchRoll(double, double, double, ref VRageMath.MatrixD)`](VRageMath.CreateFromYawPitchRoll)|Fills in a rotation matrix from a specified yaw, pitch, and roll.|
|static [`VRageMath.MatrixD CreateFromTransformScale(VRageMath.Quaternion, VRageMath.Vector3D, VRageMath.Vector3D)`](VRageMath.CreateFromTransformScale)||
|static [`VRageMath.MatrixD CreateShadow(VRageMath.Vector3D, VRageMath.Plane)`](VRageMath.CreateShadow)|Creates a Matrix that flattens geometry into a specified Plane as if casting a shadow from a specified light source.|
|static [`void CreateShadow(ref VRageMath.Vector3D, ref VRageMath.Plane, ref VRageMath.MatrixD)`](VRageMath.CreateShadow)|Fills in a Matrix to flatten geometry into a specified Plane as if casting a shadow from a specified light source.|
|static [`VRageMath.MatrixD CreateReflection(VRageMath.Plane)`](VRageMath.CreateReflection)|Creates a Matrix that reflects the coordinate system about a specified Plane.|
|static [`void CreateReflection(ref VRageMath.Plane, ref VRageMath.MatrixD)`](VRageMath.CreateReflection)|Fills in an existing Matrix so that it reflects the coordinate system about a specified Plane.|
|static [`VRageMath.MatrixD Transform(VRageMath.MatrixD, VRageMath.Quaternion)`](VRageMath.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|static [`void Transform(ref VRageMath.MatrixD, ref VRageMath.Quaternion, ref VRageMath.MatrixD)`](VRageMath.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|[`VRageMath.Vector4 GetRow(int)`](VRageMath.GetRow)||
|[`void SetRow(int, VRageMath.Vector4)`](VRageMath.SetRow)||
|[`string ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`bool Equals(VRageMath.MatrixD)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Matrix.|
|[`bool EqualsFast(ref VRageMath.MatrixD, double)`](VRageMath.EqualsFast)|Compares just position, forward and up|
|[`bool Equals(System.Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of this object.|
|static [`VRageMath.MatrixD Transpose(VRageMath.MatrixD)`](VRageMath.Transpose)|Transposes the rows and columns of a matrix.|
|static [`void Transpose(ref VRageMath.MatrixD, ref VRageMath.MatrixD)`](VRageMath.Transpose)|Transposes the rows and columns of a matrix.|
|[`double Determinant()`](VRageMath.Determinant)|Calculates the determinant of the matrix.|
|static [`VRageMath.MatrixD Invert(VRageMath.MatrixD)`](VRageMath.Invert)|Calculates the inverse of a matrix.|
|static [`VRageMath.MatrixD Invert(ref VRageMath.MatrixD)`](VRageMath.Invert)||
|static [`void Invert(ref VRageMath.MatrixD, ref VRageMath.MatrixD)`](VRageMath.Invert)|Calculates the inverse of a matrix.|
|static [`VRageMath.MatrixD Lerp(VRageMath.MatrixD, VRageMath.MatrixD, double)`](VRageMath.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|static [`void Lerp(ref VRageMath.MatrixD, ref VRageMath.MatrixD, double, ref VRageMath.MatrixD)`](VRageMath.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|static [`void Slerp(ref VRageMath.MatrixD, ref VRageMath.MatrixD, float, ref VRageMath.MatrixD)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|[`bool IsOrthogonal()`](VRageMath.IsOrthogonal)||
|[`bool IsOrthogonal(double)`](VRageMath.IsOrthogonal)||
|static [`void SlerpScale(ref VRageMath.MatrixD, ref VRageMath.MatrixD, float, ref VRageMath.MatrixD)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static [`void Slerp(VRageMath.MatrixD, VRageMath.MatrixD, float, ref VRageMath.MatrixD)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|static [`VRageMath.MatrixD Slerp(VRageMath.MatrixD, VRageMath.MatrixD, float)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|static [`void SlerpScale(VRageMath.MatrixD, VRageMath.MatrixD, float, ref VRageMath.MatrixD)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static [`VRageMath.MatrixD SlerpScale(VRageMath.MatrixD, VRageMath.MatrixD, float)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static [`VRageMath.MatrixD Negate(VRageMath.MatrixD)`](VRageMath.Negate)|Negates individual elements of a matrix.|
|static [`void Negate(ref VRageMath.MatrixD, ref VRageMath.MatrixD)`](VRageMath.Negate)|Negates individual elements of a matrix.|
|static [`VRageMath.MatrixD Add(VRageMath.MatrixD, VRageMath.MatrixD)`](VRageMath.Add)|Adds a matrix to another matrix.|
|static [`void Add(ref VRageMath.MatrixD, ref VRageMath.MatrixD, ref VRageMath.MatrixD)`](VRageMath.Add)|Adds a matrix to another matrix.|
