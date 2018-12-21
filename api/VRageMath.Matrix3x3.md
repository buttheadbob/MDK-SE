← [Index](index)
# Matrix3x3 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a matrix.
### Fields
<table style="width: 100%">
<tr><td>[`float M11`](VRageMath.M11)</td><td>Value at row 1 column 1 of the matrix.</td></tr>
<tr><td>[`float M12`](VRageMath.M12)</td><td>Value at row 1 column 2 of the matrix.</td></tr>
<tr><td>[`float M13`](VRageMath.M13)</td><td>Value at row 1 column 3 of the matrix.</td></tr>
<tr><td>[`float M21`](VRageMath.M21)</td><td>Value at row 2 column 1 of the matrix.</td></tr>
<tr><td>[`float M22`](VRageMath.M22)</td><td>Value at row 2 column 2 of the matrix.</td></tr>
<tr><td>[`float M23`](VRageMath.M23)</td><td>Value at row 2 column 3 of the matrix.</td></tr>
<tr><td>[`float M31`](VRageMath.M31)</td><td>Value at row 3 column 1 of the matrix.</td></tr>
<tr><td>[`float M32`](VRageMath.M32)</td><td>Value at row 3 column 2 of the matrix.</td></tr>
<tr><td>[`float M33`](VRageMath.M33)</td><td>Value at row 3 column 3 of the matrix.</td></tr>
<tr><td>static [`Matrix3x3 Identity`](VRageMath.Identity)</td><td></td></tr>
<tr><td>static [`Matrix3x3 Zero`](VRageMath.Zero)</td><td></td></tr>
</table>
### Properties
<table style="width: 100%">
<tr><td>[`Vector3 Up`](VRageMath.Up)</td><td>Gets and sets the up vector of the Matrix3x3.</td></tr>
<tr><td>[`Vector3 Down`](VRageMath.Down)</td><td>Gets and sets the down vector of the Matrix3x3.</td></tr>
<tr><td>[`Vector3 Right`](VRageMath.Right)</td><td>Gets and sets the right vector of the Matrix3x3.</td></tr>
<tr><td>[`Vector3 Col0`](VRageMath.Col0)</td><td></td></tr>
<tr><td>[`Vector3 Col1`](VRageMath.Col1)</td><td></td></tr>
<tr><td>[`Vector3 Col2`](VRageMath.Col2)</td><td></td></tr>
<tr><td>[`Vector3 Left`](VRageMath.Left)</td><td>Gets and sets the left vector of the Matrix3x3.</td></tr>
<tr><td>[`Vector3 Forward`](VRageMath.Forward)</td><td>Gets and sets the forward vector of the Matrix3x3.</td></tr>
<tr><td>[`Vector3 Backward`](VRageMath.Backward)</td><td>Gets and sets the backward vector of the Matrix3x3.</td></tr>
<tr><td>[`Vector3 Scale`](VRageMath.Scale)</td><td></td></tr>
<tr><td>[`float Item`](VRageMath.Item)</td><td></td></tr>
</table>
### Methods
<table style="width: 100%">
<tr><td>[`Vector3 GetDirectionVector(Direction direction)`](VRageMath.GetDirectionVector)</td><td></td></tr>
<tr><td>[`void SetDirectionVector(Direction direction, Vector3 newValue)`](VRageMath.SetDirectionVector)</td><td></td></tr>
<tr><td>[`Direction GetClosestDirection(Vector3 referenceVector)`](VRageMath.GetClosestDirection)</td><td></td></tr>
<tr><td>[`Direction GetClosestDirection(ref Vector3 referenceVector)`](VRageMath.GetClosestDirection)</td><td></td></tr>
<tr><td>static [`void Rescale(ref Matrix3x3 matrix, float scale)`](VRageMath.Rescale)</td><td>Same result as Matrix3x3.CreateScale(scale) * matrix, but much faster</td></tr>
<tr><td>static [`void Rescale(ref Matrix3x3 matrix, ref Vector3 scale)`](VRageMath.Rescale)</td><td>Same result as Matrix3x3.CreateScale(scale) * matrix, but much faster</td></tr>
<tr><td>static [`Matrix3x3 Rescale(Matrix3x3 matrix, float scale)`](VRageMath.Rescale)</td><td></td></tr>
<tr><td>static [`Matrix3x3 Rescale(Matrix3x3 matrix, Vector3 scale)`](VRageMath.Rescale)</td><td></td></tr>
<tr><td>static [`Matrix3x3 CreateScale(float xScale, float yScale, float zScale)`](VRageMath.CreateScale)</td><td>Creates a scaling Matrix3x3.</td></tr>
<tr><td>static [`void CreateScale(float xScale, float yScale, float zScale, ref Matrix3x3 result)`](VRageMath.CreateScale)</td><td>Creates a scaling Matrix3x3.</td></tr>
<tr><td>static [`Matrix3x3 CreateScale(Vector3 scales)`](VRageMath.CreateScale)</td><td>Creates a scaling Matrix3x3.</td></tr>
<tr><td>static [`void CreateScale(ref Vector3 scales, ref Matrix3x3 result)`](VRageMath.CreateScale)</td><td>Creates a scaling Matrix3x3.</td></tr>
<tr><td>static [`Matrix3x3 CreateScale(float scale)`](VRageMath.CreateScale)</td><td>Creates a scaling Matrix3x3.</td></tr>
<tr><td>static [`void CreateScale(float scale, ref Matrix3x3 result)`](VRageMath.CreateScale)</td><td>Creates a scaling Matrix3x3.</td></tr>
<tr><td>static [`Matrix3x3 CreateRotationX(float radians)`](VRageMath.CreateRotationX)</td><td>Returns a matrix that can be used to rotate a set of vertices around the x-axis.</td></tr>
<tr><td>static [`void CreateRotationX(float radians, ref Matrix3x3 result)`](VRageMath.CreateRotationX)</td><td>Populates data into a user-specified matrix that can be used to rotate a set of vertices around the x-axis.</td></tr>
<tr><td>static [`Matrix3x3 CreateRotationY(float radians)`](VRageMath.CreateRotationY)</td><td>Returns a matrix that can be used to rotate a set of vertices around the y-axis.</td></tr>
<tr><td>static [`void CreateRotationY(float radians, ref Matrix3x3 result)`](VRageMath.CreateRotationY)</td><td>Populates data into a user-specified matrix that can be used to rotate a set of vertices around the y-axis.</td></tr>
<tr><td>static [`Matrix3x3 CreateRotationZ(float radians)`](VRageMath.CreateRotationZ)</td><td>Returns a matrix that can be used to rotate a set of vertices around the z-axis.</td></tr>
<tr><td>static [`void CreateRotationZ(float radians, ref Matrix3x3 result)`](VRageMath.CreateRotationZ)</td><td>Populates data into a user-specified matrix that can be used to rotate a set of vertices around the z-axis.</td></tr>
<tr><td>static [`Matrix3x3 CreateFromAxisAngle(Vector3 axis, float angle)`](VRageMath.CreateFromAxisAngle)</td><td>Creates a new Matrix3x3 that rotates around an arbitrary vector.</td></tr>
<tr><td>static [`void CreateFromAxisAngle(ref Vector3 axis, float angle, ref Matrix3x3 result)`](VRageMath.CreateFromAxisAngle)</td><td>Creates a new Matrix3x3 that rotates around an arbitrary vector.</td></tr>
<tr><td>static [`void CreateRotationFromTwoVectors(ref Vector3 fromVector, ref Vector3 toVector, ref Matrix3x3 resultMatrix)`](VRageMath.CreateRotationFromTwoVectors)</td><td></td></tr>
<tr><td>static [`Matrix3x3 CreateFromQuaternion(Quaternion quaternion)`](VRageMath.CreateFromQuaternion)</td><td>Creates a rotation Matrix3x3 from a Quaternion.</td></tr>
<tr><td>static [`void CreateFromQuaternion(ref Quaternion quaternion, ref Matrix3x3 result)`](VRageMath.CreateFromQuaternion)</td><td>Creates a rotation Matrix3x3 from a Quaternion.</td></tr>
<tr><td>static [`Matrix3x3 CreateFromYawPitchRoll(float yaw, float pitch, float roll)`](VRageMath.CreateFromYawPitchRoll)</td><td>Creates a new rotation matrix from a specified yaw, pitch, and roll.</td></tr>
<tr><td>static [`void CreateFromYawPitchRoll(float yaw, float pitch, float roll, ref Matrix3x3 result)`](VRageMath.CreateFromYawPitchRoll)</td><td>Fills in a rotation matrix from a specified yaw, pitch, and roll.</td></tr>
<tr><td>static [`void Transform(ref Matrix3x3 value, ref Quaternion rotation, ref Matrix3x3 result)`](VRageMath.Transform)</td><td>Transforms a Matrix3x3 by applying a Quaternion rotation.</td></tr>
<tr><td>[`Vector3 GetRow(int row)`](VRageMath.GetRow)</td><td></td></tr>
<tr><td>[`void SetRow(int row, Vector3 value)`](VRageMath.SetRow)</td><td></td></tr>
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td>Retrieves a string representation of the current object.</td></tr>
<tr><td>[`bool Equals(Matrix3x3 other)`](VRageMath.Equals)</td><td>Determines whether the specified Object is equal to the Matrix3x3.</td></tr>
<tr><td>[`bool EqualsFast(ref Matrix3x3 other, float epsilon)`](VRageMath.EqualsFast)</td><td>Compares just position, forward and up</td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td>Returns a value that indicates whether the current instance is equal to a specified object.</td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td>Gets the hash code of this object.</td></tr>
<tr><td>static [`void Transpose(ref Matrix3x3 matrix, ref Matrix3x3 result)`](VRageMath.Transpose)</td><td>Transposes the rows and columns of a matrix.</td></tr>
<tr><td>[`void Transpose()`](VRageMath.Transpose)</td><td></td></tr>
<tr><td>[`float Determinant()`](VRageMath.Determinant)</td><td></td></tr>
<tr><td>static [`void Invert(ref Matrix3x3 matrix, ref Matrix3x3 result)`](VRageMath.Invert)</td><td>Calculates the inverse of a matrix.</td></tr>
<tr><td>static [`void Lerp(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, float amount, ref Matrix3x3 result)`](VRageMath.Lerp)</td><td>Linearly interpolates between the corresponding values of two matrices.</td></tr>
<tr><td>static [`void Slerp(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, float amount, ref Matrix3x3 result)`](VRageMath.Slerp)</td><td>Performs spherical linear interpolation of position and rotation.</td></tr>
<tr><td>static [`void SlerpScale(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, float amount, ref Matrix3x3 result)`](VRageMath.SlerpScale)</td><td>Performs spherical linear interpolation of position and rotation and scale.</td></tr>
<tr><td>static [`void Negate(ref Matrix3x3 matrix, ref Matrix3x3 result)`](VRageMath.Negate)</td><td>Negates individual elements of a matrix.</td></tr>
<tr><td>static [`void Add(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, ref Matrix3x3 result)`](VRageMath.Add)</td><td>Adds a matrix to another matrix.</td></tr>
<tr><td>static [`void Subtract(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, ref Matrix3x3 result)`](VRageMath.Subtract)</td><td>Subtracts matrices.</td></tr>
<tr><td>static [`void Multiply(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, ref Matrix3x3 result)`](VRageMath.Multiply)</td><td>Multiplies a matrix by another matrix.</td></tr>
<tr><td>static [`void Multiply(ref Matrix3x3 matrix1, float scaleFactor, ref Matrix3x3 result)`](VRageMath.Multiply)</td><td>Multiplies a matrix by a scalar value.</td></tr>
<tr><td>static [`void Divide(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, ref Matrix3x3 result)`](VRageMath.Divide)</td><td>Divides the components of a matrix by the corresponding components of another matrix.</td></tr>
<tr><td>static [`void Divide(ref Matrix3x3 matrix1, float divider, ref Matrix3x3 result)`](VRageMath.Divide)</td><td>Divides the components of a matrix by a scalar.</td></tr>
<tr><td>[`Matrix3x3 GetOrientation()`](VRageMath.GetOrientation)</td><td>Gets the orientation.</td></tr>
<tr><td>[`void AssertIsValid()`](VRageMath.AssertIsValid)</td><td></td></tr>
<tr><td>[`bool IsValid()`](VRageMath.IsValid)</td><td></td></tr>
<tr><td>[`bool IsNan()`](VRageMath.IsNan)</td><td></td></tr>
<tr><td>[`bool IsRotation()`](VRageMath.IsRotation)</td><td></td></tr>
<tr><td>static [`Matrix3x3 CreateFromDir(Vector3 dir)`](VRageMath.CreateFromDir)</td><td></td></tr>
<tr><td>static [`Matrix3x3 CreateWorld(ref Vector3 forward, ref Vector3 up)`](VRageMath.CreateWorld)</td><td>Creates a world matrix with the specified parameters.</td></tr>
<tr><td>static [`Matrix3x3 CreateFromDir(Vector3 dir, Vector3 suggestedUp)`](VRageMath.CreateFromDir)</td><td></td></tr>
<tr><td>static [`Matrix3x3 Normalize(Matrix3x3 matrix)`](VRageMath.Normalize)</td><td></td></tr>
<tr><td>static [`Matrix3x3 Orthogonalize(Matrix3x3 rotationMatrix)`](VRageMath.Orthogonalize)</td><td></td></tr>
<tr><td>static [`Matrix3x3 Round(ref Matrix3x3 matrix)`](VRageMath.Round)</td><td></td></tr>
<tr><td>static [`Matrix3x3 AlignRotationToAxes(ref Matrix3x3 toAlign, ref Matrix3x3 axisDefinitionMatrix)`](VRageMath.AlignRotationToAxes)</td><td></td></tr>
<tr><td>static [`bool GetEulerAnglesXYZ(ref Matrix3x3 mat, ref Vector3 xyz)`](VRageMath.GetEulerAnglesXYZ)</td><td></td></tr>
<tr><td>[`bool IsMirrored()`](VRageMath.IsMirrored)</td><td></td></tr>
<tr><td>[`bool IsOrthogonal()`](VRageMath.IsOrthogonal)</td><td></td></tr>
</table>
