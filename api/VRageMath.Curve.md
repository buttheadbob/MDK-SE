← [Index](index)
# Curve Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Stores an arbitrary collection of 2D CurveKey points, and provides methods for evaluating features of the curve they define.
### Properties
|Member|Description|
|---|---|
|[`CurveLoopType PreLoop`](VRageMath.PreLoop)|Specifies how to handle weighting values that are less than the first control point in the curve.|
|[`CurveLoopType PostLoop`](VRageMath.PostLoop)|Specifies how to handle weighting values that are greater than the last control point in the curve.|
|[`CurveKeyCollection Keys`](VRageMath.Keys)|The points that make up the curve.|
|[`bool IsConstant`](VRageMath.IsConstant)|Gets a value indicating whether the curve is constant.|
### Methods
|Member|Description|
|---|---|
|[`Curve Clone()`](VRageMath.Clone)|Creates a copy of the Curve.|
|[`void ComputeTangent(int keyIndex, CurveTangent tangentType)`](VRageMath.ComputeTangent)|Computes both the TangentIn and the TangentOut for a CurveKey specified by its index.|
|[`void ComputeTangent(int keyIndex, CurveTangent tangentInType, CurveTangent tangentOutType)`](VRageMath.ComputeTangent)|Computes a specified type of TangentIn and a specified type of TangentOut for a given CurveKey.|
|[`void ComputeTangents(CurveTangent tangentType)`](VRageMath.ComputeTangents)|Computes all tangents for all CurveKeys in this Curve, using a specified tangent type for both TangentIn and TangentOut.|
|[`void ComputeTangents(CurveTangent tangentInType, CurveTangent tangentOutType)`](VRageMath.ComputeTangents)|Computes all tangents for all CurveKeys in this Curve, using different tangent types for TangentOut and TangentIn.|
|[`float Evaluate(float position)`](VRageMath.Evaluate)|Finds the value at a position on the Curve.|
