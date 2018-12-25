← [Index](Api-Index)

#### Matrix3x3 Struct

```csharp
public struct Matrix3x3: ValueType, IEquatable<T>
```

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Inheritance: **[ValueType](System.ValueType)

**Implements:**  
* [IEquatable<T>](System.IEquatable`1)

#### Example

#### Remarks

#### Fields

|Member|Description|
|---|---|
|[M11](VRageMath.Matrix3x3.M11)|Value at row 1 column 1 of the matrix.|
|[M12](VRageMath.Matrix3x3.M12)|Value at row 1 column 2 of the matrix.|
|[M13](VRageMath.Matrix3x3.M13)|Value at row 1 column 3 of the matrix.|
|[M21](VRageMath.Matrix3x3.M21)|Value at row 2 column 1 of the matrix.|
|[M22](VRageMath.Matrix3x3.M22)|Value at row 2 column 2 of the matrix.|
|[M23](VRageMath.Matrix3x3.M23)|Value at row 2 column 3 of the matrix.|
|[M31](VRageMath.Matrix3x3.M31)|Value at row 3 column 1 of the matrix.|
|[M32](VRageMath.Matrix3x3.M32)|Value at row 3 column 2 of the matrix.|
|[M33](VRageMath.Matrix3x3.M33)|Value at row 3 column 3 of the matrix.|
|[Identity](VRageMath.Matrix3x3.Identity)||
|[Zero](VRageMath.Matrix3x3.Zero)||

#### Properties

|Member|Description|
|---|---|
|[Up](VRageMath.Matrix3x3.Up)|Gets and sets the up vector of the Matrix3x3.|
|[Down](VRageMath.Matrix3x3.Down)|Gets and sets the down vector of the Matrix3x3.|
|[Right](VRageMath.Matrix3x3.Right)|Gets and sets the right vector of the Matrix3x3.|
|[Col0](VRageMath.Matrix3x3.Col0)||
|[Col1](VRageMath.Matrix3x3.Col1)||
|[Col2](VRageMath.Matrix3x3.Col2)||
|[Left](VRageMath.Matrix3x3.Left)|Gets and sets the left vector of the Matrix3x3.|
|[Forward](VRageMath.Matrix3x3.Forward)|Gets and sets the forward vector of the Matrix3x3.|
|[Backward](VRageMath.Matrix3x3.Backward)|Gets and sets the backward vector of the Matrix3x3.|
|[Scale](VRageMath.Matrix3x3.Scale)||
|[Item](VRageMath.Matrix3x3.Item)||

#### Methods

|Member|Description|
|---|---|
|[GetDirectionVector(Direction)](VRageMath.Matrix3x3.GetDirectionVector)||
|[SetDirectionVector(Direction, Vector3)](VRageMath.Matrix3x3.SetDirectionVector)||
|[GetClosestDirection(Vector3)](VRageMath.Matrix3x3.GetClosestDirection)||
|[GetClosestDirection(ref Vector3)](VRageMath.Matrix3x3.GetClosestDirection)||
|[Rescale(ref Matrix3x3, float)](VRageMath.Matrix3x3.Rescale)|Same result as Matrix3x3.CreateScale(scale) * matrix, but much faster|
|[Rescale(ref Matrix3x3, ref Vector3)](VRageMath.Matrix3x3.Rescale)|Same result as Matrix3x3.CreateScale(scale) * matrix, but much faster|
|[Rescale(Matrix3x3, float)](VRageMath.Matrix3x3.Rescale)||
|[Rescale(Matrix3x3, Vector3)](VRageMath.Matrix3x3.Rescale)||
|[CreateScale(float, float, float)](VRageMath.Matrix3x3.CreateScale)|Creates a scaling Matrix3x3.|
|[CreateScale(float, float, float, ref Matrix3x3)](VRageMath.Matrix3x3.CreateScale)|Creates a scaling Matrix3x3.|
|[CreateScale(Vector3)](VRageMath.Matrix3x3.CreateScale)|Creates a scaling Matrix3x3.|
|[CreateScale(ref Vector3, ref Matrix3x3)](VRageMath.Matrix3x3.CreateScale)|Creates a scaling Matrix3x3.|
|[CreateScale(float)](VRageMath.Matrix3x3.CreateScale)|Creates a scaling Matrix3x3.|
|[CreateScale(float, ref Matrix3x3)](VRageMath.Matrix3x3.CreateScale)|Creates a scaling Matrix3x3.|
|[CreateRotationX(float)](VRageMath.Matrix3x3.CreateRotationX)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|[CreateRotationX(float, ref Matrix3x3)](VRageMath.Matrix3x3.CreateRotationX)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the x-axis.|
|[CreateRotationY(float)](VRageMath.Matrix3x3.CreateRotationY)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|[CreateRotationY(float, ref Matrix3x3)](VRageMath.Matrix3x3.CreateRotationY)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the y-axis.|
|[CreateRotationZ(float)](VRageMath.Matrix3x3.CreateRotationZ)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|[CreateRotationZ(float, ref Matrix3x3)](VRageMath.Matrix3x3.CreateRotationZ)|Populates data into a user-specified matrix that can be used to rotate a set of vertices around the z-axis.|
|[CreateFromAxisAngle(Vector3, float)](VRageMath.Matrix3x3.CreateFromAxisAngle)|Creates a new Matrix3x3 that rotates around an arbitrary vector.|
|[CreateFromAxisAngle(ref Vector3, float, ref Matrix3x3)](VRageMath.Matrix3x3.CreateFromAxisAngle)|Creates a new Matrix3x3 that rotates around an arbitrary vector.|
|[CreateRotationFromTwoVectors(ref Vector3, ref Vector3, ref Matrix3x3)](VRageMath.Matrix3x3.CreateRotationFromTwoVectors)||
|[CreateFromQuaternion(Quaternion)](VRageMath.Matrix3x3.CreateFromQuaternion)|Creates a rotation Matrix3x3 from a Quaternion.|
|[CreateFromQuaternion(ref Quaternion, ref Matrix3x3)](VRageMath.Matrix3x3.CreateFromQuaternion)|Creates a rotation Matrix3x3 from a Quaternion.|
|[CreateFromYawPitchRoll(float, float, float)](VRageMath.Matrix3x3.CreateFromYawPitchRoll)|Creates a new rotation matrix from a specified yaw, pitch, and roll.|
|[CreateFromYawPitchRoll(float, float, float, ref Matrix3x3)](VRageMath.Matrix3x3.CreateFromYawPitchRoll)|Fills in a rotation matrix from a specified yaw, pitch, and roll.|
|[Transform(ref Matrix3x3, ref Quaternion, ref Matrix3x3)](VRageMath.Matrix3x3.Transform)|Transforms a Matrix3x3 by applying a Quaternion rotation.|
|[GetRow(int)](VRageMath.Matrix3x3.GetRow)||
|[SetRow(int, Vector3)](VRageMath.Matrix3x3.SetRow)||
|[ToString()](VRageMath.Matrix3x3.ToString)|Retrieves a string representation of the current object.|
|[Equals(Matrix3x3)](VRageMath.Matrix3x3.Equals)|Determines whether the specified Object is equal to the Matrix3x3.|
|[EqualsFast(ref Matrix3x3, float)](VRageMath.Matrix3x3.EqualsFast)|Compares just position, forward and up|
|[Equals(object)](VRageMath.Matrix3x3.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[GetHashCode()](VRageMath.Matrix3x3.GetHashCode)|Gets the hash code of this object.|
|[Transpose(ref Matrix3x3, ref Matrix3x3)](VRageMath.Matrix3x3.Transpose)|Transposes the rows and columns of a matrix.|
|[Transpose()](VRageMath.Matrix3x3.Transpose)||
|[Determinant()](VRageMath.Matrix3x3.Determinant)||
|[Invert(ref Matrix3x3, ref Matrix3x3)](VRageMath.Matrix3x3.Invert)|Calculates the inverse of a matrix.|
|[Lerp(ref Matrix3x3, ref Matrix3x3, float, ref Matrix3x3)](VRageMath.Matrix3x3.Lerp)|Linearly interpolates between the corresponding values of two matrices.|
|[Slerp(ref Matrix3x3, ref Matrix3x3, float, ref Matrix3x3)](VRageMath.Matrix3x3.Slerp)|Performs spherical linear interpolation of position and rotation.|
|[SlerpScale(ref Matrix3x3, ref Matrix3x3, float, ref Matrix3x3)](VRageMath.Matrix3x3.SlerpScale)|Performs spherical linear interpolation of position and rotation and scale.|
|[Negate(ref Matrix3x3, ref Matrix3x3)](VRageMath.Matrix3x3.Negate)|Negates individual elements of a matrix.|
|[Add(ref Matrix3x3, ref Matrix3x3, ref Matrix3x3)](VRageMath.Matrix3x3.Add)|Adds a matrix to another matrix.|
|[Subtract(ref Matrix3x3, ref Matrix3x3, ref Matrix3x3)](VRageMath.Matrix3x3.Subtract)|Subtracts matrices.|
|[Multiply(ref Matrix3x3, ref Matrix3x3, ref Matrix3x3)](VRageMath.Matrix3x3.Multiply)|Multiplies a matrix by another matrix.|
|[Multiply(ref Matrix3x3, float, ref Matrix3x3)](VRageMath.Matrix3x3.Multiply)|Multiplies a matrix by a scalar value.|
|[Divide(ref Matrix3x3, ref Matrix3x3, ref Matrix3x3)](VRageMath.Matrix3x3.Divide)|Divides the components of a matrix by the corresponding components of another matrix.|
|[Divide(ref Matrix3x3, float, ref Matrix3x3)](VRageMath.Matrix3x3.Divide)|Divides the components of a matrix by a scalar.|
|[GetOrientation()](VRageMath.Matrix3x3.GetOrientation)|Gets the orientation.|
|[AssertIsValid()](VRageMath.Matrix3x3.AssertIsValid)||
|[IsValid()](VRageMath.Matrix3x3.IsValid)||
|[IsNan()](VRageMath.Matrix3x3.IsNan)||
|[IsRotation()](VRageMath.Matrix3x3.IsRotation)||
|[CreateFromDir(Vector3)](VRageMath.Matrix3x3.CreateFromDir)||
|[CreateWorld(ref Vector3, ref Vector3)](VRageMath.Matrix3x3.CreateWorld)|Creates a world matrix with the specified parameters.|
|[CreateFromDir(Vector3, Vector3)](VRageMath.Matrix3x3.CreateFromDir)||
|[Normalize(Matrix3x3)](VRageMath.Matrix3x3.Normalize)||
|[Orthogonalize(Matrix3x3)](VRageMath.Matrix3x3.Orthogonalize)||
|[Round(ref Matrix3x3)](VRageMath.Matrix3x3.Round)||
|[AlignRotationToAxes(ref Matrix3x3, ref Matrix3x3)](VRageMath.Matrix3x3.AlignRotationToAxes)||
|[GetEulerAnglesXYZ(ref Matrix3x3, ref Vector3)](VRageMath.Matrix3x3.GetEulerAnglesXYZ)||
|[IsMirrored()](VRageMath.Matrix3x3.IsMirrored)||
|[IsOrthogonal()](VRageMath.Matrix3x3.IsOrthogonal)||

