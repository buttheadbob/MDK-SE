← [Index](index)
# MatrixI Struct
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
### Fields
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Right"><code>Direction Right</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Up"><code>Direction Up</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Backward"><code>Direction Backward</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Translation"><code>Vector3I Translation</code></a>_</td><td></td></tr>
</table>
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Left"><code>Direction Left</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Down"><code>Direction Down</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.Forward"><code>Direction Forward</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.RightVector"><code>Vector3I RightVector</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.LeftVector"><code>Vector3I LeftVector</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.UpVector"><code>Vector3I UpVector</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.DownVector"><code>Vector3I DownVector</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.BackwardVector"><code>Vector3I BackwardVector</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.ForwardVector"><code>Vector3I ForwardVector</code></a>_</td><td></td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.GetDirection"><code>Direction GetDirection(Direction direction)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.SetDirection"><code>void SetDirection(Direction dirToSet, Direction newDirection)</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.GetBlockOrientation"><code>MyBlockOrientation GetBlockOrientation()</code></a>_</td><td></td></tr>
<tr><td>_<a href="VRageMath.GetFloatMatrix"><code>Matrix GetFloatMatrix()</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.CreateRotation"><code>MatrixI CreateRotation(Direction oldA, Direction oldB, Direction newA, Direction newB)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Invert"><code>void Invert(ref MatrixI matrix, ref MatrixI result)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Multiply"><code>void Multiply(ref MatrixI leftMatrix, ref MatrixI rightMatrix, ref MatrixI result)</code></a>_</td><td></td></tr>
<tr><td>static _<a href="VRageMath.Transform"><code>MyBlockOrientation Transform(ref MyBlockOrientation orientation, ref MatrixI transform)</code></a>_</td><td></td></tr>
</table>
