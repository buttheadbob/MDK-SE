← [Index](Api-Index) ← [Vector3I](VRageMath.Vector3I)

### Summary

```csharp
public IEnumerable<T> EnumerateRange(Vector3I minInclusive, Vector3I maxExclusive)
```

Enumerate all values in a integer interval (a cuboid). This method is an allocating version of the Vector3I_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.

### Returns

[IEnumerable<T>](System.Collections.Generic.IEnumerable`1)

An iterator for that range.

