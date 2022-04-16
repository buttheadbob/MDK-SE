← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### MyMath Class

```csharp
public abstract sealed class MyMath
```

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

#### Fields

|Member|Description|
|---|---|
|[static Vector3 Vector3One](VRageMath.MyMath.Vector3One)||

#### Methods

|Member|Description|
|---|---|
|[static Vector3 Abs(ref Vector3)](VRageMath.MyMath.Abs)||
|[static float AngleBetween(Vector3, Vector3)](VRageMath.MyMath.AngleBetween)||
|[static Vector3 AngleTo(Vector3, Vector3)](VRageMath.MyMath.AngleTo)|AngleTo|
|[static float ArcTanAngle(float, float)](VRageMath.MyMath.ArcTanAngle)|ArcTanAngle|
|[static float Clamp(float, float, float)](VRageMath.MyMath.Clamp)||
|[static float CosineDistance(ref Vector3, ref Vector3)](VRageMath.MyMath.CosineDistance)||
|[static double CosineDistance(ref Vector3D, ref Vector3D)](VRageMath.MyMath.CosineDistance)||
|[static BoundingBox CreateFromInsideRadius(float)](VRageMath.MyMath.CreateFromInsideRadius)||
|[static float DistanceSquaredFromLineSegment(Vector3, Vector3, Vector3)](VRageMath.MyMath.DistanceSquaredFromLineSegment)|Return minimum distance between line segment v-w and point p.|
|[static float FastCos(float)](VRageMath.MyMath.FastCos)||
|[static float FastSin(float)](VRageMath.MyMath.FastSin)||
|[static float FastTanH(float)](VRageMath.MyMath.FastTanH)|Fast approximation of Hyperbolic tangent Max deviation is <3%|
|[static Vector3 ForwardVectorProjection(Vector3, Vector3)](VRageMath.MyMath.ForwardVectorProjection)|This projection results to initial velocity of non-engine objects, which parents move in some velocity We want to add only forward speed of the parent to the forward direction of the object, and if parent is going backward, no speed is added.|
|[static void InitializeFastSin()](VRageMath.MyMath.InitializeFastSin)||
|[static Vector3 MaxComponents(ref Vector3, ref Vector3)](VRageMath.MyMath.MaxComponents)|Return vector with each component max|
|[static int Mod(int, int)](VRageMath.MyMath.Mod)||
|[static long Mod(long, int)](VRageMath.MyMath.Mod)||
|[static float NormalizeAngle(float, \[float])](VRageMath.MyMath.NormalizeAngle)||
|[static Vector3 QuaternionToEuler(Quaternion)](VRageMath.MyMath.QuaternionToEuler)|QuaternionToEuler|
|[static Vector3 VectorFromColor(byte, byte, byte)](VRageMath.MyMath.VectorFromColor)|Calculates color from vector|
|[static Vector4 VectorFromColor(byte, byte, byte, byte)](VRageMath.MyMath.VectorFromColor)||

