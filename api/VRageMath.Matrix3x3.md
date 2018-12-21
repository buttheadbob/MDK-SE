← [Index](index)
# Matrix3x3 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a matrix.
### Fields
|Member|Description|
|---|---|
|[`float M11`](VRageMath.M11)|Value at row 1 column 1 of the matrix.|
|[`float M12`](VRageMath.M12)|Value at row 1 column 2 of the matrix.|
|[`float M13`](VRageMath.M13)|Value at row 1 column 3 of the matrix.|
|[`float M21`](VRageMath.M21)|Value at row 2 column 1 of the matrix.|
|[`float M22`](VRageMath.M22)|Value at row 2 column 2 of the matrix.|
|[`float M23`](VRageMath.M23)|Value at row 2 column 3 of the matrix.|
|[`float M31`](VRageMath.M31)|Value at row 3 column 1 of the matrix.|
|[`float M32`](VRageMath.M32)|Value at row 3 column 2 of the matrix.|
|[`float M33`](VRageMath.M33)|Value at row 3 column 3 of the matrix.|
|static [`Matrix3x3 Identity`](VRageMath.Identity)||
|static [`Matrix3x3 Zero`](VRageMath.Zero)||
### Properties
|Member|Description|
|---|---|
|[`Vector3 Up`](VRageMath.Up)|Gets and sets the up vector of the Matrix3x3.|
|[`Vector3 Down`](VRageMath.Down)|Gets and sets the down vector of the Matrix3x3.|
|[`Vector3 Right`](VRageMath.Right)|Gets and sets the right vector of the Matrix3x3.|
|[`Vector3 Col0`](VRageMath.Col0)||
|[`Vector3 Col1`](VRageMath.Col1)||
|[`Vector3 Col2`](VRageMath.Col2)||
|[`Vector3 Left`](VRageMath.Left)|Gets and sets the left vector of the Matrix3x3.|
|[`Vector3 Forward`](VRageMath.Forward)|Gets and sets the forward vector of the Matrix3x3.|
|[`Vector3 Backward`](VRageMath.Backward)|Gets and sets the backward vector of the Matrix3x3.|
|[`Vector3 Scale`](VRageMath.Scale)||
|[`float Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|[`Vector3 GetDirectionVector(Direction direction)`](VRageMath.GetDirectionVector)||
|[`void SetDirectionVector(Direction direction, Vector3 newValue)`](VRageMath.SetDirectionVector)||
|[`Direction GetClosestDirection(Vector3 referenceVector)`](VRageMath.GetClosestDirection)||
|[`Direction GetClosestDirection(ref Vector3 referenceVector)`](VRageMath.GetClosestDirection)||
|static [`void Rescale(ref Matrix3x3 matrix, float scale)`](VRageMath.Rescale)|Same result as Matrix3x3.CreateScale(scale) * matrix, but much faster|
|static [`void Rescale(ref Matrix3x3 matrix, ref Vector3 scale)`](VRageMath.Rescale)|Same result as Matrix3x3.CreateScale(scale) * matrix, but much faster|
|static [`Matrix3x3 Rescale(Matrix3x3 matrix, float scale)`](VRageMath.Rescale)||
|static [`Matrix3x3 Rescale(Matrix3x3 matrix, Vector3 scale)`](VRageMath.Rescale)||
|static [`Matrix3x3 CreateScale(float xScale, float yScale, float zScale)`](VRageMath.CreateScale)|Creates a scaling Matrix3x3.|
|static [`void CreateScale(float xScale, float yScale, float zScale, ref Matrix3x3 result)`](VRageMath.CreateScale)|Creates a scaling Matrix3x3.|
|static [`Matrix3x3 CreateScale(Vector3 scales)`](VRageMath.CreateScale)|Creates a scaling Matrix3x3.|
|static [`void CreateScale(ref Vector3 scales, ref Matrix3x3 result)`](VRageMath.CreateScale)|Creates a scaling Matrix3x3.|
|static [`Matrix3x3 CreateScale(float scale)`](VRageMath.CreateScale)|Creates a scaling Matrix3x3.|
|static [`void CreateScale(float scale, ref Matrix3x3 result)`](VRageMath.CreateScale)|Creates a scaling Matrix3x3.|
|static [`Matrix3x3 CreateRotationX(float radians)`](VRageMath.CreateRotationX)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|static [`void CreateRotationX(float radians, ref Matrix3x3 result)`](VRageMath.CreateRotationX)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the x-axis.|
|static [`Matrix3x3 CreateRotationY(float radians)`](VRageMath.CreateRotationY)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|static [`void CreateRotationY(float radians, ref Matrix3x3 result)`](VRageMath.CreateRotationY)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the y-axis.|
|static [`Matrix3x3 CreateRotationZ(float radians)`](VRageMath.CreateRotationZ)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|static [`void CreateRotationZ(float radians, ref Matrix3x3 result)`](VRageMath.CreateRotationZ)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the z-axis.|
|static [`Matrix3x3 CreateFromAxisAngle(Vector3 axis, float angle)`](VRageMath.CreateFromAxisAngle)|Creates a new Matrix3x3 that rotates around an arbitrary vector.|
|static [`void CreateFromAxisAngle(ref Vector3 axis, float angle, ref Matrix3x3 result)`](VRageMath.CreateFromAxisAngle)|Creates a new Matrix3x3 that rotates around an arbitrary vector.|
|static [`void CreateRotationFromTwoVectors(ref Vector3 fromVector, ref Vector3 toVector, ref Matrix3x3 resultMatrix)`](VRageMath.CreateRotationFromTwoVectors)||
|static [`Matrix3x3 CreateFromQuaternion(Quaternion quaternion)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix3x3 from a Quaternion.|
|static [`void CreateFromQuaternion(ref Quaternion quaternion, ref Matrix3x3 result)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix3x3 from a Quaternion.|
|static [`Matrix3x3 CreateFromYawPitchRoll(float yaw, float pitch, float roll)`](VRageMath.CreateFromYawPitchRoll)|Creates a new rotation matrix from a specified yaw, pitch, and roll.|
|static [`void CreateFromYawPitchRoll(float yaw, float pitch, float roll, ref Matrix3x3 result)`](VRageMath.CreateFromYawPitchRoll)|Fills in a rotation matrix from a specified yaw, pitch, and roll.|
|static [`void Transform(ref Matrix3x3 value, ref Quaternion rotation, ref Matrix3x3 result)`](VRageMath.Transform)|Transforms a Matrix3x3 by applying a Quaternion rotation.|
|[`Vector3 GetRow(int row)`](VRageMath.GetRow)||
|[`void SetRow(int row, Vector3 value)`](VRageMath.SetRow)||
|[`string ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`bool Equals(Matrix3x3 other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Matrix3x3.|
|[`bool EqualsFast(ref Matrix3x3 other, float epsilon)`](VRageMath.EqualsFast)|Compares just position, forward and up|
|[`bool Equals(Object obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of this object.|
|static [`void Transpose(ref Matrix3x3 matrix, ref Matrix3x3 result)`](VRageMath.Transpose)|Transposes the rows and columns of a matrix.|
|[`void Transpose()`](VRageMath.Transpose)||
|[`float Determinant()`](VRageMath.Determinant)||
|static [`void Invert(ref Matrix3x3 matrix, ref Matrix3x3 result)`](VRageMath.Invert)|Calculates the inverse of a matrix.|
|static [`void Lerp(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, float amount, ref Matrix3x3 result)`](VRageMath.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|static [`void Slerp(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, float amount, ref Matrix3x3 result)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|static [`void SlerpScale(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, float amount, ref Matrix3x3 result)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static [`void Negate(ref Matrix3x3 matrix, ref Matrix3x3 result)`](VRageMath.Negate)|Negates individual elements of a matrix.|
|static [`void Add(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, ref Matrix3x3 result)`](VRageMath.Add)|Adds a matrix to another matrix.|
|static [`void Subtract(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, ref Matrix3x3 result)`](VRageMath.Subtract)|Subtracts matrices.|
|static [`void Multiply(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, ref Matrix3x3 result)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static [`void Multiply(ref Matrix3x3 matrix1, float scaleFactor, ref Matrix3x3 result)`](VRageMath.Multiply)|Multiplies a matrix by a scalar value.|
|static [`void Divide(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, ref Matrix3x3 result)`](VRageMath.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|static [`void Divide(ref Matrix3x3 matrix1, float divider, ref Matrix3x3 result)`](VRageMath.Divide)|Divides the components of a matrix by a scalar.|
|[`Matrix3x3 GetOrientation()`](VRageMath.GetOrientation)|Gets the orientation.|
|[`void AssertIsValid()`](VRageMath.AssertIsValid)||
|[`bool IsValid()`](VRageMath.IsValid)||
|[`bool IsNan()`](VRageMath.IsNan)||
|[`bool IsRotation()`](VRageMath.IsRotation)||
|static [`Matrix3x3 CreateFromDir(Vector3 dir)`](VRageMath.CreateFromDir)||
|static [`Matrix3x3 CreateWorld(ref Vector3 forward, ref Vector3 up)`](VRageMath.CreateWorld)|Creates a world matrix with the specified parameters.|
|static [`Matrix3x3 CreateFromDir(Vector3 dir, Vector3 suggestedUp)`](VRageMath.CreateFromDir)||
|static [`Matrix3x3 Normalize(Matrix3x3 matrix)`](VRageMath.Normalize)||
|static [`Matrix3x3 Orthogonalize(Matrix3x3 rotationMatrix)`](VRageMath.Orthogonalize)||
|static [`Matrix3x3 Round(ref Matrix3x3 matrix)`](VRageMath.Round)||
|static [`Matrix3x3 AlignRotationToAxes(ref Matrix3x3 toAlign, ref Matrix3x3 axisDefinitionMatrix)`](VRageMath.AlignRotationToAxes)||
|static [`bool GetEulerAnglesXYZ(ref Matrix3x3 mat, ref Vector3 xyz)`](VRageMath.GetEulerAnglesXYZ)||
|[`bool IsMirrored()`](VRageMath.IsMirrored)||
|[`bool IsOrthogonal()`](VRageMath.IsOrthogonal)||
