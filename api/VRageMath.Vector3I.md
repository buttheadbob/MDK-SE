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
|static [`VRageMath.EqualityComparer Comparer`](VRageMath.Comparer)||
|static [`VRageMath.Vector3I UnitX`](VRageMath.UnitX)||
|static [`VRageMath.Vector3I UnitY`](VRageMath.UnitY)||
|static [`VRageMath.Vector3I UnitZ`](VRageMath.UnitZ)||
|static [`VRageMath.Vector3I Zero`](VRageMath.Zero)||
|static [`VRageMath.Vector3I MaxValue`](VRageMath.MaxValue)||
|static [`VRageMath.Vector3I MinValue`](VRageMath.MinValue)||
|static [`VRageMath.Vector3I Up`](VRageMath.Up)||
|static [`VRageMath.Vector3I Down`](VRageMath.Down)||
|static [`VRageMath.Vector3I Right`](VRageMath.Right)||
|static [`VRageMath.Vector3I Left`](VRageMath.Left)||
|static [`VRageMath.Vector3I Forward`](VRageMath.Forward)||
|static [`VRageMath.Vector3I Backward`](VRageMath.Backward)||
|static [`VRageMath.Vector3I One`](VRageMath.One)||
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
|[`bool Equals(VRageMath.Vector3I)`](VRageMath.Equals)||
|[`bool Equals(System.Object)`](VRageMath.Equals)||
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`bool IsInsideInclusiveEnd(ref VRageMath.Vector3I, ref VRageMath.Vector3I)`](VRageMath.IsInsideInclusiveEnd)||
|[`bool IsInsideInclusiveEnd(VRageMath.Vector3I, VRageMath.Vector3I)`](VRageMath.IsInsideInclusiveEnd)||
|[`bool IsInside(ref VRageMath.Vector3I, ref VRageMath.Vector3I)`](VRageMath.IsInside)||
|[`bool IsInside(VRageMath.Vector3I, VRageMath.Vector3I)`](VRageMath.IsInside)||
|[`int RectangularDistance(VRageMath.Vector3I)`](VRageMath.RectangularDistance)|Calculates rectangular distance. It's how many sectors you have to travel to get to other sector from current sector.|
|[`int RectangularLength()`](VRageMath.RectangularLength)|Calculates rectangular distance of this vector, interpreted as a point, from the origin.|
|[`int Length()`](VRageMath.Length)||
|static [`bool BoxIntersects(VRageMath.Vector3I, VRageMath.Vector3I, VRageMath.Vector3I, VRageMath.Vector3I)`](VRageMath.BoxIntersects)||
|static [`bool BoxIntersects(ref VRageMath.Vector3I, ref VRageMath.Vector3I, ref VRageMath.Vector3I, ref VRageMath.Vector3I)`](VRageMath.BoxIntersects)||
|static [`bool BoxContains(VRageMath.Vector3I, VRageMath.Vector3I, VRageMath.Vector3I)`](VRageMath.BoxContains)||
|static [`bool BoxContains(ref VRageMath.Vector3I, ref VRageMath.Vector3I, ref VRageMath.Vector3I)`](VRageMath.BoxContains)||
|static [`VRageMath.Vector3I Min(VRageMath.Vector3I, VRageMath.Vector3I)`](VRageMath.Min)||
|static [`void Min(ref VRageMath.Vector3I, ref VRageMath.Vector3I, ref VRageMath.Vector3I)`](VRageMath.Min)||
|[`int AbsMin()`](VRageMath.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|static [`VRageMath.Vector3I Max(VRageMath.Vector3I, VRageMath.Vector3I)`](VRageMath.Max)||
|static [`void Max(ref VRageMath.Vector3I, ref VRageMath.Vector3I, ref VRageMath.Vector3I)`](VRageMath.Max)||
|[`int AbsMax()`](VRageMath.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|static [`void MinMax(ref VRageMath.Vector3I, ref VRageMath.Vector3I)`](VRageMath.MinMax)|Separates minimal and maximal values of any two input vectors|
|[`int AxisValue(VRageMath.Axis)`](VRageMath.AxisValue)||
|static [`VRageMath.CubeFace GetDominantDirection(VRageMath.Vector3I)`](VRageMath.GetDominantDirection)||
|static [`VRageMath.Vector3I GetDominantDirectionVector(VRageMath.Vector3I)`](VRageMath.GetDominantDirectionVector)||
|static [`VRageMath.Vector3I DominantAxisProjection(VRageMath.Vector3I)`](VRageMath.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|static [`void DominantAxisProjection(ref VRageMath.Vector3I, ref VRageMath.Vector3I)`](VRageMath.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved into a user-specified variable.|
|static [`VRageMath.Vector3I Sign(VRageMath.Vector3)`](VRageMath.Sign)||
|static [`VRageMath.Vector3I Sign(VRageMath.Vector3I)`](VRageMath.Sign)||
|static [`VRageMath.Vector3I Round(VRageMath.Vector3)`](VRageMath.Round)||
|static [`VRageMath.Vector3I Round(VRageMath.Vector3D)`](VRageMath.Round)||
|static [`void Round(ref VRageMath.Vector3, ref VRageMath.Vector3I)`](VRageMath.Round)||
|static [`void Round(ref VRageMath.Vector3D, ref VRageMath.Vector3I)`](VRageMath.Round)||
|static [`VRageMath.Vector3I Floor(VRageMath.Vector3)`](VRageMath.Floor)||
|static [`VRageMath.Vector3I Floor(VRageMath.Vector3D)`](VRageMath.Floor)||
|static [`void Floor(ref VRageMath.Vector3, ref VRageMath.Vector3I)`](VRageMath.Floor)||
|static [`void Floor(ref VRageMath.Vector3D, ref VRageMath.Vector3I)`](VRageMath.Floor)||
|static [`VRageMath.Vector3I Ceiling(VRageMath.Vector3)`](VRageMath.Ceiling)||
|static [`VRageMath.Vector3I Trunc(VRageMath.Vector3)`](VRageMath.Trunc)||
|static [`VRageMath.Vector3I Shift(VRageMath.Vector3I)`](VRageMath.Shift)||
|static [`void Transform(ref VRageMath.Vector3I, ref VRageMath.Matrix, ref VRageMath.Vector3I)`](VRageMath.Transform)|Transforms a Vector3I by the given Matrix.|
|static [`void Transform(ref VRageMath.Vector3I, ref VRageMath.Quaternion, ref VRageMath.Vector3I)`](VRageMath.Transform)||
|static [`VRageMath.Vector3I Transform(VRageMath.Vector3I, VRageMath.Quaternion)`](VRageMath.Transform)||
|static [`void Transform(ref VRageMath.Vector3I, ref VRageMath.MatrixI, ref VRageMath.Vector3I)`](VRageMath.Transform)||
|static [`VRageMath.Vector3I Transform(VRageMath.Vector3I, VRageMath.MatrixI)`](VRageMath.Transform)||
|static [`VRageMath.Vector3I Transform(VRageMath.Vector3I, ref VRageMath.MatrixI)`](VRageMath.Transform)||
|static [`VRageMath.Vector3I TransformNormal(VRageMath.Vector3I, ref VRageMath.MatrixI)`](VRageMath.TransformNormal)||
|static [`void TransformNormal(ref VRageMath.Vector3I, ref VRageMath.Matrix, ref VRageMath.Vector3I)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|static [`void TransformNormal(ref VRageMath.Vector3I, ref VRageMath.MatrixI, ref VRageMath.Vector3I)`](VRageMath.TransformNormal)||
|static [`void Cross(ref VRageMath.Vector3I, ref VRageMath.Vector3I, ref VRageMath.Vector3I)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|[`int CompareTo(VRageMath.Vector3I)`](VRageMath.CompareTo)||
|static [`VRageMath.Vector3I Abs(VRageMath.Vector3I)`](VRageMath.Abs)||
|static [`void Abs(ref VRageMath.Vector3I, ref VRageMath.Vector3I)`](VRageMath.Abs)||
|static [`VRageMath.Vector3I Clamp(VRageMath.Vector3I, VRageMath.Vector3I, VRageMath.Vector3I)`](VRageMath.Clamp)||
|static [`void Clamp(ref VRageMath.Vector3I, ref VRageMath.Vector3I, ref VRageMath.Vector3I, ref VRageMath.Vector3I)`](VRageMath.Clamp)||
|static [`int DistanceManhattan(VRageMath.Vector3I, VRageMath.Vector3I)`](VRageMath.DistanceManhattan)|Manhattan distance (cube distance) X + Y + Z of Abs(first - second)|
|[`int Dot(ref VRageMath.Vector3I)`](VRageMath.Dot)||
|static [`int Dot(VRageMath.Vector3I, VRageMath.Vector3I)`](VRageMath.Dot)||
|static [`int Dot(ref VRageMath.Vector3I, ref VRageMath.Vector3I)`](VRageMath.Dot)||
|static [`void Dot(ref VRageMath.Vector3I, ref VRageMath.Vector3I, ref int)`](VRageMath.Dot)||
|static [`bool TryParseFromString(string, ref VRageMath.Vector3I)`](VRageMath.TryParseFromString)||
|[`int Volume()`](VRageMath.Volume)||
|static [`IEnumerable<VRageMath.Vector3I> EnumerateRange(VRageMath.Vector3I, VRageMath.Vector3I)`](VRageMath.EnumerateRange)|Enumerate all values in a integer interval (a cuboid). This method is an allocating version of the Vector3I_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.|
|[`void ToBytes(List<System.Byte>)`](VRageMath.ToBytes)||
|[`bool IsAxisAligned()`](VRageMath.IsAxisAligned)||
