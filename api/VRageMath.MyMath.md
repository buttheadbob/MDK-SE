← [Index](index)
# MyMath Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
<table style="width: 100%">
<tr><td>static [`Vector3 Vector3One`](VRageMath.Vector3One)</td><td></td></tr>
</table>
### Methods
<table style="width: 100%">
<tr><td>static [`void InitializeFastSin()`](VRageMath.InitializeFastSin)</td><td></td></tr>
<tr><td>static [`float FastSin(float angle)`](VRageMath.FastSin)</td><td></td></tr>
<tr><td>static [`float FastCos(float angle)`](VRageMath.FastCos)</td><td></td></tr>
<tr><td>static [`float FastTanH(float x)`](VRageMath.FastTanH)</td><td>Fast approximation of Hyperbolic tangent Max deviation is <3%</td></tr>
<tr><td>static [`float NormalizeAngle(float angle, float center)`](VRageMath.NormalizeAngle)</td><td></td></tr>
<tr><td>static [`float ArcTanAngle(float x, float y)`](VRageMath.ArcTanAngle)</td><td>ArcTanAngle</td></tr>
<tr><td>static [`Vector3 Abs(ref Vector3 vector)`](VRageMath.Abs)</td><td></td></tr>
<tr><td>static [`Vector3 MaxComponents(ref Vector3 a, ref Vector3 b)`](VRageMath.MaxComponents)</td><td>Return vector with each component max</td></tr>
<tr><td>static [`Vector3 AngleTo(Vector3 From, Vector3 Location)`](VRageMath.AngleTo)</td><td>AngleTo</td></tr>
<tr><td>static [`float AngleBetween(Vector3 a, Vector3 b)`](VRageMath.AngleBetween)</td><td></td></tr>
<tr><td>static [`float CosineDistance(ref Vector3 a, ref Vector3 b)`](VRageMath.CosineDistance)</td><td></td></tr>
<tr><td>static [`double CosineDistance(ref Vector3D a, ref Vector3D b)`](VRageMath.CosineDistance)</td><td></td></tr>
<tr><td>static [`int Mod(int x, int m)`](VRageMath.Mod)</td><td></td></tr>
<tr><td>static [`long Mod(long x, int m)`](VRageMath.Mod)</td><td></td></tr>
<tr><td>static [`Vector3 QuaternionToEuler(Quaternion Rotation)`](VRageMath.QuaternionToEuler)</td><td>QuaternionToEuler</td></tr>
<tr><td>static [`Vector3 ForwardVectorProjection(Vector3 forwardVector, Vector3 projectedVector)`](VRageMath.ForwardVectorProjection)</td><td>This projection results to initial velocity of non-engine objects, which parents move in some velocity We want to add only forward speed of the parent to the forward direction of the object, and if parent is going backward, no speed is added.</td></tr>
<tr><td>static [`BoundingBox CreateFromInsideRadius(float radius)`](VRageMath.CreateFromInsideRadius)</td><td></td></tr>
<tr><td>static [`Vector3 VectorFromColor(byte red, byte green, byte blue)`](VRageMath.VectorFromColor)</td><td>Calculates color from vector</td></tr>
<tr><td>static [`Vector4 VectorFromColor(byte red, byte green, byte blue, byte alpha)`](VRageMath.VectorFromColor)</td><td></td></tr>
<tr><td>static [`float DistanceSquaredFromLineSegment(Vector3 v, Vector3 w, Vector3 p)`](VRageMath.DistanceSquaredFromLineSegment)</td><td>Return minimum distance between line segment v-w and point p.</td></tr>
<tr><td>static [`float Clamp(float val, float min, float max)`](VRageMath.Clamp)</td><td></td></tr>
</table>
