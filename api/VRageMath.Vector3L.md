← [Index](index)
# Vector3L Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`X`](VRageMath.X)||
|[`Y`](VRageMath.Y)||
|[`Z`](VRageMath.Z)||
|static [`Comparer`](VRageMath.Comparer)||
|static [`UnitX`](VRageMath.UnitX)||
|static [`UnitY`](VRageMath.UnitY)||
|static [`UnitZ`](VRageMath.UnitZ)||
|static [`Zero`](VRageMath.Zero)||
|static [`MaxValue`](VRageMath.MaxValue)||
|static [`MinValue`](VRageMath.MinValue)||
|static [`Up`](VRageMath.Up)||
|static [`Down`](VRageMath.Down)||
|static [`Right`](VRageMath.Right)||
|static [`Left`](VRageMath.Left)||
|static [`Forward`](VRageMath.Forward)||
|static [`Backward`](VRageMath.Backward)||
|static [`One`](VRageMath.One)||
### Properties
|Member|Description|
|---|---|
|[`Item`](VRageMath.Item)||
|[`Size`](VRageMath.Size)|How many cubes are in block with this size|
|[`SizeLong`](VRageMath.SizeLong)||
### Methods
|Member|Description|
|---|---|
|[`ToString()`](VRageMath.ToString)||
|[`Equals(Vector3L)`](VRageMath.Equals)||
|[`Equals(Object)`](VRageMath.Equals)||
|[`GetHashCode()`](VRageMath.GetHashCode)||
|[`IsInsideInclusiveEnd(ref Vector3L, ref Vector3L)`](VRageMath.IsInsideInclusiveEnd)||
|[`IsInsideInclusiveEnd(Vector3L, Vector3L)`](VRageMath.IsInsideInclusiveEnd)||
|[`IsInside(ref Vector3L, ref Vector3L)`](VRageMath.IsInside)||
|[`IsInside(Vector3L, Vector3L)`](VRageMath.IsInside)||
|[`RectangularDistance(Vector3L)`](VRageMath.RectangularDistance)|Calculates rectangular distance. It's how many sectors you have to travel to get to other sector from current sector.|
|[`RectangularLength()`](VRageMath.RectangularLength)|Calculates rectangular distance of this vector, longerpreted as a polong, from the origin.|
|[`Length()`](VRageMath.Length)||
|static [`Boxlongersects(Vector3L, Vector3L, Vector3L, Vector3L)`](VRageMath.Boxlongersects)||
|static [`Boxlongersects(ref Vector3L, ref Vector3L, ref Vector3L, ref Vector3L)`](VRageMath.Boxlongersects)||
|static [`BoxContains(Vector3L, Vector3L, Vector3L)`](VRageMath.BoxContains)||
|static [`BoxContains(ref Vector3L, ref Vector3L, ref Vector3L)`](VRageMath.BoxContains)||
|static [`Min(Vector3L, Vector3L)`](VRageMath.Min)||
|static [`Min(ref Vector3L, ref Vector3L, ref Vector3L)`](VRageMath.Min)||
|[`AbsMin()`](VRageMath.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|static [`Max(Vector3L, Vector3L)`](VRageMath.Max)||
|static [`Max(ref Vector3L, ref Vector3L, ref Vector3L)`](VRageMath.Max)||
|[`AbsMax()`](VRageMath.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|[`AxisValue(Axis)`](VRageMath.AxisValue)||
|static [`GetDominantDirection(Vector3L)`](VRageMath.GetDominantDirection)||
|static [`GetDominantDirectionVector(Vector3L)`](VRageMath.GetDominantDirectionVector)||
|static [`DominantAxisProjection(Vector3L)`](VRageMath.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|static [`DominantAxisProjection(ref Vector3L, ref Vector3L)`](VRageMath.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved longo a user-specified variable.|
|static [`Sign(Vector3)`](VRageMath.Sign)||
|static [`Sign(Vector3L)`](VRageMath.Sign)||
|static [`Floor(Vector3)`](VRageMath.Floor)||
|static [`Floor(Vector3D)`](VRageMath.Floor)||
|static [`Floor(ref Vector3, ref Vector3L)`](VRageMath.Floor)||
|static [`Floor(ref Vector3D, ref Vector3L)`](VRageMath.Floor)||
|static [`Ceiling(Vector3)`](VRageMath.Ceiling)||
|static [`Trunc(Vector3)`](VRageMath.Trunc)||
|static [`Shift(Vector3L)`](VRageMath.Shift)||
|static [`Transform(ref Vector3L, ref Matrix, ref Vector3L)`](VRageMath.Transform)|Transforms a Vector3L by the given Matrix.|
|static [`Transform(ref Vector3L, ref Quaternion, ref Vector3L)`](VRageMath.Transform)||
|static [`Transform(Vector3L, Quaternion)`](VRageMath.Transform)||
|static [`TransformNormal(ref Vector3L, ref Matrix, ref Vector3L)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|static [`Cross(ref Vector3L, ref Vector3L, ref Vector3L)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|[`CompareTo(Vector3L)`](VRageMath.CompareTo)||
|static [`Abs(Vector3L)`](VRageMath.Abs)||
|static [`Abs(ref Vector3L, ref Vector3L)`](VRageMath.Abs)||
|static [`Clamp(Vector3L, Vector3L, Vector3L)`](VRageMath.Clamp)||
|static [`Clamp(ref Vector3L, ref Vector3L, ref Vector3L, ref Vector3L)`](VRageMath.Clamp)||
|static [`DistanceManhattan(Vector3L, Vector3L)`](VRageMath.DistanceManhattan)|Manhattan distance (cube distance) X + Y + Z of Abs(first - second)|
|[`Dot(ref Vector3L)`](VRageMath.Dot)||
|static [`Dot(Vector3L, Vector3L)`](VRageMath.Dot)||
|static [`Dot(ref Vector3L, ref Vector3L)`](VRageMath.Dot)||
|static [`Dot(ref Vector3L, ref Vector3L, ref long)`](VRageMath.Dot)||
|static [`TryParseFromString(string, ref Vector3L)`](VRageMath.TryParseFromString)||
|[`Volume()`](VRageMath.Volume)||
|static [`EnumerateRange(Vector3L, Vector3L)`](VRageMath.EnumerateRange)|Enumerate all values in a longeger longerval (a cuboid). This method is an allocating version of the Vector3L_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.|
|[`ToBytes(List<byte>)`](VRageMath.ToBytes)||
