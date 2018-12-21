← [Index](Api-Index)
# Vector3I Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`X`](VRageMath.X)||
|[`Y`](VRageMath.Y)||
|[`Z`](VRageMath.Z)||
|[`Comparer`](VRageMath.Comparer)||
|[`UnitX`](VRageMath.UnitX)||
|[`UnitY`](VRageMath.UnitY)||
|[`UnitZ`](VRageMath.UnitZ)||
|[`Zero`](VRageMath.Zero)||
|[`MaxValue`](VRageMath.MaxValue)||
|[`MinValue`](VRageMath.MinValue)||
|[`Up`](VRageMath.Up)||
|[`Down`](VRageMath.Down)||
|[`Right`](VRageMath.Right)||
|[`Left`](VRageMath.Left)||
|[`Forward`](VRageMath.Forward)||
|[`Backward`](VRageMath.Backward)||
|[`One`](VRageMath.One)||
### Properties
|Member|Description|
|---|---|
|[`Item`](VRageMath.Item)||
|[`IsPowerOfTwo`](VRageMath.IsPowerOfTwo)||
|[`Size`](VRageMath.Size)|How many cubes are in block with this size|
|[`SizeLong`](VRageMath.SizeLong)||
### Methods
|Member|Description|
|---|---|
|[`ToString()`](VRageMath.ToString)||
|[`Equals(Vector3I)`](VRageMath.Equals)||
|[`Equals(Object)`](VRageMath.Equals)||
|[`GetHashCode()`](VRageMath.GetHashCode)||
|[`IsInsideInclusiveEnd(ref Vector3I, ref Vector3I)`](VRageMath.IsInsideInclusiveEnd)||
|[`IsInsideInclusiveEnd(Vector3I, Vector3I)`](VRageMath.IsInsideInclusiveEnd)||
|[`IsInside(ref Vector3I, ref Vector3I)`](VRageMath.IsInside)||
|[`IsInside(Vector3I, Vector3I)`](VRageMath.IsInside)||
|[`RectangularDistance(Vector3I)`](VRageMath.RectangularDistance)|Calculates rectangular distance. It's how many sectors you have to travel to get to other sector from current sector.|
|[`RectangularLength()`](VRageMath.RectangularLength)|Calculates rectangular distance of this vector, interpreted as a point, from the origin.|
|[`Length()`](VRageMath.Length)||
|[`BoxIntersects(Vector3I, Vector3I, Vector3I, Vector3I)`](VRageMath.BoxIntersects)||
|[`BoxIntersects(ref Vector3I, ref Vector3I, ref Vector3I, ref Vector3I)`](VRageMath.BoxIntersects)||
|[`BoxContains(Vector3I, Vector3I, Vector3I)`](VRageMath.BoxContains)||
|[`BoxContains(ref Vector3I, ref Vector3I, ref Vector3I)`](VRageMath.BoxContains)||
|[`Min(Vector3I, Vector3I)`](VRageMath.Min)||
|[`Min(ref Vector3I, ref Vector3I, ref Vector3I)`](VRageMath.Min)||
|[`AbsMin()`](VRageMath.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|[`Max(Vector3I, Vector3I)`](VRageMath.Max)||
|[`Max(ref Vector3I, ref Vector3I, ref Vector3I)`](VRageMath.Max)||
|[`AbsMax()`](VRageMath.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|[`MinMax(ref Vector3I, ref Vector3I)`](VRageMath.MinMax)|Separates minimal and maximal values of any two input vectors|
|[`AxisValue(Axis)`](VRageMath.AxisValue)||
|[`GetDominantDirection(Vector3I)`](VRageMath.GetDominantDirection)||
|[`GetDominantDirectionVector(Vector3I)`](VRageMath.GetDominantDirectionVector)||
|[`DominantAxisProjection(Vector3I)`](VRageMath.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|[`DominantAxisProjection(ref Vector3I, ref Vector3I)`](VRageMath.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved into a user-specified variable.|
|[`Sign(Vector3)`](VRageMath.Sign)||
|[`Sign(Vector3I)`](VRageMath.Sign)||
|[`Round(Vector3)`](VRageMath.Round)||
|[`Round(Vector3D)`](VRageMath.Round)||
|[`Round(ref Vector3, ref Vector3I)`](VRageMath.Round)||
|[`Round(ref Vector3D, ref Vector3I)`](VRageMath.Round)||
|[`Floor(Vector3)`](VRageMath.Floor)||
|[`Floor(Vector3D)`](VRageMath.Floor)||
|[`Floor(ref Vector3, ref Vector3I)`](VRageMath.Floor)||
|[`Floor(ref Vector3D, ref Vector3I)`](VRageMath.Floor)||
|[`Ceiling(Vector3)`](VRageMath.Ceiling)||
|[`Trunc(Vector3)`](VRageMath.Trunc)||
|[`Shift(Vector3I)`](VRageMath.Shift)||
|[`Transform(ref Vector3I, ref Matrix, ref Vector3I)`](VRageMath.Transform)|Transforms a Vector3I by the given Matrix.|
|[`Transform(ref Vector3I, ref Quaternion, ref Vector3I)`](VRageMath.Transform)||
|[`Transform(Vector3I, Quaternion)`](VRageMath.Transform)||
|[`Transform(ref Vector3I, ref MatrixI, ref Vector3I)`](VRageMath.Transform)||
|[`Transform(Vector3I, MatrixI)`](VRageMath.Transform)||
|[`Transform(Vector3I, ref MatrixI)`](VRageMath.Transform)||
|[`TransformNormal(Vector3I, ref MatrixI)`](VRageMath.TransformNormal)||
|[`TransformNormal(ref Vector3I, ref Matrix, ref Vector3I)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|[`TransformNormal(ref Vector3I, ref MatrixI, ref Vector3I)`](VRageMath.TransformNormal)||
|[`Cross(ref Vector3I, ref Vector3I, ref Vector3I)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|[`CompareTo(Vector3I)`](VRageMath.CompareTo)||
|[`Abs(Vector3I)`](VRageMath.Abs)||
|[`Abs(ref Vector3I, ref Vector3I)`](VRageMath.Abs)||
|[`Clamp(Vector3I, Vector3I, Vector3I)`](VRageMath.Clamp)||
|[`Clamp(ref Vector3I, ref Vector3I, ref Vector3I, ref Vector3I)`](VRageMath.Clamp)||
|[`DistanceManhattan(Vector3I, Vector3I)`](VRageMath.DistanceManhattan)|Manhattan distance (cube distance) X + Y + Z of Abs(first - second)|
|[`Dot(ref Vector3I)`](VRageMath.Dot)||
|[`Dot(Vector3I, Vector3I)`](VRageMath.Dot)||
|[`Dot(ref Vector3I, ref Vector3I)`](VRageMath.Dot)||
|[`Dot(ref Vector3I, ref Vector3I, ref int)`](VRageMath.Dot)||
|[`TryParseFromString(string, ref Vector3I)`](VRageMath.TryParseFromString)||
|[`Volume()`](VRageMath.Volume)||
|[`EnumerateRange(Vector3I, Vector3I)`](VRageMath.EnumerateRange)|Enumerate all values in a integer interval (a cuboid). This method is an allocating version of the Vector3I_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.|
|[`ToBytes(List<byte>)`](VRageMath.ToBytes)||
|[`IsAxisAligned()`](VRageMath.IsAxisAligned)||
