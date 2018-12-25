← [Index](Api-Index)

#### Vector3D Struct

```csharp
private public sealed Vector3D
```

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

#### Example

#### Remarks

#### Fields

|Member|Description|
|---|---|
|[X](VRageMath.Vector3D.X)|Gets or sets the x-component of the vector.|
|[Y](VRageMath.Vector3D.Y)|Gets or sets the y-component of the vector.|
|[Z](VRageMath.Vector3D.Z)|Gets or sets the z-component of the vector.|
|[Zero](VRageMath.Vector3D.Zero)||
|[One](VRageMath.Vector3D.One)||
|[Half](VRageMath.Vector3D.Half)||
|[PositiveInfinity](VRageMath.Vector3D.PositiveInfinity)||
|[NegativeInfinity](VRageMath.Vector3D.NegativeInfinity)||
|[UnitX](VRageMath.Vector3D.UnitX)||
|[UnitY](VRageMath.Vector3D.UnitY)||
|[UnitZ](VRageMath.Vector3D.UnitZ)||
|[Up](VRageMath.Vector3D.Up)||
|[Down](VRageMath.Vector3D.Down)||
|[Right](VRageMath.Vector3D.Right)||
|[Left](VRageMath.Vector3D.Left)||
|[Forward](VRageMath.Vector3D.Forward)||
|[Backward](VRageMath.Vector3D.Backward)||
|[MaxValue](VRageMath.Vector3D.MaxValue)||
|[MinValue](VRageMath.Vector3D.MinValue)||

#### Properties

|Member|Description|
|---|---|
|[Sum](VRageMath.Vector3D.Sum)||
|[Volume](VRageMath.Vector3D.Volume)||

#### Methods

