← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### Vector3I Struct

```csharp
public struct Vector3I: IEquatable<Vector3I>, IComparable<Vector3I>
```

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IComparable<Vector3I>](https://docs.microsoft.com/en-us/dotnet/api/System.IComparable-1?view=netframework-4.6)  
* [IEquatable<Vector3I>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\\%1static Vector3I Backward](VRageMath.Vector3I.Backward)||
|\\%1static EqualityComparer Comparer](VRageMath.Vector3I.Comparer)||
|\\%1static Vector3I Down](VRageMath.Vector3I.Down)||
|\\%1static Vector3I Forward](VRageMath.Vector3I.Forward)||
|\\%1static Vector3I Left](VRageMath.Vector3I.Left)||
|\\%1static Vector3I MaxValue](VRageMath.Vector3I.MaxValue)||
|\\%1static Vector3I MinValue](VRageMath.Vector3I.MinValue)||
|\\%1static Vector3I One](VRageMath.Vector3I.One)||
|\\%1static Vector3I Right](VRageMath.Vector3I.Right)||
|\\%1static Vector3I UnitX](VRageMath.Vector3I.UnitX)||
|\\%1static Vector3I UnitY](VRageMath.Vector3I.UnitY)||
|\\%1static Vector3I UnitZ](VRageMath.Vector3I.UnitZ)||
|\\%1static Vector3I Up](VRageMath.Vector3I.Up)||
|\\%1static Vector3I Zero](VRageMath.Vector3I.Zero)||
|\\%1int X](VRageMath.Vector3I.X)||
|\\%1int Y](VRageMath.Vector3I.Y)||
|\\%1int Z](VRageMath.Vector3I.Z)||

#### Properties

|Member|Description|
|---|---|
|\\%1bool IsPowerOfTwo { get; }](VRageMath.Vector3I.IsPowerOfTwo)||
|\\%1int Item { get; set; }](VRageMath.Vector3I.Item)||
|\\%1int Size { get; }](VRageMath.Vector3I.Size)|How many cubes are in block with this size|
|\\%1long SizeLong { get; }](VRageMath.Vector3I.SizeLong)||

#### Constructors

