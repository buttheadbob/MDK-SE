← [Index](Api-Index) ← [DictionaryExtensions](System.Collections.Generic.DictionaryExtensions)

### Summary

```csharp
public TValue GetOrAdd<TKey, TValue, TContext>(ConcurrentDictionary<TKey, TValue> dictionary, TKey key, TContext context, Func<T1, T2, TResult> activator)
```

### Returns

[TValue]()

### Parameters

* [ConcurrentDictionary<TKey, TValue>](https://docs.microsoft.com/en-us/dotnet/api/system.collections.concurrent.concurrentdictionary?view=netframework-4.6) dictionary
* [TKey]() key
* [TContext]() context
* [Func<T1, T2, TResult>](https://docs.microsoft.com/en-us/dotnet/api/system.func?view=netframework-4.6) activator
