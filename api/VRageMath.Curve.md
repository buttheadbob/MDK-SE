← [Index](index)
# Curve Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Stores an arbitrary collection of 2D CurveKey points, and provides methods for evaluating features of the curve they define.
### Properties
|Member|Description|
|---|---|
|[`PreLoop`](VRageMath.PreLoop)|Specifies how to handle weighting values that are less than the first control point in the curve.|
|[`PostLoop`](VRageMath.PostLoop)|Specifies how to handle weighting values that are greater than the last control point in the curve.|
|[`Keys`](VRageMath.Keys)|The points that make up the curve.|
|[`IsConstant`](VRageMath.IsConstant)|Gets a value indicating whether the curve is constant.|
### Methods
|Member|Description|
|---|---|
|[`Clone()`](VRageMath.Clone)|Creates a copy of the Curve.|
|[`ComputeTangent(int, CurveTangent)`](VRageMath.ComputeTangent)|Computes both the TangentIn and the TangentOut for a CurveKey specified by its index.|
|[`ComputeTangent(int, CurveTangent, CurveTangent)`](VRageMath.ComputeTangent)|Computes a specified type of TangentIn and a specified type of TangentOut for a given CurveKey.|
|[`ComputeTangents(CurveTangent)`](VRageMath.ComputeTangents)|Computes all tangents for all CurveKeys in this Curve, using a specified tangent type for both TangentIn and TangentOut.|
|[`ComputeTangents(CurveTangent, CurveTangent)`](VRageMath.ComputeTangents)|Computes all tangents for all CurveKeys in this Curve, using different tangent types for TangentOut and TangentIn.|
|[`Evaluate(float)`](VRageMath.Evaluate)|Finds the value at a position on the Curve.|
