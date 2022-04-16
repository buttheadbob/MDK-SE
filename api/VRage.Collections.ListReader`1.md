← [Index](Api-Index) ← [Namespace Index](Namespace-Index)

#### ListReader&lt;T&gt; Struct

```csharp
public struct ListReader<T>: IEnumerable<T>, IEnumerable, IReadOnlyList<T>, IReadOnlyCollection<T>
```

**Namespace:** [VRage.Collections](VRage.Collections)  
**Assembly:** VRage.Library.dll

**Implements:**  
* [IEnumerable](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.IEnumerable?view=netframework-4.6)  
* [IEnumerable<T>](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1?view=netframework-4.6)  
* [IReadOnlyCollection<T>](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyCollection-1?view=netframework-4.6)  
* [IReadOnlyList<T>](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IReadOnlyList-1?view=netframework-4.6)

#### Fields

|Member|Description|
|---|---|
|[static ListReader<T> Empty](VRage.Collections.ListReader`1.Empty)||

#### Properties

|Member|Description|
|---|---|
|[int Count { get; }](VRage.Collections.ListReader`1.Count)||
|[T Item { get; }](VRage.Collections.ListReader`1.Item)||

#### Constructors

|Member|Description|
|---|---|
|[ListReader(List<T>)](VRage.Collections.ListReader`1..ctor)||

#### Methods

|Member|Description|
|---|---|
|[Enumerator<T> GetEnumerator()](VRage.Collections.ListReader`1.GetEnumerator)||
|[int IndexOf(T)](VRage.Collections.ListReader`1.IndexOf)||
|[T ItemAt(int)](VRage.Collections.ListReader`1.ItemAt)||

