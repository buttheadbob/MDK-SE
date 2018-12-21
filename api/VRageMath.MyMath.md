← [Index](index)
# MyMath Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|static [`Vector3One`](VRageMath.Vector3One)||
### Methods
|Member|Description|
|---|---|
|static [`InitializeFastSin()`](VRageMath.InitializeFastSin)||
|static [`FastSin(float)`](VRageMath.FastSin)||
|static [`FastCos(float)`](VRageMath.FastCos)||
|static [`FastTanH(float)`](VRageMath.FastTanH)|Fast approximation of Hyperbolic tangent Max deviation is <3%|
|static [`NormalizeAngle(float, float)`](VRageMath.NormalizeAngle)||
|static [`ArcTanAngle(float, float)`](VRageMath.ArcTanAngle)|ArcTanAngle|
|static [`Abs(ref Vector3)`](VRageMath.Abs)||
|static [`MaxComponents(ref Vector3, ref Vector3)`](VRageMath.MaxComponents)|Return vector with each component max|
|static [`AngleTo(Vector3, Vector3)`](VRageMath.AngleTo)|AngleTo|
|static [`AngleBetween(Vector3, Vector3)`](VRageMath.AngleBetween)||
|static [`CosineDistance(ref Vector3, ref Vector3)`](VRageMath.CosineDistance)||
|static [`CosineDistance(ref Vector3D, ref Vector3D)`](VRageMath.CosineDistance)||
|static [`Mod(int, int)`](VRageMath.Mod)||
|static [`Mod(long, int)`](VRageMath.Mod)||
|static [`QuaternionToEuler(Quaternion)`](VRageMath.QuaternionToEuler)|QuaternionToEuler|
|static [`ForwardVectorProjection(Vector3, Vector3)`](VRageMath.ForwardVectorProjection)|This projection results to initial velocity of non-engine objects, which parents move in some velocity We want to add only forward speed of the parent to the forward direction of the object, and if parent is going backward, no speed is added.|
|static [`CreateFromInsideRadius(float)`](VRageMath.CreateFromInsideRadius)||
|static [`VectorFromColor(byte, byte, byte)`](VRageMath.VectorFromColor)|Calculates color from vector|
|static [`VectorFromColor(byte, byte, byte, byte)`](VRageMath.VectorFromColor)||
|static [`DistanceSquaredFromLineSegment(Vector3, Vector3, Vector3)`](VRageMath.DistanceSquaredFromLineSegment)|Return minimum distance between line segment v-w and point p.|
|static [`Clamp(float, float, float)`](VRageMath.Clamp)||
