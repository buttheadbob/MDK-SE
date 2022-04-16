← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### Vector3 Struct

```csharp
public struct Vector3: IEquatable<Vector3>
```

Defines a vector with three components.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<Vector3>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\\[static Vector3 Backward](VRageMath.Vector3.Backward)||
|\\[static Vector3 Down](VRageMath.Vector3.Down)||
|\\[static Vector3 Forward](VRageMath.Vector3.Forward)||
|\\[static Vector3 Half](VRageMath.Vector3.Half)||
|\\[static Vector3 Invalid](VRageMath.Vector3.Invalid)||
|\\[static Vector3 Left](VRageMath.Vector3.Left)||
|\\[static Vector3 MaxValue](VRageMath.Vector3.MaxValue)||
|\\[static Vector3 MinusOne](VRageMath.Vector3.MinusOne)||
|\\[static Vector3 MinValue](VRageMath.Vector3.MinValue)||
|\\[static Vector3 NegativeInfinity](VRageMath.Vector3.NegativeInfinity)||
|\\[static Vector3 One](VRageMath.Vector3.One)||
|\\[static Vector3 PositiveInfinity](VRageMath.Vector3.PositiveInfinity)||
|\\[static Vector3 Right](VRageMath.Vector3.Right)||
|\\[static Vector3 UnitX](VRageMath.Vector3.UnitX)||
|\\[static Vector3 UnitY](VRageMath.Vector3.UnitY)||
|\\[static Vector3 UnitZ](VRageMath.Vector3.UnitZ)||
|\\[static Vector3 Up](VRageMath.Vector3.Up)||
|\\[static Vector3 Zero](VRageMath.Vector3.Zero)||
|\\[float X](VRageMath.Vector3.X)|Gets or sets the x-component of the vector.|
|\\[float Y](VRageMath.Vector3.Y)|Gets or sets the y-component of the vector.|
|\\[float Z](VRageMath.Vector3.Z)|Gets or sets the z-component of the vector.|

#### Properties

|Member|Description|
|---|---|
|\\[float Sum { get; }](VRageMath.Vector3.Sum)||
|\\[float Volume { get; }](VRageMath.Vector3.Volume)||

#### Constructors

