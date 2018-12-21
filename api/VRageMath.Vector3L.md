← [Index](index)
# Vector3L Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`long X`](VRageMath.X)||
|[`long Y`](VRageMath.Y)||
|[`long Z`](VRageMath.Z)||
|static [`VRageMath.EqualityComparer Comparer`](VRageMath.Comparer)||
|static [`VRageMath.Vector3L UnitX`](VRageMath.UnitX)||
|static [`VRageMath.Vector3L UnitY`](VRageMath.UnitY)||
|static [`VRageMath.Vector3L UnitZ`](VRageMath.UnitZ)||
|static [`VRageMath.Vector3L Zero`](VRageMath.Zero)||
|static [`VRageMath.Vector3L MaxValue`](VRageMath.MaxValue)||
|static [`VRageMath.Vector3L MinValue`](VRageMath.MinValue)||
|static [`VRageMath.Vector3L Up`](VRageMath.Up)||
|static [`VRageMath.Vector3L Down`](VRageMath.Down)||
|static [`VRageMath.Vector3L Right`](VRageMath.Right)||
|static [`VRageMath.Vector3L Left`](VRageMath.Left)||
|static [`VRageMath.Vector3L Forward`](VRageMath.Forward)||
|static [`VRageMath.Vector3L Backward`](VRageMath.Backward)||
|static [`VRageMath.Vector3L One`](VRageMath.One)||
### Properties
|Member|Description|
|---|---|
|[`long Item`](VRageMath.Item)||
|[`long Size`](VRageMath.Size)|How many cubes are in block with this size|
|[`long SizeLong`](VRageMath.SizeLong)||
### Methods
|Member|Description|
|---|---|
|[`string ToString()`](VRageMath.ToString)||
|[`bool Equals(VRageMath.Vector3L)`](VRageMath.Equals)||
|[`bool Equals(System.Object)`](VRageMath.Equals)||
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`bool IsInsideInclusiveEnd(ref VRageMath.Vector3L, ref VRageMath.Vector3L)`](VRageMath.IsInsideInclusiveEnd)||
|[`bool IsInsideInclusiveEnd(VRageMath.Vector3L, VRageMath.Vector3L)`](VRageMath.IsInsideInclusiveEnd)||
|[`bool IsInside(ref VRageMath.Vector3L, ref VRageMath.Vector3L)`](VRageMath.IsInside)||
|[`bool IsInside(VRageMath.Vector3L, VRageMath.Vector3L)`](VRageMath.IsInside)||
|[`long RectangularDistance(VRageMath.Vector3L)`](VRageMath.RectangularDistance)|Calculates rectangular distance. It's how many sectors you have to travel to get to other sector from current sector.|
|[`long RectangularLength()`](VRageMath.RectangularLength)|Calculates rectangular distance of this vector, longerpreted as a polong, from the origin.|
|[`long Length()`](VRageMath.Length)||
|static [`bool Boxlongersects(VRageMath.Vector3L, VRageMath.Vector3L, VRageMath.Vector3L, VRageMath.Vector3L)`](VRageMath.Boxlongersects)||
|static [`bool Boxlongersects(ref VRageMath.Vector3L, ref VRageMath.Vector3L, ref VRageMath.Vector3L, ref VRageMath.Vector3L)`](VRageMath.Boxlongersects)||
|static [`bool BoxContains(VRageMath.Vector3L, VRageMath.Vector3L, VRageMath.Vector3L)`](VRageMath.BoxContains)||
|static [`bool BoxContains(ref VRageMath.Vector3L, ref VRageMath.Vector3L, ref VRageMath.Vector3L)`](VRageMath.BoxContains)||
|static [`VRageMath.Vector3L Min(VRageMath.Vector3L, VRageMath.Vector3L)`](VRageMath.Min)||
|static [`void Min(ref VRageMath.Vector3L, ref VRageMath.Vector3L, ref VRageMath.Vector3L)`](VRageMath.Min)||
|[`long AbsMin()`](VRageMath.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|static [`VRageMath.Vector3L Max(VRageMath.Vector3L, VRageMath.Vector3L)`](VRageMath.Max)||
|static [`void Max(ref VRageMath.Vector3L, ref VRageMath.Vector3L, ref VRageMath.Vector3L)`](VRageMath.Max)||
|[`long AbsMax()`](VRageMath.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|[`long AxisValue(VRageMath.Axis)`](VRageMath.AxisValue)||
|static [`VRageMath.CubeFace GetDominantDirection(VRageMath.Vector3L)`](VRageMath.GetDominantDirection)||
|static [`VRageMath.Vector3L GetDominantDirectionVector(VRageMath.Vector3L)`](VRageMath.GetDominantDirectionVector)||
|static [`VRageMath.Vector3L DominantAxisProjection(VRageMath.Vector3L)`](VRageMath.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|static [`void DominantAxisProjection(ref VRageMath.Vector3L, ref VRageMath.Vector3L)`](VRageMath.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved longo a user-specified variable.|
|static [`VRageMath.Vector3L Sign(VRageMath.Vector3)`](VRageMath.Sign)||
|static [`VRageMath.Vector3L Sign(VRageMath.Vector3L)`](VRageMath.Sign)||
|static [`VRageMath.Vector3L Floor(VRageMath.Vector3)`](VRageMath.Floor)||
|static [`VRageMath.Vector3L Floor(VRageMath.Vector3D)`](VRageMath.Floor)||
|static [`void Floor(ref VRageMath.Vector3, ref VRageMath.Vector3L)`](VRageMath.Floor)||
|static [`void Floor(ref VRageMath.Vector3D, ref VRageMath.Vector3L)`](VRageMath.Floor)||
|static [`VRageMath.Vector3L Ceiling(VRageMath.Vector3)`](VRageMath.Ceiling)||
|static [`VRageMath.Vector3L Trunc(VRageMath.Vector3)`](VRageMath.Trunc)||
|static [`VRageMath.Vector3L Shift(VRageMath.Vector3L)`](VRageMath.Shift)||
|static [`void Transform(ref VRageMath.Vector3L, ref VRageMath.Matrix, ref VRageMath.Vector3L)`](VRageMath.Transform)|Transforms a Vector3L by the given Matrix.|
|static [`void Transform(ref VRageMath.Vector3L, ref VRageMath.Quaternion, ref VRageMath.Vector3L)`](VRageMath.Transform)||
|static [`VRageMath.Vector3L Transform(VRageMath.Vector3L, VRageMath.Quaternion)`](VRageMath.Transform)||
|static [`void TransformNormal(ref VRageMath.Vector3L, ref VRageMath.Matrix, ref VRageMath.Vector3L)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|static [`void Cross(ref VRageMath.Vector3L, ref VRageMath.Vector3L, ref VRageMath.Vector3L)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|[`int CompareTo(VRageMath.Vector3L)`](VRageMath.CompareTo)||
|static [`VRageMath.Vector3L Abs(VRageMath.Vector3L)`](VRageMath.Abs)||
|static [`void Abs(ref VRageMath.Vector3L, ref VRageMath.Vector3L)`](VRageMath.Abs)||
|static [`VRageMath.Vector3L Clamp(VRageMath.Vector3L, VRageMath.Vector3L, VRageMath.Vector3L)`](VRageMath.Clamp)||
|static [`void Clamp(ref VRageMath.Vector3L, ref VRageMath.Vector3L, ref VRageMath.Vector3L, ref VRageMath.Vector3L)`](VRageMath.Clamp)||
|static [`long DistanceManhattan(VRageMath.Vector3L, VRageMath.Vector3L)`](VRageMath.DistanceManhattan)|Manhattan distance (cube distance) X + Y + Z of Abs(first - second)|
|[`long Dot(ref VRageMath.Vector3L)`](VRageMath.Dot)||
|static [`long Dot(VRageMath.Vector3L, VRageMath.Vector3L)`](VRageMath.Dot)||
|static [`long Dot(ref VRageMath.Vector3L, ref VRageMath.Vector3L)`](VRageMath.Dot)||
|static [`void Dot(ref VRageMath.Vector3L, ref VRageMath.Vector3L, ref long)`](VRageMath.Dot)||
|static [`bool TryParseFromString(string, ref VRageMath.Vector3L)`](VRageMath.TryParseFromString)||
|[`long Volume()`](VRageMath.Volume)||
|static [`IEnumerable<VRageMath.Vector3L> EnumerateRange(VRageMath.Vector3L, VRageMath.Vector3L)`](VRageMath.EnumerateRange)|Enumerate all values in a longeger longerval (a cuboid). This method is an allocating version of the Vector3L_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.|
|[`void ToBytes(List<System.Byte>)`](VRageMath.ToBytes)||
