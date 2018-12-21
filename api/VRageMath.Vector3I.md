← [Index](index)
# Vector3I Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
<table style="width:100%;display:table">
<tr><td>[`int X`](VRageMath.X)</td><td></td></tr>
<tr><td>[`int Y`](VRageMath.Y)</td><td></td></tr>
<tr><td>[`int Z`](VRageMath.Z)</td><td></td></tr>
<tr><td>static [`EqualityComparer Comparer`](VRageMath.Comparer)</td><td></td></tr>
<tr><td>static [`Vector3I UnitX`](VRageMath.UnitX)</td><td></td></tr>
<tr><td>static [`Vector3I UnitY`](VRageMath.UnitY)</td><td></td></tr>
<tr><td>static [`Vector3I UnitZ`](VRageMath.UnitZ)</td><td></td></tr>
<tr><td>static [`Vector3I Zero`](VRageMath.Zero)</td><td></td></tr>
<tr><td>static [`Vector3I MaxValue`](VRageMath.MaxValue)</td><td></td></tr>
<tr><td>static [`Vector3I MinValue`](VRageMath.MinValue)</td><td></td></tr>
<tr><td>static [`Vector3I Up`](VRageMath.Up)</td><td></td></tr>
<tr><td>static [`Vector3I Down`](VRageMath.Down)</td><td></td></tr>
<tr><td>static [`Vector3I Right`](VRageMath.Right)</td><td></td></tr>
<tr><td>static [`Vector3I Left`](VRageMath.Left)</td><td></td></tr>
<tr><td>static [`Vector3I Forward`](VRageMath.Forward)</td><td></td></tr>
<tr><td>static [`Vector3I Backward`](VRageMath.Backward)</td><td></td></tr>
<tr><td>static [`Vector3I One`](VRageMath.One)</td><td></td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>[`int Item`](VRageMath.Item)</td><td></td></tr>
<tr><td>[`bool IsPowerOfTwo`](VRageMath.IsPowerOfTwo)</td><td></td></tr>
<tr><td>[`int Size`](VRageMath.Size)</td><td>How many cubes are in block with this size</td></tr>
<tr><td>[`long SizeLong`](VRageMath.SizeLong)</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td></td></tr>
<tr><td>[`bool Equals(Vector3I other)`](VRageMath.Equals)</td><td></td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td></td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td></td></tr>
<tr><td>[`bool IsInsideInclusiveEnd(ref Vector3I min, ref Vector3I max)`](VRageMath.IsInsideInclusiveEnd)</td><td></td></tr>
<tr><td>[`bool IsInsideInclusiveEnd(Vector3I min, Vector3I max)`](VRageMath.IsInsideInclusiveEnd)</td><td></td></tr>
<tr><td>[`bool IsInside(ref Vector3I inclusiveMin, ref Vector3I exclusiveMax)`](VRageMath.IsInside)</td><td></td></tr>
<tr><td>[`bool IsInside(Vector3I inclusiveMin, Vector3I exclusiveMax)`](VRageMath.IsInside)</td><td></td></tr>
<tr><td>[`int RectangularDistance(Vector3I otherVector)`](VRageMath.RectangularDistance)</td><td>Calculates rectangular distance. It's how many sectors you have to travel to get to other sector from current sector.</td></tr>
<tr><td>[`int RectangularLength()`](VRageMath.RectangularLength)</td><td>Calculates rectangular distance of this vector, interpreted as a point, from the origin.</td></tr>
<tr><td>[`int Length()`](VRageMath.Length)</td><td></td></tr>
<tr><td>static [`bool BoxIntersects(Vector3I minA, Vector3I maxA, Vector3I minB, Vector3I maxB)`](VRageMath.BoxIntersects)</td><td></td></tr>
<tr><td>static [`bool BoxIntersects(ref Vector3I minA, ref Vector3I maxA, ref Vector3I minB, ref Vector3I maxB)`](VRageMath.BoxIntersects)</td><td></td></tr>
<tr><td>static [`bool BoxContains(Vector3I boxMin, Vector3I boxMax, Vector3I pt)`](VRageMath.BoxContains)</td><td></td></tr>
<tr><td>static [`bool BoxContains(ref Vector3I boxMin, ref Vector3I boxMax, ref Vector3I pt)`](VRageMath.BoxContains)</td><td></td></tr>
<tr><td>static [`Vector3I Min(Vector3I value1, Vector3I value2)`](VRageMath.Min)</td><td></td></tr>
<tr><td>static [`void Min(ref Vector3I value1, ref Vector3I value2, ref Vector3I result)`](VRageMath.Min)</td><td></td></tr>
<tr><td>[`int AbsMin()`](VRageMath.AbsMin)</td><td>Returns the component of the vector, whose absolute value is smallest of all the three components.</td></tr>
<tr><td>static [`Vector3I Max(Vector3I value1, Vector3I value2)`](VRageMath.Max)</td><td></td></tr>
<tr><td>static [`void Max(ref Vector3I value1, ref Vector3I value2, ref Vector3I result)`](VRageMath.Max)</td><td></td></tr>
<tr><td>[`int AbsMax()`](VRageMath.AbsMax)</td><td>Returns the component of the vector, whose absolute value is largest of all the three components.</td></tr>
<tr><td>static [`void MinMax(ref Vector3I min, ref Vector3I max)`](VRageMath.MinMax)</td><td>Separates minimal and maximal values of any two input vectors</td></tr>
<tr><td>[`int AxisValue(Axis axis)`](VRageMath.AxisValue)</td><td></td></tr>
<tr><td>static [`CubeFace GetDominantDirection(Vector3I val)`](VRageMath.GetDominantDirection)</td><td></td></tr>
<tr><td>static [`Vector3I GetDominantDirectionVector(Vector3I val)`](VRageMath.GetDominantDirectionVector)</td><td></td></tr>
<tr><td>static [`Vector3I DominantAxisProjection(Vector3I value1)`](VRageMath.DominantAxisProjection)</td><td>Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.</td></tr>
<tr><td>static [`void DominantAxisProjection(ref Vector3I value1, ref Vector3I result)`](VRageMath.DominantAxisProjection)</td><td>Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved into a user-specified variable.</td></tr>
<tr><td>static [`Vector3I Sign(Vector3 value)`](VRageMath.Sign)</td><td></td></tr>
<tr><td>static [`Vector3I Sign(Vector3I value)`](VRageMath.Sign)</td><td></td></tr>
<tr><td>static [`Vector3I Round(Vector3 value)`](VRageMath.Round)</td><td></td></tr>
<tr><td>static [`Vector3I Round(Vector3D value)`](VRageMath.Round)</td><td></td></tr>
<tr><td>static [`void Round(ref Vector3 v, ref Vector3I r)`](VRageMath.Round)</td><td></td></tr>
<tr><td>static [`void Round(ref Vector3D v, ref Vector3I r)`](VRageMath.Round)</td><td></td></tr>
<tr><td>static [`Vector3I Floor(Vector3 value)`](VRageMath.Floor)</td><td></td></tr>
<tr><td>static [`Vector3I Floor(Vector3D value)`](VRageMath.Floor)</td><td></td></tr>
<tr><td>static [`void Floor(ref Vector3 v, ref Vector3I r)`](VRageMath.Floor)</td><td></td></tr>
<tr><td>static [`void Floor(ref Vector3D v, ref Vector3I r)`](VRageMath.Floor)</td><td></td></tr>
<tr><td>static [`Vector3I Ceiling(Vector3 value)`](VRageMath.Ceiling)</td><td></td></tr>
<tr><td>static [`Vector3I Trunc(Vector3 value)`](VRageMath.Trunc)</td><td></td></tr>
<tr><td>static [`Vector3I Shift(Vector3I value)`](VRageMath.Shift)</td><td></td></tr>
<tr><td>static [`void Transform(ref Vector3I position, ref Matrix matrix, ref Vector3I result)`](VRageMath.Transform)</td><td>Transforms a Vector3I by the given Matrix.</td></tr>
<tr><td>static [`void Transform(ref Vector3I value, ref Quaternion rotation, ref Vector3I result)`](VRageMath.Transform)</td><td></td></tr>
<tr><td>static [`Vector3I Transform(Vector3I value, Quaternion rotation)`](VRageMath.Transform)</td><td></td></tr>
<tr><td>static [`void Transform(ref Vector3I value, ref MatrixI matrix, ref Vector3I result)`](VRageMath.Transform)</td><td></td></tr>
<tr><td>static [`Vector3I Transform(Vector3I value, MatrixI transformation)`](VRageMath.Transform)</td><td></td></tr>
<tr><td>static [`Vector3I Transform(Vector3I value, ref MatrixI transformation)`](VRageMath.Transform)</td><td></td></tr>
<tr><td>static [`Vector3I TransformNormal(Vector3I value, ref MatrixI transformation)`](VRageMath.TransformNormal)</td><td></td></tr>
<tr><td>static [`void TransformNormal(ref Vector3I normal, ref Matrix matrix, ref Vector3I result)`](VRageMath.TransformNormal)</td><td>Transforms a vector normal by a matrix.</td></tr>
<tr><td>static [`void TransformNormal(ref Vector3I normal, ref MatrixI matrix, ref Vector3I result)`](VRageMath.TransformNormal)</td><td></td></tr>
<tr><td>static [`void Cross(ref Vector3I vector1, ref Vector3I vector2, ref Vector3I result)`](VRageMath.Cross)</td><td>Calculates the cross product of two vectors.</td></tr>
<tr><td>[`int CompareTo(Vector3I other)`](VRageMath.CompareTo)</td><td></td></tr>
<tr><td>static [`Vector3I Abs(Vector3I value)`](VRageMath.Abs)</td><td></td></tr>
<tr><td>static [`void Abs(ref Vector3I value, ref Vector3I result)`](VRageMath.Abs)</td><td></td></tr>
<tr><td>static [`Vector3I Clamp(Vector3I value1, Vector3I min, Vector3I max)`](VRageMath.Clamp)</td><td></td></tr>
<tr><td>static [`void Clamp(ref Vector3I value1, ref Vector3I min, ref Vector3I max, ref Vector3I result)`](VRageMath.Clamp)</td><td></td></tr>
<tr><td>static [`int DistanceManhattan(Vector3I first, Vector3I second)`](VRageMath.DistanceManhattan)</td><td>Manhattan distance (cube distance) X + Y + Z of Abs(first - second)</td></tr>
<tr><td>[`int Dot(ref Vector3I v)`](VRageMath.Dot)</td><td></td></tr>
<tr><td>static [`int Dot(Vector3I vector1, Vector3I vector2)`](VRageMath.Dot)</td><td></td></tr>
<tr><td>static [`int Dot(ref Vector3I vector1, ref Vector3I vector2)`](VRageMath.Dot)</td><td></td></tr>
<tr><td>static [`void Dot(ref Vector3I vector1, ref Vector3I vector2, ref int dot)`](VRageMath.Dot)</td><td></td></tr>
<tr><td>static [`bool TryParseFromString(string p, ref Vector3I vec)`](VRageMath.TryParseFromString)</td><td></td></tr>
<tr><td>[`int Volume()`](VRageMath.Volume)</td><td></td></tr>
<tr><td>static [`IEnumerable<Vector3I> EnumerateRange(Vector3I minInclusive, Vector3I maxExclusive)`](VRageMath.EnumerateRange)</td><td>Enumerate all values in a integer interval (a cuboid). This method is an allocating version of the Vector3I_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.</td></tr>
<tr><td>[`void ToBytes(List<byte> result)`](VRageMath.ToBytes)</td><td></td></tr>
<tr><td>[`bool IsAxisAligned()`](VRageMath.IsAxisAligned)</td><td></td></tr>
</table>