|Member|Description|
|---|---|
|[TransformNormal(ref Vector3D, ref MatrixI, ref Vector3D)](VRageMath.Vector3D.TransformNormal)||
|[TransformNormal(Vector3D, MyBlockOrientation)](VRageMath.Vector3D.TransformNormal)||
|[TransformNormal(ref Vector3D, MyBlockOrientation, ref Vector3D)](VRageMath.Vector3D.TransformNormal)||
|[TransformNormal(Vector3D, ref MatrixD)](VRageMath.Vector3D.TransformNormal)||
|[Transform(Vector3D, Quaternion)](VRageMath.Vector3D.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|[Transform(ref Vector3D, ref Quaternion, ref Vector3D)](VRageMath.Vector3D.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|[Rotate(ref Vector3D, ref MatrixD, ref Vector3D)](VRageMath.Vector3D.Rotate)||
|[Rotate(Vector3D, MatrixD)](VRageMath.Vector3D.Rotate)||
|[Transform(Vector3D[], ref MatrixD, Vector3D[])](VRageMath.Vector3D.Transform)|Transforms a source array of Vector3s by a specified Matrix and writes the results to an existing destination array.|
|[Transform(Vector3D[], ref MatrixD, *Vector3D)](VRageMath.Vector3D.Transform)||
|[Transform(Vector3D[], int, ref Matrix, Vector3D[], int, int)](VRageMath.Vector3D.Transform)|Applies a specified transform Matrix to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|[TransformNormal(Vector3D[], ref Matrix, Vector3D[])](VRageMath.Vector3D.TransformNormal)|Transforms an array of 3D vector normals by a specified Matrix.|
|[TransformNormal(Vector3D[], ref Matrix, *Vector3D)](VRageMath.Vector3D.TransformNormal)||
|[TransformNormal(Vector3D[], int, ref Matrix, Vector3D[], int, int)](VRageMath.Vector3D.TransformNormal)|Transforms a specified range in an array of 3D vector normals by a specified Matrix and writes the results to a specified range in a destination array.|
|[Transform(Vector3D[], ref Quaternion, Vector3D[])](VRageMath.Vector3D.Transform)|Transforms a source array of Vector3s by a specified Quaternion rotation and writes the results to an existing destination array.|
|[Transform(Vector3D[], int, ref Quaternion, Vector3D[], int, int)](VRageMath.Vector3D.Transform)|Applies a specified Quaternion rotation to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|[Negate(Vector3D)](VRageMath.Vector3D.Negate)|Returns a vector pointing in the opposite direction.|
|[Negate(ref Vector3D, ref Vector3D)](VRageMath.Vector3D.Negate)|Returns a vector pointing in the opposite direction.|
|[Add(Vector3D, Vector3D)](VRageMath.Vector3D.Add)|Adds two vectors.|
|[Add(ref Vector3D, ref Vector3D, ref Vector3D)](VRageMath.Vector3D.Add)|Adds two vectors.|
|[Subtract(Vector3D, Vector3D)](VRageMath.Vector3D.Subtract)|Subtracts a vector from a vector.|
|[Subtract(ref Vector3D, ref Vector3D, ref Vector3D)](VRageMath.Vector3D.Subtract)|Subtracts a vector from a vector.|
|[Multiply(Vector3D, Vector3D)](VRageMath.Vector3D.Multiply)|Multiplies the components of two vectors by each other.|
|[Multiply(ref Vector3D, ref Vector3D, ref Vector3D)](VRageMath.Vector3D.Multiply)|Multiplies the components of two vectors by each other.|
|[Multiply(Vector3D, double)](VRageMath.Vector3D.Multiply)|Multiplies a vector by a scalar value.|
|[Multiply(ref Vector3D, double, ref Vector3D)](VRageMath.Vector3D.Multiply)|Multiplies a vector by a scalar value.|
|[Divide(Vector3D, Vector3D)](VRageMath.Vector3D.Divide)|Divides the components of a vector by the components of another vector.|
|[Divide(ref Vector3D, ref Vector3D, ref Vector3D)](VRageMath.Vector3D.Divide)|Divides the components of a vector by the components of another vector.|
|[Divide(Vector3D, double)](VRageMath.Vector3D.Divide)|Divides a vector by a scalar value.|
|[Divide(ref Vector3D, double, ref Vector3D)](VRageMath.Vector3D.Divide)|Divides a vector by a scalar value.|
|[CalculatePerpendicularVector(Vector3D)](VRageMath.Vector3D.CalculatePerpendicularVector)||
|[CalculatePerpendicularVector(ref Vector3D)](VRageMath.Vector3D.CalculatePerpendicularVector)||
|[GetAzimuthAndElevation(Vector3D, ref double, ref double)](VRageMath.Vector3D.GetAzimuthAndElevation)||
|[CreateFromAzimuthAndElevation(double, double, ref Vector3D)](VRageMath.Vector3D.CreateFromAzimuthAndElevation)||
|[VolumeInt(double)](VRageMath.Vector3D.VolumeInt)||
|[IsInsideInclusive(ref Vector3D, ref Vector3D)](VRageMath.Vector3D.IsInsideInclusive)||
|[SwapYZCoordinates(Vector3D)](VRageMath.Vector3D.SwapYZCoordinates)||
|[GetDim(int)](VRageMath.Vector3D.GetDim)||
|[SetDim(int, double)](VRageMath.Vector3D.SetDim)||
|[Round(Vector3D)](VRageMath.Vector3D.Round)||
|[Floor(Vector3D)](VRageMath.Vector3D.Floor)||
|[Fract(ref Vector3D, ref Vector3D)](VRageMath.Vector3D.Fract)||
|[Round(Vector3D, int)](VRageMath.Vector3D.Round)||
|[Abs(ref Vector3D, ref Vector3D)](VRageMath.Vector3D.Abs)||
|[ProjectOnPlane(ref Vector3D, ref Vector3D)](VRageMath.Vector3D.ProjectOnPlane)|Projects given vector on plane specified by it's normal.|
|[ProjectOnVector(ref Vector3D, ref Vector3D)](VRageMath.Vector3D.ProjectOnVector)|Projects vector on another vector resulting in new vector in guided vector's direction with different length.|
|[Abs(Vector3D)](VRageMath.Vector3D.Abs)||
|[Sign(Vector3D)](VRageMath.Vector3D.Sign)||
|[SignNonZero(Vector3D)](VRageMath.Vector3D.SignNonZero)|Returns per component sign, never returns zero. For zero component returns sign 1. Faster than Sign.|
|[Interpolate3(Vector3D, Vector3D, double)](VRageMath.Vector3D.Interpolate3)||
|[IsValid()](VRageMath.Vector3D.IsValid)||
|[AssertIsValid()](VRageMath.Vector3D.AssertIsValid)||
|[IsUnit(ref Vector3D)](VRageMath.Vector3D.IsUnit)||
|[ArePerpendicular(ref Vector3D, ref Vector3D)](VRageMath.Vector3D.ArePerpendicular)||
|[IsZero(Vector3D)](VRageMath.Vector3D.IsZero)||
|[IsZero(Vector3D, double)](VRageMath.Vector3D.IsZero)||
|[IsZeroVector(Vector3D)](VRageMath.Vector3D.IsZeroVector)||
|[IsZeroVector(Vector3D, double)](VRageMath.Vector3D.IsZeroVector)||
|[Step(Vector3D)](VRageMath.Vector3D.Step)||
|[ToString()](VRageMath.Vector3D.ToString)|Retrieves a string representation of the current object.|
|[TryParse(string, ref Vector3D)](VRageMath.Vector3D.TryParse)||
|[ToString(string)](VRageMath.Vector3D.ToString)||
|[Equals(Vector3D)](VRageMath.Vector3D.Equals)|Determines whether the specified Object is equal to the Vector3.|
|[Equals(Vector3D, double)](VRageMath.Vector3D.Equals)||
|[Equals(object)](VRageMath.Vector3D.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[GetHashCode()](VRageMath.Vector3D.GetHashCode)||
|[GetHash()](VRageMath.Vector3D.GetHash)|Gets the hash code of the vector object.|
|[Length()](VRageMath.Vector3D.Length)|Calculates the length of the vector.|
|[LengthSquared()](VRageMath.Vector3D.LengthSquared)|Calculates the length of the vector squared.|
|[Distance(Vector3D, Vector3D)](VRageMath.Vector3D.Distance)|Calculates the distance between two vectors.|
|[Distance(Vector3D, Vector3)](VRageMath.Vector3D.Distance)||
|[Distance(Vector3, Vector3D)](VRageMath.Vector3D.Distance)||
|[Distance(ref Vector3D, ref Vector3D, ref double)](VRageMath.Vector3D.Distance)|Calculates the distance between two vectors.|
|[DistanceSquared(Vector3D, Vector3D)](VRageMath.Vector3D.DistanceSquared)|Calculates the distance between two vectors squared.|
|[DistanceSquared(ref Vector3D, ref Vector3D, ref double)](VRageMath.Vector3D.DistanceSquared)|Calculates the distance between two vectors squared.|
|[RectangularDistance(Vector3D, Vector3D)](VRageMath.Vector3D.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|[RectangularDistance(ref Vector3D, ref Vector3D)](VRageMath.Vector3D.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|[Dot(Vector3D, Vector3D)](VRageMath.Vector3D.Dot)|Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[Dot(Vector3D, Vector3)](VRageMath.Vector3D.Dot)||
|[Dot(ref Vector3D, ref Vector3D, ref double)](VRageMath.Vector3D.Dot)|Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a doubleing point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[Dot(ref Vector3D, ref Vector3, ref double)](VRageMath.Vector3D.Dot)||
|[Dot(ref Vector3, ref Vector3D, ref double)](VRageMath.Vector3D.Dot)||
|[Dot(Vector3D)](VRageMath.Vector3D.Dot)||
|[Dot(Vector3)](VRageMath.Vector3D.Dot)||
|[Dot(ref Vector3D)](VRageMath.Vector3D.Dot)||
|[Cross(Vector3D)](VRageMath.Vector3D.Cross)||
|[Normalize()](VRageMath.Vector3D.Normalize)|Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[Normalize(Vector3D)](VRageMath.Vector3D.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[Normalize(ref Vector3D, ref Vector3D)](VRageMath.Vector3D.Normalize)|Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[Cross(Vector3D, Vector3D)](VRageMath.Vector3D.Cross)|Calculates the cross product of two vectors.|
|[Cross(ref Vector3D, ref Vector3D, ref Vector3D)](VRageMath.Vector3D.Cross)|Calculates the cross product of two vectors.|
|[Reflect(Vector3D, Vector3D)](VRageMath.Vector3D.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|[Reflect(ref Vector3D, ref Vector3D, ref Vector3D)](VRageMath.Vector3D.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|[Reject(Vector3D, Vector3D)](VRageMath.Vector3D.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|[Reject(ref Vector3D, ref Vector3D, ref Vector3D)](VRageMath.Vector3D.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|[Min()](VRageMath.Vector3D.Min)|Returns the component of the vector that is smallest of all the three components.|
|[AbsMin()](VRageMath.Vector3D.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|[Max()](VRageMath.Vector3D.Max)|Returns the component of the vector that is largest of all the three components.|
|[AbsMax()](VRageMath.Vector3D.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|[AbsMaxComponent()](VRageMath.Vector3D.AbsMaxComponent)||
|[Min(Vector3D, Vector3D)](VRageMath.Vector3D.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|[Min(ref Vector3D, ref Vector3D, ref Vector3D)](VRageMath.Vector3D.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|[Max(Vector3D, Vector3D)](VRageMath.Vector3D.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|[Max(ref Vector3D, ref Vector3D, ref Vector3D)](VRageMath.Vector3D.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|[MinMax(ref Vector3D, ref Vector3D)](VRageMath.Vector3D.MinMax)|Separates minimal and maximal values of any two input vectors|
|[DominantAxisProjection(Vector3D)](VRageMath.Vector3D.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|[DominantAxisProjection(ref Vector3D, ref Vector3D)](VRageMath.Vector3D.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved into a user-specified variable.|
|[Clamp(Vector3D, Vector3D, Vector3D)](VRageMath.Vector3D.Clamp)|Restricts a value to be within a specified range.|
|[Clamp(ref Vector3D, ref Vector3D, ref Vector3D, ref Vector3D)](VRageMath.Vector3D.Clamp)|Restricts a value to be within a specified range.|
|[ClampToSphere(Vector3D, double)](VRageMath.Vector3D.ClampToSphere)||
|[ClampToSphere(ref Vector3D, double)](VRageMath.Vector3D.ClampToSphere)||
|[Lerp(Vector3D, Vector3D, double)](VRageMath.Vector3D.Lerp)|Performs a linear interpolation between two vectors.|
|[Lerp(ref Vector3D, ref Vector3D, double, ref Vector3D)](VRageMath.Vector3D.Lerp)|Performs a linear interpolation between two vectors.|
|[Barycentric(Vector3D, Vector3D, Vector3D, double, double)](VRageMath.Vector3D.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in Barycentric coordinates relative to a 3D triangle.|
|[Barycentric(ref Vector3D, ref Vector3D, ref Vector3D, double, double, ref Vector3D)](VRageMath.Vector3D.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 3D triangle.|
|[Barycentric(Vector3D, Vector3D, Vector3D, Vector3D, ref double, ref double, ref double)](VRageMath.Vector3D.Barycentric)|Compute barycentric coordinates (u, v, w) for point p with respect to triangle (a, b, c) From : Real-Time Collision Detection, Christer Ericson, CRC Press 3.4 Barycentric Coordinates|
|[SmoothStep(Vector3D, Vector3D, double)](VRageMath.Vector3D.SmoothStep)|Interpolates between two values using a cubic equation.|
|[SmoothStep(ref Vector3D, ref Vector3D, double, ref Vector3D)](VRageMath.Vector3D.SmoothStep)|Interpolates between two values using a cubic equation.|
|[CatmullRom(Vector3D, Vector3D, Vector3D, Vector3D, double)](VRageMath.Vector3D.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|[CatmullRom(ref Vector3D, ref Vector3D, ref Vector3D, ref Vector3D, double, ref Vector3D)](VRageMath.Vector3D.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|[Hermite(Vector3D, Vector3D, Vector3D, Vector3D, double)](VRageMath.Vector3D.Hermite)|Performs a Hermite spline interpolation.|
|[Hermite(ref Vector3D, ref Vector3D, ref Vector3D, ref Vector3D, double, ref Vector3D)](VRageMath.Vector3D.Hermite)|Performs a Hermite spline interpolation.|
|[Transform(Vector3D, MatrixD)](VRageMath.Vector3D.Transform)|Transforms a 3D vector by the given matrix.|
|[Transform(Vector3, MatrixD)](VRageMath.Vector3D.Transform)||
|[Transform(Vector3D, Matrix)](VRageMath.Vector3D.Transform)|Transforms a 3D vector by the given matrix.|
|[Transform(Vector3D, ref MatrixD)](VRageMath.Vector3D.Transform)||
|[Transform(ref Vector3D, ref MatrixD, ref Vector3D)](VRageMath.Vector3D.Transform)|Transforms a Vector3 by the given Matrix.|
|[Transform(ref Vector3, ref MatrixD, ref Vector3D)](VRageMath.Vector3D.Transform)||
|[TransformNoProjection(ref Vector3D, ref MatrixD, ref Vector3D)](VRageMath.Vector3D.TransformNoProjection)||
|[RotateAndScale(ref Vector3D, ref MatrixD, ref Vector3D)](VRageMath.Vector3D.RotateAndScale)||
|[Transform(ref Vector3D, ref MatrixI, ref Vector3D)](VRageMath.Vector3D.Transform)||
|[TransformNormal(Vector3D, Matrix)](VRageMath.Vector3D.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|[TransformNormal(Vector3, MatrixD)](VRageMath.Vector3D.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|[TransformNormal(Vector3D, MatrixD)](VRageMath.Vector3D.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|[TransformNormal(ref Vector3D, ref MatrixD, ref Vector3D)](VRageMath.Vector3D.TransformNormal)|Transforms a vector normal by a matrix.|
|[TransformNormal(ref Vector3, ref MatrixD, ref Vector3D)](VRageMath.Vector3D.TransformNormal)||

