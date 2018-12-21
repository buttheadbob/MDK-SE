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
|static [`EqualityComparer Comparer`](VRageMath.Comparer)||
|static [`Vector3L UnitX`](VRageMath.UnitX)||
|static [`Vector3L UnitY`](VRageMath.UnitY)||
|static [`Vector3L UnitZ`](VRageMath.UnitZ)||
|static [`Vector3L Zero`](VRageMath.Zero)||
|static [`Vector3L MaxValue`](VRageMath.MaxValue)||
|static [`Vector3L MinValue`](VRageMath.MinValue)||
|static [`Vector3L Up`](VRageMath.Up)||
|static [`Vector3L Down`](VRageMath.Down)||
|static [`Vector3L Right`](VRageMath.Right)||
|static [`Vector3L Left`](VRageMath.Left)||
|static [`Vector3L Forward`](VRageMath.Forward)||
|static [`Vector3L Backward`](VRageMath.Backward)||
|static [`Vector3L One`](VRageMath.One)||
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
|[`bool Equals(Vector3L other)`](VRageMath.Equals)||
|[`bool Equals(Object obj)`](VRageMath.Equals)||
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`bool IsInsideInclusiveEnd(ref Vector3L min, ref Vector3L max)`](VRageMath.IsInsideInclusiveEnd)||
|[`bool IsInsideInclusiveEnd(Vector3L min, Vector3L max)`](VRageMath.IsInsideInclusiveEnd)||
|[`bool IsInside(ref Vector3L inclusiveMin, ref Vector3L exclusiveMax)`](VRageMath.IsInside)||
|[`bool IsInside(Vector3L inclusiveMin, Vector3L exclusiveMax)`](VRageMath.IsInside)||
|[`long RectangularDistance(Vector3L otherVector)`](VRageMath.RectangularDistance)|Calculates rectangular distance. It's how many sectors you have to travel to get to other sector from current sector.|
|[`long RectangularLength()`](VRageMath.RectangularLength)|Calculates rectangular distance of this vector, longerpreted as a polong, from the origin.|
|[`long Length()`](VRageMath.Length)||
|static [`bool Boxlongersects(Vector3L minA, Vector3L maxA, Vector3L minB, Vector3L maxB)`](VRageMath.Boxlongersects)||
|static [`bool Boxlongersects(ref Vector3L minA, ref Vector3L maxA, ref Vector3L minB, ref Vector3L maxB)`](VRageMath.Boxlongersects)||
|static [`bool BoxContains(Vector3L boxMin, Vector3L boxMax, Vector3L pt)`](VRageMath.BoxContains)||
|static [`bool BoxContains(ref Vector3L boxMin, ref Vector3L boxMax, ref Vector3L pt)`](VRageMath.BoxContains)||
|static [`Vector3L Min(Vector3L value1, Vector3L value2)`](VRageMath.Min)||
|static [`void Min(ref Vector3L value1, ref Vector3L value2, ref Vector3L result)`](VRageMath.Min)||
|[`long AbsMin()`](VRageMath.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|static [`Vector3L Max(Vector3L value1, Vector3L value2)`](VRageMath.Max)||
|static [`void Max(ref Vector3L value1, ref Vector3L value2, ref Vector3L result)`](VRageMath.Max)||
|[`long AbsMax()`](VRageMath.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|[`long AxisValue(Axis axis)`](VRageMath.AxisValue)||
|static [`CubeFace GetDominantDirection(Vector3L val)`](VRageMath.GetDominantDirection)||
|static [`Vector3L GetDominantDirectionVector(Vector3L val)`](VRageMath.GetDominantDirectionVector)||
|static [`Vector3L DominantAxisProjection(Vector3L value1)`](VRageMath.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|static [`void DominantAxisProjection(ref Vector3L value1, ref Vector3L result)`](VRageMath.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved longo a user-specified variable.|
|static [`Vector3L Sign(Vector3 value)`](VRageMath.Sign)||
|static [`Vector3L Sign(Vector3L value)`](VRageMath.Sign)||
|static [`Vector3L Floor(Vector3 value)`](VRageMath.Floor)||
|static [`Vector3L Floor(Vector3D value)`](VRageMath.Floor)||
|static [`void Floor(ref Vector3 v, ref Vector3L r)`](VRageMath.Floor)||
|static [`void Floor(ref Vector3D v, ref Vector3L r)`](VRageMath.Floor)||
|static [`Vector3L Ceiling(Vector3 value)`](VRageMath.Ceiling)||
|static [`Vector3L Trunc(Vector3 value)`](VRageMath.Trunc)||
|static [`Vector3L Shift(Vector3L value)`](VRageMath.Shift)||
|static [`void Transform(ref Vector3L position, ref Matrix matrix, ref Vector3L result)`](VRageMath.Transform)|Transforms a Vector3L by the given Matrix.|
|static [`void Transform(ref Vector3L value, ref Quaternion rotation, ref Vector3L result)`](VRageMath.Transform)||
|static [`Vector3L Transform(Vector3L value, Quaternion rotation)`](VRageMath.Transform)||
|static [`void TransformNormal(ref Vector3L normal, ref Matrix matrix, ref Vector3L result)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|static [`void Cross(ref Vector3L vector1, ref Vector3L vector2, ref Vector3L result)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|[`int CompareTo(Vector3L other)`](VRageMath.CompareTo)||
|static [`Vector3L Abs(Vector3L value)`](VRageMath.Abs)||
|static [`void Abs(ref Vector3L value, ref Vector3L result)`](VRageMath.Abs)||
|static [`Vector3L Clamp(Vector3L value1, Vector3L min, Vector3L max)`](VRageMath.Clamp)||
|static [`void Clamp(ref Vector3L value1, ref Vector3L min, ref Vector3L max, ref Vector3L result)`](VRageMath.Clamp)||
|static [`long DistanceManhattan(Vector3L first, Vector3L second)`](VRageMath.DistanceManhattan)|Manhattan distance (cube distance) X + Y + Z of Abs(first - second)|
|[`long Dot(ref Vector3L v)`](VRageMath.Dot)||
|static [`long Dot(Vector3L vector1, Vector3L vector2)`](VRageMath.Dot)||
|static [`long Dot(ref Vector3L vector1, ref Vector3L vector2)`](VRageMath.Dot)||
|static [`void Dot(ref Vector3L vector1, ref Vector3L vector2, ref long dot)`](VRageMath.Dot)||
|static [`bool TryParseFromString(string p, ref Vector3L vec)`](VRageMath.TryParseFromString)||
|[`long Volume()`](VRageMath.Volume)||
|static [`IEnumerable<Vector3L> EnumerateRange(Vector3L minInclusive, Vector3L maxExclusive)`](VRageMath.EnumerateRange)|Enumerate all values in a longeger longerval (a cuboid). This method is an allocating version of the Vector3L_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.|
|[`void ToBytes(List<byte> result)`](VRageMath.ToBytes)||
