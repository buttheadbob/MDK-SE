← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### Vector3D Struct

```csharp
public struct Vector3D: IEquatable<Vector3D>
```

Defines a vector with three components. Vector3 with double floating point precision

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<Vector3D>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\\$1static Vector3D Backward](VRageMath.Vector3D.Backward)||
|\\$1static Vector3D Down](VRageMath.Vector3D.Down)||
|\\$1static Vector3D Forward](VRageMath.Vector3D.Forward)||
|\\$1static Vector3D Half](VRageMath.Vector3D.Half)||
|\\$1static Vector3D Left](VRageMath.Vector3D.Left)||
|\\$1static Vector3D MaxValue](VRageMath.Vector3D.MaxValue)||
|\\$1static Vector3D MinValue](VRageMath.Vector3D.MinValue)||
|\\$1static Vector3D NegativeInfinity](VRageMath.Vector3D.NegativeInfinity)||
|\\$1static Vector3D One](VRageMath.Vector3D.One)||
|\\$1static Vector3D PositiveInfinity](VRageMath.Vector3D.PositiveInfinity)||
|\\$1static Vector3D Right](VRageMath.Vector3D.Right)||
|\\$1static Vector3D UnitX](VRageMath.Vector3D.UnitX)||
|\\$1static Vector3D UnitY](VRageMath.Vector3D.UnitY)||
|\\$1static Vector3D UnitZ](VRageMath.Vector3D.UnitZ)||
|\\$1static Vector3D Up](VRageMath.Vector3D.Up)||
|\\$1static Vector3D Zero](VRageMath.Vector3D.Zero)||
|\\$1double X](VRageMath.Vector3D.X)|Gets or sets the x-component of the vector.|
|\\$1double Y](VRageMath.Vector3D.Y)|Gets or sets the y-component of the vector.|
|\\$1double Z](VRageMath.Vector3D.Z)|Gets or sets the z-component of the vector.|

#### Properties

|Member|Description|
|---|---|
|\\$1double Sum { get; }](VRageMath.Vector3D.Sum)||
|\\$1double Volume { get; }](VRageMath.Vector3D.Volume)||

#### Constructors

