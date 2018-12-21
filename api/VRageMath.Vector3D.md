← [Index](index.md)
# Vector3D Struct
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Defines a vector with three components.
### Fields
|Member|Description|
|---|---|
|[`double X`](VRageMath.X.md)||
|[`double Y`](VRageMath.Y.md)||
|[`double Z`](VRageMath.Z.md)||
|[`Vector3D Zero`](VRageMath.Zero.md)||
|[`Vector3D One`](VRageMath.One.md)||
|[`Vector3D Half`](VRageMath.Half.md)||
|[`Vector3D PositiveInfinity`](VRageMath.PositiveInfinity.md)||
|[`Vector3D NegativeInfinity`](VRageMath.NegativeInfinity.md)||
|[`Vector3D UnitX`](VRageMath.UnitX.md)||
|[`Vector3D UnitY`](VRageMath.UnitY.md)||
|[`Vector3D UnitZ`](VRageMath.UnitZ.md)||
|[`Vector3D Up`](VRageMath.Up.md)||
|[`Vector3D Down`](VRageMath.Down.md)||
|[`Vector3D Right`](VRageMath.Right.md)||
|[`Vector3D Left`](VRageMath.Left.md)||
|[`Vector3D Forward`](VRageMath.Forward.md)||
|[`Vector3D Backward`](VRageMath.Backward.md)||
|[`Vector3D MaxValue`](VRageMath.MaxValue.md)||
|[`Vector3D MinValue`](VRageMath.MinValue.md)||
### Properties
|Member|Description|
|---|---|
|[`double Sum`](VRageMath.Sum.md)||
|[`double Volume`](VRageMath.Volume.md)||
### Methods
|Member|Description|
|---|---|
|[`void TransformNormal(ref Vector3D normal, ref MatrixI matrix, ref Vector3D result)`](VRageMath.TransformNormal.md)||
|[`Vector3D TransformNormal(Vector3D normal, MyBlockOrientation orientation)`](VRageMath.TransformNormal.md)||
|[`void TransformNormal(ref Vector3D normal, MyBlockOrientation orientation, ref Vector3D result)`](VRageMath.TransformNormal.md)||
|[`Vector3D TransformNormal(Vector3D normal, ref MatrixD matrix)`](VRageMath.TransformNormal.md)||
|[`Vector3D Transform(Vector3D value, Quaternion rotation)`](VRageMath.Transform.md)||
|[`void Transform(ref Vector3D value, ref Quaternion rotation, ref Vector3D result)`](VRageMath.Transform.md)||
|[`void Rotate(ref Vector3D vector, ref MatrixD rotationMatrix, ref Vector3D result)`](VRageMath.Rotate.md)||
|[`Vector3D Rotate(Vector3D vector, MatrixD rotationMatrix)`](VRageMath.Rotate.md)||
|[`void Transform(Vector3D[] sourceArray, ref MatrixD matrix, Vector3D[] destinationArray)`](VRageMath.Transform.md)||
|[`void Transform(Vector3D[] sourceArray, ref MatrixD matrix, *Vector3D destinationArray)`](VRageMath.Transform.md)||
|[`void Transform(Vector3D[] sourceArray, int sourceIndex, ref Matrix matrix, Vector3D[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform.md)||
|[`void TransformNormal(Vector3D[] sourceArray, ref Matrix matrix, Vector3D[] destinationArray)`](VRageMath.TransformNormal.md)||
|[`void TransformNormal(Vector3D[] sourceArray, ref Matrix matrix, *Vector3D destinationArray)`](VRageMath.TransformNormal.md)||
|[`void TransformNormal(Vector3D[] sourceArray, int sourceIndex, ref Matrix matrix, Vector3D[] destinationArray, int destinationIndex, int length)`](VRageMath.TransformNormal.md)||
|[`void Transform(Vector3D[] sourceArray, ref Quaternion rotation, Vector3D[] destinationArray)`](VRageMath.Transform.md)||
|[`void Transform(Vector3D[] sourceArray, int sourceIndex, ref Quaternion rotation, Vector3D[] destinationArray, int destinationIndex, int length)`](VRageMath.Transform.md)||
|[`Vector3D Negate(Vector3D value)`](VRageMath.Negate.md)|Returns a vector pointing in the opposite direction.|
|[`void Negate(ref Vector3D value, ref Vector3D result)`](VRageMath.Negate.md)||
|[`Vector3D Add(Vector3D value1, Vector3D value2)`](VRageMath.Add.md)||
|[`void Add(ref Vector3D value1, ref Vector3D value2, ref Vector3D result)`](VRageMath.Add.md)||
|[`Vector3D Subtract(Vector3D value1, Vector3D value2)`](VRageMath.Subtract.md)||
|[`void Subtract(ref Vector3D value1, ref Vector3D value2, ref Vector3D result)`](VRageMath.Subtract.md)||
|[`Vector3D Multiply(Vector3D value1, Vector3D value2)`](VRageMath.Multiply.md)||
|[`void Multiply(ref Vector3D value1, ref Vector3D value2, ref Vector3D result)`](VRageMath.Multiply.md)||
|[`Vector3D Multiply(Vector3D value1, double scaleFactor)`](VRageMath.Multiply.md)||
|[`void Multiply(ref Vector3D value1, double scaleFactor, ref Vector3D result)`](VRageMath.Multiply.md)||
|[`Vector3D Divide(Vector3D value1, Vector3D value2)`](VRageMath.Divide.md)||
|[`void Divide(ref Vector3D value1, ref Vector3D value2, ref Vector3D result)`](VRageMath.Divide.md)||
|[`Vector3D Divide(Vector3D value1, double value2)`](VRageMath.Divide.md)||
|[`void Divide(ref Vector3D value1, double value2, ref Vector3D result)`](VRageMath.Divide.md)||
|[`Vector3D CalculatePerpendicularVector(Vector3D v)`](VRageMath.CalculatePerpendicularVector.md)||
|[`void CalculatePerpendicularVector(ref Vector3D result)`](VRageMath.CalculatePerpendicularVector.md)||
|[`void GetAzimuthAndElevation(Vector3D v, ref double azimuth, ref double elevation)`](VRageMath.GetAzimuthAndElevation.md)||
|[`void CreateFromAzimuthAndElevation(double azimuth, double elevation, ref Vector3D direction)`](VRageMath.CreateFromAzimuthAndElevation.md)||
|[`long VolumeInt(double multiplier)`](VRageMath.VolumeInt.md)||
|[`bool IsInsideInclusive(ref Vector3D min, ref Vector3D max)`](VRageMath.IsInsideInclusive.md)||
|[`Vector3D SwapYZCoordinates(Vector3D v)`](VRageMath.SwapYZCoordinates.md)||
|[`double GetDim(int i)`](VRageMath.GetDim.md)||
|[`void SetDim(int i, double value)`](VRageMath.SetDim.md)||
|[`Vector3I Round(Vector3D vect3d)`](VRageMath.Round.md)||
|[`Vector3I Floor(Vector3D vect3d)`](VRageMath.Floor.md)||
|[`void Fract(ref Vector3D o, ref Vector3D r)`](VRageMath.Fract.md)||
|[`Vector3D Round(Vector3D v, int numDecimals)`](VRageMath.Round.md)||
|[`void Abs(ref Vector3D vector3D, ref Vector3D abs)`](VRageMath.Abs.md)||
|[`Vector3D ProjectOnPlane(ref Vector3D vec, ref Vector3D planeNormal)`](VRageMath.ProjectOnPlane.md)||
|[`Vector3D ProjectOnVector(ref Vector3D vec, ref Vector3D guideVector)`](VRageMath.ProjectOnVector.md)||
|[`Vector3D Abs(Vector3D value)`](VRageMath.Abs.md)||
|[`Vector3D Sign(Vector3D value)`](VRageMath.Sign.md)||
|[`Vector3D SignNonZero(Vector3D value)`](VRageMath.SignNonZero.md)|Returns per component sign, never returns zero. For zero component returns sign 1. Faster than Sign.|
|[`void Interpolate3(Vector3D v0, Vector3D v1, double rt)`](VRageMath.Interpolate3.md)||
|[`bool IsValid()`](VRageMath.IsValid.md)||
|[`void AssertIsValid()`](VRageMath.AssertIsValid.md)||
|[`bool IsUnit(ref Vector3D value)`](VRageMath.IsUnit.md)||
|[`bool ArePerpendicular(ref Vector3D a, ref Vector3D b)`](VRageMath.ArePerpendicular.md)||
|[`bool IsZero(Vector3D value)`](VRageMath.IsZero.md)||
|[`bool IsZero(Vector3D value, double epsilon)`](VRageMath.IsZero.md)||
|[`Vector3D IsZeroVector(Vector3D value)`](VRageMath.IsZeroVector.md)||
|[`Vector3D IsZeroVector(Vector3D value, double epsilon)`](VRageMath.IsZeroVector.md)||
|[`Vector3D Step(Vector3D value)`](VRageMath.Step.md)||
|[`string ToString()`](VRageMath.ToString.md)||
|[`bool TryParse(string str, ref Vector3D retval)`](VRageMath.TryParse.md)||
|[`string ToString(string format)`](VRageMath.ToString.md)||
|[`bool Equals(Vector3D other)`](VRageMath.Equals.md)|Determines whether the specified Object is equal to the Vector3.|
|[`bool Equals(Vector3D other, double epsilon)`](VRageMath.Equals.md)||
|[`bool Equals(Object obj)`](VRageMath.Equals.md)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int GetHashCode()`](VRageMath.GetHashCode.md)||
|[`long GetHash()`](VRageMath.GetHash.md)||
|[`double Length()`](VRageMath.Length.md)||
|[`double LengthSquared()`](VRageMath.LengthSquared.md)||
|[`double Distance(Vector3D value1, Vector3D value2)`](VRageMath.Distance.md)||
|[`double Distance(Vector3D value1, Vector3 value2)`](VRageMath.Distance.md)||
|[`double Distance(Vector3 value1, Vector3D value2)`](VRageMath.Distance.md)||
|[`void Distance(ref Vector3D value1, ref Vector3D value2, ref double result)`](VRageMath.Distance.md)||
|[`double DistanceSquared(Vector3D value1, Vector3D value2)`](VRageMath.DistanceSquared.md)||
|[`void DistanceSquared(ref Vector3D value1, ref Vector3D value2, ref double result)`](VRageMath.DistanceSquared.md)||
|[`double RectangularDistance(Vector3D value1, Vector3D value2)`](VRageMath.RectangularDistance.md)||
|[`double RectangularDistance(ref Vector3D value1, ref Vector3D value2)`](VRageMath.RectangularDistance.md)||
|[`double Dot(Vector3D vector1, Vector3D vector2)`](VRageMath.Dot.md)||
|[`double Dot(Vector3D vector1, Vector3 vector2)`](VRageMath.Dot.md)||
|[`void Dot(ref Vector3D vector1, ref Vector3D vector2, ref double result)`](VRageMath.Dot.md)||
|[`void Dot(ref Vector3D vector1, ref Vector3 vector2, ref double result)`](VRageMath.Dot.md)||
|[`void Dot(ref Vector3 vector1, ref Vector3D vector2, ref double result)`](VRageMath.Dot.md)||
|[`double Dot(Vector3D v)`](VRageMath.Dot.md)||
|[`double Dot(Vector3 v)`](VRageMath.Dot.md)||
|[`double Dot(ref Vector3D v)`](VRageMath.Dot.md)||
|[`Vector3D Cross(Vector3D v)`](VRageMath.Cross.md)||
|[`double Normalize()`](VRageMath.Normalize.md)||
|[`Vector3D Normalize(Vector3D value)`](VRageMath.Normalize.md)|Creates a unit vector from the specified vector. The result is a vector one unit in length pointing in the same direction as the original vector.|
|[`void Normalize(ref Vector3D value, ref Vector3D result)`](VRageMath.Normalize.md)||
|[`Vector3D Cross(Vector3D vector1, Vector3D vector2)`](VRageMath.Cross.md)||
|[`void Cross(ref Vector3D vector1, ref Vector3D vector2, ref Vector3D result)`](VRageMath.Cross.md)||
|[`Vector3D Reflect(Vector3D vector, Vector3D normal)`](VRageMath.Reflect.md)||
|[`void Reflect(ref Vector3D vector, ref Vector3D normal, ref Vector3D result)`](VRageMath.Reflect.md)||
|[`Vector3D Reject(Vector3D vector, Vector3D direction)`](VRageMath.Reject.md)||
|[`void Reject(ref Vector3D vector, ref Vector3D direction, ref Vector3D result)`](VRageMath.Reject.md)||
|[`double Min()`](VRageMath.Min.md)||
|[`double AbsMin()`](VRageMath.AbsMin.md)||
|[`double Max()`](VRageMath.Max.md)||
|[`double AbsMax()`](VRageMath.AbsMax.md)||
|[`int AbsMaxComponent()`](VRageMath.AbsMaxComponent.md)||
|[`Vector3D Min(Vector3D value1, Vector3D value2)`](VRageMath.Min.md)||
|[`void Min(ref Vector3D value1, ref Vector3D value2, ref Vector3D result)`](VRageMath.Min.md)||
|[`Vector3D Max(Vector3D value1, Vector3D value2)`](VRageMath.Max.md)||
|[`void Max(ref Vector3D value1, ref Vector3D value2, ref Vector3D result)`](VRageMath.Max.md)||
|[`void MinMax(ref Vector3D min, ref Vector3D max)`](VRageMath.MinMax.md)||
|[`Vector3D DominantAxisProjection(Vector3D value1)`](VRageMath.DominantAxisProjection.md)|Returns a vector that is equal to the projection of the input vector to the coordinate axis that corresponds to the original vector's largest value.|
|[`void DominantAxisProjection(ref Vector3D value1, ref Vector3D result)`](VRageMath.DominantAxisProjection.md)||
|[`Vector3D Clamp(Vector3D value1, Vector3D min, Vector3D max)`](VRageMath.Clamp.md)||
|[`void Clamp(ref Vector3D value1, ref Vector3D min, ref Vector3D max, ref Vector3D result)`](VRageMath.Clamp.md)||
|[`Vector3D ClampToSphere(Vector3D vector, double radius)`](VRageMath.ClampToSphere.md)||
|[`void ClampToSphere(ref Vector3D vector, double radius)`](VRageMath.ClampToSphere.md)||
|[`Vector3D Lerp(Vector3D value1, Vector3D value2, double amount)`](VRageMath.Lerp.md)||
|[`void Lerp(ref Vector3D value1, ref Vector3D value2, double amount, ref Vector3D result)`](VRageMath.Lerp.md)||
|[`Vector3D Barycentric(Vector3D value1, Vector3D value2, Vector3D value3, double amount1, double amount2)`](VRageMath.Barycentric.md)||
|[`void Barycentric(ref Vector3D value1, ref Vector3D value2, ref Vector3D value3, double amount1, double amount2, ref Vector3D result)`](VRageMath.Barycentric.md)||
|[`void Barycentric(Vector3D p, Vector3D a, Vector3D b, Vector3D c, ref double u, ref double v, ref double w)`](VRageMath.Barycentric.md)||
|[`Vector3D SmoothStep(Vector3D value1, Vector3D value2, double amount)`](VRageMath.SmoothStep.md)||
|[`void SmoothStep(ref Vector3D value1, ref Vector3D value2, double amount, ref Vector3D result)`](VRageMath.SmoothStep.md)||
|[`Vector3D CatmullRom(Vector3D value1, Vector3D value2, Vector3D value3, Vector3D value4, double amount)`](VRageMath.CatmullRom.md)||
|[`void CatmullRom(ref Vector3D value1, ref Vector3D value2, ref Vector3D value3, ref Vector3D value4, double amount, ref Vector3D result)`](VRageMath.CatmullRom.md)||
|[`Vector3D Hermite(Vector3D value1, Vector3D tangent1, Vector3D value2, Vector3D tangent2, double amount)`](VRageMath.Hermite.md)||
|[`void Hermite(ref Vector3D value1, ref Vector3D tangent1, ref Vector3D value2, ref Vector3D tangent2, double amount, ref Vector3D result)`](VRageMath.Hermite.md)||
|[`Vector3D Transform(Vector3D position, MatrixD matrix)`](VRageMath.Transform.md)||
|[`Vector3D Transform(Vector3 position, MatrixD matrix)`](VRageMath.Transform.md)||
|[`Vector3D Transform(Vector3D position, Matrix matrix)`](VRageMath.Transform.md)||
|[`Vector3D Transform(Vector3D position, ref MatrixD matrix)`](VRageMath.Transform.md)||
|[`void Transform(ref Vector3D position, ref MatrixD matrix, ref Vector3D result)`](VRageMath.Transform.md)||
|[`void Transform(ref Vector3 position, ref MatrixD matrix, ref Vector3D result)`](VRageMath.Transform.md)||
|[`void TransformNoProjection(ref Vector3D vector, ref MatrixD matrix, ref Vector3D result)`](VRageMath.TransformNoProjection.md)||
|[`void RotateAndScale(ref Vector3D vector, ref MatrixD matrix, ref Vector3D result)`](VRageMath.RotateAndScale.md)||
|[`void Transform(ref Vector3D position, ref MatrixI matrix, ref Vector3D result)`](VRageMath.Transform.md)||
|[`Vector3D TransformNormal(Vector3D normal, Matrix matrix)`](VRageMath.TransformNormal.md)||
|[`Vector3D TransformNormal(Vector3 normal, MatrixD matrix)`](VRageMath.TransformNormal.md)||
|[`Vector3D TransformNormal(Vector3D normal, MatrixD matrix)`](VRageMath.TransformNormal.md)||
|[`void TransformNormal(ref Vector3D normal, ref MatrixD matrix, ref Vector3D result)`](VRageMath.TransformNormal.md)||
|[`void TransformNormal(ref Vector3 normal, ref MatrixD matrix, ref Vector3D result)`](VRageMath.TransformNormal.md)||
