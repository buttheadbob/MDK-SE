← [Index](index)
# Matrix3x3 Struct
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
|[`float M21`](VRageMath.M21)|Value at row 2 column 1 of the matrix.|
|[`float M22`](VRageMath.M22)|Value at row 2 column 2 of the matrix.|
|[`float M23`](VRageMath.M23)|Value at row 2 column 3 of the matrix.|
|[`float M31`](VRageMath.M31)|Value at row 3 column 1 of the matrix.|
|[`float M32`](VRageMath.M32)|Value at row 3 column 2 of the matrix.|
|[`float M33`](VRageMath.M33)|Value at row 3 column 3 of the matrix.|
|static [`VRageMath.Matrix3x3 Identity`](VRageMath.Identity)||
|static [`VRageMath.Matrix3x3 Zero`](VRageMath.Zero)||
### Properties
|Member|Description|
|---|---|
|[`VRageMath.Vector3 Up`](VRageMath.Up)|Gets and sets the up vector of the Matrix3x3.|
|[`VRageMath.Vector3 Down`](VRageMath.Down)|Gets and sets the down vector of the Matrix3x3.|
|[`VRageMath.Vector3 Right`](VRageMath.Right)|Gets and sets the right vector of the Matrix3x3.|
|[`VRageMath.Vector3 Col0`](VRageMath.Col0)||
|[`VRageMath.Vector3 Col1`](VRageMath.Col1)||
|[`VRageMath.Vector3 Col2`](VRageMath.Col2)||
|[`VRageMath.Vector3 Left`](VRageMath.Left)|Gets and sets the left vector of the Matrix3x3.|
|[`VRageMath.Vector3 Forward`](VRageMath.Forward)|Gets and sets the forward vector of the Matrix3x3.|
|[`VRageMath.Vector3 Backward`](VRageMath.Backward)|Gets and sets the backward vector of the Matrix3x3.|
|[`VRageMath.Vector3 Scale`](VRageMath.Scale)||
|[`float Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|[`VRageMath.Vector3 GetDirectionVector(VRageMath.Direction)`](VRageMath.GetDirectionVector)||
|[`void SetDirectionVector(VRageMath.Direction, VRageMath.Vector3)`](VRageMath.SetDirectionVector)||
|[`VRageMath.Direction GetClosestDirection(VRageMath.Vector3)`](VRageMath.GetClosestDirection)||
|[`VRageMath.Direction GetClosestDirection(ref VRageMath.Vector3)`](VRageMath.GetClosestDirection)||
|static [`void Rescale(ref VRageMath.Matrix3x3, float)`](VRageMath.Rescale)|Same result as Matrix3x3.CreateScale(scale) * matrix, but much faster|
|static [`void Rescale(ref VRageMath.Matrix3x3, ref VRageMath.Vector3)`](VRageMath.Rescale)|Same result as Matrix3x3.CreateScale(scale) * matrix, but much faster|
|static [`VRageMath.Matrix3x3 Rescale(VRageMath.Matrix3x3, float)`](VRageMath.Rescale)||
|static [`VRageMath.Matrix3x3 Rescale(VRageMath.Matrix3x3, VRageMath.Vector3)`](VRageMath.Rescale)||
|static [`VRageMath.Matrix3x3 CreateScale(float, float, float)`](VRageMath.CreateScale)|Creates a scaling Matrix3x3.|
|static [`void CreateScale(float, float, float, ref VRageMath.Matrix3x3)`](VRageMath.CreateScale)|Creates a scaling Matrix3x3.|
|static [`VRageMath.Matrix3x3 CreateScale(VRageMath.Vector3)`](VRageMath.CreateScale)|Creates a scaling Matrix3x3.|
|static [`void CreateScale(ref VRageMath.Vector3, ref VRageMath.Matrix3x3)`](VRageMath.CreateScale)|Creates a scaling Matrix3x3.|
|static [`VRageMath.Matrix3x3 CreateScale(float)`](VRageMath.CreateScale)|Creates a scaling Matrix3x3.|
|static [`void CreateScale(float, ref VRageMath.Matrix3x3)`](VRageMath.CreateScale)|Creates a scaling Matrix3x3.|
|static [`VRageMath.Matrix3x3 CreateRotationX(float)`](VRageMath.CreateRotationX)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|static [`void CreateRotationX(float, ref VRageMath.Matrix3x3)`](VRageMath.CreateRotationX)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the x-axis.|
|static [`VRageMath.Matrix3x3 CreateRotationY(float)`](VRageMath.CreateRotationY)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|static [`void CreateRotationY(float, ref VRageMath.Matrix3x3)`](VRageMath.CreateRotationY)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the y-axis.|
|static [`VRageMath.Matrix3x3 CreateRotationZ(float)`](VRageMath.CreateRotationZ)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|static [`void CreateRotationZ(float, ref VRageMath.Matrix3x3)`](VRageMath.CreateRotationZ)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the z-axis.|
|static [`VRageMath.Matrix3x3 CreateFromAxisAngle(VRageMath.Vector3, float)`](VRageMath.CreateFromAxisAngle)|Creates a new Matrix3x3 that rotates around an arbitrary vector.|
|static [`void CreateFromAxisAngle(ref VRageMath.Vector3, float, ref VRageMath.Matrix3x3)`](VRageMath.CreateFromAxisAngle)|Creates a new Matrix3x3 that rotates around an arbitrary vector.|
|static [`void CreateRotationFromTwoVectors(ref VRageMath.Vector3, ref VRageMath.Vector3, ref VRageMath.Matrix3x3)`](VRageMath.CreateRotationFromTwoVectors)||
|static [`VRageMath.Matrix3x3 CreateFromQuaternion(VRageMath.Quaternion)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix3x3 from a Quaternion.|
|static [`void CreateFromQuaternion(ref VRageMath.Quaternion, ref VRageMath.Matrix3x3)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix3x3 from a Quaternion.|
|static [`VRageMath.Matrix3x3 CreateFromYawPitchRoll(float, float, float)`](VRageMath.CreateFromYawPitchRoll)|Creates a new rotation matrix from a specified yaw, pitch, and roll.|
|static [`void CreateFromYawPitchRoll(float, float, float, ref VRageMath.Matrix3x3)`](VRageMath.CreateFromYawPitchRoll)|Fills in a rotation matrix from a specified yaw, pitch, and roll.|
|static [`void Transform(ref VRageMath.Matrix3x3, ref VRageMath.Quaternion, ref VRageMath.Matrix3x3)`](VRageMath.Transform)|Transforms a Matrix3x3 by applying a Quaternion rotation.|
|[`VRageMath.Vector3 GetRow(int)`](VRageMath.GetRow)||
|[`void SetRow(int, VRageMath.Vector3)`](VRageMath.SetRow)||
|[`string ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`bool Equals(VRageMath.Matrix3x3)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Matrix3x3.|
|[`bool EqualsFast(ref VRageMath.Matrix3x3, float)`](VRageMath.EqualsFast)|Compares just position, forward and up|
|[`bool Equals(System.Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of this object.|
|static [`void Transpose(ref VRageMath.Matrix3x3, ref VRageMath.Matrix3x3)`](VRageMath.Transpose)|Transposes the rows and columns of a matrix.|
|[`void Transpose()`](VRageMath.Transpose)||
|[`float Determinant()`](VRageMath.Determinant)||
|static [`void Invert(ref VRageMath.Matrix3x3, ref VRageMath.Matrix3x3)`](VRageMath.Invert)|Calculates the inverse of a matrix.|
|static [`void Lerp(ref VRageMath.Matrix3x3, ref VRageMath.Matrix3x3, float, ref VRageMath.Matrix3x3)`](VRageMath.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|static [`void Slerp(ref VRageMath.Matrix3x3, ref VRageMath.Matrix3x3, float, ref VRageMath.Matrix3x3)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|static [`void SlerpScale(ref VRageMath.Matrix3x3, ref VRageMath.Matrix3x3, float, ref VRageMath.Matrix3x3)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static [`void Negate(ref VRageMath.Matrix3x3, ref VRageMath.Matrix3x3)`](VRageMath.Negate)|Negates individual elements of a matrix.|
|static [`void Add(ref VRageMath.Matrix3x3, ref VRageMath.Matrix3x3, ref VRageMath.Matrix3x3)`](VRageMath.Add)|Adds a matrix to another matrix.|
|static [`void Subtract(ref VRageMath.Matrix3x3, ref VRageMath.Matrix3x3, ref VRageMath.Matrix3x3)`](VRageMath.Subtract)|Subtracts matrices.|
|static [`void Multiply(ref VRageMath.Matrix3x3, ref VRageMath.Matrix3x3, ref VRageMath.Matrix3x3)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static [`void Multiply(ref VRageMath.Matrix3x3, float, ref VRageMath.Matrix3x3)`](VRageMath.Multiply)|Multiplies a matrix by a scalar value.|
|static [`void Divide(ref VRageMath.Matrix3x3, ref VRageMath.Matrix3x3, ref VRageMath.Matrix3x3)`](VRageMath.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|static [`void Divide(ref VRageMath.Matrix3x3, float, ref VRageMath.Matrix3x3)`](VRageMath.Divide)|Divides the components of a matrix by a scalar.|
|[`VRageMath.Matrix3x3 GetOrientation()`](VRageMath.GetOrientation)|Gets the orientation.|
|[`void AssertIsValid()`](VRageMath.AssertIsValid)||
|[`bool IsValid()`](VRageMath.IsValid)||
|[`bool IsNan()`](VRageMath.IsNan)||
|[`bool IsRotation()`](VRageMath.IsRotation)||
|static [`VRageMath.Matrix3x3 CreateFromDir(VRageMath.Vector3)`](VRageMath.CreateFromDir)||
|static [`VRageMath.Matrix3x3 CreateWorld(ref VRageMath.Vector3, ref VRageMath.Vector3)`](VRageMath.CreateWorld)|Creates a world matrix with the specified parameters.|
|static [`VRageMath.Matrix3x3 CreateFromDir(VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.CreateFromDir)||
|static [`VRageMath.Matrix3x3 Normalize(VRageMath.Matrix3x3)`](VRageMath.Normalize)||
|static [`VRageMath.Matrix3x3 Orthogonalize(VRageMath.Matrix3x3)`](VRageMath.Orthogonalize)||
|static [`VRageMath.Matrix3x3 Round(ref VRageMath.Matrix3x3)`](VRageMath.Round)||
|static [`VRageMath.Matrix3x3 AlignRotationToAxes(ref VRageMath.Matrix3x3, ref VRageMath.Matrix3x3)`](VRageMath.AlignRotationToAxes)||
|static [`bool GetEulerAnglesXYZ(ref VRageMath.Matrix3x3, ref VRageMath.Vector3)`](VRageMath.GetEulerAnglesXYZ)||
|[`bool IsMirrored()`](VRageMath.IsMirrored)||
|[`bool IsOrthogonal()`](VRageMath.IsOrthogonal)||
