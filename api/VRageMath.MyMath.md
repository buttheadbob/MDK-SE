← [Index](index)
# MyMath Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
<table style="width:100%;display:table">
<tr><td>static _<a href="VRageMath.Vector3One"><code>Vector3 Vector3One</code></a>_</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>static _<a href="VRageMath.InitializeFastSin"><code>void InitializeFastSin()</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.FastSin"><code>float FastSin(float angle)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.FastCos"><code>float FastCos(float angle)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.FastTanH"><code>float FastTanH(float x)</code></a>_</td><td>Fast approximation of Hyperbolic tangent Max deviation is <3%</td></tr>
<tr><td>static _<a href="VRageMath.NormalizeAngle"><code>float NormalizeAngle(float angle, float center)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.ArcTanAngle"><code>float ArcTanAngle(float x, float y)</code></a>_</td><td>ArcTanAngle</td></tr>
<tr><td>static _<a href="VRageMath.Abs"><code>Vector3 Abs(ref Vector3 vector)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.MaxComponents"><code>Vector3 MaxComponents(ref Vector3 a, ref Vector3 b)</code></a>_</td><td>Return vector with each component max</td></tr>
<tr><td>static _<a href="VRageMath.AngleTo"><code>Vector3 AngleTo(Vector3 From, Vector3 Location)</code></a>_</td><td>AngleTo</td></tr>
<tr><td>static _<a href="VRageMath.AngleBetween"><code>float AngleBetween(Vector3 a, Vector3 b)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CosineDistance"><code>float CosineDistance(ref Vector3 a, ref Vector3 b)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CosineDistance"><code>double CosineDistance(ref Vector3D a, ref Vector3D b)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Mod"><code>int Mod(int x, int m)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Mod"><code>long Mod(long x, int m)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.QuaternionToEuler"><code>Vector3 QuaternionToEuler(Quaternion Rotation)</code></a>_</td><td>QuaternionToEuler</td></tr>
<tr><td>static _<a href="VRageMath.ForwardVectorProjection"><code>Vector3 ForwardVectorProjection(Vector3 forwardVector, Vector3 projectedVector)</code></a>_</td><td>This projection results to initial velocity of non-engine objects, which parents move in some velocity We want to add only forward speed of the parent to the forward direction of the object, and if parent is going backward, no speed is added.</td></tr>
<tr><td>static _<a href="VRageMath.CreateFromInsideRadius"><code>BoundingBox CreateFromInsideRadius(float radius)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.VectorFromColor"><code>Vector3 VectorFromColor(byte red, byte green, byte blue)</code></a>_</td><td>Calculates color from vector</td></tr>
<tr><td>static _<a href="VRageMath.VectorFromColor"><code>Vector4 VectorFromColor(byte red, byte green, byte blue, byte alpha)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.DistanceSquaredFromLineSegment"><code>float DistanceSquaredFromLineSegment(Vector3 v, Vector3 w, Vector3 p)</code></a>_</td><td>Return minimum distance between line segment v-w and point p.</td></tr>
<tr><td>static _<a href="VRageMath.Clamp"><code>float Clamp(float val, float min, float max)</code></a>_</td><td></td></tr>
</table>
