← [Index](index)
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
|static [`Zero`](VRageMath.Zero)||
|static [`One`](VRageMath.One)||
|static [`MinusOne`](VRageMath.MinusOne)||
|static [`Half`](VRageMath.Half)||
|static [`PositiveInfinity`](VRageMath.PositiveInfinity)||
|static [`NegativeInfinity`](VRageMath.NegativeInfinity)||
|static [`UnitX`](VRageMath.UnitX)||
|static [`UnitY`](VRageMath.UnitY)||
|static [`UnitZ`](VRageMath.UnitZ)||
|static [`Up`](VRageMath.Up)||
|static [`Down`](VRageMath.Down)||
|static [`Right`](VRageMath.Right)||
|static [`Left`](VRageMath.Left)||
|static [`Forward`](VRageMath.Forward)||
|static [`Backward`](VRageMath.Backward)||
|static [`MaxValue`](VRageMath.MaxValue)||
|static [`MinValue`](VRageMath.MinValue)||
|static [`Invalid`](VRageMath.Invalid)||
### Properties
|Member|Description|
|---|---|
|[`Sum`](VRageMath.Sum)||
|[`Volume`](VRageMath.Volume)||
### Methods
|Member|Description|
|---|---|
|static [`Negate(ref Vector3, ref Vector3)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`Add(Vector3, Vector3)`](VRageMath.Add)|Adds two vectors.|
|static [`Add(ref Vector3, ref Vector3, ref Vector3)`](VRageMath.Add)|Adds two vectors.|
|static [`Subtract(Vector3, Vector3)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`Subtract(ref Vector3, ref Vector3, ref Vector3)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`Multiply(Vector3, Vector3)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`Multiply(ref Vector3, ref Vector3, ref Vector3)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`Multiply(Vector3, float)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`Multiply(ref Vector3, float, ref Vector3)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`Divide(Vector3, Vector3)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`Divide(ref Vector3, ref Vector3, ref Vector3)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`Divide(Vector3, float)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static [`Divide(ref Vector3, float, ref Vector3)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static [`CalculatePerpendicularVector(Vector3)`](VRageMath.CalculatePerpendicularVector)||
|[`CalculatePerpendicularVector(ref Vector3)`](VRageMath.CalculatePerpendicularVector)||
|static [`GetAzimuthAndElevation(Vector3, ref float, ref float)`](VRageMath.GetAzimuthAndElevation)||
|static [`CreateFromAzimuthAndElevation(float, float, ref Vector3)`](VRageMath.CreateFromAzimuthAndElevation)||
|[`VolumeInt(float)`](VRageMath.VolumeInt)||
|[`IsInsideInclusive(ref Vector3, ref Vector3)`](VRageMath.IsInsideInclusive)||
|static [`SwapYZCoordinates(Vector3)`](VRageMath.SwapYZCoordinates)||
|[`GetDim(int)`](VRageMath.GetDim)||
|[`SetDim(int, float)`](VRageMath.SetDim)||
|static [`Ceiling(Vector3)`](VRageMath.Ceiling)||
|static [`Floor(Vector3)`](VRageMath.Floor)||
|static [`Round(Vector3)`](VRageMath.Round)||
|static [`Round(Vector3, int)`](VRageMath.Round)||
|static [`ProjectOnPlane(ref Vector3, ref Vector3)`](VRageMath.ProjectOnPlane)|Projects given vector on plane specified by it's normal.|
|static [`ProjectOnVector(ref Vector3, ref Vector3)`](VRageMath.ProjectOnVector)|Projects vector on another vector resulting in new vector in guided vector's direction with different length.|
|static [`IsZero(ref Vector3)`](VRageMath.IsZero)||
|[`Divide(float)`](VRageMath.Divide)||
|[`Multiply(float)`](VRageMath.Multiply)||
|[`Add(Vector3)`](VRageMath.Add)||
|static [`Abs(Vector3)`](VRageMath.Abs)||
|static [`Sign(Vector3)`](VRageMath.Sign)||
|static [`Sign(Vector3, float)`](VRageMath.Sign)||
|static [`SignNonZero(Vector3)`](VRageMath.SignNonZero)|Returns per component sign, never returns zero. For zero component returns sign 1. Faster than Sign.|
|[`Interpolate3(Vector3, Vector3, float)`](VRageMath.Interpolate3)||
|[`IsValid()`](VRageMath.IsValid)||
|[`AssertIsValid()`](VRageMath.AssertIsValid)||
|static [`IsUnit(ref Vector3)`](VRageMath.IsUnit)||
|static [`ArePerpendicular(ref Vector3, ref Vector3)`](VRageMath.ArePerpendicular)||
|static [`IsZero(Vector3)`](VRageMath.IsZero)||
|static [`IsZero(Vector3, float)`](VRageMath.IsZero)||
|static [`IsZeroVector(Vector3)`](VRageMath.IsZeroVector)||
|static [`IsZeroVector(Vector3, float)`](VRageMath.IsZeroVector)||
|static [`Step(Vector3)`](VRageMath.Step)||
|[`ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|[`ToString(string)`](VRageMath.ToString)||
|[`Equals(Vector3)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector3.|
|[`Equals(Vector3, float)`](VRageMath.Equals)||
|[`Equals(Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`GetHashCode()`](VRageMath.GetHashCode)||
|[`GetHash()`](VRageMath.GetHash)|Gets the hash code of the vector object.|
|[`Length()`](VRageMath.Length)|Calculates the length of the vector.|
|[`LengthSquared()`](VRageMath.LengthSquared)|Calculates the length of the vector squared.|
|static [`Distance(Vector3, Vector3)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`Distance(ref Vector3, ref Vector3, ref float)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`DistanceSquared(Vector3, Vector3)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`DistanceSquared(ref Vector3, ref Vector3, ref float)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`RectangularDistance(Vector3, Vector3)`](VRageMath.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|static [`RectangularDistance(ref Vector3, ref Vector3)`](VRageMath.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|static [`Dot(Vector3, Vector3)`](VRageMath.Dot)|Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|static [`Dot(ref Vector3, ref Vector3, ref float)`](VRageMath.Dot)|Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[`Dot(Vector3)`](VRageMath.Dot)||
|[`Dot(ref Vector3)`](VRageMath.Dot)||
|[`Cross(Vector3)`](VRageMath.Cross)||
|[`Normalize()`](VRageMath.Normalize)|Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`Normalize(Vector3)`](VRageMath.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`Normalize(Vector3D)`](VRageMath.Normalize)||
|static [`GetNormalized(ref Vector3)`](VRageMath.GetNormalized)||
|static [`Normalize(ref Vector3, ref Vector3)`](VRageMath.Normalize)|Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`Cross(Vector3, Vector3)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|static [`Cross(ref Vector3, ref Vector3, ref Vector3)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|static [`Reflect(Vector3, Vector3)`](VRageMath.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|static [`Reflect(ref Vector3, ref Vector3, ref Vector3)`](VRageMath.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|static [`Reject(Vector3, Vector3)`](VRageMath.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|static [`Reject(ref Vector3, ref Vector3, ref Vector3)`](VRageMath.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|[`Min()`](VRageMath.Min)|Returns the component of the vector that is smallest of all the three components.|
|[`AbsMin()`](VRageMath.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|[`Max()`](VRageMath.Max)|Returns the component of the vector that is largest of all the three components.|
|[`MaxAbsComponent()`](VRageMath.MaxAbsComponent)|Keeps only component with maximal absolute, others are set to zero.|
|[`AbsMax()`](VRageMath.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|static [`Min(Vector3, Vector3)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`Min(ref Vector3, ref Vector3, ref Vector3)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`Max(Vector3, Vector3)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`Max(ref Vector3, ref Vector3, ref Vector3)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`MinMax(ref Vector3, ref Vector3)`](VRageMath.MinMax)|Separates minimal and maximal values of any two input vectors|
|static [`DominantAxisProjection(Vector3)`](VRageMath.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|static [`DominantAxisProjection(ref Vector3, ref Vector3)`](VRageMath.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved into a user-specified variable.|
|static [`Clamp(Vector3, Vector3, Vector3)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`Clamp(ref Vector3, ref Vector3, ref Vector3, ref Vector3)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`ClampToSphere(Vector3, float)`](VRageMath.ClampToSphere)||
|static [`ClampToSphere(ref Vector3, float)`](VRageMath.ClampToSphere)||
|static [`Lerp(Vector3, Vector3, float)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`Lerp(ref Vector3, ref Vector3, float, ref Vector3)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`Barycentric(Vector3, Vector3, Vector3, float, float)`](VRageMath.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in Barycentric coordinates relative to a 3D triangle.|
|static [`Barycentric(ref Vector3, ref Vector3, ref Vector3, float, float, ref Vector3)`](VRageMath.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 3D triangle.|
|static [`Barycentric(Vector3, Vector3, Vector3, Vector3, ref float, ref float, ref float)`](VRageMath.Barycentric)|Compute barycentric coordinates (u, v, w) for point p with respect to triangle (a, b, c) From : Real-Time Collision Detection, Christer Ericson, CRC Press 3.4 Barycentric Coordinates|
|static [`TriangleArea(Vector3, Vector3, Vector3)`](VRageMath.TriangleArea)||
|static [`TriangleArea(ref Vector3, ref Vector3, ref Vector3)`](VRageMath.TriangleArea)||
|static [`SmoothStep(Vector3, Vector3, float)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`SmoothStep(ref Vector3, ref Vector3, float, ref Vector3)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`CatmullRom(Vector3, Vector3, Vector3, Vector3, float)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`CatmullRom(ref Vector3, ref Vector3, ref Vector3, ref Vector3, float, ref Vector3)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`Hermite(Vector3, Vector3, Vector3, Vector3, float)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`Hermite(ref Vector3, ref Vector3, ref Vector3, ref Vector3, float, ref Vector3)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`Transform(Vector3, Matrix)`](VRageMath.Transform)|Transforms a 3D vector by the given matrix.|
|static [`Transform(Vector3, MatrixD)`](VRageMath.Transform)|Transforms a 3D vector by the given matrix.|
|static [`Transform(Vector3, ref Matrix)`](VRageMath.Transform)||
|static [`Transform(ref Vector3, ref Matrix, ref Vector3)`](VRageMath.Transform)|Transforms a Vector3 by the given Matrix.|
|static [`Transform(ref Vector3, ref MatrixI, ref Vector3)`](VRageMath.Transform)||
|static [`TransformProjection(ref Vector3, ref Matrix, ref Vector3)`](VRageMath.TransformProjection)|Transforms a Vector3 by the given projection matrix (both ortho and perspective are supported)|
|static [`TransformNoProjection(ref Vector3, ref Matrix, ref Vector3)`](VRageMath.TransformNoProjection)||
|static [`RotateAndScale(ref Vector3, ref Matrix, ref Vector3)`](VRageMath.RotateAndScale)||
|static [`RotateAndScale(Vector3, Matrix)`](VRageMath.RotateAndScale)||
|static [`TransformNormal(Vector3, Matrix)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|static [`TransformNormal(Vector3, MatrixD)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|static [`TransformNormal(Vector3D, Matrix)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|static [`TransformNormal(ref Vector3, ref Matrix, ref Vector3)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|static [`TransformNormal(ref Vector3, ref MatrixD, ref Vector3)`](VRageMath.TransformNormal)||
|static [`TransformNormal(ref Vector3, ref MatrixI, ref Vector3)`](VRageMath.TransformNormal)||
|static [`TransformNormal(Vector3, MyBlockOrientation)`](VRageMath.TransformNormal)||
|static [`TransformNormal(ref Vector3, MyBlockOrientation, ref Vector3)`](VRageMath.TransformNormal)||
|static [`TransformNormal(Vector3, ref Matrix)`](VRageMath.TransformNormal)||
|static [`Transform(Vector3, Quaternion)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|static [`Transform(ref Vector3, ref Quaternion, ref Vector3)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|static [`Transform(Vector3[], ref Matrix, Vector3[])`](VRageMath.Transform)|Transforms a source array of Vector3s by a specified Matrix and writes the results to an existing destination array.|
|static [`Transform(Vector3[], int, ref Matrix, Vector3[], int, int)`](VRageMath.Transform)|Applies a specified transform Matrix to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|static [`TransformNormal(Vector3[], ref Matrix, Vector3[])`](VRageMath.TransformNormal)|Transforms an array of 3D vector normals by a specified Matrix.|
|static [`TransformNormal(Vector3[], int, ref Matrix, Vector3[], int, int)`](VRageMath.TransformNormal)|Transforms a specified range in an array of 3D vector normals by a specified Matrix and writes the results to a specified range in a destination array.|
|static [`Transform(Vector3[], ref Quaternion, Vector3[])`](VRageMath.Transform)|Transforms a source array of Vector3s by a specified Quaternion rotation and writes the results to an existing destination array.|
|static [`Transform(Vector3[], int, ref Quaternion, Vector3[], int, int)`](VRageMath.Transform)|Applies a specified Quaternion rotation to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|static [`Negate(Vector3)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
