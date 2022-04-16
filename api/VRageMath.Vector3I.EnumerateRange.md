← [Index](Api-Index) ← [Namespace Index](Namespace-Index) ← [Vector3I](VRageMath.Vector3I)

### Summary

```csharp
public static IEnumerable<Vector3I> EnumerateRange(Vector3I minInclusive, Vector3I maxExclusive)
```

Enumerate all values in a integer interval (a cuboid). This method is an allocating version of the Vector3I_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.

### Returns

[IEnumerable&lt;Vector3I&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1?view=netframework-4.6)

An iterator for that range.

### Parameters

* [Vector3I](VRageMath.Vector3I) minInclusive
* [Vector3I](VRageMath.Vector3I) maxExclusive
