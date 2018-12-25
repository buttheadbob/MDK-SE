← [Index](Api-Index)

#### Vector3 Struct

```csharp
public struct Vector3: 
```

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

#### Example

#### Remarks

#### Fields

|Member|Description|
|---|---|
|[X](VRageMath.Vector3.X)|Gets or sets the x-component of the vector.|
|[Y](VRageMath.Vector3.Y)|Gets or sets the y-component of the vector.|
|[Z](VRageMath.Vector3.Z)|Gets or sets the z-component of the vector.|
|[Zero](VRageMath.Vector3.Zero)||
|[One](VRageMath.Vector3.One)||
|[MinusOne](VRageMath.Vector3.MinusOne)||
|[Half](VRageMath.Vector3.Half)||
|[PositiveInfinity](VRageMath.Vector3.PositiveInfinity)||
|[NegativeInfinity](VRageMath.Vector3.NegativeInfinity)||
|[UnitX](VRageMath.Vector3.UnitX)||
|[UnitY](VRageMath.Vector3.UnitY)||
|[UnitZ](VRageMath.Vector3.UnitZ)||
|[Up](VRageMath.Vector3.Up)||
|[Down](VRageMath.Vector3.Down)||
|[Right](VRageMath.Vector3.Right)||
|[Left](VRageMath.Vector3.Left)||
|[Forward](VRageMath.Vector3.Forward)||
|[Backward](VRageMath.Vector3.Backward)||
|[MaxValue](VRageMath.Vector3.MaxValue)||
|[MinValue](VRageMath.Vector3.MinValue)||
|[Invalid](VRageMath.Vector3.Invalid)||

#### Properties

|Member|Description|
|---|---|
|[Sum](VRageMath.Vector3.Sum)||
|[Volume](VRageMath.Vector3.Volume)||

#### Methods

