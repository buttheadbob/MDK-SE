← [Index](index.md)
#Vector3L Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
###Fields
|Member|Description|
|---|---|
|[`long X`](VRageMath.X.md)||
|[`long Y`](VRageMath.Y.md)||
|[`long Z`](VRageMath.Z.md)||
|[`EqualityComparer Comparer`](VRageMath.Comparer.md)||
|[`Vector3L UnitX`](VRageMath.UnitX.md)||
|[`Vector3L UnitY`](VRageMath.UnitY.md)||
|[`Vector3L UnitZ`](VRageMath.UnitZ.md)||
|[`Vector3L Zero`](VRageMath.Zero.md)||
|[`Vector3L MaxValue`](VRageMath.MaxValue.md)||
|[`Vector3L MinValue`](VRageMath.MinValue.md)||
|[`Vector3L Up`](VRageMath.Up.md)||
|[`Vector3L Down`](VRageMath.Down.md)||
|[`Vector3L Right`](VRageMath.Right.md)||
|[`Vector3L Left`](VRageMath.Left.md)||
|[`Vector3L Forward`](VRageMath.Forward.md)||
|[`Vector3L Backward`](VRageMath.Backward.md)||
|[`Vector3L One`](VRageMath.One.md)||
###Properties
|Member|Description|
|---|---|
|[`long Item`](VRageMath.Item.md)||
|[`long Size`](VRageMath.Size.md)||
|[`long SizeLong`](VRageMath.SizeLong.md)||
###Methods
|Member|Description|
|---|---|
|[`string ToString()`](VRageMath.ToString.md)||
|[`bool Equals(Vector3L other)`](VRageMath.Equals.md)||
|[`bool Equals(Object obj)`](VRageMath.Equals.md)||
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`bool IsInsideInclusiveEnd(ref Vector3L min, ref Vector3L max)`](VRageMath.IsInsideInclusiveEnd.md)||
|[`bool IsInsideInclusiveEnd(Vector3L min, Vector3L max)`](VRageMath.IsInsideInclusiveEnd.md)||
|[`bool IsInside(ref Vector3L inclusiveMin, ref Vector3L exclusiveMax)`](VRageMath.IsInside.md)||
|[`bool IsInside(Vector3L inclusiveMin, Vector3L exclusiveMax)`](VRageMath.IsInside.md)||
|[`long RectangularDistance(Vector3L otherVector)`](VRageMath.RectangularDistance.md)|Calculates rectangular distance. It's how many sectors you have to travel to get to other sector from current sector.|
|[`long RectangularLength()`](VRageMath.RectangularLength.md)||
|[`long Length()`](VRageMath.Length.md)||
|[`bool Boxlongersects(Vector3L minA, Vector3L maxA, Vector3L minB, Vector3L maxB)`](VRageMath.Boxlongersects.md)||
|[`bool Boxlongersects(ref Vector3L minA, ref Vector3L maxA, ref Vector3L minB, ref Vector3L maxB)`](VRageMath.Boxlongersects.md)||
|[`bool BoxContains(Vector3L boxMin, Vector3L boxMax, Vector3L pt)`](VRageMath.BoxContains.md)||
|[`bool BoxContains(ref Vector3L boxMin, ref Vector3L boxMax, ref Vector3L pt)`](VRageMath.BoxContains.md)||
|[`Vector3L Min(Vector3L value1, Vector3L value2)`](VRageMath.Min.md)||
|[`void Min(ref Vector3L value1, ref Vector3L value2, ref Vector3L result)`](VRageMath.Min.md)||
|[`long AbsMin()`](VRageMath.AbsMin.md)||
|[`Vector3L Max(Vector3L value1, Vector3L value2)`](VRageMath.Max.md)||
|[`void Max(ref Vector3L value1, ref Vector3L value2, ref Vector3L result)`](VRageMath.Max.md)||
|[`long AbsMax()`](VRageMath.AbsMax.md)||
|[`long AxisValue(Axis axis)`](VRageMath.AxisValue.md)||
|[`CubeFace GetDominantDirection(Vector3L val)`](VRageMath.GetDominantDirection.md)||
|[`Vector3L GetDominantDirectionVector(Vector3L val)`](VRageMath.GetDominantDirectionVector.md)||
|[`Vector3L DominantAxisProjection(Vector3L value1)`](VRageMath.DominantAxisProjection.md)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|[`void DominantAxisProjection(ref Vector3L value1, ref Vector3L result)`](VRageMath.DominantAxisProjection.md)||
|[`Vector3L Sign(Vector3 value)`](VRageMath.Sign.md)||
|[`Vector3L Sign(Vector3L value)`](VRageMath.Sign.md)||
|[`Vector3L Floor(Vector3 value)`](VRageMath.Floor.md)||
|[`Vector3L Floor(Vector3D value)`](VRageMath.Floor.md)||
|[`void Floor(ref Vector3 v, ref Vector3L r)`](VRageMath.Floor.md)||
|[`void Floor(ref Vector3D v, ref Vector3L r)`](VRageMath.Floor.md)||
|[`Vector3L Ceiling(Vector3 value)`](VRageMath.Ceiling.md)||
|[`Vector3L Trunc(Vector3 value)`](VRageMath.Trunc.md)||
|[`Vector3L Shift(Vector3L value)`](VRageMath.Shift.md)||
|[`void Transform(ref Vector3L position, ref Matrix matrix, ref Vector3L result)`](VRageMath.Transform.md)||
|[`void Transform(ref Vector3L value, ref Quaternion rotation, ref Vector3L result)`](VRageMath.Transform.md)||
|[`Vector3L Transform(Vector3L value, Quaternion rotation)`](VRageMath.Transform.md)||
|[`void TransformNormal(ref Vector3L normal, ref Matrix matrix, ref Vector3L result)`](VRageMath.TransformNormal.md)||
|[`void Cross(ref Vector3L vector1, ref Vector3L vector2, ref Vector3L result)`](VRageMath.Cross.md)||
|[`int CompareTo(Vector3L other)`](VRageMath.CompareTo.md)||
|[`Vector3L Abs(Vector3L value)`](VRageMath.Abs.md)||
|[`void Abs(ref Vector3L value, ref Vector3L result)`](VRageMath.Abs.md)||
|[`Vector3L Clamp(Vector3L value1, Vector3L min, Vector3L max)`](VRageMath.Clamp.md)||
|[`void Clamp(ref Vector3L value1, ref Vector3L min, ref Vector3L max, ref Vector3L result)`](VRageMath.Clamp.md)||
|[`long DistanceManhattan(Vector3L first, Vector3L second)`](VRageMath.DistanceManhattan.md)||
|[`long Dot(ref Vector3L v)`](VRageMath.Dot.md)||
|[`long Dot(Vector3L vector1, Vector3L vector2)`](VRageMath.Dot.md)||
|[`long Dot(ref Vector3L vector1, ref Vector3L vector2)`](VRageMath.Dot.md)||
|[`void Dot(ref Vector3L vector1, ref Vector3L vector2, ref long dot)`](VRageMath.Dot.md)||
|[`bool TryParseFromString(string p, ref Vector3L vec)`](VRageMath.TryParseFromString.md)||
|[`long Volume()`](VRageMath.Volume.md)||
|[`IEnumerable<Vector3L> EnumerateRange(Vector3L minInclusive, Vector3L maxExclusive)`](VRageMath.EnumerateRange.md)||
|[`void ToBytes(List<byte> result)`](VRageMath.ToBytes.md)||
