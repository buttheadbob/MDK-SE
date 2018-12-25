← [Index](Api-Index) ← [MyDynamicAABBTree](VRageMath.MyDynamicAABBTree)

### Summary

```csharp
private public bool MoveProxy(int proxyId, ref private public sealed struct.BoundingBox aabb, private public sealed struct.Vector3 displacement)
```

Move a proxy with a swepted BoundingBox. If the proxy has moved outside of its fattened BoundingBox, then the proxy is removed from the tree and re-inserted. Otherwise the function returns immediately.

### Returns

true if the proxy was re-inserted.

### Example

### Remarks

