← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### CurveKey Class

```csharp
public class CurveKey: IEquatable<CurveKey>, IComparable<CurveKey>
```

Represents a point in a multi-point curve.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IComparable<CurveKey>](https://docs.microsoft.com/en-us/dotnet/api/System.IComparable-1?view=netframework-4.6)  
* [IEquatable<CurveKey>](https://docs.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=netframework-4.6)

#### Properties

|Member|Description|
|---|---|
|\\$1CurveContinuity Continuity { get; set; }](VRageMath.CurveKey.Continuity)|Describes whether the segment between this point and the next point in the curve is discrete or continuous.|
|\\$1float Position { get; }](VRageMath.CurveKey.Position)|Position of the CurveKey in the curve.|
|\\$1float TangentIn { get; set; }](VRageMath.CurveKey.TangentIn)|Describes the tangent when approaching this point from the previous point in the curve.|
|\\$1float TangentOut { get; set; }](VRageMath.CurveKey.TangentOut)|Describes the tangent when leaving this point to the next point in the curve.|
|\\$1float Value { get; set; }](VRageMath.CurveKey.Value)|Describes the value of this point.|

#### Constructors

|Member|Description|
|---|---|
|\\$1CurveKey()](VRageMath.CurveKey..ctor)||
|\\$1CurveKey(float, float)](VRageMath.CurveKey..ctor)||
|\\$1CurveKey(float, float, float, float)](VRageMath.CurveKey..ctor)||
|\\$1CurveKey(float, float, float, float, CurveContinuity)](VRageMath.CurveKey..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\$1CurveKey Clone()](VRageMath.CurveKey.Clone)|Creates a copy of the CurveKey.|
|\\$1int CompareTo(CurveKey)](VRageMath.CurveKey.CompareTo)|Compares this instance to another CurveKey and returns an indication of their relative values.|
|\\$1bool Equals(CurveKey)](VRageMath.CurveKey.Equals)|Determines whether the specified Object is equal to the CurveKey.|
|\\$1bool Equals(object)](VRageMath.CurveKey.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|\\$1int GetHashCode()](VRageMath.CurveKey.GetHashCode)|Returns the hash code for this instance.|

