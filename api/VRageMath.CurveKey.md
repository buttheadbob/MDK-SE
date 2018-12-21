← [Index](index)
# CurveKey Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Represents a point in a multi-point curve.
### Properties
<table style="width:100%;display:table">
<tr><td>[`float Position`](VRageMath.Position)</td><td>Position of the CurveKey in the curve.</td></tr>
<tr><td>[`float Value`](VRageMath.Value)</td><td>Describes the value of this point.</td></tr>
<tr><td>[`float TangentIn`](VRageMath.TangentIn)</td><td>Describes the tangent when approaching this point from the previous point in the curve.</td></tr>
<tr><td>[`float TangentOut`](VRageMath.TangentOut)</td><td>Describes the tangent when leaving this point to the next point in the curve.</td></tr>
<tr><td>[`CurveContinuity Continuity`](VRageMath.Continuity)</td><td>Describes whether the segment between this point and the next point in the curve is discrete or continuous.</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>[`CurveKey Clone()`](VRageMath.Clone)</td><td>Creates a copy of the CurveKey.</td></tr>
<tr><td>[`bool Equals(CurveKey other)`](VRageMath.Equals)</td><td>Determines whether the specified Object is equal to the CurveKey.</td></tr>
<tr><td>[`bool Equals(Object obj)`](VRageMath.Equals)</td><td>Returns a value that indicates whether the current instance is equal to a specified object.</td></tr>
<tr><td>[`int GetHashCode()`](VRageMath.GetHashCode)</td><td>Returns the hash code for this instance.</td></tr>
<tr><td>[`int CompareTo(CurveKey other)`](VRageMath.CompareTo)</td><td>Compares this instance to another CurveKey and returns an indication of their relative values.</td></tr>
</table>
