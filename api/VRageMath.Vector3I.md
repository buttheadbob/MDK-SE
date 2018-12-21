← [Index](index)
# Vector3I Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`int X`](VRageMath.X)||
|[`int Y`](VRageMath.Y)||
|[`int Z`](VRageMath.Z)||
|static [`EqualityComparer Comparer`](VRageMath.Comparer)||
|static [`Vector3I UnitX`](VRageMath.UnitX)||
|static [`Vector3I UnitY`](VRageMath.UnitY)||
|static [`Vector3I UnitZ`](VRageMath.UnitZ)||
|static [`Vector3I Zero`](VRageMath.Zero)||
|static [`Vector3I MaxValue`](VRageMath.MaxValue)||
|static [`Vector3I MinValue`](VRageMath.MinValue)||
|static [`Vector3I Up`](VRageMath.Up)||
|static [`Vector3I Down`](VRageMath.Down)||
|static [`Vector3I Right`](VRageMath.Right)||
|static [`Vector3I Left`](VRageMath.Left)||
|static [`Vector3I Forward`](VRageMath.Forward)||
|static [`Vector3I Backward`](VRageMath.Backward)||
|static [`Vector3I One`](VRageMath.One)||
### Properties
|Member|Description|
|---|---|
|[`int Item`](VRageMath.Item)||
|[`bool IsPowerOfTwo`](VRageMath.IsPowerOfTwo)||
|[`int Size`](VRageMath.Size)|How many cubes are in block with this size|
|[`long SizeLong`](VRageMath.SizeLong)||
### Methods
|Member|Description|
|---|---|
|[`string ToString()`](VRageMath.ToString)||
|[`bool Equals(Vector3I other)`](VRageMath.Equals)||
|[`bool Equals(Object obj)`](VRageMath.Equals)||
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`bool IsInsideInclusiveEnd(ref Vector3I min, ref Vector3I max)`](VRageMath.IsInsideInclusiveEnd)||
|[`bool IsInsideInclusiveEnd(Vector3I min, Vector3I max)`](VRageMath.IsInsideInclusiveEnd)||
|[`bool IsInside(ref Vector3I inclusiveMin, ref Vector3I exclusiveMax)`](VRageMath.IsInside)||
|[`bool IsInside(Vector3I inclusiveMin, Vector3I exclusiveMax)`](VRageMath.IsInside)||
|[`int RectangularDistance(Vector3I otherVector)`](VRageMath.RectangularDistance)|Calculates rectangular distance. It's how many sectors you have to travel to get to other sector from current sector.|
|[`int RectangularLength()`](VRageMath.RectangularLength)|Calculates rectangular distance of this vector, interpreted as a point, from the origin.|
|[`int Length()`](VRageMath.Length)||
|static [`bool BoxIntersects(Vector3I minA, Vector3I maxA, Vector3I minB, Vector3I maxB)`](VRageMath.BoxIntersects)||
|static [`bool BoxIntersects(ref Vector3I minA, ref Vector3I maxA, ref Vector3I minB, ref Vector3I maxB)`](VRageMath.BoxIntersects)||
|static [`bool BoxContains(Vector3I boxMin, Vector3I boxMax, Vector3I pt)`](VRageMath.BoxContains)||
|static [`bool BoxContains(ref Vector3I boxMin, ref Vector3I boxMax, ref Vector3I pt)`](VRageMath.BoxContains)||
|static [`Vector3I Min(Vector3I value1, Vector3I value2)`](VRageMath.Min)||
|static [`void Min(ref Vector3I value1, ref Vector3I value2, ref Vector3I result)`](VRageMath.Min)||
|[`int AbsMin()`](VRageMath.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|static [`Vector3I Max(Vector3I value1, Vector3I value2)`](VRageMath.Max)||
|static [`void Max(ref Vector3I value1, ref Vector3I value2, ref Vector3I result)`](VRageMath.Max)||
|[`int AbsMax()`](VRageMath.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|static [`void MinMax(ref Vector3I min, ref Vector3I max)`](VRageMath.MinMax)|Separates minimal and maximal values of any two input vectors|
|[`int AxisValue(Axis axis)`](VRageMath.AxisValue)||
|static [`CubeFace GetDominantDirection(Vector3I val)`](VRageMath.GetDominantDirection)||
|static [`Vector3I GetDominantDirectionVector(Vector3I val)`](VRageMath.GetDominantDirectionVector)||
|static [`Vector3I DominantAxisProjection(Vector3I value1)`](VRageMath.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|static [`void DominantAxisProjection(ref Vector3I value1, ref Vector3I result)`](VRageMath.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved into a user-specified variable.|
|static [`Vector3I Sign(Vector3 value)`](VRageMath.Sign)||
|static [`Vector3I Sign(Vector3I value)`](VRageMath.Sign)||
|static [`Vector3I Round(Vector3 value)`](VRageMath.Round)||
|static [`Vector3I Round(Vector3D value)`](VRageMath.Round)||
|static [`void Round(ref Vector3 v, ref Vector3I r)`](VRageMath.Round)||
|static [`void Round(ref Vector3D v, ref Vector3I r)`](VRageMath.Round)||
|static [`Vector3I Floor(Vector3 value)`](VRageMath.Floor)||
|static [`Vector3I Floor(Vector3D value)`](VRageMath.Floor)||
|static [`void Floor(ref Vector3 v, ref Vector3I r)`](VRageMath.Floor)||
|static [`void Floor(ref Vector3D v, ref Vector3I r)`](VRageMath.Floor)||
|static [`Vector3I Ceiling(Vector3 value)`](VRageMath.Ceiling)||
|static [`Vector3I Trunc(Vector3 value)`](VRageMath.Trunc)||
|static [`Vector3I Shift(Vector3I value)`](VRageMath.Shift)||
|static [`void Transform(ref Vector3I position, ref Matrix matrix, ref Vector3I result)`](VRageMath.Transform)|Transforms a Vector3I by the given Matrix.|
|static [`void Transform(ref Vector3I value, ref Quaternion rotation, ref Vector3I result)`](VRageMath.Transform)||
|static [`Vector3I Transform(Vector3I value, Quaternion rotation)`](VRageMath.Transform)||
|static [`void Transform(ref Vector3I value, ref MatrixI matrix, ref Vector3I result)`](VRageMath.Transform)||
|static [`Vector3I Transform(Vector3I value, MatrixI transformation)`](VRageMath.Transform)||
|static [`Vector3I Transform(Vector3I value, ref MatrixI transformation)`](VRageMath.Transform)||
|static [`Vector3I TransformNormal(Vector3I value, ref MatrixI transformation)`](VRageMath.TransformNormal)||
|static [`void TransformNormal(ref Vector3I normal, ref Matrix matrix, ref Vector3I result)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|static [`void TransformNormal(ref Vector3I normal, ref MatrixI matrix, ref Vector3I result)`](VRageMath.TransformNormal)||
|static [`void Cross(ref Vector3I vector1, ref Vector3I vector2, ref Vector3I result)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|[`int CompareTo(Vector3I other)`](VRageMath.CompareTo)||
|static [`Vector3I Abs(Vector3I value)`](VRageMath.Abs)||
|static [`void Abs(ref Vector3I value, ref Vector3I result)`](VRageMath.Abs)||
|static [`Vector3I Clamp(Vector3I value1, Vector3I min, Vector3I max)`](VRageMath.Clamp)||
|static [`void Clamp(ref Vector3I value1, ref Vector3I min, ref Vector3I max, ref Vector3I result)`](VRageMath.Clamp)||
|static [`int DistanceManhattan(Vector3I first, Vector3I second)`](VRageMath.DistanceManhattan)|Manhattan distance (cube distance) X + Y + Z of Abs(first - second)|
|[`int Dot(ref Vector3I v)`](VRageMath.Dot)||
|static [`int Dot(Vector3I vector1, Vector3I vector2)`](VRageMath.Dot)||
|static [`int Dot(ref Vector3I vector1, ref Vector3I vector2)`](VRageMath.Dot)||
|static [`void Dot(ref Vector3I vector1, ref Vector3I vector2, ref int dot)`](VRageMath.Dot)||
|static [`bool TryParseFromString(string p, ref Vector3I vec)`](VRageMath.TryParseFromString)||
|[`int Volume()`](VRageMath.Volume)||
|static [`IEnumerable<Vector3I> EnumerateRange(Vector3I minInclusive, Vector3I maxExclusive)`](VRageMath.EnumerateRange)|Enumerate all values in a integer interval (a cuboid). This method is an allocating version of the Vector3I_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.|
|[`void ToBytes(List<byte> result)`](VRageMath.ToBytes)||
|[`bool IsAxisAligned()`](VRageMath.IsAxisAligned)||
