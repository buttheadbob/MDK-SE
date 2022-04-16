← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### Vector3L Struct

```csharp
public struct Vector3L: IEquatable<Vector3L>, IComparable<Vector3L>
```

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IComparable<Vector3L>](https://docs.microsoft.com/en-us/dotnet/api/System.IComparable-1?view=netframework-4.6)  
* [IEquatable<Vector3L>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|\\$1static Vector3L Backward](VRageMath.Vector3L.Backward)||
|\\$1static EqualityComparer Comparer](VRageMath.Vector3L.Comparer)||
|\\$1static Vector3L Down](VRageMath.Vector3L.Down)||
|\\$1static Vector3L Forward](VRageMath.Vector3L.Forward)||
|\\$1static Vector3L Left](VRageMath.Vector3L.Left)||
|\\$1static Vector3L MaxValue](VRageMath.Vector3L.MaxValue)||
|\\$1static Vector3L MinValue](VRageMath.Vector3L.MinValue)||
|\\$1static Vector3L One](VRageMath.Vector3L.One)||
|\\$1static Vector3L Right](VRageMath.Vector3L.Right)||
|\\$1static Vector3L UnitX](VRageMath.Vector3L.UnitX)||
|\\$1static Vector3L UnitY](VRageMath.Vector3L.UnitY)||
|\\$1static Vector3L UnitZ](VRageMath.Vector3L.UnitZ)||
|\\$1static Vector3L Up](VRageMath.Vector3L.Up)||
|\\$1static Vector3L Zero](VRageMath.Vector3L.Zero)||
|\\$1long X](VRageMath.Vector3L.X)||
|\\$1long Y](VRageMath.Vector3L.Y)||
|\\$1long Z](VRageMath.Vector3L.Z)||

#### Properties

|Member|Description|
|---|---|
|\\$1long Item { get; set; }](VRageMath.Vector3L.Item)||
|\\$1long Size { get; }](VRageMath.Vector3L.Size)|How many cubes are in block with this size|
|\\$1long SizeLong { get; }](VRageMath.Vector3L.SizeLong)||

#### Constructors

