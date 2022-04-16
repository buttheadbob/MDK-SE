← [Index](Api-Index) ← [Namespace Index](Namespace-Index) ← [ListExtensions](System.Collections.Generic.ListExtensions)

### Summary

```csharp
public static T MaxBy<T>(this IEnumerable<T> source, Func<T, float> selector)
```

### Returns

[T]()

### Parameters

* [IEnumerable&lt;T&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1?view=netframework-4.6) source
* [Func&lt;T, float&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2?view=netframework-4.6) selector
### Summary

```csharp
public static TItem MaxBy<TItem, TKey>(this IEnumerable<TItem> source, Func<TItem, TKey> selector, IComparer<TKey> comparer = default)
```

### Returns

[TItem]()

### Parameters

* [IEnumerable&lt;TItem&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1?view=netframework-4.6) source
* [Func&lt;TItem, TKey&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2?view=netframework-4.6) selector
* [IComparer&lt;TKey&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IComparer-1?view=netframework-4.6) comparer
