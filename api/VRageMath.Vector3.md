← [Index](ApiIndex)
# Vector3 Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with three components.
### Fields
|Member|Description|
|---|---|
|[`X`](VRageMath.X)|Gets or sets the x-component of the vector.|
|[`Y`](VRageMath.Y)|Gets or sets the y-component of the vector.|
|[`Z`](VRageMath.Z)|Gets or sets the z-component of the vector.|
|[`Zero`](VRageMath.Zero)||
|[`One`](VRageMath.One)||
|[`MinusOne`](VRageMath.MinusOne)||
|[`Half`](VRageMath.Half)||
|[`PositiveInfinity`](VRageMath.PositiveInfinity)||
|[`NegativeInfinity`](VRageMath.NegativeInfinity)||
|[`UnitX`](VRageMath.UnitX)||
|[`UnitY`](VRageMath.UnitY)||
|[`UnitZ`](VRageMath.UnitZ)||
|[`Up`](VRageMath.Up)||
|[`Down`](VRageMath.Down)||
|[`Right`](VRageMath.Right)||
|[`Left`](VRageMath.Left)||
|[`Forward`](VRageMath.Forward)||
|[`Backward`](VRageMath.Backward)||
|[`MaxValue`](VRageMath.MaxValue)||
|[`MinValue`](VRageMath.MinValue)||
|[`Invalid`](VRageMath.Invalid)||
### Properties
|Member|Description|
|---|---|
|[`Sum`](VRageMath.Sum)||
|[`Volume`](VRageMath.Volume)||
### Methods
|Member|Description|
|---|---|
|[`Negate(ref Vector3, ref Vector3)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|[`Add(Vector3, Vector3)`](VRageMath.Add)|Adds two vectors.|
|[`Add(ref Vector3, ref Vector3, ref Vector3)`](VRageMath.Add)|Adds two vectors.|
|[`Subtract(Vector3, Vector3)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|[`Subtract(ref Vector3, ref Vector3, ref Vector3)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|[`Multiply(Vector3, Vector3)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|[`Multiply(ref Vector3, ref Vector3, ref Vector3)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|[`Multiply(Vector3, float)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|[`Multiply(ref Vector3, float, ref Vector3)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|[`Divide(Vector3, Vector3)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|[`Divide(ref Vector3, ref Vector3, ref Vector3)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|[`Divide(Vector3, float)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|[`Divide(ref Vector3, float, ref Vector3)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|[`CalculatePerpendicularVector(Vector3)`](VRageMath.CalculatePerpendicularVector)||
|[`CalculatePerpendicularVector(ref Vector3)`](VRageMath.CalculatePerpendicularVector)||
|[`GetAzimuthAndElevation(Vector3, ref float, ref float)`](VRageMath.GetAzimuthAndElevation)||
|[`CreateFromAzimuthAndElevation(float, float, ref Vector3)`](VRageMath.CreateFromAzimuthAndElevation)||
|[`VolumeInt(float)`](VRageMath.VolumeInt)||
|[`IsInsideInclusive(ref Vector3, ref Vector3)`](VRageMath.IsInsideInclusive)||
|[`SwapYZCoordinates(Vector3)`](VRageMath.SwapYZCoordinates)||
|[`GetDim(int)`](VRageMath.GetDim)||
|[`SetDim(int, float)`](VRageMath.SetDim)||
|[`Ceiling(Vector3)`](VRageMath.Ceiling)||
|[`Floor(Vector3)`](VRageMath.Floor)||
|[`Round(Vector3)`](VRageMath.Round)||
|[`Round(Vector3, int)`](VRageMath.Round)||
|[`ProjectOnPlane(ref Vector3, ref Vector3)`](VRageMath.ProjectOnPlane)|Projects given vector on plane specified by it's normal.|
|[`ProjectOnVector(ref Vector3, ref Vector3)`](VRageMath.ProjectOnVector)|Projects vector on another vector resulting in new vector in guided vector's direction with different length.|
|[`IsZero(ref Vector3)`](VRageMath.IsZero)||
|[`Divide(float)`](VRageMath.Divide)||
|[`Multiply(float)`](VRageMath.Multiply)||
|[`Add(Vector3)`](VRageMath.Add)||
|[`Abs(Vector3)`](VRageMath.Abs)||
|[`Sign(Vector3)`](VRageMath.Sign)||
|[`Sign(Vector3, float)`](VRageMath.Sign)||
|[`SignNonZero(Vector3)`](VRageMath.SignNonZero)|Returns per component sign, never returns zero. For zero component returns sign 1. Faster than Sign.|
|[`Interpolate3(Vector3, Vector3, float)`](VRageMath.Interpolate3)||
|[`IsValid()`](VRageMath.IsValid)||
|[`AssertIsValid()`](VRageMath.AssertIsValid)||
|[`IsUnit(ref Vector3)`](VRageMath.IsUnit)||
|[`ArePerpendicular(ref Vector3, ref Vector3)`](VRageMath.ArePerpendicular)||
|[`IsZero(Vector3)`](VRageMath.IsZero)||
|[`IsZero(Vector3, float)`](VRageMath.IsZero)||
|[`IsZeroVector(Vector3)`](VRageMath.IsZeroVector)||
|[`IsZeroVector(Vector3, float)`](VRageMath.IsZeroVector)||
|[`Step(Vector3)`](VRageMath.Step)||
|[`ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`ToString(string)`](VRageMath.ToString)||
|[`Equals(Vector3)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector3.|
|[`Equals(Vector3, float)`](VRageMath.Equals)||
|[`Equals(Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`GetHashCode()`](VRageMath.GetHashCode)||
|[`GetHash()`](VRageMath.GetHash)|Gets the hash code of the vector object.|
|[`Length()`](VRageMath.Length)|Calculates the length of the vector.|
|[`LengthSquared()`](VRageMath.LengthSquared)|Calculates the length of the vector squared.|
|[`Distance(Vector3, Vector3)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|[`Distance(ref Vector3, ref Vector3, ref float)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|[`DistanceSquared(Vector3, Vector3)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|[`DistanceSquared(ref Vector3, ref Vector3, ref float)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|[`RectangularDistance(Vector3, Vector3)`](VRageMath.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|[`RectangularDistance(ref Vector3, ref Vector3)`](VRageMath.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|[`Dot(Vector3, Vector3)`](VRageMath.Dot)|Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[`Dot(ref Vector3, ref Vector3, ref float)`](VRageMath.Dot)|Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[`Dot(Vector3)`](VRageMath.Dot)||
|[`Dot(ref Vector3)`](VRageMath.Dot)||
|[`Cross(Vector3)`](VRageMath.Cross)||
|[`Normalize()`](VRageMath.Normalize)|Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[`Normalize(Vector3)`](VRageMath.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[`Normalize(Vector3D)`](VRageMath.Normalize)||
|[`GetNormalized(ref Vector3)`](VRageMath.GetNormalized)||
|[`Normalize(ref Vector3, ref Vector3)`](VRageMath.Normalize)|Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[`Cross(Vector3, Vector3)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|[`Cross(ref Vector3, ref Vector3, ref Vector3)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|[`Reflect(Vector3, Vector3)`](VRageMath.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|[`Reflect(ref Vector3, ref Vector3, ref Vector3)`](VRageMath.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|[`Reject(Vector3, Vector3)`](VRageMath.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|[`Reject(ref Vector3, ref Vector3, ref Vector3)`](VRageMath.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|[`Min()`](VRageMath.Min)|Returns the component of the vector that is smallest of all the three components.|
|[`AbsMin()`](VRageMath.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|[`Max()`](VRageMath.Max)|Returns the component of the vector that is largest of all the three components.|
|[`MaxAbsComponent()`](VRageMath.MaxAbsComponent)|Keeps only component with maximal absolute, others are set to zero.|
|[`AbsMax()`](VRageMath.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|[`Min(Vector3, Vector3)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|[`Min(ref Vector3, ref Vector3, ref Vector3)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|[`Max(Vector3, Vector3)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|[`Max(ref Vector3, ref Vector3, ref Vector3)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|[`MinMax(ref Vector3, ref Vector3)`](VRageMath.MinMax)|Separates minimal and maximal values of any two input vectors|
|[`DominantAxisProjection(Vector3)`](VRageMath.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|[`DominantAxisProjection(ref Vector3, ref Vector3)`](VRageMath.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved into a user-specified variable.|
|[`Clamp(Vector3, Vector3, Vector3)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|[`Clamp(ref Vector3, ref Vector3, ref Vector3, ref Vector3)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|[`ClampToSphere(Vector3, float)`](VRageMath.ClampToSphere)||
|[`ClampToSphere(ref Vector3, float)`](VRageMath.ClampToSphere)||
|[`Lerp(Vector3, Vector3, float)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|[`Lerp(ref Vector3, ref Vector3, float, ref Vector3)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|[`Barycentric(Vector3, Vector3, Vector3, float, float)`](VRageMath.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in Barycentric coordinates relative to a 3D triangle.|
|[`Barycentric(ref Vector3, ref Vector3, ref Vector3, float, float, ref Vector3)`](VRageMath.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 3D triangle.|
|[`Barycentric(Vector3, Vector3, Vector3, Vector3, ref float, ref float, ref float)`](VRageMath.Barycentric)|Compute barycentric coordinates (u, v, w) for point p with respect to triangle (a, b, c) From : Real-Time Collision Detection, Christer Ericson, CRC Press 3.4 Barycentric Coordinates|
|[`TriangleArea(Vector3, Vector3, Vector3)`](VRageMath.TriangleArea)||
|[`TriangleArea(ref Vector3, ref Vector3, ref Vector3)`](VRageMath.TriangleArea)||
|[`SmoothStep(Vector3, Vector3, float)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|[`SmoothStep(ref Vector3, ref Vector3, float, ref Vector3)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|[`CatmullRom(Vector3, Vector3, Vector3, Vector3, float)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|[`CatmullRom(ref Vector3, ref Vector3, ref Vector3, ref Vector3, float, ref Vector3)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|[`Hermite(Vector3, Vector3, Vector3, Vector3, float)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|[`Hermite(ref Vector3, ref Vector3, ref Vector3, ref Vector3, float, ref Vector3)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|[`Transform(Vector3, Matrix)`](VRageMath.Transform)|Transforms a 3D vector by the given matrix.|
|[`Transform(Vector3, MatrixD)`](VRageMath.Transform)|Transforms a 3D vector by the given matrix.|
|[`Transform(Vector3, ref Matrix)`](VRageMath.Transform)||
|[`Transform(ref Vector3, ref Matrix, ref Vector3)`](VRageMath.Transform)|Transforms a Vector3 by the given Matrix.|
|[`Transform(ref Vector3, ref MatrixI, ref Vector3)`](VRageMath.Transform)||
|[`TransformProjection(ref Vector3, ref Matrix, ref Vector3)`](VRageMath.TransformProjection)|Transforms a Vector3 by the given projection matrix (both ortho and perspective are supported)|
|[`TransformNoProjection(ref Vector3, ref Matrix, ref Vector3)`](VRageMath.TransformNoProjection)||
|[`RotateAndScale(ref Vector3, ref Matrix, ref Vector3)`](VRageMath.RotateAndScale)||
|[`RotateAndScale(Vector3, Matrix)`](VRageMath.RotateAndScale)||
|[`TransformNormal(Vector3, Matrix)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|[`TransformNormal(Vector3, MatrixD)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|[`TransformNormal(Vector3D, Matrix)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|[`TransformNormal(ref Vector3, ref Matrix, ref Vector3)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|[`TransformNormal(ref Vector3, ref MatrixD, ref Vector3)`](VRageMath.TransformNormal)||
|[`TransformNormal(ref Vector3, ref MatrixI, ref Vector3)`](VRageMath.TransformNormal)||
|[`TransformNormal(Vector3, MyBlockOrientation)`](VRageMath.TransformNormal)||
|[`TransformNormal(ref Vector3, MyBlockOrientation, ref Vector3)`](VRageMath.TransformNormal)||
|[`TransformNormal(Vector3, ref Matrix)`](VRageMath.TransformNormal)||
|[`Transform(Vector3, Quaternion)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|[`Transform(ref Vector3, ref Quaternion, ref Vector3)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|[`Transform(Vector3[], ref Matrix, Vector3[])`](VRageMath.Transform)|Transforms a source array of Vector3s by a specified Matrix and writes the results to an existing destination array.|
|[`Transform(Vector3[], int, ref Matrix, Vector3[], int, int)`](VRageMath.Transform)|Applies a specified transform Matrix to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|[`TransformNormal(Vector3[], ref Matrix, Vector3[])`](VRageMath.TransformNormal)|Transforms an array of 3D vector normals by a specified Matrix.|
|[`TransformNormal(Vector3[], int, ref Matrix, Vector3[], int, int)`](VRageMath.TransformNormal)|Transforms a specified range in an array of 3D vector normals by a specified Matrix and writes the results to a specified range in a destination array.|
|[`Transform(Vector3[], ref Quaternion, Vector3[])`](VRageMath.Transform)|Transforms a source array of Vector3s by a specified Quaternion rotation and writes the results to an existing destination array.|
|[`Transform(Vector3[], int, ref Quaternion, Vector3[], int, int)`](VRageMath.Transform)|Applies a specified Quaternion rotation to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|[`Negate(Vector3)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
