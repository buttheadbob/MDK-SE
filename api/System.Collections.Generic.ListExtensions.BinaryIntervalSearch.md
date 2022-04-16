← [Index](Api-Index) ← [Namespace Index](Namespace-Index) ← [ListExtensions](System.Collections.Generic.ListExtensions)

### Summary

```csharp
public static int BinaryIntervalSearch<T>(this IList<T> self, T value, IComparer<T> comparer = default)
```

### Returns

[int](https://docs.microsoft.com/en-us/dotnet/api/System.Int32?view=netframework-4.6)

### Parameters

* [IList&lt;T&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IList-1?view=netframework-4.6) self
* [T]() value
* [IComparer&lt;T&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IComparer-1?view=netframework-4.6) comparer
### Summary

```csharp
public static int BinaryIntervalSearch<T>(this IList<T> self, Func<T, bool> less)
```

### Returns

[int](https://docs.microsoft.com/en-us/dotnet/api/System.Int32?view=netframework-4.6)

### Parameters

* [IList&lt;T&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IList-1?view=netframework-4.6) self
* [Func&lt;T, bool&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2?view=netframework-4.6) less
### Summary

```csharp
public static int BinaryIntervalSearch<T>(this IList<T> self, T value, Comparison<T> comparison)
```

### Returns

[int](https://docs.microsoft.com/en-us/dotnet/api/System.Int32?view=netframework-4.6)

### Parameters

* [IList&lt;T&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IList-1?view=netframework-4.6) self
* [T]() value
* Comparison&lt;T&gt; <sub>prohibited</sub> comparison
