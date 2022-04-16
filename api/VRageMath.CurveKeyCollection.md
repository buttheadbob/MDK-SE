← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### CurveKeyCollection Class

```csharp
public class CurveKeyCollection: ICollection<CurveKey>, IEnumerable<CurveKey>, IEnumerable
```

Contains the CurveKeys making up a Curve.

**Namespace:** [VRageMath](VRageMath)  
**Assembly:** VRage.Math.dll

**Implements:**  
* [ICollection<CurveKey>](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.ICollection-1?view=netframework-4.6)  
* [IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.IEnumerable?view=netframework-4.6)  
* [IEnumerable<CurveKey>](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1?view=netframework-4.6)

#### Properties

|Member|Description|
|---|---|
|\\$1int Count { get; }](VRageMath.CurveKeyCollection.Count)|Gets the number of elements contained in the CurveKeyCollection.|
|\\$1bool IsReadOnly { get; }](VRageMath.CurveKeyCollection.IsReadOnly)|Returns a value indicating whether the CurveKeyCollection is read-only.|
|\\$1CurveKey Item { get; set; }](VRageMath.CurveKeyCollection.Item)||

#### Constructors

|Member|Description|
|---|---|
|\\$1CurveKeyCollection()](VRageMath.CurveKeyCollection..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\$1void Add(object)](VRageMath.CurveKeyCollection.Add)||
|\\$1void Add(CurveKey)](VRageMath.CurveKeyCollection.Add)|Adds a CurveKey to the CurveKeyCollection.|
|\\$1void Clear()](VRageMath.CurveKeyCollection.Clear)|Removes all CurveKeys from the CurveKeyCollection.|
|\\$1CurveKeyCollection Clone()](VRageMath.CurveKeyCollection.Clone)|Creates a copy of the CurveKeyCollection.|
|\\$1bool Contains(CurveKey)](VRageMath.CurveKeyCollection.Contains)|Determines whether the CurveKeyCollection contains a specific CurveKey.|
|\\$1void CopyTo(CurveKey\\$1], int)](VRageMath.CurveKeyCollection.CopyTo)|Copies the CurveKeys of the CurveKeyCollection to an array, starting at the array index provided.|
|\\$1IEnumerator\\$1CurveKey> GetEnumerator()](VRageMath.CurveKeyCollection.GetEnumerator)|Returns an enumerator that iterates through the CurveKeyCollection.|
|\\$1int IndexOf(CurveKey)](VRageMath.CurveKeyCollection.IndexOf)|Determines the index of a CurveKey in the CurveKeyCollection.|
|\\$1bool Remove(CurveKey)](VRageMath.CurveKeyCollection.Remove)|Removes the first occurrence of a specific CurveKey from the CurveKeyCollection.|
|\\$1void RemoveAt(int)](VRageMath.CurveKeyCollection.RemoveAt)|Removes the CurveKey at the specified index.|

