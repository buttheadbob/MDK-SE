← [Index](index)
# MyMath Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|static [`Vector3 Vector3One`](VRageMath.Vector3One)||
### Methods
|Member|Description|
|---|---|
|static [`void InitializeFastSin()`](VRageMath.InitializeFastSin)||
|static [`float FastSin(float angle)`](VRageMath.FastSin)||
|static [`float FastCos(float angle)`](VRageMath.FastCos)||
|static [`float FastTanH(float x)`](VRageMath.FastTanH)|Fast approximation of Hyperbolic tangent Max deviation is <3%|
|static [`float NormalizeAngle(float angle, float center)`](VRageMath.NormalizeAngle)||
|static [`float ArcTanAngle(float x, float y)`](VRageMath.ArcTanAngle)|ArcTanAngle|
|static [`Vector3 Abs(ref Vector3 vector)`](VRageMath.Abs)||
|static [`Vector3 MaxComponents(ref Vector3 a, ref Vector3 b)`](VRageMath.MaxComponents)|Return vector with each component max|
|static [`Vector3 AngleTo(Vector3 From, Vector3 Location)`](VRageMath.AngleTo)|AngleTo|
|static [`float AngleBetween(Vector3 a, Vector3 b)`](VRageMath.AngleBetween)||
|static [`float CosineDistance(ref Vector3 a, ref Vector3 b)`](VRageMath.CosineDistance)||
|static [`double CosineDistance(ref Vector3D a, ref Vector3D b)`](VRageMath.CosineDistance)||
|static [`int Mod(int x, int m)`](VRageMath.Mod)||
|static [`long Mod(long x, int m)`](VRageMath.Mod)||
|static [`Vector3 QuaternionToEuler(Quaternion Rotation)`](VRageMath.QuaternionToEuler)|QuaternionToEuler|
|static [`Vector3 ForwardVectorProjection(Vector3 forwardVector, Vector3 projectedVector)`](VRageMath.ForwardVectorProjection)|This projection results to initial velocity of non-engine objects, which parents move in some velocity We want to add only forward speed of the parent to the forward direction of the object, and if parent is going backward, no speed is added.|
|static [`BoundingBox CreateFromInsideRadius(float radius)`](VRageMath.CreateFromInsideRadius)||
|static [`Vector3 VectorFromColor(byte red, byte green, byte blue)`](VRageMath.VectorFromColor)|Calculates color from vector|
|static [`Vector4 VectorFromColor(byte red, byte green, byte blue, byte alpha)`](VRageMath.VectorFromColor)||
|static [`float DistanceSquaredFromLineSegment(Vector3 v, Vector3 w, Vector3 p)`](VRageMath.DistanceSquaredFromLineSegment)|Return minimum distance between line segment v-w and point p.|
|static [`float Clamp(float val, float min, float max)`](VRageMath.Clamp)||
