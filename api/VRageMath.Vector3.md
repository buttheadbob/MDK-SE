← [Index](index)
# Vector3 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with three components.
### Fields
|Member|Description|
|---|---|
|[`float&nbsp;X`](VRageMath.X)|Gets or sets the x-component of the vector.|
|[`float&nbsp;Y`](VRageMath.Y)|Gets or sets the y-component of the vector.|
|[`float&nbsp;Z`](VRageMath.Z)|Gets or sets the z-component of the vector.|
|static&nbsp;[`Vector3&nbsp;Zero`](VRageMath.Zero)||
|static&nbsp;[`Vector3&nbsp;One`](VRageMath.One)||
|static&nbsp;[`Vector3&nbsp;MinusOne`](VRageMath.MinusOne)||
|static&nbsp;[`Vector3&nbsp;Half`](VRageMath.Half)||
|static&nbsp;[`Vector3&nbsp;PositiveInfinity`](VRageMath.PositiveInfinity)||
|static&nbsp;[`Vector3&nbsp;NegativeInfinity`](VRageMath.NegativeInfinity)||
|static&nbsp;[`Vector3&nbsp;UnitX`](VRageMath.UnitX)||
|static&nbsp;[`Vector3&nbsp;UnitY`](VRageMath.UnitY)||
|static&nbsp;[`Vector3&nbsp;UnitZ`](VRageMath.UnitZ)||
|static&nbsp;[`Vector3&nbsp;Up`](VRageMath.Up)||
|static&nbsp;[`Vector3&nbsp;Down`](VRageMath.Down)||
|static&nbsp;[`Vector3&nbsp;Right`](VRageMath.Right)||
|static&nbsp;[`Vector3&nbsp;Left`](VRageMath.Left)||
|static&nbsp;[`Vector3&nbsp;Forward`](VRageMath.Forward)||
|static&nbsp;[`Vector3&nbsp;Backward`](VRageMath.Backward)||
|static&nbsp;[`Vector3&nbsp;MaxValue`](VRageMath.MaxValue)||
|static&nbsp;[`Vector3&nbsp;MinValue`](VRageMath.MinValue)||
|static&nbsp;[`Vector3&nbsp;Invalid`](VRageMath.Invalid)||
### Properties
|Member|Description|
|---|---|
|[`float&nbsp;Sum`](VRageMath.Sum)||
|[`float&nbsp;Volume`](VRageMath.Volume)||
### Methods
|Member|Description|
|---|---|
|static&nbsp;[`void&nbsp;Negate(ref&nbsp;Vector3&nbsp;value,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static&nbsp;[`Vector3&nbsp;Add(Vector3&nbsp;value1,&nbsp;Vector3&nbsp;value2)`](VRageMath.Add)|Adds two vectors.|
|static&nbsp;[`void&nbsp;Add(ref&nbsp;Vector3&nbsp;value1,&nbsp;ref&nbsp;Vector3&nbsp;value2,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.Add)|Adds two vectors.|
|static&nbsp;[`Vector3&nbsp;Subtract(Vector3&nbsp;value1,&nbsp;Vector3&nbsp;value2)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static&nbsp;[`void&nbsp;Subtract(ref&nbsp;Vector3&nbsp;value1,&nbsp;ref&nbsp;Vector3&nbsp;value2,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static&nbsp;[`Vector3&nbsp;Multiply(Vector3&nbsp;value1,&nbsp;Vector3&nbsp;value2)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static&nbsp;[`void&nbsp;Multiply(ref&nbsp;Vector3&nbsp;value1,&nbsp;ref&nbsp;Vector3&nbsp;value2,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static&nbsp;[`Vector3&nbsp;Multiply(Vector3&nbsp;value1,&nbsp;float&nbsp;scaleFactor)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static&nbsp;[`void&nbsp;Multiply(ref&nbsp;Vector3&nbsp;value1,&nbsp;float&nbsp;scaleFactor,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static&nbsp;[`Vector3&nbsp;Divide(Vector3&nbsp;value1,&nbsp;Vector3&nbsp;value2)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static&nbsp;[`void&nbsp;Divide(ref&nbsp;Vector3&nbsp;value1,&nbsp;ref&nbsp;Vector3&nbsp;value2,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static&nbsp;[`Vector3&nbsp;Divide(Vector3&nbsp;value1,&nbsp;float&nbsp;value2)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static&nbsp;[`void&nbsp;Divide(ref&nbsp;Vector3&nbsp;value1,&nbsp;float&nbsp;value2,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static&nbsp;[`Vector3&nbsp;CalculatePerpendicularVector(Vector3&nbsp;v)`](VRageMath.CalculatePerpendicularVector)||
|[`void&nbsp;CalculatePerpendicularVector(ref&nbsp;Vector3&nbsp;result)`](VRageMath.CalculatePerpendicularVector)||
|static&nbsp;[`void&nbsp;GetAzimuthAndElevation(Vector3&nbsp;v,&nbsp;ref&nbsp;float&nbsp;azimuth,&nbsp;ref&nbsp;float&nbsp;elevation)`](VRageMath.GetAzimuthAndElevation)||
|static&nbsp;[`void&nbsp;CreateFromAzimuthAndElevation(float&nbsp;azimuth,&nbsp;float&nbsp;elevation,&nbsp;ref&nbsp;Vector3&nbsp;direction)`](VRageMath.CreateFromAzimuthAndElevation)||
|[`long&nbsp;VolumeInt(float&nbsp;multiplier)`](VRageMath.VolumeInt)||
|[`bool&nbsp;IsInsideInclusive(ref&nbsp;Vector3&nbsp;min,&nbsp;ref&nbsp;Vector3&nbsp;max)`](VRageMath.IsInsideInclusive)||
|static&nbsp;[`Vector3&nbsp;SwapYZCoordinates(Vector3&nbsp;v)`](VRageMath.SwapYZCoordinates)||
|[`float&nbsp;GetDim(int&nbsp;i)`](VRageMath.GetDim)||
|[`void&nbsp;SetDim(int&nbsp;i,&nbsp;float&nbsp;value)`](VRageMath.SetDim)||
|static&nbsp;[`Vector3&nbsp;Ceiling(Vector3&nbsp;v)`](VRageMath.Ceiling)||
|static&nbsp;[`Vector3&nbsp;Floor(Vector3&nbsp;v)`](VRageMath.Floor)||
|static&nbsp;[`Vector3&nbsp;Round(Vector3&nbsp;v)`](VRageMath.Round)||
|static&nbsp;[`Vector3&nbsp;Round(Vector3&nbsp;v,&nbsp;int&nbsp;numDecimals)`](VRageMath.Round)||
|static&nbsp;[`Vector3&nbsp;ProjectOnPlane(ref&nbsp;Vector3&nbsp;vec,&nbsp;ref&nbsp;Vector3&nbsp;planeNormal)`](VRageMath.ProjectOnPlane)|Projects given vector on plane specified by it's normal.|
|static&nbsp;[`Vector3&nbsp;ProjectOnVector(ref&nbsp;Vector3&nbsp;vec,&nbsp;ref&nbsp;Vector3&nbsp;guideVector)`](VRageMath.ProjectOnVector)|Projects vector on another vector resulting in new vector in guided vector's direction with different length.|
|static&nbsp;[`bool&nbsp;IsZero(ref&nbsp;Vector3&nbsp;vec)`](VRageMath.IsZero)||
|[`void&nbsp;Divide(float&nbsp;divider)`](VRageMath.Divide)||
|[`void&nbsp;Multiply(float&nbsp;scale)`](VRageMath.Multiply)||
|[`void&nbsp;Add(Vector3&nbsp;other)`](VRageMath.Add)||
|static&nbsp;[`Vector3&nbsp;Abs(Vector3&nbsp;value)`](VRageMath.Abs)||
|static&nbsp;[`Vector3&nbsp;Sign(Vector3&nbsp;value)`](VRageMath.Sign)||
|static&nbsp;[`Vector3&nbsp;Sign(Vector3&nbsp;value,&nbsp;float&nbsp;epsilon)`](VRageMath.Sign)||
|static&nbsp;[`Vector3&nbsp;SignNonZero(Vector3&nbsp;value)`](VRageMath.SignNonZero)|Returns per component sign, never returns zero. For zero component returns sign 1. Faster than Sign.|
|[`void&nbsp;Interpolate3(Vector3&nbsp;v0,&nbsp;Vector3&nbsp;v1,&nbsp;float&nbsp;rt)`](VRageMath.Interpolate3)||
|[`bool&nbsp;IsValid()`](VRageMath.IsValid)||
|[`void&nbsp;AssertIsValid()`](VRageMath.AssertIsValid)||
|static&nbsp;[`bool&nbsp;IsUnit(ref&nbsp;Vector3&nbsp;value)`](VRageMath.IsUnit)||
|static&nbsp;[`bool&nbsp;ArePerpendicular(ref&nbsp;Vector3&nbsp;a,&nbsp;ref&nbsp;Vector3&nbsp;b)`](VRageMath.ArePerpendicular)||
|static&nbsp;[`bool&nbsp;IsZero(Vector3&nbsp;value)`](VRageMath.IsZero)||
|static&nbsp;[`bool&nbsp;IsZero(Vector3&nbsp;value,&nbsp;float&nbsp;epsilon)`](VRageMath.IsZero)||
|static&nbsp;[`Vector3&nbsp;IsZeroVector(Vector3&nbsp;value)`](VRageMath.IsZeroVector)||
|static&nbsp;[`Vector3&nbsp;IsZeroVector(Vector3&nbsp;value,&nbsp;float&nbsp;epsilon)`](VRageMath.IsZeroVector)||
|static&nbsp;[`Vector3&nbsp;Step(Vector3&nbsp;value)`](VRageMath.Step)||
|[`string&nbsp;ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`string&nbsp;ToString(string&nbsp;format)`](VRageMath.ToString)||
|[`bool&nbsp;Equals(Vector3&nbsp;other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector3.|
|[`bool&nbsp;Equals(Vector3&nbsp;other,&nbsp;float&nbsp;epsilon)`](VRageMath.Equals)||
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)||
|[`long&nbsp;GetHash()`](VRageMath.GetHash)|Gets the hash code of the vector object.|
|[`float&nbsp;Length()`](VRageMath.Length)|Calculates the length of the vector.|
|[`float&nbsp;LengthSquared()`](VRageMath.LengthSquared)|Calculates the length of the vector squared.|
|static&nbsp;[`float&nbsp;Distance(Vector3&nbsp;value1,&nbsp;Vector3&nbsp;value2)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static&nbsp;[`void&nbsp;Distance(ref&nbsp;Vector3&nbsp;value1,&nbsp;ref&nbsp;Vector3&nbsp;value2,&nbsp;ref&nbsp;float&nbsp;result)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static&nbsp;[`float&nbsp;DistanceSquared(Vector3&nbsp;value1,&nbsp;Vector3&nbsp;value2)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static&nbsp;[`void&nbsp;DistanceSquared(ref&nbsp;Vector3&nbsp;value1,&nbsp;ref&nbsp;Vector3&nbsp;value2,&nbsp;ref&nbsp;float&nbsp;result)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static&nbsp;[`float&nbsp;RectangularDistance(Vector3&nbsp;value1,&nbsp;Vector3&nbsp;value2)`](VRageMath.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|static&nbsp;[`float&nbsp;RectangularDistance(ref&nbsp;Vector3&nbsp;value1,&nbsp;ref&nbsp;Vector3&nbsp;value2)`](VRageMath.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|static&nbsp;[`float&nbsp;Dot(Vector3&nbsp;vector1,&nbsp;Vector3&nbsp;vector2)`](VRageMath.Dot)|Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|static&nbsp;[`void&nbsp;Dot(ref&nbsp;Vector3&nbsp;vector1,&nbsp;ref&nbsp;Vector3&nbsp;vector2,&nbsp;ref&nbsp;float&nbsp;result)`](VRageMath.Dot)|Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[`float&nbsp;Dot(Vector3&nbsp;v)`](VRageMath.Dot)||
|[`float&nbsp;Dot(ref&nbsp;Vector3&nbsp;v)`](VRageMath.Dot)||
|[`Vector3&nbsp;Cross(Vector3&nbsp;v)`](VRageMath.Cross)||
|[`float&nbsp;Normalize()`](VRageMath.Normalize)|Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static&nbsp;[`Vector3&nbsp;Normalize(Vector3&nbsp;value)`](VRageMath.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static&nbsp;[`Vector3&nbsp;Normalize(Vector3D&nbsp;value)`](VRageMath.Normalize)||
|static&nbsp;[`bool&nbsp;GetNormalized(ref&nbsp;Vector3&nbsp;value)`](VRageMath.GetNormalized)||
|static&nbsp;[`void&nbsp;Normalize(ref&nbsp;Vector3&nbsp;value,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.Normalize)|Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static&nbsp;[`Vector3&nbsp;Cross(Vector3&nbsp;vector1,&nbsp;Vector3&nbsp;vector2)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|static&nbsp;[`void&nbsp;Cross(ref&nbsp;Vector3&nbsp;vector1,&nbsp;ref&nbsp;Vector3&nbsp;vector2,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|static&nbsp;[`Vector3&nbsp;Reflect(Vector3&nbsp;vector,&nbsp;Vector3&nbsp;normal)`](VRageMath.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|static&nbsp;[`void&nbsp;Reflect(ref&nbsp;Vector3&nbsp;vector,&nbsp;ref&nbsp;Vector3&nbsp;normal,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|static&nbsp;[`Vector3&nbsp;Reject(Vector3&nbsp;vector,&nbsp;Vector3&nbsp;direction)`](VRageMath.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|static&nbsp;[`void&nbsp;Reject(ref&nbsp;Vector3&nbsp;vector,&nbsp;ref&nbsp;Vector3&nbsp;direction,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|[`float&nbsp;Min()`](VRageMath.Min)|Returns the component of the vector that is smallest of all the three components.|
|[`float&nbsp;AbsMin()`](VRageMath.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|[`float&nbsp;Max()`](VRageMath.Max)|Returns the component of the vector that is largest of all the three components.|
|[`Vector3&nbsp;MaxAbsComponent()`](VRageMath.MaxAbsComponent)|Keeps only component with maximal absolute, others are set to zero.|
|[`float&nbsp;AbsMax()`](VRageMath.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|static&nbsp;[`Vector3&nbsp;Min(Vector3&nbsp;value1,&nbsp;Vector3&nbsp;value2)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static&nbsp;[`void&nbsp;Min(ref&nbsp;Vector3&nbsp;value1,&nbsp;ref&nbsp;Vector3&nbsp;value2,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static&nbsp;[`Vector3&nbsp;Max(Vector3&nbsp;value1,&nbsp;Vector3&nbsp;value2)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static&nbsp;[`void&nbsp;Max(ref&nbsp;Vector3&nbsp;value1,&nbsp;ref&nbsp;Vector3&nbsp;value2,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static&nbsp;[`void&nbsp;MinMax(ref&nbsp;Vector3&nbsp;min,&nbsp;ref&nbsp;Vector3&nbsp;max)`](VRageMath.MinMax)|Separates minimal and maximal values of any two input vectors|
|static&nbsp;[`Vector3&nbsp;DominantAxisProjection(Vector3&nbsp;value1)`](VRageMath.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|static&nbsp;[`void&nbsp;DominantAxisProjection(ref&nbsp;Vector3&nbsp;value1,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved into a user-specified variable.|
|static&nbsp;[`Vector3&nbsp;Clamp(Vector3&nbsp;value1,&nbsp;Vector3&nbsp;min,&nbsp;Vector3&nbsp;max)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static&nbsp;[`void&nbsp;Clamp(ref&nbsp;Vector3&nbsp;value1,&nbsp;ref&nbsp;Vector3&nbsp;min,&nbsp;ref&nbsp;Vector3&nbsp;max,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static&nbsp;[`Vector3&nbsp;ClampToSphere(Vector3&nbsp;vector,&nbsp;float&nbsp;radius)`](VRageMath.ClampToSphere)||
|static&nbsp;[`void&nbsp;ClampToSphere(ref&nbsp;Vector3&nbsp;vector,&nbsp;float&nbsp;radius)`](VRageMath.ClampToSphere)||
|static&nbsp;[`Vector3&nbsp;Lerp(Vector3&nbsp;value1,&nbsp;Vector3&nbsp;value2,&nbsp;float&nbsp;amount)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static&nbsp;[`void&nbsp;Lerp(ref&nbsp;Vector3&nbsp;value1,&nbsp;ref&nbsp;Vector3&nbsp;value2,&nbsp;float&nbsp;amount,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static&nbsp;[`Vector3&nbsp;Barycentric(Vector3&nbsp;value1,&nbsp;Vector3&nbsp;value2,&nbsp;Vector3&nbsp;value3,&nbsp;float&nbsp;amount1,&nbsp;float&nbsp;amount2)`](VRageMath.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in Barycentric coordinates relative to a 3D triangle.|
|static&nbsp;[`void&nbsp;Barycentric(ref&nbsp;Vector3&nbsp;value1,&nbsp;ref&nbsp;Vector3&nbsp;value2,&nbsp;ref&nbsp;Vector3&nbsp;value3,&nbsp;float&nbsp;amount1,&nbsp;float&nbsp;amount2,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 3D triangle.|
|static&nbsp;[`void&nbsp;Barycentric(Vector3&nbsp;p,&nbsp;Vector3&nbsp;a,&nbsp;Vector3&nbsp;b,&nbsp;Vector3&nbsp;c,&nbsp;ref&nbsp;float&nbsp;u,&nbsp;ref&nbsp;float&nbsp;v,&nbsp;ref&nbsp;float&nbsp;w)`](VRageMath.Barycentric)|Compute barycentric coordinates (u, v, w) for point p with respect to triangle (a, b, c) From : Real-Time Collision Detection, Christer Ericson, CRC Press 3.4 Barycentric Coordinates|
|static&nbsp;[`float&nbsp;TriangleArea(Vector3&nbsp;v1,&nbsp;Vector3&nbsp;v2,&nbsp;Vector3&nbsp;v3)`](VRageMath.TriangleArea)||
|static&nbsp;[`float&nbsp;TriangleArea(ref&nbsp;Vector3&nbsp;v1,&nbsp;ref&nbsp;Vector3&nbsp;v2,&nbsp;ref&nbsp;Vector3&nbsp;v3)`](VRageMath.TriangleArea)||
|static&nbsp;[`Vector3&nbsp;SmoothStep(Vector3&nbsp;value1,&nbsp;Vector3&nbsp;value2,&nbsp;float&nbsp;amount)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static&nbsp;[`void&nbsp;SmoothStep(ref&nbsp;Vector3&nbsp;value1,&nbsp;ref&nbsp;Vector3&nbsp;value2,&nbsp;float&nbsp;amount,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static&nbsp;[`Vector3&nbsp;CatmullRom(Vector3&nbsp;value1,&nbsp;Vector3&nbsp;value2,&nbsp;Vector3&nbsp;value3,&nbsp;Vector3&nbsp;value4,&nbsp;float&nbsp;amount)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static&nbsp;[`void&nbsp;CatmullRom(ref&nbsp;Vector3&nbsp;value1,&nbsp;ref&nbsp;Vector3&nbsp;value2,&nbsp;ref&nbsp;Vector3&nbsp;value3,&nbsp;ref&nbsp;Vector3&nbsp;value4,&nbsp;float&nbsp;amount,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static&nbsp;[`Vector3&nbsp;Hermite(Vector3&nbsp;value1,&nbsp;Vector3&nbsp;tangent1,&nbsp;Vector3&nbsp;value2,&nbsp;Vector3&nbsp;tangent2,&nbsp;float&nbsp;amount)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static&nbsp;[`void&nbsp;Hermite(ref&nbsp;Vector3&nbsp;value1,&nbsp;ref&nbsp;Vector3&nbsp;tangent1,&nbsp;ref&nbsp;Vector3&nbsp;value2,&nbsp;ref&nbsp;Vector3&nbsp;tangent2,&nbsp;float&nbsp;amount,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static&nbsp;[`Vector3&nbsp;Transform(Vector3&nbsp;position,&nbsp;Matrix&nbsp;matrix)`](VRageMath.Transform)|Transforms a 3D vector by the given matrix.|
|static&nbsp;[`Vector3D&nbsp;Transform(Vector3&nbsp;position,&nbsp;MatrixD&nbsp;matrix)`](VRageMath.Transform)|Transforms a 3D vector by the given matrix.|
|static&nbsp;[`Vector3&nbsp;Transform(Vector3&nbsp;position,&nbsp;ref&nbsp;Matrix&nbsp;matrix)`](VRageMath.Transform)||
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector3&nbsp;position,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.Transform)|Transforms a Vector3 by the given Matrix.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector3&nbsp;position,&nbsp;ref&nbsp;MatrixI&nbsp;matrix,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.Transform)||
|static&nbsp;[`void&nbsp;TransformProjection(ref&nbsp;Vector3&nbsp;position,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.TransformProjection)|Transforms a Vector3 by the given projection matrix (both ortho and perspective are supported)|
|static&nbsp;[`void&nbsp;TransformNoProjection(ref&nbsp;Vector3&nbsp;vector,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.TransformNoProjection)||
|static&nbsp;[`void&nbsp;RotateAndScale(ref&nbsp;Vector3&nbsp;vector,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.RotateAndScale)||
|static&nbsp;[`Vector3&nbsp;RotateAndScale(Vector3&nbsp;vector,&nbsp;Matrix&nbsp;matrix)`](VRageMath.RotateAndScale)||
|static&nbsp;[`Vector3&nbsp;TransformNormal(Vector3&nbsp;normal,&nbsp;Matrix&nbsp;matrix)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|static&nbsp;[`Vector3&nbsp;TransformNormal(Vector3&nbsp;normal,&nbsp;MatrixD&nbsp;matrix)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|static&nbsp;[`Vector3&nbsp;TransformNormal(Vector3D&nbsp;normal,&nbsp;Matrix&nbsp;matrix)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|static&nbsp;[`void&nbsp;TransformNormal(ref&nbsp;Vector3&nbsp;normal,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|static&nbsp;[`void&nbsp;TransformNormal(ref&nbsp;Vector3&nbsp;normal,&nbsp;ref&nbsp;MatrixD&nbsp;matrix,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.TransformNormal)||
|static&nbsp;[`void&nbsp;TransformNormal(ref&nbsp;Vector3&nbsp;normal,&nbsp;ref&nbsp;MatrixI&nbsp;matrix,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.TransformNormal)||
|static&nbsp;[`Vector3&nbsp;TransformNormal(Vector3&nbsp;normal,&nbsp;MyBlockOrientation&nbsp;orientation)`](VRageMath.TransformNormal)||
|static&nbsp;[`void&nbsp;TransformNormal(ref&nbsp;Vector3&nbsp;normal,&nbsp;MyBlockOrientation&nbsp;orientation,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.TransformNormal)||
|static&nbsp;[`Vector3&nbsp;TransformNormal(Vector3&nbsp;normal,&nbsp;ref&nbsp;Matrix&nbsp;matrix)`](VRageMath.TransformNormal)||
|static&nbsp;[`Vector3&nbsp;Transform(Vector3&nbsp;value,&nbsp;Quaternion&nbsp;rotation)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector3&nbsp;value,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;ref&nbsp;Vector3&nbsp;result)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|static&nbsp;[`void&nbsp;Transform(Vector3[]&nbsp;sourceArray,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;Vector3[]&nbsp;destinationArray)`](VRageMath.Transform)|Transforms a source array of Vector3s by a specified Matrix and writes the results to an existing destination array.|
|static&nbsp;[`void&nbsp;Transform(Vector3[]&nbsp;sourceArray,&nbsp;int&nbsp;sourceIndex,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;Vector3[]&nbsp;destinationArray,&nbsp;int&nbsp;destinationIndex,&nbsp;int&nbsp;length)`](VRageMath.Transform)|Applies a specified transform Matrix to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|static&nbsp;[`void&nbsp;TransformNormal(Vector3[]&nbsp;sourceArray,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;Vector3[]&nbsp;destinationArray)`](VRageMath.TransformNormal)|Transforms an array of 3D vector normals by a specified Matrix.|
|static&nbsp;[`void&nbsp;TransformNormal(Vector3[]&nbsp;sourceArray,&nbsp;int&nbsp;sourceIndex,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;Vector3[]&nbsp;destinationArray,&nbsp;int&nbsp;destinationIndex,&nbsp;int&nbsp;length)`](VRageMath.TransformNormal)|Transforms a specified range in an array of 3D vector normals by a specified Matrix and writes the results to a specified range in a destination array.|
|static&nbsp;[`void&nbsp;Transform(Vector3[]&nbsp;sourceArray,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;Vector3[]&nbsp;destinationArray)`](VRageMath.Transform)|Transforms a source array of Vector3s by a specified Quaternion rotation and writes the results to an existing destination array.|
|static&nbsp;[`void&nbsp;Transform(Vector3[]&nbsp;sourceArray,&nbsp;int&nbsp;sourceIndex,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;Vector3[]&nbsp;destinationArray,&nbsp;int&nbsp;destinationIndex,&nbsp;int&nbsp;length)`](VRageMath.Transform)|Applies a specified Quaternion rotation to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|static&nbsp;[`Vector3&nbsp;Negate(Vector3&nbsp;value)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
