← [Index](index.md)
# Curve Class
** Namespace: ** VRageMath  
** Assembly: ** VRage.Math.dll  
## Summary
Stores an arbitrary collection of 2D CurveKey points, and provides methods for evaluating features of the curve they define.
### Properties
|Member|Description|
|---|---|
|[`CurveLoopType PreLoop`](VRageMath.PreLoop.md)||
|[`CurveLoopType PostLoop`](VRageMath.PostLoop.md)||
|[`CurveKeyCollection Keys`](VRageMath.Keys.md)||
|[`bool IsConstant`](VRageMath.IsConstant.md)||
### Methods
|Member|Description|
|---|---|
|[`Curve Clone()`](VRageMath.Clone.md)||
|[`void ComputeTangent(int keyIndex, CurveTangent tangentType)`](VRageMath.ComputeTangent.md)||
|[`void ComputeTangent(int keyIndex, CurveTangent tangentInType, CurveTangent tangentOutType)`](VRageMath.ComputeTangent.md)||
|[`void ComputeTangents(CurveTangent tangentType)`](VRageMath.ComputeTangents.md)|Computes all tangents for all CurveKeys in this Curve, using a specified tangent type for both TangentIn and TangentOut.|
|[`void ComputeTangents(CurveTangent tangentInType, CurveTangent tangentOutType)`](VRageMath.ComputeTangents.md)||
|[`float Evaluate(float position)`](VRageMath.Evaluate.md)|Finds the value at a position on the Curve.|
