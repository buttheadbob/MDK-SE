← [Index](index)
# Matrix3x3 Struct
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
|[`M21`](VRageMath.M21)|Value at row 2 column 1 of the matrix.|
|[`M22`](VRageMath.M22)|Value at row 2 column 2 of the matrix.|
|[`M23`](VRageMath.M23)|Value at row 2 column 3 of the matrix.|
|[`M31`](VRageMath.M31)|Value at row 3 column 1 of the matrix.|
|[`M32`](VRageMath.M32)|Value at row 3 column 2 of the matrix.|
|[`M33`](VRageMath.M33)|Value at row 3 column 3 of the matrix.|
|static [`Identity`](VRageMath.Identity)||
|static [`Zero`](VRageMath.Zero)||
### Properties
|Member|Description|
|---|---|
|[`Up`](VRageMath.Up)|Gets and sets the up vector of the Matrix3x3.|
|[`Down`](VRageMath.Down)|Gets and sets the down vector of the Matrix3x3.|
|[`Right`](VRageMath.Right)|Gets and sets the right vector of the Matrix3x3.|
|[`Col0`](VRageMath.Col0)||
|[`Col1`](VRageMath.Col1)||
|[`Col2`](VRageMath.Col2)||
|[`Left`](VRageMath.Left)|Gets and sets the left vector of the Matrix3x3.|
|[`Forward`](VRageMath.Forward)|Gets and sets the forward vector of the Matrix3x3.|
|[`Backward`](VRageMath.Backward)|Gets and sets the backward vector of the Matrix3x3.|
|[`Scale`](VRageMath.Scale)||
|[`Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|[`GetDirectionVector(Direction)`](VRageMath.GetDirectionVector)||
|[`SetDirectionVector(Direction, Vector3)`](VRageMath.SetDirectionVector)||
|[`GetClosestDirection(Vector3)`](VRageMath.GetClosestDirection)||
|[`GetClosestDirection(ref Vector3)`](VRageMath.GetClosestDirection)||
|static [`Rescale(ref Matrix3x3, float)`](VRageMath.Rescale)|Same result as Matrix3x3.CreateScale(scale) * matrix, but much faster|
|static [`Rescale(ref Matrix3x3, ref Vector3)`](VRageMath.Rescale)|Same result as Matrix3x3.CreateScale(scale) * matrix, but much faster|
|static [`Rescale(Matrix3x3, float)`](VRageMath.Rescale)||
|static [`Rescale(Matrix3x3, Vector3)`](VRageMath.Rescale)||
|static [`CreateScale(float, float, float)`](VRageMath.CreateScale)|Creates a scaling Matrix3x3.|
|static [`CreateScale(float, float, float, ref Matrix3x3)`](VRageMath.CreateScale)|Creates a scaling Matrix3x3.|
|static [`CreateScale(Vector3)`](VRageMath.CreateScale)|Creates a scaling Matrix3x3.|
|static [`CreateScale(ref Vector3, ref Matrix3x3)`](VRageMath.CreateScale)|Creates a scaling Matrix3x3.|
|static [`CreateScale(float)`](VRageMath.CreateScale)|Creates a scaling Matrix3x3.|
|static [`CreateScale(float, ref Matrix3x3)`](VRageMath.CreateScale)|Creates a scaling Matrix3x3.|
|static [`CreateRotationX(float)`](VRageMath.CreateRotationX)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|static [`CreateRotationX(float, ref Matrix3x3)`](VRageMath.CreateRotationX)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the x-axis.|
|static [`CreateRotationY(float)`](VRageMath.CreateRotationY)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|static [`CreateRotationY(float, ref Matrix3x3)`](VRageMath.CreateRotationY)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the y-axis.|
|static [`CreateRotationZ(float)`](VRageMath.CreateRotationZ)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|static [`CreateRotationZ(float, ref Matrix3x3)`](VRageMath.CreateRotationZ)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the z-axis.|
|static [`CreateFromAxisAngle(Vector3, float)`](VRageMath.CreateFromAxisAngle)|Creates a new Matrix3x3 that rotates around an arbitrary vector.|
|static [`CreateFromAxisAngle(ref Vector3, float, ref Matrix3x3)`](VRageMath.CreateFromAxisAngle)|Creates a new Matrix3x3 that rotates around an arbitrary vector.|
|static [`CreateRotationFromTwoVectors(ref Vector3, ref Vector3, ref Matrix3x3)`](VRageMath.CreateRotationFromTwoVectors)||
|static [`CreateFromQuaternion(Quaternion)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix3x3 from a Quaternion.|
|static [`CreateFromQuaternion(ref Quaternion, ref Matrix3x3)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix3x3 from a Quaternion.|
|static [`CreateFromYawPitchRoll(float, float, float)`](VRageMath.CreateFromYawPitchRoll)|Creates a new rotation matrix from a specified yaw, pitch, and roll.|
|static [`CreateFromYawPitchRoll(float, float, float, ref Matrix3x3)`](VRageMath.CreateFromYawPitchRoll)|Fills in a rotation matrix from a specified yaw, pitch, and roll.|
|static [`Transform(ref Matrix3x3, ref Quaternion, ref Matrix3x3)`](VRageMath.Transform)|Transforms a Matrix3x3 by applying a Quaternion rotation.|
|[`GetRow(int)`](VRageMath.GetRow)||
|[`SetRow(int, Vector3)`](VRageMath.SetRow)||
|[`ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`Equals(Matrix3x3)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Matrix3x3.|
|[`EqualsFast(ref Matrix3x3, float)`](VRageMath.EqualsFast)|Compares just position, forward and up|
|[`Equals(Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of this object.|
|static [`Transpose(ref Matrix3x3, ref Matrix3x3)`](VRageMath.Transpose)|Transposes the rows and columns of a matrix.|
|[`Transpose()`](VRageMath.Transpose)||
|[`Determinant()`](VRageMath.Determinant)||
|static [`Invert(ref Matrix3x3, ref Matrix3x3)`](VRageMath.Invert)|Calculates the inverse of a matrix.|
|static [`Lerp(ref Matrix3x3, ref Matrix3x3, float, ref Matrix3x3)`](VRageMath.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|static [`Slerp(ref Matrix3x3, ref Matrix3x3, float, ref Matrix3x3)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|static [`SlerpScale(ref Matrix3x3, ref Matrix3x3, float, ref Matrix3x3)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static [`Negate(ref Matrix3x3, ref Matrix3x3)`](VRageMath.Negate)|Negates individual elements of a matrix.|
|static [`Add(ref Matrix3x3, ref Matrix3x3, ref Matrix3x3)`](VRageMath.Add)|Adds a matrix to another matrix.|
|static [`Subtract(ref Matrix3x3, ref Matrix3x3, ref Matrix3x3)`](VRageMath.Subtract)|Subtracts matrices.|
|static [`Multiply(ref Matrix3x3, ref Matrix3x3, ref Matrix3x3)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static [`Multiply(ref Matrix3x3, float, ref Matrix3x3)`](VRageMath.Multiply)|Multiplies a matrix by a scalar value.|
|static [`Divide(ref Matrix3x3, ref Matrix3x3, ref Matrix3x3)`](VRageMath.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|static [`Divide(ref Matrix3x3, float, ref Matrix3x3)`](VRageMath.Divide)|Divides the components of a matrix by a scalar.|
|[`GetOrientation()`](VRageMath.GetOrientation)|Gets the orientation.|
|[`AssertIsValid()`](VRageMath.AssertIsValid)||
|[`IsValid()`](VRageMath.IsValid)||
|[`IsNan()`](VRageMath.IsNan)||
|[`IsRotation()`](VRageMath.IsRotation)||
|static [`CreateFromDir(Vector3)`](VRageMath.CreateFromDir)||
|static [`CreateWorld(ref Vector3, ref Vector3)`](VRageMath.CreateWorld)|Creates a world matrix with the specified parameters.|
|static [`CreateFromDir(Vector3, Vector3)`](VRageMath.CreateFromDir)||
|static [`Normalize(Matrix3x3)`](VRageMath.Normalize)||
|static [`Orthogonalize(Matrix3x3)`](VRageMath.Orthogonalize)||
|static [`Round(ref Matrix3x3)`](VRageMath.Round)||
|static [`AlignRotationToAxes(ref Matrix3x3, ref Matrix3x3)`](VRageMath.AlignRotationToAxes)||
|static [`GetEulerAnglesXYZ(ref Matrix3x3, ref Vector3)`](VRageMath.GetEulerAnglesXYZ)||
|[`IsMirrored()`](VRageMath.IsMirrored)||
|[`IsOrthogonal()`](VRageMath.IsOrthogonal)||
