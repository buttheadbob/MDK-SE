← [Index](index)
# MyMath Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
|Member|Description|
|---|---|
|static&nbsp;[`Vector3&nbsp;Vector3One`](VRageMath.Vector3One)||
### Methods
|Member|Description|
|---|---|
|static&nbsp;[`void&nbsp;InitializeFastSin()`](VRageMath.InitializeFastSin)||
|static&nbsp;[`float&nbsp;FastSin(float&nbsp;angle)`](VRageMath.FastSin)||
|static&nbsp;[`float&nbsp;FastCos(float&nbsp;angle)`](VRageMath.FastCos)||
|static&nbsp;[`float&nbsp;FastTanH(float&nbsp;x)`](VRageMath.FastTanH)|Fast approximation of Hyperbolic tangent Max deviation is <3%|
|static&nbsp;[`float&nbsp;NormalizeAngle(float&nbsp;angle,&nbsp;float&nbsp;center)`](VRageMath.NormalizeAngle)||
|static&nbsp;[`float&nbsp;ArcTanAngle(float&nbsp;x,&nbsp;float&nbsp;y)`](VRageMath.ArcTanAngle)|ArcTanAngle|
|static&nbsp;[`Vector3&nbsp;Abs(ref&nbsp;Vector3&nbsp;vector)`](VRageMath.Abs)||
|static&nbsp;[`Vector3&nbsp;MaxComponents(ref&nbsp;Vector3&nbsp;a,&nbsp;ref&nbsp;Vector3&nbsp;b)`](VRageMath.MaxComponents)|Return vector with each component max|
|static&nbsp;[`Vector3&nbsp;AngleTo(Vector3&nbsp;From,&nbsp;Vector3&nbsp;Location)`](VRageMath.AngleTo)|AngleTo|
|static&nbsp;[`float&nbsp;AngleBetween(Vector3&nbsp;a,&nbsp;Vector3&nbsp;b)`](VRageMath.AngleBetween)||
|static&nbsp;[`float&nbsp;CosineDistance(ref&nbsp;Vector3&nbsp;a,&nbsp;ref&nbsp;Vector3&nbsp;b)`](VRageMath.CosineDistance)||
|static&nbsp;[`double&nbsp;CosineDistance(ref&nbsp;Vector3D&nbsp;a,&nbsp;ref&nbsp;Vector3D&nbsp;b)`](VRageMath.CosineDistance)||
|static&nbsp;[`int&nbsp;Mod(int&nbsp;x,&nbsp;int&nbsp;m)`](VRageMath.Mod)||
|static&nbsp;[`long&nbsp;Mod(long&nbsp;x,&nbsp;int&nbsp;m)`](VRageMath.Mod)||
|static&nbsp;[`Vector3&nbsp;QuaternionToEuler(Quaternion&nbsp;Rotation)`](VRageMath.QuaternionToEuler)|QuaternionToEuler|
|static&nbsp;[`Vector3&nbsp;ForwardVectorProjection(Vector3&nbsp;forwardVector,&nbsp;Vector3&nbsp;projectedVector)`](VRageMath.ForwardVectorProjection)|This projection results to initial velocity of non-engine objects, which parents move in some velocity We want to add only forward speed of the parent to the forward direction of the object, and if parent is going backward, no speed is added.|
|static&nbsp;[`BoundingBox&nbsp;CreateFromInsideRadius(float&nbsp;radius)`](VRageMath.CreateFromInsideRadius)||
|static&nbsp;[`Vector3&nbsp;VectorFromColor(byte&nbsp;red,&nbsp;byte&nbsp;green,&nbsp;byte&nbsp;blue)`](VRageMath.VectorFromColor)|Calculates color from vector|
|static&nbsp;[`Vector4&nbsp;VectorFromColor(byte&nbsp;red,&nbsp;byte&nbsp;green,&nbsp;byte&nbsp;blue,&nbsp;byte&nbsp;alpha)`](VRageMath.VectorFromColor)||
|static&nbsp;[`float&nbsp;DistanceSquaredFromLineSegment(Vector3&nbsp;v,&nbsp;Vector3&nbsp;w,&nbsp;Vector3&nbsp;p)`](VRageMath.DistanceSquaredFromLineSegment)|Return minimum distance between line segment v-w and point p.|
|static&nbsp;[`float&nbsp;Clamp(float&nbsp;val,&nbsp;float&nbsp;min,&nbsp;float&nbsp;max)`](VRageMath.Clamp)||
