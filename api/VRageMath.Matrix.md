← [Index](index)
# Matrix Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a matrix.
### Fields
|Member|Description|
|---|---|
|[`float M11`](VRageMath.M11)|Value at row 1 column 1 of the matrix.|
|[`float M12`](VRageMath.M12)|Value at row 1 column 2 of the matrix.|
|[`float M13`](VRageMath.M13)|Value at row 1 column 3 of the matrix.|
|[`float M14`](VRageMath.M14)|Value at row 1 column 4 of the matrix.|
|[`float M21`](VRageMath.M21)|Value at row 2 column 1 of the matrix.|
|[`float M22`](VRageMath.M22)|Value at row 2 column 2 of the matrix.|
|[`float M23`](VRageMath.M23)|Value at row 2 column 3 of the matrix.|
|[`float M24`](VRageMath.M24)|Value at row 2 column 4 of the matrix.|
|[`float M31`](VRageMath.M31)|Value at row 3 column 1 of the matrix.|
|[`float M32`](VRageMath.M32)|Value at row 3 column 2 of the matrix.|
|[`float M33`](VRageMath.M33)|Value at row 3 column 3 of the matrix.|
|[`float M34`](VRageMath.M34)|Value at row 3 column 4 of the matrix.|
|[`float M41`](VRageMath.M41)|Value at row 4 column 1 of the matrix.|
|[`float M42`](VRageMath.M42)|Value at row 4 column 2 of the matrix.|
|[`float M43`](VRageMath.M43)|Value at row 4 column 3 of the matrix.|
|[`float M44`](VRageMath.M44)|Value at row 4 column 4 of the matrix.|
|static [`VRageMath.Matrix Identity`](VRageMath.Identity)||
|static [`VRageMath.Matrix Zero`](VRageMath.Zero)||
### Properties
|Member|Description|
|---|---|
|[`VRageMath.Vector3 Up`](VRageMath.Up)|Gets and sets the up vector of the Matrix.|
|[`VRageMath.Vector3 Down`](VRageMath.Down)|Gets and sets the down vector of the Matrix.|
|[`VRageMath.Vector3 Right`](VRageMath.Right)|Gets and sets the right vector of the Matrix.|
|[`VRageMath.Vector3 Col0`](VRageMath.Col0)||
|[`VRageMath.Vector3 Col1`](VRageMath.Col1)||
|[`VRageMath.Vector3 Col2`](VRageMath.Col2)||
|[`VRageMath.Vector3 Left`](VRageMath.Left)|Gets and sets the left vector of the Matrix.|
|[`VRageMath.Vector3 Forward`](VRageMath.Forward)|Gets and sets the forward vector of the Matrix.|
|[`VRageMath.Vector3 Backward`](VRageMath.Backward)|Gets and sets the backward vector of the Matrix.|
|[`VRageMath.Vector3 Scale`](VRageMath.Scale)||
|[`VRageMath.Vector3 Translation`](VRageMath.Translation)|Gets and sets the translation vector of the Matrix.|
|[`float Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|static [`void Subtract(ref VRageMath.Matrix, ref VRageMath.Matrix, ref VRageMath.Matrix)`](VRageMath.Subtract)|Subtracts matrices.|
|static [`VRageMath.Matrix Multiply(VRageMath.Matrix, VRageMath.Matrix)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static [`void Multiply(ref VRageMath.Matrix, ref VRageMath.Matrix, ref VRageMath.Matrix)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static [`void MultiplyRotation(ref VRageMath.Matrix, ref VRageMath.Matrix, ref VRageMath.Matrix)`](VRageMath.MultiplyRotation)|Multiplies a matrix by another matrix, only rotation parts.|
|static [`VRageMath.Matrix Multiply(VRageMath.Matrix, float)`](VRageMath.Multiply)|Multiplies a matrix by a scalar value.|
|static [`void Multiply(ref VRageMath.Matrix, float, ref VRageMath.Matrix)`](VRageMath.Multiply)|Multiplies a matrix by a scalar value.|
|static [`VRageMath.Matrix Divide(VRageMath.Matrix, VRageMath.Matrix)`](VRageMath.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|static [`void Divide(ref VRageMath.Matrix, ref VRageMath.Matrix, ref VRageMath.Matrix)`](VRageMath.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|static [`VRageMath.Matrix Divide(VRageMath.Matrix, float)`](VRageMath.Divide)|Divides the components of a matrix by a scalar.|
|static [`void Divide(ref VRageMath.Matrix, float, ref VRageMath.Matrix)`](VRageMath.Divide)|Divides the components of a matrix by a scalar.|
|[`VRageMath.Matrix GetOrientation()`](VRageMath.GetOrientation)|Gets the orientation.|
|[`void AssertIsValid()`](VRageMath.AssertIsValid)||
|[`bool IsValid()`](VRageMath.IsValid)||
|[`bool IsNan()`](VRageMath.IsNan)||
|[`bool IsRotation()`](VRageMath.IsRotation)||
|[`bool HasNoTranslationOrPerspective()`](VRageMath.HasNoTranslationOrPerspective)|Returns true if this matrix represents invertible (you can call Invert on it) linear (it does not contain translation or perspective transformation) transformation. Such matrix consist solely of rotations, shearing, mirroring and scaling. It can be orthogonalized to create an orthogonal rotation matrix.|
|static [`VRageMath.Matrix CreateFromDir(VRageMath.Vector3)`](VRageMath.CreateFromDir)||
|static [`VRageMath.Matrix CreateFromDir(VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.CreateFromDir)||
|static [`VRageMath.Matrix Normalize(VRageMath.Matrix)`](VRageMath.Normalize)||
|static [`VRageMath.Matrix Orthogonalize(VRageMath.Matrix)`](VRageMath.Orthogonalize)||
|static [`VRageMath.Matrix Round(ref VRageMath.Matrix)`](VRageMath.Round)||
|static [`VRageMath.Matrix AlignRotationToAxes(ref VRageMath.Matrix, ref VRageMath.Matrix)`](VRageMath.AlignRotationToAxes)||
|static [`bool GetEulerAnglesXYZ(ref VRageMath.Matrix, ref VRageMath.Vector3)`](VRageMath.GetEulerAnglesXYZ)||
|static [`VRageMath.Matrix SwapYZCoordinates(VRageMath.Matrix)`](VRageMath.SwapYZCoordinates)||
|[`bool IsMirrored()`](VRageMath.IsMirrored)||
|[`bool IsOrthogonal()`](VRageMath.IsOrthogonal)||
|[`VRageMath.Vector3 GetDirectionVector(VRageMath.Direction)`](VRageMath.GetDirectionVector)||
|[`void SetDirectionVector(VRageMath.Direction, VRageMath.Vector3)`](VRageMath.SetDirectionVector)||
|[`VRageMath.Direction GetClosestDirection(VRageMath.Vector3)`](VRageMath.GetClosestDirection)||
|[`VRageMath.Direction GetClosestDirection(ref VRageMath.Vector3)`](VRageMath.GetClosestDirection)||
|static [`void Rescale(ref VRageMath.Matrix, float)`](VRageMath.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|static [`void Rescale(ref VRageMath.Matrix, ref VRageMath.Vector3)`](VRageMath.Rescale)|Same result as Matrix.CreateScale(scale) * matrix, but much faster|
|static [`VRageMath.Matrix Rescale(VRageMath.Matrix, float)`](VRageMath.Rescale)||
|static [`VRageMath.Matrix Rescale(VRageMath.Matrix, VRageMath.Vector3)`](VRageMath.Rescale)||
|static [`VRageMath.Matrix CreateBillboard(VRageMath.Vector3, VRageMath.Vector3, VRageMath.Vector3, Nullable<VRageMath.Vector3>)`](VRageMath.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|static [`void CreateBillboard(ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Vector3, Nullable<VRageMath.Vector3>, ref VRageMath.Matrix)`](VRageMath.CreateBillboard)|Creates a spherical billboard that rotates around a specified object position.|
|static [`VRageMath.Matrix CreateConstrainedBillboard(VRageMath.Vector3, VRageMath.Vector3, VRageMath.Vector3, Nullable<VRageMath.Vector3>, Nullable<VRageMath.Vector3>)`](VRageMath.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|static [`void CreateConstrainedBillboard(ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Vector3, Nullable<VRageMath.Vector3>, Nullable<VRageMath.Vector3>, ref VRageMath.Matrix)`](VRageMath.CreateConstrainedBillboard)|Creates a cylindrical billboard that rotates around a specified axis.|
|static [`VRageMath.Matrix CreateTranslation(VRageMath.Vector3)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static [`void CreateTranslation(ref VRageMath.Vector3, ref VRageMath.Matrix)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static [`VRageMath.Matrix CreateTranslation(float, float, float)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static [`void CreateTranslation(float, float, float, ref VRageMath.Matrix)`](VRageMath.CreateTranslation)|Creates a translation Matrix.|
|static [`VRageMath.Matrix CreateScale(float, float, float)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`void CreateScale(float, float, float, ref VRageMath.Matrix)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`VRageMath.Matrix CreateScale(VRageMath.Vector3)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`void CreateScale(ref VRageMath.Vector3, ref VRageMath.Matrix)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`VRageMath.Matrix CreateScale(float)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`void CreateScale(float, ref VRageMath.Matrix)`](VRageMath.CreateScale)|Creates a scaling Matrix.|
|static [`VRageMath.Matrix CreateRotationX(float)`](VRageMath.CreateRotationX)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|static [`void CreateRotationX(float, ref VRageMath.Matrix)`](VRageMath.CreateRotationX)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the x-axis.|
|static [`VRageMath.Matrix CreateRotationY(float)`](VRageMath.CreateRotationY)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|static [`void CreateRotationY(float, ref VRageMath.Matrix)`](VRageMath.CreateRotationY)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the y-axis.|
|static [`VRageMath.Matrix CreateRotationZ(float)`](VRageMath.CreateRotationZ)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|static [`void CreateRotationZ(float, ref VRageMath.Matrix)`](VRageMath.CreateRotationZ)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the z-axis.|
|static [`VRageMath.Matrix CreateFromAxisAngle(VRageMath.Vector3, float)`](VRageMath.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|static [`void CreateFromAxisAngle(ref VRageMath.Vector3, float, ref VRageMath.Matrix)`](VRageMath.CreateFromAxisAngle)|Creates a new Matrix that rotates around an arbitrary vector.|
|static [`void CreateRotationFromTwoVectors(ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Matrix)`](VRageMath.CreateRotationFromTwoVectors)||
|static [`VRageMath.Matrix CreatePerspectiveFieldOfView(float, float, float, float)`](VRageMath.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by value.|
|static [`VRageMath.Matrix CreatePerspectiveFovRhComplementary(float, float, float, float)`](VRageMath.CreatePerspectiveFovRhComplementary)||
|static [`VRageMath.Matrix CreatePerspectiveFovRhInfinite(float, float, float)`](VRageMath.CreatePerspectiveFovRhInfinite)||
|static [`VRageMath.Matrix CreatePerspectiveFovRhInfiniteComplementary(float, float, float)`](VRageMath.CreatePerspectiveFovRhInfiniteComplementary)||
|static [`VRageMath.Matrix CreatePerspectiveFovRhInverse(float, float, float, float)`](VRageMath.CreatePerspectiveFovRhInverse)||
|static [`VRageMath.Matrix CreatePerspectiveFovRhInfiniteInverse(float, float, float)`](VRageMath.CreatePerspectiveFovRhInfiniteInverse)||
|static [`VRageMath.Matrix CreatePerspectiveFovRhInfiniteComplementaryInverse(float, float, float)`](VRageMath.CreatePerspectiveFovRhInfiniteComplementaryInverse)||
|static [`VRageMath.Matrix CreateFromPerspectiveFieldOfView(ref VRageMath.Matrix, float, float)`](VRageMath.CreateFromPerspectiveFieldOfView)||
|static [`void CreatePerspectiveFieldOfView(float, float, float, float, ref VRageMath.Matrix)`](VRageMath.CreatePerspectiveFieldOfView)|Builds a perspective projection matrix based on a field of view and returns by reference.|
|static [`VRageMath.Matrix CreatePerspective(float, float, float, float)`](VRageMath.CreatePerspective)|Builds a perspective projection matrix and returns the result by value.|
|static [`void CreatePerspective(float, float, float, float, ref VRageMath.Matrix)`](VRageMath.CreatePerspective)|Builds a perspective projection matrix and returns the result by reference.|
|static [`VRageMath.Matrix CreatePerspectiveOffCenter(float, float, float, float, float, float)`](VRageMath.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|static [`void CreatePerspectiveOffCenter(float, float, float, float, float, float, ref VRageMath.Matrix)`](VRageMath.CreatePerspectiveOffCenter)|Builds a customized, perspective projection matrix.|
|static [`VRageMath.Matrix CreateOrthographic(float, float, float, float)`](VRageMath.CreateOrthographic)|Builds an orthogonal projection matrix.|
|static [`void CreateOrthographic(float, float, float, float, ref VRageMath.Matrix)`](VRageMath.CreateOrthographic)|Builds an orthogonal projection matrix.|
|static [`VRageMath.Matrix CreateOrthographicOffCenter(float, float, float, float, float, float)`](VRageMath.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|static [`void CreateOrthographicOffCenter(float, float, float, float, float, float, ref VRageMath.Matrix)`](VRageMath.CreateOrthographicOffCenter)|Builds a customized, orthogonal projection matrix.|
|static [`VRageMath.Matrix CreateLookAt(VRageMath.Vector3, VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.CreateLookAt)|Creates a view matrix.|
|static [`VRageMath.Matrix CreateLookAtInverse(VRageMath.Vector3, VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.CreateLookAtInverse)||
|static [`void CreateLookAt(ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Matrix)`](VRageMath.CreateLookAt)|Creates a view matrix.|
|static [`VRageMath.Matrix CreateWorld(VRageMath.Vector3)`](VRageMath.CreateWorld)||
|static [`VRageMath.Matrix CreateWorld(VRageMath.Vector3, VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.CreateWorld)|Creates a world matrix with the specified parameters.|
|static [`void CreateWorld(ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Matrix)`](VRageMath.CreateWorld)|Creates a world matrix with the specified parameters.|
|static [`VRageMath.Matrix CreateFromQuaternion(VRageMath.Quaternion)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|static [`void CreateFromQuaternion(ref VRageMath.Quaternion, ref VRageMath.Matrix)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix from a Quaternion.|
|static [`VRageMath.Matrix CreateFromYawPitchRoll(float, float, float)`](VRageMath.CreateFromYawPitchRoll)|Creates a new rotation matrix from a specified yaw, pitch, and roll.|
|static [`void CreateFromYawPitchRoll(float, float, float, ref VRageMath.Matrix)`](VRageMath.CreateFromYawPitchRoll)|Fills in a rotation matrix from a specified yaw, pitch, and roll.|
|static [`VRageMath.Matrix CreateFromTransformScale(VRageMath.Quaternion, VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.CreateFromTransformScale)||
|static [`VRageMath.Matrix CreateShadow(VRageMath.Vector3, VRageMath.Plane)`](VRageMath.CreateShadow)|Creates a Matrix that flattens geometry into a specified Plane as if casting a shadow from a specified light source.|
|static [`void CreateShadow(ref VRageMath.Vector3, ref VRageMath.Plane, ref VRageMath.Matrix)`](VRageMath.CreateShadow)|Fills in a Matrix to flatten geometry into a specified Plane as if casting a shadow from a specified light source.|
|static [`VRageMath.Matrix CreateReflection(VRageMath.Plane)`](VRageMath.CreateReflection)|Creates a Matrix that reflects the coordinate system about a specified Plane.|
|static [`void CreateReflection(ref VRageMath.Plane, ref VRageMath.Matrix)`](VRageMath.CreateReflection)|Fills in an existing Matrix so that it reflects the coordinate system about a specified Plane.|
|static [`VRageMath.Matrix Transform(VRageMath.Matrix, VRageMath.Quaternion)`](VRageMath.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|static [`void Transform(ref VRageMath.Matrix, ref VRageMath.Quaternion, ref VRageMath.Matrix)`](VRageMath.Transform)|Transforms a Matrix by applying a Quaternion rotation.|
|[`VRageMath.Vector4 GetRow(int)`](VRageMath.GetRow)||
|[`void SetRow(int, VRageMath.Vector4)`](VRageMath.SetRow)||
|[`string ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`bool Equals(VRageMath.Matrix)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Matrix.|
|[`bool EqualsFast(ref VRageMath.Matrix, float)`](VRageMath.EqualsFast)|Compares just position, forward and up|
|[`bool Equals(System.Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of this object.|
|static [`VRageMath.Matrix Transpose(VRageMath.Matrix)`](VRageMath.Transpose)|Transposes the rows and columns of a matrix.|
|static [`void Transpose(ref VRageMath.Matrix, ref VRageMath.Matrix)`](VRageMath.Transpose)|Transposes the rows and columns of a matrix.|
|[`void TransposeRotationInPlace()`](VRageMath.TransposeRotationInPlace)|Transposes the rows and columns of a matrix that is assumed to be rotation only in place.|
|[`float Determinant()`](VRageMath.Determinant)|Calculates the determinant of the matrix.|
|static [`VRageMath.Matrix Invert(VRageMath.Matrix)`](VRageMath.Invert)|Calculates the inverse of a matrix.|
|static [`VRageMath.Matrix Invert(ref VRageMath.Matrix)`](VRageMath.Invert)||
|static [`void Invert(ref VRageMath.Matrix, ref VRageMath.Matrix)`](VRageMath.Invert)|Calculates the inverse of a matrix.|
|static [`VRageMath.Matrix Lerp(VRageMath.Matrix, VRageMath.Matrix, float)`](VRageMath.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|static [`void Lerp(ref VRageMath.Matrix, ref VRageMath.Matrix, float, ref VRageMath.Matrix)`](VRageMath.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|static [`void Slerp(ref VRageMath.Matrix, ref VRageMath.Matrix, float, ref VRageMath.Matrix)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|static [`void SlerpScale(ref VRageMath.Matrix, ref VRageMath.Matrix, float, ref VRageMath.Matrix)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static [`void Slerp(VRageMath.Matrix, VRageMath.Matrix, float, ref VRageMath.Matrix)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|static [`VRageMath.Matrix Slerp(VRageMath.Matrix, VRageMath.Matrix, float)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|static [`void SlerpScale(VRageMath.Matrix, VRageMath.Matrix, float, ref VRageMath.Matrix)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static [`VRageMath.Matrix SlerpScale(VRageMath.Matrix, VRageMath.Matrix, float)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static [`VRageMath.Matrix Negate(VRageMath.Matrix)`](VRageMath.Negate)|Negates individual elements of a matrix.|
|static [`void Negate(ref VRageMath.Matrix, ref VRageMath.Matrix)`](VRageMath.Negate)|Negates individual elements of a matrix.|
|static [`VRageMath.Matrix Add(VRageMath.Matrix, VRageMath.Matrix)`](VRageMath.Add)|Adds a matrix to another matrix.|
|static [`void Add(ref VRageMath.Matrix, ref VRageMath.Matrix, ref VRageMath.Matrix)`](VRageMath.Add)|Adds a matrix to another matrix.|
|static [`VRageMath.Matrix Subtract(VRageMath.Matrix, VRageMath.Matrix)`](VRageMath.Subtract)|Subtracts matrices.|
