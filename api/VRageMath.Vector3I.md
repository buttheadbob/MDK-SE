← [Index](index)
# Vector3I Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`X`](VRageMath.X)||
|[`Y`](VRageMath.Y)||
|[`Z`](VRageMath.Z)||
|static [`Comparer`](VRageMath.Comparer)||
|static [`UnitX`](VRageMath.UnitX)||
|static [`UnitY`](VRageMath.UnitY)||
|static [`UnitZ`](VRageMath.UnitZ)||
|static [`Zero`](VRageMath.Zero)||
|static [`MaxValue`](VRageMath.MaxValue)||
|static [`MinValue`](VRageMath.MinValue)||
|static [`Up`](VRageMath.Up)||
|static [`Down`](VRageMath.Down)||
|static [`Right`](VRageMath.Right)||
|static [`Left`](VRageMath.Left)||
|static [`Forward`](VRageMath.Forward)||
|static [`Backward`](VRageMath.Backward)||
|static [`One`](VRageMath.One)||
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
|[`IsInsideInclusiveEnd(ref Vector3I, ref Vector3I)`](VRageMath.IsInsideInclusiveEnd)||
|[`IsInsideInclusiveEnd(Vector3I, Vector3I)`](VRageMath.IsInsideInclusiveEnd)||
|[`IsInside(ref Vector3I, ref Vector3I)`](VRageMath.IsInside)||
|[`IsInside(Vector3I, Vector3I)`](VRageMath.IsInside)||
|[`RectangularDistance(Vector3I)`](VRageMath.RectangularDistance)|Calculates rectangular distance. It's how many sectors you have to travel to get to other sector from current sector.|
|[`RectangularLength()`](VRageMath.RectangularLength)|Calculates rectangular distance of this vector, interpreted as a point, from the origin.|
|[`Length()`](VRageMath.Length)||
|static [`BoxIntersects(Vector3I, Vector3I, Vector3I, Vector3I)`](VRageMath.BoxIntersects)||
|static [`BoxIntersects(ref Vector3I, ref Vector3I, ref Vector3I, ref Vector3I)`](VRageMath.BoxIntersects)||
|static [`BoxContains(Vector3I, Vector3I, Vector3I)`](VRageMath.BoxContains)||
|static [`BoxContains(ref Vector3I, ref Vector3I, ref Vector3I)`](VRageMath.BoxContains)||
|static [`Min(Vector3I, Vector3I)`](VRageMath.Min)||
|static [`Min(ref Vector3I, ref Vector3I, ref Vector3I)`](VRageMath.Min)||
|[`AbsMin()`](VRageMath.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|static [`Max(Vector3I, Vector3I)`](VRageMath.Max)||
|static [`Max(ref Vector3I, ref Vector3I, ref Vector3I)`](VRageMath.Max)||
|[`AbsMax()`](VRageMath.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|static [`MinMax(ref Vector3I, ref Vector3I)`](VRageMath.MinMax)|Separates minimal and maximal values of any two input vectors|
|[`AxisValue(Axis)`](VRageMath.AxisValue)||
|static [`GetDominantDirection(Vector3I)`](VRageMath.GetDominantDirection)||
|static [`GetDominantDirectionVector(Vector3I)`](VRageMath.GetDominantDirectionVector)||
|static [`DominantAxisProjection(Vector3I)`](VRageMath.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|static [`DominantAxisProjection(ref Vector3I, ref Vector3I)`](VRageMath.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved into a user-specified variable.|
|static [`Sign(Vector3)`](VRageMath.Sign)||
|static [`Sign(Vector3I)`](VRageMath.Sign)||
|static [`Round(Vector3)`](VRageMath.Round)||
|static [`Round(Vector3D)`](VRageMath.Round)||
|static [`Round(ref Vector3, ref Vector3I)`](VRageMath.Round)||
|static [`Round(ref Vector3D, ref Vector3I)`](VRageMath.Round)||
|static [`Floor(Vector3)`](VRageMath.Floor)||
|static [`Floor(Vector3D)`](VRageMath.Floor)||
|static [`Floor(ref Vector3, ref Vector3I)`](VRageMath.Floor)||
|static [`Floor(ref Vector3D, ref Vector3I)`](VRageMath.Floor)||
|static [`Ceiling(Vector3)`](VRageMath.Ceiling)||
|static [`Trunc(Vector3)`](VRageMath.Trunc)||
|static [`Shift(Vector3I)`](VRageMath.Shift)||
|static [`Transform(ref Vector3I, ref Matrix, ref Vector3I)`](VRageMath.Transform)|Transforms a Vector3I by the given Matrix.|
|static [`Transform(ref Vector3I, ref Quaternion, ref Vector3I)`](VRageMath.Transform)||
|static [`Transform(Vector3I, Quaternion)`](VRageMath.Transform)||
|static [`Transform(ref Vector3I, ref MatrixI, ref Vector3I)`](VRageMath.Transform)||
|static [`Transform(Vector3I, MatrixI)`](VRageMath.Transform)||
|static [`Transform(Vector3I, ref MatrixI)`](VRageMath.Transform)||
|static [`TransformNormal(Vector3I, ref MatrixI)`](VRageMath.TransformNormal)||
|static [`TransformNormal(ref Vector3I, ref Matrix, ref Vector3I)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|static [`TransformNormal(ref Vector3I, ref MatrixI, ref Vector3I)`](VRageMath.TransformNormal)||
|static [`Cross(ref Vector3I, ref Vector3I, ref Vector3I)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|[`CompareTo(Vector3I)`](VRageMath.CompareTo)||
|static [`Abs(Vector3I)`](VRageMath.Abs)||
|static [`Abs(ref Vector3I, ref Vector3I)`](VRageMath.Abs)||
|static [`Clamp(Vector3I, Vector3I, Vector3I)`](VRageMath.Clamp)||
|static [`Clamp(ref Vector3I, ref Vector3I, ref Vector3I, ref Vector3I)`](VRageMath.Clamp)||
|static [`DistanceManhattan(Vector3I, Vector3I)`](VRageMath.DistanceManhattan)|Manhattan distance (cube distance) X + Y + Z of Abs(first - second)|
|[`Dot(ref Vector3I)`](VRageMath.Dot)||
|static [`Dot(Vector3I, Vector3I)`](VRageMath.Dot)||
|static [`Dot(ref Vector3I, ref Vector3I)`](VRageMath.Dot)||
|static [`Dot(ref Vector3I, ref Vector3I, ref int)`](VRageMath.Dot)||
|static [`TryParseFromString(string, ref Vector3I)`](VRageMath.TryParseFromString)||
|[`Volume()`](VRageMath.Volume)||
|static [`EnumerateRange(Vector3I, Vector3I)`](VRageMath.EnumerateRange)|Enumerate all values in a integer interval (a cuboid). This method is an allocating version of the Vector3I_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.|
|[`ToBytes(List<byte>)`](VRageMath.ToBytes)||
|[`IsAxisAligned()`](VRageMath.IsAxisAligned)||
