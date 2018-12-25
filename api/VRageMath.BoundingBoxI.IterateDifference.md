← [Index](Api-Index) ← [BoundingBoxI](VRageMath.BoundingBoxI)

### Summary

```csharp
public IEnumerable<T> IterateDifference(BoundingBoxI left, BoundingBoxI right)
```

Iterate every cell contained in {left} - {right}, where we interpret {box} as the set of all distinct Vector3I points inside a 'box'. Containment is taken in a typical inclusive start, exclusive end fashion.

### Returns

[IEnumerable<T>](System.Collections.Generic.IEnumerable`1)



