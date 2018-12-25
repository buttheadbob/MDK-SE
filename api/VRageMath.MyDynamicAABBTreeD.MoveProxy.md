← [Index](Api-Index) ← [MyDynamicAABBTreeD](VRageMath.MyDynamicAABBTreeD)

### Summary

```csharp
public bool MoveProxy(int proxyId, ref BoundingBoxD aabb, Vector3D displacement)
```

Move a proxy with a swepted BoundingBox. If the proxy has moved outside of its fattened BoundingBox, then the proxy is removed from the tree and re-inserted. Otherwise the function returns immediately.

### Returns

[bool](System.Boolean)

true if the proxy was re-inserted.

