← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### Vector3D Struct

```csharp
public struct Vector3D: IEquatable\<Vector3D\>
```

Defines a vector with three components. Vector3 with double floating point precision

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable\<Vector3D\>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[static Vector3D Backward](VRageMath.Vector3D.Backward)||
|[static Vector3D Down](VRageMath.Vector3D.Down)||
|[static Vector3D Forward](VRageMath.Vector3D.Forward)||
|[static Vector3D Half](VRageMath.Vector3D.Half)||
|[static Vector3D Left](VRageMath.Vector3D.Left)||
|[static Vector3D MaxValue](VRageMath.Vector3D.MaxValue)||
|[static Vector3D MinValue](VRageMath.Vector3D.MinValue)||
|[static Vector3D NegativeInfinity](VRageMath.Vector3D.NegativeInfinity)||
|[static Vector3D One](VRageMath.Vector3D.One)||
|[static Vector3D PositiveInfinity](VRageMath.Vector3D.PositiveInfinity)||
|[static Vector3D Right](VRageMath.Vector3D.Right)||
|[static Vector3D UnitX](VRageMath.Vector3D.UnitX)||
|[static Vector3D UnitY](VRageMath.Vector3D.UnitY)||
|[static Vector3D UnitZ](VRageMath.Vector3D.UnitZ)||
|[static Vector3D Up](VRageMath.Vector3D.Up)||
|[static Vector3D Zero](VRageMath.Vector3D.Zero)||
|[double X](VRageMath.Vector3D.X)|Gets or sets the x-component of the vector.|
|[double Y](VRageMath.Vector3D.Y)|Gets or sets the y-component of the vector.|
|[double Z](VRageMath.Vector3D.Z)|Gets or sets the z-component of the vector.|

#### Properties

|Member|Description|
|---|---|
|[double Sum { get; }](VRageMath.Vector3D.Sum)||
|[double Volume { get; }](VRageMath.Vector3D.Volume)||

#### Constructors

|Member|Description|
|---|---|
|[Vector3D(double, double, double)](VRageMath.Vector3D..ctor)||
|[Vector3D(double)](VRageMath.Vector3D..ctor)||
|[Vector3D(Vector2, double)](VRageMath.Vector3D..ctor)||
|[Vector3D(Vector2D, double)](VRageMath.Vector3D..ctor)||
|[Vector3D(Vector4)](VRageMath.Vector3D..ctor)||
|[Vector3D(Vector4D)](VRageMath.Vector3D..ctor)||
|[Vector3D(Vector3)](VRageMath.Vector3D..ctor)||
|[Vector3D(ref Vector3I)](VRageMath.Vector3D..ctor)||
|[Vector3D(Vector3I)](VRageMath.Vector3D..ctor)||
|[Vector3D(Vector3D)](VRageMath.Vector3D..ctor)||

#### Methods

