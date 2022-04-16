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
|\\[int Count { get; }](VRageMath.CurveKeyCollection.Count)|Gets the number of elements contained in the CurveKeyCollection.|
|\\[bool IsReadOnly { get; }](VRageMath.CurveKeyCollection.IsReadOnly)|Returns a value indicating whether the CurveKeyCollection is read-only.|
|\\[CurveKey Item { get; set; }](VRageMath.CurveKeyCollection.Item)||

#### Constructors

|Member|Description|
|---|---|
|\\[CurveKeyCollection()](VRageMath.CurveKeyCollection..ctor)||

#### Methods

|Member|Description|
|---|---|
|\\[void Add(object)](VRageMath.CurveKeyCollection.Add)||
|\\[void Add(CurveKey)](VRageMath.CurveKeyCollection.Add)|Adds a CurveKey to the CurveKeyCollection.|
|\\[void Clear()](VRageMath.CurveKeyCollection.Clear)|Removes all CurveKeys from the CurveKeyCollection.|
|\\[CurveKeyCollection Clone()](VRageMath.CurveKeyCollection.Clone)|Creates a copy of the CurveKeyCollection.|
|\\[bool Contains(CurveKey)](VRageMath.CurveKeyCollection.Contains)|Determines whether the CurveKeyCollection contains a specific CurveKey.|
|\\[void CopyTo(CurveKey\\[], int)](VRageMath.CurveKeyCollection.CopyTo)|Copies the CurveKeys of the CurveKeyCollection to an array, starting at the array index provided.|
|\\[IEnumerator\\<CurveKey> GetEnumerator()](VRageMath.CurveKeyCollection.GetEnumerator)|Returns an enumerator that iterates through the CurveKeyCollection.|
|\\[int IndexOf(CurveKey)](VRageMath.CurveKeyCollection.IndexOf)|Determines the index of a CurveKey in the CurveKeyCollection.|
|\\[bool Remove(CurveKey)](VRageMath.CurveKeyCollection.Remove)|Removes the first occurrence of a specific CurveKey from the CurveKeyCollection.|
|\\[void RemoveAt(int)](VRageMath.CurveKeyCollection.RemoveAt)|Removes the CurveKey at the specified index.|

