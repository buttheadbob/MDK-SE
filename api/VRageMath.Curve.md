← [Index](index)
# Curve Class
**Namespace:** VRageMath  
**Assembly:** VRage.Math.dll  
## Summary
Stores an arbitrary collection of 2D CurveKey points, and provides methods for evaluating features of the curve they define.
### Properties
|Member|Description|
|---|---|
|[`CurveLoopType PreLoop`](VRageMath.PreLoop)||
|[`CurveLoopType PostLoop`](VRageMath.PostLoop)||
|[`CurveKeyCollection Keys`](VRageMath.Keys)||
|[`bool IsConstant`](VRageMath.IsConstant)||
### Methods
|Member|Description|
|---|---|
|[`Curve Clone()`](VRageMath.Clone)||
|[`void ComputeTangent(int keyIndex, CurveTangent tangentType)`](VRageMath.ComputeTangent)||
|[`void ComputeTangent(int keyIndex, CurveTangent tangentInType, CurveTangent tangentOutType)`](VRageMath.ComputeTangent)||
|[`void ComputeTangents(CurveTangent tangentType)`](VRageMath.ComputeTangents)|Computes all tangents for all CurveKeys in this Curve, using a specified tangent type for both TangentIn and TangentOut.|
|[`void ComputeTangents(CurveTangent tangentInType, CurveTangent tangentOutType)`](VRageMath.ComputeTangents)||
|[`float Evaluate(float position)`](VRageMath.Evaluate)|Finds the value at a position on the Curve.|
