← [Index](index)
# Vector3I Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`int X`](VRageMath.X)||
|[`int Y`](VRageMath.Y)||
|[`int Z`](VRageMath.Z)||
|[`EqualityComparer Comparer`](VRageMath.Comparer)||
|[`Vector3I UnitX`](VRageMath.UnitX)||
|[`Vector3I UnitY`](VRageMath.UnitY)||
|[`Vector3I UnitZ`](VRageMath.UnitZ)||
|[`Vector3I Zero`](VRageMath.Zero)||
|[`Vector3I MaxValue`](VRageMath.MaxValue)||
|[`Vector3I MinValue`](VRageMath.MinValue)||
|[`Vector3I Up`](VRageMath.Up)||
|[`Vector3I Down`](VRageMath.Down)||
|[`Vector3I Right`](VRageMath.Right)||
|[`Vector3I Left`](VRageMath.Left)||
|[`Vector3I Forward`](VRageMath.Forward)||
|[`Vector3I Backward`](VRageMath.Backward)||
|[`Vector3I One`](VRageMath.One)||
### Properties
|Member|Description|
|---|---|
|[`int Item`](VRageMath.Item)||
|[`bool IsPowerOfTwo`](VRageMath.IsPowerOfTwo)||
|[`int Size`](VRageMath.Size)||
|[`long SizeLong`](VRageMath.SizeLong)||
### Methods
|Member|Description|
|---|---|
|[`string ToString()`](VRageMath.ToString)||
|[`bool Equals(Vector3I other)`](VRageMath.Equals)||
|[`bool Equals(Object obj)`](VRageMath.Equals)||
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`bool IsInsideInclusiveEnd(ref Vector3I min, ref Vector3I max)`](VRageMath.IsInsideInclusiveEnd)||
|[`bool IsInsideInclusiveEnd(Vector3I min, Vector3I max)`](VRageMath.IsInsideInclusiveEnd)||
|[`bool IsInside(ref Vector3I inclusiveMin, ref Vector3I exclusiveMax)`](VRageMath.IsInside)||
|[`bool IsInside(Vector3I inclusiveMin, Vector3I exclusiveMax)`](VRageMath.IsInside)||
|[`int RectangularDistance(Vector3I otherVector)`](VRageMath.RectangularDistance)|Calculates rectangular distance. It's how many sectors you have to travel to get to other sector from current sector.|
|[`int RectangularLength()`](VRageMath.RectangularLength)||
|[`int Length()`](VRageMath.Length)||
|[`bool BoxIntersects(Vector3I minA, Vector3I maxA, Vector3I minB, Vector3I maxB)`](VRageMath.BoxIntersects)||
|[`bool BoxIntersects(ref Vector3I minA, ref Vector3I maxA, ref Vector3I minB, ref Vector3I maxB)`](VRageMath.BoxIntersects)||
|[`bool BoxContains(Vector3I boxMin, Vector3I boxMax, Vector3I pt)`](VRageMath.BoxContains)||
|[`bool BoxContains(ref Vector3I boxMin, ref Vector3I boxMax, ref Vector3I pt)`](VRageMath.BoxContains)||
|[`Vector3I Min(Vector3I value1, Vector3I value2)`](VRageMath.Min)||
|[`void Min(ref Vector3I value1, ref Vector3I value2, ref Vector3I result)`](VRageMath.Min)||
|[`int AbsMin()`](VRageMath.AbsMin)||
|[`Vector3I Max(Vector3I value1, Vector3I value2)`](VRageMath.Max)||
|[`void Max(ref Vector3I value1, ref Vector3I value2, ref Vector3I result)`](VRageMath.Max)||
|[`int AbsMax()`](VRageMath.AbsMax)||
|[`void MinMax(ref Vector3I min, ref Vector3I max)`](VRageMath.MinMax)||
|[`int AxisValue(Axis axis)`](VRageMath.AxisValue)||
|[`CubeFace GetDominantDirection(Vector3I val)`](VRageMath.GetDominantDirection)||
|[`Vector3I GetDominantDirectionVector(Vector3I val)`](VRageMath.GetDominantDirectionVector)||
|[`Vector3I DominantAxisProjection(Vector3I value1)`](VRageMath.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|[`void DominantAxisProjection(ref Vector3I value1, ref Vector3I result)`](VRageMath.DominantAxisProjection)||
|[`Vector3I Sign(Vector3 value)`](VRageMath.Sign)||
|[`Vector3I Sign(Vector3I value)`](VRageMath.Sign)||
|[`Vector3I Round(Vector3 value)`](VRageMath.Round)||
|[`Vector3I Round(Vector3D value)`](VRageMath.Round)||
|[`void Round(ref Vector3 v, ref Vector3I r)`](VRageMath.Round)||
|[`void Round(ref Vector3D v, ref Vector3I r)`](VRageMath.Round)||
|[`Vector3I Floor(Vector3 value)`](VRageMath.Floor)||
|[`Vector3I Floor(Vector3D value)`](VRageMath.Floor)||
|[`void Floor(ref Vector3 v, ref Vector3I r)`](VRageMath.Floor)||
|[`void Floor(ref Vector3D v, ref Vector3I r)`](VRageMath.Floor)||
|[`Vector3I Ceiling(Vector3 value)`](VRageMath.Ceiling)||
|[`Vector3I Trunc(Vector3 value)`](VRageMath.Trunc)||
|[`Vector3I Shift(Vector3I value)`](VRageMath.Shift)||
|[`void Transform(ref Vector3I position, ref Matrix matrix, ref Vector3I result)`](VRageMath.Transform)||
|[`void Transform(ref Vector3I value, ref Quaternion rotation, ref Vector3I result)`](VRageMath.Transform)||
|[`Vector3I Transform(Vector3I value, Quaternion rotation)`](VRageMath.Transform)||
|[`void Transform(ref Vector3I value, ref MatrixI matrix, ref Vector3I result)`](VRageMath.Transform)||
|[`Vector3I Transform(Vector3I value, MatrixI transformation)`](VRageMath.Transform)||
|[`Vector3I Transform(Vector3I value, ref MatrixI transformation)`](VRageMath.Transform)||
|[`Vector3I TransformNormal(Vector3I value, ref MatrixI transformation)`](VRageMath.TransformNormal)||
|[`void TransformNormal(ref Vector3I normal, ref Matrix matrix, ref Vector3I result)`](VRageMath.TransformNormal)||
|[`void TransformNormal(ref Vector3I normal, ref MatrixI matrix, ref Vector3I result)`](VRageMath.TransformNormal)||
|[`void Cross(ref Vector3I vector1, ref Vector3I vector2, ref Vector3I result)`](VRageMath.Cross)||
|[`int CompareTo(Vector3I other)`](VRageMath.CompareTo)||
|[`Vector3I Abs(Vector3I value)`](VRageMath.Abs)||
|[`void Abs(ref Vector3I value, ref Vector3I result)`](VRageMath.Abs)||
|[`Vector3I Clamp(Vector3I value1, Vector3I min, Vector3I max)`](VRageMath.Clamp)||
|[`void Clamp(ref Vector3I value1, ref Vector3I min, ref Vector3I max, ref Vector3I result)`](VRageMath.Clamp)||
|[`int DistanceManhattan(Vector3I first, Vector3I second)`](VRageMath.DistanceManhattan)||
|[`int Dot(ref Vector3I v)`](VRageMath.Dot)||
|[`int Dot(Vector3I vector1, Vector3I vector2)`](VRageMath.Dot)||
|[`int Dot(ref Vector3I vector1, ref Vector3I vector2)`](VRageMath.Dot)||
|[`void Dot(ref Vector3I vector1, ref Vector3I vector2, ref int dot)`](VRageMath.Dot)||
|[`bool TryParseFromString(string p, ref Vector3I vec)`](VRageMath.TryParseFromString)||
|[`int Volume()`](VRageMath.Volume)||
|[`IEnumerable<Vector3I> EnumerateRange(Vector3I minInclusive, Vector3I maxExclusive)`](VRageMath.EnumerateRange)||
|[`void ToBytes(List<byte> result)`](VRageMath.ToBytes)||
|[`bool IsAxisAligned()`](VRageMath.IsAxisAligned)||
