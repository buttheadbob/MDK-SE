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
|\\[static Vector3I Backward](VRageMath.Vector3I.Backward)||
|\\[static EqualityComparer Comparer](VRageMath.Vector3I.Comparer)||
|\\[static Vector3I Down](VRageMath.Vector3I.Down)||
|\\[static Vector3I Forward](VRageMath.Vector3I.Forward)||
|\\[static Vector3I Left](VRageMath.Vector3I.Left)||
|\\[static Vector3I MaxValue](VRageMath.Vector3I.MaxValue)||
|\\[static Vector3I MinValue](VRageMath.Vector3I.MinValue)||
|\\[static Vector3I One](VRageMath.Vector3I.One)||
|\\[static Vector3I Right](VRageMath.Vector3I.Right)||
|\\[static Vector3I UnitX](VRageMath.Vector3I.UnitX)||
|\\[static Vector3I UnitY](VRageMath.Vector3I.UnitY)||
|\\[static Vector3I UnitZ](VRageMath.Vector3I.UnitZ)||
|\\[static Vector3I Up](VRageMath.Vector3I.Up)||
|\\[static Vector3I Zero](VRageMath.Vector3I.Zero)||
|\\[int X](VRageMath.Vector3I.X)||
|\\[int Y](VRageMath.Vector3I.Y)||
|\\[int Z](VRageMath.Vector3I.Z)||

#### Properties

|Member|Description|
|---|---|
|\\[bool IsPowerOfTwo { get; }](VRageMath.Vector3I.IsPowerOfTwo)||
|\\[int Item { get; set; }](VRageMath.Vector3I.Item)||
|\\[int Size { get; }](VRageMath.Vector3I.Size)|How many cubes are in block with this size|
|\\[long SizeLong { get; }](VRageMath.Vector3I.SizeLong)||

#### Constructors

