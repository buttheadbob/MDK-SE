← [Index](Api-Index) ← [Namespace Index](Namespace-Index) ← [ListExtensions](System.Collections.Generic.ListExtensions)

### Summary

```csharp
public static T MaxBy<T>(this IEnumerable source, Func selector)
```

### Returns

[T]()

### Parameters

* [IEnumerable<T>](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1?view=netframework-4.6) source
* [Func<T, System.Single>](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2?view=netframework-4.6) selector
### Summary

```csharp
public static TItem MaxBy<TItem, TKey>(this IEnumerable source, Func selector, [IComparer comparer])
```

### Returns

[TItem]()

### Parameters

* [IEnumerable<TItem>](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1?view=netframework-4.6) source
* [Func<TItem, TKey>](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2?view=netframework-4.6) selector
* [IComparer<TKey>](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IComparer-1?view=netframework-4.6) comparer
