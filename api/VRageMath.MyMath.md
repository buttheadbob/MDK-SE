← [Index](index)
# MyMath Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|static [`VRageMath.Vector3 Vector3One`](VRageMath.Vector3One)||
### Methods
|Member|Description|
|---|---|
|static [`void InitializeFastSin()`](VRageMath.InitializeFastSin)||
|static [`float FastSin(float)`](VRageMath.FastSin)||
|static [`float FastCos(float)`](VRageMath.FastCos)||
|static [`float FastTanH(float)`](VRageMath.FastTanH)|Fast approximation of Hyperbolic tangent Max deviation is <3%|
|static [`float NormalizeAngle(float, float)`](VRageMath.NormalizeAngle)||
|static [`float ArcTanAngle(float, float)`](VRageMath.ArcTanAngle)|ArcTanAngle|
|static [`VRageMath.Vector3 Abs(ref VRageMath.Vector3)`](VRageMath.Abs)||
|static [`VRageMath.Vector3 MaxComponents(ref VRageMath.Vector3, ref VRageMath.Vector3)`](VRageMath.MaxComponents)|Return vector with each component max|
|static [`VRageMath.Vector3 AngleTo(VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.AngleTo)|AngleTo|
|static [`float AngleBetween(VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.AngleBetween)||
|static [`float CosineDistance(ref VRageMath.Vector3, ref VRageMath.Vector3)`](VRageMath.CosineDistance)||
|static [`double CosineDistance(ref VRageMath.Vector3D, ref VRageMath.Vector3D)`](VRageMath.CosineDistance)||
|static [`int Mod(int, int)`](VRageMath.Mod)||
|static [`long Mod(long, int)`](VRageMath.Mod)||
|static [`VRageMath.Vector3 QuaternionToEuler(VRageMath.Quaternion)`](VRageMath.QuaternionToEuler)|QuaternionToEuler|
|static [`VRageMath.Vector3 ForwardVectorProjection(VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.ForwardVectorProjection)|This projection results to initial velocity of non-engine objects, which parents move in some velocity We want to add only forward speed of the parent to the forward direction of the object, and if parent is going backward, no speed is added.|
|static [`VRageMath.BoundingBox CreateFromInsideRadius(float)`](VRageMath.CreateFromInsideRadius)||
|static [`VRageMath.Vector3 VectorFromColor(byte, byte, byte)`](VRageMath.VectorFromColor)|Calculates color from vector|
|static [`VRageMath.Vector4 VectorFromColor(byte, byte, byte, byte)`](VRageMath.VectorFromColor)||
|static [`float DistanceSquaredFromLineSegment(VRageMath.Vector3, VRageMath.Vector3, VRageMath.Vector3)`](VRageMath.DistanceSquaredFromLineSegment)|Return minimum distance between line segment v-w and point p.|
|static [`float Clamp(float, float, float)`](VRageMath.Clamp)||