|Member|Description|
|---|---|
|\\[Vector3I(int)](VRageMath.Vector3I..ctor)||
|\\[Vector3I(int, int, int)](VRageMath.Vector3I..ctor)||
|\\[Vector3I(Vector2I, int)](VRageMath.Vector3I..ctor)||
|\\[Vector3I(Vector3)](VRageMath.Vector3I..ctor)||
|\\[Vector3I(Vector3D)](VRageMath.Vector3I..ctor)||
|\\[Vector3I(Vector3S)](VRageMath.Vector3I..ctor)||
|\\[Vector3I(float, float, float)](VRageMath.Vector3I..ctor)||
|\\[Vector3I(Byte\\[], int)](VRageMath.Vector3I..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\[static Vector3I Abs(Vector3I)](VRageMath.Vector3I.Abs)||
|\\[static void Abs(ref Vector3I, out Vector3I)](VRageMath.Vector3I.Abs)||
|\\[static bool BoxContains(Vector3I, Vector3I, Vector3I)](VRageMath.Vector3I.BoxContains)||
|\\[static bool BoxContains(ref Vector3I, ref Vector3I, ref Vector3I)](VRageMath.Vector3I.BoxContains)||
|\\[static bool BoxIntersects(Vector3I, Vector3I, Vector3I, Vector3I)](VRageMath.Vector3I.BoxIntersects)||
|\\[static bool BoxIntersects(ref Vector3I, ref Vector3I, ref Vector3I, ref Vector3I)](VRageMath.Vector3I.BoxIntersects)||
|\\[static Vector3I Ceiling(Vector3)](VRageMath.Vector3I.Ceiling)||
|\\[static Vector3I Ceiling(Vector3D)](VRageMath.Vector3I.Ceiling)||
|\\[static Vector3I Clamp(Vector3I, Vector3I, Vector3I)](VRageMath.Vector3I.Clamp)||
|\\[static void Clamp(ref Vector3I, ref Vector3I, ref Vector3I, out Vector3I)](VRageMath.Vector3I.Clamp)||
|\\[static void Cross(ref Vector3I, ref Vector3I, out Vector3I)](VRageMath.Vector3I.Cross)|Calculates the cross product of two vectors.|
|\\[static int DistanceManhattan(Vector3I, Vector3I)](VRageMath.Vector3I.DistanceManhattan)|Manhattan distance (cube distance) X + Y + Z of Abs(first - second)|
|\\[static Vector3I DominantAxisProjection(Vector3I)](VRageMath.Vector3I.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|\\[static void DominantAxisProjection(ref Vector3I, out Vector3I)](VRageMath.Vector3I.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved into a user-specified variable.|
|\\[static int Dot(Vector3I, Vector3I)](VRageMath.Vector3I.Dot)||
|\\[static int Dot(ref Vector3I, ref Vector3I)](VRageMath.Vector3I.Dot)||
|\\[static void Dot(ref Vector3I, ref Vector3I, out int)](VRageMath.Vector3I.Dot)||
|\\[static IEnumerable\\<Vector3I> EnumerateRange(Vector3I, Vector3I)](VRageMath.Vector3I.EnumerateRange)|Enumerate all values in a integer interval (a cuboid). This method is an allocating version of the Vector3I_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.|
|\\[static Vector3I Floor(Vector3)](VRageMath.Vector3I.Floor)||
|\\[static Vector3I Floor(Vector3D)](VRageMath.Vector3I.Floor)||
|\\[static void Floor(ref Vector3, out Vector3I)](VRageMath.Vector3I.Floor)||
|\\[static void Floor(ref Vector3D, out Vector3I)](VRageMath.Vector3I.Floor)||
|\\[static CubeFace GetDominantDirection(Vector3I)](VRageMath.Vector3I.GetDominantDirection)||
|\\[static Vector3I GetDominantDirectionVector(Vector3I)](VRageMath.Vector3I.GetDominantDirectionVector)||
|\\[static Vector3I Max(Vector3I, Vector3I)](VRageMath.Vector3I.Max)||
|\\[static void Max(ref Vector3I, ref Vector3I, out Vector3I)](VRageMath.Vector3I.Max)||
|\\[static Vector3I Min(Vector3I, Vector3I)](VRageMath.Vector3I.Min)||
|\\[static void Min(ref Vector3I, ref Vector3I, out Vector3I)](VRageMath.Vector3I.Min)||
|\\[static void MinMax(ref Vector3I, ref Vector3I)](VRageMath.Vector3I.MinMax)|Separates minimal and maximal values of any two input vectors|
|\\[static Vector3I Round(Vector3)](VRageMath.Vector3I.Round)||
|\\[static Vector3I Round(Vector3D)](VRageMath.Vector3I.Round)||
|\\[static void Round(ref Vector3, out Vector3I)](VRageMath.Vector3I.Round)||
|\\[static void Round(ref Vector3D, out Vector3I)](VRageMath.Vector3I.Round)||
|\\[static Vector3I Shift(Vector3I)](VRageMath.Vector3I.Shift)||
|\\[static Vector3I Sign(Vector3)](VRageMath.Vector3I.Sign)||
|\\[static Vector3I Sign(Vector3I)](VRageMath.Vector3I.Sign)||
|\\[static void Transform(ref Vector3I, ref Matrix, out Vector3I)](VRageMath.Vector3I.Transform)|Transforms a Vector3I by the given Matrix.|
|\\[static void Transform(ref Vector3I, ref Quaternion, out Vector3I)](VRageMath.Vector3I.Transform)||
|\\[static Vector3I Transform(Vector3I, Quaternion)](VRageMath.Vector3I.Transform)||
|\\[static void Transform(ref Vector3I, ref MatrixI, out Vector3I)](VRageMath.Vector3I.Transform)||
|\\[static Vector3I Transform(Vector3I, MatrixI)](VRageMath.Vector3I.Transform)||
|\\[static Vector3I Transform(Vector3I, ref MatrixI)](VRageMath.Vector3I.Transform)||
|\\[static Vector3I TransformNormal(Vector3I, ref MatrixI)](VRageMath.Vector3I.TransformNormal)||
|\\[static void TransformNormal(ref Vector3I, ref Matrix, out Vector3I)](VRageMath.Vector3I.TransformNormal)|Transforms a vector normal by a matrix.|
|\\[static void TransformNormal(ref Vector3I, ref MatrixI, out Vector3I)](VRageMath.Vector3I.TransformNormal)||
|\\[static Vector3I Trunc(Vector3)](VRageMath.Vector3I.Trunc)||
|\\[static bool TryParseFromString(string, out Vector3I)](VRageMath.Vector3I.TryParseFromString)||
|\\[int AbsMax()](VRageMath.Vector3I.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|\\[int AbsMin()](VRageMath.Vector3I.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|\\[int AxisValue(Axis)](VRageMath.Vector3I.AxisValue)||
|\\[int CompareTo(Vector3I)](VRageMath.Vector3I.CompareTo)||
|\\[int Dot(ref Vector3I)](VRageMath.Vector3I.Dot)||
|\\[bool Equals(Vector3I)](VRageMath.Vector3I.Equals)||
|\\[bool Equals(object)](VRageMath.Vector3I.Equals)||
|\\[int GetHashCode()](VRageMath.Vector3I.GetHashCode)||
|\\[bool IsAxisAligned()](VRageMath.Vector3I.IsAxisAligned)||
|\\[bool IsInside(ref Vector3I, ref Vector3I)](VRageMath.Vector3I.IsInside)||
|\\[bool IsInside(Vector3I, Vector3I)](VRageMath.Vector3I.IsInside)||
|\\[bool IsInsideInclusiveEnd(ref Vector3I, ref Vector3I)](VRageMath.Vector3I.IsInsideInclusiveEnd)||
|\\[bool IsInsideInclusiveEnd(Vector3I, Vector3I)](VRageMath.Vector3I.IsInsideInclusiveEnd)||
|\\[int Length()](VRageMath.Vector3I.Length)||
|\\[int RectangularDistance(Vector3I)](VRageMath.Vector3I.RectangularDistance)|Calculates rectangular distance. It's how many sectors you have to travel to get to other sector from current sector.|
|\\[int RectangularLength()](VRageMath.Vector3I.RectangularLength)|Calculates rectangular distance of this vector, interpreted as a point, from the origin.|
|\\[void ToBytes(List\\<byte>)](VRageMath.Vector3I.ToBytes)||
|\\[string ToString()](VRageMath.Vector3I.ToString)||
|\\[int Volume()](VRageMath.Vector3I.Volume)||

