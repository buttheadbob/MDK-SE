← [Index](Api-Index)

#### Vector3I Struct

```csharp
public sealed struct Vector3I
```

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

#### Example

#### Remarks

#### Fields

|Member|Description|
|---|---|
|[X](VRageMath.Vector3I.X)||
|[Y](VRageMath.Vector3I.Y)||
|[Z](VRageMath.Vector3I.Z)||
|[Comparer](VRageMath.Vector3I.Comparer)||
|[UnitX](VRageMath.Vector3I.UnitX)||
|[UnitY](VRageMath.Vector3I.UnitY)||
|[UnitZ](VRageMath.Vector3I.UnitZ)||
|[Zero](VRageMath.Vector3I.Zero)||
|[MaxValue](VRageMath.Vector3I.MaxValue)||
|[MinValue](VRageMath.Vector3I.MinValue)||
|[Up](VRageMath.Vector3I.Up)||
|[Down](VRageMath.Vector3I.Down)||
|[Right](VRageMath.Vector3I.Right)||
|[Left](VRageMath.Vector3I.Left)||
|[Forward](VRageMath.Vector3I.Forward)||
|[Backward](VRageMath.Vector3I.Backward)||
|[One](VRageMath.Vector3I.One)||

#### Properties

|Member|Description|
|---|---|
|[Item](VRageMath.Vector3I.Item)||
|[IsPowerOfTwo](VRageMath.Vector3I.IsPowerOfTwo)||
|[Size](VRageMath.Vector3I.Size)|How many cubes are in block with this size|
|[SizeLong](VRageMath.Vector3I.SizeLong)||

#### Methods

