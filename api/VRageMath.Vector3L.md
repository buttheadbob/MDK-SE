← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### Vector3L Struct

```csharp
public struct Vector3L: IEquatable<T>, IComparable<T>
```

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<T>](https://docs.microsoft.com/en-us/dotnet/api/system.iequatable?view=netframework-4.6)  
* [IComparable<T>](https://docs.microsoft.com/en-us/dotnet/api/system.icomparable?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[X](VRageMath.Vector3L.X)||
|[Y](VRageMath.Vector3L.Y)||
|[Z](VRageMath.Vector3L.Z)||
|[Comparer](VRageMath.Vector3L.Comparer)||
|[UnitX](VRageMath.Vector3L.UnitX)||
|[UnitY](VRageMath.Vector3L.UnitY)||
|[UnitZ](VRageMath.Vector3L.UnitZ)||
|[Zero](VRageMath.Vector3L.Zero)||
|[MaxValue](VRageMath.Vector3L.MaxValue)||
|[MinValue](VRageMath.Vector3L.MinValue)||
|[Up](VRageMath.Vector3L.Up)||
|[Down](VRageMath.Vector3L.Down)||
|[Right](VRageMath.Vector3L.Right)||
|[Left](VRageMath.Vector3L.Left)||
|[Forward](VRageMath.Vector3L.Forward)||
|[Backward](VRageMath.Vector3L.Backward)||
|[One](VRageMath.Vector3L.One)||

#### Properties

|Member|Description|
|---|---|
|[Item](VRageMath.Vector3L.Item)||
|[Size](VRageMath.Vector3L.Size)|How many cubes are in block with this size|
|[SizeLong](VRageMath.Vector3L.SizeLong)||

#### Methods

|Member|Description|
|---|---|
|[ToString()](VRageMath.Vector3L.ToString)||
|[Equals(Vector3L)](VRageMath.Vector3L.Equals)||
|[Equals(object)](VRageMath.Vector3L.Equals)||
|[GetHashCode()](VRageMath.Vector3L.GetHashCode)||
|[IsInsideInclusiveEnd(ref Vector3L, ref Vector3L)](VRageMath.Vector3L.IsInsideInclusiveEnd)||
|[IsInsideInclusiveEnd(Vector3L, Vector3L)](VRageMath.Vector3L.IsInsideInclusiveEnd)||
|[IsInside(ref Vector3L, ref Vector3L)](VRageMath.Vector3L.IsInside)||
|[IsInside(Vector3L, Vector3L)](VRageMath.Vector3L.IsInside)||
|[RectangularDistance(Vector3L)](VRageMath.Vector3L.RectangularDistance)|Calculates rectangular distance. It's how many sectors you have to travel to get to other sector from current sector.|
|[RectangularLength()](VRageMath.Vector3L.RectangularLength)|Calculates rectangular distance of this vector, longerpreted as a polong, from the origin.|
|[Length()](VRageMath.Vector3L.Length)||
|[Boxlongersects(Vector3L, Vector3L, Vector3L, Vector3L)](VRageMath.Vector3L.Boxlongersects)||
|[Boxlongersects(ref Vector3L, ref Vector3L, ref Vector3L, ref Vector3L)](VRageMath.Vector3L.Boxlongersects)||
|[BoxContains(Vector3L, Vector3L, Vector3L)](VRageMath.Vector3L.BoxContains)||
|[BoxContains(ref Vector3L, ref Vector3L, ref Vector3L)](VRageMath.Vector3L.BoxContains)||
|[Min(Vector3L, Vector3L)](VRageMath.Vector3L.Min)||
|[Min(ref Vector3L, ref Vector3L, ref Vector3L)](VRageMath.Vector3L.Min)||
|[AbsMin()](VRageMath.Vector3L.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|[Max(Vector3L, Vector3L)](VRageMath.Vector3L.Max)||
|[Max(ref Vector3L, ref Vector3L, ref Vector3L)](VRageMath.Vector3L.Max)||
|[AbsMax()](VRageMath.Vector3L.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|[AxisValue(Axis)](VRageMath.Vector3L.AxisValue)||
|[GetDominantDirection(Vector3L)](VRageMath.Vector3L.GetDominantDirection)||
|[GetDominantDirectionVector(Vector3L)](VRageMath.Vector3L.GetDominantDirectionVector)||
|[DominantAxisProjection(Vector3L)](VRageMath.Vector3L.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|[DominantAxisProjection(ref Vector3L, ref Vector3L)](VRageMath.Vector3L.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved longo a user-specified variable.|
|[Sign(Vector3)](VRageMath.Vector3L.Sign)||
|[Sign(Vector3L)](VRageMath.Vector3L.Sign)||
|[Floor(Vector3)](VRageMath.Vector3L.Floor)||
|[Floor(Vector3D)](VRageMath.Vector3L.Floor)||
|[Floor(ref Vector3, ref Vector3L)](VRageMath.Vector3L.Floor)||
|[Floor(ref Vector3D, ref Vector3L)](VRageMath.Vector3L.Floor)||
|[Ceiling(Vector3)](VRageMath.Vector3L.Ceiling)||
|[Trunc(Vector3)](VRageMath.Vector3L.Trunc)||
|[Shift(Vector3L)](VRageMath.Vector3L.Shift)||
|[Transform(ref Vector3L, ref Matrix, ref Vector3L)](VRageMath.Vector3L.Transform)|Transforms a Vector3L by the given Matrix.|
|[Transform(ref Vector3L, ref Quaternion, ref Vector3L)](VRageMath.Vector3L.Transform)||
|[Transform(Vector3L, Quaternion)](VRageMath.Vector3L.Transform)||
|[TransformNormal(ref Vector3L, ref Matrix, ref Vector3L)](VRageMath.Vector3L.TransformNormal)|Transforms a vector normal by a matrix.|
|[Cross(ref Vector3L, ref Vector3L, ref Vector3L)](VRageMath.Vector3L.Cross)|Calculates the cross product of two vectors.|
|[CompareTo(Vector3L)](VRageMath.Vector3L.CompareTo)||
|[Abs(Vector3L)](VRageMath.Vector3L.Abs)||
|[Abs(ref Vector3L, ref Vector3L)](VRageMath.Vector3L.Abs)||
|[Clamp(Vector3L, Vector3L, Vector3L)](VRageMath.Vector3L.Clamp)||
|[Clamp(ref Vector3L, ref Vector3L, ref Vector3L, ref Vector3L)](VRageMath.Vector3L.Clamp)||
|[DistanceManhattan(Vector3L, Vector3L)](VRageMath.Vector3L.DistanceManhattan)|Manhattan distance (cube distance) X + Y + Z of Abs(first - second)|
|[Dot(ref Vector3L)](VRageMath.Vector3L.Dot)||
|[Dot(Vector3L, Vector3L)](VRageMath.Vector3L.Dot)||
|[Dot(ref Vector3L, ref Vector3L)](VRageMath.Vector3L.Dot)||
|[Dot(ref Vector3L, ref Vector3L, ref long)](VRageMath.Vector3L.Dot)||
|[TryParseFromString(string, ref Vector3L)](VRageMath.Vector3L.TryParseFromString)||
|[Volume()](VRageMath.Vector3L.Volume)||
|[EnumerateRange(Vector3L, Vector3L)](VRageMath.Vector3L.EnumerateRange)|Enumerate all values in a longeger longerval (a cuboid). This method is an allocating version of the Vector3L_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.|
|[ToBytes(List)](VRageMath.Vector3L.ToBytes)||