|Member|Description|
|---|---|
|\\$1Vector3L(long)](VRageMath.Vector3L..ctor)||
|\\$1Vector3L(long, long, long)](VRageMath.Vector3L..ctor)||
|\\$1Vector3L(Vector3)](VRageMath.Vector3L..ctor)||
|\\$1Vector3L(Vector3D)](VRageMath.Vector3L..ctor)||
|\\$1Vector3L(Vector3S)](VRageMath.Vector3L..ctor)||
|\\$1Vector3L(float, float, float)](VRageMath.Vector3L..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\$1static Vector3L Abs(Vector3L)](VRageMath.Vector3L.Abs)||
|\\$1static void Abs(ref Vector3L, out Vector3L)](VRageMath.Vector3L.Abs)||
|\\$1static bool BoxContains(Vector3L, Vector3L, Vector3L)](VRageMath.Vector3L.BoxContains)||
|\\$1static bool BoxContains(ref Vector3L, ref Vector3L, ref Vector3L)](VRageMath.Vector3L.BoxContains)||
|\\$1static bool Boxlongersects(Vector3L, Vector3L, Vector3L, Vector3L)](VRageMath.Vector3L.Boxlongersects)||
|\\$1static bool Boxlongersects(ref Vector3L, ref Vector3L, ref Vector3L, ref Vector3L)](VRageMath.Vector3L.Boxlongersects)||
|\\$1static Vector3L Ceiling(Vector3)](VRageMath.Vector3L.Ceiling)||
|\\$1static Vector3L Clamp(Vector3L, Vector3L, Vector3L)](VRageMath.Vector3L.Clamp)||
|\\$1static void Clamp(ref Vector3L, ref Vector3L, ref Vector3L, out Vector3L)](VRageMath.Vector3L.Clamp)||
|\\$1static void Cross(ref Vector3L, ref Vector3L, out Vector3L)](VRageMath.Vector3L.Cross)|Calculates the cross product of two vectors.|
|\\$1static long DistanceManhattan(Vector3L, Vector3L)](VRageMath.Vector3L.DistanceManhattan)|Manhattan distance (cube distance) X + Y + Z of Abs(first - second)|
|\\$1static Vector3L DominantAxisProjection(Vector3L)](VRageMath.Vector3L.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|\\$1static void DominantAxisProjection(ref Vector3L, out Vector3L)](VRageMath.Vector3L.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved longo a user-specified variable.|
|\\$1static long Dot(Vector3L, Vector3L)](VRageMath.Vector3L.Dot)||
|\\$1static long Dot(ref Vector3L, ref Vector3L)](VRageMath.Vector3L.Dot)||
|\\$1static void Dot(ref Vector3L, ref Vector3L, out long)](VRageMath.Vector3L.Dot)||
|\\$1static IEnumerable\\$1Vector3L> EnumerateRange(Vector3L, Vector3L)](VRageMath.Vector3L.EnumerateRange)|Enumerate all values in a longeger longerval (a cuboid). This method is an allocating version of the Vector3L_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.|
|\\$1static Vector3L Floor(Vector3)](VRageMath.Vector3L.Floor)||
|\\$1static Vector3L Floor(Vector3D)](VRageMath.Vector3L.Floor)||
|\\$1static void Floor(ref Vector3, out Vector3L)](VRageMath.Vector3L.Floor)||
|\\$1static void Floor(ref Vector3D, out Vector3L)](VRageMath.Vector3L.Floor)||
|\\$1static CubeFace GetDominantDirection(Vector3L)](VRageMath.Vector3L.GetDominantDirection)||
|\\$1static Vector3L GetDominantDirectionVector(Vector3L)](VRageMath.Vector3L.GetDominantDirectionVector)||
|\\$1static Vector3L Max(Vector3L, Vector3L)](VRageMath.Vector3L.Max)||
|\\$1static void Max(ref Vector3L, ref Vector3L, out Vector3L)](VRageMath.Vector3L.Max)||
|\\$1static Vector3L Min(Vector3L, Vector3L)](VRageMath.Vector3L.Min)||
|\\$1static void Min(ref Vector3L, ref Vector3L, out Vector3L)](VRageMath.Vector3L.Min)||
|\\$1static Vector3L Round(Vector3)](VRageMath.Vector3L.Round)||
|\\$1static Vector3L Round(Vector3D)](VRageMath.Vector3L.Round)||
|\\$1static void Round(ref Vector3, out Vector3L)](VRageMath.Vector3L.Round)||
|\\$1static void Round(ref Vector3D, out Vector3L)](VRageMath.Vector3L.Round)||
|\\$1static Vector3L Shift(Vector3L)](VRageMath.Vector3L.Shift)||
|\\$1static Vector3L Sign(Vector3)](VRageMath.Vector3L.Sign)||
|\\$1static Vector3L Sign(Vector3L)](VRageMath.Vector3L.Sign)||
|\\$1static void Transform(ref Vector3L, ref Matrix, out Vector3L)](VRageMath.Vector3L.Transform)|Transforms a Vector3L by the given Matrix.|
|\\$1static void Transform(ref Vector3L, ref Quaternion, out Vector3L)](VRageMath.Vector3L.Transform)||
|\\$1static Vector3L Transform(Vector3L, Quaternion)](VRageMath.Vector3L.Transform)||
|\\$1static void TransformNormal(ref Vector3L, ref Matrix, out Vector3L)](VRageMath.Vector3L.TransformNormal)|Transforms a vector normal by a matrix.|
|\\$1static Vector3L Trunc(Vector3)](VRageMath.Vector3L.Trunc)||
|\\$1static bool TryParseFromString(string, out Vector3L)](VRageMath.Vector3L.TryParseFromString)||
|\\$1long AbsMax()](VRageMath.Vector3L.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|\\$1long AbsMin()](VRageMath.Vector3L.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|\\$1long AxisValue(Axis)](VRageMath.Vector3L.AxisValue)||
|\\$1int CompareTo(Vector3L)](VRageMath.Vector3L.CompareTo)||
|\\$1long Dot(ref Vector3L)](VRageMath.Vector3L.Dot)||
|\\$1bool Equals(Vector3L)](VRageMath.Vector3L.Equals)||
|\\$1bool Equals(object)](VRageMath.Vector3L.Equals)||
|\\$1int GetHashCode()](VRageMath.Vector3L.GetHashCode)||
|\\$1bool IsInside(ref Vector3L, ref Vector3L)](VRageMath.Vector3L.IsInside)||
|\\$1bool IsInside(Vector3L, Vector3L)](VRageMath.Vector3L.IsInside)||
|\\$1bool IsInsideInclusiveEnd(ref Vector3L, ref Vector3L)](VRageMath.Vector3L.IsInsideInclusiveEnd)||
|\\$1bool IsInsideInclusiveEnd(Vector3L, Vector3L)](VRageMath.Vector3L.IsInsideInclusiveEnd)||
|\\$1long Length()](VRageMath.Vector3L.Length)||
|\\$1long RectangularDistance(Vector3L)](VRageMath.Vector3L.RectangularDistance)|Calculates rectangular distance. It's how many sectors you have to travel to get to other sector from current sector.|
|\\$1long RectangularLength()](VRageMath.Vector3L.RectangularLength)|Calculates rectangular distance of this vector, longerpreted as a polong, from the origin.|
|\\$1void ToBytes(List\\$1byte>)](VRageMath.Vector3L.ToBytes)||
|\\$1string ToString()](VRageMath.Vector3L.ToString)||
|\\$1long Volume()](VRageMath.Vector3L.Volume)||

