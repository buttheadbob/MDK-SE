← [Index](index)
# Vector3I Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`int&nbsp;X`](VRageMath.X)||
|[`int&nbsp;Y`](VRageMath.Y)||
|[`int&nbsp;Z`](VRageMath.Z)||
|static&nbsp;[`EqualityComparer&nbsp;Comparer`](VRageMath.Comparer)||
|static&nbsp;[`Vector3I&nbsp;UnitX`](VRageMath.UnitX)||
|static&nbsp;[`Vector3I&nbsp;UnitY`](VRageMath.UnitY)||
|static&nbsp;[`Vector3I&nbsp;UnitZ`](VRageMath.UnitZ)||
|static&nbsp;[`Vector3I&nbsp;Zero`](VRageMath.Zero)||
|static&nbsp;[`Vector3I&nbsp;MaxValue`](VRageMath.MaxValue)||
|static&nbsp;[`Vector3I&nbsp;MinValue`](VRageMath.MinValue)||
|static&nbsp;[`Vector3I&nbsp;Up`](VRageMath.Up)||
|static&nbsp;[`Vector3I&nbsp;Down`](VRageMath.Down)||
|static&nbsp;[`Vector3I&nbsp;Right`](VRageMath.Right)||
|static&nbsp;[`Vector3I&nbsp;Left`](VRageMath.Left)||
|static&nbsp;[`Vector3I&nbsp;Forward`](VRageMath.Forward)||
|static&nbsp;[`Vector3I&nbsp;Backward`](VRageMath.Backward)||
|static&nbsp;[`Vector3I&nbsp;One`](VRageMath.One)||
### Properties
|Member|Description|
|---|---|
|[`int&nbsp;Item`](VRageMath.Item)||
|[`bool&nbsp;IsPowerOfTwo`](VRageMath.IsPowerOfTwo)||
|[`int&nbsp;Size`](VRageMath.Size)|How many cubes are in block with this size|
|[`long&nbsp;SizeLong`](VRageMath.SizeLong)||
### Methods
|Member|Description|
|---|---|
|[`string&nbsp;ToString()`](VRageMath.ToString)||
|[`bool&nbsp;Equals(Vector3I&nbsp;other)`](VRageMath.Equals)||
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)||
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)||
|[`bool&nbsp;IsInsideInclusiveEnd(ref&nbsp;Vector3I&nbsp;min,&nbsp;ref&nbsp;Vector3I&nbsp;max)`](VRageMath.IsInsideInclusiveEnd)||
|[`bool&nbsp;IsInsideInclusiveEnd(Vector3I&nbsp;min,&nbsp;Vector3I&nbsp;max)`](VRageMath.IsInsideInclusiveEnd)||
|[`bool&nbsp;IsInside(ref&nbsp;Vector3I&nbsp;inclusiveMin,&nbsp;ref&nbsp;Vector3I&nbsp;exclusiveMax)`](VRageMath.IsInside)||
|[`bool&nbsp;IsInside(Vector3I&nbsp;inclusiveMin,&nbsp;Vector3I&nbsp;exclusiveMax)`](VRageMath.IsInside)||
|[`int&nbsp;RectangularDistance(Vector3I&nbsp;otherVector)`](VRageMath.RectangularDistance)|Calculates rectangular distance. It's how many sectors you have to travel to get to other sector from current sector.|
|[`int&nbsp;RectangularLength()`](VRageMath.RectangularLength)|Calculates rectangular distance of this vector, interpreted as a point, from the origin.|
|[`int&nbsp;Length()`](VRageMath.Length)||
|static&nbsp;[`bool&nbsp;BoxIntersects(Vector3I&nbsp;minA,&nbsp;Vector3I&nbsp;maxA,&nbsp;Vector3I&nbsp;minB,&nbsp;Vector3I&nbsp;maxB)`](VRageMath.BoxIntersects)||
|static&nbsp;[`bool&nbsp;BoxIntersects(ref&nbsp;Vector3I&nbsp;minA,&nbsp;ref&nbsp;Vector3I&nbsp;maxA,&nbsp;ref&nbsp;Vector3I&nbsp;minB,&nbsp;ref&nbsp;Vector3I&nbsp;maxB)`](VRageMath.BoxIntersects)||
|static&nbsp;[`bool&nbsp;BoxContains(Vector3I&nbsp;boxMin,&nbsp;Vector3I&nbsp;boxMax,&nbsp;Vector3I&nbsp;pt)`](VRageMath.BoxContains)||
|static&nbsp;[`bool&nbsp;BoxContains(ref&nbsp;Vector3I&nbsp;boxMin,&nbsp;ref&nbsp;Vector3I&nbsp;boxMax,&nbsp;ref&nbsp;Vector3I&nbsp;pt)`](VRageMath.BoxContains)||
|static&nbsp;[`Vector3I&nbsp;Min(Vector3I&nbsp;value1,&nbsp;Vector3I&nbsp;value2)`](VRageMath.Min)||
|static&nbsp;[`void&nbsp;Min(ref&nbsp;Vector3I&nbsp;value1,&nbsp;ref&nbsp;Vector3I&nbsp;value2,&nbsp;ref&nbsp;Vector3I&nbsp;result)`](VRageMath.Min)||
|[`int&nbsp;AbsMin()`](VRageMath.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|static&nbsp;[`Vector3I&nbsp;Max(Vector3I&nbsp;value1,&nbsp;Vector3I&nbsp;value2)`](VRageMath.Max)||
|static&nbsp;[`void&nbsp;Max(ref&nbsp;Vector3I&nbsp;value1,&nbsp;ref&nbsp;Vector3I&nbsp;value2,&nbsp;ref&nbsp;Vector3I&nbsp;result)`](VRageMath.Max)||
|[`int&nbsp;AbsMax()`](VRageMath.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|static&nbsp;[`void&nbsp;MinMax(ref&nbsp;Vector3I&nbsp;min,&nbsp;ref&nbsp;Vector3I&nbsp;max)`](VRageMath.MinMax)|Separates minimal and maximal values of any two input vectors|
|[`int&nbsp;AxisValue(Axis&nbsp;axis)`](VRageMath.AxisValue)||
|static&nbsp;[`CubeFace&nbsp;GetDominantDirection(Vector3I&nbsp;val)`](VRageMath.GetDominantDirection)||
|static&nbsp;[`Vector3I&nbsp;GetDominantDirectionVector(Vector3I&nbsp;val)`](VRageMath.GetDominantDirectionVector)||
|static&nbsp;[`Vector3I&nbsp;DominantAxisProjection(Vector3I&nbsp;value1)`](VRageMath.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|static&nbsp;[`void&nbsp;DominantAxisProjection(ref&nbsp;Vector3I&nbsp;value1,&nbsp;ref&nbsp;Vector3I&nbsp;result)`](VRageMath.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved into a user-specified variable.|
|static&nbsp;[`Vector3I&nbsp;Sign(Vector3&nbsp;value)`](VRageMath.Sign)||
|static&nbsp;[`Vector3I&nbsp;Sign(Vector3I&nbsp;value)`](VRageMath.Sign)||
|static&nbsp;[`Vector3I&nbsp;Round(Vector3&nbsp;value)`](VRageMath.Round)||
|static&nbsp;[`Vector3I&nbsp;Round(Vector3D&nbsp;value)`](VRageMath.Round)||
|static&nbsp;[`void&nbsp;Round(ref&nbsp;Vector3&nbsp;v,&nbsp;ref&nbsp;Vector3I&nbsp;r)`](VRageMath.Round)||
|static&nbsp;[`void&nbsp;Round(ref&nbsp;Vector3D&nbsp;v,&nbsp;ref&nbsp;Vector3I&nbsp;r)`](VRageMath.Round)||
|static&nbsp;[`Vector3I&nbsp;Floor(Vector3&nbsp;value)`](VRageMath.Floor)||
|static&nbsp;[`Vector3I&nbsp;Floor(Vector3D&nbsp;value)`](VRageMath.Floor)||
|static&nbsp;[`void&nbsp;Floor(ref&nbsp;Vector3&nbsp;v,&nbsp;ref&nbsp;Vector3I&nbsp;r)`](VRageMath.Floor)||
|static&nbsp;[`void&nbsp;Floor(ref&nbsp;Vector3D&nbsp;v,&nbsp;ref&nbsp;Vector3I&nbsp;r)`](VRageMath.Floor)||
|static&nbsp;[`Vector3I&nbsp;Ceiling(Vector3&nbsp;value)`](VRageMath.Ceiling)||
|static&nbsp;[`Vector3I&nbsp;Trunc(Vector3&nbsp;value)`](VRageMath.Trunc)||
|static&nbsp;[`Vector3I&nbsp;Shift(Vector3I&nbsp;value)`](VRageMath.Shift)||
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector3I&nbsp;position,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;ref&nbsp;Vector3I&nbsp;result)`](VRageMath.Transform)|Transforms a Vector3I by the given Matrix.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector3I&nbsp;value,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;ref&nbsp;Vector3I&nbsp;result)`](VRageMath.Transform)||
|static&nbsp;[`Vector3I&nbsp;Transform(Vector3I&nbsp;value,&nbsp;Quaternion&nbsp;rotation)`](VRageMath.Transform)||
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector3I&nbsp;value,&nbsp;ref&nbsp;MatrixI&nbsp;matrix,&nbsp;ref&nbsp;Vector3I&nbsp;result)`](VRageMath.Transform)||
|static&nbsp;[`Vector3I&nbsp;Transform(Vector3I&nbsp;value,&nbsp;MatrixI&nbsp;transformation)`](VRageMath.Transform)||
|static&nbsp;[`Vector3I&nbsp;Transform(Vector3I&nbsp;value,&nbsp;ref&nbsp;MatrixI&nbsp;transformation)`](VRageMath.Transform)||
|static&nbsp;[`Vector3I&nbsp;TransformNormal(Vector3I&nbsp;value,&nbsp;ref&nbsp;MatrixI&nbsp;transformation)`](VRageMath.TransformNormal)||
|static&nbsp;[`void&nbsp;TransformNormal(ref&nbsp;Vector3I&nbsp;normal,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;ref&nbsp;Vector3I&nbsp;result)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|static&nbsp;[`void&nbsp;TransformNormal(ref&nbsp;Vector3I&nbsp;normal,&nbsp;ref&nbsp;MatrixI&nbsp;matrix,&nbsp;ref&nbsp;Vector3I&nbsp;result)`](VRageMath.TransformNormal)||
|static&nbsp;[`void&nbsp;Cross(ref&nbsp;Vector3I&nbsp;vector1,&nbsp;ref&nbsp;Vector3I&nbsp;vector2,&nbsp;ref&nbsp;Vector3I&nbsp;result)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|[`int&nbsp;CompareTo(Vector3I&nbsp;other)`](VRageMath.CompareTo)||
|static&nbsp;[`Vector3I&nbsp;Abs(Vector3I&nbsp;value)`](VRageMath.Abs)||
|static&nbsp;[`void&nbsp;Abs(ref&nbsp;Vector3I&nbsp;value,&nbsp;ref&nbsp;Vector3I&nbsp;result)`](VRageMath.Abs)||
|static&nbsp;[`Vector3I&nbsp;Clamp(Vector3I&nbsp;value1,&nbsp;Vector3I&nbsp;min,&nbsp;Vector3I&nbsp;max)`](VRageMath.Clamp)||
|static&nbsp;[`void&nbsp;Clamp(ref&nbsp;Vector3I&nbsp;value1,&nbsp;ref&nbsp;Vector3I&nbsp;min,&nbsp;ref&nbsp;Vector3I&nbsp;max,&nbsp;ref&nbsp;Vector3I&nbsp;result)`](VRageMath.Clamp)||
|static&nbsp;[`int&nbsp;DistanceManhattan(Vector3I&nbsp;first,&nbsp;Vector3I&nbsp;second)`](VRageMath.DistanceManhattan)|Manhattan distance (cube distance) X + Y + Z of Abs(first - second)|
|[`int&nbsp;Dot(ref&nbsp;Vector3I&nbsp;v)`](VRageMath.Dot)||
|static&nbsp;[`int&nbsp;Dot(Vector3I&nbsp;vector1,&nbsp;Vector3I&nbsp;vector2)`](VRageMath.Dot)||
|static&nbsp;[`int&nbsp;Dot(ref&nbsp;Vector3I&nbsp;vector1,&nbsp;ref&nbsp;Vector3I&nbsp;vector2)`](VRageMath.Dot)||
|static&nbsp;[`void&nbsp;Dot(ref&nbsp;Vector3I&nbsp;vector1,&nbsp;ref&nbsp;Vector3I&nbsp;vector2,&nbsp;ref&nbsp;int&nbsp;dot)`](VRageMath.Dot)||
|static&nbsp;[`bool&nbsp;TryParseFromString(string&nbsp;p,&nbsp;ref&nbsp;Vector3I&nbsp;vec)`](VRageMath.TryParseFromString)||
|[`int&nbsp;Volume()`](VRageMath.Volume)||
|static&nbsp;[`IEnumerable<Vector3I>&nbsp;EnumerateRange(Vector3I&nbsp;minInclusive,&nbsp;Vector3I&nbsp;maxExclusive)`](VRageMath.EnumerateRange)|Enumerate all values in a integer interval (a cuboid). This method is an allocating version of the Vector3I_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.|
|[`void&nbsp;ToBytes(List<byte>&nbsp;result)`](VRageMath.ToBytes)||
|[`bool&nbsp;IsAxisAligned()`](VRageMath.IsAxisAligned)||
