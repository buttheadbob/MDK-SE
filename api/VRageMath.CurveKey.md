← [Index](Api-Index)
# CurveKey Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Represents a point in a multi-point curve.
### Properties
|Member|Description|
|---|---|
|[`Position`](VRageMath.Position)|Position of the CurveKey in the curve.|
|[`Value`](VRageMath.Value)|Describes the value of this point.|
|[`TangentIn`](VRageMath.TangentIn)|Describes the tangent when approaching this point from the previous point in the curve.|
|[`TangentOut`](VRageMath.TangentOut)|Describes the tangent when leaving this point to the next point in the curve.|
|[`Continuity`](VRageMath.Continuity)|Describes whether the segment between this point and the next point in the curve is discrete or continuous.|
### Methods
|Member|Description|
|---|---|
|[`Clone()`](VRageMath.Clone)|Creates a copy of the CurveKey.|
|[`Equals(CurveKey)`](VRageMath.Equals)|Determines whether the specified Object is equal to the CurveKey.|
|[`Equals(Object)`](VRageMath.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[`GetHashCode()`](VRageMath.GetHashCode)|Returns the hash code for this instance.|
|[`CompareTo(CurveKey)`](VRageMath.CompareTo)|Compares this instance to another CurveKey and returns an indication of their relative values.|