|Member|Description|
|---|---|
|\\[Vector3(float, float, float)](VRageMath.Vector3..ctor)||
|\\[Vector3(double, double, double)](VRageMath.Vector3..ctor)||
|\\[Vector3(float)](VRageMath.Vector3..ctor)||
|\\[Vector3(Vector2, float)](VRageMath.Vector3..ctor)||
|\\[Vector3(Vector4)](VRageMath.Vector3..ctor)||
|\\[Vector3(ref Vector3I)](VRageMath.Vector3..ctor)||
|\\[Vector3(Vector3I)](VRageMath.Vector3..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\[static Vector3 Abs(Vector3)](VRageMath.Vector3.Abs)||
|\\[static Vector3 Add(Vector3, Vector3)](VRageMath.Vector3.Add)|Adds two vectors.|
|\\[static void Add(ref Vector3, ref Vector3, out Vector3)](VRageMath.Vector3.Add)|Adds two vectors.|
|\\[static bool ArePerpendicular(ref Vector3, ref Vector3)](VRageMath.Vector3.ArePerpendicular)||
|\\[static bool ArePerpendicular(Vector3, Vector3)](VRageMath.Vector3.ArePerpendicular)||
|\\[static Vector3 Barycentric(Vector3, Vector3, Vector3, float, float)](VRageMath.Vector3.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in Barycentric coordinates relative to a 3D triangle.|
|\\[static void Barycentric(ref Vector3, ref Vector3, ref Vector3, float, float, out Vector3)](VRageMath.Vector3.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 3D triangle.|
|\\[static void Barycentric(Vector3, Vector3, Vector3, Vector3, out float, out float, out float)](VRageMath.Vector3.Barycentric)|Compute barycentric coordinates (u, v, w) for point p with respect to triangle (a, b, c) From : Real-Time Collision Detection, Christer Ericson, CRC Press 3.4 Barycentric Coordinates|
|\\[static Vector3 CalculatePerpendicularVector(Vector3)](VRageMath.Vector3.CalculatePerpendicularVector)||
|\\[static Vector3 CatmullRom(Vector3, Vector3, Vector3, Vector3, float)](VRageMath.Vector3.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|\\[static void CatmullRom(ref Vector3, ref Vector3, ref Vector3, ref Vector3, float, out Vector3)](VRageMath.Vector3.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|\\[static Vector3 Ceiling(Vector3)](VRageMath.Vector3.Ceiling)||
|\\[static Vector3 Clamp(Vector3, Vector3, Vector3)](VRageMath.Vector3.Clamp)|Restricts a value to be within a specified range.|
|\\[static void Clamp(ref Vector3, ref Vector3, ref Vector3, out Vector3)](VRageMath.Vector3.Clamp)|Restricts a value to be within a specified range.|
|\\[static Vector3 ClampToSphere(Vector3, float)](VRageMath.Vector3.ClampToSphere)||
|\\[static void ClampToSphere(ref Vector3, float)](VRageMath.Vector3.ClampToSphere)||
|\\[static void CreateFromAzimuthAndElevation(float, float, out Vector3)](VRageMath.Vector3.CreateFromAzimuthAndElevation)||
|\\[static Vector3 Cross(Vector3, Vector3)](VRageMath.Vector3.Cross)|Calculates the cross product of two vectors.|
|\\[static void Cross(ref Vector3, ref Vector3, out Vector3)](VRageMath.Vector3.Cross)|Calculates the cross product of two vectors.|
|\\[static float Distance(Vector3, Vector3)](VRageMath.Vector3.Distance)|Calculates the distance between two vectors.|
|\\[static void Distance(ref Vector3, ref Vector3, out float)](VRageMath.Vector3.Distance)|Calculates the distance between two vectors.|
|\\[static float DistanceSquared(Vector3, Vector3)](VRageMath.Vector3.DistanceSquared)|Calculates the distance between two vectors squared.|
|\\[static void DistanceSquared(ref Vector3, ref Vector3, out float)](VRageMath.Vector3.DistanceSquared)|Calculates the distance between two vectors squared.|
|\\[static Vector3 Divide(Vector3, Vector3)](VRageMath.Vector3.Divide)|Divides the components of a vector by the components of another vector.|
|\\[static void Divide(ref Vector3, ref Vector3, out Vector3)](VRageMath.Vector3.Divide)|Divides the components of a vector by the components of another vector.|
|\\[static Vector3 Divide(Vector3, float)](VRageMath.Vector3.Divide)|Divides a vector by a scalar value.|
|\\[static void Divide(ref Vector3, float, out Vector3)](VRageMath.Vector3.Divide)|Divides a vector by a scalar value.|
|\\[static Vector3 DominantAxisProjection(Vector3)](VRageMath.Vector3.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|\\[static void DominantAxisProjection(ref Vector3, out Vector3)](VRageMath.Vector3.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved into a user-specified variable.|
|\\[static float Dot(Vector3, Vector3)](VRageMath.Vector3.Dot)|Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|\\[static void Dot(ref Vector3, ref Vector3, out float)](VRageMath.Vector3.Dot)|Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|\\[static Vector3 Floor(Vector3)](VRageMath.Vector3.Floor)||
|\\[static void GetAzimuthAndElevation(Vector3, out float, out float)](VRageMath.Vector3.GetAzimuthAndElevation)||
|\\[static bool GetNormalized(ref Vector3)](VRageMath.Vector3.GetNormalized)||
|\\[static Vector3 Hermite(Vector3, Vector3, Vector3, Vector3, float)](VRageMath.Vector3.Hermite)|Performs a Hermite spline interpolation.|
|\\[static void Hermite(ref Vector3, ref Vector3, ref Vector3, ref Vector3, float, out Vector3)](VRageMath.Vector3.Hermite)|Performs a Hermite spline interpolation.|
|\\[static bool IsUnit(ref Vector3)](VRageMath.Vector3.IsUnit)||
|\\[static bool IsZero(ref Vector3)](VRageMath.Vector3.IsZero)||
|\\[static bool IsZero(Vector3)](VRageMath.Vector3.IsZero)||
|\\[static bool IsZero(Vector3, float)](VRageMath.Vector3.IsZero)||
|\\[static Vector3 IsZeroVector(Vector3)](VRageMath.Vector3.IsZeroVector)||
|\\[static Vector3 IsZeroVector(Vector3, float)](VRageMath.Vector3.IsZeroVector)||
|\\[static Vector3 Lerp(Vector3, Vector3, float)](VRageMath.Vector3.Lerp)|Performs a linear interpolation between two vectors.|
|\\[static void Lerp(ref Vector3, ref Vector3, float, out Vector3)](VRageMath.Vector3.Lerp)|Performs a linear interpolation between two vectors.|
|\\[static Vector3 Max(Vector3, Vector3)](VRageMath.Vector3.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|\\[static void Max(ref Vector3, ref Vector3, out Vector3)](VRageMath.Vector3.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|\\[static Vector3 Min(Vector3, Vector3)](VRageMath.Vector3.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|\\[static void Min(ref Vector3, ref Vector3, out Vector3)](VRageMath.Vector3.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|\\[static void MinMax(ref Vector3, ref Vector3)](VRageMath.Vector3.MinMax)|Separates minimal and maximal values of any two input vectors|
|\\[static Vector3 Multiply(Vector3, Vector3)](VRageMath.Vector3.Multiply)|Multiplies the components of two vectors by each other.|
|\\[static void Multiply(ref Vector3, ref Vector3, out Vector3)](VRageMath.Vector3.Multiply)|Multiplies the components of two vectors by each other.|
|\\[static Vector3 Multiply(Vector3, float)](VRageMath.Vector3.Multiply)|Multiplies a vector by a scalar value.|
|\\[static void Multiply(ref Vector3, float, out Vector3)](VRageMath.Vector3.Multiply)|Multiplies a vector by a scalar value.|
|\\[static Vector3 Negate(Vector3)](VRageMath.Vector3.Negate)|Returns a vector pointing in the opposite direction.|
|\\[static void Negate(ref Vector3, out Vector3)](VRageMath.Vector3.Negate)|Returns a vector pointing in the opposite direction.|
|\\[static Vector3 Normalize(Vector3)](VRageMath.Vector3.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|\\[static Vector3 Normalize(Vector3D)](VRageMath.Vector3.Normalize)||
|\\[static void Normalize(ref Vector3, out Vector3)](VRageMath.Vector3.Normalize)|Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.|
|\\[static Vector3 ProjectOnPlane(ref Vector3, ref Vector3)](VRageMath.Vector3.ProjectOnPlane)|Projects given vector on plane specified by it's normal.|
|\\[static Vector3 ProjectOnVector(ref Vector3, ref Vector3)](VRageMath.Vector3.ProjectOnVector)|Projects vector on another vector resulting in new vector in guided vector's direction with different length.|
|\\[static float RectangularDistance(Vector3, Vector3)](VRageMath.Vector3.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|\\[static float RectangularDistance(ref Vector3, ref Vector3)](VRageMath.Vector3.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|\\[static Vector3 Reflect(Vector3, Vector3)](VRageMath.Vector3.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|\\[static void Reflect(ref Vector3, ref Vector3, out Vector3)](VRageMath.Vector3.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|\\[static Vector3 Reject(Vector3, Vector3)](VRageMath.Vector3.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|\\[static void Reject(ref Vector3, ref Vector3, out Vector3)](VRageMath.Vector3.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|\\[static void RotateAndScale(ref Vector3, ref Matrix, out Vector3)](VRageMath.Vector3.RotateAndScale)||
|\\[static Vector3 RotateAndScale(Vector3, Matrix)](VRageMath.Vector3.RotateAndScale)||
|\\[static Vector3 Round(Vector3)](VRageMath.Vector3.Round)||
|\\[static Vector3 Round(Vector3, int)](VRageMath.Vector3.Round)||
|\\[static Vector3 Sign(Vector3)](VRageMath.Vector3.Sign)||
|\\[static Vector3 Sign(Vector3, float)](VRageMath.Vector3.Sign)||
|\\[static Vector3 SignNonZero(Vector3)](VRageMath.Vector3.SignNonZero)|Returns per component sign, never returns zero. For zero component returns sign 1. Faster than Sign.|
|\\[static Vector3 SmoothStep(Vector3, Vector3, float)](VRageMath.Vector3.SmoothStep)|Interpolates between two values using a cubic equation.|
|\\[static void SmoothStep(ref Vector3, ref Vector3, float, out Vector3)](VRageMath.Vector3.SmoothStep)|Interpolates between two values using a cubic equation.|
|\\[static Vector3 Step(Vector3)](VRageMath.Vector3.Step)||
|\\[static Vector3 Subtract(Vector3, Vector3)](VRageMath.Vector3.Subtract)|Subtracts a vector from a vector.|
|\\[static void Subtract(ref Vector3, ref Vector3, out Vector3)](VRageMath.Vector3.Subtract)|Subtracts a vector from a vector.|
|\\[static Vector3 SwapYZCoordinates(Vector3)](VRageMath.Vector3.SwapYZCoordinates)||
|\\[static Vector3 Transform(Vector3, Matrix)](VRageMath.Vector3.Transform)|Transforms a 3D vector by the given matrix.|
|\\[static Vector3D Transform(Vector3, MatrixD)](VRageMath.Vector3.Transform)|Transforms a 3D vector by the given matrix.|
|\\[static Vector3 Transform(Vector3, ref Matrix)](VRageMath.Vector3.Transform)||
|\\[static void Transform(ref Vector3, ref Matrix, out Vector3)](VRageMath.Vector3.Transform)|Transforms a Vector3 by the given Matrix.|
|\\[static void Transform(ref Vector3, ref MatrixI, out Vector3)](VRageMath.Vector3.Transform)||
|\\[static Vector3 Transform(Vector3, Quaternion)](VRageMath.Vector3.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|\\[static void Transform(ref Vector3, ref Quaternion, out Vector3)](VRageMath.Vector3.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|\\[static void Transform(Vector3\\[], ref Matrix, Vector3\\[])](VRageMath.Vector3.Transform)|Transforms a source array of Vector3s by a specified Matrix and writes the results to an existing destination array.|
|\\[static void Transform(Vector3\\[], int, ref Matrix, Vector3\\[], int, int)](VRageMath.Vector3.Transform)|Applies a specified transform Matrix to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|\\[static void Transform(Vector3\\[], ref Quaternion, Vector3\\[])](VRageMath.Vector3.Transform)|Transforms a source array of Vector3s by a specified Quaternion rotation and writes the results to an existing destination array.|
|\\[static void Transform(Vector3\\[], int, ref Quaternion, Vector3\\[], int, int)](VRageMath.Vector3.Transform)|Applies a specified Quaternion rotation to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|\\[static void TransformNoProjection(ref Vector3, ref Matrix, out Vector3)](VRageMath.Vector3.TransformNoProjection)||
|\\[static Vector3 TransformNormal(Vector3, Matrix)](VRageMath.Vector3.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|\\[static Vector3 TransformNormal(Vector3, MatrixD)](VRageMath.Vector3.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|\\[static Vector3 TransformNormal(Vector3D, Matrix)](VRageMath.Vector3.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|\\[static void TransformNormal(ref Vector3, ref Matrix, out Vector3)](VRageMath.Vector3.TransformNormal)|Transforms a vector normal by a matrix.|
|\\[static void TransformNormal(ref Vector3, ref MatrixD, out Vector3)](VRageMath.Vector3.TransformNormal)||
|\\[static void TransformNormal(ref Vector3, ref MatrixI, out Vector3)](VRageMath.Vector3.TransformNormal)||
|\\[static Vector3 TransformNormal(Vector3, MyBlockOrientation)](VRageMath.Vector3.TransformNormal)||
|\\[static void TransformNormal(ref Vector3, MyBlockOrientation, out Vector3)](VRageMath.Vector3.TransformNormal)||
|\\[static Vector3 TransformNormal(Vector3, ref Matrix)](VRageMath.Vector3.TransformNormal)||
|\\[static void TransformNormal(Vector3\\[], ref Matrix, Vector3\\[])](VRageMath.Vector3.TransformNormal)|Transforms an array of 3D vector normals by a specified Matrix.|
|\\[static void TransformNormal(Vector3\\[], int, ref Matrix, Vector3\\[], int, int)](VRageMath.Vector3.TransformNormal)|Transforms a specified range in an array of 3D vector normals by a specified Matrix and writes the results to a specified range in a destination array.|
|\\[static void TransformProjection(ref Vector3, ref Matrix, out Vector3)](VRageMath.Vector3.TransformProjection)|Transforms a Vector3 by the given projection matrix (both ortho and perspective are supported)|
|\\[static float TriangleArea(Vector3, Vector3, Vector3)](VRageMath.Vector3.TriangleArea)||
|\\[static float TriangleArea(ref Vector3, ref Vector3, ref Vector3)](VRageMath.Vector3.TriangleArea)||
|\\[float AbsMax()](VRageMath.Vector3.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|\\[float AbsMin()](VRageMath.Vector3.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|\\[void Add(Vector3)](VRageMath.Vector3.Add)||
|\\[void AssertIsValid()](VRageMath.Vector3.AssertIsValid)||
|\\[void CalculatePerpendicularVector(out Vector3)](VRageMath.Vector3.CalculatePerpendicularVector)||
|\\[Vector3 Cross(Vector3)](VRageMath.Vector3.Cross)||
|\\[void Divide(float)](VRageMath.Vector3.Divide)||
|\\[float Dot(Vector3)](VRageMath.Vector3.Dot)||
|\\[float Dot(ref Vector3)](VRageMath.Vector3.Dot)||
|\\[bool Equals(Vector3)](VRageMath.Vector3.Equals)|Determines whether the specified Object is equal to the Vector3.|
|\\[bool Equals(Vector3, float)](VRageMath.Vector3.Equals)||
|\\[bool Equals(object)](VRageMath.Vector3.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|\\[float GetDim(int)](VRageMath.Vector3.GetDim)||
|\\[long GetHash()](VRageMath.Vector3.GetHash)|Gets the hash code of the vector object.|
|\\[int GetHashCode()](VRageMath.Vector3.GetHashCode)||
|\\[void Interpolate3(Vector3, Vector3, float)](VRageMath.Vector3.Interpolate3)||
|\\[bool IsInsideInclusive(ref Vector3, ref Vector3)](VRageMath.Vector3.IsInsideInclusive)||
|\\[bool IsValid()](VRageMath.Vector3.IsValid)||
|\\[float Length()](VRageMath.Vector3.Length)|Calculates the length of the vector.|
|\\[float LengthSquared()](VRageMath.Vector3.LengthSquared)|Calculates the length of the vector squared.|
|\\[float Max()](VRageMath.Vector3.Max)|Returns the component of the vector that is largest of all the three components.|
|\\[Vector3 MaxAbsComponent()](VRageMath.Vector3.MaxAbsComponent)|Keeps only component with maximal absolute, others are set to zero.|
|\\[float Min()](VRageMath.Vector3.Min)|Returns the component of the vector that is smallest of all the three components.|
|\\[void Multiply(float)](VRageMath.Vector3.Multiply)||
|\\[float Normalize()](VRageMath.Vector3.Normalize)|Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|\\[void SetDim(int, float)](VRageMath.Vector3.SetDim)||
|\\[string ToString()](VRageMath.Vector3.ToString)|Retrieves a string representation of the current object.|
|\\[string ToString(string)](VRageMath.Vector3.ToString)||
|\\[long VolumeInt(float)](VRageMath.Vector3.VolumeInt)||

