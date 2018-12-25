← [Index](Api-Index) ← [Vector3L](VRageMath.Vector3L)

### Summary

```csharp
public IEnumerable<T> EnumerateRange(Vector3L minInclusive, Vector3L maxExclusive)
```

Enumerate all values in a longeger longerval (a cuboid). This method is an allocating version of the Vector3L_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.

### Returns

[IEnumerable<T>](System.Collections.Generic.IEnumerable`1)

An iterator for that range.

