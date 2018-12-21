← [Index](index)
# Vector3I Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.X"><code>int X</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Y"><code>int Y</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Z"><code>int Z</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Comparer"><code>EqualityComparer Comparer</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.UnitX"><code>Vector3I UnitX</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.UnitY"><code>Vector3I UnitY</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.UnitZ"><code>Vector3I UnitZ</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Zero"><code>Vector3I Zero</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.MaxValue"><code>Vector3I MaxValue</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.MinValue"><code>Vector3I MinValue</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Up"><code>Vector3I Up</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Down"><code>Vector3I Down</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Right"><code>Vector3I Right</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Left"><code>Vector3I Left</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Forward"><code>Vector3I Forward</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Backward"><code>Vector3I Backward</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.One"><code>Vector3I One</code></a>_</td><td></td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Item"><code>int Item</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.IsPowerOfTwo"><code>bool IsPowerOfTwo</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Size"><code>int Size</code></a>_</td><td>How many cubes are in block with this size</td></tr>
<tr><td>_<a href="VRageMath.SizeLong"><code>long SizeLong</code></a>_</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.ToString"><code>string ToString()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Vector3I other)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Object obj)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.GetHashCode"><code>int GetHashCode()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.IsInsideInclusiveEnd"><code>bool IsInsideInclusiveEnd(ref Vector3I min, ref Vector3I max)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.IsInsideInclusiveEnd"><code>bool IsInsideInclusiveEnd(Vector3I min, Vector3I max)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.IsInside"><code>bool IsInside(ref Vector3I inclusiveMin, ref Vector3I exclusiveMax)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.IsInside"><code>bool IsInside(Vector3I inclusiveMin, Vector3I exclusiveMax)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.RectangularDistance"><code>int RectangularDistance(Vector3I otherVector)</code></a>_</td><td>Calculates rectangular distance. It's how many sectors you have to travel to get to other sector from current sector.</td></tr>
<tr><td>_<a href="VRageMath.RectangularLength"><code>int RectangularLength()</code></a>_</td><td>Calculates rectangular distance of this vector, interpreted as a point, from the origin.</td></tr>
<tr><td>_<a href="VRageMath.Length"><code>int Length()</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.BoxIntersects"><code>bool BoxIntersects(Vector3I minA, Vector3I maxA, Vector3I minB, Vector3I maxB)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.BoxIntersects"><code>bool BoxIntersects(ref Vector3I minA, ref Vector3I maxA, ref Vector3I minB, ref Vector3I maxB)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.BoxContains"><code>bool BoxContains(Vector3I boxMin, Vector3I boxMax, Vector3I pt)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.BoxContains"><code>bool BoxContains(ref Vector3I boxMin, ref Vector3I boxMax, ref Vector3I pt)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Min"><code>Vector3I Min(Vector3I value1, Vector3I value2)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Min"><code>void Min(ref Vector3I value1, ref Vector3I value2, ref Vector3I result)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.AbsMin"><code>int AbsMin()</code></a>_</td><td>Returns the component of the vector, whose absolute value is smallest of all the three components.</td></tr>
<tr><td>static _<a href="VRageMath.Max"><code>Vector3I Max(Vector3I value1, Vector3I value2)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Max"><code>void Max(ref Vector3I value1, ref Vector3I value2, ref Vector3I result)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.AbsMax"><code>int AbsMax()</code></a>_</td><td>Returns the component of the vector, whose absolute value is largest of all the three components.</td></tr>
<tr><td>static _<a href="VRageMath.MinMax"><code>void MinMax(ref Vector3I min, ref Vector3I max)</code></a>_</td><td>Separates minimal and maximal values of any two input vectors</td></tr>
<tr><td>_<a href="VRageMath.AxisValue"><code>int AxisValue(Axis axis)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetDominantDirection"><code>CubeFace GetDominantDirection(Vector3I val)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.GetDominantDirectionVector"><code>Vector3I GetDominantDirectionVector(Vector3I val)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.DominantAxisProjection"><code>Vector3I DominantAxisProjection(Vector3I value1)</code></a>_</td><td>Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.</td></tr>
<tr><td>static _<a href="VRageMath.DominantAxisProjection"><code>void DominantAxisProjection(ref Vector3I value1, ref Vector3I result)</code></a>_</td><td>Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved into a user-specified variable.</td></tr>
<tr><td>static _<a href="VRageMath.Sign"><code>Vector3I Sign(Vector3 value)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Sign"><code>Vector3I Sign(Vector3I value)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Round"><code>Vector3I Round(Vector3 value)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Round"><code>Vector3I Round(Vector3D value)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Round"><code>void Round(ref Vector3 v, ref Vector3I r)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Round"><code>void Round(ref Vector3D v, ref Vector3I r)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Floor"><code>Vector3I Floor(Vector3 value)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Floor"><code>Vector3I Floor(Vector3D value)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Floor"><code>void Floor(ref Vector3 v, ref Vector3I r)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Floor"><code>void Floor(ref Vector3D v, ref Vector3I r)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Ceiling"><code>Vector3I Ceiling(Vector3 value)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Trunc"><code>Vector3I Trunc(Vector3 value)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Shift"><code>Vector3I Shift(Vector3I value)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(ref Vector3I position, ref Matrix matrix, ref Vector3I result)</code></a>_</td><td>Transforms a Vector3I by the given Matrix.</td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(ref Vector3I value, ref Quaternion rotation, ref Vector3I result)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>Vector3I Transform(Vector3I value, Quaternion rotation)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>void Transform(ref Vector3I value, ref MatrixI matrix, ref Vector3I result)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>Vector3I Transform(Vector3I value, MatrixI transformation)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>Vector3I Transform(Vector3I value, ref MatrixI transformation)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.TransformNormal"><code>Vector3I TransformNormal(Vector3I value, ref MatrixI transformation)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.TransformNormal"><code>void TransformNormal(ref Vector3I normal, ref Matrix matrix, ref Vector3I result)</code></a>_</td><td>Transforms a vector normal by a matrix.</td></tr>
<tr><td>static _<a href="VRageMath.TransformNormal"><code>void TransformNormal(ref Vector3I normal, ref MatrixI matrix, ref Vector3I result)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Cross"><code>void Cross(ref Vector3I vector1, ref Vector3I vector2, ref Vector3I result)</code></a>_</td><td>Calculates the cross product of two vectors.</td></tr>
<tr><td>_<a href="VRageMath.CompareTo"><code>int CompareTo(Vector3I other)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Abs"><code>Vector3I Abs(Vector3I value)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Abs"><code>void Abs(ref Vector3I value, ref Vector3I result)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Clamp"><code>Vector3I Clamp(Vector3I value1, Vector3I min, Vector3I max)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Clamp"><code>void Clamp(ref Vector3I value1, ref Vector3I min, ref Vector3I max, ref Vector3I result)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.DistanceManhattan"><code>int DistanceManhattan(Vector3I first, Vector3I second)</code></a>_</td><td>Manhattan distance (cube distance) X + Y + Z of Abs(first - second)</td></tr>
<tr><td>_<a href="VRageMath.Dot"><code>int Dot(ref Vector3I v)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Dot"><code>int Dot(Vector3I vector1, Vector3I vector2)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Dot"><code>int Dot(ref Vector3I vector1, ref Vector3I vector2)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Dot"><code>void Dot(ref Vector3I vector1, ref Vector3I vector2, ref int dot)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.TryParseFromString"><code>bool TryParseFromString(string p, ref Vector3I vec)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Volume"><code>int Volume()</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.EnumerateRange"><code>IEnumerable<Vector3I> EnumerateRange(Vector3I minInclusive, Vector3I maxExclusive)</code></a>_</td><td>Enumerate all values in a integer interval (a cuboid). This method is an allocating version of the Vector3I_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.</td></tr>
<tr><td>_<a href="VRageMath.ToBytes"><code>void ToBytes(List<byte> result)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.IsAxisAligned"><code>bool IsAxisAligned()</code></a>_</td><td></td></tr>
</table>
