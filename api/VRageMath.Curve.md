← [Index](index)
# Curve Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Stores an arbitrary collection of 2D CurveKey points, and provides methods for evaluating features of the curve they define.
### Properties
|Member|Description|
|---|---|
|[`CurveLoopType&nbsp;PreLoop`](VRageMath.PreLoop)|Specifies how to handle weighting values that are less than the first control point in the curve.|
|[`CurveLoopType&nbsp;PostLoop`](VRageMath.PostLoop)|Specifies how to handle weighting values that are greater than the last control point in the curve.|
|[`CurveKeyCollection&nbsp;Keys`](VRageMath.Keys)|The points that make up the curve.|
|[`bool&nbsp;IsConstant`](VRageMath.IsConstant)|Gets a value indicating whether the curve is constant.|
### Methods
|Member|Description|
|---|---|
|[`Curve&nbsp;Clone()`](VRageMath.Clone)|Creates a copy of the Curve.|
|[`void&nbsp;ComputeTangent(int&nbsp;keyIndex,&nbsp;CurveTangent&nbsp;tangentType)`](VRageMath.ComputeTangent)|Computes both the TangentIn and the TangentOut for a CurveKey specified by its index.|
|[`void&nbsp;ComputeTangent(int&nbsp;keyIndex,&nbsp;CurveTangent&nbsp;tangentInType,&nbsp;CurveTangent&nbsp;tangentOutType)`](VRageMath.ComputeTangent)|Computes a specified type of TangentIn and a specified type of TangentOut for a given CurveKey.|
|[`void&nbsp;ComputeTangents(CurveTangent&nbsp;tangentType)`](VRageMath.ComputeTangents)|Computes all tangents for all CurveKeys in this Curve, using a specified tangent type for both TangentIn and TangentOut.|
|[`void&nbsp;ComputeTangents(CurveTangent&nbsp;tangentInType,&nbsp;CurveTangent&nbsp;tangentOutType)`](VRageMath.ComputeTangents)|Computes all tangents for all CurveKeys in this Curve, using different tangent types for TangentOut and TangentIn.|
|[`float&nbsp;Evaluate(float&nbsp;position)`](VRageMath.Evaluate)|Finds the value at a position on the Curve.|
