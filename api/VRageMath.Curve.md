← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### Curve Class

```csharp
public class Curve
```

Stores an arbitrary collection of 2D CurveKey points, and provides methods for evaluating features of the curve they define.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

#### Properties

|Member|Description|
|---|---|
|\\%1bool IsConstant { get; }](VRageMath.Curve.IsConstant)|Gets a value indicating whether the curve is constant.|
|\\%1CurveKeyCollection Keys { get; }](VRageMath.Curve.Keys)|The points that make up the curve.|
|\\%1CurveLoopType PostLoop { get; set; }](VRageMath.Curve.PostLoop)|Specifies how to handle weighting values that are greater than the last control point in the curve.|
|\\%1CurveLoopType PreLoop { get; set; }](VRageMath.Curve.PreLoop)|Specifies how to handle weighting values that are less than the first control point in the curve.|

#### Constructors

|Member|Description|
|---|---|
|\\%1Curve()](VRageMath.Curve..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\%1Curve Clone()](VRageMath.Curve.Clone)|Creates a copy of the Curve.|
|\\%1void ComputeTangent(int, CurveTangent)](VRageMath.Curve.ComputeTangent)|Computes both the TangentIn and the TangentOut for a CurveKey specified by its index.|
|\\%1void ComputeTangent(int, CurveTangent, CurveTangent)](VRageMath.Curve.ComputeTangent)|Computes a specified type of TangentIn and a specified type of TangentOut for a given CurveKey.|
|\\%1void ComputeTangents(CurveTangent)](VRageMath.Curve.ComputeTangents)|Computes all tangents for all CurveKeys in this Curve, using a specified tangent type for both TangentIn and TangentOut.|
|\\%1void ComputeTangents(CurveTangent, CurveTangent)](VRageMath.Curve.ComputeTangents)|Computes all tangents for all CurveKeys in this Curve, using different tangent types for TangentOut and TangentIn.|
|\\%1float Evaluate(float)](VRageMath.Curve.Evaluate)|Finds the value at a position on the Curve.|

