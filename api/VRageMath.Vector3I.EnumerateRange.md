← [Index](Api-Index) ← [Vector3I](VRageMath.Vector3I)

### Summary

```csharp
public public interface IEnumerable<T> EnumerateRange(public sealed struct Vector3I minInclusive, public sealed struct Vector3I maxExclusive)
```

Enumerate all values in a integer interval (a cuboid). This method is an allocating version of the Vector3I_RangeIterator. This once can be used in the foreach syntax though so it's more convenient for debug routines.

### Returns

An iterator for that range.

### Example

### Remarks

