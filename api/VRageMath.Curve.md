← [Index](index)
# Curve Class
**Namespace:** [`VRageMath`](VRageMath)  
**Assembly:** VRage.Math.dll  
## Summary
Stores an arbitrary collection of 2D CurveKey points, and provides methods for evaluating features of the curve they define.
### Properties
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.PreLoop"><code>CurveLoopType PreLoop</code></a>_</td><td>Specifies how to handle weighting values that are less than the first control point in the curve.</td></tr>
<tr><td>_<a href="VRageMath.PostLoop"><code>CurveLoopType PostLoop</code></a>_</td><td>Specifies how to handle weighting values that are greater than the last control point in the curve.</td></tr>
<tr><td>_<a href="VRageMath.Keys"><code>CurveKeyCollection Keys</code></a>_</td><td>The points that make up the curve.</td></tr>
<tr><td>_<a href="VRageMath.IsConstant"><code>bool IsConstant</code></a>_</td><td>Gets a value indicating whether the curve is constant.</td></tr>
</table>
### Methods
<table style="width:100%;display:table">
<tr><td>_<a href="VRageMath.Clone"><code>Curve Clone()</code></a>_</td><td>Creates a copy of the Curve.</td></tr>
<tr><td>_<a href="VRageMath.ComputeTangent"><code>void ComputeTangent(int keyIndex, CurveTangent tangentType)</code></a>_</td><td>Computes both the TangentIn and the TangentOut for a CurveKey specified by its index.</td></tr>
<tr><td>_<a href="VRageMath.ComputeTangent"><code>void ComputeTangent(int keyIndex, CurveTangent tangentInType, CurveTangent tangentOutType)</code></a>_</td><td>Computes a specified type of TangentIn and a specified type of TangentOut for a given CurveKey.</td></tr>
<tr><td>_<a href="VRageMath.ComputeTangents"><code>void ComputeTangents(CurveTangent tangentType)</code></a>_</td><td>Computes all tangents for all CurveKeys in this Curve, using a specified tangent type for both TangentIn and TangentOut.</td></tr>
<tr><td>_<a href="VRageMath.ComputeTangents"><code>void ComputeTangents(CurveTangent tangentInType, CurveTangent tangentOutType)</code></a>_</td><td>Computes all tangents for all CurveKeys in this Curve, using different tangent types for TangentOut and TangentIn.</td></tr>
<tr><td>_<a href="VRageMath.Evaluate"><code>float Evaluate(float position)</code></a>_</td><td>Finds the value at a position on the Curve.</td></tr>
</table>
