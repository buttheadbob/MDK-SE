← [Index](Api-Index)
# Vector3L Struct
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
|[`Boxlongersects(Vector3L, Vector3L, Vector3L, Vector3L)`](VRageMath.Boxlongersects)||
|[`Boxlongersects(ref Vector3L, ref Vector3L, ref Vector3L, ref Vector3L)`](VRageMath.Boxlongersects)||
|[`BoxContains(Vector3L, Vector3L, Vector3L)`](VRageMath.BoxContains)||
|[`BoxContains(ref Vector3L, ref Vector3L, ref Vector3L)`](VRageMath.BoxContains)||
|[`Min(Vector3L, Vector3L)`](VRageMath.Min)||
|[`Min(ref Vector3L, ref Vector3L, ref Vector3L)`](VRageMath.Min)||
|[`AbsMin()`](VRageMath.AbsMin)|Returns the component of the vector, whose absolute value is smallest of all the three components.|
|[`Max(Vector3L, Vector3L)`](VRageMath.Max)||
|[`Max(ref Vector3L, ref Vector3L, ref Vector3L)`](VRageMath.Max)||
|[`AbsMax()`](VRageMath.AbsMax)|Returns the component of the vector, whose absolute value is largest of all the three components.|
|[`AxisValue(Axis)`](VRageMath.AxisValue)||
|[`GetDominantDirection(Vector3L)`](VRageMath.GetDominantDirection)||
|[`GetDominantDirectionVector(Vector3L)`](VRageMath.GetDominantDirectionVector)||
|[`DominantAxisProjection(Vector3L)`](VRageMath.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|[`DominantAxisProjection(ref Vector3L, ref Vector3L)`](VRageMath.DominantAxisProjection)|Calculates a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value. The result is saved longo a user-specified variable.|
|[`Sign(Vector3)`](VRageMath.Sign)||
|[`Sign(Vector3L)`](VRageMath.Sign)||
|[`Floor(Vector3)`](VRageMath.Floor)||
|[`Floor(Vector3D)`](VRageMath.Floor)||
|[`Floor(ref Vector3, ref Vector3L)`](VRageMath.Floor)||
|[`Floor(ref Vector3D, ref Vector3L)`](VRageMath.Floor)||
|[`Ceiling(Vector3)`](VRageMath.Ceiling)||
|[`Trunc(Vector3)`](VRageMath.Trunc)||
|[`Shift(Vector3L)`](VRageMath.Shift)||
|[`Transform(ref Vector3L, ref Matrix, ref Vector3L)`](VRageMath.Transform)|Transforms a Vector3L by the given Matrix.|
|[`Transform(ref Vector3L, ref Quaternion, ref Vector3L)`](VRageMath.Transform)||
|[`Transform(Vector3L, Quaternion)`](VRageMath.Transform)||
|[`TransformNormal(ref Vector3L, ref Matrix, ref Vector3L)`](VRageMath.TransformNormal)|Transforms a vector normal by a matrix.|
|[`Cross(ref Vector3L, ref Vector3L, ref Vector3L)`](VRageMath.Cross)|Calculates the cross product of two vectors.|
|[`CompareTo(Vector3L)`](VRageMath.CompareTo)||
|[`Abs(Vector3L)`](VRageMath.Abs)||
|[`Abs(ref Vector3L, ref Vector3L)`](VRageMath.Abs)||
|[`Clamp(Vector3L, Vector3L, Vector3L)`](VRageMath.Clamp)||
|[`Clamp(ref Vector3L, ref Vector3L, ref Vector3L, ref Vector3L)`](VRageMath.Clamp)||
|[`DistanceManhattan(Vector3L, Vector3L)`](VRageMath.DistanceManhattan)|Manhattan distance (cube distance) X + Y + Z of Abs(first - second)|
|[`Dot(ref Vector3L)`](VRageMath.Dot)||
|[`Dot(Vector3L, Vector3L)`](VRageMath.Dot)||
|[`Dot(ref Vector3L, ref Vector3L)`](VRageMath.Dot)||
|[`Dot(ref Vector3L, ref Vector3L, ref long)`](VRageMath.Dot)||
|[`TryParseFromString(string, ref Vector3L)`](VRageMath.TryParseFromString)||
|[`Volume()`](VRageMath.Volume)||
|[`EnumerateRange(Vector3L, Vector3L)`](VRageMath.EnumerateRange)|Enumerate all values in a longeger longerval (a cuboid). This method is an allocating version of the Vector3L_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.|
|[`ToBytes(List<byte>)`](VRageMath.ToBytes)||
