← [Index](index)
# CurveKey Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Represents a point in a multi-point curve.
### Properties
|Member|Description|
|---|---|
|[`float&nbsp;Position`](VRageMath.Position)|Position of the CurveKey in the curve.|
|[`float&nbsp;Value`](VRageMath.Value)|Describes the value of this point.|
|[`float&nbsp;TangentIn`](VRageMath.TangentIn)|Describes the tangent when approaching this point from the previous point in the curve.|
|[`float&nbsp;TangentOut`](VRageMath.TangentOut)|Describes the tangent when leaving this point to the next point in the curve.|
|[`CurveContinuity&nbsp;Continuity`](VRageMath.Continuity)|Describes whether the segment between this point and the next point in the curve is discrete or continuous.|
### Methods
|Member|Description|
|---|---|
|[`CurveKey&nbsp;Clone()`](VRageMath.Clone)|Creates a copy of the CurveKey.|
|[`bool&nbsp;Equals(CurveKey&nbsp;other)`](VRageMath.Equals)|Determines whether the specified Object is equal to the CurveKey.|
|[`bool&nbsp;Equals(Object&nbsp;obj)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`int&nbsp;GetHashCode()`](VRageMath.GetHashCode)|Returns the hash code for this instance.|
|[`int&nbsp;CompareTo(CurveKey&nbsp;other)`](VRageMath.CompareTo)|Compares this instance to another CurveKey and returns an indication of their relative values.|