|Member|Description|
|---|---|
|[ToString()](VRageMath.Vector3I.ToString)||
|[Equals(Vector3I)](VRageMath.Vector3I.Equals)||
|[Equals(object)](VRageMath.Vector3I.Equals)||
|[GetHashCode()](VRageMath.Vector3I.GetHashCode)||
|[IsInsideInclusiveEnd(ref Vector3I, ref Vector3I)](VRageMath.Vector3I.IsInsideInclusiveEnd)||
|[IsInsideInclusiveEnd(Vector3I, Vector3I)](VRageMath.Vector3I.IsInsideInclusiveEnd)||
|[IsInside(ref Vector3I, ref Vector3I)](VRageMath.Vector3I.IsInside)||
|[IsInside(Vector3I, Vector3I)](VRageMath.Vector3I.IsInside)||
|[RectangularDistance(Vector3I)](VRageMath.Vector3I.RectangularDistance)|Calculates rectangular distance. It's how many sectors you have to travel to get to other sector from current sector.|
|[RectangularLength()](VRageMath.Vector3I.RectangularLength)|Calculates rectangular distance of this vector, interpreted as a point, from the origin.|
|[Length()](VRageMath.Vector3I.Length)||
|[BoxIntersects(Vector3I, Vector3I, Vector3I, Vector3I)](VRageMath.Vector3I.BoxIntersects)||
|[BoxIntersects(ref Vector3I, ref Vector3I, ref Vector3I, ref Vector3I)](VRageMath.Vector3I.BoxIntersects)||
|[BoxContains(Vector3I, Vector3I, Vector3I)](VRageMath.Vector3I.BoxContains)||
|[BoxContains(ref Vector3I, ref Vector3I, ref Vector3I)](VRageMath.Vector3I.BoxContains)||
|[Min(Vector3I, Vector3I)](VRageMath.Vector3I.Min)||
|[Min(ref Vector3I, ref Vector3I, ref Vector3I)](VRageMath.Vector3I.Min)||
|[AbsMin()](VRageMath.Vector3I.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|[Max(Vector3I, Vector3I)](VRageMath.Vector3I.Max)||
|[Max(ref Vector3I, ref Vector3I, ref Vector3I)](VRageMath.Vector3I.Max)||
|[AbsMax()](VRageMath.Vector3I.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|[MinMax(ref Vector3I, ref Vector3I)](VRageMath.Vector3I.MinMax)|Separates minimal and maximal values of any two input vectors|
|[AxisValue(Axis)](VRageMath.Vector3I.AxisValue)||
|[GetDominantDirection(Vector3I)](VRageMath.Vector3I.GetDominantDirection)||
|[GetDominantDirectionVector(Vector3I)](VRageMath.Vector3I.GetDominantDirectionVector)||
|[DominantAxisProjection(Vector3I)](VRageMath.Vector3I.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|[DominantAxisProjection(ref Vector3I, ref Vector3I)](VRageMath.Vector3I.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved into a user-specified variable.|
|[Sign(Vector3)](VRageMath.Vector3I.Sign)||
|[Sign(Vector3I)](VRageMath.Vector3I.Sign)||
|[Round(Vector3)](VRageMath.Vector3I.Round)||
|[Round(Vector3D)](VRageMath.Vector3I.Round)||
|[Round(ref Vector3, ref Vector3I)](VRageMath.Vector3I.Round)||
|[Round(ref Vector3D, ref Vector3I)](VRageMath.Vector3I.Round)||
|[Floor(Vector3)](VRageMath.Vector3I.Floor)||
|[Floor(Vector3D)](VRageMath.Vector3I.Floor)||
|[Floor(ref Vector3, ref Vector3I)](VRageMath.Vector3I.Floor)||
|[Floor(ref Vector3D, ref Vector3I)](VRageMath.Vector3I.Floor)||
|[Ceiling(Vector3)](VRageMath.Vector3I.Ceiling)||
|[Trunc(Vector3)](VRageMath.Vector3I.Trunc)||
|[Shift(Vector3I)](VRageMath.Vector3I.Shift)||
|[Transform(ref Vector3I, ref Matrix, ref Vector3I)](VRageMath.Vector3I.Transform)|Transforms a Vector3I by the given Matrix.|
|[Transform(ref Vector3I, ref Quaternion, ref Vector3I)](VRageMath.Vector3I.Transform)||
|[Transform(Vector3I, Quaternion)](VRageMath.Vector3I.Transform)||
|[Transform(ref Vector3I, ref MatrixI, ref Vector3I)](VRageMath.Vector3I.Transform)||
|[Transform(Vector3I, MatrixI)](VRageMath.Vector3I.Transform)||
|[Transform(Vector3I, ref MatrixI)](VRageMath.Vector3I.Transform)||
|[TransformNormal(Vector3I, ref MatrixI)](VRageMath.Vector3I.TransformNormal)||
|[TransformNormal(ref Vector3I, ref Matrix, ref Vector3I)](VRageMath.Vector3I.TransformNormal)|Transforms a vector normal by a matrix.|
|[TransformNormal(ref Vector3I, ref MatrixI, ref Vector3I)](VRageMath.Vector3I.TransformNormal)||
|[Cross(ref Vector3I, ref Vector3I, ref Vector3I)](VRageMath.Vector3I.Cross)|Calculates the cross product of two vectors.|
|[CompareTo(Vector3I)](VRageMath.Vector3I.CompareTo)||
|[Abs(Vector3I)](VRageMath.Vector3I.Abs)||
|[Abs(ref Vector3I, ref Vector3I)](VRageMath.Vector3I.Abs)||
|[Clamp(Vector3I, Vector3I, Vector3I)](VRageMath.Vector3I.Clamp)||
|[Clamp(ref Vector3I, ref Vector3I, ref Vector3I, ref Vector3I)](VRageMath.Vector3I.Clamp)||
|[DistanceManhattan(Vector3I, Vector3I)](VRageMath.Vector3I.DistanceManhattan)|Manhattan distance (cube distance) X + Y + Z of Abs(first - second)|
|[Dot(ref Vector3I)](VRageMath.Vector3I.Dot)||
|[Dot(Vector3I, Vector3I)](VRageMath.Vector3I.Dot)||
|[Dot(ref Vector3I, ref Vector3I)](VRageMath.Vector3I.Dot)||
|[Dot(ref Vector3I, ref Vector3I, ref int)](VRageMath.Vector3I.Dot)||
|[TryParseFromString(string, ref Vector3I)](VRageMath.Vector3I.TryParseFromString)||
|[Volume()](VRageMath.Vector3I.Volume)||
|[EnumerateRange(Vector3I, Vector3I)](VRageMath.Vector3I.EnumerateRange)|Enumerate all values in a integer interval (a cuboid). This method is an allocating version of the Vector3I_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.|
|[ToBytes(List)](VRageMath.Vector3I.ToBytes)||
|[IsAxisAligned()](VRageMath.Vector3I.IsAxisAligned)||

