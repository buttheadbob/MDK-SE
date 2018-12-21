← [Index](index)
# Vector3D Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with three components.
### Fields
|Member|Description|
|---|---|
|[`double&nbsp;X`](VRageMath.X)|Gets or sets the x-component of the vector.|
|[`double&nbsp;Y`](VRageMath.Y)|Gets or sets the y-component of the vector.|
|[`double&nbsp;Z`](VRageMath.Z)|Gets or sets the z-component of the vector.|
|static&nbsp;[`Vector3D&nbsp;Zero`](VRageMath.Zero)||
|static&nbsp;[`Vector3D&nbsp;One`](VRageMath.One)||
|static&nbsp;[`Vector3D&nbsp;Half`](VRageMath.Half)||
|static&nbsp;[`Vector3D&nbsp;PositiveInfinity`](VRageMath.PositiveInfinity)||
|static&nbsp;[`Vector3D&nbsp;NegativeInfinity`](VRageMath.NegativeInfinity)||
|static&nbsp;[`Vector3D&nbsp;UnitX`](VRageMath.UnitX)||
|static&nbsp;[`Vector3D&nbsp;UnitY`](VRageMath.UnitY)||
|static&nbsp;[`Vector3D&nbsp;UnitZ`](VRageMath.UnitZ)||
|static&nbsp;[`Vector3D&nbsp;Up`](VRageMath.Up)||
|static&nbsp;[`Vector3D&nbsp;Down`](VRageMath.Down)||
|static&nbsp;[`Vector3D&nbsp;Right`](VRageMath.Right)||
|static&nbsp;[`Vector3D&nbsp;Left`](VRageMath.Left)||
|static&nbsp;[`Vector3D&nbsp;Forward`](VRageMath.Forward)||
|static&nbsp;[`Vector3D&nbsp;Backward`](VRageMath.Backward)||
|static&nbsp;[`Vector3D&nbsp;MaxValue`](VRageMath.MaxValue)||
|static&nbsp;[`Vector3D&nbsp;MinValue`](VRageMath.MinValue)||
### Properties
|Member|Description|
|---|---|
|[`double&nbsp;Sum`](VRageMath.Sum)||
|[`double&nbsp;Volume`](VRageMath.Volume)||
### Methods
|Member|Description|
|---|---|
|static&nbsp;[`void&nbsp;TransformNormal(ref&nbsp;Vector3D&nbsp;normal,&nbsp;ref&nbsp;MatrixI&nbsp;matrix,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.TransformNormal)||
|static&nbsp;[`Vector3D&nbsp;TransformNormal(Vector3D&nbsp;normal,&nbsp;MyBlockOrientation&nbsp;orientation)`](VRageMath.TransformNormal)||
|static&nbsp;[`void&nbsp;TransformNormal(ref&nbsp;Vector3D&nbsp;normal,&nbsp;MyBlockOrientation&nbsp;orientation,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.TransformNormal)||
|static&nbsp;[`Vector3D&nbsp;TransformNormal(Vector3D&nbsp;normal,&nbsp;ref&nbsp;MatrixD&nbsp;matrix)`](VRageMath.TransformNormal)||
|static&nbsp;[`Vector3D&nbsp;Transform(Vector3D&nbsp;value,&nbsp;Quaternion&nbsp;rotation)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector3D&nbsp;value,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|static&nbsp;[`void&nbsp;Rotate(ref&nbsp;Vector3D&nbsp;vector,&nbsp;ref&nbsp;MatrixD&nbsp;rotationMatrix,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.Rotate)||
|static&nbsp;[`Vector3D&nbsp;Rotate(Vector3D&nbsp;vector,&nbsp;MatrixD&nbsp;rotationMatrix)`](VRageMath.Rotate)||
|static&nbsp;[`void&nbsp;Transform(Vector3D[]&nbsp;sourceArray,&nbsp;ref&nbsp;MatrixD&nbsp;matrix,&nbsp;Vector3D[]&nbsp;destinationArray)`](VRageMath.Transform)|Transforms a source array of Vector3s by a specified Matrix and writes the results to an existing destination array.|
|static&nbsp;[`void&nbsp;Transform(Vector3D[]&nbsp;sourceArray,&nbsp;ref&nbsp;MatrixD&nbsp;matrix,&nbsp;*Vector3D&nbsp;destinationArray)`](VRageMath.Transform)||
|static&nbsp;[`void&nbsp;Transform(Vector3D[]&nbsp;sourceArray,&nbsp;int&nbsp;sourceIndex,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;Vector3D[]&nbsp;destinationArray,&nbsp;int&nbsp;destinationIndex,&nbsp;int&nbsp;length)`](VRageMath.Transform)|Applies a specified transform Matrix to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|static&nbsp;[`void&nbsp;TransformNormal(Vector3D[]&nbsp;sourceArray,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;Vector3D[]&nbsp;destinationArray)`](VRageMath.TransformNormal)|Transforms an array of 3D vector normals by a specified Matrix.|
|static&nbsp;[`void&nbsp;TransformNormal(Vector3D[]&nbsp;sourceArray,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;*Vector3D&nbsp;destinationArray)`](VRageMath.TransformNormal)||
|static&nbsp;[`void&nbsp;TransformNormal(Vector3D[]&nbsp;sourceArray,&nbsp;int&nbsp;sourceIndex,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;Vector3D[]&nbsp;destinationArray,&nbsp;int&nbsp;destinationIndex,&nbsp;int&nbsp;length)`](VRageMath.TransformNormal)|Transforms a specified range in an array of 3D vector normals by a specified Matrix and writes the results to a specified range in a destination array.|
|static&nbsp;[`void&nbsp;Transform(Vector3D[]&nbsp;sourceArray,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;Vector3D[]&nbsp;destinationArray)`](VRageMath.Transform)|Transforms a source array of Vector3s by a specified Quaternion rotation and writes the results to an existing destination array.|
|static&nbsp;[`void&nbsp;Transform(Vector3D[]&nbsp;sourceArray,&nbsp;int&nbsp;sourceIndex,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;Vector3D[]&nbsp;destinationArray,&nbsp;int&nbsp;destinationIndex,&nbsp;int&nbsp;length)`](VRageMath.Transform)|Applies a specified Quaternion rotation to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|static&nbsp;[`Vector3D&nbsp;Negate(Vector3D&nbsp;value)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static&nbsp;[`void&nbsp;Negate(ref&nbsp;Vector3D&nbsp;value,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static&nbsp;[`Vector3D&nbsp;Add(Vector3D&nbsp;value1,&nbsp;Vector3D&nbsp;value2)`](VRageMath.Add)|Adds two vectors.|
|static&nbsp;[`void&nbsp;Add(ref&nbsp;Vector3D&nbsp;value1,&nbsp;ref&nbsp;Vector3D&nbsp;value2,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.Add)|Adds two vectors.|
|static&nbsp;[`Vector3D&nbsp;Subtract(Vector3D&nbsp;value1,&nbsp;Vector3D&nbsp;value2)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static&nbsp;[`void&nbsp;Subtract(ref&nbsp;Vector3D&nbsp;value1,&nbsp;ref&nbsp;Vector3D&nbsp;value2,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static&nbsp;[`Vector3D&nbsp;Multiply(Vector3D&nbsp;value1,&nbsp;Vector3D&nbsp;value2)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static&nbsp;[`void&nbsp;Multiply(ref&nbsp;Vector3D&nbsp;value1,&nbsp;ref&nbsp;Vector3D&nbsp;value2,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static&nbsp;[`Vector3D&nbsp;Multiply(Vector3D&nbsp;value1,&nbsp;double&nbsp;scaleFactor)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static&nbsp;[`void&nbsp;Multiply(ref&nbsp;Vector3D&nbsp;value1,&nbsp;double&nbsp;scaleFactor,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static&nbsp;[`Vector3D&nbsp;Divide(Vector3D&nbsp;value1,&nbsp;Vector3D&nbsp;value2)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static&nbsp;[`void&nbsp;Divide(ref&nbsp;Vector3D&nbsp;value1,&nbsp;ref&nbsp;Vector3D&nbsp;value2,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static&nbsp;[`Vector3D&nbsp;Divide(Vector3D&nbsp;value1,&nbsp;double&nbsp;value2)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static&nbsp;[`void&nbsp;Divide(ref&nbsp;Vector3D&nbsp;value1,&nbsp;double&nbsp;value2,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static&nbsp;[`Vector3D&nbsp;CalculatePerpendicularVector(Vector3D&nbsp;v)`](VRageMath.CalculatePerpendicularVector)||
|[`void&nbsp;CalculatePerpendicularVector(ref&nbsp;Vector3D&nbsp;result)`](VRageMath.CalculatePerpendicularVector)||
|static&nbsp;[`void&nbsp;GetAzimuthAndElevation(Vector3D&nbsp;v,&nbsp;ref&nbsp;double&nbsp;azimuth,&nbsp;ref&nbsp;double&nbsp;elevation)`](VRageMath.GetAzimuthAndElevation)||
|static&nbsp;[`void&nbsp;CreateFromAzimuthAndElevation(double&nbsp;azimuth,&nbsp;double&nbsp;elevation,&nbsp;ref&nbsp;Vector3D&nbsp;direction)`](VRageMath.CreateFromAzimuthAndElevation)||
|[`long&nbsp;VolumeInt(double&nbsp;multiplier)`](VRageMath.VolumeInt)||
|[`bool&nbsp;IsInsideInclusive(ref&nbsp;Vector3D&nbsp;min,&nbsp;ref&nbsp;Vector3D&nbsp;max)`](VRageMath.IsInsideInclusive)||
|static&nbsp;[`Vector3D&nbsp;SwapYZCoordinates(Vector3D&nbsp;v)`](VRageMath.SwapYZCoordinates)||
|[`double&nbsp;GetDim(int&nbsp;i)`](VRageMath.GetDim)||
|[`void&nbsp;SetDim(int&nbsp;i,&nbsp;double&nbsp;value)`](VRageMath.SetDim)||
|static&nbsp;[`Vector3I&nbsp;Round(Vector3D&nbsp;vect3d)`](VRageMath.Round)||
|static&nbsp;[`Vector3I&nbsp;Floor(Vector3D&nbsp;vect3d)`](VRageMath.Floor)||
|static&nbsp;[`void&nbsp;Fract(ref&nbsp;Vector3D&nbsp;o,&nbsp;ref&nbsp;Vector3D&nbsp;r)`](VRageMath.Fract)||
|static&nbsp;[`Vector3D&nbsp;Round(Vector3D&nbsp;v,&nbsp;int&nbsp;numDecimals)`](VRageMath.Round)||
|static&nbsp;[`void&nbsp;Abs(ref&nbsp;Vector3D&nbsp;vector3D,&nbsp;ref&nbsp;Vector3D&nbsp;abs)`](VRageMath.Abs)||
|static&nbsp;[`Vector3D&nbsp;ProjectOnPlane(ref&nbsp;Vector3D&nbsp;vec,&nbsp;ref&nbsp;Vector3D&nbsp;planeNormal)`](VRageMath.ProjectOnPlane)|Projects given vector on plane specified by it's normal.|
|static&nbsp;[`Vector3D&nbsp;ProjectOnVector(ref&nbsp;Vector3D&nbsp;vec,&nbsp;ref&nbsp;Vector3D&nbsp;guideVector)`](VRageMath.ProjectOnVector)|Projects vector on another vector resulting in new vector in guided vector's direction with different length.|
|static&nbsp;[`Vector3D&nbsp;Abs(Vector3D&nbsp;value)`](VRageMath.Abs)||
|static&nbsp;[`Vector3D&nbsp;Sign(Vector3D&nbsp;value)`](VRageMath.Sign)||
|static&nbsp;[`Vector3D&nbsp;SignNonZero(Vector3D&nbsp;value)`](VRageMath.SignNonZero)|Returns per component sign, never returns zero. For zero component returns sign 1. Faster than Sign.|
|[`void&nbsp;Interpolate3(Vector3D&nbsp;v0,&nbsp;Vector3D&nbsp;v1,&nbsp;double&nbsp;rt)`](VRageMath.Interpolate3)||
|[`bool&nbsp;IsValid()`](VRageMath.IsValid)||
|[`void&nbsp;AssertIsValid()`](VRageMath.AssertIsValid)||
|static&nbsp;[`bool&nbsp;IsUnit(ref&nbsp;Vector3D&nbsp;value)`](VRageMath.IsUnit)||
|static&nbsp;[`bool&nbsp;ArePerpendicular(ref&nbsp;Vector3D&nbsp;a,&nbsp;ref&nbsp;Vector3D&nbsp;b)`](VRageMath.ArePerpendicular)||
|static&nbsp;[`bool&nbsp;IsZero(Vector3D&nbsp;value)`](VRageMath.IsZero)||
|static&nbsp;[`bool&nbsp;IsZero(Vector3D&nbsp;value,&nbsp;double&nbsp;epsilon)`](VRageMath.IsZero)||
|static&nbsp;[`Vector3D&nbsp;IsZeroVector(Vector3D&nbsp;value)`](VRageMath.IsZeroVector)||
|static&nbsp;[`Vector3D&nbsp;IsZeroVector(Vector3D&nbsp;value,&nbsp;double&nbsp;epsilon)`](VRageMath.IsZeroVector)||
|static&nbsp;[`Vector3D&nbsp;Step(Vector3D&nbsp;value)`](VRageMath.Step)||
|[`string&nbsp;ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|static&nbsp;[`bool&nbsp;TryParse(string&nbsp;str,&nbsp;ref&nbsp;Vector3D&nbsp;retval)`](VRageMath.TryParse)||
|[`string&nbsp;ToString(string&nbsp;format)`](VRageMath.ToString)||
|[`bool&nbsp;Equals(Vector3D&nbsp;other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector3.|
|[`bool&nbsp;Equals(Vector3D&nbsp;other,&nbsp;double&nbsp;epsilon)`](VRageMath.Equals)||
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)||
|[`long&nbsp;GetHash()`](VRageMath.GetHash)|Gets the hash code of the vector object.|
|[`double&nbsp;Length()`](VRageMath.Length)|Calculates the length of the vector.|
|[`double&nbsp;LengthSquared()`](VRageMath.LengthSquared)|Calculates the length of the vector squared.|
|static&nbsp;[`double&nbsp;Distance(Vector3D&nbsp;value1,&nbsp;Vector3D&nbsp;value2)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static&nbsp;[`double&nbsp;Distance(Vector3D&nbsp;value1,&nbsp;Vector3&nbsp;value2)`](VRageMath.Distance)||
|static&nbsp;[`double&nbsp;Distance(Vector3&nbsp;value1,&nbsp;Vector3D&nbsp;value2)`](VRageMath.Distance)||
|static&nbsp;[`void&nbsp;Distance(ref&nbsp;Vector3D&nbsp;value1,&nbsp;ref&nbsp;Vector3D&nbsp;value2,&nbsp;ref&nbsp;double&nbsp;result)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static&nbsp;[`double&nbsp;DistanceSquared(Vector3D&nbsp;value1,&nbsp;Vector3D&nbsp;value2)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static&nbsp;[`void&nbsp;DistanceSquared(ref&nbsp;Vector3D&nbsp;value1,&nbsp;ref&nbsp;Vector3D&nbsp;value2,&nbsp;ref&nbsp;double&nbsp;result)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static&nbsp;[`double&nbsp;RectangularDistance(Vector3D&nbsp;value1,&nbsp;Vector3D&nbsp;value2)`](VRageMath.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|static&nbsp;[`double&nbsp;RectangularDistance(ref&nbsp;Vector3D&nbsp;value1,&nbsp;ref&nbsp;Vector3D&nbsp;value2)`](VRageMath.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|static&nbsp;[`double&nbsp;Dot(Vector3D&nbsp;vector1,&nbsp;Vector3D&nbsp;vector2)`](VRageMath.Dot)|Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|static&nbsp;[`double&nbsp;Dot(Vector3D&nbsp;vector1,&nbsp;Vector3&nbsp;vector2)`](VRageMath.Dot)||
|static&nbsp;[`void&nbsp;Dot(ref&nbsp;Vector3D&nbsp;vector1,&nbsp;ref&nbsp;Vector3D&nbsp;vector2,&nbsp;ref&nbsp;double&nbsp;result)`](VRageMath.Dot)|Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|static&nbsp;[`void&nbsp;Dot(ref&nbsp;Vector3D&nbsp;vector1,&nbsp;ref&nbsp;Vector3&nbsp;vector2,&nbsp;ref&nbsp;double&nbsp;result)`](VRageMath.Dot)||
|static&nbsp;[`void&nbsp;Dot(ref&nbsp;Vector3&nbsp;vector1,&nbsp;ref&nbsp;Vector3D&nbsp;vector2,&nbsp;ref&nbsp;double&nbsp;result)`](VRageMath.Dot)||
|[`double&nbsp;Dot(Vector3D&nbsp;v)`](VRageMath.Dot)||
|[`double&nbsp;Dot(Vector3&nbsp;v)`](VRageMath.Dot)||
|[`double&nbsp;Dot(ref&nbsp;Vector3D&nbsp;v)`](VRageMath.Dot)||
|[`Vector3D&nbsp;Cross(Vector3D&nbsp;v)`](VRageMath.Cross)||
|[`double&nbsp;Normalize()`](VRageMath.Normalize)|Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static&nbsp;[`Vector3D&nbsp;Normalize(Vector3D&nbsp;value)`](VRageMath.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static&nbsp;[`void&nbsp;Normalize(ref&nbsp;Vector3D&nbsp;value,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.Normalize)|Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static&nbsp;[`Vector3D&nbsp;Cross(Vector3D&nbsp;vector1,&nbsp;Vector3D&nbsp;vector2)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|static&nbsp;[`void&nbsp;Cross(ref&nbsp;Vector3D&nbsp;vector1,&nbsp;ref&nbsp;Vector3D&nbsp;vector2,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|static&nbsp;[`Vector3D&nbsp;Reflect(Vector3D&nbsp;vector,&nbsp;Vector3D&nbsp;normal)`](VRageMath.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|static&nbsp;[`void&nbsp;Reflect(ref&nbsp;Vector3D&nbsp;vector,&nbsp;ref&nbsp;Vector3D&nbsp;normal,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|static&nbsp;[`Vector3D&nbsp;Reject(Vector3D&nbsp;vector,&nbsp;Vector3D&nbsp;direction)`](VRageMath.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|static&nbsp;[`void&nbsp;Reject(ref&nbsp;Vector3D&nbsp;vector,&nbsp;ref&nbsp;Vector3D&nbsp;direction,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|[`double&nbsp;Min()`](VRageMath.Min)|Returns the component of the vector that is smallest of all the three components.|
|[`double&nbsp;AbsMin()`](VRageMath.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|[`double&nbsp;Max()`](VRageMath.Max)|Returns the component of the vector that is largest of all the three components.|
|[`double&nbsp;AbsMax()`](VRageMath.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|[`int&nbsp;AbsMaxComponent()`](VRageMath.AbsMaxComponent)||
|static&nbsp;[`Vector3D&nbsp;Min(Vector3D&nbsp;value1,&nbsp;Vector3D&nbsp;value2)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static&nbsp;[`void&nbsp;Min(ref&nbsp;Vector3D&nbsp;value1,&nbsp;ref&nbsp;Vector3D&nbsp;value2,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static&nbsp;[`Vector3D&nbsp;Max(Vector3D&nbsp;value1,&nbsp;Vector3D&nbsp;value2)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static&nbsp;[`void&nbsp;Max(ref&nbsp;Vector3D&nbsp;value1,&nbsp;ref&nbsp;Vector3D&nbsp;value2,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static&nbsp;[`void&nbsp;MinMax(ref&nbsp;Vector3D&nbsp;min,&nbsp;ref&nbsp;Vector3D&nbsp;max)`](VRageMath.MinMax)|Separates minimal and maximal values of any two input vectors|
|static&nbsp;[`Vector3D&nbsp;DominantAxisProjection(Vector3D&nbsp;value1)`](VRageMath.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|static&nbsp;[`void&nbsp;DominantAxisProjection(ref&nbsp;Vector3D&nbsp;value1,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved into a user-specified variable.|
|static&nbsp;[`Vector3D&nbsp;Clamp(Vector3D&nbsp;value1,&nbsp;Vector3D&nbsp;min,&nbsp;Vector3D&nbsp;max)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static&nbsp;[`void&nbsp;Clamp(ref&nbsp;Vector3D&nbsp;value1,&nbsp;ref&nbsp;Vector3D&nbsp;min,&nbsp;ref&nbsp;Vector3D&nbsp;max,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static&nbsp;[`Vector3D&nbsp;ClampToSphere(Vector3D&nbsp;vector,&nbsp;double&nbsp;radius)`](VRageMath.ClampToSphere)||
|static&nbsp;[`void&nbsp;ClampToSphere(ref&nbsp;Vector3D&nbsp;vector,&nbsp;double&nbsp;radius)`](VRageMath.ClampToSphere)||
|static&nbsp;[`Vector3D&nbsp;Lerp(Vector3D&nbsp;value1,&nbsp;Vector3D&nbsp;value2,&nbsp;double&nbsp;amount)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static&nbsp;[`void&nbsp;Lerp(ref&nbsp;Vector3D&nbsp;value1,&nbsp;ref&nbsp;Vector3D&nbsp;value2,&nbsp;double&nbsp;amount,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static&nbsp;[`Vector3D&nbsp;Barycentric(Vector3D&nbsp;value1,&nbsp;Vector3D&nbsp;value2,&nbsp;Vector3D&nbsp;value3,&nbsp;double&nbsp;amount1,&nbsp;double&nbsp;amount2)`](VRageMath.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in Barycentric coordinates relative to a 3D triangle.|
|static&nbsp;[`void&nbsp;Barycentric(ref&nbsp;Vector3D&nbsp;value1,&nbsp;ref&nbsp;Vector3D&nbsp;value2,&nbsp;ref&nbsp;Vector3D&nbsp;value3,&nbsp;double&nbsp;amount1,&nbsp;double&nbsp;amount2,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 3D triangle.|
|static&nbsp;[`void&nbsp;Barycentric(Vector3D&nbsp;p,&nbsp;Vector3D&nbsp;a,&nbsp;Vector3D&nbsp;b,&nbsp;Vector3D&nbsp;c,&nbsp;ref&nbsp;double&nbsp;u,&nbsp;ref&nbsp;double&nbsp;v,&nbsp;ref&nbsp;double&nbsp;w)`](VRageMath.Barycentric)|Compute barycentric coordinates (u, v, w) for point p with respect to triangle (a, b, c) From : Real-Time Collision Detection, Christer Ericson, CRC Press 3.4 Barycentric Coordinates|
|static&nbsp;[`Vector3D&nbsp;SmoothStep(Vector3D&nbsp;value1,&nbsp;Vector3D&nbsp;value2,&nbsp;double&nbsp;amount)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static&nbsp;[`void&nbsp;SmoothStep(ref&nbsp;Vector3D&nbsp;value1,&nbsp;ref&nbsp;Vector3D&nbsp;value2,&nbsp;double&nbsp;amount,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static&nbsp;[`Vector3D&nbsp;CatmullRom(Vector3D&nbsp;value1,&nbsp;Vector3D&nbsp;value2,&nbsp;Vector3D&nbsp;value3,&nbsp;Vector3D&nbsp;value4,&nbsp;double&nbsp;amount)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static&nbsp;[`void&nbsp;CatmullRom(ref&nbsp;Vector3D&nbsp;value1,&nbsp;ref&nbsp;Vector3D&nbsp;value2,&nbsp;ref&nbsp;Vector3D&nbsp;value3,&nbsp;ref&nbsp;Vector3D&nbsp;value4,&nbsp;double&nbsp;amount,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static&nbsp;[`Vector3D&nbsp;Hermite(Vector3D&nbsp;value1,&nbsp;Vector3D&nbsp;tangent1,&nbsp;Vector3D&nbsp;value2,&nbsp;Vector3D&nbsp;tangent2,&nbsp;double&nbsp;amount)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static&nbsp;[`void&nbsp;Hermite(ref&nbsp;Vector3D&nbsp;value1,&nbsp;ref&nbsp;Vector3D&nbsp;tangent1,&nbsp;ref&nbsp;Vector3D&nbsp;value2,&nbsp;ref&nbsp;Vector3D&nbsp;tangent2,&nbsp;double&nbsp;amount,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static&nbsp;[`Vector3D&nbsp;Transform(Vector3D&nbsp;position,&nbsp;MatrixD&nbsp;matrix)`](VRageMath.Transform)|Transforms a 3D vector by the given matrix.|
|static&nbsp;[`Vector3D&nbsp;Transform(Vector3&nbsp;position,&nbsp;MatrixD&nbsp;matrix)`](VRageMath.Transform)||
|static&nbsp;[`Vector3D&nbsp;Transform(Vector3D&nbsp;position,&nbsp;Matrix&nbsp;matrix)`](VRageMath.Transform)|Transforms a 3D vector by the given matrix.|
|static&nbsp;[`Vector3D&nbsp;Transform(Vector3D&nbsp;position,&nbsp;ref&nbsp;MatrixD&nbsp;matrix)`](VRageMath.Transform)||
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector3D&nbsp;position,&nbsp;ref&nbsp;MatrixD&nbsp;matrix,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.Transform)|Transforms a Vector3 by the given Matrix.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector3&nbsp;position,&nbsp;ref&nbsp;MatrixD&nbsp;matrix,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.Transform)||
|static&nbsp;[`void&nbsp;TransformNoProjection(ref&nbsp;Vector3D&nbsp;vector,&nbsp;ref&nbsp;MatrixD&nbsp;matrix,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.TransformNoProjection)||
|static&nbsp;[`void&nbsp;RotateAndScale(ref&nbsp;Vector3D&nbsp;vector,&nbsp;ref&nbsp;MatrixD&nbsp;matrix,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.RotateAndScale)||
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector3D&nbsp;position,&nbsp;ref&nbsp;MatrixI&nbsp;matrix,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.Transform)||
|static&nbsp;[`Vector3D&nbsp;TransformNormal(Vector3D&nbsp;normal,&nbsp;Matrix&nbsp;matrix)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|static&nbsp;[`Vector3D&nbsp;TransformNormal(Vector3&nbsp;normal,&nbsp;MatrixD&nbsp;matrix)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|static&nbsp;[`Vector3D&nbsp;TransformNormal(Vector3D&nbsp;normal,&nbsp;MatrixD&nbsp;matrix)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|static&nbsp;[`void&nbsp;TransformNormal(ref&nbsp;Vector3D&nbsp;normal,&nbsp;ref&nbsp;MatrixD&nbsp;matrix,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|static&nbsp;[`void&nbsp;TransformNormal(ref&nbsp;Vector3&nbsp;normal,&nbsp;ref&nbsp;MatrixD&nbsp;matrix,&nbsp;ref&nbsp;Vector3D&nbsp;result)`](VRageMath.TransformNormal)||
