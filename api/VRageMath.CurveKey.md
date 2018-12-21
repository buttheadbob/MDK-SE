← [Index](index)
# CurveKey Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Represents a point in a multi-point curve.
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Position"><code>float Position</code></a>_</td><td>Position of the CurveKey in the curve.</td></tr>
<tr><td>_<a href="VRageMath.Value"><code>float Value</code></a>_</td><td>Describes the value of this point.</td></tr>
<tr><td>_<a href="VRageMath.TangentIn"><code>float TangentIn</code></a>_</td><td>Describes the tangent when approaching this point from the previous point in the curve.</td></tr>
<tr><td>_<a href="VRageMath.TangentOut"><code>float TangentOut</code></a>_</td><td>Describes the tangent when leaving this point to the next point in the curve.</td></tr>
<tr><td>_<a href="VRageMath.Continuity"><code>CurveContinuity Continuity</code></a>_</td><td>Describes whether the segment between this point and the next point in the curve is discrete or continuous.</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Clone"><code>CurveKey Clone()</code></a>_</td><td>Creates a copy of the CurveKey.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(CurveKey other)</code></a>_</td><td>Determines whether the specified Object is equal to the CurveKey.</td></tr>
<tr><td>_<a href="VRageMath.Equals"><code>bool Equals(Object obj)</code></a>_</td><td>Returns a value that indicates whether the current instance is equal to a specified object.</td></tr>
<tr><td>_<a href="VRageMath.GetHashCode"><code>int GetHashCode()</code></a>_</td><td>Returns the hash code for this instance.</td></tr>
<tr><td>_<a href="VRageMath.CompareTo"><code>int CompareTo(CurveKey other)</code></a>_</td><td>Compares this instance to another CurveKey and returns an indication of their relative values.</td></tr>
</table>