|Member|Description|
|---|---|
|\\%1Vector3I(int)](VRageMath.Vector3I..ctor)||
|\\%1Vector3I(int, int, int)](VRageMath.Vector3I..ctor)||
|\\%1Vector3I(Vector2I, int)](VRageMath.Vector3I..ctor)||
|\\%1Vector3I(Vector3)](VRageMath.Vector3I..ctor)||
|\\%1Vector3I(Vector3D)](VRageMath.Vector3I..ctor)||
|\\%1Vector3I(Vector3S)](VRageMath.Vector3I..ctor)||
|\\%1Vector3I(float, float, float)](VRageMath.Vector3I..ctor)||
|\\%1Vector3I(Byte\\%1], int)](VRageMath.Vector3I..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\%1static Vector3I Abs(Vector3I)](VRageMath.Vector3I.Abs)||
|\\%1static void Abs(ref Vector3I, out Vector3I)](VRageMath.Vector3I.Abs)||
|\\%1static bool BoxContains(Vector3I, Vector3I, Vector3I)](VRageMath.Vector3I.BoxContains)||
|\\%1static bool BoxContains(ref Vector3I, ref Vector3I, ref Vector3I)](VRageMath.Vector3I.BoxContains)||
|\\%1static bool BoxIntersects(Vector3I, Vector3I, Vector3I, Vector3I)](VRageMath.Vector3I.BoxIntersects)||
|\\%1static bool BoxIntersects(ref Vector3I, ref Vector3I, ref Vector3I, ref Vector3I)](VRageMath.Vector3I.BoxIntersects)||
|\\%1static Vector3I Ceiling(Vector3)](VRageMath.Vector3I.Ceiling)||
|\\%1static Vector3I Ceiling(Vector3D)](VRageMath.Vector3I.Ceiling)||
|\\%1static Vector3I Clamp(Vector3I, Vector3I, Vector3I)](VRageMath.Vector3I.Clamp)||
|\\%1static void Clamp(ref Vector3I, ref Vector3I, ref Vector3I, out Vector3I)](VRageMath.Vector3I.Clamp)||
|\\%1static void Cross(ref Vector3I, ref Vector3I, out Vector3I)](VRageMath.Vector3I.Cross)|Calculates the cross product of two vectors.|
|\\%1static int DistanceManhattan(Vector3I, Vector3I)](VRageMath.Vector3I.DistanceManhattan)|Manhattan distance (cube distance) X + Y + Z of Abs(first - second)|
|\\%1static Vector3I DominantAxisProjection(Vector3I)](VRageMath.Vector3I.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|\\%1static void DominantAxisProjection(ref Vector3I, out Vector3I)](VRageMath.Vector3I.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved into a user-specified variable.|
|\\%1static int Dot(Vector3I, Vector3I)](VRageMath.Vector3I.Dot)||
|\\%1static int Dot(ref Vector3I, ref Vector3I)](VRageMath.Vector3I.Dot)||
|\\%1static void Dot(ref Vector3I, ref Vector3I, out int)](VRageMath.Vector3I.Dot)||
|\\%1static IEnumerable\\%1Vector3I> EnumerateRange(Vector3I, Vector3I)](VRageMath.Vector3I.EnumerateRange)|Enumerate all values in a integer interval (a cuboid). This method is an allocating version of the Vector3I_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.|
|\\%1static Vector3I Floor(Vector3)](VRageMath.Vector3I.Floor)||
|\\%1static Vector3I Floor(Vector3D)](VRageMath.Vector3I.Floor)||
|\\%1static void Floor(ref Vector3, out Vector3I)](VRageMath.Vector3I.Floor)||
|\\%1static void Floor(ref Vector3D, out Vector3I)](VRageMath.Vector3I.Floor)||
|\\%1static CubeFace GetDominantDirection(Vector3I)](VRageMath.Vector3I.GetDominantDirection)||
|\\%1static Vector3I GetDominantDirectionVector(Vector3I)](VRageMath.Vector3I.GetDominantDirectionVector)||
|\\%1static Vector3I Max(Vector3I, Vector3I)](VRageMath.Vector3I.Max)||
|\\%1static void Max(ref Vector3I, ref Vector3I, out Vector3I)](VRageMath.Vector3I.Max)||
|\\%1static Vector3I Min(Vector3I, Vector3I)](VRageMath.Vector3I.Min)||
|\\%1static void Min(ref Vector3I, ref Vector3I, out Vector3I)](VRageMath.Vector3I.Min)||
|\\%1static void MinMax(ref Vector3I, ref Vector3I)](VRageMath.Vector3I.MinMax)|Separates minimal and maximal values of any two input vectors|
|\\%1static Vector3I Round(Vector3)](VRageMath.Vector3I.Round)||
|\\%1static Vector3I Round(Vector3D)](VRageMath.Vector3I.Round)||
|\\%1static void Round(ref Vector3, out Vector3I)](VRageMath.Vector3I.Round)||
|\\%1static void Round(ref Vector3D, out Vector3I)](VRageMath.Vector3I.Round)||
|\\%1static Vector3I Shift(Vector3I)](VRageMath.Vector3I.Shift)||
|\\%1static Vector3I Sign(Vector3)](VRageMath.Vector3I.Sign)||
|\\%1static Vector3I Sign(Vector3I)](VRageMath.Vector3I.Sign)||
|\\%1static void Transform(ref Vector3I, ref Matrix, out Vector3I)](VRageMath.Vector3I.Transform)|Transforms a Vector3I by the given Matrix.|
|\\%1static void Transform(ref Vector3I, ref Quaternion, out Vector3I)](VRageMath.Vector3I.Transform)||
|\\%1static Vector3I Transform(Vector3I, Quaternion)](VRageMath.Vector3I.Transform)||
|\\%1static void Transform(ref Vector3I, ref MatrixI, out Vector3I)](VRageMath.Vector3I.Transform)||
|\\%1static Vector3I Transform(Vector3I, MatrixI)](VRageMath.Vector3I.Transform)||
|\\%1static Vector3I Transform(Vector3I, ref MatrixI)](VRageMath.Vector3I.Transform)||
|\\%1static Vector3I TransformNormal(Vector3I, ref MatrixI)](VRageMath.Vector3I.TransformNormal)||
|\\%1static void TransformNormal(ref Vector3I, ref Matrix, out Vector3I)](VRageMath.Vector3I.TransformNormal)|Transforms a vector normal by a matrix.|
|\\%1static void TransformNormal(ref Vector3I, ref MatrixI, out Vector3I)](VRageMath.Vector3I.TransformNormal)||
|\\%1static Vector3I Trunc(Vector3)](VRageMath.Vector3I.Trunc)||
|\\%1static bool TryParseFromString(string, out Vector3I)](VRageMath.Vector3I.TryParseFromString)||
|\\%1int AbsMax()](VRageMath.Vector3I.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|\\%1int AbsMin()](VRageMath.Vector3I.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|\\%1int AxisValue(Axis)](VRageMath.Vector3I.AxisValue)||
|\\%1int CompareTo(Vector3I)](VRageMath.Vector3I.CompareTo)||
|\\%1int Dot(ref Vector3I)](VRageMath.Vector3I.Dot)||
|\\%1bool Equals(Vector3I)](VRageMath.Vector3I.Equals)||
|\\%1bool Equals(object)](VRageMath.Vector3I.Equals)||
|\\%1int GetHashCode()](VRageMath.Vector3I.GetHashCode)||
|\\%1bool IsAxisAligned()](VRageMath.Vector3I.IsAxisAligned)||
|\\%1bool IsInside(ref Vector3I, ref Vector3I)](VRageMath.Vector3I.IsInside)||
|\\%1bool IsInside(Vector3I, Vector3I)](VRageMath.Vector3I.IsInside)||
|\\%1bool IsInsideInclusiveEnd(ref Vector3I, ref Vector3I)](VRageMath.Vector3I.IsInsideInclusiveEnd)||
|\\%1bool IsInsideInclusiveEnd(Vector3I, Vector3I)](VRageMath.Vector3I.IsInsideInclusiveEnd)||
|\\%1int Length()](VRageMath.Vector3I.Length)||
|\\%1int RectangularDistance(Vector3I)](VRageMath.Vector3I.RectangularDistance)|Calculates rectangular distance. It's how many sectors you have to travel to get to other sector from current sector.|
|\\%1int RectangularLength()](VRageMath.Vector3I.RectangularLength)|Calculates rectangular distance of this vector, interpreted as a point, from the origin.|
|\\%1void ToBytes(List\\%1byte>)](VRageMath.Vector3I.ToBytes)||
|\\%1string ToString()](VRageMath.Vector3I.ToString)||
|\\%1int Volume()](VRageMath.Vector3I.Volume)||

