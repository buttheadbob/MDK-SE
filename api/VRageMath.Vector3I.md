← [Index](index.md)
# Vector3I Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|[`int X`](VRageMath.X.md)||
|[`int Y`](VRageMath.Y.md)||
|[`int Z`](VRageMath.Z.md)||
|[`EqualityComparer Comparer`](VRageMath.Comparer.md)||
|[`Vector3I UnitX`](VRageMath.UnitX.md)||
|[`Vector3I UnitY`](VRageMath.UnitY.md)||
|[`Vector3I UnitZ`](VRageMath.UnitZ.md)||
|[`Vector3I Zero`](VRageMath.Zero.md)||
|[`Vector3I MaxValue`](VRageMath.MaxValue.md)||
|[`Vector3I MinValue`](VRageMath.MinValue.md)||
|[`Vector3I Up`](VRageMath.Up.md)||
|[`Vector3I Down`](VRageMath.Down.md)||
|[`Vector3I Right`](VRageMath.Right.md)||
|[`Vector3I Left`](VRageMath.Left.md)||
|[`Vector3I Forward`](VRageMath.Forward.md)||
|[`Vector3I Backward`](VRageMath.Backward.md)||
|[`Vector3I One`](VRageMath.One.md)||
### Properties
|Member|Description|
|---|---|
|[`int Item`](VRageMath.Item.md)||
|[`bool IsPowerOfTwo`](VRageMath.IsPowerOfTwo.md)||
|[`int Size`](VRageMath.Size.md)||
|[`long SizeLong`](VRageMath.SizeLong.md)||
### Methods
|Member|Description|
|---|---|
|[`string ToString()`](VRageMath.ToString.md)||
|[`bool Equals(Vector3I other)`](VRageMath.Equals.md)||
|[`bool Equals(Object obj)`](VRageMath.Equals.md)||
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`bool IsInsideInclusiveEnd(ref Vector3I min, ref Vector3I max)`](VRageMath.IsInsideInclusiveEnd.md)||
|[`bool IsInsideInclusiveEnd(Vector3I min, Vector3I max)`](VRageMath.IsInsideInclusiveEnd.md)||
|[`bool IsInside(ref Vector3I inclusiveMin, ref Vector3I exclusiveMax)`](VRageMath.IsInside.md)||
|[`bool IsInside(Vector3I inclusiveMin, Vector3I exclusiveMax)`](VRageMath.IsInside.md)||
|[`int RectangularDistance(Vector3I otherVector)`](VRageMath.RectangularDistance.md)|Calculates rectangular distance. It's how many sectors you have to travel to get to other sector from current sector.|
|[`int RectangularLength()`](VRageMath.RectangularLength.md)||
|[`int Length()`](VRageMath.Length.md)||
|[`bool BoxIntersects(Vector3I minA, Vector3I maxA, Vector3I minB, Vector3I maxB)`](VRageMath.BoxIntersects.md)||
|[`bool BoxIntersects(ref Vector3I minA, ref Vector3I maxA, ref Vector3I minB, ref Vector3I maxB)`](VRageMath.BoxIntersects.md)||
|[`bool BoxContains(Vector3I boxMin, Vector3I boxMax, Vector3I pt)`](VRageMath.BoxContains.md)||
|[`bool BoxContains(ref Vector3I boxMin, ref Vector3I boxMax, ref Vector3I pt)`](VRageMath.BoxContains.md)||
|[`Vector3I Min(Vector3I value1, Vector3I value2)`](VRageMath.Min.md)||
|[`void Min(ref Vector3I value1, ref Vector3I value2, ref Vector3I result)`](VRageMath.Min.md)||
|[`int AbsMin()`](VRageMath.AbsMin.md)||
|[`Vector3I Max(Vector3I value1, Vector3I value2)`](VRageMath.Max.md)||
|[`void Max(ref Vector3I value1, ref Vector3I value2, ref Vector3I result)`](VRageMath.Max.md)||
|[`int AbsMax()`](VRageMath.AbsMax.md)||
|[`void MinMax(ref Vector3I min, ref Vector3I max)`](VRageMath.MinMax.md)||
|[`int AxisValue(Axis axis)`](VRageMath.AxisValue.md)||
|[`CubeFace GetDominantDirection(Vector3I val)`](VRageMath.GetDominantDirection.md)||
|[`Vector3I GetDominantDirectionVector(Vector3I val)`](VRageMath.GetDominantDirectionVector.md)||
|[`Vector3I DominantAxisProjection(Vector3I value1)`](VRageMath.DominantAxisProjection.md)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|[`void DominantAxisProjection(ref Vector3I value1, ref Vector3I result)`](VRageMath.DominantAxisProjection.md)||
|[`Vector3I Sign(Vector3 value)`](VRageMath.Sign.md)||
|[`Vector3I Sign(Vector3I value)`](VRageMath.Sign.md)||
|[`Vector3I Round(Vector3 value)`](VRageMath.Round.md)||
|[`Vector3I Round(Vector3D value)`](VRageMath.Round.md)||
|[`void Round(ref Vector3 v, ref Vector3I r)`](VRageMath.Round.md)||
|[`void Round(ref Vector3D v, ref Vector3I r)`](VRageMath.Round.md)||
|[`Vector3I Floor(Vector3 value)`](VRageMath.Floor.md)||
|[`Vector3I Floor(Vector3D value)`](VRageMath.Floor.md)||
|[`void Floor(ref Vector3 v, ref Vector3I r)`](VRageMath.Floor.md)||
|[`void Floor(ref Vector3D v, ref Vector3I r)`](VRageMath.Floor.md)||
|[`Vector3I Ceiling(Vector3 value)`](VRageMath.Ceiling.md)||
|[`Vector3I Trunc(Vector3 value)`](VRageMath.Trunc.md)||
|[`Vector3I Shift(Vector3I value)`](VRageMath.Shift.md)||
|[`void Transform(ref Vector3I position, ref Matrix matrix, ref Vector3I result)`](VRageMath.Transform.md)||
|[`void Transform(ref Vector3I value, ref Quaternion rotation, ref Vector3I result)`](VRageMath.Transform.md)||
|[`Vector3I Transform(Vector3I value, Quaternion rotation)`](VRageMath.Transform.md)||
|[`void Transform(ref Vector3I value, ref MatrixI matrix, ref Vector3I result)`](VRageMath.Transform.md)||
|[`Vector3I Transform(Vector3I value, MatrixI transformation)`](VRageMath.Transform.md)||
|[`Vector3I Transform(Vector3I value, ref MatrixI transformation)`](VRageMath.Transform.md)||
|[`Vector3I TransformNormal(Vector3I value, ref MatrixI transformation)`](VRageMath.TransformNormal.md)||
|[`void TransformNormal(ref Vector3I normal, ref Matrix matrix, ref Vector3I result)`](VRageMath.TransformNormal.md)||
|[`void TransformNormal(ref Vector3I normal, ref MatrixI matrix, ref Vector3I result)`](VRageMath.TransformNormal.md)||
|[`void Cross(ref Vector3I vector1, ref Vector3I vector2, ref Vector3I result)`](VRageMath.Cross.md)||
|[`int CompareTo(Vector3I other)`](VRageMath.CompareTo.md)||
|[`Vector3I Abs(Vector3I value)`](VRageMath.Abs.md)||
|[`void Abs(ref Vector3I value, ref Vector3I result)`](VRageMath.Abs.md)||
|[`Vector3I Clamp(Vector3I value1, Vector3I min, Vector3I max)`](VRageMath.Clamp.md)||
|[`void Clamp(ref Vector3I value1, ref Vector3I min, ref Vector3I max, ref Vector3I result)`](VRageMath.Clamp.md)||
|[`int DistanceManhattan(Vector3I first, Vector3I second)`](VRageMath.DistanceManhattan.md)||
|[`int Dot(ref Vector3I v)`](VRageMath.Dot.md)||
|[`int Dot(Vector3I vector1, Vector3I vector2)`](VRageMath.Dot.md)||
|[`int Dot(ref Vector3I vector1, ref Vector3I vector2)`](VRageMath.Dot.md)||
|[`void Dot(ref Vector3I vector1, ref Vector3I vector2, ref int dot)`](VRageMath.Dot.md)||
|[`bool TryParseFromString(string p, ref Vector3I vec)`](VRageMath.TryParseFromString.md)||
|[`int Volume()`](VRageMath.Volume.md)||
|[`IEnumerable<Vector3I> EnumerateRange(Vector3I minInclusive, Vector3I maxExclusive)`](VRageMath.EnumerateRange.md)||
|[`void ToBytes(List<byte> result)`](VRageMath.ToBytes.md)||
|[`bool IsAxisAligned()`](VRageMath.IsAxisAligned.md)||
