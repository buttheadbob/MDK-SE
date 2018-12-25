← [Index](Api-Index) ← [MathHelper](VRageMath.MathHelper)

### Summary

```csharp
public float MonotonicCosine(float radians)
```

Calculate the monotonic cosine of a value. Monotonic cosine is an alternative cosine encoding that is monotonic in the [-pi, pi] interval. We use this when some parameter of an onject in a planet is constrained by latitude. The 'monotonicity' is guaranteed by subtracting the cosine value from 2 if the angle is positive. So for instance MonotonicCos(pi/2) = 2. This only works in the above interval of course.

### Returns

The cosine of the angle if it is > 0, 2 - that value otherwise.

### Example

### Remarks

