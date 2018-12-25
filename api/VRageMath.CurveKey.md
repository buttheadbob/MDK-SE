← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### CurveKey Class

```csharp
public class CurveKey: IEquatable<T>, IComparable<T>
```

Represents a point in a multi-point curve.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [IEquatable<T>](https://docs.microsoft.com/en-us/dotnet/api/system.iequatable?view=netframework-4.6)  
* [IComparable<T>](https://docs.microsoft.com/en-us/dotnet/api/system.icomparable?view=netframework-4.6)

#### Properties

|Member|Description|
|---|---|
|[Position](VRageMath.CurveKey.Position)|Position of the CurveKey in the curve.|
|[Value](VRageMath.CurveKey.Value)|Describes the value of this point.|
|[TangentIn](VRageMath.CurveKey.TangentIn)|Describes the tangent when approaching this point from the previous point in the curve.|
|[TangentOut](VRageMath.CurveKey.TangentOut)|Describes the tangent when leaving this point to the next point in the curve.|
|[Continuity](VRageMath.CurveKey.Continuity)|Describes whether the segment between this point and the next point in the curve is discrete or continuous.|

#### Methods

|Member|Description|
|---|---|
|[Clone()](VRageMath.CurveKey.Clone)|Creates a copy of the CurveKey.|
|[Equals(CurveKey)](VRageMath.CurveKey.Equals)|Determines whether the specified Object is equal to the CurveKey.|
|[Equals(object)](VRageMath.CurveKey.Equals)|Returns a value that indicates whether the current instance is equal to a specified object.|
|[GetHashCode()](VRageMath.CurveKey.GetHashCode)|Returns the hash code for this instance.|
|[CompareTo(CurveKey)](VRageMath.CurveKey.CompareTo)|Compares this instance to another CurveKey and returns an indication of their relative values.|

