← [Index](index.md)
# Matrix3x3 Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Defines a matrix.
### Fields
|Member|Description|
|---|---|
|[`float M11`](VRageMath.M11.md)||
|[`float M12`](VRageMath.M12.md)||
|[`float M13`](VRageMath.M13.md)||
|[`float M21`](VRageMath.M21.md)||
|[`float M22`](VRageMath.M22.md)||
|[`float M23`](VRageMath.M23.md)||
|[`float M31`](VRageMath.M31.md)||
|[`float M32`](VRageMath.M32.md)||
|[`float M33`](VRageMath.M33.md)||
|[`Matrix3x3 Identity`](VRageMath.Identity.md)||
|[`Matrix3x3 Zero`](VRageMath.Zero.md)||
### Properties
|Member|Description|
|---|---|
|[`Vector3 Up`](VRageMath.Up.md)||
|[`Vector3 Down`](VRageMath.Down.md)||
|[`Vector3 Right`](VRageMath.Right.md)||
|[`Vector3 Col0`](VRageMath.Col0.md)||
|[`Vector3 Col1`](VRageMath.Col1.md)||
|[`Vector3 Col2`](VRageMath.Col2.md)||
|[`Vector3 Left`](VRageMath.Left.md)||
|[`Vector3 Forward`](VRageMath.Forward.md)||
|[`Vector3 Backward`](VRageMath.Backward.md)||
|[`Vector3 Scale`](VRageMath.Scale.md)||
|[`float Item`](VRageMath.Item.md)||
### Methods
|Member|Description|
|---|---|
|[`Vector3 GetDirectionVector(Direction direction)`](VRageMath.GetDirectionVector.md)||
|[`void SetDirectionVector(Direction direction, Vector3 newValue)`](VRageMath.SetDirectionVector.md)||
|[`Direction GetClosestDirection(Vector3 referenceVector)`](VRageMath.GetClosestDirection.md)||
|[`Direction GetClosestDirection(ref Vector3 referenceVector)`](VRageMath.GetClosestDirection.md)||
|[`void Rescale(ref Matrix3x3 matrix, float scale)`](VRageMath.Rescale.md)||
|[`void Rescale(ref Matrix3x3 matrix, ref Vector3 scale)`](VRageMath.Rescale.md)||
|[`Matrix3x3 Rescale(Matrix3x3 matrix, float scale)`](VRageMath.Rescale.md)||
|[`Matrix3x3 Rescale(Matrix3x3 matrix, Vector3 scale)`](VRageMath.Rescale.md)||
|[`Matrix3x3 CreateScale(float xScale, float yScale, float zScale)`](VRageMath.CreateScale.md)||
|[`void CreateScale(float xScale, float yScale, float zScale, ref Matrix3x3 result)`](VRageMath.CreateScale.md)||
|[`Matrix3x3 CreateScale(Vector3 scales)`](VRageMath.CreateScale.md)|Creates a scaling Matrix3x3.|
|[`void CreateScale(ref Vector3 scales, ref Matrix3x3 result)`](VRageMath.CreateScale.md)||
|[`Matrix3x3 CreateScale(float scale)`](VRageMath.CreateScale.md)|Creates a scaling Matrix3x3.|
|[`void CreateScale(float scale, ref Matrix3x3 result)`](VRageMath.CreateScale.md)||
|[`Matrix3x3 CreateRotationX(float radians)`](VRageMath.CreateRotationX.md)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|[`void CreateRotationX(float radians, ref Matrix3x3 result)`](VRageMath.CreateRotationX.md)||
|[`Matrix3x3 CreateRotationY(float radians)`](VRageMath.CreateRotationY.md)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|[`void CreateRotationY(float radians, ref Matrix3x3 result)`](VRageMath.CreateRotationY.md)||
|[`Matrix3x3 CreateRotationZ(float radians)`](VRageMath.CreateRotationZ.md)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|[`void CreateRotationZ(float radians, ref Matrix3x3 result)`](VRageMath.CreateRotationZ.md)||
|[`Matrix3x3 CreateFromAxisAngle(Vector3 axis, float angle)`](VRageMath.CreateFromAxisAngle.md)||
|[`void CreateFromAxisAngle(ref Vector3 axis, float angle, ref Matrix3x3 result)`](VRageMath.CreateFromAxisAngle.md)||
|[`void CreateRotationFromTwoVectors(ref Vector3 fromVector, ref Vector3 toVector, ref Matrix3x3 resultMatrix)`](VRageMath.CreateRotationFromTwoVectors.md)||
|[`Matrix3x3 CreateFromQuaternion(Quaternion quaternion)`](VRageMath.CreateFromQuaternion.md)|Creates a rotation Matrix3x3 from a Quaternion.|
|[`void CreateFromQuaternion(ref Quaternion quaternion, ref Matrix3x3 result)`](VRageMath.CreateFromQuaternion.md)||
|[`Matrix3x3 CreateFromYawPitchRoll(float yaw, float pitch, float roll)`](VRageMath.CreateFromYawPitchRoll.md)||
|[`void CreateFromYawPitchRoll(float yaw, float pitch, float roll, ref Matrix3x3 result)`](VRageMath.CreateFromYawPitchRoll.md)||
|[`void Transform(ref Matrix3x3 value, ref Quaternion rotation, ref Matrix3x3 result)`](VRageMath.Transform.md)||
|[`Vector3 GetRow(int row)`](VRageMath.GetRow.md)||
|[`void SetRow(int row, Vector3 value)`](VRageMath.SetRow.md)||
|[`string ToString()`](VRageMath.ToString.md)||
|[`bool Equals(Matrix3x3 other)`](VRageMath.Equals.md)|Determines whether the specified Object is equal to the Matrix3x3.|
|[`bool EqualsFast(ref Matrix3x3 other, float epsilon)`](VRageMath.EqualsFast.md)||
|[`bool Equals(Object obj)`](VRageMath.Equals.md)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`void Transpose(ref Matrix3x3 matrix, ref Matrix3x3 result)`](VRageMath.Transpose.md)||
|[`void Transpose()`](VRageMath.Transpose.md)||
|[`float Determinant()`](VRageMath.Determinant.md)||
|[`void Invert(ref Matrix3x3 matrix, ref Matrix3x3 result)`](VRageMath.Invert.md)||
|[`void Lerp(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, float amount, ref Matrix3x3 result)`](VRageMath.Lerp.md)||
|[`void Slerp(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, float amount, ref Matrix3x3 result)`](VRageMath.Slerp.md)||
|[`void SlerpScale(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, float amount, ref Matrix3x3 result)`](VRageMath.SlerpScale.md)||
|[`void Negate(ref Matrix3x3 matrix, ref Matrix3x3 result)`](VRageMath.Negate.md)||
|[`void Add(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, ref Matrix3x3 result)`](VRageMath.Add.md)||
|[`void Subtract(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, ref Matrix3x3 result)`](VRageMath.Subtract.md)||
|[`void Multiply(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, ref Matrix3x3 result)`](VRageMath.Multiply.md)||
|[`void Multiply(ref Matrix3x3 matrix1, float scaleFactor, ref Matrix3x3 result)`](VRageMath.Multiply.md)||
|[`void Divide(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, ref Matrix3x3 result)`](VRageMath.Divide.md)||
|[`void Divide(ref Matrix3x3 matrix1, float divider, ref Matrix3x3 result)`](VRageMath.Divide.md)||
|[`Matrix3x3 GetOrientation()`](VRageMath.GetOrientation.md)||
|[`void AssertIsValid()`](VRageMath.AssertIsValid.md)||
|[`bool IsValid()`](VRageMath.IsValid.md)||
|[`bool IsNan()`](VRageMath.IsNan.md)||
|[`bool IsRotation()`](VRageMath.IsRotation.md)||
|[`Matrix3x3 CreateFromDir(Vector3 dir)`](VRageMath.CreateFromDir.md)||
|[`Matrix3x3 CreateWorld(ref Vector3 forward, ref Vector3 up)`](VRageMath.CreateWorld.md)||
|[`Matrix3x3 CreateFromDir(Vector3 dir, Vector3 suggestedUp)`](VRageMath.CreateFromDir.md)||
|[`Matrix3x3 Normalize(Matrix3x3 matrix)`](VRageMath.Normalize.md)||
|[`Matrix3x3 Orthogonalize(Matrix3x3 rotationMatrix)`](VRageMath.Orthogonalize.md)||
|[`Matrix3x3 Round(ref Matrix3x3 matrix)`](VRageMath.Round.md)||
|[`Matrix3x3 AlignRotationToAxes(ref Matrix3x3 toAlign, ref Matrix3x3 axisDefinitionMatrix)`](VRageMath.AlignRotationToAxes.md)||
|[`bool GetEulerAnglesXYZ(ref Matrix3x3 mat, ref Vector3 xyz)`](VRageMath.GetEulerAnglesXYZ.md)||
|[`bool IsMirrored()`](VRageMath.IsMirrored.md)||
|[`bool IsOrthogonal()`](VRageMath.IsOrthogonal.md)||
