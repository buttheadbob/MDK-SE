← [Index](index)
# Matrix3x3 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a matrix.
### Fields
|Member|Description|
|---|---|
|[`float M11`](VRageMath.M11)||
|[`float M12`](VRageMath.M12)||
|[`float M13`](VRageMath.M13)||
|[`float M21`](VRageMath.M21)||
|[`float M22`](VRageMath.M22)||
|[`float M23`](VRageMath.M23)||
|[`float M31`](VRageMath.M31)||
|[`float M32`](VRageMath.M32)||
|[`float M33`](VRageMath.M33)||
|[`Matrix3x3 Identity`](VRageMath.Identity)||
|[`Matrix3x3 Zero`](VRageMath.Zero)||
### Properties
|Member|Description|
|---|---|
|[`Vector3 Up`](VRageMath.Up)||
|[`Vector3 Down`](VRageMath.Down)||
|[`Vector3 Right`](VRageMath.Right)||
|[`Vector3 Col0`](VRageMath.Col0)||
|[`Vector3 Col1`](VRageMath.Col1)||
|[`Vector3 Col2`](VRageMath.Col2)||
|[`Vector3 Left`](VRageMath.Left)||
|[`Vector3 Forward`](VRageMath.Forward)||
|[`Vector3 Backward`](VRageMath.Backward)||
|[`Vector3 Scale`](VRageMath.Scale)||
|[`float Item`](VRageMath.Item)||
### Methods
|Member|Description|
|---|---|
|[`Vector3 GetDirectionVector(Direction direction)`](VRageMath.GetDirectionVector)||
|[`void SetDirectionVector(Direction direction, Vector3 newValue)`](VRageMath.SetDirectionVector)||
|[`Direction GetClosestDirection(Vector3 referenceVector)`](VRageMath.GetClosestDirection)||
|[`Direction GetClosestDirection(ref Vector3 referenceVector)`](VRageMath.GetClosestDirection)||
|[`void Rescale(ref Matrix3x3 matrix, float scale)`](VRageMath.Rescale)||
|[`void Rescale(ref Matrix3x3 matrix, ref Vector3 scale)`](VRageMath.Rescale)||
|[`Matrix3x3 Rescale(Matrix3x3 matrix, float scale)`](VRageMath.Rescale)||
|[`Matrix3x3 Rescale(Matrix3x3 matrix, Vector3 scale)`](VRageMath.Rescale)||
|[`Matrix3x3 CreateScale(float xScale, float yScale, float zScale)`](VRageMath.CreateScale)||
|[`void CreateScale(float xScale, float yScale, float zScale, ref Matrix3x3 result)`](VRageMath.CreateScale)||
|[`Matrix3x3 CreateScale(Vector3 scales)`](VRageMath.CreateScale)|Creates a scaling Matrix3x3.|
|[`void CreateScale(ref Vector3 scales, ref Matrix3x3 result)`](VRageMath.CreateScale)||
|[`Matrix3x3 CreateScale(float scale)`](VRageMath.CreateScale)|Creates a scaling Matrix3x3.|
|[`void CreateScale(float scale, ref Matrix3x3 result)`](VRageMath.CreateScale)||
|[`Matrix3x3 CreateRotationX(float radians)`](VRageMath.CreateRotationX)|Returns a matrix that can be used to rotate a set of vertices around the x-axis.|
|[`void CreateRotationX(float radians, ref Matrix3x3 result)`](VRageMath.CreateRotationX)||
|[`Matrix3x3 CreateRotationY(float radians)`](VRageMath.CreateRotationY)|Returns a matrix that can be used to rotate a set of vertices around the y-axis.|
|[`void CreateRotationY(float radians, ref Matrix3x3 result)`](VRageMath.CreateRotationY)||
|[`Matrix3x3 CreateRotationZ(float radians)`](VRageMath.CreateRotationZ)|Returns a matrix that can be used to rotate a set of vertices around the z-axis.|
|[`void CreateRotationZ(float radians, ref Matrix3x3 result)`](VRageMath.CreateRotationZ)||
|[`Matrix3x3 CreateFromAxisAngle(Vector3 axis, float angle)`](VRageMath.CreateFromAxisAngle)||
|[`void CreateFromAxisAngle(ref Vector3 axis, float angle, ref Matrix3x3 result)`](VRageMath.CreateFromAxisAngle)||
|[`void CreateRotationFromTwoVectors(ref Vector3 fromVector, ref Vector3 toVector, ref Matrix3x3 resultMatrix)`](VRageMath.CreateRotationFromTwoVectors)||
|[`Matrix3x3 CreateFromQuaternion(Quaternion quaternion)`](VRageMath.CreateFromQuaternion)|Creates a rotation Matrix3x3 from a Quaternion.|
|[`void CreateFromQuaternion(ref Quaternion quaternion, ref Matrix3x3 result)`](VRageMath.CreateFromQuaternion)||
|[`Matrix3x3 CreateFromYawPitchRoll(float yaw, float pitch, float roll)`](VRageMath.CreateFromYawPitchRoll)||
|[`void CreateFromYawPitchRoll(float yaw, float pitch, float roll, ref Matrix3x3 result)`](VRageMath.CreateFromYawPitchRoll)||
|[`void Transform(ref Matrix3x3 value, ref Quaternion rotation, ref Matrix3x3 result)`](VRageMath.Transform)||
|[`Vector3 GetRow(int row)`](VRageMath.GetRow)||
|[`void SetRow(int row, Vector3 value)`](VRageMath.SetRow)||
|[`string ToString()`](VRageMath.ToString)||
|[`bool Equals(Matrix3x3 other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Matrix3x3.|
|[`bool EqualsFast(ref Matrix3x3 other, float epsilon)`](VRageMath.EqualsFast)||
|[`bool Equals(Object obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`void Transpose(ref Matrix3x3 matrix, ref Matrix3x3 result)`](VRageMath.Transpose)||
|[`void Transpose()`](VRageMath.Transpose)||
|[`float Determinant()`](VRageMath.Determinant)||
|[`void Invert(ref Matrix3x3 matrix, ref Matrix3x3 result)`](VRageMath.Invert)||
|[`void Lerp(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, float amount, ref Matrix3x3 result)`](VRageMath.Lerp)||
|[`void Slerp(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, float amount, ref Matrix3x3 result)`](VRageMath.Slerp)||
|[`void SlerpScale(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, float amount, ref Matrix3x3 result)`](VRageMath.SlerpScale)||
|[`void Negate(ref Matrix3x3 matrix, ref Matrix3x3 result)`](VRageMath.Negate)||
|[`void Add(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, ref Matrix3x3 result)`](VRageMath.Add)||
|[`void Subtract(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, ref Matrix3x3 result)`](VRageMath.Subtract)||
|[`void Multiply(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, ref Matrix3x3 result)`](VRageMath.Multiply)||
|[`void Multiply(ref Matrix3x3 matrix1, float scaleFactor, ref Matrix3x3 result)`](VRageMath.Multiply)||
|[`void Divide(ref Matrix3x3 matrix1, ref Matrix3x3 matrix2, ref Matrix3x3 result)`](VRageMath.Divide)||
|[`void Divide(ref Matrix3x3 matrix1, float divider, ref Matrix3x3 result)`](VRageMath.Divide)||
|[`Matrix3x3 GetOrientation()`](VRageMath.GetOrientation)||
|[`void AssertIsValid()`](VRageMath.AssertIsValid)||
|[`bool IsValid()`](VRageMath.IsValid)||
|[`bool IsNan()`](VRageMath.IsNan)||
|[`bool IsRotation()`](VRageMath.IsRotation)||
|[`Matrix3x3 CreateFromDir(Vector3 dir)`](VRageMath.CreateFromDir)||
|[`Matrix3x3 CreateWorld(ref Vector3 forward, ref Vector3 up)`](VRageMath.CreateWorld)||
|[`Matrix3x3 CreateFromDir(Vector3 dir, Vector3 suggestedUp)`](VRageMath.CreateFromDir)||
|[`Matrix3x3 Normalize(Matrix3x3 matrix)`](VRageMath.Normalize)||
|[`Matrix3x3 Orthogonalize(Matrix3x3 rotationMatrix)`](VRageMath.Orthogonalize)||
|[`Matrix3x3 Round(ref Matrix3x3 matrix)`](VRageMath.Round)||
|[`Matrix3x3 AlignRotationToAxes(ref Matrix3x3 toAlign, ref Matrix3x3 axisDefinitionMatrix)`](VRageMath.AlignRotationToAxes)||
|[`bool GetEulerAnglesXYZ(ref Matrix3x3 mat, ref Vector3 xyz)`](VRageMath.GetEulerAnglesXYZ)||
|[`bool IsMirrored()`](VRageMath.IsMirrored)||
|[`bool IsOrthogonal()`](VRageMath.IsOrthogonal)||
