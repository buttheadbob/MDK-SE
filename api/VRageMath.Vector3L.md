← [Index](index)
# Vector3L Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.X"><code>long X</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Y"><code>long Y</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Z"><code>long Z</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Comparer"><code>EqualityComparer Comparer</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.UnitX"><code>Vector3L UnitX</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.UnitY"><code>Vector3L UnitY</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.UnitZ"><code>Vector3L UnitZ</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Zero"><code>Vector3L Zero</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.MaxValue"><code>Vector3L MaxValue</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.MinValue"><code>Vector3L MinValue</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Up"><code>Vector3L Up</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Down"><code>Vector3L Down</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Right"><code>Vector3L Right</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Left"><code>Vector3L Left</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Forward"><code>Vector3L Forward</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Backward"><code>Vector3L Backward</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.One"><code>Vector3L One</code></a>_</td><td></td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Item"><code>long Item</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Size"><code>long Size</code></a>_</td><td>How many cubes are in block with this size</td></tr>
<tr><td>_<a href="VRageMath.SizeLong"><code>long SizeLong</code></a>_</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.ToString"><code>string ToString()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Vector3L other)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Object obj)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.GetHashCode"><code>int GetHashCode()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.IsInsideInclusiveEnd"><code>bool IsInsideInclusiveEnd(ref Vector3L min, ref Vector3L max)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.IsInsideInclusiveEnd"><code>bool IsInsideInclusiveEnd(Vector3L min, Vector3L max)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.IsInside"><code>bool IsInside(ref Vector3L inclusiveMin, ref Vector3L exclusiveMax)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.IsInside"><code>bool IsInside(Vector3L inclusiveMin, Vector3L exclusiveMax)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.RectangularDistance"><code>long RectangularDistance(Vector3L otherVector)</code></a>_</td><td>Calculates rectangular distance. It's how many sectors you have to travel to get to other sector from current sector.</td></tr>
<tr><td>_<a href="VRageMath.RectangularLength"><code>long RectangularLength()</code></a>_</td><td>Calculates rectangular distance of this vector, longerpreted as a polong, from the origin.</td></tr>
<tr><td>_<a href="VRageMath.Length"><code>long Length()</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Boxlongersects"><code>bool Boxlongersects(Vector3L minA, Vector3L maxA, Vector3L minB, Vector3L maxB)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Boxlongersects"><code>bool Boxlongersects(ref Vector3L minA, ref Vector3L maxA, ref Vector3L minB, ref Vector3L maxB)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.BoxContains"><code>bool BoxContains(Vector3L boxMin, Vector3L boxMax, Vector3L pt)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.BoxContains"><code>bool BoxContains(ref Vector3L boxMin, ref Vector3L boxMax, ref Vector3L pt)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Min"><code>Vector3L Min(Vector3L value1, Vector3L value2)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Min"><code>void Min(ref Vector3L value1, ref Vector3L value2, ref Vector3L result)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.AbsMin"><code>long AbsMin()</code></a>_</td><td>Returns the component of the vector, whose absolute value is smallest of all the three components.</td></tr>
<tr><td>static _<a href="VRageMath.Max"><code>Vector3L Max(Vector3L value1, Vector3L value2)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Max"><code>void Max(ref Vector3L value1, ref Vector3L value2, ref Vector3L result)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.AbsMax"><code>long AbsMax()</code></a>_</td><td>Returns the component of the vector, whose absolute value is largest of all the three components.</td></tr>
<tr><td>_<a href="VRageMath.AxisValue"><code>long AxisValue(Axis axis)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetDominantDirection"><code>CubeFace GetDominantDirection(Vector3L val)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetDominantDirectionVector"><code>Vector3L GetDominantDirectionVector(Vector3L val)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.DominantAxisProjection"><code>Vector3L DominantAxisProjection(Vector3L value1)</code></a>_</td><td>Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.</td></tr>
<tr><td>static _<a href="VRageMath.DominantAxisProjection"><code>void DominantAxisProjection(ref Vector3L value1, ref Vector3L result)</code></a>_</td><td>Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved longo a user-specified variable.</td></tr>
<tr><td>static _<a href="VRageMath.Sign"><code>Vector3L Sign(Vector3 value)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Sign"><code>Vector3L Sign(Vector3L value)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Floor"><code>Vector3L Floor(Vector3 value)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Floor"><code>Vector3L Floor(Vector3D value)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Floor"><code>void Floor(ref Vector3 v, ref Vector3L r)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Floor"><code>void Floor(ref Vector3D v, ref Vector3L r)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Ceiling"><code>Vector3L Ceiling(Vector3 value)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Trunc"><code>Vector3L Trunc(Vector3 value)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Shift"><code>Vector3L Shift(Vector3L value)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(ref Vector3L position, ref Matrix matrix, ref Vector3L result)</code></a>_</td><td>Transforms a Vector3L by the given Matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(ref Vector3L value, ref Quaternion rotation, ref Vector3L result)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>Vector3L Transform(Vector3L value, Quaternion rotation)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.TransformNormal"><code>void TransformNormal(ref Vector3L normal, ref Matrix matrix, ref Vector3L result)</code></a>_</td><td>Transforms a vector normal by a matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Cross"><code>void Cross(ref Vector3L vector1, ref Vector3L vector2, ref Vector3L result)</code></a>_</td><td>Calculates the cross product of two vectors.</td></tr>
<tr><td>_<a href="VRageMath.CompareTo"><code>int CompareTo(Vector3L other)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Abs"><code>Vector3L Abs(Vector3L value)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Abs"><code>void Abs(ref Vector3L value, ref Vector3L result)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Clamp"><code>Vector3L Clamp(Vector3L value1, Vector3L min, Vector3L max)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Clamp"><code>void Clamp(ref Vector3L value1, ref Vector3L min, ref Vector3L max, ref Vector3L result)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.DistanceManhattan"><code>long DistanceManhattan(Vector3L first, Vector3L second)</code></a>_</td><td>Manhattan distance (cube distance) X + Y + Z of Abs(first - second)</td></tr>
<tr><td>_<a href="VRageMath.Dot"><code>long Dot(ref Vector3L v)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Dot"><code>long Dot(Vector3L vector1, Vector3L vector2)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Dot"><code>long Dot(ref Vector3L vector1, ref Vector3L vector2)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Dot"><code>void Dot(ref Vector3L vector1, ref Vector3L vector2, ref long dot)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.TryParseFromString"><code>bool TryParseFromString(string p, ref Vector3L vec)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Volume"><code>long Volume()</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.EnumerateRange"><code>IEnumerable<Vector3L> EnumerateRange(Vector3L minInclusive, Vector3L maxExclusive)</code></a>_</td><td>Enumerate all values in a longeger longerval (a cuboid). This method is an allocating version of the Vector3L_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.</td></tr>
<tr><td>_<a href="VRageMath.ToBytes"><code>void ToBytes(List<byte> result)</code></a>_</td><td></td></tr>
</table>