|Member|Description|
|---|---|
|[static void Abs(ref Vector3D, out Vector3D)](VRageMath.Vector3D.Abs)||
|[static Vector3D Abs(Vector3D)](VRageMath.Vector3D.Abs)||
|[static Vector3D Add(Vector3D, Vector3D)](VRageMath.Vector3D.Add)|Adds two vectors.|
|[static void Add(ref Vector3D, ref Vector3D, out Vector3D)](VRageMath.Vector3D.Add)|Adds two vectors.|
|[static bool ArePerpendicular(ref Vector3D, ref Vector3D)](VRageMath.Vector3D.ArePerpendicular)||
|[static Vector3D Barycentric(Vector3D, Vector3D, Vector3D, double, double)](VRageMath.Vector3D.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in Barycentric coordinates relative to a 3D triangle.|
|[static void Barycentric(ref Vector3D, ref Vector3D, ref Vector3D, double, double, out Vector3D)](VRageMath.Vector3D.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 3D triangle.|
|[static void Barycentric(Vector3D, Vector3D, Vector3D, Vector3D, out double, out double, out double)](VRageMath.Vector3D.Barycentric)|Compute barycentric coordinates (u, v, w) for point p with respect to triangle (a, b, c) From : Real-Time Collision Detection, Christer Ericson, CRC Press 3.4 Barycentric Coordinates|
|[static Vector3D CalculatePerpendicularVector(Vector3D)](VRageMath.Vector3D.CalculatePerpendicularVector)||
|[static Vector3D CatmullRom(Vector3D, Vector3D, Vector3D, Vector3D, double)](VRageMath.Vector3D.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|[static void CatmullRom(ref Vector3D, ref Vector3D, ref Vector3D, ref Vector3D, double, out Vector3D)](VRageMath.Vector3D.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|[static Vector3D Clamp(Vector3D, Vector3D, Vector3D)](VRageMath.Vector3D.Clamp)|Restricts a value to be within a specified range.|
|[static void Clamp(ref Vector3D, ref Vector3D, ref Vector3D, out Vector3D)](VRageMath.Vector3D.Clamp)|Restricts a value to be within a specified range.|
|[static Vector3D ClampToSphere(Vector3D, double)](VRageMath.Vector3D.ClampToSphere)||
|[static void ClampToSphere(ref Vector3D, double)](VRageMath.Vector3D.ClampToSphere)||
|[static void CreateFromAzimuthAndElevation(double, double, out Vector3D)](VRageMath.Vector3D.CreateFromAzimuthAndElevation)||
|[static Vector3D Cross(Vector3D, Vector3D)](VRageMath.Vector3D.Cross)|Calculates the cross product of two vectors.|
|[static void Cross(ref Vector3D, ref Vector3D, out Vector3D)](VRageMath.Vector3D.Cross)|Calculates the cross product of two vectors.|
|[static double Distance(Vector3D, Vector3D)](VRageMath.Vector3D.Distance)|Calculates the distance between two vectors.|
|[static double Distance(Vector3D, Vector3)](VRageMath.Vector3D.Distance)||
|[static double Distance(Vector3, Vector3D)](VRageMath.Vector3D.Distance)||
|[static void Distance(ref Vector3D, ref Vector3D, out double)](VRageMath.Vector3D.Distance)|Calculates the distance between two vectors.|
|[static double DistanceSquared(Vector3D, Vector3D)](VRageMath.Vector3D.DistanceSquared)|Calculates the distance between two vectors squared.|
|[static void DistanceSquared(ref Vector3D, ref Vector3D, out double)](VRageMath.Vector3D.DistanceSquared)|Calculates the distance between two vectors squared.|
|[static Vector3D Divide(Vector3D, Vector3D)](VRageMath.Vector3D.Divide)|Divides the components of a vector by the components of another vector.|
|[static void Divide(ref Vector3D, ref Vector3D, out Vector3D)](VRageMath.Vector3D.Divide)|Divides the components of a vector by the components of another vector.|
|[static Vector3D Divide(Vector3D, double)](VRageMath.Vector3D.Divide)|Divides a vector by a scalar value.|
|[static void Divide(ref Vector3D, double, out Vector3D)](VRageMath.Vector3D.Divide)|Divides a vector by a scalar value.|
|[static Vector3D DominantAxisProjection(Vector3D)](VRageMath.Vector3D.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|[static void DominantAxisProjection(ref Vector3D, out Vector3D)](VRageMath.Vector3D.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved into a user-specified variable.|
|[static double Dot(Vector3D, Vector3D)](VRageMath.Vector3D.Dot)|Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[static double Dot(Vector3D, Vector3)](VRageMath.Vector3D.Dot)||
|[static void Dot(ref Vector3D, ref Vector3D, out double)](VRageMath.Vector3D.Dot)|Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[static void Dot(ref Vector3D, ref Vector3, out double)](VRageMath.Vector3D.Dot)||
|[static void Dot(ref Vector3, ref Vector3D, out double)](VRageMath.Vector3D.Dot)||
|[static Vector3I Floor(Vector3D)](VRageMath.Vector3D.Floor)||
|[static void Fract(ref Vector3D, out Vector3D)](VRageMath.Vector3D.Fract)||
|[static void GetAzimuthAndElevation(Vector3D, out double, out double)](VRageMath.Vector3D.GetAzimuthAndElevation)||
|[static Vector3D Hermite(Vector3D, Vector3D, Vector3D, Vector3D, double)](VRageMath.Vector3D.Hermite)|Performs a Hermite spline interpolation.|
|[static void Hermite(ref Vector3D, ref Vector3D, ref Vector3D, ref Vector3D, double, out Vector3D)](VRageMath.Vector3D.Hermite)|Performs a Hermite spline interpolation.|
|[static bool IsUnit(ref Vector3D)](VRageMath.Vector3D.IsUnit)||
|[static bool IsZero(Vector3D)](VRageMath.Vector3D.IsZero)||
|[static bool IsZero(Vector3D, double)](VRageMath.Vector3D.IsZero)||
|[static Vector3D IsZeroVector(Vector3D)](VRageMath.Vector3D.IsZeroVector)||
|[static Vector3D IsZeroVector(Vector3D, double)](VRageMath.Vector3D.IsZeroVector)||
|[static Vector3D Lerp(Vector3D, Vector3D, double)](VRageMath.Vector3D.Lerp)|Performs a linear interpolation between two vectors.|
|[static void Lerp(ref Vector3D, ref Vector3D, double, out Vector3D)](VRageMath.Vector3D.Lerp)|Performs a linear interpolation between two vectors.|
|[static Vector3D Max(Vector3D, Vector3D)](VRageMath.Vector3D.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|[static void Max(ref Vector3D, ref Vector3D, out Vector3D)](VRageMath.Vector3D.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|[static Vector3D Min(Vector3D, Vector3D)](VRageMath.Vector3D.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|[static void Min(ref Vector3D, ref Vector3D, out Vector3D)](VRageMath.Vector3D.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|[static void MinMax(ref Vector3D, ref Vector3D)](VRageMath.Vector3D.MinMax)|Separates minimal and maximal values of any two input vectors|
|[static Vector3D Multiply(Vector3D, Vector3D)](VRageMath.Vector3D.Multiply)|Multiplies the components of two vectors by each other.|
|[static void Multiply(ref Vector3D, ref Vector3D, out Vector3D)](VRageMath.Vector3D.Multiply)|Multiplies the components of two vectors by each other.|
|[static Vector3D Multiply(Vector3D, double)](VRageMath.Vector3D.Multiply)|Multiplies a vector by a scalar value.|
|[static void Multiply(ref Vector3D, double, out Vector3D)](VRageMath.Vector3D.Multiply)|Multiplies a vector by a scalar value.|
|[static Vector3D Negate(Vector3D)](VRageMath.Vector3D.Negate)|Returns a vector pointing in the opposite direction.|
|[static void Negate(ref Vector3D, out Vector3D)](VRageMath.Vector3D.Negate)|Returns a vector pointing in the opposite direction.|
|[static Vector3D Normalize(Vector3D)](VRageMath.Vector3D.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[static void Normalize(ref Vector3D, out Vector3D)](VRageMath.Vector3D.Normalize)|Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[static Vector3D ProjectOnPlane(ref Vector3D, ref Vector3D)](VRageMath.Vector3D.ProjectOnPlane)|Projects given vector on plane specified by it's normal.|
|[static Vector3D ProjectOnVector(ref Vector3D, ref Vector3D)](VRageMath.Vector3D.ProjectOnVector)|Projects vector on another vector resulting in new vector in guided vector's direction with different length.|
|[static double RectangularDistance(Vector3D, Vector3D)](VRageMath.Vector3D.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|[static double RectangularDistance(ref Vector3D, ref Vector3D)](VRageMath.Vector3D.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|[static Vector3D Reflect(Vector3D, Vector3D)](VRageMath.Vector3D.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|[static void Reflect(ref Vector3D, ref Vector3D, out Vector3D)](VRageMath.Vector3D.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|[static Vector3D Reject(Vector3D, Vector3D)](VRageMath.Vector3D.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|[static void Reject(ref Vector3D, ref Vector3D, out Vector3D)](VRageMath.Vector3D.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|[static void Rotate(ref Vector3D, ref MatrixD, out Vector3D)](VRageMath.Vector3D.Rotate)||
|[static Vector3D Rotate(Vector3D, MatrixD)](VRageMath.Vector3D.Rotate)||
|[static void RotateAndScale(ref Vector3D, ref MatrixD, out Vector3D)](VRageMath.Vector3D.RotateAndScale)||
|[static Vector3I Round(Vector3D)](VRageMath.Vector3D.Round)||
|[static Vector3D Round(Vector3D, int)](VRageMath.Vector3D.Round)||
|[static Vector3D Sign(Vector3D)](VRageMath.Vector3D.Sign)||
|[static Vector3D SignNonZero(Vector3D)](VRageMath.Vector3D.SignNonZero)|Returns per component sign, never returns zero. For zero component returns sign 1. Faster than Sign.|
|[static Vector3D SmoothStep(Vector3D, Vector3D, double)](VRageMath.Vector3D.SmoothStep)|Interpolates between two values using a cubic equation.|
|[static void SmoothStep(ref Vector3D, ref Vector3D, double, out Vector3D)](VRageMath.Vector3D.SmoothStep)|Interpolates between two values using a cubic equation.|
|[static Vector3D Step(Vector3D)](VRageMath.Vector3D.Step)||
|[static Vector3D Subtract(Vector3D, Vector3D)](VRageMath.Vector3D.Subtract)|Subtracts a vector from a vector.|
|[static void Subtract(ref Vector3D, ref Vector3D, out Vector3D)](VRageMath.Vector3D.Subtract)|Subtracts a vector from a vector.|
|[static Vector3D SwapYZCoordinates(Vector3D)](VRageMath.Vector3D.SwapYZCoordinates)||
|[static Vector3D Transform(Vector3D, Quaternion)](VRageMath.Vector3D.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|[static void Transform(ref Vector3D, ref Quaternion, out Vector3D)](VRageMath.Vector3D.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|[static void Transform(Vector3D[], ref MatrixD, Vector3D[])](VRageMath.Vector3D.Transform)|Transforms a source array of Vector3s by a specified Matrix and writes the results to an existing destination array.|
|[static void Transform(Vector3D[], ref MatrixD, *Vector3D)](VRageMath.Vector3D.Transform)||
|[static void Transform(Vector3D[], int, ref Matrix, Vector3D[], int, int)](VRageMath.Vector3D.Transform)|Applies a specified transform Matrix to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|[static void Transform(Vector3D[], ref Quaternion, Vector3D[])](VRageMath.Vector3D.Transform)|Transforms a source array of Vector3s by a specified Quaternion rotation and writes the results to an existing destination array.|
|[static void Transform(Vector3D[], int, ref Quaternion, Vector3D[], int, int)](VRageMath.Vector3D.Transform)|Applies a specified Quaternion rotation to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|[static Vector3D Transform(Vector3D, MatrixD)](VRageMath.Vector3D.Transform)|Transforms a 3D vector by the given matrix.|
|[static Vector3D Transform(Vector3, MatrixD)](VRageMath.Vector3D.Transform)||
|[static Vector3D Transform(Vector3D, Matrix)](VRageMath.Vector3D.Transform)|Transforms a 3D vector by the given matrix.|
|[static Vector3D Transform(Vector3D, ref MatrixD)](VRageMath.Vector3D.Transform)||
|[static void Transform(ref Vector3D, ref MatrixD, out Vector3D)](VRageMath.Vector3D.Transform)|Transforms a Vector3 by the given Matrix.|
|[static void Transform(ref Vector3, ref MatrixD, out Vector3D)](VRageMath.Vector3D.Transform)||
|[static void Transform(ref Vector3D, ref MatrixI, out Vector3D)](VRageMath.Vector3D.Transform)||
|[static void TransformNoProjection(ref Vector3D, ref MatrixD, out Vector3D)](VRageMath.Vector3D.TransformNoProjection)||
|[static void TransformNormal(ref Vector3D, ref MatrixD, out Vector3D)](VRageMath.Vector3D.TransformNormal)|Transforms a vector normal by a matrix.|
|[static void TransformNormal(ref Vector3, ref MatrixD, out Vector3D)](VRageMath.Vector3D.TransformNormal)||
|[static void TransformNormal(ref Vector3D, ref MatrixI, out Vector3D)](VRageMath.Vector3D.TransformNormal)||
|[static Vector3D TransformNormal(Vector3D, MyBlockOrientation)](VRageMath.Vector3D.TransformNormal)||
|[static void TransformNormal(ref Vector3D, MyBlockOrientation, out Vector3D)](VRageMath.Vector3D.TransformNormal)||
|[static Vector3D TransformNormal(Vector3D, ref MatrixD)](VRageMath.Vector3D.TransformNormal)||
|[static void TransformNormal(Vector3D[], ref Matrix, Vector3D[])](VRageMath.Vector3D.TransformNormal)|Transforms an array of 3D vector normals by a specified Matrix.|
|[static void TransformNormal(Vector3D[], ref Matrix, *Vector3D)](VRageMath.Vector3D.TransformNormal)||
|[static void TransformNormal(Vector3D[], int, ref Matrix, Vector3D[], int, int)](VRageMath.Vector3D.TransformNormal)|Transforms a specified range in an array of 3D vector normals by a specified Matrix and writes the results to a specified range in a destination array.|
|[static Vector3D TransformNormal(Vector3D, Matrix)](VRageMath.Vector3D.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|[static Vector3D TransformNormal(Vector3, MatrixD)](VRageMath.Vector3D.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|[static Vector3D TransformNormal(Vector3D, MatrixD)](VRageMath.Vector3D.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|[static bool TryParse(string, out Vector3D)](VRageMath.Vector3D.TryParse)||
|[double AbsMax()](VRageMath.Vector3D.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|[int AbsMaxComponent()](VRageMath.Vector3D.AbsMaxComponent)||
|[double AbsMin()](VRageMath.Vector3D.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|[void AssertIsValid()](VRageMath.Vector3D.AssertIsValid)||
|[void CalculatePerpendicularVector(out Vector3D)](VRageMath.Vector3D.CalculatePerpendicularVector)||
|[Vector3D Cross(Vector3D)](VRageMath.Vector3D.Cross)||
|[double Dot(Vector3D)](VRageMath.Vector3D.Dot)||
|[double Dot(Vector3)](VRageMath.Vector3D.Dot)||
|[double Dot(ref Vector3D)](VRageMath.Vector3D.Dot)||
|[bool Equals(Vector3D)](VRageMath.Vector3D.Equals)|Determines whether the specified Object is equal to the Vector3.|
|[bool Equals(Vector3D, double)](VRageMath.Vector3D.Equals)||
|[bool Equals(object)](VRageMath.Vector3D.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[double GetDim(int)](VRageMath.Vector3D.GetDim)||
|[long GetHash()](VRageMath.Vector3D.GetHash)|Gets the hash code of the vector object.|
|[int GetHashCode()](VRageMath.Vector3D.GetHashCode)||
|[void Interpolate3(Vector3D, Vector3D, double)](VRageMath.Vector3D.Interpolate3)||
|[bool IsInsideInclusive(ref Vector3D, ref Vector3D)](VRageMath.Vector3D.IsInsideInclusive)||
|[bool IsValid()](VRageMath.Vector3D.IsValid)||
|[bool IsZero()](VRageMath.Vector3D.IsZero)||
|[double Length()](VRageMath.Vector3D.Length)|Calculates the length of the vector.|
|[double LengthSquared()](VRageMath.Vector3D.LengthSquared)|Calculates the length of the vector squared.|
|[double Max()](VRageMath.Vector3D.Max)|Returns the component of the vector that is largest of all the three components.|
|[double Min()](VRageMath.Vector3D.Min)|Returns the component of the vector that is smallest of all the three components.|
|[double Normalize()](VRageMath.Vector3D.Normalize)|Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[void SetDim(int, double)](VRageMath.Vector3D.SetDim)||
|[string ToString()](VRageMath.Vector3D.ToString)|Retrieves a string representation of the current object.|
|[string ToString(string)](VRageMath.Vector3D.ToString)||
|[long VolumeInt(double)](VRageMath.Vector3D.VolumeInt)||

