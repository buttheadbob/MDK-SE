← [Index](index.md)
# Vector3L Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`long X`](VRageMath.X)||
|[`long Y`](VRageMath.Y)||
|[`long Z`](VRageMath.Z)||
|[`EqualityComparer Comparer`](VRageMath.Comparer)||
|[`Vector3L UnitX`](VRageMath.UnitX)||
|[`Vector3L UnitY`](VRageMath.UnitY)||
|[`Vector3L UnitZ`](VRageMath.UnitZ)||
|[`Vector3L Zero`](VRageMath.Zero)||
|[`Vector3L MaxValue`](VRageMath.MaxValue)||
|[`Vector3L MinValue`](VRageMath.MinValue)||
|[`Vector3L Up`](VRageMath.Up)||
|[`Vector3L Down`](VRageMath.Down)||
|[`Vector3L Right`](VRageMath.Right)||
|[`Vector3L Left`](VRageMath.Left)||
|[`Vector3L Forward`](VRageMath.Forward)||
|[`Vector3L Backward`](VRageMath.Backward)||
|[`Vector3L One`](VRageMath.One)||
### Properties
|Member|Description|
|---|---|
|[`long Item`](VRageMath.Item)||
|[`long Size`](VRageMath.Size)||
|[`long SizeLong`](VRageMath.SizeLong)||
### Methods
|Member|Description|
|---|---|
|[`string ToString()`](VRageMath.ToString)||
|[`bool Equals(Vector3L other)`](VRageMath.Equals)||
|[`bool Equals(Object obj)`](VRageMath.Equals)||
|[`int GetHashCode()`](VRageMath.GetHashCode)||
|[`bool IsInsideInclusiveEnd(ref Vector3L min, ref Vector3L max)`](VRageMath.IsInsideInclusiveEnd)||
|[`bool IsInsideInclusiveEnd(Vector3L min, Vector3L max)`](VRageMath.IsInsideInclusiveEnd)||
|[`bool IsInside(ref Vector3L inclusiveMin, ref Vector3L exclusiveMax)`](VRageMath.IsInside)||
|[`bool IsInside(Vector3L inclusiveMin, Vector3L exclusiveMax)`](VRageMath.IsInside)||
|[`long RectangularDistance(Vector3L otherVector)`](VRageMath.RectangularDistance)|Calculates rectangular distance. It's how many sectors you have to travel to get to other sector from current sector.|
|[`long RectangularLength()`](VRageMath.RectangularLength)||
|[`long Length()`](VRageMath.Length)||
|[`bool Boxlongersects(Vector3L minA, Vector3L maxA, Vector3L minB, Vector3L maxB)`](VRageMath.Boxlongersects)||
|[`bool Boxlongersects(ref Vector3L minA, ref Vector3L maxA, ref Vector3L minB, ref Vector3L maxB)`](VRageMath.Boxlongersects)||
|[`bool BoxContains(Vector3L boxMin, Vector3L boxMax, Vector3L pt)`](VRageMath.BoxContains)||
|[`bool BoxContains(ref Vector3L boxMin, ref Vector3L boxMax, ref Vector3L pt)`](VRageMath.BoxContains)||
|[`Vector3L Min(Vector3L value1, Vector3L value2)`](VRageMath.Min)||
|[`void Min(ref Vector3L value1, ref Vector3L value2, ref Vector3L result)`](VRageMath.Min)||
|[`long AbsMin()`](VRageMath.AbsMin)||
|[`Vector3L Max(Vector3L value1, Vector3L value2)`](VRageMath.Max)||
|[`void Max(ref Vector3L value1, ref Vector3L value2, ref Vector3L result)`](VRageMath.Max)||
|[`long AbsMax()`](VRageMath.AbsMax)||
|[`long AxisValue(Axis axis)`](VRageMath.AxisValue)||
|[`CubeFace GetDominantDirection(Vector3L val)`](VRageMath.GetDominantDirection)||
|[`Vector3L GetDominantDirectionVector(Vector3L val)`](VRageMath.GetDominantDirectionVector)||
|[`Vector3L DominantAxisProjection(Vector3L value1)`](VRageMath.DominantAxisProjection)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|[`void DominantAxisProjection(ref Vector3L value1, ref Vector3L result)`](VRageMath.DominantAxisProjection)||
|[`Vector3L Sign(Vector3 value)`](VRageMath.Sign)||
|[`Vector3L Sign(Vector3L value)`](VRageMath.Sign)||
|[`Vector3L Floor(Vector3 value)`](VRageMath.Floor)||
|[`Vector3L Floor(Vector3D value)`](VRageMath.Floor)||
|[`void Floor(ref Vector3 v, ref Vector3L r)`](VRageMath.Floor)||
|[`void Floor(ref Vector3D v, ref Vector3L r)`](VRageMath.Floor)||
|[`Vector3L Ceiling(Vector3 value)`](VRageMath.Ceiling)||
|[`Vector3L Trunc(Vector3 value)`](VRageMath.Trunc)||
|[`Vector3L Shift(Vector3L value)`](VRageMath.Shift)||
|[`void Transform(ref Vector3L position, ref Matrix matrix, ref Vector3L result)`](VRageMath.Transform)||
|[`void Transform(ref Vector3L value, ref Quaternion rotation, ref Vector3L result)`](VRageMath.Transform)||
|[`Vector3L Transform(Vector3L value, Quaternion rotation)`](VRageMath.Transform)||
|[`void TransformNormal(ref Vector3L normal, ref Matrix matrix, ref Vector3L result)`](VRageMath.TransformNormal)||
|[`void Cross(ref Vector3L vector1, ref Vector3L vector2, ref Vector3L result)`](VRageMath.Cross)||
|[`int CompareTo(Vector3L other)`](VRageMath.CompareTo)||
|[`Vector3L Abs(Vector3L value)`](VRageMath.Abs)||
|[`void Abs(ref Vector3L value, ref Vector3L result)`](VRageMath.Abs)||
|[`Vector3L Clamp(Vector3L value1, Vector3L min, Vector3L max)`](VRageMath.Clamp)||
|[`void Clamp(ref Vector3L value1, ref Vector3L min, ref Vector3L max, ref Vector3L result)`](VRageMath.Clamp)||
|[`long DistanceManhattan(Vector3L first, Vector3L second)`](VRageMath.DistanceManhattan)||
|[`long Dot(ref Vector3L v)`](VRageMath.Dot)||
|[`long Dot(Vector3L vector1, Vector3L vector2)`](VRageMath.Dot)||
|[`long Dot(ref Vector3L vector1, ref Vector3L vector2)`](VRageMath.Dot)||
|[`void Dot(ref Vector3L vector1, ref Vector3L vector2, ref long dot)`](VRageMath.Dot)||
|[`bool TryParseFromString(string p, ref Vector3L vec)`](VRageMath.TryParseFromString)||
|[`long Volume()`](VRageMath.Volume)||
|[`IEnumerable<Vector3L> EnumerateRange(Vector3L minInclusive, Vector3L maxExclusive)`](VRageMath.EnumerateRange)||
|[`void ToBytes(List<byte> result)`](VRageMath.ToBytes)||
