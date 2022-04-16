← [Index](Api-Index) ← [Namespace Index](Namespace-Index) ← [ListExtensions](System.Collections.Generic.ListExtensions)

### Summary

```csharp
public static int BinaryIntervalSearch<T>(this IList self, T value, [IComparer comparer])
```

### Returns

[int](https://docs.microsoft.com/en-us/dotnet/api/System.Int32?view=netframework-4.6)

### Parameters

* [IList<T>](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IList-1?view=netframework-4.6) self
* [T]() value
* [IComparer<T>](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IComparer-1?view=netframework-4.6) comparer
### Summary

```csharp
public static int BinaryIntervalSearch<T>(this IList self, Func less)
```

### Returns

[int](https://docs.microsoft.com/en-us/dotnet/api/System.Int32?view=netframework-4.6)

### Parameters

* [IList<T>](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IList-1?view=netframework-4.6) self
* [Func<T, System.Boolean>](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2?view=netframework-4.6) less
### Summary

```csharp
public static int BinaryIntervalSearch<T>(this IList self, T value, Comparison comparison)
```

### Returns

[int](https://docs.microsoft.com/en-us/dotnet/api/System.Int32?view=netframework-4.6)

### Parameters

* [IList<T>](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IList-1?view=netframework-4.6) self
* [T]() value
* [Comparison<T>](https://docs.microsoft.com/en-us/dotnet/api/System.Comparison-1?view=netframework-4.6) comparison
