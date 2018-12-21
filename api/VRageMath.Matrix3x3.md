← [Index](index)
# Matrix3x3 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a matrix.
### Fields
|Member|Description|
|---|---|
|[`float&nbsp;M11`](VRageMath.M11)|Value at row 1 column 1 of the matrix.|
|[`float&nbsp;M12`](VRageMath.M12)|Value at row 1 column 2 of the matrix.|
|[`float&nbsp;M13`](VRageMath.M13)|Value at row 1 column 3 of the matrix.|
|[`float&nbsp;M21`](VRageMath.M21)|Value at row 2 column 1 of the matrix.|
|[`float&nbsp;M22`](VRageMath.M22)|Value at row 2 column 2 of the matrix.|
|[`float&nbsp;M23`](VRageMath.M23)|Value at row 2 column 3 of the matrix.|
|[`float&nbsp;M31`](VRageMath.M31)|Value at row 3 column 1 of the matrix.|
|[`float&nbsp;M32`](VRageMath.M32)|Value at row 3 column 2 of the matrix.|
|[`float&nbsp;M33`](VRageMath.M33)|Value at row 3 column 3 of the matrix.|
|static&nbsp;[`Matrix3x3&nbsp;Identity`](VRageMath.Identity)||
|static&nbsp;[`Matrix3x3&nbsp;Zero`](VRageMath.Zero)||
### Properties
|Member|Description|
|---|---|
|[`Vector3&nbsp;Up`](VRageMath.Up)|Gets and sets the up vector of the Matrix3x3.|
|[`Vector3&nbsp;Down`](VRageMath.Down)|Gets and sets the down vector of the Matrix3x3.|
|[`Vector3&nbsp;Right`](VRageMath.Right)|Gets and sets the right vector of the Matrix3x3.|
|[`Vector3&nbsp;Col0`](VRageMath.Col0)||
|[`Vector3&nbsp;Col1`](VRageMath.Col1)||
|[`Vector3&nbsp;Col2`](VRageMath.Col2)||
|[`Vector3&nbsp;Left`](VRageMath.Left)|Gets and sets the left vector of the Matrix3x3.|
|[`Vector3&nbsp;Forward`](VRageMath.Forward)|Gets and sets the forward vector of the Matrix3x3.|
|[`Vector3&nbsp;Backward`](VRageMath.Backward)|Gets and sets the backward vector of the Matrix3x3.|
|[`Vector3&nbsp;Scale`](VRageMath.Scale)||
|[`float&nbsp;Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|[`Vector3&nbsp;GetDirectionVector(Direction&nbsp;direction)`](VRageMath.GetDirectionVector)||
|[`void&nbsp;SetDirectionVector(Direction&nbsp;direction,&nbsp;Vector3&nbsp;newValue)`](VRageMath.SetDirectionVector)||
|[`Direction&nbsp;GetClosestDirection(Vector3&nbsp;referenceVector)`](VRageMath.GetClosestDirection)||
|[`Direction&nbsp;GetClosestDirection(ref&nbsp;Vector3&nbsp;referenceVector)`](VRageMath.GetClosestDirection)||
|static&nbsp;[`void&nbsp;Rescale(ref&nbsp;Matrix3x3&nbsp;matrix,&nbsp;float&nbsp;scale)`](VRageMath.Rescale)|Same result as Matrix3x3.CreateScale(scale) * matrix, but much faster|
|static&nbsp;[`void&nbsp;Rescale(ref&nbsp;Matrix3x3&nbsp;matrix,&nbsp;ref&nbsp;Vector3&nbsp;scale)`](VRageMath.Rescale)|Same result as Matrix3x3.CreateScale(scale) * matrix, but much faster|
|static&nbsp;[`Matrix3x3&nbsp;Rescale(Matrix3x3&nbsp;matrix,&nbsp;float&nbsp;scale)`](VRageMath.Rescale)||
|static&nbsp;[`Matrix3x3&nbsp;Rescale(Matrix3x3&nbsp;matrix,&nbsp;Vector3&nbsp;scale)`](VRageMath.Rescale)||
|static&nbsp;[`Matrix3x3&nbsp;CreateScale(float&nbsp;xScale,&nbsp;float&nbsp;yScale,&nbsp;float&nbsp;zScale)`](VRageMath.CreateScale)|Creates a scaling Matrix3x3.|
|static&nbsp;[`void&nbsp;CreateScale(float&nbsp;xScale,&nbsp;float&nbsp;yScale,&nbsp;float&nbsp;zScale,&nbsp;ref&nbsp;Matrix3x3&nbsp;result)`](VRageMath.CreateScale)|Creates a scaling Matrix3x3.|
|static&nbsp;[`Matrix3x3&nbsp;CreateScale(Vector3&nbsp;scales)`](VRageMath.CreateScale)|Creates a scaling Matrix3x3.|
|static&nbsp;[`void&nbsp;CreateScale(ref&nbsp;Vector3&nbsp;scales,&nbsp;ref&nbsp;Matrix3x3&nbsp;result)`](VRageMath.CreateScale)|Creates a scaling Matrix3x3.|
|static&nbsp;[`Matrix3x3&nbsp;CreateScale(float&nbsp;scale)`](VRageMath.CreateScale)|Creates a scaling Matrix3x3.|
|static&nbsp;[`void&nbsp;CreateScale(float&nbsp;scale,&nbsp;ref&nbsp;Matrix3x3&nbsp;result)`](VRageMath.CreateScale)|Creates a scaling Matrix3x3.|
|static&nbsp;[`Matrix3x3&nbsp;CreateRotationX(float&nbsp;radians)`](VRageMath.CreateRotationX)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|static&nbsp;[`void&nbsp;CreateRotationX(float&nbsp;radians,&nbsp;ref&nbsp;Matrix3x3&nbsp;result)`](VRageMath.CreateRotationX)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the x-axis.|
|static&nbsp;[`Matrix3x3&nbsp;CreateRotationY(float&nbsp;radians)`](VRageMath.CreateRotationY)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|static&nbsp;[`void&nbsp;CreateRotationY(float&nbsp;radians,&nbsp;ref&nbsp;Matrix3x3&nbsp;result)`](VRageMath.CreateRotationY)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the y-axis.|
|static&nbsp;[`Matrix3x3&nbsp;CreateRotationZ(float&nbsp;radians)`](VRageMath.CreateRotationZ)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|static&nbsp;[`void&nbsp;CreateRotationZ(float&nbsp;radians,&nbsp;ref&nbsp;Matrix3x3&nbsp;result)`](VRageMath.CreateRotationZ)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the z-axis.|
|static&nbsp;[`Matrix3x3&nbsp;CreateFromAxisAngle(Vector3&nbsp;axis,&nbsp;float&nbsp;angle)`](VRageMath.CreateFromAxisAngle)|Creates a new Matrix3x3 that rotates around an arbitrary vector.|
|static&nbsp;[`void&nbsp;CreateFromAxisAngle(ref&nbsp;Vector3&nbsp;axis,&nbsp;float&nbsp;angle,&nbsp;ref&nbsp;Matrix3x3&nbsp;result)`](VRageMath.CreateFromAxisAngle)|Creates a new Matrix3x3 that rotates around an arbitrary vector.|
|static&nbsp;[`void&nbsp;CreateRotationFromTwoVectors(ref&nbsp;Vector3&nbsp;fromVector,&nbsp;ref&nbsp;Vector3&nbsp;toVector,&nbsp;ref&nbsp;Matrix3x3&nbsp;resultMatrix)`](VRageMath.CreateRotationFromTwoVectors)||
|static&nbsp;[`Matrix3x3&nbsp;CreateFromQuaternion(Quaternion&nbsp;quaternion)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix3x3 from a Quaternion.|
|static&nbsp;[`void&nbsp;CreateFromQuaternion(ref&nbsp;Quaternion&nbsp;quaternion,&nbsp;ref&nbsp;Matrix3x3&nbsp;result)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix3x3 from a Quaternion.|
|static&nbsp;[`Matrix3x3&nbsp;CreateFromYawPitchRoll(float&nbsp;yaw,&nbsp;float&nbsp;pitch,&nbsp;float&nbsp;roll)`](VRageMath.CreateFromYawPitchRoll)|Creates a new rotation matrix from a specified yaw, pitch, and roll.|
|static&nbsp;[`void&nbsp;CreateFromYawPitchRoll(float&nbsp;yaw,&nbsp;float&nbsp;pitch,&nbsp;float&nbsp;roll,&nbsp;ref&nbsp;Matrix3x3&nbsp;result)`](VRageMath.CreateFromYawPitchRoll)|Fills in a rotation matrix from a specified yaw, pitch, and roll.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Matrix3x3&nbsp;value,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;ref&nbsp;Matrix3x3&nbsp;result)`](VRageMath.Transform)|Transforms a Matrix3x3 by applying a Quaternion rotation.|
|[`Vector3&nbsp;GetRow(int&nbsp;row)`](VRageMath.GetRow)||
|[`void&nbsp;SetRow(int&nbsp;row,&nbsp;Vector3&nbsp;value)`](VRageMath.SetRow)||
|[`string&nbsp;ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`bool&nbsp;Equals(Matrix3x3&nbsp;other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Matrix3x3.|
|[`bool&nbsp;EqualsFast(ref&nbsp;Matrix3x3&nbsp;other,&nbsp;float&nbsp;epsilon)`](VRageMath.EqualsFast)|Compares just position, forward and up|
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)|Gets the hash code of this object.|
|static&nbsp;[`void&nbsp;Transpose(ref&nbsp;Matrix3x3&nbsp;matrix,&nbsp;ref&nbsp;Matrix3x3&nbsp;result)`](VRageMath.Transpose)|Transposes the rows and columns of a matrix.|
|[`void&nbsp;Transpose()`](VRageMath.Transpose)||
|[`float&nbsp;Determinant()`](VRageMath.Determinant)||
|static&nbsp;[`void&nbsp;Invert(ref&nbsp;Matrix3x3&nbsp;matrix,&nbsp;ref&nbsp;Matrix3x3&nbsp;result)`](VRageMath.Invert)|Calculates the inverse of a matrix.|
|static&nbsp;[`void&nbsp;Lerp(ref&nbsp;Matrix3x3&nbsp;matrix1,&nbsp;ref&nbsp;Matrix3x3&nbsp;matrix2,&nbsp;float&nbsp;amount,&nbsp;ref&nbsp;Matrix3x3&nbsp;result)`](VRageMath.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|static&nbsp;[`void&nbsp;Slerp(ref&nbsp;Matrix3x3&nbsp;matrix1,&nbsp;ref&nbsp;Matrix3x3&nbsp;matrix2,&nbsp;float&nbsp;amount,&nbsp;ref&nbsp;Matrix3x3&nbsp;result)`](VRageMath.Slerp)|Performs spherical linear interpolation of position and rotation.|
|static&nbsp;[`void&nbsp;SlerpScale(ref&nbsp;Matrix3x3&nbsp;matrix1,&nbsp;ref&nbsp;Matrix3x3&nbsp;matrix2,&nbsp;float&nbsp;amount,&nbsp;ref&nbsp;Matrix3x3&nbsp;result)`](VRageMath.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|static&nbsp;[`void&nbsp;Negate(ref&nbsp;Matrix3x3&nbsp;matrix,&nbsp;ref&nbsp;Matrix3x3&nbsp;result)`](VRageMath.Negate)|Negates individual elements of a matrix.|
|static&nbsp;[`void&nbsp;Add(ref&nbsp;Matrix3x3&nbsp;matrix1,&nbsp;ref&nbsp;Matrix3x3&nbsp;matrix2,&nbsp;ref&nbsp;Matrix3x3&nbsp;result)`](VRageMath.Add)|Adds a matrix to another matrix.|
|static&nbsp;[`void&nbsp;Subtract(ref&nbsp;Matrix3x3&nbsp;matrix1,&nbsp;ref&nbsp;Matrix3x3&nbsp;matrix2,&nbsp;ref&nbsp;Matrix3x3&nbsp;result)`](VRageMath.Subtract)|Subtracts matrices.|
|static&nbsp;[`void&nbsp;Multiply(ref&nbsp;Matrix3x3&nbsp;matrix1,&nbsp;ref&nbsp;Matrix3x3&nbsp;matrix2,&nbsp;ref&nbsp;Matrix3x3&nbsp;result)`](VRageMath.Multiply)|Multiplies a matrix by another matrix.|
|static&nbsp;[`void&nbsp;Multiply(ref&nbsp;Matrix3x3&nbsp;matrix1,&nbsp;float&nbsp;scaleFactor,&nbsp;ref&nbsp;Matrix3x3&nbsp;result)`](VRageMath.Multiply)|Multiplies a matrix by a scalar value.|
|static&nbsp;[`void&nbsp;Divide(ref&nbsp;Matrix3x3&nbsp;matrix1,&nbsp;ref&nbsp;Matrix3x3&nbsp;matrix2,&nbsp;ref&nbsp;Matrix3x3&nbsp;result)`](VRageMath.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|static&nbsp;[`void&nbsp;Divide(ref&nbsp;Matrix3x3&nbsp;matrix1,&nbsp;float&nbsp;divider,&nbsp;ref&nbsp;Matrix3x3&nbsp;result)`](VRageMath.Divide)|Divides the components of a matrix by a scalar.|
|[`Matrix3x3&nbsp;GetOrientation()`](VRageMath.GetOrientation)|Gets the orientation.|
|[`void&nbsp;AssertIsValid()`](VRageMath.AssertIsValid)||
|[`bool&nbsp;IsValid()`](VRageMath.IsValid)||
|[`bool&nbsp;IsNan()`](VRageMath.IsNan)||
|[`bool&nbsp;IsRotation()`](VRageMath.IsRotation)||
|static&nbsp;[`Matrix3x3&nbsp;CreateFromDir(Vector3&nbsp;dir)`](VRageMath.CreateFromDir)||
|static&nbsp;[`Matrix3x3&nbsp;CreateWorld(ref&nbsp;Vector3&nbsp;forward,&nbsp;ref&nbsp;Vector3&nbsp;up)`](VRageMath.CreateWorld)|Creates a world matrix with the specified parameters.|
|static&nbsp;[`Matrix3x3&nbsp;CreateFromDir(Vector3&nbsp;dir,&nbsp;Vector3&nbsp;suggestedUp)`](VRageMath.CreateFromDir)||
|static&nbsp;[`Matrix3x3&nbsp;Normalize(Matrix3x3&nbsp;matrix)`](VRageMath.Normalize)||
|static&nbsp;[`Matrix3x3&nbsp;Orthogonalize(Matrix3x3&nbsp;rotationMatrix)`](VRageMath.Orthogonalize)||
|static&nbsp;[`Matrix3x3&nbsp;Round(ref&nbsp;Matrix3x3&nbsp;matrix)`](VRageMath.Round)||
|static&nbsp;[`Matrix3x3&nbsp;AlignRotationToAxes(ref&nbsp;Matrix3x3&nbsp;toAlign,&nbsp;ref&nbsp;Matrix3x3&nbsp;axisDefinitionMatrix)`](VRageMath.AlignRotationToAxes)||
|static&nbsp;[`bool&nbsp;GetEulerAnglesXYZ(ref&nbsp;Matrix3x3&nbsp;mat,&nbsp;ref&nbsp;Vector3&nbsp;xyz)`](VRageMath.GetEulerAnglesXYZ)||
|[`bool&nbsp;IsMirrored()`](VRageMath.IsMirrored)||
|[`bool&nbsp;IsOrthogonal()`](VRageMath.IsOrthogonal)||
