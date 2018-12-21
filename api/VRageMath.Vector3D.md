← [Index](index)
# Vector3D Struct
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
|static [`Zero`](VRageMath.Zero)||
|static [`One`](VRageMath.One)||
|static [`Half`](VRageMath.Half)||
|static [`PositiveInfinity`](VRageMath.PositiveInfinity)||
|static [`NegativeInfinity`](VRageMath.NegativeInfinity)||
|static [`UnitX`](VRageMath.UnitX)||
|static [`UnitY`](VRageMath.UnitY)||
|static [`UnitZ`](VRageMath.UnitZ)||
|static [`Up`](VRageMath.Up)||
|static [`Down`](VRageMath.Down)||
|static [`Right`](VRageMath.Right)||
|static [`Left`](VRageMath.Left)||
|static [`Forward`](VRageMath.Forward)||
|static [`Backward`](VRageMath.Backward)||
|static [`MaxValue`](VRageMath.MaxValue)||
|static [`MinValue`](VRageMath.MinValue)||
### Properties
|Member|Description|
|---|---|
|[`Sum`](VRageMath.Sum)||
|[`Volume`](VRageMath.Volume)||
### Methods
|Member|Description|
|---|---|
|static [`TransformNormal(ref Vector3D, ref MatrixI, ref Vector3D)`](VRageMath.TransformNormal)||
|static [`TransformNormal(Vector3D, MyBlockOrientation)`](VRageMath.TransformNormal)||
|static [`TransformNormal(ref Vector3D, MyBlockOrientation, ref Vector3D)`](VRageMath.TransformNormal)||
|static [`TransformNormal(Vector3D, ref MatrixD)`](VRageMath.TransformNormal)||
|static [`Transform(Vector3D, Quaternion)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|static [`Transform(ref Vector3D, ref Quaternion, ref Vector3D)`](VRageMath.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|static [`Rotate(ref Vector3D, ref MatrixD, ref Vector3D)`](VRageMath.Rotate)||
|static [`Rotate(Vector3D, MatrixD)`](VRageMath.Rotate)||
|static [`Transform(Vector3D[], ref MatrixD, Vector3D[])`](VRageMath.Transform)|Transforms a source array of Vector3s by a specified Matrix and writes the results to an existing destination array.|
|static [`Transform(Vector3D[], ref MatrixD, *Vector3D)`](VRageMath.Transform)||
|static [`Transform(Vector3D[], int, ref Matrix, Vector3D[], int, int)`](VRageMath.Transform)|Applies a specified transform Matrix to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|static [`TransformNormal(Vector3D[], ref Matrix, Vector3D[])`](VRageMath.TransformNormal)|Transforms an array of 3D vector normals by a specified Matrix.|
|static [`TransformNormal(Vector3D[], ref Matrix, *Vector3D)`](VRageMath.TransformNormal)||
|static [`TransformNormal(Vector3D[], int, ref Matrix, Vector3D[], int, int)`](VRageMath.TransformNormal)|Transforms a specified range in an array of 3D vector normals by a specified Matrix and writes the results to a specified range in a destination array.|
|static [`Transform(Vector3D[], ref Quaternion, Vector3D[])`](VRageMath.Transform)|Transforms a source array of Vector3s by a specified Quaternion rotation and writes the results to an existing destination array.|
|static [`Transform(Vector3D[], int, ref Quaternion, Vector3D[], int, int)`](VRageMath.Transform)|Applies a specified Quaternion rotation to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|static [`Negate(Vector3D)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`Negate(ref Vector3D, ref Vector3D)`](VRageMath.Negate)|Returns a vector pointing in the opposite direction.|
|static [`Add(Vector3D, Vector3D)`](VRageMath.Add)|Adds two vectors.|
|static [`Add(ref Vector3D, ref Vector3D, ref Vector3D)`](VRageMath.Add)|Adds two vectors.|
|static [`Subtract(Vector3D, Vector3D)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`Subtract(ref Vector3D, ref Vector3D, ref Vector3D)`](VRageMath.Subtract)|Subtracts a vector from a vector.|
|static [`Multiply(Vector3D, Vector3D)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`Multiply(ref Vector3D, ref Vector3D, ref Vector3D)`](VRageMath.Multiply)|Multiplies the components of two vectors by each other.|
|static [`Multiply(Vector3D, double)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`Multiply(ref Vector3D, double, ref Vector3D)`](VRageMath.Multiply)|Multiplies a vector by a scalar value.|
|static [`Divide(Vector3D, Vector3D)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`Divide(ref Vector3D, ref Vector3D, ref Vector3D)`](VRageMath.Divide)|Divides the components of a vector by the components of another vector.|
|static [`Divide(Vector3D, double)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static [`Divide(ref Vector3D, double, ref Vector3D)`](VRageMath.Divide)|Divides a vector by a scalar value.|
|static [`CalculatePerpendicularVector(Vector3D)`](VRageMath.CalculatePerpendicularVector)||
|[`CalculatePerpendicularVector(ref Vector3D)`](VRageMath.CalculatePerpendicularVector)||
|static [`GetAzimuthAndElevation(Vector3D, ref double, ref double)`](VRageMath.GetAzimuthAndElevation)||
|static [`CreateFromAzimuthAndElevation(double, double, ref Vector3D)`](VRageMath.CreateFromAzimuthAndElevation)||
|[`VolumeInt(double)`](VRageMath.VolumeInt)||
|[`IsInsideInclusive(ref Vector3D, ref Vector3D)`](VRageMath.IsInsideInclusive)||
|static [`SwapYZCoordinates(Vector3D)`](VRageMath.SwapYZCoordinates)||
|[`GetDim(int)`](VRageMath.GetDim)||
|[`SetDim(int, double)`](VRageMath.SetDim)||
|static [`Round(Vector3D)`](VRageMath.Round)||
|static [`Floor(Vector3D)`](VRageMath.Floor)||
|static [`Fract(ref Vector3D, ref Vector3D)`](VRageMath.Fract)||
|static [`Round(Vector3D, int)`](VRageMath.Round)||
|static [`Abs(ref Vector3D, ref Vector3D)`](VRageMath.Abs)||
|static [`ProjectOnPlane(ref Vector3D, ref Vector3D)`](VRageMath.ProjectOnPlane)|Projects given vector on plane specified by it's normal.|
|static [`ProjectOnVector(ref Vector3D, ref Vector3D)`](VRageMath.ProjectOnVector)|Projects vector on another vector resulting in new vector in guided vector's direction with different length.|
|static [`Abs(Vector3D)`](VRageMath.Abs)||
|static [`Sign(Vector3D)`](VRageMath.Sign)||
|static [`SignNonZero(Vector3D)`](VRageMath.SignNonZero)|Returns per component sign, never returns zero. For zero component returns sign 1. Faster than Sign.|
|[`Interpolate3(Vector3D, Vector3D, double)`](VRageMath.Interpolate3)||
|[`IsValid()`](VRageMath.IsValid)||
|[`AssertIsValid()`](VRageMath.AssertIsValid)||
|static [`IsUnit(ref Vector3D)`](VRageMath.IsUnit)||
|static [`ArePerpendicular(ref Vector3D, ref Vector3D)`](VRageMath.ArePerpendicular)||
|static [`IsZero(Vector3D)`](VRageMath.IsZero)||
|static [`IsZero(Vector3D, double)`](VRageMath.IsZero)||
|static [`IsZeroVector(Vector3D)`](VRageMath.IsZeroVector)||
|static [`IsZeroVector(Vector3D, double)`](VRageMath.IsZeroVector)||
|static [`Step(Vector3D)`](VRageMath.Step)||
|[`ToString()`](VRageMath.ToString)|Retrieves a string representation of the current object.|
|static [`TryParse(string, ref Vector3D)`](VRageMath.TryParse)||
|[`ToString(string)`](VRageMath.ToString)||
|[`Equals(Vector3D)`](VRageMath.Equals)|Determines whether the specified Object is equal to the Vector3.|
|[`Equals(Vector3D, double)`](VRageMath.Equals)||
|[`Equals(Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`GetHashCode()`](VRageMath.GetHashCode)||
|[`GetHash()`](VRageMath.GetHash)|Gets the hash code of the vector object.|
|[`Length()`](VRageMath.Length)|Calculates the length of the vector.|
|[`LengthSquared()`](VRageMath.LengthSquared)|Calculates the length of the vector squared.|
|static [`Distance(Vector3D, Vector3D)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`Distance(Vector3D, Vector3)`](VRageMath.Distance)||
|static [`Distance(Vector3, Vector3D)`](VRageMath.Distance)||
|static [`Distance(ref Vector3D, ref Vector3D, ref double)`](VRageMath.Distance)|Calculates the distance between two vectors.|
|static [`DistanceSquared(Vector3D, Vector3D)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`DistanceSquared(ref Vector3D, ref Vector3D, ref double)`](VRageMath.DistanceSquared)|Calculates the distance between two vectors squared.|
|static [`RectangularDistance(Vector3D, Vector3D)`](VRageMath.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|static [`RectangularDistance(ref Vector3D, ref Vector3D)`](VRageMath.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|static [`Dot(Vector3D, Vector3D)`](VRageMath.Dot)|Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|static [`Dot(Vector3D, Vector3)`](VRageMath.Dot)||
|static [`Dot(ref Vector3D, ref Vector3D, ref double)`](VRageMath.Dot)|Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|static [`Dot(ref Vector3D, ref Vector3, ref double)`](VRageMath.Dot)||
|static [`Dot(ref Vector3, ref Vector3D, ref double)`](VRageMath.Dot)||
|[`Dot(Vector3D)`](VRageMath.Dot)||
|[`Dot(Vector3)`](VRageMath.Dot)||
|[`Dot(ref Vector3D)`](VRageMath.Dot)||
|[`Cross(Vector3D)`](VRageMath.Cross)||
|[`Normalize()`](VRageMath.Normalize)|Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`Normalize(Vector3D)`](VRageMath.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`Normalize(ref Vector3D, ref Vector3D)`](VRageMath.Normalize)|Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.|
|static [`Cross(Vector3D, Vector3D)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|static [`Cross(ref Vector3D, ref Vector3D, ref Vector3D)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|static [`Reflect(Vector3D, Vector3D)`](VRageMath.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|static [`Reflect(ref Vector3D, ref Vector3D, ref Vector3D)`](VRageMath.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|static [`Reject(Vector3D, Vector3D)`](VRageMath.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|static [`Reject(ref Vector3D, ref Vector3D, ref Vector3D)`](VRageMath.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|[`Min()`](VRageMath.Min)|Returns the component of the vector that is smallest of all the three components.|
|[`AbsMin()`](VRageMath.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|[`Max()`](VRageMath.Max)|Returns the component of the vector that is largest of all the three components.|
|[`AbsMax()`](VRageMath.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|[`AbsMaxComponent()`](VRageMath.AbsMaxComponent)||
|static [`Min(Vector3D, Vector3D)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`Min(ref Vector3D, ref Vector3D, ref Vector3D)`](VRageMath.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|static [`Max(Vector3D, Vector3D)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`Max(ref Vector3D, ref Vector3D, ref Vector3D)`](VRageMath.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|static [`MinMax(ref Vector3D, ref Vector3D)`](VRageMath.MinMax)|Separates minimal and maximal values of any two input vectors|
|static [`DominantAxisProjection(Vector3D)`](VRageMath.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|static [`DominantAxisProjection(ref Vector3D, ref Vector3D)`](VRageMath.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved into a user-specified variable.|
|static [`Clamp(Vector3D, Vector3D, Vector3D)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`Clamp(ref Vector3D, ref Vector3D, ref Vector3D, ref Vector3D)`](VRageMath.Clamp)|Restricts a value to be within a specified range.|
|static [`ClampToSphere(Vector3D, double)`](VRageMath.ClampToSphere)||
|static [`ClampToSphere(ref Vector3D, double)`](VRageMath.ClampToSphere)||
|static [`Lerp(Vector3D, Vector3D, double)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`Lerp(ref Vector3D, ref Vector3D, double, ref Vector3D)`](VRageMath.Lerp)|Performs a linear interpolation between two vectors.|
|static [`Barycentric(Vector3D, Vector3D, Vector3D, double, double)`](VRageMath.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in Barycentric coordinates relative to a 3D triangle.|
|static [`Barycentric(ref Vector3D, ref Vector3D, ref Vector3D, double, double, ref Vector3D)`](VRageMath.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 3D triangle.|
|static [`Barycentric(Vector3D, Vector3D, Vector3D, Vector3D, ref double, ref double, ref double)`](VRageMath.Barycentric)|Compute barycentric coordinates (u, v, w) for point p with respect to triangle (a, b, c) From : Real-Time Collision Detection, Christer Ericson, CRC Press 3.4 Barycentric Coordinates|
|static [`SmoothStep(Vector3D, Vector3D, double)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`SmoothStep(ref Vector3D, ref Vector3D, double, ref Vector3D)`](VRageMath.SmoothStep)|Interpolates between two values using a cubic equation.|
|static [`CatmullRom(Vector3D, Vector3D, Vector3D, Vector3D, double)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`CatmullRom(ref Vector3D, ref Vector3D, ref Vector3D, ref Vector3D, double, ref Vector3D)`](VRageMath.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|static [`Hermite(Vector3D, Vector3D, Vector3D, Vector3D, double)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`Hermite(ref Vector3D, ref Vector3D, ref Vector3D, ref Vector3D, double, ref Vector3D)`](VRageMath.Hermite)|Performs a Hermite spline interpolation.|
|static [`Transform(Vector3D, MatrixD)`](VRageMath.Transform)|Transforms a 3D vector by the given matrix.|
|static [`Transform(Vector3, MatrixD)`](VRageMath.Transform)||
|static [`Transform(Vector3D, Matrix)`](VRageMath.Transform)|Transforms a 3D vector by the given matrix.|
|static [`Transform(Vector3D, ref MatrixD)`](VRageMath.Transform)||
|static [`Transform(ref Vector3D, ref MatrixD, ref Vector3D)`](VRageMath.Transform)|Transforms a Vector3 by the given Matrix.|
|static [`Transform(ref Vector3, ref MatrixD, ref Vector3D)`](VRageMath.Transform)||
|static [`TransformNoProjection(ref Vector3D, ref MatrixD, ref Vector3D)`](VRageMath.TransformNoProjection)||
|static [`RotateAndScale(ref Vector3D, ref MatrixD, ref Vector3D)`](VRageMath.RotateAndScale)||
|static [`Transform(ref Vector3D, ref MatrixI, ref Vector3D)`](VRageMath.Transform)||
|static [`TransformNormal(Vector3D, Matrix)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|static [`TransformNormal(Vector3, MatrixD)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|static [`TransformNormal(Vector3D, MatrixD)`](VRageMath.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|static [`TransformNormal(ref Vector3D, ref MatrixD, ref Vector3D)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|static [`TransformNormal(ref Vector3, ref MatrixD, ref Vector3D)`](VRageMath.TransformNormal)||
