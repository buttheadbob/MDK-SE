← [Index](index)
# Vector3L Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`long&nbsp;X`](VRageMath.X)||
|[`long&nbsp;Y`](VRageMath.Y)||
|[`long&nbsp;Z`](VRageMath.Z)||
|static&nbsp;[`EqualityComparer&nbsp;Comparer`](VRageMath.Comparer)||
|static&nbsp;[`Vector3L&nbsp;UnitX`](VRageMath.UnitX)||
|static&nbsp;[`Vector3L&nbsp;UnitY`](VRageMath.UnitY)||
|static&nbsp;[`Vector3L&nbsp;UnitZ`](VRageMath.UnitZ)||
|static&nbsp;[`Vector3L&nbsp;Zero`](VRageMath.Zero)||
|static&nbsp;[`Vector3L&nbsp;MaxValue`](VRageMath.MaxValue)||
|static&nbsp;[`Vector3L&nbsp;MinValue`](VRageMath.MinValue)||
|static&nbsp;[`Vector3L&nbsp;Up`](VRageMath.Up)||
|static&nbsp;[`Vector3L&nbsp;Down`](VRageMath.Down)||
|static&nbsp;[`Vector3L&nbsp;Right`](VRageMath.Right)||
|static&nbsp;[`Vector3L&nbsp;Left`](VRageMath.Left)||
|static&nbsp;[`Vector3L&nbsp;Forward`](VRageMath.Forward)||
|static&nbsp;[`Vector3L&nbsp;Backward`](VRageMath.Backward)||
|static&nbsp;[`Vector3L&nbsp;One`](VRageMath.One)||
### Properties
|Member|Description|
|---|---|
|[`long&nbsp;Item`](VRageMath.Item)||
|[`long&nbsp;Size`](VRageMath.Size)|How many cubes are in block with this size|
|[`long&nbsp;SizeLong`](VRageMath.SizeLong)||
### Methods
|Member|Description|
|---|---|
|[`string&nbsp;ToString()`](VRageMath.ToString)||
|[`bool&nbsp;Equals(Vector3L&nbsp;other)`](VRageMath.Equals)||
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)||
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)||
|[`bool&nbsp;IsInsideInclusiveEnd(ref&nbsp;Vector3L&nbsp;min,&nbsp;ref&nbsp;Vector3L&nbsp;max)`](VRageMath.IsInsideInclusiveEnd)||
|[`bool&nbsp;IsInsideInclusiveEnd(Vector3L&nbsp;min,&nbsp;Vector3L&nbsp;max)`](VRageMath.IsInsideInclusiveEnd)||
|[`bool&nbsp;IsInside(ref&nbsp;Vector3L&nbsp;inclusiveMin,&nbsp;ref&nbsp;Vector3L&nbsp;exclusiveMax)`](VRageMath.IsInside)||
|[`bool&nbsp;IsInside(Vector3L&nbsp;inclusiveMin,&nbsp;Vector3L&nbsp;exclusiveMax)`](VRageMath.IsInside)||
|[`long&nbsp;RectangularDistance(Vector3L&nbsp;otherVector)`](VRageMath.RectangularDistance)|Calculates rectangular distance. It's how many sectors you have to travel to get to other sector from current sector.|
|[`long&nbsp;RectangularLength()`](VRageMath.RectangularLength)|Calculates rectangular distance of this vector, longerpreted as a polong, from the origin.|
|[`long&nbsp;Length()`](VRageMath.Length)||
|static&nbsp;[`bool&nbsp;Boxlongersects(Vector3L&nbsp;minA,&nbsp;Vector3L&nbsp;maxA,&nbsp;Vector3L&nbsp;minB,&nbsp;Vector3L&nbsp;maxB)`](VRageMath.Boxlongersects)||
|static&nbsp;[`bool&nbsp;Boxlongersects(ref&nbsp;Vector3L&nbsp;minA,&nbsp;ref&nbsp;Vector3L&nbsp;maxA,&nbsp;ref&nbsp;Vector3L&nbsp;minB,&nbsp;ref&nbsp;Vector3L&nbsp;maxB)`](VRageMath.Boxlongersects)||
|static&nbsp;[`bool&nbsp;BoxContains(Vector3L&nbsp;boxMin,&nbsp;Vector3L&nbsp;boxMax,&nbsp;Vector3L&nbsp;pt)`](VRageMath.BoxContains)||
|static&nbsp;[`bool&nbsp;BoxContains(ref&nbsp;Vector3L&nbsp;boxMin,&nbsp;ref&nbsp;Vector3L&nbsp;boxMax,&nbsp;ref&nbsp;Vector3L&nbsp;pt)`](VRageMath.BoxContains)||
|static&nbsp;[`Vector3L&nbsp;Min(Vector3L&nbsp;value1,&nbsp;Vector3L&nbsp;value2)`](VRageMath.Min)||
|static&nbsp;[`void&nbsp;Min(ref&nbsp;Vector3L&nbsp;value1,&nbsp;ref&nbsp;Vector3L&nbsp;value2,&nbsp;ref&nbsp;Vector3L&nbsp;result)`](VRageMath.Min)||
|[`long&nbsp;AbsMin()`](VRageMath.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|static&nbsp;[`Vector3L&nbsp;Max(Vector3L&nbsp;value1,&nbsp;Vector3L&nbsp;value2)`](VRageMath.Max)||
|static&nbsp;[`void&nbsp;Max(ref&nbsp;Vector3L&nbsp;value1,&nbsp;ref&nbsp;Vector3L&nbsp;value2,&nbsp;ref&nbsp;Vector3L&nbsp;result)`](VRageMath.Max)||
|[`long&nbsp;AbsMax()`](VRageMath.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|[`long&nbsp;AxisValue(Axis&nbsp;axis)`](VRageMath.AxisValue)||
|static&nbsp;[`CubeFace&nbsp;GetDominantDirection(Vector3L&nbsp;val)`](VRageMath.GetDominantDirection)||
|static&nbsp;[`Vector3L&nbsp;GetDominantDirectionVector(Vector3L&nbsp;val)`](VRageMath.GetDominantDirectionVector)||
|static&nbsp;[`Vector3L&nbsp;DominantAxisProjection(Vector3L&nbsp;value1)`](VRageMath.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|static&nbsp;[`void&nbsp;DominantAxisProjection(ref&nbsp;Vector3L&nbsp;value1,&nbsp;ref&nbsp;Vector3L&nbsp;result)`](VRageMath.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved longo a user-specified variable.|
|static&nbsp;[`Vector3L&nbsp;Sign(Vector3&nbsp;value)`](VRageMath.Sign)||
|static&nbsp;[`Vector3L&nbsp;Sign(Vector3L&nbsp;value)`](VRageMath.Sign)||
|static&nbsp;[`Vector3L&nbsp;Floor(Vector3&nbsp;value)`](VRageMath.Floor)||
|static&nbsp;[`Vector3L&nbsp;Floor(Vector3D&nbsp;value)`](VRageMath.Floor)||
|static&nbsp;[`void&nbsp;Floor(ref&nbsp;Vector3&nbsp;v,&nbsp;ref&nbsp;Vector3L&nbsp;r)`](VRageMath.Floor)||
|static&nbsp;[`void&nbsp;Floor(ref&nbsp;Vector3D&nbsp;v,&nbsp;ref&nbsp;Vector3L&nbsp;r)`](VRageMath.Floor)||
|static&nbsp;[`Vector3L&nbsp;Ceiling(Vector3&nbsp;value)`](VRageMath.Ceiling)||
|static&nbsp;[`Vector3L&nbsp;Trunc(Vector3&nbsp;value)`](VRageMath.Trunc)||
|static&nbsp;[`Vector3L&nbsp;Shift(Vector3L&nbsp;value)`](VRageMath.Shift)||
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector3L&nbsp;position,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;ref&nbsp;Vector3L&nbsp;result)`](VRageMath.Transform)|Transforms a Vector3L by the given Matrix.|
|static&nbsp;[`void&nbsp;Transform(ref&nbsp;Vector3L&nbsp;value,&nbsp;ref&nbsp;Quaternion&nbsp;rotation,&nbsp;ref&nbsp;Vector3L&nbsp;result)`](VRageMath.Transform)||
|static&nbsp;[`Vector3L&nbsp;Transform(Vector3L&nbsp;value,&nbsp;Quaternion&nbsp;rotation)`](VRageMath.Transform)||
|static&nbsp;[`void&nbsp;TransformNormal(ref&nbsp;Vector3L&nbsp;normal,&nbsp;ref&nbsp;Matrix&nbsp;matrix,&nbsp;ref&nbsp;Vector3L&nbsp;result)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|static&nbsp;[`void&nbsp;Cross(ref&nbsp;Vector3L&nbsp;vector1,&nbsp;ref&nbsp;Vector3L&nbsp;vector2,&nbsp;ref&nbsp;Vector3L&nbsp;result)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|[`int&nbsp;CompareTo(Vector3L&nbsp;other)`](VRageMath.CompareTo)||
|static&nbsp;[`Vector3L&nbsp;Abs(Vector3L&nbsp;value)`](VRageMath.Abs)||
|static&nbsp;[`void&nbsp;Abs(ref&nbsp;Vector3L&nbsp;value,&nbsp;ref&nbsp;Vector3L&nbsp;result)`](VRageMath.Abs)||
|static&nbsp;[`Vector3L&nbsp;Clamp(Vector3L&nbsp;value1,&nbsp;Vector3L&nbsp;min,&nbsp;Vector3L&nbsp;max)`](VRageMath.Clamp)||
|static&nbsp;[`void&nbsp;Clamp(ref&nbsp;Vector3L&nbsp;value1,&nbsp;ref&nbsp;Vector3L&nbsp;min,&nbsp;ref&nbsp;Vector3L&nbsp;max,&nbsp;ref&nbsp;Vector3L&nbsp;result)`](VRageMath.Clamp)||
|static&nbsp;[`long&nbsp;DistanceManhattan(Vector3L&nbsp;first,&nbsp;Vector3L&nbsp;second)`](VRageMath.DistanceManhattan)|Manhattan distance (cube distance) X + Y + Z of Abs(first - second)|
|[`long&nbsp;Dot(ref&nbsp;Vector3L&nbsp;v)`](VRageMath.Dot)||
|static&nbsp;[`long&nbsp;Dot(Vector3L&nbsp;vector1,&nbsp;Vector3L&nbsp;vector2)`](VRageMath.Dot)||
|static&nbsp;[`long&nbsp;Dot(ref&nbsp;Vector3L&nbsp;vector1,&nbsp;ref&nbsp;Vector3L&nbsp;vector2)`](VRageMath.Dot)||
|static&nbsp;[`void&nbsp;Dot(ref&nbsp;Vector3L&nbsp;vector1,&nbsp;ref&nbsp;Vector3L&nbsp;vector2,&nbsp;ref&nbsp;long&nbsp;dot)`](VRageMath.Dot)||
|static&nbsp;[`bool&nbsp;TryParseFromString(string&nbsp;p,&nbsp;ref&nbsp;Vector3L&nbsp;vec)`](VRageMath.TryParseFromString)||
|[`long&nbsp;Volume()`](VRageMath.Volume)||
|static&nbsp;[`IEnumerable<Vector3L>&nbsp;EnumerateRange(Vector3L&nbsp;minInclusive,&nbsp;Vector3L&nbsp;maxExclusive)`](VRageMath.EnumerateRange)|Enumerate all values in a longeger longerval (a cuboid). This method is an allocating version of the Vector3L_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.|
|[`void&nbsp;ToBytes(List<byte>&nbsp;result)`](VRageMath.ToBytes)||
