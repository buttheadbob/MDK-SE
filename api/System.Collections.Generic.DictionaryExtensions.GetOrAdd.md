← [Index](Api-Index) ← [Namespace Index](Namespace-Index) ← [DictionaryExtensions](System.Collections.Generic.DictionaryExtensions)

### Summary

```csharp
public static TValue GetOrAdd<TKey, TValue, TContext>(this ConcurrentDictionary dictionary, TKey key, TContext context, Func activator)
```

### Returns

[TValue]()

### Parameters

* [ConcurrentDictionary<TKey, TValue>](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Concurrent.ConcurrentDictionary-2?view=netframework-4.6) dictionary
* [TKey]() key
* [TContext]() context
* [Func<TContext, TKey, TValue>](https://docs.microsoft.com/en-us/dotnet/api/System.Func-3?view=netframework-4.6) activator
