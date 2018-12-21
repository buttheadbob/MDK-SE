← [Index](index)
# Matrix3x3 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a matrix.
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.M11"><code>float M11</code></a>_</td><td>Value at row 1 column 1 of the matrix.</td></tr>
<tr><td>_<a href="VRageMath.M12"><code>float M12</code></a>_</td><td>Value at row 1 column 2 of the matrix.</td></tr>
<tr><td>_<a href="VRageMath.M13"><code>float M13</code></a>_</td><td>Value at row 1 column 3 of the matrix.</td></tr>
<tr><td>_<a href="VRageMath.M21"><code>float M21</code></a>_</td><td>Value at row 2 column 1 of the matrix.</td></tr>
<tr><td>_<a href="VRageMath.M22"><code>float M22</code></a>_</td><td>Value at row 2 column 2 of the matrix.</td></tr>
<tr><td>_<a href="VRageMath.M23"><code>float M23</code></a>_</td><td>Value at row 2 column 3 of the matrix.</td></tr>
<tr><td>_<a href="VRageMath.M31"><code>float M31</code></a>_</td><td>Value at row 3 column 1 of the matrix.</td></tr>
<tr><td>_<a href="VRageMath.M32"><code>float M32</code></a>_</td><td>Value at row 3 column 2 of the matrix.</td></tr>
<tr><td>_<a href="VRageMath.M33"><code>float M33</code></a>_</td><td>Value at row 3 column 3 of the matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Identity"><code>Matrix3x3 Identity</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Zero"><code>Matrix3x3 Zero</code></a>_</td><td></td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Up"><code>Vector3 Up</code></a>_</td><td>Gets and sets the up vector of the Matrix3x3.</td></tr>
<tr><td>_<a href="VRageMath.Down"><code>Vector3 Down</code></a>_</td><td>Gets and sets the down vector of the Matrix3x3.</td></tr>
<tr><td>_<a href="VRageMath.Right"><code>Vector3 Right</code></a>_</td><td>Gets and sets the right vector of the Matrix3x3.</td></tr>
<tr><td>_<a href="VRageMath.Col0"><code>Vector3 Col0</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Col1"><code>Vector3 Col1</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Col2"><code>Vector3 Col2</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Left"><code>Vector3 Left</code></a>_</td><td>Gets and sets the left vector of the Matrix3x3.</td></tr>
<tr><td>_<a href="VRageMath.Forward"><code>Vector3 Forward</code></a>_</td><td>Gets and sets the forward vector of the Matrix3x3.</td></tr>
<tr><td>_<a href="VRageMath.Backward"><code>Vector3 Backward</code></a>_</td><td>Gets and sets the backward vector of the Matrix3x3.</td></tr>
<tr><td>_<a href="VRageMath.Scale"><code>Vector3 Scale</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Item"><code>float Item</code></a>_</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.GetDirectionVector"><code>Vector3 GetDirectionVector(Direction direction)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.SetDirectionVector"><code>void SetDirectionVector(Direction direction, Vector3 newValue)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.GetClosestDirection"><code>Direction GetClosestDirection(Vector3 referenceVector)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.GetClosestDirection"><code>Direction GetClosestDirection(ref Vector3 referenceVector)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Rescale"><code>void Rescale(ref Matrix3x3 matrix, float scale)</code></a>_</td><td>Same result as Matrix3x3.CreateScale(scale) * matrix, but much faster</td></tr>
<tr><td>static _<a href="VRageMath.Rescale"><code>void Rescale(ref Matrix3x3 matrix, ref Vector3 scale)</code></a>_</td><td>Same result as Matrix3x3.CreateScale(scale) * matrix, but much faster</td></tr>
<tr><td>static _<a href="VRageMath.Rescale"><code>Matrix3x3 Rescale(Matrix3x3 matrix, float scale)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Rescale"><code>Matrix3x3 Rescale(Matrix3x3 matrix, Vector3 scale)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CreateScale"><code>Matrix3x3 CreateScale(float xScale, float yScale, float zScale)</code></a>_</td><td>Creates a scaling Matrix3x3.</td></tr>
<tr><td>static _<a href="VRageMath.CreateScale"><code>void CreateScale(float xScale, float yScale, float zScale, ref Matrix3x3 result)</code></a>_</td><td>Creates a scaling Matrix3x3.</td></tr>
<tr><td>static _<a href="VRageMath.CreateScale"><code>Matrix3x3 CreateScale(Vector3 scales)</code></a>_</td><td>Creates a scaling Matrix3x3.</td></tr>
<tr><td>static _<a href="VRageMath.CreateScale"><code>void CreateScale(ref Vector3 scales, ref Matrix3x3 result)</code></a>_</td><td>Creates a scaling Matrix3x3.</td></tr>
<tr><td>static _<a href="VRageMath.CreateScale"><code>Matrix3x3 CreateScale(float scale)</code></a>_</td><td>Creates a scaling Matrix3x3.</td></tr>
<tr><td>static _<a href="VRageMath.CreateScale"><code>void CreateScale(float scale, ref Matrix3x3 result)</code></a>_</td><td>Creates a scaling Matrix3x3.</td></tr>
<tr><td>static _<a href="VRageMath.CreateRotationX"><code>Matrix3x3 CreateRotationX(float radians)</code></a>_</td><td>Returns a matrix that can be used to rotate a set of vertices around the x-axis.</td></tr>
<tr><td>static _<a href="VRageMath.CreateRotationX"><code>void CreateRotationX(float radians, ref Matrix3x3 result)</code></a>_</td><td>Populates data into a user-specified matrix that can be used to rotate a set of vertices around the x-axis.</td></tr>
<tr><td>static _<a href="VRageMath.CreateRotationY"><code>Matrix3x3 CreateRotationY(float radians)</code></a>_</td><td>Returns a matrix that can be used to rotate a set of vertices around the y-axis.</td></tr>
<tr><td>static _<a href="VRageMath.CreateRotationY"><code>void CreateRotationY(float radians, ref Matrix3x3 result)</code></a>_</td><td>Populates data into a user-specified matrix that can be used to rotate a set of vertices around the y-axis.</td></tr>
<tr><td>static _<a href="VRageMath.CreateRotationZ"><code>Matrix3x3 CreateRotationZ(float radians)</code></a>_</td><td>Returns a matrix that can be used to rotate a set of vertices around the z-axis.</td></tr>
<tr><td>static _<a href="VRageMath.CreateRotationZ"><code>void CreateRotationZ(float radians, ref Matrix3x3 result)</code></a>_</td><td>Populates data into a user-specified matrix that can be used to rotate a set of vertices around the z-axis.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromAxisAngle"><code>Matrix3x3 CreateFromAxisAngle(Vector3 axis, float angle)</code></a>_</td><td>Creates a new Matrix3x3 that rotates around an arbitrary vector.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromAxisAngle"><code>void CreateFromAxisAngle(ref Vector3 axis, float angle, ref Matrix3x3 result)</code></a>_</td><td>Creates a new Matrix3x3 that rotates around an arbitrary vector.</td></tr>
<tr><td>static _<a href="VRageMath.CreateRotationFromTwoVectors"><code>void CreateRotationFromTwoVectors(ref Vector3 fromVector, ref Vector3 toVector, ref Matrix3x3 resultMatrix)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CreateFromQuaternion"><code>Matrix3x3 CreateFromQuaternion(Quaternion quaternion)</code></a>_</td><td>Creates a rotation Matrix3x3 from a Quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromQuaternion"><code>void CreateFromQuaternion(ref Quaternion quaternion, ref Matrix3x3 result)</code></a>_</td><td>Creates a rotation Matrix3x3 from a Quaternion.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromYawPitchRoll"><code>Matrix3x3 CreateFromYawPitchRoll(float yaw, float pitch, float roll)</code></a>_</td><td>Creates a new rotation matrix from a specified yaw, pitch, and roll.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromYawPitchRoll"><code>void CreateFromYawPitchRoll(float yaw, float pitch, float roll, ref Matrix3x3 result)</code></a>_</td><td>Fills in a rotation matrix from a specified yaw, pitch, and roll.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(ref Matrix3x3 value, ref Quaternion rotation, ref Matrix3x3 result)</code></a>_</td><td>Transforms a Matrix3x3 by applying a Quaternion rotation.</td></tr>
<tr><td>_<a href="VRageMath.GetRow"><code>Vector3 GetRow(int row)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.SetRow"><code>void SetRow(int row, Vector3 value)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.ToString"><code>string ToString()</code></a>_</td><td>Retrieves a string representation of the current object.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Matrix3x3 other)</code></a>_</td><td>Determines whether the specified Object is equal to the Matrix3x3.</td></tr>
<tr><td>_<a href="VRageMath.EqualsFast"><code>bool EqualsFast(ref Matrix3x3 other, float epsilon)</code></a>_</td><td>Compares just position, forward and up</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Object obj)</code></a>_</td><td>Returns a value that indicates whether the current instance is equal to a specified object.</td></tr>
<tr><td>_<a href="VRageMath.GetHashCode"><code>int GetHashCode()</code></a>_</td><td>Gets the hash code of this object.</td></tr>
<tr><td>static _<a href="VRageMath.Transpose"><code>void Transpose(ref Matrix3x3 matrix, ref Matrix3x3 result)</code></a>_</td><td>Transposes the rows and columns of a matrix.</td></tr>
<tr><td>_<a href="VRageMath.Transpose"><code>void Transpose()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Determinant"><code>float Determinant()</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Invert"><code>void Invert(ref Matrix3x3 matrix, ref Matrix3x3 result)</code></a>_</td><td>Calculates the inverse of a matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Lerp"><code>void Lerp(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, float amount, ref Matrix3x3 result)</code></a>_</td><td>Linearly interpolates between the corresponding values of two matrices.</td></tr>
<tr><td>static _<a href="VRageMath.Slerp"><code>void Slerp(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, float amount, ref Matrix3x3 result)</code></a>_</td><td>Performs spherical linear interpolation of position and rotation.</td></tr>
<tr><td>static _<a href="VRageMath.SlerpScale"><code>void SlerpScale(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, float amount, ref Matrix3x3 result)</code></a>_</td><td>Performs spherical linear interpolation of position and rotation and scale.</td></tr>
<tr><td>static _<a href="VRageMath.Negate"><code>void Negate(ref Matrix3x3 matrix, ref Matrix3x3 result)</code></a>_</td><td>Negates individual elements of a matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Add"><code>void Add(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, ref Matrix3x3 result)</code></a>_</td><td>Adds a matrix to another matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Subtract"><code>void Subtract(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, ref Matrix3x3 result)</code></a>_</td><td>Subtracts matrices.</td></tr>
<tr><td>static _<a href="VRageMath.Multiply"><code>void Multiply(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, ref Matrix3x3 result)</code></a>_</td><td>Multiplies a matrix by another matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Multiply"><code>void Multiply(ref Matrix3x3 matrix1, float scaleFactor, ref Matrix3x3 result)</code></a>_</td><td>Multiplies a matrix by a scalar value.</td></tr>
<tr><td>static _<a href="VRageMath.Divide"><code>void Divide(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, ref Matrix3x3 result)</code></a>_</td><td>Divides the components of a matrix by the corresponding components of another matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Divide"><code>void Divide(ref Matrix3x3 matrix1, float divider, ref Matrix3x3 result)</code></a>_</td><td>Divides the components of a matrix by a scalar.</td></tr>
<tr><td>_<a href="VRageMath.GetOrientation"><code>Matrix3x3 GetOrientation()</code></a>_</td><td>Gets the orientation.</td></tr>
<tr><td>_<a href="VRageMath.AssertIsValid"><code>void AssertIsValid()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.IsValid"><code>bool IsValid()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.IsNan"><code>bool IsNan()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.IsRotation"><code>bool IsRotation()</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CreateFromDir"><code>Matrix3x3 CreateFromDir(Vector3 dir)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CreateWorld"><code>Matrix3x3 CreateWorld(ref Vector3 forward, ref Vector3 up)</code></a>_</td><td>Creates a world matrix with the specified parameters.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromDir"><code>Matrix3x3 CreateFromDir(Vector3 dir, Vector3 suggestedUp)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Normalize"><code>Matrix3x3 Normalize(Matrix3x3 matrix)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Orthogonalize"><code>Matrix3x3 Orthogonalize(Matrix3x3 rotationMatrix)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Round"><code>Matrix3x3 Round(ref Matrix3x3 matrix)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.AlignRotationToAxes"><code>Matrix3x3 AlignRotationToAxes(ref Matrix3x3 toAlign, ref Matrix3x3 axisDefinitionMatrix)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetEulerAnglesXYZ"><code>bool GetEulerAnglesXYZ(ref Matrix3x3 mat, ref Vector3 xyz)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.IsMirrored"><code>bool IsMirrored()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.IsOrthogonal"><code>bool IsOrthogonal()</code></a>_</td><td></td></tr>
</table>