|Member|Description|
|---|---|
|\\$1Vector3D(double, double, double)](VRageMath.Vector3D..ctor)||
|\\$1Vector3D(double)](VRageMath.Vector3D..ctor)||
|\\$1Vector3D(Vector2, double)](VRageMath.Vector3D..ctor)||
|\\$1Vector3D(Vector2D, double)](VRageMath.Vector3D..ctor)||
|\\$1Vector3D(Vector4)](VRageMath.Vector3D..ctor)||
|\\$1Vector3D(Vector4D)](VRageMath.Vector3D..ctor)||
|\\$1Vector3D(Vector3)](VRageMath.Vector3D..ctor)||
|\\$1Vector3D(ref Vector3I)](VRageMath.Vector3D..ctor)||
|\\$1Vector3D(Vector3I)](VRageMath.Vector3D..ctor)||
|\\$1Vector3D(Vector3D)](VRageMath.Vector3D..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\$1static void Abs(ref Vector3D, out Vector3D)](VRageMath.Vector3D.Abs)||
|\\$1static Vector3D Abs(Vector3D)](VRageMath.Vector3D.Abs)||
|\\$1static Vector3D Add(Vector3D, Vector3D)](VRageMath.Vector3D.Add)|Adds two vectors.|
|\\$1static void Add(ref Vector3D, ref Vector3D, out Vector3D)](VRageMath.Vector3D.Add)|Adds two vectors.|
|\\$1static bool ArePerpendicular(ref Vector3D, ref Vector3D)](VRageMath.Vector3D.ArePerpendicular)||
|\\$1static Vector3D Barycentric(Vector3D, Vector3D, Vector3D, double, double)](VRageMath.Vector3D.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in Barycentric coordinates relative to a 3D triangle.|
|\\$1static void Barycentric(ref Vector3D, ref Vector3D, ref Vector3D, double, double, out Vector3D)](VRageMath.Vector3D.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 3D triangle.|
|\\$1static void Barycentric(Vector3D, Vector3D, Vector3D, Vector3D, out double, out double, out double)](VRageMath.Vector3D.Barycentric)|Compute barycentric coordinates (u, v, w) for point p with respect to triangle (a, b, c) From : Real-Time Collision Detection, Christer Ericson, CRC Press 3.4 Barycentric Coordinates|
|\\$1static Vector3D CalculatePerpendicularVector(Vector3D)](VRageMath.Vector3D.CalculatePerpendicularVector)||
|\\$1static Vector3D CatmullRom(Vector3D, Vector3D, Vector3D, Vector3D, double)](VRageMath.Vector3D.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|\\$1static void CatmullRom(ref Vector3D, ref Vector3D, ref Vector3D, ref Vector3D, double, out Vector3D)](VRageMath.Vector3D.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|\\$1static Vector3D Clamp(Vector3D, Vector3D, Vector3D)](VRageMath.Vector3D.Clamp)|Restricts a value to be within a specified range.|
|\\$1static void Clamp(ref Vector3D, ref Vector3D, ref Vector3D, out Vector3D)](VRageMath.Vector3D.Clamp)|Restricts a value to be within a specified range.|
|\\$1static Vector3D ClampToSphere(Vector3D, double)](VRageMath.Vector3D.ClampToSphere)||
|\\$1static void ClampToSphere(ref Vector3D, double)](VRageMath.Vector3D.ClampToSphere)||
|\\$1static void CreateFromAzimuthAndElevation(double, double, out Vector3D)](VRageMath.Vector3D.CreateFromAzimuthAndElevation)||
|\\$1static Vector3D Cross(Vector3D, Vector3D)](VRageMath.Vector3D.Cross)|Calculates the cross product of two vectors.|
|\\$1static void Cross(ref Vector3D, ref Vector3D, out Vector3D)](VRageMath.Vector3D.Cross)|Calculates the cross product of two vectors.|
|\\$1static double Distance(Vector3D, Vector3D)](VRageMath.Vector3D.Distance)|Calculates the distance between two vectors.|
|\\$1static double Distance(Vector3D, Vector3)](VRageMath.Vector3D.Distance)||
|\\$1static double Distance(Vector3, Vector3D)](VRageMath.Vector3D.Distance)||
|\\$1static void Distance(ref Vector3D, ref Vector3D, out double)](VRageMath.Vector3D.Distance)|Calculates the distance between two vectors.|
|\\$1static double DistanceSquared(Vector3D, Vector3D)](VRageMath.Vector3D.DistanceSquared)|Calculates the distance between two vectors squared.|
|\\$1static void DistanceSquared(ref Vector3D, ref Vector3D, out double)](VRageMath.Vector3D.DistanceSquared)|Calculates the distance between two vectors squared.|
|\\$1static Vector3D Divide(Vector3D, Vector3D)](VRageMath.Vector3D.Divide)|Divides the components of a vector by the components of another vector.|
|\\$1static void Divide(ref Vector3D, ref Vector3D, out Vector3D)](VRageMath.Vector3D.Divide)|Divides the components of a vector by the components of another vector.|
|\\$1static Vector3D Divide(Vector3D, double)](VRageMath.Vector3D.Divide)|Divides a vector by a scalar value.|
|\\$1static void Divide(ref Vector3D, double, out Vector3D)](VRageMath.Vector3D.Divide)|Divides a vector by a scalar value.|
|\\$1static Vector3D DominantAxisProjection(Vector3D)](VRageMath.Vector3D.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|\\$1static void DominantAxisProjection(ref Vector3D, out Vector3D)](VRageMath.Vector3D.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved into a user-specified variable.|
|\\$1static double Dot(Vector3D, Vector3D)](VRageMath.Vector3D.Dot)|Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|\\$1static double Dot(Vector3D, Vector3)](VRageMath.Vector3D.Dot)||
|\\$1static void Dot(ref Vector3D, ref Vector3D, out double)](VRageMath.Vector3D.Dot)|Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|\\$1static void Dot(ref Vector3D, ref Vector3, out double)](VRageMath.Vector3D.Dot)||
|\\$1static void Dot(ref Vector3, ref Vector3D, out double)](VRageMath.Vector3D.Dot)||
|\\$1static Vector3I Floor(Vector3D)](VRageMath.Vector3D.Floor)||
|\\$1static void Fract(ref Vector3D, out Vector3D)](VRageMath.Vector3D.Fract)||
|\\$1static void GetAzimuthAndElevation(Vector3D, out double, out double)](VRageMath.Vector3D.GetAzimuthAndElevation)||
|\\$1static Vector3D Hermite(Vector3D, Vector3D, Vector3D, Vector3D, double)](VRageMath.Vector3D.Hermite)|Performs a Hermite spline interpolation.|
|\\$1static void Hermite(ref Vector3D, ref Vector3D, ref Vector3D, ref Vector3D, double, out Vector3D)](VRageMath.Vector3D.Hermite)|Performs a Hermite spline interpolation.|
|\\$1static bool IsUnit(ref Vector3D)](VRageMath.Vector3D.IsUnit)||
|\\$1static bool IsZero(Vector3D)](VRageMath.Vector3D.IsZero)||
|\\$1static bool IsZero(Vector3D, double)](VRageMath.Vector3D.IsZero)||
|\\$1static Vector3D IsZeroVector(Vector3D)](VRageMath.Vector3D.IsZeroVector)||
|\\$1static Vector3D IsZeroVector(Vector3D, double)](VRageMath.Vector3D.IsZeroVector)||
|\\$1static Vector3D Lerp(Vector3D, Vector3D, double)](VRageMath.Vector3D.Lerp)|Performs a linear interpolation between two vectors.|
|\\$1static void Lerp(ref Vector3D, ref Vector3D, double, out Vector3D)](VRageMath.Vector3D.Lerp)|Performs a linear interpolation between two vectors.|
|\\$1static Vector3D Max(Vector3D, Vector3D)](VRageMath.Vector3D.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|\\$1static void Max(ref Vector3D, ref Vector3D, out Vector3D)](VRageMath.Vector3D.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|\\$1static Vector3D Min(Vector3D, Vector3D)](VRageMath.Vector3D.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|\\$1static void Min(ref Vector3D, ref Vector3D, out Vector3D)](VRageMath.Vector3D.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|\\$1static void MinMax(ref Vector3D, ref Vector3D)](VRageMath.Vector3D.MinMax)|Separates minimal and maximal values of any two input vectors|
|\\$1static Vector3D Multiply(Vector3D, Vector3D)](VRageMath.Vector3D.Multiply)|Multiplies the components of two vectors by each other.|
|\\$1static void Multiply(ref Vector3D, ref Vector3D, out Vector3D)](VRageMath.Vector3D.Multiply)|Multiplies the components of two vectors by each other.|
|\\$1static Vector3D Multiply(Vector3D, double)](VRageMath.Vector3D.Multiply)|Multiplies a vector by a scalar value.|
|\\$1static void Multiply(ref Vector3D, double, out Vector3D)](VRageMath.Vector3D.Multiply)|Multiplies a vector by a scalar value.|
|\\$1static Vector3D Negate(Vector3D)](VRageMath.Vector3D.Negate)|Returns a vector pointing in the opposite direction.|
|\\$1static void Negate(ref Vector3D, out Vector3D)](VRageMath.Vector3D.Negate)|Returns a vector pointing in the opposite direction.|
|\\$1static Vector3D Normalize(Vector3D)](VRageMath.Vector3D.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|\\$1static void Normalize(ref Vector3D, out Vector3D)](VRageMath.Vector3D.Normalize)|Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.|
|\\$1static Vector3D ProjectOnPlane(ref Vector3D, ref Vector3D)](VRageMath.Vector3D.ProjectOnPlane)|Projects given vector on plane specified by it's normal.|
|\\$1static Vector3D ProjectOnVector(ref Vector3D, ref Vector3D)](VRageMath.Vector3D.ProjectOnVector)|Projects vector on another vector resulting in new vector in guided vector's direction with different length.|
|\\$1static double RectangularDistance(Vector3D, Vector3D)](VRageMath.Vector3D.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|\\$1static double RectangularDistance(ref Vector3D, ref Vector3D)](VRageMath.Vector3D.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|\\$1static Vector3D Reflect(Vector3D, Vector3D)](VRageMath.Vector3D.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|\\$1static void Reflect(ref Vector3D, ref Vector3D, out Vector3D)](VRageMath.Vector3D.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|\\$1static Vector3D Reject(Vector3D, Vector3D)](VRageMath.Vector3D.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|\\$1static void Reject(ref Vector3D, ref Vector3D, out Vector3D)](VRageMath.Vector3D.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|\\$1static void Rotate(ref Vector3D, ref MatrixD, out Vector3D)](VRageMath.Vector3D.Rotate)||
|\\$1static Vector3D Rotate(Vector3D, MatrixD)](VRageMath.Vector3D.Rotate)||
|\\$1static void RotateAndScale(ref Vector3D, ref MatrixD, out Vector3D)](VRageMath.Vector3D.RotateAndScale)||
|\\$1static Vector3I Round(Vector3D)](VRageMath.Vector3D.Round)||
|\\$1static Vector3D Round(Vector3D, int)](VRageMath.Vector3D.Round)||
|\\$1static Vector3D Sign(Vector3D)](VRageMath.Vector3D.Sign)||
|\\$1static Vector3D SignNonZero(Vector3D)](VRageMath.Vector3D.SignNonZero)|Returns per component sign, never returns zero. For zero component returns sign 1. Faster than Sign.|
|\\$1static Vector3D SmoothStep(Vector3D, Vector3D, double)](VRageMath.Vector3D.SmoothStep)|Interpolates between two values using a cubic equation.|
|\\$1static void SmoothStep(ref Vector3D, ref Vector3D, double, out Vector3D)](VRageMath.Vector3D.SmoothStep)|Interpolates between two values using a cubic equation.|
|\\$1static Vector3D Step(Vector3D)](VRageMath.Vector3D.Step)||
|\\$1static Vector3D Subtract(Vector3D, Vector3D)](VRageMath.Vector3D.Subtract)|Subtracts a vector from a vector.|
|\\$1static void Subtract(ref Vector3D, ref Vector3D, out Vector3D)](VRageMath.Vector3D.Subtract)|Subtracts a vector from a vector.|
|\\$1static Vector3D SwapYZCoordinates(Vector3D)](VRageMath.Vector3D.SwapYZCoordinates)||
|\\$1static Vector3D Transform(Vector3D, Quaternion)](VRageMath.Vector3D.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|\\$1static void Transform(ref Vector3D, ref Quaternion, out Vector3D)](VRageMath.Vector3D.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|\\$1static void Transform(Vector3D\\$1], ref MatrixD, Vector3D\\$1])](VRageMath.Vector3D.Transform)|Transforms a source array of Vector3s by a specified Matrix and writes the results to an existing destination array.|
|\\$1static void Transform(Vector3D\\$1], ref MatrixD, *Vector3D)](VRageMath.Vector3D.Transform)||
|\\$1static void Transform(Vector3D\\$1], int, ref Matrix, Vector3D\\$1], int, int)](VRageMath.Vector3D.Transform)|Applies a specified transform Matrix to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|\\$1static void Transform(Vector3D\\$1], ref Quaternion, Vector3D\\$1])](VRageMath.Vector3D.Transform)|Transforms a source array of Vector3s by a specified Quaternion rotation and writes the results to an existing destination array.|
|\\$1static void Transform(Vector3D\\$1], int, ref Quaternion, Vector3D\\$1], int, int)](VRageMath.Vector3D.Transform)|Applies a specified Quaternion rotation to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|\\$1static Vector3D Transform(Vector3D, MatrixD)](VRageMath.Vector3D.Transform)|Transforms a 3D vector by the given matrix.|
|\\$1static Vector3D Transform(Vector3, MatrixD)](VRageMath.Vector3D.Transform)||
|\\$1static Vector3D Transform(Vector3D, Matrix)](VRageMath.Vector3D.Transform)|Transforms a 3D vector by the given matrix.|
|\\$1static Vector3D Transform(Vector3D, ref MatrixD)](VRageMath.Vector3D.Transform)||
|\\$1static void Transform(ref Vector3D, ref MatrixD, out Vector3D)](VRageMath.Vector3D.Transform)|Transforms a Vector3 by the given Matrix.|
|\\$1static void Transform(ref Vector3, ref MatrixD, out Vector3D)](VRageMath.Vector3D.Transform)||
|\\$1static void Transform(ref Vector3D, ref MatrixI, out Vector3D)](VRageMath.Vector3D.Transform)||
|\\$1static void TransformNoProjection(ref Vector3D, ref MatrixD, out Vector3D)](VRageMath.Vector3D.TransformNoProjection)||
|\\$1static void TransformNormal(ref Vector3D, ref MatrixD, out Vector3D)](VRageMath.Vector3D.TransformNormal)|Transforms a vector normal by a matrix.|
|\\$1static void TransformNormal(ref Vector3, ref MatrixD, out Vector3D)](VRageMath.Vector3D.TransformNormal)||
|\\$1static void TransformNormal(ref Vector3D, ref MatrixI, out Vector3D)](VRageMath.Vector3D.TransformNormal)||
|\\$1static Vector3D TransformNormal(Vector3D, MyBlockOrientation)](VRageMath.Vector3D.TransformNormal)||
|\\$1static void TransformNormal(ref Vector3D, MyBlockOrientation, out Vector3D)](VRageMath.Vector3D.TransformNormal)||
|\\$1static Vector3D TransformNormal(Vector3D, ref MatrixD)](VRageMath.Vector3D.TransformNormal)||
|\\$1static void TransformNormal(Vector3D\\$1], ref Matrix, Vector3D\\$1])](VRageMath.Vector3D.TransformNormal)|Transforms an array of 3D vector normals by a specified Matrix.|
|\\$1static void TransformNormal(Vector3D\\$1], ref Matrix, *Vector3D)](VRageMath.Vector3D.TransformNormal)||
|\\$1static void TransformNormal(Vector3D\\$1], int, ref Matrix, Vector3D\\$1], int, int)](VRageMath.Vector3D.TransformNormal)|Transforms a specified range in an array of 3D vector normals by a specified Matrix and writes the results to a specified range in a destination array.|
|\\$1static Vector3D TransformNormal(Vector3D, Matrix)](VRageMath.Vector3D.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|\\$1static Vector3D TransformNormal(Vector3, MatrixD)](VRageMath.Vector3D.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|\\$1static Vector3D TransformNormal(Vector3D, MatrixD)](VRageMath.Vector3D.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|\\$1static bool TryParse(string, out Vector3D)](VRageMath.Vector3D.TryParse)||
|\\$1double AbsMax()](VRageMath.Vector3D.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|\\$1int AbsMaxComponent()](VRageMath.Vector3D.AbsMaxComponent)||
|\\$1double AbsMin()](VRageMath.Vector3D.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|\\$1void AssertIsValid()](VRageMath.Vector3D.AssertIsValid)||
|\\$1void CalculatePerpendicularVector(out Vector3D)](VRageMath.Vector3D.CalculatePerpendicularVector)||
|\\$1Vector3D Cross(Vector3D)](VRageMath.Vector3D.Cross)||
|\\$1double Dot(Vector3D)](VRageMath.Vector3D.Dot)||
|\\$1double Dot(Vector3)](VRageMath.Vector3D.Dot)||
|\\$1double Dot(ref Vector3D)](VRageMath.Vector3D.Dot)||
|\\$1bool Equals(Vector3D)](VRageMath.Vector3D.Equals)|Determines whether the specified Object is equal to the Vector3.|
|\\$1bool Equals(Vector3D, double)](VRageMath.Vector3D.Equals)||
|\\$1bool Equals(object)](VRageMath.Vector3D.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|\\$1double GetDim(int)](VRageMath.Vector3D.GetDim)||
|\\$1long GetHash()](VRageMath.Vector3D.GetHash)|Gets the hash code of the vector object.|
|\\$1int GetHashCode()](VRageMath.Vector3D.GetHashCode)||
|\\$1void Interpolate3(Vector3D, Vector3D, double)](VRageMath.Vector3D.Interpolate3)||
|\\$1bool IsInsideInclusive(ref Vector3D, ref Vector3D)](VRageMath.Vector3D.IsInsideInclusive)||
|\\$1bool IsValid()](VRageMath.Vector3D.IsValid)||
|\\$1bool IsZero()](VRageMath.Vector3D.IsZero)||
|\\$1double Length()](VRageMath.Vector3D.Length)|Calculates the length of the vector.|
|\\$1double LengthSquared()](VRageMath.Vector3D.LengthSquared)|Calculates the length of the vector squared.|
|\\$1double Max()](VRageMath.Vector3D.Max)|Returns the component of the vector that is largest of all the three components.|
|\\$1double Min()](VRageMath.Vector3D.Min)|Returns the component of the vector that is smallest of all the three components.|
|\\$1double Normalize()](VRageMath.Vector3D.Normalize)|Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|\\$1void SetDim(int, double)](VRageMath.Vector3D.SetDim)||
|\\$1string ToString()](VRageMath.Vector3D.ToString)|Retrieves a string representation of the current object.|
|\\$1string ToString(string)](VRageMath.Vector3D.ToString)||
|\\$1long VolumeInt(double)](VRageMath.Vector3D.VolumeInt)||