|Member|Description|
|---|---|
|[Negate(ref Vector3, ref Vector3)](VRageMath.Vector3.Negate)|Returns a vector pointing in the opposite direction.|
|[Add(Vector3, Vector3)](VRageMath.Vector3.Add)|Adds two vectors.|
|[Add(ref Vector3, ref Vector3, ref Vector3)](VRageMath.Vector3.Add)|Adds two vectors.|
|[Subtract(Vector3, Vector3)](VRageMath.Vector3.Subtract)|Subtracts a vector from a vector.|
|[Subtract(ref Vector3, ref Vector3, ref Vector3)](VRageMath.Vector3.Subtract)|Subtracts a vector from a vector.|
|[Multiply(Vector3, Vector3)](VRageMath.Vector3.Multiply)|Multiplies the components of two vectors by each other.|
|[Multiply(ref Vector3, ref Vector3, ref Vector3)](VRageMath.Vector3.Multiply)|Multiplies the components of two vectors by each other.|
|[Multiply(Vector3, float)](VRageMath.Vector3.Multiply)|Multiplies a vector by a scalar value.|
|[Multiply(ref Vector3, float, ref Vector3)](VRageMath.Vector3.Multiply)|Multiplies a vector by a scalar value.|
|[Divide(Vector3, Vector3)](VRageMath.Vector3.Divide)|Divides the components of a vector by the components of another vector.|
|[Divide(ref Vector3, ref Vector3, ref Vector3)](VRageMath.Vector3.Divide)|Divides the components of a vector by the components of another vector.|
|[Divide(Vector3, float)](VRageMath.Vector3.Divide)|Divides a vector by a scalar value.|
|[Divide(ref Vector3, float, ref Vector3)](VRageMath.Vector3.Divide)|Divides a vector by a scalar value.|
|[CalculatePerpendicularVector(Vector3)](VRageMath.Vector3.CalculatePerpendicularVector)||
|[CalculatePerpendicularVector(ref Vector3)](VRageMath.Vector3.CalculatePerpendicularVector)||
|[GetAzimuthAndElevation(Vector3, ref float, ref float)](VRageMath.Vector3.GetAzimuthAndElevation)||
|[CreateFromAzimuthAndElevation(float, float, ref Vector3)](VRageMath.Vector3.CreateFromAzimuthAndElevation)||
|[VolumeInt(float)](VRageMath.Vector3.VolumeInt)||
|[IsInsideInclusive(ref Vector3, ref Vector3)](VRageMath.Vector3.IsInsideInclusive)||
|[SwapYZCoordinates(Vector3)](VRageMath.Vector3.SwapYZCoordinates)||
|[GetDim(int)](VRageMath.Vector3.GetDim)||
|[SetDim(int, float)](VRageMath.Vector3.SetDim)||
|[Ceiling(Vector3)](VRageMath.Vector3.Ceiling)||
|[Floor(Vector3)](VRageMath.Vector3.Floor)||
|[Round(Vector3)](VRageMath.Vector3.Round)||
|[Round(Vector3, int)](VRageMath.Vector3.Round)||
|[ProjectOnPlane(ref Vector3, ref Vector3)](VRageMath.Vector3.ProjectOnPlane)|Projects given vector on plane specified by it's normal.|
|[ProjectOnVector(ref Vector3, ref Vector3)](VRageMath.Vector3.ProjectOnVector)|Projects vector on another vector resulting in new vector in guided vector's direction with different length.|
|[IsZero(ref Vector3)](VRageMath.Vector3.IsZero)||
|[Divide(float)](VRageMath.Vector3.Divide)||
|[Multiply(float)](VRageMath.Vector3.Multiply)||
|[Add(Vector3)](VRageMath.Vector3.Add)||
|[Abs(Vector3)](VRageMath.Vector3.Abs)||
|[Sign(Vector3)](VRageMath.Vector3.Sign)||
|[Sign(Vector3, float)](VRageMath.Vector3.Sign)||
|[SignNonZero(Vector3)](VRageMath.Vector3.SignNonZero)|Returns per component sign, never returns zero. For zero component returns sign 1. Faster than Sign.|
|[Interpolate3(Vector3, Vector3, float)](VRageMath.Vector3.Interpolate3)||
|[IsValid()](VRageMath.Vector3.IsValid)||
|[AssertIsValid()](VRageMath.Vector3.AssertIsValid)||
|[IsUnit(ref Vector3)](VRageMath.Vector3.IsUnit)||
|[ArePerpendicular(ref Vector3, ref Vector3)](VRageMath.Vector3.ArePerpendicular)||
|[IsZero(Vector3)](VRageMath.Vector3.IsZero)||
|[IsZero(Vector3, float)](VRageMath.Vector3.IsZero)||
|[IsZeroVector(Vector3)](VRageMath.Vector3.IsZeroVector)||
|[IsZeroVector(Vector3, float)](VRageMath.Vector3.IsZeroVector)||
|[Step(Vector3)](VRageMath.Vector3.Step)||
|[ToString()](VRageMath.Vector3.ToString)|Retrieves a string representation of the current object.|
|[ToString(string)](VRageMath.Vector3.ToString)||
|[Equals(Vector3)](VRageMath.Vector3.Equals)|Determines whether the specified Object is equal to the Vector3.|
|[Equals(Vector3, float)](VRageMath.Vector3.Equals)||
|[Equals(object)](VRageMath.Vector3.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[GetHashCode()](VRageMath.Vector3.GetHashCode)||
|[GetHash()](VRageMath.Vector3.GetHash)|Gets the hash code of the vector object.|
|[Length()](VRageMath.Vector3.Length)|Calculates the length of the vector.|
|[LengthSquared()](VRageMath.Vector3.LengthSquared)|Calculates the length of the vector squared.|
|[Distance(Vector3, Vector3)](VRageMath.Vector3.Distance)|Calculates the distance between two vectors.|
|[Distance(ref Vector3, ref Vector3, ref float)](VRageMath.Vector3.Distance)|Calculates the distance between two vectors.|
|[DistanceSquared(Vector3, Vector3)](VRageMath.Vector3.DistanceSquared)|Calculates the distance between two vectors squared.|
|[DistanceSquared(ref Vector3, ref Vector3, ref float)](VRageMath.Vector3.DistanceSquared)|Calculates the distance between two vectors squared.|
|[RectangularDistance(Vector3, Vector3)](VRageMath.Vector3.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|[RectangularDistance(ref Vector3, ref Vector3)](VRageMath.Vector3.RectangularDistance)|Calculates rectangular distance (a.k.a. Manhattan distance or Chessboard distace) between two vectors.|
|[Dot(Vector3, Vector3)](VRageMath.Vector3.Dot)|Calculates the dot product of two vectors. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[Dot(ref Vector3, ref Vector3, ref float)](VRageMath.Vector3.Dot)|Calculates the dot product of two vectors and writes the result to a user-specified variable. If the two vectors are unit vectors, the dot product returns a floating point value between -1 and 1 that can be used to determine some properties of the angle between two vectors. For example, it can show whether the vectors are orthogonal, parallel, or have an acute or obtuse angle between them.|
|[Dot(Vector3)](VRageMath.Vector3.Dot)||
|[Dot(ref Vector3)](VRageMath.Vector3.Dot)||
|[Cross(Vector3)](VRageMath.Vector3.Cross)||
|[Normalize()](VRageMath.Vector3.Normalize)|Turns the current vector into a unit vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[Normalize(Vector3)](VRageMath.Vector3.Normalize)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[Normalize(Vector3D)](VRageMath.Vector3.Normalize)||
|[GetNormalized(ref Vector3)](VRageMath.Vector3.GetNormalized)||
|[Normalize(ref Vector3, ref Vector3)](VRageMath.Vector3.Normalize)|Creates a unit vector from the specified vector, writing the result to a user-specified variable. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[Cross(Vector3, Vector3)](VRageMath.Vector3.Cross)|Calculates the cross product of two vectors.|
|[Cross(ref Vector3, ref Vector3, ref Vector3)](VRageMath.Vector3.Cross)|Calculates the cross product of two vectors.|
|[Reflect(Vector3, Vector3)](VRageMath.Vector3.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|[Reflect(ref Vector3, ref Vector3, ref Vector3)](VRageMath.Vector3.Reflect)|Returns the reflection of a vector off a surface that has the specified normal. Reference page contains code sample.|
|[Reject(Vector3, Vector3)](VRageMath.Vector3.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|[Reject(ref Vector3, ref Vector3, ref Vector3)](VRageMath.Vector3.Reject)|Returns the rejection of vector from direction, i.e. projection of vector onto the plane defined by origin and direction|
|[Min()](VRageMath.Vector3.Min)|Returns the component of the vector that is smallest of all the three components.|
|[AbsMin()](VRageMath.Vector3.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|[Max()](VRageMath.Vector3.Max)|Returns the component of the vector that is largest of all the three components.|
|[MaxAbsComponent()](VRageMath.Vector3.MaxAbsComponent)|Keeps only component with maximal absolute, others are set to zero.|
|[AbsMax()](VRageMath.Vector3.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|[Min(Vector3, Vector3)](VRageMath.Vector3.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|[Min(ref Vector3, ref Vector3, ref Vector3)](VRageMath.Vector3.Min)|Returns a vector that contains the lowest value from each matching pair of components.|
|[Max(Vector3, Vector3)](VRageMath.Vector3.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|[Max(ref Vector3, ref Vector3, ref Vector3)](VRageMath.Vector3.Max)|Returns a vector that contains the highest value from each matching pair of components.|
|[MinMax(ref Vector3, ref Vector3)](VRageMath.Vector3.MinMax)|Separates minimal and maximal values of any two input vectors|
|[DominantAxisProjection(Vector3)](VRageMath.Vector3.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|[DominantAxisProjection(ref Vector3, ref Vector3)](VRageMath.Vector3.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved into a user-specified variable.|
|[Clamp(Vector3, Vector3, Vector3)](VRageMath.Vector3.Clamp)|Restricts a value to be within a specified range.|
|[Clamp(ref Vector3, ref Vector3, ref Vector3, ref Vector3)](VRageMath.Vector3.Clamp)|Restricts a value to be within a specified range.|
|[ClampToSphere(Vector3, float)](VRageMath.Vector3.ClampToSphere)||
|[ClampToSphere(ref Vector3, float)](VRageMath.Vector3.ClampToSphere)||
|[Lerp(Vector3, Vector3, float)](VRageMath.Vector3.Lerp)|Performs a linear interpolation between two vectors.|
|[Lerp(ref Vector3, ref Vector3, float, ref Vector3)](VRageMath.Vector3.Lerp)|Performs a linear interpolation between two vectors.|
|[Barycentric(Vector3, Vector3, Vector3, float, float)](VRageMath.Vector3.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in Barycentric coordinates relative to a 3D triangle.|
|[Barycentric(ref Vector3, ref Vector3, ref Vector3, float, float, ref Vector3)](VRageMath.Vector3.Barycentric)|Returns a Vector3 containing the 3D Cartesian coordinates of a point specified in barycentric (areal) coordinates relative to a 3D triangle.|
|[Barycentric(Vector3, Vector3, Vector3, Vector3, ref float, ref float, ref float)](VRageMath.Vector3.Barycentric)|Compute barycentric coordinates (u, v, w) for point p with respect to triangle (a, b, c) From : Real-Time Collision Detection, Christer Ericson, CRC Press 3.4 Barycentric Coordinates|
|[TriangleArea(Vector3, Vector3, Vector3)](VRageMath.Vector3.TriangleArea)||
|[TriangleArea(ref Vector3, ref Vector3, ref Vector3)](VRageMath.Vector3.TriangleArea)||
|[SmoothStep(Vector3, Vector3, float)](VRageMath.Vector3.SmoothStep)|Interpolates between two values using a cubic equation.|
|[SmoothStep(ref Vector3, ref Vector3, float, ref Vector3)](VRageMath.Vector3.SmoothStep)|Interpolates between two values using a cubic equation.|
|[CatmullRom(Vector3, Vector3, Vector3, Vector3, float)](VRageMath.Vector3.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|[CatmullRom(ref Vector3, ref Vector3, ref Vector3, ref Vector3, float, ref Vector3)](VRageMath.Vector3.CatmullRom)|Performs a Catmull-Rom interpolation using the specified positions.|
|[Hermite(Vector3, Vector3, Vector3, Vector3, float)](VRageMath.Vector3.Hermite)|Performs a Hermite spline interpolation.|
|[Hermite(ref Vector3, ref Vector3, ref Vector3, ref Vector3, float, ref Vector3)](VRageMath.Vector3.Hermite)|Performs a Hermite spline interpolation.|
|[Transform(Vector3, Matrix)](VRageMath.Vector3.Transform)|Transforms a 3D vector by the given matrix.|
|[Transform(Vector3, MatrixD)](VRageMath.Vector3.Transform)|Transforms a 3D vector by the given matrix.|
|[Transform(Vector3, ref Matrix)](VRageMath.Vector3.Transform)||
|[Transform(ref Vector3, ref Matrix, ref Vector3)](VRageMath.Vector3.Transform)|Transforms a Vector3 by the given Matrix.|
|[Transform(ref Vector3, ref MatrixI, ref Vector3)](VRageMath.Vector3.Transform)||
|[TransformProjection(ref Vector3, ref Matrix, ref Vector3)](VRageMath.Vector3.TransformProjection)|Transforms a Vector3 by the given projection matrix (both ortho and perspective are supported)|
|[TransformNoProjection(ref Vector3, ref Matrix, ref Vector3)](VRageMath.Vector3.TransformNoProjection)||
|[RotateAndScale(ref Vector3, ref Matrix, ref Vector3)](VRageMath.Vector3.RotateAndScale)||
|[RotateAndScale(Vector3, Matrix)](VRageMath.Vector3.RotateAndScale)||
|[TransformNormal(Vector3, Matrix)](VRageMath.Vector3.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|[TransformNormal(Vector3, MatrixD)](VRageMath.Vector3.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|[TransformNormal(Vector3D, Matrix)](VRageMath.Vector3.TransformNormal)|Transforms a 3D vector normal by a matrix.|
|[TransformNormal(ref Vector3, ref Matrix, ref Vector3)](VRageMath.Vector3.TransformNormal)|Transforms a vector normal by a matrix.|
|[TransformNormal(ref Vector3, ref MatrixD, ref Vector3)](VRageMath.Vector3.TransformNormal)||
|[TransformNormal(ref Vector3, ref MatrixI, ref Vector3)](VRageMath.Vector3.TransformNormal)||
|[TransformNormal(Vector3, MyBlockOrientation)](VRageMath.Vector3.TransformNormal)||
|[TransformNormal(ref Vector3, MyBlockOrientation, ref Vector3)](VRageMath.Vector3.TransformNormal)||
|[TransformNormal(Vector3, ref Matrix)](VRageMath.Vector3.TransformNormal)||
|[Transform(Vector3, Quaternion)](VRageMath.Vector3.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|[Transform(ref Vector3, ref Quaternion, ref Vector3)](VRageMath.Vector3.Transform)|Transforms a Vector3 by a specified Quaternion rotation.|
|[Transform(Vector3[], ref Matrix, Vector3[])](VRageMath.Vector3.Transform)|Transforms a source array of Vector3s by a specified Matrix and writes the results to an existing destination array.|
|[Transform(Vector3[], int, ref Matrix, Vector3[], int, int)](VRageMath.Vector3.Transform)|Applies a specified transform Matrix to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|[TransformNormal(Vector3[], ref Matrix, Vector3[])](VRageMath.Vector3.TransformNormal)|Transforms an array of 3D vector normals by a specified Matrix.|
|[TransformNormal(Vector3[], int, ref Matrix, Vector3[], int, int)](VRageMath.Vector3.TransformNormal)|Transforms a specified range in an array of 3D vector normals by a specified Matrix and writes the results to a specified range in a destination array.|
|[Transform(Vector3[], ref Quaternion, Vector3[])](VRageMath.Vector3.Transform)|Transforms a source array of Vector3s by a specified Quaternion rotation and writes the results to an existing destination array.|
|[Transform(Vector3[], int, ref Quaternion, Vector3[], int, int)](VRageMath.Vector3.Transform)|Applies a specified Quaternion rotation to a specified range of an array of Vector3s and writes the results into a specified range of a destination array.|
|[Negate(Vector3)](VRageMath.Vector3.Negate)|Returns a vector pointing in the opposite direction.|

