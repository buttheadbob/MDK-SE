← [Index](index)
# Vector3L Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
<table style="width:100%;display:table">
<tr><td>[`long X`](VRageMath.X)</td><td></td></tr>
<tr><td>[`long Y`](VRageMath.Y)</td><td></td></tr>
<tr><td>[`long Z`](VRageMath.Z)</td><td></td></tr>
<tr><td>static [`EqualityComparer Comparer`](VRageMath.Comparer)</td><td></td></tr>
<tr><td>static [`Vector3L UnitX`](VRageMath.UnitX)</td><td></td></tr>
<tr><td>static [`Vector3L UnitY`](VRageMath.UnitY)</td><td></td></tr>
<tr><td>static [`Vector3L UnitZ`](VRageMath.UnitZ)</td><td></td></tr>
<tr><td>static [`Vector3L Zero`](VRageMath.Zero)</td><td></td></tr>
<tr><td>static [`Vector3L MaxValue`](VRageMath.MaxValue)</td><td></td></tr>
<tr><td>static [`Vector3L MinValue`](VRageMath.MinValue)</td><td></td></tr>
<tr><td>static [`Vector3L Up`](VRageMath.Up)</td><td></td></tr>
<tr><td>static [`Vector3L Down`](VRageMath.Down)</td><td></td></tr>
<tr><td>static [`Vector3L Right`](VRageMath.Right)</td><td></td></tr>
<tr><td>static [`Vector3L Left`](VRageMath.Left)</td><td></td></tr>
<tr><td>static [`Vector3L Forward`](VRageMath.Forward)</td><td></td></tr>
<tr><td>static [`Vector3L Backward`](VRageMath.Backward)</td><td></td></tr>
<tr><td>static [`Vector3L One`](VRageMath.One)</td><td></td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>[`long Item`](VRageMath.Item)</td><td></td></tr>
<tr><td>[`long Size`](VRageMath.Size)</td><td>How many cubes are in block with this size</td></tr>
<tr><td>[`long SizeLong`](VRageMath.SizeLong)</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>[`string ToString()`](VRageMath.ToString)</td><td></td></tr>
<tr><td>[`bool Equals(Vector3L other)`](VRageMath.Equals)</td><td></td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td></td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td></td></tr>
<tr><td>[`bool IsInsideInclusiveEnd(ref Vector3L min, ref Vector3L max)`](VRageMath.IsInsideInclusiveEnd)</td><td></td></tr>
<tr><td>[`bool IsInsideInclusiveEnd(Vector3L min, Vector3L max)`](VRageMath.IsInsideInclusiveEnd)</td><td></td></tr>
<tr><td>[`bool IsInside(ref Vector3L inclusiveMin, ref Vector3L exclusiveMax)`](VRageMath.IsInside)</td><td></td></tr>
<tr><td>[`bool IsInside(Vector3L inclusiveMin, Vector3L exclusiveMax)`](VRageMath.IsInside)</td><td></td></tr>
<tr><td>[`long RectangularDistance(Vector3L otherVector)`](VRageMath.RectangularDistance)</td><td>Calculates rectangular distance. It's how many sectors you have to travel to get to other sector from current sector.</td></tr>
<tr><td>[`long RectangularLength()`](VRageMath.RectangularLength)</td><td>Calculates rectangular distance of this vector, longerpreted as a polong, from the origin.</td></tr>
<tr><td>[`long Length()`](VRageMath.Length)</td><td></td></tr>
<tr><td>static [`bool Boxlongersects(Vector3L minA, Vector3L maxA, Vector3L minB, Vector3L maxB)`](VRageMath.Boxlongersects)</td><td></td></tr>
<tr><td>static [`bool Boxlongersects(ref Vector3L minA, ref Vector3L maxA, ref Vector3L minB, ref Vector3L maxB)`](VRageMath.Boxlongersects)</td><td></td></tr>
<tr><td>static [`bool BoxContains(Vector3L boxMin, Vector3L boxMax, Vector3L pt)`](VRageMath.BoxContains)</td><td></td></tr>
<tr><td>static [`bool BoxContains(ref Vector3L boxMin, ref Vector3L boxMax, ref Vector3L pt)`](VRageMath.BoxContains)</td><td></td></tr>
<tr><td>static [`Vector3L Min(Vector3L value1, Vector3L value2)`](VRageMath.Min)</td><td></td></tr>
<tr><td>static [`void Min(ref Vector3L value1, ref Vector3L value2, ref Vector3L result)`](VRageMath.Min)</td><td></td></tr>
<tr><td>[`long AbsMin()`](VRageMath.AbsMin)</td><td>Returns the component of the vector, whose absolute value is smallest of all the three components.</td></tr>
<tr><td>static [`Vector3L Max(Vector3L value1, Vector3L value2)`](VRageMath.Max)</td><td></td></tr>
<tr><td>static [`void Max(ref Vector3L value1, ref Vector3L value2, ref Vector3L result)`](VRageMath.Max)</td><td></td></tr>
<tr><td>[`long AbsMax()`](VRageMath.AbsMax)</td><td>Returns the component of the vector, whose absolute value is largest of all the three components.</td></tr>
<tr><td>[`long AxisValue(Axis axis)`](VRageMath.AxisValue)</td><td></td></tr>
<tr><td>static [`CubeFace GetDominantDirection(Vector3L val)`](VRageMath.GetDominantDirection)</td><td></td></tr>
<tr><td>static [`Vector3L GetDominantDirectionVector(Vector3L val)`](VRageMath.GetDominantDirectionVector)</td><td></td></tr>
<tr><td>static [`Vector3L DominantAxisProjection(Vector3L value1)`](VRageMath.DominantAxisProjection)</td><td>Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.</td></tr>
<tr><td>static [`void DominantAxisProjection(ref Vector3L value1, ref Vector3L result)`](VRageMath.DominantAxisProjection)</td><td>Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved longo a user-specified variable.</td></tr>
<tr><td>static [`Vector3L Sign(Vector3 value)`](VRageMath.Sign)</td><td></td></tr>
<tr><td>static [`Vector3L Sign(Vector3L value)`](VRageMath.Sign)</td><td></td></tr>
<tr><td>static [`Vector3L Floor(Vector3 value)`](VRageMath.Floor)</td><td></td></tr>
<tr><td>static [`Vector3L Floor(Vector3D value)`](VRageMath.Floor)</td><td></td></tr>
<tr><td>static [`void Floor(ref Vector3 v, ref Vector3L r)`](VRageMath.Floor)</td><td></td></tr>
<tr><td>static [`void Floor(ref Vector3D v, ref Vector3L r)`](VRageMath.Floor)</td><td></td></tr>
<tr><td>static [`Vector3L Ceiling(Vector3 value)`](VRageMath.Ceiling)</td><td></td></tr>
<tr><td>static [`Vector3L Trunc(Vector3 value)`](VRageMath.Trunc)</td><td></td></tr>
<tr><td>static [`Vector3L Shift(Vector3L value)`](VRageMath.Shift)</td><td></td></tr>
<tr><td>static [`void Transform(ref Vector3L position, ref Matrix matrix, ref Vector3L result)`](VRageMath.Transform)</td><td>Transforms a Vector3L by the given Matrix.</td></tr>
<tr><td>static [`void Transform(ref Vector3L value, ref Quaternion rotation, ref Vector3L result)`](VRageMath.Transform)</td><td></td></tr>
<tr><td>static [`Vector3L Transform(Vector3L value, Quaternion rotation)`](VRageMath.Transform)</td><td></td></tr>
<tr><td>static [`void TransformNormal(ref Vector3L normal, ref Matrix matrix, ref Vector3L result)`](VRageMath.TransformNormal)</td><td>Transforms a vector normal by a matrix.</td></tr>
<tr><td>static [`void Cross(ref Vector3L vector1, ref Vector3L vector2, ref Vector3L result)`](VRageMath.Cross)</td><td>Calculates the cross product of two vectors.</td></tr>
<tr><td>[`int CompareTo(Vector3L other)`](VRageMath.CompareTo)</td><td></td></tr>
<tr><td>static [`Vector3L Abs(Vector3L value)`](VRageMath.Abs)</td><td></td></tr>
<tr><td>static [`void Abs(ref Vector3L value, ref Vector3L result)`](VRageMath.Abs)</td><td></td></tr>
<tr><td>static [`Vector3L Clamp(Vector3L value1, Vector3L min, Vector3L max)`](VRageMath.Clamp)</td><td></td></tr>
<tr><td>static [`void Clamp(ref Vector3L value1, ref Vector3L min, ref Vector3L max, ref Vector3L result)`](VRageMath.Clamp)</td><td></td></tr>
<tr><td>static [`long DistanceManhattan(Vector3L first, Vector3L second)`](VRageMath.DistanceManhattan)</td><td>Manhattan distance (cube distance) X + Y + Z of Abs(first - second)</td></tr>
<tr><td>[`long Dot(ref Vector3L v)`](VRageMath.Dot)</td><td></td></tr>
<tr><td>static [`long Dot(Vector3L vector1, Vector3L vector2)`](VRageMath.Dot)</td><td></td></tr>
<tr><td>static [`long Dot(ref Vector3L vector1, ref Vector3L vector2)`](VRageMath.Dot)</td><td></td></tr>
<tr><td>static [`void Dot(ref Vector3L vector1, ref Vector3L vector2, ref long dot)`](VRageMath.Dot)</td><td></td></tr>
<tr><td>static [`bool TryParseFromString(string p, ref Vector3L vec)`](VRageMath.TryParseFromString)</td><td></td></tr>
<tr><td>[`long Volume()`](VRageMath.Volume)</td><td></td></tr>
<tr><td>static [`IEnumerable<Vector3L> EnumerateRange(Vector3L minInclusive, Vector3L maxExclusive)`](VRageMath.EnumerateRange)</td><td>Enumerate all values in a longeger longerval (a cuboid). This method is an allocating version of the Vector3L_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.</td></tr>
<tr><td>[`void ToBytes(List<byte> result)`](VRageMath.ToBytes)</td><td></td></tr>
</table>
